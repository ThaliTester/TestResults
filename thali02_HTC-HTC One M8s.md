#### Test 7578926821ef376_thali02_HTC-HTC One M8s Logs


```
--------- beginning of system
07-07 20:26:06.769   966  1746 I ActivityManager: Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=5623 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a
--------- beginning of main
07-07 20:26:06.799   434   434 I art     : Explicit concurrent mark sweep GC freed 8608(365KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 375us total 38.676ms
,07-07 20:26:06.829  5623  5623 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-07 20:26:06.829   434   434 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 198us total 29.076ms
07-07 20:26:06.849   966  1793 D PMS     : acquireWL(3b6617e): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 5623 10069 null
07-07 20:26:06.859   966  1541 D PMS     : acquireWL(bd016df): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 5623 10069 null
07-07 20:26:06.859   966  1732 D PMS     : acquireWL(11159df5): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 5623 10069 null
07-07 20:26:06.859   966   985 D PMS     : releaseWL(3b6617e): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
07-07 20:26:06.869   434   434 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 211us total 29.797ms
07-07 20:26:06.869   966  5647 I CertBlacklister: Certificate blacklist changed, updating...
07-07 20:26:06.869  5600  5600 D SMSBackup: Got a database change event
07-07 20:26:06.869   966   985 D PMS     : acquireWL(bd016df): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 5623 10069 null
07-07 20:26:06.869   966  1795 D PMS     : releaseWL(11159df5): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
07-07 20:26:06.879   966  5647 I CertBlacklister: Certificate blacklist updated
07-07 20:26:06.879  5623  5649 E TodoTaskNotifyService: java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
07-07 20:26:06.879  5623  5649 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
07-07 20:26:06.879  5623  5649 W System.err: 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
07-07 20:26:06.879  5623  5649 W System.err: 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
07-07 20:26:06.879  5623  5649 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:26:06.879  5623  5649 W System.err: 	at android.os.Looper.loop(Looper.java:155)
07-07 20:26:06.879   966  1270 D PMS     : releaseWL(bd016df): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
07-07 20:26:06.879  5623  5649 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-07 20:26:06.879  5623  5649 W NotifyReceiver: stopSelfResult true
07-07 20:26:06.879  5623  5649 E TodoTaskNotifyService: java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
07-07 20:26:06.879  5623  5649 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
07-07 20:26:06.889  5623  5649 W System.err: 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
07-07 20:26:06.889  5623  5649 W System.err: 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
07-07 20:26:06.889  5623  5649 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:26:06.889  5623  5649 W System.err: 	at android.os.Looper.loop(Looper.java:155)
07-07 20:26:06.889  5623  5649 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-07 20:26:06.889  5623  5649 E NotifyReceiver: mStartingService is null
07-07 20:26:06.889  5623  5649 W NotifyReceiver: stopSelfResult false
07-07 20:26:06.889  1964  1984 I GservicesProvider: main difference update completed
07-07 20:26:06.899  2194  5284 I CheckinRequestBuilder: Checkin reason type: 8 attempt count: 1
07-07 20:26:06.899   966  1795 I ActivityManager: Cannot resolve ContentProvider=com.google.android.wearable.settings
07-07 20:26:06.899  2194  5284 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
07-07 20:26:06.919  1600  1901 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
07-07 20:26:06.919  1600  1901 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@7f6d2e9 +
07-07 20:26:06.919  1600  1901 I Prism.WidgetManager: onLoadItems() +
07-07 20:26:06.949   966  1270 D Process : killProcessQuiet, pid=5196
07-07 20:26:06.949   966  1270 I ActivityManager: Killing 5196:com.google.android.music:main/u0a159 (adj 15): empty #17
07-07 20:26:06.949   966  1270 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
07-07 20:26:06.969  1600  1901 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
07-07 20:26:07.019   966  1794 I ActivityManager: Recipient 5196
07-07 20:26:07.019   966  1732 D MediaRouterService: Client com.google.android.music (pid 5196): Died!
07-07 20:26:07.049  1600  3007 I SocialFeedProvider: +disConnect socialManager
07-07 20:26:07.049  1600  3007 I SocialFeedProvider: disconnect socialManager
07-07 20:26:07.059   966  1026 I ActivityManager: Waited long enough for: ServiceRecord{1273bd4e u0 com.google.android.gms/.config.ConfigFetchService}
07-07 20:26:07.059  3853  3853 D MtpReceiver: [MTP][handleUsbStateAsync]+
07-07 20:26:07.059  3853  3853 D MtpReceiver: [MTP][handleUsbStateAsync]1:1-
07-07 20:26:07.059  3853  5653 D MtpReceiver: [MTP][handleUsbState]+
07-07 20:26:07.059  1600  3007 I SocialFeedProvider: -disConnect socialManager
07-07 20:26:07.089   966  1541 I ActivityManager: Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=5655 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a
07-07 20:26:07.089  3853  5653 D MtpReceiver: [MTP][scanExternalVolumeIfNeed] scan external volume
07-07 20:26:07.089  3853  3853 D MtpService: updating state; isCurrentUser=true, mMtpLocked=false
07-07 20:26:07.089  3853  3853 D MtpDatabase: TotalSize=1886532,MediaCacheLimit=6000
07-07 20:26:07.089  3853  5653 D MtpReceiver: [MTP][handleUsbState]-
07-07 20:26:07.089  3853  5653 D MtpReceiver: [MTP][handleMessage]-
07-07 20:26:07.099   966  1271 D PMS     : acquireWL(3bedc218): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 2194 10024 null
07-07 20:26:07.099  3853  3853 D MtpService: [isMtpConnected] connected: true
07-07 20:26:07.119  1560  2192 D PhoneApp: EVENT_QUERY_MO_PACKAGES
07-07 20:26:07.119  1560  2192 D PhoneApp: -- N1 =0
07-07 20:26:07.119  1560  2192 D PhoneApp: -- N2 =0
07-07 20:26:07.119  1560  2192 D PhoneApp: -- N3 =0
07-07 20:26:07.129  5650  5679 E cutils-trace: Error opening trace file: Permission denied (13)
07-07 20:26:07.169   966  1250 I ActivityManager: Start proc com.htc.sense.news for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper: pid=5691 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=armeabi-v7a
07-07 20:26:07.169   966  1250 V AlarmManager: sending alarm PendingIntent{2bef2471: PendingIntentRecord{32532256 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1467915967156, Int=0
07-07 20:26:07.189  2194  5667 I iu.UploadsManager: End new media; added: 0, uploading: 0, time: 93 ms
07-07 20:26:07.189   438   438 I art     : Explicit concurrent mark sweep GC freed 8678(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 265us total 20.906ms
07-07 20:26:07.189   966  1271 D PMS     : releaseWL(3bedc218): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 null
07-07 20:26:07.199  3853  3853 E MediaScannerService: [onStartCommand] --- Should not be here, redirect request. ----
07-07 20:26:07.199  3853  5668 E MediaScannerService: [handleMessage] --- Should not be here, ignore request. ----
07-07 20:26:07.209   438   438 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 211us total 15.313ms
07-07 20:26:07.219   438   438 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 235us total 14.466ms
07-07 20:26:07.229  5650  5650 D CustomizationManager: ====startRecUseTime====
07-07 20:26:07.229  5650  5650 D htc.customization.log.level:  is 
07-07 20:26:07.229  5650  5650 W CustomizationLogLevel: Level value is invalid, use default level 2
07-07 20:26:07.229  5655  5655 D SyncApplication: Loading default preferences
07-07 20:26:07.229  1600  1901 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-07 20:26:07.249  5691  5691 I MultiDex: VM with version 2.1.0 has multidex support
07-07 20:26:07.249  5691  5691 I MultiDex: install
07-07 20:26:07.249  5691  5691 I MultiDex: VM has multidex support, MultiDex support library is disabled.
07-07 20:26:07.259  5655  5655 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
07-07 20:26:07.299  5650  5650 D CustomizationManager:  Read ACC file spent 0.037 (s)
07-07 20:26:07.299  5650  5650 D CIDMapFileReader: Parsing tag item name = HTC__001
07-07 20:26:07.299  5650  5650 D CIDMapFileReader: Parsing tag item name = HTC__102
07-07 20:26:07.299  5650  5650 D CIDMapFileReader: Parsing tag item name = HTC__Y13
07-07 20:26:07.299  5650  5650 D CIDMapFileReader: Parsing tag item name = HTC__032
07-07 20:26:07.299  5650  5650 D CIDMapFileReader: Parsing tag item name = HTC__M27
07-07 20:26:07.299  5650  5650 D CIDMapFileReader: Parsing tag item name = HTC__002
07-07 20:26:07.299  5650  5650 D CIDMapFileReader: Parsing tag item name = HTC__031
07-07 20:26:07.299  5650  5650 D CIDMapFileReader: Parsing tag item name = HTC__A07
07-07 20:26:07.309  5650  5650 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__102.xml
07-07 20:26:07.309  5650  5650 I CustomizationCIDLoader: Parsing tag category name = system
07-07 20:26:07.309  5650  5650 I CustomizationCIDLoader: Parsing tag category name = application
07-07 20:26:07.309  5650  5650 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
07-07 20:26:07.309  5650  5650 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
07-07 20:26:07.309  5650  5650 I CustomizationCIDLoader: Parsing tag category name = AudioService
07-07 20:26:07.309  5650  5650 I CustomizationCIDLoader: Parsing tag category name = Settings
07-07 20:26:07.309  5650  5650 I CustomizationCIDLoader: Parsing tag category name = ACC
07-07 20:26:07.309  5650  5650 I CustomizationCIDLoader: add string-array item, value = 42507
07-07 20:26:07.309  5650  5650 I CustomizationCIDLoader: add string-array item, value = 21902
07-07 20:26:07.309  5650  5650 I CustomizationCIDLoader: add string-array item, value = 26006:26001.26002.26003
07-07 20:26:07.309  5650  5650 I CustomizationCIDLoader: add string-array item, value = 23420
07-07 20:26:07.309  5650  5650 I CustomizationCIDLoader: add string-array item, value = 22299
07-07 20:26:07.309  5650  5650 I CustomizationCIDLoader: add string-array item, value = 24002
07-07 20:26:07.309  5650  5650 I CustomizationCIDLoader: add string-array item, value = 23210
07-07 20:26:07.309  5650  5650 I CustomizationCIDLoader: add string-array item, value = 23205
07-07 20:26:07.309  5650  5650 I CustomizationCIDLoader: add string-array item, value = 23806
07-07 20:26:07.309  5650  5650 I CustomizationCIDLoader: add string-array item, value = 23430
07-07 20:26:07.309  5650  5650 I CustomizationCIDLoader: add string-array item, value = 23408
07-07 20:26:07.309  5650  5650 I CustomizationCIDLoader: add string-array item, value = 27205
07-07 20:26:07.309  5650  5650 I CustomizationCIDLoader: add string-array item, value = 42507:C:1:0
07-07 20:26:07.309  5650  5650 I CustomizationCIDLoader: add string-array item, value = 21902:C:1:0
07-07 20:26:07.309  5650  5650 I CustomizationCIDLoader: add string-array item, value = 26006:D:1:0
07-07 20:26:07.309  5650  5650 I CustomizationCIDLoader: add string-array item, value = 23420:D:0:0
07-07 20:26:07.309  5650  5650 I CustomizationCIDLoader: add string-array item, value = 22299:D:0:0
07-07 20:26:07.309  5650  5650 I CustomizationCIDLoader: add string-array item, value = 24002:D:0:0
07-07 20:26:07.309  5650  5650 I CustomizationCIDLoader: add string-array item, value = 23210:D:2:0
07-07 20:26:07.309  5650  5650 I CustomizationCIDLoader: add string-array item, value = 23205:D:2:0
07-07 20:26:07.309  5650  5650 I CustomizationCIDLoader: add string-array item, value = 23806:D:0:0
07-07 20:26:07.319   966  1262 D WifiService: New client listening to asynchronous messages
07-07 20:26:07.309  5650  5650 I CustomizationCIDLoader: add string-array item, value = 23430:C:1:0
07-07 20:26:07.309  5650  5650 I CustomizationCIDLoader: add string-array item, value = 23408:C:1:0
07-07 20:26:07.309  5650  5650 I CustomizationCIDLoader: add string-array item, value = 27205:C:1:0
07-07 20:26:07.309  5650  5650 D CustomizationManager:  Read CID file spent 0.078 (s)
07-07 20:26:07.309  5650  5650 D CustomizationManager:  All configurations done spent 0.078 (s)
07-07 20:26:07.309  3853  5712 E MediaScannerServiceEx: [getStorageMaskIdFromPath] path is null
07-07 20:26:07.309  3853  5712 D MediaScannerServiceEx: [ServiceHandler][handleMessage] , action: null, Id: 0, path: /storage/emulated/0
07-07 20:26:07.319   966   966 E WifiTrafficPoller: ADD_CLIENT: 7
07-07 20:26:07.319  3853  5712 D MediaScannerServiceEx: [handleExternalVolume] ext storage
07-07 20:26:07.329  3853  5712 D MediaProviderUtils: calcVolumeId: /storage/emulated/0
07-07 20:26:07.329  3853  5712 D MediaProviderUtils: calcVolumeId: /storage/ext_sd
07-07 20:26:07.329  3853  5712 D MediaProviderUtils: calcVolumeId: /storage/usb
07-07 20:26:07.329  3853  5712 D MediaScannerServiceEx: [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
07-07 20:26:07.329  3853  5712 D MediaScannerServiceEx: [AliveExtStorageRows]+65537, 11223344
07-07 20:26:07.329  3853  5712 D MediaProvider: [update][7]#0#
07-07 20:26:07.339  3853  5712 D MediaProvider: [update][2]#0#
07-07 20:26:07.349  5691  5720 I SocialManager[SocialBiLogHelper]: action: com.htc.sense.hsp.HANDLE_ULOG
07-07 20:26:07.349  5691  5720 I SocialManager[SocialBiLogHelper]: last commit ulog time 1467867127825
07-07 20:26:07.349  5691  5720 I SocialManager[SocialBiLogHelper]: skip commit this time
07-07 20:26:07.349   966  1791 D Process : killProcessQuiet, pid=4977
07-07 20:26:07.349   966  1791 I ActivityManager: Killing 4977:com.htc.bgp/u0a11 (adj 15): empty #17
07-07 20:26:07.349   966  1791 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
07-07 20:26:07.359  5655  5655 D SyncApplication: Overriding preferences with custom values
07-07 20:26:07.369  3853  5712 D MediaProvider: [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
07-07 20:26:07.369  3853  5712 D MtpService: [sendStorageAdded] Already send to MTP: /storage/emulated/0
07-07 20:26:07.369  3853  5712 D MediaProvider: [update][24]#1#
07-07 20:26:07.369  3853  5712 D MediaScannerServiceEx: [AliveExtStorageRows]-0, 0
07-07 20:26:07.369   966  1795 D PMS     : acquireWL(215b6b5c): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3853 10017 null
07-07 20:26:07.379  5655  5655 D SyncApplication: Updating preferences succeeded
07-07 20:26:07.379  1964  1997 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
07-07 20:26:07.379  1964  1997 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
07-07 20:26:07.379  1964  1997 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:26:07.379  1964  1997 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-07 20:26:07.419  1600  1901 W asset   : Copying FileAsset 0xac81e7d0 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
07-07 20:26:07.479  1600  1901 I Prism.WidgetManager: onLoadItems() -
07-07 20:26:07.479  1600  1901 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@7f6d2e9 -
07-07 20:26:07.499  1600  1901 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-07 20:26:07.499  1600  1901 W PackageManager: Failure retrieving resources for com.test.thalitest: Resource ID #0x0
07-07 20:26:07.499  1600  1901 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
07-07 20:26:07.499  1600  1901 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
07-07 20:26:07.509   966  1732 I ActivityManager: Recipient 4977
07-07 20:26:07.519  1600  1600 W SystemReader: Cannot find allapps_style_enabled_deafult, use default value instead
07-07 20:26:07.519  1600  1600 I Prism.AllAppsOptionsMa_: getAllAppsAbility() true
07-07 20:26:07.519  1600  1600 W SystemReader: Cannot find support_china_sense_feature, use default value instead
07-07 20:26:07.519  1600  1600 I Prism.AllAppsOptionsMa_: removeAllAppsAbility()
07-07 20:26:07.519  1600  1600 W SystemReader: Cannot find support_china_sense_feature, use default value instead
07-07 20:26:07.539   966   966 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 7
07-07 20:26:07.539   966   966 E WifiTrafficPoller:  packet count Tx=215 Rx=351
07-07 20:26:07.559   966  1793 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 5650 on display 0
07-07 20:26:07.559   966  1067 D PMS     : acquireHCC(33caee65): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 966 1000 null
07-07 20:26:07.569   966  1067 D PMS     : acquireHCC(2928773a): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 966 1000 null
07-07 20:26:07.579   966  1793 D PMS     : acquireWL(2f810be1): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 966 1000 null
07-07 20:26:07.589   966  1039 I AnimationUtil: isHTCRecent(ThaliTest/Recent screens.)/4
07-07 20:26:07.599  5655  5655 E SyncApplication: Application created.
07-07 20:26:07.609  1600  1600 I FeedHostManager: [onPause]
07-07 20:26:07.609  1600  1600 I FeedProviderManager: onPause
07-07 20:26:07.609  1600  1600 I FeedHostManager: [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@4711014
07-07 20:26:07.609  1600  2659 I SocialFeedProvider: +onPause
07-07 20:26:07.609  1600  2659 I SocialFeedProvider: -onPause
07-07 20:26:07.619  5655  5655 I CalendarDefines: getNewCalendarAuthority()...
07-07 20:26:07.619  5655  5724 W VolumeInfo: Unable to read mount points
07-07 20:26:07.619  5655  5724 W VolumeInfo: java.io.FileNotFoundException: /etc/vold.fstab: open failed: ENOENT (No such file or directory)
07-07 20:26:07.619  5655  5724 W VolumeInfo: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-07 20:26:07.619  5655  5724 W VolumeInfo: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-07 20:26:07.619  5655  5724 W VolumeInfo: 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
07-07 20:26:07.619  5655  5724 W VolumeInfo: 	at java.io.FileReader.<init>(FileReader.java:66)
07-07 20:26:07.619  5655  5724 W VolumeInfo: 	at com.nero.android.common.VolumeInfo.getVolumeMountPoints(VolumeInfo.java:194)
07-07 20:26:07.619  5655  5724 W VolumeInfo: 	at com.nero.android.common.VolumeInfo.getVolumes(VolumeInfo.java:153)
07-07 20:26:07.619  5655  5724 W VolumeInfo: 	at com.nero.android.common.VolumeInfo.initializeVolumeIDs(VolumeInfo.java:474)
07-07 20:26:07.619  5655  5724 W VolumeInfo: 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:51)
07-07 20:26:07.619  5655  5724 W VolumeInfo: 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:1)
07-07 20:26:07.619  5655  5724 W VolumeInfo: 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
07-07 20:26:07.619  5655  5724 W VolumeInfo: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-07 20:26:07.619  5655  5724 W VolumeInfo: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-07 20:26:07.619  5655  5724 W VolumeInfo: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-07 20:26:07.619  5655  5724 W VolumeInfo: 	at java.lang.Thread.run(Thread.java:818)
07-07 20:26:07.619  5655  5724 W VolumeInfo: Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
07-07 20:26:07.619  5655  5724 W VolumeInfo: 	at libcore.io.Posix.open(Native Method)
07-07 20:26:07.619  5655  5724 W VolumeInfo: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-07 20:26:07.619  5655  5724 W VolumeInfo: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-07 20:26:07.619  5655  5724 W VolumeInfo: 	... 13 more
07-07 20:26:07.619  5655  5724 V VolumeInfo: Found 0 mount point(s)
07-07 20:26:07.619   966  1746 I PackageManager:  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=5655, uid=10005, userID:0
07-07 20:26:07.619  5655  5724 V VolumeInfo: New VolumeInfo with mount point /storage/emulated/0 and sys path null created
07-07 20:26:07.619  1600  1600 I ContextualWidget: onPause
07-07 20:26:07.619  1600  1600 I ContextualWidget: notifyWidgetDeactive
07-07 20:26:07.619  1964  1997 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-07 20:26:07.619   966  1746 W PackageManager: Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
07-07 20:26:07.629   966  1271 I PackageManager:  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=5655, uid=10005, userID:0
07-07 20:26:07.629   966  1271 W PackageManager: Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
07-07 20:26:07.629  5655  5655 D SyncApplication: enableAppOperation()+
07-07 20:26:07.629  3853  5712 D MediaScanner: =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
07-07 20:26:07.629  5655  5655 D SyncApplication: enableAppOperation()-
07-07 20:26:07.629   966  1646 W HtcSystemUPManager: HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
07-07 20:26:07.629  5655  5724 D VolumeInfo: read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
07-07 20:26:07.629  5655  5655 D HTCUtilities: isNeorSinged() + 
07-07 20:26:07.639  5655  5724 D VolumeInfo: Read the volume-id from the sd card: {9B5E872B-8520-47C6-8BD3-3081C2E38355}
07-07 20:26:07.639  5655  5724 W VolumeInfo: Can not create volume ID for unmounted volume null
07-07 20:26:07.639  5655  5655 D HTCUtilities: sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
07-07 20:26:07.639  5655  5655 D HTCUtilities: isNeorSinged() return false
07-07 20:26:07.649  5655  5655 D CDMountReceiver: receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
07-07 20:26:07.649  5655  5655 D CDMountReceiver: USB connected to PC
07-07 20:26:07.649   966  1794 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5726 uid=10195 gids={50195, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-07 20:26:07.679  5655  5655 D FOTAReceiver: onReceive() enter 
07-07 20:26:07.679  5655  5655 D FOTAReceiver: receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
07-07 20:26:07.699   966  1794 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.NSReceiver: pid=5748 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
07-07 20:26:07.699   966  1794 D Process : killProcessQuiet, pid=5238
07-07 20:26:07.699   966  1794 I ActivityManager: Killing 5238:com.google.android.setupwizard/u0a77 (adj 15): empty #17
07-07 20:26:07.699   966  1794 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.trimApplications:19136 
07-07 20:26:07.809   966  1792 I ActivityManager: Recipient 5238
07-07 20:26:07.809   966  1533 D PMS     : acquireWL(312d22ea): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null
07-07 20:26:07.809   966  1533 I BatteryService: n_update end
07-07 20:26:07.809   966  1533 D PMS     : releaseWL(312d22ea): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,07-07 20:26:07.919  1600  1600 I TrimMemoryManager: [trimMemory] 20,
,07-07 20:26:07.929   966  1037 D StatusBarManagerService: setSystemUiVisibility(0x8600)
07-07 20:26:07.929   966  1037 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-07 20:26:07.929   966  1037 D StatusBarManagerService: hiding MENU key
,07-07 20:26:08.019   966  1045 D HtcPowerSaver: updateBatteryInfo,
07-07 20:26:08.029  1427  1427 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
07-07 20:26:08.029  1335  1335 D PowerUI : closing low battery warning: level=100
07-07 20:26:08.029  1427  1427 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
07-07 20:26:08.029  1335  1335 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
07-07 20:26:08.029  1427  1427 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
07-07 20:26:08.029   966   966 D NotificationService: plugged=true pluggin=true
07-07 20:26:08.029  1335  1684 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
07-07 20:26:08.029   966   966 D UsbnetService: BroadcastReceiver::onReceive+
07-07 20:26:08.029   966   966 D UsbnetService: onReceive BATTERY_CHANGED
07-07 20:26:08.029   966   966 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
07-07 20:26:08.029   966   966 D UsbnetService: BroadcastReceiver::onReceive-
07-07 20:26:08.029   966   966 D PMS     : runPSCheck
07-07 20:26:08.029  3089  3192 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-07 20:26:08.029   966   966 D HtcPowerSaver: Checking...
07-07 20:26:08.029   966   966 I HtcPowerSaver: >> updateStatus
,07-07 20:26:08.029   966  1262 D WifiController: handleMessage: E msg.what=155652
07-07 20:26:08.029   966  1262 D WifiController: processMsg: DeviceActiveState
07-07 20:26:08.029   966  1262 D WifiController: battery changed pluggedType: 2
07-07 20:26:08.029   966  1262 D WifiController: processMsg: StaEnabledState
07-07 20:26:08.029   966  1262 D WifiController: processMsg: DefaultState
07-07 20:26:08.029   966  1262 D WifiController: handleMessage: X
,07-07 20:26:08.039   966   966 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
07-07 20:26:08.039   966   966 I HtcPowerSaver: << updateStatus
,07-07 20:26:08.049  5748  5748 D Fingerprint/ HtcFingerPrintQuickLaunchProvider: -onCreate()
,07-07 20:26:08.049  1427  1647 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 3, tag: null, isClearable: true, isForDotMatrix: false
07-07 20:26:08.049  1427  1647 D DotMatrix: [EventService] notificationPosted, eventType:1014
,07-07 20:26:08.059  1427  1647 D DotMatrix: [EventService] notificationPosted, This eventType was disabled by user.
,07-07 20:26:08.069  2194  5284 W CheckinRequestBuilder: awaiting user notification for token
,07-07 20:26:08.069  1335  1335 I RemoteViews: reapply : com.google.android.gms 2 40
,07-07 20:26:08.079  5748  5748 V Settings:HtcSettingsApplication: [5748/5748] onCreate(),
,07-07 20:26:08.079  2194  5284 I CheckinRequestBuilder: Classify the device as Phone.
,07-07 20:26:08.089  1335  1335 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,07-07 20:26:08.089  5748  5748 D TetherSettings: CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse,
07-07 20:26:08.089  5748  5748 D         : Cust_ConnectToPC   : Internet_Sharing>true
07-07 20:26:08.089  5748  5748 D         : Cust_ConnectToPC   : Modem_Link>false
07-07 20:26:08.089  5748  5748 D         : Cust_ConnectToPC   : spcsc>false
07-07 20:26:08.089  5748  5748 D         : Cust_ConnectToPC   : IPT>true
07-07 20:26:08.089  5748  5748 D         : Cust_ConnectToPC   : Singel_USB>false
,07-07 20:26:08.099  5748  5748 W Settings: Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,07-07 20:26:08.109  5748  5748 E SmartNS_Utility: hasRemovableStorageSlot: true,
07-07 20:26:08.109  5748  5748 D SmartNS_Utility: [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
07-07 20:26:08.109  5748  5748 D SmartNS_NSReceiver: onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
,07-07 20:26:08.109  5748  5748 D SmartNS_Utility: usb_cable_connect = 1
07-07 20:26:08.109  5748  5748 D SmartNS_Utility: usb_denied = 0
,07-07 20:26:08.109  5748  5748 I SmartNS_NSReceiver: locked:falsesecurity:falseisLocked:false
07-07 20:26:08.119  5748  5748 D SmartNS_NSReceiver: USB = true hasTethered = false isNSOpening: false
,07-07 20:26:08.119  5748  5748 I SmartNS_PSReceiver: onReceive:com.htc.intent.action.USB_CONNECT2PC,
07-07 20:26:08.119  5748  5748 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.PSReceiver.onReceive:45 android.app.ActivityThread.handleReceiver:2712 
,07-07 20:26:08.159  5726  5726 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,07-07 20:26:08.169  3853  5712 D MediaProvider: [update][100]#1#
,07-07 20:26:08.199  1659  1876 D AutoSetting: service - mRequestRunnable: screen on delay 10s, request NLP now,
,07-07 20:26:08.199  1659  1876 D AutoSetting: Util - check NLP state, Allowned:false, Enabled:false,
07-07 20:26:08.209  1659  1876 D AutoSetting: service - requestNLP() NetworkLocationProvider not enabled
,07-07 20:26:08.269   966  1732 I art     : Explicit concurrent mark sweep GC freed 30333(1678KB) AllocSpace objects, 1(84KB) LOS objects, 33% free, 16MB/25MB, paused 1.642ms total 145.454ms,
,07-07 20:26:08.279  5748  5748 I SmartNS_PSService: onReceive:com.htc.intent.action.USB_CONNECT2PC
,07-07 20:26:08.279  5748  5748 W Settings: Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
07-07 20:26:08.279  5748  5748 I SmartNS_PSService:  defaultType:0,
07-07 20:26:08.279  5748  5748 I SmartNS_PSService: fail notificaiton:false
,07-07 20:26:08.279  5748  5748 D SmartNS_Utility: usb_cable_connect = 1
07-07 20:26:08.279  5748  5748 D SmartNS_Utility: usb_denied = 0
07-07 20:26:08.279  5748  5748 I SmartNS_PSService: usb notificaiton:true
,07-07 20:26:08.289   966  1794 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false,
,07-07 20:26:08.289   966  1533 I ActivityManager: Start proc com.htc.bgp for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5776 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,07-07 20:26:08.299  5748  5748 I ActionCombine: replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,07-07 20:26:08.309  5748  5748 D SmartNS_Utility: usb_cable_connect = 1
,07-07 20:26:08.309  5748  5748 D SmartNS_Utility: usb_denied = 0
,07-07 20:26:08.309  5748  5748 I SmartNS_PSService: usb notificaiton:true
07-07 20:26:08.309   966   986 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
07-07 20:26:08.319  1427  1461 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837809, tag: null, isClearable: false, isForDotMatrix: false
07-07 20:26:08.319  1335  1335 I RemoteViews: reapply : com.android.settings 2 36
07-07 20:26:08.319  2194  5284 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,07-07 20:26:08.329  5748  5748 D SmartNS_Utility: usb_cable_connect = 1
,07-07 20:26:08.329  5748  5748 D SmartNS_Utility: usb_denied = 0
,07-07 20:26:08.339  1427  1647 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837809, tag: null, isClearable: false, isForDotMatrix: false
07-07 20:26:08.339  5726  5726 I LibraryLoader: Time to load native libraries: 15 ms (timestamps 5503-5518)
,07-07 20:26:08.339  5726  5726 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-07 20:26:08.339  5748  5748 I SmartNS_PSService: KeyGuard locked:falseKeyGuard is secured:false
07-07 20:26:08.339  1335  1335 I RemoteViews: reapply : com.android.settings 1 36
07-07 20:26:08.339  5748  5748 D SmartNS_PSService: USB Plugged, Set USBPlugged=  truePSenabled:false
,07-07 20:26:08.349   966  1271 I ActivityManager: Killing 5262:com.google.android.apps.photos/u0a197 (adj 15): empty #17
07-07 20:26:08.349   966  1271 D Process : killProcessQuiet, pid=5262
,07-07 20:26:08.349   966  1271 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-07 20:26:08.349  5776  5776 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,07-07 20:26:08.369  5726  5726 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {361b3e0d}
,07-07 20:26:08.369  5726  5726 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-07 20:26:08.379  5726  5726 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,07-07 20:26:08.399  5726  5726 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-07 20:26:08.399  5726  5726 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-07 20:26:08.409  5726  5726 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-07 20:26:08.409   966   986 I ActivityManager: Recipient 5262
,07-07 20:26:08.459  2194  5284 I CheckinService: Checking schedule, now: 1467915968462 next: 1468452800326
,07-07 20:26:08.459  2194  5284 I CheckinService: active receiver: disabled
07-07 20:26:08.459   966  1732 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2194, uid=10024, userID:0
,07-07 20:26:08.459  5776  5776 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@1de2c337(com.htc.providers.calendar.HtcCalendarProvider@49210a4)
,07-07 20:26:08.489  5726  5726 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,07-07 20:26:08.499  5776  5803 D CalendarProvider2: wait start:true
,07-07 20:26:08.499  5726  5726 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-07 20:26:08.499  5726  5726 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-07 20:26:08.499  5726  5726 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BR.1.1.2.05.00.02.028.191_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2.05.00.02.028.191__release_AU ()
07-07 20:26:08.499  5726  5726 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
07-07 20:26:08.499  5726  5726 I Adreno-EGL: Build Date: 04/17/15 Fri
07-07 20:26:08.499  5726  5726 I Adreno-EGL: Local Branch: 
07-07 20:26:08.499  5726  5726 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2.05.00.02.028.191
07-07 20:26:08.499  5726  5726 I Adreno-EGL: Local Patches: NONE
07-07 20:26:08.499  5726  5726 I Adreno-EGL: Reconstruct Branch: NOTHING
07-07 20:26:08.499   966  1541 D PMS     : releaseWL(30f159): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
,07-07 20:26:08.519  3853  5712 D MediaProvider: [update][10]#1#
,07-07 20:26:08.519   966  1541 D PMS     : acquireWL(368e0ec1): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 5776 10011 null,
,07-07 20:26:08.529  5776  5803 D CalendarProvider2: wait end:false
,07-07 20:26:08.529  5776  5807 E SQLiteLog: (284) automatic index on view_events(_id),
,07-07 20:26:08.539   966   966 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 7
07-07 20:26:08.539   966   966 E WifiTrafficPoller:  packet count Tx=215 Rx=351
07-07 20:26:08.539   966   966 E WifiTrafficPoller: notifying of data activity 0
07-07 20:26:08.539  1335  1335 D WIFI_ICON: WifiActivity: 0
,07-07 20:26:08.549   966  1732 I ActivityManager: Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=5808 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
07-07 20:26:08.549  1335  1335 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,07-07 20:26:08.549   966  1793 D PMS     : releaseWL(368e0ec1): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,07-07 20:26:08.569   966  1270 W System.err: java.lang.Throwable: stack dump
07-07 20:26:08.569   966  1038 D BluetoothManagerService: Message: MESSAGE_REGISTER_ADAPTER
07-07 20:26:08.569   966  1270 W System.err: 	at java.lang.Thread.dumpStack(Thread.java:490)
07-07 20:26:08.569   966  1038 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3ee8bc3e:true
07-07 20:26:08.569   966  1270 W System.err: 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
07-07 20:26:08.569   966  1270 W System.err: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
07-07 20:26:08.569   966  1270 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
,07-07 20:26:08.569  5726  5828 D BluetoothAdapter: 1011527177: getState(). Returning 12
,07-07 20:26:08.639   966  1250 V AlarmManager: sending alarm PendingIntent{394df884: PendingIntentRecord{2203386d android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=65814, Int=0
,07-07 20:26:08.659  5808  5808 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.backupreset.receiver.BackupResetReceiver.onReceive:45 android.app.ActivityThread.handleReceiver:2712 
,07-07 20:26:08.679   966  1734 I ActivityManager: Killing 3889:com.htc.sense.mms/u0a64 (adj 15): empty #17,
07-07 20:26:08.679   966  1734 D Process : killProcessQuiet, pid=3889
07-07 20:26:08.679   966  1734 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-07 20:26:08.689  5776  5776 D FlexNetS: updateSvcAllowedInSettings:false,
,07-07 20:26:08.699  5726  5726 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-07 20:26:08.709  5726  5726 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-07 20:26:08.719  5726  5726 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC
,07-07 20:26:08.769  3853  5712 D MediaProvider: [update][25]#1#
,07-07 20:26:08.779  3853  5712 D MediaScanner:  prescan time: 391ms
,07-07 20:26:08.779  3853  5712 D MediaScanner:     scan time: 755ms
07-07 20:26:08.779  3853  5712 D MediaScanner: postscan time: 3ms
07-07 20:26:08.779  3853  5712 D MediaScanner:    total time: 1149ms
07-07 20:26:08.779  3853  5712 D MediaScanner: -----------------------------------------------------------------
07-07 20:26:08.779  3853  5712 D MediaScanner: firstscan(media) time: 470ms
07-07 20:26:08.779  3853  5712 D MediaScanner: secondscan(non-media) time: 285ms
07-07 20:26:08.779  3853  5712 D MediaScanner:  [Update]   Image: 0 Video: 0 Audio: 0 Other: 1
07-07 20:26:08.779  3853  5712 D MediaScanner:  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
07-07 20:26:08.779  3853  5712 D MediaScanner:  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
07-07 20:26:08.779  3853  5712 D MediaScanner:  [Total]    File(Image+Video+Audio+Others) in database : 1553
,07-07 20:26:08.779  3853  5712 D MediaProvider: [delete][7]
07-07 20:26:08.779  3853  5712 D MediaProvider: [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
,07-07 20:26:08.789   966  1270 I ActivityManager: Recipient 3889
,07-07 20:26:08.789  3853  5712 D MediaProvider: [recoverParentNodes] - 0
,07-07 20:26:08.789  3853  5712 D MediaProvider: [update][4]
07-07 20:26:08.789  3853  5712 D MediaScannerServiceEx: [scan] Recover Parent Node is finished!
07-07 20:26:08.789  3853  5712 D MediaScannerServiceEx: [updateImage]+
,07-07 20:26:08.799  3853  5712 D MediaScannerServiceEx: [updateImage]-0,
,07-07 20:26:08.889   966  1795 D PMS     : releaseWL(215b6b5c): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null,
07-07 20:26:08.889  5726  5726 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-07 20:26:08.889  5726  5726 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-07 20:26:08.899  3853  5712 D MediaScannerServiceEx: [1] scan finished
,07-07 20:26:08.899  3853  5712 D MediaProviderUtils: calcVolumeId: /storage/emulated/0
07-07 20:26:08.899  3853  5712 D MediaProviderUtils: calcVolumeId: /storage/ext_sd
07-07 20:26:08.899  3853  5712 D MediaProviderUtils: calcVolumeId: /storage/usb
07-07 20:26:08.899  3853  5712 D MediaScannerServiceEx: [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1
,07-07 20:26:08.899  3853  5712 W MediaScannerServiceEx: Process mounted intent for unmounted storage: /storage/ext_sd
07-07 20:26:08.899  3853  5712 D MediaScannerServiceEx: [disAliveExtStorageRows]+131073
,07-07 20:26:08.949  5726  5823 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,07-07 20:26:08.989  5726  5726 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,07-07 20:26:08.989   966  1261 E WifiStateMachine: handleMessage: E msg.what=131155,
07-07 20:26:08.989   966  1261 E WifiStateMachine: processMsg: ConnectedState
,07-07 20:26:08.989   966  1261 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=150 tx=21.4, 0.0, 0.0  rx=29.9 bcn=0 [on:0 tx:0 rx:0 period:2809] from screen [on:0 period:-962846235] gl hn u24 rssi=-51 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0,
07-07 20:26:08.989   966  1261 E WifiStateMachine: processMsg: L2ConnectedState
,07-07 20:26:08.989   966  1261 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=150 tx=21.4, 0.0, 0.0  rx=29.9 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-962846234] gl hn u24 rssi=-51 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-07 20:26:08.989   966  1261 E WifiStateMachine:  get link layer stats 0
07-07 20:26:08.989   966  1261 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,07-07 20:26:08.989  1456  1456 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
,07-07 20:26:08.999  3853  5712 D MediaProvider: [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted
07-07 20:26:08.999  3853  5712 D MediaProvider: [update][95]#1#
,07-07 20:26:09.009  1456  1456 I wpa_supplicant: environment dirty rate=0 [4][0][0]
07-07 20:26:09.009   966  1261 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 150
,07-07 20:26:09.009   966  1261 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-56 linkspeed=150
07-07 20:26:09.009   966  1261 E WifiConfigStore: updateConfiguration freq=2447 BSSID=f4:f2:6d:22:99:3e RSSI=-56 "NG700"WPA_PSK
,07-07 20:26:09.009   966  1261 E WifiStateMachine: calculateWifiScore freq=2447 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=12.70 txretriesrate=0.00 rxrate=17.46 userTriggerdPenalty0
,07-07 20:26:09.009   966  1261 E WifiStateMachine:  good link -> stuck count =0
07-07 20:26:09.009   966  1261 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 60
07-07 20:26:09.009   966  1261 E WifiStateMachine:  isHighRSSI       ---> score=65
,07-07 20:26:09.009   966  1286 D WifiWatchdogStateMachine: RSSI current: 3 new: -56, 3
07-07 20:26:09.009  1335  1335 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
07-07 20:26:09.009   966  1261 E WifiStateMachine: handleMessage: X
07-07 20:26:09.009  1335  1335 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,07-07 20:26:09.009  1600  1901 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
07-07 20:26:09.009  1600  1901 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@7f6d2e9 +
07-07 20:26:09.009  1600  1901 I Prism.WidgetManager: onLoadItems() +
,07-07 20:26:09.019  3853  5712 D MediaProvider: [update][26]#0#
,07-07 20:26:09.029  3853  5712 D MediaScannerServiceEx: [disAliveExtStorageRows]--1, 0
,07-07 20:26:09.029  3853  5712 D MediaProviderUtils: calcVolumeId: /storage/emulated/0
07-07 20:26:09.029  3853  5712 D MediaProviderUtils: calcVolumeId: /storage/ext_sd
07-07 20:26:09.029  3853  5712 D MediaProviderUtils: calcVolumeId: /storage/usb
07-07 20:26:09.029  3853  5712 D MediaScannerServiceEx: [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
,07-07 20:26:09.029  3853  5712 W MediaScannerServiceEx: Process mounted intent for unmounted storage: /storage/usb
07-07 20:26:09.029  3853  5712 D MediaScannerServiceEx: [disAliveExtStorageRows]+196609
,07-07 20:26:09.049  1600  1901 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,07-07 20:26:09.089  3853  5712 D MediaProvider: [sendStorageAddedIfNeed]: /storage/usb : unmounted,
07-07 20:26:09.089  3853  5712 D MediaProvider: [update][54]#1#
07-07 20:26:09.089  5726  5726 I InputMethodManager: [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@3c2d0635, mServedView=org.apache.cordova.engine.SystemWebView{190dfaca VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@2f99843b
,07-07 20:26:09.099   966  1794 I InputMethodManagerService: Disable input method client, pid=1600
,07-07 20:26:09.099   966  1794 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
,07-07 20:26:09.099   966  1794 I InputMethodManagerService: Enable input method client, pid=5726,
07-07 20:26:09.109  1335  1335 I PhoneStatusBar: setImeWindowStatus(false,false)
,07-07 20:26:09.109   966  1039 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s474ms
,07-07 20:26:09.119   966  1791 D PMS     : releaseWL(2f810be1): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,07-07 20:26:09.159  1501  1501 W XT9_C   : [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
07-07 20:26:09.159  1501  1501 I XT9_C   : [T9_ReleaseBuffer] Reset LDB#0
07-07 20:26:09.159  1501  1501 I XT9_C   : [T9_ReleaseBuffer] Reset LDB#1
07-07 20:26:09.159  1501  1501 D XT9_C   : [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,07-07 20:26:09.169  3853  5712 D MediaProvider: [update][79]#0#
07-07 20:26:09.169  3853  5712 D MediaScannerServiceEx: [disAliveExtStorageRows]--1, 0
,07-07 20:26:09.189   966  1270 D PMS     : acquireWL(13e3efc6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1964 10024 WorkSource{10024 com.google.android.gms},
,07-07 20:26:09.209  1659  5855 D WeatherUtility: Weather sync is On,
07-07 20:26:09.209   966  1794 I ActivityManager: Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=5856 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a
07-07 20:26:09.209  1659  5855 D WSP     : [Receiver] auto sync agent, auto sync is enabled, reset schedule
,07-07 20:26:09.209  5726  5726 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5726
,07-07 20:26:09.209   966   985 D PMS     : releaseWL(13e3efc6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,07-07 20:26:09.279   966  1270 I ActivityManager: Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=5880 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
,07-07 20:26:09.309  5856  5893 D WeatherUtility: Weather sync is On
,07-07 20:26:09.309  1600  1901 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,07-07 20:26:09.399  5726  5726 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-07 20:26:09.449  5856  5893 W WeatherRequest: request cur loc, but there is no sys cur
07-07 20:26:09.449  5856  5893 W Settings: Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-07 20:26:09.469  5856  5893 I ActionCombine: replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal],
,07-07 20:26:09.489  5880  5880 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,07-07 20:26:09.489   966  1541 D PMS     : acquireWL(2ef016dd): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 5776 10011 null,
07-07 20:26:09.499  1600  1600 I RemoteViews: reapply : com.htc.widget.weatherclock 14 17
,07-07 20:26:09.509  5776  5776 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,07-07 20:26:09.519  5776  5776 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,07-07 20:26:09.519  5880  5911 D PowerUtils: getUserIdOfProcess, curUserId = 0
07-07 20:26:09.519  5880  5911 D PowerUtils: isRunningUnderOwner, isOwner = true
,07-07 20:26:09.529   966  1270 I ActivityManager: Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=5914 uid=10028 gids={50028, 9997, 1028, 1015, 3003, 1023, 2001, 3002} abi=armeabi-v7a,
,07-07 20:26:09.539   966   966 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 7
07-07 20:26:09.549   966   966 E WifiTrafficPoller:  packet count Tx=215 Rx=351
07-07 20:26:09.549  5880  5911 D PowerUsageList:PowerUsageHelper: MY_DEBUG = false
07-07 20:26:09.549   966  1271 D PMS     : releaseWL(2ef016dd): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,07-07 20:26:09.559  5880  5911 D PowerUsageService: repeat time = 1467916869561
,07-07 20:26:09.569   966  1067 D PMS     : releaseHCC(33caee65): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,07-07 20:26:09.569   966  1067 D PMS     : releaseHCC(2928773a): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,07-07 20:26:09.629  5726  5852 D jxcore_app_log: JniHelper::setJavaVM(0xab1cd7b8), pthread_self() = -1404109648,
,07-07 20:26:09.639   966  1734 I ActivityManager: Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=5935 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a
,07-07 20:26:09.639  5726  5852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: ,
07-07 20:26:09.639  5726  5852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-07 20:26:09.639  5726  5852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-07 20:26:09.639  5726  5852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-07 20:26:09.639  5726  5852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-07 20:26:09.639  5726  5852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fa51c9c added. We now have 1 listener(s)
,07-07 20:26:09.649   966  1270 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-07 20:26:09.659  5726  5852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 90:E7:C4:F6:69:77
,07-07 20:26:09.659  5726  5852 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "90:E7:C4:F6:69:77"
,07-07 20:26:09.659  5726  5852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-07 20:26:09.659  5726  5852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-07 20:26:09.659  5914  5914 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-07 20:26:09.679  5726  5852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-07 20:26:09.679  5726  5852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-07 20:26:09.679  5726  5852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-07 20:26:09.679  5726  5852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 90:E7:C4:F6:69:77
07-07 20:26:09.679  5726  5852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-07 20:26:09.679  5726  5852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-07 20:26:09.679  5726  5852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-07 20:26:09.679  5726  5852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-07 20:26:09.679  5726  5852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-07 20:26:09.679  5726  5852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-07 20:26:09.679  5726  5852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-07 20:26:09.679  5726  5852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3feff22b added. We now have 1 listener(s)
07-07 20:26:09.679  5726  5852 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-07 20:26:09.699   966  1262 D WifiService: New client listening to asynchronous messages
,07-07 20:26:09.699   966   966 E WifiTrafficPoller: ADD_CLIENT: 8
07-07 20:26:09.699   966  1746 D Process : killProcessQuiet, pid=5359
07-07 20:26:09.699   966  1746 I ActivityManager: Killing 5359:com.google.android.apps.magazines/u0a161 (adj 15): empty #17
07-07 20:26:09.699   966  1746 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-07 20:26:09.709  5726  5852 D BluetoothAdapter: 1011527177: getState(). Returning 12
07-07 20:26:09.709  5726  5852 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
07-07 20:26:09.709  5726  5852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-07 20:26:09.719  5726  5852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-07 20:26:09.719  5726  5852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-07 20:26:09.719  5726  5852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-07 20:26:09.739  1600  1901 E Prism.WidgetManager: The same lists. No need to update. skip it.,
07-07 20:26:09.739  1600  1901 I Prism.WidgetManager: onLoadItems() -
07-07 20:26:09.739  1600  1901 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@7f6d2e9 -
,07-07 20:26:09.759   966  1261 E WifiStateMachine: handleMessage: E msg.what=131165,
,07-07 20:26:09.759   966  1261 E WifiStateMachine: processMsg: ConnectedState
,07-07 20:26:09.769   966  1261 E WifiStateMachine:  ConnectedState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0,
07-07 20:26:09.769   966  1261 E WifiStateMachine: processMsg: L2ConnectedState
07-07 20:26:09.769   966  1261 E WifiStateMachine:  L2ConnectedState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
07-07 20:26:09.769   966  1261 E WifiStateMachine: processMsg: ConnectModeState
07-07 20:26:09.769   966  1261 E WifiStateMachine:  ConnectModeState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
07-07 20:26:09.769   966  1261 E WifiStateMachine: processMsg: DriverStartedState
07-07 20:26:09.769   966  1261 E WifiStateMachine:  DriverStartedState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
07-07 20:26:09.769   966  1261 E WifiStateMachine: processMsg: SupplicantStartedState
,07-07 20:26:09.769   966  1261 E WifiStateMachine:  SupplicantStartedState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
07-07 20:26:09.769   966  1261 E WifiStateMachine: processMsg: DefaultState
,07-07 20:26:09.769   966  1261 E WifiStateMachine:  DefaultState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,07-07 20:26:09.769   966  1261 E WifiStateMachine: handleMessage: X
,07-07 20:26:09.769  5914  5914 I MultiDex: VM with version 2.1.0 has multidex support,
07-07 20:26:09.769  5914  5914 I MultiDex: install
,07-07 20:26:09.769  5914  5914 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-07 20:26:09.839   966  1734 I ActivityManager: Recipient 5359
,07-07 20:26:09.909  5880  5911 I PowerUsageList:PowerUsageHelper: calcPower(), PowerProfile::POWER_SCREEN_FULL = 154.8
,07-07 20:26:09.909  5726  5852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-07 20:26:09.919   966   985 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-07 20:26:09.929  5726  5852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 90:E7:C4:F6:69:77
,07-07 20:26:09.939  5726  5852 D BluetoothAdapter: 1011527177: getState(). Returning 12
,07-07 20:26:09.939  5726  5852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:26:09.939  5726  5852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:26:09.939  5726  5852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:26:09.939  5726  5852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:26:09.939  5726  5852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:26:09.939  5726  5852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-07 20:26:09.939  5726  5852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-07 20:26:09.939  5726  5852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-07 20:26:09.939  5726  5852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,07-07 20:26:09.939  5726  5852 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-07 20:26:09.939  5726  5852 I io.jxcore.node.LifeCycleMonitor: start: OK,
07-07 20:26:09.939  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,07-07 20:26:09.949  5880  5911 D PowerUtils: getUserIdOfProcess, curUserId = 0
,07-07 20:26:09.949  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:26:09.959  5880  5911 D PowerUsageList:PowerUsageHelper: calcPower(), skip because sipper.cpuTime = 0, sipper.uId = 10017, sipper.name = android.process.media,
07-07 20:26:09.959  5880  5911 D PowerUsageList:PowerUsageHelper: calcPower(), skip because sipper.cpuTime = 0, sipper.uId = 10024, sipper.name = com.google.android.gms.persistent
07-07 20:26:09.959  5880  5911 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0
,07-07 20:26:09.969  5880  5911 D PowerUsageList:PowerUsageHelper: calcPower(), skip because sipper.cpuTime = 0, sipper.uId = 1000, sipper.name = com.android.settings:remote,
07-07 20:26:09.969  5880  5911 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0,
,07-07 20:26:09.979  5935  5935 I EASAppSvc: [ NA ]onCreate,
,07-07 20:26:09.989  5880  5911 D PowerUsageList:PowerUsageHelper: calcPower(), skip because sipper.cpuTime = 0, sipper.uId = 10041, sipper.name = com.htc.dotmatrixevent
,07-07 20:26:09.989  5935  5964 I VersionUtil: [ NA ]setIsFOTAing: true,
,07-07 20:26:09.999  5935  5964 I VersionUtil: [ NA ]onUpgrade: current version=100, latest version=100,
07-07 20:26:10.009  5726  5726 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-07 20:26:10.009  5935  5964 I VersionUtil: [ NA ]setIsFOTAing: false
,07-07 20:26:10.019  3251  3350 I HtcModeClient: handler message = 4011
07-07 20:26:10.019  3251  3350 E HtcModeClient: Check connection and retry 6 times.
,07-07 20:26:10.049   966   985 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=5968 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
07-07 20:26:10.049   966  1270 I ActivityManager: Cannot resolve ContentProvider=com.aiqidii.mercury.provider
07-07 20:26:10.049  5914  5963 E ActivityThread: Failed to find provider info for com.aiqidii.mercury.provider
07-07 20:26:10.059  5623  5965 D ORMLib  : put()
,07-07 20:26:10.059  5914  5963 E MediaManager: [PPClientWrapper]	 (isPPLogin) has an exception
07-07 20:26:10.069  5935  5964 D HtcAdjCursorFactory: Set CursorWindow size to: 4194304 KB, Tid: 5964
,07-07 20:26:10.079  5914  5963 E MediaManager: [PPClientWrapper]	PP Error code:1, Error msg:Unknown URI content://com.aiqidii.mercury.provider
,07-07 20:26:10.089   966  1792 D Process : killProcessQuiet, pid=5390,
07-07 20:26:10.089   966  1792 I ActivityManager: Killing 5390:com.htc.mobiledata:remote/u0a46 (adj 15): empty #17
07-07 20:26:10.089   966  1792 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-07 20:26:10.159  5880  5911 D PowerUsageService: calcPower(), no data,
,07-07 20:26:10.219   966  1533 I ActivityManager: Recipient 5390
,07-07 20:26:10.309   966  1794 I ActivityManager: Waited long enough for: ServiceRecord{2540649a u0 com.htc.club/com.mcrm.autonotification.NotificationService}
07-07 20:26:10.309   966  1250 V AlarmManager: sending alarm PendingIntent{22e6425d: PendingIntentRecord{3530c7d2 android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1467915969751, Int=20000
,07-07 20:26:10.319   966  1795 D Process : killProcessQuiet, pid=5417
07-07 20:26:10.319   966  1795 I ActivityManager: Killing 5417:com.htc.mobiledata/u0a46 (adj 15): empty #17
07-07 20:26:10.319   966  1795 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-07 20:26:10.349  5914  5967 E SQLiteLog: (283) recovered 15 frames from WAL file /data/data/com.htc.album/databases/MMexternal.db-wal
,07-07 20:26:10.419  5968  5968 I MusicStore: Database version: 120,
,07-07 20:26:10.449   966  1541 I ActivityManager: Recipient 5417
,07-07 20:26:10.529   966  1250 V AlarmManager: sending alarm PendingIntent{9d0e481: PendingIntentRecord{1056c926 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1467915970213, Int=0
,07-07 20:26:10.539   966   966 E WifiTrafficPoller: ADD_CLIENT: 9,
07-07 20:26:10.539   966  1262 D WifiService: New client listening to asynchronous messages
,07-07 20:26:10.549   966   966 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 9
07-07 20:26:10.549   966   966 E WifiTrafficPoller:  packet count Tx=215 Rx=352
07-07 20:26:10.549   966   966 E WifiTrafficPoller: notifying of data activity 1
,07-07 20:26:10.549  1335  1335 D WIFI_ICON: WifiActivity: 1
07-07 20:26:10.549  1335  1335 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,07-07 20:26:10.569   966  1795 D Process : killProcessQuiet, pid=5473,
07-07 20:26:10.569   966  1795 I ActivityManager: Killing 5473:com.android.chrome/u0a96 (adj 15): empty #17
07-07 20:26:10.569   966  1795 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-07 20:26:10.659   966  1734 I ActivityManager: Recipient 5473
,07-07 20:26:10.669   966   966 E WifiDataStallTracker: DATA_MONITOR_POLL true Token 1
,07-07 20:26:10.679   966  6001 D WifiDataStallTracker: updateDataStallInfo: mDataStallTxRxSum={txSum=194 rxSum=204} preTxRxSum={txSum=182 rxSum=196}
07-07 20:26:10.679   966  6001 D WifiDataStallTracker: updateDataStallInfo: IN/OUT
07-07 20:26:10.679   966  6001 D WifiDataStallTracker: onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,07-07 20:26:10.679   966  1795 D Process : killProcessQuiet, pid=5173
07-07 20:26:10.679   966  1795 I ActivityManager: Killing 5173:com.google.android.gms.wearable/u0a24 (adj 15): empty #17
07-07 20:26:10.679   966  1795 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-07 20:26:10.709  5726  5961 W jxcore-log: Initializing JXcore engine,
07-07 20:26:10.709  5726  5961 W jxcore-log: JXcore engine is ready
,07-07 20:26:10.789  5726  5961 W jxcore-log: Starting JXcore engine,
,07-07 20:26:10.799   966  1792 I ActivityManager: Recipient 5173
,07-07 20:26:10.909  5935  5935 I EASAppSvc: [ NA ]onDestroy,
07-07 20:26:10.909  5935  5964 I EASAppSvc: [ NA ]> uninitEASService
07-07 20:26:10.909  5935  5964 I EASRequestController: [ NA ]release
07-07 20:26:10.909  5935  5935 I EASAppSvc: [ NA ]onCreate
,07-07 20:26:10.919  5726  5961 W jxcore-log: Platform android
07-07 20:26:10.919  5726  5961 W jxcore-log: 
,07-07 20:26:10.919  5726  5961 W jxcore-log: Process ARCH arm
07-07 20:26:10.919  5726  5961 W jxcore-log: 
,07-07 20:26:10.929  5935  6006 I VersionUtil: [ NA ]setIsFOTAing: true
,07-07 20:26:10.929  5935  6006 I VersionUtil: [ NA ]onUpgrade: current version=100, latest version=100,
07-07 20:26:10.929  5935  6006 I VersionUtil: [ NA ]setIsFOTAing: false
07-07 20:26:10.939  5935  5964 D EASPublicBinder: [ NA ]release
07-07 20:26:10.939  5935  5964 D TaskBinder: [ NA ]release,
07-07 20:26:10.939  5935  5964 D TaskBinder: [ NA ]release
07-07 20:26:10.939  5935  5964 I EASAppSvc: [ NA ]< uninitEASService
,07-07 20:26:10.949  5623  6007 D ORMLib  : put(),
07-07 20:26:10.949   966  1533 D VoldConnector: SND -> {25 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
,07-07 20:26:10.949   385   602 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
07-07 20:26:10.949  5968  5968 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,07-07 20:26:10.989  5935  5935 I EASAppSvc: [ NA ]onDestroy,
,07-07 20:26:10.989  5935  6006 I EASAppSvc: [ NA ]> uninitEASService
07-07 20:26:10.989  5935  6006 I EASRequestController: [ NA ]release
,07-07 20:26:11.009   966  1270 I ActivityManager: Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=6015 uid=10066 gids={50066, 9997, 3003} abi=arm64-v8a
,07-07 20:26:11.009  5935  6006 D EASPublicBinder: [ NA ]release
07-07 20:26:11.009  5935  6006 D TaskBinder: [ NA ]release
07-07 20:26:11.009  5935  6006 D TaskBinder: [ NA ]release
07-07 20:26:11.009  5935  6006 I EASAppSvc: [ NA ]< uninitEASService
,07-07 20:26:11.019   966  1734 D VoldConnector: SND -> {26 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
07-07 20:26:11.019  5968  5968 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
07-07 20:26:11.019   385   602 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
07-07 20:26:11.019   966  1533 D VoldConnector: SND -> {27 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
07-07 20:26:11.019   385   602 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
07-07 20:26:11.019  5968  5968 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,07-07 20:26:11.109  5726  5961 I jxcore-log: JXcore Cordova bridge is ready!,
07-07 20:26:11.109  5726  5961 I jxcore-log: 
07-07 20:26:11.109  5726  5961 W jxcore-log: JXcore engine is started
,07-07 20:26:11.119  5726  5852 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION,
07-07 20:26:11.119  5726  5726 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-07 20:26:11.129  5726  5961 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
07-07 20:26:11.129  5726  5961 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,07-07 20:26:11.139  5726  5726 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,07-07 20:26:11.139  5726  5726 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,07-07 20:26:11.169   966  1746 I art     : Explicit concurrent mark sweep GC freed 21339(1153KB) AllocSpace objects, 4(336KB) LOS objects, 33% free, 16MB/25MB, paused 1.299ms total 128.524ms
,07-07 20:26:11.209  5726  5726 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-07 20:26:11.209  5726  5726 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,07-07 20:26:11.209   966   986 D PMS     : acquireWL(3a26ac29): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 966 1000 null
07-07 20:26:11.219  5726  5852 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 71ms. Plugin should use CordovaInterface.getThreadPool().
,07-07 20:26:11.219   966  1646 W HtcSystemUPManager: HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,07-07 20:26:11.239  1600  1600 I FeedHostManager: [onResume]
07-07 20:26:11.239  1600  1600 I FeedProviderManager: onResume
07-07 20:26:11.239  1600  2659 I SocialFeedProvider: +onResume
07-07 20:26:11.239  1600  2659 I SocialFeedProvider: updateAccounts - Accounts is no change
07-07 20:26:11.239  1600  2659 I SocialFeedProvider: -onResume
,07-07 20:26:11.249  1600  1600 I ContextualWidget: onResume
07-07 20:26:11.249  1600  1600 I ContextualWidget: notifyWidgetActive location size=0 user consent location=false
07-07 20:26:11.249  1600  1600 W SystemReader: Cannot find enable_suggestion_option, use default value instead
07-07 20:26:11.249  1600  1922 I ContextualWidget: handleMessage, what=1018 mode=GettingOut maxcount=8
07-07 20:26:11.249  1600  1600 I ContextualWidget: ignore uploadUsageData location=false usage data=false allowAutoUpload=true
07-07 20:26:11.249  1600  1600 W SystemReader: Cannot find enable_suggestion_option, use default value instead
,07-07 20:26:11.249  1600  1600 I ContextualWidget: postSyncRecommendedApps, isReady=false allowAutoSync=true syncMode=1 isEnableRecommend=true
,07-07 20:26:11.249  5968  5968 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,07-07 20:26:11.249   966  1794 D Process : killProcessQuiet, pid=4404
07-07 20:26:11.249  5968  5968 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
07-07 20:26:11.249   966  1794 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
07-07 20:26:11.249   966  1794 I ActivityManager: Killing 4404:com.android.defcontainer/u0a15 (adj 15): empty #17
,07-07 20:26:11.259   966  1037 D StatusBarManagerService: setSystemUiVisibility(0x8700)
,07-07 20:26:11.259   966  1037 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-07 20:26:11.259   966  1037 D StatusBarManagerService: hiding MENU key
07-07 20:26:11.259  1600  1600 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
07-07 20:26:11.259  1600  1600 I ThreadedRenderer: Defer allocateBuffers to drawing time
,07-07 20:26:11.269   966  1791 I InputMethodManagerService: Disable input method client, pid=5726
07-07 20:26:11.269   966  1791 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
,07-07 20:26:11.269   966  1791 I InputMethodManagerService: Enable input method client, pid=1600
,07-07 20:26:11.269  5726  5726 W IInputConnectionWrapper: reportFullscreenMode on inactive InputConnection
07-07 20:26:11.269  1335  1335 I PhoneStatusBar: setImeWindowStatus(false,false)
,07-07 20:26:11.279  5623  6042 D ORMLib  : put(),
,07-07 20:26:11.309   966  1037 D StatusBarManagerService: setSystemUiVisibility(0xc0000700)
,07-07 20:26:11.309   966  1037 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-07 20:26:11.309   966  1037 D StatusBarManagerService: hiding MENU key
,07-07 20:26:11.349   966  1271 I ActivityManager: Recipient 4404
,07-07 20:26:11.359   966  1734 D PMS     : releaseWL(3a26ac29): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,07-07 20:26:11.379   966  1026 D Process : killProcessQuiet, pid=5499,
,07-07 20:26:11.379   966  1026 I ActivityManager: Killing 5499:com.google.android.apps.plus/u0a167 (adj 15): empty #17
,07-07 20:26:11.379   966  1026 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityStack.destroyActivityLocked:3435 
,07-07 20:26:11.399  5968  5968 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,07-07 20:26:11.459  5968  5968 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,07-07 20:26:11.469  5968  5968 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@16723c18: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
07-07 20:26:11.469  5968  5968 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
07-07 20:26:11.469  5968  5968 D AndroidMusic: GMSCore installation verified
,07-07 20:26:11.519   966  1794 I ActivityManager: Recipient 5499
,07-07 20:26:11.549   966   966 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 9,
07-07 20:26:11.549   966   966 E WifiTrafficPoller:  packet count Tx=215 Rx=352
,07-07 20:26:11.549   966   966 E WifiTrafficPoller: notifying of data activity 0
07-07 20:26:11.549  1335  1335 D WIFI_ICON: WifiActivity: 0
,07-07 20:26:11.549  1335  1335 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,07-07 20:26:11.599  5726  5726 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-07 20:26:11.599  5726  5726 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
07-07 20:26:11.599  5726  5726 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,07-07 20:26:11.599  5726  5726 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
07-07 20:26:11.599  5726  5726 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:26:11.599  5726  5726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:26:11.599  5726  5726 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:26:11.599  5726  5726 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-07 20:26:11.599  5726  5726 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fa51c9c removed from the list
07-07 20:26:11.599  5726  5726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-07 20:26:11.599  5726  5726 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3feff22b removed from the list
07-07 20:26:11.599  5726  5726 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:26:11.599  5726  5726 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,07-07 20:26:11.609  5968  5968 I ConfigStore: Config Database version: 1,
,07-07 20:26:11.609  5726  5726 I io.jxcore.node.LifeCycleMonitor: stop: OK,
,07-07 20:26:11.609   966  1791 I ActivityManager: Killing 5540:com.htc.calendar/u0a10 (adj 15): empty #17
07-07 20:26:11.609   966  1791 D Process : killProcessQuiet, pid=5540
07-07 20:26:11.619   966  1791 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-07 20:26:11.639  6039  6045 E cutils-trace: Error opening trace file: Permission denied (13)
,07-07 20:26:11.749   966  1533 I ActivityManager: Recipient 5540,
,07-07 20:26:11.769  6039  6039 D CustomizationManager: ====startRecUseTime====,
07-07 20:26:11.769  6039  6039 D htc.customization.log.level:  is ,
07-07 20:26:11.769  6039  6039 W CustomizationLogLevel: Level value is invalid, use default level 2,
,07-07 20:26:11.799  1600  2179 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...,
,07-07 20:26:11.879  6039  6039 D CustomizationManager:  Read ACC file spent 0.062 (s),
,07-07 20:26:11.879  6039  6039 D CIDMapFileReader: Parsing tag item name = HTC__001,
,07-07 20:26:11.879  6039  6039 D CIDMapFileReader: Parsing tag item name = HTC__102
07-07 20:26:11.879  6039  6039 D CIDMapFileReader: Parsing tag item name = HTC__Y13
07-07 20:26:11.879  6039  6039 D CIDMapFileReader: Parsing tag item name = HTC__032
07-07 20:26:11.879  6039  6039 D CIDMapFileReader: Parsing tag item name = HTC__M27,
07-07 20:26:11.879  6039  6039 D CIDMapFileReader: Parsing tag item name = HTC__002
07-07 20:26:11.879  6039  6039 D CIDMapFileReader: Parsing tag item name = HTC__031
07-07 20:26:11.879  6039  6039 D CIDMapFileReader: Parsing tag item name = HTC__A07
07-07 20:26:11.879  6039  6039 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__102.xml
07-07 20:26:11.879  6039  6039 I CustomizationCIDLoader: Parsing tag category name = system
,07-07 20:26:11.879  6039  6039 I CustomizationCIDLoader: Parsing tag category name = application,
,07-07 20:26:11.889  6039  6039 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider,
07-07 20:26:11.889  6039  6039 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome,
07-07 20:26:11.889  6039  6039 I CustomizationCIDLoader: Parsing tag category name = AudioService
,07-07 20:26:11.889  6039  6039 I CustomizationCIDLoader: Parsing tag category name = Settings
,07-07 20:26:11.889  6039  6039 I CustomizationCIDLoader: Parsing tag category name = ACC
,07-07 20:26:11.889  6039  6039 I CustomizationCIDLoader: add string-array item, value = 42507,
07-07 20:26:11.889  6039  6039 I CustomizationCIDLoader: add string-array item, value = 21902
,07-07 20:26:11.889  6039  6039 I CustomizationCIDLoader: add string-array item, value = 26006:26001.26002.26003
07-07 20:26:11.889  6039  6039 I CustomizationCIDLoader: add string-array item, value = 23420
,07-07 20:26:11.889  6039  6039 I CustomizationCIDLoader: add string-array item, value = 22299
07-07 20:26:11.889  6039  6039 I CustomizationCIDLoader: add string-array item, value = 24002
07-07 20:26:11.889  6039  6039 I CustomizationCIDLoader: add string-array item, value = 23210
,07-07 20:26:11.889  6039  6039 I CustomizationCIDLoader: add string-array item, value = 23205
07-07 20:26:11.889  6039  6039 I CustomizationCIDLoader: add string-array item, value = 23806
07-07 20:26:11.889  6039  6039 I CustomizationCIDLoader: add string-array item, value = 23430
,07-07 20:26:11.889  6039  6039 I CustomizationCIDLoader: add string-array item, value = 23408
07-07 20:26:11.889  6039  6039 I CustomizationCIDLoader: add string-array item, value = 27205
07-07 20:26:11.889  6039  6039 I CustomizationCIDLoader: add string-array item, value = 42507:C:1:0
07-07 20:26:11.889  6039  6039 I CustomizationCIDLoader: add string-array item, value = 21902:C:1:0
07-07 20:26:11.889  6039  6039 I CustomizationCIDLoader: add string-array item, value = 26006:D:1:0
,07-07 20:26:11.889  6039  6039 I CustomizationCIDLoader: add string-array item, value = 23420:D:0:0
07-07 20:26:11.889  6039  6039 I CustomizationCIDLoader: add string-array item, value = 22299:D:0:0
07-07 20:26:11.889  6039  6039 I CustomizationCIDLoader: add string-array item, value = 24002:D:0:0
07-07 20:26:11.889  6039  6039 I CustomizationCIDLoader: add string-array item, value = 23210:D:2:0
07-07 20:26:11.889  6039  6039 I CustomizationCIDLoader: add string-array item, value = 23205:D:2:0
07-07 20:26:11.889  6039  6039 I CustomizationCIDLoader: add string-array item, value = 23806:D:0:0,
07-07 20:26:11.889  6039  6039 I CustomizationCIDLoader: add string-array item, value = 23430:C:1:0
07-07 20:26:11.889  6039  6039 I CustomizationCIDLoader: add string-array item, value = 23408:C:1:0
07-07 20:26:11.889  6039  6039 I CustomizationCIDLoader: add string-array item, value = 27205:C:1:0
07-07 20:26:11.889  6039  6039 D CustomizationManager:  Read CID file spent 0.124 (s)
07-07 20:26:11.889  6039  6039 D CustomizationManager:  All configurations done spent 0.124 (s)
,07-07 20:26:11.909   966  1791 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=5968, uid=10159, userID:0,
,07-07 20:26:11.929   966  1793 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
07-07 20:26:11.929   966  1793 D WifiDisplayAdapter:     Client/Owner: Client
07-07 20:26:11.929   966  1793 D WifiDisplayAdapter:     GroupId: 
07-07 20:26:11.929   966  1793 D WifiDisplayAdapter:     Passphrase: 
07-07 20:26:11.929   966  1793 D WifiDisplayAdapter:     SessionId: 0
07-07 20:26:11.929   966  1793 D WifiDisplayAdapter:     IP Address: }
,07-07 20:26:11.929   966  1541 D MediaRouterService: Client com.google.android.music (pid 5968): Registered
,07-07 20:26:11.939   966  1533 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
07-07 20:26:11.939   966  1533 D WifiDisplayAdapter:     Client/Owner: Client
07-07 20:26:11.939   966  1533 D WifiDisplayAdapter:     GroupId: 
07-07 20:26:11.939   966  1533 D WifiDisplayAdapter:     Passphrase: 
07-07 20:26:11.939   966  1533 D WifiDisplayAdapter:     SessionId: 0
07-07 20:26:11.939   966  1533 D WifiDisplayAdapter:     IP Address: }
,07-07 20:26:11.939  5968  5968 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android },
,07-07 20:26:11.949  1560  1560 D TelephonyReceiver: bind: true,
07-07 20:26:11.959   966   986 D PackageManager: deletePackageAsUser: pkg=com.test.thalitest, pid=6039, uid=2000 userid=0
07-07 20:26:11.959  5968  5968 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,07-07 20:26:11.979   966  1541 I ActivityManager: Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=6062 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=arm64-v8a
,07-07 20:26:11.979   966  1026 I ActivityManager: Force stopping com.test.thalitest appid=10195 user=-1: uninstall pkg
,07-07 20:26:11.979   966  1026 D Process : killProcessQuiet, pid=5726
07-07 20:26:11.979   966  1026 I ActivityManager: Killing 5726:com.test.thalitest/u0a195 (adj 9): stop com.test.thalitest
07-07 20:26:11.979   966  1026 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6372 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
,07-07 20:26:12.009   966  1261 E WifiStateMachine: handleMessage: E msg.what=131155
,07-07 20:26:12.009   966  1261 E WifiStateMachine: processMsg: ConnectedState
07-07 20:26:12.009   966  1261 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=150 tx=12.7, 0.0, 0.0  rx=17.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-962843214] gl hn u24 rssi=-51 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-07 20:26:12.009   966  1261 E WifiStateMachine: processMsg: L2ConnectedState
07-07 20:26:12.009   966  1261 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=150 tx=12.7, 0.0, 0.0  rx=17.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-962843213] gl hn u24 rssi=-51 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-07 20:26:12.009   966  1261 E WifiStateMachine:  get link layer stats 0
07-07 20:26:12.009   966  1261 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
07-07 20:26:12.019  1456  1456 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
,07-07 20:26:12.019  1456  1456 I wpa_supplicant: environment dirty rate=0 [0][0][0]
07-07 20:26:12.019   966  1261 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 150
07-07 20:26:12.019   966  1261 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-56 linkspeed=150
07-07 20:26:12.019   966  1261 E WifiConfigStore: updateConfiguration freq=2447 BSSID=f4:f2:6d:22:99:3e RSSI=-56 "NG700"WPA_PSK
07-07 20:26:12.019   966  1261 E WifiStateMachine: calculateWifiScore freq=2447 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=6.35 txretriesrate=0.00 rxrate=9.73 userTriggerdPenalty0
07-07 20:26:12.019   966  1182 W PackageSettings: Skipping PackageSetting{2d16ec9e com.example.hello/10374} due to missing metadata
07-07 20:26:12.019   966  1261 E WifiStateMachine:  good link -> stuck count =0
07-07 20:26:12.019   966  1261 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 60
07-07 20:26:12.019   966  1261 E WifiStateMachine:  isHighRSSI       ---> score=65
07-07 20:26:12.039   966  1732 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=2194, uid=10024, userID:0
07-07 20:26:12.039   966  1793 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=2194, uid=10024, userID:0
07-07 20:26:12.039   966  1270 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=2194, uid=10024, userID:0
07-07 20:26:12.039  2194  4563 I CheckinService: Done disabling old GoogleServicesFramework version
,07-07 20:26:12.129   966  1795 I ActivityManager: Recipient 5726,
07-07 20:26:12.129  1501  1501 E InputEventReceiver: Looper::removeFd(68) is failed, result(0), input channel 'ClientState{1744edfa uid 10195 pid 5726} (c)'
07-07 20:26:12.129   966  1262 D WifiService: Client connection lost with reason: 4
,07-07 20:26:12.189   966  1026 W ActivityManager: ProcessRecord{1177b30d 5726:com.test.thalitest/u0a195} has been replaced to new process null
,07-07 20:26:12.209   966  1533 I ActivityManager: Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.GenericMessagesProvider: pid=6083 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
07-07 20:26:12.219   966  1286 D WifiWatchdogStateMachine: RSSI current: 3 new: -56, 3
07-07 20:26:12.219   966  1182 I ActivityManager: Force stopping com.test.thalitest appid=10195 user=0: pkg removed
07-07 20:26:12.219   966  1261 E WifiStateMachine: handleMessage: X
07-07 20:26:12.219  1335  1335 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
07-07 20:26:12.219  1335  1335 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,07-07 20:26:12.239   966  1795 W ActivityManager: Spurious death for ProcessRecord{1177b30d 0:com.test.thalitest/u0a195}, curProc for 5726: null
,07-07 20:26:12.249  1427  1427 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest,
07-07 20:26:12.249  1427  1427 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
07-07 20:26:12.259   966  1734 D PMS     : acquireWL(29797309): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1850 10024 WorkSource{10024 com.google.android.gms}
,07-07 20:26:12.269  1850  2256 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-07 20:26:12.279   966  1252 W SystemReader: Cannot find grip_rejection_width, use default value instead,
07-07 20:26:12.279  1744  2110 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
07-07 20:26:12.279   966  1794 D PMS     : releaseWL(29797309): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,07-07 20:26:12.279   966  1258 V NetworkPolicy: ACTION_UID_REMOVED for uid=10195
,07-07 20:26:12.279   966  1258 V NetworkPolicy: writePolicyLocked()
,07-07 20:26:12.289   966  1257 D PMS     : acquireWL(27bd36c5): PARTIAL_WAKE_LOCK  NetworkStats 0x1 966 1000 null
,07-07 20:26:12.289  1744  2110 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana,
,07-07 20:26:12.309  6062  6062 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,07-07 20:26:12.319   966  1258 V NetworkPolicy: updateNetworkEnabledLocked()
07-07 20:26:12.319   966  1258 V NetworkPolicy: updateNotificationsLocked()
,07-07 20:26:12.339  6062  6106 I DFPI.ApkInstallService: onHandleIntent
07-07 20:26:12.339  6062  6106 I DFPI.ApkInstallService: Media Scan Finished Case 
,07-07 20:26:12.339  6062  6106 D DFPI.ApkInstallService: check CID = HTC__102,
07-07 20:26:12.339  6062  6106 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
,07-07 20:26:12.339  1744  2110 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,07-07 20:26:12.349   966  1791 I ActivityManager: Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=6108 uid=10049 gids={50049, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,07-07 20:26:12.359  1560  1560 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
07-07 20:26:12.369   966  1024 I InputMethodManagerService: [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
07-07 20:26:12.369   966  1257 D PMS     : releaseWL(27bd36c5): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
07-07 20:26:12.369  6083  6083 W HtcWrapAdjustableCursorFactory: HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.
07-07 20:26:12.369  6083  6083 D MessageFrequencyProvider: onCreate
,07-07 20:26:12.379  1744  2110 E ExternalAccountType: Unsupported attribute readOnly
,07-07 20:26:12.379  6083  6083 V GetPrviateResource: GetPrviateResource
07-07 20:26:12.379  6083  6083 V GetPrviateResource: GetPrviateResource
07-07 20:26:12.379  6083  6103 D GenericMessagesProvider: query uri: content://htc-messages/wappush/count
07-07 20:26:12.379  5968  5968 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,07-07 20:26:12.389  6083  6083 D MessageCustFlag: sense_version=6.0
07-07 20:26:12.399  6083  6103 E SQLiteLog: (14) cannot open file at line 30058 of [9491ba7d73]
07-07 20:26:12.399  6083  6103 E SQLiteLog: (14) os_unix.c:30058: (2) open(/data/data/com.htc.sense.mms/databases/wappush.db) - 
07-07 20:26:12.399  6083  6103 E SQLiteConnection: DB info: sqlite3_open_v2, path: /data/data/com.htc.sense.mms/databases/wappush.db, flag: 1, ret: 14
07-07 20:26:12.399  6083  6103 E SQLiteConnection: DB info: errno = 2, errno message = No such file or directory
07-07 20:26:12.399  6083  6083 D BTAccessoryUtil: createReceiver,
07-07 20:26:12.399  6083  6083 D BTAccessoryUtil: registerReceiver return intent = null
07-07 20:26:12.399  6083  6083 D MessageCustFlag: sku_id=118
,07-07 20:26:12.409  6083  6103 E SQLiteDatabase: Failed to open database '/data/data/com.htc.sense.mms/databases/wappush.db'.
07-07 20:26:12.409  6083  6103 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
07-07 20:26:12.409  6083  6103 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-07 20:26:12.409  6083  6103 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-07 20:26:12.409  6083  6103 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-07 20:26:12.409  6083  6103 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-07 20:26:12.409  6083  6103 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-07 20:26:12.409  6083  6103 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-07 20:26:12.409  6083  6103 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
07-07 20:26:12.409  6083  6103 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
07-07 20:26:12.409  6083  6103 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
07-07 20:26:12.409  6083  6103 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:712)
07-07 20:26:12.409  6083  6103 E SQLiteDatabase: 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
07-07 20:26:12.409  6083  6103 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:960)
07-07 20:26:12.409  6083  6103 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
07-07 20:26:12.409  6083  6103 E SQLiteDatabase: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
07-07 20:26:12.409  6083  6103 E SQLiteDatabase: 	at android.os.Binder.execTransact(Binder.java:454)
07-07 20:26:12.409  6083  6083 D HtcBuildUtils: getRATByHtcTelephonyCapability:1
07-07 20:26:12.409  6083  6103 W System.err: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
07-07 20:26:12.409  6083  6103 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-07 20:26:12.409  6083  6103 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-07 20:26:12.409  6083  6103 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
,07-07 20:26:12.409  6083  6103 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-07 20:26:12.409  6083  6103 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-07 20:26:12.409  6083  6103 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-07 20:26:12.409  6083  6103 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
07-07 20:26:12.409  6083  6103 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
07-07 20:26:12.409  6083  6103 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
07-07 20:26:12.409  6083  6103 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:712)
07-07 20:26:12.409  6083  6103 W System.err: 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
07-07 20:26:12.409  6083  6103 W System.err: 	at android.content.ContentProvider.query(ContentProvider.java:960)
07-07 20:26:12.409  6083  6103 W System.err: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
07-07 20:26:12.409  6083  6103 W System.err: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
07-07 20:26:12.409  6083  6103 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
07-07 20:26:12.409  6083  6083 W SystemReader: Cannot find qct_8960_interface, use default value instead
07-07 20:26:12.409   966  1533 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=5968, uid=10159, userID:0
07-07 20:26:12.409  1560  1560 D TelephonyReceiver: switchBindHtcMsgCursor: null
07-07 20:26:12.429  5968  5968 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
07-07 20:26:12.429  5968  5968 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-07 20:26:12.449   966   966 W PackageManager: Unable to load service info ResolveInfo{15319815 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
,07-07 20:26:12.449   966   966 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
07-07 20:26:12.449   966   966 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
07-07 20:26:12.449   966   966 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
07-07 20:26:12.449   966   966 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
07-07 20:26:12.449   966   966 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
07-07 20:26:12.449   966   966 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169),
07-07 20:26:12.449   966   966 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
07-07 20:26:12.449   966   966 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
07-07 20:26:12.449   966   966 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-07 20:26:12.449   966   966 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
07-07 20:26:12.449   966   966 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:324)
07-07 20:26:12.449   966   966 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:225)
07-07 20:26:12.449   966   966 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
07-07 20:26:12.449   966   966 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-07 20:26:12.449   966   966 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
07-07 20:26:12.449   966   966 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,07-07 20:26:12.459   966  1024 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,07-07 20:26:12.479   966  1794 I ActivityManager: Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=6134 uid=10079 gids={50079, 9997, 5001, 1028, 1015} abi=arm64-v8a,
,07-07 20:26:12.519   966  1182 I art     : Explicit concurrent mark sweep GC freed 23681(2MB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 18MB/28MB, paused 2.166ms total 232.753ms
07-07 20:26:12.519  1964  2719 I art     : Explicit concurrent mark sweep GC freed 15048(769KB) AllocSpace objects, 3(252KB) LOS objects, 48% free, 4MB/8MB, paused 2.512ms total 57.052ms
,07-07 20:26:12.559   966  1271 I ActivityManager: Killing 5576:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17
07-07 20:26:12.559   966  1271 D Process : killProcessQuiet, pid=5576
,07-07 20:26:12.559   966  1271 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-07 20:26:12.569  6134  6134 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,07-07 20:26:12.579   966   986 I ActivityManager: Recipient 5576
,07-07 20:26:12.629   966   966 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED,
,07-07 20:26:12.659  6134  6134 I SoundPicker: SoundPickerReceiver [onReceive] startService
,07-07 20:26:12.669  1600  1901 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,07-07 20:26:12.669  1600  1901 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,07-07 20:26:12.669  6134  6161 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
,07-07 20:26:12.669  6134  6161 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
07-07 20:26:12.669   966  1792 D VoldConnector: SND -> {28 volume mkdirs /storage/ext_sd/Android/data/com.htc.musicenhancer/cache/}
07-07 20:26:12.669  6134  6161 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
07-07 20:26:12.669   385   602 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.htc.musicenhancer/cache/
,07-07 20:26:12.669  6108  6159 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
,07-07 20:26:12.679  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-07 20:26:12.679   966  1182 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6162 uid=10015 gids={50015, 9997, 1028, 1015, 1023, 2001, 1035, 5001} abi=arm64-v8a
,07-07 20:26:12.689   966   966 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8,
,07-07 20:26:12.689   966  1026 W BroadcastQueue: Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_MEDIA due to registered receiver BroadcastFilter{3769a73e u0 ReceiverList{157a8bf9 6108 com.htc.musicenhancer/10049/u0 remote:193f72c0}}
07-07 20:26:12.689   966   966 E WifiTrafficPoller:  packet count Tx=215 Rx=355
07-07 20:26:12.689  1335  1335 D WIFI_ICON: WifiActivity: 1
07-07 20:26:12.689   966   966 E WifiTrafficPoller: notifying of data activity 1
07-07 20:26:12.689  1335  1335 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,07-07 20:26:12.699  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
07-07 20:26:12.699  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-07 20:26:12.699  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-07 20:26:12.699  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
07-07 20:26:12.699  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-07 20:26:12.699  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-07 20:26:12.699  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-07 20:26:12.699  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-07 20:26:12.699  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
,07-07 20:26:12.699  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-07 20:26:12.709  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-07 20:26:12.709  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-07 20:26:12.709  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-07 20:26:12.709  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
07-07 20:26:12.709  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
07-07 20:26:12.709  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
07-07 20:26:12.709  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
07-07 20:26:12.709  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
07-07 20:26:12.709  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
07-07 20:26:12.709  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
07-07 20:26:12.709  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
07-07 20:26:12.709  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-07 20:26:12.709  6134  6161 I SoundPicker: TurnFileToMediaUriService [checkFileExistence]
07-07 20:26:12.709  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-07 20:26:12.709  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
07-07 20:26:12.709  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-07 20:26:12.719   434   434 I art     : Explicit concurrent mark sweep GC freed 8685(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 208us total 32.068ms
,07-07 20:26:12.739  6062  6062 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED,
07-07 20:26:12.739   434   434 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 174us total 21.776ms
,07-07 20:26:12.749  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
07-07 20:26:12.749  6062  6185 I DFPI.ApkInstallService: onHandleIntent
07-07 20:26:12.749  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,07-07 20:26:12.749  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-07 20:26:12.749  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-07 20:26:12.749  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
07-07 20:26:12.749  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
07-07 20:26:12.749  6062  6185 I DFPI.ApkInstallService: Media Scan Finished Case 
07-07 20:26:12.749  6134  6134 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
07-07 20:26:12.759  6134  6134 I SoundPicker: SoundPickerReceiver [onReceive] startService
07-07 20:26:12.759  6062  6185 D DFPI.ApkInstallService: check CID = HTC__102
07-07 20:26:12.759  6062  6185 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
07-07 20:26:12.759   434   434 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 187us total 25.207ms
,07-07 20:26:12.769  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
,07-07 20:26:12.779  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-07 20:26:12.779  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-07 20:26:12.779  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
,07-07 20:26:12.779  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-07 20:26:12.779  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-07 20:26:12.779  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,07-07 20:26:12.789  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,07-07 20:26:12.789  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-07 20:26:12.789  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-07 20:26:12.789  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-07 20:26:12.789  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,07-07 20:26:12.789  6062  6062 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED,
,07-07 20:26:12.799  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,07-07 20:26:12.799  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,07-07 20:26:12.799  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
07-07 20:26:12.799  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-07 20:26:12.799  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-07 20:26:12.799  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,07-07 20:26:12.799  6062  6188 I DFPI.ApkInstallService: onHandleIntent,
07-07 20:26:12.799  6062  6188 I DFPI.ApkInstallService: Media Scan Finished Case 
07-07 20:26:12.809  6062  6188 D DFPI.ApkInstallService: check CID = HTC__102
07-07 20:26:12.809  6062  6188 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
,07-07 20:26:12.819  6134  6134 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,07-07 20:26:12.819  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,07-07 20:26:12.819  6134  6134 I SoundPicker: SoundPickerReceiver [onReceive] startService
,07-07 20:26:12.819  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
07-07 20:26:12.829  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
07-07 20:26:12.829  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6,
07-07 20:26:12.829  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,07-07 20:26:12.839  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,07-07 20:26:12.839  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac,
07-07 20:26:12.839  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
07-07 20:26:12.839  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
07-07 20:26:12.839  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,07-07 20:26:12.849  6062  6062 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED,
07-07 20:26:12.849  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,07-07 20:26:12.849  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac,
07-07 20:26:12.849  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
07-07 20:26:12.849  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
07-07 20:26:12.849  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,07-07 20:26:12.859  6062  6189 I DFPI.ApkInstallService: onHandleIntent,
07-07 20:26:12.859  6062  6189 I DFPI.ApkInstallService: Media Scan Finished Case 
07-07 20:26:12.859  6062  6189 D DFPI.ApkInstallService: check CID = HTC__102
07-07 20:26:12.859  6062  6189 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
07-07 20:26:12.859  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,07-07 20:26:12.859  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,07-07 20:26:12.859  6134  6134 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,07-07 20:26:12.859  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
07-07 20:26:12.869  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
07-07 20:26:12.869  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
07-07 20:26:12.869  6134  6134 I SoundPicker: SoundPickerReceiver [onReceive] startService
,07-07 20:26:12.869  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,07-07 20:26:12.879  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac,
07-07 20:26:12.879  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,07-07 20:26:12.879  6134  6161 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
07-07 20:26:12.879  6134  6161 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
07-07 20:26:12.879  6134  6161 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
07-07 20:26:12.879  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-07 20:26:12.879  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1,
07-07 20:26:12.879  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-07 20:26:12.879  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-07 20:26:12.879  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
07-07 20:26:12.879  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-07 20:26:12.879  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-07 20:26:12.879  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-07 20:26:12.879  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
,07-07 20:26:12.879  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-07 20:26:12.879  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-07 20:26:12.879  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-07 20:26:12.879  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-07 20:26:12.879  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-07 20:26:12.879  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
07-07 20:26:12.879  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
07-07 20:26:12.889  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
07-07 20:26:12.889  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
07-07 20:26:12.889  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
07-07 20:26:12.889  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
07-07 20:26:12.889  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
07-07 20:26:12.889  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
,07-07 20:26:12.889  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-07 20:26:12.889  6134  6161 I SoundPicker: TurnFileToMediaUriService [checkFileExistence]
07-07 20:26:12.889  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-07 20:26:12.889  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
07-07 20:26:12.889  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-07 20:26:12.889  1560  1560 D TelephonyReceiver: bind: false
07-07 20:26:12.889  1560  1560 D TelephonyReceiver: switchBindHtcMsgCursor: null
07-07 20:26:12.889  6062  6062 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
07-07 20:26:12.889  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,07-07 20:26:12.899  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-07 20:26:12.899  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-07 20:26:12.899  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-07 20:26:12.899  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
07-07 20:26:12.899  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-07 20:26:12.899  6062  6192 I DFPI.ApkInstallService: onHandleIntent
,07-07 20:26:12.899  6062  6192 I DFPI.ApkInstallService: Media Scan Finished Case 
,07-07 20:26:12.899  6062  6192 D DFPI.ApkInstallService: check CID = HTC__102
,07-07 20:26:12.909  6062  6192 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
07-07 20:26:12.909  6134  6134 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,07-07 20:26:12.909  6134  6134 I SoundPicker: SoundPickerReceiver [onReceive] startService,
,07-07 20:26:12.909  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,07-07 20:26:12.909  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac,
,07-07 20:26:12.909  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-07 20:26:12.909  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-07 20:26:12.909  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3,
07-07 20:26:12.909  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-07 20:26:12.919  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,07-07 20:26:12.919  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac,
07-07 20:26:12.919  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-07 20:26:12.919  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-07 20:26:12.919  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-07 20:26:12.929  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,07-07 20:26:12.929  6062  6062 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,07-07 20:26:12.929  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,07-07 20:26:12.939  6062  6193 I DFPI.ApkInstallService: onHandleIntent
07-07 20:26:12.939  6062  6193 I DFPI.ApkInstallService: Media Scan Finished Case 
07-07 20:26:12.939  6062  6193 D DFPI.ApkInstallService: check CID = HTC__102
07-07 20:26:12.939  6062  6193 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
,07-07 20:26:12.939  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,07-07 20:26:12.939  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
07-07 20:26:12.939  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-07 20:26:12.939  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-07 20:26:12.939  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,07-07 20:26:12.949  6134  6134 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
07-07 20:26:12.949  6134  6134 I SoundPicker: SoundPickerReceiver [onReceive] startService
07-07 20:26:12.949  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,07-07 20:26:12.949  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
07-07 20:26:12.949  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
07-07 20:26:12.949  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
07-07 20:26:12.949  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,07-07 20:26:12.959  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,07-07 20:26:12.959   966  1296 D TaskPersister: removeObsoleteFile: deleting file=104_task.xml
,07-07 20:26:12.959  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,07-07 20:26:12.959  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
07-07 20:26:12.959  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
07-07 20:26:12.959  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,07-07 20:26:12.959   966  1296 D TaskPersister: removeObsoleteFile: deleting file=104_task_thumbnail.png
,07-07 20:26:12.959  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,07-07 20:26:12.969  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,07-07 20:26:12.969  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
07-07 20:26:12.969  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
07-07 20:26:12.969  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,07-07 20:26:12.969  5968  6187 I MediaStoreImporter: Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,07-07 20:26:12.989  6062  6062 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED,
,07-07 20:26:12.999  6062  6195 I DFPI.ApkInstallService: onHandleIntent
07-07 20:26:12.999  6062  6195 I DFPI.ApkInstallService: Media Scan Finished Case 
07-07 20:26:13.009  6062  6195 D DFPI.ApkInstallService: check CID = HTC__102
07-07 20:26:13.009  6062  6195 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
,07-07 20:26:13.019  6134  6134 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,07-07 20:26:13.019  3853  3875 I art     : Explicit concurrent mark sweep GC freed 60079(4MB) AllocSpace objects, 0(0B) LOS objects, 72% free, 1551KB/5MB, paused 797us total 50.592ms,
07-07 20:26:13.019  6134  6134 I SoundPicker: SoundPickerReceiver [onReceive] startService,
,07-07 20:26:13.029  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,07-07 20:26:13.039  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac,
07-07 20:26:13.039  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
07-07 20:26:13.039  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
,07-07 20:26:13.039  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,07-07 20:26:13.039  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
07-07 20:26:13.049  1964  6198 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,07-07 20:26:13.049  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
07-07 20:26:13.049  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,07-07 20:26:13.049  6134  6161 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
,07-07 20:26:13.049  6134  6161 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
07-07 20:26:13.049  6134  6161 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
07-07 20:26:13.049  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-07 20:26:13.049  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
07-07 20:26:13.049  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-07 20:26:13.049  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
,07-07 20:26:13.049  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
07-07 20:26:13.049  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-07 20:26:13.049  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-07 20:26:13.049  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-07 20:26:13.049  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-07 20:26:13.049  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
,07-07 20:26:13.049  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-07 20:26:13.049  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
,07-07 20:26:13.049  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-07 20:26:13.049  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-07 20:26:13.049  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
07-07 20:26:13.049  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
07-07 20:26:13.049  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
07-07 20:26:13.049  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
,07-07 20:26:13.049  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
07-07 20:26:13.049  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8,
07-07 20:26:13.049  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
07-07 20:26:13.049  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
07-07 20:26:13.049  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98,
07-07 20:26:13.049  6134  6161 I SoundPicker: TurnFileToMediaUriService [checkFileExistence]
07-07 20:26:13.049  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-07 20:26:13.049  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
07-07 20:26:13.049  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
07-07 20:26:13.049  5968  6187 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,07-07 20:26:13.049  5968  6187 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.music/databases/music.db, handle: 0x559f58ed60
07-07 20:26:13.059  1964  1964 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,07-07 20:26:13.059  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,07-07 20:26:13.059  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,07-07 20:26:13.059  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-07 20:26:13.059  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-07 20:26:13.059  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
07-07 20:26:13.059  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-07 20:26:13.069  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,07-07 20:26:13.069  2194  2194 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,07-07 20:26:13.069  5968  6187 E AndroidRuntime: FATAL EXCEPTION: MediaStoreImportService
07-07 20:26:13.069  5968  6187 E AndroidRuntime: Process: com.google.android.music:main, PID: 5968
07-07 20:26:13.069  5968  6187 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-07 20:26:13.069  5968  6187 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
07-07 20:26:13.069  5968  6187 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
07-07 20:26:13.069  5968  6187 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
07-07 20:26:13.069  5968  6187 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
07-07 20:26:13.069  5968  6187 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
07-07 20:26:13.069  5968  6187 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
07-07 20:26:13.069  5968  6187 E AndroidRuntime: 	at com.google.android.music.store.BaseStore.beginWriteTxn(BaseStore.java:58)
07-07 20:26:13.069  5968  6187 E AndroidRuntime: 	at com.google.android.music.store.Store.beginWriteTxn(Store.java:232)
07-07 20:26:13.069  5968  6187 E AndroidRuntime: 	at com.google.android.music.store.MediaStoreImporter.importAudioFiles(MediaStoreImporter.java:504)
07-07 20:26:13.069  5968  6187 E AndroidRuntime: 	at com.google.android.music.store.MediaStoreImporter.importNow(MediaStoreImporter.java:307)
07-07 20:26:13.069  5968  6187 E AndroidRuntime: 	at com.google.android.music.store.MediaStoreImporter.doImport(MediaStoreImporter.java:222)
07-07 20:26:13.069  5968  6187 E AndroidRuntime: 	at com.google.android.music.store.Store.importMediaStore(Store.java:10438)
07-07 20:26:13.069  5968  6187 E AndroidRuntime: 	at com.google.android.music.store.MediaStoreImportService.importMediaStore(MediaStoreImportService.java:75)
07-07 20:26:13.069  5968  6187 E AndroidRuntime: 	at com.google.android.music.store.MediaStoreImportService.access$100(MediaStoreImportService.java:34)
07-07 20:26:13.069  5968  6187 E AndroidRuntime: 	at com.google.android.music.store.MediaStoreImportService$4.run(MediaStoreImportService.java:140)
07-07 20:26:13.069  5968  6187 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
07-07 20:26:13.069  5968  6187 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-07 20:26:13.069  5968  6187 E AndroidRuntime: 	at com.google.android.music.utils.LoggableHandler.dispatchMessage(LoggableHandler.java:82)
07-07 20:26:13.069  5968  6187 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
07-07 20:26:13.069  5968  6187 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-07 20:26:13.069  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,07-07 20:26:13.069  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-07 20:26:13.069  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-07 20:26:13.069  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-07 20:26:13.069  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
07-07 20:26:13.069   966  1792 E ActivityManager: App crashed! Process: com.google.android.music:main
07-07 20:26:13.069  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
07-07 20:26:13.069  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-07 20:26:13.069  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-07 20:26:13.069  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-07 20:26:13.069  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-07 20:26:13.069  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
07-07 20:26:13.079   966  6199 E DropBoxManagerService: Can't write: system_app_crash
07-07 20:26:13.079   966  6199 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop133.tmp: open failed: EROFS (Read-only file system)
07-07 20:26:13.079   966  6199 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-07 20:26:13.079   966  6199 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-07 20:26:13.079   966  6199 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-07 20:26:13.079   966  6199 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
07-07 20:26:13.079   966  6199 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-07 20:26:13.079   966  6199 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12663)
07-07 20:26:13.079   966  6199 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-07 20:26:13.079   966  6199 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-07 20:26:13.079   966  6199 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-07 20:26:13.079   966  6199 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-07 20:26:13.079   966  6199 E DropBoxManagerService: 	... 5 more
,07-07 20:26:13.119   966  1037 D StatusBarManagerService: setSystemUiVisibility(0xc0000000),
07-07 20:26:13.119   966  1037 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-07 20:26:13.119   966  1037 D StatusBarManagerService: hiding MENU key
,07-07 20:26:13.129  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac,
,07-07 20:26:13.129  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
07-07 20:26:13.129  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
07-07 20:26:13.129  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-07 20:26:13.129  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-07 20:26:13.129  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,07-07 20:26:13.139  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,07-07 20:26:13.149  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
07-07 20:26:13.149   966   985 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=2194, uid=10024, userID:0
07-07 20:26:13.149  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
07-07 20:26:13.149  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
07-07 20:26:13.149  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,07-07 20:26:13.169   966  1794 I ActivityManager: Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=6201 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,07-07 20:26:13.179  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,07-07 20:26:13.179  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac,
,07-07 20:26:13.179  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
07-07 20:26:13.179  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
,07-07 20:26:13.179  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,07-07 20:26:13.189   966   985 D PMS     : acquireWL(3108037f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1964 10024 WorkSource{10024 com.google.android.gms}
,07-07 20:26:13.189  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,07-07 20:26:13.189  2194  6214 D LocationInitializer: Restart initialization of location
,07-07 20:26:13.189  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac,
07-07 20:26:13.189  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac,
07-07 20:26:13.189  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
07-07 20:26:13.199   966   986 D PMS     : releaseWL(3108037f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
07-07 20:26:13.189  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
07-07 20:26:13.209  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,07-07 20:26:13.209  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
07-07 20:26:13.209  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
07-07 20:26:13.209  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
,07-07 20:26:13.209  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,07-07 20:26:13.209   966  1794 D PMS     : acquireWL(369deb95): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1964 10024 WorkSource{10024 com.google.android.gms}
07-07 20:26:13.209  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,07-07 20:26:13.219  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
07-07 20:26:13.219  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,07-07 20:26:13.229  6134  6161 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
07-07 20:26:13.229  6134  6161 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
,07-07 20:26:13.229  6134  6161 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
07-07 20:26:13.229  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-07 20:26:13.229  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
07-07 20:26:13.229  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-07 20:26:13.229  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-07 20:26:13.229  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
07-07 20:26:13.229  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-07 20:26:13.229  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-07 20:26:13.229  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-07 20:26:13.229  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-07 20:26:13.229  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
,07-07 20:26:13.229  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-07 20:26:13.229   966  1271 D PMS     : releaseWL(369deb95): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
07-07 20:26:13.229  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-07 20:26:13.229  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
,07-07 20:26:13.229  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-07 20:26:13.229  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
07-07 20:26:13.229  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
07-07 20:26:13.229  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
07-07 20:26:13.229  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
,07-07 20:26:13.229  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
07-07 20:26:13.229  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
07-07 20:26:13.229  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
07-07 20:26:13.229  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
07-07 20:26:13.229  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-07 20:26:13.229  6134  6161 I SoundPicker: TurnFileToMediaUriService [checkFileExistence]
07-07 20:26:13.229  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-07 20:26:13.229  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
07-07 20:26:13.229  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-07 20:26:13.239  6201  6201 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,07-07 20:26:13.239  6201  6201 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-07 20:26:13.269  6201  6201 I MultiDex: VM with version 2.1.0 has multidex support
07-07 20:26:13.269  6201  6201 I MultiDex: install
07-07 20:26:13.269  6201  6201 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-07 20:26:13.269   966  1791 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6224 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a
,07-07 20:26:13.279  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,07-07 20:26:13.279  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-07 20:26:13.279  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-07 20:26:13.279  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-07 20:26:13.279  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
07-07 20:26:13.279  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-07 20:26:13.289  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
,07-07 20:26:13.289  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-07 20:26:13.289  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-07 20:26:13.289  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
,07-07 20:26:13.289  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-07 20:26:13.289  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-07 20:26:13.299  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,07-07 20:26:13.299  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac,
07-07 20:26:13.299  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-07 20:26:13.299  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-07 20:26:13.299  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-07 20:26:13.299  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,07-07 20:26:13.309  6201  6201 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,07-07 20:26:13.309  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,07-07 20:26:13.319  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,07-07 20:26:13.319  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
07-07 20:26:13.319  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-07 20:26:13.319  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-07 20:26:13.319  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,07-07 20:26:13.329  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,07-07 20:26:13.339  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
07-07 20:26:13.339  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
07-07 20:26:13.339  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
07-07 20:26:13.339  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,07-07 20:26:13.349  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,07-07 20:26:13.349  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,07-07 20:26:13.349  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
07-07 20:26:13.349  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
07-07 20:26:13.349  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,07-07 20:26:13.359  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac,
07-07 20:26:13.359  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
07-07 20:26:13.359  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
07-07 20:26:13.359  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
,07-07 20:26:13.359  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,07-07 20:26:13.369  6224  6224 D PhoneMonitor: Register our PhoneStateListener
,07-07 20:26:13.369  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,07-07 20:26:13.379  6201  6201 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,07-07 20:26:13.379  6201  6201 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@14e2da59: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
07-07 20:26:13.379  6201  6201 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
07-07 20:26:13.379  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
07-07 20:26:13.379  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
,07-07 20:26:13.379  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
07-07 20:26:13.379  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,07-07 20:26:13.389  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,07-07 20:26:13.389  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,07-07 20:26:13.389  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac,
07-07 20:26:13.389  6134  6161 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
07-07 20:26:13.389  6134  6161 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
07-07 20:26:13.389  6134  6161 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
07-07 20:26:13.389  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-07 20:26:13.389  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
07-07 20:26:13.389  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-07 20:26:13.389  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-07 20:26:13.389  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
07-07 20:26:13.389  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-07 20:26:13.389  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-07 20:26:13.389  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-07 20:26:13.389  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
,07-07 20:26:13.389  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-07 20:26:13.389  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-07 20:26:13.389  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-07 20:26:13.389  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-07 20:26:13.389  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-07 20:26:13.389  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
07-07 20:26:13.389  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
07-07 20:26:13.389  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
07-07 20:26:13.389  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
07-07 20:26:13.389  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102,
07-07 20:26:13.389  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
07-07 20:26:13.389  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
07-07 20:26:13.389  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
07-07 20:26:13.389  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-07 20:26:13.389  6134  6161 I SoundPicker: TurnFileToMediaUriService [checkFileExistence]
07-07 20:26:13.389  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-07 20:26:13.389  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
07-07 20:26:13.389  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
07-07 20:26:13.399  6201  6247 W NativeLibraryUtils: Failed to open lock file
07-07 20:26:13.399  6201  6247 W NativeLibraryUtils: java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
07-07 20:26:13.399  6201  6247 W NativeLibraryUtils: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-07 20:26:13.399  6201  6247 W NativeLibraryUtils: 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
07-07 20:26:13.399  6201  6247 W NativeLibraryUtils: 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
07-07 20:26:13.399  6201  6247 W NativeLibraryUtils: 	at com.google.android.gms.common.app.a.run(SourceFile:136)
07-07 20:26:13.399  6201  6247 W NativeLibraryUtils: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-07 20:26:13.399  6201  6247 W NativeLibraryUtils: 	at libcore.io.Posix.open(Native Method)
07-07 20:26:13.399  6201  6247 W NativeLibraryUtils: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-07 20:26:13.399  6201  6247 W NativeLibraryUtils: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-07 20:26:13.399  6201  6247 W NativeLibraryUtils: 	... 3 more
,07-07 20:26:13.399  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
07-07 20:26:13.399   966   986 I ActivityManager: Killing 5600:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
07-07 20:26:13.399   966   986 D Process : killProcessQuiet, pid=5600
07-07 20:26:13.399   966   986 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,07-07 20:26:13.399  6201  6201 D WearableService: callingUid 10024, callindPid: 6201
,07-07 20:26:13.419  6224  6224 D PhoneMonitor: onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,07-07 20:26:13.419  6224  6224 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false,
,07-07 20:26:13.509   966  1533 I ActivityManager: Recipient 5600,
,07-07 20:26:13.509  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac,
,07-07 20:26:13.509  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-07 20:26:13.509  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-07 20:26:13.509  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
07-07 20:26:13.509  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-07 20:26:13.519  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,07-07 20:26:13.529   966  1794 D PMS     : acquireWL(3838694e): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2194 10024 WorkSource{10024 com.google.android.gms}
,07-07 20:26:13.529  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-07 20:26:13.529  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-07 20:26:13.529  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-07 20:26:13.529  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-07 20:26:13.529  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-07 20:26:13.539   966  1791 D PMS     : acquireWL(11b4337c): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2194 10024 WorkSource{10024 com.google.android.gms},
07-07 20:26:13.549   966  1795 D PMS     : releaseWL(3838694e): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
,07-07 20:26:13.549  1964  6249 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,07-07 20:26:13.549  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,07-07 20:26:13.559  2194  4554 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/Checkin.xml to backup file /data/data/com.google.android.gms/shared_prefs/Checkin.xml.bak
07-07 20:26:13.559  1850  6200 E MDM     : [144] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,07-07 20:26:13.559  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,07-07 20:26:13.559  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-07 20:26:13.559  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-07 20:26:13.559  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-07 20:26:13.559  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,07-07 20:26:13.569  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,07-07 20:26:13.569  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,07-07 20:26:13.569  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
07-07 20:26:13.569  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-07 20:26:13.569  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-07 20:26:13.569  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,07-07 20:26:13.569  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,07-07 20:26:13.579  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,07-07 20:26:13.579  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
07-07 20:26:13.579  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
07-07 20:26:13.579  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,07-07 20:26:13.589  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,07-07 20:26:13.589  2194  6250 I CheckinService: Checking schedule, now: 1467915973593 next: 1467915998326
07-07 20:26:13.589   966  1795 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2194, uid=10024, userID:0
07-07 20:26:13.589  2194  6250 I CheckinService: active receiver: disabled
07-07 20:26:13.589  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
07-07 20:26:13.589  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
07-07 20:26:13.589  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
,07-07 20:26:13.589  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102,
,07-07 20:26:13.589  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac,
,07-07 20:26:13.599  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
07-07 20:26:13.599  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
07-07 20:26:13.599  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
,07-07 20:26:13.599  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,07-07 20:26:13.599  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,07-07 20:26:13.609  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,07-07 20:26:13.609  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
07-07 20:26:13.609  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
07-07 20:26:13.609  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,07-07 20:26:13.609  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,07-07 20:26:13.619  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
07-07 20:26:13.619  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,07-07 20:26:13.619  6134  6161 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
07-07 20:26:13.619  6134  6161 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
07-07 20:26:13.619  6134  6161 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
07-07 20:26:13.619  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
,07-07 20:26:13.619  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
07-07 20:26:13.619  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-07 20:26:13.619  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-07 20:26:13.619  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
07-07 20:26:13.619  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122,
07-07 20:26:13.619  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-07 20:26:13.619  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
,07-07 20:26:13.619  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
,07-07 20:26:13.619  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
,07-07 20:26:13.619  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
,07-07 20:26:13.619  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-07 20:26:13.619  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
,07-07 20:26:13.619  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5,
,07-07 20:26:13.619  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
07-07 20:26:13.619  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
07-07 20:26:13.619  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
07-07 20:26:13.619  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
07-07 20:26:13.619  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
07-07 20:26:13.619  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
07-07 20:26:13.619  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
07-07 20:26:13.619  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
07-07 20:26:13.619  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-07 20:26:13.619  6134  6161 I SoundPicker: TurnFileToMediaUriService [checkFileExistence]
07-07 20:26:13.619  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-07 20:26:13.619  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
07-07 20:26:13.619  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
07-07 20:26:13.619  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
07-07 20:26:13.629  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-07 20:26:13.629  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-07 20:26:13.629  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-07 20:26:13.629  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
07-07 20:26:13.629  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
07-07 20:26:13.629  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,07-07 20:26:13.639  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,07-07 20:26:13.639  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-07 20:26:13.639  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-07 20:26:13.639  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-07 20:26:13.639  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,07-07 20:26:13.639  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
,07-07 20:26:13.639  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,07-07 20:26:13.639  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-07 20:26:13.639  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-07 20:26:13.639  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-07 20:26:13.639  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,07-07 20:26:13.649  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,07-07 20:26:13.649  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac,
07-07 20:26:13.649  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
07-07 20:26:13.649  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-07 20:26:13.649  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-07 20:26:13.649  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,07-07 20:26:13.659  2194  2194 I art     : Explicit concurrent mark sweep GC freed 16483(1175KB) AllocSpace objects, 14(280KB) LOS objects, 40% free, 5MB/9MB, paused 1.338ms total 90.049ms,
,07-07 20:26:13.689   966   966 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
,07-07 20:26:13.689  1335  1335 D WIFI_ICON: WifiActivity: 0
07-07 20:26:13.689   966   966 E WifiTrafficPoller:  packet count Tx=215 Rx=355
07-07 20:26:13.689  1335  1335 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
07-07 20:26:13.689   966   966 E WifiTrafficPoller: notifying of data activity 0
,07-07 20:26:13.819   966  1734 I art     : Explicit concurrent mark sweep GC freed 17758(920KB) AllocSpace objects, 2(1036KB) LOS objects, 33% free, 17MB/26MB, paused 1.527ms total 168.298ms,
,07-07 20:26:13.829  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac,
07-07 20:26:13.829  2194  2194 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-07 20:26:13.829  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac,
,07-07 20:26:13.829  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
07-07 20:26:13.829  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
,07-07 20:26:13.829  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,07-07 20:26:13.839  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac,
,07-07 20:26:13.839  2194  2194 I Kids    : [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
07-07 20:26:13.839   966  1271 D PMS     : releaseWL(11b4337c): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
,07-07 20:26:13.839  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,07-07 20:26:13.849  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
07-07 20:26:13.849  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
07-07 20:26:13.849  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,07-07 20:26:13.859  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac,
,07-07 20:26:13.859  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,07-07 20:26:13.859  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
07-07 20:26:13.859  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
,07-07 20:26:13.859  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,07-07 20:26:13.869  2194  4554 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/DownloadService.xml to backup file /data/data/com.google.android.gms/shared_prefs/DownloadService.xml.bak,
,07-07 20:26:13.879  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,07-07 20:26:13.879  2194  4554 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/DownloadService.xml to backup file /data/data/com.google.android.gms/shared_prefs/DownloadService.xml.bak
,07-07 20:26:13.889   966  1732 D PMS     : acquireWL(2911bb81): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 2194 10024 WorkSource{10024 com.google.android.gms}
07-07 20:26:13.889  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,07-07 20:26:13.889  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
07-07 20:26:13.889  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
07-07 20:26:13.889  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,07-07 20:26:13.889  1964  1964 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/ns.db'.,
07-07 20:26:13.889  1964  1964 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-07 20:26:13.889  1964  1964 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-07 20:26:13.889  1964  1964 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235),
07-07 20:26:13.889  1964  1964 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-07 20:26:13.889  1964  1964 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-07 20:26:13.889  1964  1964 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-07 20:26:13.889  1964  1964 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-07 20:26:13.889  1964  1964 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
07-07 20:26:13.889  1964  1964 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
07-07 20:26:13.889  1964  1964 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
07-07 20:26:13.889  1964  1964 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
07-07 20:26:13.889  1964  1964 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-07 20:26:13.889  1964  1964 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-07 20:26:13.889  1964  1964 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-07 20:26:13.889  1964  1964 E SQLiteDatabase: 	at com.google.android.gms.gcm.nts.n.b(SourceFile:252)
07-07 20:26:13.889  1964  1964 E SQLiteDatabase: 	at com.google.android.gms.gcm.nts.k.a(SourceFile:562)
07-07 20:26:13.889  1964  1964 E SQLiteDatabase: 	at com.google.android.gms.gcm.nts.k.b(SourceFile:540)
07-07 20:26:13.889  1964  1964 E SQLiteDatabase: 	at com.google.android.gms.gcm.nts.SchedulerReceiver.onReceive(SourceFile:176)
07-07 20:26:13.889  1964  1964 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
07-07 20:26:13.889  1964  1964 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
07-07 20:26:13.889  1964  1964 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
07-07 20:26:13.889  1964  1964 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:26:13.889  1964  1964 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
07-07 20:26:13.889  1964  1964 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5721)
07-07 20:26:13.889  1964  1964 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-07 20:26:13.889  1964  1964 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-07 20:26:13.889  1964  1964 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
07-07 20:26:13.889  1964  1964 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
07-07 20:26:13.889  1964  1964 E AndroidRuntime: FATAL EXCEPTION: main
07-07 20:26:13.889  1964  1964 E AndroidRuntime: Process: com.google.process.gapps, PID: 1964
07-07 20:26:13.889  1964  1964 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.nts.SchedulerReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-07 20:26:13.889  1964  1964 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2726)
07-07 20:26:13.889  1964  1964 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
07-07 20:26:13.889  1964  1964 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
07-07 20:26:13.889  1964  1964 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:26:13.889  1964  1964 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
07-07 20:26:13.889  1964  1964 E AndroidRuntime: 	at androi,d.app.ActivityThread.main(ActivityThread.java:5721)
07-07 20:26:13.889  1964  1964 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-07 20:26:13.889  1964  1964 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-07 20:26:13.889  1964  1964 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
07-07 20:26:13.889  1964  1964 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
07-07 20:26:13.889  1964  1964 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-07 20:26:13.889  1964  1964 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-07 20:26:13.889  1964  1964 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-07 20:26:13.889  1964  1964 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-07 20:26:13.889  1964  1964 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-07 20:26:13.889  1964  1964 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-07 20:26:13.889  1964  1964 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-07 20:26:13.889  1964  1964 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
07-07 20:26:13.889  1964  1964 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
07-07 20:26:13.889  1964  1964 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
07-07 20:26:13.889  1964  1964 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
07-07 20:26:13.889  1964  1964 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-07 20:26:13.889  1964  1964 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-07 20:26:13.889  1964  1964 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-07 20:26:13.889  1964  1964 E AndroidRuntime: 	at com.google.android.gms.gcm.nts.n.b(SourceFile:252)
07-07 20:26:13.889  1964  1964 E AndroidRuntime: 	at com.google.android.gms.gcm.nts.k.a(SourceFile:562)
07-07 20:26:13.889  1964  1964 E AndroidRuntime: 	at com.google.android.gms.gcm.nts.k.b(SourceFile:540)
07-07 20:26:13.889  1964  1964 E AndroidRuntime: 	at com.google.android.gms.gcm.nts.SchedulerReceiver.onReceive(SourceFile:176)
07-07 20:26:13.889  1964  1964 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
07-07 20:26:13.889  1964  1964 E AndroidRuntime: 	... 9 more
07-07 20:26:13.899   966  6256 E DropBoxManagerService: Can't write: system_app_crash
07-07 20:26:13.899   966  6256 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop134.tmp: open failed: EROFS (Read-only file system)
07-07 20:26:13.899   966  6256 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-07 20:26:13.899   966  6256 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-07 20:26:13.899   966  6256 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-07 20:26:13.899   966  6256 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
07-07 20:26:13.899   966  6256 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-07 20:26:13.899   966  6256 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12663)
07-07 20:26:13.899   966  6256 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-07 20:26:13.899   966  6256 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-07 20:26:13.899   966  6256 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-07 20:26:13.899   966  6256 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-07 20:26:13.899   966  6256 E DropBoxManagerService: 	... 5 more
07-07 20:26:13.899   966   986 E ActivityManager: App crashed! Process: com.google.process.gapps
07-07 20:26:13.919  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
07-07 20:26:13.929  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,07-07 20:26:13.929  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
07-07 20:26:13.929  6134  6161 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
07-07 20:26:13.929  6134  6161 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
07-07 20:26:13.929  6134  6161 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
07-07 20:26:13.929  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-07 20:26:13.929  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
07-07 20:26:13.929  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-07 20:26:13.929  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-07 20:26:13.929  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
07-07 20:26:13.929  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-07 20:26:13.929  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-07 20:26:13.929  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-07 20:26:13.929  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
07-07 20:26:13.929  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-07 20:26:13.929  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-07 20:26:13.929  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-07 20:26:13.929  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-07 20:26:13.929  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-07 20:26:13.929  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
07-07 20:26:13.929  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
07-07 20:26:13.929  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
07-07 20:26:13.929  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
07-07 20:26:13.929  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
07-07 20:26:13.929  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
07-07 20:26:13.929  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
07-07 20:26:13.929  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
07-07 20:26:13.929  6134  6161 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
07-07 20:26:13.929  6134  6161 I SoundPicker: TurnFileToMediaUriService [checkFileExistence]
07-07 20:26:13.929  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-07 20:26:13.929  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
07-07 20:26:13.929  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
07-07 20:26:13.939  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
07-07 20:26:13.949  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-07 20:26:13.949  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-07 20:26:13.949  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-07 20:26:13.949  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
07-07 20:26:13.949  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
07-07 20:26:13.949  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
07-07 20:26:13.959  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-07 20:26:13.959  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-07 20:26:13.959  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-07 20:26:13.959  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
07-07 20:26:13.959  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
07-07 20:26:13.969  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,07-07 20:26:13.969  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
07-07 20:26:13.969  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
07-07 20:26:13.969  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-07 20:26:13.969  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
07-07 20:26:13.969  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
07-07 20:26:13.979  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
07-07 20:26:13.979  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
07-07 20:26:13.979  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
07-07 20:26:13.979  6134  6161 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-07 20:26:13.979  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
07-07 20:26:13.979  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
07-07 20:26:13.989  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
07-07 20:26:13.999  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
07-07 20:26:13.999  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
07-07 20:26:13.999  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
07-07 20:26:13.999  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
07-07 20:26:14.009  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,07-07 20:26:14.009  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
07-07 20:26:14.009  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
,07-07 20:26:14.009  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
07-07 20:26:14.009  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,07-07 20:26:14.029  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,07-07 20:26:14.029  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
07-07 20:26:14.029  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
,07-07 20:26:14.029  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
07-07 20:26:14.029  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,07-07 20:26:14.039  2194  4554 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/DownloadService.xml to backup file /data/data/com.google.android.gms/shared_prefs/DownloadService.xml.bak
07-07 20:26:14.039   966  1793 D PMS     : releaseWL(2911bb81): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 WorkSource{10024 com.google.android.gms}
,07-07 20:26:14.049  6134  6161 I SoundPicker: SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac,
,07-07 20:26:14.049  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
07-07 20:26:14.049  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
07-07 20:26:14.049  6134  6161 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
,07-07 20:26:14.049  6134  6161 I SoundPicker: TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98

```
