#### Test 75789268514fc25_thali06_HTC-HTC One M9 Logs


```
--------- beginning of main
07-15 15:20:25.493  6473  6473 D CmaSystemUpdateService: onStartCommand: intent: Intent { act=com.google.android.gms.update.START_SERVICE pkg=com.google.android.gms (has extras) }
--------- beginning of system
07-15 15:20:25.513  1112  3698 I ActivityManager: Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
07-15 15:20:25.523  6473  7941 I SystemUpdateTask: cancelUpdate (empty URL)
07-15 15:20:25.523  6473  7941 I CmaSystemUpdateService: active receiver: disabled
07-15 15:20:25.533  6473  7941 D ChimeraResource: Successfully parsed resource with package name: com.google.android.gms and resource name drawable/notification_system_update_available
07-15 15:20:25.533  1112  3698 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateServiceActiveReceiver, state=2, flag=1, pid=6473, uid=10020, userID:0
07-15 15:20:25.533  1112  3247 I ActivityManager: Resuming delayed broadcast
07-15 15:20:25.543  6473  7941 D ChimeraResource: Successfully parsed resource with package name: com.google.android.gms and resource name drawable/notification_system_update_download_failure
07-15 15:20:25.563  7846  7883 I Babel_RequestWriter: error sending REQ[fc:5; creat:1468588807869; type:bme-149932641: userphotoalbums
07-15 15:20:25.563  7846  7883 I Babel_RequestWriter: ProtoBuf:
07-15 15:20:25.563  7846  7883 I Babel_RequestWriter: null
07-15 15:20:25.563  7846  7883 I Babel_RequestWriter: Creation stack:
07-15 15:20:25.563  7846  7883 I Babel_RequestWriter: java.lang.Throwable
07-15 15:20:25.563  7846  7883 I Babel_RequestWriter: 	at bng.<init>(SourceFile:300)
07-15 15:20:25.563  7846  7883 I Babel_RequestWriter: 	at bnw.<init>(SourceFile:443)
07-15 15:20:25.563  7846  7883 I Babel_RequestWriter: 	at bma.<init>(SourceFile:50)
07-15 15:20:25.563  7846  7883 I Babel_RequestWriter: 	at bme.<init>(SourceFile:344)
07-15 15:20:25.563  7846  7883 I Babel_RequestWriter: 	at bvf.a(SourceFile:26)
07-15 15:20:25.563  7846  7883 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.a(SourceFile:5093)
07-15 15:20:25.563  7846  7883 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.g(SourceFile:4568)
07-15 15:20:25.563  7846  7883 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.a(SourceFile:887)
07-15 15:20:25.563  7846  7883 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.onHandleIntent(SourceFile:766)
07-15 15:20:25.563  7846  7883 I Babel_RequestWriter: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-15 15:20:25.563  7846  7883 I Babel_RequestWriter: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-15 15:20:25.563  7846  7883 I Babel_RequestWriter: 	at android.os.Looper.loop(Looper.java:155)
07-15 15:20:25.563  7846  7883 I Babel_RequestWriter: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-15 15:20:25.563  7846  7883 I Babel_RequestWriter: 
07-15 15:20:25.563  7846  7883 I Babel_RequestWriter: Origin stack:
07-15 15:20:25.563  7846  7883 I Babel_RequestWriter: java.lang.Throwable
07-15 15:20:25.563  7846  7883 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.e(SourceFile:1157)
07-15 15:20:25.563  7846  7883 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.f(SourceFile:3214)
07-15 15:20:25.563  7846  7883 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.s(SourceFile:2980)
07-15 15:20:25.563  7846  7883 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.stickers.StickersModule.a(SourceFile:132)
07-15 15:20:25.563  7846  7883 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.stickers.StickersModule.v_(SourceFile:105)
07-15 15:20:25.563  7846  7883 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.phone.EsApplication.onCreate(SourceFile:566)
07-15 15:20:25.563  7846  7883 I Babel_RequestWriter: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1025)
07-15 15:20:25.563  7846  7883 I Babel_RequestWriter: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4959)
07-15 15:20:25.563  7846  7883 I Babel_RequestWriter: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
07-15 15:20:25.563  7846  7883 I Babel_RequestWriter: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
07-15 15:20:25.563  7846  7883 I Babel_RequestWriter: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-15 15:20:25.563  7846  7883 I Babel_RequestWriter: 	at android.os.Looper.loop(Looper.java:155)
07-15 15:20:25.563  7846  7883 I Babel_RequestWriter: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
07-15 15:20:25.563  7846  7883 I Babel_RequestWriter: 	at java.lang.reflect.Method.invoke(Native Method)
07-15 15:20:25.563  7846  7883 I Babel_RequestWriter: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-15 15:20:25.563  7846  7883 I Babel_RequestWriter: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
07-15 15:20:25.563  7846  7883 I Babel_RequestWriter: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
07-15 15:20:25.563  7846  7883 I Babel_RequestWriter: ]; took 0 ms (error code == 101)
,07-15 15:20:25.573  1112  3824 I ActivityManager: Delay finish: com.google.android.gms/.security.snet.SnetReceiver
07-15 15:20:25.573  1112  1133 D PMS     : releaseWL(14e0805d): PARTIAL_WAKE_LOCK  CmaSystemUpdateService 0x1 WorkSource{10020 com.google.android.gms}
07-15 15:20:25.583  6473  6473 D CmaSystemUpdateService: onDestroy
07-15 15:20:25.613  1112  3698 I ActivityManager: Resuming delayed broadcast
07-15 15:20:25.623  4261  7948 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
07-15 15:20:25.663  1112  3642 D PMS     : acquireWL(1de718b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4261 10020 WorkSource{10020 com.google.android.gms}
07-15 15:20:25.693  1112  3438 D PMS     : releaseWL(1de718b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10020 com.google.android.gms}
07-15 15:20:25.693  7846  7894 I Babel_RequestWriter: error sending REQ[fc:1; creat:1468588824577; type:boc-340418213: devices/registerdevice
07-15 15:20:25.693  7846  7894 I Babel_RequestWriter: ProtoBuf:
07-15 15:20:25.693  7846  7894 I Babel_RequestWriter: null
07-15 15:20:25.693  7846  7894 I Babel_RequestWriter: Creation stack:
07-15 15:20:25.693  7846  7894 I Babel_RequestWriter: java.lang.Throwable
07-15 15:20:25.693  7846  7894 I Babel_RequestWriter: 	at bng.<init>(SourceFile:300)
07-15 15:20:25.693  7846  7894 I Babel_RequestWriter: 	at bnw.<init>(SourceFile:443)
07-15 15:20:25.693  7846  7894 I Babel_RequestWriter: 	at boc.<init>(SourceFile:2476)
07-15 15:20:25.693  7846  7894 I Babel_RequestWriter: 	at boc.a(SourceFile:2506)
07-15 15:20:25.693  7846  7894 I Babel_RequestWriter: 	at bxx.a(SourceFile:88)
07-15 15:20:25.693  7846  7894 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.a(SourceFile:5093)
07-15 15:20:25.693  7846  7894 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.g(SourceFile:3328)
07-15 15:20:25.693  7846  7894 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.a(SourceFile:887)
07-15 15:20:25.693  7846  7894 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.onHandleIntent(SourceFile:766)
07-15 15:20:25.693  7846  7894 I Babel_RequestWriter: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-15 15:20:25.693  7846  7894 I Babel_RequestWriter: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-15 15:20:25.693  7846  7894 I Babel_RequestWriter: 	at android.os.Looper.loop(Looper.java:155)
07-15 15:20:25.693  7846  7894 I Babel_RequestWriter: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-15 15:20:25.693  7846  7894 I Babel_RequestWriter: 
07-15 15:20:25.693  7846  7894 I Babel_RequestWriter: Origin stack:
07-15 15:20:25.693  7846  7894 I Babel_RequestWriter: java.lang.Throwable
07-15 15:20:25.693  7846  7894 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.e(SourceFile:1157)
07-15 15:20:25.693  7846  7894 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.a(SourceFile:1175)
07-15 15:20:25.693  7846  7894 I Babel_RequestWriter: 	at btp.b(SourceFile:1867)
07-15 15:20:25.693  7846  7894 I Babel_RequestWriter: 	at btl.u(SourceFile:1301)
07-15 15:20:25.693  7846  7894 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.a(SourceFile:829)
07-15 15:20:25.693  7846  7894 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.onHandleIntent(SourceFile:766)
07-15 15:20:25.693  7846  7894 I Babel_RequestWriter: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-15 15:20:25.693  7846  7894 I Babel_RequestWriter: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-15 15:20:25.693  7846  7894 I Babel_RequestWriter: 	at android.os.Looper.loop(Looper.java:155)
07-15 15:20:25.693  7846  7894 I Babel_RequestWriter: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-15 15:20:25.693  7846  7894 I Babel_RequestWriter: ]; took 0 ms (error code == 101)
07-15 15:20:25.713  1112  3940 D PMS     : acquireWL(3b3dc691): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4261 10020 WorkSource{10020 com.google.android.gms}
07-15 15:20:25.743  1112  3443 D PMS     : releaseWL(3b3dc691): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10020 com.google.android.gms}
07-15 15:20:25.773  1112  3247 D PMS     : acquireWL(30f3e9f6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4261 10020 WorkSource{10020 com.google.android.gms}
07-15 15:20:25.783  7949  7949 W HTCLOG  : use specified tag [AndroidRuntime], func [0].
07-15 15:20:25.783  7949  7949 W HTCLOG  : mask=0x18
07-15 15:20:25.793  3446  5207 I SocialFeedProvider: +disConnect socialManager
07-15 15:20:25.793  3446  5207 I SocialFeedProvider: disconnect socialManager
07-15 15:20:25.793  3446  5207 I SocialFeedProvider: -disConnect socialManager
07-15 15:20:25.803  1112  3824 D PMS     : releaseWL(30f3e9f6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10020 com.google.android.gms}
07-15 15:20:25.833  1112  3712 D PMS     : acquireWL(1367c1f7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4261 10020 WorkSource{10020 com.google.android.gms}
07-15 15:20:25.843  1112  2929 V AlarmManager: sending alarm PendingIntent{1c510864: PendingIntentRecord{20673acd com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=59101, Int=0
07-15 15:20:25.853  1112  3442 D PMS     : releaseWL(1367c1f7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10020 com.google.android.gms}
07-15 15:20:25.883  1112  3510 I ActivityManager: Start proc 7952:com.htc.calendar/u0a7 for broadcast com.htc.calendar/.ProviderChangeReceiver
07-15 15:20:25.893  7952  7952 W HTCLOG  : use specified tag [FDManager], func [0].
07-15 15:20:25.893  7952  7952 W HTCLOG  : mask=0x18
07-15 15:20:25.923  7952  7952 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
07-15 15:20:25.933  7952  7952 D CalendarApplication: onCreate
07-15 15:20:25.943  7952  7952 D ProviderChangeReceiver: ---------------------------------------------------
07-15 15:20:25.943  7952  7952 D ProviderChangeReceiver: ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
07-15 15:20:25.943  7952  7975 D HtcAlertService: start to updateAlertNotification!
07-15 15:20:25.943  7482  7482 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
07-15 15:20:25.963  7482  7976 I DFPI.ApkInstallService: onHandleIntent
07-15 15:20:25.963  7482  7976 I DFPI.ApkInstallService: Media Scan Finished Case 
07-15 15:20:25.963  7952  7975 D HtcAlertService: No fired or scheduled alerts
07-15 15:20:25.963  7952  7975 D HtcAlertUtils: -- cancelReminderNotification --
07-15 15:20:25.963  7592  7592 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
07-15 15:20:25.963  7952  7975 D HtcAlertUtils: broadcastExistReminder!
07-15 15:20:25.963  7482  7976 I DFPI.SystemPropertiesUtil: value = HTC__102
07-15 15:20:25.963  7482  7976 I DFPI.ApkInstallService: deviceCID = HTC__102
07-15 15:20:25.963  7482  7976 D DFPI.ApkInstallService: check CID = HTC__102
07-15 15:20:25.963  7482  7976 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
07-15 15:20:25.963  7592  7592 I SoundPicker: SoundPickerReceiver [onReceive] startService
07-15 15:20:25.973  1112  1133 I ActivityManager: Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
07-15 15:20:25.973  3175  3175 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
07-15 15:20:25.973  1112  3940 I ActivityManager: Resuming delayed broadcast
07-15 15:20:25.973  7592  7977 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
07-15 15:20:25.973  7592  7977 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
07-15 15:20:25.973  7592  7977 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
07-15 15:20:25.973  7592  7977 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-15 15:20:25.973  7592  7977 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/132 type=1
07-15 15:20:25.973  7592  7977 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/132
07-15 15:20:25.973  7592  7977 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-15 15:20:25.973  7592  7977 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/132 type=2
07-15 15:20:25.973  7592  7977 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/132
07-15 15:20:25.973  7592  7977 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-15 15:20:25.973  7592  7977 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/132 type=3
07-15 15:20:25.973  7592  7977 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/132
07-15 15:20:25.973  7592  7977 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-15 15:20:25.973  7592  7977 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/105 type=4
07-15 15:20:25.973  7592  7977 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/105
07-15 15:20:25.983  7592  7977 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-15 15:20:25.983  7592  7977 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/31 type=5
07-15 15:20:25.983  7592  7977 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/31
07-15 15:20:25.983  1112  3510 I ActivityManager: Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
07-15 15:20:25.983  7592  7977 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/103 type=6
07-15 15:20:25.983  7592  7977 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/103
07-15 15:20:25.983  7592  7977 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/109 type=7
07-15 15:20:25.983  7592  7977 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/109
07-15 15:20:25.983  7592  7977 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=8
07-15 15:20:25.983  7592  7977 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
07-15 15:20:25.983  7592  7977 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/105 type=9
07-15 15:20:25.983  7592  7977 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/105
07-15 15:20:25.983  1112  3442 I ActivityManager: Resuming delayed broadcast
07-15 15:20:25.993  3446  3866 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
07-15 15:20:25.993  3446  3866 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@3c5fe8ee +
07-15 15:20:25.993  3446  3866 I Prism.WidgetManager: onLoadItems() +
07-15 15:20:26.013  7482  7482 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
07-15 15:20:26.013  3446  3866 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
07-15 15:20:26.033  1112  2929 I ActivityManager: Start proc 7979:com.htc.sense.news/u0a59 for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper
07-15 15:20:26.033  1112  2929 V AlarmManager: sending alarm PendingIntent{2c9df685: PendingIntentRecord{103cacda com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1468588826018, Int=0
07-15 15:20:26.033  7979  7979 W HTCLOG  : use specified tag [FDManager], func [0].
07-15 15:20:26.033  1112  3510 I ActivityManager: Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
07-15 15:20:26.033  7979  7979 W HTCLOG  : mask=0x18
07-15 15:20:26.033  7482  7995 I DFPI.ApkInstallService: onHandleIntent
07-15 15:20:26.033  7482  7995 I DFPI.ApkInstallService: Media Scan Finished Case 
07-15 15:20:26.043  7482  7995 I DFPI.SystemPropertiesUtil: value = HTC__102
07-15 15:20:26.043  7482  7995 I DFPI.ApkInstallService: deviceCID = HTC__102
07-15 15:20:26.043  7482  7995 D DFPI.ApkInstallService: check CID = HTC__102
07-15 15:20:26.043  7482  7995 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
07-15 15:20:26.043  1112  3247 I ActivityManager: Resuming delayed broadcast
07-15 15:20:26.053   579   579 I art     : Explicit concurrent mark sweep GC freed 8673(369KB) AllocSpace objects, 0(0B) LOS objects, 97% free, 113KB/4MB, paused 203us total 19.235ms
07-15 15:20:26.053  7592  7592 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
07-15 15:20:26.063  7592  7592 I SoundPicker: SoundPickerReceiver [onReceive] startService
07-15 15:20:26.063  1112  3510 I ActivityManager: Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
07-15 15:20:26.063   579   579 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 97% free, 113KB/4MB, paused 195us total 14.701ms
07-15 15:20:26.073  7592  8001 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
07-15 15:20:26.073  7592  8001 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
07-15 15:20:26.073  7592  8001 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
07-15 15:20:26.073  7592  8001 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-15 15:20:26.073  7592  8001 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/132 type=1
07-15 15:20:26.073  7592  8001 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/132
07-15 15:20:26.073  7592  8001 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-15 15:20:26.073  7592  8001 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/132 type=2
07-15 15:20:26.073  7592  8001 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/132
07-15 15:20:26.073  7592  8001 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-15 15:20:26.073  7592  8001 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/132 type=3
07-15 15:20:26.073  7592  8001 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/132
07-15 15:20:26.073  7592  8001 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-15 15:20:26.083  7592  8001 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/105 type=4
07-15 15:20:26.083   579   579 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 97% free, 113KB/4MB, paused 209us total 14.505ms
07-15 15:20:26.083  7592  8001 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/105
07-15 15:20:26.083  7592  8001 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-15 15:20:26.083  7592  8001 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/31 type=5
07-15 15:20:26.083  1112  3438 I ActivityManager: Resuming delayed broadcast
07-15 15:20:26.083  7592  8001 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/31
07-15 15:20:26.083  7592  8001 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/103 type=6
07-15 15:20:26.083  7592  8001 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/103
07-15 15:20:26.083  7592  8001 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/109 type=7
07-15 15:20:26.083  7592  8001 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/109
07-15 15:20:26.083  7592  8001 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=8
07-15 15:20:26.083  7592  8001 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
07-15 15:20:26.083  7592  8001 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/105 type=9
07-15 15:20:26.083  7979  7979 I MultiDex: VM with version 2.1.0 has multidex support
07-15 15:20:26.083  7592  8001 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/105
07-15 15:20:26.083  7979  7979 I MultiDex: install
07-15 15:20:26.083  7979  7979 I MultiDex: VM has multidex support, MultiDex support library is disabled.
07-15 15:20:26.103  7949  8006 W HTCLOG  : use specified tag [cutils-trace], func [0].
07-15 15:20:26.103  7482  7482 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
07-15 15:20:26.103  7949  8006 W HTCLOG  : mask=0x18
07-15 15:20:26.103  7949  8006 E cutils-trace: Error opening trace file: Permission denied (13)
07-15 15:20:26.103  1112  3443 I ActivityManager: Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
07-15 15:20:26.103  7482  8012 I DFPI.ApkInstallService: onHandleIntent
07-15 15:20:26.113  7482  8012 I DFPI.ApkInstallService: Media Scan Finished Case 
07-15 15:20:26.113  7482  8012 I DFPI.SystemPropertiesUtil: value = HTC__102
07-15 15:20:26.113  1112  3824 I ActivityManager: Resuming delayed broadcast
07-15 15:20:26.113  7482  8012 I DFPI.ApkInstallService: deviceCID = HTC__102
07-15 15:20:26.113  7482  8012 D DFPI.ApkInstallService: check CID = HTC__102
07-15 15:20:26.113  7482  8012 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
07-15 15:20:26.113  7979  8013 I SocialManager[SocialBiLogHelper]: action: com.htc.sense.hsp.HANDLE_ULOG
07-15 15:20:26.113  7979  8013 I SocialManager[SocialBiLogHelper]: last commit ulog time 1468558947857
07-15 15:20:26.113  7979  8013 I SocialManager[SocialBiLogHelper]: skip commit this time
07-15 15:20:26.113  1112  3940 D Process : killProcessQuiet, pid=7458
07-15 15:20:26.113  1112  3940 I ActivityManager: Killing 7458:com.google.android.partnersetup/u0a23 (adj 15): empty #17
07-15 15:20:26.113  1112  3940 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19304 
07-15 15:20:26.123  7384  7978 I MediaStoreImporter: Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
07-15 15:20:26.123  1112  3510 I ActivityManager: Recipient 7458
07-15 15:20:26.163  7949  7949 D CustomizationManager: ====startRecUseTime====
07-15 15:20:26.173  7949  7949 D htc.customization.log.level:  is 
07-15 15:20:26.173  7949  7949 W CustomizationLogLevel: Level value is invalid, use default level 2
07-15 15:20:26.193  3446  3866 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-15 15:20:26.223  7949  7949 D CustomizationManager:  Read ACC file spent 0.025 (s)
07-15 15:20:26.223  7949  7949 D CIDMapFileReader: Parsing tag item name = HTC__001
07-15 15:20:26.223  7949  7949 D CIDMapFileReader: Parsing tag item name = HTC__002
07-15 15:20:26.223  7949  7949 D CIDMapFileReader: Parsing tag item name = HTC__016
07-15 15:20:26.223  7949  7949 D CIDMapFileReader: Parsing tag item name = HTC__031
07-15 15:20:26.223  7949  7949 D CIDMapFileReader: Parsing tag item name = HTC__032
07-15 15:20:26.223  7949  7949 D CIDMapFileReader: Parsing tag item name = HTC__102
07-15 15:20:26.223  7949  7949 D CIDMapFileReader: Parsing tag item name = HTC__A07
07-15 15:20:26.223  7949  7949 D CIDMapFileReader: Parsing tag item name = HTC__J15
07-15 15:20:26.223  7949  7949 D CIDMapFileReader: Parsing tag item name = HTC__M27
07-15 15:20:26.223  7949  7949 D CIDMapFileReader: Parsing tag item name = HTC__Y13
07-15 15:20:26.223  7949  7949 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__102.xml
07-15 15:20:26.223  7949  7949 I CustomizationCIDLoader: Parsing tag category name = application
07-15 15:20:26.223  7949  7949 I CustomizationCIDLoader: Parsing tag category name = system
07-15 15:20:26.223  7949  7949 I CustomizationCIDLoader: Parsing tag category name = Settings
07-15 15:20:26.223  7949  7949 I CustomizationCIDLoader: Parsing tag category name = ACC
07-15 15:20:26.223  7949  7949 I CustomizationCIDLoader: add string-array item, value = 42507
07-15 15:20:26.223  7949  7949 I CustomizationCIDLoader: add string-array item, value = 21902
07-15 15:20:26.223  7949  7949 I CustomizationCIDLoader: add string-array item, value = 26006:26001.26002.26003
07-15 15:20:26.223  7949  7949 I CustomizationCIDLoader: add string-array item, value = 23420
07-15 15:20:26.223  7949  7949 I CustomizationCIDLoader: add string-array item, value = 22299
07-15 15:20:26.223  7949  7949 I CustomizationCIDLoader: add string-array item, value = 24002
07-15 15:20:26.223  7949  7949 I CustomizationCIDLoader: add string-array item, value = 23210
07-15 15:20:26.223  7949  7949 I CustomizationCIDLoader: add string-array item, value = 23205
07-15 15:20:26.223  7949  7949 I CustomizationCIDLoader: add string-array item, value = 23806
07-15 15:20:26.223  7949  7949 I CustomizationCIDLoader: add string-array item, value = 23430
07-15 15:20:26.223  7949  7949 I CustomizationCIDLoader: add string-array item, value = 23408
07-15 15:20:26.223  7949  7949 I CustomizationCIDLoader: add string-array item, value = 27205
07-15 15:20:26.223  7949  7949 I CustomizationCIDLoader: add string-array item, value = 27202:27205
07-15 15:20:26.223  7949  7949 I CustomizationCIDLoader: add string-array item, value = 27216:27202.27205
07-15 15:20:26.223  7949  7949 I CustomizationCIDLoader: add string-array item, value = 42507:C:1:0
07-15 15:20:26.223  7949  7949 I CustomizationCIDLoader: add string-array item, value = 21902:C:1:0
07-15 15:20:26.223  7949  7949 I CustomizationCIDLoader: add string-array item, value = 26006:D:1:0
07-15 15:20:26.223  7949  7949 I CustomizationCIDLoader: add string-array item, value = 23420:D:0:0
07-15 15:20:26.223  7949  7949 I CustomizationCIDLoader: add string-array item, value = 27205:C:1:0
07-15 15:20:26.223  7949  7949 I CustomizationCIDLoader: add string-array item, value = 22299:D:0:0
07-15 15:20:26.223  7949  7949 I CustomizationCIDLoader: add string-array item, value = 24002:D:0:0
07-15 15:20:26.223  7949  7949 I CustomizationCIDLoader: add string-array item, value = 23210:D:2:0
07-15 15:20:26.223  7949  7949 I CustomizationCIDLoader: add string-array item, value = 23205:D:2:0
07-15 15:20:26.223  7949  7949 I CustomizationCIDLoader: add string-array item, value = 23806:D:0:0
07-15 15:20:26.233  1112  3824 I ActivityManager: Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
07-15 15:20:26.223  7949  7949 I CustomizationCIDLoader: add string-array item, value = 23430:C:1:0
07-15 15:20:26.223  7949  7949 I CustomizationCIDLoader: add string-array item, value = 23408:C:1:0
07-15 15:20:26.223  7949  7949 I CustomizationCIDLoader: add string-array item, value = 27202:C:1:0
07-15 15:20:26.223  7949  7949 I CustomizationCIDLoader: add string-array item, value = 27216:C:1:0
07-15 15:20:26.223  7949  7949 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
07-15 15:20:26.223  7949  7949 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
07-15 15:20:26.223  7949  7949 I CustomizationCIDLoader: Parsing tag category name = AudioService
07-15 15:20:26.223  7949  7949 D CustomizationManager:  Read CID file spent 0.055 (s)
07-15 15:20:26.223  7949  7949 D CustomizationManager:  All configurations done spent 0.055 (s)
07-15 15:20:26.233  7592  7592 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
07-15 15:20:26.233  7592  7592 I SoundPicker: SoundPickerReceiver [onReceive] startService
07-15 15:20:26.233  7592  8022 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
07-15 15:20:26.233  7592  8022 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
07-15 15:20:26.233  7592  8022 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
07-15 15:20:26.233  7592  8022 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-15 15:20:26.233  7592  8022 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/132 type=1
07-15 15:20:26.233  7592  8022 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/132
07-15 15:20:26.233  7592  8022 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-15 15:20:26.233  7592  8022 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/132 type=2
07-15 15:20:26.233  1112  3698 I ActivityManager: Resuming delayed broadcast
07-15 15:20:26.233  7592  8022 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/132
07-15 15:20:26.233  7592  8022 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-15 15:20:26.233  7592  8022 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/132 type=3
07-15 15:20:26.233  7592  8022 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/132
07-15 15:20:26.233  7592  8022 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-15 15:20:26.233  7592  8022 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/105 type=4
07-15 15:20:26.233  7592  8022 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/105
07-15 15:20:26.233  7592  8022 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-15 15:20:26.233  7592  8022 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/31 type=5
07-15 15:20:26.233  7592  8022 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/31
07-15 15:20:26.233  7592  8022 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/103 type=6
07-15 15:20:26.233  7592  8022 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/103
07-15 15:20:26.233  7592  8022 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/109 type=7
07-15 15:20:26.233  7592  8022 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/109
07-15 15:20:26.233  7592  8022 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=8
07-15 15:20:26.233  7592  8022 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
07-15 15:20:26.233  7592  8022 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/105 type=9
07-15 15:20:26.233  7592  8022 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/105
07-15 15:20:26.243  3409  3409 D TelephonyReceiver: bind: true
07-15 15:20:26.243  3409  3409 D TelephonyReceiver: bind: false
07-15 15:20:26.243  3409  3409 D TelephonyReceiver: switchBindHtcMsgCursor: null
07-15 15:20:26.253  1112  3698 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 7949 on display 0
07-15 15:20:26.253  1112  1186 D PMS     : acquireHCC(25395294): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 1112 1000 null
07-15 15:20:26.253  1112  1186 D PMS     : acquireHCC(309713d): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 1112 1000 null
07-15 15:20:26.253  1112  3698 V WindowManager: addAppToken: AppWindowToken{6a30400 token=Token{23743a83 ActivityRecord{3db3fd32 u0 com.test.thalitest/.MainActivity t124}}} to stack=1 task=124 at 0
07-15 15:20:26.263  1112  3698 D PMS     : acquireWL(16a0e439): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 1112 1000 null
07-15 15:20:26.263  7949  7949 W HTCLOG  : use specified tag [IPCThreadState], func [0].
07-15 15:20:26.263  7949  7949 W HTCLOG  : mask=0x18
07-15 15:20:26.263  1112  1169 I AnimationUtil: isHTCRecent(ThaliTest/Recents screens.)/4
07-15 15:20:26.263  7949  8024 W HTCLOG  : use specified tag [Vector], func [0].
07-15 15:20:26.263  7949  8024 W HTCLOG  : mask=0x18
07-15 15:20:26.263  3446  3446 I FeedHostManager: [onPause]
07-15 15:20:26.263  3446  3446 I FeedProviderManager: onPause
07-15 15:20:26.263  3446  3446 I FeedHostManager: [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@2cf7b092
07-15 15:20:26.263  3446  4830 I SocialFeedProvider: +onPause
07-15 15:20:26.263  3446  4830 I SocialFeedProvider: -onPause
07-15 15:20:26.263  3446  3446 I ContextualWidget: onPause
07-15 15:20:26.263  3446  3446 I ContextualWidget: notifyWidgetDeactive
07-15 15:20:26.263  1112  1169 V WindowManager: Adding window Window{1c9d5318 u0 Starting com.test.thalitest} at 2 of 7 (after Window{3ae9e78f u0 com.htc.launcher/com.htc.launcher.Launcher})
07-15 15:20:26.273  7437  7456 D GenericMessagesProvider: query uri: content://htc-messages/wappush/count
07-15 15:20:26.273  7339  8027 D libc    : [NET] android_getaddrinfofornet+,hn 17(0x73646b2e686f63),sn(),hints(known),family 0,flags 4
07-15 15:20:26.273  7339  8027 D libc    : [NET] android_getaddrinfofornet-, err=8
07-15 15:20:26.273  7339  8027 D libc    : [NET] android_getaddrinfofornet+,hn 17(0x73646b2e686f63),sn(),hints(known),family 0,flags 1024
07-15 15:20:26.273  7339  8027 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
07-15 15:20:26.273  7339  8027 D libc    : [NET] android_getaddrinfo_proxy+
07-15 15:20:26.273  7339  8027 D libc    : [NET] android_getaddrinfo_proxy get netid:0
07-15 15:20:26.283   525  8030 D libc    : [NET] android_getaddrinfofornet+,hn 17(0x73646b2e686f63),sn(),hints(known),family 0,flags 1024
07-15 15:20:26.283   525  8030 D libc    : [NET] _dns_getaddrinfo+, netid:0, mark:917504
07-15 15:20:26.283   525  8030 D libc    : [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
07-15 15:20:26.283   525  8030 D libc    : [NET] android_getaddrinfofornet-, err=7
07-15 15:20:26.283  7339  8027 D libc    : [NET] android_getaddrinfo_proxy-, NODATA
07-15 15:20:26.283  7339  8027 W System.err: java.net.UnknownHostException: Unable to resolve host "sdk.hockeyapp.net": No address associated with hostname
07-15 15:20:26.283  7339  8027 W System.err: 	at java.net.InetAddress.lookupHostByName(InetAddress.java:457)
07-15 15:20:26.283  7339  8027 W System.err: 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
07-15 15:20:26.283  7339  8027 W System.err: 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
07-15 15:20:26.283  7339  8027 W System.err: 	at com.android.okhttp.HostResolver$1.getAllByName(HostResolver.java:29)
07-15 15:20:26.283  7339  8027 W System.err: 	at com.android.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:232)
07-15 15:20:26.283  7339  8027 W System.err: 	at com.android.okhttp.internal.http.RouteSelector.next(RouteSelector.java:124)
07-15 15:20:26.283  7339  8027 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:272)
07-15 15:20:26.283  7339  8027 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:211)
07-15 15:20:26.283  7339  8027 W System.err: 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:403)
07-15 15:20:26.283  7339  8027 W System.err: 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.connect(HttpURLConnectionImpl.java:116)
07-15 15:20:26.283  1112  3940 I ActivityManager: Start proc 8029:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
07-15 15:20:26.283  7339  8027 W System.err: 	at com.android.okhttp.internal.http.DelegatingHttpsURLConnection.connect(DelegatingHttpsURLConnection.java:89)
07-15 15:20:26.283  7339  8027 W System.err: 	at com.android.okhttp.internal.http.HttpsURLConnectionImpl.connect(HttpsURLConnectionImpl.java:25)
07-15 15:20:26.283  7339  8027 W System.err: 	at net.hockeyapp.android.tasks.CheckUpdateTask.doInBackground(CheckUpdateTask.java:130)
07-15 15:20:26.283  7339  8027 W System.err: 	at net.hockeyapp.android.tasks.CheckUpdateTask.doInBackground(CheckUpdateTask.java:58)
07-15 15:20:26.283  7339  8027 W System.err: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
07-15 15:20:26.283  7339  8027 W System.err: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-15 15:20:26.283  7339  8027 W System.err: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-15 15:20:26.283  7339  8027 W System.err: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-15 15:20:26.283  7339  8027 W System.err: 	at java.lang.Thread.run(Thread.java:818)
07-15 15:20:26.283  7339  8027 W System.err: Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
07-15 15:20:26.283  7339  8027 W System.err: 	at libcore.io.Posix.android_getaddrinfo(Native Method)
07-15 15:20:26.283  7339  8027 W System.err: 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
07-15 15:20:26.283  7339  8027 W System.err: 	at java.net.InetAddress.lookupHostByName(InetAddress.java:438)
07-15 15:20:26.283  7339  8027 W System.err: 	... 18 more
07-15 15:20:26.293  8029  8029 W HTCLOG  : use specified tag [FDManager], func [0].
07-15 15:20:26.293  8029  8029 W HTCLOG  : mask=0x18
07-15 15:20:26.313  1112  3522 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
07-15 15:20:26.323  1112  3510 I ActivityManager: Delay finish: com.aiqidii.mercury/.service.location.GeocoderUpdateReceiver
07-15 15:20:26.323  3409  3409 D TelephonyReceiver: switchBindHtcMsgCursor: android.content.ContentResolver$CursorWrapperInner@2be36301
07-15 15:20:26.333  1112  1148 D StatusBarManagerService: setSystemUiVisibility(0x8600)
07-15 15:20:26.333  1112  1148 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{1c9d5318 u0 Starting com.test.thalitest}
07-15 15:20:26.333  1112  1148 D StatusBarManagerService: hiding MENU key
07-15 15:20:26.333  3097  3097 I PhoneStatusBar: setSystemUiNavVisibility(swipe=false hasFocus=false hasPolicy=false shadeState=true)
07-15 15:20:26.333  1112  3438 I ActivityManager: Resuming delayed broadcast
07-15 15:20:26.333  3097  3097 I PhoneStatusBar: hiding the MENU button mLongPressHomeMenu = false
07-15 15:20:26.343  3446  3446 I TrimMemoryManager: [trimMemory] 20
07-15 15:20:26.343  3312  8052 I WSP     : [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
07-15 15:20:26.343  7384  7978 I MediaStoreImporter: Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
07-15 15:20:26.343  3312  8052 D WeatherUtility: Weather sync is On
07-15 15:20:26.353  3312  8052 I WSP     : [Receiver] next auto-sync alarm event is 60 mins later, at time: Fri Jul 15 16:20:26 GMT+02:00 2016
07-15 15:20:26.353  3312  8052 W WSP     : [Receiver] can't get active network info
07-15 15:20:26.353  1112  3712 D PMS     : acquireWL(28a64da9): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 7384 10114 null
07-15 15:20:26.353  3409  4240 D PhoneApp: EVENT_QUERY_MO_PACKAGES
07-15 15:20:26.353  3409  4240 D PhoneApp: -- N1 =1
07-15 15:20:26.353  1112  3824 I ActivityManager: Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
07-15 15:20:26.353  3409  4240 D PhoneApp: -- N2 =0
07-15 15:20:26.363  3409  4240 D PhoneApp: -- N3 =0
07-15 15:20:26.363  3312  3312 V WSP     : [SyncService] no data connection, stop sync service
07-15 15:20:26.363  3446  3866 W asset   : Copying FileAsset 0xac451db0 (zip:/data/app/com.gameloft.android.gdc-1/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
07-15 15:20:26.373  7384  7384 W GoogleHttpClient: Failed to load SSLCertificateSocketFactory from package
07-15 15:20:26.373  7384  7384 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
07-15 15:20:26.383  7384  7384 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
07-15 15:20:26.403  7384  7978 I MediaStoreImporter: Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
07-15 15:20:26.403  1112  3712 I ActivityManager: Resuming delayed broadcast
07-15 15:20:26.403  8029  8029 I WebViewFactory: Loading com.google.android.webview version 42.0.2311.137 (code 52311137)
07-15 15:20:26.413  5039  8057 I art     : Explicit concurrent mark sweep GC freed 60191(4MB) AllocSpace objects, 0(0B) LOS objects, 72% free, 1531KB/5MB, paused 734us total 29.572ms
07-15 15:20:26.423  3446  3866 I Prism.WidgetManager: onLoadItems() -
07-15 15:20:26.423  3446  3866 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@3c5fe8ee -
07-15 15:20:26.423  3446  3866 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-15 15:20:26.423  3446  3866 W PackageManager: Failure retrieving resources for com.google.android.talk: Resource ID #0x0
07-15 15:20:26.433  3446  3866 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
07-15 15:20:26.433  3446  3866 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
07-15 15:20:26.433  3446  3446 W Prism.AllAppsManager: AllAppsMgr addApps, already exist: ApplicationInfo(id=29, title=Hangouts, componentNameComponentInfo{com.google.android.talk/com.google.android.talk.SigningInActivity} appsContainer=<ALLAPPS> P=UserHandle{0})
07-15 15:20:26.433  4261  4261 D WearableService: callingUid 10020, callindPid: 4261
07-15 15:20:26.443  3446  3866 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-15 15:20:26.443  1112  3642 I ActivityManager: Delay finish: com.google.android.music/.wear.WearBroadcastReceiver
07-15 15:20:26.443  3446  3866 W PackageManager: Failure retrieving resources for com.test.thalitest: Resource ID #0x0
07-15 15:20:26.443  3446  3866 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
07-15 15:20:26.443  3446  3866 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
07-15 15:20:26.453  3446  3446 I Launcher: Deferring update until onResume
07-15 15:20:26.453  3446  3446 D Launcher: waitUntilResume // bindAppsUpdated
07-15 15:20:26.453  3446  3446 I Launcher: Deferring update until onResume
07-15 15:20:26.453  3446  3446 D Launcher: waitUntilResume // bindAppsAdded
07-15 15:20:26.453  7384  7384 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
07-15 15:20:26.453  7384  8060 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
07-15 15:20:26.463  1112  3510 I ActivityManager: Resuming delayed broadcast
07-15 15:20:26.473  1112  1133 I ActivityManager: Delay finish: com.google.android.gm/.MailIntentReceiver
07-15 15:20:26.473  1112  3642 I ActivityManager: Resuming delayed broadcast
07-15 15:20:26.473  8029  8029 I LibraryLoader: Time to load native libraries: 34 ms (timestamps 9701-9735)
07-15 15:20:26.473  8029  8029 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-15 15:20:26.483  8029  8029 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {30b359cc}
07-15 15:20:26.483  8029  8029 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-15 15:20:26.493  8029  8029 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,07-15 15:20:26.493  8029  8029 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-15 15:20:26.503  8029  8029 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,07-15 15:20:26.503  8029  8029 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-15 15:20:26.513  7196  7196 D CDMountReceiver: whether to enable CD Auto-mount: true
07-15 15:20:26.513  7196  7196 D CDMountReceiver: showNotification() contentText=If HTC Sync Manager setup doesn't start automatically on your computer, download it from www.htc.com/hsm
,07-15 15:20:26.523  1112  1112 D ValidateNoPeople: setContact(com.nero.android.htc.sync,0.0,false),
,07-15 15:20:26.533  3175  3200 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true, isForDotMatrix: false
,07-15 15:20:26.533  8029  8064 W chromium: [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,07-15 15:20:26.543  8029  8068 D BluetoothAdapter: 562140181: getState() :  mService = null. Returning STATE_OFF
,07-15 15:20:26.553  8029  8029 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty(),
07-15 15:20:26.553  8029  8029 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50364 len=3345
07-15 15:20:26.553  8029  8029 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:9397000 len:1161174
,07-15 15:20:26.553  3097  3097 I RemoteViews: apply:com.nero.android.htc.sync 1 5 2 38,
,07-15 15:20:26.553  1112  3442 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=7384, uid=10114, userID:0
07-15 15:20:26.553  8029  8029 W HTCLOG  : use specified tag [libEGL], func [3].
07-15 15:20:26.563  1112  1134 D PMS     : releaseWL(28a64da9): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
07-15 15:20:26.553  8029  8029 W HTCLOG  : mask=0x18
07-15 15:20:26.563  1112  3775 I ActivityManager: Delay finish: com.nero.android.htc.sync/.CDMountReceiver
07-15 15:20:26.563  8029  8029 W HTCLOG  : use specified tag [libEGL], func [3].
07-15 15:20:26.563  1112  3824 I ActivityManager: Resuming delayed broadcast
,07-15 15:20:26.563  8029  8029 W HTCLOG  : mask=0x18
07-15 15:20:26.563  1112  3940 D VoldConnector: SND -> {7 mountISO mount /system/etc/PCTOOL.ISO /sys/class/android_usb/f_mass_storage/lun0/file}
07-15 15:20:26.563  8029  8029 I Adreno  : QUALCOMM build                   : 065751b, 
07-15 15:20:26.563  8029  8029 I Adreno  : Build Date                       : 04/15/15
07-15 15:20:26.563  8029  8029 I Adreno  : OpenGL ES Shader Compiler Version: E031.25.03.07
07-15 15:20:26.563  8029  8029 I Adreno  : Local Branch                     : 
07-15 15:20:26.563  8029  8029 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.1_rb2.9
07-15 15:20:26.563  8029  8029 I Adreno  : Remote Branch                    : NONE
07-15 15:20:26.563  8029  8029 I Adreno  : Reconstruct Branch               : AU_LINUX_ANDROID_LA.BF64.1.2.1_RB2.05.01.00.081.016 + 065751b +  NOTHING
07-15 15:20:26.563  1112  2934 D VoldConnector: RCV <- {200 7 mountISO operation succeeded}
07-15 15:20:26.563  7196  7196 D CDMountReceiver: enable CD Auto-mount: true
07-15 15:20:26.563  1112  3940 D MountService: mountISO: /system/etc/PCTOOL.ISO
07-15 15:20:26.563  7384  8053 I MusicLeanback: Conditions not met for autocaching.
07-15 15:20:26.573  1112  3442 D PMS     : acquireWL(1567d489): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 4261 10020 WorkSource{10020 com.google.android.gms}
07-15 15:20:26.563  7384  8053 I MusicLeanback: Stop autocaching.
07-15 15:20:26.563  7196  8069 D HTCUtilities: enable auto-mount
07-15 15:20:26.563  3097  3097 I RemoteViews: apply:com.nero.android.htc.sync 0 5 1 53
07-15 15:20:26.563  7196  8069 I HtcMountManagerAdapter: mHtcMountManager is  null
07-15 15:20:26.563  7196  8069 I HtcMountManagerAdapter: mStorageManager is  not null
07-15 15:20:26.573  4261  8070 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
07-15 15:20:26.573  4261  8070 D libc    : [NET] android_getaddrinfofornet-, err=8
07-15 15:20:26.573  4261  8070 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
,07-15 15:20:26.573  4261  8070 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
07-15 15:20:26.573  4261  8070 D libc    : [NET] android_getaddrinfo_proxy+
07-15 15:20:26.573  4261  8070 D libc    : [NET] android_getaddrinfo_proxy get netid:0
07-15 15:20:26.573   525  8071 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
07-15 15:20:26.573   525  8071 D libc    : [NET] _dns_getaddrinfo+, netid:0, mark:917504
,07-15 15:20:26.573   525  8071 D libc    : [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
07-15 15:20:26.573   525  8071 D libc    : [NET] android_getaddrinfofornet-, err=7
07-15 15:20:26.573  1112  1134 D PMS     : acquireWL(2aed6c8e): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 7846 10102 null
07-15 15:20:26.573  4261  8070 D libc    : [NET] android_getaddrinfo_proxy-, NODATA
07-15 15:20:26.573  3097  3097 I NotificationStackScrollLayout: setBlockTouchEnabled:false
07-15 15:20:26.573  1112  3940 D PMS     : releaseWL(1567d489): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10020 com.google.android.gms}
,07-15 15:20:26.583  3446  3446 D Prism.PackageStateRece_: action: android.intent.action.PACKAGE_CHANGED
07-15 15:20:26.583  3446  3446 I ContextualWidget: package com.google.android.gms changed
,07-15 15:20:26.583  3446  3903 I ContextualWidget: handleMessage, what=1026 mode=GettingOut maxcount=8
07-15 15:20:26.583  1112  3247 I ActivityManager: Delay finish: com.htc.launcher/.receiver.PackageStateReceiver
07-15 15:20:26.583  3312  8076 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
07-15 15:20:26.583  3312  8076 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed
,07-15 15:20:26.593  1112  3824 D PMS     : releaseWL(2aed6c8e): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,07-15 15:20:26.593  1112  2980 I ActivityManager: Resuming delayed broadcast
,07-15 15:20:26.593  1112  3698 I ActivityManager: Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver
,07-15 15:20:26.603  6221  8085 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,07-15 15:20:26.613  6221  8085 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
07-15 15:20:26.613  6221  8085 W HTCLOG  : mask=0x18
,07-15 15:20:26.623  3446  3903 I ContextualWidget: MFU.onDataSetChanged
07-15 15:20:26.623  3446  3903 I ContextualWidget: handleMessage, what=1001 mode=GettingOut maxcount=8
,07-15 15:20:26.623  3446  3903 I ContextualWidget: updateMFULaunchCountIfNeeded update=false days=0
07-15 15:20:26.623  3446  3903 I ContextualWidget: Download enabled: true, Recommend enabled: true
07-15 15:20:26.623  3446  3903 I ContextualWidget: sync all data, download=0 recommend=4
07-15 15:20:26.623  3446  3903 I ContextualWidget: sync all data, mode=GettingOut count=10
07-15 15:20:26.623  3446  3903 I ContextualWidget: notifyDataChanged, list size 8
,07-15 15:20:26.623  3446  3446 I HtcContextualWidgetDataManager: onDataChanged: GettingOut, item count: 8, original: 8, first add: false
,07-15 15:20:26.643  8029  8080 W chromium: [WARNING:data_reduction_proxy_config.cc(150)] SPDY proxy OFF at startup
,07-15 15:20:26.653  8029  8029 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-15 15:20:26.663  8029  8029 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-15 15:20:26.683  8029  8029 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC
,07-15 15:20:26.683  8029  8029 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-15 15:20:26.683  8029  8029 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-15 15:20:26.703  6221  8085 I ApplicationLogger: canRun() : Opted Out
,07-15 15:20:26.703  6221  8085 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 96 ms] updated apps [took 95 ms] 
07-15 15:20:26.703  1112  3442 I ActivityManager: Resuming delayed broadcast
,07-15 15:20:26.713  1112  3940 I ActivityManager: Start proc 8094:com.google.android.apps.plus/u0a126 for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor
,07-15 15:20:26.723  8094  8094 W HTCLOG  : use specified tag [FDManager], func [0].
07-15 15:20:26.723  8094  8094 W HTCLOG  : mask=0x18
07-15 15:20:26.723  7697  7753 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
07-15 15:20:26.733  8029  8115 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
07-15 15:20:26.733  8029  8115 W HTCLOG  : mask=0x18
07-15 15:20:26.743  1112  1133 V WindowManager: Adding window Window{1c78474a u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{1c9d5318 u0 Starting com.test.thalitest})
,07-15 15:20:26.743  1112  5609 I art     : Explicit concurrent mark sweep GC freed 31211(1670KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.259ms total 118.246ms
07-15 15:20:26.753  8094  8094 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,07-15 15:20:26.803  8029  8029 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
07-15 15:20:26.803  8029  8029 W HTCLOG  : use specified tag [ThreadedRenderer], func [0].
07-15 15:20:26.803  8029  8029 W HTCLOG  : mask=0x18
07-15 15:20:26.803  8029  8029 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
07-15 15:20:26.803  8029  8029 W HTCLOG  : mask=0x18
,07-15 15:20:26.803  8029  8115 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
07-15 15:20:26.803  8029  8115 W HTCLOG  : mask=0x18,
07-15 15:20:26.803  8029  8115 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
07-15 15:20:26.803  8029  8115 W HTCLOG  : mask=0x18
07-15 15:20:26.803  8029  8115 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].,
07-15 15:20:26.803  8029  8115 W HTCLOG  : mask=0x18
07-15 15:20:26.813  8029  8115 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
07-15 15:20:26.813  8029  8115 W HTCLOG  : mask=0x18
,07-15 15:20:26.813  8029  8115 W HTCLOG  : use specified tag [Surface], func [3].,
07-15 15:20:26.813  8029  8115 W HTCLOG  : mask=0x18
07-15 15:20:26.813  8029  8115 W HTCLOG  : use specified tag [GraphicBufferMapper], func [3].
07-15 15:20:26.813  8029  8115 W HTCLOG  : mask=0x18
07-15 15:20:26.813  8029  8115 W HTCLOG  : use specified tag [qdmemalloc], func [0].
07-15 15:20:26.813  8029  8115 W HTCLOG  : mask=0x18,
,07-15 15:20:26.923  3446  3446 I PendingUpdateTask: run pending update task - max:8, ori:8, incoming:8,
,07-15 15:20:26.933  8029  8029 I InputMethodManager: [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@1bfce73d, mServedView=org.apache.cordova.engine.SystemWebView{f513b32 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@4ba083
,07-15 15:20:26.933  3446  3903 I ContextualWidget: MFU.onDataSetChanged
,07-15 15:20:26.933  3446  3903 I ContextualWidget: handleMessage, what=1001 mode=GettingOut maxcount=8
07-15 15:20:26.933  3446  3903 I ContextualWidget: updateMFULaunchCountIfNeeded update=false days=0
,07-15 15:20:26.963  1112  1169 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +695ms
,07-15 15:20:26.963  1112  3510 I InputMethodManagerService: Disable input method client, pid=3446
07-15 15:20:26.963  1112  3510 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
07-15 15:20:26.963  1112  3510 I InputMethodManagerService: Enable input method client, pid=8029
07-15 15:20:26.963  3097  3097 I PhoneStatusBar: setImeWindowStatus(false,false)
,07-15 15:20:26.983  1112  3510 D PMS     : releaseWL(16a0e439): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null,
,07-15 15:20:27.023  8029  8029 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 8029
,07-15 15:20:27.033  1112  3775 D PMS     : acquireWL(14ee9984): PARTIAL_WAKE_LOCK  AsyncService 0x1 8094 10126 null
,07-15 15:20:27.033  1112  3438 D PMS     : releaseWL(14ee9984): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,07-15 15:20:27.043  6473  8127 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,07-15 15:20:27.053  1112  3775 I ActivityManager: Start proc 8129:com.android.vending/u0a57 for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver,
,07-15 15:20:27.063  1112  3510 D Process : killProcessQuiet, pid=7118
07-15 15:20:27.063  1112  3510 I ActivityManager: Killing 7118:com.htc.bgp/u0a8 (adj 15): empty #17
07-15 15:20:27.063  1112  3510 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19304 
07-15 15:20:27.063  8129  8129 W HTCLOG  : use specified tag [FDManager], func [0].
07-15 15:20:27.063  8129  8129 W HTCLOG  : mask=0x18
,07-15 15:20:27.103  8029  8029 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode,
,07-15 15:20:27.133  1112  3442 I ActivityManager: Recipient 7118
,07-15 15:20:27.183  6473  8127 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,07-15 15:20:27.183  1112  2980 D PMS     : acquireWL(354b24ab): PARTIAL_WAKE_LOCK  Icing 0x1 6473 10020 WorkSource{10020 com.google.android.gms}
,07-15 15:20:27.203  8029  8121 D jxcore_app_log: JniHelper::setJavaVM(0xab210b70), pthread_self() = -1407748072
,07-15 15:20:27.213  6473  6547 I Icing   : updateResources: need to parse owf{com.google.android.gms}
,07-15 15:20:27.213  8029  8121 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-15 15:20:27.213  8029  8121 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-15 15:20:27.213  8029  8121 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-15 15:20:27.213  8029  8121 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-15 15:20:27.213  8029  8121 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-15 15:20:27.213  8029  8121 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38580dd7 added. We now have 1 listener(s)
,07-15 15:20:27.213  1112  3442 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
07-15 15:20:27.223  1112  1134 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=6473, uid=10020, userID:0
07-15 15:20:27.213  8029  8121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 90:E7:C4:3C:62:6A
07-15 15:20:27.213  8029  8121 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "90:E7:C4:3C:62:6A"
07-15 15:20:27.213  8029  8121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-15 15:20:27.223  8029  8121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-15 15:20:27.223  8029  8121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-15 15:20:27.223  8029  8121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
,07-15 15:20:27.223  8029  8121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-15 15:20:27.223  8029  8121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 90:E7:C4:3C:62:6A
07-15 15:20:27.223  8029  8121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-15 15:20:27.223  8029  8121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-15 15:20:27.223  8029  8121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-15 15:20:27.223  8029  8121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-15 15:20:27.223  8029  8121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-15 15:20:27.223  8029  8121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-15 15:20:27.223  8029  8121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-15 15:20:27.223  8029  8121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3825b073 added. We now have 1 listener(s)
07-15 15:20:27.223  8029  8121 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-15 15:20:27.233  1112  2972 D WifiService: New client listening to asynchronous messages
,07-15 15:20:27.233  8029  8121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-15 15:20:27.233  8029  8121 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,07-15 15:20:27.243  8029  8121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-15 15:20:27.243  8029  8121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-15 15:20:27.243  8029  8121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-15 15:20:27.243  8029  8121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-15 15:20:27.243  8029  8121 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-15 15:20:27.243  1112  3940 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
07-15 15:20:27.243  8029  8121 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 90:E7:C4:3C:62:6A
,07-15 15:20:27.253  1112  1186 D PMS     : releaseHCC(25395294): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
07-15 15:20:27.253  1112  1186 D PMS     : releaseHCC(309713d): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,07-15 15:20:27.253  8029  8121 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-15 15:20:27.253  8029  8121 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-15 15:20:27.253  8029  8121 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:20:27.253  8029  8121 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-15 15:20:27.253  8029  8121 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-15 15:20:27.253  8029  8121 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-15 15:20:27.253  8029  8121 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:20:27.253  8029  8121 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:20:27.253  8029  8121 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-15 15:20:27.253  8029  8121 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-15 15:20:27.253  8029  8121 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-15 15:20:27.253  8029  8121 I io.jxcore.node.LifeCycleMonitor: start: OK
07-15 15:20:27.253  8029  8121 D io.jxcore.node.JXcoreExtension: Unit Tests on
,07-15 15:20:27.273  6473  8160 W IcingInternalCorpora: getNumBytesRead when not calculated.
,07-15 15:20:27.273  1112  3510 I PackageManager:  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=8129, uid=10057, userID:0
,07-15 15:20:27.283  8129  8129 W global  : [apache-http] Connection GC has been deprecated!
,07-15 15:20:27.293  3446  3903 I ContextualWidget: MFU.onLoadComplete
,07-15 15:20:27.303  3446  3903 I ContextualWidget: Download enabled: true, Recommend enabled: true
,07-15 15:20:27.303  3446  3903 I ContextualWidget: sync all data, download=0 recommend=4
07-15 15:20:27.303  3446  3903 I ContextualWidget: sync all data, mode=GettingOut count=10
07-15 15:20:27.303  3446  3903 I ContextualWidget: notifyDataChanged, list size 8
07-15 15:20:27.303  8129  8129 I Finsky  : [1] com.google.android.finsky.FinskyApp.onCreate(428): Initializing network with DFE https://android.clients.google.com/fdfe/
07-15 15:20:27.303  3446  3446 I HtcContextualWidgetDataManager: onDataChanged: GettingOut, item count: 8, original: 8, first add: false
,07-15 15:20:27.333  8029  8029 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-15 15:20:27.423  8129  8129 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(168): Dirty, need more hygiene.
,07-15 15:20:27.423  4261  4261 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-15 15:20:27.433  4261  4261 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.,
07-15 15:20:27.433  4261  4261 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-15 15:20:27.443  8129  8129 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
07-15 15:20:27.443  8129  8129 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-15 15:20:27.453  8129  8181 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
07-15 15:20:27.453  8129  8181 W HTCLOG  : mask=0x18
,07-15 15:20:27.463  1112  1133 I PackageManager:  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=8129, uid=10057, userID:0,
07-15 15:20:27.473  8129  8129 I Finsky  : [1] com.google.android.finsky.utils.bk.a(177): Enabling bucket experiment: factor=2.000, zeroDelta=0ms, forceNetwork=false
,07-15 15:20:27.473  8129  8178 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
07-15 15:20:27.473  8129  8178 D libc    : [NET] android_getaddrinfofornet-, err=8
,07-15 15:20:27.473  8129  8178 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
07-15 15:20:27.473  8129  8178 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
07-15 15:20:27.473  8129  8178 D libc    : [NET] android_getaddrinfo_proxy+
07-15 15:20:27.473  8129  8178 D libc    : [NET] android_getaddrinfo_proxy get netid:0
,07-15 15:20:27.473   525  8184 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024,
07-15 15:20:27.483   525  8184 D libc    : [NET] _dns_getaddrinfo+, netid:0, mark:917504
07-15 15:20:27.483   525  8184 D libc    : [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
07-15 15:20:27.483   525  8184 D libc    : [NET] android_getaddrinfofornet-, err=7
,07-15 15:20:27.483  8129  8178 D libc    : [NET] android_getaddrinfo_proxy-, NODATA
,07-15 15:20:27.483  3446  3446 I ContextualWidget: updateItemPosition item size=8   {-1740867511=7, -696942466=4, -335140367=0, -700633570=6, 956745593=1, 1475455068=3, 534392203=5, -33266553=2}
,07-15 15:20:27.483  3446  3903 I ContextualWidget: handleMessage, what=1028 mode=GettingOut maxcount=8
,07-15 15:20:27.513  8129  8129 I Finsky  : [1] com.google.android.finsky.j.j.run(208): Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
07-15 15:20:27.513  8129  8129 I Finsky  : [1] com.google.android.finsky.j.j.run(214): Finished loading 1 libraries.
,07-15 15:20:27.513  8129  8129 I Finsky  : [1] com.google.android.finsky.c.l.a(270): result=false type=4
,07-15 15:20:27.533  1112  3247 I ActivityManager: Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider,
,07-15 15:20:27.543  8129  8129 I Finsky  : [1] com.google.android.finsky.services.bc.a(1050): Restore complete with 0 success and 0 failed.,
07-15 15:20:27.543  1112  3775 I ActivityManager: Resuming delayed broadcast
,07-15 15:20:27.553  1112  3247 I ActivityManager: Killing 7618:com.htc.updater/u0a68 (adj 15): empty #17
07-15 15:20:27.553  1112  3247 D Process : killProcessQuiet, pid=7618,
07-15 15:20:27.553  1112  3247 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19304 ,
,07-15 15:20:27.573  7846  7883 I Babel_RequestWriter: error sending REQ[fc:6; creat:1468588807869; type:bme-149932641: userphotoalbums
07-15 15:20:27.573  7846  7883 I Babel_RequestWriter: ProtoBuf:
07-15 15:20:27.573  7846  7883 I Babel_RequestWriter: null
07-15 15:20:27.573  7846  7883 I Babel_RequestWriter: Creation stack:
07-15 15:20:27.573  7846  7883 I Babel_RequestWriter: java.lang.Throwable
,07-15 15:20:27.573  7846  7883 I Babel_RequestWriter: 	at bng.<init>(SourceFile:300)
07-15 15:20:27.573  7846  7883 I Babel_RequestWriter: 	at bnw.<init>(SourceFile:443)
07-15 15:20:27.573  7846  7883 I Babel_RequestWriter: 	at bma.<init>(SourceFile:50)
07-15 15:20:27.573  7846  7883 I Babel_RequestWriter: 	at bme.<init>(SourceFile:344)
07-15 15:20:27.573  7846  7883 I Babel_RequestWriter: 	at bvf.a(SourceFile:26)
07-15 15:20:27.573  7846  7883 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.a(SourceFile:5093)
07-15 15:20:27.573  7846  7883 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.g(SourceFile:4568)
07-15 15:20:27.573  7846  7883 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.a(SourceFile:887)
07-15 15:20:27.573  7846  7883 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.onHandleIntent(SourceFile:766)
07-15 15:20:27.573  7846  7883 I Babel_RequestWriter: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-15 15:20:27.573  7846  7883 I Babel_RequestWriter: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-15 15:20:27.573  7846  7883 I Babel_RequestWriter: 	at android.os.Looper.loop(Looper.java:155)
07-15 15:20:27.573  7846  7883 I Babel_RequestWriter: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-15 15:20:27.573  7846  7883 I Babel_RequestWriter: 
07-15 15:20:27.573  7846  7883 I Babel_RequestWriter: Origin stack:
07-15 15:20:27.573  7846  7883 I Babel_RequestWriter: java.lang.Throwable
07-15 15:20:27.573  7846  7883 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.e(SourceFile:1157)
07-15 15:20:27.573  7846  7883 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.f(SourceFile:3214)
07-15 15:20:27.573  7846  7883 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.s(SourceFile:2980)
07-15 15:20:27.573  7846  7883 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.stickers.StickersModule.a(SourceFile:132)
07-15 15:20:27.573  7846  7883 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.stickers.StickersModule.v_(SourceFile:105)
07-15 15:20:27.573  7846  7883 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.phone.EsApplication.onCreate(SourceFile:566),
07-15 15:20:27.573  7846  7883 I Babel_RequestWriter: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1025)
07-15 15:20:27.573  7846  7883 I Babel_RequestWriter: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4959)
07-15 15:20:27.573  7846  7883 I Babel_RequestWriter: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
07-15 15:20:27.573  7846  7883 I Babel_RequestWriter: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
07-15 15:20:27.573  7846  7883 I Babel_RequestWriter: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-15 15:20:27.573  7846  7883 I Babel_RequestWriter: ,	at android.os.Looper.loop(Looper.java:155)
07-15 15:20:27.573  7846  7883 I Babel_RequestWriter: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
07-15 15:20:27.573  7846  7883 I Babel_RequestWriter: 	at java.lang.reflect.Method.invoke(Native Method)
07-15 15:20:27.573  7846  7883 I Babel_RequestWriter: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-15 15:20:27.573  7846  7883 I Babel_RequestWriter: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030),
07-15 15:20:27.573  7846  7883 I Babel_RequestWriter: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
07-15 15:20:27.573  7846  7883 I Babel_RequestWriter: ]; took 0 ms (error code == 101)
,07-15 15:20:27.633  1112  3940 I ActivityManager: Recipient 7618,
,07-15 15:20:27.653  1112  1147 I ActivityManager: Waited long enough for: ServiceRecord{35b8bf39 u0 com.htc.club/com.mcrm.autonotification.NotificationService},
,07-15 15:20:27.673  3446  3446 D Prism.PackageStateRece_: action: android.intent.action.PACKAGE_CHANGED
07-15 15:20:27.673  3446  3446 I ContextualWidget: package com.google.android.talk changed
,07-15 15:20:27.683  3446  3903 I ContextualWidget: handleMessage, what=1026 mode=GettingOut maxcount=8
,07-15 15:20:27.693  1112  3698 I ActivityManager: Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver
,07-15 15:20:27.693  3312  8188 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.talk
,07-15 15:20:27.693  3312  8188 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed
,07-15 15:20:27.693  6221  8190 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
,07-15 15:20:27.703  7846  7894 I Babel_RequestWriter: error sending REQ[fc:2; creat:1468588824577; type:boc-340418213: devices/registerdevice,
07-15 15:20:27.703  7846  7894 I Babel_RequestWriter: ProtoBuf:
07-15 15:20:27.703  7846  7894 I Babel_RequestWriter: null
07-15 15:20:27.703  7846  7894 I Babel_RequestWriter: Creation stack:
07-15 15:20:27.703  7846  7894 I Babel_RequestWriter: java.lang.Throwable
07-15 15:20:27.703  7846  7894 I Babel_RequestWriter: 	at bng.<init>(SourceFile:300)
07-15 15:20:27.703  7846  7894 I Babel_RequestWriter: 	at bnw.<init>(SourceFile:443)
07-15 15:20:27.703  7846  7894 I Babel_RequestWriter: 	at boc.<init>(SourceFile:2476)
07-15 15:20:27.703  7846  7894 I Babel_RequestWriter: 	at boc.a(SourceFile:2506)
07-15 15:20:27.703  7846  7894 I Babel_RequestWriter: ,	at bxx.a(SourceFile:88)
07-15 15:20:27.703  7846  7894 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.a(SourceFile:5093)
07-15 15:20:27.703  7846  7894 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.g(SourceFile:3328)
07-15 15:20:27.703  7846  7894 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.a(SourceFile:887)
07-15 15:20:27.703  7846  7894 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.onHandleIntent(SourceFile:766)
07-15 15:20:27.703  7846  7894 I Babel_RequestWriter: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-15 15:20:27.703  7846  7894 I Babel_RequestWriter: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-15 15:20:27.703  7846  7894 I Babel_RequestWriter: 	at android.os.Looper.loop(Looper.java:155)
07-15 15:20:27.703  7846  7894 I Babel_RequestWriter: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-15 15:20:27.703  7846  7894 I Babel_RequestWriter: 
,07-15 15:20:27.703  7846  7894 I Babel_RequestWriter: Origin stack:
07-15 15:20:27.703  7846  7894 I Babel_RequestWriter: java.lang.Throwable
07-15 15:20:27.703  7846  7894 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.e(SourceFile:1157)
07-15 15:20:27.703  7846  7894 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.a(SourceFile:1175)
07-15 15:20:27.703  7846  7894 I Babel_RequestWriter: 	at btp.b(SourceFile:1867)
07-15 15:20:27.703  7846  7894 I Babel_RequestWriter: 	at btl.u(SourceFile:1301)
07-15 15:20:27.703  7846  7894 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.a(SourceFile:829)
07-15 15:20:27.703  7846  7894 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.onHandleIntent(SourceFile:766)
07-15 15:20:27.703  7846  7894 I Babel_RequestWriter: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-15 15:20:27.703  7846  7894 I Babel_RequestWriter: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-15 15:20:27.703  7846  7894 I Babel_RequestWriter: 	at android.os.Looper.loop(Looper.java:155)
07-15 15:20:27.703  7846  7894 I Babel_RequestWriter: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-15 15:20:27.703  7846  7894 I Babel_RequestWriter: ]; took 0 ms (error code == 101)
,07-15 15:20:27.733  3446  3903 I ContextualWidget: MFU.onDataSetChanged
07-15 15:20:27.733  3446  3903 I ContextualWidget: handleMessage, what=1001 mode=GettingOut maxcount=8
07-15 15:20:27.733  3446  3903 I ContextualWidget: updateMFULaunchCountIfNeeded update=false days=0
07-15 15:20:27.733  3446  3903 I ContextualWidget: Download enabled: true, Recommend enabled: true
07-15 15:20:27.733  3446  3903 I ContextualWidget: sync all data, download=0 recommend=4
07-15 15:20:27.733  3446  3903 I ContextualWidget: sync all data, mode=GettingOut count=10
07-15 15:20:27.733  3446  3903 I ContextualWidget: notifyDataChanged, list size 8
07-15 15:20:27.733  3446  3446 I HtcContextualWidgetDataManager: onDataChanged: GettingOut, item count: 8, original: 8, first add: false
,07-15 15:20:27.763  6221  8190 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,07-15 15:20:27.763  6221  8190 I ApplicationLogger: canRun() : Opted Out
07-15 15:20:27.763  6221  8190 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 68 ms] updated apps [took 68 ms] 
07-15 15:20:27.763  1112  3443 I ActivityManager: Resuming delayed broadcast
,07-15 15:20:27.773  1112  3442 I ActivityManager: Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,07-15 15:20:27.773  1112  3247 D PMS     : acquireWL(2910d414): PARTIAL_WAKE_LOCK  AsyncService 0x1 8094 10126 null
,07-15 15:20:27.773  1112  3510 D PMS     : releaseWL(2910d414): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,07-15 15:20:27.783  1112  3698 I ActivityManager: Resuming delayed broadcast
,07-15 15:20:27.783  6473  8127 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk,
,07-15 15:20:27.803  6473  8127 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
07-15 15:20:27.803  1112  3247 I ActivityManager: Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,07-15 15:20:27.813  1112  3442 I ActivityManager: Resuming delayed broadcast,
,07-15 15:20:27.843  1112  3698 I ActivityManager: Start proc 8196:com.google.android.partnersetup/u0a23 for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver
,07-15 15:20:27.853  8196  8196 W HTCLOG  : use specified tag [FDManager], func [0].,
07-15 15:20:27.853  8196  8196 W HTCLOG  : mask=0x18
,07-15 15:20:27.903  1112  2980 I ActivityManager: Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,07-15 15:20:27.913  1112  3775 I ActivityManager: Resuming delayed broadcast
,07-15 15:20:27.923  1112  3510 I ActivityManager: Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
,07-15 15:20:27.933  1112  3438 I ActivityManager: Resuming delayed broadcast,
07-15 15:20:27.933  3672  3672 E PackageActionReceiver: ACTION_PACKAGE_ADDED
07-15 15:20:27.933  1112  3443 I ActivityManager: Killing 7647:com.htc.autobot/u0a27 (adj 15): empty #17
07-15 15:20:27.933  1112  3443 D Process : killProcessQuiet, pid=7647
07-15 15:20:27.933  1112  3443 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19304 
,07-15 15:20:27.943  3446  3866 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
07-15 15:20:27.943  3446  3866 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@3c5fe8ee +
07-15 15:20:27.943  3446  3866 I Prism.WidgetManager: onLoadItems() +
07-15 15:20:27.953  1112  3940 I ActivityManager: Recipient 7647
,07-15 15:20:27.973  3446  3866 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,07-15 15:20:28.043  3446  3446 I PendingUpdateTask: run pending update task - max:8, ori:8, incoming:8,
,07-15 15:20:28.053  4993  4993 I [MirrorLinkServer]PackageInstalledReceiver: PackageInstalledReceiver Received::Intent { act=android.intent.action.PACKAGE_ADDED dat=package: flg=0x4000010 cmp=com.htc.mirrorlinkserver/.PackageInstalledReceiver (has extras) }
07-15 15:20:28.053  4993  4993 D [MirrorLinkServer]PackageInstalledReceiver: Counter : 1
07-15 15:20:28.053  4993  4993 D [MirrorLinkServer]MirrorLinkConnectionReceiver: notifyMlSevrer
,07-15 15:20:28.063  3312  8220 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.test.thalitest,
07-15 15:20:28.063  3312  8220 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed
,07-15 15:20:28.083  1112  2929 I ActivityManager: Start proc 8221:com.htc.bgp/u0a8 for service com.htc.flexnet/.FlexNetService,
,07-15 15:20:28.083  4993  4993 I [MirrorLinkServer]MirrorLinkServer: onStartCommand() Action : android.intent.action.PACKAGE_ADDED
07-15 15:20:28.083  1112  2929 V AlarmManager: sending alarm PendingIntent{24a91ac: PendingIntentRecord{92a9e75 com.htc.flexnet startService}}, i=ACTION_CAMPNETWORK_NOT_IN_SERVICE_OR_ROAMING, t=2, cnt=1, w=61319, Int=0
07-15 15:20:28.083  4993  4993 D [MirrorLinkServer]MirrorLinkServer: New Application installed : com.test.thalitest
07-15 15:20:28.083  4993  4993 D [MirrorLinkServer]d: onApplicationInstalled
07-15 15:20:28.083  8221  8221 W HTCLOG  : use specified tag [FDManager], func [0].
07-15 15:20:28.083  8221  8221 W HTCLOG  : mask=0x18
07-15 15:20:28.083  4993  4993 W [MirrorLinkServer]d: Cannot find find the  com.mirrorlink.android.app.LAUNCH intent.
07-15 15:20:28.083  4993  4993 I [MirrorLinkServer]d: com.test.thalitest is not a MirrorLink-aware app.
07-15 15:20:28.083  3446  3446 D Prism.PackageStateRece_: action: android.intent.action.PACKAGE_ADDED
07-15 15:20:28.083  4993  8236 I [MirrorLinkServer]d: Database Update Progress State : false
07-15 15:20:28.083  4993  8236 I [MirrorLinkServer]c: onApplicationUpdationCompleted, sending broadcast
07-15 15:20:28.083  4993  4993 I [MirrorLinkServer]MirrorLinkServer: Broadcast Received::Intent { act=com.htc.HTCMirrorLinkServer.PACKAGE_UPDATE_COMPLETED }
07-15 15:20:28.083  4993  4993 D [MirrorLinkServer]MirrorLinkServer: ML_PACKAGE_UPDATE_COMPLETED intent received
07-15 15:20:28.083  4993  4993 D [MirrorLinkServer]MirrorLinkServer: Counter : 0
07-15 15:20:28.083  4993  4993 I [MirrorLinkServer]MirrorLinkConnectionReceiver: checkAndStopMLSession
07-15 15:20:28.083  4993  4993 I [MirrorLinkServer]MirrorLinkConnectionReceiver: Stopping Service
,07-15 15:20:28.083  3446  3446 I ContextualWidget: package com.test.thalitest added
07-15 15:20:28.093  3446  3903 I ContextualWidget: handleMessage, what=1003 mode=GettingOut maxcount=8
,07-15 15:20:28.093  1112  1134 I ActivityManager: Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver
07-15 15:20:28.103  6221  8243 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,07-15 15:20:28.143  8221  8221 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,07-15 15:20:28.163  8221  8221 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
07-15 15:20:28.163  8221  8221 W HTCLOG  : mask=0x18
,07-15 15:20:28.173  8221  8221 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@1c88a32a(com.htc.providers.calendar.HtcCalendarProvider@2460751b),
,07-15 15:20:28.193  8221  8245 D CalendarProvider2: wait start:true
,07-15 15:20:28.203  1112  3698 D PMS     : acquireWL(3dbe824f): PARTIAL_WAKE_LOCK  SWITCH_NETWORK_MODE_WAKE_LOCK_0 0x1 8221 10008 null
,07-15 15:20:28.213  8221  8245 D CalendarProvider2: wait end:false
,07-15 15:20:28.233  8221  8221 D FlexNetS: registerStateListener
,07-15 15:20:28.233  1112  3712 D PMS     : releaseWL(3dbe824f): PARTIAL_WAKE_LOCK  SWITCH_NETWORK_MODE_WAKE_LOCK_0 0x1 null
,07-15 15:20:28.243  8221  8221 D FlexNetS: getServiceState:2
,07-15 15:20:28.253  8221  8221 D FlexNetS: unregisterStateListener
,07-15 15:20:28.263  3446  3866 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-15 15:20:28.263  6221  8243 I ApplicationLogger: canRun() : Opted Out
,07-15 15:20:28.263  6221  8243 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 164 ms] updated apps [took 163 ms] 
,07-15 15:20:28.273  3446  3903 I ContextualWidget: MFU.onDataSetChanged,
07-15 15:20:28.273  3446  3903 I ContextualWidget: handleMessage, what=1001 mode=GettingOut maxcount=8
07-15 15:20:28.273  3446  3903 I ContextualWidget: updateMFULaunchCountIfNeeded update=false days=0
,07-15 15:20:28.313  8029  8164 W jxcore-log: Initializing JXcore engine
07-15 15:20:28.313  8029  8164 W jxcore-log: JXcore engine is ready
,07-15 15:20:28.343  1112  3443 I ActivityManager: Resuming delayed broadcast,
,07-15 15:20:28.353  8029  8164 W jxcore-log: Starting JXcore engine,
,07-15 15:20:28.373  1112  2980 I ActivityManager: Start proc 8250:com.htc.cs.dm/u0a88 for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver
,07-15 15:20:28.383  8250  8250 W HTCLOG  : use specified tag [FDManager], func [0].
07-15 15:20:28.383  8250  8250 W HTCLOG  : mask=0x18
,07-15 15:20:28.413  8029  8164 W jxcore-log: Platform android
07-15 15:20:28.413  8029  8164 W jxcore-log: 
07-15 15:20:28.413  8029  8164 W jxcore-log: Process ARCH arm
07-15 15:20:28.413  8029  8164 W jxcore-log: 
,07-15 15:20:28.423  6473  6560 I Icing   : Indexing E7E0925662843324D4EEB09F3BC5C5BCEC2A972A from com.google.android.gms
,07-15 15:20:28.453  3446  3866 W asset   : Copying FileAsset 0xac4dd920 (zip:/data/app/com.gameloft.android.gdc-1/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,
,07-15 15:20:28.463  8250  8250 I DeviceManagement: DMApplication: !!! Hello, this is: [com.htc.cs.dm;3.0.404391;250011189] pid=8250 dbg=false s=true,
07-15 15:20:28.463  8250  8250 I DeviceManagement: PackageUpdateReceiver: vvv Package added: [com.test.thalitest],
,07-15 15:20:28.483  1112  3438 D Process : killProcessQuiet, pid=7674
07-15 15:20:28.483  1112  3438 I ActivityManager: Start proc 8272:com.google.android.apps.docs/u0a90 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
07-15 15:20:28.483  1112  3438 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityManagerService.trimApplications:19731 
07-15 15:20:28.483  1112  3438 I ActivityManager: Killing 7674:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,07-15 15:20:28.493  8272  8272 W HTCLOG  : use specified tag [FDManager], func [0].
07-15 15:20:28.493  8272  8272 W HTCLOG  : mask=0x18
,07-15 15:20:28.523  3446  3866 E Prism.WidgetManager: The same lists. No need to update. skip it.
,07-15 15:20:28.523  3446  3866 I Prism.WidgetManager: onLoadItems() -
07-15 15:20:28.523  3446  3866 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@3c5fe8ee -
,07-15 15:20:28.533  8029  8164 I jxcore-log: JXcore Cordova bridge is ready!
07-15 15:20:28.533  8029  8164 I jxcore-log: 
,07-15 15:20:28.533  8029  8164 W jxcore-log: JXcore engine is started
,07-15 15:20:28.533  8029  8121 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION,
07-15 15:20:28.533  8029  8029 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-15 15:20:28.543  6473  6560 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-15 15:20:28.543  8029  8164 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
07-15 15:20:28.543  8029  8164 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,07-15 15:20:28.553  6473  6560 D Icing   : Loaded CLD2 Version V2.0 - 20141016
07-15 15:20:28.553  8029  8029 I chromium: [INFO:CONSOLE(57)] "app.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57),
07-15 15:20:28.553  8029  8029 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,07-15 15:20:28.553  6473  6560 I Icing   : Indexing done E7E0925662843324D4EEB09F3BC5C5BCEC2A972A
07-15 15:20:28.573  1112  3247 I ActivityManager: Recipient 7674
,07-15 15:20:28.603  3446  3446 I ContextualWidget: updateItemPosition item size=8   {-1740867511=7, -696942466=4, -335140367=0, -700633570=6, 956745593=1, 1475455068=3, 534392203=5, -33266553=2}
,07-15 15:20:28.613  8029  8029 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
07-15 15:20:28.613  1112  3698 D PMS     : acquireWL(15610ee5): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 1112 1000 null
07-15 15:20:28.613  8029  8029 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
07-15 15:20:28.613  8029  8121 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 63ms. Plugin should use CordovaInterface.getThreadPool().
,07-15 15:20:28.623  1112  3522 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
,07-15 15:20:28.653  3446  3446 I Prism.AllAppsOptionsMa_: getAllAppsAbility() false,
07-15 15:20:28.653  3446  3446 I Prism.AllAppsOptionsMa_: removeAllAppsAbility()
,07-15 15:20:28.653  3446  3446 I FeedHostManager: [onResume],
07-15 15:20:28.653  3446  3446 I FeedProviderManager: onResume
07-15 15:20:28.653  3446  4830 I SocialFeedProvider: +onResume
07-15 15:20:28.653  3446  4830 I SocialFeedProvider: updateAccounts - Accounts is no change
,07-15 15:20:28.653  3446  4830 I SocialFeedProvider: -onResume
,07-15 15:20:28.653  3446  3446 I ConnectivityHelper: [getCurrentConnectionType] no network connection
07-15 15:20:28.653  3446  3446 I ContextualWidget: onResume
07-15 15:20:28.653  3446  3446 I ContextualWidget: notifyWidgetActive location size=0 user consent location=false
07-15 15:20:28.653  3446  3446 I ContextualWidget: ignore uploadUsageData location=false usage data=false allowAutoUpload=true
07-15 15:20:28.653  3446  3446 I ContextualWidget: postSyncRecommendedApps, isReady=true allowAutoSync=true syncMode=1 isEnableRecommend=true
07-15 15:20:28.663  3097  3097 I PhoneStatusBar: setSystemUiNavVisibility(swipe=false hasFocus=false hasPolicy=false shadeState=true)
07-15 15:20:28.663  1112  1148 D StatusBarManagerService: setSystemUiVisibility(0x8700)
07-15 15:20:28.663  3097  3097 I PhoneStatusBar: hiding the MENU button mLongPressHomeMenu = false
07-15 15:20:28.663  1112  1148 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{3ae9e78f u0 com.htc.launcher/com.htc.launcher.Launcher}
07-15 15:20:28.663  3446  3446 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
07-15 15:20:28.663  1112  1148 D StatusBarManagerService: hiding MENU key
,07-15 15:20:28.673  3446  3446 I ThreadedRenderer: Defer allocateBuffers to drawing time
07-15 15:20:28.673  1112  3775 I InputMethodManagerService: Disable input method client, pid=8029
07-15 15:20:28.673  3097  3097 I PhoneStatusBar: setImeWindowStatus(false,false)
07-15 15:20:28.673  1112  3775 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
07-15 15:20:28.673  1112  3775 I InputMethodManagerService: Enable input method client, pid=3446
07-15 15:20:28.683  8029  8029 W IInputConnectionWrapper: reportFullscreenMode on inactive InputConnection
,07-15 15:20:28.713  1112  3775 D PMS     : releaseWL(15610ee5): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null,
,07-15 15:20:28.723  8272  8272 D DocsApplication: Plugin installer initialized.,
07-15 15:20:28.723  1112  1148 D StatusBarManagerService: setSystemUiVisibility(0xc0000700)
07-15 15:20:28.723  1112  1148 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{3ae9e78f u0 com.htc.launcher/com.htc.launcher.Launcher}
07-15 15:20:28.723  1112  1148 D StatusBarManagerService: hiding MENU key
,07-15 15:20:28.723  3097  3097 I PhoneStatusBar: setSystemUiNavVisibility(swipe=false hasFocus=false hasPolicy=false shadeState=true),
07-15 15:20:28.723  3097  3097 I PhoneStatusBar: hiding the MENU button mLongPressHomeMenu = false
,07-15 15:20:28.733  1112  1147 D Process : killProcessQuiet, pid=7724
07-15 15:20:28.733  1112  1147 I ActivityManager: Killing 7724:com.google.android.gm.exchange/u0a156 (adj 15): empty #17
07-15 15:20:28.733  1112  1147 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityStack.destroyActivityLocked:3407 ,
,07-15 15:20:28.753  8272  8272 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{1be7a3a0 com.google.android.apps.docs}
,07-15 15:20:28.753  8293  8293 W HTCLOG  : use specified tag [AndroidRuntime], func [0].
,07-15 15:20:28.753  8293  8293 W HTCLOG  : mask=0x18
07-15 15:20:28.763   589   589 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-15 15:20:28.763  3446  3903 I ContextualWidget: MFU.onLoadComplete,
,07-15 15:20:28.763  3446  3903 I ContextualWidget: Download enabled: true, Recommend enabled: true
07-15 15:20:28.763  3446  3903 I ContextualWidget: sync all data, download=0 recommend=4
07-15 15:20:28.763  3446  3903 I ContextualWidget: sync all data, mode=GettingOut count=10
07-15 15:20:28.763  3446  3903 I ContextualWidget: notifyDataChanged, list size 8
07-15 15:20:28.763  3446  3446 I HtcContextualWidgetDataManager: onDataChanged: GettingOut, item count: 8, original: 8, first add: false
,07-15 15:20:28.773  8272  8272 D TAG     : onCreate()
,07-15 15:20:28.773  3446  3903 I ContextualWidget: MFU.onDownloadDataSetChanged
07-15 15:20:28.773  3446  3903 I ContextualWidget: handleMessage, what=1028 mode=GettingOut maxcount=8
07-15 15:20:28.773  3446  3903 I ContextualWidget: handleMessage, what=1018 mode=GettingOut maxcount=8
,07-15 15:20:28.783  8272  8272 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,07-15 15:20:28.793  1112  3723 I art     : Explicit concurrent mark sweep GC freed 29376(1390KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 17MB/26MB, paused 1.714ms total 143.283ms,
,07-15 15:20:28.823  1112  3940 I ActivityManager: Recipient 7724,
,07-15 15:20:28.833  3446  4725 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1468588828842
,07-15 15:20:28.843  8029  8029 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-15 15:20:28.843  8029  8029 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
07-15 15:20:28.843  8029  8029 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-15 15:20:28.843  8029  8029 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
07-15 15:20:28.843  8029  8029 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:20:28.843  8029  8029 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:20:28.843  8029  8029 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:20:28.843  8029  8029 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-15 15:20:28.843  8029  8029 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38580dd7 removed from the list
,07-15 15:20:28.853  8029  8029 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-15 15:20:28.853  8029  8029 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3825b073 removed from the list
07-15 15:20:28.853  8029  8029 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:20:28.853  8029  8029 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
07-15 15:20:28.853  8029  8029 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-15 15:20:28.863  6473  6560 I Icing   : Indexing E7E0925662843324D4EEB09F3BC5C5BCEC2A972A from com.google.android.gms,
07-15 15:20:28.873  6473  6560 I Icing   : Indexing done E7E0925662843324D4EEB09F3BC5C5BCEC2A972A
,07-15 15:20:28.923  1112  1147 I ActivityManager: Waited long enough for: ServiceRecord{fb969b2 u0 com.nero.android.htc.sync/.PowerDisconService},
,07-15 15:20:28.933  8029  8029 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 8029
,07-15 15:20:28.943  3446  4725 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1468588828949,
,07-15 15:20:28.953  3446  4398 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1468588828962,
,07-15 15:20:29.033  8293  8301 W HTCLOG  : use specified tag [cutils-trace], func [0].
07-15 15:20:29.033  8293  8301 W HTCLOG  : mask=0x18
07-15 15:20:29.033  8293  8301 E cutils-trace: Error opening trace file: Permission denied (13)
,07-15 15:20:29.073  3446  3446 I PendingUpdateTask: run pending update task - max:8, ori:8, incoming:8,
,07-15 15:20:29.083  8293  8293 D CustomizationManager: ====startRecUseTime====,
07-15 15:20:29.083  8293  8293 D htc.customization.log.level:  is 
07-15 15:20:29.083  8293  8293 W CustomizationLogLevel: Level value is invalid, use default level 2
07-15 15:20:29.083  3446  4398 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1468588829090
,07-15 15:20:29.093  3446  4640 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
,07-15 15:20:29.113  3446  4388 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1468588829116,
,07-15 15:20:29.133  8293  8293 D CustomizationManager:  Read ACC file spent 0.026 (s)
,07-15 15:20:29.133  8293  8293 D CIDMapFileReader: Parsing tag item name = HTC__001
07-15 15:20:29.133  8293  8293 D CIDMapFileReader: Parsing tag item name = HTC__002
07-15 15:20:29.133  8293  8293 D CIDMapFileReader: Parsing tag item name = HTC__016
07-15 15:20:29.133  8293  8293 D CIDMapFileReader: Parsing tag item name = HTC__031
07-15 15:20:29.133  8293  8293 D CIDMapFileReader: Parsing tag item name = HTC__032
07-15 15:20:29.133  8293  8293 D CIDMapFileReader: Parsing tag item name = HTC__102,
07-15 15:20:29.133  8293  8293 D CIDMapFileReader: Parsing tag item name = HTC__A07
07-15 15:20:29.133  8293  8293 D CIDMapFileReader: Parsing tag item name = HTC__J15
07-15 15:20:29.133  8293  8293 D CIDMapFileReader: Parsing tag item name = HTC__M27
07-15 15:20:29.133  8293  8293 D CIDMapFileReader: Parsing tag item name = HTC__Y13
07-15 15:20:29.133  8293  8293 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__102.xml
07-15 15:20:29.133  8293  8293 I CustomizationCIDLoader: Parsing tag category name = application
07-15 15:20:29.133  8293  8293 I CustomizationCIDLoader: Parsing tag category name = system
07-15 15:20:29.133  8293  8293 I CustomizationCIDLoader: Parsing tag category name = Settings
07-15 15:20:29.133  8293  8293 I CustomizationCIDLoader: Parsing tag category name = ACC
07-15 15:20:29.133  8293  8293 I CustomizationCIDLoader: add string-array item, value = 42507
07-15 15:20:29.133  8293  8293 I CustomizationCIDLoader: add string-array item, value = 21902
07-15 15:20:29.133  8293  8293 I CustomizationCIDLoader: add string-array item, value = 26006:26001.26002.26003
07-15 15:20:29.133  8293  8293 I CustomizationCIDLoader: add string-array item, value = 23420
07-15 15:20:29.133  8293  8293 I CustomizationCIDLoader: add string-array item, value = 22299
07-15 15:20:29.133  8293  8293 I CustomizationCIDLoader: add string-array item, value = 24002
07-15 15:20:29.133  8293  8293 I CustomizationCIDLoader: add string-array item, value = 23210
07-15 15:20:29.133  8293  8293 I CustomizationCIDLoader: add string-array item, value = 23205
07-15 15:20:29.133  8293  8293 I CustomizationCIDLoader: add string-array item, value = 23806
07-15 15:20:29.133  8293  8293 I CustomizationCIDLoader: add string-array item, value = 23430
07-15 15:20:29.133  8293  8293 I CustomizationCIDLoader: add string-array item, value = 23408
07-15 15:20:29.133  8293  8293 I CustomizationCIDLoader: add string-array item, value = 27205
07-15 15:20:29.133  8293  8293 I CustomizationCIDLoader: add string-array item, value = 27202:27205
07-15 15:20:29.133  8293  8293 I CustomizationCIDLoader: add string-array item, value = 27216:27202.27205
07-15 15:20:29.133  8293  8293 I CustomizationCIDLoader: add string-array item, value = 42507:C:1:0
07-15 15:20:29.133  8293  8293 I CustomizationCIDLoader: add string-array item, value = 21902:C:1:0
07-15 15:20:29.133  8293  8293 I CustomizationCIDLoader: add string-array item, value = 26006:D:1:0
07-15 15:20:29.133  8293  8293 I CustomizationCIDLoader: add string-array item, value = 23420:D:0:0
07-15 15:20:29.133  8293  8293 I CustomizationCIDLoader: add string-array item, value = 27205:C:1:0
07-15 15:20:29.133  8293  8293 I CustomizationCIDLoader: add string-array item, value = 22299:D:0:0
07-15 15:20:29.133  8293  8293 I CustomizationCIDLoader: add string-array item, value = 24002:D:0:0
07-15 15:20:29.133  8293  8293 I CustomizationCIDLoader: add string-array item, value = 23210:D:2:0
07-15 15:20:29.133  8293  8293 I CustomizationCIDLoader: add string-array item, value = 23205:D:2:0
07-15 15:20:29.133  8293  8293 I CustomizationCIDLoader: add string-array item, value = 23806:D:0:0
07-15 15:20:29.133  8293  8293 I CustomizationCIDLoader: add string-array item, value = 23430:C:1:0
07-15 15:20:29.133  8293  8293 I CustomizationCIDLoader: add string-array item, value = 23408:C:1:0
07-15 15:20:29.133  8293  8293 I CustomizationCIDLoader: add string-array item, value = 27202:C:1:0
07-15 15:20:29.133  8293  8293 I CustomizationCIDLoader: add string-array item, value = 27216:C:1:0
07-15 15:20:29.133  8293  8293 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
07-15 15:20:29.133  8293  8293 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
07-15 15:20:29.133  8293  8293 I CustomizationCIDLoader: Parsing tag category name = AudioService
07-15 15:20:29.133  8293  8293 D CustomizationManager:  Read CID file spent 0.056 (s)
07-15 15:20:29.133  8293  8293 D CustomizationManager:  All configurations done spent 0.057 (s)
,07-15 15:20:29.163  1112  3824 D PackageManager: deletePackageAsUser: pkg=com.test.thalitest user=0, pid=8293, uid=2000,
,07-15 15:20:29.163  1112  1147 D Process : killProcessQuiet, pid=8029
07-15 15:20:29.163  1112  1147 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
07-15 15:20:29.163  1112  1147 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.removeProcessLocked:6195 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5997 
07-15 15:20:29.163  1112  1147 I ActivityManager: Killing 8029:com.test.thalitest/u0a0 (adj 9): stop com.test.thalitest
,07-15 15:20:29.203  3446  4116 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,07-15 15:20:29.213  1112  1190 W PackageSettings: Skipping PackageSetting{1cf0f01a com.example.hello/10193} due to missing metadata,
,07-15 15:20:29.223  8221  8221 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: },
07-15 15:20:29.223  8221  8221 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,07-15 15:20:29.233   539   539 W HTCLOG  : use specified tag [Vector], func [0].
07-15 15:20:29.233   539   539 W HTCLOG  : mask=0x18
,07-15 15:20:29.253  1112  3824 I ActivityManager: Recipient 8029
07-15 15:20:29.253  1112  2972 D WifiService: Client connection lost with reason: 4
,07-15 15:20:29.253  3233  3233 W HTCLOG  : use specified tag [InputEventReceiver], func [0].
07-15 15:20:29.253  3233  3233 W HTCLOG  : mask=0x18
,07-15 15:20:29.253  3233  3233 E InputEventReceiver: Looper::removeFd(33) is failed, result(0), input channel 'ClientState{ce7d7d8 uid 10000 pid 8029} (c)'
07-15 15:20:29.253  3446  4388 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1468588829263
,07-15 15:20:29.263  6473  6560 I Icing   : Indexing CF3FE6BD92DAECCC594E8F8BDE8C89D040E637CF from com.google.android.googlequicksearchbox,
07-15 15:20:29.273  3446  4725 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1468588829277
,07-15 15:20:29.273  1112  1190 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,07-15 15:20:29.283  1112  3824 W ActivityManager: Spurious death for ProcessRecord{214f85e3 8029:com.test.thalitest/u0a0}, curProc for 8029: null
,07-15 15:20:29.293  4993  4993 I [MirrorLinkServer]MirrorLinkServer: Broadcast Received::Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
07-15 15:20:29.293  4993  4993 D [MirrorLinkServer]MirrorLinkServer: ACTION_PACKAGE_REMOVED intent received
07-15 15:20:29.293  4993  4993 D [MirrorLinkServer]MirrorLinkServer: Counter : 1
07-15 15:20:29.293  4993  4993 D [MirrorLinkServer]MirrorLinkConnectionReceiver: notifyMlSevrer
07-15 15:20:29.293  3672  4136 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,07-15 15:20:29.293  3175  3175 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
,07-15 15:20:29.293  3175  3175 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
07-15 15:20:29.303  1112  2932 W SystemReader: Cannot find grip_rejection_width, use default value instead
07-15 15:20:29.303  4261  4717 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-15 15:20:29.303  1112  1134 D PMS     : acquireWL(13aa8e99): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 4261 10020 WorkSource{10020 com.google.android.gms}
07-15 15:20:29.303  3672  4136 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
07-15 15:20:29.303  1112  3712 D PMS     : releaseWL(13aa8e99): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10020 com.google.android.gms}
07-15 15:20:29.303  4993  4993 I [MirrorLinkServer]MirrorLinkServer: onStartCommand() Action : android.intent.action.PACKAGE_REMOVED
07-15 15:20:29.313  4993  4993 D [MirrorLinkServer]MirrorLinkServer: Application Removed
07-15 15:20:29.313  4993  4993 D [MirrorLinkServer]MirrorLinkServer:  Application removed : com.test.thalitest
07-15 15:20:29.313  4993  4993 D [MirrorLinkServer]d: onApplicationRemoved
07-15 15:20:29.313  4993  4993 I [MirrorLinkServer]d: Package name found : com.test.thalitest
,07-15 15:20:29.313  3672  4136 D AccTypeManager: Registering external account type=com.google.android.gm.exchange, packageName=com.google.android.gm
07-15 15:20:29.313  4993  8315 I [MirrorLinkServer]c: onApplicationUpdationCompleted, sending broadcast
,07-15 15:20:29.313  4993  4993 I [MirrorLinkServer]MirrorLinkServer: Broadcast Received::Intent { act=com.htc.HTCMirrorLinkServer.PACKAGE_UPDATE_COMPLETED }
07-15 15:20:29.313  4993  4993 D [MirrorLinkServer]MirrorLinkServer: ML_PACKAGE_UPDATE_COMPLETED intent received
07-15 15:20:29.313  4993  4993 D [MirrorLinkServer]MirrorLinkServer: Counter : 0
07-15 15:20:29.313  1112  2937 D PMS     : acquireWL(3008560c): PARTIAL_WAKE_LOCK  NetworkStats 0x1 1112 1000 null
07-15 15:20:29.313  4993  4993 I [MirrorLinkServer]MirrorLinkConnectionReceiver: checkAndStopMLSession
,07-15 15:20:29.313  4993  4993 I [MirrorLinkServer]MirrorLinkConnectionReceiver: Stopping Service
,07-15 15:20:29.333  1112  2952 V NetworkPolicy: ACTION_UID_REMOVED for uid=10000
,07-15 15:20:29.333  1112  1146 I InputMethodManagerService: [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false,
,07-15 15:20:29.343  3672  4136 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,07-15 15:20:29.363  3672  4136 E ExternalAccountType: Unsupported attribute readOnly,
07-15 15:20:29.363  1112  2937 D PMS     : releaseWL(3008560c): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
07-15 15:20:29.363  1112  2952 V NetworkPolicy: writePolicyLocked()
,07-15 15:20:29.373  3409  3409 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,07-15 15:20:29.373  1112  2952 D NetworkPolicy: notifyPoliciesChangeLocked: no change,
07-15 15:20:29.373  1112  2952 V NetworkPolicy: updateNetworkEnabledLocked()
07-15 15:20:29.373  1112  2952 V NetworkPolicy: updateNotificationsLocked()
,07-15 15:20:29.403  3446  4725 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1468588829409
,07-15 15:20:29.413  3446  4291 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1468588829423,
,07-15 15:20:29.423  3446  3903 I ContextualWidget: handleMessage, what=1017 mode=GettingOut maxcount=8
07-15 15:20:29.423  1112  3698 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-15 15:20:29.423  1112  3775 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
07-15 15:20:29.423  1112  3824 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
07-15 15:20:29.423  1112  3438 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
07-15 15:20:29.433  3446  3903 I ContextualWidget: handleMessage, what=1019 mode=GettingOut maxcount=8
,07-15 15:20:29.433  1112  1146 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,07-15 15:20:29.433  3446  3446 I ContextualWidget: notifyDataChanged, pos=6 item=FolderInfo: Recent downloads, app folderId da7ee82e-78ab-45e2-8f6f-80e40503c366, (Item(id=-1 type=6 container=-200 screen=-1 cellX=-1 cellY=-1 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0}))
07-15 15:20:29.433  3446  3446 I HtcContextualWidgetDataManager: onDataChanged: GettingOut, position: 6, item:[FolderInfo: Recent downloads, app folderId da7ee82e-78ab-45e2-8f6f-80e40503c366, (Item(id=-1 type=6 container=-200 screen=-1 cellX=-1 cellY=-1 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0}))]
,07-15 15:20:29.443  1112  1112 W PackageManager: Unable to load service info ResolveInfo{29a50abe com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
07-15 15:20:29.443  1112  1112 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
07-15 15:20:29.443  1112  1112 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:509)
07-15 15:20:29.443  1112  1112 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:345)
07-15 15:20:29.443  1112  1112 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:171)
07-15 15:20:29.443  1112  1112 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:71)
07-15 15:20:29.443  1112  1112 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:180)
07-15 15:20:29.443  1112  1112 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:927)
07-15 15:20:29.443  1112  1112 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
07-15 15:20:29.443  1112  1112 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-15 15:20:29.443  1112  1112 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
07-15 15:20:29.443  1112  1112 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:331)
07-15 15:20:29.443  1112  1112 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:232)
07-15 15:20:29.443  1112  1112 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
07-15 15:20:29.443  1112  1112 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-15 15:20:29.443  1112  1112 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
07-15 15:20:29.443  1112  1112 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
,07-15 15:20:29.493  1112  1190 I art     : Explicit concurrent mark sweep GC freed 21890(1842KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 17MB/26MB, paused 3.195ms total 184.316ms
,07-15 15:20:29.533  3446  4291 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1468588829537
,07-15 15:20:29.533  3446  8317 D HtcTelephonyManager: wrong phone slot in non-dual projects
07-15 15:20:29.533  8293  8293 I art     : System.exit called, status: 0
07-15 15:20:29.533  8293  8293 W HTCLOG  : use specified tag [Vector], func [0].
07-15 15:20:29.533  8293  8293 W HTCLOG  : mask=0x18
07-15 15:20:29.543  3446  4139 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1468588829554
07-15 15:20:29.553  6473  6560 I Icing   : Indexing done CF3FE6BD92DAECCC594E8F8BDE8C89D040E637CF
,07-15 15:20:29.593  1112  3443 D PMS     : releaseWL(354b24ab): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10020 com.google.android.gms},
,07-15 15:20:29.593  3380  3380 D Nfc-Utils: isNxpCodebase: isNxp=false
,07-15 15:20:29.633  3446  3446 I ContextualWidget: updateItemPosition item size=8   {-1740867511=7, -696942466=4, -335140367=0, -700633570=6, 956745593=1, 1475455068=3, 534392203=5, -33266553=2},
07-15 15:20:29.633  3446  3903 I ContextualWidget: handleMessage, what=1028 mode=GettingOut maxcount=8
,07-15 15:20:29.643  3446  8317 D HtcTelephonyManager: wrong phone slot in non-dual projects,
07-15 15:20:29.643  1112  1112 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,07-15 15:20:29.663  3446  4139 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1468588829664
,07-15 15:20:29.673  3446  4223 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
,07-15 15:20:29.693  3446  4640 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1468588829694
,07-15 15:20:29.693  3446  4640 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml.bak
,07-15 15:20:29.733  8272  8325 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
07-15 15:20:29.733  8272  8325 W HTCLOG  : mask=0x18
,07-15 15:20:29.743  8272  8325 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
07-15 15:20:29.743  8272  8325 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-15 15:20:29.743  8272  8325 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-15 15:20:29.743  8272  8325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-15 15:20:29.743  8272  8325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-15 15:20:29.743  8272  8325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-15 15:20:29.743  8272  8325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-15 15:20:29.743  8272  8325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-15 15:20:29.743  8272  8325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-15 15:20:29.743  8272  8325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-15 15:20:29.743  8272  8325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-15 15:20:29.743  8272  8325 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-15 15:20:29.743  8272  8325 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-15 15:20:29.743  8272  8325 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-15 15:20:29.743  8272  8325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-15 15:20:29.743  8272  8325 E SQLiteDatabase: 	at abs.getWritableDatabase(DatabaseHelper.java:237)
07-15 15:20:29.743  8272  8325 E SQLiteDatabase: 	at abo.a(AbstractDatabaseInstance.java:478)
07-15 15:20:29.743  8272  8325 E SQLiteDatabase: 	at abo.a(AbstractDatabaseInstance.java:473)
07-15 15:20:29.743  8272  8325 E SQLiteDatabase: 	at aoJ$a.a(Suppliers.java:125)
07-15 15:20:29.743  8272  8325 E SQLiteDatabase: 	at abp.run(AbstractDatabaseInstance.java:492)
07-15 15:20:29.753  8272  8325 E CAKEMIX_CRASHED: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-15 15:20:29.753  8272  8325 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-15 15:20:29.753  8272  8325 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-15 15:20:29.753  8272  8325 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-15 15:20:29.753  8272  8325 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-15 15:20:29.753  8272  8325 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-15 15:20:29.753  8272  8325 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-15 15:20:29.753  8272  8325 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-15 15:20:29.753  8272  8325 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-15 15:20:29.753  8272  8325 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-15 15:20:29.753  8272  8325 E CAKEMIX_CRASHED: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-15 15:20:29.753  8272  8325 E CAKEMIX_CRASHED: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-15 15:20:29.753  8272  8325 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-15 15:20:29.753  8272  8325 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-15 15:20:29.753  8272  8325 E CAKEMIX_CRASHED: 	at abs.getWritableDatabase(DatabaseHelper.java:237)
07-15 15:20:29.753  8272  8325 E CAKEMIX_CRASHED: 	at abo.a(AbstractDatabaseInstance.java:478)
07-15 15:20:29.753  8272  8325 E CAKEMIX_CRASHED: 	at abo.a(AbstractDatabaseInstance.java:473)
07-15 15:20:29.753  8272  8325 E CAKEMIX_CRASHED: 	at aoJ$a.a(Suppliers.java:125)
07-15 15:20:29.753  8272  8325 E CAKEMIX_CRASHED: 	at abp.run(AbstractDatabaseInstance.java:492)
,07-15 15:20:29.763  3446  4640 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1468588829769
,07-15 15:20:29.763  1112  3247 I ActivityManager: START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10090 pid 8272 on display 0,
07-15 15:20:29.773  1112  3247 V WindowManager: addAppToken: AppWindowToken{33f9191d token=Token{3c12df4 ActivityRecord{1a31c3c7 u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t125}}} to stack=1 task=125 at 0
07-15 15:20:29.773  1112  3247 D PMS     : acquireWL(1024b792): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 1112 1000 null
07-15 15:20:29.773  1112  1169 I AnimationUtil: isHTCRecent(Drive/Recents screens.)/3
,07-15 15:20:29.773  8272  8325 D Process : killProcess, pid=8272,
07-15 15:20:29.773  8272  8325 D Process : jG.uncaughtException:164 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
07-15 15:20:29.773  8272  8325 W HTCLOG  : use specified tag [Process], func [0].
07-15 15:20:29.773  8272  8325 W HTCLOG  : mask=0x18
07-15 15:20:29.773  3446  3446 I FeedHostManager: [onPause]
07-15 15:20:29.773  3446  3446 I FeedProviderManager: onPause
07-15 15:20:29.773  3446  3446 I FeedHostManager: [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@2cf7b092
07-15 15:20:29.773  3446  4830 I SocialFeedProvider: +onPause
07-15 15:20:29.773  3446  4830 I SocialFeedProvider: -onPause
,07-15 15:20:29.783  3446  3446 I ContextualWidget: onPause
07-15 15:20:29.783  3446  3446 I ContextualWidget: notifyWidgetDeactive
07-15 15:20:29.783  1112  3438 W HTCLOG  : use specified tag [JavaBinder], func [0].,
07-15 15:20:29.783  1112  3438 W HTCLOG  : mask=0x18
07-15 15:20:29.783  1112  3438 E ActivityManager: TransactionSize: scheduleLaunchActivity(), TransactionTooLargeException, data size = 4220, Intent = Intent { act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras) }
07-15 15:20:29.783  1112  3438 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
07-15 15:20:29.783  1112  3438 W ActivityManager: Exception when starting activity com.google.android.apps.docs/.app.ErrorNotificationActivity
07-15 15:20:29.783  1112  3438 W ActivityManager: android.os.TransactionTooLargeException
,07-15 15:20:29.783  1112  3438 W ActivityManager: ,	at android.os.BinderProxy.transactNative(Native Method)
07-15 15:20:29.783  1112  3438 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:504)
07-15 15:20:29.783  1112  3438 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleLaunchActivity(ApplicationThreadNative.java:855)
07-15 15:20:29.783  1112  3438 W ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.realStartActivityLocked(ActivityStackSupervisor.java:1227)
07-15 15:20:29.783  1112  3438 W ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1327)
07-15 15:20:29.783  1112  3438 W ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:1994)
07-15 15:20:29.783  1112  3438 W ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1536)
07-15 15:20:29.783  1112  3438 W ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2575)
07-15 15:20:29.783  1112  3438 W ActivityManager: 	at com.android.server.am.ActivityStack.completePauseLocked(ActivityStack.java:1039)
07-15 15:20:29.783  1112  3438 W ActivityManager: 	at com.android.server.am.ActivityStack.activityPausedLocked(ActivityStack.java:937)
07-15 15:20:29.783  1112  3438 W ActivityManager: 	at com.android.server.am.ActivityManagerService.activityPaused(ActivityManagerService.java:6757)
07-15 15:20:29.783  1112  3438 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:519)
07-15 15:20:29.783  1112  3438 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
07-15 15:20:29.783  1112  3438 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:454)
07-15 15:20:29.783  3446  4398 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1468588829786
07-15 15:20:29.783  3446  4398 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml.bak
,07-15 15:20:29.783  1112  1169 V WindowManager: Adding window Window{53547b6 u0 Starting com.google.android.apps.docs} at 2 of 7 (after Window{3ae9e78f u0 com.htc.launcher/com.htc.launcher.Launcher})
,07-15 15:20:29.853  3446  8317 D libc    : [NET] android_getaddrinfofornet+,hn 28(0x7265636f6d6d65),sn(),hints(known),family 0,flags 4,
07-15 15:20:29.853  3446  8317 D libc    : [NET] android_getaddrinfofornet-, err=8
07-15 15:20:29.853  3446  8317 D libc    : [NET] android_getaddrinfofornet+,hn 28(0x7265636f6d6d65),sn(),hints(known),family 0,flags 1024
07-15 15:20:29.853  3446  8317 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
07-15 15:20:29.853  3446  8317 D libc    : [NET] android_getaddrinfo_proxy+
07-15 15:20:29.853  3446  8317 D libc    : [NET] android_getaddrinfo_proxy get netid:0
,07-15 15:20:29.853   525  8328 D libc    : [NET] android_getaddrinfofornet+,hn 28(0x7265636f6d6d65),sn(),hints(known),family 0,flags 1024,
07-15 15:20:29.853   525  8328 D libc    : [NET] _dns_getaddrinfo+, netid:0, mark:917504
,07-15 15:20:29.853   525  8328 D libc    : [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
07-15 15:20:29.853   525  8328 D libc    : [NET] android_getaddrinfofornet-, err=7
,07-15 15:20:29.853  3446  8317 D libc    : [NET] android_getaddrinfo_proxy-, NODATA
07-15 15:20:29.853  3446  8317 E ServerCorridor: BaseException: ServiceUnavailableException java.lang.Throwable: Unable to resolve host "recommend-prism.htcsense.com": No address associated with hostname
07-15 15:20:29.853  3446  8317 W System.err: com.htc.prism.feed.corridor.exceptions.ServiceUnavailableException: java.lang.Throwable: Unable to resolve host "recommend-prism.htcsense.com": No address associated with hostname
07-15 15:20:29.853  3446  8317 W System.err: 	at com.htc.prism.feed.corridor.RestClient.sendHTTPRequest(RestClient.java:192)
07-15 15:20:29.853  3446  8317 W System.err: 	at com.htc.prism.feed.corridor.RestClient.sendHTTPRequest(RestClient.java:98)
07-15 15:20:29.853  3446  8317 W System.err: 	at com.htc.prism.feed.corridor.RestClient.getString(RestClient.java:367)
07-15 15:20:29.853  3446  8317 W System.err: 	at com.htc.prism.feed.corridor.recommendation.RecommendationNService.getWelcomeAppSuggest(RecommendationNService.java:125)
07-15 15:20:29.853  3446  8317 W System.err: 	at com.htc.launcher.htcwidget.HtcContextualWidgetService.syncRecommendedApps(HtcContextualWidgetService.java:374)
07-15 15:20:29.853  3446  8317 W System.err: 	at com.htc.launcher.htcwidget.HtcContextualWidgetService.onHandleIntent(HtcContextualWidgetService.java:168)
07-15 15:20:29.853  3446  8317 W System.err: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65),
07-15 15:20:29.853  3446  8317 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-15 15:20:29.853  3446  8317 W System.err: 	at android.os.Looper.loop(Looper.java:155),
07-15 15:20:29.853  3446  8317 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-15 15:20:29.853  3446  8317 W System.err: Caused by: java.lang.Throwable: Unable to resolve host "recommend-prism.htcsense.com": No address associated with hostname
07-15 15:20:29.853  3446  8317 W System.err: 	at java.net.InetAddress.lookupHostByName(InetAddress.java:457),
07-15 15:20:29.853  3446  8317 W System.err: 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
07-15 15:20:29.853  3446  8317 W System.err: 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
07-15 15:20:29.853  3446  8317 W System.err: 	at com.android.okhttp.HostResolver$1.getAllByName(HostResolver.java:29)
07-15 15:20:29.853  3446  8317 W System.err: 	at com.android.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:232)
07-15 15:20:29.853  3446  8317 W System.err: 	at com.android.okhttp.internal.http.RouteSelector.next(RouteSelector.java:124)
,07-15 15:20:29.853  3446  8317 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:272)
07-15 15:20:29.853  3446  8317 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:211)
07-15 15:20:29.853  3446  8317 W System.err: 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:403)
07-15 15:20:29.853  3446  8317 W System.err: 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.connect(HttpURLConnectionImpl.java:116)
07-15 15:20:29.853  3446  8317 W System.err: 	at com.android.okhttp.internal.http.DelegatingHttpsURLConnection.connect(DelegatingHttpsURLConnection.java:89)
07-15 15:20:29.853  3446  8317 W System.err: 	at com.android.okhttp.internal.http.HttpsURLConnectionImpl.connect(HttpsURLConnectionImpl.java:25)
07-15 15:20:29.853  3446  8317 W System.err: 	at com.htc.prism.feed.corridor.RestClient.sendHTTPRequest(RestClient.java:137)
07-15 15:20:29.853  3446  8317 W System.err: 	... 9 more
,07-15 15:20:29.853  3446  3783 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/com.htc.launcher.prefs.contextualwidget.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/com.htc.launcher.prefs.contextualwidget.xml.bak
07-15 15:20:29.863  3446  4398 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1468588829866
,07-15 15:20:29.873  3446  4399 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
,07-15 15:20:29.883  3446  4388 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1468588829889
,07-15 15:20:29.883  1112  1134 I ActivityManager: Recipient 8272
,07-15 15:20:29.893  3446  4388 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml.bak
,07-15 15:20:29.943  3446  4388 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1468588829953
,07-15 15:20:29.953  3446  4190 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1468588829963
,07-15 15:20:29.963  3446  4190 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml.bak
,07-15 15:20:30.003  1112  3438 I ActivityManager: Start proc 8329:com.google.android.apps.docs/u0a90 for activity com.google.android.apps.docs/.app.ErrorNotificationActivity
,07-15 15:20:30.003  1112  3522 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true,
,07-15 15:20:30.013  1112  1134 W ActivityManager: Spurious death for ProcessRecord{32fddd53 8329:com.google.android.apps.docs/u0a90}, curProc for 8272: null
,07-15 15:20:30.013  8329  8329 W HTCLOG  : use specified tag [FDManager], func [0].
07-15 15:20:30.013  8329  8329 W HTCLOG  : mask=0x18,
07-15 15:20:30.023  3446  3866 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,07-15 15:20:30.023  3446  3866 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@3c5fe8ee +
07-15 15:20:30.023  3446  3866 I Prism.WidgetManager: onLoadItems() +
07-15 15:20:30.023  1112  3698 D PMS     : acquireWL(29a5cb89): PARTIAL_WAKE_LOCK  AsyncService 0x1 8094 10126 null
07-15 15:20:30.023  1112  3442 D PMS     : releaseWL(29a5cb89): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,07-15 15:20:30.053  1112  1148 D StatusBarManagerService: setSystemUiVisibility(0x8600)
07-15 15:20:30.053  1112  1148 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{53547b6 u0 Starting com.google.android.apps.docs}
07-15 15:20:30.053  1112  1148 D StatusBarManagerService: hiding MENU key
,07-15 15:20:30.053  3097  3097 I PhoneStatusBar: setSystemUiNavVisibility(swipe=false hasFocus=false hasPolicy=false shadeState=true)
07-15 15:20:30.053  3097  3097 I PhoneStatusBar: hiding the MENU button mLongPressHomeMenu = false
07-15 15:20:30.053  3446  3446 I TrimMemoryManager: [trimMemory] 20
,07-15 15:20:30.093  3446  4190 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1468588830101
,07-15 15:20:30.093  8329  8329 D DocsApplication: Plugin installer initialized.
,07-15 15:20:30.103  8329  8329 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{1be7a3a0 com.google.android.apps.docs},
07-15 15:20:30.113  6473  8127 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
07-15 15:20:30.113  6473  8126 E IntentOperationSvc: Failed to instantiate Chimera operation impl, dropping operation
,07-15 15:20:30.113  8329  8329 D TAG     : onCreate(),
07-15 15:20:30.113  6473  8127 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
07-15 15:20:30.113  6473  6473 D AsyncTaskServiceImpl: Submit a task: nwp
,07-15 15:20:30.123  3446  4196 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.,
07-15 15:20:30.123  8329  8329 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,07-15 15:20:30.133  1112  3443 D PMS     : acquireWL(e7d0a66): PARTIAL_WAKE_LOCK  Icing 0x1 6473 10020 WorkSource{10020 com.google.android.gms}
07-15 15:20:30.133  1112  3775 I ActivityManager: Delay finish: com.google.android.gms/.gcm.GcmPackageTracker$GcmPackageChangeReceiver
07-15 15:20:30.143  6473  8127 E Vision  : Failed to find package com.test.thalitest
07-15 15:20:30.143  6473  7784 E WorkSourceUtil: Could not find package: com.test.thalitest
07-15 15:20:30.143  6473  8127 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
07-15 15:20:30.143  6473  6560 E Icing   : Package com.test.thalitest not found
07-15 15:20:30.143  6473  6547 D nwp     : Processing package: com.test.thalitest
07-15 15:20:30.143  1112  3712 I ActivityManager: Resuming delayed broadcast
07-15 15:20:30.153  6473  7167 W FileUtils: Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
07-15 15:20:30.153  6473  7167 E IcingInternalCorpora: Failed to open Apps corpus file.
07-15 15:20:30.153  6473  6547 W nwp     : Failed to find package com.test.thalitest
07-15 15:20:30.153  1112  3442 D PMS     : releaseWL(e7d0a66): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10020 com.google.android.gms}
07-15 15:20:30.163  3446  4725 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1468588830165
07-15 15:20:30.163  6473  7167 E IcingInternalCorpora: Failed to append to component name file.
,07-15 15:20:30.173  3446  4725 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml.bak
,07-15 15:20:30.273  1112  1134 D PMS     : acquireWL(1888c143): PARTIAL_WAKE_LOCK  Icing 0x1 6473 10020 WorkSource{10020 com.google.android.gms}
07-15 15:20:30.283  8129  8129 I Finsky  : [1] com.google.android.finsky.utils.bh.run(2302): Package state data is missing for com.test.thalitest
07-15 15:20:30.283  1112  3510 I ActivityManager: Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
07-15 15:20:30.283  1112  3442 I ActivityManager: Resuming delayed broadcast
07-15 15:20:30.293  3446  4725 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1468588830298
07-15 15:20:30.293  8129  8178 E PlayEventLogger: Could not write string (f <
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   d: 12602035
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   d: 12602049
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   d: 12602392
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   d: 12602748
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   d: 12602761
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   d: 12602795
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   d: 12602981
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   d: 12603067
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   d: 12603111
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   d: 12603130
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   d: 12603146
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   d: 12603248
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   d: 12603380
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   d: 12603385
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   d: 12603394
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   d: 12603428
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   d: 12603513
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   d: 12603787
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   d: 12603788
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   d: 12603791
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   d: 12603948
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   d: 12604059
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   d: 12604230
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   d: 12604266
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   d: 12604267
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   d: 12605120
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   d: 12605124
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   d: 12605176
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   d: 12605260
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   d: 12605398
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   d: 12605423
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   d: 12605501
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   d: 12605523
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   d: 12605524
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   d: 12605728
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   d: 12605742
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   d: 12606629
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   d: 12606756
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   d: 12607045
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   d: 12608262
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   d: 12608625
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   d: 12608685
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   d: 12609286
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 18
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 19
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 20
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 21
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 24
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 35
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 113
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 241
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 254
07-15 15:20:30.293  812,9  8178 E PlayEventLogger:   e: 259
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 299
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 580
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 739
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 741
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 744
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 748
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 793
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 855
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 910
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602000
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602001
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602002
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602005
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602007
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602010
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602011
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602020
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602028
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602036
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602037
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602038
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602040
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602044
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602048
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602051
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602052
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602053
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602055
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602056
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602057
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602062
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602063
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602064,
,07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602068
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602073
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602091
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602092
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602093
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602098
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602104
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602106
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602117
,07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602120
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602123
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602125
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602128
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602142
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602143
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602144
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602145
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602150
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602152
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602155
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602314
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602322
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602350
,07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602351
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602370
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602373
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602377
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602418
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602430
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602623
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602797
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602825
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602826
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602827,
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602837
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12602993
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12603044
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12603068
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12603101
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12603131
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12603152
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12603159,
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12603193
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12603406
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12603505
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12603514
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12603602
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12603630
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12603633
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12603729
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12603746
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12603763
,07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12603767
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12603794
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12603844
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12603930
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12603954
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12604079
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12604087
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12604095
,07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12604130
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12604138
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12604155
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12604158
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12604189
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12604384
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12604399
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12604451
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12604484
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12604501
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12604505
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12604579
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12604694
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12604988
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12605043
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12605377
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12605384
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12605522
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12605545
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12605550
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12605559
,07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12605560
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12605600
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12605655
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12605739
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12605740
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12605756
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12605782
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12605861
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12605897
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12605904
,07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12605959
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12606001
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12606111
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12606652
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12606678
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12606696
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12606712
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12606747
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12606797
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12606798
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12606827
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12606831
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12606832
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12607164
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12607166
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12607168
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12607194
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12607522
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12607552
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12607597
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12607602
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12607619
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12607654
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12607793
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12607797
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12607830
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12608140
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12608330
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12608433
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12608484
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12608504
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12608565
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12608566
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12608705
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12608798
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12608810
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12608875
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12608953
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12608966
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12609048
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12609051
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12609116
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12609148
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12609211
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12609245
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12609308
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12609441
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12609451
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12609456
,07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12609469
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12609523
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12609639
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12609714
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12609733
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12609777
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12609808
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12609860
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12609920
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12609925
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12609941
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12610003
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12610004
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12610082
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12610147
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12610193
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12610199
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12610262
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12610265
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12610302
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12610305
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12610348
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12610392
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12610428
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12610430
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12610440
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12610449
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12610551
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12610552
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12610553
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12610554
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12610605
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12610690
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12610694
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12610733
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12610899
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12610900
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12611011
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12611013
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12611090
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12611132
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12611188
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12611279
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12611292
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12611454
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12611458
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12611464
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   e: 12611558
07-15 15:20:30.293  8129  8178 E PlayEventLogger:   a_b: 1325
07-15 15:20:30.293  8129  8178 E PlayEventLogger: >
07-15 15:20:30.293  8129  8178 E PlayEventLogger: a_b: 1389
07-15 15:20:30.293  8129  8178 E PlayEventLogger: ) to file: write failed: EBADF (Bad file number)
07-15 15:20:30.293  8129  8178 E PlayEventLogger: java.io.IOException: write failed: EBADF (Bad file number)
07-15 15:20:30.293  8129  8178 E PlayEventLogger: 	at libcore.io.IoBridge.write(IoBridge.java:502)
07-15 15:20:30.293  8129  8178 E PlayEventLogger: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
07-15 15:20:30.293  8129  8178 E PlayEventLogger: 	at java.io.FileOutputStream.write(FileOutputStream.
07-15 15:20:30.293  4261  4261 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/ns.db'.
07-15 15:20:30.293  4261  4261 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in r,ead/write mode.
07-15 15:20:30.293  4261  4261 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-15 15:20:30.293  4261  4261 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-15 15:20:30.293  4261  4261 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-15 15:20:30.293  4261  4261 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-15 15:20:30.293  4261  4261 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-15 15:20:30.293  4261  4261 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-15 15:20:30.293  4261  4261 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-15 15:20:30.293  4261  4261 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-15 15:20:30.293  4261  4261 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-15 15:20:30.293  4261  4261 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-15 15:20:30.293  4261  4261 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1275)
07-15 15:20:30.293  4261  4261 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:262)
07-15 15:20:30.293  4261  4261 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:262)
07-15 15:20:30.293  4261  4261 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:262)
07-15 15:20:30.293  4261  4261 E SQLiteDatabase: 	at irl.c(:com.google.android.gms:216)
07-15 15:20:30.293  4261  4261 E SQLiteDatabase: 	at irl.d(:com.google.android.gms:187)
07-15 15:20:30.293  4261  4261 E SQLiteDatabase: 	at irg.a(:com.google.android.gms:22519)
07-15 15:20:30.293  4261  4261 E SQLiteDatabase: 	at obo.b(:com.google.android.gms:335)
07-15 15:20:30.293  4261  4261 E SQLiteDatabase: 	at obl.a(:com.google.android.gms:479)
07-15 15:20:30.293  4261  4261 E SQLiteDatabase: 	at obl.a(:com.google.android.gms:462)
07-15 15:20:30.293  4261  4261 E SQLiteDatabase: 	at com.google.android.gms.gcm.nts.SchedulerChimeraReceiver.onReceive(:com.google.android.gms:12258)
07-15 15:20:30.293  4261  4261 E SQLiteDatabase: 	at com.google.android.chimera.container.BroadcastReceiverProxy.onReceive(:com.google.android.gms:114)
07-15 15:20:30.293  4261  4261 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
07-15 15:20:30.293  4261  4261 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
07-15 15:20:30.293  4261  4261 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
07-15 15:20:30.293  4261  4261 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-15 15:20:30.293  4261  4261 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
07-15 15:20:30.293  4261  4261 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
07-15 15:20:30.293  4261  4261 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-15 15:20:30.293  4261  4261 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-15 15:20:30.293  4261  4261 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
07-15 15:20:30.293  4261  4261 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
07-15 15:20:30.333  1112  8355 E DropBoxManagerService: Can't write: system_app_crash
07-15 15:20:30.333  1112  8355 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
07-15 15:20:30.333  1112  8355 E DropBoxMa,nagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-15 15:20:30.333  1112  8355 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-15 15:20:30.333  1112  8355 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-15 15:20:30.333  1112  8355 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
07-15 15:20:30.333  1112  8355 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-15 15:20:30.333  1112  8355 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
07-15 15:20:30.333  1112  8355 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-15 15:20:30.333  1112  8355 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-15 15:20:30.333  1112  8355 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-15 15:20:30.333  1112  8355 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-15 15:20:30.333  1112  8355 E DropBoxManagerService: 	... 5 more
07-15 15:20:30.313  3446  4390 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1468588830323
07-15 15:20:30.323  4261  4261 I GCore-Chimera-Crash: Cg0KB3ZJbmZyYTQQor84Gl8KHWNvbS5nb29nbGUuYW5kcm9pZC
07-15 15:20:30.323  4261  4261 I GCore-Chimera-Crash: 5wbGF5LmdhbWVzEhQzLjcuMjMgKDI4Njc2MzctMDQ4KRjgq-AR
07-15 15:20:30.323  4261  4261 I GCore-Chimera-Crash: IiMKHGNvbS5nb29nbGUuYW5kcm9pZC5nbXMuZ2FtZXMQsKvgEQ
07-15 15:20:30.323  4261  4261 I GCore-Chimera-Crash: ==
07-15 15:20:30.323  4261  4261 I GCore-Chimera-Crash: GCore-Chimera-Crash
07-15 15:20:30.323  4261  4261 E AndroidRuntime: FATAL EXCEPTION: main
07-15 15:20:30.323  4261  4261 E AndroidRuntime: Process: com.google.android.gms.persistent, PID: 4261
07-15 15:20:30.323  4261  4261 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.nts.SchedulerReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-15 15:20:30.323  4261  4261 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2733)
07-15 15:20:30.323  4261  4261 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
07-15 15:20:30.323  4261  4261 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
07-15 15:20:30.323  4261  4261 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-15 15:20:30.323  4261  4261 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
07-15 15:20:30.323  4261  4261 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
07-15 15:20:30.323  4261  4261 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-15 15:20:30.323  4261  4261 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-15 15:20:30.323  4261  4261 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
07-15 15:20:30.323  4261  4261 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
07-15 15:20:30.323  4261  4261 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-15 15:20:30.323  4261  4261 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-15 15:20:30.323  4261  4261 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-15 15:20:30.323  4261  4261 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-15 15:20:30.323  4261  4261 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-15 15:20:30.323  4261  4261 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-15 15:20:30.323  4261  4261 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-15 15:20:30.323  4261  4261 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-15 15:20:30.323  4261  4261 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-15 15:20:30.323  4261  4261 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-15 15:20:30.323  4261  4261 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-15 15:20:30.323  4261  4261 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1275)
07-15 15:20:30.323  4261  4261 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:262)
07-15 15:20:30.323  4261  4261 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:262)
07-15 15:20:30.323  4261  4261 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:262)
07-15 15:20:30.323  4261  4261 E AndroidRuntime: 	at irl.c(:com.google.android.gms:216)
07-15 15:20:30.323  4261  4261 E AndroidRuntime: 	at irl.d(:com.google.android.gms:187)
07-15 15:20:30.323  4261  4261 E AndroidRuntime: 	at irg.a(:com.google.android.gms:22519)
07-15 15:20:30.323  4261  4261 E AndroidRuntime: 	at obo.b(:com.google.android.gms:335)
07-15 15:20:30.323  4261  4261 E AndroidRuntime: 	at obl.a(:com.google.android.gms:479)
07-15 15:20:30.323  4261  4261 E AndroidRuntime: 	at obl.a(:com.google.android.gms:462)
07-15 15:20:30.323  4261  4261 E AndroidRuntime: 	at com.google.android.gms.gcm.nts.SchedulerChimeraReceiver.onReceive(:com.google.android.gms:12258)
07-15 15:20:30.323  4261  4261 E AndroidRuntime: 	at com.google.android.chimera.container.BroadcastReceiverProxy.onReceive(:com.google.android.gms:114)
07-15 15:20:30.323  4261  4261 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
07-15 15:20:30.323  4261  4261 E AndroidRuntime: 	... 9 more
07-15 15:20:30.323  1112  3775 E ActivityManager: App crashed! Process: com.google.android.gms.persistent
07-15 15:20:30.333  3446  4390 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml.bak
07-15 15:20:30.373  3446  3866 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,07-15 15:20:30.423  1112  1148 D StatusBarManagerService: setSystemUiVisibility(0x8000)
,07-15 15:20:30.423  1112  1148 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{16e3f4ee u0 Application Error: com.google.android.gms}
07-15 15:20:30.423  3097  3097 I PhoneStatusBar: setSystemUiNavVisibility(swipe=false hasFocus=false hasPolicy=false shadeState=true)
07-15 15:20:30.423  1112  1148 D StatusBarManagerService: hiding MENU key
,07-15 15:20:30.423  3097  3097 I PhoneStatusBar: hiding the MENU button mLongPressHomeMenu = false
,07-15 15:20:30.463  3446  4390 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1468588830467,
,07-15 15:20:30.483  3446  4156 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.,
,07-15 15:20:30.493  1112  1147 I ActivityManager: Waited long enough for: ServiceRecord{313d8136 u0 com.aiqidii.mercury/.service.ls.LocalServerControllerService},
,07-15 15:20:30.503  3446  4291 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1468588830506
,07-15 15:20:30.513  3446  4291 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml.bak
,07-15 15:20:30.613  3097  3097 I NotificationStackScrollLayout: setBlockTouchEnabled:false
,07-15 15:20:30.643  3446  4291 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1468588830651
,07-15 15:20:30.653  3446  3866 W asset   : Copying FileAsset 0xac4a1ca8 (zip:/data/app/com.gameloft.android.gdc-1/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,
,07-15 15:20:30.663  3446  4141 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
,07-15 15:20:30.683  3446  4223 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1468588830687
,07-15 15:20:30.683  3446  4223 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml.bak,
,07-15 15:20:30.733  3446  3866 E Prism.WidgetManager: The same lists. No need to update. skip it.
07-15 15:20:30.733  3446  3866 I Prism.WidgetManager: onLoadItems() -
,07-15 15:20:30.733  3446  3866 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@3c5fe8ee -
,07-15 15:20:30.733  3446  3866 E SQLiteLog: (3850) statement aborts at 19: [INSERT INTO appscustomize(profileId,title,customized_order,container,itemType,_id,component_name,hidden) VALUES (?,?,?,?,?,?,?,?)] disk I/O error
07-15 15:20:30.733  3446  3866 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
07-15 15:20:30.733  3446  3866 W HTCLOG  : mask=0x18
07-15 15:20:30.733  3446  3866 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.htc.launcher/databases/launcher.db, handle: 0xabe6a108
,07-15 15:20:30.733  3446  3866 E SQLiteDatabase: Error inserting ...
07-15 15:20:30.733  3446  3866 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-15 15:20:30.733  3446  3866 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
07-15 15:20:30.733  3446  3866 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
07-15 15:20:30.733  3446  3866 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
07-15 15:20:30.733  3446  3866 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
07-15 15:20:30.733  3446  3866 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1570)
07-15 15:20:30.733  3446  3866 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1425)
07-15 15:20:30.733  3446  3866 E SQLiteDatabase: 	at com.htc.launcher.LauncherProvider.dbInsertAndCheck(LauncherProvider.java:313)
07-15 15:20:30.733  3446  3866 E SQLiteDatabase: 	at com.htc.launcher.LauncherProvider.insert(LauncherProvider.java:341)
07-15 15:20:30.733  3446  3866 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:246)
07-15 15:20:30.733  3446  3866 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1272)
07-15 15:20:30.733  3446  3866 E SQLiteDatabase: 	at com.htc.launcher.pageview.RearrangeDBHelper$1.run(RearrangeDBHelper.java:112)
07-15 15:20:30.733  3446  3866 E SQLiteDatabase: 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
07-15 15:20:30.733  3446  3866 E SQLiteDatabase: 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
07-15 15:20:30.733  3446  3866 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-15 15:20:30.733  3446  3866 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
07-15 15:20:30.733  3446  3866 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-15 15:20:30.743  3446  3866 E SQLiteLog: (3850) statement aborts at 19: [INSERT INTO appscustomize(profileId,title,customized_order,container,itemType,_id,component_name,hidden) VALUES (?,?,?,?,?,?,?,?)] disk I/O error
07-15 15:20:30.743  3446  3866 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.htc.launcher/databases/launcher.db, handle: 0xabe6a108
07-15 15:20:30.743  3446  3866 E SQLiteDatabase: Error inserting ...
07-15 15:20:30.743  3446  3866 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-15 15:20:30.743  3446  3866 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
07-15 15:20:30.743  3446  3866 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
07-15 15:20:30.743  3446  3866 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
07-15 15:20:30.743  3446  3866 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
07-15 15:20:30.743  3446  3866 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1570)
07-15 15:20:30.743  3446  3866 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1425)
07-15 15:20:30.743  3446  3866 E SQLiteDatabase: 	at com.htc.launcher.LauncherProvider.dbInsertAndCheck(LauncherProvider.java:313)
07-15 15:20:30.743  3446  3866 E SQLiteDatabase: 	at com.htc.launcher.LauncherProvider.insert(LauncherProvider.java:341)
07-15 15:20:30.743  3446  3866 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:246)
07-15 15:20:30.743  3446  3866 E SQ,LiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1272)
07-15 15:20:30.743  3446  3866 E SQLiteDatabase: 	at com.htc.launcher.pageview.RearrangeDBHelper$1.run(RearrangeDBHelper.java:118)
07-15 15:20:30.743  3446  3866 E SQLiteDatabase: 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
07-15 15:20:30.743  3446  3866 E SQLiteDatabase: 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
07-15 15:20:30.743  3446  3866 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-15 15:20:30.743  3446  3866 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
07-15 15:20:30.743  3446  3866 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-15 15:20:30.743  3446  3866 I Prism.ExternalAppState_: com.test.thalitest is not installed
07-15 15:20:30.743  3446  3866 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
07-15 15:20:30.743  3446  3866 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,07-15 15:20:30.753  3446  3446 I Launcher: Deferring update until onResume,
07-15 15:20:30.753  3446  3446 D Launcher: waitUntilResume // bindAppsRemoved
,07-15 15:20:30.783  3446  4223 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1468588830787,
,07-15 15:20:30.803  3446  4139 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
,07-15 15:20:30.823  3446  4209 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1468588830826
,07-15 15:20:30.823   500   500 E qdoverlay: validateAndSet failed, error 108: Cannot send after transport endpoint shutdown,
07-15 15:20:30.823   500   500 E qdoverlay: Bad ov dump:  mdp_overlay z=1 alpha=255 mask=-1 flags=0x220000 id=8
07-15 15:20:30.823   500   500 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888,
07-15 15:20:30.823   500   500 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
07-15 15:20:30.823   500   500 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
07-15 15:20:30.823   500   500 E qdoverlay: validateAndSet failed, error 108: Cannot send after transport endpoint shutdown
,07-15 15:20:30.823   500   500 E qdoverlay: Bad ov dump:  mdp_overlay z=0 alpha=255 mask=-1 flags=0x220000 id=8
07-15 15:20:30.823   500   500 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
07-15 15:20:30.823   500   500 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
07-15 15:20:30.823   500   500 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
,07-15 15:20:30.823   500   500 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Cannot send after transport endpoint shutdown
07-15 15:20:30.823   500   500 E qdoverlay: MdpCtrl close error in unset,
,07-15 15:20:30.833  3446  4209 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml.bak
,07-15 15:20:30.853   500   836 E qdhwcomposer: hwc_vsync_control: vsync control failed. Dpy=0, enable=0 : Cannot send after transport endpoint shutdown
,07-15 15:20:30.853   500   836 E SurfaceFlinger: eventControl(0, 0) failed Cannot send after transport endpoint shutdown
,07-15 15:20:30.883  3446  4209 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1468588830893,
,07-15 15:20:30.893  3446  4640 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1468588830903,
,07-15 15:20:30.903  3446  4640 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml.bak
,07-15 15:20:30.963   500   500 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Cannot send after transport endpoint shutdown
07-15 15:20:30.963   500   500 E qdoverlay: MdpCtrl close error in unset,
,07-15 15:20:30.993  3446  4640 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1468588830995

```
