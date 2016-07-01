#### Test 757892680c366d1_thali06_HTC-HTC One M9 Logs


```
--------- beginning of main
07-01 12:06:56.093  6718  8116 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
--------- beginning of system
07-01 12:06:56.093  1114  3962 D PMS     : releaseWL(40bfdec): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10020 com.google.android.gms}
07-01 12:06:56.093  1114  3660 I ActivityManager: Resuming delayed broadcast
07-01 12:06:56.113  1114  1134 D PMS     : acquireWL(3adf344a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4270 10020 WorkSource{10020 com.google.android.gms}
07-01 12:06:56.143  1114  3923 D PMS     : releaseWL(3adf344a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10020 com.google.android.gms}
07-01 12:06:56.173  1114  3670 D PMS     : acquireWL(e33ffbb): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4270 10020 WorkSource{10020 com.google.android.gms},
07-01 12:06:56.173  6718  6718 I CmaSystemUpdateService: receiver: Intent { act=com.google.android.gms.update.BOOT_START_SERVICE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.update.SystemUpdateServiceReceiver }
07-01 12:06:56.193  6718  6718 I CmaSystemUpdateService: receiver: Intent { act=com.google.android.gms.update.BOOT_START_SERVICE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.update.SystemUpdateServiceReceiver }
07-01 12:06:56.193  1114  3670 D PMS     : acquireWL(29b10cd8): PARTIAL_WAKE_LOCK  CmaSystemUpdateService 0x1 6718 10020 WorkSource{10020 com.google.android.gms}
07-01 12:06:56.203  1114  3937 I ActivityManager: Delay finish: com.google.android.gms/.update.SystemUpdateServiceReceiver
07-01 12:06:56.213  6718  6718 D CmaSystemUpdateService: onCreate
07-01 12:06:56.213  6718  6718 D CmaSystemUpdateService: mProcessPackageEnabled: false, mAutomaticUpdateEnabled: false
07-01 12:06:56.213  1114  3937 D PMS     : releaseWL(e33ffbb): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10020 com.google.android.gms}
07-01 12:06:56.213  6718  6718 D CmaSystemUpdateService: onStartCommand: intent: Intent { act=com.google.android.gms.update.START_SERVICE pkg=com.google.android.gms (has extras) }
07-01 12:06:56.243  6718  8121 I SystemUpdateTask: cancelUpdate (empty URL)
07-01 12:06:56.243  6718  8121 I CmaSystemUpdateService: active receiver: disabled
07-01 12:06:56.243  1114  3253 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateServiceActiveReceiver, state=2, flag=1, pid=6718, uid=10020, userID:0
07-01 12:06:56.253  6718  8121 D ChimeraResource: Successfully parsed resource with package name: com.google.android.gms and resource name drawable/notification_system_update_available
07-01 12:06:56.253  6718  8121 D ChimeraResource: Successfully parsed resource with package name: com.google.android.gms and resource name drawable/notification_system_update_download_failure
07-01 12:06:56.263  1114  3966 I ActivityManager: Resuming delayed broadcast
07-01 12:06:56.263  1114  1134 D PMS     : releaseWL(29b10cd8): PARTIAL_WAKE_LOCK  CmaSystemUpdateService 0x1 WorkSource{10020 com.google.android.gms}
07-01 12:06:56.263  6718  6718 D CmaSystemUpdateService: onDestroy
07-01 12:06:56.273  1114  3494 I ActivityManager: Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
07-01 12:06:56.293  1114  3660 I ActivityManager: Resuming delayed broadcast
07-01 12:06:56.313  1114  3670 I ActivityManager: Delay finish: com.google.android.gms/.security.snet.SnetReceiver
07-01 12:06:56.363  8122  8122 W HTCLOG  : use specified tag [AndroidRuntime], func [0].
07-01 12:06:56.363  8122  8122 W HTCLOG  : mask=0x18
07-01 12:06:56.383  1114  3966 I ActivityManager: Resuming delayed broadcast
07-01 12:06:56.403  4270  8128 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
07-01 12:06:56.433  1114  3041 D PMS     : acquireWL(2bd4c78f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4270 10020 WorkSource{10020 com.google.android.gms}
07-01 12:06:56.453  3452  5318 I SocialFeedProvider: +disConnect socialManager
07-01 12:06:56.453  3452  5318 I SocialFeedProvider: disconnect socialManager
07-01 12:06:56.463  3452  5318 I SocialFeedProvider: -disConnect socialManager
07-01 12:06:56.463  1114  1134 D PMS     : releaseWL(2bd4c78f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10020 com.google.android.gms}
07-01 12:06:56.493  1114  3494 D PMS     : acquireWL(2600ba1c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4270 10020 WorkSource{10020 com.google.android.gms}
07-01 12:06:56.523  1114  3937 D PMS     : releaseWL(2600ba1c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10020 com.google.android.gms}
07-01 12:06:56.523  8022  8067 I Babel_RequestWriter: error sending REQ[fc:5; creat:1467367599745; type:bme-795119421: userphotoalbums
07-01 12:06:56.523  8022  8067 I Babel_RequestWriter: ProtoBuf:
07-01 12:06:56.523  8022  8067 I Babel_RequestWriter: null
07-01 12:06:56.523  8022  8067 I Babel_RequestWriter: Creation stack:
07-01 12:06:56.523  8022  8067 I Babel_RequestWriter: java.lang.Throwable
07-01 12:06:56.523  8022  8067 I Babel_RequestWriter: 	at bng.<init>(SourceFile:300)
07-01 12:06:56.523  8022  8067 I Babel_RequestWriter: 	at bnw.<init>(SourceFile:443)
07-01 12:06:56.523  8022  8067 I Babel_RequestWriter: 	at bma.<init>(SourceFile:50)
07-01 12:06:56.523  8022  8067 I Babel_RequestWriter: 	at bme.<init>(SourceFile:344)
07-01 12:06:56.523  8022  8067 I Babel_RequestWriter: 	at bvf.a(SourceFile:26)
07-01 12:06:56.523  8022  8067 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.a(SourceFile:5093)
07-01 12:06:56.523  8022  8067 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.g(SourceFile:4568)
07-01 12:06:56.523  8022  8067 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.a(SourceFile:887)
07-01 12:06:56.523  8022  8067 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.onHandleIntent(SourceFile:766)
07-01 12:06:56.523  8022  8067 I Babel_RequestWriter: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-01 12:06:56.523  8022  8067 I Babel_RequestWriter: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:06:56.523  8022  8067 I Babel_RequestWriter: 	at android.os.Looper.loop(Looper.java:155)
07-01 12:06:56.523  8022  8067 I Babel_RequestWriter: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:06:56.523  8022  8067 I Babel_RequestWriter: 
07-01 12:06:56.523  8022  8067 I Babel_RequestWriter: Origin stack:
07-01 12:06:56.523  8022  8067 I Babel_RequestWriter: java.lang.Throwable
07-01 12:06:56.523  8022  8067 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.e(SourceFile:1157)
07-01 12:06:56.523  8022  8067 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.f(SourceFile:3214)
07-01 12:06:56.523  8022  8067 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.s(SourceFile:2980)
07-01 12:06:56.523  8022  8067 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.stickers.StickersModule.a(SourceFile:132)
07-01 12:06:56.523  8022  8067 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.stickers.StickersModule.v_(SourceFile:105)
07-01 12:06:56.523  8022  8067 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.phone.EsApplication.onCreate(SourceFile:566)
07-01 12:06:56.523  8022  8067 I Babel_RequestWriter: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1025)
07-01 12:06:56.523  8022  8067 I Babel_RequestWriter: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4959)
07-01 12:06:56.523  8022  8067 I Babel_RequestWriter: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
07-01 12:06:56.523  8022  8067 I Babel_RequestWriter: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
07-01 12:06:56.523  8022  8067 I Babel_RequestWriter: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:06:56.523  8022  8067 I Babel_RequestWriter: 	at android.os.Looper.loop(Looper.java:155)
07-01 12:06:56.523  8022  8067 I Babel_RequestWriter: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
07-01 12:06:56.523  8022  8067 I Babel_RequestWriter: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 12:06:56.523  8022  8067 I Babel_RequestWriter: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 12:06:56.523  8022  8067 I Babel_RequestWriter: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
07-01 12:06:56.523  8022  8067 I Babel_RequestWriter: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
07-01 12:06:56.523  8022  8067 I Babel_RequestWriter: ]; took 0 ms (error code == 101)
07-01 12:06:56.563  1114  3494 D PMS     : acquireWL(34abf625): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4270 10020 WorkSource{10020 com.google.android.gms}
07-01 12:06:56.583  1114  3937 D PMS     : releaseWL(34abf625): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10020 com.google.android.gms}
07-01 12:06:56.593  1114  1149 I ActivityManager: Waited long enough for: ServiceRecord{e856206 u0 com.aiqidi.nemo/com.reefs.service.localserver.LocalServerControllerService}
07-01 12:06:56.613  1114  3660 D PMS     : acquireWL(17d543fa): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4270 10020 WorkSource{10020 com.google.android.gms}
07-01 12:06:56.633  8122  8135 W HTCLOG  : use specified tag [cutils-trace], func [0].
07-01 12:06:56.633  8122  8135 W HTCLOG  : mask=0x18
07-01 12:06:56.633  8122  8135 E cutils-trace: Error opening trace file: Permission denied (13)
07-01 12:06:56.643  1114  3961 D PMS     : releaseWL(17d543fa): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10020 com.google.android.gms}
07-01 12:06:56.653  1114  3923 D PMS     : acquireWL(1d6d5c08): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.notifications.GunsService 0x1 4270 10020 null
07-01 12:06:56.683  1114  3442 D PMS     : acquireWL(238030b4): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 4270 10020 WorkSource{10020 com.google.android.gms}
07-01 12:06:56.683  4270  8146 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
07-01 12:06:56.693  4270  8146 D libc    : [NET] android_getaddrinfofornet-, err=8
07-01 12:06:56.693  4270  8146 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
07-01 12:06:56.693  1114  3442 D PMS     : releaseWL(238030b4): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10020 com.google.android.gms}
07-01 12:06:56.693  4270  8146 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
07-01 12:06:56.693  4270  8146 D libc    : [NET] android_getaddrinfo_proxy+
07-01 12:06:56.693  4270  8146 D libc    : [NET] android_getaddrinfo_proxy get netid:0
07-01 12:06:56.693   523  8147 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
07-01 12:06:56.693   523  8147 D libc    : [NET] _dns_getaddrinfo+, netid:0, mark:917504
07-01 12:06:56.693   523  8147 D libc    : [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
07-01 12:06:56.693   523  8147 D libc    : [NET] android_getaddrinfofornet-, err=7
07-01 12:06:56.693  4270  8146 D libc    : [NET] android_getaddrinfo_proxy-, NODATA
07-01 12:06:56.693  7661  7661 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
07-01 12:06:56.703  4270  8141 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
07-01 12:06:56.703  4270  8141 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
07-01 12:06:56.703  7790  7790 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
07-01 12:06:56.703  4270  8141 V BaseAppContext: GmsRequestQueue started.
07-01 12:06:56.713  7661  8148 I DFPI.ApkInstallService: onHandleIntent
07-01 12:06:56.713  7790  7790 I SoundPicker: SoundPickerReceiver [onReceive] startService
07-01 12:06:56.713  7661  8148 I DFPI.ApkInstallService: Media Scan Finished Case 
07-01 12:06:56.713  7661  8148 I DFPI.SystemPropertiesUtil: value = HTC__102
07-01 12:06:56.713  7661  8148 I DFPI.ApkInstallService: deviceCID = HTC__102
07-01 12:06:56.713  1114  3660 I ActivityManager: Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
07-01 12:06:56.713  7790  8154 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
07-01 12:06:56.713  7790  8154 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
07-01 12:06:56.713  7790  8154 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
07-01 12:06:56.713  7790  8154 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-01 12:06:56.713  7790  8154 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/132 type=1
07-01 12:06:56.713  7790  8154 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/132
07-01 12:06:56.713  7790  8154 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-01 12:06:56.713  7790  8154 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/132 type=2
07-01 12:06:56.713  7790  8154 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/132
07-01 12:06:56.713  7790  8154 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-01 12:06:56.713  7790  8154 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/132 type=3
07-01 12:06:56.713  7790  8154 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/132
07-01 12:06:56.713  7790  8154 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-01 12:06:56.713  7790  8154 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/105 type=4
07-01 12:06:56.713  7790  8154 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/105
07-01 12:06:56.713  7661  8148 D DFPI.ApkInstallService: check CID = HTC__102
07-01 12:06:56.713  1114  1133 I ActivityManager: Resuming delayed broadcast
07-01 12:06:56.713  7661  8148 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
07-01 12:06:56.713  7790  8154 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-01 12:06:56.713  7790  8154 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/31 type=5
07-01 12:06:56.713  7790  8154 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/31
07-01 12:06:56.713  7790  8154 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/103 type=6
07-01 12:06:56.713  7790  8154 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/103
07-01 12:06:56.713  7790  8154 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/109 type=7
07-01 12:06:56.713  7790  8154 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/109
07-01 12:06:56.713  7790  8154 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=8
07-01 12:06:56.713  7790  8154 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
07-01 12:06:56.713  7790  8154 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/105 type=9
07-01 12:06:56.713  7790  8154 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/105
07-01 12:06:56.713  4270  8141 D ChimeraResource: Successfully parsed resource with package name: com.google.android.gms and resource name drawable/ic_identity_app_security_threat
07-01 12:06:56.723  4270  8141 D ChimeraResource: Successfully parsed resource with package name: com.google.android.gms and resource name drawable/ic_google_g_icon
07-01 12:06:56.733  7661  7661 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
07-01 12:06:56.743  8122  8122 D CustomizationManager: ====startRecUseTime====
07-01 12:06:56.743  1114  1114 D ValidateNoPeople: setContact(com.google.android.gms,0.0,false)
07-01 12:06:56.743  8122  8122 D htc.customization.log.level:  is 
07-01 12:06:56.743  1114  3660 I ActivityManager: Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
07-01 12:06:56.743  8122  8122 W CustomizationLogLevel: Level value is invalid, use default level 2
07-01 12:06:56.743  7661  8156 I DFPI.ApkInstallService: onHandleIntent
07-01 12:06:56.743  7661  8156 I DFPI.ApkInstallService: Media Scan Finished Case 
07-01 12:06:56.743  7661  8156 I DFPI.SystemPropertiesUtil: value = HTC__102
07-01 12:06:56.743  7661  8156 I DFPI.ApkInstallService: deviceCID = HTC__102
07-01 12:06:56.743  7661  8156 D DFPI.ApkInstallService: check CID = HTC__102
07-01 12:06:56.743  7661  8156 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
07-01 12:06:56.743  3205  3747 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-01 12:06:56.743  3205  3747 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
07-01 12:06:56.743  1114  3494 I ActivityManager: Resuming delayed broadcast
07-01 12:06:56.753  3127  3147 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-01 12:06:56.753  3127  3147 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
07-01 12:06:56.753  3205  3231 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1000, tag: ChBhY2NvdW50X25vdGlmaWVyGhVBSF9SRUNPVkVSWV9PUFRJT05TOjA:105256135866144380227, isClearable: true, isForDotMatrix: false
07-01 12:06:56.753  3205  3231 D DotMatrix: [EventService] notificationPosted, eventType:1020
07-01 12:06:56.753  3205  3231 D DotMatrix: [EventService] notificationPosted, This eventType was disabled by user.
07-01 12:06:56.773  3127  3127 I RemoteViews: apply:com.google.android.gms 0 13 3 41
07-01 12:06:56.793  3452  3896 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
07-01 12:06:56.793  3452  3896 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@2966e341 +
07-01 12:06:56.793  3452  3896 I Prism.WidgetManager: onLoadItems() +
07-01 12:06:56.793  3127  3127 I RemoteViews: apply:com.google.android.gms 0 11 3 54
07-01 12:06:56.803  3127  3127 I RemoteViews: apply:com.google.android.gms 0 7 3 39
07-01 12:06:56.803  1114  2959 I ActivityManager: Start proc 8158:com.htc.sense.news/u0a59 for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper
07-01 12:06:56.803  1114  2959 V AlarmManager: sending alarm PendingIntent{2e1cd1d9: PendingIntentRecord{110ba79e com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1467367616792, Int=0
07-01 12:06:56.803  7790  7790 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
07-01 12:06:56.813  3127  3127 I NotificationStackScrollLayout: setBlockTouchEnabled:false
07-01 12:06:56.813  7790  7790 I SoundPicker: SoundPickerReceiver [onReceive] startService
07-01 12:06:56.813  8158  8158 W HTCLOG  : use specified tag [FDManager], func [0].
07-01 12:06:56.813  8158  8158 W HTCLOG  : mask=0x18
07-01 12:06:56.813  1114  3961 I ActivityManager: Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
07-01 12:06:56.813  3452  3896 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
07-01 12:06:56.823  7790  8175 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
07-01 12:06:56.823   566   566 I art     : Explicit concurrent mark sweep GC freed 8675(369KB) AllocSpace objects, 0(0B) LOS objects, 97% free, 113KB/4MB, paused 359us total 22.005ms
07-01 12:06:56.823  7790  8175 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
07-01 12:06:56.823  8122  8122 D CustomizationManager:  Read ACC file spent 0.045 (s)
07-01 12:06:56.823  7790  8175 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
07-01 12:06:56.833  8122  8122 D CIDMapFileReader: Parsing tag item name = HTC__001
07-01 12:06:56.833  8122  8122 D CIDMapFileReader: Parsing tag item name = HTC__002
07-01 12:06:56.833  8122  8122 D CIDMapFileReader: Parsing tag item name = HTC__016
07-01 12:06:56.833  8122  8122 D CIDMapFileReader: Parsing tag item name = HTC__031
07-01 12:06:56.833  8122  8122 D CIDMapFileReader: Parsing tag item name = HTC__032
07-01 12:06:56.833  8122  8122 D CIDMapFileReader: Parsing tag item name = HTC__102
07-01 12:06:56.833  8122  8122 D CIDMapFileReader: Parsing tag item name = HTC__A07
07-01 12:06:56.833  8122  8122 D CIDMapFileReader: Parsing tag item name = HTC__J15
07-01 12:06:56.833  8122  8122 D CIDMapFileReader: Parsing tag item name = HTC__M27
07-01 12:06:56.833  8122  8122 D CIDMapFileReader: Parsing tag item name = HTC__Y13
07-01 12:06:56.833  8122  8122 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__102.xml
07-01 12:06:56.833  8122  8122 I CustomizationCIDLoader: Parsing tag category name = application
07-01 12:06:56.833  7790  8175 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-01 12:06:56.833  8122  8122 I CustomizationCIDLoader: Parsing tag category name = system
07-01 12:06:56.833  7790  8175 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/132 type=1
07-01 12:06:56.833  8122  8122 I CustomizationCIDLoader: Parsing tag category name = Settings
07-01 12:06:56.833  8122  8122 I CustomizationCIDLoader: Parsing tag category name = ACC
07-01 12:06:56.833  8122  8122 I CustomizationCIDLoader: add string-array item, value = 42507
07-01 12:06:56.833  8122  8122 I CustomizationCIDLoader: add string-array item, value = 21902
07-01 12:06:56.833  8122  8122 I CustomizationCIDLoader: add string-array item, value = 26006:26001.26002.26003
07-01 12:06:56.833  8122  8122 I CustomizationCIDLoader: add string-array item, value = 23420
07-01 12:06:56.833  8122  8122 I CustomizationCIDLoader: add string-array item, value = 22299
07-01 12:06:56.833  8122  8122 I CustomizationCIDLoader: add string-array item, value = 24002
07-01 12:06:56.833  8122  8122 I CustomizationCIDLoader: add string-array item, value = 23210
07-01 12:06:56.833  8122  8122 I CustomizationCIDLoader: add string-array item, value = 23205
07-01 12:06:56.833  8122  8122 I CustomizationCIDLoader: add string-array item, value = 23806
07-01 12:06:56.833  8122  8122 I CustomizationCIDLoader: add string-array item, value = 23430
07-01 12:06:56.833  8122  8122 I CustomizationCIDLoader: add string-array item, value = 23408
07-01 12:06:56.833  8122  8122 I CustomizationCIDLoader: add string-array item, value = 27205
07-01 12:06:56.833  8122  8122 I CustomizationCIDLoader: add string-array item, value = 27202:27205
07-01 12:06:56.833  8122  8122 I CustomizationCIDLoader: add string-array item, value = 27216:27202.27205
07-01 12:06:56.833  8122  8122 I CustomizationCIDLoader: add string-array item, value = 42507:C:1:0
07-01 12:06:56.833  8122  8122 I CustomizationCIDLoader: add string-array item, value = 21902:C:1:0
07-01 12:06:56.833  8122  8122 I CustomizationCIDLoader: add string-array item, value = 26006:D:1:0
07-01 12:06:56.833  8122  8122 I CustomizationCIDLoader: add string-array item, value = 23420:D:0:0
07-01 12:06:56.833  8122  8122 I CustomizationCIDLoader: add string-array item, value = 27205:C:1:0
07-01 12:06:56.833  8122  8122 I CustomizationCIDLoader: add string-array item, value = 22299:D:0:0
07-01 12:06:56.833  8122  8122 I CustomizationCIDLoader: add string-array item, value = 24002:D:0:0
07-01 12:06:56.833  8122  8122 I CustomizationCIDLoader: add string-array item, value = 23210:D:2:0
07-01 12:06:56.833  8122  8122 I CustomizationCIDLoader: add string-array item, value = 23205:D:2:0
07-01 12:06:56.833  8122  8122 I CustomizationCIDLoader: add string-array item, value = 23806:D:0:0
07-01 12:06:56.833  8122  8122 I CustomizationCIDLoader: add string-array item, value = 23430:C:1:0
07-01 12:06:56.833  8122  8122 I CustomizationCIDLoader: add string-array item, value = 23408:C:1:0
07-01 12:06:56.833  8122  8122 I CustomizationCIDLoader: add string-array item, value = 27202:C:1:0
07-01 12:06:56.833  8122  8122 I CustomizationCIDLoader: add string-array item, value = 27216:C:1:0
07-01 12:06:56.833  8122  8122 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
07-01 12:06:56.833  8122  8122 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
07-01 12:06:56.833  8122  8122 I CustomizationCIDLoader: Parsing tag category name = AudioService
07-01 12:06:56.833  8122  8122 D CustomizationManager:  Read CID file spent 0.094 (s)
07-01 12:06:56.833  8122  8122 D CustomizationManager:  All configurations done spent 0.094 (s)
07-01 12:06:56.843  7790  8175 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/132
07-01 12:06:56.843  7790  8175 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-01 12:06:56.843   566   566 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 97% free, 113KB/4MB, paused 304us total 15.105ms
07-01 12:06:56.843  7790  8175 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/132 type=2
07-01 12:06:56.843  7790  8175 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/132
07-01 12:06:56.843  7790  8175 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-01 12:06:56.843  7790  8175 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/132 type=3
07-01 12:06:56.843  7790  8175 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/132
07-01 12:06:56.843  7790  8175 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-01 12:06:56.843  7790  8175 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/105 type=4
07-01 12:06:56.843  7790  8175 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/105
07-01 12:06:56.843  7790  8175 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-01 12:06:56.843  7790  8175 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/31 type=5
07-01 12:06:56.843  7790  8175 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/31
07-01 12:06:56.853  7790  8175 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/103 type=6
07-01 12:06:56.853  7790  8175 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/103
07-01 12:06:56.853  7790  8175 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/109 type=7
07-01 12:06:56.853  7790  8175 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/109
07-01 12:06:56.853  7790  8175 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=8
07-01 12:06:56.853  7790  8175 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
07-01 12:06:56.853  7790  8175 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/105 type=9
07-01 12:06:56.853  7790  8175 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/105
07-01 12:06:56.853  1114  3254 I ActivityManager: Resuming delayed broadcast
07-01 12:06:56.853   566   566 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 97% free, 113KB/4MB, paused 155us total 14.158ms
07-01 12:06:56.863  8158  8158 I MultiDex: VM with version 2.1.0 has multidex support
07-01 12:06:56.863  8158  8158 I MultiDex: install
07-01 12:06:56.863  8158  8158 I MultiDex: VM has multidex support, MultiDex support library is disabled.
07-01 12:06:56.873  1114  3660 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 8122 on display 0
07-01 12:06:56.873  1114  1180 D PMS     : acquireHCC(1b7fb295): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 1114 1000 null
07-01 12:06:56.873  1114  1180 D PMS     : acquireHCC(12069faa): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 1114 1000 null
07-01 12:06:56.873  7612  8155 I MediaStoreImporter: Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
07-01 12:06:56.873  1114  3660 V WindowManager: addAppToken: AppWindowToken{38f5e311 token=Token{1233d738 ActivityRecord{18f3f79b u0 com.test.thalitest/.MainActivity t104}}} to stack=1 task=104 at 0
07-01 12:06:56.873  1114  3660 D PMS     : acquireWL(1c070c76): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 1114 1000 null
07-01 12:06:56.883  1114  1157 I AnimationUtil: isHTCRecent(ThaliTest/Recents screens.)/3
07-01 12:06:56.883  1114  1157 V WindowManager: Adding window Window{1a48e349 u0 Starting com.test.thalitest} at 2 of 7 (after Window{2b365e7c u0 com.htc.launcher/com.htc.launcher.Launcher})
07-01 12:06:56.883  8122  8122 W HTCLOG  : use specified tag [IPCThreadState], func [0].
07-01 12:06:56.883  8122  8122 W HTCLOG  : mask=0x18
07-01 12:06:56.893  3452  3452 I FeedHostManager: [onPause]
07-01 12:06:56.893  3452  3452 I FeedProviderManager: onPause
07-01 12:06:56.893  8122  8180 W HTCLOG  : use specified tag [Vector], func [0].
07-01 12:06:56.893  8122  8180 W HTCLOG  : mask=0x18
07-01 12:06:56.893  3452  4899 I SocialFeedProvider: +onPause
07-01 12:06:56.893  3452  3452 I FeedHostManager: [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@55240fe
07-01 12:06:56.893  3452  4899 I SocialFeedProvider: -onPause
07-01 12:06:56.893  3452  3452 I ContextualWidget: onPause
07-01 12:06:56.893  3452  3452 I ContextualWidget: notifyWidgetDeactive
07-01 12:06:56.923  1114  3442 I ActivityManager: Start proc 8185:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
07-01 12:06:56.933  8185  8185 W HTCLOG  : use specified tag [FDManager], func [0].
07-01 12:06:56.933  8185  8185 W HTCLOG  : mask=0x18
07-01 12:06:56.933  4270  8141 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
07-01 12:06:56.933  4270  8141 D libc    : [NET] android_getaddrinfofornet-, err=8
07-01 12:06:56.933  4270  8141 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
07-01 12:06:56.933  4270  8141 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
07-01 12:06:56.933  4270  8141 D libc    : [NET] android_getaddrinfo_proxy+
07-01 12:06:56.933  4270  8141 D libc    : [NET] android_getaddrinfo_proxy get netid:0
07-01 12:06:56.933   523  8204 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
07-01 12:06:56.933   523  8204 D libc    : [NET] _dns_getaddrinfo+, netid:0, mark:917504
07-01 12:06:56.933   523  8204 D libc    : [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
07-01 12:06:56.933   523  8204 D libc    : [NET] android_getaddrinfofornet-, err=7
07-01 12:06:56.933  4270  8141 D libc    : [NET] android_getaddrinfo_proxy-, NODATA
07-01 12:06:56.933  4270  8141 E Auth    : [GoogleAccountDataServiceImpl] getToken() -> NETWORK_ERROR. Account: <ELLIDED:-200118834>, App: com.google.android.gms, Service: oauth2:https://www.googleapis.com/auth/plus.me
07-01 12:06:56.933  1114  3534 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
07-01 12:06:56.943  7661  7661 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
07-01 12:06:56.943  4270  8141 W GnotsSRSOperation: Failed to update the notification(s) read state.
07-01 12:06:56.943  4270  8141 W GnotsSRSOperation: com.android.volley.VolleyError: java.io.IOException: NetworkError
07-01 12:06:56.943  4270  8141 W GnotsSRSOperation: 	at ioh.b(:com.google.android.gms:111)
07-01 12:06:56.943  4270  8141 W GnotsSRSOperation: 	at ioy.b(:com.google.android.gms:339)
07-01 12:06:56.943  4270  8141 W GnotsSRSOperation: 	at ioy.a(:com.google.android.gms:220)
07-01 12:06:56.943  4270  8141 W GnotsSRSOperation: 	at ioy.a(:com.google.android.gms:198)
07-01 12:06:56.943  4270  8141 W GnotsSRSOperation: 	at rog.a(:com.google.android.gms:44)
07-01 12:06:56.943  4270  8141 W GnotsSRSOperation: 	at com.google.android.gms.notifications.GunsChimeraService.a(:com.google.android.gms:13044)
07-01 12:06:56.943  4270  8141 W GnotsSRSOperation: 	at com.google.android.gms.notifications.GunsChimeraService.onHandleIntent(:com.google.android.gms:5132)
07-01 12:06:56.943  4270  8141 W GnotsSRSOperation: 	at bdz.handleMessage(:com.google.android.gms:65)
07-01 12:06:56.943  4270  8141 W GnotsSRSOperation: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:06:56.943  4270  8141 W GnotsSRSOperation: 	at android.os.Looper.loop(Looper.java:155)
07-01 12:06:56.943  4270  8141 W GnotsSRSOperation: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:06:56.943  4270  8141 W GnotsSRSOperation: Caused by: java.io.IOException: NetworkError
07-01 12:06:56.943  4270  8141 W GnotsSRSOperation: 	at cxs.a(:com.google.android.gms:1529)
07-01 12:06:56.943  4270  8141 W GnotsSRSOperation: 	at cxr.a(:com.google.android.gms:921)
07-01 12:06:56.943  4270  8141 W GnotsSRSOperation: 	at cxr.e(:com.google.android.gms:535)
07-01 12:06:56.943  4270  8141 W GnotsSRSOperation: 	at cxr.d(:com.google.android.gms:455)
07-01 12:06:56.943  4270  8141 W GnotsSRSOperation: 	at cxp.b(:com.google.android.gms:555)
07-01 12:06:56.943  4270  8141 W GnotsSRSOperation: 	at ipq.b(:com.google.android.gms:98)
07-01 12:06:56.943  4270  8141 W GnotsSRSOperation: 	at ioh.b(:com.google.android.gms:107)
07-01 12:06:56.943  4270  8141 W GnotsSRSOperation: 	... 10 more
07-01 12:06:56.943  4270  8141 W WakefulBroadcastReceiver: No active wake lock id #1
07-01 12:06:56.943  8158  8207 I SocialManager[SocialBiLogHelper]: action: com.htc.sense.hsp.HANDLE_ULOG
07-01 12:06:56.943  8158  8207 I SocialManager[SocialBiLogHelper]: last commit ulog time 1467363353580
07-01 12:06:56.943  8158  8207 I SocialManager[SocialBiLogHelper]: skip commit this time
07-01 12:06:56.943  7661  8209 I DFPI.ApkInstallService: onHandleIntent
07-01 12:06:56.953  7661  8209 I DFPI.ApkInstallService: Media Scan Finished Case 
07-01 12:06:56.953  7661  8209 I DFPI.SystemPropertiesUtil: value = HTC__102
07-01 12:06:56.953  7661  8209 I DFPI.ApkInstallService: deviceCID = HTC__102
07-01 12:06:56.953  7661  8209 D DFPI.ApkInstallService: check CID = HTC__102
07-01 12:06:56.953  7661  8209 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
07-01 12:06:56.953  1114  1150 D StatusBarManagerService: setSystemUiVisibility(0x8600)
07-01 12:06:56.953  1114  1150 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{1a48e349 u0 Starting com.test.thalitest}
07-01 12:06:56.953  1114  1150 D StatusBarManagerService: hiding MENU key
07-01 12:06:56.953  3127  3127 I PhoneStatusBar: setSystemUiNavVisibility(swipe=false hasFocus=false hasPolicy=false shadeState=true)
07-01 12:06:56.953  3127  3127 I PhoneStatusBar: hiding the MENU button mLongPressHomeMenu = false
07-01 12:06:56.973  7790  7790 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
07-01 12:06:56.983  3452  3452 I TrimMemoryManager: [trimMemory] 20
07-01 12:06:56.983  7790  7790 I SoundPicker: SoundPickerReceiver [onReceive] startService
07-01 12:06:56.983  1114  3442 I ActivityManager: Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
07-01 12:06:56.983  7790  8210 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
07-01 12:06:56.983  7790  8210 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
07-01 12:06:56.983  7790  8210 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
07-01 12:06:56.983  7790  8210 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-01 12:06:56.983  7790  8210 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/132 type=1
07-01 12:06:56.983  7790  8210 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/132
07-01 12:06:56.983  7790  8210 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-01 12:06:56.983  7790  8210 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/132 type=2
07-01 12:06:56.983  7790  8210 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/132
07-01 12:06:56.983  7790  8210 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-01 12:06:56.983  7790  8210 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/132 type=3
07-01 12:06:56.983  7790  8210 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/132
07-01 12:06:56.983  7790  8210 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-01 12:06:56.983  7790  8210 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/105 type=4
07-01 12:06:56.983  7790  8210 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/105
07-01 12:06:56.983  7790  8210 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-01 12:06:56.983  7790  8210 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/31 type=5
07-01 12:06:56.983  7790  8210 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/31
07-01 12:06:56.983  7790  8210 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/103 type=6
07-01 12:06:56.983  7790  8210 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/103
07-01 12:06:56.983  7790  8210 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/109 type=7
07-01 12:06:56.983  7790  8210 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/109
07-01 12:06:56.983  7790  8210 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=8
07-01 12:06:56.983  7790  8210 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
07-01 12:06:56.983  7790  8210 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/105 type=9
07-01 12:06:56.983  7790  8210 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/105
07-01 12:06:56.993  1114  3041 I ActivityManager: Resuming delayed broadcast
07-01 12:06:57.003  3452  3896 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-01 12:06:57.013  1114  3937 I ActivityManager: Start proc 8211:com.htc.calendar/u0a7 for broadcast com.htc.calendar/.ProviderChangeReceiver
07-01 12:06:57.023  8185  8185 I WebViewFactory: Loading com.google.android.webview version 42.0.2311.137 (code 52311137)
07-01 12:06:57.023  8211  8211 W HTCLOG  : use specified tag [FDManager], func [0].
07-01 12:06:57.023  8211  8211 W HTCLOG  : mask=0x18
07-01 12:06:57.033  7612  8155 I MediaStoreImporter: Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
07-01 12:06:57.053  8211  8211 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
07-01 12:06:57.063  8211  8211 D CalendarApplication: onCreate
07-01 12:06:57.073  8211  8211 D ProviderChangeReceiver: ---------------------------------------------------
07-01 12:06:57.073  8211  8211 D ProviderChangeReceiver: ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
07-01 12:06:57.073  1114  1133 I ActivityManager: Killing 7242:com.android.vending/u0a57 (adj 15): empty #17
07-01 12:06:57.073  1114  1133 D Process : killProcessQuiet, pid=7242
07-01 12:06:57.073  1114  1133 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:238 
07-01 12:06:57.073  8211  8234 D HtcAlertService: start to updateAlertNotification!
07-01 12:06:57.083  8185  8185 I LibraryLoader: Time to load native libraries: 31 ms (timestamps 537-568)
07-01 12:06:57.083  8185  8185 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-01 12:06:57.093  5210  8232 I art     : Explicit concurrent mark sweep GC freed 49084(3MB) AllocSpace objects, 0(0B) LOS objects, 72% free, 1527KB/5MB, paused 323us total 30.963ms
07-01 12:06:57.103  8185  8185 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {11dc324a}
,07-01 12:06:57.103  7612  8155 I MediaStoreImporter: Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
07-01 12:06:57.103  8185  8185 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-01 12:06:57.103  8185  8185 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,07-01 12:06:57.113  8185  8185 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-01 12:06:57.113  8185  8185 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-01 12:06:57.113  8185  8185 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-01 12:06:57.143  8185  8238 W chromium: [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,07-01 12:06:57.153  1114  3911 I ActivityManager: Recipient 7242
,07-01 12:06:57.153  1114  5649 I art     : Explicit concurrent mark sweep GC freed 33532(1829KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.690ms total 107.586ms
,07-01 12:06:57.153  1114  1114 D PMS     : releaseWL(19fc9a57): PARTIAL_WAKE_LOCK  NextAlarmTracker 0x1 null
07-01 12:06:57.163  8185  8242 D BluetoothAdapter: 558900667: getState() :  mService = null. Returning STATE_OFF
,07-01 12:06:57.163  8185  8185 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
07-01 12:06:57.173  8185  8185 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50364 len=3345
,07-01 12:06:57.173  8185  8185 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:9397000 len:1161174
,07-01 12:06:57.173  8185  8185 W HTCLOG  : use specified tag [libEGL], func [3].
,07-01 12:06:57.173  8185  8185 W HTCLOG  : mask=0x18
,07-01 12:06:57.173  8185  8185 W HTCLOG  : use specified tag [libEGL], func [3].
07-01 12:06:57.173  8185  8185 W HTCLOG  : mask=0x18
07-01 12:06:57.173  8185  8185 I Adreno  : QUALCOMM build                   : 065751b, 
07-01 12:06:57.173  8185  8185 I Adreno  : Build Date                       : 04/15/15
07-01 12:06:57.173  8185  8185 I Adreno  : OpenGL ES Shader Compiler Version: E031.25.03.07
07-01 12:06:57.173  8185  8185 I Adreno  : Local Branch                     : 
07-01 12:06:57.173  8185  8185 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.1_rb2.9
07-01 12:06:57.173  8185  8185 I Adreno  : Remote Branch                    : NONE
,07-01 12:06:57.173  8185  8185 I Adreno  : Reconstruct Branch               : AU_LINUX_ANDROID_LA.BF64.1.2.1_RB2.05.01.00.081.016 + 065751b +  NOTHING
,07-01 12:06:57.193  1114  3688 D Process : killProcessQuiet, pid=7482
07-01 12:06:57.193  1114  3688 I ActivityManager: Killing 7482:com.htc.widget.hmsproc2/u0a36 (adj 15): empty #17
07-01 12:06:57.193  1114  3688 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19304 
,07-01 12:06:57.193  3452  3896 W asset   : Copying FileAsset 0xac10dc28 (zip:/data/app/com.gameloft.android.gdc-1/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,07-01 12:06:57.203  7532  8244 D libc    : [NET] android_getaddrinfofornet+,hn 17(0x73646b2e686f63),sn(),hints(known),family 0,flags 4
07-01 12:06:57.203  7532  8244 D libc    : [NET] android_getaddrinfofornet-, err=8
07-01 12:06:57.203  7532  8244 D libc    : [NET] android_getaddrinfofornet+,hn 17(0x73646b2e686f63),sn(),hints(known),family 0,flags 1024
07-01 12:06:57.203  7532  8244 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
07-01 12:06:57.203  7532  8244 D libc    : [NET] android_getaddrinfo_proxy+
07-01 12:06:57.203  7532  8244 D libc    : [NET] android_getaddrinfo_proxy get netid:0
07-01 12:06:57.203   523  8246 D libc    : [NET] android_getaddrinfofornet+,hn 17(0x73646b2e686f63),sn(),hints(known),family 0,flags 1024
,07-01 12:06:57.203   523  8246 D libc    : [NET] _dns_getaddrinfo+, netid:0, mark:917504
07-01 12:06:57.203   523  8246 D libc    : [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
07-01 12:06:57.203   523  8246 D libc    : [NET] android_getaddrinfofornet-, err=7
07-01 12:06:57.203  7532  8244 D libc    : [NET] android_getaddrinfo_proxy-, NODATA
07-01 12:06:57.203  7532  8244 W System.err: java.net.UnknownHostException: Unable to resolve host "sdk.hockeyapp.net": No address associated with hostname
,07-01 12:06:57.203  7532  8244 W System.err: 	at java.net.InetAddress.lookupHostByName(InetAddress.java:457)
,07-01 12:06:57.203  7532  8244 W System.err: 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
07-01 12:06:57.203  7532  8244 W System.err: 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
07-01 12:06:57.203  7532  8244 W System.err: 	at com.android.okhttp.HostResolver$1.getAllByName(HostResolver.java:29)
07-01 12:06:57.203  7532  8244 W System.err: 	at com.android.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:232)
,07-01 12:06:57.203  7532  8244 W System.err: 	at com.android.okhttp.internal.http.RouteSelector.next(RouteSelector.java:124)
07-01 12:06:57.203  7532  8244 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:272)
07-01 12:06:57.203  7532  8244 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:211)
07-01 12:06:57.203  7532  8244 W System.err: 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:403)
07-01 12:06:57.203  7532  8244 W System.err: 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.connect(HttpURLConnectionImpl.java:116)
07-01 12:06:57.203  7532  8244 W System.err: 	at com.android.okhttp.internal.http.DelegatingHttpsURLConnection.connect(DelegatingHttpsURLConnection.java:89)
07-01 12:06:57.203  7532  8244 W System.err: 	at com.android.okhttp.internal.http.HttpsURLConnectionImpl.connect(HttpsURLConnectionImpl.java:25)
07-01 12:06:57.203  7532  8244 W System.err: 	at net.hockeyapp.android.tasks.CheckUpdateTask.doInBackground(CheckUpdateTask.java:130)
07-01 12:06:57.203  7532  8244 W System.err: 	at net.hockeyapp.android.tasks.CheckUpdateTask.doInBackground(CheckUpdateTask.java:58)
,07-01 12:06:57.203  7532  8244 W System.err: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
07-01 12:06:57.203  7532  8244 W System.err: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-01 12:06:57.203  7532  8244 W System.err: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,07-01 12:06:57.203  7532  8244 W System.err: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-01 12:06:57.203  7532  8244 W System.err: 	at java.lang.Thread.run(Thread.java:818)
07-01 12:06:57.203  7532  8244 W System.err: Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
07-01 12:06:57.203  7532  8244 W System.err: 	at libcore.io.Posix.android_getaddrinfo(Native Method)
07-01 12:06:57.203  7532  8244 W System.err: 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
07-01 12:06:57.203  7532  8244 W System.err: 	at java.net.InetAddress.lookupHostByName(InetAddress.java:438)
07-01 12:06:57.203  7532  8244 W System.err: 	... 18 more
,07-01 12:06:57.243  3418  4155 D PhoneApp: EVENT_QUERY_MO_PACKAGES
,07-01 12:06:57.243  3418  4155 D PhoneApp: -- N1 =1
,07-01 12:06:57.253  3418  4155 D PhoneApp: -- N2 =0
,07-01 12:06:57.253  3418  4155 D PhoneApp: -- N3 =0
,07-01 12:06:57.253  3452  3896 I Prism.WidgetManager: onLoadItems() -,
07-01 12:06:57.253  3452  3896 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@2966e341 -
,07-01 12:06:57.273  1114  3494 I ActivityManager: Recipient 7482,
,07-01 12:06:57.273  3452  3896 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
07-01 12:06:57.273  3452  3452 W Prism.AllAppsManager: AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS> P=UserHandle{0})
07-01 12:06:57.273  3452  3896 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,07-01 12:06:57.283  3452  3452 I Launcher: Deferring update until onResume
07-01 12:06:57.283  3452  3452 D Launcher: waitUntilResume // bindAppsUpdated
,07-01 12:06:57.283  3452  3896 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-01 12:06:57.283  3452  3896 W PackageManager: Failure retrieving resources for com.google.android.talk: Resource ID #0x0,
,07-01 12:06:57.283  3452  3896 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
07-01 12:06:57.283  3452  3896 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,07-01 12:06:57.293  3452  3452 W Prism.AllAppsManager: AllAppsMgr addApps, already exist: ApplicationInfo(id=29, title=Hangouts, componentNameComponentInfo{com.google.android.talk/com.google.android.talk.SigningInActivity} appsContainer=<ALLAPPS> P=UserHandle{0})
,07-01 12:06:57.293  3452  3452 I Launcher: Deferring update until onResume
07-01 12:06:57.293  3452  3452 D Launcher: waitUntilResume // bindAppsUpdated
,07-01 12:06:57.303  8211  8234 D HtcAlertService: No fired or scheduled alerts,
07-01 12:06:57.303  8211  8234 D HtcAlertUtils: -- cancelReminderNotification --
07-01 12:06:57.303  8211  8234 D HtcAlertUtils: broadcastExistReminder!
,07-01 12:06:57.303  3205  3205 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
,07-01 12:06:57.303  3321  8257 I WSP     : [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
07-01 12:06:57.313  3321  8257 D WeatherUtility: Weather sync is On
07-01 12:06:57.313  3321  8257 I WSP     : [Receiver] next auto-sync alarm event is 60 mins later, at time: Fri Jul 01 13:06:57 GMT+02:00 2016
07-01 12:06:57.313  1114  3442 D PMS     : acquireWL(34e41b4f): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 7612 10114 null
07-01 12:06:57.313  3321  8257 W WSP     : [Receiver] can't get active network info
07-01 12:06:57.323  3321  3321 V WSP     : [SyncService] no data connection, stop sync service
,07-01 12:06:57.343  8185  8252 W chromium: [WARNING:data_reduction_proxy_config.cc(150)] SPDY proxy OFF at startup
,07-01 12:06:57.353  4270  4270 D WearableService: callingUid 10020, callindPid: 4270
,07-01 12:06:57.363  1114  1133 I ActivityManager: Delay finish: com.google.android.music/.wear.WearBroadcastReceiver
,07-01 12:06:57.363  8185  8185 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-01 12:06:57.373  7612  7612 W GoogleHttpClient: Failed to load SSLCertificateSocketFactory from package
07-01 12:06:57.373  7612  7612 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
07-01 12:06:57.373  7612  7612 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,07-01 12:06:57.373  8185  8185 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-01 12:06:57.393  8185  8185 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC
,07-01 12:06:57.393  1114  3442 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=7612, uid=10114, userID:0
,07-01 12:06:57.403  8185  8185 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-01 12:06:57.403  8185  8185 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-01 12:06:57.403  1114  3688 D PMS     : releaseWL(34e41b4f): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,07-01 12:06:57.403  7612  8259 I MusicLeanback: Conditions not met for autocaching.
07-01 12:06:57.403  7612  8259 I MusicLeanback: Stop autocaching.
07-01 12:06:57.403  1114  1133 I ActivityManager: Resuming delayed broadcast
,07-01 12:06:57.413  7612  7612 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,07-01 12:06:57.413  7612  8267 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,07-01 12:06:57.443  8185  8272 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].,
07-01 12:06:57.443  8185  8272 W HTCLOG  : mask=0x18
,07-01 12:06:57.453  1114  3961 V WindowManager: Adding window Window{65c5fa4 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{1a48e349 u0 Starting com.test.thalitest})
,07-01 12:06:57.493  8185  8185 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
07-01 12:06:57.503  8185  8185 W HTCLOG  : use specified tag [ThreadedRenderer], func [0].,
07-01 12:06:57.503  8185  8185 W HTCLOG  : mask=0x18
07-01 12:06:57.503  8185  8185 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
07-01 12:06:57.503  8185  8185 W HTCLOG  : mask=0x18
07-01 12:06:57.503  8185  8272 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
07-01 12:06:57.503  8185  8272 W HTCLOG  : mask=0x18
07-01 12:06:57.503  8185  8272 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
07-01 12:06:57.503  8185  8272 W HTCLOG  : mask=0x18
07-01 12:06:57.503  8185  8272 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
07-01 12:06:57.503  8185  8272 W HTCLOG  : mask=0x18
07-01 12:06:57.503  8185  8272 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
07-01 12:06:57.503  8185  8272 W HTCLOG  : mask=0x18
07-01 12:06:57.503  7385  7385 D CDMountReceiver: whether to enable CD Auto-mount: true
07-01 12:06:57.503  7385  7385 D CDMountReceiver: showNotification() contentText=If HTC Sync Manager setup doesn't start automatically on your computer, download it from www.htc.com/hsm
,07-01 12:06:57.513  8185  8272 W HTCLOG  : use specified tag [Surface], func [3].
07-01 12:06:57.513  8185  8272 W HTCLOG  : mask=0x18
,07-01 12:06:57.513  8185  8272 W HTCLOG  : use specified tag [GraphicBufferMapper], func [3].
07-01 12:06:57.513  8185  8272 W HTCLOG  : mask=0x18
07-01 12:06:57.513  8185  8272 W HTCLOG  : use specified tag [qdmemalloc], func [0].
07-01 12:06:57.513  8185  8272 W HTCLOG  : mask=0x18
,07-01 12:06:57.523  1114  1114 D ValidateNoPeople: setContact(com.nero.android.htc.sync,0.0,false)
,07-01 12:06:57.543  3205  3747 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true, isForDotMatrix: false
,07-01 12:06:57.553  3127  3127 I RemoteViews: apply:com.nero.android.htc.sync 0 6 3 38
,07-01 12:06:57.553  3127  3127 I RemoteViews: apply:com.nero.android.htc.sync 0 6 1 53
,07-01 12:06:57.563  7385  7385 D CDMountReceiver: enable CD Auto-mount: true
,07-01 12:06:57.563  3127  3127 I NotificationStackScrollLayout: setBlockTouchEnabled:false
07-01 12:06:57.563  1114  1114 D PMS     : releaseWL(f4705b2): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10003}
,07-01 12:06:57.563  7385  8275 D HTCUtilities: enable auto-mount
,07-01 12:06:57.573  7385  8275 I HtcMountManagerAdapter: mHtcMountManager is  null
07-01 12:06:57.573  7385  8275 I HtcMountManagerAdapter: mStorageManager is  not null
,07-01 12:06:57.573  1114  1133 D VoldConnector: SND -> {7 mountISO mount /system/etc/PCTOOL.ISO /sys/class/android_usb/f_mass_storage/lun0/file}
07-01 12:06:57.573  1114  2964 D VoldConnector: RCV <- {200 7 mountISO operation succeeded}
07-01 12:06:57.573  1114  1133 D MountService: mountISO: /system/etc/PCTOOL.ISO
,07-01 12:06:57.583  1114  3961 I ActivityManager: Start proc 8276:com.google.android.partnersetup/u0a23 for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver
,07-01 12:06:57.593  8276  8276 W HTCLOG  : use specified tag [FDManager], func [0].
07-01 12:06:57.593  8276  8276 W HTCLOG  : mask=0x18
,07-01 12:06:57.623  8185  8185 I InputMethodManager: [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@58f2d23, mServedView=org.apache.cordova.engine.SystemWebView{9c91220 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@12e2a7d9,
,07-01 12:06:57.633  3717  3717 E PackageActionReceiver: ACTION_PACKAGE_ADDED,
,07-01 12:06:57.633  5041  5041 I [MirrorLinkServer]PackageInstalledReceiver: PackageInstalledReceiver Received::Intent { act=android.intent.action.PACKAGE_ADDED dat=package: flg=0x4000010 cmp=com.htc.mirrorlinkserver/.PackageInstalledReceiver (has extras) }
07-01 12:06:57.633  5041  5041 D [MirrorLinkServer]PackageInstalledReceiver: Counter : 1
07-01 12:06:57.633  5041  5041 D [MirrorLinkServer]MirrorLinkConnectionReceiver: notifyMlSevrer
,07-01 12:06:57.633  3321  8300 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.test.thalitest
07-01 12:06:57.633  3321  8300 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed
,07-01 12:06:57.643  5041  5041 I [MirrorLinkServer]MirrorLinkServer: onStartCommand() Action : android.intent.action.PACKAGE_ADDED,
07-01 12:06:57.643  5041  5041 D [MirrorLinkServer]MirrorLinkServer: New Application installed : com.test.thalitest
07-01 12:06:57.643  5041  5041 D [MirrorLinkServer]d: onApplicationInstalled
07-01 12:06:57.643  5041  5041 W [MirrorLinkServer]d: Cannot find find the  com.mirrorlink.android.app.LAUNCH intent.
07-01 12:06:57.643  5041  5041 I [MirrorLinkServer]d: com.test.thalitest is not a MirrorLink-aware app.
07-01 12:06:57.643  3452  3452 D Prism.PackageStateRece_: action: android.intent.action.PACKAGE_ADDED
,07-01 12:06:57.643  5041  8301 I [MirrorLinkServer]d: Database Update Progress State : false
07-01 12:06:57.643  5041  8301 I [MirrorLinkServer]c: onApplicationUpdationCompleted, sending broadcast
07-01 12:06:57.643  1114  3962 D Process : killProcessQuiet, pid=7551
07-01 12:06:57.643  1114  3962 I ActivityManager: Killing 7551:com.htc.bgp/u0a8 (adj 15): empty #17
,07-01 12:06:57.643  5041  5041 I [MirrorLinkServer]MirrorLinkServer: Broadcast Received::Intent { act=com.htc.HTCMirrorLinkServer.PACKAGE_UPDATE_COMPLETED }
07-01 12:06:57.643  1114  3962 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19304 
07-01 12:06:57.643  3452  3452 I ContextualWidget: package com.test.thalitest added
07-01 12:06:57.643  5041  5041 D [MirrorLinkServer]MirrorLinkServer: ML_PACKAGE_UPDATE_COMPLETED intent received
07-01 12:06:57.643  5041  5041 D [MirrorLinkServer]MirrorLinkServer: Counter : 0
07-01 12:06:57.643  5041  5041 I [MirrorLinkServer]MirrorLinkConnectionReceiver: checkAndStopMLSession
07-01 12:06:57.643  5041  5041 I [MirrorLinkServer]MirrorLinkConnectionReceiver: Stopping Service
,07-01 12:06:57.663  1114  3911 I InputMethodManagerService: Disable input method client, pid=3452
07-01 12:06:57.663  1114  3911 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
07-01 12:06:57.663  1114  3911 I InputMethodManagerService: Enable input method client, pid=8185
,07-01 12:06:57.663  3127  3127 I PhoneStatusBar: setImeWindowStatus(false,false)
,07-01 12:06:57.703  1114  3494 I ActivityManager: Recipient 7551
,07-01 12:06:57.703  8185  8185 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 8185
,07-01 12:06:57.743  1114  1157 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +838ms,
07-01 12:06:57.743  1114  3962 D PMS     : releaseWL(1c070c76): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
07-01 12:06:57.753  3452  4034 I ContextualWidget: handleMessage, what=1003 mode=GettingOut maxcount=8
,07-01 12:06:57.773  1114  3937 I ActivityManager: Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver
,07-01 12:06:57.773  6444  8308 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,07-01 12:06:57.783  8185  8185 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-01 12:06:57.793  6444  8308 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
07-01 12:06:57.793  6444  8308 W HTCLOG  : mask=0x18
,07-01 12:06:57.793  3452  4034 I ContextualWidget: MFU.onDownloadDataSetChanged
07-01 12:06:57.793  3452  4034 I ContextualWidget: handleMessage, what=1019 mode=GettingOut maxcount=8
,07-01 12:06:57.793  3452  3452 I ContextualWidget: notifyDataChanged, pos=6 item=FolderInfo: Recent downloads, app folderId e1265ad8-1cc5-47a2-9913-814b73534388, (Item(id=-1 type=6 container=-200 screen=-1 cellX=-1 cellY=-1 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0}))
,07-01 12:06:57.793  3452  3452 I HtcContextualWidgetDataManager: onDataChanged: GettingOut, position: 6, item:[FolderInfo: Recent downloads, app folderId e1265ad8-1cc5-47a2-9913-814b73534388, (Item(id=-1 type=6 container=-200 screen=-1 cellX=-1 cellY=-1 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0}))]
,07-01 12:06:57.803  1114  3962 I ActivityManager: Resuming delayed broadcast
,07-01 12:06:57.813  1114  3966 I ActivityManager: Start proc 8309:com.htc.cs.dm/u0a88 for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver
,07-01 12:06:57.823  8309  8309 W HTCLOG  : use specified tag [FDManager], func [0].
07-01 12:06:57.823  1114  2959 D PMS     : acquireWL(20f5d328): PARTIAL_WAKE_LOCK  *alarm* 0x1 1114 1000 WorkSource{10027},
07-01 12:06:57.823  8309  8309 W HTCLOG  : mask=0x18
07-01 12:06:57.823  1114  2959 V AlarmManager: sending alarm PendingIntent{27f14841: PendingIntentRecord{2905c1e6 com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=61303, Int=0
,07-01 12:06:57.873  1114  1180 D PMS     : releaseHCC(1b7fb295): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
07-01 12:06:57.873  1114  1180 D PMS     : releaseHCC(12069faa): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,07-01 12:06:57.873  8309  8309 I DeviceManagement: DMApplication: !!! Hello, this is: [com.htc.cs.dm;3.0.404391;250011189] pid=8309 dbg=false s=true
07-01 12:06:57.873  8309  8309 I DeviceManagement: PackageUpdateReceiver: vvv Package added: [com.test.thalitest]
,07-01 12:06:57.893  1114  1133 I ActivityManager: Start proc 8334:com.google.android.apps.docs/u0a90 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,07-01 12:06:57.893  1114  1133 I ActivityManager: Killing 7815:com.htc.updater/u0a68 (adj 15): empty #17
07-01 12:06:57.903  1114  1133 D Process : killProcessQuiet, pid=7815
07-01 12:06:57.903  1114  1133 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityManagerService.trimApplications:19731 
,07-01 12:06:57.903  8334  8334 W HTCLOG  : use specified tag [FDManager], func [0].
,07-01 12:06:57.903  8334  8334 W HTCLOG  : mask=0x18
,07-01 12:06:57.973  1114  1134 I ActivityManager: Recipient 7815
,07-01 12:06:58.033  1114  3688 D PMS     : acquireWL(1045be79): PARTIAL_WAKE_LOCK  Icing 0x1 6718 10020 WorkSource{10069 com.google.android.googlequicksearchbox}
,07-01 12:06:58.063  8185  8302 D jxcore_app_log: JniHelper::setJavaVM(0xab29eb70), pthread_self() = -1407157760
,07-01 12:06:58.073  8185  8302 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: ,
07-01 12:06:58.073  8185  8302 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-01 12:06:58.073  8185  8302 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-01 12:06:58.073  8185  8302 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-01 12:06:58.073  8185  8302 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-01 12:06:58.073  8185  8302 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8e53802 added. We now have 1 listener(s)
07-01 12:06:58.083  1114  3041 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
07-01 12:06:58.083  8185  8302 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 90:E7:C4:3C:62:6A
07-01 12:06:58.083  8185  8302 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "90:E7:C4:3C:62:6A"
07-01 12:06:58.083  8185  8302 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-01 12:06:58.083  8185  8302 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-01 12:06:58.093  8185  8302 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-01 12:06:58.093  8185  8302 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-01 12:06:58.093  8185  8302 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-01 12:06:58.093  8185  8302 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 90:E7:C4:3C:62:6A
07-01 12:06:58.093  8185  8302 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-01 12:06:58.093  8185  8302 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-01 12:06:58.093  8185  8302 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-01 12:06:58.093  8185  8302 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-01 12:06:58.093  8185  8302 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-01 12:06:58.093  8185  8302 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-01 12:06:58.093  8185  8302 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-01 12:06:58.093  8185  8302 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f303949 added. We now have 1 listener(s)
07-01 12:06:58.093  8185  8302 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-01 12:06:58.093  8185  8302 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-01 12:06:58.093  1114  2973 D WifiService: New client listening to asynchronous messages
07-01 12:06:58.103  8185  8302 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
07-01 12:06:58.103  8185  8302 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-01 12:06:58.103  8185  8302 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2,
07-01 12:06:58.103  8185  8302 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
,07-01 12:06:58.103  8185  8302 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
07-01 12:06:58.103  8185  8302 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-01 12:06:58.103  1114  3253 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
07-01 12:06:58.103  8185  8302 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 90:E7:C4:3C:62:6A
,07-01 12:06:58.113  8185  8302 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved",
07-01 12:06:58.113  8185  8302 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-01 12:06:58.113  8185  8302 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:06:58.113  8185  8302 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-01 12:06:58.113  8185  8302 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 12:06:58.113  8185  8302 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false,
07-01 12:06:58.113  8185  8302 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 12:06:58.113  8185  8302 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 12:06:58.113  8185  8302 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-01 12:06:58.113  8185  8302 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-01 12:06:58.113  8185  8302 D io.jxcore.node.ConnectivityMonitor: start: OK
07-01 12:06:58.113  8185  8302 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-01 12:06:58.123  1114  1133 D PMS     : releaseWL(1045be79): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10020 com.google.android.gms}
,07-01 12:06:58.133  1114  1134 D PMS     : acquireWL(32387096): PARTIAL_WAKE_LOCK  Icing 0x1 6718 10020 WorkSource{10069 com.google.android.googlequicksearchbox},
,07-01 12:06:58.153  8185  8185 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-01 12:06:58.153  6444  8308 I ApplicationLogger: canRun() : Opted Out,
07-01 12:06:58.153  6444  8308 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 374 ms] updated apps [took 374 ms] 
,07-01 12:06:58.183  8334  8334 D DocsApplication: Plugin installer initialized.
,07-01 12:06:58.203  8334  8334 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{393f503e com.google.android.apps.docs}
,07-01 12:06:58.223  8334  8334 D TAG     : onCreate(),
07-01 12:06:58.233  8334  8334 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,07-01 12:06:58.433  7941  7978 I GAV2    : Thread[GAThread,5,main]: No campaign data found.,
,07-01 12:06:58.533  8022  8067 I Babel_RequestWriter: error sending REQ[fc:6; creat:1467367599745; type:bme-795119421: userphotoalbums
07-01 12:06:58.533  8022  8067 I Babel_RequestWriter: ProtoBuf:
07-01 12:06:58.533  8022  8067 I Babel_RequestWriter: null
07-01 12:06:58.533  8022  8067 I Babel_RequestWriter: Creation stack:,
07-01 12:06:58.533  8022  8067 I Babel_RequestWriter: java.lang.Throwable
07-01 12:06:58.533  8022  8067 I Babel_RequestWriter: 	at bng.<init>(SourceFile:300)
07-01 12:06:58.533  8022  8067 I Babel_RequestWriter: 	at bnw.<init>(SourceFile:443)
07-01 12:06:58.533  8022  8067 I Babel_RequestWriter: ,	at bma.<init>(SourceFile:50)
07-01 12:06:58.533  8022  8067 I Babel_RequestWriter: 	at bme.<init>(SourceFile:344)
07-01 12:06:58.533  8022  8067 I Babel_RequestWriter: 	at bvf.a(SourceFile:26)
07-01 12:06:58.533  8022  8067 I Babel_RequestWriter: 	,at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.a(SourceFile:5093)
07-01 12:06:58.533  8022  8067 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.g(SourceFile:4568)
07-01 12:06:58.533  8022  8067 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.a(SourceFile:887)
07-01 12:06:58.533  8022  8067 I Babel_RequestWriter: 	,at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.onHandleIntent(SourceFile:766)
07-01 12:06:58.533  8022  8067 I Babel_RequestWriter: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-01 12:06:58.533  8022  8067 I Babel_RequestWriter: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:06:58.533  8022  8067 I Babel_RequestWriter: 	at android.os.Looper.loop(Looper.java:155)
07-01 12:06:58.533  8022  8067 I Babel_RequestWriter: ,	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:06:58.533  8022  8067 I Babel_RequestWriter: 
07-01 12:06:58.533  8022  8067 I Babel_RequestWriter: Origin stack:
07-01 12:06:58.533  8022  8067 I Babel_RequestWriter: java.lang.Throwable
07-01 12:06:58.533  8022  8067 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.e(SourceFile:1157),
07-01 12:06:58.533  8022  8067 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.f(SourceFile:3214)
07-01 12:06:58.533  8022  8067 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.s(SourceFile:2980)
07-01 12:06:58.533  8022  8067 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.stickers.StickersModule.a(SourceFile:132)
07-01 12:06:58.533  8022  8067 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.stickers.StickersModule.v_(SourceFile:105)
07-01 12:06:58.533  8022  8067 I Babel_RequestWriter: 	,at com.google.android.apps.hangouts.phone.EsApplication.onCreate(SourceFile:566)
07-01 12:06:58.533  8022  8067 I Babel_RequestWriter: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1025)
07-01 12:06:58.533  8022  8067 I Babel_RequestWriter: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4959)
07-01 12:06:58.533  8022  8067 I Babel_RequestWriter: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
07-01 12:06:58.533  8022  8067 I Babel_RequestWriter: 	,at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
,07-01 12:06:58.533  8022  8067 I Babel_RequestWriter: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:06:58.533  8022  8067 I Babel_RequestWriter: 	at android.os.Looper.loop(Looper.java:155)
07-01 12:06:58.533  8022  8067 I Babel_RequestWriter: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
07-01 12:06:58.533  8022  8067 I Babel_RequestWriter: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 12:06:58.533  8022  8067 I Babel_RequestWriter: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 12:06:58.533  8022  8067 I Babel_RequestWriter: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
07-01 12:06:58.533  8022  8067 I Babel_RequestWriter: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
07-01 12:06:58.533  8022  8067 I Babel_RequestWriter: ]; took 0 ms (error code == 101)
,07-01 12:06:58.783  3452  3896 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
07-01 12:06:58.783  3452  3896 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@2966e341 +
07-01 12:06:58.783  3452  3896 I Prism.WidgetManager: onLoadItems() +
,07-01 12:06:58.803  8185  8357 W jxcore-log: Initializing JXcore engine,
07-01 12:06:58.803  8185  8357 W jxcore-log: JXcore engine is ready
,07-01 12:06:58.853  8185  8357 W jxcore-log: Starting JXcore engine,
,07-01 12:06:58.923  8185  8357 W jxcore-log: Platform android
07-01 12:06:58.923  8185  8357 W jxcore-log: 
07-01 12:06:58.923  8185  8357 W jxcore-log: Process ARCH arm
07-01 12:06:58.923  8185  8357 W jxcore-log: 
,07-01 12:06:58.933   575   575 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-01 12:06:59.033  8185  8357 I jxcore-log: JXcore Cordova bridge is ready!,
07-01 12:06:59.033  8185  8357 I jxcore-log: 
07-01 12:06:59.033  8185  8357 W jxcore-log: JXcore engine is started
,07-01 12:06:59.043  8185  8302 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-01 12:06:59.053  8185  8185 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-01 12:06:59.063  8185  8357 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
07-01 12:06:59.063  8185  8357 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,07-01 12:06:59.063  8185  8185 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
07-01 12:06:59.063  8185  8185 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,07-01 12:06:59.093  8185  8185 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-01 12:06:59.093  1114  3923 D PMS     : acquireWL(2c2f9870): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 1114 1000 null
07-01 12:06:59.093  8185  8185 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
07-01 12:06:59.093  8185  8302 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 23ms. Plugin should use CordovaInterface.getThreadPool().
,07-01 12:06:59.103  1114  3534 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true,
07-01 12:06:59.103  1114  1149 I ActivityManager: Waited long enough for: ServiceRecord{3ce06a0a u0 com.htc.club/com.mcrm.autonotification.NotificationService}
,07-01 12:06:59.103  8334  8363 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
07-01 12:06:59.103  8334  8363 W HTCLOG  : mask=0x18
,07-01 12:06:59.113  3452  3452 I FeedHostManager: [onResume]
07-01 12:06:59.113  3452  3452 I FeedProviderManager: onResume
07-01 12:06:59.113  3452  4899 I SocialFeedProvider: +onResume
07-01 12:06:59.113  3452  4899 I SocialFeedProvider: updateAccounts - Accounts is no change
07-01 12:06:59.113  3452  4899 I SocialFeedProvider: -onResume
07-01 12:06:59.123  3452  3452 I ConnectivityHelper: [getCurrentConnectionType] no network connection
,07-01 12:06:59.123  3452  3452 I ContextualWidget: onResume
,07-01 12:06:59.123  3452  3452 I ContextualWidget: notifyWidgetActive location size=0 user consent location=false
07-01 12:06:59.123  3452  3452 I ContextualWidget: ignore uploadUsageData location=false usage data=false allowAutoUpload=true
07-01 12:06:59.123  3452  4034 I ContextualWidget: handleMessage, what=1018 mode=GettingOut maxcount=8
07-01 12:06:59.123  3452  3452 I ContextualWidget: postSyncRecommendedApps, isReady=true allowAutoSync=true syncMode=1 isEnableRecommend=true
,07-01 12:06:59.123  1114  1150 D StatusBarManagerService: setSystemUiVisibility(0x8700)
07-01 12:06:59.123  3127  3127 I PhoneStatusBar: setSystemUiNavVisibility(swipe=false hasFocus=false hasPolicy=false shadeState=true)
07-01 12:06:59.123  1114  1150 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{2b365e7c u0 com.htc.launcher/com.htc.launcher.Launcher}
07-01 12:06:59.123  3127  3127 I PhoneStatusBar: hiding the MENU button mLongPressHomeMenu = false
07-01 12:06:59.123  1114  1150 D StatusBarManagerService: hiding MENU key
,07-01 12:06:59.133  3452  3452 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,07-01 12:06:59.133  3452  3452 I ThreadedRenderer: Defer allocateBuffers to drawing time
07-01 12:06:59.133  3127  3127 I PhoneStatusBar: setImeWindowStatus(false,false)
,07-01 12:06:59.133  1114  1133 I InputMethodManagerService: Disable input method client, pid=8185
07-01 12:06:59.133  8185  8185 W IInputConnectionWrapper: reportFullscreenMode on inactive InputConnection
07-01 12:06:59.133  1114  1133 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
07-01 12:06:59.133  1114  1133 I InputMethodManagerService: Enable input method client, pid=3452
,07-01 12:06:59.153  3452  3896 E Prism.WidgetManager: The same lists. No need to update. skip it.
,07-01 12:06:59.153  3452  3896 I Prism.WidgetManager: onLoadItems() -
07-01 12:06:59.153  3452  3896 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@2966e341 -
07-01 12:06:59.163  1114  3937 I ActivityManager: Start proc 8371:com.google.android.apps.plus/u0a126 for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor
07-01 12:06:59.163  1114  3937 I ActivityManager: Killing 7865:com.htc.mobiledata:remote/u0a39 (adj 15): empty #17
07-01 12:06:59.163  1114  3937 D Process : killProcessQuiet, pid=7865
07-01 12:06:59.163  1114  3937 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityManagerService.trimApplications:19731 
07-01 12:06:59.163  1114  1150 D StatusBarManagerService: setSystemUiVisibility(0xc0000700),
07-01 12:06:59.163  1114  1150 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{2b365e7c u0 com.htc.launcher/com.htc.launcher.Launcher}
07-01 12:06:59.163  1114  1150 D StatusBarManagerService: hiding MENU key
07-01 12:06:59.173  3127  3127 I PhoneStatusBar: setSystemUiNavVisibility(swipe=false hasFocus=false hasPolicy=false shadeState=true)
07-01 12:06:59.173  3127  3127 I PhoneStatusBar: hiding the MENU button mLongPressHomeMenu = false
,07-01 12:06:59.183  8371  8371 W HTCLOG  : use specified tag [FDManager], func [0].
07-01 12:06:59.183  8371  8371 W HTCLOG  : mask=0x18
,07-01 12:06:59.183  6718  6794 I Icing   : Indexing CF3FE6BD92DAECCC594E8F8BDE8C89D040E637CF from com.google.android.googlequicksearchbox
,07-01 12:06:59.193  1114  3670 I ActivityManager: Recipient 7865
,07-01 12:06:59.203  3452  4731 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467367619218
,07-01 12:06:59.253  8369  8369 W HTCLOG  : use specified tag [AndroidRuntime], func [0].
07-01 12:06:59.253  8369  8369 W HTCLOG  : mask=0x18,
,07-01 12:06:59.303  3452  4731 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1467367619318,
,07-01 12:06:59.323  3452  4424 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467367619339
,07-01 12:06:59.383  8334  8334 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
07-01 12:06:59.383  1114  3937 D PMS     : releaseWL(2c2f9870): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,07-01 12:06:59.403  8371  8371 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-01 12:06:59.413  8185  8185 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-01 12:06:59.413  8185  8185 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED,
07-01 12:06:59.413  8185  8185 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-01 12:06:59.413  8185  8185 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
07-01 12:06:59.413  8185  8185 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-01 12:06:59.413  8185  8185 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-01 12:06:59.413  8185  8185 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-01 12:06:59.413  8185  8185 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-01 12:06:59.413  8185  8185 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8e53802 removed from the list
07-01 12:06:59.413  8185  8185 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-01 12:06:59.413  8185  8185 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f303949 removed from the list
07-01 12:06:59.413  8185  8185 D io.jxcore.node.ConnectivityMonitor: stop
07-01 12:06:59.413  8185  8185 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,07-01 12:06:59.423  8185  8185 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-01 12:06:59.433  8369  8397 W HTCLOG  : use specified tag [cutils-trace], func [0].
07-01 12:06:59.433  8369  8397 W HTCLOG  : mask=0x18
,07-01 12:06:59.443  8369  8397 E cutils-trace: Error opening trace file: Permission denied (13)
,07-01 12:06:59.463  3452  4424 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1467367619479,
07-01 12:06:59.463  6718  6794 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,07-01 12:06:59.483  3452  4297 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
,07-01 12:06:59.483  8185  8185 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 8185
,07-01 12:06:59.493  3452  4646 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467367619506
,07-01 12:06:59.513  8369  8369 D CustomizationManager: ====startRecUseTime====,
07-01 12:06:59.513  8369  8369 D htc.customization.log.level:  is 
07-01 12:06:59.513  8369  8369 W CustomizationLogLevel: Level value is invalid, use default level 2
,07-01 12:06:59.563  8369  8369 D CustomizationManager:  Read ACC file spent 0.026 (s)
,07-01 12:06:59.563  8369  8369 D CIDMapFileReader: Parsing tag item name = HTC__001
07-01 12:06:59.563  8369  8369 D CIDMapFileReader: Parsing tag item name = HTC__002
07-01 12:06:59.563  8369  8369 D CIDMapFileReader: Parsing tag item name = HTC__016
07-01 12:06:59.563  8369  8369 D CIDMapFileReader: Parsing tag item name = HTC__031
07-01 12:06:59.563  8369  8369 D CIDMapFileReader: Parsing tag item name = HTC__032
,07-01 12:06:59.563  8369  8369 D CIDMapFileReader: Parsing tag item name = HTC__102
07-01 12:06:59.563  8369  8369 D CIDMapFileReader: Parsing tag item name = HTC__A07
07-01 12:06:59.563  8369  8369 D CIDMapFileReader: Parsing tag item name = HTC__J15
07-01 12:06:59.563  8369  8369 D CIDMapFileReader: Parsing tag item name = HTC__M27,
07-01 12:06:59.563  8369  8369 D CIDMapFileReader: Parsing tag item name = HTC__Y13
07-01 12:06:59.563  8369  8369 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__102.xml
07-01 12:06:59.563  8369  8369 I CustomizationCIDLoader: Parsing tag category name = application
07-01 12:06:59.563  8369  8369 I CustomizationCIDLoader: Parsing tag category name = system
07-01 12:06:59.573  8369  8369 I CustomizationCIDLoader: Parsing tag category name = Settings
07-01 12:06:59.573  8369  8369 I CustomizationCIDLoader: Parsing tag category name = ACC
07-01 12:06:59.573  8369  8369 I CustomizationCIDLoader: add string-array item, value = 42507
07-01 12:06:59.573  8369  8369 I CustomizationCIDLoader: add string-array item, value = 21902
07-01 12:06:59.573  8369  8369 I CustomizationCIDLoader: add string-array item, value = 26006:26001.26002.26003
07-01 12:06:59.573  8369  8369 I CustomizationCIDLoader: add string-array item, value = 23420
07-01 12:06:59.573  8369  8369 I CustomizationCIDLoader: add string-array item, value = 22299
07-01 12:06:59.573  8369  8369 I CustomizationCIDLoader: add string-array item, value = 24002
07-01 12:06:59.573  8369  8369 I CustomizationCIDLoader: add string-array item, value = 23210
07-01 12:06:59.573  8369  8369 I CustomizationCIDLoader: add string-array item, value = 23205
07-01 12:06:59.573  8369  8369 I CustomizationCIDLoader: add string-array item, value = 23806
07-01 12:06:59.573  8369  8369 I CustomizationCIDLoader: add string-array item, value = 23430
07-01 12:06:59.573  8369  8369 I CustomizationCIDLoader: add string-array item, value = 23408
07-01 12:06:59.573  8369  8369 I CustomizationCIDLoader: add string-array item, value = 27205
07-01 12:06:59.573  8369  8369 I CustomizationCIDLoader: add string-array item, value = 27202:27205
07-01 12:06:59.573  8369  8369 I CustomizationCIDLoader: add string-array item, value = 27216:27202.27205
07-01 12:06:59.573  8369  8369 I CustomizationCIDLoader: add string-array item, value = 42507:C:1:0
07-01 12:06:59.573  8369  8369 I CustomizationCIDLoader: add string-array item, value = 21902:C:1:0
07-01 12:06:59.573  8369  8369 I CustomizationCIDLoader: add string-array item, value = 26006:D:1:0
07-01 12:06:59.573  8369  8369 I CustomizationCIDLoader: add string-array item, value = 23420:D:0:0
07-01 12:06:59.573  8369  8369 I CustomizationCIDLoader: add string-array item, value = 27205:C:1:0
07-01 12:06:59.573  8369  8369 I CustomizationCIDLoader: add string-array item, value = 22299:D:0:0
07-01 12:06:59.573  8369  8369 I CustomizationCIDLoader: add string-array item, value = 24002:D:0:0
07-01 12:06:59.573  8369  8369 I CustomizationCIDLoader: add string-array item, value = 23210:D:2:0
07-01 12:06:59.573  8369  8369 I CustomizationCIDLoader: add string-array item, value = 23205:D:2:0
07-01 12:06:59.573  8369  8369 I CustomizationCIDLoader: add string-array item, value = 23806:D:0:0
07-01 12:06:59.573  8369  8369 I CustomizationCIDLoader: add string-array item, value = 23430:C:1:0
07-01 12:06:59.573  8369  8369 I CustomizationCIDLoader: add string-array item, value = 23408:C:1:0
07-01 12:06:59.573  8369  8369 I CustomizationCIDLoader: add string-array item, value = 27202:C:1:0
07-01 12:06:59.573  8369  8369 I CustomizationCIDLoader: add string-array item, value = 27216:C:1:0
07-01 12:06:59.573  8369  8369 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
07-01 12:06:59.573  8369  8369 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
07-01 12:06:59.573  8369  8369 I CustomizationCIDLoader: Parsing tag category name = AudioService
07-01 12:06:59.573  8369  8369 D CustomizationManager:  Read CID file spent 0.058 (s)
07-01 12:06:59.573  8369  8369 D CustomizationManager:  All configurations done spent 0.059 (s)
07-01 12:06:59.583  6718  6794 I Icing   : Indexing done CF3FE6BD92DAECCC594E8F8BDE8C89D040E637CF
,07-01 12:06:59.593  1114  3041 D PackageManager: deletePackageAsUser: pkg=com.test.thalitest user=0, pid=8369, uid=2000,
,07-01 12:06:59.603  1114  1149 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
07-01 12:06:59.603  1114  1149 D Process : killProcessQuiet, pid=8185
07-01 12:06:59.603  1114  1149 I ActivityManager: Killing 8185:com.test.thalitest/u0a0 (adj 9): stop com.test.thalitest
,07-01 12:06:59.603  1114  1149 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.removeProcessLocked:6195 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5997 
,07-01 12:06:59.663  3452  4243 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,07-01 12:06:59.673  1114  1185 W PackageSettings: Skipping PackageSetting{1881bbe1 com.example.hello/10193} due to missing metadata
,07-01 12:06:59.703   533   533 W HTCLOG  : use specified tag [Vector], func [0].,
07-01 12:06:59.703   533   533 W HTCLOG  : mask=0x18
,07-01 12:06:59.723  1114  3670 I ActivityManager: Recipient 8185
07-01 12:06:59.723  1114  2973 D WifiService: Client connection lost with reason: 4
,07-01 12:06:59.723  3264  3264 W HTCLOG  : use specified tag [InputEventReceiver], func [0].
07-01 12:06:59.733  3264  3264 W HTCLOG  : mask=0x18
07-01 12:06:59.733  3264  3264 E InputEventReceiver: Looper::removeFd(33) is failed, result(0), input channel 'ClientState{3eb78109 uid 10000 pid 8185} (c)'
07-01 12:06:59.733  3452  4646 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1467367619741
,07-01 12:06:59.743  3452  4731 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467367619752
,07-01 12:06:59.813  1114  1185 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed,
,07-01 12:06:59.833  1114  3670 W ActivityManager: Spurious death for ProcessRecord{204296a3 8185:com.test.thalitest/u0a0}, curProc for 8185: null
,07-01 12:06:59.833  1114  3494 I ActivityManager: Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,07-01 12:06:59.843  3205  3205 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest,
07-01 12:06:59.843  3205  3205 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
07-01 12:06:59.843  1114  2968 V NetworkPolicy: ACTION_UID_REMOVED for uid=10000
07-01 12:06:59.843  5041  5041 I [MirrorLinkServer]MirrorLinkServer: Broadcast Received::Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
07-01 12:06:59.843  1114  2968 V NetworkPolicy: writePolicyLocked()
,07-01 12:06:59.843  5041  5041 D [MirrorLinkServer]MirrorLinkServer: ACTION_PACKAGE_REMOVED intent received
07-01 12:06:59.843  1114  2967 D PMS     : acquireWL(2b51fda0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 1114 1000 null
,07-01 12:06:59.843  5041  5041 D [MirrorLinkServer]MirrorLinkServer: Counter : 1
,07-01 12:06:59.843  5041  5041 D [MirrorLinkServer]MirrorLinkConnectionReceiver: notifyMlSevrer
,07-01 12:06:59.853  3717  4236 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,07-01 12:06:59.853  1114  3660 D PMS     : acquireWL(2a4f5d1e): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 4270 10020 WorkSource{10020 com.google.android.gms}
,07-01 12:06:59.853  1114  2968 D NetworkPolicy: notifyPoliciesChangeLocked: no change
07-01 12:06:59.853  4270  4644 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-01 12:06:59.853  1114  3966 D PMS     : releaseWL(32387096): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10020 com.google.android.gms}
07-01 12:06:59.853  5041  5041 I [MirrorLinkServer]MirrorLinkServer: onStartCommand() Action : android.intent.action.PACKAGE_REMOVED
07-01 12:06:59.853  5041  5041 D [MirrorLinkServer]MirrorLinkServer: Application Removed
07-01 12:06:59.853  5041  5041 D [MirrorLinkServer]MirrorLinkServer:  Application removed : com.test.thalitest
07-01 12:06:59.853  5041  5041 D [MirrorLinkServer]d: onApplicationRemoved
07-01 12:06:59.853  5041  5041 I [MirrorLinkServer]d: Package name found : com.test.thalitest
07-01 12:06:59.853  1114  3961 D PMS     : releaseWL(2a4f5d1e): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10020 com.google.android.gms}
07-01 12:06:59.853  3452  4034 I ContextualWidget: handleMessage, what=1017 mode=GettingOut maxcount=8
07-01 12:06:59.853  1114  3660 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-01 12:06:59.853  1114  3961 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
07-01 12:06:59.863  1114  3253 I ActivityManager: Resuming delayed broadcast
07-01 12:06:59.863  3452  4731 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1467367619871
07-01 12:06:59.863  3717  4236 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
07-01 12:06:59.863  5041  8417 I [MirrorLinkServer]c: onApplicationUpdationCompleted, sending broadcast
07-01 12:06:59.863  5041  5041 I [MirrorLinkServer]MirrorLinkServer: Broadcast Received::Intent { act=com.htc.HTCMirrorLinkServer.PACKAGE_UPDATE_COMPLETED }
07-01 12:06:59.863  5041  5041 D [MirrorLinkServer]MirrorLinkServer: ML_PACKAGE_UPDATE_COMPLETED intent received
07-01 12:06:59.863  5041  5041 D [MirrorLinkServer]MirrorLinkServer: Counter : 0
07-01 12:06:59.863  5041  5041 I [MirrorLinkServer]MirrorLinkConnectionReceiver: checkAndStopMLSession
07-01 12:06:59.863  5041  5041 I [MirrorLinkServer]MirrorLinkConnectionReceiver: Stopping Service
,07-01 12:06:59.863  1114  1148 I InputMethodManagerService: [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
07-01 12:06:59.863  1114  3660 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,07-01 12:06:59.863  1114  3041 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,07-01 12:06:59.873  1114  3961 D PMS     : acquireWL(11290615): PARTIAL_WAKE_LOCK  AsyncService 0x1 8371 10126 null
,07-01 12:06:59.873  3717  4236 D AccTypeManager: Registering external account type=com.google.android.gm.exchange, packageName=com.google.android.gm
07-01 12:06:59.873  6444  6444 I art     : Explicit concurrent mark sweep GC freed 10509(699KB) AllocSpace objects, 0(0B) LOS objects, 31% free, 4MB/6MB, paused 342us total 52.164ms
,07-01 12:06:59.873  3717  4236 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,07-01 12:06:59.883  3452  4374 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467367619891
,07-01 12:06:59.883  1114  2968 V NetworkPolicy: updateNetworkEnabledLocked()
07-01 12:06:59.883  1114  2968 V NetworkPolicy: updateNotificationsLocked()
,07-01 12:06:59.893  1114  2967 D PMS     : releaseWL(2b51fda0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,07-01 12:06:59.893  1114  2962 W SystemReader: Cannot find grip_rejection_width, use default value instead,
,07-01 12:06:59.913  1114  3961 D PMS     : releaseWL(11290615): PARTIAL_WAKE_LOCK  AsyncService 0x1 null,
,07-01 12:06:59.923  3717  4236 E ExternalAccountType: Unsupported attribute readOnly
,07-01 12:06:59.933  3418  3418 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED,
07-01 12:06:59.933  1114  2959 V AlarmManager: sending alarm PendingIntent{3dc6e7e8: PendingIntentRecord{2eed4471 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=63419, Int=0
,07-01 12:06:59.983  1114  1148 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,07-01 12:06:59.983  1114  1114 W PackageManager: Unable to load service info ResolveInfo{3b72a82c com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
07-01 12:06:59.983  1114  1114 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data,
07-01 12:06:59.983  1114  1114 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:509)
07-01 12:06:59.983  1114  1114 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:345)
07-01 12:06:59.983  1114  1114 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:171)
07-01 12:06:59.983  1114  1114 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:71)
07-01 12:06:59.983  1114  1114 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:180)
07-01 12:06:59.983  1114  1114 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:927)
07-01 12:06:59.983  1114  1114 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
07-01 12:06:59.983  1114  1114 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-01 12:06:59.983  1114  1114 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
07-01 12:06:59.983  1114  1114 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:331)
07-01 12:06:59.983  1114  1114 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:232)
07-01 12:06:59.983  1114  1114 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 12:06:59.983  1114  1114 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 12:06:59.983  1114  1114 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
07-01 12:06:59.983  1114  1114 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
,07-01 12:06:59.993  1114  2959 V AlarmManager: sending alarm PendingIntent{1a137cc7: PendingIntentRecord{133af2f4 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=63469, Int=0,
07-01 12:06:59.993  6718  8420 E IntentOperationSvc: Failed to instantiate Chimera operation impl, dropping operation
,07-01 12:06:59.993  6718  6718 D AsyncTaskServiceImpl: Submit a task: nwp,
07-01 12:06:59.993  6718  8422 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,07-01 12:07:00.003  3452  8419 D HtcTelephonyManager: wrong phone slot in non-dual projects
07-01 12:07:00.003  1114  1185 I art     : Explicit concurrent mark sweep GC freed 32379(2MB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 17MB/26MB, paused 2.031ms total 173.726ms,
07-01 12:07:00.003  6718  8422 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
07-01 12:07:00.013  6718  6794 D nwp     : Processing package: com.test.thalitest
,07-01 12:07:00.013  6718  6794 W nwp     : Failed to find package com.test.thalitest
,07-01 12:07:00.023  3127  3956 I ClockController: schedule update now=1467367620030 next=59970
,07-01 12:07:00.023  3452  4374 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1467367620032
,07-01 12:07:00.023  3127  3127 I Clock   : updateClock:12:07 Europe/Brussels
,07-01 12:07:00.033  8334  8334 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,07-01 12:07:00.033  3452  4365 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.,
07-01 12:07:00.033  1114  3254 D Process : killProcessQuiet, pid=7844
,07-01 12:07:00.033  1114  3254 I ActivityManager: Delay finish: com.google.android.gms/.gcm.GcmPackageTracker$GcmPackageChangeReceiver
07-01 12:07:00.033  1114  3254 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19304 
07-01 12:07:00.033  1114  3254 I ActivityManager: Killing 7844:com.htc.autobot/u0a27 (adj 15): empty #17
,07-01 12:07:00.043  8369  8369 I art     : System.exit called, status: 0
,07-01 12:07:00.053  3452  4297 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467367620062
,07-01 12:07:00.113  3452  8419 D HtcTelephonyManager: wrong phone slot in non-dual projects,
,07-01 12:07:00.143  1114  3253 I ActivityManager: Recipient 7844
,07-01 12:07:00.143  1114  1114 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED,
07-01 12:07:00.143  3127  3127 I Clock   : updateClock:12:07 Europe/Brussels
,07-01 12:07:00.153  3127  3127 I Clock   : updateClock:12:07 Europe/Brussels
,07-01 12:07:00.153  1114  3660 D PMS     : acquireWL(3bee9efa): PARTIAL_WAKE_LOCK  Icing 0x1 6718 10020 WorkSource{10020 com.google.android.gms}
07-01 12:07:00.153  3382  3382 D Nfc-Utils: isNxpCodebase: isNxp=false,
07-01 12:07:00.153  6718  8422 E Vision  : Failed to find package com.test.thalitest
07-01 12:07:00.153  6718  8422 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,07-01 12:07:00.173  1114  3254 I ActivityManager: Resuming delayed broadcast
,07-01 12:07:00.183  6718  7990 E WorkSourceUtil: Could not find package: com.test.thalitest
,07-01 12:07:00.183  3127  4721 D WeatherUtility: Weather sync is On
,07-01 12:07:00.183  3127  4721 W WeatherTimeKeeper: [refreshWeatherData] no weather data
,07-01 12:07:00.203  6718  6794 E Icing   : Package com.test.thalitest not found
,07-01 12:07:00.203  3452  4297 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1467367620219
,07-01 12:07:00.213  1114  3253 D PMS     : releaseWL(3bee9efa): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10020 com.google.android.gms}
,07-01 12:07:00.223  3452  4424 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467367620234
,07-01 12:07:00.283  1114  3494 I ActivityManager: Start proc 8432:com.android.vending/u0a57 for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,07-01 12:07:00.293  8432  8432 W HTCLOG  : use specified tag [FDManager], func [0].
07-01 12:07:00.293  8432  8432 W HTCLOG  : mask=0x18
,07-01 12:07:00.303  1114  3494 D PMS     : acquireWL(2be7769b): PARTIAL_WAKE_LOCK  Icing 0x1 6718 10020 WorkSource{10020 com.google.android.gms}
,07-01 12:07:00.323  3452  8419 D libc    : [NET] android_getaddrinfofornet+,hn 28(0x7265636f6d6d65),sn(),hints(known),family 0,flags 4
07-01 12:07:00.323  3452  8419 D libc    : [NET] android_getaddrinfofornet-, err=8
07-01 12:07:00.323  3452  8419 D libc    : [NET] android_getaddrinfofornet+,hn 28(0x7265636f6d6d65),sn(),hints(known),family 0,flags 1024
07-01 12:07:00.323  3452  8419 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
07-01 12:07:00.323  3452  8419 D libc    : [NET] android_getaddrinfo_proxy+
07-01 12:07:00.333  3452  8419 D libc    : [NET] android_getaddrinfo_proxy get netid:0
,07-01 12:07:00.333   523  8453 D libc    : [NET] android_getaddrinfofornet+,hn 28(0x7265636f6d6d65),sn(),hints(known),family 0,flags 1024
07-01 12:07:00.333   523  8453 D libc    : [NET] _dns_getaddrinfo+, netid:0, mark:917504
,07-01 12:07:00.333   523  8453 D libc    : [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
07-01 12:07:00.333   523  8453 D libc    : [NET] android_getaddrinfofornet-, err=7
,07-01 12:07:00.333  3452  8419 D libc    : [NET] android_getaddrinfo_proxy-, NODATA
07-01 12:07:00.333  3452  8419 E ServerCorridor: BaseException: ServiceUnavailableException java.lang.Throwable: Unable to resolve host "recommend-prism.htcsense.com": No address associated with hostname
07-01 12:07:00.333  3452  8419 W System.err: com.htc.prism.feed.corridor.exceptions.ServiceUnavailableException: java.lang.Throwable: Unable to resolve host "recommend-prism.htcsense.com": No address associated with hostname
,07-01 12:07:00.333  3452  8419 W System.err: 	at com.htc.prism.feed.corridor.RestClient.sendHTTPRequest(RestClient.java:192)
07-01 12:07:00.333  3452  8419 W System.err: 	at com.htc.prism.feed.corridor.RestClient.sendHTTPRequest(RestClient.java:98)
,07-01 12:07:00.333  3452  8419 W System.err: 	at com.htc.prism.feed.corridor.RestClient.getString(RestClient.java:367)
07-01 12:07:00.333  3452  8419 W System.err: 	at com.htc.prism.feed.corridor.recommendation.RecommendationNService.getWelcomeAppSuggest(RecommendationNService.java:125)
07-01 12:07:00.333  3452  8419 W System.err: 	at com.htc.launcher.htcwidget.HtcContextualWidgetService.syncRecommendedApps(HtcContextualWidgetService.java:374)
07-01 12:07:00.333  3452  8419 W System.err: 	at com.htc.launcher.htcwidget.HtcContextualWidgetService.onHandleIntent(HtcContextualWidgetService.java:168)
07-01 12:07:00.333  3452  8419 W System.err: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-01 12:07:00.333  3452  8419 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:07:00.333  3452  8419 W System.err: 	at android.os.Looper.loop(Looper.java:155)
07-01 12:07:00.333  3452  8419 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:07:00.333  3452  8419 W System.err: Caused by: java.lang.Throwable: Unable to resolve host "recommend-prism.htcsense.com": No address associated with hostname
07-01 12:07:00.333  3452  8419 W System.err: 	at java.net.InetAddress.lookupHostByName(InetAddress.java:457)
07-01 12:07:00.333  3452  8419 W System.err: 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
07-01 12:07:00.333  3452  8419 W System.err: 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
07-01 12:07:00.333  3452  8419 W System.err: 	at com.android.okhttp.HostResolver$1.getAllByName(HostResolver.java:29)
07-01 12:07:00.333  3452  8419 W System.err: 	at com.android.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:232)
07-01 12:07:00.333  3452  8419 W System.err: 	at com.android.okhttp.internal.http.RouteSelector.next(RouteSelector.java:124)
07-01 12:07:00.333  3452  8419 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:272)
07-01 12:07:00.333  3452  8419 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:211)
07-01 12:07:00.333  3452  8419 W System.err: 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:403)
07-01 12:07:00.333  3452  8419 W System.err: 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.connect(HttpURLConnectionImpl.java:116)
07-01 12:07:00.333  3452  8419 W System.err: 	at com.android.okhttp.internal.http.DelegatingHttpsURLConnection.connect(DelegatingHttpsURLConnection.java:89)
07-01 12:07:00.333  3452  8419 W System.err: 	at com.android.okhttp.internal.http.HttpsURLConnectionImpl.connect(HttpsURLConnectionImpl.java:25)
07-01 12:07:00.333  3452  8419 W System.err: 	at com.htc.prism.feed.corridor.RestClient.sendHTTPRequest(RestClient.java:137)
,07-01 12:07:00.333  3452  8419 W System.err: 	... 9 more
07-01 12:07:00.333  3452  3776 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/com.htc.launcher.prefs.contextualwidget.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/com.htc.launcher.prefs.contextualwidget.xml.bak
,07-01 12:07:00.353  3452  4424 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1467367620364
,07-01 12:07:00.373  3452  4351 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467367620381
,07-01 12:07:00.373  3452  4351 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml.bak
,07-01 12:07:00.413  3936  8455 I art     : Explicit concurrent mark sweep GC freed 2351(91KB) AllocSpace objects, 0(0B) LOS objects, 67% free, 966KB/2MB, paused 382us total 28.064ms,
,07-01 12:07:00.443  1114  3961 I PackageManager:  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=8432, uid=10057, userID:0,
,07-01 12:07:00.453  8432  8432 W global  : [apache-http] Connection GC has been deprecated!
,07-01 12:07:00.453  3452  4351 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1467367620470
,07-01 12:07:00.463  8432  8432 I Finsky  : [1] com.google.android.finsky.FinskyApp.onCreate(428): Initializing network with DFE https://android.clients.google.com/fdfe/
,07-01 12:07:00.473  3452  4343 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
,07-01 12:07:00.483  3452  4646 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467367620498
,07-01 12:07:00.493  3452  4646 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml.bak
,07-01 12:07:00.573  8432  8432 E RollingFileStream: Could not create a temp file with prefix: "eventlog.store" and suffix: ".log" in dir: "/data/data/com.android.vending/cache/logs/com.google.thalitester%40gmail.com".,
07-01 12:07:00.573  3452  4646 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1467367620584
,07-01 12:07:00.583  3452  4732 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467367620597
,07-01 12:07:00.593  3452  4732 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml.bak
,07-01 12:07:00.603  8432  8432 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(168): Dirty, need more hygiene.,
,07-01 12:07:00.613  1114  1149 I ActivityManager: Waited long enough for: ServiceRecord{35ea6985 u0 com.nero.android.htc.sync/.PowerDisconService}
,07-01 12:07:00.623  4270  4270 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.,
07-01 12:07:00.623  8432  8432 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-01 12:07:00.633  8432  8432 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-01 12:07:00.633  8432  8475 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
07-01 12:07:00.633  8432  8475 W HTCLOG  : mask=0x18
,07-01 12:07:00.633  8432  8475 E SQLiteDatabase: Failed to open database '/data/data/com.android.vending/databases/library.db'.
07-01 12:07:00.633  8432  8475 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 12:07:00.633  8432  8475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 12:07:00.633  8432  8475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 12:07:00.633  8432  8475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 12:07:00.633  8432  8475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-01 12:07:00.633  8432  8475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-01 12:07:00.633  8432  8475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-01 12:07:00.633  8432  8475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-01 12:07:00.633  8432  8475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-01 12:07:00.633  8432  8475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-01 12:07:00.633  8432  8475 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-01 12:07:00.633  8432  8475 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-01 12:07:00.633  8432  8475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 12:07:00.633  8432  8475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 12:07:00.633  8432  8475 E SQLiteDatabase: 	at com.google.android.finsky.j.av.iterator(SourceFile:15316)
07-01 12:07:00.633  8432  8475 E SQLiteDatabase: 	at com.google.android.finsky.j.w.run(SourceFile:1078)
07-01 12:07:00.633  8432  8475 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
07-01 12:07:00.633  8432  8475 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-01 12:07:00.633  8432  8475 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
07-01 12:07:00.633  8432  8475 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-01 12:07:00.633  8432  8475 W Finsky.CrashDetector: Failed to write crash file cnt=0 ts=0 cause=null.
07-01 12:07:00.633  8432  8475 W Finsky.CrashDetector: java.io.FileNotFoundException: /data/data/com.android.vending/cache/crash806713: open failed: EROFS (Read-only file system)
07-01 12:07:00.633  8432  8475 W Finsky.CrashDetector: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 12:07:00.633  8432  8475 W Finsky.CrashDetector: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 12:07:00.633  8432  8475 W Finsky.CrashDetector: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-01 12:07:00.633  8432  8475 W Finsky.CrashDetector: 	at com.google.android.finsky.a.a(SourceFile:180)
07-01 12:07:00.633  8432  8475 W Finsky.CrashDetector: 	at com.google.android.finsky.a.uncaughtException(SourceFile:98)
07-01 12:07:00.633  8432  8475 W Finsky.CrashDetector: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
07-01 12:07:00.633  8432  8475 W Finsky.CrashDetector: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
07-01 12:07:00.633  8432  8475 W Finsky.CrashDetector: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 12:07:00.633  8432  8475 W Finsky.CrashDetector: 	at libcore.io.Posix.open(Native Method)
07-01 12:07:00.633  8432  8475 W Finsky.CrashDetector: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 12:07:00.633  8432  8475 W Finsky.CrashDetector: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 12:07:00.633  8432  8475 W Finsky.CrashDetector: 	... 6 more
07-01 12:07:00.643  1114  1149 I ActivityManager: Killing 7914:com.htc.mobiledata/u0a39 (adj 15): empty #17
07-01 12:07:00.633  8432  8475 E AndroidRuntime: FATAL EXCEPTION: libraries-thread
07-01 12:07:00.633  8432  8475 E AndroidRuntime: Process: com.android.vending, PID: 8432,
07-01 12:07:00.633  8432  8475 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 12:07:00.633  8432  8475 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 12:07:00.633  8432  8475 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 12:07:00.633  8432  8475 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 12:07:00.633  8432  8475 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-01 12:07:00.633  8432  8475 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-01 12:07:00.633  8432  8475 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-01 12:07:00.633  8432  8475 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-01 12:07:00.633  8432  8475 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-01 12:07:00.633  8432  8475 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-01 12:07:00.633  8432  8475 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-01 12:07:00.633  8432  8475 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-01 12:07:00.633  8432  8475 E AndroidRuntime: ,	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 12:07:00.633  8432  8475 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 12:07:00.633  8432  8475 E AndroidRuntime: 	at com.google.android.finsky.j.av.iterator(SourceFile:15316)
07-01 12:07:00.633  8432  8475 E AndroidRuntime: 	at com.google.android.finsky.j.w.run(SourceFile:1078)
07-01 12:07:00.633  8432  8475 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
07-01 12:07:00.633  8432  8475 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-01 12:07:00.633  8432  8475 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
07-01 12:07:00.633  8432  8475 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:07:00.653  1114  8476 E DropBoxManagerService: Can't write: system_app_crash
07-01 12:07:00.653  1114  8476 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
07-01 12:07:00.653  1114  8476 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 12:07:00.653  1114  8476 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 12:07:00.653  1114  8476 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-01 12:07:00.653  1114  8476 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
07-01 12:07:00.653  1114  8476 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-01 12:07:00.653  1114  8476 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
07-01 12:07:00.653  1114  8476 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 12:07:00.653  1114  8476 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-01 12:07:00.653  1114  8476 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 12:07:00.653  1114  8476 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 12:07:00.653  1114  8476 E DropBoxManagerService: 	... 5 more
07-01 12:07:00.643  1114  3041 E ActivityManager: App crashed! Process: com.android.vending
07-01 12:07:00.653  1114  3660 I PackageManager:  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=8432, uid=10057, userID:0
07-01 12:07:00.643  1114  1149 D Process : killProcessQuiet, pid=7914
07-01 12:07:00.653  8432  8477 E AndroidRuntime_2_crash: crash in the same process: AsyncTask #1
07-01 12:07:00.653  8432  8477 E AndroidRuntime_2_crash: java.lang.RuntimeException: An error occured while executing doInBackground()
07-01 12:07:00.653  8432  8477 E AndroidRuntime_2_crash: 	at android.os.AsyncTask$3.done(AsyncTask.java:304)
07-01 12:07:00.653  8432  8477 E AndroidRuntime_2_crash: 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
07-01 12:07:00.653  8432  8477 E AndroidRuntime_2_crash: 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
07-01 12:07:00.653  8432  8477 E AndroidRuntime_2_crash: 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
07-01 12:07:00.653  8432  8477 E AndroidRuntime_2_crash: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
07-01 12:07:00.653  8432  8477 E AndroidRuntime_2_crash: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-01 12:07:00.653  8432  8477 E AndroidRuntime_2_crash: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-01 12:07:00.653  8432  8477 E AndroidRuntime_2_crash: 	at java.lang.Thread.run(Thread.java:818)
07-01 12:07:00.653  8432  8477 E AndroidRuntime_2_crash: Caused by: android.database.sqlite.SQLiteExcep,tion: not an error (code 0): Could not open the database in read/write mode.
07-01 12:07:00.653  8432  8477 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 12:07:00.653  8432  8477 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 12:07:00.653  8432  8477 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 12:07:00.653  8432  8477 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-01 12:07:00.653  8432  8477 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-01 12:07:00.653  8432  8477 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-01 12:07:00.653  8432  8477 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-01 12:07:00.653  8432  8477 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-01 12:07:00.653  8432  8477 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-01 12:07:00.653  8432  8477 E AndroidRuntime_2_crash: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-01 12:07:00.653  8432  8477 E AndroidRuntime_2_crash: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-01 12:07:00.653  8432  8477 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 12:07:00.653  8432  8477 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 12:07:00.653  8432  8477 E AndroidRuntime_2_crash: 	at com.google.android.finsky.c.z.a(SourceFile:2336)
07-01 12:07:00.653  8432  8477 E AndroidRuntime_2_crash: 	at com.google.android.finsky.c.ab.c(SourceFile:56)
07-01 12:07:00.653  8432  8477 E AndroidRuntime_2_crash: 	at com.google.android.finsky.receivers.l.doInBackground(SourceFile:3083)
07-01 12:07:00.653  8432  8477 E AndroidRuntime_2_crash: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
07-01 12:07:00.653  8432  8477 E AndroidRuntime_2_crash: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-01 12:07:00.653  8432  8477 E AndroidRuntime_2_crash: 	... 4 more
07-01 12:07:00.643  1114  1149 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:238 
07-01 12:07:00.653  8432  8477 E SQLiteDatabase: Failed to open database '/data/data/com.android.vending/databases/localappstate.db'.
07-01 12:07:00.653  8432  8477 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 12:07:00.653  8432  8477 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 12:07:00.653  8432  8477 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 12:07:00.653  8432  8477 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 12:07:00.653  8432  8477 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-01 12:07:00.653  8432  8477 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-01 12:07:00.653  8432  8477 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-01 12:07:00.653  8432  8477 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-01 12:07:00.653  8432  8477 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLi,teDatabase.java:854)
07-01 12:07:00.653  8432  8477 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-01 12:07:00.653  8432  8477 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-01 12:07:00.653  8432  8477 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-01 12:07:00.653  8432  8477 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 12:07:00.653  8432  8477 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 12:07:00.653  8432  8477 E SQLiteDatabase: 	at com.google.android.finsky.c.z.a(SourceFile:2336)
07-01 12:07:00.653  8432  8477 E SQLiteDatabase: 	at com.google.android.finsky.c.ab.c(SourceFile:56)
07-01 12:07:00.653  8432  8477 E SQLiteDatabase: 	at com.google.android.finsky.receivers.l.doInBackground(SourceFile:3083)
07-01 12:07:00.653  8432  8477 E SQLiteDatabase: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
07-01 12:07:00.653  8432  8477 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-01 12:07:00.653  8432  8477 E SQLiteDatabase: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
07-01 12:07:00.653  8432  8477 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-01 12:07:00.653  8432  8477 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-01 12:07:00.653  8432  8477 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-01 12:07:00.663  8432  8478 E AndroidRuntime_3_crash: crash in the same process: AsyncTask #2
07-01 12:07:00.663  8432  8478 E AndroidRuntime_3_crash: java.lang.RuntimeException: An error occured while executing doInBackground()
07-01 12:07:00.663  8432  8478 E AndroidRuntime_3_crash: 	at android.os.AsyncTask$3.done(AsyncTask.java:304)
07-01 12:07:00.663  8432  8478 E AndroidRuntime_3_crash: 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
07-01 12:07:00.663  8432  8478 E AndroidRuntime_3_crash: 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
07-01 12:07:00.663  8432  8478 E AndroidRuntime_3_crash: 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
07-01 12:07:00.663  8432  8478 E AndroidRuntime_3_crash: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
07-01 12:07:00.663  8432  8478 E AndroidRuntime_3_crash: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-01 12:07:00.663  8432  8478 E AndroidRuntime_3_crash: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-01 12:07:00.663  8432  8478 E AndroidRuntime_3_crash: 	at java.lang.Thread.run(Thread.java:818)
07-01 12:07:00.663  8432  8478 E AndroidRuntime_3_crash: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 12:07:00.663  8432  8478 E AndroidRuntime_3_crash: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 12:07:00.663  8432  8478 E AndroidRuntime_3_crash: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 12:07:00.663  8432  8478 E AndroidRuntime_3_crash: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 12:07:00.663  8432  8478 E AndroidRuntime_3_crash: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-01 12:07:00.663  8432  8478 E AndroidRuntime_3_crash: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-01 12:07:00.663  8432  8478 E AndroidRuntime_3_crash: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-01 12:07:00.663  8432  8478 E AndroidRuntime_3_crash: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-01 12:07:00.663  8432  8478 E AndroidRuntime_3_crash: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-01 12:07:00.663  8432  8478 E AndroidRuntime_3_crash: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-01 12:07:00.663  8432  8478 E AndroidRuntime_3_crash: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-01 12:07:00.663  8432  8478 E AndroidRuntime_3_crash: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-01 12:07:00.663  8432  8478 E AndroidRuntime_3_crash: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 12:07:00.663  8432  8478 E AndroidRuntime_3_crash: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 12:07:00.663  8432  8478 E AndroidRuntime_3_crash: 	at com.google.android.finsky.c.z.a(SourceFile:2336)
07-01 12:07:00.663  8432  8478 E AndroidRuntime_3_crash: 	at com.google.android.finsky.c.ab.c(SourceFile:56)
07-01 12:07:00.663  8432  8478 E AndroidRuntime_3_crash: 	at com.google.android.finsky.c.v.doInBackground(SourceFile:4083)
07-01 12:07:00.663  8432  8478 E AndroidRuntime_3_crash: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
07-01 12:07:00.663  8432  8478 E AndroidRuntime_3_crash: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-01 12:07:00.663  8432  8478 E AndroidRuntime_3_crash: 	... 4 more
07-01 12:07:00.653  3452  3896 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
07-01 12:07:00.653  3452  3896 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@2966e341 +
07-01 12:07:00.653  3452  3896 I Prism.WidgetManager: onLoadItems() +
07-01 12:07:00.663  8432  8478 E SQLiteDatabase: Failed to open database '/data/data/com.android.vending/databases/localappstate.db'.
07-01 12:07:00.663  8432  8478 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 12:07:00.663  8432  8478 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 12:07:00.663  8432  8478 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 12:07:00.663  8432  8478 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 12:07:00.663  8432  8478 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-01 12:07:00.663  8432  8478 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-01 12:07:00.663  8432  8478 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-01 12:07:00.663  8432  8478 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-01 12:07:00.663  8432  8478 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-01 12:07:00.663  8432  8478 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-01 12:07:00.663  8432  8478 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-01 12:07:00.663  8432  8478 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-01 12:07:00.663  8432  8478 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 12:07:00.663  8432  8478 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 12:07:00.663  8432  8478 E SQLiteDatabase: 	at com.google.android.finsky.c.z.a(SourceFile:2336)
07-01 12:07:00.663  8432  8478 E SQLiteDatabase: 	at com.google.android.finsky.c.ab.c(SourceFile:56)
07-01 12:07:00.663  8432  8478 E SQLiteDatabase: 	at com.google.android.finsky.c.v.doInBackground(SourceFile:4083)
07-01 12:07:00.663  8432  8478 E SQLiteDatabase: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
07-01 12:07:00.663  8432  8478 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-01 12:07:00.663  8432  8478 E SQLiteDatabase: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
07-01 12:07:00.663  8432  8478 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-01 12:07:00.663  8432  8478 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-01 12:07:00.663  8432  8478 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-01 12:07:00.683  3452  4732 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1467367620692
07-01 12:07:00.693  3452  3896 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
07-01 12:07:00.693  3452  4417 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
07-01 12:07:00.703  3452  4310 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467367620718
07-01 12:07:00.713  3452  4310 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml.bak
,07-01 12:07:00.733  1114  3923 I ActivityManager: Recipient 7914
,07-01 12:07:00.763  1114  3670 D PMS     : acquireWL(ac1225a): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 8022 10102 null,
,07-01 12:07:00.803  8432  8472 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
07-01 12:07:00.803  8432  8472 D libc    : [NET] android_getaddrinfofornet-, err=8
07-01 12:07:00.803  8432  8472 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
07-01 12:07:00.803  8432  8472 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
07-01 12:07:00.803  8432  8472 D libc    : [NET] android_getaddrinfo_proxy+
,07-01 12:07:00.803  8432  8472 D libc    : [NET] android_getaddrinfo_proxy get netid:0
07-01 12:07:00.803   523  8484 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
07-01 12:07:00.803   523  8484 D libc    : [NET] _dns_getaddrinfo+, netid:0, mark:917504
07-01 12:07:00.803   523  8484 D libc    : [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
07-01 12:07:00.803   523  8484 D libc    : [NET] android_getaddrinfofornet-, err=7
07-01 12:07:00.803  8432  8472 D libc    : [NET] android_getaddrinfo_proxy-, NODATA
07-01 12:07:00.813  3452  3452 D Prism.PackageStateRece_: action: android.intent.action.PACKAGE_CHANGED
07-01 12:07:00.813  3452  3452 I ContextualWidget: package com.google.android.gms changed
07-01 12:07:00.813  3321  8485 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
07-01 12:07:00.813  3321  8485 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed
07-01 12:07:00.813  1114  1134 D PMS     : releaseWL(ac1225a): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
07-01 12:07:00.813  3452  4034 I ContextualWidget: handleMessage, what=1026 mode=GettingOut maxcount=8
,07-01 12:07:00.823  3696  3902 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
07-01 12:07:00.823  3696  3902 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
07-01 12:07:00.823  3696  3902 W HTCLOG  : mask=0x18
07-01 12:07:00.823  3696  3902 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.android.providers.contacts/databases/contacts2.db, handle: 0x55af7e0f60
,07-01 12:07:00.823  3696  3902 W ContactsProvider: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-01 12:07:00.823  3696  3902 W ContactsProvider: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
07-01 12:07:00.823  3696  3902 W ContactsProvider: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
07-01 12:07:00.823  3696  3902 W ContactsProvider: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
07-01 12:07:00.823  3696  3902 W ContactsProvider: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
07-01 12:07:00.823  3696  3902 W ContactsProvider: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:557)
07-01 12:07:00.823  3696  3902 W ContactsProvider: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:461)
07-01 12:07:00.823  3696  3902 W ContactsProvider: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:391)
07-01 12:07:00.823  3696  3902 W ContactsProvider: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
07-01 12:07:00.823  3696  3902 W ContactsProvider: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2162)
07-01 12:07:00.823  3696  3902 W ContactsProvider: 	at com.android.providers.contacts.HtcContactsProvider2.performBackgroundTask(HtcContactsProvider2.java:11533)
07-01 12:07:00.823  3696  3902 W ContactsProvider: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1819)
07-01 12:07:00.823  3696  3902 W ContactsProvider: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:07:00.823  3696  3902 W ContactsProvider: 	at android.os.Looper.loop(Looper.java:155)
07-01 12:07:00.823  3696  3902 W ContactsProvider: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-01 12:07:00.843  6444  8487 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
07-01 12:07:00.843  1114  1150 D StatusBarManagerService: setSystemUiVisibility(0xc0000000)
,07-01 12:07:00.843  1114  1150 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{170337fe u0 Application Error: com.android.vending}
07-01 12:07:00.853  3127  3127 I PhoneStatusBar: setSystemUiNavVisibility(swipe=false hasFocus=false hasPolicy=false shadeState=true)
07-01 12:07:00.843  1114  1150 D StatusBarManagerService: hiding MENU key
07-01 12:07:00.853  3127  3127 I PhoneStatusBar: hiding the MENU button mLongPressHomeMenu = false
07-01 12:07:00.853  3452  4310 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1467367620861
,07-01 12:07:00.863  1114  3911 I ActivityManager: Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,07-01 12:07:00.873  1114  3937 D PMS     : acquireWL(21eab244): PARTIAL_WAKE_LOCK  AsyncService 0x1 8371 10126 null
,07-01 12:07:00.883  1114  3670 D PMS     : releaseWL(21eab244): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,07-01 12:07:00.893  1114  3688 I ActivityManager: Resuming delayed broadcast
,07-01 12:07:00.903  3452  4731 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467367620912
,07-01 12:07:00.913  3452  4731 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml.bak,
,07-01 12:07:00.923  1114  3962 I ActivityManager: Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
07-01 12:07:00.923  3452  4034 I ContextualWidget: MFU.onDataSetChanged
07-01 12:07:00.923  3452  4034 I ContextualWidget: handleMessage, what=1001 mode=GettingOut maxcount=8
07-01 12:07:00.923  3452  3776 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/com.htc.launcher.prefs.contextualwidget.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/com.htc.launcher.prefs.contextualwidget.xml.bak,
07-01 12:07:00.923  3452  4034 I ContextualWidget: updateMFULaunchCountIfNeeded update=false days=0
07-01 12:07:00.923  3452  4034 I ContextualWidget: Download enabled: true, Recommend enabled: true
07-01 12:07:00.923  3452  4034 I ContextualWidget: sync all data, download=1 recommend=4
07-01 12:07:00.923  3452  4034 I ContextualWidget: sync all data, mode=GettingOut count=8,
07-01 12:07:00.923  3452  4034 I ContextualWidget: notifyDataChanged, list size 8
,07-01 12:07:00.933  6444  8487 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,07-01 12:07:00.943  6444  8487 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
07-01 12:07:00.943  6444  8487 W HTCLOG  : mask=0x18
,07-01 12:07:00.943  6444  8487 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle: 0x55af7bab50
,07-01 12:07:00.943  3452  3452 I HtcContextualWidgetDataManager: onDataChanged: GettingOut, item count: 8, original: 8, first add: false
,07-01 12:07:00.953  3452  8486 I ContextualWidget: com.test.thalitest is not installed
07-01 12:07:00.953  3452  8486 W MFUDataManager: loadDownloadItems - skip DownloadItem: ApplicationInfo(id=-1, title=null, componentNameComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity} appsContainer=<ALLAPPS> P=UserHandle{0})
,07-01 12:07:00.953  3452  8486 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM contextualdownload WHERE component_name=?] disk I/O error
07-01 12:07:00.953  3452  8486 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
07-01 12:07:00.953  3452  8486 W HTCLOG  : mask=0x18
07-01 12:07:00.953  3452  8486 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.htc.launcher/databases/launcher.db, handle: 0xabef7b78
,07-01 12:07:00.953  3452  8486 E AndroidRuntime: FATAL EXCEPTION: IntentService[HtcContextualWidgetService]
07-01 12:07:00.953  3452  8486 E AndroidRuntime: Process: com.htc.launcher, PID: 3452
07-01 12:07:00.953  3452  8486 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-01 12:07:00.953  3452  8486 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-01 12:07:00.953  3452  8486 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
,07-01 12:07:00.953  3452  8486 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-01 12:07:00.953  3452  8486 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-01 12:07:00.953  3452  8486 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
07-01 12:07:00.953  3452  8486 E AndroidRuntime: 	at com.htc.launcher.LauncherProvider.delete(LauncherProvider.java:377)
07-01 12:07:00.953  3452  8486 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
07-01 12:07:00.953  3452  8486 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
07-01 12:07:00.953  3452  8486 E AndroidRuntime: 	at com.htc.launcher.htcwidget.MFUDataManager$DownloadManager.loadDownloadItems(MFUDataManager.java:2463)
07-01 12:07:00.953  3452  8486 E AndroidRuntime: 	at com.htc.launcher.htcwidget.MFUDataManager$DownloadManager.getDownloadList(MFUDataManager.java:2228)
07-01 12:07:00.953  3452  8486 E AndroidRuntime: 	at com.htc.launcher.htcwidget.MFUDataManager.getDownloadList(MFUDataManager.java:2142)
07-01 12:07:00.953  3452  8486 E AndroidRuntime: 	at com.htc.launcher.htcwidget.MFUDataManager.getDownloadList(MFUDataManager.java:2129)
07-01 12:07:00.953  3452  8486 E AndroidRuntime: 	at com.htc.launcher.htcwidget.HtcContextualWidgetService.handlePackageChanged(HtcContextualWidgetService.java:304)
07-01 12:07:00.953  3452  8486 E AndroidRuntime: 	at com.htc.launcher.htcwidget.HtcContextualWidgetService.onHandleIntent(HtcContextualWidgetService.java:186)
07-01 12:07:00.953  3452  8486 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-01 12:07:00.953  3452  8486 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:07:00.953  3452  8486 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
07-01 12:07:00.953  3452  8486 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:07:00.953  1114  1133 E ActivityManager: App crashed! Process: com.htc.launcher
07-01 12:07:00.953  1114  1133 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
07-01 12:07:00.963  6444  8487 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
07-01 12:07:00.963  1114  1133 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
07-01 12:07:00.963  1114  1133 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 12:07:00.963  1114  1133 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 12:07:00.963  1114  1133 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-01 12:07:00.963  1114  1133 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-01 12:07:00.963  1114  1133 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
07-01 12:07:00.963  1114  1133 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
07-01 12:07:00.963  1114  1133 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
07-01 12:07:00.963  1114  1133 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
07-01 12:07:00.963  6444  8487 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
07-01 12:07:00.963  6444  8487 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 6444
07-01 12:07:00.963  6444  8487 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-01 12:07:00.963  6444  8487 E AndroidRuntime,: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
07-01 12:07:00.963  6444  8487 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
07-01 12:07:00.963  6444  8487 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
07-01 12:07:00.963  6444  8487 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
07-01 12:07:00.963  6444  8487 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:557)
07-01 12:07:00.963  6444  8487 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:461)
07-01 12:07:00.963  6444  8487 E AndroidRuntime: 	at com.google.android.search.core.icingsync.b.d(ApplicationsHelper.java:193)
07-01 12:07:00.963  6444  8487 E AndroidRuntime: 	at com.google.android.search.core.icingsync.ar.g(InternalIcingCorporaProvider.java:548)
07-01 12:07:00.963  6444  8487 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:282)
07-01 12:07:00.963  6444  8487 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:338)
07-01 12:07:00.963  6444  8487 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1398)
07-01 12:07:00.963  6444  8487 E AndroidRuntime: 	at com.google.android.search.core.icingsync.ba.Zh(UpdateIcingCorporaService.java:358)
07-01 12:07:00.963  6444  8487 E AndroidRuntime: 	at com.google.android.search.core.icingsync.bc.Zj(UpdateIcingCorporaService.java:297)
07-01 12:07:00.963  6444  8487 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:270)
07-01 12:07:00.963  6444  8487 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ac(UpdateIcingCorporaService.java:194)
07-01 12:07:00.963  6444  8487 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:182)
07-01 12:07:00.963  6444  8487 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-01 12:07:00.963  6444  8487 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:07:00.963  6444  8487 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
07-01 12:07:00.963  6444  8487 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:07:00.963  1114  1133 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
07-01 12:07:00.963  1114  1133 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
07-01 12:07:00.963  1114  1133 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
07-01 12:07:00.963  1114  1133 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
07-01 12:07:00.963  1114  1133 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
07-01 12:07:00.963  1114  1133 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
07-01 12:07:00.963  1114  1133 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
07-01 12:07:00.963  1114  1133 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 12:07:00.963  1114  1133 W System.err: 	at libcore.io.Posix.open(Native Method)
07-01 12:07:00.963  1114  1133 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 12:07:00.963  1114  1133 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 12:07:00.963  1114  1133 W System.err: 	... 14 more
07-01 ,12:07:00.963  1114  3660 E ActivityManager: App crashed! Process: com.google.android.googlequicksearchbox:search
07-01 12:07:00.963  1114  1133 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
07-01 12:07:00.963  1114  1133 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 12:07:00.963  1114  1133 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 12:07:00.963  1114  1133 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-01 12:07:00.963  1114  1133 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-01 12:07:00.963  1114  1133 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
07-01 12:07:00.963  1114  1133 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
07-01 12:07:00.963  1114  1133 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
07-01 12:07:00.963  1114  1133 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
07-01 12:07:00.963  1114  1133 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
07-01 12:07:00.963  1114  1133 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
07-01 12:07:00.963  1114  1133 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
07-01 12:07:00.963  1114  1133 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
07-01 12:07:00.963  1114  1133 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
07-01 12:07:00.963  1114  1133 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
07-01 12:07:00.963  1114  1133 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
07-01 12:07:00.963  1114  1133 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 12:07:00.963  1114  1133 W System.err: 	at libcore.io.Posix.open(Native Method)
07-01 12:07:00.963  1114  1133 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 12:07:00.963  1114  1133 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 12:07:00.963  1114  1133 W System.err: 	... 14 more
07-01 12:07:00.973  1114  8491 E DropBoxManagerService: Can't write: system_app_crash
07-01 12:07:00.973  1114  8491 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
07-01 12:07:00.973  1114  8491 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 12:07:00.973  1114  8491 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 12:07:00.973  1114  8491 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-01 12:07:00.973  1114  8491 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
07-01 12:07:00.973  1114  8491 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-01 12:07:00.973  1114  8491 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
07-01 12:07:00.973  1114  8491 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 12:07:00.973  1114  8491 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-01 12:07:00.973  1114  8491 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 12:07:00.973  1114  8491 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 12:07:00.973  1114  8491 E DropBoxManagerService: 	... 5 more
07-01 12:07:00.983  1114  1133 W ActivityManager:   Force finishing activity 1 com.htc.launcher/.Launcher
07-01 12:07:00.983  1114  1133 D PMS     : acquireWL(36076de3): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 1114 1000 null
07-01 12:07:00.983  1114  8493 E ErrorReport: HtcErrorReportManager.Error in dumping error information
07-01 12:07:00.983  1114  8493 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_HOME_RESTART@1467367620998.dbox_tmp: open failed: EROFS (Read-only file system)
07-01 12:07:00.983  1114  8493 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 12:07:00.983  1114  8493 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 12:07:00.983  1114  8493 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-01 12:07:00.983  1114  8493 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
07-01 12:07:00.983  1114  8493 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
07-01 12:07:00.983  1114  8493 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 12:07:00.983  1114  8493 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
07-01 12:07:00.983  1114  8493 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 12:07:00.983  1114  8493 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 12:07:00.983  1114  8493 E ErrorReport: 	... 4 more
07-01 12:07:00.993  8432  8458 E SharedPreferencesImpl: Couldn't rename file /data/data/com.android.vending/shared_prefs/finsky.xml to backup file /data/data/com.android.vending/shared_prefs/finsky.xml.bak
07-01 12:07:00.993  1114  3534 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
07-01 12:07:00.993  1114  3534 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 12:07:00.993  1114  3534 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 12:07:00.993  1114  3534 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-01 12:07:00.993  1114  3534 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-01 12:07:00.993  1114  3534 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
07-01 12:07:00.993  1114  3534 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
07-01 12:07:00.993  1114  3534 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
07-01 12:07:00.993  1114  3534 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
07-01 12:07:00.993  1114  3534 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
07-01 12:07:00.993  1114  3534 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
07-01 12:07:00.993  1114  3534 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:07:00.993  1114  3534 W System.err: 	at android.os.Looper.loop(Looper.java:155)
07-01 12:07:00.993  1114  3534 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:07:00.993  1114  3534 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
,07-01 12:07:01.003  1114  3534 W System.err: 	at libcore.io.Posix.open(Native Method)
07-01 12:07:01.003  1114  3534 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 12:07:01.003  1114  3534 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 12:07:01.003  1114  3534 W System.err: 	... 12 more
07-01 12:07:01.013  3452  3452 I FeedHostManager: [onPause]
07-01 12:07:01.013  3452  3452 I FeedProviderManager: onPause
07-01 12:07:01.013  3452  3452 I FeedHostManager: [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@55240fe
07-01 12:07:01.013  3452  4899 I SocialFeedProvider: +onPause
07-01 12:07:01.013  3452  4899 I SocialFeedProvider: -onPause
07-01 12:07:01.013  3452  3452 I ContextualWidget: onPause
07-01 12:07:01.013  3452  3452 I ContextualWidget: notifyWidgetDeactive
07-01 12:07:01.033  3452  3896 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-01 12:07:01.033  1114  3966 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.htc.launcher/.Launcher} from uid 0 pid 0 on display 0
07-01 12:07:01.043  1114  3966 V WindowManager: addAppToken: AppWindowToken{1708ea36 token=Token{37019fd1 ActivityRecord{39d98ef8 u0 com.htc.launcher/.Launcher t105}}} to stack=0 task=105 at 0
,07-01 12:07:01.043  3452  4731 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1467367621056,
,07-01 12:07:01.053  1114  3534 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
,07-01 12:07:01.053  3452  3452 D HtcThemeUtils: Unregister com.htc.launcher.util.HtcWrapConfigurationActivity$2@f5a9daa for type 0
07-01 12:07:01.053  3452  3452 D HtcThemeUtils: Unregister com.htc.launcher.util.HtcWrapConfigurationActivity$2@f5a9daa for type 1
07-01 12:07:01.053  3452  3452 D HtcThemeUtils: Unregister com.htc.launcher.util.HtcWrapConfigurationActivity$2@f5a9daa for type 3
07-01 12:07:01.053  3452  3452 D HtcThemeUtils: Unregister com.htc.launcher.util.HtcWrapConfigurationActivity$2@f5a9daa for type 2
,07-01 12:07:01.063  3452  3452 I OrientationManager: [release]
07-01 12:07:01.063  3452  3452 I PagedView: IndicatorPagedView.nCapability with type count = 1 and capability = 20,
,07-01 12:07:01.063  3452  3452 I ContextualWidget: onDestroy
07-01 12:07:01.063  3452  4034 I ContextualWidget: handleMessage, what=1030 mode=GettingOut maxcount=8
07-01 12:07:01.063  3452  4034 I ContextualWidget: release
,07-01 12:07:01.073  3452  4269 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.,
07-01 12:07:01.073  3452  3452 I ContextualWidget: new instance com.htc.launcher.htcwidget.HtcContextualWidgetController@fc47ad5
07-01 12:07:01.073  3452  3452 I ContextualWidget: unlockModeChange,
,07-01 12:07:01.083  3452  3452 I ContextualWidget: notifyWidgetDeactive,
,07-01 12:07:01.083  1114  3911 I ActivityManager: Delaying start of: ServiceRecord{18af680d u0 com.htc.launcher/com.htc.BiLogClient.BiLogUploadService},
,07-01 12:07:01.103  3452  4365 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467367621112,
,07-01 12:07:01.113  3452  4365 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml.bak
,07-01 12:07:01.123  3452  3452 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.util.ConnectivityHelper$ConnectivityChangeReceiver@deca375 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 12:07:01.123  3452  3452 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.util.ConnectivityHelper$ConnectivityChangeReceiver@deca375 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 12:07:01.123  3452  3452 E ActivityThread: ,	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:980)
07-01 12:07:01.123  3452  3452 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:742)
07-01 12:07:01.123  3452  3452 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1781)
07-01 12:07:01.123  3452  3452 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1761)
07-01 12:07:01.123  3452  3452 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
07-01 12:07:01.123  3452  3452 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:489)
07-01 12:07:01.123  3452  3452 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:209)
07-01 12:07:01.123  3452  3452 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.registerReceivers(FeedHostManager.java:826)
07-01 12:07:01.123  3452  3452 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.onCreate(FeedHostManager.java:857)
07-01 12:07:01.123  3452  3452 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.onCreate(FeedHostManagerProxy.java:175)
07-01 12:07:01.123  3452  3452 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:134)
07-01 12:07:01.123  3452  3452 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1360)
07-01 12:07:01.123  3452  3452 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6751)
07-01 12:07:01.123  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1529)
07-01 12:07:01.123  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.access$1200(LauncherModel.java:1262)
07-01 12:07:01.123  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1315)
07-01 12:07:01.123  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:663)
07-01 12:07:01.123  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:121)
07-01 12:07:01.123  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:982)
07-01 12:07:01.123  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:1009)
07-01 12:07:01.123  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1477)
07-01 12:07:01.123  3452  3452 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
07-01 12:07:01.123  3452  3452 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
07-01 12:07:01.123  3452  3452 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:07:01.123  3452  3452 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
07-01 12:07:01.123  3452  3452 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:07:01.133  3452  3452 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.feed.local.calendar.CalendarFeedAdapter$TimeZoneChangeReceiver@152e53e5 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 12:07:01.133  3452  3452 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.feed.local.calendar.CalendarFeedAdapter$TimeZoneChangeReceiver@152e53e5 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:980)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:742)
07-01 12:07:01.133  3452  3452 ,E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1781)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1761)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:489)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:209)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderContext$WrappedContext.registerReceiver(FeedProviderContext.java:325)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at com.htc.feed.local.calendar.CalendarFeedAdapter.<init>(CalendarFeedAdapter.java:98)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at com.htc.feed.local.calendar.CalendarFeedProvider.onCreate(CalendarFeedProvider.java:19)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at com.htc.libfeedframework.FeedProvider.performCreate(FeedProvider.java:84)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at com.htc.libfeedframework.FeedProvider.init(FeedProvider.java:64)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderContext.loadFeedProvider(FeedProviderContext.java:154)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager.registerProvider(FeedProviderManager.java:602)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager$16.call(FeedProviderManager.java:1223)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager$16.call(FeedProviderManager.java:1194)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at java.lang.Thread.run(Thread.java:818)
07-01 12:07:01.133  3452  3452 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$CustomHighlightReceiver@1647405f that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 12:07:01.133  3452  3452 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$CustomHighlightReceiver@1647405f that was originally registered here. Are you missing a call to unregisterReceiver()?,
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:980)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:742)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1781)
,07-01 12:07:01.133  3452  3452 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1761)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:496)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:202)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.registerReceivers(FeedHostManager.java:817)
,07-01 12:07:01.133  3452  3452 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.onCreate(FeedHostManager.java:857)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.onCreate(FeedHostManagerProxy.java:175)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:134)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1360)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6751)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1529)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.access$1200(LauncherModel.java:1262)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1315)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:663)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:121)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:982)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:1009)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1477)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:07:01.133  3452  3452 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.feed.local.getstarted.GetStartedFeedProvider$1@17754961 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 12:07:01.133  3452  3452 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.feed.local.getstarted.GetStartedFeedProvider$1@17754961 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:980)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:742)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1781)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1761)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:496)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:202)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderContext$WrappedContext.registerReceiver(FeedProviderContext.java:338)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at com.htc.feed.local.getstarted.GetStartedFeedProvider.onCreate(GetStartedFeedProvider.java:75)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at com.htc.libfeedframework.FeedProvider.performCreate(FeedProvider.java:84)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at com.htc.libfeedfram,ework.FeedProvider.init(FeedProvider.java:64)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderContext.loadFeedProvider(FeedProviderContext.java:154)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager.registerProvider(FeedProviderManager.java:602)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager$16.call(FeedProviderManager.java:1223)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager$16.call(FeedProviderManager.java:1194)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-01 12:07:01.133  3452  3452 E ActivityThread: 	at java.lang.Thread.run(Thread.java:818)
07-01 12:07:01.143  3452  3452 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$SummonSnapToReceiver@177ea598 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 12:07:01.143  3452  3452 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$SummonSnapToReceiver@177ea598 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:980)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:742)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1781)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1761)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:496)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:202)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.registerReceivers(FeedHostManager.java:847)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.onCreate(FeedHostManager.java:857)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.onCreate(FeedHostManagerProxy.java:175)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:134)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1360)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launche,r.Launcher.bindFeedCustomization(Launcher.java:6751)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1529)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.access$1200(LauncherModel.java:1262)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1315)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:663)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:121)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:982)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:1009)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1477)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:07:01.143  3452  3452 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$FilterSettingReceiver@1a6d8aac that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 12:07:01.143  3452  3452 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$FilterSettingReceiver@1a6d8aac that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:980)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:742)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1781)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1761)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:496)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:202)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.registerReceivers(FeedHostManager.java:822)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.onCreate(FeedHostManager.java:857)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.onCreate(FeedHostManagerProxy.java:175)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:134)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1360)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6751),
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1529)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.access$1200(LauncherModel.java:1262)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1315)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:663)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:121)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:982)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:1009)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1477)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:07:01.143  3452  3452 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.util.FeedSevenDaysNotification$HTCAccountAddedReceiver@21e68680 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 12:07:01.143  3452  3452 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.util.FeedSevenDaysNotification$HTCAccountAddedReceiver@21e68680 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:980)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:742)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1781)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1761)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:496)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:202)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.feeds.util.FeedSevenDaysNotification.<init>(FeedSevenDaysNotification.java:95)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.<init>(FeedHostManager.java:535)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:118)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1360)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6751)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1529)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.access$1200(LauncherModel.java:1262)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1315)
07-01 12:07:01.143  3452  3452 E, ActivityThread: 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:663)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:121)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:982)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:1009)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1477)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:07:01.143  3452  3452 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.feed.socialfeedprovider.SocialFeedProvider$7@27e6ff4f that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 12:07:01.143  3452  3452 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.feed.socialfeedprovider.SocialFeedProvider$7@27e6ff4f that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:980)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:742)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1781)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1761)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:496)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:202)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderContext$WrappedContext.registerReceiver(FeedProviderContext.java:338)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.feed.socialfeedprovider.SocialFeedProvider.onCreate(SocialFeedProvider.java:674)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.libfeedframework.FeedProvider.performCreate(FeedProvider.java:84)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.libfeedframework.FeedProvider.init(FeedProvider.java:64)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderContext.loadFeedProvider(FeedProviderContext.java:154)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager.registerProvider(FeedProviderManager.java:602)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager$16.call(FeedProviderManager.java:1223)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager$16.call(FeedProviderManager.java:1194)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-01 12:07:01.143  3452  3452 E ActivityThread: 	at java.lang.Thread.run(Thread.java:818)
07-01 12:07:01.1,53  3452  3452 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$NightModeSyncReceiver@290d6f0a that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 12:07:01.153  3452  3452 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$NightModeSyncReceiver@290d6f0a that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:980)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:742)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1781)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1761)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:496)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:202)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.registerReceivers(FeedHostManager.java:839)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.onCreate(FeedHostManager.java:857)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.onCreate(FeedHostManagerProxy.java:175)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:134)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1360)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6751)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1529)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.access$1200(LauncherModel.java:1262)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1315)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:663)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:121)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:982)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:1009)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1477)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:07:01.153  3452  3452 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.libfeedframework.FeedProviderManager$RestoreCompleteReceiver@2c9e7681 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 12:07:01.153  3452  3452 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.libfeedframework.FeedProviderManager$RestoreCompleteReceiver@2c9e7681 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:980)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:742)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1781)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1761)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:496)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:202)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager.<init>(FeedProviderManager.java:152)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.<init>(FeedHostManager.java:503)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:118)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1360)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6751)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1529)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.access$1200(LauncherModel.java:1262)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1315)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:663)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:121)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:982)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:1009)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1477)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:07:01.153  3452  3452 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.libfeedframework.FeedPushReceiver@3059f326 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 12:07:01.153  3452  3452 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.libfeedframework.FeedPushReceiver@3059f326 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:980)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:742)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1781)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1761)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:496)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:202)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager.<init>(FeedProviderManager.java:153)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.<init>(FeedHostManager.java:503)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:118)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1360)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6751)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1529)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.access$1200(LauncherModel.java:1262)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1315)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:663)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:121)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:982)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:1009)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1477)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:07:01.153  3452  3452 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.util.FeedSevenDaysNotification$GoogleBackupReceiver@332274b9 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 12:07:01.153  3452  3452 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.util.FeedSevenDaysNotification$GoogleBackupReceiver@332274b9 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:980)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:742)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1781)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1761)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:489)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:209)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.feeds.util.FeedSevenDaysNotification.<init>(FeedSevenDaysNotification.java:98)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.<init>(FeedHostManager.java:535)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:118)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1360)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6751)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1529)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.access$1200(LauncherModel.java:1262)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1315)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:663)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:121)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:982)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:1009)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1477)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
07-01 12:07:01.153  3452  3452 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:07:01.173  3452  3452 I OrientationManager: [init] currentOrienation: 1
07-01 12:07:01.163  3452  3452 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.feed.socialfeedprovider.SocialFeedProvider$6@390ee5ae that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 12:07:01.163  3452  3452 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.feed.socialfeedprovider.SocialFeedProvider$6@390ee5ae that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 12:07:01.163  3452  3452 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:980)
07-01 12:07:01.163  3452  3452 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:742)
07-01 12:07:01.163  3452  3452 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1781)
07-01 12:07:01.163  3452  3452 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1761)
07-01 12:07:01.163  3452  3452 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:496)
07-01 12:07:01.163  3452  3452 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:202)
07-01 12:07:01.163  3452  3452 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderContext$WrappedContext.registerReceiver(FeedProviderContext.java:338)
07-01 12:07:01.163  3452  3452 E ActivityThread: 	at com.htc.feed.socialfeedprovider.SocialFeedProvider.onCreate(SocialFeedProvider.java:617)
07-01 12:07:01.163  3452  3452 E ActivityThread: 	at com.htc.libfeedframework.FeedProvider.performCreate(FeedProvider.java:84)
07-01 12:07:01.163  3452  3452 E ActivityThread: 	at com.htc.libfeedframework.FeedProvider.init(FeedProvider.java:64)
07-01 12:07:01.163  3452  3452 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderContext.loadFeedProvider(FeedProviderContext.java:154)
07-01 12:07:01.163  3452  3452 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager.registerProvider(FeedProviderManager.java:602)
07-01 12:07:01.163  3452  3452 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager$16.call(FeedProviderManager.java:1223)
07-01 12:07:01.163  3452  3452 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager$16.call(FeedProviderManager.java:1194)
07-01 12:07:01.163  3452  3452 E ActivityThread: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-01 12:07:01.163  3452  3452 E ActivityThread: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-01 12:07:01.163  3452  3452 E ActivityThread: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-01 12:07:01.163  3452  3452 E ActivityThread: 	at java.lang.Thread.run(Thread.java:818)
07-01 12:07:01.163  3452  3452 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$LaunchCoobeReceiver@3e49837b that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 12:07:01.163  3452  3452 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$LaunchCoobeReceiver@3e49837b that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 12:07:01.163  3452  3452 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:980)
07-01 12:07:01.163  3452  3452 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:742)
07-01 12:07:01.163  3452  3452 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1781)
07-01 12:07:01.163  3452  3452 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1761)
07-01 12:07:01.163  3452  3452 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:496)
07-01 12:07:01.163  3452  3452 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:202)
07-01 12:07:01.163  3452  3452 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.registerReceivers(FeedHostManager.java:843)
07-01 12:07:01.163  3452  3452 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.onCreate(FeedHostManager.java:857)
07-01 12:07:01.163  3452  3452 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.onCreate(FeedHostManagerProxy.java:175)
07-01 12:07:01.163  3452  3452 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:134)
07-01 12:07:01.163  3452  3452 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1360)
07-01 12:07:01.163  3452  3452 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6751)
07-01 12:07:01.163  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1529)
07-01 12:07:01.163  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.access$1200(LauncherModel.java:1262)
07-01 12:07:01.163  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1315)
07-01 12:07:01.163  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:663)
07-01 12:07:01.163  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:121)
07-01 12:07:01.163  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:982)
07-01 12:07:01.163  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:1009)
07-01 12:07:01.163  3452  3452 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1477)
07-01 12:07:01.163  3452  3452 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
07-01 12:07:01.163  3452  3452 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
07-01 12:07:01.163  3452  3452 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:07:01.163  3452  3452 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
07-01 12:07:01.163  3452  3452 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:07:01.183  3452  3452 E ResourceType: Style contains key with bad entry: 0x01010504
07-01 12:07:01.183  3452  3452 W HtcWrapConfigurationActivity: no reset icon com.htc.launcher.Launcher@2e896542, false
07-01 12:07:01.183  3452  3452 D HtcThemeUtils: Register com.htc.launcher.util.HtcWrapConfigurationActivity$2@124c938e for type 0
07-01 12:07:01.183  3452  3452 D HtcThemeUtils: Register com.htc.launcher.util.HtcWrapConfigurationActivity$2@124c938e for type 1
07-01 12:07:01.183  3452  3452 D HtcThemeUtils: Register com.htc.launcher.util.HtcWrapConfigurationActivity$2@124c938e for type 3
07-01 12:07:01.183  3452  3452 D HtcThemeUtils: Register com.htc.launcher.util.HtcWrapConfigurationActivity$2@124c938e for type 2
07-01 12:07:01.193  1114  1134 W AppWidgetServiceImpl: startListening(),set useForground = true
07-01 12:07:01.193  1114  1134 D AppWidgetServiceImpl: sendEnableIntentLocked for ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherTransClock4x1}
07-01 12:07:01.193  1114  1134 W AppWidgetServiceImpl: use FLAG_RECEIVER_FOREGROUND to send android.appwidget.action.APPWIDGET_ENABLED
07-01 12:07:01.193  3452  3452 I ContextualWidget: onCreate
07-01 12:07:01.193  1114  1134 D AppWidgetServiceImpl: sendUpdateIntentLocked for ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherTransClock4x1}
07-01 12:07:01.193  3452  8494 I ContextualWidget: handleMessage, what=1029 mode=GettingOut maxcount=8
07-01 12:07:01.193  1114  1134 W AppWidgetServiceImpl: use FLAG_RECEIVER_FOREGROUND to send android.appwidget.action.APPWIDGET_UPDATE
07-01 12:07:01.193  3452  8494 I ContextualWidget: initialize()
07-01 12:07:01.193  1114  1134 D AppWidgetServiceImpl: sendEnableIntentLocked for ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider}
07-01 12:07:01.193  1114  1134 W AppWidgetServiceImpl: use FLAG_RECEIVER_FOREGROUND to send android.appwidget.action.APPWIDGET_ENABLED
07-01 12:07:01.193  1114  1134 D AppWidgetServiceImpl: sendUpdateIntentLocked for ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider}
07-01 12:07:01.193  1114  1134 W AppWidgetServiceImpl: use FLAG_RECEIVER_FOREGROUND to send android.appwidget.action.APPWIDGET_UPDATE
07-01 12:07:01.193  1114  1134 D AppWidgetServiceImpl: sendEnableIntentLocked for ComponentInfo{pl.k2.droidoaudioteka/pl.k2.droidoaudioteka.ui.widgets.BigWidgetProvider}
07-01 12:07:01.193  1114  1134 W AppWidgetServiceImpl: use FLAG_RECEIVER_FOREGROUND to send android.appwidget.action.APPWIDGET_ENABLED
07-01 12:07:01.193  1114  1134 D AppWidgetServiceImpl: sendUpdateIntentLocked for ComponentInfo{pl.k2.droidoaudioteka/pl.k2.droidoaudioteka.ui.widgets.BigWidgetProvider}
07-01 12:07:01.193  1114  1134 W AppWidgetServiceImpl: use FLAG_RECEIVER_FOREGROUND to send android.appwidget.action.APPWIDGET_UPDATE
07-01 12:07:01.203  3452  3452 W ResourceType: Invalid package identifier when getting bag for resource number 0x00000014
,07-01 12:07:01.213  3452  3452 D AbsListView:  setHtcScrollEnabled item height = 190
07-01 12:07:01.223  3452  3452 I FeedScrollGridView: velocity 0.850000
07-01 12:07:01.223  1114  1149 I ActivityManager: Start proc 8495:com.htc.widget.hmsproc2/u0a36 for broadcast com.htc.widget.weatherclock/.WeatherTransClock4x1
07-01 12:07:01.223  3321  3798 D [LocationSvProvider]: query uri = content://com.htc.locationservicessettingprovider.provider/table_address
07-01 12:07:01.233  3321  3798 D [LocationSvProvider]: No data in AddressInfo database, do not sync to LocationInfo
07-01 12:07:01.233  3321  3798 D [LocationSvProvider]: No data in AddressInfo database, do not sync to LocationInfo
07-01 12:07:01.243  3321  3808 D [LocationSvProvider]: query uri = content://com.htc.locationservicessettingprovider.provider/table_address
07-01 12:07:01.243  3321  3808 D [LocationSvProvider]: No data in AddressInfo database, do not sync to LocationInfo
07-01 12:07:01.243  3321  3808 D [LocationSvProvider]: No data in AddressInfo database, do not sync to LocationInfo
07-01 12:07:01.243  8495  8495 W HTCLOG  : use specified tag [FDManager], func [0].
07-01 12:07:01.243  8495  8495 W HTCLOG  : mask=0x18
07-01 12:07:01.243  3452  8494 I ContextualWidget: loadLocations size = 0, home: 0, work: 0
07-01 12:07:01.243  3321  3798 D [LocationSvProvider]: query uri = content://com.htc.locationservicessettingprovider.provider/table_wifi
07-01 12:07:01.253  3321  3798 D [LocationSvProvider]: No data in AddressInfo database, do not sync to LocationInfo
07-01 12:07:01.253  3321  3798 D [LocationSvProvider]: No data in AddressInfo database, do not sync to LocationInfo
,07-01 12:07:01.263  3321  3798 D [LocationSvProvider]: query uri = content://com.htc.locationservicessettingprovider.provider/table_wifi
07-01 12:07:01.263  3321  3798 D [LocationSvProvider]: No data in AddressInfo database, do not sync to LocationInfo
07-01 12:07:01.263  3321  3798 D [LocationSvProvider]: No data in AddressInfo database, do not sync to LocationInfo
07-01 12:07:01.263  3452  8494 I ContextualWidget: loadwifis , home: 0, work: 0
,07-01 12:07:01.273  3452  3452 I Prism.AllAppsOptionsMa_: getAllAppsAbility() false
07-01 12:07:01.273  3452  3452 I Prism.AllAppsOptionsMa_: removeAllAppsAbility()
07-01 12:07:01.273  3452  3452 I Prism.AllAppsOptionsMa_: getAllAppsAbility() false
07-01 12:07:01.273  3452  3452 I Prism.AllAppsOptionsMa_: removeAllAppsAbility()
07-01 12:07:01.273  3452  4365 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1467367621284
07-01 12:07:01.273  3452  8494 I ContextualWidget: updateUserConsent() - location: false, data: false
07-01 12:07:01.283  3452  3452 D HtcFooter: layerDrawableIndex = 0
07-01 12:07:01.283  6718  8431 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/games_3a3529a.db'.
07-01 12:07:01.283  6718  8431 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 12:07:01.283  6718  8431 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 12:07:01.283  6718  8431 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 12:07:01.283  6718  8431 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 12:07:01.283  6718  8431 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-01 12:07:01.283  6718  8431 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-01 12:07:01.283  6718  8431 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-01 12:07:01.283  6718  8431 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-01 12:07:01.283  6718  8431 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-01 12:07:01.283  6718  8431 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-01 12:07:01.283  6718  8431 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-01 12:07:01.283  6718  8431 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-01 12:07:01.283  6718  8431 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-01 12:07:01.283  6718  8431 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 12:07:01.283  6718  8431 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-01 12:07:01.283  6718  8431 E SQLiteDatabase: 	at com.google.android.gms.chimera.BaseGmsContentProvider.query(BaseGmsContentProvider.java:191)
07-01 12:07:01.283  6718  8431 E SQLiteDatabase: 	at com.google.android.chimera.container.ContentProviderProxy.query(:com.google.android.gms:408)
07-01 12:07:01.283  6718  8431 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:976)
07-01 12:07:01.283  6718  8431 E SQLiteDatabase: 	at com.google.android.chimera.container.ContentProviderProxy.superQuery(:com.google.android.gms:540)
07-01 12:07:01.283  6718  8431 E SQLiteDatabase: 	at com.google.android.chimera.ContentProvider.query(:com.google.android.gms:172)
07-01 12:07:01.283  6718  8431 E SQLiteDatabase: 	at com.google.android.chimera.container.ContentProviderProxy.query(:com.google.android.gms:420)
07-01 12:07:01.283  6718  8431 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
07-01 12:07:01.283  6718  8431 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:499)
07-01 12:07:01.283  6718  8431 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:443)
07-01 12:07:01.283  6718  8431 E SQLiteDatabase: 	at com.google.android.gms.games.broker.AccountAgent.getAccount(AccountAgent.java:86)
07-01 12:07:01.283  6718  8431 E SQLiteDatabase: 	at com.google.android.gms.games.broker.DataBroker.getClientContextsForAllDatastores(DataBroker.java:3782)
07-01 12:07:01.283  6718  8431 E SQLiteDatabase: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:30)
07-01 12:07:01.283  6718  8431 E SQLiteDatabase: 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
07-01 12:07:01.283  6718  8431 E SQLiteDatabase: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:177)
07-01 12:07:01.283  6718  8431 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-01 12:07:01.283  6718  8431 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-01 12:07:01.283  6718  8431 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-01 12:07:01.283  6718  8431 E SQLiteOpenHelper: Couldn't open games_3a3529a.db for writing (will try read-only):
07-01 12:07:01.283  6718  8431 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 12:07:01.283  6718  8431 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 12:07:01.283  6718  8431 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 12:07:01.283  6718  8431 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 12:07:01.283  6718  8431 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-01 12:07:01.283  6718  8431 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-01 12:07:01.283  6718  8431 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-01 12:07:01.283  6718  8431 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-01 12:07:01.283  6718  8431 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-01 12:07:01.283  6718  8431 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-01 12:07:01.283  6718  8431 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-01 12:07:01.283  6718  8431 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-01 12:07:01.283  6718  8431 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-01 12:07:01.283  6718  8431 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 12:07:01.283  6718  8431 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-01 12:07:01.283  6718  8431 E SQLiteOpenHelper: 	at com.google.android.gms.chimera.BaseGmsContentProvider.query(BaseGmsContentProvider.java:191)
07-01 12:07:01.283  6718  8431 E SQLiteOpenHelper: 	at com.google.android.chimera.container.ContentProviderProxy.query(:com.google.android.gms:408)
07-01 12:07:01.283  6718  8431 E SQLiteOpenHelper: 	at android.content.ContentProvider.query(ContentProvider.java:976)
07-01 12:07:01.283  6718  8431 E SQLiteOpenHelper: 	at com.google.android.chimera.container.ContentProviderProxy.superQuery(:com.google.android.gms:540)
07-01 12:07:01.283  6718  8431 E SQLiteOpenHelper: 	at com.google.android.chimera.ContentProvider.query(:com.google.android.gms:172)
07-01 12:07:01.283  6718  8431 E SQLiteOpenHelper: 	at com.google.android.chimera.container.ContentProviderProxy.query(:com.google.android.gms:420)
07-01 12:07:01.283  6718  8431 E SQLiteOpenHelper: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
07-01 12:07:01.283  6718  8431 E SQLiteOpenHelper: 	at android.content.ContentResolver.query(ContentResolver.java:499)
07-01 12:07:01.283  6718  8431 E SQLiteOpenHelper: 	at android.content.ContentResolver.query(ContentResolver.java:443)
07-01 12:07:01.283  6718  8431 E SQLiteOpenHelper: 	at com.google.android.gms.games.broker.AccountAgent.getAccount(AccountAgent.java:86)
07-01 12:07:01.283  6718  8431 E SQLiteOpenHelper: 	at com.google.android.gms.games.broker.DataBroker.getClientContextsForAllDatastores(DataBroker.java:3782)
07-01 12:07:01.283  6718  8431 E SQLiteOpenHelper: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:30)
07-01 12:07:01.283  6718  8431 E SQLiteOpenHelper: 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
07-01 12:07:01.283  6718  8431 E SQLiteOpenHelper: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:177)
07-01 12:07:01.283  6718  8431 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-01 12:07:01.283  6718  8431 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-01 12:07:01.283  6718  8431 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
07-01 12:07:01.293  3452  4374 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467367621303
07-01 12:07:01.293  3452  3452 W asset   : Asset path /data/data/com.htc.launcher/files/.htc_theme/WeatherClock.apk is neither a directory nor file (type=1).
07-01 12:07:01.293  6718  8431 W SQLiteOpenHelper: Opened games_3a3529a.db in read-only mode
07-01 12:07:01.293  3452  3452 D HtcThemeUtils: AssetMaanger addAssetPath WeatherClock fail!
07-01 12:07:01.293  3452  4374 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml.bak
,07-01 12:07:01.323  3452  3452 I FeedActionBar: updateLastUpdatedTime(in String) LAST UPDATED 1:00
,07-01 12:07:01.323  6718  8515 I GCore-Chimera-Crash: Cg0KB3ZJbmZyYTQQor84Gl8KHWNvbS5nb29nbGUuYW5kcm9pZC
07-01 12:07:01.323  6718  8515 I GCore-Chimera-Crash: 5wbGF5LmdhbWVzEhQzLjcuMjMgKDI4Njc2MzctMDQ4KRjgq-AR
07-01 12:07:01.323  6718  8515 I GCore-Chimera-Crash: IiMKHGNvbS5nb29nbGUuYW5kcm9pZC5nbXMuZ2FtZXMQsKvgEQ
07-01 12:07:01.323  6718  8515 I GCore-Chimera-Crash: ==
07-01 12:07:01.323  6718  8515 I GCore-Chimera-Crash: GCore-Chimera-Crash
07-01 12:07:01.323  6718  8515 E AndroidRuntime: FATAL EXCEPTION: GamesProviderWorker
07-01 12:07:01.323  6718  8515 E AndroidRuntime: Process: com.google.android.gms, PID: 6718
07-01 12:07:01.323  6718  8515 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 12:07:01.323  6718  8515 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 12:07:01.323  6718  8515 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 12:07:01.323  6718  8515 E AndroidRuntime: ,	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 12:07:01.323  6718  8515 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-01 12:07:01.323  6718  8515 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:311)
07-01 12:07:01.323  6718  8515 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:843)
07-01 12:07:01.323  6718  8515 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
07-01 12:07:01.323  6718  8515 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 12:07:01.323  6718  8515 E AndroidRuntime: 	at com.google.android.gms.games.provider.ImageStore.initialize(ImageStore.java:149)
07-01 12:07:01.323  6718  8515 E AndroidRuntime: 	at com.google.android.gms.games.provider.ImageStore.<init>(ImageStore.java:78)
07-01 12:07:01.323  6718  8515 E AndroidRuntime: 	at com.google.android.gms.games.provider.GamesDataStore.initialize(GamesDataStore.java:111)
07-01 12:07:01.323  6718  8515 E AndroidRuntime: 	at com.google.android.gms.games.provider.PlayGamesContentProvider.performBackgroundTask(PlayGamesContentProvider.java:1730)
07-01 12:07:01.323  6718  8515 E AndroidRuntime: 	at com.google.android.gms.games.provider.PlayGamesContentProvider$1.handleMessage(PlayGamesContentProvider.java:1651)
07-01 12:07:01.323  6718  8515 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:07:01.323  6718  8515 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
07-01 12:07:01.323  6718  8515 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:07:01.323  1114  3937 E ActivityManager: App crashed! Process: com.google.android.gms
07-01 12:07:01.333   531  8523 E MM_OSAL : FileSource::FileSource
07-01 12:07:01.333   531  8523 E MM_OSAL : FileSource::FileSource m_bEveryThingOK 1
07-01 12:07:01.333   531  8523 E MM_OSAL : MM_File_Create failed .Efs Error No -1 , File Name /data/mmosal_logmask.cfg , Mode 0
07-01 12:07:01.333   531  8523 E MM_OSAL : Open or read fail on /data/mmosal_logmask.cfg. Possible permission denied issue. Looking for /data/misc/media/mmosal_logmask.cfg
07-01 12:07:01.333   531  8523 E MM_OSAL : MM_File_Create failed .Efs Error No -1 , File Name /data/misc/media/mmosal_logmask.cfg , Mode 0
07-01 12:07:01.343  1114  8524 E DropBoxManagerService: Can't write: system_app_crash
07-01 12:07:01.343  1114  8524 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
07-01 12:07:01.343  1114  8524 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 12:07:01.343  1114  8524 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 12:07:01.343  1114  8524 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-01 12:07:01.343  1114  8524 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
07-01 12:07:01.343  1114  8524 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-01 12:07:01.343  1114  8524 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
07-01 12:07:01.343  1114  8524 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 12:07:01.343  1114  8524 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-01 12:07:01.343  1114  8524 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 12:07:01.343  1114  8524 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 12:07:01.343  1114  8524 E DropBoxManagerService: 	... 5 more
07-01 12:07:01.343   531  8523 W, QCOMExtractor: Sample Bit is, 16, set to kKeyBitsPerSample
07-01 12:07:01.343   531  8523 W MediaExtractor: Sample Bit is, 16, support QCOMExtractor
07-01 12:07:01.343   531  8522 W Utils   : Qcom parser, bits per sample supported is 16 or 24
,07-01 12:07:01.343   531  8523 E MMParserExtractor: FileSource::FILE_SOURCE_DATA_END 
07-01 12:07:01.343   531  8523 E FLACDecoder: qti_flac: Parser returned -1011
07-01 12:07:01.343   531  8522 W Utils   : Qcom parser, bits per sample supported is 16 or 24
07-01 12:07:01.343   531  8522 W Utils   : Qcom parser, bits per sample supported is 16 or 24
07-01 12:07:01.353  3452  3452 I Prism.AllAppsOptionsMa_: getAllAppsAbility() false
07-01 12:07:01.353  3452  3452 I Prism.AllAppsOptionsMa_: removeAllAppsAbility()
,07-01 12:07:01.363  3452  3896 W asset   : Copying FileAsset 0xac56ab28 (zip:/data/app/com.gameloft.android.gdc-1/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,07-01 12:07:01.363   531  8523 E MMParserExtractor: FileSource::FILE_SOURCE_DATA_END 
07-01 12:07:01.363   531  8523 E FLACDecoder: qti_flac: Parser returned -1011
,07-01 12:07:01.363  6718  6837 I Icing   : Indexing E7E0925662843324D4EEB09F3BC5C5BCEC2A972A from com.google.android.gms
,07-01 12:07:01.373  3452  4158 I BlinkFeedStateMonitor: checkState, feed:true, subsribed:true, loc:false
07-01 12:07:01.373  3452  3452 I Prism.AllAppsOptionsMa_: getAllAppsAbility() false
07-01 12:07:01.373  3452  3452 I Prism.AllAppsOptionsMa_: removeAllAppsAbility()
,07-01 12:07:01.373  3452  3452 I PagedView: IndicatorPagedView.nCapability with type count = 1 and capability = 20
,07-01 12:07:01.393  6718  6837 I Icing   : Indexing done E7E0925662843324D4EEB09F3BC5C5BCEC2A972A
,07-01 12:07:01.403  8495  8532 D WeatherUtility: Weather sync is On
,07-01 12:07:01.403  6718  6837 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
07-01 12:07:01.403  6718  6837 E Icing   : Writing status failed
,07-01 12:07:01.403   531  8535 E MM_OSAL : FileSource::FileSource
07-01 12:07:01.403   531  8535 E MM_OSAL : FileSource::FileSource m_bEveryThingOK 1
07-01 12:07:01.403  1114  3253 D PMS     : releaseWL(2be7769b): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10020 com.google.android.gms}
07-01 12:07:01.403   531  8535 E MM_OSAL : MM_File_Create failed .Efs Error No -1 , File Name /data/mmosal_logmask.cfg , Mode 0
07-01 12:07:01.403   531  8535 E MM_OSAL : Open or read fail on /data/mmosal_logmask.cfg. Possible permission denied issue. Looking for /data/misc/media/mmosal_logmask.cfg
07-01 12:07:01.403   531  8535 E MM_OSAL : MM_File_Create failed .Efs Error No -1 , File Name /data/misc/media/mmosal_logmask.cfg , Mode 0
07-01 12:07:01.403  3452  4374 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1467367621417
07-01 12:07:01.403   531  8535 W QCOMExtractor: Sample Bit is, 16, set to kKeyBitsPerSample
07-01 12:07:01.413   531  8535 W MediaExtractor: Sample Bit is, 16, support QCOMExtractor
,07-01 12:07:01.413   531  8534 W Utils   : Qcom parser, bits per sample supported is 16 or 24
,07-01 12:07:01.423  3452  3452 I PagedView: IndicatorPagedView.nCapability with type count = 2 and capability = 20
07-01 12:07:01.423   531  8535 E MMParserExtractor: FileSource::FILE_SOURCE_DATA_END 
07-01 12:07:01.423   531  8535 E FLACDecoder: qti_flac: Parser returned -1011
07-01 12:07:01.423   531  8534 W Utils   : Qcom parser, bits per sample supported is 16 or 24
,07-01 12:07:01.423   531  8534 W Utils   : Qcom parser, bits per sample supported is 16 or 24
,07-01 12:07:01.443  3452  3452 I Prism.AllAppsOptionsMa_: getAllAppsAbility() false,
07-01 12:07:01.443  3452  3452 I Prism.AllAppsOptionsMa_: removeAllAppsAbility()
07-01 12:07:01.443  1114  3911 I ActivityManager: Start proc 8540:com.htc.launcher:biclient/u0a59 for service com.htc.launcher/com.htc.BiLogClient.BiLogUploadService
07-01 12:07:01.443  3452  4377 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
,07-01 12:07:01.443  3452  3452 D CoworkInterfaceListener: loadMethod() = true
,07-01 12:07:01.453  3452  3452 D CoworkInterfaceListener: IsSecure: 1
07-01 12:07:01.453  3452  3452 D CoworkInterfaceListener: IsDuggable: 0
07-01 12:07:01.453  3452  3452 D CoworkInterfaceListener: isTestable: false
07-01 12:07:01.453  3452  3452 D CoworkInterfaceListener: Enable CIListener: false
,07-01 12:07:01.453   531  8535 E MMParserExtractor: FileSource::FILE_SOURCE_DATA_END 
07-01 12:07:01.453   531  8535 E FLACDecoder: qti_flac: Parser returned -1011
07-01 12:07:01.453  3452  3452 I ContextualWidget: onResume
07-01 12:07:01.453  3452  3452 I ContextualWidget: notifyWidgetActive location size=0 user consent location=false
07-01 12:07:01.453  3452  8494 I ContextualWidget: handleMessage, what=1018 mode=GettingOut maxcount=8
07-01 12:07:01.453  3452  3452 I ContextualWidget: ignore uploadUsageData location=false usage data=false allowAutoUpload=true,
07-01 12:07:01.453  3452  3452 I ContextualWidget: postSyncRecommendedApps, isReady=true allowAutoSync=true syncMode=1 isEnableRecommend=true
07-01 12:07:01.453  3452  3776 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/com.htc.launcher.prefs.contextualwidget.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/com.htc.launcher.prefs.contextualwidget.xml.bak
,07-01 12:07:01.463   499   499 E qdoverlay: validateAndSet failed, error 108: Cannot send after transport endpoint shutdown,
,07-01 12:07:01.463   499   499 E qdoverlay: Bad ov dump:  mdp_overlay z=4 alpha=255 mask=-1 flags=0x220000 id=8
07-01 12:07:01.463  1114  3442 D PMS     : acquireHCC(30e4a76e): CPU_MIN_NUM PrismLaunch_20 0x8000 3452 10059 null
07-01 12:07:01.463   499   499 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
07-01 12:07:01.473  1114  1134 V WindowManager: Adding window Window{3df8ee9c u0 com.htc.launcher/com.htc.launcher.Launcher} at 2 of 11 (after Window{2b365e7c u0 com.htc.launcher/com.htc.launcher.Launcher EXITING})
07-01 12:07:01.463   499   499 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
07-01 12:07:01.463   499   499 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
07-01 12:07:01.463   499   499 E qdoverlay: validateAndSet failed, error 108: Cannot send after transport endpoint shutdown
07-01 12:07:01.463   499   499 E qdoverlay: Bad ov dump:  mdp_overlay z=3 alpha=255 mask=-1 flags=0x220000 id=8
07-01 12:07:01.463   499   499 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
07-01 12:07:01.463   499   499 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
07-01 12:07:01.463   499   499 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
07-01 12:07:01.463   499   499 E qdoverlay: validateAndSet failed, error 108: Cannot send after transport endpoint shutdown
07-01 12:07:01.463   499   499 E qdoverlay: Bad ov dump:  mdp_overlay z=2 alpha=255 mask=-1 flags=0x220000 id=8
,07-01 12:07:01.463   499   499 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
07-01 12:07:01.463   499   499 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
07-01 12:07:01.463   499   499 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
07-01 12:07:01.463   499   499 E qdoverlay: validateAndSet failed, error 108: Cannot send after transport endpoint shutdown
07-01 12:07:01.463   499   499 E qdoverlay: Bad ov dump:  mdp_overlay z=1 alpha=255 mask=-1 flags=0x220000 id=8
07-01 12:07:01.463   499   499 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
07-01 12:07:01.463   499   499 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
07-01 12:07:01.463   499   499 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
07-01 12:07:01.463   499   499 E qdoverlay: validateAndSet failed, error 108: Cannot send after transport endpoint shutdown
07-01 12:07:01.463   499   499 E qdoverlay: Bad ov dump:  mdp_overlay z=0 alpha=255 mask=-1 flags=0x220000 id=8
07-01 12:07:01.463   499   499 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
07-01 12:07:01.463   499   499 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
07-01 12:07:01.463   499   499 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
07-01 12:07:01.463   499   499 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Cannot send after transport endpoint shutdown
07-01 12:07:01.463   499   499 E qdoverlay: MdpCtrl close error in unset
07-01 12:07:01.463  3452  3896 E Prism.WidgetManager: The same lists. No need to update. skip it.
07-01 12:07:01.463  3452  3896 I Prism.WidgetManager: onLoadItems() -
07-01 12:07:01.463  3452  3896 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@2966e341 -
07-01 12:07:01.463  8540  8540 W HTCLOG  : use specified tag [FDManager], func [0].
07-01 12:07:01.463  8540  8540 W HTCLOG  : mask=0x18
07-01 12:07:01.463  3452  3896 I Prism.ExternalAppState_: com.test.thalitest is not installed
,07-01 12:07:01.463  3452  3896 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
07-01 12:07:01.463  3452  3896 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.AllAppsManager@1331bdb9 +
07-01 12:07:01.473  1114  3670 D PMS     : acquireHCC(11f45888): CPU_MIN_FREQ PrismLaunch_20 0x2000 3452 10059 null
07-01 12:07:01.463  3452  3896 I Prism.AllAppsManager: onLoadItems() +
07-01 12:07:01.473  3452  4297 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467367621484
,07-01 12:07:01.483  3452  4297 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml.bak
,07-01 12:07:01.533  8540  8540 I MultiDex: VM with version 2.1.0 has multidex support
07-01 12:07:01.533  8540  8540 I MultiDex: install
,07-01 12:07:01.533  8540  8540 I MultiDex: VM has multidex support, MultiDex support library is disabled.
07-01 12:07:01.533   499   867 E qdhwcomposer: hwc_vsync_control: vsync control failed. Dpy=0, enable=0 : Cannot send after transport endpoint shutdown
,07-01 12:07:01.533   499   867 E SurfaceFlinger: eventControl(0, 0) failed Cannot send after transport endpoint shutdown
,07-01 12:07:01.533  3321  3365 E SQLiteLog: (3850) statement aborts at 83: [UPDATE data SET lastRequest=? WHERE type = 1] disk I/O error
07-01 12:07:01.533  3321  3365 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
07-01 12:07:01.533  3321  3365 W HTCLOG  : mask=0x18
,07-01 12:07:01.533  3321  3365 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.sense.hsp/databases/weathersync.db, handle: 0x55af8d1760
07-01 12:07:01.543  3321  3365 W WSP     : [Provider] caught exception: disk I/O error (code 3850)
07-01 12:07:01.543  3321  3365 W WSP     : android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850),
07-01 12:07:01.543  3321  3365 W WSP     : 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-01 12:07:01.543  3321  3365 W WSP     : 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
07-01 12:07:01.543  3321  3365 W WSP     : 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-01 12:07:01.543  3321  3365 W WSP     : 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-01 12:07:01.543  3321  3365 W WSP     : 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1675)
07-01 12:07:01.543  3321  3365 W WSP     : 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1621)
07-01 12:07:01.543  3321  3365 W WSP     : 	at com.htc.sense.hsp.weather.provider.data.Provider.update(Unknown Source)
07-01 12:07:01.543  3321  3365 W WSP     : 	at android.content.ContentProvider$Transport.update(ContentProvider.java:338)
07-01 12:07:01.543  3321  3365 W WSP     : 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:258)
07-01 12:07:01.543  3321  3365 W WSP     : 	at android.os.Binder.execTransact(Binder.java:454)
07-01 12:07:01.543  8495  8532 W WeatherUtility: adding request is failed, request: 
,07-01 12:07:01.543  8495  8532 D WeatherUtility: Weather sync is On
07-01 12:07:01.543  8495  8532 W Settings: Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-01 12:07:01.553  3321  3321 V WSP     : [SyncService] no data connection, stop sync service
,07-01 12:07:01.563  8495  8532 D HtcThemeUtils: context=android.view.ContextThemeWrapper@215025bb, category=0, byUser=false, userHandle=0
,07-01 12:07:01.563  3452  4297 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1467367621579
,07-01 12:07:01.573  8495  8532 D HtcThemeUtils: [CC][checkIfNeedRecreate] mNeedRecreate=false, mCategoryRes=null, mCategoryTheme=null, sameDefRes=false
,07-01 12:07:01.573  8495  8532 W HtcThemeUtils: Can not get alternative color from specificInfo:C:0:0:0:0:0:0:0:0:0:0:0:0, with category(0)
07-01 12:07:01.573  8495  8532 W HtcThemeUtils: java.lang.IllegalArgumentException: Unknown color
07-01 12:07:01.573  8495  8532 W HtcThemeUtils: 	at android.graphics.Color.parseColor(Color.java:216)
07-01 12:07:01.573  8495  8532 W HtcThemeUtils: 	at com.htc.lib1.cc.c.h.a(HtcThemeUtils.java:594)
07-01 12:07:01.573  8495  8532 W HtcThemeUtils: 	at com.htc.lib1.cc.c.h.d(HtcThemeUtils.java:513)
07-01 12:07:01.573  8495  8532 W HtcThemeUtils: 	at com.htc.lib1.cc.c.h.c(HtcThemeUtils.java:459)
07-01 12:07:01.573  8495  8532 W HtcThemeUtils: 	at com.htc.lib1.cc.c.h.b(HtcThemeUtils.java:449)
07-01 12:07:01.573  8495  8532 W HtcThemeUtils: 	at com.htc.lib1.cc.c.h.a(HtcThemeUtils.java:424)
07-01 12:07:01.573  8495  8532 W HtcThemeUtils: 	at com.htc.lib1.cc.c.g.a(HtcThemeUtils.java:1112)
07-01 12:07:01.573  8495  8532 W HtcThemeUtils: 	at com.htc.lib1.cc.c.g.a(HtcThemeUtils.java:1076)
07-01 12:07:01.573  8495  8532 W HtcThemeUtils: 	at com.htc.lib1.cc.c.g.a(HtcThemeUtils.java:365)
07-01 12:07:01.573  8495  8532 W HtcThemeUtils: 	at com.htc.lib1.cc.c.c.a(HtcCommonUtil.java:372)
07-01 12:07:01.573  8495  8532 W HtcThemeUtils: 	at com.htc.widget.weatherclock.util.WidgetTheme.init(WidgetTheme.java:29)
07-01 12:07:01.573  8495  8532 W HtcThemeUtils: 	at com.htc.widget.weatherclock.util.WidgetTheme.<init>(WidgetTheme.java:22)
,07-01 12:07:01.573  8495  8532 W HtcThemeUtils: 	at com.htc.widget.weatherclock.res.WeatherTransClock4x1Res.<init>(WeatherTransClock4x1Res.java:16)
07-01 12:07:01.573  8495  8532 W HtcThemeUtils: 	at com.htc.widget.weatherclock.view.WeatherTransClock4x1View.<init>(WeatherTransClock4x1View.java:34)
07-01 12:07:01.573  8495  8532 W HtcThemeUtils: 	at com.htc.widget.weatherclock.util.WidgetUtils.getAllViews(WidgetUtils.java:42)
07-01 12:07:01.573  8495  8532 W HtcThemeUtils: 	at com.htc.widget.weatherclock.util.WidgetConfigure$ConfigureTask.doInBackground(WidgetConfigure.java:160)
07-01 12:07:01.573  8495  8532 W HtcThemeUtils: 	at com.htc.widget.weatherclock.util.WidgetConfigure$ConfigureTask.doInBackground(WidgetConfigure.java:144)
07-01 12:07:01.573  8495  8532 W HtcThemeUtils: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
07-01 12:07:01.573  8495  8532 W HtcThemeUtils: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-01 12:07:01.573  8495  8532 W HtcThemeUtils: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
07-01 12:07:01.573  8495  8532 W HtcThemeUtils: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-01 12:07:01.573  8495  8532 W HtcThemeUtils: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-01 12:07:01.573  8495  8532 W HtcThemeUtils: 	at java.lang.Thread.run(Thread.java:818)
,07-01 12:07:01.583  8495  8532 W HTCLOG  : use specified tag [ResourceType], func [0].
07-01 12:07:01.583  8495  8532 W HTCLOG  : mask=0x18
07-01 12:07:01.583  8495  8532 E ResourceType: Style contains key with bad entry: 0x01010504
07-01 12:07:01.583  3452  4237 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467367621592
07-01 12:07:01.583  8495  8532 D HtcThemeUtils: context=android.view.ContextThemeWrapper@215025bb, target=/data/data/com.htc.launcher/files/.htc_theme/CResources.apk
,07-01 12:07:01.583  3452  4237 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml.bak
07-01 12:07:01.583  8495  8532 W HTCLOG  : use specified tag [asset], func [0].
07-01 12:07:01.583  8495  8532 W HTCLOG  : mask=0x18
07-01 12:07:01.583  8495  8532 W asset   : Asset path /data/data/com.htc.launcher/files/.htc_theme/CResources.apk is neither a directory nor file (type=0).
07-01 12:07:01.583  8495  8532 D HtcThemeUtils: AssetMaanger addAssetPath CResources fail!
07-01 12:07:01.583  8495  8532 D HtcThemeUtils: init done
07-01 12:07:01.583  8495  8532 D HtcThemeUtils: context=com.htc.widget.weatherclock.util.WidgetService@4413ad8, target=/data/data/com.htc.launcher/files/.htc_theme/WeatherClock.apk
07-01 12:07:01.583  8495  8532 W asset   : Asset path /data/data/com.htc.launcher/files/.htc_theme/WeatherClock.apk is neither a directory nor file (type=0).
07-01 12:07:01.583  8495  8532 D HtcThemeUtils: AssetMaanger addAssetPath WeatherClock fail!
,07-01 12:07:01.603  1114  2959 V AlarmManager: sending alarm PendingIntent{78ad15: PendingIntentRecord{100e8080 com.android.vending startService}}, i=null, t=0, cnt=1, w=1467367621615, Int=0
,07-01 12:07:01.603  8432  8432 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(17227): Beginning daily hygiene, foreground = false
,07-01 12:07:01.623   499   499 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Cannot send after transport endpoint shutdown
07-01 12:07:01.623   499   499 E qdoverlay: MdpCtrl close error in unset
07-01 12:07:01.623   499   499 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Cannot send after transport endpoint shutdown
07-01 12:07:01.623   499   499 E qdoverlay: MdpCtrl close error in unset
07-01 12:07:01.623   499   499 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Cannot send after transport endpoint shutdown
07-01 12:07:01.623   499   499 E qdoverlay: MdpCtrl close error in unset
,07-01 12:07:01.623   499   499 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Cannot send after transport endpoint shutdown
07-01 12:07:01.623   499   499 E qdoverlay: MdpCtrl close error in unset

```
