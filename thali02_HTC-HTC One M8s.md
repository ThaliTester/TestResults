#### Test 757892686f45c73_thali02_HTC-HTC One M8s Logs


```
--------- beginning of system
07-26 15:19:41.462  1010  1810 I ActivityManager: Recipient 5221
07-26 15:19:41.502  1010  1047 I ActivityManager: Waited long enough for: ServiceRecord{3c542023 u0 com.google.android.gms/.config.ConfigFetchService}
,--------- beginning of main
07-26 15:19:41.552  1010  1668 D Process : killProcessQuiet, pid=5274
07-26 15:19:41.552  1010  1668 I ActivityManager: Killing 5274:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17
07-26 15:19:41.552  1010  1668 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
07-26 15:19:41.562  5648  5648 I EASAppSvc: [ NA ]onCreate
07-26 15:19:41.572  5648  5701 I VersionUtil: [ NA ]setIsFOTAing: true
07-26 15:19:41.582  5648  5701 I VersionUtil: [ NA ]onUpgrade: current version=100, latest version=100
07-26 15:19:41.582  5648  5701 I VersionUtil: [ NA ]setIsFOTAing: false
07-26 15:19:41.592  5648  5701 D HtcAdjCursorFactory: Set CursorWindow size to: 4194304 KB, Tid: 5701
07-26 15:19:41.612  1010  1478 I ActivityManager: Recipient 5274
07-26 15:19:41.672  1010  1283 D WifiService: New client listening to asynchronous messages
07-26 15:19:41.682  1010  1010 E WifiTrafficPoller: ADD_CLIENT: 8
07-26 15:19:41.702  1010  1810 I ActivityManager: Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=5710 uid=10079 gids={50079, 9997, 5001, 1028, 1015} abi=arm64-v8a
07-26 15:19:41.712  5343  5706 D ORMLib  : put()
07-26 15:19:41.722   451   451 I art     : Explicit concurrent mark sweep GC freed 8648(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 265us total 29.272ms
07-26 15:19:41.742  1010  1047 W BroadcastQueue: Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_MEDIA due to registered receiver BroadcastFilter{190fa4a9 u0 ReceiverList{17ebc030 5673 com.htc.musicenhancer/10049/u0 remote:18968973}}
07-26 15:19:41.742  1010  1687 D VoldConnector: SND -> {27 volume mkdirs /storage/ext_sd/Android/data/com.htc.musicenhancer/cache/}
07-26 15:19:41.742   386   599 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.htc.musicenhancer/cache/
07-26 15:19:41.752  1010  1817 D Process : killProcessQuiet, pid=5298
07-26 15:19:41.752  1010  1817 I ActivityManager: Killing 5298:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
07-26 15:19:41.752  1010  1817 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
07-26 15:19:41.752   451   451 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 169us total 21.332ms
07-26 15:19:41.752  5673  5733 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
07-26 15:19:41.772   451   451 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 135us total 21.143ms
07-26 15:19:41.772  5710  5710 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
07-26 15:19:41.772  1010  1282 E WifiStateMachine: handleMessage: E msg.what=131165
07-26 15:19:41.772  1010  1282 E WifiStateMachine: processMsg: ConnectedState
07-26 15:19:41.772  1010  1282 E WifiStateMachine:  ConnectedState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
07-26 15:19:41.772  1010  1282 E WifiStateMachine: processMsg: L2ConnectedState
07-26 15:19:41.772  1010  1282 E WifiStateMachine:  L2ConnectedState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
07-26 15:19:41.772  1010  1282 E WifiStateMachine: processMsg: ConnectModeState
07-26 15:19:41.772  1010  1282 E WifiStateMachine:  ConnectModeState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
07-26 15:19:41.772  1010  1282 E WifiStateMachine: processMsg: DriverStartedState
07-26 15:19:41.772  1010  1282 E WifiStateMachine:  DriverStartedState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
07-26 15:19:41.772  1010  1282 E WifiStateMachine: processMsg: SupplicantStartedState
07-26 15:19:41.772  1010  1282 E WifiStateMachine:  SupplicantStartedState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
07-26 15:19:41.772  1010  1282 E WifiStateMachine: processMsg: DefaultState
07-26 15:19:41.772  1010  1282 E WifiStateMachine:  DefaultState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
07-26 15:19:41.772  1010  1282 E WifiStateMachine: handleMessage: X
07-26 15:19:41.792  1630  1900 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
07-26 15:19:41.792  1630  1900 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@2fd048ed +
07-26 15:19:41.792  1630  1900 I Prism.WidgetManager: onLoadItems() +
07-26 15:19:41.812  3873  5392 D MediaProvider: [update][14]#1#
07-26 15:19:41.822  1010  1818 I ActivityManager: Recipient 5298
07-26 15:19:41.822  5702  5737 E cutils-trace: Error opening trace file: Permission denied (13)
07-26 15:19:41.822  3873  5392 D MediaScanner:  prescan time: 1367ms
07-26 15:19:41.822  3873  5392 D MediaScanner:     scan time: 2588ms
07-26 15:19:41.822  3873  5392 D MediaScanner: postscan time: 3ms
07-26 15:19:41.822  3873  5392 D MediaScanner:    total time: 3958ms
07-26 15:19:41.822  3873  5392 D MediaScanner: -----------------------------------------------------------------
07-26 15:19:41.822  3873  5392 D MediaScanner: firstscan(media) time: 1665ms
07-26 15:19:41.822  3873  5392 D MediaScanner: secondscan(non-media) time: 922ms
07-26 15:19:41.822  3873  5392 D MediaScanner:  [Update]   Image: 0 Video: 0 Audio: 0 Other: 1
07-26 15:19:41.822  3873  5392 D MediaScanner:  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
07-26 15:19:41.822  3873  5392 D MediaScanner:  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
07-26 15:19:41.822  3873  5392 D MediaScanner:  [Total]    File(Image+Video+Audio+Others) in database : 1694
07-26 15:19:41.822  3873  5392 D MediaProvider: [delete][4]
07-26 15:19:41.822  3873  5392 D MediaProvider: [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
07-26 15:19:41.832  1630  1900 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
07-26 15:19:41.832  3873  5392 D MediaProvider: [recoverParentNodes] - 0
07-26 15:19:41.832  3873  5392 D MediaProvider: [update][6]
07-26 15:19:41.832  3873  5392 D MediaScannerServiceEx: [scan] Recover Parent Node is finished!
07-26 15:19:41.832  3873  5392 D MediaScannerServiceEx: [updateImage]+
07-26 15:19:41.842  3873  5392 D MediaScannerServiceEx: [updateImage]-0
07-26 15:19:41.852  5710  5710 I SoundPicker: SoundPickerReceiver [onReceive] startService
07-26 15:19:41.862  1010  1478 D PMS     : releaseWL(2b0b8346): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
07-26 15:19:41.862  3873  5392 D MediaScannerServiceEx: [1] scan finished
07-26 15:19:41.862  3873  5392 D MediaProviderUtils: calcVolumeId: /storage/emulated/0
07-26 15:19:41.862  3873  5392 D MediaProviderUtils: calcVolumeId: /storage/ext_sd
07-26 15:19:41.862  3873  5392 D MediaProviderUtils: calcVolumeId: /storage/usb
07-26 15:19:41.862  3873  5392 D MediaScannerServiceEx: [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1
07-26 15:19:41.862  3873  5392 W MediaScannerServiceEx: Process mounted intent for unmounted storage: /storage/ext_sd
07-26 15:19:41.862  5710  5749 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
07-26 15:19:41.862  5710  5749 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
07-26 15:19:41.862  5710  5749 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
07-26 15:19:41.872  3873  5392 D MediaScannerServiceEx: [disAliveExtStorageRows]+131073
07-26 15:19:41.872  1010  1811 I ActivityManager: Killing 5319:com.htc.calendar/u0a10 (adj 15): empty #17
07-26 15:19:41.872  1010  1811 D Process : killProcessQuiet, pid=5319
07-26 15:19:41.872  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-26 15:19:41.872  1010  1811 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
07-26 15:19:41.882  5702  5702 D CustomizationManager: ====startRecUseTime====
07-26 15:19:41.882  5702  5702 D htc.customization.log.level:  is 
07-26 15:19:41.882  5702  5702 W CustomizationLogLevel: Level value is invalid, use default level 2
07-26 15:19:41.882  3873  5392 D MediaProvider: [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted
07-26 15:19:41.882  3873  5392 D MediaProvider: [update][12]#1#
07-26 15:19:41.912  3873  5392 D MediaProvider: [update][29]#0#
07-26 15:19:41.912  3873  5392 D MediaScannerServiceEx: [disAliveExtStorageRows]--1, 0
07-26 15:19:41.952  5702  5702 D CustomizationManager:  Read ACC file spent 0.034 (s)
07-26 15:19:41.952  5702  5702 D CIDMapFileReader: Parsing tag item name = HTC__001
07-26 15:19:41.952  5702  5702 D CIDMapFileReader: Parsing tag item name = HTC__102
07-26 15:19:41.952  5702  5702 D CIDMapFileReader: Parsing tag item name = HTC__Y13
07-26 15:19:41.952  5702  5702 D CIDMapFileReader: Parsing tag item name = HTC__032
07-26 15:19:41.952  5702  5702 D CIDMapFileReader: Parsing tag item name = HTC__M27
07-26 15:19:41.952  5702  5702 D CIDMapFileReader: Parsing tag item name = HTC__002
07-26 15:19:41.952  5702  5702 D CIDMapFileReader: Parsing tag item name = HTC__031
07-26 15:19:41.952  5702  5702 D CIDMapFileReader: Parsing tag item name = HTC__A07
07-26 15:19:41.952  5702  5702 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__102.xml
07-26 15:19:41.952  5702  5702 I CustomizationCIDLoader: Parsing tag category name = system
07-26 15:19:41.952  5702  5702 I CustomizationCIDLoader: Parsing tag category name = application
07-26 15:19:41.952  5702  5702 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
07-26 15:19:41.952  5702  5702 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
07-26 15:19:41.952  5702  5702 I CustomizationCIDLoader: Parsing tag category name = AudioService
07-26 15:19:41.952  5702  5702 I CustomizationCIDLoader: Parsing tag category name = Settings
07-26 15:19:41.952  5702  5702 I CustomizationCIDLoader: Parsing tag category name = ACC
07-26 15:19:41.952  5702  5702 I CustomizationCIDLoader: add string-array item, value = 42507
07-26 15:19:41.952  5702  5702 I CustomizationCIDLoader: add string-array item, value = 21902
07-26 15:19:41.952  5702  5702 I CustomizationCIDLoader: add string-array item, value = 26006:26001.26002.26003
07-26 15:19:41.952  5702  5702 I CustomizationCIDLoader: add string-array item, value = 23420
07-26 15:19:41.952  5702  5702 I CustomizationCIDLoader: add string-array item, value = 22299
07-26 15:19:41.952  5702  5702 I CustomizationCIDLoader: add string-array item, value = 24002
07-26 15:19:41.952  5702  5702 I CustomizationCIDLoader: add string-array item, value = 23210
07-26 15:19:41.952  5702  5702 I CustomizationCIDLoader: add string-array item, value = 23205
07-26 15:19:41.952  5702  5702 I CustomizationCIDLoader: add string-array item, value = 23806
07-26 15:19:41.952  5702  5702 I CustomizationCIDLoader: add string-array item, value = 23430
07-26 15:19:41.952  5702  5702 I CustomizationCIDLoader: add string-array item, value = 23408
07-26 15:19:41.952  5702  5702 I CustomizationCIDLoader: add string-array item, value = 27205
07-26 15:19:41.952  5702  5702 I CustomizationCIDLoader: add string-array item, value = 42507:C:1:0
07-26 15:19:41.952  5702  5702 I CustomizationCIDLoader: add string-array item, value = 21902:C:1:0
07-26 15:19:41.952  5702  5702 I CustomizationCIDLoader: add string-array item, value = 26006:D:1:0
07-26 15:19:41.952  5702  5702 I CustomizationCIDLoader: add string-array item, value = 23420:D:0:0
07-26 15:19:41.952  5702  5702 I CustomizationCIDLoader: add string-array item, value = 22299:D:0:0
07-26 15:19:41.952  5702  5702 I CustomizationCIDLoader: add string-array item, value = 24002:D:0:0
07-26 15:19:41.952  5702  5702 I CustomizationCIDLoader: add string-array item, value = 23210:D:2:0
07-26 15:19:41.952  5702  5702 I CustomizationCIDLoader: add string-array item, value = 23205:D:2:0
07-26 15:19:41.952  5702  5702 I CustomizationCIDLoader: add string-array item, value = 23806:D:0:0
07-26 15:19:41.952  5702  5702 I CustomizationCIDLoader: add string-array item, value = 23430:C:1:0
07-26 15:19:41.952  5702  5702 I CustomizationCIDLoader: add string-array item, value = 23408:C:1:0
07-26 15:19:41.952  5702  5702 I CustomizationCIDLoader: add string-array item, value = 27205:C:1:0
07-26 15:19:41.952  5702  5702 D CustomizationManager:  Read CID file spent 0.074 (s)
07-26 15:19:41.952  5702  5702 D CustomizationManager:  All configurations done spent 0.075 (s)
07-26 15:19:41.972  1010  1687 I ActivityManager: Recipient 5319
07-26 15:19:41.982  5648  5648 I EASAppSvc: [ NA ]onDestroy
07-26 15:19:41.982  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
07-26 15:19:41.992  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-26 15:19:41.992  3873  5392 D MediaProviderUtils: calcVolumeId: /storage/emulated/0
07-26 15:19:41.992  3873  5392 D MediaProviderUtils: calcVolumeId: /storage/ext_sd
07-26 15:19:41.992  3873  5392 D MediaProviderUtils: calcVolumeId: /storage/usb
07-26 15:19:41.992  3873  5392 D MediaScannerServiceEx: [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
07-26 15:19:41.992  3873  5392 W MediaScannerServiceEx: Process mounted intent for unmounted storage: /storage/usb
07-26 15:19:41.992  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-26 15:19:41.992  5648  5648 I EASAppSvc: [ NA ]onCreate
07-26 15:19:41.992  1010  1096 D PMS     : acquireHCC(1dfd5b3a): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 1010 1000 null
07-26 15:19:41.992  1010  1478 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 5702 on display 0
07-26 15:19:41.992  3873  5392 D MediaScannerServiceEx: [disAliveExtStorageRows]+196609
07-26 15:19:41.992  1010  1096 D PMS     : acquireHCC(3f87b3eb): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 1010 1000 null
07-26 15:19:41.992  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
07-26 15:19:41.992  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-26 15:19:41.992  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-26 15:19:41.992  5648  5701 I EASAppSvc: [ NA ]> uninitEASService
07-26 15:19:41.992  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-26 15:19:41.992  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-26 15:19:41.992  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-26 15:19:41.992  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-26 15:19:41.992  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-26 15:19:41.992  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-26 15:19:41.992  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-26 15:19:41.992  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
07-26 15:19:41.992  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
07-26 15:19:41.992  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
07-26 15:19:41.992  3873  5392 D MediaProvider: [sendStorageAddedIfNeed]: /storage/usb : unmounted
07-26 15:19:41.992  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
07-26 15:19:41.992  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
07-26 15:19:41.992  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
07-26 15:19:41.992  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
07-26 15:19:42.002  3873  5392 D MediaProvider: [update][4]#1#
07-26 15:19:42.002  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
07-26 15:19:42.002  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-26 15:19:42.002  5710  5749 I SoundPicker: TurnFileToMediaUriService [checkFileExistence]
07-26 15:19:42.002  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-26 15:19:42.002  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
07-26 15:19:42.002  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
07-26 15:19:42.002  5648  5752 I VersionUtil: [ NA ]setIsFOTAing: true
07-26 15:19:42.002  5648  5752 I VersionUtil: [ NA ]onUpgrade: current version=100, latest version=100
07-26 15:19:42.002  5648  5752 I VersionUtil: [ NA ]setIsFOTAing: false
07-26 15:19:42.002  1010  1478 D PMS     : acquireWL(13d5f106): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 1010 1000 null
07-26 15:19:42.012  1010  1069 I AnimationUtil: isHTCRecent(ThaliTest/Recent screens.)/5
07-26 15:19:42.012  5648  5701 I EASRequestController: [ NA ]release
07-26 15:19:42.012  1630  1630 I FeedHostManager: [onPause]
07-26 15:19:42.012  1630  1630 I FeedProviderManager: onPause
07-26 15:19:42.012  1630  1630 I FeedHostManager: [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@2aa4548b
07-26 15:19:42.012  1630  2634 I SocialFeedProvider: +onPause
07-26 15:19:42.012  1630  2634 I SocialFeedProvider: -onPause
07-26 15:19:42.012  1630  1630 I ContextualWidget: onPause
07-26 15:19:42.012  1630  1630 I ContextualWidget: notifyWidgetDeactive
07-26 15:19:42.022  1630  1900 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-26 15:19:42.022  1010  1684 W HtcSystemUPManager: HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
07-26 15:19:42.022  5648  5701 D EASPublicBinder: [ NA ]release
07-26 15:19:42.022  5648  5701 D TaskBinder: [ NA ]release
07-26 15:19:42.022  5648  5701 D TaskBinder: [ NA ]release
07-26 15:19:42.022  5648  5701 I EASAppSvc: [ NA ]< uninitEASService
07-26 15:19:42.022  5343  5754 D ORMLib  : put()
07-26 15:19:42.032  1010  1817 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5761 uid=10195 gids={50195, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-26 15:19:42.032  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:42.042  3873  5392 D MediaProvider: [update][44]#0#
07-26 15:19:42.042  3873  5392 D MediaScannerServiceEx: [disAliveExtStorageRows]--1, 0
07-26 15:19:42.052  1010  1030 I ActivityManager: Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=5777 uid=10084 gids={50084, 9997, 3003, 1028, 1015, 1023, 2001, 5006, 5001} abi=arm64-v8a
07-26 15:19:42.062  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:42.062  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:42.062  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-26 15:19:42.062  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
07-26 15:19:42.062  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
07-26 15:19:42.062  5648  5648 I EASAppSvc: [ NA ]onDestroy
07-26 15:19:42.062  5648  5752 I EASAppSvc: [ NA ]> uninitEASService
07-26 15:19:42.062  5648  5752 W System.err: java.lang.IllegalArgumentException: Receiver not registered: null
07-26 15:19:42.062  5648  5752 W System.err: 	at android.app.LoadedApk.forgetReceiverDispatcher(LoadedApk.java:828)
07-26 15:19:42.062  5648  5752 W System.err: 	at android.app.ContextImpl.unregisterReceiver(ContextImpl.java:1798)
07-26 15:19:42.062  5648  5752 W System.err: 	at android.content.ContextWrapper.unregisterReceiver(ContextWrapper.java:510)
07-26 15:19:42.062  5648  5752 W System.err: 	at com.htc.android.mail.eassvc.EASAppSvc.F(EASAppSvc.java:2451)
07-26 15:19:42.062  5648  5752 W System.err: 	at com.htc.android.mail.eassvc.EASAppSvc.g(EASAppSvc.java:133)
07-26 15:19:42.062  5648  5752 W System.err: 	at com.htc.android.mail.eassvc.i.run(EASAppSvc.java:1499)
07-26 15:19:42.082  1578  2220 D PhoneApp: EVENT_QUERY_MO_PACKAGES
07-26 15:19:42.092  1010  1810 I ActivityManager: Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=5803 uid=10066 gids={50066, 9997, 3003} abi=arm64-v8a
07-26 15:19:42.102  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:42.102  1578  2220 D PhoneApp: -- N1 =0
07-26 15:19:42.102  1578  2220 D PhoneApp: -- N2 =0
07-26 15:19:42.102  1578  2220 D PhoneApp: -- N3 =0
07-26 15:19:42.122  1010  1067 D StatusBarManagerService: setSystemUiVisibility(0x8600)
07-26 15:19:42.122  1010  1067 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-26 15:19:42.122  1010  1067 D StatusBarManagerService: hiding MENU key
07-26 15:19:42.122  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:42.122  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:42.122  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-26 15:19:42.122  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-26 15:19:42.122  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
07-26 15:19:42.172  1630  1630 I TrimMemoryManager: [trimMemory] 20
07-26 15:19:42.222  1630  1900 W asset   : Copying FileAsset 0xac71fde0 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,07-26 15:19:42.302  1010  1818 I art     : Explicit concurrent mark sweep GC freed 30139(1704KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/25MB, paused 2.162ms total 171.392ms,
,07-26 15:19:42.302  1630  1900 I Prism.WidgetManager: onLoadItems() -,
07-26 15:19:42.302  1630  1900 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@2fd048ed -
07-26 15:19:42.302  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:42.302  1010  1010 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
,07-26 15:19:42.312  1010  1010 E WifiTrafficPoller:  packet count Tx=203 Rx=370,
07-26 15:19:42.312  1010  1010 E WifiTrafficPoller: notifying of data activity 0
,07-26 15:19:42.312  5621  5621 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
07-26 15:19:42.312  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,07-26 15:19:42.312  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac,
07-26 15:19:42.312  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-26 15:19:42.312  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-26 15:19:42.312  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,07-26 15:19:42.322  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,07-26 15:19:42.322  1630  1900 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-26 15:19:42.322  1630  1900 W PackageManager: Failure retrieving resources for com.test.thalitest: Resource ID #0x0
07-26 15:19:42.322  1351  1351 D WIFI_ICON: WifiActivity: 0
,07-26 15:19:42.332  1351  1351 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,07-26 15:19:42.332  5621  5827 I DFPI.ApkInstallService: onHandleIntent
07-26 15:19:42.332  5621  5827 I DFPI.ApkInstallService: Media Scan Finished Case 
,07-26 15:19:42.332  5621  5827 D DFPI.ApkInstallService: check CID = HTC__102
07-26 15:19:42.332  5621  5827 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
,07-26 15:19:42.342  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
07-26 15:19:42.342  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
07-26 15:19:42.342  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-26 15:19:42.342  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-26 15:19:42.342  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,07-26 15:19:42.342  1630  1900 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
07-26 15:19:42.342  1630  1900 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
07-26 15:19:42.342  5710  5710 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,07-26 15:19:42.342  1010  1668 I ActivityManager: Killing 4593:com.google.android.talk/u0a112 (adj 15): empty #17
07-26 15:19:42.342  1010  1668 D Process : killProcessQuiet, pid=4593
07-26 15:19:42.342  1010  1668 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-26 15:19:42.352  1630  1630 I Launcher: Deferring update until onResume
,07-26 15:19:42.352  1630  1630 D Launcher: waitUntilResume // bindAppsAdded
,07-26 15:19:42.422  5761  5761 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 240311750),
,07-26 15:19:42.452  1010  1627 I ActivityManager: Recipient 4593
,07-26 15:19:42.552  5710  5710 I SoundPicker: SoundPickerReceiver [onReceive] startService
,07-26 15:19:42.562  1010  1816 D Process : killProcessQuiet, pid=5368,
07-26 15:19:42.562  1010  1816 I ActivityManager: Killing 5368:com.nero.android.htc.sync/u0a5 (adj 15): empty #17
07-26 15:19:42.562  1010  1816 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-26 15:19:42.582  5343  5829 D ORMLib  : put(),
,07-26 15:19:42.632  1010  1740 I ActivityManager: Recipient 5368
07-26 15:19:42.632  1010  1283 D WifiService: Client connection lost with reason: 4
,07-26 15:19:42.672  1010  1271 V AlarmManager: sending alarm PendingIntent{2a825c24: PendingIntentRecord{396c638d android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=69336, Int=0
,07-26 15:19:42.682  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,07-26 15:19:42.692  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
07-26 15:19:42.692  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
07-26 15:19:42.692  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
07-26 15:19:42.692  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,07-26 15:19:42.702  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac,
,07-26 15:19:42.712  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,07-26 15:19:42.712  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
07-26 15:19:42.712  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
07-26 15:19:42.712  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,07-26 15:19:42.712  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,07-26 15:19:42.712  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,07-26 15:19:42.712  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
,07-26 15:19:42.722  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
07-26 15:19:42.722  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,07-26 15:19:42.722  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
07-26 15:19:42.722  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
07-26 15:19:42.722  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
07-26 15:19:42.722  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
07-26 15:19:42.722  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
07-26 15:19:42.732  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
07-26 15:19:42.732  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
07-26 15:19:42.732  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
07-26 15:19:42.732  5761  5761 I LibraryLoader: Time to load native libraries: 12 ms (timestamps 9605-9617)
07-26 15:19:42.732  5761  5761 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-26 15:19:42.742  5710  5749 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) },
07-26 15:19:42.742  5710  5749 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
07-26 15:19:42.742  5710  5749 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
07-26 15:19:42.742  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-26 15:19:42.742  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
07-26 15:19:42.742  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-26 15:19:42.742  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-26 15:19:42.742  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2,
07-26 15:19:42.742  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-26 15:19:42.742  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-26 15:19:42.742  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-26 15:19:42.742  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-26 15:19:42.742  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-26 15:19:42.742  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-26 15:19:42.742  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-26 15:19:42.742  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-26 15:19:42.742  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-26 15:19:42.742  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
07-26 15:19:42.742  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6,
07-26 15:19:42.742  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
07-26 15:19:42.742  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
07-26 15:19:42.742  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
07-26 15:19:42.742  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
07-26 15:19:42.742  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
07-26 15:19:42.742  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
07-26 15:19:42.742  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-26 15:19:42.742  5710  5749 I SoundPicker: TurnFileToMediaUriService [checkFileExistence]
07-26 15:19:42.742  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-26 15:19:42.742  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
07-26 15:19:42.742  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
07-26 15:19:42.742  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:42.752  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:42.752  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:42.752  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-26 15:19:42.752  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
07-26 15:19:42.752  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-26 15:19:42.762  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:42.762  5761  5761 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1c22099}
07-26 15:19:42.762  5761  5761 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-26 15:19:42.762  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:42.762  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:42.762  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-26 15:19:42.762  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-26 15:19:42.762  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
07-26 15:19:42.762  5621  5621 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
07-26 15:19:42.762  5761  5761 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
07-26 15:19:42.772  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:42.772  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:42.772  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:42.772  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-26 15:19:42.772  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-26 15:19:42.772  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
07-26 15:19:42.782  5621  5836 I DFPI.ApkInstallService: onHandleIntent
07-26 15:19:42.782  5621  5836 I DFPI.ApkInstallService: Media Scan Finished Case 
07-26 15:19:42.782  5621  5836 D DFPI.ApkInstallService: check CID = HTC__102
07-26 15:19:42.782  5621  5836 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
,07-26 15:19:42.792  5710  5710 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
07-26 15:19:42.792  5761  5761 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-26 15:19:42.792  5710  5710 I SoundPicker: SoundPickerReceiver [onReceive] startService
07-26 15:19:42.792  5761  5761 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-26 15:19:42.792  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
07-26 15:19:42.792  5761  5761 E SysUtils: ApplicationContext is null in ApplicationStatus
07-26 15:19:42.792  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
07-26 15:19:42.792  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
07-26 15:19:42.802  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-26 15:19:42.802  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-26 15:19:42.802  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
07-26 15:19:42.802  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
07-26 15:19:42.802  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
07-26 15:19:42.802  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
07-26 15:19:42.802  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
07-26 15:19:42.802  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
07-26 15:19:42.802  5621  5621 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
07-26 15:19:42.812  5621  5837 I DFPI.ApkInstallService: onHandleIntent
07-26 15:19:42.812  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
07-26 15:19:42.812  5621  5837 I DFPI.ApkInstallService: Media Scan Finished Case 
07-26 15:19:42.812  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
07-26 15:19:42.812  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
07-26 15:19:42.812  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
07-26 15:19:42.812  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
07-26 15:19:42.812  5621  5837 D DFPI.ApkInstallService: check CID = HTC__102
07-26 15:19:42.812  5621  5837 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
07-26 15:19:42.822  5710  5710 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
07-26 15:19:42.822  5710  5710 I SoundPicker: SoundPickerReceiver [onReceive] startService
07-26 15:19:42.822  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,07-26 15:19:42.822  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
07-26 15:19:42.822  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
07-26 15:19:42.822  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
07-26 15:19:42.822  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
07-26 15:19:42.832  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
07-26 15:19:42.832  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
07-26 15:19:42.832  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
07-26 15:19:42.832  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
07-26 15:19:42.832  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
07-26 15:19:42.832  1578  1578 D TelephonyReceiver: bind: false
07-26 15:19:42.832  1578  1578 D TelephonyReceiver: switchBindHtcMsgCursor: null
07-26 15:19:42.832  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
07-26 15:19:42.842  5621  5621 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
07-26 15:19:42.842  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
07-26 15:19:42.842  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
07-26 15:19:42.842  5710  5749 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
07-26 15:19:42.842  5710  5749 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
07-26 15:19:42.842  5710  5749 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
07-26 15:19:42.842  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-26 15:19:42.842  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
07-26 15:19:42.842  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-26 15:19:42.842  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-26 15:19:42.842  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
07-26 15:19:42.842  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-26 15:19:42.842  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-26 15:19:42.842  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-26 15:19:42.842  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-26 15:19:42.842  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-26 15:19:42.842  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-26 15:19:42.842  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-26 15:19:42.842  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-26 15:19:42.842  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-26 15:19:42.842  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
07-26 15:19:42.842  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
07-26 15:19:42.842  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
07-26 15:19:42.842  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
07-26 15:19:42.842  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
07-26 15:19:42.842  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
07-26 15:19:42.842  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
07-26 15:19:42.842  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
07-26 15:19:42.842  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-26 15:19:42.842  5710  5749 I SoundPicker: TurnFileToMediaUriService [checkFileExistence]
07-26 15:19:42.842  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-26 15:19:42.842  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
07-26 15:19:42.842  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
07-26 15:19:42.852  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:42.852  5710  5710 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
07-26 15:19:42.852  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:42.852  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:42.852  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-26 15:19:42.852  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
07-26 15:19:42.852  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
07-26 15:19:42.852  5710  5710 I SoundPicker: SoundPickerReceiver [onReceive] startService
07-26 15:19:42.852  5621  5838 I DFPI.ApkInstallService: onHandleIntent
07-26 15:19:42.852  5621  5838 I DFPI.ApkInstallService: Media Scan Finished Case 
07-26 15:19:42.852  5621  5838 D DFPI.ApkInstallService: check CID = HTC__102
07-26 15:19:42.852  5621  5838 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
07-26 15:19:42.862  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:42.862  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:42.862  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:42.862  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-26 15:19:42.862  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-26 15:19:42.862  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-26 15:19:42.862  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:42.872  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:42.872  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:42.872  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-26 15:19:42.872  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-26 15:19:42.872  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
07-26 15:19:42.872  5621  5621 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
07-26 15:19:42.872  5761  5761 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
07-26 15:19:42.872  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
07-26 15:19:42.882  5621  5843 I DFPI.ApkInstallService: onHandleIntent
07-26 15:19:42.882  5621  5843 I DFPI.ApkInstallService: Media Scan Finished Case 
07-26 15:19:42.882  5761  5761 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-26 15:19:42.882  5761  5761 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-26 15:19:42.882  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
07-26 15:19:42.882  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
07-26 15:19:42.882  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-26 15:19:42.882  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-26 15:19:42.882  5761  5761 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BR.1.1.2.05.00.02.028.191_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2.05.00.02.028.191__release_AU ()
07-26 15:19:42.882  5761  5761 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
07-26 15:19:42.882  5761  5761 I Adreno-EGL: Build Date: 04/17/15 Fri
07-26 15:19:42.882  5761  5761 I Adreno-EGL: Local Branch: 
07-26 15:19:42.882  5761  5761 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2.05.00.02.028.191
07-26 15:19:42.882  5761  5761 I Adreno-EGL: Local Patches: NONE
07-26 15:19:42.882  5761  5761 I Adreno-EGL: Reconstruct Branch: NOTHING
07-26 15:19:42.882  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
07-26 15:19:42.882  5621  5843 D DFPI.ApkInstallService: check CID = HTC__102
07-26 15:19:42.882  5621  5843 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
07-26 15:19:42.882  5710  5710 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
07-26 15:19:42.892  5710  5710 I SoundPicker: SoundPickerReceiver [onReceive] startService
07-26 15:19:42.892  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
07-26 15:19:42.892  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
07-26 15:19:42.892  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
07-26 15:19:42.892  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
07-26 15:19:42.892  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
07-26 15:19:42.902  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
07-26 15:19:42.902  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
07-26 15:19:42.902  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
07-26 15:19:42.902  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
07-26 15:19:42.902  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,07-26 15:19:42.902  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,07-26 15:19:42.912  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
07-26 15:19:42.912  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
07-26 15:19:42.912  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
07-26 15:19:42.912  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,07-26 15:19:42.912  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,07-26 15:19:42.912  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
07-26 15:19:42.912  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
07-26 15:19:42.912  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
07-26 15:19:42.912  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,07-26 15:19:42.922  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,07-26 15:19:42.922  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac,
07-26 15:19:42.922  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,07-26 15:19:42.922  5710  5749 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
07-26 15:19:42.922  5710  5749 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true,
07-26 15:19:42.922  5710  5749 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
07-26 15:19:42.922  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
,07-26 15:19:42.922  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
07-26 15:19:42.922  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-26 15:19:42.922  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-26 15:19:42.922  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
07-26 15:19:42.922  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
,07-26 15:19:42.922  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma),
,07-26 15:19:42.922  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-26 15:19:42.922  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-26 15:19:42.922  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 2),
07-26 15:19:42.922  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-26 15:19:42.922  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-26 15:19:42.922  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-26 15:19:42.922  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-26 15:19:42.922  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
07-26 15:19:42.922  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
07-26 15:19:42.922  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
07-26 15:19:42.922  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
07-26 15:19:42.922  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
07-26 15:19:42.922  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
07-26 15:19:42.922  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
,07-26 15:19:42.922  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
07-26 15:19:42.922  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-26 15:19:42.922  5710  5749 I SoundPicker: TurnFileToMediaUriService [checkFileExistence]
07-26 15:19:42.922  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-26 15:19:42.922  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
07-26 15:19:42.922  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
07-26 15:19:42.922  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:42.932  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:42.932  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:42.932  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-26 15:19:42.932  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
07-26 15:19:42.932  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-26 15:19:42.932  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,07-26 15:19:42.932  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,07-26 15:19:42.932  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:42.932  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-26 15:19:42.932  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-26 15:19:42.932  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-26 15:19:42.942  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,07-26 15:19:42.942  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:42.942  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:42.942  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
,07-26 15:19:42.942  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-26 15:19:42.942  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,07-26 15:19:42.952  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,07-26 15:19:42.952  1010  1030 W System.err: java.lang.Throwable: stack dump
07-26 15:19:42.952  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
07-26 15:19:42.952  1010  1030 W System.err: 	at java.lang.Thread.dumpStack(Thread.java:490)
07-26 15:19:42.952  1010  1030 W System.err: 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
07-26 15:19:42.952  1010  1030 W System.err: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
07-26 15:19:42.952  1010  1030 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
07-26 15:19:42.952  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
07-26 15:19:42.952  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-26 15:19:42.952  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-26 15:19:42.952  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
07-26 15:19:42.952  1010  1068 D BluetoothManagerService: Message: MESSAGE_REGISTER_ADAPTER
07-26 15:19:42.952  1010  1068 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3f471654:true
,07-26 15:19:42.952  5761  5851 D BluetoothAdapter: 67841365: getState(). Returning 12
,07-26 15:19:42.962  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,07-26 15:19:42.962  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,07-26 15:19:42.962  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
07-26 15:19:42.962  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
07-26 15:19:42.962  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,07-26 15:19:42.972  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,07-26 15:19:42.972  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac,
07-26 15:19:42.972  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac,
07-26 15:19:42.972  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
07-26 15:19:42.972  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
07-26 15:19:42.982  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
07-26 15:19:42.982  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
07-26 15:19:42.982  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
07-26 15:19:42.982  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
07-26 15:19:42.982  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,07-26 15:19:42.992  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,07-26 15:19:42.992  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
07-26 15:19:42.992  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac,
07-26 15:19:42.992  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
07-26 15:19:42.992  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,07-26 15:19:43.002  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,07-26 15:19:43.002  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
07-26 15:19:43.002  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,07-26 15:19:43.002  5710  5749 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
,07-26 15:19:43.002  5710  5749 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
07-26 15:19:43.002  5710  5749 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
07-26 15:19:43.002  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-26 15:19:43.002  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
07-26 15:19:43.002  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-26 15:19:43.002  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-26 15:19:43.002  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
07-26 15:19:43.002  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-26 15:19:43.002  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-26 15:19:43.002  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-26 15:19:43.002  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-26 15:19:43.002  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-26 15:19:43.002  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-26 15:19:43.002  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-26 15:19:43.002  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-26 15:19:43.002  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-26 15:19:43.002  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
07-26 15:19:43.002  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
07-26 15:19:43.002  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
07-26 15:19:43.002  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
07-26 15:19:43.002  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
07-26 15:19:43.002  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
07-26 15:19:43.002  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
07-26 15:19:43.002  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
07-26 15:19:43.002  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-26 15:19:43.002  5710  5749 I SoundPicker: TurnFileToMediaUriService [checkFileExistence]
07-26 15:19:43.002  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-26 15:19:43.002  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
07-26 15:19:43.002  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-26 15:19:43.002  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,07-26 15:19:43.012  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:43.012  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:43.012  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-26 15:19:43.012  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
07-26 15:19:43.012  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-26 15:19:43.012  1010  1010 E WifiDataStallTracker: DATA_MONITOR_POLL true Token 1
,07-26 15:19:43.012  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,07-26 15:19:43.012  1010  5857 D WifiDataStallTracker: updateDataStallInfo: mDataStallTxRxSum={txSum=184 rxSum=185} preTxRxSum={txSum=180 rxSum=184}
07-26 15:19:43.012  1010  5857 D WifiDataStallTracker: updateDataStallInfo: IN/OUT
07-26 15:19:43.012  1010  5857 D WifiDataStallTracker: onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
07-26 15:19:43.012  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:43.012  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac,
07-26 15:19:43.012  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-26 15:19:43.012  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-26 15:19:43.012  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-26 15:19:43.022  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
07-26 15:19:43.022  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:43.022  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:43.022  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-26 15:19:43.022  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-26 15:19:43.022  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,07-26 15:19:43.022  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,07-26 15:19:43.032  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
07-26 15:19:43.032  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
07-26 15:19:43.032  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-26 15:19:43.032  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
,07-26 15:19:43.032  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,07-26 15:19:43.032  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,07-26 15:19:43.032  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac,
07-26 15:19:43.032  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
,07-26 15:19:43.042  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6,
07-26 15:19:43.042  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,07-26 15:19:43.042  5761  5761 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-26 15:19:43.062  5761  5761 W AwContents: onDetachedFromWindow called when already detached. Ignoring,
,07-26 15:19:43.072  3873  3903 I art     : Explicit concurrent mark sweep GC freed 35309(2MB) AllocSpace objects, 0(0B) LOS objects, 73% free, 1496KB/5MB, paused 635us total 26.898ms
,07-26 15:19:43.072  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac,
07-26 15:19:43.072  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
07-26 15:19:43.072  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
07-26 15:19:43.072  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
07-26 15:19:43.072  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
07-26 15:19:43.072  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
07-26 15:19:43.082  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
07-26 15:19:43.082  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
07-26 15:19:43.082  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
07-26 15:19:43.082  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,07-26 15:19:43.082  5761  5761 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC,
,07-26 15:19:43.082  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
07-26 15:19:43.082  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
07-26 15:19:43.082  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
07-26 15:19:43.082  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
07-26 15:19:43.082  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,07-26 15:19:43.092  5761  5761 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-26 15:19:43.092  5761  5761 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-26 15:19:43.092  5548  5831 I MediaStoreImporter: Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
07-26 15:19:43.092  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,07-26 15:19:43.092  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,07-26 15:19:43.092  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,07-26 15:19:43.092  5710  5749 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
,07-26 15:19:43.092  5710  5749 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
07-26 15:19:43.092  5710  5749 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
,07-26 15:19:43.092  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
,07-26 15:19:43.102  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1,
07-26 15:19:43.102  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-26 15:19:43.102  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-26 15:19:43.102  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
,07-26 15:19:43.102  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-26 15:19:43.102  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-26 15:19:43.102  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-26 15:19:43.102  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-26 15:19:43.102  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-26 15:19:43.102  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-26 15:19:43.102  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-26 15:19:43.102  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-26 15:19:43.102  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-26 15:19:43.102  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
07-26 15:19:43.102  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
07-26 15:19:43.102  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
07-26 15:19:43.102  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
07-26 15:19:43.102  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
07-26 15:19:43.102  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8,
,07-26 15:19:43.102  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
,07-26 15:19:43.102  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
07-26 15:19:43.102  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-26 15:19:43.102  5710  5749 I SoundPicker: TurnFileToMediaUriService [checkFileExistence]
07-26 15:19:43.102  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-26 15:19:43.102  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
07-26 15:19:43.102  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
07-26 15:19:43.102  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,07-26 15:19:43.112  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:43.112  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:43.112  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-26 15:19:43.112  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
07-26 15:19:43.112  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-26 15:19:43.112  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:43.112  5621  5621 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,07-26 15:19:43.112  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:43.112  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:43.112  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-26 15:19:43.112  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-26 15:19:43.112  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-26 15:19:43.122  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,07-26 15:19:43.122  5621  5862 I DFPI.ApkInstallService: onHandleIntent
07-26 15:19:43.122  5621  5862 I DFPI.ApkInstallService: Media Scan Finished Case 
,07-26 15:19:43.122  5621  5862 D DFPI.ApkInstallService: check CID = HTC__102
07-26 15:19:43.122  5621  5862 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
,07-26 15:19:43.122  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:43.122  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:43.122  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-26 15:19:43.122  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-26 15:19:43.122  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,07-26 15:19:43.132  5710  5710 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,07-26 15:19:43.132  5710  5710 I SoundPicker: SoundPickerReceiver [onReceive] startService
,07-26 15:19:43.142  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,07-26 15:19:43.142  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,07-26 15:19:43.142  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,07-26 15:19:43.142  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-26 15:19:43.142  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-26 15:19:43.142  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,07-26 15:19:43.152  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,07-26 15:19:43.152  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
07-26 15:19:43.152  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
07-26 15:19:43.152  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
07-26 15:19:43.152  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
07-26 15:19:43.152  1995  5865 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,07-26 15:19:43.162  1995  1995 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,07-26 15:19:43.162  5761  5849 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
07-26 15:19:43.162  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,07-26 15:19:43.162  2224  2224 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher },
,07-26 15:19:43.182  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
07-26 15:19:43.182  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
07-26 15:19:43.182  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
07-26 15:19:43.182  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,07-26 15:19:43.182  1010  1816 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=2224, uid=10024, userID:0,
,07-26 15:19:43.222  5761  5761 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,07-26 15:19:43.252  5548  5831 I MediaStoreImporter: Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,07-26 15:19:43.312  1010  1010 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 7
07-26 15:19:43.312  1010  1010 E WifiTrafficPoller:  packet count Tx=205 Rx=370
07-26 15:19:43.312  5761  5761 I InputMethodManager: [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@2c744941, mServedView=org.apache.cordova.engine.SystemWebView{51b2ee6 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@20c13c27
07-26 15:19:43.312  1351  1351 D WIFI_ICON: WifiActivity: 2
07-26 15:19:43.312  1010  1010 E WifiTrafficPoller: notifying of data activity 2
,07-26 15:19:43.322  1351  1351 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
07-26 15:19:43.322  1010  1819 I InputMethodManagerService: Disable input method client, pid=1630
07-26 15:19:43.322  1010  1819 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
,07-26 15:19:43.322  1010  1819 I InputMethodManagerService: Enable input method client, pid=5761
07-26 15:19:43.322  1351  1351 I PhoneStatusBar: setImeWindowStatus(false,false)
,07-26 15:19:43.342  5601  5601 D Messaging: supportCMAS(SIE)/init? false/true,
07-26 15:19:43.342  5601  5601 D MmsConfig: networkCode: 
07-26 15:19:43.342  5601  5601 D MessageCustFlag: sku_id=118
07-26 15:19:43.342  5601  5601 D MmsConfig: SIE smsPri: null
07-26 15:19:43.342  5601  5601 D MmsConfig: networkCode: 
07-26 15:19:43.352  1010  1810 I art     : Explicit concurrent mark sweep GC freed 13231(731KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 2.126ms total 152.955ms
,07-26 15:19:43.352  5252  5252 D WearableService: callingUid 10024, callindPid: 5252
,07-26 15:19:43.352  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,07-26 15:19:43.352  2224  5867 D LocationInitializer: Restart initialization of location
07-26 15:19:43.352  1010  1478 D PMS     : releaseWL(13d5f106): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
07-26 15:19:43.352  5601  5601 D MmsConfig: packageName: com.htc.vvm.att does not exist
07-26 15:19:43.362  5601  5601 D ReportIndicatorCache: startAsyncQueryReports ---
07-26 15:19:43.362  5601  5646 D MmsAsyncWorkHandler: 
07-26 15:19:43.362  5601  5646 D MmsAsyncWorkHandler: HM tk = 20001
07-26 15:19:43.362  5601  5872 D Messaging: mNeedToUpdateDate2 start
07-26 15:19:43.362  5601  5646 D ReportIndicatorCache: MSG_QUERY_REPORTS >>
07-26 15:19:43.362  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac,
07-26 15:19:43.362  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
07-26 15:19:43.362  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
07-26 15:19:43.362  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
07-26 15:19:43.362  1010  1069 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s341ms
07-26 15:19:43.362  5601  5601 D SettingsManager: init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@2e8bf5e0
,07-26 15:19:43.362  1869  5866 E MDM     : [140] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,07-26 15:19:43.372  5601  5601 D DraftCache: [DraftCache/1] DraftCache.constructor
07-26 15:19:43.372  5601  5601 D DraftCache: [DraftCache/1] refresh
,07-26 15:19:43.372  1511  1511 W XT9_C   : [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
,07-26 15:19:43.372  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
07-26 15:19:43.372  1511  1511 I XT9_C   : [T9_ReleaseBuffer] Reset LDB#0
07-26 15:19:43.372  1511  1511 I XT9_C   : [T9_ReleaseBuffer] Reset LDB#1
07-26 15:19:43.372  1511  1511 D XT9_C   : [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,07-26 15:19:43.382  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac,
07-26 15:19:43.382  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
,07-26 15:19:43.382  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
07-26 15:19:43.382  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98,
07-26 15:19:43.382  1578  1623 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
07-26 15:19:43.382  1578  1623 D MmsSmsV2Provider:  slotId = -1000
,07-26 15:19:43.382  1578  1623 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
07-26 15:19:43.382  1010  1813 D PMS     : acquireWL(4df35a1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1995 10024 WorkSource{10024 com.google.android.gms}
07-26 15:19:43.382  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,07-26 15:19:43.382  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
07-26 15:19:43.382  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,07-26 15:19:43.382  5710  5749 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
07-26 15:19:43.382  5710  5749 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
07-26 15:19:43.382  5710  5749 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
07-26 15:19:43.382  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-26 15:19:43.382  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
07-26 15:19:43.382  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-26 15:19:43.382  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-26 15:19:43.382  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
07-26 15:19:43.382  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-26 15:19:43.382  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-26 15:19:43.392  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-26 15:19:43.392  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-26 15:19:43.392  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-26 15:19:43.392  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-26 15:19:43.392  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-26 15:19:43.392  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-26 15:19:43.392  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-26 15:19:43.392  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
07-26 15:19:43.392  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
07-26 15:19:43.392  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
07-26 15:19:43.392  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
07-26 15:19:43.392  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
07-26 15:19:43.392  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
07-26 15:19:43.392  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
07-26 15:19:43.392  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
07-26 15:19:43.392  5710  5749 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-26 15:19:43.392  5710  5749 I SoundPicker: TurnFileToMediaUriService [checkFileExistence]
07-26 15:19:43.392  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-26 15:19:43.392  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
07-26 15:19:43.392  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
07-26 15:19:43.392  5601  5601 D MmsConfig: networkCode: 
,07-26 15:19:43.392  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:43.392  1578  2191 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 78
07-26 15:19:43.392  1578  2191 D AccFlag : sku_id=118
,07-26 15:19:43.392  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:43.392  1010  1687 D PMS     : releaseWL(4df35a1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
07-26 15:19:43.392  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:43.392  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-26 15:19:43.392  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
07-26 15:19:43.392  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-26 15:19:43.402  1010  1030 D PMS     : acquireWL(30e713c6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1995 10024 WorkSource{10024 com.google.android.gms}
,07-26 15:19:43.412  5601  5875 I Messaging: mccmnc> 
,07-26 15:19:43.432  5601  5877 D Messaging: ViewCache CreatePreloadOnlyConversationList
,07-26 15:19:43.442  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:43.442  5761  5761 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5761
07-26 15:19:43.442  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:43.442  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:43.442  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-26 15:19:43.442  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-26 15:19:43.442  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-26 15:19:43.442  5601  5646 D DraftCache: [DraftCache/156] rebuildCache
,07-26 15:19:43.442  1578  1623 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
07-26 15:19:43.442  1578  1623 D MmsSmsV2Provider:  slotId = -1000
07-26 15:19:43.452  1578  1623 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,07-26 15:19:43.452  1010  1811 D PMS     : releaseWL(30e713c6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
07-26 15:19:43.452  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,07-26 15:19:43.462  1578  2211 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 80,
07-26 15:19:43.462  1578  2211 D MmsSmsV2Provider:  slotId = -1000
07-26 15:19:43.462  1578  2211 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,07-26 15:19:43.472  5601  5601 D PhoneStorageUtil: HtcWrapEnvironment.getSupportedStorages() >1
,07-26 15:19:43.472  5601  5601 D PhoneStorageUtil: HtcWrapEnvironment.hasRemovableStorageSlot()() >true
07-26 15:19:43.472  1578  2191 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 78
07-26 15:19:43.472  5601  5601 D PhoneStorageUtil: createReceiver
07-26 15:19:43.472  1578  2191 D MmsSmsV2Provider:  slotId = -1000
07-26 15:19:43.472  1578  2191 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
07-26 15:19:43.472  5601  5873 D Messaging: mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,07-26 15:19:43.502  5601  5877 D MessageCustFlag: sense_version=6.0
07-26 15:19:43.502  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,07-26 15:19:43.502  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-26 15:19:43.502  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-26 15:19:43.502  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-26 15:19:43.502  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
07-26 15:19:43.502  5601  5877 D Jerry   : start to preload cursor >>>>>>>
,07-26 15:19:43.512  1578  1623 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
07-26 15:19:43.512  1578  1623 D Jerry   : URI_DRAFT
07-26 15:19:43.522  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,07-26 15:19:43.522  5601  5872 D Messaging: mNeedToUpdateDate2: false
,07-26 15:19:43.522  1578  2211 D TelephUtils: UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 80
07-26 15:19:43.522  1578  2211 V MmsProvider: Update uri=content://mms, match=0
07-26 15:19:43.522  1578  2211 V MmsProvider: selection=st=129 AND m_type!=134
,07-26 15:19:43.522  5548  5831 I MediaStoreImporter: Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
07-26 15:19:43.522  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
07-26 15:19:43.522  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
07-26 15:19:43.522  5710  5749 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-26 15:19:43.522  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-26 15:19:43.522  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
07-26 15:19:43.532  5601  5885 D Messaging: Reset downloading state: 0
07-26 15:19:43.532  5601  5885 V MmsSystemEventReceiver: TransactionService is going to be woken up.
,07-26 15:19:43.532  1010  1291 D PMS     : acquireWL(1d8cbc68): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 2224 10024 WorkSource{10024 com.google.android.gms}
,07-26 15:19:43.532  5601  5646 D DraftCache: hasDraft() = false mNeedNotifyChange = true
07-26 15:19:43.532  5601  5646 D DraftCache: [DraftCache/156] rebuildCache time: 12
07-26 15:19:43.532  5601  5646 D MmsAsyncWorkHandler: 
07-26 15:19:43.532  5601  5646 D MmsAsyncWorkHandler: HM tk = 20002
,07-26 15:19:43.542  5601  5601 V TransactionService: 1-Creating TransactionService
,07-26 15:19:43.542  1578  2191 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 78
07-26 15:19:43.542  1578  2191 D MmsSmsV2Provider:  slotId = -1000
07-26 15:19:43.542  5777  5830 I ActionCombine: replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,07-26 15:19:43.552  5601  5601 V TransactionService: onStartCommand: 1
07-26 15:19:43.552  5601  5601 D MmsSystemEventReceiver: unRegisterForConnectionStateChanges
,07-26 15:19:43.552  5601  5889 V TransactionService: 4-Handling incoming message: { when=-1ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,07-26 15:19:43.552  5601  5889 V TransactionService: Loading previous transactions.
,07-26 15:19:43.552  5601  5877 D Messaging: ViewCache CreatePreload
,07-26 15:19:43.552  5601  5877 D Messaging: ViewCache CreatePreloadOnlyMultipleOpsList
,07-26 15:19:43.562  1010  1478 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5891 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a
,07-26 15:19:43.562  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,07-26 15:19:43.572  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,07-26 15:19:43.572  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
07-26 15:19:43.572  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
07-26 15:19:43.572  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,07-26 15:19:43.572  1578  1618 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
07-26 15:19:43.572  1578  1618 D AccFlag : sku_id=118
07-26 15:19:43.572  1578  1623 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
07-26 15:19:43.582  1578  1623 D AccFlag : device_type: 1
,07-26 15:19:43.582  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,07-26 15:19:43.582  1351  2102 D RingtonePlayer: play: pkg=com.htc.updater uri=content://settings/system/notification_sound AudioAttributes: usage=5 content=4 flags=0x0 tags= cmas=false cl=false
07-26 15:19:43.582  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
07-26 15:19:43.582  1010  1010 D PMS     : acquireWL(25bbed26): PARTIAL_WAKE_LOCK  RingtonePlayer 0x1 1351 10041 null
07-26 15:19:43.582  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
07-26 15:19:43.582  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
07-26 15:19:43.582  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
07-26 15:19:43.582  5601  5889 D TransactionService: Force clearing mTransactionList
07-26 15:19:43.592  5601  5889 D TransactionService: Force set service start id to 1
07-26 15:19:43.592  5601  5889 V TransactionService: stopSelfIfIdle: unRegisterForConnectionStateChanges
07-26 15:19:43.592  5601  5889 D MmsSystemEventReceiver: unRegisterForConnectionStateChanges
07-26 15:19:43.592  5601  5877 D Cust_MMSMS: _has_set_default_values_2=true
,07-26 15:19:43.592  5601  5601 V TransactionService: Destroying TransactionService
,07-26 15:19:43.592  5601  5877 D MsgPreferenceUtils: def_index: 0
07-26 15:19:43.602  5601  5889 D TransactionService: stopSelfResult: true, mLastHandledServiceId: 1
,07-26 15:19:43.602  5601  5877 D MsgPreferenceUtils: globalIndex = 1
,07-26 15:19:43.602  1578  2211 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 80
07-26 15:19:43.602  1578  2211 D AccFlag : sku_id=118
07-26 15:19:43.602  1458  1685 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false, isForDotMatrix: false
,07-26 15:19:43.612  5601  5889 V TransactionService: 4-Handling incoming message: { when=-11ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
07-26 15:19:43.612  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
07-26 15:19:43.612  1010  1816 D PMS     : acquireWL(24a9bd67): PARTIAL_WAKE_LOCK  AudioMix 0x1 0 1013 null
07-26 15:19:43.612  5601  5877 D MsgPreferenceUtils: phone state: true
07-26 15:19:43.612  5601  5877 D MsgPreferenceUtils: sd state: false
07-26 15:19:43.612  5601  5877 D MsgPreferenceUtils: vIndex = 0
07-26 15:19:43.622  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
07-26 15:19:43.622  1010  1819 D PMS     : acquireWL(38a53714): PARTIAL_WAKE_LOCK  AudioMix 0x1 0 1013 null
07-26 15:19:43.622  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
07-26 15:19:43.622  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
07-26 15:19:43.622  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
07-26 15:19:43.622  1351  1351 I RemoteViews: setHTCTheme(com.htc.updater,true,33751145)
,07-26 15:19:43.632  5761  5761 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-26 15:19:43.642  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,07-26 15:19:43.642  1010  1740 D RingtoneManager: getActualDefaultRingtoneUri(context, 2),
,07-26 15:19:43.642  1351  1351 I RemoteViews: apply : com.htc.updater 1 17 2 36
,07-26 15:19:43.642  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
07-26 15:19:43.642  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac,
07-26 15:19:43.642  5710  5749 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
07-26 15:19:43.642  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,07-26 15:19:43.652  3873  3969 D MediaProvider: [isExternalPath] not external path
,07-26 15:19:43.662  1351  5913 D MediaPlayer: ANDROID_HTC_INVOKE_GET_CALLING_PROCESS packageName: com.android.systemui
,07-26 15:19:43.662  5710  5749 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
07-26 15:19:43.662  1351  5913 W Parcel  : **** enforceInterface() expected '' but read 'android.media.IMediaPlayer'
,07-26 15:19:43.662  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
07-26 15:19:43.662  5710  5749 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,07-26 15:19:43.682  5891  5891 D PhoneMonitor: Register our PhoneStateListener
,07-26 15:19:43.692  1351  1387 W MediaPlayer: info/warning (1, 902)
07-26 15:19:43.692  1351  5913 E MediaPlayer: Should have subtitle controller already set
,07-26 15:19:43.702  1351  5913 E MediaPlayer: Should have subtitle controller already set,
07-26 15:19:43.702  1010  1816 D PMS     : releaseWL(25bbed26): PARTIAL_WAKE_LOCK  RingtonePlayer 0x1 null
07-26 15:19:43.702  1351  5913 D MediaPlayer: Is using offload now: false
,07-26 15:19:43.722  1351  1351 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,07-26 15:19:43.732  1995  5938 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
07-26 15:19:43.732  1351  1351 I ThreadedRenderer: Defer allocateBuffers to drawing time
,07-26 15:19:43.732   431  5933 W AudFlgTh: Using by PID 431, ProcessName:/system/bin/mediaserver  
07-26 15:19:43.732   431  1000 V SRS_Proc: ParamSet string: Ramping_upper_speaker=enable,
07-26 15:19:43.732   431  1000 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
07-26 15:19:43.732  1351  5913 D MediaPlayer: Is using offload now: false
07-26 15:19:43.742   431  1055 W AudFlgTh: A_Shock: initial RampingCountStep(4320) RampingFlag(1)
07-26 15:19:43.742   431  1055 W audio_hw_utils: audio_extn_utils_update_stream_app_type_cfg: App type could not be selected. Falling back to default
,07-26 15:19:43.742  5891  5891 D PhoneMonitor: onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,07-26 15:19:43.752  2224  2224 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-26 15:19:43.752  5548  5831 I MediaStoreImporter: Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,07-26 15:19:43.762  2224  2224 I Kids    : [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
,07-26 15:19:43.782  5891  5891 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,07-26 15:19:43.782  3348  3402 I HtcModeClient: handler message = 4011
07-26 15:19:43.802  1010  1819 D PMS     : releaseWL(1d8cbc68): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 WorkSource{10024 com.google.android.gms}
07-26 15:19:43.782  3348  3402 E HtcModeClient: Check connection and retry 6 times.
07-26 15:19:43.812  1010  1810 D PMS     : acquireWL(3da854ac): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2224 10024 WorkSource{10024 com.google.android.gms}
,07-26 15:19:43.822  1010  1687 D PMS     : acquireWL(dae490a): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2224 10024 WorkSource{10024 com.google.android.gms}
,07-26 15:19:43.822  1010  1816 D PMS     : releaseWL(3da854ac): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
,07-26 15:19:43.832  1010  1819 D PMS     : acquireWL(3532557b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1995 10024 WorkSource{10024 com.google.android.gms}
,07-26 15:19:43.842  1630  1900 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,07-26 15:19:43.842  1630  1900 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@2fd048ed +
07-26 15:19:43.842  1630  1900 I Prism.WidgetManager: onLoadItems() +
,07-26 15:19:43.842  2224  5950 I CheckinService: Checking schedule, now: 1469539183851 next: 1469539207741
07-26 15:19:43.842  2224  5950 I CheckinService: active receiver: disabled
07-26 15:19:43.842  1010  1668 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2224, uid=10024, userID:0
,07-26 15:19:43.872  1010  1817 D PMS     : releaseWL(3532557b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,07-26 15:19:43.872  1010  1740 D PMS     : releaseWL(dae490a): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
,07-26 15:19:43.902  5761  5870 D jxcore_app_log: JniHelper::setJavaVM(0xab2947b8), pthread_self() = -1403248056
,07-26 15:19:43.902  1010  1668 I ActivityManager: Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent: pid=5951 uid=10035 gids={50035, 9997} abi=arm64-v8a
,07-26 15:19:43.912  5761  5870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: ,
07-26 15:19:43.912  5761  5870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-26 15:19:43.912  5761  5870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-26 15:19:43.912  5761  5870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-26 15:19:43.912  5761  5870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-26 15:19:43.912  5761  5870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1db5983b added. We now have 1 listener(s)
,07-26 15:19:43.922  1010  1668 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
,07-26 15:19:43.922  5761  5870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 90:E7:C4:F6:69:77
,07-26 15:19:43.932  5761  5870 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "90:E7:C4:F6:69:77"
,07-26 15:19:43.932  5761  5870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:19:43.932  5761  5870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-26 15:19:43.932  5548  5831 I MediaStoreImporter: Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,07-26 15:19:43.932  5761  5870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-26 15:19:43.932  5761  5870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-26 15:19:43.932  5761  5870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-26 15:19:43.932  5761  5870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 90:E7:C4:F6:69:77
07-26 15:19:43.932  5761  5870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE,
07-26 15:19:43.932  5761  5870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-26 15:19:43.932  5761  5870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
07-26 15:19:43.932  5761  5870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
07-26 15:19:43.932  5761  5870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
07-26 15:19:43.932  5761  5870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-26 15:19:43.932  5761  5870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-26 15:19:43.932  5761  5870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-26 15:19:43.932  5761  5870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-26 15:19:43.932  5761  5870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-26 15:19:43.932  5761  5870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19031d96 added. We now have 1 listener(s)
07-26 15:19:43.932  5761  5870 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-26 15:19:43.952  1010  1283 D WifiService: New client listening to asynchronous messages
,07-26 15:19:43.952  1010  1010 E WifiTrafficPoller: ADD_CLIENT: 8
07-26 15:19:43.952  5761  5870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-26 15:19:43.952  5761  5870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-26 15:19:43.952  5761  5870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-26 15:19:43.952  5761  5870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-26 15:19:43.972  5761  5870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-26 15:19:43.972  1010  1819 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-26 15:19:43.982  5761  5870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 90:E7:C4:F6:69:77
,07-26 15:19:43.992  1010  1096 D PMS     : releaseHCC(1dfd5b3a): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
07-26 15:19:43.992  1010  1096 D PMS     : releaseHCC(3f87b3eb): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,07-26 15:19:44.012  5761  5870 D BluetoothAdapter: 67841365: getState(). Returning 12
07-26 15:19:44.012  5761  5870 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
07-26 15:19:44.012  1010  1819 I ActivityManager: Killing 5402:com.android.settings/1000 (adj 15): empty #17
07-26 15:19:44.012  1010  1819 D Process : killProcessQuiet, pid=5402
07-26 15:19:44.012  5761  5870 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:19:44.012  5761  5870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:19:44.012  5761  5870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 15:19:44.012  5761  5870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:19:44.012  5761  5870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:19:44.012  5761  5870 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-26 15:19:44.012  5761  5870 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:19:44.012  5761  5870 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-26 15:19:44.012  5761  5870 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-26 15:19:44.012  1010  1819 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
07-26 15:19:44.012  5761  5870 D io.jxcore.node.ConnectivityMonitor: start: OK
07-26 15:19:44.012  5761  5870 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-26 15:19:44.022  5761  5761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:19:44.022  5761  5761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:19:44.032  1010  1282 E WifiStateMachine: handleMessage: E msg.what=131155
07-26 15:19:44.032  1010  1282 E WifiStateMachine: processMsg: ConnectedState
07-26 15:19:44.032  1010  1282 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-50 f=2447 sc=60 link=150 tx=14.6, 0.0, 0.0  rx=21.1 bcn=0 [on:0 tx:0 rx:0 period:2995] from screen [on:0 period:660368803] gl hn u24 rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-26 15:19:44.032  1010  1282 E WifiStateMachine: processMsg: L2ConnectedState
07-26 15:19:44.032  1010  1282 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-50 f=2447 sc=60 link=150 tx=14.6, 0.0, 0.0  rx=21.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:660368806] gl hn u24 rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-26 15:19:44.032  1010  1282 E WifiStateMachine:  get link layer stats 0
07-26 15:19:44.032  1010  1282 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
07-26 15:19:44.032  1454  1454 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
,07-26 15:19:44.052  1454  1454 I wpa_supplicant: environment dirty rate=0 [4][0][0],
07-26 15:19:44.052  1010  1282 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 150,
07-26 15:19:44.052  1010  1282 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-50 linkspeed=150
07-26 15:19:44.052  1010  1282 E WifiConfigStore: updateConfiguration freq=2447 BSSID=f4:f2:6d:22:99:3e RSSI=-50 "NG700"WPA_PSK
,07-26 15:19:44.052  1010  1282 E WifiStateMachine: calculateWifiScore freq=2447 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=9.32 txretriesrate=0.00 rxrate=12.07 userTriggerdPenalty0
07-26 15:19:44.052  1010  1282 E WifiStateMachine:  good link -> stuck count =0
07-26 15:19:44.052  1010  1282 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 60
07-26 15:19:44.052  1010  1282 E WifiStateMachine:  isHighRSSI       ---> score=65
,07-26 15:19:44.122  1010  1030 I ActivityManager: Recipient 5402
,07-26 15:19:44.182  5761  5761 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,07-26 15:19:44.232  1010  1282 E WifiStateMachine: handleMessage: X
07-26 15:19:44.232  1010  1307 D WifiWatchdogStateMachine: RSSI current: 3 new: -50, 3
07-26 15:19:44.232  1351  1351 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
07-26 15:19:44.232  1351  1351 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
,07-26 15:19:44.262  1010  1478 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=5976 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a,
,07-26 15:19:44.282  5548  5831 I MediaStoreImporter: Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,07-26 15:19:44.292  1010  1668 D Process : killProcessQuiet, pid=5426,
07-26 15:19:44.292  1010  1668 I ActivityManager: Killing 5426:com.htc.backupreset/1000 (adj 15): empty #17
07-26 15:19:44.292  1010  1668 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-26 15:19:44.312  1010  1010 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
,07-26 15:19:44.312  1351  1351 D WIFI_ICON: WifiActivity: 3
07-26 15:19:44.312  1010  1010 E WifiTrafficPoller:  packet count Tx=207 Rx=372
07-26 15:19:44.312  1351  1351 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
07-26 15:19:44.312  1010  1010 E WifiTrafficPoller: notifying of data activity 3
,07-26 15:19:44.352  1630  1900 E Prism.WidgetManager: The same lists. No need to update. skip it.,
07-26 15:19:44.352  1630  1900 I Prism.WidgetManager: onLoadItems() -
07-26 15:19:44.352  1630  1900 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@2fd048ed -
,07-26 15:19:44.432  1010  1029 I ActivityManager: Recipient 5426
,07-26 15:19:44.532  5976  5976 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-26 15:19:44.622  5761  5975 W jxcore-log: Initializing JXcore engine
,07-26 15:19:44.622  5761  5975 W jxcore-log: JXcore engine is ready
,07-26 15:19:44.682  5761  5975 W jxcore-log: Starting JXcore engine,
,07-26 15:19:44.722  5976  6002 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,07-26 15:19:44.722  5976  6002 I Babel_SMS: MmsConfig.loadMmsSettings
07-26 15:19:44.722  5601  5624 D MmsCustomizationProvider: query uri: content://htc-mms-customization/mms-ua/ua_string,
,07-26 15:19:44.742  5601  5635 D MmsCustomizationProvider: query uri: content://htc-mms-customization/mms-ua/ua_profile
,07-26 15:19:44.742  5976  6002 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
07-26 15:19:44.742  5976  6002 I Babel_SMS: MmsConfig.loadFromDatabase
,07-26 15:19:44.762  1010  1668 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=5976, uid=10112, userID:0
07-26 15:19:44.762  5976  6002 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
07-26 15:19:44.762  5976  6002 I Babel_SMS: MmsConfig.loadFromResources
,07-26 15:19:44.782  5976  6002 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,07-26 15:19:44.782  5761  5975 W jxcore-log: Platform android,
07-26 15:19:44.782  5761  5975 W jxcore-log: 
07-26 15:19:44.782  5761  5975 W jxcore-log: Process ARCH arm
07-26 15:19:44.782  5761  5975 W jxcore-log: 
,07-26 15:19:44.782  5976  6002 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,07-26 15:19:44.832  5976  5976 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-26 15:19:44.832  5976  5976 I Babel_Crash: startup - clean
,07-26 15:19:44.842  5976  6006 I Babel   : deleted: false for 0,
,07-26 15:19:44.872  1010  1810 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=5976, uid=10112, userID:0,
,07-26 15:19:44.872  1010  1811 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=5976, uid=10112, userID:0
,07-26 15:19:44.872  1010  1818 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=5976, uid=10112, userID:0
,07-26 15:19:44.872  1010  1627 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=5976, uid=10112, userID:0,
,07-26 15:19:44.872  1010  1030 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=5976, uid=10112, userID:0
,07-26 15:19:44.882  1010  1813 D PMS     : acquireWL(c75a599): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 5976 10112 null
,07-26 15:19:44.892  1010  1010 E WifiStateMachine: WiFiStateMachine SCAN ALARM
07-26 15:19:44.892  1010  1010 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
07-26 15:19:44.892  1010  1010 D WifiDisplayAdapter:     Client/Owner: Client
07-26 15:19:44.892  1010  1010 D WifiDisplayAdapter:     GroupId: 
07-26 15:19:44.892  1010  1010 D WifiDisplayAdapter:     Passphrase: 
07-26 15:19:44.892  1010  1010 D WifiDisplayAdapter:     SessionId: 0
07-26 15:19:44.892  1010  1010 D WifiDisplayAdapter:     IP Address: }
07-26 15:19:44.902  1010  1282 E WifiStateMachine: handleMessage: E msg.what=131143
07-26 15:19:44.902  1010  1282 E WifiStateMachine: processMsg: ConnectedState
07-26 15:19:44.902  1010  1282 E WifiStateMachine:  ConnectedState !CMD_START_SCAN -2 -2 ic=2 proc(ms):2 dur:77 rssi=-50 f=2447 sc=60 link=150 tx=9.3, 0.0, 0.0  rx=12.1 list=2447 [on:0 tx:0 rx:0 period:671] from screen [on:0 period:660369672]
07-26 15:19:44.902  1010  1282 E WifiStateMachine: processMsg: L2ConnectedState
07-26 15:19:44.902  1010  1282 E WifiStateMachine:  L2ConnectedState !CMD_START_SCAN -2 -2 ic=2 proc(ms):3 dur:77 rssi=-50 f=2447 sc=60 link=150 tx=9.3, 0.0, 0.0  rx=12.1 list=2447 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:660369673]
,07-26 15:19:44.902  1010  1282 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=9.32 rxSuccessRate=12.07 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-50
07-26 15:19:44.902  1010  1282 E WifiStateMachine: WifiStateMachine CMD_START_SCAN with age=1469539184905 interval=40000 maxinterval=300000
,07-26 15:19:44.902  1010  1282 E WifiStateMachine: WifiStateMachine CMD_START_SCAN try full band scan age=1469539184905 interval=40000 maxinterval=300000
,07-26 15:19:44.902  1010  1282 E WifiStateMachine: WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
07-26 15:19:44.902  1010  1282 E WifiStateMachine: WifiStateMachine CMD_START_SCAN full=false
07-26 15:19:44.902  1010  1282 E WifiConfigStore: makeChannelList age=3600000 for "NG700"WPA_PSK max=6 bssids=1
07-26 15:19:44.902  1010  1282 E WifiConfigStore: has f4:f2:6d:22:99:3e freq=2447 age=852 ?=true
07-26 15:19:44.902  1010  1282 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
07-26 15:19:44.902  1010  1282 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY freq=2447"
07-26 15:19:44.902  1454  1454 D wpa_supplicant: wlan0: Control interface command 'SCAN TYPE=ONLY freq=2447'
07-26 15:19:44.902  1454  1454 D wpa_supplicant: wlan0: Setting scan request: 0.000000 sec
07-26 15:19:44.902  1454  1454 I wpa_supplicant: wpa_supplicant_scan enter
07-26 15:19:44.902  1454  1454 D wpa_supplicant: wlan0: Starting AP scan for wildcard SSID
07-26 15:19:44.902  1454  1454 D wpa_supplicant: WPS: Building WPS IE for Probe Request
07-26 15:19:44.902  1454  1454 D wpa_supplicant: WPS:  * Version (hardcoded 0x10)
07-26 15:19:44.902  1454  1454 D wpa_supplicant: WPS:  * Request Type
07-26 15:19:44.902  1454  1454 D wpa_supplicant: WPS:  * Config Methods (4288)
07-26 15:19:44.902  1454  1454 D wpa_supplicant: WPS:  * UUID-E
07-26 15:19:44.902  1454  1454 D wpa_supplicant: WPS:  * Primary Device Type
07-26 15:19:44.902  1454  1454 D wpa_supplicant: WPS:  * RF Bands (3)
07-26 15:19:44.902  1454  1454 D wpa_supplicant: WPS:  * Association State
07-26 15:19:44.902  1454  1454 D wpa_supplicant: WPS:  * Configuration Error (0)
07-26 15:19:44.902  1454  1454 D wpa_supplicant: WPS:  * Device Password ID (0)
07-26 15:19:44.902  1454  1454 D wpa_supplicant: WPS:  * Manufacturer
07-26 15:19:44.902  1454  1454 D wpa_supplicant: WPS:  * Model Name
07-26 15:19:44.902  1454  1454 D wpa_supplicant: WPS:  * Model Number
07-26 15:19:44.902  1454  1454 D wpa_supplicant: WPS:  * Device Name
07-26 15:19:44.902  1454  1454 D wpa_supplicant: WPS:  * Version2 (0x20)
07-26 15:19:44.902  1454  1454 D wpa_supplicant: P2P: * P2P IE header
07-26 15:19:44.902  1454  1454 D wpa_supplicant: P2P: * Capability dev=25 group=00
07-26 15:19:44.902  1454  1454 D wpa_supplicant: P2P: * Listen Channel: Regulatory Class 81 Channel 6
07-26 15:19:44.902  1454  1454 D wpa_supplicant: wlan0: Limit manual scan to specified channels
07-26 15:19:44.902  1454  1454 D wpa_supplicant: wlan0: Add radio work 'scan'@0x55b0d30860
07-26 15:19:44.902  1454  1454 D wpa_supplicant: wlan0: First radio work item in the queue - schedule start immediately
07-26 15:19:44.902  1454  1454 D wpa_supplicant: wlan0: Starting radio work 'scan'@0x55b0d30860 after 0.000046 second wait
07-26 15:19:44.902  1454  1454 D wpa_supplicant: wlan0: nl80211: scan request
07-26 15:19:44.902  1454  1454 D wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
07-26 15:19:44.902  1454  1454 D wpa_supplicant: nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
07-26 15:19:44.902  1454  1454 D wpa_supplicant: wlan0: nl80211: Scan trigger
07-26 15:19:44.902  1454  1454 D wpa_supplicant: wlan0: Event SCAN_STARTED (49) received
07-26 15:19:44.902  1454  1454 D wpa_supplicant: wlan0: Own scan request started a scan in 0.000110 seconds
07-26 15:19:44.902  1454  1454 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
07-26 15:19:44.902  1010  1688 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
07-26 15:19:44.902  1010  1688 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
07-26 15:19:44.902  1010  1688 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
07-26 15:19:44.902  1010  1688 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
07-26 15:19:44.902  1010  1282 E WifiStateMachine: [1,469,539,184,909 ms] noteScanstart no scan source
07-26 15:19:44.902  1010  1282 E WifiStateMachine: handleMessage: X
07-26 15:19:44.912  1010  1010, I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6008 uid=10106 gids={50106, 9997, 3003, 1028, 1015} abi=arm64-v8a
,07-26 15:19:44.922  5761  5975 I jxcore-log: JXcore Cordova bridge is ready!
07-26 15:19:44.922  5761  5975 I jxcore-log: 
07-26 15:19:44.932  5761  5975 W jxcore-log: JXcore engine is started
,07-26 15:19:44.932  5761  5870 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-26 15:19:44.932  5976  5976 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc,
07-26 15:19:44.942  5761  5761 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-26 15:19:44.952  5761  5975 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
07-26 15:19:44.952  5761  5975 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,07-26 15:19:44.962  5761  5761 I chromium: [INFO:CONSOLE(57)] "app.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,07-26 15:19:44.962  5761  5761 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,07-26 15:19:44.972  5976  5976 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,07-26 15:19:44.982  5976  5976 W Utils   : could not parse size range '64x64-1920X1080',
,07-26 15:19:44.982  1454  1454 D wpa_supplicant: nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
07-26 15:19:44.982  1454  1454 D wpa_supplicant: wlan0: nl80211: New scan results available
07-26 15:19:44.982  1454  1454 D wpa_supplicant: nl80211: Scan included frequencies: 2447
07-26 15:19:44.982  1454  1454 D wpa_supplicant: wlan0: Event SCAN_RESULTS (3) received
07-26 15:19:44.982  1454  1454 I wpa_supplicant: Got an original EVENT_SCAN_RESULTS
07-26 15:19:44.982  1454  1454 D wpa_supplicant: wlan0: Scan completed in 0.083270 seconds
07-26 15:19:44.982  1454  1454 D wpa_supplicant: nl80211: Associated on 2447 MHz
07-26 15:19:44.982  1454  1454 D wpa_supplicant: nl80211: Associated with f4:f2:6d:22:99:3e
07-26 15:19:44.982  1454  1454 D wpa_supplicant: nl80211: Received scan results (9 BSSes)
07-26 15:19:44.982  1454  1454 D wpa_supplicant: nl80211: Scan results indicate BSS status with f4:f2:6d:22:99:3e as associated
07-26 15:19:44.982  1454  1454 I wpa_supplicant: [NULL] f0:f2:6d:22:99:3e freq=2447 level=-45
07-26 15:19:44.982  1454  1454 I wpa_supplicant: [NULL] f4:f2:6d:22:99:3e freq=2447 level=-50
07-26 15:19:44.982  1454  1454 I wpa_supplicant: [NULL] 00:1f:27:54:70:c0 freq=2412 level=-60
07-26 15:19:44.982  1454  1454 I wpa_supplicant: [NULL] 00:1f:27:54:70:c1 freq=2412 level=-60
07-26 15:19:44.982  1454  1454 I wpa_supplicant: [NULL] 84:b2:61:1c:62:da freq=5220 level=-82
07-26 15:19:44.982  1454  1454 I wpa_supplicant: [NULL] 58:48:22:93:c9:6d freq=2412 level=-83
07-26 15:19:44.982  1454  1454 I wpa_supplicant: [NULL] 00:fe:c8:73:02:04 freq=2462 level=-88
07-26 15:19:44.982  1454  1454 I wpa_supplicant: [NULL] 84:b2:61:1c:62:de freq=5220 level=-82
07-26 15:19:44.982  1454  1454 I wpa_supplicant: [NULL] 84:b2:61:1a:ce:73 freq=2412 level=-85
07-26 15:19:44.982  1454  1454 D wpa_supplicant: wlan0: BSS: Start scan result update 3
07-26 15:19:44.982  1454  1454 D wpa_supplicant: wlan0: BSS: Add new id 8 BSSID f0:f2:6d:22:99:3e SSID 'NG700_GUEST'
07-26 15:19:44.982  1454  1454 D wpa_supplicant: BSS: last_scan_res_used=9/32
07-26 15:19:44.982  1454  1454 D wpa_supplicant: wlan0: Scan-only results received
07-26 15:19:44.982  1454  1454 D wpa_supplicant: wlan0: Radio work 'scan'@0x55b0d30860 done in 0.084198 seconds
07-26 15:19:44.982  1010  1688 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 8 f0:f2:6d:22:99:3e]
07-26 15:19:44.982  1010  1688 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
07-26 15:19:44.982  1010  1688 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
07-26 15:19:44.982  1010  1282 E WifiStateMachine: handleMessage: E msg.what=147461
07-26 15:19:44.982  1010  1282 E WifiStateMachine: processMsg: ConnectedState
07-26 15:19:44.982  1010  1282 E WifiStateMachine:  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=8 known=1 got=8 bcn=0
07-26 15:19:44.982  1010  1282 E WifiStateMachine: processMsg: L2ConnectedState
07-26 15:19:44.982  1010  1282 E WifiStateMachine:  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=8 known=1 got=8 bcn=0
07-26 15:19:44.982  1010  1282 E WifiStateMachine: processMsg: ConnectModeState
07-26 15:19:44.982  1010  1282 E WifiStateMachine:  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=8 known=1 got=8 bcn=0
07-26 15:19:44.982  1010  1282 E WifiStateMachine: processMsg: DriverStartedState
07-26 15:19:44.982  1010  1282 E WifiStateMachine:  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=8 known=1 got=8 bcn=0
07-26 15:19:44.982  1010  1282 E WifiStateMachine: processMsg: SupplicantStartedState
07-26 15:19:44.992  1010  1282 E WifiStateMachine:  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=8 known=1 got=8 bcn=0
07-26 15:19:44.992  1010  1282 D WifiStateMachine: [MLHD] enter handleMediaLinkEvent SupplicantStartedState
07-26 15:19:44.992  1010  1282 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
07-26 15:19:44.992  1454  1454 D wpa_supplicant: wlan0: Control interface command 'LIST_DONGLES'
07-26 15:19:44.992  1010  1282 W ContextImpl: Calling a method ,in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14202 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14367 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8128 
07-26 15:19:44.992  5976  5976 W AudioCapabilities: Unsupported mime audio/qcelp
07-26 15:19:44.992  5976  5976 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,07-26 15:19:45.002  5976  5976 W AudioCapabilities: Unsupported mime audio/qcelp
,07-26 15:19:45.002  5976  5976 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,07-26 15:19:45.012  5761  5761 D io.jxcore.node.LifeCycleMonitor: onActivityPaused,
07-26 15:19:45.012  1010  1816 D PMS     : acquireWL(328d0c3f): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 1010 1000 null
07-26 15:19:45.012  5761  5761 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,07-26 15:19:45.012  1010  1282 E WifiStateMachine: [1,469,539,185,016 ms] noteScanEnd no scan source
07-26 15:19:45.012  1010  1282 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
07-26 15:19:45.012  1454  1454 D wpa_supplicant: wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
07-26 15:19:45.012  5761  5870 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 48ms. Plugin should use CordovaInterface.getThreadPool().
,07-26 15:19:45.012  1010  1282 E WifiStateMachine: wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@29a7236c sup_state=COMPLETED debouncing=false
07-26 15:19:45.012  1010  1282 E WifiAutoJoinController : NG700 f4:f2:6d:22:99:3e rssi=-50 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
07-26 15:19:45.012  1010  1282 E WifiConfigStore: updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
07-26 15:19:45.012  1010  1282 E WifiConfigStore: updateSavedNetworkHistory: HTC improve mode
07-26 15:19:45.012  1010  1282 E WifiConfigStore:         got known scan result f4:f2:6d:22:99:3e key : "NG700"WPA_PSK num: 1 rssi=-50 freq=2447
07-26 15:19:45.012  1010  1282 E WifiAutoJoinController : TEST_KTW01 00:1f:27:54:70:c1 rssi=-60 cap [WPA2-EAP-TKIP][ESS] is not scored
07-26 15:19:45.012  1010  1282 E WifiAutoJoinController : ktwtestwifi 00:1f:27:54:70:c0 rssi=-60 cap [WPA2-EAP-CCMP+TKIP][ESS] is not scored
,07-26 15:19:45.012  1010  1282 E WifiAutoJoinController :  84:b2:61:1c:62:da rssi=-82 cap [WPA2-EAP-CCMP][ESS] is not scored
07-26 15:19:45.012  1010  1282 E WifiAutoJoinController : Xperia Z5_ff02 58:48:22:93:c9:6d rssi=-83 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
07-26 15:19:45.012  1010  1282 E WifiAutoJoinController :  00:fe:c8:73:02:04 rssi=-88 cap [WPA2-EAP-CCMP][ESS] is not scored
07-26 15:19:45.012  1010  1282 E WifiAutoJoinController :  84:b2:61:1c:62:de rssi=-82 cap [ESS] is not scored
07-26 15:19:45.012  1010  1282 E WifiAutoJoinController : RA-WINGS 84:b2:61:1a:ce:73 rssi=-85 cap [ESS] is not scored
07-26 15:19:45.012  1010  1282 E WifiAutoJoinController : NG700_GUEST f0:f2:6d:22:99:3e rssi=-45 cap [WPA2-PSK-CCMP][ESS] is not scored
07-26 15:19:45.012  1010  1282 E WifiAutoJoinController : ageScanResultsOut delay 40000 size 9 now 1469539185022
07-26 15:19:45.012  1010  1282 E WifiAutoJoinController : newSupplicantResults size=9 known=1 true
07-26 15:19:45.012  1010  1282 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
07-26 15:19:45.022  1454  1454 D wpa_supplicant: wlan0: Control interface command 'STATUS-NO_EVENTS'
07-26 15:19:45.022  1010  1684 W HtcSystemUPManager: HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
07-26 15:19:45.022  1010  1282 E WifiAutoJoinController : attemptAutoJoin() status=bssid=f4:f2:6d:22:99:3e
07-26 15:19:45.022  1010  1282 E WifiAutoJoinController : ssid=NG700
07-26 15:19:45.022  1010  1282 E WifiAutoJoinController : id=0
07-26 15:19:45.022  1010  1282 E WifiAutoJoinController : mode=station
07-26 15:19:45.022  1010  1282 E WifiAutoJoinController : pairwise_cipher=CCMP
07-26 15:19:45.022  1010  1282 E WifiAutoJoinController : group_cipher=CCMP
07-26 15:19:45.022  1010  1282 E WifiAutoJoinController : key_mgmt=WPA2-PSK
07-26 15:19:45.022  1010  1282 E WifiAutoJoinController : wpa_state=COMPLETED
07-26 15:19:45.022  1010  1282 E WifiAutoJoinController : ip_address=192.168.1.126
07-26 15:19:45.022  1010  1282 E WifiAutoJoinController : p2p_device_address=92:e7:c4:e6:4c:f8
07-26 15:19:45.022  1010  1282 E WifiAutoJoinController : address=XX:XX:XX:XX:XX:XX
07-26 15:19:45.022  1010  1282 E WifiAutoJoinController : uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
,07-26 15:19:45.022  1010  1282 E WifiAutoJoinController : attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
07-26 15:19:45.022  1010  1282 E WifiAutoJoinController : attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-50,-127) num=(1,0)
07-26 15:19:45.022  1010  1282 E WifiAutoJoinController : attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
07-26 15:19:45.022  1010  1282 E WifiAutoJoinController : attemptRoam: "NG700"WPA_PSK Found f4:f2:6d:22:99:3e rssi=-50 freq=2447 Current: f4:f2:6d:22:99:3e
07-26 15:19:45.022  1010  1282 D HtcWifiControlRoamOffload: : roamCandidate: nullcurrentBSSID: f4:f2:6d:22:99:3e
07-26 15:19:45.022  1010  1282 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
07-26 15:19:45.022  1010  1282 E WifiAutoJoinController : Done attemptAutoJoin status=0
07-26 15:19:45.022  1010  1282 E WifiConfigStore:  writeKnownNetworkHistory() num networks:1 needWrite=false
07-26 15:19:45.022  1010  1282 E WifiStateMachine: handleMessage: X
,07-26 15:19:45.032  1630  1630 W SystemReader: Cannot find allapps_style_enabled_deafult, use default value instead
07-26 15:19:45.032  1630  1630 I Prism.AllAppsOptionsMa_: getAllAppsAbility() true
07-26 15:19:45.032  1630  1630 W SystemReader: Cannot find support_china_sense_feature, use default value instead
07-26 15:19:45.032  1630  1630 I Prism.AllAppsOptionsMa_: removeAllAppsAbility()
07-26 15:19:45.032  1630  1630 W SystemReader: Cannot find support_china_sense_feature, use default value instead
,07-26 15:19:45.042  1630  1630 I FeedHostManager: [onResume]
07-26 15:19:45.042  1630  1630 I FeedProviderManager: onResume
07-26 15:19:45.042  1630  2634 I SocialFeedProvider: +onResume
07-26 15:19:45.042  1630  2634 I SocialFeedProvider: updateAccounts - Accounts is no change
07-26 15:19:45.042  1630  2634 I SocialFeedProvider: -onResume
,07-26 15:19:45.082  5976  5976 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es,
,07-26 15:19:45.082  5976  5976 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-26 15:19:45.082  5976  5976 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-26 15:19:45.092  5976  5976 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc,
,07-26 15:19:45.092  5976  5976 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc,
,07-26 15:19:45.192  1010  1740 I art     : Explicit concurrent mark sweep GC freed 13288(714KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 18MB/27MB, paused 1.410ms total 149.232ms
,07-26 15:19:45.192  1010  1816 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
07-26 15:19:45.192  1630  1630 I ContextualWidget: onResume,
07-26 15:19:45.192  1630  1630 I ContextualWidget: notifyWidgetActive location size=0 user consent location=false
07-26 15:19:45.192  1630  1630 W SystemReader: Cannot find enable_suggestion_option, use default value instead
07-26 15:19:45.192  1630  1907 I ContextualWidget: handleMessage, what=1018 mode=GettingOut maxcount=8
07-26 15:19:45.192  1630  1630 I ContextualWidget: ignore uploadUsageData location=false usage data=false allowAutoUpload=true
07-26 15:19:45.192  1630  1630 W SystemReader: Cannot find enable_suggestion_option, use default value instead
07-26 15:19:45.192  1630  1630 I ContextualWidget: postSyncRecommendedApps, isReady=false allowAutoSync=true syncMode=1 isEnableRecommend=true
,07-26 15:19:45.202  1010  1067 D StatusBarManagerService: setSystemUiVisibility(0x8700),
07-26 15:19:45.202  1010  1067 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-26 15:19:45.202  1010  1067 D StatusBarManagerService: hiding MENU key
,07-26 15:19:45.212  1630  1630 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,07-26 15:19:45.222  1630  1630 I ThreadedRenderer: Defer allocateBuffers to drawing time
,07-26 15:19:45.222  1010  1668 I InputMethodManagerService: Disable input method client, pid=5761,
07-26 15:19:45.222  1351  1351 I PhoneStatusBar: setImeWindowStatus(false,false)
07-26 15:19:45.222  1010  1668 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
,07-26 15:19:45.222  5761  5761 W IInputConnectionWrapper: reportFullscreenMode on inactive InputConnection
07-26 15:19:45.222  1010  1668 I InputMethodManagerService: Enable input method client, pid=1630
,07-26 15:19:45.252  6030  6044 E cutils-trace: Error opening trace file: Permission denied (13)
,07-26 15:19:45.272  1010  1030 D PMS     : releaseWL(328d0c3f): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,07-26 15:19:45.292  5976  5976 I vclib   : onServiceConnected,
07-26 15:19:45.292  5976  5976 W Babel   : Attempted to change video mute state without an active call.
07-26 15:19:45.292  1010  1067 D StatusBarManagerService: setSystemUiVisibility(0xc0000700)
,07-26 15:19:45.292  1010  1067 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-26 15:19:45.292  1010  1067 D StatusBarManagerService: hiding MENU key
,07-26 15:19:45.302  6008  6008 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,07-26 15:19:45.312  1351  5913 D RingtonePlayer: onCompletion
07-26 15:19:45.312  1351  5913 D MediaPlayer: Send PlaybackCompleteEvent for LPCM,
07-26 15:19:45.312  1010  1010 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
07-26 15:19:45.322  1010  1010 E WifiTrafficPoller:  packet count Tx=207 Rx=374
07-26 15:19:45.322  1010  1010 E WifiTrafficPoller: notifying of data activity 1
,07-26 15:19:45.352  1351  1351 D WIFI_ICON: WifiActivity: 1
,07-26 15:19:45.352  6008  6037 I Gmail   : getAccountsCursor
07-26 15:19:45.352  1351  1351 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T],
07-26 15:19:45.352  1010  1047 D Process : killProcessQuiet, pid=5447
07-26 15:19:45.352  1010  1047 I ActivityManager: Killing 5447:com.htc.sense.news/u0a74 (adj 15): empty #17
07-26 15:19:45.352  1010  1047 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityStack.destroyActivityLocked:3435 
,07-26 15:19:45.382  1010  1668 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.AttachmentService, state=2, flag=1, pid=6008, uid=10106, userID:0
,07-26 15:19:45.402  5976  5976 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
07-26 15:19:45.402  5976  5976 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-26 15:19:45.412  6030  6030 D CustomizationManager: ====startRecUseTime====
07-26 15:19:45.412  6030  6030 D htc.customization.log.level:  is 
07-26 15:19:45.412  6030  6030 W CustomizationLogLevel: Level value is invalid, use default level 2
,07-26 15:19:45.442   431  1000 V SRS_Proc: ParamSet string: Ramping_upper_speaker=disable,
07-26 15:19:45.442   431  1000 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
,07-26 15:19:45.452   431  1055 W AudFlgTh: A_Shock: Stop Aocustic shock !,
,07-26 15:19:45.462  1010  1029 I ActivityManager: Recipient 5447,
,07-26 15:19:45.482  6030  6030 D CustomizationManager:  Read ACC file spent 0.037 (s),
,07-26 15:19:45.482  6030  6030 D CIDMapFileReader: Parsing tag item name = HTC__001,
07-26 15:19:45.482  6030  6030 D CIDMapFileReader: Parsing tag item name = HTC__102
07-26 15:19:45.482  6030  6030 D CIDMapFileReader: Parsing tag item name = HTC__Y13
07-26 15:19:45.482  6030  6030 D CIDMapFileReader: Parsing tag item name = HTC__032
07-26 15:19:45.482  6030  6030 D CIDMapFileReader: Parsing tag item name = HTC__M27
07-26 15:19:45.482  6030  6030 D CIDMapFileReader: Parsing tag item name = HTC__002
07-26 15:19:45.482  6030  6030 D CIDMapFileReader: Parsing tag item name = HTC__031
07-26 15:19:45.482  6030  6030 D CIDMapFileReader: Parsing tag item name = HTC__A07
,07-26 15:19:45.482  6030  6030 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__102.xml
07-26 15:19:45.482  6030  6030 I CustomizationCIDLoader: Parsing tag category name = system
07-26 15:19:45.482  6030  6030 I CustomizationCIDLoader: Parsing tag category name = application
07-26 15:19:45.482  6030  6030 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
07-26 15:19:45.482  6030  6030 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
07-26 15:19:45.482  6030  6030 I CustomizationCIDLoader: Parsing tag category name = AudioService
07-26 15:19:45.482  6030  6030 I CustomizationCIDLoader: Parsing tag category name = Settings
07-26 15:19:45.482  6030  6030 I CustomizationCIDLoader: Parsing tag category name = ACC
07-26 15:19:45.492  6030  6030 I CustomizationCIDLoader: add string-array item, value = 42507
07-26 15:19:45.492  6030  6030 I CustomizationCIDLoader: add string-array item, value = 21902
07-26 15:19:45.492  6030  6030 I CustomizationCIDLoader: add string-array item, value = 26006:26001.26002.26003
07-26 15:19:45.492  6030  6030 I CustomizationCIDLoader: add string-array item, value = 23420
07-26 15:19:45.492  6030  6030 I CustomizationCIDLoader: add string-array item, value = 22299
07-26 15:19:45.492  6030  6030 I CustomizationCIDLoader: add string-array item, value = 24002
07-26 15:19:45.492  6030  6030 I CustomizationCIDLoader: add string-array item, value = 23210
07-26 15:19:45.492  6030  6030 I CustomizationCIDLoader: add string-array item, value = 23205
07-26 15:19:45.492  6030  6030 I CustomizationCIDLoader: add string-array item, value = 23806
07-26 15:19:45.492  6030  6030 I CustomizationCIDLoader: add string-array item, value = 23430
07-26 15:19:45.492  6030  6030 I CustomizationCIDLoader: add string-array item, value = 23408
07-26 15:19:45.492  6030  6030 I CustomizationCIDLoader: add string-array item, value = 27205
07-26 15:19:45.492  6030  6030 I CustomizationCIDLoader: add string-array item, value = 42507:C:1:0
07-26 15:19:45.492  6030  6030 I CustomizationCIDLoader: add string-array item, value = 21902:C:1:0
07-26 15:19:45.492  6030  6030 I CustomizationCIDLoader: add string-array item, value = 26006:D:1:0
07-26 15:19:45.492  6030  6030 I CustomizationCIDLoader: add string-array item, value = 23420:D:0:0
07-26 15:19:45.492  6030  6030 I CustomizationCIDLoader: add string-array item, value = 22299:D:0:0
07-26 15:19:45.492  6030  6030 I CustomizationCIDLoader: add string-array item, value = 24002:D:0:0
07-26 15:19:45.492  6030  6030 I CustomizationCIDLoader: add string-array item, value = 23210:D:2:0
07-26 15:19:45.492  6030  6030 I CustomizationCIDLoader: add string-array item, value = 23205:D:2:0
07-26 15:19:45.492  6030  6030 I CustomizationCIDLoader: add string-array item, value = 23806:D:0:0
07-26 15:19:45.492  6030  6030 I CustomizationCIDLoader: add string-array item, value = 23430:C:1:0
07-26 15:19:45.492  6030  6030 I CustomizationCIDLoader: add string-array item, value = 23408:C:1:0
07-26 15:19:45.492  6030  6030 I CustomizationCIDLoader: add string-array item, value = 27205:C:1:0
07-26 15:19:45.492  6030  6030 D CustomizationManager:  Read CID file spent 0.075 (s)
07-26 15:19:45.492  6030  6030 D CustomizationManager:  All configurations done spent 0.075 (s)
,07-26 15:19:45.532  1010  1818 D PackageManager: deletePackageAsUser: pkg=com.test.thalitest, pid=6030, uid=2000 userid=0,
,07-26 15:19:45.572  5761  5761 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,07-26 15:19:45.572  5761  5761 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
07-26 15:19:45.572  5761  5761 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-26 15:19:45.572  5761  5761 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
07-26 15:19:45.572  5761  5761 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:19:45.572  5761  5761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:19:45.572  5761  5761 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:19:45.572  5761  5761 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:19:45.572  5761  5761 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1db5983b removed from the list
,07-26 15:19:45.572  5761  5761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:19:45.572  5761  5761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19031d96 removed from the list
07-26 15:19:45.572  5761  5761 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:19:45.572  5761  5761 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,07-26 15:19:45.612  1010  1224 W PackageSettings: Skipping PackageSetting{19397cfa com.example.hello/10374} due to missing metadata,
,07-26 15:19:45.632  1010  1811 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found,
,07-26 15:19:45.642  1995  1995 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-26 15:19:45.642  1010  1047 I ActivityManager: Force stopping com.test.thalitest appid=10195 user=-1: uninstall pkg
,07-26 15:19:45.652  1010  1047 I ActivityManager: Killing 5761:com.test.thalitest/u0a195 (adj 9): stop com.test.thalitest
,07-26 15:19:45.652  1010  1047 D Process : killProcessQuiet, pid=5761
,07-26 15:19:45.652  1010  1047 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6372 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
,07-26 15:19:45.652  6008  6062 I Gmail   : Observing account changes for notifications
,07-26 15:19:45.762  1630  2203 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...,
,07-26 15:19:45.822  5976  5976 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,07-26 15:19:45.852  1010  1813 I ActivityManager: Recipient 5761
,07-26 15:19:45.862  1010  1478 I WindowState: WIN DEATH: Window{3de6ac6d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,07-26 15:19:45.862  1511  1511 E InputEventReceiver: Looper::removeFd(68) is failed, result(0), input channel 'ClientState{2dad54ee uid 10195 pid 5761} (c)'
07-26 15:19:45.862  1010  1283 D WifiService: Client connection lost with reason: 4
07-26 15:19:45.862  1010  1047 E libprocessgroup: failed to kill 1 processes for processgroup 5761
07-26 15:19:45.862  1010  1047 W ActivityManager: ProcessRecord{1ea55d3c 5761:com.test.thalitest/u0a195} has been replaced to new process null
,07-26 15:19:45.872  1010  1816 W ActivityManager: unregisterReceiver: receiver object not existed in mRegisteredReceivers,
,07-26 15:19:45.882  1010  1224 I ActivityManager: Force stopping com.test.thalitest appid=10195 user=0: pkg removed
,07-26 15:19:45.902  1010  1291 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
07-26 15:19:45.902  1010  1813 W ActivityManager: Spurious death for ProcessRecord{1ea55d3c 0:com.test.thalitest/u0a195}, curProc for 5761: null
07-26 15:19:45.902  1010  1740 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=6008, uid=10106, userID:0,
,07-26 15:19:45.902  1010  1687 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=6008, uid=10106, userID:0
07-26 15:19:45.912  1458  1458 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
07-26 15:19:45.912  1458  1458 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,07-26 15:19:45.912  1010  1810 D PMS     : acquireWL(17bd6c1a): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1869 10024 WorkSource{10024 com.google.android.gms}
07-26 15:19:45.912  1786  2165 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,07-26 15:19:45.922  1869  2280 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-26 15:19:45.922  1010  1740 D PMS     : releaseWL(17bd6c1a): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
07-26 15:19:45.922  1010  1816 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,07-26 15:19:45.932  1010  1280 V NetworkPolicy: ACTION_UID_REMOVED for uid=10195
07-26 15:19:45.932  1010  1280 V NetworkPolicy: writePolicyLocked()
,07-26 15:19:45.942  1010  1279 D PMS     : acquireWL(17362fe6): PARTIAL_WAKE_LOCK  NetworkStats 0x1 1010 1000 null
,07-26 15:19:45.942  1010  1273 W SystemReader: Cannot find grip_rejection_width, use default value instead
07-26 15:19:45.942  1010  1271 V AlarmManager: sending alarm PendingIntent{d7217d4: PendingIntentRecord{3eceed7d com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1469539185946, Int=0
07-26 15:19:45.942  1786  2165 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,07-26 15:19:45.952  1010  1280 V NetworkPolicy: updateNetworkEnabledLocked(),
07-26 15:19:45.952  5976  5976 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
07-26 15:19:45.952  1010  1280 V NetworkPolicy: updateNotificationsLocked()
07-26 15:19:45.952  5976  5976 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-26 15:19:45.982  1578  1578 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,07-26 15:19:45.992  1010  1279 D PMS     : releaseWL(17362fe6): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
07-26 15:19:46.002  1786  2165 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,07-26 15:19:46.002  6008  6065 E Gmail   : Error finding the version of the Email provider.....
07-26 15:19:46.002  6008  6065 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
07-26 15:19:46.002  6008  6065 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
07-26 15:19:46.002  6008  6065 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
07-26 15:19:46.002  6008  6065 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
07-26 15:19:46.002  6008  6065 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-26 15:19:46.002  6008  6065 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:19:46.002  6008  6065 E Gmail   : 	at android.os.Looper.loop(Looper.java:155)
07-26 15:19:46.002  6008  6065 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-26 15:19:46.002  6008  6065 W EmailMigration: We do not support migrating this version of the Email provider.
,07-26 15:19:46.012  1630  1630 I art     : Explicit concurrent mark sweep GC freed 79096(5MB) AllocSpace objects, 49(3MB) LOS objects, 32% free, 32MB/48MB, paused 2.894ms total 120.175ms
07-26 15:19:46.012  1010  1046 I InputMethodManagerService: [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
07-26 15:19:46.032  1786  2165 E ExternalAccountType: Unsupported attribute readOnly
,07-26 15:19:46.032  1578  1623 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,07-26 15:19:46.042  6008  6068 I Gmail   : getAccountsCursor
,07-26 15:19:46.052  5976  6033 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-26 15:19:46.052  5976  6033 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-26 15:19:46.052  1995  1995 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-26 15:19:46.062  5976  6033 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-26 15:19:46.092  1010  1740 I ActivityManager: Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=6071 uid=10197 gids={50197, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,07-26 15:19:46.132  1010  1046 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,07-26 15:19:46.132  1010  1010 W PackageManager: Unable to load service info ResolveInfo{34202d1b com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
07-26 15:19:46.132  1010  1010 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
07-26 15:19:46.132  1010  1010 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
07-26 15:19:46.132  1010  1010 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
07-26 15:19:46.132  1010  1010 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
07-26 15:19:46.132  1010  1010 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
,07-26 15:19:46.132  1010  1010 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
07-26 15:19:46.132  1010  1010 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
07-26 15:19:46.132  1010  1010 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
07-26 15:19:46.132  1010  1010 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-26 15:19:46.132  1010  1010 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
07-26 15:19:46.132  1010  1010 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:324)
07-26 15:19:46.132  1010  1010 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:225)
07-26 15:19:46.132  1010  1010 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
07-26 15:19:46.132  1010  1010 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-26 15:19:46.132  1010  1010 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
07-26 15:19:46.132  1010  1010 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,07-26 15:19:46.162  1010  1818 D PMS     : releaseWL(c75a599): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
07-26 15:19:46.162  6008  6069 E SQLiteLog: (283) recovered 1991 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal,
,07-26 15:19:46.162  1010  1047 I ActivityManager: Waited long enough for: ServiceRecord{ac97763 u0 com.htc.club/com.mcrm.autonotification.NotificationService}
,07-26 15:19:46.192  1010  1224 I art     : Explicit concurrent mark sweep GC freed 22348(1973KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 18MB/27MB, paused 2.015ms total 259.151ms,
,07-26 15:19:46.272  6008  6086 I Gmail   : notifyAccountChanged,
,07-26 15:19:46.282  1630  1900 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false,
07-26 15:19:46.282  1630  1900 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,07-26 15:19:46.282  6008  6086 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,07-26 15:19:46.292  6008  6098 I Gmail   : getAccountsCursor
07-26 15:19:46.292  6008  6086 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,07-26 15:19:46.312  6008  6086 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running,
,07-26 15:19:46.312  6008  6086 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,07-26 15:19:46.342  1010  1010 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,07-26 15:19:46.352  1010  1316 D TaskPersister: removeObsoleteFile: deleting file=4_task.xml
07-26 15:19:46.352  1010  1010 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 7
07-26 15:19:46.352  1010  1316 D TaskPersister: removeObsoleteFile: deleting file=4_task_thumbnail.png
07-26 15:19:46.352  1010  1010 E WifiTrafficPoller:  packet count Tx=207 Rx=376
,07-26 15:19:46.362  1995  4587 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
07-26 15:19:46.362  1995  4587 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
07-26 15:19:46.362  1995  4587 I GLSUser : [GLSUser] Extracting token using key: Auth
07-26 15:19:46.362  1995  4587 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-26 15:19:46.362  1995  4587 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-26 15:19:46.382  5976  6095 E Babel   : UserRecoverableAuthException.
,07-26 15:19:46.392  6008  6098 I Gmail   : master sync=false, engine sync=true
,07-26 15:19:46.392  5976  6095 E Babel   : eei: BadAuthentication
07-26 15:19:46.392  5976  6095 E Babel   : 	at eeg.a(Unknown Source)
07-26 15:19:46.392  5976  6095 E Babel   : 	at eeg.a(Unknown Source)
07-26 15:19:46.392  5976  6095 E Babel   : 	at eeg.a(Unknown Source)
07-26 15:19:46.392  5976  6095 E Babel   : 	at g.a(Unknown Source)
07-26 15:19:46.392  5976  6095 E Babel   : 	at cae.a(SourceFile:3089)
07-26 15:19:46.392  5976  6095 E Babel   : 	at cae.a(SourceFile:1131)
07-26 15:19:46.392  5976  6095 E Babel   : 	at cws.a(SourceFile:4333)
07-26 15:19:46.392  5976  6095 E Babel   : 	at cws.a(SourceFile:1419)
07-26 15:19:46.392  5976  6095 E Babel   : 	at crl.a(SourceFile:492)
07-26 15:19:46.392  5976  6095 E Babel   : 	at crl.a(SourceFile:1468)
07-26 15:19:46.392  5976  6095 E Babel   : 	at cqu.a(SourceFile:4416)
07-26 15:19:46.392  5976  6095 E Babel   : 	at cas.b(SourceFile:106)
07-26 15:19:46.392  5976  6095 E Babel   : 	at cap.d(SourceFile:335)
07-26 15:19:46.392  5976  6095 E Babel   : 	at caq.run(SourceFile:81)
07-26 15:19:46.392  5976  6095 E Babel   : Error getting auth token
,07-26 15:19:46.392  5976  6095 E Babel   : dvm
07-26 15:19:46.392  5976  6095 E Babel   : 	at g.a(Unknown Source)
07-26 15:19:46.392  5976  6095 E Babel   : 	at cae.a(SourceFile:3089)
07-26 15:19:46.392  5976  6095 E Babel   : 	at cae.a(SourceFile:1131)
07-26 15:19:46.392  5976  6095 E Babel   : 	at cws.a(SourceFile:4333)
07-26 15:19:46.392  5976  6095 E Babel   : 	at cws.a(SourceFile:1419)
07-26 15:19:46.392  5976  6095 E Babel   : 	at crl.a(SourceFile:492)
07-26 15:19:46.392  5976  6095 E Babel   : 	at crl.a(SourceFile:1468)
07-26 15:19:46.392  5976  6095 E Babel   : 	at cqu.a(SourceFile:4416)
07-26 15:19:46.392  5976  6095 E Babel   : 	at cas.b(SourceFile:106)
07-26 15:19:46.392  5976  6095 E Babel   : 	at cap.d(SourceFile:335)
07-26 15:19:46.392  5976  6095 E Babel   : 	at caq.run(SourceFile:81)
,07-26 15:19:46.402  6008  6103 I Gmail   : getAccountsCursor
,07-26 15:19:46.402  5976  6095 E Babel   : Account registration failed 1-Redacted-21
,07-26 15:19:46.402  5976  6095 E Babel   : cyp: null -- null
07-26 15:19:46.402  5976  6095 E Babel   : 	at cae.a(SourceFile:3121)
07-26 15:19:46.402  5976  6095 E Babel   : 	at cae.a(SourceFile:1131)
07-26 15:19:46.402  5976  6095 E Babel   : 	at cws.a(SourceFile:4333),
07-26 15:19:46.402  5976  6095 E Babel   : 	at cws.a(SourceFile:1419)
07-26 15:19:46.402  5976  6095 E Babel   : 	at crl.a(SourceFile:492)
07-26 15:19:46.402  5976  6095 E Babel   : 	at crl.a(SourceFile:1468)
07-26 15:19:46.402  5976  6095 E Babel   : 	at cqu.a(SourceFile:4416)
07-26 15:19:46.402  5976  6095 E Babel   : 	at cas.b(SourceFile:106)
07-26 15:19:46.402  5976  6095 E Babel   : 	at cap.d(SourceFile:335)
07-26 15:19:46.402  5976  6095 E Babel   : 	at caq.run(SourceFile:81)
,07-26 15:19:46.402  1995  1995 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-26 15:19:46.412  6008  6103 I Gmail   : master sync=false, engine sync=true
,07-26 15:19:46.412  5976  6095 I art     : Note: end time exceeds epoch: 
,07-26 15:19:46.422  5976  6104 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
07-26 15:19:46.422  5976  6104 D libc    : [NET] android_getaddrinfofornet-, err=8
07-26 15:19:46.422  5976  6104 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
07-26 15:19:46.422  5976  6104 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
07-26 15:19:46.422  5976  6104 D libc    : [NET] android_getaddrinfo_proxy+
07-26 15:19:46.422  5976  6104 D libc    : [NET] android_getaddrinfo_proxy get netid:0
07-26 15:19:46.422   413  6110 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
07-26 15:19:46.422   413  6110 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
07-26 15:19:46.422   413  6110 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
07-26 15:19:46.422   413  6110 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
07-26 15:19:46.422  5976  6104 D libc    : [NET] android_getaddrinfo_proxy-, success
,07-26 15:19:46.422  1010  1291 D PMS     : acquireWL(8101969): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.photos/.jobqueue.JobService 0x1 6071 10197 null
,07-26 15:19:46.432  1995  6113 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,07-26 15:19:46.432  1995  1995 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,07-26 15:19:46.442  2224  2224 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,07-26 15:19:46.452  6008  6069 I NotifUtils: Validating Notification, mapSize: 0 getAttention: true ignoreUnobtrusive: false,
07-26 15:19:46.462  1995  4588 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
07-26 15:19:46.462  1010  1819 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=2224, uid=10024, userID:0
07-26 15:19:46.462  1995  4588 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
07-26 15:19:46.462  1995  4588 I GLSUser : [GLSUser] Extracting token using key: Auth
07-26 15:19:46.462  1995  4588 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-26 15:19:46.462  1010  1687 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=2224, uid=10024, userID:0
,07-26 15:19:46.462  1995  4588 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-26 15:19:46.462  1010  1810 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=2224, uid=10024, userID:0
07-26 15:19:46.472  2224  4559 I CheckinService: Done disabling old GoogleServicesFramework version
07-26 15:19:46.472  1010  1687 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=2224, uid=10024, userID:0
,07-26 15:19:46.472  1869  6116 E MDM     : [141] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,07-26 15:19:46.482  2224  6117 D LocationInitializer: Restart initialization of location,
,07-26 15:19:46.482  5976  6104 I Babel   : connection state changed from UNKNOWN to CONNECTED
,07-26 15:19:46.492  1010  1810 D PMS     : releaseWL(8101969): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.photos/.jobqueue.JobService 0x1 null
,07-26 15:19:46.502  1010  1291 I ActivityManager: Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=6119 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
,07-26 15:19:46.522  1995  4588 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-26 15:19:46.532  6008  6069 I NotifUtils: validateNotifications - cancelling 1729800001 for 61035162 / -317575340,
,07-26 15:19:46.542  1010  1291 D Process : killProcessQuiet, pid=5470,
07-26 15:19:46.542  1010  1291 I ActivityManager: Killing 5470:com.htc.widget.hmsproc2/u0a40 (adj 15): empty #17
07-26 15:19:46.542  1010  1291 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 ,
07-26 15:19:46.552  5976  6107 E Babel   : Unexpected exception while authenticating.
07-26 15:19:46.552  5976  6107 E Babel   : eej: User intervention required. Notification has been pushed.
07-26 15:19:46.552  5976  6107 E Babel   : 	at eeg.b(Unknown Source)
07-26 15:19:46.552  5976  6107 E Babel   : 	at eeg.b(Unknown Source)
07-26 15:19:46.552  5976  6107 E Babel   : 	at g.a(Unknown Source)
07-26 15:19:46.552  5976  6107 E Babel   : 	at cae.b(SourceFile:1146)
07-26 15:19:46.552  5976  6107 E Babel   : 	at dcg.run(SourceFile:5617)
07-26 15:19:46.552  5976  6107 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-26 15:19:46.552  5976  6107 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-26 15:19:46.552  5976  6107 E Babel   : 	at java.lang.Thread.run(Thread.java:818)
07-26 15:19:46.552  6119  6119 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,07-26 15:19:46.622  1010  1813 D PMS     : releaseWL(38a53714): PARTIAL_WAKE_LOCK  AudioMix 0x1 null,
,07-26 15:19:46.672  1010  1819 I ActivityManager: Recipient 5470,
,07-26 15:19:46.772  1458  1685 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true, isForDotMatrix: false
07-26 15:19:46.772  1458  1685 D DotMatrix: [EventService] notificationPosted, eventType:1014
07-26 15:19:46.772  6119  6119 D CalendarApplication: onCreate
07-26 15:19:46.782  6119  6119 D ProviderChangeReceiver: ---------------------------------------------------
07-26 15:19:46.782  6119  6119 D ProviderChangeReceiver: ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,07-26 15:19:46.782  1351  1351 I RemoteViews: reapply : com.google.android.gms 6 40
,07-26 15:19:46.792  1010  1819 I ActivityManager: Killing 5497:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
07-26 15:19:46.792  1010  1819 D Process : killProcessQuiet, pid=5497
07-26 15:19:46.792  1010  1819 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,07-26 15:19:46.792  1458  1685 D DotMatrix: [EventService] notificationPosted, This eventType was disabled by user.
07-26 15:19:46.792  6119  6146 D HtcAlertService: start to updateAlertNotification!
,07-26 15:19:46.902  1010  1291 I ActivityManager: Recipient 5497
,07-26 15:19:47.012  1995  2935 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,07-26 15:19:47.012  1995  1995 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.,
,07-26 15:19:47.022  2224  2224 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,07-26 15:19:47.022  6119  6146 D HtcAlertService: No fired or scheduled alerts
,07-26 15:19:47.022  6119  6146 D HtcAlertUtils: -- cancelReminderNotification --
,07-26 15:19:47.032  6119  6146 D HtcAlertUtils: broadcastExistReminder!,
,07-26 15:19:47.032  1458  1458 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
,07-26 15:19:47.052  1010  1811 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=2224, uid=10024, userID:0,
,07-26 15:19:47.052  1869  6148 E MDM     : [142] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,07-26 15:19:47.052  1010  1282 E WifiStateMachine: handleMessage: E msg.what=131155
07-26 15:19:47.052  1010  1282 E WifiStateMachine: processMsg: ConnectedState
07-26 15:19:47.052  1010  1282 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-50 f=2447 sc=60 link=150 tx=9.3, 0.0, 0.0  rx=12.1 bcn=0 [on:0 tx:0 rx:0 period:2149] from screen [on:0 period:660371827] gl hn u24 rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-26 15:19:47.052  1010  1282 E WifiStateMachine: processMsg: L2ConnectedState
07-26 15:19:47.052  1010  1282 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-50 f=2447 sc=60 link=150 tx=9.3, 0.0, 0.0  rx=12.1 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:660371829] gl hn u24 rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-26 15:19:47.052  1010  1282 E WifiStateMachine:  get link layer stats 0
07-26 15:19:47.052  1010  1282 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
07-26 15:19:47.052  1454  1454 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
07-26 15:19:47.062  2224  6149 D LocationInitializer: Restart initialization of location
,07-26 15:19:47.072  1454  1454 I wpa_supplicant: environment dirty rate=0 [4][0][0],
07-26 15:19:47.072  1010  1282 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 150
07-26 15:19:47.072  1010  1282 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-50 linkspeed=150
07-26 15:19:47.072  1010  1282 E WifiConfigStore: updateConfiguration freq=2447 BSSID=f4:f2:6d:22:99:3e RSSI=-50 "NG700"WPA_PSK
07-26 15:19:47.072  1010  1282 E WifiStateMachine: calculateWifiScore freq=2447 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=6.66 txretriesrate=0.00 rxrate=10.04 userTriggerdPenalty0
07-26 15:19:47.072  1010  1282 E WifiStateMachine:  good link -> stuck count =0
07-26 15:19:47.072  1010  1282 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 60
07-26 15:19:47.072  1010  1282 E WifiStateMachine:  isHighRSSI       ---> score=65
07-26 15:19:47.072  1010  1307 D WifiWatchdogStateMachine: RSSI current: 3 new: -50, 3
,07-26 15:19:47.072  1010  1282 E WifiStateMachine: handleMessage: X
07-26 15:19:47.082  1351  1351 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
,07-26 15:19:47.082  1351  1351 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,07-26 15:19:47.082  1010  1687 D PMS     : acquireWL(117051dd): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 5548 10159 null
,07-26 15:19:47.152  1010  1291 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=5548, uid=10159, userID:0,
,07-26 15:19:47.162  1010  1029 D PMS     : releaseWL(117051dd): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null,
07-26 15:19:47.162  5548  6151 I MusicLeanback: Conditions not met for autocaching. okToAttempt=false
07-26 15:19:47.162  5548  6151 I MusicLeanback: Stop autocaching.
,07-26 15:19:47.162  5252  6157 W FileUtils: Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,07-26 15:19:47.172  5252  6157 W ServiceConnection: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/service.connections: open failed: EROFS (Read-only file system),
07-26 15:19:47.172  5252  6157 W ServiceConnection: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-26 15:19:47.172  5252  6157 W ServiceConnection: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-26 15:19:47.172  5252  6157 W ServiceConnection: 	at android.app.ContextImpl.openFileOutput(ContextImpl.java:1114)
07-26 15:19:47.172  5252  6157 W ServiceConnection: 	at android.content.ContextWrapper.openFileOutput(ContextWrapper.java:181)
07-26 15:19:47.172  5252  6157 W ServiceConnection: 	at com.google.android.gms.common.internal.cm.b(SourceFile:80)
07-26 15:19:47.172  5252  6157 W ServiceConnection: 	at com.google.android.gms.common.internal.cm.a(SourceFile:27)
07-26 15:19:47.172  5252  6157 W ServiceConnection: 	at com.google.android.gms.common.internal.cn.run(SourceFile:64)
07-26 15:19:47.172  5252  6157 W ServiceConnection: 	at java.lang.Thread.run(Thread.java:818)
07-26 15:19:47.172  5252  6157 W ServiceConnection: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-26 15:19:47.172  5252  6157 W ServiceConnection: 	at libcore.io.Posix.open(Native Method)
07-26 15:19:47.172  5252  6157 W ServiceConnection: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-26 15:19:47.172  5252  6157 W ServiceConnection: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-26 15:19:47.172  5252  6157 W ServiceConnection: 	... 7 more
,07-26 15:19:47.172  5252  6158 W ServiceConnection: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/service.connections: open failed: EROFS (Read-only file system)
07-26 15:19:47.172  5252  6158 W ServiceConnection: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-26 15:19:47.172  5252  6158 W ServiceConnection: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-26 15:19:47.172  5252  6158 W ServiceConnection: 	at android.app.ContextImpl.openFileOutput(ContextImpl.java:1114)
07-26 15:19:47.172  5252  6158 W ServiceConnection: 	at android.content.ContextWrapper.openFileOutput(ContextWrapper.java:181)
07-26 15:19:47.172  5252  6158 W ServiceConnection: 	at com.google.android.gms.common.internal.cm.b(SourceFile:80)
07-26 15:19:47.172  5252  6158 W ServiceConnection: 	at com.google.android.gms.common.internal.cm.a(SourceFile:27)
07-26 15:19:47.172  5252  6158 W ServiceConnection: 	at com.google.android.gms.common.internal.cn.run(SourceFile:64)
07-26 15:19:47.172  5252  6158 W ServiceConnection: 	at java.lang.Thread.run(Thread.java:818)
07-26 15:19:47.172  5252  6158 W ServiceConnection: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-26 15:19:47.172  5252  6158 W ServiceConnection: 	at libcore.io.Posix.open(Native Method)
07-26 15:19:47.172  5252  6158 W ServiceConnection: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-26 15:19:47.172  5252  6158 W ServiceConnection: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-26 15:19:47.172  5252  6158 W ServiceConnection: 	... 7 more
07-26 15:19:47.172  5252  6158 W FileUtils: Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,07-26 15:19:47.172  5548  5548 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,07-26 15:19:47.172  5548  6156 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,07-26 15:19:47.262  1995  1995 I art     : Explicit concurrent mark sweep GC freed 15869(913KB) AllocSpace objects, 6(504KB) LOS objects, 48% free, 4MB/8MB, paused 1.100ms total 61.360ms,
,07-26 15:19:47.282  5891  5891 V SetupWizard: Connected to Gservices successfully,
,07-26 15:19:47.302  2224  2224 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-26 15:19:47.312  2224  2224 I Kids    : [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
,07-26 15:19:47.352  1995  2963 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
07-26 15:19:47.352  1010  1816 I ActivityManager: Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.extremepowersaver.ExtremePowerSaverReceiver: pid=6161 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,07-26 15:19:47.352  1010  1010 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 7
07-26 15:19:47.352  1010  1010 E WifiTrafficPoller:  packet count Tx=211 Rx=380,
07-26 15:19:47.352  1010  1010 E WifiTrafficPoller: notifying of data activity 3
07-26 15:19:47.352  1351  1351 D WIFI_ICON: WifiActivity: 3
07-26 15:19:47.352  1351  1351 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,07-26 15:19:47.502  6161  6161 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:66 android.app.ActivityThread.handleReceiver:2712 
,07-26 15:19:47.532  1010  1627 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.NSReceiver: pid=6183 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,07-26 15:19:47.532  1010  1668 D Process : killProcessQuiet, pid=4949
07-26 15:19:47.532  1010  1668 I ActivityManager: Killing 4949:com.htc.bgp/u0a11 (adj 15): empty #17
,07-26 15:19:47.532  1010  1668 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 

```
