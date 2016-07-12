#### Test 757892685a40176_thali02_HTC-HTC One M8s Logs


```
--------- beginning of system
07-12 17:43:37.898   989  2338 I ActivityManager: Recipient 4796
--------- beginning of main
07-12 17:43:37.938  5285  5285 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-12 17:43:37.988  5285  5285 W VideoCapabilities: Unsupported mime video/x-ms-wmv
07-12 17:43:37.998  5285  5285 W Utils   : could not parse size range '64x64-1920X1080'
07-12 17:43:37.998  5285  5285 W AudioCapabilities: Unsupported mime audio/qcelp
07-12 17:43:37.998  5285  5285 W AudioCapabilities: Unsupported mime audio/x-ms-wma
07-12 17:43:38.008  5285  5285 W AudioCapabilities: Unsupported mime audio/qcelp
07-12 17:43:38.008  5285  5285 W VideoCapabilities: Unsupported mime video/x-ms-wmv
07-12 17:43:38.078  5285  5285 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
07-12 17:43:38.088  5285  5285 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-12 17:43:38.098  5285  5285 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-12 17:43:38.098  5285  5285 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-12 17:43:38.108  5285  5285 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-12 17:43:38.148   989  1274 V AlarmManager: sending alarm PendingIntent{3e79de86: PendingIntentRecord{1d54c347 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1468338218160, Int=0
07-12 17:43:38.178  5285  5285 I vclib   : onServiceConnected
07-12 17:43:38.178  5285  5285 W Babel   : Attempted to change video mute state without an active call.
07-12 17:43:38.198  1635  1834 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
07-12 17:43:38.198  1635  1834 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@358b74e2 +
07-12 17:43:38.198  1635  1834 I Prism.WidgetManager: onLoadItems() +
07-12 17:43:38.198   989  1294 I ActivityManager: Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=5351 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
07-12 17:43:38.198  5285  5285 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-12 17:43:38.198  5285  5285 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
07-12 17:43:38.238  5285  5285 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
07-12 17:43:38.248  5351  5351 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
07-12 17:43:38.248  1635  1834 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
07-12 17:43:38.278  5351  5351 D CalendarApplication: onCreate
07-12 17:43:38.278  5351  5351 D ProviderChangeReceiver: ---------------------------------------------------
07-12 17:43:38.278  5351  5351 D ProviderChangeReceiver: ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
07-12 17:43:38.278   989  1624 I ActivityManager: Killing 4846:com.htc.widget.hmsproc2/u0a40 (adj 15): empty #17
07-12 17:43:38.278   989  1624 D Process : killProcessQuiet, pid=4846
07-12 17:43:38.278   989  1624 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
07-12 17:43:38.288  5351  5373 D HtcAlertService: start to updateAlertNotification!
07-12 17:43:38.298  5346  5376 E cutils-trace: Error opening trace file: Permission denied (13)
07-12 17:43:38.318  5285  5285 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
07-12 17:43:38.318  5285  5285 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
07-12 17:43:38.368  5346  5346 D CustomizationManager: ====startRecUseTime====
07-12 17:43:38.368  5346  5346 D htc.customization.log.level:  is 
07-12 17:43:38.368  5346  5346 W CustomizationLogLevel: Level value is invalid, use default level 2
07-12 17:43:38.388   989  1770 I ActivityManager: Recipient 4846
07-12 17:43:38.398  1549  5388 I WSP     : [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
07-12 17:43:38.398  1549  5388 D WeatherUtility: Weather sync is On
07-12 17:43:38.408  1583  2180 D PhoneApp: EVENT_QUERY_MO_PACKAGES
07-12 17:43:38.408  1583  2180 D PhoneApp: -- N1 =0
07-12 17:43:38.408  5351  5373 D HtcAlertService: No fired or scheduled alerts
07-12 17:43:38.408  5351  5373 D HtcAlertUtils: -- cancelReminderNotification --
07-12 17:43:38.418  1549  5388 I WSP     : [Receiver] next auto-sync alarm event is 60 mins later, at time: Tue Jul 12 18:43:38 CEST 2016
07-12 17:43:38.418  1583  2180 D PhoneApp: -- N2 =0
07-12 17:43:38.418  5351  5373 D HtcAlertUtils: broadcastExistReminder!
07-12 17:43:38.418  1549  5388 W WSP     : [Receiver] can't get active network info
07-12 17:43:38.418  4955  4955 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
07-12 17:43:38.428  1447  1447 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
07-12 17:43:38.428   989  1770 I ActivityManager: Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
07-12 17:43:38.428  4955  5391 I DFPI.ApkInstallService: onHandleIntent
07-12 17:43:38.428  4955  5391 I DFPI.ApkInstallService: Media Scan Finished Case 
07-12 17:43:38.428  4955  5391 D DFPI.ApkInstallService: check CID = HTC__102
07-12 17:43:38.428  4955  5391 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
07-12 17:43:38.428   989  1650 I ActivityManager: Resuming delayed broadcast
07-12 17:43:38.438  1549  1549 V WSP     : [SyncService] no data connection, stop sync service
07-12 17:43:38.438  1583  2180 D PhoneApp: -- N3 =0
07-12 17:43:38.448  5346  5346 D CustomizationManager:  Read ACC file spent 0.037 (s)
07-12 17:43:38.448  5346  5346 D CIDMapFileReader: Parsing tag item name = HTC__001
07-12 17:43:38.448  5346  5346 D CIDMapFileReader: Parsing tag item name = HTC__102
07-12 17:43:38.448  5346  5346 D CIDMapFileReader: Parsing tag item name = HTC__Y13
07-12 17:43:38.448  5346  5346 D CIDMapFileReader: Parsing tag item name = HTC__032
07-12 17:43:38.448  5346  5346 D CIDMapFileReader: Parsing tag item name = HTC__M27
07-12 17:43:38.448  5346  5346 D CIDMapFileReader: Parsing tag item name = HTC__002
07-12 17:43:38.448  5346  5346 D CIDMapFileReader: Parsing tag item name = HTC__031
07-12 17:43:38.448  5346  5346 D CIDMapFileReader: Parsing tag item name = HTC__A07
07-12 17:43:38.448  5007  5007 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
07-12 17:43:38.448  5346  5346 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__102.xml
07-12 17:43:38.448  5346  5346 I CustomizationCIDLoader: Parsing tag category name = system
07-12 17:43:38.448  5346  5346 I CustomizationCIDLoader: Parsing tag category name = application
07-12 17:43:38.448  5346  5346 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
07-12 17:43:38.448   989  2338 I ActivityManager: Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
07-12 17:43:38.448  5346  5346 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
07-12 17:43:38.448  5346  5346 I CustomizationCIDLoader: Parsing tag category name = AudioService
07-12 17:43:38.448  5346  5346 I CustomizationCIDLoader: Parsing tag category name = Settings
07-12 17:43:38.448  5346  5346 I CustomizationCIDLoader: Parsing tag category name = ACC
07-12 17:43:38.448  4731  5390 I Task_Calendar: Set ICALENDAR_UID to sync_data7 due to SDK_INT is 21
07-12 17:43:38.448  5346  5346 I CustomizationCIDLoader: add string-array item, value = 42507
07-12 17:43:38.448  5346  5346 I CustomizationCIDLoader: add string-array item, value = 21902
07-12 17:43:38.448  5346  5346 I CustomizationCIDLoader: add string-array item, value = 26006:26001.26002.26003
07-12 17:43:38.448  5346  5346 I CustomizationCIDLoader: add string-array item, value = 23420
07-12 17:43:38.448  5346  5346 I CustomizationCIDLoader: add string-array item, value = 22299
07-12 17:43:38.448  5346  5346 I CustomizationCIDLoader: add string-array item, value = 24002
07-12 17:43:38.448  5346  5346 I CustomizationCIDLoader: add string-array item, value = 23210
07-12 17:43:38.448  5346  5346 I CustomizationCIDLoader: add string-array item, value = 23205
07-12 17:43:38.448  5346  5346 I CustomizationCIDLoader: add string-array item, value = 23806
07-12 17:43:38.448  5346  5346 I CustomizationCIDLoader: add string-array item, value = 23430
07-12 17:43:38.448  5346  5346 I CustomizationCIDLoader: add string-array item, value = 23408
07-12 17:43:38.448  5346  5346 I CustomizationCIDLoader: add string-array item, value = 27205
07-12 17:43:38.448  5346  5346 I CustomizationCIDLoader: add string-array item, value = 42507:C:1:0
07-12 17:43:38.448  5346  5346 I CustomizationCIDLoader: add string-array item, value = 21902:C:1:0
07-12 17:43:38.448  5346  5346 I CustomizationCIDLoader: add string-array item, value = 26006:D:1:0
07-12 17:43:38.448  5346  5346 I CustomizationCIDLoader: add string-array item, value = 23420:D:0:0
07-12 17:43:38.448  5346  5346 I CustomizationCIDLoader: add string-array item, value = 22299:D:0:0
07-12 17:43:38.448  5346  5346 I CustomizationCIDLoader: add string-array item, value = 24002:D:0:0
07-12 17:43:38.448  5346  5346 I CustomizationCIDLoader: add string-array item, value = 23210:D:2:0
07-12 17:43:38.448  5346  5346 I CustomizationCIDLoader: add string-array item, value = 23205:D:2:0
07-12 17:43:38.448  5346  5346 I CustomizationCIDLoader: add string-array item, value = 23806:D:0:0
07-12 17:43:38.448  5346  5346 I CustomizationCIDLoader: add string-array item, value = 23430:C:1:0
07-12 17:43:38.448  5346  5346 I CustomizationCIDLoader: add string-array item, value = 23408:C:1:0
07-12 17:43:38.448  5346  5346 I CustomizationCIDLoader: add string-array item, value = 27205:C:1:0
07-12 17:43:38.448  5346  5346 D CustomizationManager:  Read CID file spent 0.084 (s)
07-12 17:43:38.448  5007  5007 I SoundPicker: SoundPickerReceiver [onReceive] startService
07-12 17:43:38.448  5346  5346 D CustomizationManager:  All configurations done spent 0.084 (s)
07-12 17:43:38.458  5007  5028 W art     : Suspending all threads took: 10.638ms
07-12 17:43:38.458  1583  1623 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
07-12 17:43:38.478  5285  5348 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-12 17:43:38.488  5285  5348 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-12 17:43:38.488  5285  5348 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-12 17:43:38.488  5007  5394 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
07-12 17:43:38.488  5285  5393 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
07-12 17:43:38.498  5007  5394 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
07-12 17:43:38.498  5007  5394 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
07-12 17:43:38.498  5007  5394 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-12 17:43:38.498  5007  5394 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
07-12 17:43:38.498  5007  5394 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-12 17:43:38.498  5007  5394 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-12 17:43:38.498  5007  5394 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
07-12 17:43:38.498  5007  5394 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-12 17:43:38.498  5007  5394 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-12 17:43:38.498  5007  5394 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-12 17:43:38.498   989  1008 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 5346 on display 0
07-12 17:43:38.498   989  1071 D PMS     : acquireHCC(3cdde1f8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 989 1000 null
07-12 17:43:38.498   989  1071 D PMS     : acquireHCC(322f6d1): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 989 1000 null
07-12 17:43:38.508  1635  1834 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-12 17:43:38.508  5007  5394 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-12 17:43:38.508  5007  5394 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-12 17:43:38.508  5007  5394 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-12 17:43:38.508  5007  5394 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-12 17:43:38.508  5007  5394 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-12 17:43:38.508   989  1008 D PMS     : acquireWL(100b25a4): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 989 1000 null
07-12 17:43:38.508  5007  5394 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-12 17:43:38.508  5007  5394 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
07-12 17:43:38.508   989  1060 I AnimationUtil: isHTCRecent(ThaliTest/Recent screens.)/0
07-12 17:43:38.508  5007  5394 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
07-12 17:43:38.508  5007  5394 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
07-12 17:43:38.518  5007  5394 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
07-12 17:43:38.518  5007  5394 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
07-12 17:43:38.518  5007  5394 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
07-12 17:43:38.518  5007  5394 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
07-12 17:43:38.518  5007  5394 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
07-12 17:43:38.518  5007  5394 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-12 17:43:38.518  5007  5394 I SoundPicker: TurnFileToMediaUriService [checkFileExistence]
07-12 17:43:38.518  5007  5394 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-12 17:43:38.518  5007  5394 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
07-12 17:43:38.518  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
07-12 17:43:38.518  1635  1635 I FeedHostManager: [onPause]
07-12 17:43:38.518  1635  1635 I FeedProviderManager: onPause
07-12 17:43:38.518  1635  1635 I FeedHostManager: [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@14fb52c5
07-12 17:43:38.518  1635  2461 I SocialFeedProvider: +onPause
07-12 17:43:38.518  1635  2461 I SocialFeedProvider: -onPause
07-12 17:43:38.518  1635  1635 I ContextualWidget: onPause
07-12 17:43:38.518  1635  1635 I ContextualWidget: notifyWidgetDeactive
07-12 17:43:38.528   989  1675 W HtcSystemUPManager: HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
07-12 17:43:38.548   989  1770 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5398 uid=10195 gids={50195, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-12 17:43:38.548   989  5151 D PMS     : releaseWL(1d35db6b): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
07-12 17:43:38.568   989  1621 I ActivityManager: Resuming delayed broadcast
07-12 17:43:38.608   989  1621 I ActivityManager: Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
07-12 17:43:38.638   989  1058 D StatusBarManagerService: setSystemUiVisibility(0x8600)
07-12 17:43:38.638   989  1058 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-12 17:43:38.638   989  1058 D StatusBarManagerService: hiding MENU key
07-12 17:43:38.668   989  1673 I art     : Explicit concurrent mark sweep GC freed 25679(1452KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 2.917ms total 204.474ms
07-12 17:43:38.668  5007  5394 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
07-12 17:43:38.668  4731  5390 D TodoTaskshortcut: update TASK shortcut>
07-12 17:43:38.688  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-12 17:43:38.688  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-12 17:43:38.688  5007  5394 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-12 17:43:38.688  5007  5394 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
07-12 17:43:38.688  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
07-12 17:43:38.708  5007  5394 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
07-12 17:43:38.708  1635  1635 I TrimMemoryManager: [trimMemory] 20
07-12 17:43:38.718  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-12 17:43:38.718  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-12 17:43:38.718  5007  5394 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-12 17:43:38.718  5007  5394 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-12 17:43:38.718  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
07-12 17:43:38.728   989  1770 I ActivityManager: Resuming delayed broadcast
,07-12 17:43:38.738  5007  5394 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
07-12 17:43:38.748  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-12 17:43:38.748  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-12 17:43:38.748  5007  5394 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-12 17:43:38.748  5007  5394 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-12 17:43:38.748  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,07-12 17:43:38.748  3660  3703 I art     : Explicit concurrent mark sweep GC freed 17292(1316KB) AllocSpace objects, 0(0B) LOS objects, 72% free, 1528KB/5MB, paused 706us total 49.276ms
,07-12 17:43:38.758  5007  5394 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,07-12 17:43:38.758  4955  4955 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
07-12 17:43:38.758  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
07-12 17:43:38.758  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
07-12 17:43:38.758  5007  5394 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-12 17:43:38.758  5007  5394 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-12 17:43:38.758  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,07-12 17:43:38.758   989  5151 I ActivityManager: Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,07-12 17:43:38.768  5007  5394 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,07-12 17:43:38.768  4955  5423 I DFPI.ApkInstallService: onHandleIntent
07-12 17:43:38.768  4955  5423 I DFPI.ApkInstallService: Media Scan Finished Case 
,07-12 17:43:38.768  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
07-12 17:43:38.768  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
,07-12 17:43:38.768  5007  5394 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
07-12 17:43:38.768  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
07-12 17:43:38.768  4955  5423 D DFPI.ApkInstallService: check CID = HTC__102
07-12 17:43:38.768  4955  5423 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
07-12 17:43:38.768   989  1294 I ActivityManager: Resuming delayed broadcast
,07-12 17:43:38.778  5007  5394 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,07-12 17:43:38.778  5398  5398 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,07-12 17:43:38.778  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,07-12 17:43:38.778  5007  5007 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED,
07-12 17:43:38.778  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
07-12 17:43:38.778  5007  5394 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
,07-12 17:43:38.778  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
07-12 17:43:38.778  5007  5007 I SoundPicker: SoundPickerReceiver [onReceive] startService
07-12 17:43:38.788  5007  5394 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,07-12 17:43:38.788  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
07-12 17:43:38.788  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
07-12 17:43:38.788  5007  5394 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
07-12 17:43:38.788  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,07-12 17:43:38.798  5007  5394 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,07-12 17:43:38.798   989  1008 D PMS     : acquireWL(17fe3641): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 5285 10112 null
,07-12 17:43:38.798   989  1621 I ActivityManager: Delay finish: com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver
,07-12 17:43:38.798  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,07-12 17:43:38.798  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
,07-12 17:43:38.798  5007  5394 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
07-12 17:43:38.798  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,07-12 17:43:38.808  5007  5394 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac,
,07-12 17:43:38.808  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
07-12 17:43:38.808  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,07-12 17:43:38.808  1635  1834 W asset   : Copying FileAsset 0xac5b31f0 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,07-12 17:43:38.808  5007  5394 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
07-12 17:43:38.808  5007  5394 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
07-12 17:43:38.808  5007  5394 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
07-12 17:43:38.808  5007  5394 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-12 17:43:38.808  5007  5394 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
07-12 17:43:38.808  5007  5394 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
,07-12 17:43:38.808  5007  5394 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-12 17:43:38.808  5007  5394 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
07-12 17:43:38.808  5007  5394 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-12 17:43:38.808  5007  5394 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-12 17:43:38.808  5007  5394 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-12 17:43:38.808  5007  5394 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-12 17:43:38.808  5007  5394 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-12 17:43:38.808  5007  5394 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-12 17:43:38.808  5007  5394 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-12 17:43:38.808  5007  5394 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-12 17:43:38.808  5007  5394 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-12 17:43:38.808  5007  5394 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
07-12 17:43:38.808  5007  5394 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
07-12 17:43:38.808  5007  5394 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
,07-12 17:43:38.808  5007  5394 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
07-12 17:43:38.808  5007  5394 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
07-12 17:43:38.808  5007  5394 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
07-12 17:43:38.808  5007  5394 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
07-12 17:43:38.808  5007  5394 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
07-12 17:43:38.808  5007  5394 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-12 17:43:38.808  5007  5394 I SoundPicker: TurnFileToMediaUriService [checkFileExistence]
07-12 17:43:38.808  5007  5394 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-12 17:43:38.808  5007  5394 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
07-12 17:43:38.808  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-12 17:43:38.818  5007  5394 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,07-12 17:43:38.818  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,07-12 17:43:38.818  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-12 17:43:38.818  5007  5394 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-12 17:43:38.818  5007  5394 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
07-12 17:43:38.818  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-12 17:43:38.818   989  1650 D PMS     : releaseWL(17fe3641): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
07-12 17:43:38.818   989  1050 I ActivityManager: Waited long enough for: ServiceRecord{3c2b1791 u0 com.htc.backup/.notifications.contextual.ContextualReminderControlService}
07-12 17:43:38.818   989  1050 I ActivityManager: Resuming delayed broadcast
,07-12 17:43:38.828  4917  5419 I MediaStoreImporter: Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,07-12 17:43:38.838  5398  5398 I LibraryLoader: Time to load native libraries: 13 ms (timestamps 1563-1576),
07-12 17:43:38.838  5398  5398 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-12 17:43:38.838  5007  5394 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
07-12 17:43:38.838   989  1050 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=5428 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
07-12 17:43:38.848  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,07-12 17:43:38.848  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-12 17:43:38.848  5007  5394 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
,07-12 17:43:38.848  5007  5394 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
,07-12 17:43:38.848  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122,
,07-12 17:43:38.858  5007  5394 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,07-12 17:43:38.858  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-12 17:43:38.858  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-12 17:43:38.858  5007  5394 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-12 17:43:38.858  5007  5394 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-12 17:43:38.858  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
07-12 17:43:38.858  5398  5398 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1387a94}
07-12 17:43:38.868  5398  5398 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-12 17:43:38.868  5007  5394 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
07-12 17:43:38.868  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
07-12 17:43:38.868  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
07-12 17:43:38.868  5007  5394 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-12 17:43:38.868  5007  5394 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-12 17:43:38.868  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
07-12 17:43:38.868  5398  5398 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
07-12 17:43:38.878  5007  5394 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
07-12 17:43:38.878  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
07-12 17:43:38.878  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
07-12 17:43:38.878  5007  5394 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
07-12 17:43:38.878  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,07-12 17:43:38.888  5007  5394 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,07-12 17:43:38.888  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
07-12 17:43:38.888  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
07-12 17:43:38.888  5007  5394 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
07-12 17:43:38.888  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,07-12 17:43:38.888  5398  5398 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-12 17:43:38.888  1635  1834 I Prism.WidgetManager: onLoadItems() -
07-12 17:43:38.888  1635  1834 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@358b74e2 -
,07-12 17:43:38.898  5007  5394 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,07-12 17:43:38.898  5398  5398 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-12 17:43:38.898  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
07-12 17:43:38.898  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
07-12 17:43:38.898  5007  5394 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
07-12 17:43:38.898  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,07-12 17:43:38.898  5398  5398 E SysUtils: ApplicationContext is null in ApplicationStatus
07-12 17:43:38.898  5007  5394 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
07-12 17:43:38.898  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
07-12 17:43:38.898  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
07-12 17:43:38.898  5007  5394 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
07-12 17:43:38.898  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,07-12 17:43:38.908  1635  1834 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-12 17:43:38.908  1635  1834 W PackageManager: Failure retrieving resources for com.test.thalitest: Resource ID #0x0
,07-12 17:43:38.908  5007  5394 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,07-12 17:43:38.908  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac,
07-12 17:43:38.908  5007  5394 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,07-12 17:43:38.918  1635  1834 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false,
07-12 17:43:38.918  1635  1834 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,07-12 17:43:38.928  1635  1635 I Launcher: Deferring update until onResume,
07-12 17:43:38.928  1635  1635 D Launcher: waitUntilResume // bindAppsAdded
,07-12 17:43:38.948  5398  5451 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,07-12 17:43:38.968  5398  5398 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,07-12 17:43:38.978  5398  5398 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY),
07-12 17:43:38.978  5398  5398 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-12 17:43:38.978  5398  5398 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BR.1.1.2.05.00.02.028.191_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2.05.00.02.028.191__release_AU ()
07-12 17:43:38.978  5398  5398 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
07-12 17:43:38.978  5398  5398 I Adreno-EGL: Build Date: 04/17/15 Fri
07-12 17:43:38.978  5398  5398 I Adreno-EGL: Local Branch: 
07-12 17:43:38.978  5398  5398 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2.05.00.02.028.191
07-12 17:43:38.978  5398  5398 I Adreno-EGL: Local Patches: NONE
07-12 17:43:38.978  5398  5398 I Adreno-EGL: Reconstruct Branch: NOTHING
,07-12 17:43:38.988  4917  5419 I MediaStoreImporter: Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,07-12 17:43:39.038  1635  2753 I SocialFeedProvider: +disConnect socialManager
,07-12 17:43:39.038  1635  2753 I SocialFeedProvider: disconnect socialManager
07-12 17:43:39.038   989  1770 W System.err: java.lang.Throwable: stack dump
,07-12 17:43:39.038   989  1059 D BluetoothManagerService: Message: MESSAGE_REGISTER_ADAPTER
07-12 17:43:39.038   989  1770 W System.err: 	at java.lang.Thread.dumpStack(Thread.java:490)
07-12 17:43:39.038   989  1770 W System.err: 	,at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
07-12 17:43:39.038   989  1770 W System.err: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
,07-12 17:43:39.038   989  1770 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
07-12 17:43:39.048   989  1059 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2745735:true
07-12 17:43:39.048  5398  5463 D BluetoothAdapter: 661433344: getState() :  mService = null. Returning STATE_OFF
07-12 17:43:39.048  1635  2753 I SocialFeedProvider: -disConnect socialManager
,07-12 17:43:39.108   989  1274 I ActivityManager: Start proc com.htc.sense.news for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper: pid=5471 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=armeabi-v7a
,07-12 17:43:39.108   989  1274 V AlarmManager: sending alarm PendingIntent{2840926e: PendingIntentRecord{340a519c com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1468338219099, Int=0
,07-12 17:43:39.108   989  1008 D LocationManagerService: getProviders()=[passive]
,07-12 17:43:39.128   422   422 I art     : Explicit concurrent mark sweep GC freed 8657(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 288us total 22.024ms
,07-12 17:43:39.148   422   422 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 259us total 18.487ms,
,07-12 17:43:39.158  5398  5398 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-12 17:43:39.168   422   422 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 329us total 16.919ms,
,07-12 17:43:39.188   989  1678 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5496 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a
,07-12 17:43:39.188  5471  5471 I MultiDex: VM with version 2.1.0 has multidex support,
07-12 17:43:39.188   989  1770 I ActivityManager: Killing 4868:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
07-12 17:43:39.188  5471  5471 I MultiDex: install
,07-12 17:43:39.188  5471  5471 I MultiDex: VM has multidex support, MultiDex support library is disabled.
07-12 17:43:39.188   989  1770 D Process : killProcessQuiet, pid=4868
07-12 17:43:39.188   989  1770 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
07-12 17:43:39.198  5398  5398 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-12 17:43:39.208   989  1650 D PMS     : releaseWL(3d71817f): PARTIAL_WAKE_LOCK  AudioMix 0x1 null,
,07-12 17:43:39.218  5398  5398 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC
,07-12 17:43:39.298   989  2338 I ActivityManager: Recipient 4868
,07-12 17:43:39.308   989  1624 I ActivityManager: Killing 4820:com.htc.bgp/u0a11 (adj 15): empty #17,
07-12 17:43:39.308   989  1624 D Process : killProcessQuiet, pid=4820
,07-12 17:43:39.308   989  1624 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.attachApplicationLocked:6655 
,07-12 17:43:39.388   989  1770 I ActivityManager: Recipient 4820
,07-12 17:43:39.418  5398  5398 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
07-12 17:43:39.418  5398  5398 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-12 17:43:39.438  1635  1635 D Prism.PackageStateRece_: action: android.intent.action.PACKAGE_CHANGED
07-12 17:43:39.438  1635  1635 I ContextualWidget: package com.google.android.gms changed,
,07-12 17:43:39.448  1549  5517 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
07-12 17:43:39.448  1549  5517 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed
,07-12 17:43:39.448  1635  1864 I ContextualWidget: handleMessage, what=1026 mode=GettingOut maxcount=8
,07-12 17:43:39.458  1635  1864 I ContextualWidget: MFU.onDataSetChanged
07-12 17:43:39.458  1635  1864 I ContextualWidget: handleMessage, what=1001 mode=GettingOut maxcount=8
07-12 17:43:39.458  1635  1864 I ContextualWidget: updateMFULaunchCountIfNeeded update=false days=0
,07-12 17:43:39.458  1635  1864 W SystemReader: Cannot find enable_download_option, use default value instead
07-12 17:43:39.458  1635  1864 W SystemReader: Cannot find enable_suggestion_option, use default value instead
07-12 17:43:39.458  1635  1864 I ContextualWidget: Download enabled: true, Recommend enabled: true
07-12 17:43:39.458  1635  1864 I ContextualWidget: sync all data, download=0 recommend=4
07-12 17:43:39.458  1635  1864 I ContextualWidget: sync all data, mode=GettingOut count=2
07-12 17:43:39.458  1635  1864 I ContextualWidget: notifyDataChanged, list size 4
,07-12 17:43:39.498   989  1624 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=5525 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,07-12 17:43:39.518   418   418 I art     : Explicit concurrent mark sweep GC freed 8632(366KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 185us total 19.566ms,
,07-12 17:43:39.518  5471  5545 I SocialManager[SocialBiLogHelper]: action: com.htc.sense.hsp.HANDLE_ULOG
07-12 17:43:39.528  5471  5545 I SocialManager[SocialBiLogHelper]: last commit ulog time 1468299493093
,07-12 17:43:39.528  5471  5545 I SocialManager[SocialBiLogHelper]: skip commit this time
,07-12 17:43:39.528   989  1008 I ActivityManager: Killing 5036:com.htc.updater/u0a84 (adj 15): empty #17
,07-12 17:43:39.528   989  1008 D Process : killProcessQuiet, pid=5036
,07-12 17:43:39.528   989  1008 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-12 17:43:39.538   418   418 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 139us total 16.933ms
,07-12 17:43:39.548   418   418 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 154us total 15.552ms,
,07-12 17:43:39.588  1635  1864 I ContextualWidget: MFU.onDataSetChanged
07-12 17:43:39.588  1635  1864 I ContextualWidget: handleMessage, what=1001 mode=GettingOut maxcount=8
07-12 17:43:39.588  1635  1864 I ContextualWidget: updateMFULaunchCountIfNeeded update=false days=0
,07-12 17:43:39.608   989  1673 I ActivityManager: Recipient 5036
,07-12 17:43:39.748  1635  1864 I ContextualWidget: MFU.onLoadComplete
,07-12 17:43:39.748  1635  1864 W SystemReader: Cannot find enable_download_option, use default value instead
07-12 17:43:39.748  1635  1864 W SystemReader: Cannot find enable_suggestion_option, use default value instead
07-12 17:43:39.748  1635  1864 I ContextualWidget: Download enabled: true, Recommend enabled: true
,07-12 17:43:39.748  1635  1864 I ContextualWidget: sync all data, download=0 recommend=4
07-12 17:43:39.748  1635  1864 I ContextualWidget: sync all data, mode=GettingOut count=2
07-12 17:43:39.748  1635  1864 I ContextualWidget: notifyDataChanged, list size 4
,07-12 17:43:39.768  5398  5461 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,07-12 17:43:39.778  5525  5525 D Fingerprint/ HtcFingerPrintQuickLaunchProvider: -onCreate()
,07-12 17:43:39.798  5525  5525 V Settings:HtcSettingsApplication: [5525/5525] onCreate()
,07-12 17:43:39.808  5398  5398 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,07-12 17:43:39.848   989  1621 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5556 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,07-12 17:43:39.848   989  1621 D Process : killProcessQuiet, pid=5057
,07-12 17:43:39.848   989  1621 I ActivityManager: Killing 5057:com.htc.android.mail:sync/u0a62 (adj 15): empty #17
07-12 17:43:39.848   989  1621 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.trimApplications:19136 
,07-12 17:43:39.908  5525  5580 D Settings:HtcWirelessFeatureFlags: id/is att sku: 118/false,
,07-12 17:43:39.938   989  1678 I ActivityManager: Recipient 5057,
07-12 17:43:39.938   989  1286 D WifiService: Client connection lost with reason: 4
07-12 17:43:39.938  5398  5398 I InputMethodManager: [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@343c545c, mServedView=org.apache.cordova.engine.SystemWebView{3a8c2365 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@2592083a
,07-12 17:43:39.938   989  1008 I InputMethodManagerService: Disable input method client, pid=1635,
07-12 17:43:39.938   989  1008 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
07-12 17:43:39.948  1362  1362 I PhoneStatusBar: setImeWindowStatus(false,false)
07-12 17:43:39.938   989  1008 I InputMethodManagerService: Enable input method client, pid=5398
,07-12 17:43:39.958   989  1673 D PMS     : releaseWL(100b25a4): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null,
,07-12 17:43:39.968   989  1060 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s441ms
,07-12 17:43:39.968  5525  5580 E Settings:HtcWrapHeaderInfo: no such activity!
07-12 17:43:39.968  5398  5398 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5398
,07-12 17:43:39.988  5525  5571 W Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub: The wrap header doesn't exist in header list.,
,07-12 17:43:39.998  1506  1506 W XT9_C   : [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4),
07-12 17:43:39.998  1506  1506 I XT9_C   : [T9_ReleaseBuffer] Reset LDB#0
07-12 17:43:39.998  1506  1506 I XT9_C   : [T9_ReleaseBuffer] Reset LDB#1
,07-12 17:43:39.998  1506  1506 D XT9_C   : [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,07-12 17:43:39.998  5525  5571 E Settings:HtcWrapHeaderInfo: updateDevelopment, showDev = true
,07-12 17:43:40.028  5525  5571 E Settings:HtcUmcWidgetEnabler: isSupportMusicChannel(): false,
,07-12 17:43:40.048  5525  5571 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportRecentAppsButton]hasNavigationBar:true
07-12 17:43:40.048  5525  5571 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportRecentAppsButton]hasRecentAppsKey:false
07-12 17:43:40.048  5525  5571 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportRecentAppsButton]support         :false
,07-12 17:43:40.048  5525  5571 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasNavigationBar:true,
07-12 17:43:40.048  5525  5571 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasMenuKey      :false
07-12 17:43:40.048  5525  5571 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasRecentAppKey :false
07-12 17:43:40.048  5525  5571 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasBackKey      :false
07-12 17:43:40.048  5525  5571 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasHomeKey      :false
07-12 17:43:40.048  5525  5571 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]support         :false
,07-12 17:43:40.048   989  1678 I PackageManager:  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=5556, uid=10072, userID:0
,07-12 17:43:40.058  5556  5556 W global  : [apache-http] Connection GC has been deprecated!,
,07-12 17:43:40.068   989  1009 I ActivityManager: Cannot resolve ContentProvider=com.htc.vowifi
,07-12 17:43:40.068  5525  5571 E Settings:HtcVoWifiWidgetEnabler: isSupportVoWifi: null
07-12 17:43:40.068  5525  5571 E ActivityThread: Failed to find provider info for com.htc.vowifi
,07-12 17:43:40.078  5556  5556 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,07-12 17:43:40.078  5525  5570 W Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub: The wrap header doesn't exist in header list.
,07-12 17:43:40.078  5525  5570 E Settings:HtcWrapHeaderInfo: updateDevelopment, showDev = true
,07-12 17:43:40.078  5525  5570 E Settings:HtcUmcWidgetEnabler: isSupportMusicChannel(): false
07-12 17:43:40.078  5556  5556 W global  : [apache-http] Connection GC has been deprecated!
,07-12 17:43:40.078  5525  5570 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportRecentAppsButton]hasNavigationBar:true
07-12 17:43:40.078  5525  5570 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportRecentAppsButton]hasRecentAppsKey:false
07-12 17:43:40.078  5525  5570 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportRecentAppsButton]support         :false
,07-12 17:43:40.078  5525  5570 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasNavigationBar:true
07-12 17:43:40.078  5525  5570 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasMenuKey      :false
07-12 17:43:40.078  5525  5570 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasRecentAppKey :false
07-12 17:43:40.078  5525  5570 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasBackKey      :false
07-12 17:43:40.078  5525  5570 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasHomeKey      :false
07-12 17:43:40.078  5525  5570 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]support         :false
,07-12 17:43:40.088   989  2338 I ActivityManager: Cannot resolve ContentProvider=com.htc.vowifi
07-12 17:43:40.088  5525  5570 E Settings:HtcVoWifiWidgetEnabler: isSupportVoWifi: null
07-12 17:43:40.088  5525  5570 E ActivityThread: Failed to find provider info for com.htc.vowifi
,07-12 17:43:40.118  5398  5398 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-12 17:43:40.148  5556  5556 W global  : [apache-http] Connection GC has been deprecated!,
,07-12 17:43:40.178  3205  3261 I HtcModeClient: handler message = 4011
07-12 17:43:40.178  3205  3261 E HtcModeClient: Check connection and retry 5 times.
07-12 17:43:40.178  5556  5556 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,07-12 17:43:40.238   989  1621 I ActivityManager: Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5611 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,07-12 17:43:40.258  5556  5556 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-12 17:43:40.258  5556  5556 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-12 17:43:40.278   989  1650 I PackageManager:  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=5556, uid=10072, userID:0
,07-12 17:43:40.288  5398  5555 D jxcore_app_log: JniHelper::setJavaVM(0xab0377b8), pthread_self() = -1405759512
,07-12 17:43:40.288  5611  5611 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-12 17:43:40.288  5611  5611 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-12 17:43:40.298  5398  5555 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-12 17:43:40.298  5398  5555 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-12 17:43:40.298  5398  5555 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-12 17:43:40.298  5398  5555 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-12 17:43:40.298  5398  5555 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-12 17:43:40.298  5398  5555 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14969dbf added. We now have 1 listener(s)
,07-12 17:43:40.308   989  1570 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
07-12 17:43:40.308  5398  5555 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 90:E7:C4:F6:69:77
07-12 17:43:40.308  5398  5555 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "90:E7:C4:F6:69:77"
,07-12 17:43:40.308  5398  5555 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-12 17:43:40.308  5398  5555 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 17:43:40.318  5611  5611 I MultiDex: VM with version 2.1.0 has multidex support
07-12 17:43:40.318  5611  5611 I MultiDex: install
07-12 17:43:40.318  5611  5611 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-12 17:43:40.318  5398  5555 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-12 17:43:40.318  5398  5555 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-12 17:43:40.318  5398  5555 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-12 17:43:40.318  5398  5555 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 90:E7:C4:F6:69:77
,07-12 17:43:40.318  5398  5555 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-12 17:43:40.318  5398  5555 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-12 17:43:40.318  5398  5555 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-12 17:43:40.318  5398  5555 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-12 17:43:40.318  5398  5555 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-12 17:43:40.318  5398  5555 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-12 17:43:40.318  5398  5555 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-12 17:43:40.318  5398  5555 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@179cf3ea added. We now have 1 listener(s)
07-12 17:43:40.318  5556  5556 D Finsky  : [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
07-12 17:43:40.318  5556  5556 D Finsky  : [1] 2.run: Finished loading 1 libraries.
07-12 17:43:40.318  5398  5555 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-12 17:43:40.328  5556  5556 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,07-12 17:43:40.338   989   989 E WifiTrafficPoller: ADD_CLIENT: 6
,07-12 17:43:40.338   989  1286 D WifiService: New client listening to asynchronous messages
,07-12 17:43:40.338  5398  5555 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,07-12 17:43:40.338  5398  5555 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
07-12 17:43:40.348  5398  5555 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-12 17:43:40.348  5398  5555 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-12 17:43:40.348  5398  5555 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-12 17:43:40.348  5398  5555 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-12 17:43:40.358  5398  5555 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-12 17:43:40.358   989  1650 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-12 17:43:40.358  5398  5555 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 90:E7:C4:F6:69:77
,07-12 17:43:40.358  5611  5611 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,07-12 17:43:40.358  5398  5555 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,07-12 17:43:40.358  5398  5555 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:43:40.358  5398  5555 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:43:40.358  5398  5555 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-12 17:43:40.358  5398  5555 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 17:43:40.358  5398  5555 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:43:40.358  5398  5555 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:43:40.358  5398  5555 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:43:40.358  5398  5555 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:43:40.358  5398  5555 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-12 17:43:40.358  5398  5555 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-12 17:43:40.358  5398  5555 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-12 17:43:40.368  5556  5556 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,07-12 17:43:40.398  5611  5611 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,07-12 17:43:40.398  5611  5611 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@900eb90: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
07-12 17:43:40.398  5611  5611 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-12 17:43:40.418  1635  1834 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
07-12 17:43:40.418  1635  1834 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@358b74e2 +
07-12 17:43:40.418  1635  1834 I Prism.WidgetManager: onLoadItems() +
,07-12 17:43:40.418  5398  5398 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-12 17:43:40.448  5398  5416 W art     : Suspending all threads took: 5.284ms
,07-12 17:43:40.458  5398  5416 I art     : Background sticky concurrent mark sweep GC freed 25666(1552KB) AllocSpace objects, 6(96KB) LOS objects, 14% free, 3MB/4MB, paused 6.677ms total 48.831ms,
,07-12 17:43:40.498   989  1071 D PMS     : releaseHCC(3cdde1f8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,07-12 17:43:40.498   989  1071 D PMS     : releaseHCC(322f6d1): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,07-12 17:43:40.518  5398  5416 I art     : Background partial concurrent mark sweep GC freed 7184(420KB) AllocSpace objects, 0(0B) LOS objects, 48% free, 4MB/8MB, paused 5.912ms total 40.979ms
,07-12 17:43:40.558   989  1294 I art     : Explicit concurrent mark sweep GC freed 15418(903KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.801ms total 193.225ms
,07-12 17:43:40.568  2102  5641 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,07-12 17:43:40.588   989  1673 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5642 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,07-12 17:43:40.588   989  1673 I ActivityManager: Killing 5125:com.htc.task.gtask/u0a66 (adj 15): empty #17
07-12 17:43:40.588   989  1673 D Process : killProcessQuiet, pid=5125
07-12 17:43:40.588   989  1673 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-12 17:43:40.668   989  1770 I ActivityManager: Recipient 5125,
,07-12 17:43:40.708  2102  5641 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,07-12 17:43:40.708   989  1621 D PMS     : acquireWL(27713b32): PARTIAL_WAKE_LOCK  Icing 0x1 2102 10024 WorkSource{10024 com.google.android.gms}
,07-12 17:43:40.718  5642  5642 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-12 17:43:40.778  1635  1834 E Prism.WidgetManager: The same lists. No need to update. skip it.
,07-12 17:43:40.778  1635  1834 I Prism.WidgetManager: onLoadItems() -
07-12 17:43:40.778  1635  1834 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@358b74e2 -,
07-12 17:43:40.778  2102  4382 I Icing   : Storage manager: low false usage 1.77MB avail 3.86GB capacity 7.95GB
,07-12 17:43:40.798   989  1050 I ActivityManager: Waited long enough for: ServiceRecord{3fde1c65 u0 com.google.android.gms/.config.ConfigFetchService}
,07-12 17:43:40.808  2102  4382 W Icing   : Received bad json for section weights override -- ignoring.,
,07-12 17:43:40.828  2102  2120 I art     : Background sticky concurrent mark sweep GC freed 4796(374KB) AllocSpace objects, 6(120KB) LOS objects, 10% free, 4MB/5MB, paused 6.443ms total 32.420ms,
,07-12 17:43:40.828  2102  4382 W Icing   : Received bad json for corpus context scoring override -- ignoring.,
07-12 17:43:40.828  2102  4382 W Icing   : Received bad json for section weights override -- ignoring.
07-12 17:43:40.828  2102  4382 W Icing   : Received bad json for corpus context scoring override -- ignoring.
,07-12 17:43:40.938  2102  4382 E Icing   : Loading extension by file descriptor -1 failed
,07-12 17:43:40.958   989  1770 I ActivityManager: Killing 5162:com.google.android.setupwizard/u0a77 (adj 15): empty #17,
07-12 17:43:40.958   989  1770 D Process : killProcessQuiet, pid=5162
07-12 17:43:40.958   989  1770 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-12 17:43:41.008   989  5151 I ActivityManager: Recipient 5162
,07-12 17:43:41.048  5556  5556 V Finsky  : [1] GearheadStateMonitor.onReady: sIsProjecting:false,
,07-12 17:43:41.078  5398  5640 W jxcore-log: Initializing JXcore engine,
07-12 17:43:41.078  5398  5640 W jxcore-log: JXcore engine is ready
,07-12 17:43:41.158  5398  5640 W jxcore-log: Starting JXcore engine,
,07-12 17:43:41.198   989  1274 V AlarmManager: sending alarm PendingIntent{d70fe8a: PendingIntentRecord{f669cfb com.android.vending startService}}, i=null, t=0, cnt=1, w=1468338221194, Int=0
07-12 17:43:41.198  5556  5556 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,07-12 17:43:41.218  2102  4382 I Icing   : updateResources: need to parse f{com.google.android.gms},
,07-12 17:43:41.238  2102  2120 I art     : Background sticky concurrent mark sweep GC freed 2146(243KB) AllocSpace objects, 3(60KB) LOS objects, 6% free, 5MB/5MB, paused 6.128ms total 40.016ms,
,07-12 17:43:41.268   989  1008 D PMS     : acquireWL(24fb19ad): PARTIAL_WAKE_LOCK  AsyncService 0x1 5642 10167 null,
,07-12 17:43:41.288   989  5151 D PMS     : acquireWL(25c5b073): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 5642 10167 null
07-12 17:43:41.288   989  1570 D PMS     : releaseWL(24fb19ad): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,07-12 17:43:41.288  5398  5640 W jxcore-log: Platform android
07-12 17:43:41.288  5398  5640 W jxcore-log: 
,07-12 17:43:41.288  5398  5640 W jxcore-log: Process ARCH arm
07-12 17:43:41.288  5398  5640 W jxcore-log: 
,07-12 17:43:41.298  1908  1932 I art     : Explicit concurrent mark sweep GC freed 9858(486KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 1.369ms total 56.517ms
07-12 17:43:41.308  1908  1908 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:43:41.318  5428  5682 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE,
,07-12 17:43:41.368  1908  4409 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
07-12 17:43:41.368  1908  4409 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,07-12 17:43:41.368  1908  4409 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:43:41.368  1908  4409 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:43:41.378  1635  1635 D Prism.PackageStateRece_: action: android.intent.action.PACKAGE_ADDED,
,07-12 17:43:41.378  1908  4409 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-12 17:43:41.378  1549  5688 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.test.thalitest
07-12 17:43:41.388  1549  5688 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed
07-12 17:43:41.388  1635  1635 I ContextualWidget: package com.test.thalitest added
,07-12 17:43:41.408  2102  4382 I Icing   : Internal init done: storage state 0
,07-12 17:43:41.428   989  1570 I ActivityManager: Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5691 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a,
,07-12 17:43:41.448  1635  5690 W SystemReader: Cannot find enable_download_option, use default value instead,
,07-12 17:43:41.448  5556  5556 W Finsky  : [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,07-12 17:43:41.458  2102  4382 I Icing   : Post-init done,
07-12 17:43:41.458   989  1009 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.photos.phone.GetContentActivityAlias, state=2, flag=1, pid=5642, uid=10167, userID:0
,07-12 17:43:41.468   989  1008 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.photos.phone.SendContentActivityAlias, state=2, flag=1, pid=5642, uid=10167, userID:0,
,07-12 17:43:41.468   989  2338 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.photos.phone.SetWallpaperActivityAlias, state=2, flag=1, pid=5642, uid=10167, userID:0
,07-12 17:43:41.468  2102  4382 I Icing   : updateResources: need to parse f{com.google.android.gms}
07-12 17:43:41.468   989  1621 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.plus.phone.VideoViewActivityAlias, state=2, flag=1, pid=5642, uid=10167, userID:0,
07-12 17:43:41.468  1908  1908 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:43:41.468   989  5151 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.plus.phone.HostPhotoViewIntentActivityAlias, state=2, flag=1, pid=5642, uid=10167, userID:0
07-12 17:43:41.468   989  1650 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.plus.service.EsDreamService, state=2, flag=1, pid=5642, uid=10167, userID:0
07-12 17:43:41.468   989  1009 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.libraries.social.ingest.IngestActivity, state=2, flag=1, pid=5642, uid=10167, userID:0
,07-12 17:43:41.478   989  1624 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.libraries.social.ingest.IngestService, state=2, flag=1, pid=5642, uid=10167, userID:0
,07-12 17:43:41.488   989  5151 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.photos.service.GooglePhotoDownsyncService, state=2, flag=1, pid=5642, uid=10167, userID:0,
,07-12 17:43:41.488   989  1624 D PMS     : releaseWL(25c5b073): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,07-12 17:43:41.508   989  1294 D PMS     : releaseWL(27713b32): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,07-12 17:43:41.508  5428  5682 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 189 ms] updated apps [took 189 ms] 
,07-12 17:43:41.508  5398  5640 I jxcore-log: JXcore Cordova bridge is ready!
07-12 17:43:41.508  5398  5640 I jxcore-log: 
,07-12 17:43:41.508  5398  5640 W jxcore-log: JXcore engine is started,
07-12 17:43:41.518  1908  4409 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
07-12 17:43:41.518  1908  4409 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
07-12 17:43:41.518  1908  4409 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:43:41.518  1908  4409 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,07-12 17:43:41.518  1908  4409 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:43:41.528  5398  5555 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-12 17:43:41.528  5398  5398 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-12 17:43:41.538  5398  5640 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
07-12 17:43:41.538  5398  5640 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,07-12 17:43:41.548  5691  5691 I DeviceManagement: DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=5691 dbg=false s=true
,07-12 17:43:41.548  5398  5398 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
07-12 17:43:41.548  5398  5398 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,07-12 17:43:41.548  5691  5691 I DeviceManagement: PackageUpdateReceiver: vvv Package added: [com.test.thalitest]
,07-12 17:43:41.578   989  5151 D PMS     : acquireWL(12c18251): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 989 1000 null
07-12 17:43:41.578  5398  5398 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
07-12 17:43:41.578  5398  5398 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,07-12 17:43:41.588  5398  5555 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 36ms. Plugin should use CordovaInterface.getThreadPool().
,07-12 17:43:41.588   989  1675 W HtcSystemUPManager: HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch,
,07-12 17:43:41.608   989  1009 D PMS     : acquireWL(30caf28d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 989 1000 null
07-12 17:43:41.608   989  1009 I BatteryService: n_update end
07-12 17:43:41.608  1908  1908 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-12 17:43:41.608   989  1009 D PMS     : releaseWL(30caf28d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,07-12 17:43:41.628   989  1650 I ActivityManager: Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=5715 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a
,07-12 17:43:41.638  1635  1635 W SystemReader: Cannot find allapps_style_enabled_deafult, use default value instead
,07-12 17:43:41.638  1635  1635 I Prism.AllAppsOptionsMa_: getAllAppsAbility() true
07-12 17:43:41.638  1635  1635 W SystemReader: Cannot find support_china_sense_feature, use default value instead
07-12 17:43:41.638  1635  1635 I Prism.AllAppsOptionsMa_: removeAllAppsAbility()
07-12 17:43:41.638  1635  1635 W SystemReader: Cannot find support_china_sense_feature, use default value instead
,07-12 17:43:41.638   989  1067 D HtcPowerSaver: updateBatteryInfo,
07-12 17:43:41.638  1447  1447 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
07-12 17:43:41.638  1447  1447 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
07-12 17:43:41.648  1362  1362 D PowerUI : closing low battery warning: level=100
07-12 17:43:41.638  1447  1447 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
07-12 17:43:41.648  1362  1688 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
,07-12 17:43:41.648   989   989 D UsbnetService: BroadcastReceiver::onReceive+
07-12 17:43:41.648   989   989 D NotificationService: plugged=true pluggin=true
07-12 17:43:41.648   989   989 D UsbnetService: onReceive BATTERY_CHANGED,
07-12 17:43:41.648   989   989 D PMS     : runPSCheck
07-12 17:43:41.648   989   989 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
07-12 17:43:41.648   989   989 D HtcPowerSaver: Checking...
07-12 17:43:41.648   989   989 D UsbnetService: BroadcastReceiver::onReceive-
07-12 17:43:41.648   989   989 I HtcPowerSaver: >> updateStatus
07-12 17:43:41.648   989  1286 D WifiController: handleMessage: E msg.what=155652
07-12 17:43:41.648   989  1286 D WifiController: battery changed pluggedType: 2
07-12 17:43:41.648   989  1286 D WifiController: processMsg: ApStaDisabledState
07-12 17:43:41.648  1362  1362 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
07-12 17:43:41.648   989  1286 D WifiController: processMsg: DefaultState
07-12 17:43:41.648   989   989 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
07-12 17:43:41.648   989  1286 D WifiController: handleMessage: X
07-12 17:43:41.648   989   989 I HtcPowerSaver: << updateStatus
07-12 17:43:41.648  1635  1635 I FeedHostManager: [onResume]
07-12 17:43:41.658   989  1058 D StatusBarManagerService: setSystemUiVisibility(0x8700)
07-12 17:43:41.648  1635  1635 I FeedProviderManager: onResume
07-12 17:43:41.658   989  1058 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-12 17:43:41.648  1635  2461 I SocialFeedProvider: +onResume
07-12 17:43:41.658   989  1058 D StatusBarManagerService: hiding MENU key
07-12 17:43:41.648  1635  2461 I SocialFeedProvider: updateAccounts - Accounts is no change
07-12 17:43:41.648  1635  2461 I SocialFeedProvider: -onResume
07-12 17:43:41.648  1635  1635 I ConnectivityHelper: [getCurrentConnectionType] no network connection
07-12 17:43:41.648  1635  1635 I ContextualWidget: onResume
07-12 17:43:41.648  1635  1635 I ContextualWidget: notifyWidgetActive location size=0 user consent location=false
07-12 17:43:41.648  1635  1635 W SystemReader: Cannot find enable_suggestion_option, use default value instead
07-12 17:43:41.648  1635  1864 I ContextualWidget: handleMessage, what=1018 mode=GettingOut maxcount=8
07-12 17:43:41.648  1635  1635 I ContextualWidget: ignore uploadUsageData location=false usage data=false allowAutoUpload=true
07-12 17:43:41.648  1635  1635 W SystemReader: Cannot find enable_suggestion_option, use default value instead
07-12 17:43:41.648  1635  1635 I ContextualWidget: postSyncRecommendedApps, isReady=true allowAutoSync=true syncMode=1 isEnableRecommend=true
07-12 17:43:41.658  1635  1864 I ContextualWidget: handleMessage, what=1017 mode=GettingOut maxcount=8
07-12 17:43:41.658   989  2338 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-12 17:43:41.658   989  1678 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
07-12 17:43:41.658   989  1570 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
07-12 17:43:41.658   989  1650 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,07-12 17:43:41.678  1635  1635 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,07-12 17:43:41.678  1635  1635 I ThreadedRenderer: Defer allocateBuffers to drawing time
,07-12 17:43:41.698  1362  1362 I BatteryController: status:5 level:100 unsupport:false plugged:true,
07-12 17:43:41.698   989  1624 I InputMethodManagerService: Disable input method client, pid=5398
07-12 17:43:41.698   989  1624 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
,07-12 17:43:41.698   989  1624 I InputMethodManagerService: Enable input method client, pid=1635
07-12 17:43:41.698  1362  1362 I PhoneStatusBar: setImeWindowStatus(false,false)
,07-12 17:43:41.698  5398  5398 W IInputConnectionWrapper: reportFullscreenMode on inactive InputConnection
,07-12 17:43:41.728  1908  1932 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,07-12 17:43:41.728  1908  1932 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
07-12 17:43:41.728  1908  1932 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:43:41.728  1908  1932 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:43:41.738  5715  5715 D HtcCupdReceiver(Provider):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED,
07-12 17:43:41.738  1635  5738 D HtcTelephonyManager: wrong phone slot in non-dual projects
07-12 17:43:41.738   989  1770 D PMS     : releaseWL(12c18251): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,07-12 17:43:41.748  1908  1932 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:43:41.748   989  1770 D Process : killProcessQuiet, pid=4177,
07-12 17:43:41.748   989  1770 I ActivityManager: Killing 4177:com.android.defcontainer/u0a15 (adj 15): empty #17
07-12 17:43:41.748   989  1770 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,07-12 17:43:41.758   989  1058 D StatusBarManagerService: setSystemUiVisibility(0xc0000700),
07-12 17:43:41.758   989  1058 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-12 17:43:41.758   989  1058 D StatusBarManagerService: hiding MENU key
,07-12 17:43:41.788  1635  5738 D HtcTelephonyManager: wrong phone slot in non-dual projects,
,07-12 17:43:41.798  1635  5738 D libc    : [NET] android_getaddrinfofornet+,hn 28(0x7265636f6d6d65),sn(),hints(known),family 0,flags 4,
07-12 17:43:41.798  1635  5738 D libc    : [NET] android_getaddrinfofornet-, err=8
07-12 17:43:41.798  1635  5738 D libc    : [NET] android_getaddrinfofornet+,hn 28(0x7265636f6d6d65),sn(),hints(known),family 0,flags 1024
07-12 17:43:41.798  1635  5738 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
07-12 17:43:41.798  1635  5738 D libc    : [NET] android_getaddrinfo_proxy+
07-12 17:43:41.798  1635  5738 D libc    : [NET] android_getaddrinfo_proxy get netid:0
07-12 17:43:41.798   399  5740 D libc    : [NET] android_getaddrinfofornet+,hn 28(0x7265636f6d6d65),sn(),hints(known),family 0,flags 1024
07-12 17:43:41.798   399  5740 D libc    : [NET] _dns_getaddrinfo+, netid:0, mark:917504
07-12 17:43:41.798   399  5740 D libc    : [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
07-12 17:43:41.798   399  5740 D libc    : [NET] android_getaddrinfofornet-, err=7
07-12 17:43:41.808  1635  5738 D libc    : [NET] android_getaddrinfo_proxy-, NODATA
07-12 17:43:41.808  1635  5738 E ServerCorridor: BaseException: ServiceUnavailableException java.lang.Throwable: Unable to resolve host "recommend-prism.htcsense.com": No address associated with hostname
07-12 17:43:41.808  1635  5738 W System.err: com.htc.prism.feed.corridor.exceptions.ServiceUnavailableException: java.lang.Throwable: Unable to resolve host "recommend-prism.htcsense.com": No address associated with hostname
07-12 17:43:41.808  1635  5738 W System.err: 	at com.htc.prism.feed.corridor.RestClient.sendHTTPRequest(RestClient.java:202)
07-12 17:43:41.808  1635  5738 W System.err: 	at com.htc.prism.feed.corridor.RestClient.sendHTTPRequest(RestClient.java:107)
07-12 17:43:41.808  1635  5738 W System.err: 	at com.htc.prism.feed.corridor.RestClient.sendHTTPRequest(RestClient.java:102)
07-12 17:43:41.808  1635  5738 W System.err: 	at com.htc.prism.feed.corridor.RestClient.getString(RestClient.java:381)
07-12 17:43:41.808  1635  5738 W System.err: 	at com.htc.prism.feed.corridor.recommendation.RecommendationNService.getWelcomeAppSuggest(RecommendationNService.java:125)
07-12 17:43:41.808  1635  5738 W System.err: 	at com.htc.launcher.htcwidget.HtcContextualWidgetService.syncRecommendedApps(HtcContextualWidgetService.java:374)
07-12 17:43:41.808  1635  5738 W System.err: 	at com.htc.launcher.htcwidget.HtcContextualWidgetService.onHandleIntent(HtcContextualWidgetService.java:168)
07-12 17:43:41.808  1635  5738 W System.err: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-12 17:43:41.808  1635  5738 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:43:41.808  1635  5738 W System.err: 	at android.os.Looper.loop(Looper.java:155)
07-12 17:43:41.808  1635  5738 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 17:43:41.808  1635  5738 W System.err: Caused by: java.lang.Throwable: Unable to resolve host "recommend-prism.htcsense.com": No address associated with hostname
07-12 17:43:41.808  1635  5738 W System.err: 	at java.net.InetAddress.lookupHostByName(InetAddress.java:457)
07-12 17:43:41.808  1635  5738 W System.err: 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
07-12 17:43:41.808  1635  5738 W System.err: 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
07-12 17:43:41.808  1635  5738 W System.err: 	at com.android.okhttp.HostResolver$1.getAllByName(HostResolver.java:29)
07-12 17:43:41.808  1635  5738 W System.err: 	at com.android.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:236)
07-12 17:43:41.808  1635  5738 W System.err: 	at com.android.okhttp.internal.http.RouteSelector.next(RouteSelector.java:124)
07-12 17:43:41.808  1635  5738 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:272)
07-12 17:43:41.808  1635  5738 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:211)
07-12 17:43:41.808  1635  5738 W System.err: 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:373)
07-12 17:,43:41.808  1635  5738 W System.err: 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.connect(HttpURLConnectionImpl.java:106)
07-12 17:43:41.808  1635  5738 W System.err: 	at com.android.okhttp.internal.http.DelegatingHttpsURLConnection.connect(DelegatingHttpsURLConnection.java:89)
07-12 17:43:41.808  1635  5738 W System.err: 	at com.android.okhttp.internal.http.HttpsURLConnectionImpl.connect(HttpsURLConnectionImpl.java:25)
07-12 17:43:41.808  1635  5738 W System.err: 	at com.htc.prism.feed.corridor.RestClient.sendHTTPRequest(RestClient.java:147)
07-12 17:43:41.808  1635  5738 W System.err: 	... 10 more
,07-12 17:43:41.898   989  1294 I ActivityManager: Recipient 4177
,07-12 17:43:41.908  5713  5742 E cutils-trace: Error opening trace file: Permission denied (13)
,07-12 17:43:41.968  5713  5713 D CustomizationManager: ====startRecUseTime====
07-12 17:43:41.968  5713  5713 D htc.customization.log.level:  is 
07-12 17:43:41.968  5713  5713 W CustomizationLogLevel: Level value is invalid, use default level 2
,07-12 17:43:41.978  5208  5264 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-12 17:43:41.988   989  1050 D Process : killProcessQuiet, pid=5187
07-12 17:43:41.988   989  1050 I ActivityManager: Killing 5187:com.htc.mobiledata:remote/u0a46 (adj 15): empty #17
,07-12 17:43:41.988   989  1050 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityStack.destroyActivityLocked:3435 
,07-12 17:43:42.038  5713  5713 D CustomizationManager:  Read ACC file spent 0.041 (s),
,07-12 17:43:42.038  5713  5713 D CIDMapFileReader: Parsing tag item name = HTC__001,
07-12 17:43:42.038  5713  5713 D CIDMapFileReader: Parsing tag item name = HTC__102
07-12 17:43:42.038  5713  5713 D CIDMapFileReader: Parsing tag item name = HTC__Y13
07-12 17:43:42.038  5713  5713 D CIDMapFileReader: Parsing tag item name = HTC__032
07-12 17:43:42.048  5713  5713 D CIDMapFileReader: Parsing tag item name = HTC__M27
07-12 17:43:42.048  5713  5713 D CIDMapFileReader: Parsing tag item name = HTC__002
07-12 17:43:42.048  5713  5713 D CIDMapFileReader: Parsing tag item name = HTC__031
,07-12 17:43:42.048  5713  5713 D CIDMapFileReader: Parsing tag item name = HTC__A07
,07-12 17:43:42.048  5713  5713 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__102.xml
,07-12 17:43:42.048  5713  5713 I CustomizationCIDLoader: Parsing tag category name = system
,07-12 17:43:42.048  5713  5713 I CustomizationCIDLoader: Parsing tag category name = application
,07-12 17:43:42.048  5713  5713 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider,
07-12 17:43:42.048  5713  5713 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
07-12 17:43:42.048  5713  5713 I CustomizationCIDLoader: Parsing tag category name = AudioService
07-12 17:43:42.048  5713  5713 I CustomizationCIDLoader: Parsing tag category name = Settings
07-12 17:43:42.048  5713  5713 I CustomizationCIDLoader: Parsing tag category name = ACC
,07-12 17:43:42.048  5713  5713 I CustomizationCIDLoader: add string-array item, value = 42507,
07-12 17:43:42.048  5713  5713 I CustomizationCIDLoader: add string-array item, value = 21902
07-12 17:43:42.048  5713  5713 I CustomizationCIDLoader: add string-array item, value = 26006:26001.26002.26003
07-12 17:43:42.048  5713  5713 I CustomizationCIDLoader: add string-array item, value = 23420
07-12 17:43:42.048  5713  5713 I CustomizationCIDLoader: add string-array item, value = 22299
07-12 17:43:42.048  5713  5713 I CustomizationCIDLoader: add string-array item, value = 24002
07-12 17:43:42.048  5713  5713 I CustomizationCIDLoader: add string-array item, value = 23210
07-12 17:43:42.048  5713  5713 I CustomizationCIDLoader: add string-array item, value = 23205
07-12 17:43:42.048  5713  5713 I CustomizationCIDLoader: add string-array item, value = 23806
07-12 17:43:42.048  5713  5713 I CustomizationCIDLoader: add string-array item, value = 23430
07-12 17:43:42.048  5713  5713 I CustomizationCIDLoader: add string-array item, value = 23408
07-12 17:43:42.048  5713  5713 I CustomizationCIDLoader: add string-array item, value = 27205
07-12 17:43:42.048  5713  5713 I CustomizationCIDLoader: add string-array item, value = 42507:C:1:0
07-12 17:43:42.048  5713  5713 I CustomizationCIDLoader: add string-array item, value = 21902:C:1:0
,07-12 17:43:42.048  5713  5713 I CustomizationCIDLoader: add string-array item, value = 26006:D:1:0
07-12 17:43:42.048  5713  5713 I CustomizationCIDLoader: add string-array item, value = 23420:D:0:0
07-12 17:43:42.048  5713  5713 I CustomizationCIDLoader: add string-array item, value = 22299:D:0:0
07-12 17:43:42.048  5713  5713 I CustomizationCIDLoader: add string-array item, value = 24002:D:0:0
07-12 17:43:42.048  5713  5713 I CustomizationCIDLoader: add string-array item, value = 23210:D:2:0
07-12 17:43:42.048  5713  5713 I CustomizationCIDLoader: add string-array item, value = 23205:D:2:0
,07-12 17:43:42.048  5713  5713 I CustomizationCIDLoader: add string-array item, value = 23806:D:0:0
07-12 17:43:42.048  5713  5713 I CustomizationCIDLoader: add string-array item, value = 23430:C:1:0
07-12 17:43:42.048  5713  5713 I CustomizationCIDLoader: add string-array item, value = 23408:C:1:0
07-12 17:43:42.048  5713  5713 I CustomizationCIDLoader: add string-array item, value = 27205:C:1:0
07-12 17:43:42.048  5713  5713 D CustomizationManager:  Read CID file spent 0.084 (s)
07-12 17:43:42.048  5713  5713 D CustomizationManager:  All configurations done spent 0.084 (s)
,07-12 17:43:42.058   989  1294 I ActivityManager: Recipient 5187
,07-12 17:43:42.088   989  5151 D PackageManager: deletePackageAsUser: pkg=com.test.thalitest, pid=5713, uid=2000 userid=0,
,07-12 17:43:42.108  5398  5398 D io.jxcore.node.LifeCycleMonitor: onActivityStopped,
,07-12 17:43:42.108  5398  5398 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED,
,07-12 17:43:42.108  5398  5398 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed,
07-12 17:43:42.108  5398  5398 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
07-12 17:43:42.108  5398  5398 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:43:42.108  5398  5398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:43:42.108  5398  5398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-12 17:43:42.108  5398  5398 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-12 17:43:42.108  5398  5398 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14969dbf removed from the list
07-12 17:43:42.108  5398  5398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:43:42.108  5398  5398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@179cf3ea removed from the list
07-12 17:43:42.108  5398  5398 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:43:42.108  5398  5398 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...,
,07-12 17:43:42.158   989  1124 W PackageSettings: Skipping PackageSetting{10e71b0e com.example.hello/10374} due to missing metadata,
,07-12 17:43:42.178   989  1050 I ActivityManager: Force stopping com.test.thalitest appid=10195 user=-1: uninstall pkg
07-12 17:43:42.178   989  1050 D Process : killProcessQuiet, pid=5398
,07-12 17:43:42.178   989  1050 I ActivityManager: Killing 5398:com.test.thalitest/u0a195 (adj 9): stop com.test.thalitest
07-12 17:43:42.178   989  1050 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6372 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
,07-12 17:43:42.218  1635  2045 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,07-12 17:43:42.288   989  1673 I ActivityManager: Recipient 5398
,07-12 17:43:42.288   989  1678 I WindowState: WIN DEATH: Window{13ac731e u0 com.test.thalitest/com.test.thalitest.MainActivity},
07-12 17:43:42.288  1506  1506 E InputEventReceiver: Looper::removeFd(68) is failed, result(0), input channel 'ClientState{12b457ff uid 10195 pid 5398} (c)'
07-12 17:43:42.288   989  1286 D WifiService: Client connection lost with reason: 4
,07-12 17:43:42.388   989  1050 W ActivityManager: ProcessRecord{3175333e 5398:com.test.thalitest/u0a195} has been replaced to new process null,
,07-12 17:43:42.398   989  1124 I ActivityManager: Force stopping com.test.thalitest appid=10195 user=0: pkg removed,
,07-12 17:43:42.418   989  1673 W ActivityManager: Spurious death for ProcessRecord{3175333e 0:com.test.thalitest/u0a195}, curProc for 5398: null,
07-12 17:43:42.418   989  5151 W ActivityManager: unregisterReceiver: receiver object not existed in mRegisteredReceivers
,07-12 17:43:42.428  1447  1447 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
07-12 17:43:42.438  1447  1447 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,07-12 17:43:42.438   989  1282 V NetworkPolicy: ACTION_UID_REMOVED for uid=10195
07-12 17:43:42.438   989  1282 V NetworkPolicy: writePolicyLocked()
,07-12 17:43:42.458   989  1281 D PMS     : acquireWL(35c8eab5): PARTIAL_WAKE_LOCK  NetworkStats 0x1 989 1000 null,
,07-12 17:43:42.468   989  1276 W SystemReader: Cannot find grip_rejection_width, use default value instead
07-12 17:43:42.468   989  1570 D PMS     : acquireWL(30ff3cbb): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1835 10024 WorkSource{10024 com.google.android.gms}
07-12 17:43:42.478  1729  2034 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,07-12 17:43:42.478  1835  2178 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-12 17:43:42.478   989  5151 D PMS     : releaseWL(30ff3cbb): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,07-12 17:43:42.498  1729  2034 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
07-12 17:43:42.498   989  1047 I InputMethodManagerService: [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false,
07-12 17:43:42.498  2102  5759 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
07-12 17:43:42.508   989  1282 V NetworkPolicy: updateNetworkEnabledLocked()
07-12 17:43:42.508  2102  2102 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
07-12 17:43:42.508   989  1282 V NetworkPolicy: updateNotificationsLocked()
07-12 17:43:42.508  2102  2102 D ChimeraModuleLdr: Loading module APK com.google.android.play.games
,07-12 17:43:42.528  5556  5556 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,07-12 17:43:42.538   989  5151 D PMS     : acquireWL(165a8833): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 2102 10024 null,
,07-12 17:43:42.538  1583  1583 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,07-12 17:43:42.548  1729  2034 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,07-12 17:43:42.548  1635  1635 I art     : Explicit concurrent mark sweep GC freed 90095(6MB) AllocSpace objects, 69(4MB) LOS objects, 33% free, 32MB/48MB, paused 3.949ms total 149.685ms
,07-12 17:43:42.568   989  1281 D PMS     : releaseWL(35c8eab5): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,07-12 17:43:42.568  1729  2034 E ExternalAccountType: Unsupported attribute readOnly
,07-12 17:43:42.658  2102  2120 W art     : Suspending all threads took: 5.052ms,
,07-12 17:43:42.678   989   989 W PackageManager: Unable to load service info ResolveInfo{309130aa com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
07-12 17:43:42.678   989   989 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
07-12 17:43:42.678   989   989 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
07-12 17:43:42.678   989   989 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
07-12 17:43:42.678   989   989 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
07-12 17:43:42.678   989   989 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
07-12 17:43:42.678   989   989 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
07-12 17:43:42.678   989   989 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
07-12 17:43:42.678   989   989 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
07-12 17:43:42.678   989   989 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-12 17:43:42.678   989   989 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
07-12 17:43:42.678   989   989 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:324)
07-12 17:43:42.678   989   989 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:225)
07-12 17:43:42.678   989   989 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 17:43:42.678   989   989 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-12 17:43:42.678   989   989 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
07-12 17:43:42.678   989   989 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
07-12 17:43:42.688   989  1047 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,07-12 17:43:42.708  5556  5574 E AndroidHttpClient: Leak found
07-12 17:43:42.708  5556  5574 E AndroidHttpClient: java.lang.IllegalStateException: AndroidHttpClient created and never closed
07-12 17:43:42.708  5556  5574 E AndroidHttpClient: 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
07-12 17:43:42.708  5556  5574 E AndroidHttpClient: 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
07-12 17:43:42.708  5556  5574 E AndroidHttpClient: 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
07-12 17:43:42.708  5556  5574 E AndroidHttpClient: 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
07-12 17:43:42.708  5556  5574 E AndroidHttpClient: 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
07-12 17:43:42.708  5556  5574 E AndroidHttpClient: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
07-12 17:43:42.708  5556  5574 E AndroidHttpClient: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
07-12 17:43:42.708  5556  5574 E AndroidHttpClient: 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
07-12 17:43:42.708  5556  5574 E AndroidHttpClient: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
07-12 17:43:42.708  5556  5574 E AndroidHttpClient: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:43:42.708  5556  5574 E AndroidHttpClient: 	at android.os.Looper.loop(Looper.java:155)
07-12 17:43:42.708  5556  5574 E AndroidHttpClient: 	at android.app.ActivityThread.main(ActivityThread.java:5721)
07-12 17:43:42.708  5556  5574 E AndroidHttpClient: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 17:43:42.708  5556  5574 E AndroidHttpClient: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-12 17:43:42.708  5556  5574 E AndroidHttpClient: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
07-12 17:43:42.708  5556  5574 E AndroidHttpClient: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,07-12 17:43:42.718   989  1124 I art     : Explicit concurrent mark sweep GC freed 28737(2MB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 18MB/27MB, paused 1.940ms total 285.591ms,
,07-12 17:43:42.778  2102  2102 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) },
,07-12 17:43:42.778  2102  2102 E WorkSourceUtil: Could not find package: com.test.thalitest
,07-12 17:43:42.788  2102  2102 I ConfigFetchService: launchTask,
07-12 17:43:42.788   989  1009 D PMS     : acquireWL(344f0dd1): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 2102 10024 null
07-12 17:43:42.788   989  1294 D PMS     : releaseWL(165a8833): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,07-12 17:43:42.808   989  1124 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=5765 uid=10015 gids={50015, 9997, 1028, 1015, 1023, 2001, 1035, 5001} abi=arm64-v8a,
,07-12 17:43:42.808   989  1570 D PMS     : acquireWL(23de0d41): PARTIAL_WAKE_LOCK  Icing 0x1 2102 10024 WorkSource{10024 com.google.android.gms}
,07-12 17:43:42.818  2102  2102 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
07-12 17:43:42.818  2102  2102 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,07-12 17:43:42.818  2102  4382 E Icing   : Package com.test.thalitest not found
,07-12 17:43:42.818   989  1770 D PMS     : releaseWL(23de0d41): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,07-12 17:43:42.828  2102  2102 D ChimeraCfgMgr: Loading module com.google.android.gms.vision from APK com.google.android.gms
,07-12 17:43:42.838  2102  5763 V ConfigFetchTask: ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1VpB9u4YAmchnd7bniH3P4TCGDjhErwXoliRG_IrM8L65XdIHwTyXjXxxJag7WF_VHLOw9NMLpxdxj54ZUUmiE5BI6LbFQHcLxOo2pUTB2Tit9KwTEhcS47EPl8gbluoXV5G3Et1tkxRLcra-dFRg-kJMoBqDeRPF-FoAhv8CfbZYGoVg4cNf4LiEEYogtv-BFzkK2Ucaa2opVEtHUH_NYq6I3PWKHcW2Hq3GrY2S1N9ejfjtrml2sYmaf69VDeK6ONGbR3Ntj98MDpUkliG5smr2InLC0IlC-6Tn4eQwKPuaOGQNQ,
07-12 17:43:42.838  2102  5764 I PeopleContactsSync: CP2 sync disabled,
07-12 17:43:42.838  2102  5763 E ConfigFetchTask: failed to build request; aborting config fetch
,07-12 17:43:42.848  2102  2102 D Vision  : Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package: flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
,07-12 17:43:42.848   989  1570 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2102, uid=10024, userID:0
07-12 17:43:42.858  2102  2102 D Vision  : No vision deps
07-12 17:43:42.858   989   989 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,07-12 17:43:42.878   989  1008 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5791 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a
,07-12 17:43:42.878  1635  1834 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false,
07-12 17:43:42.878   989  1770 D PMS     : releaseWL(344f0dd1): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 null
07-12 17:43:42.878  1635  1834 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
07-12 17:43:42.878   989  1008 I ActivityManager: Killing 5236:com.htc.mobiledata/u0a46 (adj 15): empty #17
07-12 17:43:42.878  2102  2102 I ConfigFetchService: fetch service done; releasing wakelock
07-12 17:43:42.878   989  1008 D Process : killProcessQuiet, pid=5236
07-12 17:43:42.878  2102  2102 I ConfigFetchService: stopping self
07-12 17:43:42.878   989  1008 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-12 17:43:42.988   989  1770 I ActivityManager: Recipient 5236
,07-12 17:43:43.028  2102  5787 W BaseAppContext: Using Auth Proxy for data requests.
,07-12 17:43:43.028  2102  5787 W BaseAppContext: Using Auth Proxy for data requests.,
,07-12 17:43:43.048  1908  1908 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:43:43.048   989  1318 D TaskPersister: removeObsoleteFile: deleting file=4_task.xml
07-12 17:43:43.058   989  1318 D TaskPersister: removeObsoleteFile: deleting file=4_task_thumbnail.png
,07-12 17:43:43.078  2102  5787 W BaseAppContext: Using Auth Proxy for data requests.
,07-12 17:43:43.088  1908  4410 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
07-12 17:43:43.088  1908  4410 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
07-12 17:43:43.088  1908  4410 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:43:43.088  1908  4410 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:43:43.098  1908  4410 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:43:43.098  2102  5787 W BaseAppContext: Using Auth Proxy for data requests.
,07-12 17:43:43.108  2102  5787 W BaseAppContext: Using Auth Proxy for data requests.
07-12 17:43:43.108  5556  5556 W Finsky  : [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,07-12 17:43:43.118  5556  5556 D Finsky  : [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,07-12 17:43:43.128  5556  5556 D Finsky  : [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,07-12 17:43:43.128  2102  5787 W BaseAppContext: Using Auth Proxy for data requests.
,07-12 17:43:43.128  5556  5556 D Finsky  : [1] DailyHygiene.reschedule: Giving up. (failures=6)
,07-12 17:43:43.228  1835  4226 D DeviceConnectionService: client connected with version: 7571000
,07-12 17:43:43.228   989  1294 D Process : killProcessQuiet, pid=3690
,07-12 17:43:43.228   989  1294 I ActivityManager: Killing 3690:com.htc.sense.mms/u0a64 (adj 15): empty #17
07-12 17:43:43.228   989  1294 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-12 17:43:43.388   989  1009 I ActivityManager: Recipient 3690
,07-12 17:43:43.438   989  1294 I ActivityManager: Killing 5208:com.google.android.gm/u0a106 (adj 15): empty #18,
07-12 17:43:43.448   989  1294 D Process : killProcessQuiet, pid=5208
07-12 17:43:43.448   989  1294 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-12 17:43:43.548   989  2338 I ActivityManager: Recipient 5208,
,07-12 17:43:43.578  1835  5816 W FileUtils: Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,07-12 17:43:43.578  1835  5816 W ServiceConnection: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/service.connections: open failed: EROFS (Read-only file system),
07-12 17:43:43.578  1835  5816 W ServiceConnection: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-12 17:43:43.578  1835  5816 W ServiceConnection: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-12 17:43:43.578  1835  5816 W ServiceConnection: 	at android.app.ContextImpl.openFileOutput(ContextImpl.java:1114)
07-12 17:43:43.578  1835  5816 W ServiceConnection: 	at android.content.ContextWrapper.openFileOutput(ContextWrapper.java:181)
07-12 17:43:43.578  1835  5816 W ServiceConnection: 	at com.google.android.gms.common.internal.cm.b(SourceFile:80)
07-12 17:43:43.578  1835  5816 W ServiceConnection: 	at com.google.android.gms.common.internal.cm.a(SourceFile:27)
07-12 17:43:43.578  1835  5816 W ServiceConnection: 	at com.google.android.gms.common.internal.cn.run(SourceFile:64)
07-12 17:43:43.578  1835  5816 W ServiceConnection: 	at java.lang.Thread.run(Thread.java:818)
07-12 17:43:43.578  1835  5816 W ServiceConnection: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-12 17:43:43.578  1835  5816 W ServiceConnection: 	at libcore.io.Posix.open(Native Method)
07-12 17:43:43.578  1835  5816 W ServiceConnection: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-12 17:43:43.578  1835  5816 W ServiceConnection: 	at libcore.io.IoBridge.open(IoBridge.java:442)
,07-12 17:43:43.578  1835  5816 W ServiceConnection: 	... 7 more
,07-12 17:43:43.718  5791  5791 I GAv4    : Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:,
07-12 17:43:43.718  5791  5791 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-12 17:43:43.718  5791  5791 I GAv4    :   adb logcat -s GAv4
,07-12 17:43:43.738  5791  5791 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,07-12 17:43:43.758  5791  5791 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
07-12 17:43:43.758  5791  5823 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak,
07-12 17:43:43.758  5791  5823 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,07-12 17:43:43.758  5791  5824 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-12 17:43:43.758  5791  5823 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,07-12 17:43:43.778  5791  5824 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
,07-12 17:43:43.778  5791  5824 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223),
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: ,	at fdw$a.getWritableDatabase(Unknown Source)
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: 	at fdw.g(Unknown Source)
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: 	at fdw.a(Unknown Source)
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: 	at fdw.e(Unknown Source)
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: 	at fdy.b(Unknown Source)
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: 	at feb.run(Unknown Source)
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: 	at gir$c.run(Unknown Source)
,07-12 17:43:43.778  5791  5824 E GAv4    : Opening the database failed, dropping the table and recreating it
07-12 17:43:43.778  5791  5823 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: 	,at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: 	at fdw$a.getWritableDatabase(Unknown Source)
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: 	at fdw.g(Unknown Source)
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: 	at fdw.a(Unknown Source)
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: 	at fdw.e(Unknown Source)
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: 	at fdy.b(Unknown Source)
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: 	at feb.run(Unknown Source)
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-12 17:43:43.778  5791  5824 E SQLiteDatabase: 	at gir$c.run(Unknown Source)
,07-12 17:43:43.778  5791  5824 E GAv4    : Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-12 17:43:43.778  5791  5824 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-12 17:43:43.778  5791  5823 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
07-12 17:43:43.778  5791  5824 E GAv4    : Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-12 17:43:43.778  5791  5823 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
07-12 17:43:43.788  5791  5823 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,07-12 17:43:43.788  5791  5791 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.45
,07-12 17:43:43.818  5791  5825 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.,
07-12 17:43:43.818  5791  5825 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-12 17:43:43.818  5791  5825 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-12 17:43:43.818  5791  5825 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-12 17:43:43.818  5791  5825 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-12 17:43:43.818  5791  5825 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-12 17:43:43.818  5791  5825 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-12 17:43:43.818  5791  5825 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-12 17:43:43.818  5791  5825 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
07-12 17:43:43.818  5791  5825 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
07-12 17:43:43.818  5791  5825 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
07-12 17:43:43.818  5791  5825 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
,07-12 17:43:43.818  5791  5825 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-12 17:43:43.818  5791  5825 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-12 17:43:43.818  5791  5825 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-12 17:43:43.818  5791  5825 E SQLiteDatabase: 	at aev.getWritableDatabase(PG:238)
07-12 17:43:43.818  5791  5825 E SQLiteDatabase: 	at ael.a(PG:1521)
07-12 17:43:43.818  5791  5825 E SQLiteDatabase: 	at hix$a.a(PG:125)
07-12 17:43:43.818  5791  5825 E SQLiteDatabase: 	at aen.run(PG:536)
,07-12 17:43:43.858  2102  5787 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games,
07-12 17:43:43.858  2102  5787 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,07-12 17:43:43.878  2102  5787 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/games_3a3529a.db'.,
07-12 17:43:43.878  2102  5787 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-12 17:43:43.878  2102  5787 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-12 17:43:43.878  2102  5787 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-12 17:43:43.878  2102  5787 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-12 17:43:43.878  2102  5787 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-12 17:43:43.878  2102  5787 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-12 17:43:43.878  2102  5787 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-12 17:43:43.878  2102  5787 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
07-12 17:43:43.878  2102  5787 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
07-12 17:43:43.878  2102  5787 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
07-12 17:43:43.878  2102  5787 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
07-12 17:43:43.878  2102  5787 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-12 17:43:43.878  2102  5787 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-12 17:43:43.878  2102  5787 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-12 17:43:43.878  2102  5787 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-12 17:43:43.878  2102  5787 E SQLiteDatabase: 	at com.google.android.gms.chimera.BaseGmsContentProvider.query(BaseGmsContentProvider.java:191)
07-12 17:43:43.878  2102  5787 E SQLiteDatabase: 	at com.google.android.chimera.ContentProviderProxy.query(SourceFile:345)
07-12 17:43:43.878  2102  5787 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:960)
07-12 17:43:43.878  2102  5787 E SQLiteDatabase: 	at com.google.android.chimera.ContentProviderProxy.superQuery(SourceFile:477)
07-12 17:43:43.878  2102  5787 E SQLiteDatabase: 	,at com.google.android.chimera.ContentProvider.query(SourceFile:142)
07-12 17:43:43.878  2102  5787 E SQLiteDatabase: 	at com.google.android.chimera.ContentProviderProxy.query(SourceFile:357)
07-12 17:43:43.878  2102  5787 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
07-12 17:43:43.878  2102  5787 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:491)
07-12 17:43:43.878  2102  5787 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:435)
07-12 17:43:43.878  2102  5787 E SQLiteDatabase: 	at com.google.android.gms.games.broker.AccountAgent.getAccountName(AccountAgent.java:80)
07-12 17:43:43.878  2102  5787 E SQLiteDatabase: 	at com.google.android.gms.games.broker.DataBroker.getClientContextsForAllDatastores(DataBroker.java:3442)
07-12 17:43:43.878  2102  5787 E SQLiteDatabase: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:24)
07-12 17:43:43.878  2102  5787 E SQLiteDatabase: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
07-12 17:43:43.878  2102  5787 E SQLiteDatabase: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
07-12 17:43:43.878  2102  5787 E SQLiteDatabase: 	at jav,a.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-12 17:43:43.878  2102  5787 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-12 17:43:43.878  2102  5787 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-12 17:43:43.878  2102  5787 E SQLiteOpenHelper: Couldn't open games_3a3529a.db for writing (will try read-only):
07-12 17:43:43.878  2102  5787 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-12 17:43:43.878  2102  5787 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-12 17:43:43.878  2102  5787 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-12 17:43:43.878  2102  5787 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-12 17:43:43.878  2102  5787 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-12 17:43:43.878  2102  5787 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-12 17:43:43.878  2102  5787 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-12 17:43:43.878  2102  5787 E SQLiteOpenHelper: ,	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
07-12 17:43:43.878  2102  5787 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
07-12 17:43:43.878  2102  5787 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
07-12 17:43:43.878  2102  5787 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
07-12 17:43:43.878  2102  5787 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-12 17:43:43.878  2102  5787 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-12 17:43:43.878  2102  5787 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-12 17:43:43.878  2102  5787 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-12 17:43:43.878  2102  5787 E SQLiteOpenHelper: 	at com.google.android.gms.chimera.BaseGmsContentProvider.query(BaseGmsContentProvider.java:191)
07-12 17:43:43.878  2102  5787 E SQLiteOpenHelper: 	at com.google.android.chimera.ContentProviderProxy.query(SourceFile:345)
07-12 17:43:43.878  2102  5787 E SQLiteOpenHelper: 	at android.content.ContentProvider.query(ContentProvider.java:960)
07-12 17:43:43.878  2102  5787 E SQLiteOpenHelper: 	at com.google.android.chimera.ContentProviderProxy.superQuery(SourceFile:477)
07-12 17:43:43.878  2102  5787 E SQLiteOpenHelper: 	at com.google.android.chimera.ContentProvider.query(SourceFile:142)
07-12 17:43:43.878  2102  5787 E SQLiteOpenHelper: 	at com.google.android.chimera.ContentProviderProxy.query(SourceFile:357)
07-12 17:43:43.878  2102  5787 E SQLiteOpenHelper: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
07-12 17:43:43.878  2102  5787 E SQLiteOpenHelper: 	,at android.content.ContentResolver.query(ContentResolver.java:491)
07-12 17:43:43.878  2102  5787 E SQLiteOpenHelper: 	at android.content.ContentResolver.query(ContentResolver.java:435)
07-12 17:43:43.878  2102  5787 E SQLiteOpenHelper: 	at com.google.android.gms.games.broker.AccountAgent.getAccountName(AccountAgent.java:80)
07-12 17:43:43.878  2102  5787 E SQLiteOpenHelper: 	at com.google.android.gms.games.broker.DataBroker.getClientContextsForAllDatastores(DataBroker.java:3442)
07-12 17:43:43.878  2102  5787 E SQLiteOpenHelper: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:24)
07-12 17:43:43.878  2102  5787 E SQLiteOpenHelper: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
07-12 17:43:43.878  2102  5787 E SQLiteOpenHelper: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
07-12 17:43:43.878  2102  5787 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-12 17:43:43.878  2102  5787 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-12 17:43:43.878  2102  5787 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
07-12 17:43:43.878  2102  5787 W SQLiteOpenHelper: Opened games_3a3529a.db in read-only mode,
,07-12 17:43:43.888  2102  5828 E AndroidRuntime: FATAL EXCEPTION: GamesProviderWorker
07-12 17:43:43.888  2102  5828 E AndroidRuntime: Process: com.google.android.gms, PID: 2102
07-12 17:43:43.888  2102  5828 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,07-12 17:43:43.888  2102  5828 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-12 17:43:43.888  2102  5828 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-12 17:43:43.888  2102  5828 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-12 17:43:43.888  2102  5828 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-12 17:43:43.888  2102  5828 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
07-12 17:43:43.888  2102  5828 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:823)
07-12 17:43:43.888  2102  5828 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
07-12 17:43:43.888  2102  5828 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-12 17:43:43.888  2102  5828 E AndroidRuntime: 	at com.google.android.gms.games.provider.ImageStore.initialize(ImageStore.java:149)
07-12 17:43:43.888  2102  5828 E AndroidRuntime: 	at com.google.android.gms.games.provider.ImageStore.<init>(ImageStore.java:78)
07-12 17:43:43.888  2102  5828 E AndroidRuntime: 	at com.google.android.gms.games.provider.GamesDataStore.initialize(GamesDataStore.java:111)
07-12 17:43:43.888  2102  5828 E AndroidRuntime: 	at com.google.android.gms.games.provider.PlayGamesContentProvider.performBackgroundTask(PlayGamesContentProvider.java:1577)
07-12 17:43:43.888  2102  5828 E AndroidRuntime: 	at com.google.android.gms.games.provider.PlayGamesContentProvider$1.handleMessage(PlayGamesContentProvider.java:1510)
07-12 17:43:43.888  2102  5828 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:43:43.888  2102  5828 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
07-12 17:43:43.888  2102  5828 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 17:43:43.888   989  5151 E ActivityManager: App crashed! Process: com.google.android.gms
,07-12 17:43:43.898   989  5830 E DropBoxManagerService: Can't write: system_app_crash
07-12 17:43:43.898   989  5830 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop114.tmp: open failed: EROFS (Read-only file system)
07-12 17:43:43.898   989  5830 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-12 17:43:43.898   989  5830 E DropBoxManagerService: 	,at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-12 17:43:43.898   989  5830 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-12 17:43:43.898   989  5830 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
07-12 17:43:43.898   989  5830 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-12 17:43:43.898   989  5830 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12663)
07-12 17:43:43.898   989  5830 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-12 17:43:43.898   989  5830 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-12 17:43:43.898   989  5830 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-12 17:43:43.898   989  5830 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-12 17:43:43.898   989  5830 E DropBoxManagerService: ,	... 5 more
,07-12 17:43:43.928   989  1058 D StatusBarManagerService: setSystemUiVisibility(0xc0000000),
07-12 17:43:43.928   989  1058 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-12 17:43:43.928   989  1058 D StatusBarManagerService: hiding MENU key
,07-12 17:43:43.938   989  1621 D VoldConnector: SND -> {20 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/}
,07-12 17:43:43.938   387   675 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
,07-12 17:43:43.938  5791  5832 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache
07-12 17:43:43.938  5791  5824 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
,07-12 17:43:43.938  5791  5824 E GAv4    : Job execution failed: android.database.sqlite.SQLiteException: Database open failed
,07-12 17:43:43.938  5791  5823 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
07-12 17:43:43.938  5791  5823 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
07-12 17:43:43.938  5791  5824 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
07-12 17:43:43.938  5791  5824 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
,07-12 17:43:43.948  5791  5824 E GAv4    : Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
07-12 17:43:43.948  5791  5824 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
07-12 17:43:43.948  5791  5824 E GAv4    : Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
,07-12 17:43:43.948  5791  5824 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
07-12 17:43:43.948  5791  5825 E GAv4    : syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
07-12 17:43:43.948  5791  5825 E CAKEMIX_CRASHED: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-12 17:43:43.948  5791  5825 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-12 17:43:43.948  5791  5825 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-12 17:43:43.948  5791  5825 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-12 17:43:43.948  5791  5825 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-12 17:43:43.948  5791  5825 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-12 17:43:43.948  5791  5825 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-12 17:43:43.948  5791  5825 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
07-12 17:43:43.948  5791  5825 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
07-12 17:43:43.948  5791  5825 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
07-12 17:43:43.948  5791  5825 E CAKEMIX_CRASHED: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
07-12 17:43:43.948  5791  5825 E CAKEMIX_CRASHED: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-12 17:43:43.948  5791  5825 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-12 17:43:43.948  5791  5825 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-12 17:43:43.948  5791  5825 E CAKEMIX_CRASHED: 	at aev.getWritableDatabase(PG:238)
07-12 17:43:43.948  5791  5825 E CAKEMIX_CRASHED: 	at ael.a(PG:1521)
07-12 17:43:43.948  5791  5825 E CAKEMIX_CRASHED: 	at hix$a.a(PG:125)
07-12 17:43:43.948  5791  5825 E CAKEMIX_CRASHED: 	at aen.run(PG:536)
07-12 17:43:43.948  5791  5823 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
07-12 17:43:43.948  5791  5823 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
07-12 17:43:43.948  5791  5823 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak,
07-12 17:43:43.948  5791  5832 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
07-12 17:43:43.948  5791  5832 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-12 17:43:43.948  5791  5832 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-12 17:43:43.948  5791  5832 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-12 17:43:43.948  5791  5832 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-12 17:43:43.948  5791  5832 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-12 17:43:43.948  5791  5832 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-12 17:43:43.948  5791  5832 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-12 17:43:43.948  5791  5832 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
07-12 17:43:43.948  5791  5832 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
07-12 17:43:43.948  5791  5832 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
07-12 17:43:43.948  5791  5832 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
07-12 17:43:43.948  5791  5832 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-12 17:43:43.948  5791  5832 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-12 17:43:43.948  5791  5832 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-12 17:43:43.948  5791  5832 E SQLiteDatabase: 	at aev.getWritableDatabase(PG:238)
07-12 17:43:43.948  5791  5832 E SQLiteDatabase: 	at ael.a(PG:1521)
07-12 17:43:43.948  5791  5832 E SQLiteDatabase: 	at hix$a.a(PG:125)
07-12 17:43:43.948  5791  5832 E SQLiteDatabase: 	at aej.c(PG:139)
07-12 17:43:43.948  5791  5832 E SQLiteDatabase: 	at aej.b(PG:398)
07-12 17:43:43.948  5791  5832 E SQLiteDatabase: 	at agf.f(PG:417)
07-12 17:43:43.948  5791  5832 E SQLiteDatabase: 	at oe.run(PG:1112)
07-12 17:43:43.948  5791  5832 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
07-12 17:43:43.948  5791  5832 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 17:43:43.948  5791  5832 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,07-12 17:43:43.948  5791  5832 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-12 17:43:43.948  5791  5832 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-12 17:43:43.948  5791  5823 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
07-12 17:43:43.948  5791  5823 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
07-12 17:43:43.948  5791  5823 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
07-12 17:43:43.948  5791  5823 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
07-12 17:43:43.948  5791  5823 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
07-12 17:43:43.948  5791  5832 E AbstractDatabaseInstance: Failed to delete from CachedSearch133
07-12 17:43:43.948  5791  5832 E AbstractDatabaseInstance: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-12 17:43:43.948  5791  5832 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-12 17:43:43.948  5791  5832 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-12 17:43:43.948  5791  5832 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-12 17:43:43.948  5791  5832 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-12 17:43:43.948  5791  5832 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-12 17:43:43.948  5791  5832 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-12 17:43:43.948  5791  5832 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
07-12 17:43:43.948  5791  5832 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
07-12 17:43:43.948  5791  5832 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
07-12 17:43:43.948  5791  5832 E AbstractDatabaseInstance: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
07-12 17:43:43.948  5791  5832 E AbstractDatabaseInstance: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-12 17:43:43.948  5791  5832 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-12 17:43:43.948  5791  5832 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-12 17:43:43.948  5791  5832 E AbstractDatabaseInstance: 	at aev.getWritableDatabase(PG:238)
07-12 17:43:43.948  5791  5832 E AbstractDatabaseInstance: 	at ael.a(PG:1521)
07-12 17:43:43.948  5791  5832 E AbstractDatabaseInstance: 	at hix$a.a(PG:125)
07-12 17:43:43.948  5791  5832 E AbstractDatabaseInstance,: 	at aej.c(PG:139)
07-12 17:43:43.948  5791  5832 E AbstractDatabaseInstance: 	at aej.b(PG:398)
07-12 17:43:43.948  5791  5832 E AbstractDatabaseInstance: 	at agf.f(PG:417)
07-12 17:43:43.948  5791  5832 E AbstractDatabaseInstance: 	at oe.run(PG:1112)
07-12 17:43:43.948  5791  5832 E AbstractDatabaseInstance: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
07-12 17:43:43.948  5791  5832 E AbstractDatabaseInstance: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 17:43:43.948  5791  5832 E AbstractDatabaseInstance: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-12 17:43:43.948  5791  5832 E AbstractDatabaseInstance: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-12 17:43:43.948  5791  5832 E AbstractDatabaseInstance: 	at java.lang.Thread.run(Thread.java:818)
07-12 17:43:43.958   989  1624 D PMS     : acquireWL(f59b8): PARTIAL_WAKE_LOCK  AsyncService 0x1 5642 10167 null
07-12 17:43:43.968   989  1294 D PMS     : acquireWL(c9092f6): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 5642 10167 null
07-12 17:43:43.968   989  2338 D PMS     : releaseWL(f59b8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
07-12 17:43:43.968   989  1570 I ActivityManager: Waited long enough for: ServiceRecord{3fa69658 u0 com.htc.club/com.mcrm.autonotification.NotificationService}
07-12 17:43:43.998  5791  5833 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-12 17:43:43.998  5791  5833 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-12 17:43:44.018   989  1678 I ActivityManager: START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10101 pid 5791 on display 0
,07-12 17:43:44.028   989  1624 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.photos.phone.GetContentActivityAlias, state=2, flag=1, pid=5642, uid=10167, userID:0
07-12 17:43:44.028   989  1621 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.photos.phone.SendContentActivityAlias, state=2, flag=1, pid=5642, uid=10167, userID:0
07-12 17:43:44.028   989  2338 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.photos.phone.SetWallpaperActivityAlias, state=2, flag=1, pid=5642, uid=10167, userID:0
,07-12 17:43:44.028   989  1673 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.plus.phone.VideoViewActivityAlias, state=2, flag=1, pid=5642, uid=10167, userID:0
07-12 17:43:44.028   989  1008 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.plus.phone.HostPhotoViewIntentActivityAlias, state=2, flag=1, pid=5642, uid=10167, userID:0
,07-12 17:43:44.028   989  1570 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.plus.service.EsDreamService, state=2, flag=1, pid=5642, uid=10167, userID:0
,07-12 17:43:44.038   989  1650 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.libraries.social.ingest.IngestActivity, state=2, flag=1, pid=5642, uid=10167, userID:0
,07-12 17:43:44.038   989  1294 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.libraries.social.ingest.IngestService, state=2, flag=1, pid=5642, uid=10167, userID:0
,07-12 17:43:44.038   989  1770 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.photos.service.GooglePhotoDownsyncService, state=2, flag=1, pid=5642, uid=10167, userID:0
,07-12 17:43:44.038   989  1650 D PMS     : releaseWL(c9092f6): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,07-12 17:43:44.058   989  1678 D PMS     : acquireWL(3428cb93): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 989 1000 null,
,07-12 17:43:44.068  5791  5825 D Process : killProcess, pid=5791
,07-12 17:43:44.068  5791  5825 D Process : vf.uncaughtException:213 fct.uncaughtException:0 java.lang.ThreadGroup.uncaughtException:693 
,07-12 17:43:44.068   989  1060 I AnimationUtil: isHTCRecent(Drive/Recent screens.)/10
,07-12 17:43:44.078  1635  1635 I FeedHostManager: [onPause]
07-12 17:43:44.078  1635  1635 I FeedProviderManager: onPause
07-12 17:43:44.078  1635  1635 I FeedHostManager: [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@14fb52c5
07-12 17:43:44.078  1635  2461 I SocialFeedProvider: +onPause
07-12 17:43:44.078  1635  2461 I SocialFeedProvider: -onPause
,07-12 17:43:44.078  1635  1635 I ContextualWidget: onPause
07-12 17:43:44.078  1635  1635 I ContextualWidget: notifyWidgetDeactive
07-12 17:43:44.078   989  1675 W HtcSystemUPManager: HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
07-12 17:43:44.078   385   385 E lowmemorykiller: Error writing /proc/5791/oom_score_adj; errno=22
07-12 17:43:44.078   989  1650 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
07-12 17:43:44.088   989  1650 E ActivityManager: TransactionSize: scheduleLaunchActivity(), TransactionTooLargeException, data size = 4316, Intent = Intent { act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras) }
,07-12 17:43:44.088   989  1650 W ActivityManager: Exception when starting activity com.google.android.apps.docs/.app.ErrorNotificationActivity,
07-12 17:43:44.088   989  1650 W ActivityManager: android.os.TransactionTooLargeException
07-12 17:43:44.088   989  1650 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
07-12 17:43:44.088   989  1650 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:504)
07-12 17:43:44.088   989  1650 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleLaunchActivity(ApplicationThreadNative.java:851)
07-12 17:43:44.088   989  1650 W ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.realStartActivityLocked(ActivityStackSupervisor.java:1203)
07-12 17:43:44.088   989  1650 W ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1303)
07-12 17:43:44.088   989  1650 W ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2027)
07-12 17:43:44.088   989  1650 W ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1565)
07-12 17:43:44.088   989  1650 W ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2536)
07-12 17:43:44.088   989  1650 W ActivityManager: 	at com.android.server.am.ActivityStack.completePauseLocked(ActivityStack.java:1065)
07-12 17:43:44.088   989  1650 W ActivityManager: 	at com.android.server.am.ActivityStack.activityPausedLocked(ActivityStack.java:963)
07-12 17:43:44.088   989  1650 W ActivityManager: 	at com.android.server.am.ActivityManagerService.activityPaused(ActivityManagerService.java:6887)
07-12 17:43:44.088   989  1650 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:518)
07-12 17:43:44.088   989  1650 W ActivityManager: ,	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
07-12 17:43:44.088   989  1650 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:454)
,07-12 17:43:44.188   989  2338 I ActivityManager: Recipient 5791,
,07-12 17:43:44.218   989  1650 I ActivityManager: Start proc com.google.android.apps.docs for activity com.google.android.apps.docs/.app.ErrorNotificationActivity: pid=5836 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a
,07-12 17:43:44.218   989  2338 W ActivityManager: Spurious death for ProcessRecord{36fb3eed 5836:com.google.android.apps.docs/u0a101}, curProc for 5791: null
,07-12 17:43:44.228  1635  1635 I TrimMemoryManager: [trimMemory] 20,
07-12 17:43:44.228  4955  4955 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,07-12 17:43:44.248  5428  5848 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,07-12 17:43:44.258  4955  5855 I DFPI.ApkInstallService: onHandleIntent
07-12 17:43:44.258  4955  5855 I DFPI.ApkInstallService: Media Scan Finished Case 
,07-12 17:43:44.258  4955  5855 D DFPI.ApkInstallService: check CID = HTC__102
07-12 17:43:44.258  4955  5855 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
,07-12 17:43:44.278   989  1058 D StatusBarManagerService: setSystemUiVisibility(0x8000),
07-12 17:43:44.278   989  1058 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-12 17:43:44.278   989  1058 D StatusBarManagerService: hiding MENU key
,07-12 17:43:44.288  5007  5007 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,07-12 17:43:44.298  5007  5007 I SoundPicker: SoundPickerReceiver [onReceive] startService
,07-12 17:43:44.298  5007  5859 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
,07-12 17:43:44.298  5007  5859 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
07-12 17:43:44.298  5007  5859 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
07-12 17:43:44.298  5007  5859 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-12 17:43:44.298  5007  5859 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
07-12 17:43:44.298  5007  5859 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-12 17:43:44.298  5007  5859 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-12 17:43:44.298  5007  5859 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
07-12 17:43:44.298  5007  5859 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
,07-12 17:43:44.298  5007  5859 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-12 17:43:44.298  5007  5859 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
,07-12 17:43:44.298  5007  5859 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-12 17:43:44.298  5007  5859 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-12 17:43:44.298  5007  5859 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-12 17:43:44.298  5007  5859 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-12 17:43:44.298  5007  5859 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
,07-12 17:43:44.298  5007  5859 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5,
07-12 17:43:44.298  5007  5859 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
,07-12 17:43:44.298  5428  5848 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
07-12 17:43:44.298  5007  5859 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
07-12 17:43:44.298  5007  5859 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
07-12 17:43:44.298  5007  5859 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
07-12 17:43:44.298  5007  5859 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
07-12 17:43:44.298  5007  5859 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
07-12 17:43:44.298  5007  5859 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
07-12 17:43:44.298  5007  5859 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
,07-12 17:43:44.298  5007  5859 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-12 17:43:44.298  5007  5859 I SoundPicker: TurnFileToMediaUriService [checkFileExistence]
07-12 17:43:44.298  5007  5859 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-12 17:43:44.298  5007  5859 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
07-12 17:43:44.298  5007  5859 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
07-12 17:43:44.298  5428  5848 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle: 0x55734f8b10
07-12 17:43:44.298  4917  4977 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.music/shared_prefs/store.preferences.xml to backup file /data/data/com.google.android.music/shared_prefs/store.preferences.xml.bak
,07-12 17:43:44.328   989  1008 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5861 uid=10106 gids={50106, 9997, 3003, 1028, 1015} abi=arm64-v8a
,07-12 17:43:44.368   989  2338 I ActivityManager: Start proc com.google.android.googlequicksearchbox:crash_report for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService: pid=5881 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
,07-12 17:43:44.368  5007  5859 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,07-12 17:43:44.378  5007  5859 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac,
07-12 17:43:44.378  1635  1834 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
07-12 17:43:44.378  1635  1834 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@358b74e2 +
07-12 17:43:44.378  1635  1834 I Prism.WidgetManager: onLoadItems() +
07-12 17:43:44.378  5007  5859 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-12 17:43:44.378  5007  5859 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-12 17:43:44.378  5007  5859 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
07-12 17:43:44.378  5007  5859 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
07-12 17:43:44.388  5428  5848 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
07-12 17:43:44.388  5428  5848 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
07-12 17:43:44.388  5428  5848 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 5428
07-12 17:43:44.388  5428  5848 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-12 17:43:44.388  5428  5848 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
07-12 17:43:44.388  5428  5848 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
07-12 17:43:44.388  5428  5848 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
07-12 17:43:44.388  5428  5848 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
07-12 17:43:44.388  5428  5848 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
07-12 17:43:44.388  5428  5848 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
07-12 17:43:44.388  5428  5848 E AndroidRuntime: 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:85)
07-12 17:43:44.388  5428  5848 E AndroidRuntime: 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:623)
07-12 17:43:44.388  5428  5848 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
07-12 17:43:44.388  5428  5848 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
07-12 17:43:44.388  5428  5848 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1354)
07-12 17:43:44.388  5428  5848 E AndroidRuntime: 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
07-12 17:43:44.388  5428  5848 E AndroidRuntime: 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
07-12 17:43:44.388  5428  5848 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
07-12 17:43:44.388  5428  5848 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
07-12 17:43:44.388  5428  5848 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201),
07-12 17:43:44.388  5428  5848 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-12 17:43:44.388  5428  5848 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:43:44.388  5428  5848 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
07-12 17:43:44.388  5428  5848 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-12 17:43:44.388   989  2338 E ActivityManager: App crashed! Process: com.google.android.googlequicksearchbox:search
,07-12 17:43:44.398   989  5901 E DropBoxManagerService: Can't write: system_app_crash
07-12 17:43:44.398   989  5901 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop115.tmp: open failed: EROFS (Read-only file system)
07-12 17:43:44.398   989  5901 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-12 17:43:44.398   989  5901 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-12 17:43:44.398   989  5901 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-12 17:43:44.398   989  5901 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
07-12 17:43:44.398   989  5901 E DropBoxManagerService: 	,at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-12 17:43:44.398   989  5901 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12663)
07-12 17:43:44.398   989  5901 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-12 17:43:44.398   989  5901 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-12 17:43:44.398   989  5901 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-12 17:43:44.398   989  5901 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-12 17:43:44.398   989  5901 E DropBoxManagerService: 	,... 5 more
,07-12 17:43:44.438  5007  5859 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,07-12 17:43:44.438  1635  1834 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,07-12 17:43:44.448  5007  5859 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-12 17:43:44.448  5007  5859 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-12 17:43:44.448  5007  5859 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-12 17:43:44.448  5007  5859 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-12 17:43:44.448  5007  5859 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-12 17:43:44.458  5007  5859 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac

```
