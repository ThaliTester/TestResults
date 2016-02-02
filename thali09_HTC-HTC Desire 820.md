#### Test 575312431f256a6_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  913): Recipient 3681
--------- beginning of /dev/log/main
D/SMSBackup( 3910): Got a database change event
D/DFPI.PIReciver( 3663): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3663): onHandleIntent
I/DFPI.ApkInstallService( 3663): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3663): check CID = HTC__032
I/DFPI.ApkInstallService( 3663): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  913): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  913): Resuming delayed broadcast
I/ActivityManager(  913): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,E/cutils-trace( 3926): Error opening trace file: No such file or directory (2)
V/AlarmManager(  913): sending alarm PendingIntent{42389ac8: PendingIntentRecord{424081d0 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1454433942232, Int=0
I/SocialManager[SocialBiLogHelper]( 3706): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 3706): last commit ulog time 1454392527077
I/SocialManager[SocialBiLogHelper]( 3706): skip commit this time
I/Prism.ItemManager( 1277): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1277): loadItems() com.htc.launcher.pageview.WidgetManager@41b5dc38 +
I/Prism.WidgetManager( 1277): onLoadItems() +
W/PackageManager(  913): Unable to load service info ResolveInfo{42616228 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  913): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  913): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  913): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  913): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  913): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  913): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  913): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  913): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  913): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  913): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  913): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  913): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  913): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  913): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  913): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  913): 	at dalvik.system.NativeStart.main(Native Method)
I/Prism.ItemManager( 3706): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 3706): loadItems() com.htc.launcher.pageview.WidgetManager@41b3db58 +
I/Prism.WidgetManager( 3706): onLoadItems() +
D/CustomizationManager( 3926): ====startRecUseTime====
D/htc.customization.log.level( 3926):  is 
W/CustomizationLogLevel( 3926): Level value is invalid, use default level 2
D/CustomizationManager( 3926):  Read ACC file spent 0.084 (s)
D/CIDMapFileReader( 3926): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3926): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3926): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3926): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3926): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3926): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3926): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3926): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3926): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3926): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3926): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3926): Parsing tag category name = system
I/CustomizationCIDLoader( 3926): Parsing tag category name = application
I/CustomizationCIDLoader( 3926): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3926): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3926): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3926): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3926): Parsing tag category name = Settings
D/CustomizationManager( 3926):  Read CID file spent 0.136 (s)
D/CustomizationManager( 3926):  All configurations done spent 0.137 (s)
W/HtcNativeFlag( 3926): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3926): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3926): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3926): Fail to get flag for type 'language', use default value: -1
I/ActivityManager(  913): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3926
D/RemoteDisplayProvider(  913): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  913): start
I/GCoreNlp( 1230): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/LocationProviderProxy(  913): applying state to connected service
D/PMS     (  913): acquireWL(424360b8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): releaseWL(424360b8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/LocationProviderProxy(  913): applying state to connected service
D/PMS     (  913): acquireWL(4262da60): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): releaseWL(4262da60): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): acquireWL(425f3628): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): releaseWL(425f3628): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
E/Prism.WidgetManager( 1277): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1277): onLoadItems() -
I/Prism.ItemManager( 1277): loadItems() com.htc.launcher.pageview.WidgetManager@41b5dc38 -
I/ActivityManager(  913): Resuming delayed broadcast
D/Process (  913): killProcessQuiet, pid=3694
D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Killing 3694:com.htc.stock:remote/u0a82 (adj 15): empty #17
I/SoundPicker( 3879): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
W/ContextImpl( 3879): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
I/SoundPicker( 3879): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3879): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3879): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3879): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3879): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3879): MODE_GSM access default DB
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3879): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3879): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3879): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3879): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3879): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3879): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3879): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3879): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3879): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3879): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3879): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3879): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3879): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3879): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3879): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3879): MODE_GSM access default DB
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/ActivityManager(  913): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/ActivityManager(  913): Recipient 3694
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/SoundPicker( 3879): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3879): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3879): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3879): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3879): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3879): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3879): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3879): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
I/SoundPicker( 3879): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
,I/Prism.WidgetManager( 3706): onLoadItems() -
I/Prism.ItemManager( 3706): loadItems() com.htc.launcher.pageview.WidgetManager@41b3db58 -
,I/SoundPicker( 3879): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
,I/SoundPicker( 3879): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
,I/SoundPicker( 3879): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
,I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3879): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  913): Resuming delayed broadcast
,I/ActivityManager(  913): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  913):    returned true
D/PhoneApp( 1250): EVENT_QUERY_MO_PACKAGES
D/PhoneApp( 1250): -- N1 =0
D/PhoneApp( 1250): -- N2 =0
D/PhoneApp( 1250): -- N3 =0
V/AlarmManager(  913): sending alarm PendingIntent{41c5cc28: PendingIntentRecord{424c5fb8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=60153, Int=0
I/ActivityManager(  913): Resuming delayed broadcast
I/ActivityManager(  913): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/ActivityManager(  913): Resuming delayed broadcast
I/ActivityManager(  913): Delay finish: com.htc.task/.TodoTaskReceiver
I/ActivityManager(  913): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=3944 uid=10064 gids={50064, 3003, 5012, 1023, 1028, 1015}
I/HtcModeClient( 1546): handler message = 4011
E/HtcModeClient( 1546): Check connection and retry 6 times.
D/DFPI.PIReciver( 3663): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  913): Resuming delayed broadcast
I/DFPI.ApkInstallService( 3663): onHandleIntent
I/DFPI.ApkInstallService( 3663): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3663): check CID = HTC__032
I/DFPI.ApkInstallService( 3663): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  913): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  913): Resuming delayed broadcast
I/EASAppSvc( 3944): [ NA ]- onCreate()
I/ActivityManager(  913): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
I/EASAppSvc( 3944): [ NA ]> onUpgrade: version = 63
D/ORMLib  ( 3610): put()
I/EASAppSvc( 3944): [ NA ]- onDestroy()
I/EASAppSvc( 3944): [ NA ]> uninitEASService
D/WifiService(  913): New client listening to asynchronous messages
D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.htc.android.mail (3944/10064)
D/ConnectivityService(  913): getNetworkInfo networkType=0 called by com.htc.android.mail (3944/10064)
D/ConnectivityService(  913): getNetworkInfo networkType=55 called by com.htc.android.mail (3944/10064)
,I/EASRequestController( 3944): [ NA ]release
,I/EASAppSvc( 3944): [ NA ]< uninitEASService
,I/EASAppSvc( 3944): [ NA ]- onCreate()
,I/EASAppSvc( 3944): [ NA ]> onUpgrade: version = 63
,D/Process (  913): killProcessQuiet, pid=3724,
D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.htc.android.mail (3944/10064)
,I/ActivityManager(  913): Killing 3724:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/ConnectivityService(  913): getNetworkInfo networkType=0 called by com.htc.android.mail (3944/10064)
D/ConnectivityService(  913): getNetworkInfo networkType=55 called by com.htc.android.mail (3944/10064)
,D/ORMLib  ( 3610): put()
I/ActivityManager(  913): Recipient 3724
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/EASAppSvc( 3944): [ NA ]- onDestroy()
,I/EASAppSvc( 3944): [ NA ]> uninitEASService
,I/EASRequestController( 3944): [ NA ]release
,I/EASAppSvc( 3944): [ NA ]< uninitEASService
,I/ActivityManager(  913): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=3983 uid=10068 gids={50068, 3003, 5012}
,D/Process (  913): killProcessQuiet, pid=3738
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Killing 3738:com.htc.mobiledata/u0a91 (adj 15): empty #17
,I/ActivityManager(  913): Recipient 3738
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ORMLib  ( 3610): put()
,I/ActivityManager(  913): Resuming delayed broadcast
,I/ActivityManager(  913): Killing 3545:com.google.android.apps.plus/u0a160 (adj 15): empty #17
D/Process (  913): killProcessQuiet, pid=3545
D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/SoundPicker( 3879): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
W/ContextImpl( 3879): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3879): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 3879): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3879): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3879): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3879): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3879): MODE_GSM access default DB
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3879): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3879): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3879): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3879): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3879): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3879): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3879): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3879): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3879): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3879): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3879): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3879): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3879): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3879): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3879): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3879): MODE_GSM access default DB
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
,I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/ActivityManager(  913): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3879): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3879): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3879): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3879): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3879): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3879): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3879): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3879): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
I/SoundPicker( 3879): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
I/SoundPicker( 3879): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lil,ac.flac
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
I/SoundPicker( 3879): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
,I/SoundPicker( 3879): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
,I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3879): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  913): Resuming delayed broadcast
I/ActivityManager(  913): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,D/WIFI_ICON( 1121): WifiActivity: 0
,D/StatusBar.NetworkController( 1121): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/ActivityManager(  913): Recipient 3545
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/MediaStoreImporter( 3837): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  913): Resuming delayed broadcast
I/ActivityManager(  913): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  913): Resuming delayed broadcast
,I/ActivityManager(  913): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,D/DFPI.PIReciver( 3663): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  913): Resuming delayed broadcast
I/DFPI.ApkInstallService( 3663): onHandleIntent
,I/DFPI.ApkInstallService( 3663): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3663): check CID = HTC__032
,I/DFPI.ApkInstallService( 3663): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  913): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  913): Resuming delayed broadcast
,I/ActivityManager(  913): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,D/PMS     (  913): acquireWL(425d7760): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(425d7760): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1121): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1121): closing low battery warning: level=100
,D/PowerUI ( 1121): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1601): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  913): << updateStatus
,D/WIFI_ICON( 1121): WifiActivity: 1
,I/BatteryController( 1121): status:5 level:100 unsupport:false plugged:true
D/StatusBar.NetworkController( 1121): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,V/AlarmManager(  913): sending alarm PendingIntent{426a4fe8: PendingIntentRecord{426d8c18 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1454433945618, Int=0
,I/ActivityManager(  913): Waited long enough for: ServiceRecord{41db5380 u0 com.google.android.gms/.gcm.GcmService}
,I/ActivityManager(  913): Resuming delayed broadcast
,I/SoundPicker( 3879): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3879): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3879): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3879): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3879): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3879): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3879): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3879): MODE_GSM access default DB
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3879): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
,D/RingtoneManager( 3879): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3879): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3879): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3879): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3879): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3879): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3879): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3879): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3879): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3879): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3879): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3879): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3879): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3879): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3879): MODE_GSM access default DB
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
,I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/ActivityManager(  913): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3879): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3879): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3879): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3879): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3879): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3879): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3879): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3879): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
,I/SoundPicker( 3879): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
,I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
,I/SoundPicker( 3879): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
,I/SoundPicker( 3879): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
,I/SoundPicker( 3879): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3879): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
,I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3879): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3879): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  913): Resuming delayed broadcast
,I/ActivityManager(  913): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/MediaStoreImporter( 3837): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  913): Resuming delayed broadcast
D/PMS     (  913): acquireWL(427ec320): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1546 10014 null
I/ActivityManager(  913): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,D/PMS     (  913): releaseWL(427ec320): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,D/TelephonyReceiver( 1250): bind: false
,D/TelephonyReceiver( 1250): switchBindHtcMsgCursor: null
I/ActivityManager(  913): Resuming delayed broadcast
,I/ActivityManager(  913): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=4007 uid=10085 gids={50085, 3003, 5012, 1028, 1015, 1023, 2001, 5006, 5001}
,D/PMS     (  913): acquireWL(426ed068): PARTIAL_WAKE_LOCK  NetworkStats 0x1 913 1000 null
,D/WifiDataStallTracker(  913): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  913): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/PMS     (  913): releaseWL(426ed068): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/WifiDataStallTracker(  913): updateDataStallInfo: mDataStallTxRxSum={txSum=42 rxSum=32} preTxRxSum={txSum=0 rxSum=0}
,D/WifiDataStallTracker(  913): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  913): onDataStallAlarm: tag=21280 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  913): startDataStallAlarm: tag=21281 delay=15s
,I/ActivityManager(  913): Start proc com.google.android.gm for broadcast com.google.android.gm/.MailIntentReceiver: pid=4023 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  913):    returned true
D/WifiStateMachine(  913): [ScoreAP] + current TXpacket:69, mTXpacketCount:36, avgLinkspeed:72,mAvgTxRate72
D/WifiStateMachine(  913): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
D/PMS     (  913): acquireWL(42604fc8): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): releaseWL(42604fc8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,W/GAV2    ( 4023): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  913): Delay finish: com.google.android.gm/.MailIntentReceiver
,D/PMS     (  913): acquireWL(42483f58): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(42483f58): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(423e17b8): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1601): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
D/NotificationService(  913): notification sound not played, stream=5 volume=0 always=false
,I/RemoteViews( 1121): com.htc.updater (true,33751552)
,D/OnDemandProgressBar( 1121): release indeterminate drawable android.widget.OnDemandProgressBar{41c1bc90 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1121): com.htc.updater 2 9 1 10
,D/Process (  913): killProcessQuiet, pid=3756
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  913): releaseWL(423e17b8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  913): Resuming delayed broadcast
,I/ActivityManager(  913): Killing 3756:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
I/RemoteViews( 1121): com.htc.updater (true,33751552)
,D/OnDemandProgressBar( 1121): release indeterminate drawable android.widget.OnDemandProgressBar{41acdcd0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1121): com.htc.updater 1 8 1 10
I/[PluginManager]RegisterService( 1321): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.aurora
,I/[PluginManager]RegisterService( 1321): handle notify Blinkfeed plugin client changed
I/ActivityManager(  913): Recipient 3756
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  913): Client connection lost with reason: 4
I/ActivityManager(  913): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  913): Resuming delayed broadcast
,I/IcingCorporaProvider( 2836): Updating corpora: APPS=com.htc.aurora, CONTACTS=MAYBE
I/ActivityManager(  913): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/ActivityManager(  913): Resuming delayed broadcast
,I/Gmail   ( 4023): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/Process (  913): killProcessQuiet, pid=3779
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4055 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,I/ActivityManager(  913): Killing 3779:com.android.settings/1000 (adj 15): empty #17
,I/Gmail   ( 4023): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/ActivityManager(  913): Recipient 3779
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Gmail   ( 4023): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 4023): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/PMS     (  913): acquireWL(425ac900): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  913): releaseWL(425ac900): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(425fe4e0): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(425fe4e0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(424330f0): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  913): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  913): releaseWL(424330f0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(4265ed10): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(426d23d0): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 4055 10160 null
,D/PMS     (  913): acquireWL(426215a8): PARTIAL_WAKE_LOCK  AsyncService 0x1 4055 10160 null
,D/PMS     (  913): releaseWL(426215a8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  913): acquireWL(428219a0): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 4055 10160 null
,D/PMS     (  913): releaseWL(426d23d0): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  913): releaseWL(4265ed10): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.apps.plus (4055/10160)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.apps.plus (4055/10160)
D/PMS     (  913): acquireWL(424dfdf0): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  913): releaseWL(428219a0): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,D/Process (  913): killProcessQuiet, pid=3798
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Killing 3798:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,D/PMS     (  913): releaseWL(424dfdf0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  913): Recipient 3798
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  913): Resuming delayed broadcast
,I/ActivityManager(  913): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=4081 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/PMS     (  913): acquireWL(4286e690): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(4286e690): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(425e2ab0): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(425e2ab0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/HtcFingerPrintQuickLaunchProvider( 4081): -onCreate()
D/PMS     (  913): acquireWL(425ed6b8): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(425ed6b8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
V/Settings:HtcSettingsApplication( 4081): [4081/4081] onCreate()
,I/ActivityManager(  913): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4098 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,D/Process (  913): killProcessQuiet, pid=3594
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  913): Killing 3594:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
D/PMS     (  913): acquireWL(423f4bf8): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(423f4bf8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(427cf7d0): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(427cf7d0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/SensorManager(  913): mEventCount = 450
,I/IcingCorporaProvider( 2836): UpdateCorporaTask done [took 399 ms] updated apps [took 399 ms] 
,W/dalvikvm( 4098): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,I/PackageManager(  913):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4098, uid=10074, userID:0
,D/Finsky  ( 4098): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Settings:HtcWirelessFeatureFlags( 4081): id/is att sku: 99/false
D/ConnectivityService(  913): getAllNetworkInfo called by com.android.vending (4098/10074)
,W/SystemReader( 4081): Cannot find devicepolicy_lower_fp_quality, use default value instead
,I/ActivityManager(  913): Recipient 3594
,W/SystemReader( 4081): Cannot find support_harman, use default value instead
,W/SystemReader( 4081): Cannot find effect_manager_id, use default value instead
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/Settings:HtcWrapHeaderInfo( 4081): no such activity!
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4081): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 4081): updateDevelopment, bPrefShow = true
,W/dalvikvm( 4098): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,W/dalvikvm( 4098): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,E/Settings:HtcUmcWidgetEnabler( 4081): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4081): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4081): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4081): [supportRecentAppsButton]support         :false
,D/ConnectivityService(  913): getAllNetworkInfo called by com.android.vending (4098/10074)
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4081): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4081): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4081): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4081): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4081): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4081): [supportHomeButton]support         :false
,W/FingerprintManager( 4081): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
,D/Finsky  ( 4098): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/dalvikvm( 4098): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,E/Settings:HtcVoWifiWidgetEnabler( 4081): isSupportVoWifi: null
,W/Settings( 4098): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4098): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/ActivityManager(  913): Cannot resolve ContentProvider=com.htc.vowifi
,E/ActivityThread( 4081): Failed to find provider info for com.htc.vowifi
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4081): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 4081): updateDevelopment, bPrefShow = true
E/Settings:HtcUmcWidgetEnabler( 4081): isSupportMusicChannel(): false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4081): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4081): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4081): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4081): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4081): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4081): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4081): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4081): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4081): [supportHomeButton]support         :false
,W/FingerprintManager( 4081): hasFingerprint() - sSensorCode = 0
E/Settings:HtcVoWifiWidgetEnabler( 4081): isSupportVoWifi: null
,W/dalvikvm( 4098): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
W/dalvikvm( 4098): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4098): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
I/ActivityManager(  913): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 4081): Failed to find provider info for com.htc.vowifi
,W/dalvikvm( 4098): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  913):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4098, uid=10074, userID:0
,D/Ads     ( 4098): Skipping gmscore version check
,D/Finsky  ( 4098): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4098): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 4098): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/dalvikvm( 4098): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/Finsky  ( 4098): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/Process (  913): killProcessQuiet, pid=2157
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Killing 2157:com.htc.sense.mms/u0a65 (adj 15): empty #17
,D/PackageBroadcastService( 2183): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.aurora
,I/ActivityManager(  913): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver: pid=4136 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,D/PMS     (  913): acquireWL(42715e08): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  913): Recipient 2157
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Babel   ( 4136): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4136): MmsConfig.loadMmsSettings
W/dalvikvm( 2183): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,W/dalvikvm( 2183): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 2183): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,W/dalvikvm( 2183): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 2183): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
W/dalvikvm( 2183): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
,W/dalvikvm( 2183): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
,W/dalvikvm( 4136): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2183, uid=10029, userID:0
W/dalvikvm( 4136): VFY: unable to resolve instance field 36
W/dalvikvm( 4136): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4136): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4136, uid=10111, userID:0
,W/Settings( 4136): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  913): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4164 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4136, uid=10111, userID:0
I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4136, uid=10111, userID:0
I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4136, uid=10111, userID:0
I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4136, uid=10111, userID:0
I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4136, uid=10111, userID:0
,D/PMS     (  913): acquireWL(426e13b0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4136 10111 null
,I/ActivityManager(  913): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/MessageFrequencyProvider( 4164): onCreate
,V/GetPrviateResource( 4164): GetPrviateResource
,V/GetPrviateResource( 4164): GetPrviateResource
,D/MmsCustomizationProvider( 4164): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 4164): query uri: content://htc-mms-customization/mms-ua/ua_profile
,D/Process (  913): killProcessQuiet, pid=3895
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  913): Killing 3895:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
,I/Babel   ( 4136): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4136): MmsConfig.loadFromDatabase
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  913): Recipient 3895
,E/Babel   ( 4136): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4136): MmsConfig.loadFromResources
,E/Babel   ( 4136): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4136): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/ProviderInstaller( 4136): Installed default security provider GmsCore_OpenSSL
,I/PeopleDatabaseHelper( 2183): cleanUpNonGplusAccounts done.
,D/MessageCustFlag( 4164): sense_version=6.0
,D/BTAccessoryUtil( 4164): createReceiver
,D/BTAccessoryUtil( 4164): registerReceiver return intent = null
D/MessageCustFlag( 4164): sku_id=99
,W/SystemReader( 4164): Cannot find message_ambs_application_id, use default value instead
,D/Messaging( 4164): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4164): networkCode: 
,D/MessageCustFlag( 4164): sku_id=99
D/MmsConfig( 4164): SIE smsPri: null
,D/MmsConfig( 4164): networkCode: 
,D/HtcTelephonyCapability( 4164): traditional single GSM/CDMA/World-phone
D/HtcTelephonyCapability( 4164): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 4164): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4164): Cannot find qct_8960_interface, use default value instead
D/PMS     (  913): releaseWL(426e13b0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
I/ActivityManager(  913): Resuming delayed broadcast
,D/PMS     (  913): acquireWL(426fa8f8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4136 10111 null
,I/ActivityManager(  913): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/PMS     (  913): releaseWL(426fa8f8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  913): Resuming delayed broadcast
,D/Process (  913): killProcessQuiet, pid=3910
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Killing 3910:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,D/PMS     (  913): acquireWL(426d15a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1370/10029)
,I/ActivityManager(  913): Recipient 3910
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024953
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025530
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025645
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025649
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025672
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025675
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027107
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027118
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029589
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360030814
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  913): releaseWL(426d15a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  913): acquireWL(426b3f80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1370/10029)
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024953
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025530
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025645
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025649
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025672
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025675
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027107
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027118
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029589
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360030814
D/PMS     (  913): releaseWL(426b3f80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/GCM     ( 1370): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  913): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
,W/GCoreFlp( 1230): No location to return for getLastLocation()
,W/FusedLocationProvider( 1230): location=null
D/PMS     (  913): acquireWL(42680380): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): acquireWL(4267ffc8): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): releaseWL(42680380): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024953
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025530
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025645
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025649
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025672
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025675
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027107
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027118
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029589
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360030814
,V/AlarmManager(  913): sending alarm PendingIntent{42387098: PendingIntentRecord{4237f1a0 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1454433947389, Int=0
,D/PMS     (  913): releaseWL(4267ffc8): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  913): Resuming delayed broadcast
,V/AlarmManager(  913): sending alarm PendingIntent{42434350: PendingIntentRecord{426e5ea8 com.google.android.apps.plus startService}}, i=null, t=0, cnt=1, w=1454433947443, Int=0
,D/PMS     (  913): acquireWL(42401708): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,I/iu.UploadsManager( 2183): End new media; added: 0, uploading: 0, time: 69 ms
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1370/10029)
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024953
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025530
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025645
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025649
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025672
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025675
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027107
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027118
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029589
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360030814
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/PMS     (  913): releaseWL(42401708): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(42551530): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1370/10029)
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024953
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025530
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025645
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025649
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025672
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025675
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027107
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027118
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029589
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360030814
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  913): releaseWL(42551530): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): acquireWL(422bf370): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1370/10029)
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024953
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025530
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025645
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025649
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025672
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025675
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027107
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027118
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029589
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360030814
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  913): releaseWL(422bf370): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/PMS     (  913): acquireWL(42469e58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1370/10029)
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024953
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025530
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025645
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025649
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025672
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025675
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027107
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027118
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029589
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360030814
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  913): releaseWL(42469e58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/PMS     (  913): acquireWL(423fe848): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  913): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent: pid=4202 uid=10041 gids={50041}
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1370/10029)
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024953
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025530
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025645
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025649
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025672
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025675
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027107
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027118
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029589
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360030814
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/PMS     (  913): releaseWL(423fe848): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(4252af80): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4136 10111 null
,I/ActivityManager(  913): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/PMS     (  913): releaseWL(4252af80): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  913): Resuming delayed broadcast
,D/ConnectivityService(  913): Sampling interval elapsed, updating statistics ..
,I/ActivityManager(  913): Killing 3706:com.htc.sense.news/u0a76 (adj 15): empty #17
D/Process (  913): killProcessQuiet, pid=3706
D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/ConnectivityService(  913): Done.
,D/ConnectivityService(  913): Setting timer for 720seconds
,D/WearableService( 1230): callingUid 10029, callindPid: 1230
,D/LocationInitializer( 2183): Restart initialization of location
,D/AuthorizationBluetoothService( 1370): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 1370): Proximity feature is not enabled.
,E/MDM     ( 1230): [109] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  913): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
D/PMS     (  913): acquireWL(4259f5f0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  913): Resuming delayed broadcast
W/GCoreFlp( 1230): No location to return for getLastLocation()
,W/FusedLocationProvider( 1230): location=null
D/PMS     (  913): releaseWL(4259f5f0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  913): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024953
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025530
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025645
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025649
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025672
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025675
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027107
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027118
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029589
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360030814
I/ActivityManager(  913): Resuming delayed broadcast
D/PMS     (  913): acquireWL(42623858): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3610 10071 null
D/PMS     (  913): acquireWL(42565878): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3610 10071 null
D/PMS     (  913): releaseWL(42623858): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
E/TodoTaskNotifyService( 3610): java.lang.NullPointerException
W/System.err( 3610): java.lang.NullPointerException
W/System.err( 3610): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3610): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
,W/System.err( 3610): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3610): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3610): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 3610): stopSelfResult true
D/PMS     (  913): acquireWL(426994e8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3610 10071 null
I/ActivityManager(  913): Delay finish: com.htc.task/.notification.NotifyReceiver
D/PMS     (  913): acquireWL(42565878): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3610 10071 null
D/PMS     (  913): releaseWL(426994e8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  913): releaseWL(42565878): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  913): Resuming delayed broadcast
E/TodoTaskNotifyService( 3610): java.lang.NullPointerException
,W/System.err( 3610): java.lang.NullPointerException
W/System.err( 3610): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3610): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3610): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3610): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3610): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  913): acquireWL(42560a80): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3610 10071 null
D/PMS     (  913): acquireWL(42612ba8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3610 10071 null
I/ActivityManager(  913): Delay finish: com.htc.launcher/.receiver.NotificationReceiver
D/PMS     (  913): releaseWL(42560a80): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,W/NotifyReceiver( 3610): stopSelfResult true
D/PMS     (  913): releaseWL(42612ba8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  913): Resuming delayed broadcast
,D/GCM     ( 1370): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
I/ActivityManager(  913): Recipient 3706
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WSP     ( 1321): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
D/WeatherUtility( 1321): Weather sync is On
,I/WSP     ( 1321): [Receiver] next auto-sync alarm event is 60 mins later, at time: Tue Feb 02 19:25:47 CET 2016
D/ConnectivityService(  913): getActiveNetworkInfo called by com.htc.sense.hsp (1321/10055)
I/ActivityManager(  913): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
D/ConnectivityService(  913): getActiveNetworkInfo called by com.htc.sense.hsp (1321/10055)
D/PMS     (  913): acquireWL(42630b80): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 1321 10055 null
,I/Icing   ( 2183): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,W/MediaManager( 3817): [DualLensScanUtil]	mmpCursor count is 0
,I/Icing   ( 2183): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/PMS     (  913): releaseWL(42715e08): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  913): Resuming delayed broadcast
D/PMS     (  913): acquireWL(4262a578): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4136 10111 null
I/ActivityManager(  913): Delay finish: com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver
,D/PMS     (  913): releaseWL(4262a578): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  913): Resuming delayed broadcast
,I/[PluginManager]RegisterService( 1321): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1321): handle notify Blinkfeed plugin client changed
I/ActivityManager(  913): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  913): Resuming delayed broadcast
,I/IcingCorporaProvider( 2836): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  913): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/PMS     (  913): acquireWL(42366ae8): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(42366ae8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(4263dcf8): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(4263dcf8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(426e7710): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(426e7710): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(426c68d8): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(426c68d8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(426a4808): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(426a4808): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(426c8e90): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(426c8e90): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(4267d1d8): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(4267d1d8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(426e4af8): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(426e4af8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(42650710): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(42650710): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2836): UpdateCorporaTask done [took 354 ms] updated apps [took 354 ms] 
I/ActivityManager(  913): Resuming delayed broadcast
,I/ActivityManager(  913): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
D/PMS     (  913): acquireWL(42824058): PARTIAL_WAKE_LOCK  AsyncService 0x1 4055 10160 null
D/PMS     (  913): releaseWL(42824058): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  913): Resuming delayed broadcast
,D/PackageBroadcastService( 2183): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2183): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  913): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,D/PMS     (  913): acquireWL(427205d0): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
I/Icing   ( 2183): updateResources: need to parse f{com.google.android.gms}
,W/SQLiteConnectionPool( 2183): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/HtcModeClient( 1546): handler message = 4011
,E/HtcModeClient( 1546): Check connection and retry 7 times.
,W/MediaManager( 3817): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  913): Resuming delayed broadcast
D/PMS     (  913): acquireWL(427131a0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 913 1000 null
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
D/PMS     (  913): acquireWL(42705928): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 913 1000 null
I/ActivityManager(  913): Delay finish: com.htc.task/.TodoReceiver
D/PMS     (  913): releaseWL(427131a0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  913): releaseWL(42705928): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/TodoTaskshortcut( 3610): update TASK shortcut>
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  913):    returned true
,D/Messaging( 4164): mNeedToUpdateDate2 start
,D/MmsConfig( 4164): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4164): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4164): 
D/MmsAsyncWorkHandler( 4164): HM tk = 20001
D/ReportIndicatorCache( 4164): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4164): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41ad2488
,I/Messaging( 4164): mccmnc> 
,D/TelephUtils( 1250): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/MmsSmsV2Provider( 1250):  phoneType = -1
,D/MmsSmsV2Provider( 1250): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/DraftCache( 4164): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4164): [DraftCache/1] refresh
,D/MmsConfig( 4164): networkCode: 
,D/Messaging( 4164): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1250): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/MmsSmsV2Provider( 1250):  phoneType = -1
,D/MmsSmsV2Provider( 1250): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/PhoneStorageUtil( 4164): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4164): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/Messaging( 4164): mNeedToUpdateDate2: false
,D/PhoneStorageUtil( 4164): createReceiver
,D/MessageCustFlag( 4164): sense_version=6.0
,D/Jerry   ( 4164): start to preload cursor >>>>>>>
D/TelephUtils( 1250): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
,V/MmsProvider( 1250): Update uri=content://mms, match=0
,V/MmsProvider( 1250): selection=st=129 AND m_type!=134
,D/Messaging( 4164): Reset downloading state: 0
V/MmsSystemEventReceiver( 4164): TransactionService is going to be woken up.
,D/TelephUtils( 1250): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/MmsSmsV2Provider( 1250):  phoneType = -1
I/ActivityManager(  913): Delaying start of: ServiceRecord{4261ad70 u0 com.htc.sense.mms/.transaction.TransactionService}
,D/Messaging( 4164): ViewCache CreatePreload
,D/Messaging( 4164): ViewCache CreatePreloadOnlyMultipleOpsList
,D/Cust_MMSMS( 4164): _has_set_default_values_2=true
,D/MsgPreferenceUtils( 4164): def_index: 0
,D/MsgPreferenceUtils( 4164): globalIndex = 1
D/MsgPreferenceUtils( 4164): phone state: true
D/MsgPreferenceUtils( 4164): sd state: false
,D/MsgPreferenceUtils( 4164): vIndex = 0
,D/TelephUtils( 1250): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/MmsSmsV2Provider( 1250):  phoneType = -1
,D/MmsSmsV2Provider( 1250): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/TelephUtils( 1250): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/AccFlag ( 1250): sku_id=99
,D/DraftCache( 4164): [DraftCache/415] rebuildCache
,D/TelephUtils( 1250): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/MmsSmsV2Provider( 1250):  phoneType = -1
,D/MmsSmsV2Provider( 1250): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 4164): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/TelephUtils( 1250): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/Jerry   ( 1250): URI_DRAFT
,D/DraftCache( 4164): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 4164): [DraftCache/415] rebuildCache time: 1
,D/MmsAsyncWorkHandler( 4164): 
D/MmsAsyncWorkHandler( 4164): HM tk = 20002
D/TelephUtils( 1250): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1250): sku_id=99
,D/TelephUtils( 1250): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/AccFlag ( 1250): sku_id=99
,I/Icing   ( 2183): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,D/Icing   ( 2183): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 2183): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  913): releaseWL(427205d0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=2183, uid=10029, userID:0
,I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=2183, uid=10029, userID:0
,I/CheckinService( 2183): Done disabling old GoogleServicesFramework version
I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=2183, uid=10029, userID:0
,I/GAV2    ( 4023): Thread[GAThread,5,main]: No campaign data found.
,I/GAV4    ( 4136): Thread[GAThread,5,main]: No campaign data found.
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  913):    returned true
,I/HtcModeClient( 1546): handler message = 4011
,E/HtcModeClient( 1546): Check connection and retry 8 times.
,I/CalendarProvider2( 1546): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1546): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,V/TransactionService( 4164): 1-Creating TransactionService
,V/TransactionService( 4164): onStartCommand: 1
,D/MmsSystemEventReceiver( 4164): unRegisterForConnectionStateChanges
V/TransactionService( 4164): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4164): Loading previous transactions.
,D/TelephUtils( 1250): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
,D/AccFlag ( 1250): device_type: 1
,D/TransactionService( 4164): Force set service start id to 1
V/TransactionService( 4164): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4164): unRegisterForConnectionStateChanges
,V/TransactionService( 4164): Destroying TransactionService
,D/TransactionService( 4164): stopSelfResult: true, mLastHandledServiceId: 1
I/ActivityManager(  913): Resuming delayed broadcast
,V/TransactionService( 4164): 4-Handling incoming message: { when=-7ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
I/ActivityManager(  913): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,W/MediaManager( 3817): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  913): Resuming delayed broadcast
,D/PMS     (  913): acquireWL(425e5638): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 3837 10154 null
,I/ActivityManager(  913): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,W/ContextImpl( 3837): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=3837, uid=10154, userID:0
,I/MusicLeanback( 3837): Conditions not met for autocaching.
,I/MusicLeanback( 3837): Stop autocaching.
D/PMS     (  913): releaseWL(425e5638): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,I/ActivityManager(  913): Resuming delayed broadcast
W/ContextImpl( 3837): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/ActivityManager(  913): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4280 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/SyncApplication( 4280): Loading default preferences
,W/Resources( 4280): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/SyncApplication( 4280): Overriding preferences with custom values
,D/SyncApplication( 4280): Updating preferences succeeded
,E/SyncApplication( 4280): Application created.
D/VolumeInfo( 4280): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 4280): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 4280): Found 0 mount point(s)
,V/VolumeInfo( 4280): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 4280): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,I/CalendarDefines( 4280): getNewCalendarAuthority()...
,D/VolumeInfo( 4280): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
,W/VolumeInfo( 4280): Can not create volume ID for unmounted volume null
,D/SyncApplication( 4280): enableAppOperation()+
,D/SyncApplication( 4280): enableAppOperation()-
,D/HTCUtilities( 4280): isNeorSinged() + 
I/PackageManager(  913):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4280, uid=10008, userID:0
W/PackageManager(  913): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  913):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4280, uid=10008, userID:0
W/PackageManager(  913): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 4280): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 4280): isNeorSinged() return false
,D/CDMountReceiver( 4280): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 4280): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/CDMountReceiver( 4280): enable CD Auto-mount: true
,D/HTCUtilities( 4280): enable auto-mount
D/DotMatrix( 1601): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,D/HTCUtilities( 4280): enable auto-mount
,I/RemoteViews( 1121): com.nero.android.htc.sync (false,0)
I/ActivityManager(  913): Delay finish: com.nero.android.htc.sync/.CDMountReceiver
D/MountService(  913): mountISO: /system/etc/PCTOOL.ISO
D/MountService(  913): mountISO: /system/etc/PCTOOL.ISO
,D/OnDemandProgressBar( 1121): release indeterminate drawable android.widget.OnDemandProgressBar{41ac1ca8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress},
I/ActivityManager(  913): Resuming delayed broadcast
D/PMS     (  913): releaseWL(426c71f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10008}
I/ActivityManager(  913): Delay finish: com.google.android.gm/.MailIntentReceiver
I/RemoteViews.Performance( 1121): com.nero.android.htc.sync 3 11 4 11
,I/RemoteViews( 1121): com.nero.android.htc.sync (false,0)
,D/OnDemandProgressBar( 1121): release indeterminate drawable android.widget.OnDemandProgressBar{41c7d518 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/ActivityManager(  913): Resuming delayed broadcast
,I/RemoteViews.Performance( 1121): com.nero.android.htc.sync 0 7 2 16
D/WifiService(  913): New client listening to asynchronous messages
,I/ActivityManager(  913): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,W/MediaManager( 3817): [DualLensScanUtil]	mmpCursor count is 0
,D/Process (  913): killProcessQuiet, pid=3557
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Resuming delayed broadcast
I/ActivityManager(  913): Killing 3557:com.google.android.gms.unstable/u0a29 (adj 15): empty #17
,D/PMS     (  913): acquireWL(42700ce0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1370/10029)
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024953
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025530
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025645
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025649
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025672
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025675
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027107
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027118
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029589
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360030814
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  913): releaseWL(42700ce0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/PMS     (  913): acquireWL(426ed068): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1370/10029)
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024953
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025530
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025645
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025649
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025672
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025675
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027107
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027118
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029589
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360030814
,D/PMS     (  913): releaseWL(426ed068): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  913): Recipient 3557
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/PMS     (  913): acquireWL(4202f808): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1370/10029)
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  913): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=4305 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024953
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025530
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025645
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025649
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025672
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025675
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027107
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027118
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029589
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360030814
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  913): releaseWL(4202f808): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/CalendarApplication( 4305): onCreate
D/ProviderChangeReceiver( 4305): ---------------------------------------------------
,D/ProviderChangeReceiver( 4305): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 4305): start to updateAlertNotification!
,I/ActivityManager(  913): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4319 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  913): killProcessQuiet, pid=3944
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  913): Killing 3944:com.htc.android.mail:sync/u0a64 (adj 15): empty #17
,D/AlertService( 4305): No fired or scheduled alerts
,D/HtcAlertUtils( 4305): -- cancelReminderNotification --
,D/HtcAlertUtils( 4305): broadcastExistReminder!
,D/DotMatrix( 1601): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/ActivityManager(  913): Recipient 3944
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  913): Client connection lost with reason: 4
,V/Settings:HtcSettingsApplication( 4319): [4319/4319] onCreate()
W/ContextImpl( 4319): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  913): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
,I/ActivityManager(  913): Resuming delayed broadcast
,D/Process (  913): killProcessQuiet, pid=3983
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  913): Killing 3983:com.htc.task.gtask/u0a68 (adj 15): empty #17
,I/ActivityManager(  913): Recipient 3983
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  913): Waited long enough for: ServiceRecord{426684b8 u0 com.htc.musicenhancer/.EnhancerService}
,D/PMS     (  913): acquireWL(4252b040): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(4252b040): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1121): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1601): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/PowerUI ( 1121): closing low battery warning: level=100
D/PowerUI ( 1121): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1121): status:5 level:100 unsupport:false plugged:true
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  913):    returned true
,I/SensorManager(  913): mEventCount = 600
,D/WIFI_ICON( 1121): WifiActivity: 0
,D/StatusBar.NetworkController( 1121): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1121): WifiActivity: 1
,D/StatusBar.NetworkController( 1121): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  913): releaseWL(42630b80): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  913):    returned true
,I/HtcModeClient( 1546): handler message = 4011
,E/HtcModeClient( 1546): Check connection and retry 9 times.
,D/PMS     (  913): acquireWL(42439488): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41f42c70: PendingIntentRecord{41f2f068 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=77026, Int=0
I/IntentController( 1121): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(42439488): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Finsky  ( 4098): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/dalvikvm( 4098): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
D/PMS     (  913): acquireWL(425db200): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{10074}
V/AlarmManager(  913): sending alarm PendingIntent{4264de40: PendingIntentRecord{426e05e8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454433960132, Int=0
D/PMS     (  913): releaseWL(425db200): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.android.vending (4098/10074)
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4098): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4098): [NET] getaddrinfo-,err=8
D/libc    ( 4098): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 4098): [NET] getaddrinfo-, 1
D/libc    ( 4098): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =75ac +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4098): [NET] getaddrinfo_proxy-, success
I/global  ( 4098): call createSocket() return a new socket.
D/libc    ( 4098): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4098): [NET] getaddrinfo-, SUCCESS
,I/ClockThread( 1121): now=1454433960324 next=59676
,D/libc    ( 4098): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4098): [NET] getaddrinfo-,err=8
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4098): untagSocket(69) failed with errno -22
,D/Finsky  ( 4098): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,D/WIFI_ICON( 1121): WifiActivity: 3
,D/StatusBar.NetworkController( 1121): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4098): untagSocket(69) failed with errno -22
,D/PMS     (  913): acquireWL(42360e68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
D/WifiDataStallTracker(  913): onReceive: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  913): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  913): updateDataStallInfo: mDataStallTxRxSum={txSum=62 rxSum=48} preTxRxSum={txSum=42 rxSum=32}
D/WifiDataStallTracker(  913): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  913): onDataStallAlarm: tag=21281 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  913): startDataStallAlarm: tag=21282 delay=15s
V/AlarmManager(  913): sending alarm PendingIntent{42581320: PendingIntentRecord{42400fc8 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=78009, Int=0
D/PMS     (  913): releaseWL(42360e68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=5 [20][1][0]
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  913):    returned true
D/WifiStateMachine(  913): [ScoreAP] + current TXpacket:90, mTXpacketCount:69, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  913): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4098): untagSocket(69) failed with errno -22
,D/Finsky  ( 4098): [1] MultiWayUpdateController.collateResponses: Change varies-by-account for com.google.android.apps.magazines to false
,D/Finsky  ( 4098): [1] MultiWayUpdateController.collateResponses: Change auto-acquire tags for com.google.android.apps.magazines from d_AAAAAAADF8w= to 
,D/ConnectivityService(  913): getNetworkInfo networkType=0 called by com.android.vending (4098/10074)
,D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.android.vending (4098/10074)
,D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.android.vending (4098/10074)
,D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.android.vending (4098/10074)
,D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.android.vending (4098/10074)
,D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.android.vending (4098/10074)
,D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.android.vending (4098/10074)
,D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.android.vending (4098/10074)
,D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.android.vending (4098/10074)
,D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.android.vending (4098/10074)
,D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.android.vending (4098/10074)
,D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.android.vending (4098/10074)
,D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.android.vending (4098/10074)
,D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.android.vending (4098/10074)
,D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.android.vending (4098/10074)
,D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.android.vending (4098/10074)
,D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.android.vending (4098/10074)
,D/Finsky  ( 4098): [1] DailyHygiene.access$600: Logging device features
,D/PMS     (  913): acquireWL(42726890): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{10074}
,V/AlarmManager(  913): sending alarm PendingIntent{42501e50: PendingIntentRecord{4265e678 com.android.vending broadcastIntent}}, i=null, t=0, cnt=1, w=1454433962133, Int=0
,D/WearableService( 1230): callingUid 10029, callindPid: 1230
,D/Finsky  ( 4098): [438] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/DeviceConnectionService( 1230): client connected with version: 8296000
D/PMS     (  913): acquireWL(426d8460): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 4098 10074 null
D/PMS     (  913): releaseWL(42726890): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/Finsky  ( 4098): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 4098): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4098): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4098): [NET] getaddrinfo-,err=8
D/libc    ( 4098): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4098): [NET] getaddrinfo-, 1
,D/libc    ( 4098): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =47e5 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  364): [NET]res_nsend:resplen=87
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4098): [NET] getaddrinfo_proxy-, success
,D/PMS     (  913): releaseWL(426d8460): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 null
,I/HtcModeClient( 1546): handler message = 4011
,E/HtcModeClient( 1546): Check connection and retry 10 times.
,D/WIFI_ICON( 1121): WifiActivity: 0
,D/StatusBar.NetworkController( 1121): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=13 [52][7][0]
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  913):    returned true
,D/WIFI_ICON( 1121): WifiActivity: 1
,D/StatusBar.NetworkController( 1121): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/AutoSetting( 1321): service - mHandler: update timezone
,D/AutoSetting( 1321): service - handleMessage() stop self
,D/AutoSetting( 1321): service - handleMessage() quit looper
,D/AutoSetting( 1321): service - onDestroy() END
,D/Process (  913): killProcessQuiet, pid=3663
,I/ActivityManager(  913): Killing 3663:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/AutoSetting( 1546): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1546): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1546): service - onCreate()
W/ActivityManager(  913): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  913): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1546): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1546): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/AutoSetting( 1546): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1546): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1546): service - mHandler: update timezone
,D/AutoSetting( 1546): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1546): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1546): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1546): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1601): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1601): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1121): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1121): release indeterminate drawable android.widget.OnDemandProgressBar{41ee9d90 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1121): com.htc.htclocationservice 1 7 2 11
,I/ActivityManager(  913): Recipient 3663
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WIFI_ICON( 1121): WifiActivity: 0
,D/StatusBar.NetworkController( 1121): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  913):    returned true
,I/SensorManager(  913): mEventCount = 750
,D/ContactMessageStore( 1250): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1250): MSG_NOTIFY_CS_TO_SYNC <<
,D/WIFI_ICON( 1121): WifiActivity: 1
,D/StatusBar.NetworkController( 1121): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/HtcModeClient( 1546): handler message = 4011
,E/HtcModeClient( 1546): Check connection and retry 11 times.
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  913):    returned true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl(  913): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  913):    returned true
,I/HtcModeClient( 1546): handler message = 4011
,E/HtcModeClient( 1546): Check connection and retry 12 times.
,D/PMS     (  913): acquireWL(4269d570): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,D/WifiDataStallTracker(  913): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  913): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
V/AlarmManager(  913): sending alarm PendingIntent{42651cc8: PendingIntentRecord{42400fc8 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=93012, Int=0
,D/WifiDataStallTracker(  913): updateDataStallInfo: mDataStallTxRxSum={txSum=113 rxSum=96} preTxRxSum={txSum=62 rxSum=48}
D/WifiDataStallTracker(  913): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  913): onDataStallAlarm: tag=21282 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  913): startDataStallAlarm: tag=21283 delay=15s
D/PMS     (  913): releaseWL(4269d570): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  913): acquireWL(4269e898): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(4269e898): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(426333c8): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(426333c8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(427fdc20): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(427fdc20): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  913):    returned true
,D/WifiStateMachine(  913): [ScoreAP] + current TXpacket:150, mTXpacketCount:90, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  913): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,I/HtcModeClient( 1546): handler message = 4011
,E/HtcModeClient( 1546): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1546): Don't start project servcice
,D/HtcModeClient( 1546): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1546): connectState: CONNECTION_READY = false
D/SilentMusic( 1546): call stop
D/HtcModeClient( 1546): close connection
,W/HtcModeClient( 1546): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1546): read the terminate packet, so break
,D/PMS     (  913): acquireWL(42674c00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{10074}
,V/AlarmManager(  913): sending alarm PendingIntent{426b68d8: PendingIntentRecord{423a8fa8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454433976434, Int=0
,I/ActivityManager(  913): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4351 uid=10078 gids={50078}
,V/AlarmManager(  913): sending alarm PendingIntent{425a8990: PendingIntentRecord{42522458 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454433979289, Int=60000
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  913): releaseWL(42674c00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  913):    returned true
,D/SMSBackup( 4351): SMSBackupAgentService started
,D/SMSBackup( 4351): Checking restore status
D/SMSBackup( 4351): Restore complete
,D/SMSBackup( 4351): cancelCheckAlarm
,D/SMSBackup( 4351): SMSBackupAgentService completed: completed in 0.0 seconds
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024953
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025530
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025645
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025649
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025672
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025675
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027107
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027118
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029589
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360030814
,D/Finsky  ( 4098): [428] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4098): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/Process (  913): killProcessQuiet, pid=3879
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Killing 3879:com.htc.sdm/u0a81 (adj 15): empty #17
,I/ActivityManager(  913): Recipient 3879
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  913): Waited long enough for: ServiceRecord{42703308 u0 com.htc.htclocationservice/.AutoSettingService}
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97,
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0,
D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  913):    returned true,
,D/WIFI_ICON( 1121): WifiActivity: 0
,D/StatusBar.NetworkController( 1121): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1121): WifiActivity: 1
,D/StatusBar.NetworkController( 1121): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,V/LightsService(  913): setLight #0: color=#25
,V/LightsService(  913): setLight #0: color=#22
,V/LightsService(  913): setLight #0: color=#1b
,V/LightsService(  913): setLight #0: color=#15
,V/LightsService(  913): setLight #0: color=#14
,D/WIFI_ICON( 1121): WifiActivity: 0
,D/StatusBar.NetworkController( 1121): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  913):    returned true
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  913):    returned true
,I/PMS     (  913): Going to sleep due to screen timeout...
,I/SensorManager(  913): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421cce40
,W/SensorService(  913): Following SensorService logs are not warning, just make sure they are printed
D/WirelessDisplayService(  913): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  913): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,W/SensorService(  913): disable: get sensor name = CM36282 Light sensor
,W/SensorService(  913): pid=913, uid=1000
,W/SensorService(  913): Active sensors: size = 2
W/SensorService(  913): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
,W/SensorService(  913): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  913): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421cce40, eanble = 0, strlen(mName) = 59
W/SensorService(  913): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  913): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41f78978
W/SensorService(  913): Listener[1] = com.htc.smartdim.sensor_eye@426bc7a0
,W/SensorService(  913): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/PMS     (  913): mWirelessDisplayManager is null
W/BatSI   (  913): Couldn't get kernel wake lock stats
V/LightsService(  913): setLight #2: color=#0
D/qdlights(  913): set_light_buttons_func: on=0 brightness=0
V/LightsService(  913): setLight #0: color=#0
,D/WifiDataStallTracker(  913): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  913): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  913): updateDataStallInfo: mDataStallTxRxSum={txSum=113 rxSum=96} preTxRxSum={txSum=113 rxSum=96}
D/WifiDataStallTracker(  913): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  913): onDataStallAlarm: tag=21283 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  913): startDataStallAlarm: tag=21284 delay=15s
D/PMS     (  913): acquireWL(42877028): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
V/AlarmManager(  913): sending alarm PendingIntent{422244c0: PendingIntentRecord{42400fc8 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=108032, Int=0
D/PMS     (  913): releaseWL(42877028): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/SurfaceControl(  913): Excessive delay in blankDisplay() while turning screen off: 341ms
,W/PnPMgr  (  357): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
D/PMS     (  913): nativeSetInteractive:false
D/PMS     (  913): nativeSetInteractive:false done
D/PMS     (  913): nativeSetAutoSuspend:true
D/PMS     (  913): nativeSetAutoSuspend:true done
D/HABCtrl (  913): TPE algorithm. remove timeout.
D/PMS     (  913): OOBE c monitor 11
I/InputManager(  913): Cancel all due to getting PMS screen off broadcast
D/NfcService( 1262): ScreenObserver: OFF
,D/NfcService( 1262): applyRouting - 0
D/NfcService( 1262): applyRouting -2
,I/IntentController( 1121): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,V/KeyguardServiceDelegate(  913): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@427d4090)
I/InputMethodManagerService(  913): screenObserver, isScreenOn=false
D/PMS     (  913): acquireWL(427d3158): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1262 1027 null
D/PMS     (  913): releaseWL(427d3158): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/InputMethodManagerService(  913): Disable input method client, pid=1277
D/PMN     (  913): wakingUp
,D/PMS     (  913): acquireWL(427d5388): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,V/KeyguardServiceDelegate(  913): **** SHOWN CALLED ****
W/XT9_C   ( 1217): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1217): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1217): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1217): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/BatteryService(  913): n_update end
D/AlarmManager(  913): ACTION_SCREEN_ON
D/PMS     (  913): releaseWL(427d5388): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/AlarmManager(  913): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  913): [AlarmQueuing] done recovering
I/AlarmManager(  913): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  913): [AlarmQueuing] done EPS screen off alarm recovering
I/WindowManager(  913): No lock screen! windowToken=null
D/WirelessDisplayService(  913): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  913): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  913): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,I/IntentController( 1121): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMN     (  913): onScreenOn
,D/HtcPowerSaver(  913): updateBatteryInfo
D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiDataStallTracker(  913): onReceive: action=android.intent.action.SCREEN_ON
,D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1601): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiDataStallTracker(  913): startDataStallAlarm: tag=21285 delay=15s
D/MtpService( 2731): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2731): [MTP][onReceive]-
,D/NfcService( 1262): applyRouting - 0
D/PowerUI ( 1121): closing low battery warning: level=100
D/PowerUI ( 1121): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024953
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025530
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025645
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025649
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025672
D/PMS     (  913): acquireWL(428623b0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1262 1027 null
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025675
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027107
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027118
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029589
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360030814
D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  913): BroadcastReceiver::onReceive-
,D/NfcService( 1262): applyRouting -2
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
D/PMS     (  913): releaseWL(428623b0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  913): << updateStatus
,V/NotificationService(  913): batLight: Full, plugged,
V/LightsService(  913): setLight #8: color=#c8c800
D/WirelessDisplayService(  913): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  913): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  913): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiNative-wlan0(  913): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1165): SET_SCREEN_ON:On
I/wpa_supplicant( 1165): htc_wext_set_keepalive +
,I/wpa_supplicant( 1165): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1165): getPrivFuncNum +	
I/wpa_supplicant( 1165): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1165): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1165): htc_wext_set_keepalive - ret = 0,
I/ClockThread( 1121): stop update clock
I/wpa_supplicant( 1165): htc_wext_set_TX_TRACKING (1)+,
I/wpa_supplicant( 1165): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
D/WifiNative-wlan0(  913):    returned true,
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/qdlights(  913): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
,D/qdlights(  913): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  913): setLight #8: color=#c800
D/qdlights(  913): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  913): [LedInfo] has indicator attribute
D/qdlights(  913): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  913): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
I/ActivityManager(  913): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4372 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
V/NotificationService(  913): batLight: Full, plugged
V/LightsService(  913): setLight #8: color=#c8c800
D/qdlights(  913): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  913): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  913): setLight #8: color=#c800
D/qdlights(  913): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  913): [LedInfo] has indicator attribute
V/SRS_Proc(  372): ParamSet string: screen_state=on
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50,
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WirelessDisplayService(  913): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  913):    returned true
D/qdlights(  913): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  913): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/NetworkPolicy(  913): updateScreenOn: false
I/BatteryController( 1121): status:5 level:100 unsupport:false plugged:true
D/WifiStateMachine(  913): [ScoreAP] + current TXpacket:150, mTXpacketCount:150, avgLinkspeed:72,mAvgTxRate72
D/WifiStateMachine(  913): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,I/SensorManager(  913): mEventCount = 900
,W/ContextImpl( 4372): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4372): isEpsOn(), nState = 0
,W/ContextImpl(  913): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/SmartSyncUtils( 4372): getMobilePolicyEnabled, result = true
D/AutoSetting( 1321): receiver - intent: android.intent.action.USER_PRESENT
,D/AutoSetting( 1321): service - onCreate()
,D/AutoSetting( 1321): service - AddressCache: using context: com.htc.Weather
,D/AutoSetting( 1321): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/LocationManagerService(  913): request 42475998 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/LocationManagerService(  913): provider request: passive ProviderRequest[ON interval=0]
D/TetherSettings( 4081): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4081): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4081): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4081): Cust_ConnectToPC   : spcsc>false
D/        ( 4081): Cust_ConnectToPC   : IPT>true
,D/        ( 4081): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 4081): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4081): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 4081): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4081): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 4081): onReceive:android.intent.action.USER_PRESENT
W/ContextImpl( 4081): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/SmartNS_PSService( 4081): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4081): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4081):  defaultType:0
,D/PMS     (  913): acquireWL(4280b298): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(42894258): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4372 1000 null
,D/DotMatrix( 1601): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  913): releaseWL(4280b298): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(4285d9e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(42894258): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1787): onScreenOn: false
,D/PMS     (  913): releaseWL(4285d9e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1787): onScreenOn: 1454433991394
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1787): onScreenOn: 1454433991394
,I/SensorManager(  913): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41f78978
W/SensorService(  913): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  913): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  913): pid=913, uid=1000
W/SensorService(  913): Active sensors: size = 2
W/SensorService(  913): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  913): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  913): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41f78978, eanble = 0, strlen(mName) = 91
W/SensorService(  913): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  913): Listener[0] = com.htc.smartdim.sensor_eye@426bc7a0
,W/SensorService(  913): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  913): goingToSleep
D/PMS     (  913): acquireWL(4285d0f8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 913 1000 null
,I/FeedHostManager( 1277): [onPause]
,I/FeedProviderManager( 1277): onPause
,I/SocialFeedProvider( 1277): +onPause
,I/SocialFeedProvider( 1277): -onPause
,I/FeedHostManager( 1277): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c34e08
D/WifiDataStallTracker(  913): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  913): stopDataStallAlarm: current tag=21285 mDataStallAlarmIntent=PendingIntent{424b40c8: PendingIntentRecord{42400fc8 android broadcastIntent}}
D/AlarmManager(  913): ACTION_SCREEN_OFF
I/AlarmManager(  913): [AlarmQueuing] screen off now: 
I/AlarmManager(  913): [AlarmQueuing] data connection: true
I/AlarmManager(  913): [AlarmQueuing] wifi connection: true
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024953
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025530
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025645
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025649
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025672
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025675
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027107
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027118
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029589
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360030814
D/WifiNative-wlan0(  913): doBoolean: DRIVER SETSUSPENDMODE 1
D/WifiNative-wlan0(  913): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  913): acquireWL(4285c3d8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 913 1000 null
D/PMS     (  913): releaseWL(4285d0f8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,W/ContextImpl( 4372): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4372): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4372): isEpsOn(), nState = 0
D/SmartSyncUtils( 4372): getMobilePolicyEnabled, result = true
,D/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  913):    returned true
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1165): SET_SCREEN_ON:Off
I/wpa_supplicant( 1165): htc_wext_set_keepalive +
I/wpa_supplicant( 1165): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1165): getPrivFuncNum +	
I/wpa_supplicant( 1165): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1165): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1165): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1165): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1165): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  913):    returned true
D/PMS     (  913): releaseWL(4285c3d8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/WifiService(  913): New client listening to asynchronous messages
I/SensorManager(  913): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@426bc7a0
W/SensorService(  913): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  913): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  913): pid=913, uid=1000
W/SensorService(  913): Active sensors: size = 1
W/SensorService(  913): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  913): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@426bc7a0, eanble = 0, strlen(mName) = 36
W/SensorService(  913): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  913): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  913): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  913): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  913): pid=913, uid=1000
W/SensorService(  913): Active sensors: size = 0
W/SensorService(  913): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@426bc7a0, eanble = 0, strlen(mName) = 36
W/SensorService(  913): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  913): void android::SensorService::listenerSensor(const char*, int32_t)--:,
,I/SensorManager(  913): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@426bc7a0
W/ContextImpl(  913): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,V/SRS_Proc(  372): ParamSet string: screen_state=off
E/ActivityThread(  913): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@426bcc30 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  913): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@426bcc30 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  913): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  913): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  913): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  913): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  913): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  913): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  913): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  913): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  913): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  913): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  913): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  913): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  913): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  913): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  913): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  913): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  913): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  913): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  913): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  913): 	at dalvik.system.NativeStart.main(Native Method)
D/NetworkPolicy(  913): updateScreenOn: false
D/ContactMessageStore( 1250): start background delete task...
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/ContactMessageStore( 1250): size: 0 , 0
,D/ContactMessageStore( 1250): Background delete complete
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,I/PhoneStatusBar( 1121): removeHeadsNotification.gc: 54
,D/PMS     (  913): acquireWL(428129d8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(428129d8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1601): [EventService] getTotalRam: 1873 Mb
,D/PMS     (  913): acquireWL(4280b6d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(4280b6d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1787): onScreenOff.
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1787): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1787): disableBatteryAlarm
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1787): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1787): onScreenOff
,D/AutoSetting( 1321): service - mHandler: cancel location update
,D/AutoSetting( 1321): service -           changes count: 0
,D/AutoSetting( 1546): service - handleMessage() stop self
,D/AutoSetting( 1546): service - onDestroy() END
,D/AutoSetting( 1546): service - handleMessage() quit looper
,D/Process (  913): killProcessQuiet, pid=4007
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Killing 4007:com.htc.updater/u0a85 (adj 15): empty #17
,I/ActivityManager(  913): Recipient 4007
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ContactMessageStore( 1250): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1250): MSG_NOTIFY_CS_TO_SYNC <<
,D/Process (  913): killProcessQuiet, pid=3860
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Killing 3860:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  913): Recipient 3860
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  913): Waited long enough for: ServiceRecord{427bb450 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  913): acquireWL(427f0468): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  913): sending alarm PendingIntent{42088d18: PendingIntentRecord{42418d30 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=124544, Int=0
,D/PMS     (  913): releaseWL(427f0468): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(427e8d78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1370/10029)
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/PMS     (  913): acquireWL(427e7cb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(427e7cb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(427e8d78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(427e7838): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024953
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025530
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025645
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025649
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025672
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025675
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027107
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027118
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029589
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360030814
,D/PMS     (  913): releaseWL(427e7838): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(427e6768): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1370/10029)
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024953
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025530
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025645
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025649
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025672
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025675
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027107
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027118
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029589
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360030814
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/PMS     (  913): acquireWL(42686728): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(425e6748): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1230): Vacuum at: now=1454434007820 tag=VacuumService
,D/PMS     (  913): releaseWL(427e6768): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(42686728): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(423d1690): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(425e6748): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024953
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025530
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025645
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025649
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025672
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025675
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027107
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027118
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029589
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360030814
,D/PMS     (  913): releaseWL(423d1690): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(425f4800): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1370/10029)
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024953
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025530
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025645
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025649
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025672
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025675
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027107
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027118
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029589
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360030814
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/PMS     (  913): releaseWL(425f4800): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(420c3a18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024953
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025530
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025645
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025649
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025672
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025675
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027107
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027118
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029589
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360030814
,D/PMS     (  913): releaseWL(420c3a18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(41fe8510): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms},
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1370/10029)
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024953
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025530
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025645
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025649
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025672
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025675
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027107
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027118
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029589
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360030814
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/PMS     (  913): releaseWL(41fe8510): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(41fc7070): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1370/10029)
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024953
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025530
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025645
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025649
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025672
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025675
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027107
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027118
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029589
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360030814
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/PMS     (  913): acquireWL(42661510): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(42661510): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(427f24c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(41fc7070): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(426f1a28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024953
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025530
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025645
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025649
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025672
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025675
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027107
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027118
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029589
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360030814
,D/PMS     (  913): releaseWL(426f1a28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1230/10029)
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1230/10029)
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1230/10029)
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1230): Scheduling Phenotype for one-off execution 10736 seconds from now (1454434008751)
,D/GetConfigurationSnapshotOperation( 1230): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1230): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1230): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1230): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1230): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1230): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1230): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  913): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1230/10029)
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1230/10029)
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/libc    ( 1230): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1230): [NET] getaddrinfo-,err=8
,D/libc    ( 1230): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1230): [NET] getaddrinfo-, 1
,D/libc    ( 1230): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =1118 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/libc    ( 1230): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1230): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1230): [NET] getaddrinfo-,err=8
D/libc    ( 1230): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1230): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  913): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1230/10029)
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=10 [10][1][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1230/10029)
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  913): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1230/10029)
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1230/10029)
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/PMS     (  913): releaseWL(427f24c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(428629d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024953
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025530
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025645
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025649
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025672
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025675
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027107
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027118
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029589
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360030814
,D/PMS     (  913): releaseWL(428629d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(426b0eb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1370/10029)
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024953
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025530
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025645
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025649
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025672
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025675
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027107
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027118
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029589
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360030814
,D/PMS     (  913): releaseWL(426b0eb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(424eeaf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PowerUI ( 1121): closing low battery warning: level=100
,I/IntentController( 1121): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/PowerUI ( 1121): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1601): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  913): releaseWL(424eeaf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1121): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  913): acquireWL(425cf850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41f42c70: PendingIntentRecord{41f2f068 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=137026, Int=0
,I/IntentController( 1121): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(425cf850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(4264cef8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  913): sending alarm PendingIntent{4250ce68: PendingIntentRecord{426ba7c8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=138670, Int=0
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1370/10029)
,D/PMS     (  913): releaseWL(4264cef8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1321): service - handleMessage() stop self
,D/AutoSetting( 1321): service - handleMessage() quit looper
,D/AutoSetting( 1321): service - onDestroy() END
,D/Process (  913): killProcessQuiet, pid=4202
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Killing 4202:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
,I/ActivityManager(  913): Recipient 4202
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  913): acquireWL(4263ab00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{424bd4f0: PendingIntentRecord{424bd490 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=142931, Int=0
,D/GpsLocationProvider(  913): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  913): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  913): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  913): acquireWL(42651568): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 913 1000 null
D/PMS     (  913): releaseWL(4263ab00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  913): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  913): [NET] getaddrinfo-,err=8
D/libc    (  913): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  913): [NET] getaddrinfo-, 1
,D/libc    (  913): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =792 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE,
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  364): [NET]res_nsend:resplen=238
D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  913): [NET] getaddrinfo_proxy-, success
I/global  (  913): call createSocket() return a new socket.
D/libc    (  913): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  913): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  913): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  913): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  913): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  913):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  913): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  913): releaseWL(42651568): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  913): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  913): acquireWL(42634a78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(42634a78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
,D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
,I/IntentController( 1121): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1601): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1121): closing low battery warning: level=100
D/PowerUI ( 1121): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1121): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  913): acquireWL(4265f840): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{10027}
,V/AlarmManager(  913): sending alarm PendingIntent{42418c80: PendingIntentRecord{426f9fd8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=173012, Int=0
,D/PMS     (  913): releaseWL(4265f840): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/TelephonyReceiver( 1250): switchBindHtcMsgCursor: null
,D/PMS     (  913): acquireWL(42838af0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(42838af0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  913): acquireWL(426f4ce0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41f42c70: PendingIntentRecord{41f2f068 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=197026, Int=0
,I/IntentController( 1121): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(426f4ce0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(42678748): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(42678748): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/IntentController( 1121): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1601): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1121): closing low battery warning: level=100
D/PowerUI ( 1121): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1121): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  913): acquireWL(42850098): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
,I/IntentController( 1121): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  913): releaseWL(42850098): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
,I/HtcPowerSaver(  913): >> updateStatus
D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1601): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1121): closing low battery warning: level=100
D/PowerUI ( 1121): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1121): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  913): acquireWL(4269d930): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41f42c70: PendingIntentRecord{41f2f068 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=257026, Int=0
,I/IntentController( 1121): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(4269d930): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  913): acquireWL(42864010): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
,D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/PMS     (  913): releaseWL(42864010): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  913): BroadcastReceiver::onReceive-,
,I/IntentController( 1121): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1601): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
D/PowerUI ( 1121): closing low battery warning: level=100
D/PowerUI ( 1121): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1121): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  913): acquireWL(426ea088): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(426ea088): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  913): updateBatteryInfo
D/PowerUI ( 1121): closing low battery warning: level=100
,I/IntentController( 1121): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  913): BroadcastReceiver::onReceive+
,D/PowerUI ( 1121): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1601): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1121): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  913): acquireWL(426807b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41f42c70: PendingIntentRecord{41f2f068 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=317026, Int=0
,I/IntentController( 1121): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(426807b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  913): killProcessQuiet, pid=4136
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Killing 4136:com.google.android.talk/u0a111 (adj 15): empty #17
,I/ActivityManager(  913): Recipient 4136
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  913): acquireWL(427ef1b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,I/IntentController( 1121): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1601): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1121): closing low battery warning: level=100
D/PowerUI ( 1121): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
D/PMS     (  913): releaseWL(427ef1b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1121): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  913): acquireWL(42865230): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(42865230): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
,I/IntentController( 1121): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1601): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
D/PowerUI ( 1121): closing low battery warning: level=100
D/PowerUI ( 1121): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1121): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  913): acquireWL(4270eff8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41f42c70: PendingIntentRecord{41f2f068 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=377026, Int=0
,I/IntentController( 1121): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(4270eff8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  913): acquireWL(42810548): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(42810548): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  913): acquireWL(426871d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(426871d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  913): updateBatteryInfo
D/PowerUI ( 1121): closing low battery warning: level=100
D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1601): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
,I/IntentController( 1121): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1121): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1121): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  913): acquireWL(427152c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41f42c70: PendingIntentRecord{41f2f068 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=437026, Int=0
,I/IntentController( 1121): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(427152c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  913): acquireWL(428368c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(428368c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
,D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  913): updateBatteryInfo
I/IntentController( 1121): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1601): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/PowerUI ( 1121): closing low battery warning: level=100
D/PowerUI ( 1121): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1121): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  913): acquireWL(426ffe80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(426ffe80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  913): updateBatteryInfo
D/PowerUI ( 1121): closing low battery warning: level=100
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
,I/IntentController( 1121): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1601): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1121): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1121): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  913): acquireWL(4286c318): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41f42c70: PendingIntentRecord{41f2f068 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=497026, Int=0
,I/IntentController( 1121): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(4286c318): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  913): acquireWL(42805fb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(42805fb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/IntentController( 1121): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1601): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1121): closing low battery warning: level=100
D/PowerUI ( 1121): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1121): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  913): acquireWL(4277d160): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(4277d160): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  913): acquireWL(4277e1d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41f42c70: PendingIntentRecord{41f2f068 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=557026, Int=0
,I/IntentController( 1121): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(4277e1d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(42780500): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(42780500): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1121): closing low battery warning: level=100
,D/PowerUI ( 1121): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1121): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  913): updateBatteryInfo
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
,D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1601): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1121): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory),
,D/PMS     (  913): acquireWL(42785938): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41f42c70: PendingIntentRecord{41f2f068 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=617026, Int=0
,I/IntentController( 1121): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(42785938): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ContactMessageStore( 1250): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1250): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1250): sku_id=99
D/ContactMessageStore( 1250): start background delete task...
,D/ContactMessageStore( 1250): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1250): size: 0 , 0
,D/ContactMessageStore( 1250): Background delete complete
,D/PMS     (  913): acquireWL(42789c50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
,D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
,I/IntentController( 1121): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1601): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1121): closing low battery warning: level=100
D/HtcPowerSaver(  913): updateBatteryInfo
D/PowerUI ( 1121): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  913): releaseWL(42789c50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1121): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  913): acquireWL(4278f410): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41f42c70: PendingIntentRecord{41f2f068 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=677026, Int=0
,I/IntentController( 1121): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(4278f410): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(42791d00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(42791d00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
,D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/IntentController( 1121): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1601): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1121): closing low battery warning: level=100
I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
D/PowerUI ( 1121): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1121): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  913): acquireWL(42797520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(42797520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  913): acquireWL(42798598): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41f42c70: PendingIntentRecord{41f2f068 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=737026, Int=0
,I/IntentController( 1121): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(42798598): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(4279a8a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(4279a8a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
,D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,D/PowerUI ( 1121): closing low battery warning: level=100
,I/IntentController( 1121): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1601): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1121): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1121): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  913): acquireWL(427a00a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(427a00a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,D/PowerUI ( 1121): closing low battery warning: level=100
,D/PowerUI ( 1121): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1121): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1601): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1121): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  913): acquireWL(427a54b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41f42c70: PendingIntentRecord{41f2f068 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=797026, Int=0
,I/IntentController( 1121): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(427a54b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(427a77e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(427a77e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
D/PowerUI ( 1121): closing low battery warning: level=100
D/PowerUI ( 1121): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1121): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1601): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1121): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  913): acquireWL(427acbf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41f42c70: PendingIntentRecord{41f2f068 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=857026, Int=0
,I/IntentController( 1121): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(427acbf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(427afc28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41d28bf0: PendingIntentRecord{4245f028 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=784694, Int=0
,V/AlarmManager(  913): sending alarm PendingIntent{41c5cc28: PendingIntentRecord{424c5fb8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=893028, Int=0
,I/ActivityManager(  913): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4441 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  913): sending alarm PendingIntent{42617f00: PendingIntentRecord{425faa78 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1454434095128, Int=10800000,
,V/AlarmManager(  913): sending alarm PendingIntent{42434450: PendingIntentRecord{4251f770 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1454434526190, Int=1800000
,D/ConnectivityService(  913): Sampling interval elapsed, updating statistics ..
,D/PMS     (  913): acquireWL(427b71a8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 913 1000 null
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
D/ConnectivityService(  913): Done.
,D/ConnectivityService(  913): Setting timer for 720seconds
,D/PMS     (  913): acquireWL(42731e38): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 913 1000 null
,D/PMS     (  913): releaseWL(427b71a8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  913): releaseWL(42731e38): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  913): acquireWL(427393a8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(427afc28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029}
,D/PMS     (  913): acquireWL(4273b5b8): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(427393a8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/EventLogService( 2183): Aggregate from 1454433935683 (log), 1454432726144 (data)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.htc.aurora (4441/10049)
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024953
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025530
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025645
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025649
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025672
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025675
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027107
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027118
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029589
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360030814
,D/PMS     (  913): releaseWL(4273b5b8): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024953
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025530
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025645
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025649
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025672
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025675
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027107
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027118
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029589
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360030814
,D/Process (  913): killProcessQuiet, pid=4055
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Killing 4055:com.google.android.apps.plus/u0a160 (adj 15): empty #17
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  913): Recipient 4055
,D/PMS     (  913): acquireWL(4274e5b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(4274e5b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1121): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1601): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1121): closing low battery warning: level=100
D/PowerUI ( 1121): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1121): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  913): acquireWL(42753920): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41f42c70: PendingIntentRecord{41f2f068 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=917026, Int=0
,I/IntentController( 1121): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(42753920): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(427560b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  913): sending alarm PendingIntent{42640708: PendingIntentRecord{42561bf8 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=948175, Int=0
,D/PMS     (  913): acquireWL(427576d0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  913): sending alarm PendingIntent{422be718: PendingIntentRecord{426fdc20 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1454434815507, Int=900000
,D/PMS     (  913): releaseWL(427576d0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4372): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  913): releaseWL(427560b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PowerUsageService( 4372): call getInstance()
D/PowerUsageList:PowerUsageHelper( 4372): MY_DEBUG = false
,W/BatSI   (  913): Couldn't get kernel wake lock stats
,W/BatSI   (  913): Couldn't get kernel wake lock stats
,W/BatSI   (  913): Couldn't get kernel wake lock stats
,W/BatSI   (  913): Couldn't get kernel wake lock stats
,D/PMS     (  913): acquireWL(42379818): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/PMS     (  913): releaseWL(42379818): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1121): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
D/PowerUI ( 1121): closing low battery warning: level=100
,D/PowerUI ( 1121): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1601): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1121): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  913): acquireWL(42628d68): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1370 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1370/10029)
,D/ConnectivityService(  913): reportInetCondition for net 1, percentage: 100 by  (1370/10029)
D/ConnectivityService(  913): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  913): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1370/10029)
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024953
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025530
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025645
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025649
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025672
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025675
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027107
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360027118
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029589
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360030814,
,D/PMS     (  913): releaseWL(42628d68): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms},
,D/ConnectivityService(  913): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  913): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  913): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/PMS     (  913): acquireWL(425f6c80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/PMS     (  913): releaseWL(425f6c80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/IntentController( 1121): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1601): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1121): closing low battery warning: level=100
I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  913): << updateStatus
D/PowerUI ( 1121): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1121): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  913): acquireWL(4265ed48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41f42c70: PendingIntentRecord{41f2f068 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=977026, Int=0
,I/IntentController( 1121): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(4265ed48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(426994b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,D/SmartSyncUtils( 4372): isEpsOn(), nState = 0
V/AlarmManager(  913): sending alarm PendingIntent{4262fca8: PendingIntentRecord{4280d530 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1454434891467, Int=0
D/PMS     (  913): releaseWL(426994b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  913): acquireWL(41da2e60): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4372 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4372): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4372): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4372): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4372): SettingOnTime = 1454479200000, randomSettingOnTime = 1454478952000
,D/SmartSyncScreenOnOffTimeReceiver( 4372): SettingOffTime = 1454464800000, randomSettingOffTime = 1454469860000
,D/SmartSyncScreenOnOffTimeReceiver( 4372): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4372): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4372): bNightModeTurnOffOnce = false
D/PMS     (  913): releaseWL(41da2e60): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  913): acquireWL(426b99e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(426b99e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  913): acquireWL(42625568): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(42625568): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  913): acquireWL(42628a50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41f42c70: PendingIntentRecord{41f2f068 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1037026, Int=0
,I/IntentController( 1121): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(42628a50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(4245d5b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
,D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/PMS     (  913): releaseWL(4245d5b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1121): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
D/PowerUI ( 1121): closing low battery warning: level=100
D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1601): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1121): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1121): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  913): acquireWL(4295d648): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41f42c70: PendingIntentRecord{41f2f068 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1097026, Int=0
,I/IntentController( 1121): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(4295d648): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(426d9180): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(426d9180): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  913): updateBatteryInfo
D/PowerUI ( 1121): closing low battery warning: level=98
,D/PowerUI ( 1121): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetPhoneState( 1638): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/DotMatrix( 1601): [EventService] reorderNotification, total:1
D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1601): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1121): receive(android.intent.action.BATTERY_CHANGED,1,false)
V/NotificationService(  913): batLight: plugged
V/LightsService(  913): setLight #8: color=#c8c800
D/qdlights(  913): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  913): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  913): setLight #8: color=#c80000
D/qdlights(  913): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  913): [LedInfo] has indicator attribute
D/qdlights(  913): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  913): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,W/ContextImpl( 4372): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,I/HtcPowerSaver(  913): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,D/TetherSettings( 4081): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4081): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4081): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4081): Cust_ConnectToPC   : spcsc>false
,D/        ( 4081): Cust_ConnectToPC   : IPT>true
,D/        ( 4081): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 4081): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4081): Index of the first 1 = -1
,W/Settings( 4081): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4081): hasRemovableStorageSlot: true
W/ContextImpl( 4081): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 4081): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
D/SmartNS_Utility( 4081): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4081): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 4081): [ACC]android_networking:tethering_guard_support=false
,I/BatteryController( 1121): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  913): acquireWL(426ce270): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(426ce270): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
,D/HtcPowerSaver(  913): updateBatteryInfo
I/IntentController( 1121): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
,D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1601): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1121): closing low battery warning: level=98
D/PowerUI ( 1121): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/HtcPowerSaver(  913): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1121): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  913): acquireWL(426479b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  913): BroadcastReceiver::onReceive-
,I/IntentController( 1121): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1601): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1601): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  913): releaseWL(426479b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  913): updateBatteryInfo
D/PowerUI ( 1121): closing low battery warning: level=98
D/PowerUI ( 1121): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/HtcPowerSaver(  913): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1121): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  913): acquireWL(4273ee60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{41f42c70: PendingIntentRecord{41f2f068 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1157026, Int=0
,I/IntentController( 1121): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(4273ee60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(4263cb20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(4263cb20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  913): acquireWL(425c5c48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(425c5c48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  913): acquireWL(42640ae0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,I/IntentController( 1121): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  913): sending alarm PendingIntent{41f42c70: PendingIntentRecord{41f2f068 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1217026, Int=0
,D/PMS     (  913): releaseWL(42640ae0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4467): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4467): ====startRecUseTime====
D/htc.customization.log.level( 4467):  is 
W/CustomizationLogLevel( 4467): Level value is invalid, use default level 2
D/CustomizationManager( 4467):  Read ACC file spent 0.125 (s)
D/CIDMapFileReader( 4467): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4467): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4467): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4467): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4467): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4467): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4467): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4467): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4467): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4467): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4467): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4467): Parsing tag category name = system
I/CustomizationCIDLoader( 4467): Parsing tag category name = application
I/CustomizationCIDLoader( 4467): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4467): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4467): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4467): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4467): Parsing tag category name = Settings
D/CustomizationManager( 4467):  Read CID file spent 0.186 (s)
D/CustomizationManager( 4467):  All configurations done spent 0.186 (s)
W/HtcNativeFlag( 4467): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4467): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4467): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4467): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  913): deletePackageAsUser: pkg=com.test.thalitest, pid=4467, uid=2000 user=0
I/ActivityManager(  913): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
W/PackageSettings(  913): Skipping PackageSetting{421941b0 com.example.hello/10397} due to missing metadata
W/PackageSettings(  913): Skipping PackageSetting{42197e20 com.test.thalitest/10389} due to missing metadata
I/ActivityManager(  913): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1121): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1121): ApplicationsIntentReceiver packageName:com.test.thalitest
I/Prism.ItemManager( 1277): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/HtcKeyguardAppUpdateMonitor( 1121): ApplicationsIntentReceiver replacing:false
I/Prism.ItemManager( 1277): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/DotMatrix( 1601): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1601): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1601): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
D/PMS     (  913): acquireWL(427d9110): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1230 10029 WorkSource{10029 com.google.android.gms}
W/GeofencerStateMachine( 1230): Ignoring removeGeofence because network location is disabled.
W/PackageManager(  913): Package source /data/app/com.test.thalitest-2.apk does not exist.
W/PackageManager(  913): Couldn't delete native library directory /data/app-lib/com.test.thalitest-2
D/PMS     (  913): acquireWL(42993fd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/PMS     (  913): releaseWL(427d9110): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/BatteryService(  913): n_update end
D/PMS     (  913): releaseWL(42993fd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/AccTypeManager( 1344): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/VoicemailCleanupService( 1291): Cleaning up data for package: com.test.thalitest
D/Prism.PackageStateRece_( 1277): action: android.intent.action.PACKAGE_REMOVED
I/[PluginManager]RegisterService( 1321): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  913):   Scheme: "sms"
I/[PluginManager]RegisterService( 1321): handle notify Blinkfeed plugin client changed
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1250 :
W/AccTypeManager( 1344): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1344): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  913):   Scheme: "smsto"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1250 :
I/IcingCorporaProvider( 2836): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/SystemReader( 1262): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  913):   Scheme: "mms"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1250 :
I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  913):   Scheme: "mmsto"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1250 :
I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  913):   Scheme: "sms"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1250 :
I/ActivityManager(  913): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4481 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  913):   Scheme: "smsto"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1250 :
I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  913):   Scheme: "mms"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1250 :
I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  913):   Scheme: "mmsto"
E/ExternalAccountType( 1344): Unsupported attribute readOnly
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1250 :
I/IcingCorporaProvider( 2836): UpdateCorporaTask done [took 236 ms] updated apps [took 236 ms] 
D/PhoneApp( 1250): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/InputMethodManagerService(  913): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
E/SQLiteDatabase( 4481): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4481): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4481): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4481): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4481): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4481): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4481): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4481): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4481): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4481): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4481): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4481): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4481): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4481): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4481): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4481): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4481): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4481): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4481): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4481): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4481): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4481): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4481): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4481): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4481): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4481): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4481): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4481): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4481): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4481): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4481): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4481): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4481): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4481): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4481): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4481): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4481): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4481): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4481): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4481): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4481): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4481): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4481): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4481): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4481): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4481): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4481): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4481): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4481): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4481): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4481): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4481): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4481): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4481): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4481): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4481): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4481): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4481): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4481): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4481): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4481): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4481): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4481): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4481): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4481): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4481): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4481): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4481): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4481): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4481): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4481): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4481): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4481): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4481): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4481): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4481): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4481): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4481): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4481): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4481): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4481): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4481): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4481): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4481): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4481): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4481): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4481): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4481): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4481): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4481): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4481): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4481): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4481): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4481): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4481): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4481): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4481): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4481): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4481): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4481): threadid=11: thread exiting with uncaught exception (group=0x41698e30)
E/ActivityManager(  913): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4481): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4481): Process: com.google.android.apps.docs, PID: 4481
E/AndroidRuntime( 4481): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4481): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4481): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4481): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4481): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4481): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4481): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4481): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4481): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4481): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4481): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4481): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4481): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4481): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4481): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4481): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4481): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4481): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4481): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  913): Can't write: system_app_crash
E/DropBoxManagerService(  913): java.io.FileNotFoundException: /data/system/dropbox/drop137.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  913): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  913): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  913): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  913): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  913): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  913): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  913): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  913): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  913): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  913): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  913): 	... 5 more
I/ActivityManager(  913): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4499 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process ( 4481): killProcess, pid=4481
D/Process ( 4481): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  913): Recipient 4481
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  913): Process com.google.android.apps.docs (pid 4481) has died.
W/ContextImpl( 4499): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  913): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4512 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4499): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4499): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4499): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4499): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4499): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4499): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4499): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4499): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4499): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4499): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4499): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4499): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4499): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4499): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4499): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4499): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4499): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4499): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4499): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4499): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4499): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4499): threadid=10: thread exiting with uncaught exception (group=0x41698e30)
E/AndroidRuntime( 4499): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4499): Process: com.android.keychain, PID: 4499
E/AndroidRuntime( 4499): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4499): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4499): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4499): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4499): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4499): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4499): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4499): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4499): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4499): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4499): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4499): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4499): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4499): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4499): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4499): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4499): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4499): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4499): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4499): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  913): App crashed! Process: com.android.keychain
D/ErrorReport(  913): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4499): killProcess, pid=4499
D/Process ( 4499): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/Prism.ItemManager( 1277): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1277): loadItems() com.htc.launcher.pageview.WidgetManager@41b5dc38 +
I/Prism.WidgetManager( 1277): onLoadItems() +
E/ErrorReport(  913): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  913): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1454435156329.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  913): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  913): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  913): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  913): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  913): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  913): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  913): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  913): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  913): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  913): 	... 4 more
I/ActivityManager(  913): Recipient 4499
I/ActivityManager(  913): Process com.android.keychain (pid 4499) has died.
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/AppTag  ( 4512): getInstance(Context context)
W/ActivityManager(  913): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
W/PackageManager(  913): Unable to load service info ResolveInfo{42629f18 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  913): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  913): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  913): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  913): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  913): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  913): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  913): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  913): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  913): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  913): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  913): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  913): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  913): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  913): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  913): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  913): 	at dalvik.system.NativeStart.main(Native Method)
D/AppTag  ( 4512): getInstance(Context context)
D/AppTag  ( 4512): onCreate()
I/ActivityManager(  913): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4527 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
D/Process (  913): killProcessQuiet, pid=3610
I/ActivityManager(  913): Killing 3610:com.htc.task/u0a71 (adj 15): empty #17
D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/SQLiteDatabase( 4527): Failed to open database '/data/data/com.google.android.apps.plus/databases/trash.db'.
E/SQLiteDatabase( 4527): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4527): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4527): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4527): 	at dek.getWritableDatabase(PG:48)
E/SQLiteDatabase( 4527): 	at del.a(PG:264)
E/SQLiteDatabase( 4527): 	at eeq.run(PG:187)
E/SQLiteDatabase( 4527): 	at java.lang.Thread.run(Thread.java:864)
D/PMS     (  913): acquireWL(4260ce10): PARTIAL_WAKE_LOCK  AsyncService 0x1 4527 10160 null
W/dalvikvm( 4098): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
E/SQLiteDatabase( 4527): Failed to open database '/data/data/com.google.android.apps.plus/databases/trash.db'.
E/SQLiteDatabase( 4527): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4527): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4527): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4527): 	at dek.getWritableDatabase(PG:51)
E/SQLiteDatabase( 4527): 	at del.a(PG:264)
E/SQLiteDatabase( 4527): 	at eeq.run(PG:187)
E/SQLiteDatabase( 4527): 	at java.lang.Thread.run(Thread.java:864)
I/ActivityManager(  913): Recipient 3610
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  913): releaseWL(4260ce10): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
E/EsApplication( 4527): Failed app initialization
E/EsApplication( 4527): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/EsApplication( 4527): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/EsApplication( 4527): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/EsApplication( 4527): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/EsApplication( 4527): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/EsApplication( 4527): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/EsApplication( 4527): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/EsApplication( 4527): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/EsApplication( 4527): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/EsApplication( 4527): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/EsApplication( 4527): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/EsApplication( 4527): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/EsApplication( 4527): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/EsApplication( 4527): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/EsApplication( 4527): 	at dek.getWritableDatabase(PG:51)
E/EsApplication( 4527): 	at del.a(PG:264)
E/EsApplication( 4527): 	at eeq.run(PG:187)
E/EsApplication( 4527): 	at java.lang.Thread.run(Thread.java:864)
D/PackageBroadcastService( 2183): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2183): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 2183): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2183): Loading module APK com.google.android.play.games
I/LocationSettingsChecker( 2183): Removing dialog suppression flag for package com.test.thalitest
W/dalvikvm( 2183): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
E/SQLiteDatabase( 2183): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 2183): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2183): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2183): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2183): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2183): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 2183): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2183): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2183): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2183): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 2183): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 2183): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 2183): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 2183): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/PhenotypeInitializer( 2183): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/PhenotypeInitializer( 2183): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 2183): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 2183): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 2183): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/PhenotypeInitializer( 2183): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/PhenotypeInitializer( 2183): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/PhenotypeInitializer( 2183): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/PhenotypeInitializer( 2183): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2183): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2183): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 2183): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 2183): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 2183): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 2183): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 2183): 	at android.os.Looper.loop(Looper.java:157)
E/PhenotypeInitializer( 2183): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 2183): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 2183): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 2183): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
W/dalvikvm( 2183): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
I/GMPM-SVC( 2183): App measurement is starting up, version: 8489
I/GMPM-SVC( 2183): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE

```
