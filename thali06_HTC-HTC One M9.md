#### Test 75789268d2ecd3a_thali06_HTC-HTC One M9 Logs


```
--------- beginning of main
07-08 14:00:58.861  6366  6366 I CmaSystemUpdateService: receiver: Intent { act=com.google.android.gms.update.BOOT_START_SERVICE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.update.SystemUpdateServiceReceiver }
--------- beginning of system
07-08 14:00:58.861  1116  3532 D PMS     : acquireWL(2ee331ae): PARTIAL_WAKE_LOCK  CmaSystemUpdateService 0x1 6366 10020 WorkSource{10020 com.google.android.gms}
07-08 14:00:58.891  6366  6366 D CmaSystemUpdateService: onCreate
07-08 14:00:58.891  6366  6366 D CmaSystemUpdateService: mProcessPackageEnabled: false, mAutomaticUpdateEnabled: false
07-08 14:00:58.891  6366  6366 D CmaSystemUpdateService: onStartCommand: intent: Intent { act=com.google.android.gms.update.START_SERVICE pkg=com.google.android.gms (has extras) }
07-08 14:00:58.921  6366  6366 I CmaSystemUpdateService: connectivity change: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
07-08 14:00:58.921  6366  6366 I CmaSystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
07-08 14:00:58.921  1116  3946 D PMS     : acquireWL(2ee331ae): PARTIAL_WAKE_LOCK  CmaSystemUpdateService 0x1 6366 10020 WorkSource{10020 com.google.android.gms}
07-08 14:00:58.931  3122  3122 D WIFI_ICON: WifiActivity: 0
07-08 14:00:58.931  3122  3122 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 stat_sys_no_sim F]
07-08 14:00:58.931  6366  8614 I SystemUpdateTask: cancelUpdate (empty URL)
07-08 14:00:58.931  6366  8614 I CmaSystemUpdateService: active receiver: disabled
07-08 14:00:58.931  1116  3473 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateServiceActiveReceiver, state=2, flag=1, pid=6366, uid=10020, userID:0
07-08 14:00:58.941  6366  8614 D ChimeraResource: Successfully parsed resource with package name: com.google.android.gms and resource name drawable/notification_system_update_available
07-08 14:00:58.941  6366  8614 D ChimeraResource: Successfully parsed resource with package name: com.google.android.gms and resource name drawable/notification_system_update_download_failure
07-08 14:00:58.961  6366  6366 D CmaSystemUpdateService: onStartCommand: intent: Intent { act=com.google.android.gms.update.START_SERVICE pkg=com.google.android.gms (has extras) },
07-08 14:00:58.961  1116  2987 D PMS     : acquireWL(11c1569d): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 6366 10020 WorkSource{10020 com.google.android.gms}
07-08 14:00:58.961  1116  3324 I ActivityManager: Delay finish: com.google.android.gms/.security.snet.SnetReceiver
07-08 14:00:58.971  6366  8620 I SystemUpdateTask: cancelUpdate (empty URL)
07-08 14:00:58.971  6366  8620 I CmaSystemUpdateService: active receiver: disabled
07-08 14:00:58.971  1116  3588 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateServiceActiveReceiver, state=2, flag=1, pid=6366, uid=10020, userID:0
07-08 14:00:58.981  6366  8620 D ChimeraResource: Successfully parsed resource with package name: com.google.android.gms and resource name drawable/notification_system_update_available
07-08 14:00:58.981  6366  8620 D ChimeraResource: Successfully parsed resource with package name: com.google.android.gms and resource name drawable/notification_system_update_download_failure
07-08 14:00:58.991  1116  5294 D PMS     : releaseWL(2ee331ae): PARTIAL_WAKE_LOCK  CmaSystemUpdateService 0x1 WorkSource{10020 com.google.android.gms}
07-08 14:00:58.991  6366  6366 D CmaSystemUpdateService: onDestroy
07-08 14:00:59.011  1116  1163 I ActivityManager: Waited long enough for: ServiceRecord{fa07605 u0 com.aiqidi.nemo/com.reefs.service.localserver.LocalServerControllerService}
07-08 14:00:59.011  1116  1163 I ActivityManager: Resuming delayed broadcast
07-08 14:00:59.021  3687  4942 I art     : Explicit concurrent mark sweep GC freed 3061(120KB) AllocSpace objects, 0(0B) LOS objects, 67% free, 980KB/2MB, paused 2.077ms total 25.033ms
07-08 14:00:59.031  4336  8624 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
07-08 14:00:59.031  6366  6383 I art     : WaitForGcToComplete blocked for 42.451ms for cause HomogeneousSpaceCompact
07-08 14:00:59.061  1116  3532 D PMS     : acquireWL(1223e712): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4336 10020 WorkSource{10020 com.google.android.gms}
07-08 14:00:59.091  1116  3588 D PMS     : releaseWL(1223e712): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10020 com.google.android.gms}
07-08 14:00:59.111  1116  3475 D PMS     : acquireWL(339d0ee3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4336 10020 WorkSource{10020 com.google.android.gms}
07-08 14:00:59.121  6366  6381 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
07-08 14:00:59.131  8622  8622 W HTCLOG  : use specified tag [AndroidRuntime], func [0].
07-08 14:00:59.131  8622  8622 W HTCLOG  : mask=0x18
07-08 14:00:59.131  1116  1139 D PMS     : releaseWL(11c1569d): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 WorkSource{10020 com.google.android.gms}
07-08 14:00:59.141  1116  4027 D PMS     : releaseWL(339d0ee3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10020 com.google.android.gms}
07-08 14:00:59.171  1116  3574 D PMS     : acquireWL(3afab0e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4336 10020 WorkSource{10020 com.google.android.gms}
07-08 14:00:59.191  1116  3529 D PMS     : releaseWL(3afab0e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10020 com.google.android.gms}
07-08 14:00:59.211  1116  3532 D PMS     : acquireWL(2be1bf99): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4336 10020 WorkSource{10020 com.google.android.gms}
07-08 14:00:59.231  1116  4027 I ActivityManager: Start proc 8626:com.htc.widget.hmsproc1/u0a32 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent
07-08 14:00:59.231  8626  8626 W HTCLOG  : use specified tag [FDManager], func [0].
07-08 14:00:59.231  8626  8626 W HTCLOG  : mask=0x18
07-08 14:00:59.271  1116  3574 D PMS     : releaseWL(2be1bf99): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10020 com.google.android.gms}
07-08 14:00:59.291  1116  1139 D Process : killProcessQuiet, pid=7820
07-08 14:00:59.291  1116  1139 I ActivityManager: Killing 7820:com.htc.updater/u0a68 (adj 15): empty #17
07-08 14:00:59.301  1116  1139 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:238 
07-08 14:00:59.361  1116  3588 I ActivityManager: Recipient 7820
07-08 14:00:59.431  1116  5294 D PMS     : acquireWL(d5625e): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 8523 10102 null
07-08 14:00:59.441  8183  8183 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
07-08 14:00:59.461  8239  8239 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
07-08 14:00:59.461  8239  8239 I SoundPicker: SoundPickerReceiver [onReceive] startService
07-08 14:00:59.461  8239  8657 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
07-08 14:00:59.461  8183  8656 I DFPI.ApkInstallService: onHandleIntent
07-08 14:00:59.461  8183  8656 I DFPI.ApkInstallService: Media Scan Finished Case 
07-08 14:00:59.461  8239  8657 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
07-08 14:00:59.461  8239  8657 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
07-08 14:00:59.461  8239  8657 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-08 14:00:59.461  8239  8657 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/132 type=1
07-08 14:00:59.461  8239  8657 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/132
07-08 14:00:59.461  8239  8657 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-08 14:00:59.461  8239  8657 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/132 type=2
07-08 14:00:59.461  8239  8657 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/132
07-08 14:00:59.461  8239  8657 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-08 14:00:59.461  8239  8657 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/132 type=3
07-08 14:00:59.461  8239  8657 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/132
07-08 14:00:59.461  8239  8657 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-08 14:00:59.461  8239  8657 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/105 type=4
07-08 14:00:59.461  8239  8657 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/105
07-08 14:00:59.471  1116  3588 D PMS     : releaseWL(d5625e): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
07-08 14:00:59.461  8239  8657 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-08 14:00:59.461  8239  8657 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/31 type=5
07-08 14:00:59.461  8239  8657 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/31
07-08 14:00:59.461  8239  8657 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/103 type=6
07-08 14:00:59.461  3526  3988 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
07-08 14:00:59.461  8239  8657 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/103
07-08 14:00:59.461  8239  8657 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/109 type=7
07-08 14:00:59.461  8239  8657 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/109
07-08 14:00:59.461  3526  3988 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@109ce902 +
07-08 14:00:59.461  8239  8657 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=8
07-08 14:00:59.461  8239  8657 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
07-08 14:00:59.461  3526  3988 I Prism.WidgetManager: onLoadItems() +
07-08 14:00:59.461  8239  8657 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/105 type=9
07-08 14:00:59.461  8239  8657 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/105
07-08 14:00:59.481  8183  8656 I DFPI.SystemPropertiesUtil: value = HTC__102
07-08 14:00:59.481  8183  8656 I DFPI.ApkInstallService: deviceCID = HTC__102
07-08 14:00:59.481  8183  8656 D DFPI.ApkInstallService: check CID = HTC__102
07-08 14:00:59.481  8183  8656 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
07-08 14:00:59.491  8183  8183 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
07-08 14:00:59.491  3526  3988 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
07-08 14:00:59.491  8622  8663 W HTCLOG  : use specified tag [cutils-trace], func [0].
07-08 14:00:59.501  8622  8663 W HTCLOG  : mask=0x18
07-08 14:00:59.501  8183  8666 I DFPI.ApkInstallService: onHandleIntent
07-08 14:00:59.501  8183  8666 I DFPI.ApkInstallService: Media Scan Finished Case 
07-08 14:00:59.501  8622  8663 E cutils-trace: Error opening trace file: Permission denied (13)
07-08 14:00:59.501  8183  8666 I DFPI.SystemPropertiesUtil: value = HTC__102
07-08 14:00:59.501  8183  8666 I DFPI.ApkInstallService: deviceCID = HTC__102
07-08 14:00:59.501  8183  8666 D DFPI.ApkInstallService: check CID = HTC__102
07-08 14:00:59.501  8183  8666 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
07-08 14:00:59.511  8239  8239 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
07-08 14:00:59.511  8239  8239 I SoundPicker: SoundPickerReceiver [onReceive] startService
07-08 14:00:59.521  8239  8668 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
07-08 14:00:59.521  8239  8668 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
07-08 14:00:59.521  8239  8668 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
07-08 14:00:59.521  8239  8668 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-08 14:00:59.531  8239  8668 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/132 type=1
07-08 14:00:59.531  8239  8668 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/132
07-08 14:00:59.531  8239  8668 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-08 14:00:59.531  8239  8668 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/132 type=2
07-08 14:00:59.531  8239  8668 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/132
07-08 14:00:59.531  8239  8668 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-08 14:00:59.531  8239  8668 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/132 type=3
07-08 14:00:59.531  8239  8668 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/132
07-08 14:00:59.531  8239  8668 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-08 14:00:59.531  8239  8668 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/105 type=4
07-08 14:00:59.531  8239  8668 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/105
07-08 14:00:59.531  8239  8668 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-08 14:00:59.531  8622  8622 D CustomizationManager: ====startRecUseTime====
07-08 14:00:59.531  8622  8622 D htc.customization.log.level:  is 
07-08 14:00:59.531  8622  8622 W CustomizationLogLevel: Level value is invalid, use default level 2
07-08 14:00:59.531  8239  8668 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/31 type=5
07-08 14:00:59.531  8239  8668 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/31
07-08 14:00:59.531  8239  8668 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/103 type=6
07-08 14:00:59.531  8239  8668 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/103
07-08 14:00:59.531  8239  8668 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/109 type=7
07-08 14:00:59.531  8239  8668 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/109
07-08 14:00:59.531  8239  8668 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=8
07-08 14:00:59.531  8239  8668 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
07-08 14:00:59.531  8239  8668 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/105 type=9
07-08 14:00:59.531  8239  8668 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/105
07-08 14:00:59.541  8183  8183 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
07-08 14:00:59.551  8183  8669 I DFPI.ApkInstallService: onHandleIntent
07-08 14:00:59.551  8183  8669 I DFPI.ApkInstallService: Media Scan Finished Case 
07-08 14:00:59.551  8183  8669 I DFPI.SystemPropertiesUtil: value = HTC__102
07-08 14:00:59.551  8183  8669 I DFPI.ApkInstallService: deviceCID = HTC__102
07-08 14:00:59.551  8183  8669 D DFPI.ApkInstallService: check CID = HTC__102
07-08 14:00:59.551  8183  8669 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
07-08 14:00:59.551  8239  8239 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
07-08 14:00:59.551  8239  8239 I SoundPicker: SoundPickerReceiver [onReceive] startService
07-08 14:00:59.561  8239  8670 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
07-08 14:00:59.561  8239  8670 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
07-08 14:00:59.561  8239  8670 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
07-08 14:00:59.561  8239  8670 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-08 14:00:59.561  8239  8670 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/132 type=1
07-08 14:00:59.561  8239  8670 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/132
07-08 14:00:59.561  8239  8670 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-08 14:00:59.561  8239  8670 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/132 type=2
07-08 14:00:59.561  8239  8670 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/132
07-08 14:00:59.561  8239  8670 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-08 14:00:59.561  8239  8670 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/132 type=3
07-08 14:00:59.561  8239  8670 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/132
07-08 14:00:59.561  8239  8670 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-08 14:00:59.561  8239  8670 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/105 type=4
07-08 14:00:59.561  8239  8670 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/105
07-08 14:00:59.561  8239  8670 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-08 14:00:59.561  8239  8670 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/31 type=5
07-08 14:00:59.561  8239  8670 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/31
07-08 14:00:59.561  8239  8670 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/103 type=6
07-08 14:00:59.561  8239  8670 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/103
07-08 14:00:59.561  8239  8670 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/109 type=7
07-08 14:00:59.561  8239  8670 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/109
07-08 14:00:59.561  8239  8670 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=8
07-08 14:00:59.561  8239  8670 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
07-08 14:00:59.561  8239  8670 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/105 type=9
07-08 14:00:59.561  8239  8670 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/105
07-08 14:00:59.571  1116  1139 I ActivityManager: Start proc 8671:com.htc.calendar/u0a7 for broadcast com.htc.calendar/.ProviderChangeReceiver
07-08 14:00:59.581  8622  8622 D CustomizationManager:  Read ACC file spent 0.025 (s)
07-08 14:00:59.581  8622  8622 D CIDMapFileReader: Parsing tag item name = HTC__001
07-08 14:00:59.581  8622  8622 D CIDMapFileReader: Parsing tag item name = HTC__002
07-08 14:00:59.581  8622  8622 D CIDMapFileReader: Parsing tag item name = HTC__016
07-08 14:00:59.581  8622  8622 D CIDMapFileReader: Parsing tag item name = HTC__031
07-08 14:00:59.581  8622  8622 D CIDMapFileReader: Parsing tag item name = HTC__032
07-08 14:00:59.581  8622  8622 D CIDMapFileReader: Parsing tag item name = HTC__102
07-08 14:00:59.581  8622  8622 D CIDMapFileReader: Parsing tag item name = HTC__A07
07-08 14:00:59.581  8622  8622 D CIDMapFileReader: Parsing tag item name = HTC__J15
07-08 14:00:59.581  8622  8622 D CIDMapFileReader: Parsing tag item name = HTC__M27
07-08 14:00:59.581  8622  8622 D CIDMapFileReader: Parsing tag item name = HTC__Y13
07-08 14:00:59.581  8622  8622 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__102.xml
07-08 14:00:59.581  8622  8622 I CustomizationCIDLoader: Parsing tag category name = application
07-08 14:00:59.581  8622  8622 I CustomizationCIDLoader: Parsing tag category name = system
07-08 14:00:59.581  8622  8622 I CustomizationCIDLoader: Parsing tag category name = Settings
07-08 14:00:59.581  8622  8622 I CustomizationCIDLoader: Parsing tag category name = ACC
07-08 14:00:59.581  8622  8622 I CustomizationCIDLoader: add string-array item, value = 42507
07-08 14:00:59.581  8622  8622 I CustomizationCIDLoader: add string-array item, value = 21902
07-08 14:00:59.581  8671  8671 W HTCLOG  : use specified tag [FDManager], func [0].
07-08 14:00:59.581  8671  8671 W HTCLOG  : mask=0x18
07-08 14:00:59.581  8622  8622 I CustomizationCIDLoader: add string-array item, value = 26006:26001.26002.26003
07-08 14:00:59.581  8622  8622 I CustomizationCIDLoader: add string-array item, value = 23420
07-08 14:00:59.581  8622  8622 I CustomizationCIDLoader: add string-array item, value = 22299
07-08 14:00:59.581  8622  8622 I CustomizationCIDLoader: add string-array item, value = 24002
07-08 14:00:59.581  8622  8622 I CustomizationCIDLoader: add string-array item, value = 23210
07-08 14:00:59.581  8622  8622 I CustomizationCIDLoader: add string-array item, value = 23205
07-08 14:00:59.581  8622  8622 I CustomizationCIDLoader: add string-array item, value = 23806
07-08 14:00:59.581  8622  8622 I CustomizationCIDLoader: add string-array item, value = 23430
07-08 14:00:59.581  8622  8622 I CustomizationCIDLoader: add string-array item, value = 23408
07-08 14:00:59.581  8622  8622 I CustomizationCIDLoader: add string-array item, value = 27205
07-08 14:00:59.581  8622  8622 I CustomizationCIDLoader: add string-array item, value = 27202:27205
07-08 14:00:59.581  8622  8622 I CustomizationCIDLoader: add string-array item, value = 27216:27202.27205
07-08 14:00:59.581  8622  8622 I CustomizationCIDLoader: add string-array item, value = 42507:C:1:0
07-08 14:00:59.581  8622  8622 I CustomizationCIDLoader: add string-array item, value = 21902:C:1:0
07-08 14:00:59.581  8622  8622 I CustomizationCIDLoader: add string-array item, value = 26006:D:1:0
07-08 14:00:59.581  8622  8622 I CustomizationCIDLoader: add string-array item, value = 23420:D:0:0
07-08 14:00:59.581  8622  8622 I CustomizationCIDLoader: add string-array item, value = 27205:C:1:0
07-08 14:00:59.581  8622  8622 I CustomizationCIDLoader: add string-array item, value = 22299:D:0:0
07-08 14:00:59.581  8622  8622 I CustomizationCIDLoader: add string-array item, value = 24002:D:0:0
07-08 14:00:59.581  8622  8622 I CustomizationCIDLoader: add string-array item, value = 23210:D:2:0
07-08 14:00:59.581  8622  8622 I CustomizationCIDLoader: add string-array item, value = 23205:D:2:0
07-08 14:00:59.581  8622  8622 I CustomizationCIDLoader: add string-array item, value = 23806:D:0:0
07-08 14:00:59.581  8622  8622 I CustomizationCIDLoader: add string-array item, value = 23430:C:1:0
07-08 14:00:59.581  8622  8622 I CustomizationCIDLoader: add string-array item, value = 23408:C:1:0
07-08 14:00:59.581  8622  8622 I CustomizationCIDLoader: add string-array item, value = 27202:C:1:0
07-08 14:00:59.581  8622  8622 I CustomizationCIDLoader: add string-array item, value = 27216:C:1:0
07-08 14:00:59.581  8622  8622 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
07-08 14:00:59.581  8622  8622 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
07-08 14:00:59.581  8622  8622 I CustomizationCIDLoader: Parsing tag category name = AudioService
07-08 14:00:59.581  8622  8622 D CustomizationManager:  Read CID file spent 0.054 (s)
07-08 14:00:59.581  8622  8622 D CustomizationManager:  All configurations done spent 0.054 (s)
07-08 14:00:59.591  7721  8660 I MediaStoreImporter: Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
07-08 14:00:59.611  1116  4027 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 8622 on display 0
07-08 14:00:59.611  1116  1185 D PMS     : acquireHCC(cc02e37): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 1116 1000 null
07-08 14:00:59.611  1116  1185 D PMS     : acquireHCC(31729fa4): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 1116 1000 null
07-08 14:00:59.611  8671  8671 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
07-08 14:00:59.621  1116  4027 V WindowManager: addAppToken: AppWindowToken{3d5f76d3 token=Token{1db038c2 ActivityRecord{174a210d u0 com.test.thalitest/.MainActivity t122}}} to stack=1 task=122 at 0
07-08 14:00:59.621  1116  4027 D PMS     : acquireWL(320c1210): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 1116 1000 null
07-08 14:00:59.621  3526  3526 I FeedHostManager: [onPause]
07-08 14:00:59.621  3526  3526 I FeedProviderManager: onPause
07-08 14:00:59.621  3526  3526 I FeedHostManager: [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@e0e6819
07-08 14:00:59.621  3526  4944 I SocialFeedProvider: +onPause
07-08 14:00:59.621  3526  4944 I SocialFeedProvider: -onPause
07-08 14:00:59.621  8622  8622 W HTCLOG  : use specified tag [IPCThreadState], func [0].
07-08 14:00:59.621  8622  8622 W HTCLOG  : mask=0x18
07-08 14:00:59.621  1116  1176 I AnimationUtil: isHTCRecent(ThaliTest/Recents screens.)/3
07-08 14:00:59.621  3526  3526 I ContextualWidget: onPause
07-08 14:00:59.621  3526  3526 I ContextualWidget: notifyWidgetDeactive
07-08 14:00:59.621  8622  8692 W HTCLOG  : use specified tag [Vector], func [0].
07-08 14:00:59.621  8622  8692 W HTCLOG  : mask=0x18
07-08 14:00:59.621  8622  8694 W HTCLOG  : use specified tag [Vector], func [0].
07-08 14:00:59.621  8622  8694 W HTCLOG  : mask=0x18
07-08 14:00:59.621  1116  1176 V WindowManager: Adding window Window{1014ed4b u0 Starting com.test.thalitest} at 2 of 7 (after Window{1b725ec u0 com.htc.launcher/com.htc.launcher.Launcher})
07-08 14:00:59.641  1116  3529 I ActivityManager: Start proc 8695:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
07-08 14:00:59.641  8695  8695 W HTCLOG  : use specified tag [FDManager], func [0].
07-08 14:00:59.641  8695  8695 W HTCLOG  : mask=0x18
07-08 14:00:59.671  3526  3988 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-08 14:00:59.671  1116  1116 D PMS     : releaseWL(28da3473): PARTIAL_WAKE_LOCK  NextAlarmTracker 0x1 null
07-08 14:00:59.691  8671  8671 D CalendarApplication: onCreate
07-08 14:00:59.691  1116  3625 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
07-08 14:00:59.691  8671  8671 D ProviderChangeReceiver: ---------------------------------------------------
07-08 14:00:59.691  8671  8671 D ProviderChangeReceiver: ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
07-08 14:00:59.701  8671  8717 D HtcAlertService: start to updateAlertNotification!
07-08 14:00:59.711  7721  8660 I MediaStoreImporter: Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
07-08 14:00:59.711  3526  3526 I TrimMemoryManager: [trimMemory] 20
07-08 14:00:59.711  1116  1164 D StatusBarManagerService: setSystemUiVisibility(0x8600)
07-08 14:00:59.711  1116  3473 I ActivityManager: Start proc 8718:com.htc.bgp/u0a8 for content provider com.android.providers.calendar/com.htc.providers.calendar.HtcCalendarProvider
07-08 14:00:59.711  1116  1164 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{1014ed4b u0 Starting com.test.thalitest}
07-08 14:00:59.711  1116  1164 D StatusBarManagerService: hiding MENU key
07-08 14:00:59.721  3122  3122 I PhoneStatusBar: setSystemUiNavVisibility(swipe=false hasFocus=false hasPolicy=false shadeState=true)
07-08 14:00:59.721  3122  3122 I PhoneStatusBar: hiding the MENU button mLongPressHomeMenu = false
07-08 14:00:59.721  8718  8718 W HTCLOG  : use specified tag [FDManager], func [0].
07-08 14:00:59.721  8718  8718 W HTCLOG  : mask=0x18
07-08 14:00:59.731  1116  3532 I ActivityManager: Start proc 8735:com.google.android.apps.photos/u0a157 for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal
07-08 14:00:59.741  8735  8735 W HTCLOG  : use specified tag [FDManager], func [0].
07-08 14:00:59.741  8735  8735 W HTCLOG  : mask=0x18
07-08 14:00:59.751  1116  3529 D Process : killProcessQuiet, pid=8266
07-08 14:00:59.751  1116  3529 I ActivityManager: Killing 8266:com.htc.autobot/u0a27 (adj 15): empty #17
07-08 14:00:59.751  1116  3529 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityManagerService.attachApplicationLocked:6484 
07-08 14:00:59.761  8695  8695 I WebViewFactory: Loading com.google.android.webview version 42.0.2311.137 (code 52311137)
07-08 14:00:59.821  1116  3588 I ActivityManager: Recipient 8266
07-08 14:00:59.831  3526  3988 W asset   : Copying FileAsset 0xac5a7a00 (zip:/data/app/com.gameloft.android.gdc-1/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,
,07-08 14:00:59.871  8718  8718 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,07-08 14:00:59.891  8718  8718 W HTCLOG  : use specified tag [SQLiteConnection], func [0].,
07-08 14:00:59.891  1116  2933 V AlarmManager: sending alarm PendingIntent{81d401f: PendingIntentRecord{14f7ef6c com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1467979259901, Int=0,
07-08 14:00:59.891  8718  8718 W HTCLOG  : mask=0x18
07-08 14:00:59.901  3526  3988 I Prism.WidgetManager: onLoadItems() -
07-08 14:00:59.901  3526  3988 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@109ce902 -
07-08 14:00:59.911  8718  8718 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@265380f7(com.htc.providers.calendar.HtcCalendarProvider@38e35b64)
07-08 14:00:59.911  8718  8763 D CalendarProvider2: wait start:true
07-08 14:00:59.921  8718  8763 D CalendarProvider2: wait end:false
,07-08 14:00:59.931  3122  3122 D WIFI_ICON: WifiActivity: 1
07-08 14:00:59.931  3122  3122 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 stat_sys_no_sim F]
,07-08 14:00:59.941  6366  8741 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,07-08 14:00:59.941  8671  8717 D HtcAlertService: No fired or scheduled alerts
,07-08 14:00:59.941  8695  8695 I LibraryLoader: Time to load native libraries: 52 ms (timestamps 9882-9934)
07-08 14:00:59.941  8695  8695 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-08 14:00:59.941  8671  8717 D HtcAlertUtils: -- cancelReminderNotification --
,07-08 14:00:59.941  8671  8717 D HtcAlertUtils: broadcastExistReminder!
07-08 14:00:59.941  3265  3265 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
,07-08 14:00:59.951  8695  8695 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {f3dad91}
,07-08 14:00:59.951  8695  8695 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-08 14:00:59.951  6366  8762 I iu.UploadsManager: End new media; added: 0, uploading: 0, time: 52 ms
,07-08 14:00:59.951  8695  8695 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,07-08 14:00:59.971  5148  8769 I art     : Explicit concurrent mark sweep GC freed 3481(248KB) AllocSpace objects, 0(0B) LOS objects, 72% free, 1514KB/5MB, paused 443us total 17.316ms
,07-08 14:00:59.971  8695  8695 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-08 14:00:59.971  1116  2933 V AlarmManager: sending alarm PendingIntent{d00b17a: PendingIntentRecord{3dbaed2b com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=59968, Int=0
07-08 14:00:59.971  7721  8660 I MediaStoreImporter: Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
07-08 14:00:59.981  8695  8695 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-08 14:00:59.981  8695  8695 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-08 14:00:59.991  3122  3972 I ClockController: schedule update now=1467979260000 next=60000,
,07-08 14:00:59.991  3122  3122 I Clock   : updateClock:14:01 Europe/Brussels
07-08 14:00:59.991  1116  2933 V AlarmManager: sending alarm PendingIntent{3693b21: PendingIntentRecord{20586b46 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=59984, Int=0
,07-08 14:00:59.991  1116  2987 D PMS     : acquireWL(34793107): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.photos/.jobqueue.JobService 0x1 8735 10157 null
07-08 14:00:59.991  3122  3122 I Clock   : updateClock:14:01 Europe/Brussels
07-08 14:00:59.991  3122  3122 I Clock   : updateClock:14:01 Europe/Brussels
,07-08 14:00:59.991  3500  3500 D TelephonyReceiver: bind: true
,07-08 14:01:00.001  3500  3500 D TelephonyReceiver: bind: false
07-08 14:01:00.001  3500  3500 D TelephonyReceiver: switchBindHtcMsgCursor: null,
,07-08 14:01:00.001  8103  8123 D GenericMessagesProvider: query uri: content://htc-messages/wappush/count
,07-08 14:01:00.011  3500  4315 D PhoneApp: EVENT_QUERY_MO_PACKAGES
,07-08 14:01:00.011  1116  3574 D PMS     : acquireWL(157d685d): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 7721 10114 null
,07-08 14:01:00.011  3500  3500 D TelephonyReceiver: switchBindHtcMsgCursor: android.content.ContentResolver$CursorWrapperInner@277b207e
,07-08 14:01:00.011  3500  4315 D PhoneApp: -- N1 =1
07-08 14:01:00.011  3122  4532 D WeatherUtility: Weather sync is On
07-08 14:01:00.011  3122  4532 W WeatherTimeKeeper: [refreshWeatherData] no weather data
07-08 14:01:00.011  3500  4315 D PhoneApp: -- N2 =0
,07-08 14:01:00.011  3500  4315 D PhoneApp: -- N3 =0
,07-08 14:01:00.031  5929  6313 D BluetoothAdapterService(850075163): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1db0d32c
,07-08 14:01:00.031  8695  8695 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,07-08 14:01:00.031  8695  8695 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50364 len=3345
07-08 14:01:00.041  8695  8695 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:9397000 len:1161174
,07-08 14:01:00.041  8695  8695 W HTCLOG  : use specified tag [libEGL], func [3].,
07-08 14:01:00.041  8695  8695 W HTCLOG  : mask=0x18
,07-08 14:01:00.041  8695  8695 W HTCLOG  : use specified tag [libEGL], func [3].
,07-08 14:01:00.041  8695  8695 W HTCLOG  : mask=0x18
07-08 14:01:00.041  8695  8695 I Adreno  : QUALCOMM build                   : 065751b, 
07-08 14:01:00.041  8695  8695 I Adreno  : Build Date                       : 04/15/15
07-08 14:01:00.041  8695  8695 I Adreno  : OpenGL ES Shader Compiler Version: E031.25.03.07
07-08 14:01:00.041  8695  8695 I Adreno  : Local Branch                     : 
07-08 14:01:00.041  8695  8695 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.1_rb2.9
07-08 14:01:00.041  8695  8695 I Adreno  : Remote Branch                    : NONE
07-08 14:01:00.041  8695  8695 I Adreno  : Reconstruct Branch               : AU_LINUX_ANDROID_LA.BF64.1.2.1_RB2.05.01.00.081.016 + 065751b +  NOTHING
07-08 14:01:00.041  1116  5294 D PMS     : releaseWL(34793107): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.photos/.jobqueue.JobService 0x1 null
,07-08 14:01:00.051  4336  4336 D WearableService: callingUid 10020, callindPid: 4336
,07-08 14:01:00.061  3662  8783 I WSP     : [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
,07-08 14:01:00.061  3662  8783 D WeatherUtility: Weather sync is On
,07-08 14:01:00.061  1116  3543 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=7721, uid=10114, userID:0
07-08 14:01:00.061  3662  8783 I WSP     : [Receiver] next auto-sync alarm event is 60 mins later, at time: Fri Jul 08 15:01:00 GMT+02:00 2016
,07-08 14:01:00.071  7721  7721 W GoogleHttpClient: Failed to load SSLCertificateSocketFactory from package
07-08 14:01:00.071  7721  7721 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
07-08 14:01:00.071  7552  7552 D CDMountReceiver: whether to enable CD Auto-mount: true
,07-08 14:01:00.071  7552  7552 D CDMountReceiver: showNotification() contentText=If HTC Sync Manager setup doesn't start automatically on your computer, download it from www.htc.com/hsm
07-08 14:01:00.071  7721  7721 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
07-08 14:01:00.071  1116  3532 D PMS     : releaseWL(157d685d): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
07-08 14:01:00.071  1116  4465 I art     : Explicit concurrent mark sweep GC freed 30465(1637KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 16MB/25MB, paused 1.120ms total 109.241ms
,07-08 14:01:00.071  7721  8776 I MusicLeanback: Conditions not met for autocaching.
07-08 14:01:00.071  7721  8776 I MusicLeanback: Stop autocaching.
,07-08 14:01:00.081  3059  3059 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
,07-08 14:01:00.081  1116  1116 D ValidateNoPeople: setContact(com.nero.android.htc.sync,0.0,false),
,07-08 14:01:00.081  3526  3988 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
07-08 14:01:00.081  3526  3988 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,07-08 14:01:00.091  3526  3526 W Prism.AllAppsManager: AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS> P=UserHandle{0})
,07-08 14:01:00.101  3265  3287 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true, isForDotMatrix: false
07-08 14:01:00.101  3526  3526 I Launcher: Deferring update until onResume
07-08 14:01:00.101  3526  3526 D Launcher: waitUntilResume // bindAppsUpdated
07-08 14:01:00.111  3662  8793 D WSP     : save sync status: 1467976956287,1467979260110
07-08 14:01:00.111  1116  1139 D PMS     : acquireWL(10970c00): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 3662 10042 null
07-08 14:01:00.111  3122  3122 I RemoteViews: apply:com.nero.android.htc.sync 0 6 4 38
07-08 14:01:00.121  3122  3122 I RemoteViews: apply:com.nero.android.htc.sync 0 6 1 53,
,07-08 14:01:00.131  7721  7721 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
07-08 14:01:00.131  3122  3122 I NotificationStackScrollLayout: setBlockTouchEnabled:false,
,07-08 14:01:00.131  7721  8799 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,07-08 14:01:00.141  3662  8794 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x6170692e616363),sn(),hints(known),family 0,flags 4
07-08 14:01:00.141  3662  8794 D libc    : [NET] android_getaddrinfofornet-, err=8
07-08 14:01:00.141  3662  8794 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x6170692e616363),sn(),hints(known),family 0,flags 1024
07-08 14:01:00.141  3662  8794 D libc    : [NET] android_getaddrinfofornet-, pass to proxy,
07-08 14:01:00.141  3662  8794 D libc    : [NET] android_getaddrinfo_proxy+
07-08 14:01:00.141  3662  8794 D libc    : [NET] android_getaddrinfo_proxy get netid:0
,07-08 14:01:00.141   518  8804 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x6170692e616363),sn(),hints(known),family 0,flags 1024
07-08 14:01:00.141   518  8804 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
,07-08 14:01:00.141  8695  8790 W chromium: [WARNING:data_reduction_proxy_config.cc(150)] SPDY proxy OFF at startup
,07-08 14:01:00.161  7552  7552 D CDMountReceiver: enable CD Auto-mount: true
,07-08 14:01:00.161  8695  8695 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-08 14:01:00.171  7552  8806 D HTCUtilities: enable auto-mount
,07-08 14:01:00.171  7552  8806 I HtcMountManagerAdapter: mHtcMountManager is  null
,07-08 14:01:00.171  7552  8806 I HtcMountManagerAdapter: mStorageManager is  not null
07-08 14:01:00.171  1116  3532 D VoldConnector: SND -> {7 mountISO mount /system/etc/PCTOOL.ISO /sys/class/android_usb/f_mass_storage/lun0/file}
,07-08 14:01:00.171  1116  2971 D VoldConnector: RCV <- {200 7 mountISO operation succeeded}
07-08 14:01:00.171  1116  3532 D MountService: mountISO: /system/etc/PCTOOL.ISO
07-08 14:01:00.171  3526  5407 I SocialFeedProvider: +disConnect socialManager
07-08 14:01:00.171  3526  5407 I SocialFeedProvider: disconnect socialManager
07-08 14:01:00.171  3526  5407 I SocialFeedProvider: -disConnect socialManager
,07-08 14:01:00.181  8695  8695 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-08 14:01:00.191   518  8804 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
07-08 14:01:00.191   518  8804 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
07-08 14:01:00.191  3662  8794 D libc    : [NET] android_getaddrinfo_proxy-, success
,07-08 14:01:00.191  8695  8695 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC
,07-08 14:01:00.201  1116  2987 I ActivityManager: Start proc 8808:com.google.android.partnersetup/u0a23 for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver
,07-08 14:01:00.201  8695  8695 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-08 14:01:00.201  8695  8695 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-08 14:01:00.211  8808  8808 W HTCLOG  : use specified tag [FDManager], func [0].
07-08 14:01:00.211  8808  8808 W HTCLOG  : mask=0x18
,07-08 14:01:00.221  3662  8794 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x6170692e616363),sn(),hints(known),family 0,flags 4
,07-08 14:01:00.221  3662  8794 D libc    : [NET] android_getaddrinfofornet-, err=8
,07-08 14:01:00.251  3767  3767 E PackageActionReceiver: ACTION_PACKAGE_ADDED,
07-08 14:01:00.251  8695  8834 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
07-08 14:01:00.251  8695  8834 W HTCLOG  : mask=0x18
,07-08 14:01:00.251  1116  4027 V WindowManager: Adding window Window{23f42fd7 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{1014ed4b u0 Starting com.test.thalitest})
,07-08 14:01:00.261  1116  3543 D Process : killProcessQuiet, pid=8352
07-08 14:01:00.261  1116  3543 I ActivityManager: Killing 8352:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
07-08 14:01:00.261  1116  3543 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityManagerService.removeContentProvider:10118 ,
,07-08 14:01:00.321  3662  8794 D WSP     : response code: 200
,07-08 14:01:00.321  1116  2987 I ActivityManager: Recipient 8352
,07-08 14:01:00.351  3662  8794 D WSP JsonParser: sync status: pass sync h&d, 13,14
,07-08 14:01:00.371  5061  5061 I [MirrorLinkServer]PackageInstalledReceiver: PackageInstalledReceiver Received::Intent { act=android.intent.action.PACKAGE_ADDED dat=package: flg=0x4000010 cmp=com.htc.mirrorlinkserver/.PackageInstalledReceiver (has extras) }
,07-08 14:01:00.371  5061  5061 D [MirrorLinkServer]PackageInstalledReceiver: Counter : 1
07-08 14:01:00.371  5061  5061 D [MirrorLinkServer]MirrorLinkConnectionReceiver: notifyMlSevrer
,07-08 14:01:00.371  5061  5061 I [MirrorLinkServer]MirrorLinkServer: onStartCommand() Action : android.intent.action.PACKAGE_ADDED
07-08 14:01:00.371  5061  5061 D [MirrorLinkServer]MirrorLinkServer: New Application installed : com.test.thalitest
07-08 14:01:00.371  5061  5061 D [MirrorLinkServer]d: onApplicationInstalled
07-08 14:01:00.371  5061  5061 W [MirrorLinkServer]d: Cannot find find the  com.mirrorlink.android.app.LAUNCH intent.
07-08 14:01:00.371  5061  5061 I [MirrorLinkServer]d: com.test.thalitest is not a MirrorLink-aware app.
,07-08 14:01:00.371  3662  8837 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.test.thalitest
07-08 14:01:00.371  3662  8837 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed
07-08 14:01:00.371  3526  3526 D Prism.PackageStateRece_: action: android.intent.action.PACKAGE_ADDED
07-08 14:01:00.371  5061  8838 I [MirrorLinkServer]d: Database Update Progress State : false
07-08 14:01:00.371  5061  8838 I [MirrorLinkServer]c: onApplicationUpdationCompleted, sending broadcast
,07-08 14:01:00.371  3526  3526 I ContextualWidget: package com.test.thalitest added
,07-08 14:01:00.381  5061  5061 I [MirrorLinkServer]MirrorLinkServer: Broadcast Received::Intent { act=com.htc.HTCMirrorLinkServer.PACKAGE_UPDATE_COMPLETED }
07-08 14:01:00.381  5061  5061 D [MirrorLinkServer]MirrorLinkServer: ML_PACKAGE_UPDATE_COMPLETED intent received
07-08 14:01:00.381  5061  5061 D [MirrorLinkServer]MirrorLinkServer: Counter : 0
07-08 14:01:00.381  5061  5061 I [MirrorLinkServer]MirrorLinkConnectionReceiver: checkAndStopMLSession
07-08 14:01:00.381  5061  5061 I [MirrorLinkServer]MirrorLinkConnectionReceiver: Stopping Service
,07-08 14:01:00.381  3526  4160 I ContextualWidget: handleMessage, what=1003 mode=GettingOut maxcount=8
,07-08 14:01:00.391   518  8351 D libc    : [NET]Querying server xid =a4f9 (# 1) address = 192.168.1.1 (try=1,nscount=1,v_circuit=0),
07-08 14:01:00.391   518  8351 D libc    : before statp->options=0x800002C3)
,07-08 14:01:00.391  6637  8840 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE,
,07-08 14:01:00.391  8695  8695 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
07-08 14:01:00.391  8695  8695 W HTCLOG  : use specified tag [ThreadedRenderer], func [0].
07-08 14:01:00.391  8695  8695 W HTCLOG  : mask=0x18
07-08 14:01:00.391  8695  8695 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
07-08 14:01:00.391  8695  8695 W HTCLOG  : mask=0x18
07-08 14:01:00.401  8695  8834 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
07-08 14:01:00.401  8695  8834 W HTCLOG  : mask=0x18
07-08 14:01:00.401  8695  8834 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
07-08 14:01:00.401  8695  8834 W HTCLOG  : mask=0x18
07-08 14:01:00.401  8695  8834 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
07-08 14:01:00.401  8695  8834 W HTCLOG  : mask=0x18
,07-08 14:01:00.401  8695  8834 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
07-08 14:01:00.401  8695  8834 W HTCLOG  : mask=0x18
,07-08 14:01:00.401  1116  3532 I ActivityManager: Start proc 8841:com.htc.cs.dm/u0a88 for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver
07-08 14:01:00.401  6637  8840 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
07-08 14:01:00.401  6637  8840 W HTCLOG  : mask=0x18
,07-08 14:01:00.411  8695  8834 W HTCLOG  : use specified tag [Surface], func [3].
07-08 14:01:00.411  8695  8834 W HTCLOG  : mask=0x18
,07-08 14:01:00.411  8695  8834 W HTCLOG  : use specified tag [GraphicBufferMapper], func [3].
07-08 14:01:00.411  8695  8834 W HTCLOG  : mask=0x18
07-08 14:01:00.411  8695  8834 W HTCLOG  : use specified tag [qdmemalloc], func [0].
07-08 14:01:00.411  8695  8834 W HTCLOG  : mask=0x18
,07-08 14:01:00.411  8841  8841 W HTCLOG  : use specified tag [FDManager], func [0].
,07-08 14:01:00.411  8841  8841 W HTCLOG  : mask=0x18
,07-08 14:01:00.411   518  8351 D libc    : after statp->options=0x800002C1)
07-08 14:01:00.421   518  8351 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
07-08 14:01:00.421   518  8351 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
07-08 14:01:00.421  5505  8348 D libc    : [NET] android_getaddrinfo_proxy-, success
,07-08 14:01:00.451  8841  8841 I DeviceManagement: DMApplication: !!! Hello, this is: [com.htc.cs.dm;3.0.404391;250011189] pid=8841 dbg=false s=true
,07-08 14:01:00.461  8841  8841 I DeviceManagement: PackageUpdateReceiver: vvv Package added: [com.test.thalitest]
,07-08 14:01:00.471  8695  8695 I InputMethodManager: [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@88d357e, mServedView=org.apache.cordova.engine.SystemWebView{7e05adf VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@1db0d32c
07-08 14:01:00.471  1116  3324 I InputMethodManagerService: Disable input method client, pid=3526
07-08 14:01:00.471  1116  3324 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
07-08 14:01:00.471  3122  3122 I PhoneStatusBar: setImeWindowStatus(false,false)
07-08 14:01:00.471  1116  3324 I InputMethodManagerService: Enable input method client, pid=8695
,07-08 14:01:00.481  1116  3529 I ActivityManager: Start proc 8865:com.google.android.apps.docs/u0a90 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
07-08 14:01:00.481  1116  3529 I ActivityManager: Killing 8373:com.htc.mobiledata:remote/u0a39 (adj 15): empty #17
07-08 14:01:00.481  1116  3529 D Process : killProcessQuiet, pid=8373
07-08 14:01:00.481  1116  3529 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityManagerService.trimApplications:19731 
07-08 14:01:00.481  8865  8865 W HTCLOG  : use specified tag [FDManager], func [0].
07-08 14:01:00.481  8865  8865 W HTCLOG  : mask=0x18
,07-08 14:01:00.501  3526  4160 I ContextualWidget: MFU.onDownloadDataSetChanged
,07-08 14:01:00.501  3526  4160 I ContextualWidget: handleMessage, what=1019 mode=GettingOut maxcount=8
,07-08 14:01:00.511  3526  3526 I ContextualWidget: notifyDataChanged, pos=6 item=FolderInfo: Recent downloads, app folderId 49957ce6-0237-4197-b414-874a9f8960eb, (Item(id=-1 type=6 container=-200 screen=-1 cellX=-1 cellY=-1 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0}))
,07-08 14:01:00.511  3526  3526 I HtcContextualWidgetDataManager: onDataChanged: GettingOut, position: 6, item:[FolderInfo: Recent downloads, app folderId 49957ce6-0237-4197-b414-874a9f8960eb, (Item(id=-1 type=6 container=-200 screen=-1 cellX=-1 cellY=-1 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0}))]
,07-08 14:01:00.521  8695  8695 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 8695
,07-08 14:01:00.551  5505  8348 D libc    : [NET] android_getaddrinfofornet+,hn 17(0x73646b2e686f63),sn(),hints(known),family 0,flags 4
,07-08 14:01:00.551  5505  8348 D libc    : [NET] android_getaddrinfofornet-, err=8
,07-08 14:01:00.611  8695  8695 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-08 14:01:00.611  1116  3532 I ActivityManager: Recipient 8373
,07-08 14:01:00.691  1116  3529 D PMS     : releaseWL(320c1210): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null,
,07-08 14:01:00.691  1116  1185 D PMS     : releaseHCC(cc02e37): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,07-08 14:01:00.691  1116  1185 D PMS     : releaseHCC(31729fa4): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,07-08 14:01:00.721  1116  2933 I ActivityManager: Start proc 8892:com.htc.sense.news/u0a59 for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper
07-08 14:01:00.721  1116  2933 V AlarmManager: sending alarm PendingIntent{adf42cf: PendingIntentRecord{2284b45c com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1467979260638, Int=0
07-08 14:01:00.731  3265  3409 D DotMatrix: [EventService] EVENT_WEATHER_INFO_UPDATE
,07-08 14:01:00.731  3122  4532 D WeatherUtility: Weather sync is On
07-08 14:01:00.731  1116  1176 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s106ms
07-08 14:01:00.731  3122  4532 W WeatherTimeKeeper: [refreshWeatherData] no weather data
07-08 14:01:00.741  1116  2987 D PMS     : acquireWL(30c132f4): PARTIAL_WAKE_LOCK  Icing 0x1 6366 10020 WorkSource{10069 com.google.android.googlequicksearchbox},
,07-08 14:01:00.741  8892  8892 W HTCLOG  : use specified tag [FDManager], func [0].
,07-08 14:01:00.741  8892  8892 W HTCLOG  : mask=0x18
,07-08 14:01:00.751  3662  8794 D CityCodeHelper: code_mapping get key: 328328
,07-08 14:01:00.771  3662  8794 D WSP     : response code: 200
,07-08 14:01:00.781  3662  8794 D WSP JsonParser: sync status: pass sync h&d, 13,14
,07-08 14:01:00.791  8695  8864 D jxcore_app_log: JniHelper::setJavaVM(0xab30bb70), pthread_self() = -1406484400,
,07-08 14:01:00.801  8695  8864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-08 14:01:00.801  8695  8864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-08 14:01:00.801  8695  8864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-08 14:01:00.801  8695  8864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-08 14:01:00.801  8695  8864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-08 14:01:00.801  8695  8864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@224b94a9 added. We now have 1 listener(s)
,07-08 14:01:00.801  8892  8892 I MultiDex: VM with version 2.1.0 has multidex support
07-08 14:01:00.801  8892  8892 I MultiDex: install
07-08 14:01:00.801  8892  8892 I MultiDex: VM has multidex support, MultiDex support library is disabled.
07-08 14:01:00.811  1116  3529 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,07-08 14:01:00.811  8695  8864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 90:E7:C4:3C:62:6A
07-08 14:01:00.811  8695  8864 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "90:E7:C4:3C:62:6A"
07-08 14:01:00.811  8695  8864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-08 14:01:00.811  8695  8864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-08 14:01:00.821  8695  8864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-08 14:01:00.821  8695  8864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-08 14:01:00.821  8695  8864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-08 14:01:00.821  8695  8864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 90:E7:C4:3C:62:6A
07-08 14:01:00.821  8695  8864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-08 14:01:00.821  8695  8864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-08 14:01:00.821  8695  8864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-08 14:01:00.821  8695  8864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-08 14:01:00.821  8695  8864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-08 14:01:00.821  8695  8864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-08 14:01:00.821  8695  8864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-08 14:01:00.821  8695  8864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e255f5c added. We now have 1 listener(s)
07-08 14:01:00.821  8695  8864 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
07-08 14:01:00.821  6637  8840 I ApplicationLogger: canRun() : Opted Out
,07-08 14:01:00.821  6637  8840 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 426 ms] updated apps [took 426 ms] 
,07-08 14:01:00.831  1116  2978 D WifiService: New client listening to asynchronous messages
,07-08 14:01:00.831  5929  5952 D BluetoothAdapterService(850075163): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1db0d32c,
07-08 14:01:00.831  8695  8864 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage,
,07-08 14:01:00.831  8695  8864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-08 14:01:00.831  8695  8864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-08 14:01:00.831  8695  8864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-08 14:01:00.831  8695  8864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-08 14:01:00.841  8695  8864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-08 14:01:00.841  1116  3946 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,07-08 14:01:00.841  8695  8864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 90:E7:C4:3C:62:6A
,07-08 14:01:00.841  8865  8865 D DocsApplication: Plugin installer initialized.
07-08 14:01:00.841  5929  5952 D BluetoothAdapterService(850075163): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1db0d32c
07-08 14:01:00.851  8892  8918 I SocialManager[SocialBiLogHelper]: action: com.htc.sense.hsp.HANDLE_ULOG
07-08 14:01:00.851  8892  8918 I SocialManager[SocialBiLogHelper]: last commit ulog time 1467953588795
07-08 14:01:00.851  8892  8918 I SocialManager[SocialBiLogHelper]: skip commit this time
,07-08 14:01:00.851  8695  8864 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-08 14:01:00.851  8695  8864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:01:00.851  8695  8864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:01:00.851  8695  8864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:01:00.851  8695  8864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:01:00.851  8695  8864 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-08 14:01:00.851  8695  8864 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-08 14:01:00.851  8695  8864 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-08 14:01:00.851  8695  8864 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-08 14:01:00.851  8695  8864 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-08 14:01:00.851  8695  8864 I io.jxcore.node.LifeCycleMonitor: start: OK
07-08 14:01:00.851  1116  3529 I ActivityManager: Killing 8419:com.htc.mobiledata/u0a39 (adj 15): empty #17
07-08 14:01:00.851  1116  3529 D Process : killProcessQuiet, pid=8419
07-08 14:01:00.851  1116  3529 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19304 
07-08 14:01:00.851  8695  8695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-08 14:01:00.851  8695  8695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-08 14:01:00.861  1116  1138 I ActivityManager: Recipient 8419
,07-08 14:01:00.871  3122  3238 D WeatherUtility: Weather sync is On
,07-08 14:01:00.871  8865  8865 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{3f27d515 com.google.android.apps.docs}
,07-08 14:01:00.891  8695  8695 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,07-08 14:01:00.891  8865  8865 D TAG     : onCreate()
,07-08 14:01:00.911  8865  8865 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer,
,07-08 14:01:00.931  8718  8718 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: },
,07-08 14:01:00.931  8718  8718 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,07-08 14:01:00.961  3122  3122 D WIFI_ICON: WifiActivity: 3
,07-08 14:01:00.961  3122  3122 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 stat_sys_no_sim F]
,07-08 14:01:00.971  3662  8794 D CityCodeHelper: code_mapping get key: 349727
,07-08 14:01:00.981  8399  8484 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
07-08 14:01:00.981  1116  3473 D Process : killProcessQuiet, pid=8453,
07-08 14:01:00.981  1116  3473 I ActivityManager: Killing 8453:com.google.android.gm.exchange/u0a156 (adj 15): empty #17,
,07-08 14:01:00.981  1116  3473 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19304 
07-08 14:01:00.991  3662  8794 D WSP     : response code: 200
,07-08 14:01:01.021  3662  8794 D WSP JsonParser: sync status: pass sync h&d, 13,14,
07-08 14:01:01.031  3265  3409 D WeatherUtility: Weather sync is On
,07-08 14:01:01.061  1116  5294 I ActivityManager: Recipient 8453,
07-08 14:01:01.061   552   552 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-08 14:01:01.101  3662  8794 D CityCodeHelper: code_mapping get key: 274663,
,07-08 14:01:01.121  3265  3409 D DotMatrix: [EventService] Next weather trigger time:1467982860366,
,07-08 14:01:01.121  3662  8794 D WSP     : response code: 200,
,07-08 14:01:01.131  3662  8794 D WSP JsonParser: sync status: pass sync h&d, 13,14,
,07-08 14:01:01.181  3662  8794 D CityCodeHelper: code_mapping get key: 213490,
,07-08 14:01:01.211  3662  8794 D WSP     : response code: 200
,07-08 14:01:01.221  3662  8794 D WSP JsonParser: sync status: pass sync h&d, 13,14
,07-08 14:01:01.261  3662  8794 D CityCodeHelper: code_mapping get key: 307297
,07-08 14:01:01.301  3662  8794 D WSP     : response code: 200
,07-08 14:01:01.321  3662  8794 D WSP JsonParser: sync status: pass sync h&d, 13,14
,07-08 14:01:01.351  3662  8794 D CityCodeHelper: code_mapping get key: 623
,07-08 14:01:01.361  3662  8794 D WSP     : response code: 200,
,07-08 14:01:01.371  3662  8794 D WSP JsonParser: sync status: pass sync h&d, 13,14,
,07-08 14:01:01.491  8695  8920 W jxcore-log: Initializing JXcore engine
07-08 14:01:01.491  8695  8920 W jxcore-log: JXcore engine is ready
,07-08 14:01:01.551  8695  8920 W jxcore-log: Starting JXcore engine,
,07-08 14:01:01.581  3526  3988 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
07-08 14:01:01.581  3526  3988 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@109ce902 +
07-08 14:01:01.581  3526  3988 I Prism.WidgetManager: onLoadItems() +
,07-08 14:01:01.631  8695  8920 W jxcore-log: Platform android,
07-08 14:01:01.631  8695  8920 W jxcore-log: 
07-08 14:01:01.631  8695  8920 W jxcore-log: Process ARCH arm
07-08 14:01:01.631  8695  8920 W jxcore-log: 
,07-08 14:01:01.791  8695  8920 I jxcore-log: JXcore Cordova bridge is ready!
07-08 14:01:01.791  8695  8920 I jxcore-log: 
,07-08 14:01:01.791  8695  8920 W jxcore-log: JXcore engine is started
,07-08 14:01:01.801  8695  8864 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-08 14:01:01.801  8695  8695 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41),
,07-08 14:01:01.811  8695  8920 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
07-08 14:01:01.811  8695  8920 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,07-08 14:01:01.831  8695  8695 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
07-08 14:01:01.831  8695  8695 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62),
,07-08 14:01:01.841  6366  6680 I Icing   : Indexing CF3FE6BD92DAECCC594E8F8BDE8C89D040E637CF from com.google.android.googlequicksearchbox,
,07-08 14:01:01.861  8695  8695 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
07-08 14:01:01.861  1116  5294 D PMS     : acquireWL(238536db): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 1116 1000 null
07-08 14:01:01.861  8695  8695 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
07-08 14:01:01.861  8695  8864 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 37ms. Plugin should use CordovaInterface.getThreadPool().
,07-08 14:01:01.871  1116  3625 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
07-08 14:01:01.881  3526  3526 I FeedHostManager: [onResume]
07-08 14:01:01.881  3526  3526 I FeedProviderManager: onResume
07-08 14:01:01.881  3526  4944 I SocialFeedProvider: +onResume
07-08 14:01:01.881  3526  4944 I SocialFeedProvider: updateAccounts - Accounts is no change
07-08 14:01:01.881  3526  4944 I SocialFeedProvider: -onResume
07-08 14:01:01.891  3526  3526 I ContextualWidget: onResume
07-08 14:01:01.891  3526  3526 I ContextualWidget: notifyWidgetActive location size=0 user consent location=false
07-08 14:01:01.891  3526  3526 I ContextualWidget: ignore uploadUsageData location=false usage data=false allowAutoUpload=true,
07-08 14:01:01.891  3526  3526 I ContextualWidget: postSyncRecommendedApps, isReady=true allowAutoSync=true syncMode=1 isEnableRecommend=true
07-08 14:01:01.891  3526  4160 I ContextualWidget: handleMessage, what=1018 mode=GettingOut maxcount=8
07-08 14:01:01.891  3526  4160 I ContextualWidget: handleMessage, what=1017 mode=GettingOut maxcount=8
07-08 14:01:01.891  1116  3946 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-08 14:01:01.891  1116  5294 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
07-08 14:01:01.891  1116  3529 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,07-08 14:01:01.891  1116  2987 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,07-08 14:01:01.891  1116  1164 D StatusBarManagerService: setSystemUiVisibility(0x8700)
07-08 14:01:01.891  3122  3122 I PhoneStatusBar: setSystemUiNavVisibility(swipe=false hasFocus=false hasPolicy=false shadeState=true)
,07-08 14:01:01.891  1116  1164 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{1b725ec u0 com.htc.launcher/com.htc.launcher.Launcher}
07-08 14:01:01.891  3122  3122 I PhoneStatusBar: hiding the MENU button mLongPressHomeMenu = false
07-08 14:01:01.891  1116  1164 D StatusBarManagerService: hiding MENU key
,07-08 14:01:01.901  3526  3526 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,07-08 14:01:01.901  3526  3526 I ThreadedRenderer: Defer allocateBuffers to drawing time,
,07-08 14:01:01.901  1116  4027 I InputMethodManagerService: Disable input method client, pid=8695
07-08 14:01:01.901  1116  4027 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
07-08 14:01:01.911  1116  4027 I InputMethodManagerService: Enable input method client, pid=3526
07-08 14:01:01.911  3122  3122 I PhoneStatusBar: setImeWindowStatus(false,false)
,07-08 14:01:01.911  8695  8695 W IInputConnectionWrapper: reportFullscreenMode on inactive InputConnection
,07-08 14:01:01.931  6366  6680 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,07-08 14:01:01.941  1116  1163 I ActivityManager: Waited long enough for: ServiceRecord{1368cf96 u0 com.htc.club/com.mcrm.autonotification.NotificationService},
,07-08 14:01:01.941  1116  3529 D PMS     : releaseWL(238536db): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,07-08 14:01:01.951  1116  1164 D StatusBarManagerService: setSystemUiVisibility(0xc0000700)
07-08 14:01:01.951  1116  1164 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{1b725ec u0 com.htc.launcher/com.htc.launcher.Launcher}
07-08 14:01:01.951  1116  1164 D StatusBarManagerService: hiding MENU key
,07-08 14:01:01.961  3122  3122 I PhoneStatusBar: setSystemUiNavVisibility(swipe=false hasFocus=false hasPolicy=false shadeState=true)
,07-08 14:01:01.971  1116  1163 I ActivityManager: Killing 7352:com.android.defcontainer/u0a11 (adj 15): empty #17
,07-08 14:01:01.971  1116  1163 D Process : killProcessQuiet, pid=7352
07-08 14:01:01.971  1116  1163 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityStack.destroyActivityLocked:3407 ,
,07-08 14:01:01.981  8865  8932 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
07-08 14:01:01.981  8865  8932 W HTCLOG  : mask=0x18
,07-08 14:01:01.991  3526  8925 D HtcTelephonyManager: wrong phone slot in non-dual projects,
07-08 14:01:01.991  3122  3122 I PhoneStatusBar: hiding the MENU button mLongPressHomeMenu = false
,07-08 14:01:02.021  8926  8926 W HTCLOG  : use specified tag [AndroidRuntime], func [0].,
,07-08 14:01:02.021  8926  8926 W HTCLOG  : mask=0x18,
07-08 14:01:02.021  3526  3988 E Prism.WidgetManager: The same lists. No need to update. skip it.
07-08 14:01:02.021  3526  3988 I Prism.WidgetManager: onLoadItems() -
07-08 14:01:02.021  3526  3988 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@109ce902 -
,07-08 14:01:02.051  1116  1139 I ActivityManager: Recipient 7352,
,07-08 14:01:02.051  3526  8925 D HtcTelephonyManager: wrong phone slot in non-dual projects
,07-08 14:01:02.071  3526  8925 D libc    : [NET] android_getaddrinfofornet+,hn 28(0x7265636f6d6d65),sn(),hints(known),family 0,flags 4
,07-08 14:01:02.071  3526  8925 D libc    : [NET] android_getaddrinfofornet-, err=8
07-08 14:01:02.071  3526  8925 D libc    : [NET] android_getaddrinfofornet+,hn 28(0x7265636f6d6d65),sn(),hints(known),family 0,flags 1024
07-08 14:01:02.071  3526  8925 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
07-08 14:01:02.071  3526  8925 D libc    : [NET] android_getaddrinfo_proxy+
07-08 14:01:02.071  3526  8925 D libc    : [NET] android_getaddrinfo_proxy get netid:0
07-08 14:01:02.071   518  8935 D libc    : [NET] android_getaddrinfofornet+,hn 28(0x7265636f6d6d65),sn(),hints(known),family 0,flags 1024
07-08 14:01:02.071   518  8935 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
,07-08 14:01:02.081  8695  8695 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-08 14:01:02.081  8695  8695 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
07-08 14:01:02.081  8695  8695 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-08 14:01:02.081  8695  8695 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
07-08 14:01:02.081  8695  8695 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:01:02.081  8695  8695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:01:02.081  8695  8695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:01:02.081  8695  8695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-08 14:01:02.081  8695  8695 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@224b94a9 removed from the list
07-08 14:01:02.081  8695  8695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:01:02.081  8695  8695 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e255f5c removed from the list
,07-08 14:01:02.081  8695  8695 D io.jxcore.node.ConnectivityMonitor: stop,
07-08 14:01:02.081  8695  8695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,07-08 14:01:02.101  1116  3588 I ActivityManager: Start proc 8939:com.google.android.apps.plus/u0a126 for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor
,07-08 14:01:02.101  1116  3588 D Process : killProcessQuiet, pid=7991,
07-08 14:01:02.101  1116  3588 I ActivityManager: Killing 7991:com.google.android.gms.unstable/u0a20 (adj 15): empty #17
07-08 14:01:02.101  1116  3588 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityManagerService.trimApplications:19731 
,07-08 14:01:02.111  8939  8939 W HTCLOG  : use specified tag [FDManager], func [0].,
07-08 14:01:02.111  8939  8939 W HTCLOG  : mask=0x18
,07-08 14:01:02.121  6366  6680 I Icing   : Indexing done CF3FE6BD92DAECCC594E8F8BDE8C89D040E637CF
07-08 14:01:02.121  1116  2987 D PMS     : releaseWL(30c132f4): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10069 com.google.android.googlequicksearchbox}
,07-08 14:01:02.141   518  8935 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS),
07-08 14:01:02.141   518  8935 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
07-08 14:01:02.141  3526  8925 D libc    : [NET] android_getaddrinfo_proxy-, success
,07-08 14:01:02.191  3526  8925 D libc    : [NET] android_getaddrinfofornet+,hn 28(0x7265636f6d6d65),sn(),hints(known),family 0,flags 4,
07-08 14:01:02.191  3526  8925 D libc    : [NET] android_getaddrinfofornet-, err=8
,07-08 14:01:02.211  1116  5294 I ActivityManager: Recipient 7991
,07-08 14:01:02.291  8926  8964 W HTCLOG  : use specified tag [cutils-trace], func [0].
07-08 14:01:02.291  8926  8964 W HTCLOG  : mask=0x18
,07-08 14:01:02.291  8926  8964 E cutils-trace: Error opening trace file: Permission denied (13)
,07-08 14:01:02.321  3526  8925 I ContextualWidget: notifyRecommendedAppsUpdated,
07-08 14:01:02.321  3526  8925 I ContextualWidget: notifyRecommendedAppsUpdated
07-08 14:01:02.321  3526  8925 I ContextualWidget: notifyRecommendedAppsUpdated
07-08 14:01:02.321  3526  4160 I ContextualWidget: handleMessage, what=1013 mode=GettingOut maxcount=8,
,07-08 14:01:02.321  3526  4160 I ContextualWidget: update recommended apps for mode=HomeLife
07-08 14:01:02.331  8926  8926 D CustomizationManager: ====startRecUseTime====
07-08 14:01:02.331  8926  8926 D htc.customization.log.level:  is 
07-08 14:01:02.331  8926  8926 W CustomizationLogLevel: Level value is invalid, use default level 2
07-08 14:01:02.331  8865  8865 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
07-08 14:01:02.331  8695  8695 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-08 14:01:02.351  8939  8939 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-08 14:01:02.381  8695  8695 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 8695,
,07-08 14:01:02.381  3526  4160 I ContextualWidget: MFU.onRecommendDataSetChanged,
,07-08 14:01:02.391  8926  8926 D CustomizationManager:  Read ACC file spent 0.030 (s),
07-08 14:01:02.391  8926  8926 D CIDMapFileReader: Parsing tag item name = HTC__001
07-08 14:01:02.391  8926  8926 D CIDMapFileReader: Parsing tag item name = HTC__002
07-08 14:01:02.391  8926  8926 D CIDMapFileReader: Parsing tag item name = HTC__016
07-08 14:01:02.391  8926  8926 D CIDMapFileReader: Parsing tag item name = HTC__031
,07-08 14:01:02.391  8926  8926 D CIDMapFileReader: Parsing tag item name = HTC__032
07-08 14:01:02.391  8926  8926 D CIDMapFileReader: Parsing tag item name = HTC__102
07-08 14:01:02.391  8926  8926 D CIDMapFileReader: Parsing tag item name = HTC__A07
07-08 14:01:02.391  8926  8926 D CIDMapFileReader: Parsing tag item name = HTC__J15,
07-08 14:01:02.391  8926  8926 D CIDMapFileReader: Parsing tag item name = HTC__M27,
07-08 14:01:02.391  8926  8926 D CIDMapFileReader: Parsing tag item name = HTC__Y13
07-08 14:01:02.391  8926  8926 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__102.xml
07-08 14:01:02.391  8926  8926 I CustomizationCIDLoader: Parsing tag category name = application
07-08 14:01:02.391  8926  8926 I CustomizationCIDLoader: Parsing tag category name = system
07-08 14:01:02.391  8926  8926 I CustomizationCIDLoader: Parsing tag category name = Settings
07-08 14:01:02.391  8926  8926 I CustomizationCIDLoader: Parsing tag category name = ACC
,07-08 14:01:02.391  8926  8926 I CustomizationCIDLoader: add string-array item, value = 42507
07-08 14:01:02.391  8926  8926 I CustomizationCIDLoader: add string-array item, value = 21902
07-08 14:01:02.391  8926  8926 I CustomizationCIDLoader: add string-array item, value = 26006:26001.26002.26003
07-08 14:01:02.391  8926  8926 I CustomizationCIDLoader: add string-array item, value = 23420
07-08 14:01:02.391  8926  8926 I CustomizationCIDLoader: add string-array item, value = 22299
07-08 14:01:02.391  8926  8926 I CustomizationCIDLoader: add string-array item, value = 24002
07-08 14:01:02.391  8926  8926 I CustomizationCIDLoader: add string-array item, value = 23210
07-08 14:01:02.391  8926  8926 I CustomizationCIDLoader: add string-array item, value = 23205
07-08 14:01:02.391  8926  8926 I CustomizationCIDLoader: add string-array item, value = 23806
07-08 14:01:02.391  8926  8926 I CustomizationCIDLoader: add string-array item, value = 23430
,07-08 14:01:02.391  8926  8926 I CustomizationCIDLoader: add string-array item, value = 23408
07-08 14:01:02.391  8926  8926 I CustomizationCIDLoader: add string-array item, value = 27205
07-08 14:01:02.391  8926  8926 I CustomizationCIDLoader: add string-array item, value = 27202:27205
07-08 14:01:02.391  8926  8926 I CustomizationCIDLoader: add string-array item, value = 27216:27202.27205
07-08 14:01:02.391  8926  8926 I CustomizationCIDLoader: add string-array item, value = 42507:C:1:0
07-08 14:01:02.391  8926  8926 I CustomizationCIDLoader: add string-array item, value = 21902:C:1:0
07-08 14:01:02.391  8926  8926 I CustomizationCIDLoader: add string-array item, value = 26006:D:1:0
07-08 14:01:02.391  8926  8926 I CustomizationCIDLoader: add string-array item, value = 23420:D:0:0
07-08 14:01:02.391  8926  8926 I CustomizationCIDLoader: add string-array item, value = 27205:C:1:0
07-08 14:01:02.391  8926  8926 I CustomizationCIDLoader: add string-array item, value = 22299:D:0:0
,07-08 14:01:02.391  8926  8926 I CustomizationCIDLoader: add string-array item, value = 24002:D:0:0
07-08 14:01:02.391  8926  8926 I CustomizationCIDLoader: add string-array item, value = 23210:D:2:0
07-08 14:01:02.391  8926  8926 I CustomizationCIDLoader: add string-array item, value = 23205:D:2:0
07-08 14:01:02.391  8926  8926 I CustomizationCIDLoader: add string-array item, value = 23806:D:0:0
07-08 14:01:02.391  8926  8926 I CustomizationCIDLoader: add string-array item, value = 23430:C:1:0
07-08 14:01:02.391  8926  8926 I CustomizationCIDLoader: add string-array item, value = 23408:C:1:0
07-08 14:01:02.391  8926  8926 I CustomizationCIDLoader: add string-array item, value = 27202:C:1:0
,07-08 14:01:02.391  8926  8926 I CustomizationCIDLoader: add string-array item, value = 27216:C:1:0
07-08 14:01:02.391  8926  8926 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
07-08 14:01:02.391  8926  8926 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
07-08 14:01:02.391  8926  8926 I CustomizationCIDLoader: Parsing tag category name = AudioService
07-08 14:01:02.391  8926  8926 D CustomizationManager:  Read CID file spent 0.065 (s)
07-08 14:01:02.391  8926  8926 D CustomizationManager:  All configurations done spent 0.066 (s)
,07-08 14:01:02.401  3526  4160 I ContextualWidget: MFU.onRecommendDataSetChanged,
07-08 14:01:02.401  3526  4160 I ContextualWidget: handleMessage, what=1020 mode=GettingOut maxcount=8
,07-08 14:01:02.411  8865  8865 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,07-08 14:01:02.421  3526  4160 I ContextualWidget: getRecommendedFolder(GettingOut) - 4 , refresh=false
07-08 14:01:02.421  3526  4160 I ContextualWidget: handleMessage, what=1013 mode=GettingOut maxcount=8
07-08 14:01:02.421  3526  4160 I ContextualWidget: update recommended apps for mode=WorkTime
,07-08 14:01:02.421  1116  3574 D PackageManager: deletePackageAsUser: pkg=com.test.thalitest user=0, pid=8926, uid=2000
,07-08 14:01:02.431  1116  1163 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg,
07-08 14:01:02.431  1116  1163 D Process : killProcessQuiet, pid=8695
07-08 14:01:02.431  1116  1163 I ActivityManager: Killing 8695:com.test.thalitest/u0a0 (adj 9): stop com.test.thalitest
,07-08 14:01:02.431  1116  1163 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.removeProcessLocked:6195 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5997 
07-08 14:01:02.431  3526  4326 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
07-08 14:01:02.431  3526  3526 I SimpleImageLoader: addTask() - https://lh5.ggpht.com/cHtz6fFl1YsgSL_F014us5IL7uL0o-qagcQJGX7gwQWDK8N7S4uKI_W4iqC97nz9Ow=w300, ShortcutInfo(title=Fun Fit intent=Intent { cmp=com.aiqidi.nemo/com.nemo.ui.SplashActivity } id=-1 type=1 container=-1 appsContainer=<ALLAPPS> screen=0 cellX=0 cellY=0 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0})
07-08 14:01:02.431  3526  4851 D CacheManager: Thread name : SimpleImageLoader #2 , add callback : -329022872, url : aHR0cHM6Ly9saDUuZ2dwaHQuY29tL2NIdHo2ZkZsMVlzZ1NMX0YwMTR1czVJTDd1TDBvLXFhZ2NR
07-08 14:01:02.431  3526  4851 D CacheManager: SkdYN2d3UVdESzhON1M0dUtJX1c0aXFDOTduejlPdz13MzAw
07-08 14:01:02.441  3526  3526 I SimpleImageLoader: addTask() - https://lh4.ggpht.com/F0F4Z965uf3psiHu5h77e-8o-Yla68BEaJI8xLfK-V3JkMK4yQv1WLqqZQCwYhDevKoa=w300, ShortcutInfo(title=Yelp intent=Intent { act=android.intent.action.VIEW dat=market: } id=-1 type=1 container=-1 appsContainer=<ALLAPPS> screen=0 cellX=1 cellY=0 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0})
,07-08 14:01:02.441  3526  4850 D CacheManager: Thread name : SimpleImageLoader #1 , add callback : -1645233105, url : aHR0cHM6Ly9saDQuZ2dwaHQuY29tL0YwRjRaOTY1dWYzcHNpSHU1aDc3ZS04by1ZbGE2OEJFYUpJ
07-08 14:01:02.441  3526  4850 D CacheManager: OHhMZkstVjNKa01LNHlRdjFXTHFxWlFDd1loRGV2S29hPXczMDA=
07-08 14:01:02.451  3526  3526 I SimpleImageLoader: addTask() - https://lh6.ggpht.com/F5A9Q6ZksQUBNq-I2NH4KpRV9qkO7xBu71Zcjk6TNnxNChS29KimUIajma0v1_1iOIc=w300, ShortcutInfo(title=Zoe intent=Intent { cmp=com.htc.zero/.activity.ZeroMainActivity } id=-1 type=1 container=-1 appsContainer=<ALLAPPS> screen=0 cellX=0 cellY=1 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0})
,07-08 14:01:02.451  3526  3526 I SimpleImageLoader: addTask() - https://lh4.ggpht.com/a6ylT3ZfZU5avHMM3b-ppKjglntDV7OBilzED1Qe7BcunhElu-gSF4vDGjO2CxUYQg=w300, ShortcutInfo(title=Movies by Flixster intent=Intent { act=android.intent.action.VIEW dat=market: } id=-1 type=1 container=-1 appsContainer=<ALLAPPS> screen=0 cellX=1 cellY=1 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0})
,07-08 14:01:02.461  3526  3526 I ContextualWidget: notifyDataChanged, pos=7 item=FolderInfo: Suggestions for you, app folderId 44e5daf1-3588-4182-b462-c57e3f25da43, (Item(id=-1 type=7 container=-1 screen=-1 cellX=-1 cellY=-1 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0}))
,07-08 14:01:02.461  3526  3526 I HtcContextualWidgetDataManager: onDataChanged: GettingOut, position: 7, item:[FolderInfo: Suggestions for you, app folderId 44e5daf1-3588-4182-b462-c57e3f25da43, (Item(id=-1 type=7 container=-1 screen=-1 cellX=-1 cellY=-1 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0}))]
,07-08 14:01:02.461  3526  4160 I ContextualWidget: MFU.onRecommendDataSetChanged
,07-08 14:01:02.481  1116  1187 W PackageSettings: Skipping PackageSetting{39709627 com.example.hello/10193} due to missing metadata,
,07-08 14:01:02.491  3526  4160 I ContextualWidget: MFU.onRecommendDataSetChanged
,07-08 14:01:02.491  3526  4160 I ContextualWidget: handleMessage, what=1020 mode=GettingOut maxcount=8
,07-08 14:01:02.501   527   527 W HTCLOG  : use specified tag [Vector], func [0].,
07-08 14:01:02.501   527   527 W HTCLOG  : mask=0x18
,07-08 14:01:02.511  3526  4160 I ContextualWidget: getRecommendedFolder(GettingOut) - 4 , refresh=false,
07-08 14:01:02.511  3526  4160 I ContextualWidget: handleMessage, what=1013 mode=GettingOut maxcount=8
07-08 14:01:02.511  3526  3526 I SimpleImageLoader: addTask() - https://lh5.ggpht.com/cHtz6fFl1YsgSL_F014us5IL7uL0o-qagcQJGX7gwQWDK8N7S4uKI_W4iqC97nz9Ow=w300, ShortcutInfo(title=Fun Fit intent=Intent { cmp=com.aiqidi.nemo/com.nemo.ui.SplashActivity } id=-1 type=1 container=-1 appsContainer=<ALLAPPS> screen=0 cellX=0 cellY=0 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0})
07-08 14:01:02.511  3526  3526 I SimpleImageLoader: addTask() - Append a task with same Url: https://lh5.ggpht.com/cHtz6fFl1YsgSL_F014us5IL7uL0o-qagcQJGX7gwQWDK8N7S4uKI_W4iqC97nz9Ow=w300   [ShortcutInfo(title=Fun Fit intent=Intent { cmp=com.aiqidi.nemo/com.nemo.ui.SplashActivity } id=-1 type=1 container=-1 appsContainer=<ALLAPPS> screen=0 cellX=0 cellY=0 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0})]
07-08 14:01:02.511  3526  4160 I ContextualWidget: update recommended apps for mode=GettingOut
07-08 14:01:02.521  3526  3526 I SimpleImageLoader: addTask() - https://lh4.ggpht.com/F0F4Z965uf3psiHu5h77e-8o-Yla68BEaJI8xLfK-V3JkMK4yQv1WLqqZQCwYhDevKoa=w300, ShortcutInfo(title=Yelp intent=Intent { act=android.intent.action.VIEW dat=market: } id=-1 type=1 container=-1 appsContainer=<ALLAPPS> screen=0 cellX=1 cellY=0 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0})
07-08 14:01:02.521  3526  3526 I SimpleImageLoader: addTask() - Append a task with same Url: https://lh4.ggpht.com/F0F4Z965uf3psiHu5h77e-8o-Yla68BEaJI8xLfK-V3JkMK4yQv1WLqqZQCwYhDevKoa=w300   [ShortcutInfo(title=Yelp intent=Intent { act=android.intent.action.VIEW dat=market: } id=-1 type=1 container=-1 appsContainer=<ALLAPPS> screen=0 cellX=1 cellY=0 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0})]
07-08 14:01:02.521  3526  3526 I SimpleImageLoader: addTask() - https://lh6.ggpht.com/F5A9Q6ZksQUBNq-I2NH4KpRV9qkO7xBu71Zcjk6TNnxNChS29KimUIajma0v1_1iOIc=w300, ShortcutInfo(title=Zoe intent=Intent { cmp=com.htc.zero/.activity.ZeroMainActivity } id=-1 type=1 container=-1 appsContainer=<ALLAPPS> screen=0 cellX=0 cellY=1 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0}),
07-08 14:01:02.521  3526  3526 I SimpleImageLoader: addTask() - Append a task with same Url: https://lh6.ggpht.com/F5A9Q6ZksQUBNq-I2NH4KpRV9qkO7xBu71Zcjk6TNnxNChS29KimUIajma0v1_1iOIc=w300   [ShortcutInfo(title=Zoe intent=Intent { cmp=com.htc.zero/.activity.ZeroMainActivity } id=-1 type=1 container=-1 appsContainer=<ALLAPPS> screen=0 cellX=0 cellY=1 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0})]
07-08 14:01:02.521  3526  3526 I SimpleImageLoader: addTask() - https://lh4.ggpht.com/a6ylT3ZfZU5avHMM3b-ppKjglntDV7OBilzED1Qe7BcunhElu-gSF4vDGjO2CxUYQg=w300, ShortcutInfo(title=Movies by Flixster intent=Intent { act=android.intent.action.VIEW dat=market: } id=-1 type=1 container=-1 appsContainer=<ALLAPPS> screen=0 cellX=1 cellY=1 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0})
07-08 14:01:02.521  3526  3526 I SimpleImageLoader: addTask() - Append a task with same Url: https://lh4.ggpht.com/a6ylT3ZfZU5avHMM3b-ppKjglntDV7OBilzED1Qe7BcunhElu-gSF4vDGjO2CxUYQg=w300   [ShortcutInfo(title=Movies by Flixster intent=Intent { act=android.intent.action.VIEW dat=market: } id=-1 type=1 container=-1 appsContainer=<ALLAPPS> screen=0 cellX=1 cellY=1 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0})]
07-08 14:01:02.531  3526  3526 I ContextualWidget: notifyDataChanged, pos=7 item=FolderInfo: Suggestions for you, app folderId 44e5daf1-3588-4182-b462-c57e3f25da43, (Item(id=-1 type=7 container=-1 screen=-1 cellX=-1 cellY=-1 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0}))
,07-08 14:01:02.531  3526  3526 I HtcContextualWidgetDataManager: onDataChanged: GettingOut, position: 7, item:[FolderInfo: Suggestions for you, app folderId 44e5daf1-3588-4182-b462-c57e3f25da43, (Item(id=-1 type=7 container=-1 screen=-1 cellX=-1 cellY=-1 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0}))]
07-08 14:01:02.541  3526  4160 I ContextualWidget: MFU.onRecommendDataSetChanged
,07-08 14:01:02.551  3526  4160 I ContextualWidget: MFU.onRecommendDataSetChanged,
,07-08 14:01:02.561  3526  4160 I ContextualWidget: handleMessage, what=1020 mode=GettingOut maxcount=8
07-08 14:01:02.571  1116  3588 I ActivityManager: Recipient 8695
07-08 14:01:02.571  1116  2978 D WifiService: Client connection lost with reason: 4
,07-08 14:01:02.571  3334  3334 W HTCLOG  : use specified tag [InputEventReceiver], func [0].
07-08 14:01:02.571  3334  3334 W HTCLOG  : mask=0x18
07-08 14:01:02.571  3334  3334 E InputEventReceiver: Looper::removeFd(33) is failed, result(0), input channel 'ClientState{3f857530 uid 10000 pid 8695} (c)'
,07-08 14:01:02.601  3526  4160 I ContextualWidget: getRecommendedFolder(GettingOut) - 4 , refresh=false
07-08 14:01:02.601  3526  3526 I SimpleImageLoader: addTask() - https://lh5.ggpht.com/cHtz6fFl1YsgSL_F014us5IL7uL0o-qagcQJGX7gwQWDK8N7S4uKI_W4iqC97nz9Ow=w300, ShortcutInfo(title=Fun Fit intent=Intent { cmp=com.aiqidi.nemo/com.nemo.ui.SplashActivity } id=-1 type=1 container=-1 appsContainer=<ALLAPPS> screen=-1 cellX=-1 cellY=-1 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0}),
07-08 14:01:02.601  3526  3526 I SimpleImageLoader: addTask() - Append a task with same Url: https://lh5.ggpht.com/cHtz6fFl1YsgSL_F014us5IL7uL0o-qagcQJGX7gwQWDK8N7S4uKI_W4iqC97nz9Ow=w300   [ShortcutInfo(title=Fun Fit intent=Intent { cmp=com.aiqidi.nemo/com.nemo.ui.SplashActivity } id=-1 type=1 container=-1 appsContainer=<ALLAPPS> screen=-1 cellX=-1 cellY=-1 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0})]
07-08 14:01:02.611  3526  3526 I SimpleImageLoader: addTask() - https://lh4.ggpht.com/F0F4Z965uf3psiHu5h77e-8o-Yla68BEaJI8xLfK-V3JkMK4yQv1WLqqZQCwYhDevKoa=w300, ShortcutInfo(title=Yelp intent=Intent { act=android.intent.action.VIEW dat=market: } id=-1 type=1 container=-1 appsContainer=<ALLAPPS> screen=-1 cellX=-1 cellY=-1 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0})
07-08 14:01:02.611  3526  3526 I SimpleImageLoader: addTask() - Append a task with same Url: https://lh4.ggpht.com/F0F4Z965uf3psiHu5h77e-8o-Yla68BEaJI8xLfK-V3JkMK4yQv1WLqqZQCwYhDevKoa=w300   [ShortcutInfo(title=Yelp intent=Intent { act=android.intent.action.VIEW dat=market: } id=-1 type=1 container=-1 appsContainer=<ALLAPPS> screen=-1 cellX=-1 cellY=-1 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0})]
07-08 14:01:02.611  3526  3526 I SimpleImageLoader: addTask() - https://lh6.ggpht.com/F5A9Q6ZksQUBNq-I2NH4KpRV9qkO7xBu71Zcjk6TNnxNChS29KimUIajma0v1_1iOIc=w300, ShortcutInfo(title=Zoe intent=Intent { cmp=com.htc.zero/.activity.ZeroMainActivity } id=-1 type=1 container=-1 appsContainer=<ALLAPPS> screen=-1 cellX=-1 cellY=-1 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0})
07-08 14:01:02.611  3526  3526 I SimpleImageLoader: addTask() - Append a task with same Url: https://lh6.ggpht.com/F5A9Q6ZksQUBNq-I2NH4KpRV9qkO7xBu71Zcjk6TNnxNChS29KimUIajma0v1_1iOIc=w300   [ShortcutInfo(title=Zoe intent=Intent { cmp=com.htc.zero/.activity.ZeroMainActivity } id=-1 type=1 container=-1 appsContainer=<ALLAPPS> screen=-1 cellX=-1 cellY=-1 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0})]
,07-08 14:01:02.611  3526  3526 I SimpleImageLoader: addTask() - https://lh4.ggpht.com/a6ylT3ZfZU5avHMM3b-ppKjglntDV7OBilzED1Qe7BcunhElu-gSF4vDGjO2CxUYQg=w300, ShortcutInfo(title=Movies by Flixster intent=Intent { act=android.intent.action.VIEW dat=market: } id=-1 type=1 container=-1 appsContainer=<ALLAPPS> screen=-1 cellX=-1 cellY=-1 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0})
07-08 14:01:02.611  3526  3526 I SimpleImageLoader: addTask() - Append a task with same Url: https://lh4.ggpht.com/a6ylT3ZfZU5avHMM3b-ppKjglntDV7OBilzED1Qe7BcunhElu-gSF4vDGjO2CxUYQg=w300   [ShortcutInfo(title=Movies by Flixster intent=Intent { act=android.intent.action.VIEW dat=market: } id=-1 type=1 container=-1 appsContainer=<ALLAPPS> screen=-1 cellX=-1 cellY=-1 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0})]
,07-08 14:01:02.611  3526  3526 I ContextualWidget: notifyDataChanged, pos=7 item=FolderInfo: Suggestions for you, app folderId 44e5daf1-3588-4182-b462-c57e3f25da43, (Item(id=-1 type=7 container=-1 screen=-1 cellX=-1 cellY=-1 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0}))
07-08 14:01:02.611  3526  3526 I HtcContextualWidgetDataManager: onDataChanged: GettingOut, position: 7, item:[FolderInfo: Suggestions for you, app folderId 44e5daf1-3588-4182-b462-c57e3f25da43, (Item(id=-1 type=7 container=-1 screen=-1 cellX=-1 cellY=-1 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0}))]
,07-08 14:01:02.641  1116  3588 W ActivityManager: Spurious death for ProcessRecord{3802f3c1 8695:com.test.thalitest/u0a0}, curProc for 8695: null
,07-08 14:01:02.651  3662  3895 D CacheProvider: uri content://com.htc.sense.hsp.opensense.cachemanager/item
07-08 14:01:02.641  1116  1187 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,07-08 14:01:02.651  3662  3895 D CacheProvider: match  0
,07-08 14:01:02.671  1116  2974 D PMS     : acquireWL(7ccc766): PARTIAL_WAKE_LOCK  NetworkStats 0x1 1116 1000 null
07-08 14:01:02.671  5061  5061 I [MirrorLinkServer]MirrorLinkServer: Broadcast Received::Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
07-08 14:01:02.671  1116  2975 V NetworkPolicy: ACTION_UID_REMOVED for uid=10000
07-08 14:01:02.671  5061  5061 D [MirrorLinkServer]MirrorLinkServer: ACTION_PACKAGE_REMOVED intent received
07-08 14:01:02.681  1116  3475 D PMS     : acquireWL(15d62aa7): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 4336 10020 WorkSource{10020 com.google.android.gms}
07-08 14:01:02.671  5061  5061 D [MirrorLinkServer]MirrorLinkServer: Counter : 1
07-08 14:01:02.681  1116  1138 D PMS     : releaseWL(15d62aa7): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10020 com.google.android.gms}
07-08 14:01:02.671  5061  5061 D [MirrorLinkServer]MirrorLinkConnectionReceiver: notifyMlSevrer
07-08 14:01:02.681  4336  4855 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-08 14:01:02.681  3265  3265 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
07-08 14:01:02.681  3265  3265 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,07-08 14:01:02.691  5061  5061 I [MirrorLinkServer]MirrorLinkServer: onStartCommand() Action : android.intent.action.PACKAGE_REMOVED
07-08 14:01:02.691  5061  5061 D [MirrorLinkServer]MirrorLinkServer: Application Removed
07-08 14:01:02.691  5061  5061 D [MirrorLinkServer]MirrorLinkServer:  Application removed : com.test.thalitest
07-08 14:01:02.691  5061  5061 D [MirrorLinkServer]d: onApplicationRemoved
07-08 14:01:02.691  5061  5061 I [MirrorLinkServer]d: Package name found : com.test.thalitest
07-08 14:01:02.691  1116  2967 W SystemReader: Cannot find grip_rejection_width, use default value instead
07-08 14:01:02.691  3767  4251 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
07-08 14:01:02.691  5061  8989 I [MirrorLinkServer]c: onApplicationUpdationCompleted, sending broadcast
07-08 14:01:02.701  3767  4251 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,07-08 14:01:02.701  5061  5061 I [MirrorLinkServer]MirrorLinkServer: Broadcast Received::Intent { act=com.htc.HTCMirrorLinkServer.PACKAGE_UPDATE_COMPLETED }
07-08 14:01:02.701  5061  5061 D [MirrorLinkServer]MirrorLinkServer: ML_PACKAGE_UPDATE_COMPLETED intent received
07-08 14:01:02.701  5061  5061 D [MirrorLinkServer]MirrorLinkServer: Counter : 0
07-08 14:01:02.701  5061  5061 I [MirrorLinkServer]MirrorLinkConnectionReceiver: checkAndStopMLSession
07-08 14:01:02.701  5061  5061 I [MirrorLinkServer]MirrorLinkConnectionReceiver: Stopping Service
07-08 14:01:02.701  6637  6637 I art     : Explicit concurrent mark sweep GC freed 10591(710KB) AllocSpace objects, 0(0B) LOS objects, 30% free, 4MB/6MB, paused 496us total 55.237ms
,07-08 14:01:02.711  1116  2974 D PMS     : releaseWL(7ccc766): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
07-08 14:01:02.711  1116  2975 V NetworkPolicy: writePolicyLocked()
,07-08 14:01:02.721  1116  2975 D NetworkPolicy: notifyPoliciesChangeLocked: no change,
07-08 14:01:02.721  3767  4251 D AccTypeManager: Registering external account type=com.google.android.gm.exchange, packageName=com.google.android.gm
07-08 14:01:02.721  1116  2975 V NetworkPolicy: updateNetworkEnabledLocked()
07-08 14:01:02.721  1116  2975 V NetworkPolicy: updateNotificationsLocked()
07-08 14:01:02.721  1116  1163 I ActivityManager: Waited long enough for: ServiceRecord{35a29193 u0 com.nero.android.htc.sync/.PowerDisconService}
,07-08 14:01:02.721  1116  1162 I InputMethodManagerService: [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,07-08 14:01:02.751  3767  4251 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
07-08 14:01:02.751  3526  8987 D CacheManager: Thread name : pool-2-thread-5 , In done : -329022872
07-08 14:01:02.751  3526  8990 D CacheManager: Thread name : Thread-118 , on Download Success callback : file:///storage/emulated/0/.data/CacheManager/-329022872
07-08 14:01:02.751  3500  3500 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
07-08 14:01:02.751  3526  8990 I AsyncImageDownLoader: CacheManager download success: https://lh5.ggpht.com/cHtz6fFl1YsgSL_F014us5IL7uL0o-qagcQJGX7gwQWDK8N7S4uKI_W4iqC97nz9Ow=w300
,07-08 14:01:02.771  1116  3529 D PMS     : acquireWL(3a9f91ee): PARTIAL_WAKE_LOCK  AsyncService 0x1 8939 10126 null
,07-08 14:01:02.781  3767  4251 E ExternalAccountType: Unsupported attribute readOnly
07-08 14:01:02.781  3526  4851 D CacheManager: Thread name : SimpleImageLoader #2 , add callback : 1858784170, url : aHR0cHM6Ly9saDYuZ2dwaHQuY29tL0Y1QTlRNlprc1FVQk5xLUkyTkg0S3BSVjlxa083eEJ1NzFa
07-08 14:01:02.781  3526  4851 D CacheManager: Y2prNlRObnhOQ2hTMjlLaW1VSWFqbWEwdjFfMWlPSWM9dzMwMA==
,07-08 14:01:02.801  1116  3324 D PMS     : releaseWL(3a9f91ee): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,07-08 14:01:02.811  1116  1162 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,07-08 14:01:02.811  1116  1116 W PackageManager: Unable to load service info ResolveInfo{348ccbdd com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
07-08 14:01:02.811  1116  1116 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
07-08 14:01:02.811  1116  1116 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:509)
07-08 14:01:02.811  1116  1116 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:345)
07-08 14:01:02.811  1116  1116 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:171)
07-08 14:01:02.811  1116  1116 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:71)
07-08 14:01:02.811  1116  1116 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:180)
07-08 14:01:02.811  1116  1116 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:927)
07-08 14:01:02.811  1116  1116 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
07-08 14:01:02.811  1116  1116 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-08 14:01:02.811  1116  1116 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
07-08 14:01:02.811  1116  1116 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:331)
07-08 14:01:02.811  1116  1116 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:232)
07-08 14:01:02.811  1116  1116 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
07-08 14:01:02.811  1116  1116 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-08 14:01:02.811  1116  1116 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
07-08 14:01:02.811  1116  1116 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
,07-08 14:01:02.811  3526  3562 I art     : Background partial concurrent mark sweep GC freed 13303(719KB) AllocSpace objects, 27(2MB) LOS objects, 25% free, 47MB/63MB, paused 5.909ms total 58.551ms
,07-08 14:01:02.841  3662  3895 D CacheProvider: uri content://com.htc.sense.hsp.opensense.cachemanager/item
,07-08 14:01:02.841  3662  3895 D CacheProvider: match  0
,07-08 14:01:02.841  1116  1187 I art     : Explicit concurrent mark sweep GC freed 32426(2MB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 17MB/26MB, paused 1.680ms total 177.481ms
07-08 14:01:02.841  1116  3056 D TaskPersister: removeObsoleteFile: deleting file=122_task.xml
07-08 14:01:02.841  1116  3056 D TaskPersister: removeObsoleteFile: deleting file=122_task_thumbnail.png
,07-08 14:01:02.861  3662  3703 D CacheProvider: uri content://com.htc.sense.hsp.opensense.cachemanager/item,
07-08 14:01:02.861  3662  3703 D CacheProvider: match  0
07-08 14:01:02.861  8926  8926 I art     : System.exit called, status: 0
07-08 14:01:02.871  8926  8926 W HTCLOG  : use specified tag [Vector], func [0].
07-08 14:01:02.871  8926  8926 W HTCLOG  : mask=0x18
07-08 14:01:02.871  3526  8988 D CacheManager: Thread name : pool-2-thread-6 , In done : -1645233105
07-08 14:01:02.871  3526  8999 D CacheManager: Thread name : Thread-121 , on Download Success callback : file:///storage/emulated/0/.data/CacheManager/-1645233105
07-08 14:01:02.871  3526  8999 I AsyncImageDownLoader: CacheManager download success: https://lh4.ggpht.com/F0F4Z965uf3psiHu5h77e-8o-Yla68BEaJI8xLfK-V3JkMK4yQv1WLqqZQCwYhDevKoa=w300
07-08 14:01:02.871  6366  8996 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
07-08 14:01:02.881  6366  8995 E IntentOperationSvc: Failed to instantiate Chimera operation impl, dropping operation
07-08 14:01:02.881  1116  1187 I ActivityManager: Start proc 9000:com.android.defcontainer/u0a11 for service com.android.defcontainer/.DefaultContainerService
,07-08 14:01:02.891  6366  8996 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,07-08 14:01:02.891  6366  6366 D AsyncTaskServiceImpl: Submit a task: nwp
,07-08 14:01:02.891  9000  9000 W HTCLOG  : use specified tag [FDManager], func [0].
07-08 14:01:02.891  9000  9000 W HTCLOG  : mask=0x18
,07-08 14:01:02.901  3526  8994 D CacheManager: Thread name : pool-2-thread-7 , In done : 1858784170
07-08 14:01:02.901  3526  9018 D CacheManager: Thread name : Thread-122 , on Download Success callback : file:///storage/emulated/0/.data/CacheManager/1858784170
07-08 14:01:02.901  3526  9018 I AsyncImageDownLoader: CacheManager download success: https://lh6.ggpht.com/F5A9Q6ZksQUBNq-I2NH4KpRV9qkO7xBu71Zcjk6TNnxNChS29KimUIajma0v1_1iOIc=w300
07-08 14:01:02.901  3526  4850 D CacheManager: Thread name : SimpleImageLoader #1 , add callback : 981433814, url : aHR0cHM6Ly9saDQuZ2dwaHQuY29tL2E2eWxUM1pmWlU1YXZITU0zYi1wcEtqZ2xudERWN09CaWx6
07-08 14:01:02.901  3526  4850 D CacheManager: RUQxUWU3QmN1bmhFbHUtZ1NGNHZER2pPMkN4VVlRZz13MzAw
07-08 14:01:02.911  1116  1138 D PMS     : acquireWL(112b7129): PARTIAL_WAKE_LOCK  Icing 0x1 6366 10020 WorkSource{10020 com.google.android.gms}
,07-08 14:01:02.911  6366  8996 E Vision  : Failed to find package com.test.thalitest
07-08 14:01:02.911  6366  8996 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
07-08 14:01:02.931  6366  6680 D nwp     : Processing package: com.test.thalitest
07-08 14:01:02.931  6366  6680 W nwp     : Failed to find package com.test.thalitest
,07-08 14:01:02.941  6366  6979 E WorkSourceUtil: Could not find package: com.test.thalitest,
07-08 14:01:02.941  3526  3988 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
07-08 14:01:02.941  3526  3988 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,07-08 14:01:02.941  6366  6680 E Icing   : Package com.test.thalitest not found
,07-08 14:01:02.961  1116  1139 I ActivityManager: Killing 8568:com.google.android.setupwizard/u0a62 (adj 15): empty #17
07-08 14:01:02.961  1116  1139 D Process : killProcessQuiet, pid=8568
,07-08 14:01:02.961  1116  1139 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19304 
,07-08 14:01:02.991  1116  1116 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,07-08 14:01:03.031  3662  3896 D CacheProvider: uri content://com.htc.sense.hsp.opensense.cachemanager/item,
07-08 14:01:03.031  3662  3896 D CacheProvider: match  0,
,07-08 14:01:03.041  3526  9021 D CacheManager: Thread name : pool-2-thread-8 , In done : 981433814
,07-08 14:01:03.041  3526  9029 D CacheManager: Thread name : Thread-124 , on Download Success callback : file:///storage/emulated/0/.data/CacheManager/981433814,
07-08 14:01:03.041  3526  9029 I AsyncImageDownLoader: CacheManager download success: https://lh4.ggpht.com/a6ylT3ZfZU5avHMM3b-ppKjglntDV7OBilzED1Qe7BcunhElu-gSF4vDGjO2CxUYQg=w300
,07-08 14:01:03.071  1116  1138 I ActivityManager: Recipient 8568,
,07-08 14:01:03.091  3059  3059 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL',
,07-08 14:01:03.181  3416  3416 D Nfc-Utils: isNxpCodebase: isNxp=false
,07-08 14:01:03.211  3662  3895 E SQLiteLog: (3850) statement aborts at 19: [UPDATE item SET  last_modified_time=? WHERE _id = 4] disk I/O error,
07-08 14:01:03.211  3662  3895 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
07-08 14:01:03.211  3662  3895 W HTCLOG  : mask=0x18
07-08 14:01:03.211  3662  3895 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.htc.sense.hsp/databases/cache.db, handle: 0x55bbd22150
07-08 14:01:03.211  3662  3895 E DatabaseUtils: Writing exception to parcel
07-08 14:01:03.211  3662  3895 E DatabaseUtils: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-08 14:01:03.211  3662  3895 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-08 14:01:03.211  3662  3895 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
07-08 14:01:03.211  3662  3895 E DatabaseUtils: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-08 14:01:03.211  3662  3895 E DatabaseUtils: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-08 14:01:03.211  3662  3895 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1675)
07-08 14:01:03.211  3662  3895 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1621)
07-08 14:01:03.211  3662  3895 E DatabaseUtils: 	at com.htc.sense.hsp.opensense.cachemanager.CacheProvider.update(Unknown Source)
07-08 14:01:03.211  3662  3895 E DatabaseUtils: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:338)
07-08 14:01:03.211  3662  3895 E DatabaseUtils: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:258)
07-08 14:01:03.211  3662  3895 E DatabaseUtils: 	at android.os.Binder.execTransact(Binder.java:454)
,07-08 14:01:03.221  3526  9021 W System.err: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
,07-08 14:01:03.221   544   703 W HTCLOG  : use specified tag [ThermalEngine], func [0].
07-08 14:01:03.221   544   703 W HTCLOG  : mask=0x18
,07-08 14:01:03.221  1116  3543 I ActivityManager: Start proc 9030:com.android.vending/u0a57 for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
07-08 14:01:03.231  3526  9021 W System.err: 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:179)
07-08 14:01:03.231  3526  9021 W System.err: 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
07-08 14:01:03.231  3526  9021 W System.err: 	at android.content.ContentProviderProxy.update(ContentProviderNative.java:622)
07-08 14:01:03.231  3526  9021 W System.err: 	at android.content.ContentProviderClient.update(ContentProviderClient.java:279)
07-08 14:01:03.231  3526  9021 W System.err: 	at com.htc.lib2.opensense.cache.CacheManager.updateToDb(CacheManager.java:772)
07-08 14:01:03.231  3526  9021 W System.err: 	at com.htc.lib2.opensense.cache.CacheManager.access$1000(CacheManager.java:66)
07-08 14:01:03.231  3526  9021 W System.err: 	,at com.htc.lib2.opensense.cache.CacheManager$DownloadFutureTask.done(CacheManager.java:1020)
07-08 14:01:03.231  3526  9021 W System.err: 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
07-08 14:01:03.231  3526  9021 W System.err: 	at java.util.concurrent.FutureTask.set(FutureTask.java:204)
07-08 14:01:03.231  3526  9021 W System.err: 	at java.util.concurrent.FutureTask.run(FutureTask.java:245)
07-08 14:01:03.231  3526  9021 W System.err: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-08 14:01:03.231  3526  9021 W System.err: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-08 14:01:03.231  3526  9021 W System.err: 	at java.lang.Thread.run(Thread.java:818)
,07-08 14:01:03.231  3526  9021 E CacheManager: Thread name : pool-2-thread-8 , Exception in [updateToDb] : android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-08 14:01:03.231  6366  6680 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
07-08 14:01:03.231  6366  6680 E Icing   : Writing status failed
,07-08 14:01:03.231  6366  6680 E Icing   : Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
,07-08 14:01:03.241  9030  9030 W HTCLOG  : use specified tag [FDManager], func [0].
,07-08 14:01:03.241  9030  9030 W HTCLOG  : mask=0x18
,07-08 14:01:03.351  1116  4027 I PackageManager:  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=9030, uid=10057, userID:0
,07-08 14:01:03.361  9030  9030 W global  : [apache-http] Connection GC has been deprecated!,
,07-08 14:01:03.371  9030  9030 I Finsky  : [1] com.google.android.finsky.FinskyApp.onCreate(428): Initializing network with DFE https://android.clients.google.com/fdfe/
,07-08 14:01:03.431  9030  9030 E PlayRollingFileStream: Could not create a temp file with prefix: "eventlog.store" and suffix: ".log" in dir: "/data/data/com.android.vending/cache/logs/com.google.thalitester%40gmail.com".,
,07-08 14:01:03.441  9030  9030 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(171): No need to run daily hygiene.,
,07-08 14:01:03.451  9030  9030 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-08 14:01:03.451  9030  9072 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
07-08 14:01:03.451  9030  9030 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,07-08 14:01:03.451  9030  9072 W HTCLOG  : mask=0x18
,07-08 14:01:03.461  9030  9072 E SQLiteDatabase: Failed to open database '/data/data/com.android.vending/databases/library.db'.
07-08 14:01:03.461  9030  9072 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-08 14:01:03.461  9030  9072 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-08 14:01:03.461  9030  9072 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-08 14:01:03.461  9030  9072 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-08 14:01:03.461  9030  9072 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-08 14:01:03.461  9030  9072 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-08 14:01:03.461  9030  9072 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-08 14:01:03.461  9030  9072 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-08 14:01:03.461  9030  9072 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-08 14:01:03.461  9030  9072 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-08 14:01:03.461  9030  9072 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-08 14:01:03.461  9030  9072 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-08 14:01:03.461  9030  9072 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-08 14:01:03.461  9030  9072 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
,07-08 14:01:03.461  9030  9072 E SQLiteDatabase: 	at com.google.android.finsky.j.av.iterator(SourceFile:15316)
07-08 14:01:03.461  9030  9072 E SQLiteDatabase: 	at com.google.android.finsky.j.w.run(SourceFile:1078)
07-08 14:01:03.461  9030  9072 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
07-08 14:01:03.461  9030  9072 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-08 14:01:03.461  9030  9072 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
07-08 14:01:03.461  9030  9072 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-08 14:01:03.461  9030  9072 W Finsky.CrashDetector: Failed to write crash file cnt=0 ts=0 cause=null.,
07-08 14:01:03.461  9030  9072 W Finsky.CrashDetector: java.io.FileNotFoundException: /data/data/com.android.vending/cache/crash806713: open failed: EROFS (Read-only file system)
07-08 14:01:03.461  9030  9072 W Finsky.CrashDetector: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-08 14:01:03.461  9030  9072 W Finsky.CrashDetector: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-08 14:01:03.461  9030  9072 W Finsky.CrashDetector: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-08 14:01:03.461  9030  9072 W Finsky.CrashDetector: 	at com.google.android.finsky.a.a(SourceFile:180)
07-08 14:01:03.461  9030  9072 W Finsky.CrashDetector: 	at com.google.android.finsky.a.uncaughtException(SourceFile:98)
07-08 14:01:03.461  9030  9072 W Finsky.CrashDetector: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
07-08 14:01:03.461  9030  9072 W Finsky.CrashDetector: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
07-08 14:01:03.461  9030  9072 W Finsky.CrashDetector: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-08 14:01:03.461  9030  9072 W Finsky.CrashDetector: 	at libcore.io.Posix.open(Native Method)
07-08 14:01:03.461  9030  9072 W Finsky.CrashDetector: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-08 14:01:03.461  9030  9072 W Finsky.CrashDetector: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-08 14:01:03.461  9030  9072 W Finsky.CrashDetector: 	... 6 more
07-08 14:01:03.461  9030  9072 E AndroidRuntime: FATAL EXCEPTION: libraries-thread
07-08 14:01:03.461  9030  9072 E AndroidRuntime: Process: com.android.vending, PID: 9030
07-08 14:01:03.461  9030  9072 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-08 14:01:03.461  9030  9072 E AndroidRuntime: 	,at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-08 14:01:03.461  9030  9072 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-08 14:01:03.461  9030  9072 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-08 14:01:03.461  9030  9072 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-08 14:01:03.461  9030  9072 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-08 14:01:03.461  9030  9072 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-08 14:01:03.461  9030  9072 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-08 14:01:03.461  9030  9072 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-08 14:01:03.461  9030  9072 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-08 14:01:03.461  9030  9072 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-08 14:01:03.461  9030  9072 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-08 14:01:03.461  9030  9072 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-08 14:01:03.461  9030  9072 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-08 14:01:03.461  9030  9072 E AndroidRuntime: 	at com.google.android.finsky.j.av.iterator(SourceFile:15316)
07-08 14:01:03.461  9030  9072 E AndroidRuntime: 	at com.google.android.finsky.j.w.run(SourceFile:1078)
07-08 14:01:03.461  9030  9072 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
07-08 14:01:03.461  9030  9072 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-08 14:01:03.461  9030  9072 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
07-08 14:01:03.461  9030  9072 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-08 14:01:03.471  1116  1139 I PackageManager:  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=9030, uid=10057, userID:0
07-08 14:01:03.461  1116  3574 E ActivityManager: App crashed! Process: com.android.vending
07-08 14:01:03.471  1116  9074 E DropBoxManagerService: Can't write: system_app_crash
07-08 14:01:03.471  1116  9074 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop139.tmp: open failed: EROFS (Read-only file system)
07-08 14:01:03.471  1116  9074 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-08 14:01:03.471  1116  9074 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-08 14:01:03.471  1116  9074 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-08 14:01:03.471  1116  9074 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
07-08 14:01:03.471  1116  9074 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-08 14:01:03.471  1116  9074 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
07-08 14:01:03.471  1116  9074 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-08 14:01:03.471  1116  9074 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-08 14:01:03.471  1116  9074 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-08 14:01:03.471  1116  9074 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-08 14:01:03.471  1116  9074 E DropBoxMana,gerService: 	... 5 more
07-08 14:01:03.471  9030  9030 I Finsky  : [1] com.google.android.finsky.utils.bk.a(177): Enabling bucket experiment: factor=2.000, zeroDelta=0ms, forceNetwork=false
07-08 14:01:03.471  9030  9073 E AndroidRuntime_2_crash: crash in the same process: AsyncTask #1
07-08 14:01:03.471  9030  9073 E AndroidRuntime_2_crash: java.lang.RuntimeException: An error occured while executing doInBackground()
07-08 14:01:03.471  9030  9073 E AndroidRuntime_2_crash: 	at android.os.AsyncTask$3.done(AsyncTask.java:304)
07-08 14:01:03.471  9030  9073 E AndroidRuntime_2_crash: 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
07-08 14:01:03.471  9030  9073 E AndroidRuntime_2_crash: 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
07-08 14:01:03.471  9030  9073 E AndroidRuntime_2_crash: 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
07-08 14:01:03.471  9030  9073 E AndroidRuntime_2_crash: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
07-08 14:01:03.471  9030  9073 E AndroidRuntime_2_crash: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-08 14:01:03.471  9030  9073 E AndroidRuntime_2_crash: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-08 14:01:03.471  9030  9073 E AndroidRuntime_2_crash: 	at java.lang.Thread.run(Thread.java:818)
07-08 14:01:03.471  9030  9073 E AndroidRuntime_2_crash: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-08 14:01:03.471  9030  9073 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-08 14:01:03.471  9030  9073 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-08 14:01:03.471  9030  9073 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-08 14:01:03.471  9030  9073 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-08 14:01:03.471  9030  9073 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-08 14:01:03.471  9030  9073 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-08 14:01:03.471  9030  9073 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-08 14:01:03.471  9030  9073 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-08 14:01:03.471  9030  9073 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-08 14:01:03.471  9030  9073 E AndroidRuntime_2_crash: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-08 14:01:03.471  9030  9073 E AndroidRuntime_2_crash: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-08 14:01:03.471  9030  9073 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-08 14:01:03.471  9030  9073 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-08 14:01:03.471  9030  9073 E AndroidRuntime_2_crash: 	at com.google.android.finsky.c.z.a(SourceFile:2336)
07-08 14:01:03.471  9030  9073 E AndroidRuntime_2_crash: 	at com.google.android.finsky.c.ab.c(SourceFile:56)
07-08 14:01:03.471  9030  9073 E AndroidRuntime_2_crash: 	at com.google.android.finsky.receivers.l.doInBackground(SourceFile:3083)
07-08 14:01:03.471  9030  9073 E AndroidRuntime_2_crash: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
07-08 14:01:03.471  9030  9073 E AndroidRuntime_2_crash: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-08 14:01:03.471  9030  9073 E AndroidRuntime_2_crash: 	... 4 more
07-08 14:01:03.471  9030  9073 E SQLiteDatabase: Failed to open database '/data/data/com.android.vending/databases/localappstate.db'.
07-08 14:01:03.471  9030  9073 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-08 14:01:03.471  9030  9073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-08 14:01:03.471  9030  9073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-08 14:01:03.471  9030  9073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-08 14:01:03.471  9030  9073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-08 14:01:03.471  9030  9073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-08 14:01:03.471  9030  9073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-08 14:01:03.471  9030  9073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-08 14:01:03.471  9030  9073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-08 14:01:03.471  9030  9073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-08 14:01:03.471  9030  9073 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-08 14:01:03.471  9030  9073 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-08 14:01:03.471  9030  9073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-08 14:01:03.471  9030  9073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-08 14:01:03.471  9030  9073 E SQLiteDatabase: 	at com.google.android.finsky.c.z.a(SourceFile:2336)
07-08 14:01:03.471  9030  9073 E SQLiteDatabase: 	at com.google.android.finsky.c.ab.c(SourceFile:56)
07-08 14:01:03.471  9030  9073 E SQLiteDatabase: 	at com.google.android.finsky.receivers.l.doInBackground(SourceFile:3083)
07-08 14:01:03.471  9030  9073 E SQLiteDatabase: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
07-08 14:01:03.471  9030  9073 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-08 14:01:03.471  9030  9073 E SQLiteDatabase: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
07-08 14:01:03.471  9030  9073 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-08 14:01:03.471  9030  9073 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-08 14:01:03.471  9030  9073 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-08 14:01:03.511  9030  9075 E SQLiteDatabase: Failed to open database '/data/data/com.android.vending/databases/localappstate.db'.
07-08 14:01:03.511  9030  9075 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-08 14:01:03.511  9030  9075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-08 14:01:03.511  9030  9075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-08 14:01:03.511  9030  9075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-08 14:01:03.511  9030  9075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-08 14:01:03.511  9030  9075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-08 14:01:03.511  9030  9075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-08 14:01:03.511  9030  9075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-08 14:01:03.511  9030  9075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-08 14:01:03.511  9030  9075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
,07-08 14:01:03.511  9030  9075 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-08 14:01:03.511  9030  9075 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-08 14:01:03.511  9030  9075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-08 14:01:03.511  9030  9075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-08 14:01:03.511  9030  9075 E SQLiteDatabase: 	at com.google.android.finsky.c.z.a(SourceFile:2336)
07-08 14:01:03.511  9030  9075 E SQLiteDatabase: 	at com.google.android.finsky.c.ab.c(SourceFile:56)
07-08 14:01:03.511  9030  9075 E SQLiteDatabase: 	at com.google.android.finsky.c.v.doInBackground(SourceFile:4083)
07-08 14:01:03.511  9030  9075 E SQLiteDatabase: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
07-08 14:01:03.511  9030  9075 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-08 14:01:03.511  9030  9075 E SQLiteDatabase: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
07-08 14:01:03.511  9030  9075 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-08 14:01:03.511  9030  9075 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-08 14:01:03.511  9030  9075 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-08 14:01:03.511  9030  9075 E AndroidRuntime_3_crash: crash in the same process: AsyncTask #2
07-08 14:01:03.511  9030  9075 E AndroidRuntime_3_crash: java.lang.RuntimeException: An error occured while executing doInBackground()
07-08 14:01:03.511  9030  9075 E AndroidRuntime_3_crash: 	at android.os.AsyncTask$3.done(AsyncTask.java:304)
07-08 14:01:03.511  9030  9075 E AndroidRuntime_3_crash: 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
07-08 14:01:03.511  9030  9075 E AndroidRuntime_3_crash: 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
07-08 14:01:03.511  9030  9075 E AndroidRuntime_3_crash: 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
07-08 14:01:03.511  9030  9075 E AndroidRuntime_3_crash: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
07-08 14:01:03.511  9030  9075 E AndroidRuntime_3_crash: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-08 14:01:03.511  9030  9075 E AndroidRuntime_3_crash: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-08 14:01:03.511  9030  9075 E AndroidRuntime_3_crash: 	at java.lang.Thread.run(Thread.java:818)
07-08 14:01:03.511  9030  9075 E AndroidRuntime_3_crash: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-08 14:01:03.511  9030  9075 E AndroidRuntime_3_crash: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-08 14:01:03.511  9030  9075 E AndroidRuntime_3_crash: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-08 14:01:03.511  9030  9075 E AndroidRuntime_3_crash: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-08 14:01:03.511  9030  9075 E AndroidRuntime_3_crash: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-08 14:01:03.511  9030  9075 E AndroidRuntime_3_crash: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-08 14:01:03.511  9030  9075 E AndroidRuntime_3_crash: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-08 14:01:03.511  9030  9075 E AndroidRuntime_3_crash: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-08 14:01:03.511  9030  9075 E AndroidRuntime_3_crash: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-08 14:01:03.511  9030  9075 E AndroidRuntime_3_crash: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-08 14:01:03.511  9030  9075 E AndroidRuntime_3_crash: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-08 14:01:03.511  9030  9075 E AndroidRuntime_3_crash: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-08 14:01:03.511  9030  9075 E AndroidRuntime_3_crash: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-08 14:01:03.511  9030  9075 E AndroidRuntime_3_crash: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-08 14:01:03.511  9030  9075 E AndroidRuntime_3_crash: 	at com.google.android.finsky.c.z.a(SourceFile:2336)
07-08 14:01:03.511  9030  9075 E AndroidRuntime_3_crash: 	at com.google.android.finsky.c.ab.c(SourceFile:56)
07-08 14:01:03.511  9030  9075 E AndroidRuntime_3_crash: 	at com.google.android.finsky.c.v.doInBackground(SourceFile:4083)
07-08 14:01:03.511  9030  9075 E AndroidRuntime_3_crash: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
07-08 14:01:03.511  9030  9075 E AndroidRuntime_3_crash: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-08 14:01:03.511  9030  9075 E AndroidRuntime_3_crash: 	... 4 more
07-08 14:01:03.521  9077  9077 W HTCLOG  : use specified tag [FDManager], func [0].
07-08 14:01:03.521  9077  9077 W HTCLOG  : mask=0x18
07-08 14:01:03.531  1116  1139 I ActivityManager: Start proc 9077:com.google.android.setupwizard/u0a62 for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver
07-08 14:01:03.531  1116  3946 D Process : killProcessQuiet, pid=8626
07-08 14:01:03.531  1116  3946 I ActivityManager: Killing 8626:com.htc.widget.hmsproc1/u0a32 (adj 15): empty #17
07-08 14:01:03.531  1116  3946 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityManagerService.removeContentProvider:10118 
07-08 14:01:03.541   547   547 I art     : Explicit concurrent mark sweep GC freed 8607(366KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 163KB/4MB, paused 121us total 26.168ms
07-08 14:01:03.541  1116  1164 D StatusBarManagerService: setSystemUiVisibility(0xc0000000)
07-08 14:01:03.541  1116  1164 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{21caeee9 u0 Application Error: com.android.vending}
07-08 14:01:03.541  1116  1164 D StatusBarManagerService: hiding MENU key
07-08 14:01:03.541  3122  3122 I PhoneStatusBar: setSystemUiNavVisibility(swipe=false hasFocus=false hasPolicy=false shadeState=true)
07-08 14:01:03.541  3122  3122 I PhoneStatusBar: hiding the MENU button mLongPressHomeMenu = false
,07-08 14:01:03.561   547   547 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 163KB/4MB, paused 112us total 18.551ms
,07-08 14:01:03.581   547   547 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 163KB/4MB, paused 101us total 18.579ms,
,07-08 14:01:03.681  1116  3532 I ActivityManager: Recipient 8626,
,07-08 14:01:03.811  9030  9030 I Finsky  : [1] com.google.android.finsky.receivers.j.a(1226): Installer kick - no action, not running yet
,07-08 14:01:03.841  9077  9077 I SetupWizard: Connected to Gservices successfully
,07-08 14:01:03.841  9030  9055 E SharedPreferencesImpl: Couldn't rename file /data/data/com.android.vending/shared_prefs/finsky.xml to backup file /data/data/com.android.vending/shared_prefs/finsky.xml.bak
,07-08 14:01:03.871  1116  3946 D PMS     : acquireWL(62533b8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 8523 10102 null
,07-08 14:01:03.881  4336  9103 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,07-08 14:01:03.891  3526  3526 D Prism.PackageStateRece_: action: android.intent.action.PACKAGE_CHANGED,
07-08 14:01:03.891  3526  3526 I ContextualWidget: package com.google.android.gms changed
07-08 14:01:03.891  9077  9100 I SetupWizard.FrpHelper: FRP status: supported: true, challengeRequired: false
,07-08 14:01:03.901  3526  4160 I ContextualWidget: handleMessage, what=1026 mode=GettingOut maxcount=8
,07-08 14:01:03.911  6637  9108 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,07-08 14:01:03.911  3662  9106 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
07-08 14:01:03.911  3662  9106 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed
07-08 14:01:03.911  3804  3996 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
07-08 14:01:03.911  3804  3996 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
07-08 14:01:03.911  3804  3996 W HTCLOG  : mask=0x18
07-08 14:01:03.911  3804  3996 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.android.providers.contacts/databases/contacts2.db, handle: 0x55bbbb0030
07-08 14:01:03.911  3804  3996 W ContactsProvider: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-08 14:01:03.911  3804  3996 W ContactsProvider: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
07-08 14:01:03.911  3804  3996 W ContactsProvider: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
07-08 14:01:03.911  3804  3996 W ContactsProvider: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
07-08 14:01:03.911  3804  3996 W ContactsProvider: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
07-08 14:01:03.911  3804  3996 W ContactsProvider: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:557)
07-08 14:01:03.911  3804  3996 W ContactsProvider: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:461)
07-08 14:01:03.911  3804  3996 W ContactsProvider: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:391)
07-08 14:01:03.911  3804  3996 W ContactsProvider: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
07-08 14:01:03.911  3804  3996 W ContactsProvider: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2162)
07-08 14:01:03.911  3804  3996 W ContactsProvider: 	at com.android.providers.contacts.HtcContactsProvider2.performBackgroundTask(HtcContactsProvider2.java:11533)
07-08 14:01:03.911  3804  3996 W ContactsProvider: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1819)
07-08 14:01:03.911  3804  3996 W ContactsProvider: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:01:03.911  3804  3996 W ContactsProvider: 	at android.os.Looper.loop(Looper.java:155)
07-08 14:01:03.911  3804  3996 W ContactsProvider: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-08 14:01:03.931  3526  4160 I ContextualWidget: MFU.onDataSetChanged
07-08 14:01:03.931  3526  4160 I ContextualWidget: handleMessage, what=1001 mode=GettingOut maxcount=8
,07-08 14:01:03.931  3526  4160 I ContextualWidget: updateMFULaunchCountIfNeeded update=false days=0
07-08 14:01:03.931  3526  4160 I ContextualWidget: Download enabled: true, Recommend enabled: true
07-08 14:01:03.931  3526  4160 I ContextualWidget: sync all data, download=1 recommend=4
,07-08 14:01:03.931  1116  3324 D PMS     : releaseWL(62533b8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
07-08 14:01:03.931  3526  4160 I ContextualWidget: sync all data, mode=GettingOut count=9
07-08 14:01:03.931  3526  4160 I ContextualWidget: notifyDataChanged, list size 8
07-08 14:01:03.931  3526  3526 I HtcContextualWidgetDataManager: onDataChanged: GettingOut, item count: 8, original: 8, first add: false,
07-08 14:01:03.931  3526  3899 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/com.htc.launcher.prefs.contextualwidget.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/com.htc.launcher.prefs.contextualwidget.xml.bak
,07-08 14:01:03.931  1116  1138 D PMS     : acquireWL(3b01f282): PARTIAL_WAKE_LOCK  AsyncService 0x1 8939 10126 null,
07-08 14:01:03.941  1116  3473 D PMS     : releaseWL(3b01f282): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,07-08 14:01:03.951  6366  8996 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,07-08 14:01:03.961  6637  9108 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
07-08 14:01:03.961  6637  9108 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
07-08 14:01:03.961  6637  9108 W HTCLOG  : mask=0x18
07-08 14:01:03.961  6637  9108 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle: 0x55bbc789a0,
,07-08 14:01:03.971  6637  9108 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml,
,07-08 14:01:03.971  3526  9107 I ContextualWidget: com.test.thalitest is not installed
07-08 14:01:03.981  3526  9107 W MFUDataManager: loadDownloadItems - skip DownloadItem: ApplicationInfo(id=-1, title=null, componentNameComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity} appsContainer=<ALLAPPS> P=UserHandle{0})
,07-08 14:01:03.981  3526  9107 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM contextualdownload WHERE component_name=?] disk I/O error
,07-08 14:01:03.981  6637  9108 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
07-08 14:01:03.981  6637  9108 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 6637
07-08 14:01:03.981  6637  9108 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-08 14:01:03.981  6637  9108 E AndroidRuntime: 	,at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
07-08 14:01:03.981  6637  9108 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
07-08 14:01:03.981  6637  9108 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
07-08 14:01:03.981  6637  9108 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
07-08 14:01:03.981  6637  9108 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:557)
07-08 14:01:03.981  6637  9108 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:461)
07-08 14:01:03.981  6637  9108 E AndroidRuntime: 	at com.google.android.search.core.icingsync.b.d(ApplicationsHelper.java:193)
07-08 14:01:03.981  6637  9108 E AndroidRuntime: 	at com.google.android.search.core.icingsync.ar.g(InternalIcingCorporaProvider.java:548)
07-08 14:01:03.981  6637  9108 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:282)
07-08 14:01:03.981  6637  9108 E AndroidRuntime: 	,at android.content.ContentProvider$Transport.update(ContentProvider.java:338)
07-08 14:01:03.981  6637  9108 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1398)
07-08 14:01:03.981  6637  9108 E AndroidRuntime: 	at com.google.android.search.core.icingsync.ba.Zh(UpdateIcingCorporaService.java:358)
07-08 14:01:03.981  6637  9108 E AndroidRuntime: 	at com.google.android.search.core.icingsync.bc.Zj(UpdateIcingCorporaService.java:297)
07-08 14:01:03.981  6637  9108 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:270),
07-08 14:01:03.981  6637  9108 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ac(UpdateIcingCorporaService.java:194)
07-08 14:01:03.981  6637  9108 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:182)
07-08 14:01:03.981  6637  9108 E AndroidRuntime: ,	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-08 14:01:03.981  6637  9108 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:01:03.981  6637  9108 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
07-08 14:01:03.981  6637  9108 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-08 14:01:03.981  3526  9107 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
07-08 14:01:03.981  1116  9113 E DropBoxManagerService: Can't write: system_app_crash
07-08 14:01:03.981  1116  9113 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system),
07-08 14:01:03.981  1116  9113 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-08 14:01:03.981  1116  9113 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-08 14:01:03.981  1116  9113 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-08 14:01:03.981  1116  9113 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
07-08 14:01:03.981  1116  9113 E DropBoxManagerService: ,	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-08 14:01:03.981  1116  9113 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
07-08 14:01:03.981  1116  9113 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-08 14:01:03.981  1116  9113 E DropBoxManagerService: 	,at libcore.io.Posix.open(Native Method)
07-08 14:01:03.981  1116  9113 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-08 14:01:03.981  1116  9113 E DropBoxManagerService: ,	at libcore.io.IoBridge.open(IoBridge.java:442)
07-08 14:01:03.981  1116  9113 E DropBoxManagerService: 	... 5 more
07-08 14:01:03.981  3526  9107 W HTCLOG  : mask=0x18
07-08 14:01:03.981  3526  9107 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.htc.launcher/databases/launcher.db, handle: 0xabf64a40,
07-08 14:01:03.981  3526  9107 E AndroidRuntime: FATAL EXCEPTION: IntentService[HtcContextualWidgetService]
07-08 14:01:03.981  3526  9107 E AndroidRuntime: Process: com.htc.launcher, PID: 3526
07-08 14:01:03.981  3526  9107 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-08 14:01:03.981  3526  9107 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-08 14:01:03.981  3526  9107 E AndroidRuntime: ,	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
07-08 14:01:03.981  3526  9107 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-08 14:01:03.981  3526  9107 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-08 14:01:03.981  3526  9107 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
07-08 14:01:03.981  3526  9107 E AndroidRuntime: 	at com.htc.launcher.LauncherProvider.delete(LauncherProvider.java:377),
07-08 14:01:03.981  3526  9107 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
07-08 14:01:03.981  3526  9107 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
07-08 14:01:03.981  3526  9107 E AndroidRuntime: 	at com.htc.launcher.htcwidget.MFUDataManager$DownloadManager.loadDownloadItems(MFUDataManager.java:2463)
07-08 14:01:03.981  3526  9107 E AndroidRuntime: 	at com.htc.launcher.htcwidget.MFUDataManager$DownloadManager.getDownloadList(MFUDataManager.java:2228)
07-08 14:01:03.981  3526  9107 E AndroidRuntime: ,	at com.htc.launcher.htcwidget.MFUDataManager.getDownloadList(MFUDataManager.java:2142)
07-08 14:01:03.981  3526  9107 E AndroidRuntime: 	at com.htc.launcher.htcwidget.MFUDataManager.getDownloadList(MFUDataManager.java:2129)
07-08 14:01:03.981  3526  9107 E AndroidRuntime: 	at com.htc.launcher.htcwidget.HtcContextualWidgetService.handlePackageChanged(HtcContextualWidgetService.java:304)
07-08 14:01:03.981  3526  9107 E AndroidRuntime: 	at com.htc.launcher.htcwidget.HtcContextualWidgetService.onHandleIntent(HtcContextualWidgetService.java:186)
07-08 14:01:03.981  3526  9107 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-08 14:01:03.981  3526  9107 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:01:03.981  3526  9107 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
07-08 14:01:03.981  3526  9107 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-08 14:01:03.981  1116  3473 E ActivityManager: App crashed! Process: com.google.android.googlequicksearchbox:search
07-08 14:01:03.991  6366  6690 W FileUtils: Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
07-08 14:01:03.981  6366  8996 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
07-08 14:01:03.981  1116  3543 E ActivityManager: App crashed! Process: com.htc.launcher
07-08 14:01:03.991  6366  6690 E IcingInternalCorpora: Failed to open Apps corpus file.
07-08 14:01:03.991  6366  6690 E IcingInternalCorpora: Failed to append to component name file.
07-08 14:01:03.991  6366  6690 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml to backup file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml.bak
07-08 14:01:04.001  1116  3543 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
,07-08 14:01:04.001  1116  3543 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
07-08 14:01:04.001  1116  3543 W ActivityManager:   Force finishing activity 1 com.htc.launcher/.Launcher
07-08 14:01:04.001  1116  3543 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-08 14:01:04.001  1116  3543 D PMS     : acquireWL(2db8183): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 1116 1000 null
07-08 14:01:04.001  1116  3543 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-08 14:01:04.001  1116  3543 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-08 14:01:04.001  1116  3543 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-08 14:01:04.001  1116  3543 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
07-08 14:01:04.001  1116  3543 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
07-08 14:01:04.001  1116  3543 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
,07-08 14:01:04.001  1116  3543 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
07-08 14:01:04.011  1116  9115 E ErrorReport: HtcErrorReportManager.Error in dumping error information
07-08 14:01:04.011  1116  9115 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_HOME_RESTART@1467979264015.dbox_tmp: open failed: EROFS (Read-only file system)
07-08 14:01:04.011  1116  9115 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-08 14:01:04.011  1116  9115 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-08 14:01:04.011  1116  9115 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-08 14:01:04.011  1116  9115 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
07-08 14:01:04.011  1116  9115 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
07-08 14:01:04.011  1116  9115 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-08 14:01:04.011  1116  9115 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
07-08 14:01:04.011  1116  9115 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-08 14:01:04.011  1116  9115 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-08 14:01:04.011  1116  9115 E ErrorReport: 	... 4 more
07-08 14:01:04.001  1116  3543 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
07-08 14:01:04.001  1116  3543 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
,07-08 14:01:04.001  1116  3543 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
07-08 14:01:04.001  1116  3543 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
07-08 14:01:04.001  1116  3543 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
07-08 14:01:04.001  1116  3543 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
07-08 14:01:04.001  1116  3543 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
07-08 14:01:04.001  1116  3543 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-08 14:01:04.001  1116  3543 W System.err: 	at libcore.io.Posix.open(Native Method)
07-08 14:01:04.001  1116  3543 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-08 14:01:04.001  1116  3543 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-08 14:01:04.001  1116  3543 W System.err: 	... 14 more
07-08 14:01:04.001  1116  3543 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
07-08 14:01:04.001  1116  3543 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
,07-08 14:01:04.001  1116  3543 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-08 14:01:04.001  1116  3543 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-08 14:01:04.001  1116  3543 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
,07-08 14:01:04.001  1116  3543 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
07-08 14:01:04.001  1116  3543 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
07-08 14:01:04.001  1116  3543 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
07-08 14:01:04.001  1116  3543 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
07-08 14:01:04.001  1116  3543 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
,07-08 14:01:04.001  1116  3543 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
07-08 14:01:04.001  1116  3543 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
07-08 14:01:04.001  1116  3543 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
07-08 14:01:04.001  1116  3543 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
07-08 14:01:04.001  1116  3543 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
07-08 14:01:04.001  1116  3543 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
07-08 14:01:04.001  1116  3543 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
,07-08 14:01:04.001  1116  3543 W System.err: 	at libcore.io.Posix.open(Native Method)
07-08 14:01:04.001  1116  3543 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-08 14:01:04.001  1116  3543 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-08 14:01:04.001  1116  3543 W System.err: 	... 14 more
07-08 14:01:04.011  1116  3625 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
07-08 14:01:04.011  1116  3625 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-08 14:01:04.011  1116  3625 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-08 14:01:04.011  1116  3625 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-08 14:01:04.011  1116  3625 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-08 14:01:04.011  1116  3625 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
07-08 14:01:04.011  1116  3625 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
07-08 14:01:04.011  1116  3625 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
07-08 14:01:04.011  1116  3625 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
07-08 14:01:04.011  1116  3625 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
07-08 14:01:04.011  1116  3625 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
07-08 14:01:04.011  1116  3625 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:01:04.011  1116  3625 W System.err: 	at android.os.Looper.loop(Looper.java:155)
07-08 14:01:04.011  1116  3625 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-08 14:01:04.011  1116  3625 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-08 14:01:04.011  1116  3625 W System.err: 	at libcore.io.Posix.open(Native Method)
07-08 14:01:04.011  1116  3625 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-08 14:01:04.011  1116  3625 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-08 14:01:04.011  1116  3625 W System.err: 	... 12 more
07-08 14:01:04.011  6366  6680 I Icing   : updateResources: need to parse owf{com.google.android.gms}
07-08 14:01:04.011  4336  9117 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,07-08 14:01:04.031  3526  3526 I FeedHostManager: [onPause]
07-08 14:01:04.031  3526  3526 I FeedProviderManager: onPause
07-08 14:01:04.031  3526  3526 I FeedHostManager: [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@e0e6819
07-08 14:01:04.031  3526  4944 I SocialFeedProvider: +onPause
07-08 14:01:04.031  3526  4944 I SocialFeedProvider: -onPause
,07-08 14:01:04.031  3526  3526 I ContextualWidget: onPause
07-08 14:01:04.031  3526  3526 I ContextualWidget: notifyWidgetDeactive
,07-08 14:01:04.041  4336  4336 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/ns.db'.
07-08 14:01:04.041  4336  4336 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-08 14:01:04.041  4336  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-08 14:01:04.041  4336  4336 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-08 14:01:04.041  4336  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-08 14:01:04.041  4336  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-08 14:01:04.041  4336  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-08 14:01:04.041  4336  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-08 14:01:04.041  4336  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-08 14:01:04.041  4336  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-08 14:01:04.041  4336  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-08 14:01:04.041  4336  4336 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-08 14:01:04.041  4336  4336 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1275)
07-08 14:01:04.041  4336  4336 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:262)
07-08 14:01:04.041  4336  4336 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:262)
07-08 14:01:04.041  4336  4336 E SQLiteDatabase: 	at irl.c(:com.google.android.gms:216)
07-08 14:01:04.041  4336  4336 E SQLiteDatabase: 	at irl.d(:com.google.android.gms:187)
07-08 14:01:04.041  4336  4336 E SQLiteDatabase: 	at irg.a(:com.google.android.gms:22519)
07-08 14:01:04.041  4336  4336 E SQLiteDatabase: 	at obo.b(:com.google.android.gms:335)
07-08 14:01:04.041  4336  4336 E SQLiteDatabase: 	at obl.a(:com.google.android.gms:479)
07-08 14:01:04.041  4336  4336 E SQLiteDatabase: 	at obl.a(:com.google.android.gms:462)
07-08 14:01:04.041  4336  4336 E SQLiteDatabase: 	at com.google.android.gms.gcm.nts.SchedulerChimeraReceiver.onReceive(:com.google.android.gms:12258)
07-08 14:01:04.041  4336  4336 E SQLiteDatabase: 	at com.google.android.chimera.container.BroadcastReceiverProxy.onReceive(:com.google.android.gms:114)
07-08 14:01:04.041  4336  4336 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
07-08 14:01:04.041  4336  4336 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
07-08 14:01:04.041  4336  4336 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
07-08 14:01:04.041  4336  4336 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:01:04.041  4336  4336 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
,07-08 14:01:04.041  4336  4336 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
07-08 14:01:04.041  4336  4336 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-08 14:01:04.041  4336  4336 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-08 14:01:04.041  4336  4336 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
07-08 14:01:04.041  4336  4336 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
07-08 14:01:04.051  1116  3475 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.htc.launcher/.Launcher} from uid 0 pid 0 on display 0
,07-08 14:01:04.081  1116  3475 V WindowManager: addAppToken: AppWindowToken{4c2e56 token=Token{3934e071 ActivityRecord{1804ee18 u0 com.htc.launcher/.Launcher t123}}} to stack=0 task=123 at 0
,07-08 14:01:04.091  1116  3625 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
,07-08 14:01:04.091  3526  3526 D HtcThemeUtils: Unregister com.htc.launcher.util.HtcWrapConfigurationActivity$2@edd4871 for type 0
07-08 14:01:04.091  3526  3526 D HtcThemeUtils: Unregister com.htc.launcher.util.HtcWrapConfigurationActivity$2@edd4871 for type 1
07-08 14:01:04.091  3526  3526 D HtcThemeUtils: Unregister com.htc.launcher.util.HtcWrapConfigurationActivity$2@edd4871 for type 3
07-08 14:01:04.091  3526  3526 D HtcThemeUtils: Unregister com.htc.launcher.util.HtcWrapConfigurationActivity$2@edd4871 for type 2
,07-08 14:01:04.101  3526  3526 I OrientationManager: [release]
,07-08 14:01:04.101  3526  3526 I PagedView: IndicatorPagedView.nCapability with type count = 1 and capability = 20
,07-08 14:01:04.101  4336  4336 I GCore-Chimera-Crash: Cg0KB3ZJbmZyYTQQor84Gl8KHWNvbS5nb29nbGUuYW5kcm9pZC
07-08 14:01:04.101  4336  4336 I GCore-Chimera-Crash: 5wbGF5LmdhbWVzEhQzLjcuMjMgKDI4Njc2MzctMDQ4KRjgq-AR
07-08 14:01:04.101  4336  4336 I GCore-Chimera-Crash: IiMKHGNvbS5nb29nbGUuYW5kcm9pZC5nbXMuZ2FtZXMQsKvgEQ
07-08 14:01:04.101  4336  4336 I GCore-Chimera-Crash: ==
07-08 14:01:04.101  4336  4336 I GCore-Chimera-Crash: GCore-Chimera-Crash
,07-08 14:01:04.101  4336  4336 E AndroidRuntime: FATAL EXCEPTION: main
07-08 14:01:04.101  4336  4336 E AndroidRuntime: Process: com.google.android.gms.persistent, PID: 4336
07-08 14:01:04.101  4336  4336 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.nts.SchedulerReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-08 14:01:04.101  4336  4336 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2733)
07-08 14:01:04.101  4336  4336 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
07-08 14:01:04.101  4336  4336 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
07-08 14:01:04.101  4336  4336 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:01:04.101  4336  4336 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
07-08 14:01:04.101  4336  4336 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
07-08 14:01:04.101  4336  4336 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-08 14:01:04.101  4336  4336 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-08 14:01:04.101  4336  4336 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
07-08 14:01:04.101  4336  4336 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
07-08 14:01:04.101  4336  4336 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-08 14:01:04.101  4336  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-08 14:01:04.101  4336  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-08 14:01:04.101  4336  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-08 14:01:04.101  4336  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-08 14:01:04.101  4336  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-08 14:01:04.101  4336  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-08 14:01:04.101  4336  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-08 14:01:04.101  4336  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-08 14:01:04.101  4336  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-08 14:01:04.101  4336  4336 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-08 14:01:04.101  4336  4336 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1275)
07-08 14:01:04.101  4336  4336 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:262)
07-08 14:01:04.101  4336  4336 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:262)
07-08 14:01:04.101  4336  4336 E AndroidRuntime: 	at irl.c(:com.google.android.gms:216)
07-08 14:01:04.101  4336  4336 E AndroidRuntime: 	at irl.d(:com.google.android.gms:187)
07-08 14:01:04.101  4336  4336 E AndroidRuntime: 	at irg.a(:com.google.android.gms:22519)
07-08 14:01:04.101  4336  4336 E AndroidRuntime: 	at obo.b(:com.google.android.gms:335)
07-08 14:01:04.101  4336  4336 E AndroidRuntime: 	at obl.a(:com.google.android.gms:479)
07-08 14:01:04.101  4336  4336 E AndroidRuntime: 	at obl.a(:com.google.android.gms:462)
07-08 14:01:04.101  4336  4336 E AndroidRuntime: 	at com.google.android.gms.gcm.nts.SchedulerChimeraReceiver.onReceive(:com.google.a,ndroid.gms:12258)
07-08 14:01:04.101  4336  4336 E AndroidRuntime: 	at com.google.android.chimera.container.BroadcastReceiverProxy.onReceive(:com.google.android.gms:114)
07-08 14:01:04.101  4336  4336 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
07-08 14:01:04.101  4336  4336 E AndroidRuntime: 	... 9 more
07-08 14:01:04.101  1116  3946 E ActivityManager: App crashed! Process: com.google.android.gms.persistent
07-08 14:01:04.111  3526  3526 I ContextualWidget: onDestroy
07-08 14:01:04.111  3526  4160 I ContextualWidget: handleMessage, what=1030 mode=GettingOut maxcount=8
07-08 14:01:04.111  3526  4160 I ContextualWidget: release
07-08 14:01:04.111  1116  9118 E DropBoxManagerService: Can't write: system_app_crash
07-08 14:01:04.111  1116  9118 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
07-08 14:01:04.111  1116  9118 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-08 14:01:04.111  1116  9118 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-08 14:01:04.111  1116  9118 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-08 14:01:04.111  1116  9118 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
07-08 14:01:04.111  1116  9118 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-08 14:01:04.111  1116  9118 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
07-08 14:01:04.111  1116  9118 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-08 14:01:04.111  1116  9118 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-08 14:01:04.111  1116  9118 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-08 14:01:04.111  1116  9118 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-08 14:01:04.111  1116  9118 E DropBoxManagerService: 	... 5 more
,07-08 14:01:04.121  3526  3526 I ContextualWidget: new instance com.htc.launcher.htcwidget.HtcContextualWidgetController@3d491a1b
,07-08 14:01:04.121  3526  3526 I ContextualWidget: unlockModeChange
,07-08 14:01:04.121  3526  3526 I ContextualWidget: notifyWidgetDeactive
,07-08 14:01:04.151  1116  2987 I ActivityManager: Start proc 9120:com.htc.launcher:biclient/u0a59 for service com.htc.launcher/com.htc.BiLogClient.BiLogUploadService
,07-08 14:01:04.161  9120  9120 W HTCLOG  : use specified tag [FDManager], func [0].
07-08 14:01:04.161  9120  9120 W HTCLOG  : mask=0x18
,07-08 14:01:04.201  3122  3122 D WIFI_ICON: WifiActivity: 0
07-08 14:01:04.201  3122  3122 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 stat_sys_no_sim F]
,07-08 14:01:04.261   499   841 E qdhwcomposer: hwc_vsync_control: vsync control failed. Dpy=0, enable=0 : Cannot send after transport endpoint shutdown,
07-08 14:01:04.261   499   841 E SurfaceFlinger: eventControl(0, 0) failed Cannot send after transport endpoint shutdown
,07-08 14:01:04.321   499   499 E qdoverlay: Cant open device /dev/graphics/fb0 err=108,

```
