#### Test 72145431fdae11f_thali06_HTC-HTC One M9 Logs


```
--------- beginning of main
06-30 10:34:23.243  7403  7462 I System  : exec(/system/bin/sh -c ps @ com.aiqidii.mercury.service.ls.LocalServerControllerService.findZombies:301)
--------- beginning of system
06-30 10:34:23.243  1121  5139 I ActivityManager: Start proc 7468:com.google.android.music:main/u0a114 for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver
06-30 10:34:23.253  1121  3766 D Process : killProcessQuiet, pid=6611
06-30 10:34:23.253  1121  3766 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19304 
06-30 10:34:23.253  7468  7468 W HTCLOG  : use specified tag [FDManager], func [0].
06-30 10:34:23.253  7468  7468 W HTCLOG  : mask=0x18
06-30 10:34:23.253  1121  3766 I ActivityManager: Killing 6611:com.google.android.apps.maps/u0a113 (adj 15): empty #17
06-30 10:34:23.333  1121  3907 I ActivityManager: Recipient 6611
,06-30 10:34:23.483  7468  7468 I MusicStore: Database version: 107
06-30 10:34:23.523  7493  7493 W HTCLOG  : use specified tag [AndroidRuntime], func [0].
06-30 10:34:23.523  7493  7493 W HTCLOG  : mask=0x18
06-30 10:34:23.553  7468  7468 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
06-30 10:34:23.553  7468  7468 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
06-30 10:34:23.573  7468  7468 W linker  : /data/app/com.google.android.gms-1/lib/arm64/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x7a8
06-30 10:34:23.573  7468  7468 W linker  : /data/app/com.google.android.gms-1/lib/arm64/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0x80
06-30 10:34:23.573  7468  7468 W linker  : /data/app/com.google.android.gms-1/lib/arm64/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x169
06-30 10:34:23.583  7468  7468 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
06-30 10:34:23.623  7468  7468 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
06-30 10:34:23.623  7468  7468 D AndroidMusic: GMSCore installation verified
06-30 10:34:23.643  7468  7468 I ConfigStore: Config Database version: 1
06-30 10:34:23.643  7468  7468 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
06-30 10:34:23.643  7468  7468 W HTCLOG  : mask=0x18
06-30 10:34:23.713  1121  3440 E MountService: mkdirs when SD card not mounted/storage/ext_sd/Android/data/com.google.android.music/files/
06-30 10:34:23.713  7468  7468 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
06-30 10:34:23.723   508   517 W PnPMgr  : Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
06-30 10:34:23.743  7493  7506 W HTCLOG  : use specified tag [cutils-trace], func [0].
06-30 10:34:23.743  7493  7506 W HTCLOG  : mask=0x18
06-30 10:34:23.743  7493  7506 E cutils-trace: Error opening trace file: Permission denied (13)
06-30 10:34:23.743  1121  1190 E MountService: mkdirs when SD card not mounted/storage/ext_sd/Android/data/com.google.android.music/files/
06-30 10:34:23.743  7468  7468 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
06-30 10:34:23.753  1121  3754 E MountService: mkdirs when SD card not mounted/storage/ext_sd/Android/data/com.google.android.music/files/
06-30 10:34:23.753  7468  7468 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
06-30 10:34:23.773  1121  1190 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=7468, uid=10114, userID:0
06-30 10:34:23.783  1121  3506 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
06-30 10:34:23.783  1121  3506 D WifiDisplayAdapter:     Client/Owner: Client
06-30 10:34:23.783  1121  3506 D WifiDisplayAdapter:     GroupId: 
06-30 10:34:23.783  1121  3506 D WifiDisplayAdapter:     Passphrase: 
06-30 10:34:23.783  1121  3506 D WifiDisplayAdapter:     SessionId: 0
06-30 10:34:23.783  1121  3506 D WifiDisplayAdapter:     IP Address: }
06-30 10:34:23.783  7493  7493 D CustomizationManager: ====startRecUseTime====
06-30 10:34:23.783  7493  7493 D htc.customization.log.level:  is 
06-30 10:34:23.783  7493  7493 W CustomizationLogLevel: Level value is invalid, use default level 2
06-30 10:34:23.793  1121  3440 D MediaRouterService: Client com.google.android.music (pid 7468): Registered
06-30 10:34:23.793  1121  3460 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
06-30 10:34:23.793  1121  3460 D WifiDisplayAdapter:     Client/Owner: Client
06-30 10:34:23.793  1121  3460 D WifiDisplayAdapter:     GroupId: 
06-30 10:34:23.793  1121  3460 D WifiDisplayAdapter:     Passphrase: 
06-30 10:34:23.793  1121  3460 D WifiDisplayAdapter:     SessionId: 0
06-30 10:34:23.793  1121  3460 D WifiDisplayAdapter:     IP Address: }
06-30 10:34:23.793  7403  7462 I System  : exec(/system/bin/sh -c cd /data/user/0/com.aiqidii.mercury/files; /data/user/0/com.aiqidii.mercury/files/server -content_encoding=true -localsocket=/data/user/0/com.aiqidii.mercury/files/dsock -remotehost=xdsi-prod-cg.aiqidii.com -remoteport=443 -localhost=localhost -localport=19090 -get_patch_size=30 -get_slice_size=500 -pull_interval=2147483647 -syncmod_interval=2147483647 -repo_tables="1:pp" -enablepprof=false -enable_pullsnapshot=true -num_concurrent_work=4 @ com.aiqidii.mercury.service.ls.LocalServerControllerService.startLocalServer:407)
06-30 10:34:23.793  3475  3854 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
06-30 10:34:23.793  3475  3854 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@39a45cb4 +
06-30 10:34:23.793  3475  3854 I Prism.WidgetManager: onLoadItems() +
06-30 10:34:23.793  7468  7468 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
06-30 10:34:23.813  7524  7524 W linker  : /data/user/0/com.aiqidii.mercury/files/server has text relocations. This is wasting memory and prevents security hardening. Please fix.
06-30 10:34:23.823  3475  3854 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
06-30 10:34:23.823   508   517 W PnPMgr  : Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
06-30 10:34:23.823  1121  3506 I ActivityManager: Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
06-30 10:34:23.843  7493  7493 D CustomizationManager:  Read ACC file spent 0.026 (s)
06-30 10:34:23.843  7493  7493 D CIDMapFileReader: Parsing tag item name = HTC__001
06-30 10:34:23.843  7493  7493 D CIDMapFileReader: Parsing tag item name = HTC__002
06-30 10:34:23.843  7493  7493 D CIDMapFileReader: Parsing tag item name = HTC__016
06-30 10:34:23.843  7493  7493 D CIDMapFileReader: Parsing tag item name = HTC__031
06-30 10:34:23.843  7493  7493 D CIDMapFileReader: Parsing tag item name = HTC__032
06-30 10:34:23.843  7493  7493 D CIDMapFileReader: Parsing tag item name = HTC__102
06-30 10:34:23.843  7493  7493 D CIDMapFileReader: Parsing tag item name = HTC__A07
06-30 10:34:23.843  7493  7493 D CIDMapFileReader: Parsing tag item name = HTC__J15
06-30 10:34:23.843  7493  7493 D CIDMapFileReader: Parsing tag item name = HTC__M27
06-30 10:34:23.843  7493  7493 D CIDMapFileReader: Parsing tag item name = HTC__Y13
06-30 10:34:23.843  7493  7493 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__102.xml
06-30 10:34:23.843  7493  7493 I CustomizationCIDLoader: Parsing tag category name = application
06-30 10:34:23.843  7493  7493 I CustomizationCIDLoader: Parsing tag category name = system
06-30 10:34:23.843  7493  7493 I CustomizationCIDLoader: Parsing tag category name = Settings
06-30 10:34:23.843  7493  7493 I CustomizationCIDLoader: Parsing tag category name = ACC
06-30 10:34:23.843  7493  7493 I CustomizationCIDLoader: add string-array item, value = 42507
06-30 10:34:23.843  7493  7493 I CustomizationCIDLoader: add string-array item, value = 21902
06-30 10:34:23.843  7493  7493 I CustomizationCIDLoader: add string-array item, value = 26006:26001.26002.26003
06-30 10:34:23.843  7493  7493 I CustomizationCIDLoader: add string-array item, value = 23420
06-30 10:34:23.843  7493  7493 I CustomizationCIDLoader: add string-array item, value = 22299
06-30 10:34:23.843  7493  7493 I CustomizationCIDLoader: add string-array item, value = 24002
06-30 10:34:23.843  7493  7493 I CustomizationCIDLoader: add string-array item, value = 23210
06-30 10:34:23.843  7493  7493 I CustomizationCIDLoader: add string-array item, value = 23205
06-30 10:34:23.843  7493  7493 I CustomizationCIDLoader: add string-array item, value = 23806
06-30 10:34:23.843  7493  7493 I CustomizationCIDLoader: add string-array item, value = 23430
06-30 10:34:23.843  7493  7493 I CustomizationCIDLoader: add string-array item, value = 23408
06-30 10:34:23.843  7493  7493 I CustomizationCIDLoader: add string-array item, value = 27205
06-30 10:34:23.843  7493  7493 I CustomizationCIDLoader: add string-array item, value = 27202:27205
06-30 10:34:23.843  7493  7493 I CustomizationCIDLoader: add string-array item, value = 27216:27202.27205
06-30 10:34:23.843  7493  7493 I CustomizationCIDLoader: add string-array item, value = 42507:C:1:0
06-30 10:34:23.843  7493  7493 I CustomizationCIDLoader: add string-array item, value = 21902:C:1:0
06-30 10:34:23.843  7493  7493 I CustomizationCIDLoader: add string-array item, value = 26006:D:1:0
06-30 10:34:23.843  7493  7493 I CustomizationCIDLoader: add string-array item, value = 23420:D:0:0
06-30 10:34:23.843  7493  7493 I CustomizationCIDLoader: add string-array item, value = 27205:C:1:0
06-30 10:34:23.843  7493  7493 I CustomizationCIDLoader: add string-array item, value = 22299:D:0:0
06-30 10:34:23.843  7493  7493 I CustomizationCIDLoader: add string-array item, value = 24002:D:0:0
06-30 10:34:23.843  7493  7493 I CustomizationCIDLoader: add string-array item, value = 23210:D:2:0
06-30 10:34:23.843  7493  7493 I CustomizationCIDLoader: add string-array item, value = 23205:D:2:0
06-30 10:34:23.843  7493  7493 I CustomizationCIDLoader: add string-array item, value = 23806:D:0:0
06-30 10:34:23.843  7493  7493 I CustomizationCIDLoader: add string-array item, value = 23430:C:1:0
06-30 10:34:23.843  7493  7493 I CustomizationCIDLoader: add string-array item, value = 23408:C:1:0
06-30 10:34:23.843  7493  7493 I CustomizationCIDLoader: add string-array item, value = 27202:C:1:0
06-30 10:34:23.843  7493  7493 I CustomizationCIDLoader: add string-array item, value = 27216:C:1:0
06-30 10:34:23.843  7493  7493 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
06-30 10:34:23.843  7493  7493 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
06-30 10:34:23.843  7493  7493 I CustomizationCIDLoader: Parsing tag category name = AudioService
06-30 10:34:23.843  7493  7493 D CustomizationManager:  Read CID file spent 0.060 (s)
06-30 10:34:23.843  7493  7493 D CustomizationManager:  All configurations done spent 0.060 (s)
06-30 10:34:23.863   508   517 W PnPMgr  : Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
06-30 10:34:23.873  1121  3960 I ActivityManager: Resuming delayed broadcast
06-30 10:34:23.873  1121  3506 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=7468, uid=10114, userID:0
06-30 10:34:23.873  3443  3443 D TelephonyReceiver: bind: true
06-30 10:34:23.873  1121  1190 D Process : killProcessQuiet, pid=6652
06-30 10:34:23.873  1121  1190 I ActivityManager: Killing 6652:com.htc.cs.pns:boot_complete/u0a119 (adj 15): empty #17
06-30 10:34:23.873  7468  7530 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
06-30 10:34:23.873  1121  3460 E MountService: mkdirs when SD card not mounted/storage/ext_sd/Android/data/com.google.android.music/files/
06-30 10:34:23.873  1121  1190 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19304 
06-30 10:34:23.883  1121  3440 E MountService: mkdirs when SD card not mounted/storage/ext_sd/Android/data/com.google.android.music/files/
06-30 10:34:23.883  7468  7530 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
06-30 10:34:23.893  7468  7530 W ArtDownloadService: Setting cache size 0
06-30 10:34:23.933  3475  3854 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
06-30 10:34:23.953  1121  5139 I ActivityManager: Recipient 6652
06-30 10:34:23.983  7128  7128 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
06-30 10:34:23.993  1121  3506 I ActivityManager: Start proc 7540:com.htc.sense.mms/u0a54 for content provider com.htc.sense.mms/.util.GenericMessagesProvider
06-30 10:34:23.993  1121  3460 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 7493 on display 0
06-30 10:34:23.993  1121  1187 D PMS     : acquireHCC(7fb3fb4): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 1121 1000 null
06-30 10:34:23.993  1121  1187 D PMS     : acquireHCC(2c9b27dd): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 1121 1000 null
06-30 10:34:23.993  7540  7540 W HTCLOG  : use specified tag [FDManager], func [0].
06-30 10:34:23.993  7540  7540 W HTCLOG  : mask=0x18
06-30 10:34:24.003  1121  3460 V WindowManager: addAppToken: AppWindowToken{18e6a320 token=Token{29546223 ActivityRecord{36237f52 u0 com.test.thalitest/.MainActivity t101}}} to stack=1 task=101 at 0
06-30 10:34:24.003  1121  3460 D PMS     : acquireWL(2aa764d9): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 1121 1000 null
06-30 10:34:24.003  1121  1178 I AnimationUtil: isHTCRecent(ThaliTest/Recents screens.)/4
06-30 10:34:24.013  1121  1178 V WindowManager: Adding window Window{23dfd611 u0 Starting com.test.thalitest} at 2 of 7 (after Window{f74a0e7 u0 com.htc.launcher/com.htc.launcher.Launcher})
06-30 10:34:24.013  7493  7493 W HTCLOG  : use specified tag [IPCThreadState], func [0].
06-30 10:34:24.013  7493  7493 W HTCLOG  : mask=0x18
06-30 10:34:24.013  3475  3475 I FeedHostManager: [onPause]
06-30 10:34:24.013  1121  3754 I ActivityManager: Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
06-30 10:34:24.013  3475  3475 I FeedProviderManager: onPause
06-30 10:34:24.013  3475  3475 I FeedHostManager: [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@c6ca3b7
06-30 10:34:24.013  3475  4822 I SocialFeedProvider: +onPause
06-30 10:34:24.013  3475  4822 I SocialFeedProvider: -onPause
06-30 10:34:24.013  7128  7561 I DFPI.ApkInstallService: onHandleIntent
06-30 10:34:24.013  7128  7561 I DFPI.ApkInstallService: Media Scan Finished Case 
06-30 10:34:24.013  3475  3475 I ContextualWidget: onPause
06-30 10:34:24.013  3475  3475 I ContextualWidget: notifyWidgetDeactive
06-30 10:34:24.023  7493  7532 W HTCLOG  : use specified tag [Vector], func [0].
06-30 10:34:24.023  7493  7532 W HTCLOG  : mask=0x18
06-30 10:34:24.023  7493  7534 W HTCLOG  : use specified tag [Vector], func [0].
06-30 10:34:24.023  7493  7534 W HTCLOG  : mask=0x18
06-30 10:34:24.023  7128  7561 I DFPI.SystemPropertiesUtil: value = HTC__102
06-30 10:34:24.023  7128  7561 I DFPI.ApkInstallService: deviceCID = HTC__102
06-30 10:34:24.023  7128  7561 D DFPI.ApkInstallService: check CID = HTC__102
06-30 10:34:24.023  7128  7561 I DFPI.ApkInstallService: There is no Demo.apk in sd card or phone storage
06-30 10:34:24.023  3475  3854 W asset   : Copying FileAsset 0xac3bc5f0 (zip:/data/app/com.gameloft.android.gdc-1/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
06-30 10:34:24.043  1121  1141 I ActivityManager: Start proc 7562:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
06-30 10:34:24.053  1121  3522 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
06-30 10:34:24.053  1121  1140 I ActivityManager: Resuming delayed broadcast
06-30 10:34:24.053  7562  7562 W HTCLOG  : use specified tag [FDManager], func [0].
06-30 10:34:24.053  7562  7562 W HTCLOG  : mask=0x18
06-30 10:34:24.063  1121  1141 I ActivityManager: Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
06-30 10:34:24.073  7540  7540 D MessageFrequencyProvider: onCreate
06-30 10:34:24.073  3475  3475 I TrimMemoryManager: [trimMemory] 20
06-30 10:34:24.083  1121  1152 D StatusBarManagerService: setSystemUiVisibility(0x8600)
06-30 10:34:24.083  3475  3854 I Prism.WidgetManager: onLoadItems() -
06-30 10:34:24.083  1121  1152 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{23dfd611 u0 Starting com.test.thalitest}
06-30 10:34:24.083  3475  3854 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@39a45cb4 -
06-30 10:34:24.083  1121  1152 D StatusBarManagerService: hiding MENU key
06-30 10:34:24.083  3053  3053 I PhoneStatusBar: setSystemUiNavVisibility(swipe=false hasFocus=false hasPolicy=false shadeState=true)
06-30 10:34:24.083  3053  3053 I PhoneStatusBar: hiding the MENU button mLongPressHomeMenu = false
06-30 10:34:24.083  3443  4249 D PhoneApp: EVENT_QUERY_MO_PACKAGES
06-30 10:34:24.083  3443  4249 D PhoneApp: -- N1 =1
06-30 10:34:24.083  3443  4249 D PhoneApp: -- N2 =0
06-30 10:34:24.083  7540  7560 D GenericMessagesProvider: query uri: content://htc-messages/wappush/count
06-30 10:34:24.083  3443  4249 D PhoneApp: -- N3 =0
06-30 10:34:24.083  7540  7560 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
06-30 10:34:24.083  7540  7560 W HTCLOG  : mask=0x18
06-30 10:34:24.083  7540  7560 E SQLiteLog: (14) cannot open file at line 30046 of [9491ba7d73]
06-30 10:34:24.083  7540  7560 E SQLiteLog: (14) os_unix.c:30046: (2) open(/data/data/com.htc.sense.mms/databases/wappush.db) - 
06-30 10:34:24.083  7540  7540 D MessageCustFlag: sense_version=7.0
06-30 10:34:24.083  7540  7560 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
06-30 10:34:24.083  7540  7560 W HTCLOG  : mask=0x18
06-30 10:34:24.083  7540  7560 E SQLiteConnection: DB info: sqlite3_open_v2, path: /data/data/com.htc.sense.mms/databases/wappush.db, flag: 1, ret: 14
06-30 10:34:24.083  7540  7560 E SQLiteConnection: DB info: errno = 2, errno message = No such file or directory
06-30 10:34:24.093  7540  7560 E SQLiteDatabase: Failed to open database '/data/data/com.htc.sense.mms/databases/wappush.db'.
06-30 10:34:24.093  7540  7560 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
06-30 10:34:24.093  7540  7560 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 10:34:24.093  7540  7560 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 10:34:24.093  7540  7560 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 10:34:24.093  7540  7560 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 10:34:24.093  7540  7560 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
06-30 10:34:24.093  7540  7560 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
06-30 10:34:24.093  7540  7560 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
06-30 10:34:24.093  7540  7560 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
06-30 10:34:24.093  7540  7560 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
06-30 10:34:24.093  7540  7560 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:727)
06-30 10:34:24.093  7540  7560 E SQLiteDatabase: 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:279)
06-30 10:34:24.093  7540  7560 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:976)
06-30 10:34:24.093  7540  7560 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
06-30 10:34:24.093  7540  7560 E SQLiteDatabase: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
06-30 10:34:24.093  7540  7560 E SQLiteDatabase: 	at android.os.Binder.execTransact(Binder.java:454)
06-30 10:34:24.093  7540  7560 W System.err: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
06-30 10:34:24.093  7540  7560 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 10:34:24.093  7540  7560 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 10:34:24.093  7540  7560 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 10:34:24.093  7540  7560 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 10:34:24.093  7540  7560 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
06-30 10:34:24.093  7540  7560 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
06-30 10:34:24.093  7540  7560 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
06-30 10:34:24.093  7540  7560 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
06-30 10:34:24.093  7540  7560 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
06-30 10:34:24.093  7540  7560 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:727)
06-30 10:34:24.093  7540  7560 W System.err: 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:279)
06-30 10:34:24.093  7540  7560 W System.err: 	at android.content.ContentProvider.query(ContentProvider.java:976)
06-30 10:34:24.093  7540  7560 W System.err: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
06-30 10:34:24.093  7540  7560 W System.err: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
06-30 10:34:24.093  7540  7560 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
06-30 10:34:24.093  7540  7540 V GetPrviateResource: GetPrviateResource
06-30 10:34:24.093  7540  7540 V GetPrviateResource: GetPrviateResource
06-30 10:34:24.093  3443  3443 D TelephonyReceiver: switchBindHtcMsgCursor: null
06-30 10:34:24.093  7540  7540 D RcsChatUtils: isSup> false
06-30 10:34:24.093  7540  7540 D n       : createReceiver
06-30 10:34:24.093  7540  7540 D n       : registerReceiver return intent = null
06-30 10:34:24.103  7540  7540 W HtcThemeUtils: Can not get alternative color from specificInfo:C:0:0:0:0:0:0:0:0:0:0:0:0, with category(1)
06-30 10:34:24.103  7540  7540 W HtcThemeUtils: java.lang.IllegalArgumentException: Unknown color
06-30 10:34:24.103  7540  7540 W HtcThemeUtils: 	at android.graphics.Color.parseColor(Color.java:216)
06-30 10:34:24.103  7540  7540 W HtcThemeUtils: 	at com.htc.lib1.cc.util.HtcThemeUtils$CommonCategoryResources.setAlternativeColor(HtcThemeUtils.java:611)
06-30 10:34:24.103  7540  7540 W HtcThemeUtils: 	at com.htc.lib1.cc.util.HtcThemeUtils$CommonCategoryResources.checkResourceSrc(HtcThemeUtils.java:534)
06-30 10:34:24.103  7540  7540 W HtcThemeUtils: 	at com.htc.lib1.cc.util.HtcThemeUtils$CommonCategoryResources.createResourceInstance(HtcThemeUtils.java:486)
06-30 10:34:24.103  7540  7540 W HtcThemeUtils: 	at com.htc.lib1.cc.util.HtcThemeUtils$CommonCategoryResources.init(HtcThemeUtils.java:476)
06-30 10:34:24.103  7540  7540 W HtcThemeUtils: 	at com.htc.lib1.cc.util.HtcThemeUtils$CommonCategoryResources.access$600(HtcThemeUtils.java:451)
06-30 10:34:24.103  7540  7540 W HtcThemeUtils: 	at com.htc.lib1.cc.util.HtcThemeUtils.init(HtcThemeUtils.java:390)
06-30 10:34:24.103  7540  7540 W HtcThemeUtils: 	at com.htc.lib1.cc.util.HtcCommonUtil.initTheme(HtcCommonUtil.java:315)
06-30 10:34:24.103  7540  7540 W HtcThemeUtils: 	at com.htc.sense.mms.util.af.b(CommonActivityLayout.java:1003)
06-30 10:34:24.103  7540  7540 W HtcThemeUtils: 	at com.htc.sense.mms.MmsApp.onCreate(MmsApp.java:582)
06-30 10:34:24.103  7540  7540 W HtcThemeUtils: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1025)
06-30 10:34:24.103  7540  7540 W HtcThemeUtils: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4959)
06-30 10:34:24.103  7540  7540 W HtcThemeUtils: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
06-30 10:34:24.103  7540  7540 W HtcThemeUtils: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
06-30 10:34:24.103  7540  7540 W HtcThemeUtils: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:34:24.103  7540  7540 W HtcThemeUtils: 	at android.os.Looper.loop(Looper.java:155)
06-30 10:34:24.103  7540  7540 W HtcThemeUtils: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
06-30 10:34:24.103  7540  7540 W HtcThemeUtils: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 10:34:24.103  7540  7540 W HtcThemeUtils: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 10:34:24.103  7540  7540 W HtcThemeUtils: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
06-30 10:34:24.103  7540  7540 W HtcThemeUtils: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
06-30 10:34:24.113  7540  7540 W HTCLOG  : use specified tag [asset], func [0].
06-30 10:34:24.113  7540  7540 W HTCLOG  : mask=0x18
06-30 10:34:24.113  7540  7540 W asset   : Asset path /data/data/com.htc.launcher/files/.htc_theme/CResources.apk is neither a directory nor file (type=0).
06-30 10:34:24.113  7540  7540 D HtcThemeUtils: AssetMaanger addAssetPath CResources fail!
06-30 10:34:24.113  7540  7540 D HtcThemeUtils: Register com.htc.sense.mms.util.aj@d7bd0b for type 0
06-30 10:34:24.113  7540  7540 D HtcThemeUtils: Register com.htc.sense.mms.util.aj@d7bd0b for type 1
06-30 10:34:24.113  7540  7540 D HtcThemeUtils: Register com.htc.sense.mms.util.aj@d7bd0b for type 5
06-30 10:34:24.123  7562  7562 I WebViewFactory: Loading com.google.android.webview version 42.0.2311.137 (code 52311137)
06-30 10:34:24.173  7562  7562 I LibraryLoader: Time to load native libraries: 27 ms (timestamps 1088-1115)
06-30 10:34:24.173  7562  7562 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 10:34:24.183  7562  7562 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {25f45782}
06-30 10:34:24.183  7562  7562 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 10:34:24.193  7562  7562 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
06-30 10:34:24.193  7562  7562 I BrowserStartupController: Initializing chromium process, singleProcess=true
06-30 10:34:24.193  7562  7562 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 10:34:24.203  7562  7562 E SysUtils: ApplicationContext is null in ApplicationStatus
06-30 10:34:24.223  7562  7588 W chromium: [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,06-30 10:34:24.233  7562  7592 D BluetoothAdapter: 205459091: getState() :  mService = null. Returning STATE_OFF,
,06-30 10:34:24.233  7562  7562 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty(),
06-30 10:34:24.233  7562  7562 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50364 len=3345
06-30 10:34:24.233  7562  7562 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:9397000 len:1161174
,06-30 10:34:24.243  7562  7562 W HTCLOG  : use specified tag [libEGL], func [3].,
06-30 10:34:24.243  7562  7562 W HTCLOG  : mask=0x18
,06-30 10:34:24.243  7562  7562 W HTCLOG  : use specified tag [libEGL], func [3].,
06-30 10:34:24.243  7562  7562 W HTCLOG  : mask=0x18
06-30 10:34:24.243  7562  7562 I Adreno  : QUALCOMM build                   : 065751b, 
06-30 10:34:24.243  7562  7562 I Adreno  : Build Date                       : 04/15/15
06-30 10:34:24.243  7562  7562 I Adreno  : OpenGL ES Shader Compiler Version: E031.25.03.07
06-30 10:34:24.243  7562  7562 I Adreno  : Local Branch                     : 
06-30 10:34:24.243  7562  7562 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.1_rb2.9
06-30 10:34:24.243  7562  7562 I Adreno  : Remote Branch                    : NONE
06-30 10:34:24.243  7562  7562 I Adreno  : Reconstruct Branch               : AU_LINUX_ANDROID_LA.BF64.1.2.1_RB2.05.01.00.081.016 + 065751b +  NOTHING
,06-30 10:34:24.313  7562  7598 W chromium: [WARNING:data_reduction_proxy_config.cc(150)] SPDY proxy OFF at startup
,06-30 10:34:24.323  7562  7562 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,06-30 10:34:24.333  7562  7562 W AwContents: onDetachedFromWindow called when already detached. Ignoring,
,06-30 10:34:24.343  7562  7562 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC,
,06-30 10:34:24.353  7562  7562 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
06-30 10:34:24.353  7562  7562 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-30 10:34:24.373  7562  7610 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].,
06-30 10:34:24.373  7562  7610 W HTCLOG  : mask=0x18
,06-30 10:34:24.383  1121  3754 V WindowManager: Adding window Window{19de1df3 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{23dfd611 u0 Starting com.test.thalitest}),
,06-30 10:34:24.433  7562  7562 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
06-30 10:34:24.433  7562  7562 W HTCLOG  : use specified tag [ThreadedRenderer], func [0].
06-30 10:34:24.433  7562  7562 W HTCLOG  : mask=0x18
,06-30 10:34:24.433  7562  7562 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
06-30 10:34:24.433  7562  7562 W HTCLOG  : mask=0x18
,06-30 10:34:24.443  7562  7610 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
06-30 10:34:24.443  7562  7610 W HTCLOG  : mask=0x18
,06-30 10:34:24.443  7562  7610 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
06-30 10:34:24.443  7562  7610 W HTCLOG  : mask=0x18
06-30 10:34:24.443  7562  7610 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
06-30 10:34:24.443  7562  7610 W HTCLOG  : mask=0x18
,06-30 10:34:24.453  7562  7610 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
06-30 10:34:24.453  7562  7610 W HTCLOG  : mask=0x18
,06-30 10:34:24.453  7562  7610 W HTCLOG  : use specified tag [Surface], func [3].,
06-30 10:34:24.453  7562  7610 W HTCLOG  : mask=0x18
06-30 10:34:24.453  7562  7610 W HTCLOG  : use specified tag [GraphicBufferMapper], func [3].
06-30 10:34:24.453  7562  7610 W HTCLOG  : mask=0x18
,06-30 10:34:24.453  7562  7610 W HTCLOG  : use specified tag [qdmemalloc], func [0].
06-30 10:34:24.453  7562  7610 W HTCLOG  : mask=0x18
,06-30 10:34:24.493  7562  7562 I InputMethodManager: [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@27d5fefb, mServedView=org.apache.cordova.engine.SystemWebView{1af03b18 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@36daa971
,06-30 10:34:24.493  1121  1178 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +461ms
06-30 10:34:24.493  1121  3782 I InputMethodManagerService: Disable input method client, pid=3475
06-30 10:34:24.493  1121  3782 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
06-30 10:34:24.493  1121  3782 I InputMethodManagerService: Enable input method client, pid=7562
06-30 10:34:24.493  3053  3053 I PhoneStatusBar: setImeWindowStatus(false,false)
,06-30 10:34:24.503  1121  3766 D PMS     : releaseWL(2aa764d9): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,06-30 10:34:24.533  7562  7562 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7562,
,06-30 10:34:24.593  7562  7562 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,06-30 10:34:24.653  7562  7613 D jxcore_app_log: JniHelper::setJavaVM(0xaafbdb70), pthread_self() = -1410163424
,06-30 10:34:24.653  7562  7613 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-30 10:34:24.653  7562  7613 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-30 10:34:24.653  7562  7613 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-30 10:34:24.653  7562  7613 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-30 10:34:24.653  7562  7613 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
06-30 10:34:24.653  7562  7613 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32cf6365 added. We now have 1 listener(s)
,06-30 10:34:24.653  1121  3440 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,06-30 10:34:24.653  7562  7613 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 90:E7:C4:3C:62:6A,
06-30 10:34:24.653  7562  7613 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "90:E7:C4:3C:62:6A"
06-30 10:34:24.653  7562  7613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
06-30 10:34:24.653  7562  7613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,06-30 10:34:24.663  7562  7613 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: ,
06-30 10:34:24.663  7562  7613 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-30 10:34:24.663  7562  7613 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-30 10:34:24.663  7562  7613 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 90:E7:C4:3C:62:6A
06-30 10:34:24.663  7562  7613 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-30 10:34:24.663  7562  7613 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-30 10:34:24.663  7562  7613 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-30 10:34:24.663  7562  7613 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-30 10:34:24.663  7562  7613 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-30 10:34:24.663  7562  7613 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-30 10:34:24.663  7562  7613 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,06-30 10:34:24.663  7562  7613 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28f49a48 added. We now have 1 listener(s)
06-30 10:34:24.663  7562  7613 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,06-30 10:34:24.663  7562  7613 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved",
06-30 10:34:24.663  1121  2931 D WifiService: New client listening to asynchronous messages
06-30 10:34:24.663  7562  7613 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,06-30 10:34:24.663  7562  7613 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
,06-30 10:34:24.663  7562  7613 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
06-30 10:34:24.663  7562  7613 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
06-30 10:34:24.663  7562  7613 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
06-30 10:34:24.663  7562  7613 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-30 10:34:24.663  1121  3782 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
06-30 10:34:24.663  7562  7613 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 90:E7:C4:3C:62:6A
,06-30 10:34:24.663  7562  7613 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved",
06-30 10:34:24.663  7562  7613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 10:34:24.663  7562  7613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 10:34:24.663  7562  7613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-30 10:34:24.663  7562  7613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 10:34:24.663  7562  7613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false,
06-30 10:34:24.663  7562  7613 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 10:34:24.663  7562  7613 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 10:34:24.663  7562  7613 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 10:34:24.663  7562  7613 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
06-30 10:34:24.663  7562  7613 D io.jxcore.node.ConnectivityMonitor: start: OK
06-30 10:34:24.663  7562  7613 I io.jxcore.node.LifeCycleMonitor: start: OK
,06-30 10:34:24.703  7562  7562 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,06-30 10:34:24.813  7403  7464 D libc    : [NET] android_getaddrinfofornet+,hn 9(0x6c6f63616c686f),sn(),hints(known),family 0,flags 4
06-30 10:34:24.813  7403  7464 D libc    : [NET] android_getaddrinfofornet-, err=8
,06-30 10:34:24.843  1121  2886 V AlarmManager: sending alarm PendingIntent{b046fe0: PendingIntentRecord{323a1299 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1467275662883, Int=0
,06-30 10:34:24.993  1121  1187 D PMS     : releaseHCC(7fb3fb4): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,06-30 10:34:24.993  1121  1187 D PMS     : releaseHCC(2c9b27dd): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,06-30 10:34:25.093  1121  3628 I ActivityManager: Resuming delayed broadcast
,06-30 10:34:25.113  1121  3628 I ActivityManager: Start proc 7624:com.htc.music:musicenhancer/u0a25 for broadcast com.htc.music/com.htc.musicenhancer.provider.MScannerReceiver
,06-30 10:34:25.123  7624  7624 W HTCLOG  : use specified tag [FDManager], func [0].,
06-30 10:34:25.123  7624  7624 W HTCLOG  : mask=0x18
,06-30 10:34:25.173  1121  3460 I ActivityManager: Delay finish: com.htc.music/com.htc.musicenhancer.provider.MScannerReceiver
,06-30 10:34:25.263  7624  7624 D HtcThemeUtils: context=android.view.ContextThemeWrapper@5fc2ed0, category=3, byUser=false, userHandle=0,
,06-30 10:34:25.263  7624  7624 D HtcThemeUtils: [CC][checkIfNeedRecreate] mNeedRecreate=false, mCategoryRes=null, mCategoryTheme=null, sameDefRes=false
,06-30 10:34:25.273  7624  7624 W HtcThemeUtils: Can not get alternative color from specificInfo:C:0:0:0:0:0:0:0:0:0:0:0:0, with category(3)
06-30 10:34:25.273  7624  7624 W HtcThemeUtils: java.lang.IllegalArgumentException: Unknown color
06-30 10:34:25.273  7624  7624 W HtcThemeUtils: 	at android.graphics.Color.parseColor(Color.java:216)
,06-30 10:34:25.273  7624  7624 W HtcThemeUtils: 	at com.htc.lib1.cc.util.HtcThemeUtils$CommonCategoryResources.setAlternativeColor(HtcThemeUtils.java:594)
06-30 10:34:25.273  7624  7624 W HtcThemeUtils: 	at com.htc.lib1.cc.util.HtcThemeUtils$CommonCategoryResources.checkResourceSrc(HtcThemeUtils.java:513)
06-30 10:34:25.273  7624  7624 W HtcThemeUtils: 	at com.htc.lib1.cc.util.HtcThemeUtils$CommonCategoryResources.createResourceInstance(HtcThemeUtils.java:459)
06-30 10:34:25.273  7624  7624 W HtcThemeUtils: 	at com.htc.lib1.cc.util.HtcThemeUtils$CommonCategoryResources.init(HtcThemeUtils.java:449)
06-30 10:34:25.273  7624  7624 W HtcThemeUtils: 	at com.htc.lib1.cc.util.HtcThemeUtils$CommonCategoryResources.access$1400(HtcThemeUtils.java:424)
06-30 10:34:25.273  7624  7624 W HtcThemeUtils: 	at com.htc.lib1.cc.util.HtcThemeUtils.initInternal(HtcThemeUtils.java:1112)
06-30 10:34:25.273  7624  7624 W HtcThemeUtils: 	at com.htc.lib1.cc.util.HtcThemeUtils.init(HtcThemeUtils.java:1076)
06-30 10:34:25.273  7624  7624 W HtcThemeUtils: 	at com.htc.lib1.cc.util.HtcThemeUtils.init(HtcThemeUtils.java:365)
06-30 10:34:25.273  7624  7624 W HtcThemeUtils: 	at com.htc.lib1.cc.util.HtcCommonUtil.initTheme(HtcCommonUtil.java:372)
06-30 10:34:25.273  7624  7624 W HtcThemeUtils: 	at com.htc.musicenhancer.EnhancerService.onCreate(EnhancerService.java:302)
06-30 10:34:25.273  7624  7624 W HtcThemeUtils: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2901)
06-30 10:34:25.273  7624  7624 W HtcThemeUtils: 	at android.app.ActivityThread.access$1800(ActivityThread.java:151)
06-30 10:34:25.273  7624  7624 W HtcThemeUtils: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1473)
06-30 10:34:25.273  7624  7624 W HtcThemeUtils: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:34:25.273  7624  7624 W HtcThemeUtils: 	at android.os.Looper.loop(Looper.java:155)
06-30 10:34:25.273  7624  7624 W HtcThemeUtils: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
06-30 10:34:25.273  7624  7624 W HtcThemeUtils: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 10:34:25.273  7624  7624 W HtcThemeUtils: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 10:34:25.273  7624  7624 W HtcThemeUtils: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
06-30 10:34:25.273  7624  7624 W HtcThemeUtils: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
06-30 10:34:25.273  7624  7624 W HTCLOG  : use specified tag [ResourceType], func [0].
06-30 10:34:25.273  7624  7624 W HTCLOG  : mask=0x18
06-30 10:34:25.273  7624  7624 E ResourceType: Style contains key with bad entry: 0x01010504
,06-30 10:34:25.283  7624  7624 D HtcThemeUtils: context=android.view.ContextThemeWrapper@5fc2ed0, target=/data/data/com.htc.launcher/files/.htc_theme/CResources.apk,
,06-30 10:34:25.283  7624  7624 W HTCLOG  : use specified tag [asset], func [0].
06-30 10:34:25.283  7624  7624 W HTCLOG  : mask=0x18
06-30 10:34:25.283  7624  7624 W asset   : Asset path /data/data/com.htc.launcher/files/.htc_theme/CResources.apk is neither a directory nor file (type=0).
06-30 10:34:25.283  7624  7624 D HtcThemeUtils: AssetMaanger addAssetPath CResources fail!
06-30 10:34:25.283  7624  7624 D HtcThemeUtils: init done
,06-30 10:34:25.283  7624  7624 D HtcThemeUtils: Register com.htc.musicenhancer.EnhancerService$1@3c1469ce for type 1
,06-30 10:34:25.283  7624  7624 D HtcThemeUtils: Register com.htc.musicenhancer.EnhancerService$1@3c1469ce for type 0
,06-30 10:34:25.303  1121  3440 E MountService: mkdirs when SD card not mounted/storage/ext_sd/Android/data/com.htc.music/cache/
,06-30 10:34:25.303  7624  7653 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.music/cache
,06-30 10:34:25.333  1121  3440 I ActivityManager: Start proc 7656:com.htc.camera/u0a9 for content provider com.htc.camera/.CameraContentProvider
,06-30 10:34:25.353  7656  7656 W HTCLOG  : use specified tag [FDManager], func [0].,
06-30 10:34:25.353  7656  7656 W HTCLOG  : mask=0x18
,06-30 10:34:25.373  1121  5002 I art     : Explicit concurrent mark sweep GC freed 21341(1141KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.745ms total 150.037ms
,06-30 10:34:25.393  7562  7620 W jxcore-log: Initializing JXcore engine
,06-30 10:34:25.393  7562  7620 W jxcore-log: JXcore engine is ready
,06-30 10:34:25.443  7656  7656 V CameraProfiler: [PROFILE] Start timer 'CameraApplication.OnCreate.Start'
,06-30 10:34:25.443  7656  7676 W CameraApplication: getCustomizedBundle() - No data
,06-30 10:34:25.443  7562  7620 W jxcore-log: Starting JXcore engine
,06-30 10:34:25.453  7656  7676 W HTCLOG  : use specified tag [CameraBase], func [0].,
06-30 10:34:25.453  7656  7676 W HTCLOG  : mask=0x18
,06-30 10:34:25.483  7656  7676 W FeatureConfig: mIsRawPhotoSupported:true
,06-30 10:34:25.493  7656  7656 V CameraProfiler: [PROFILE] Start timer 'CameraApplication.OnCreate.End',
06-30 10:34:25.493  7656  7656 V CameraProfiler: [PROFILE][INTERVAL][CameraApplication.OnCreate.Start -> CameraApplication.OnCreate.End] 49.684 ms (49683906 ns)
,06-30 10:34:25.513  7370  7633 W MediaManager: [DualLensScanUtil],	mmpCursor count is 0
,06-30 10:34:25.513  1121  3782 D Process : killProcessQuiet, pid=6700
06-30 10:34:25.513  1121  3782 I ActivityManager: Killing 6700:tv.peel.app/u0a123 (adj 15): empty #17
06-30 10:34:25.513  1121  3782 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19304 
,06-30 10:34:25.523  7562  7620 W jxcore-log: Platform android
06-30 10:34:25.523  7562  7620 W jxcore-log: ,
06-30 10:34:25.523  7562  7620 W jxcore-log: Process ARCH arm
06-30 10:34:25.523  7562  7620 W jxcore-log: 
,06-30 10:34:25.533  1121  5139 I ActivityManager: Recipient 6700
,06-30 10:34:25.663  7562  7620 I jxcore-log: JXcore Cordova bridge is ready!
06-30 10:34:25.663  7562  7620 I jxcore-log: 
06-30 10:34:25.663  7562  7620 W jxcore-log: JXcore engine is started
,06-30 10:34:25.683  7562  7613 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,06-30 10:34:25.683  7562  7562 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,06-30 10:34:25.683  7562  7620 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
06-30 10:34:25.683  7562  7620 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,06-30 10:34:25.703  7562  7562 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57),
06-30 10:34:25.703  7562  7562 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,06-30 10:34:25.723  1121  3766 D PMS     : acquireWL(1797d409): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 1121 1000 null,
06-30 10:34:25.733  7562  7613 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 28ms. Plugin should use CordovaInterface.getThreadPool().
,06-30 10:34:25.743  7562  7562 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
06-30 10:34:25.743  7562  7562 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,06-30 10:34:25.753  1121  3522 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
,06-30 10:34:25.763  3475  3475 I FeedHostManager: [onResume],
06-30 10:34:25.763  3475  3475 I FeedProviderManager: onResume
06-30 10:34:25.763  3475  4822 I SocialFeedProvider: +onResume
06-30 10:34:25.763  3475  4822 I SocialFeedProvider: updateAccounts - Accounts is no change
06-30 10:34:25.763  3475  4822 I SocialFeedProvider: -onResume
06-30 10:34:25.763  3475  3475 I ConnectivityHelper: [getCurrentConnectionType] no network connection
,06-30 10:34:25.773  3475  3475 I ContextualWidget: onResume,
06-30 10:34:25.773  3475  3475 I ContextualWidget: notifyWidgetActive location size=0 user consent location=false
06-30 10:34:25.773  3475  3475 I ContextualWidget: ignore uploadUsageData location=false usage data=false allowAutoUpload=true
06-30 10:34:25.773  3475  3475 I ContextualWidget: postSyncRecommendedApps, isReady=true allowAutoSync=true syncMode=1 isEnableRecommend=true
06-30 10:34:25.773  3475  3992 I ContextualWidget: handleMessage, what=1018 mode=GettingOut maxcount=8,
,06-30 10:34:25.773  1121  1152 D StatusBarManagerService: setSystemUiVisibility(0x8700)
06-30 10:34:25.783  3053  3053 I PhoneStatusBar: setSystemUiNavVisibility(swipe=false hasFocus=false hasPolicy=false shadeState=true)
,06-30 10:34:25.773  1121  1152 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{f74a0e7 u0 com.htc.launcher/com.htc.launcher.Launcher}
06-30 10:34:25.783  3053  3053 I PhoneStatusBar: hiding the MENU button mLongPressHomeMenu = false
06-30 10:34:25.773  1121  1152 D StatusBarManagerService: hiding MENU key
06-30 10:34:25.783  3475  3475 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
06-30 10:34:25.783  3475  3475 I ThreadedRenderer: Defer allocateBuffers to drawing time
,06-30 10:34:25.783  1121  1140 I InputMethodManagerService: Disable input method client, pid=7562
06-30 10:34:25.783  3053  3053 I PhoneStatusBar: setImeWindowStatus(false,false)
06-30 10:34:25.783  1121  1140 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
06-30 10:34:25.783  1121  1140 I InputMethodManagerService: Enable input method client, pid=3475,
,06-30 10:34:25.793  7562  7562 W IInputConnectionWrapper: reportFullscreenMode on inactive InputConnection
,06-30 10:34:25.813  1121  3754 D PMS     : releaseWL(1797d409): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,06-30 10:34:25.823  1121  1152 D StatusBarManagerService: setSystemUiVisibility(0xc0000700)
06-30 10:34:25.823  3053  3053 I PhoneStatusBar: setSystemUiNavVisibility(swipe=false hasFocus=false hasPolicy=false shadeState=true)
06-30 10:34:25.823  1121  1152 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{f74a0e7 u0 com.htc.launcher/com.htc.launcher.Launcher}
,06-30 10:34:25.823  3053  3053 I PhoneStatusBar: hiding the MENU button mLongPressHomeMenu = false,
06-30 10:34:25.823  1121  1152 D StatusBarManagerService: hiding MENU key
,06-30 10:34:25.843  1121  1151 I ActivityManager: Killing 6769:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17,
06-30 10:34:25.843  1121  1151 D Process : killProcessQuiet, pid=6769
06-30 10:34:25.853  1121  1151 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityStack.destroyActivityLocked:3407 
,06-30 10:34:25.873  3475  4196 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467275665883
,06-30 10:34:25.923  7678  7678 W HTCLOG  : use specified tag [AndroidRuntime], func [0].
06-30 10:34:25.923  7678  7678 W HTCLOG  : mask=0x18
,06-30 10:34:25.963  1121  3782 I ActivityManager: Recipient 6769,
,06-30 10:34:25.983  3475  4196 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1467275665994
,06-30 10:34:25.993  3475  4744 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467275666010
,06-30 10:34:26.063  7562  7562 D io.jxcore.node.LifeCycleMonitor: onActivityStopped,
,06-30 10:34:26.063  7562  7562 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,06-30 10:34:26.063  7562  7562 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
06-30 10:34:26.063  7562  7562 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
06-30 10:34:26.063  7562  7562 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
06-30 10:34:26.063  7562  7562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
06-30 10:34:26.063  7562  7562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
06-30 10:34:26.063  7562  7562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
06-30 10:34:26.063  7562  7562 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32cf6365 removed from the list
06-30 10:34:26.063  7562  7562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
06-30 10:34:26.063  7562  7562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28f49a48 removed from the list
06-30 10:34:26.063  7562  7562 D io.jxcore.node.ConnectivityMonitor: stop
06-30 10:34:26.063  7562  7562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
06-30 10:34:26.063  7562  7562 I io.jxcore.node.LifeCycleMonitor: stop: OK
,06-30 10:34:26.093  3475  4744 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1467275666110,
,06-30 10:34:26.113  3475  4338 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467275666123
,06-30 10:34:26.123  7540  7540 D MessageUtils: [isPackageExists] packageName: com.htc.vvm.att does not exist
06-30 10:34:26.123  7540  7540 D MessageCustFlag: sku_id=118
,06-30 10:34:26.123  7540  7681 D Messaging: mNeedToUpdateDate2 start,
06-30 10:34:26.133  7540  7540 D ReportIndicatorCache: startAsyncQueryReports --- , first = true
,06-30 10:34:26.133  7540  7585 D ReportIndicatorCache: MSG_QUERY_REPORTS >>,
06-30 10:34:26.133  7540  7540 D SettingsManager: init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@304200ef
06-30 10:34:26.133  7540  7584 D MmsAsyncWorkHandler: 
06-30 10:34:26.133  7540  7584 D MmsAsyncWorkHandler: HM tk = 20002
06-30 10:34:26.133  7540  7540 D DraftCache: [DraftCache/1] DraftCache.constructor
,06-30 10:34:26.133  7540  7540 D DraftCache: [DraftCache/1] refresh
,06-30 10:34:26.133  3443  4032 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 75
06-30 10:34:26.133  3443  4032 D MmsSmsV2Provider:  slotId = -1
06-30 10:34:26.133  3443  4032 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: select _id,msg_id from addr where (type = 129 or type = 130 or type = 151) , selectionArgs: null
06-30 10:34:26.143  7540  7684 D MmsConfig: Start to get Carrier ID
,06-30 10:34:26.143  7562  7562 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7562
,06-30 10:34:26.143  7678  7689 W HTCLOG  : use specified tag [cutils-trace], func [0].
,06-30 10:34:26.143  7678  7689 W HTCLOG  : mask=0x18
06-30 10:34:26.143  7678  7689 E cutils-trace: Error opening trace file: Permission denied (13)
,06-30 10:34:26.153  7540  7540 D MmsConfig: networkCode: 
,06-30 10:34:26.153  3443  4032 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 75
06-30 10:34:26.153  3443  4032 D MmsSmsV2Provider:  slotId = -1
06-30 10:34:26.153  3443  4032 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,06-30 10:34:26.153  7540  7693 D Messaging: ViewCache CreatePreloadOnlyConversationList
,06-30 10:34:26.163  7540  7693 D MessageCustFlag: sense_version=7.0
,06-30 10:34:26.163  3443  3481 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
06-30 10:34:26.163  3443  3481 D MmsSmsV2Provider:  slotId = -1
06-30 10:34:26.163  3443  3481 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
06-30 10:34:26.163  7540  7540 D HfmClient: getIHFMServiceHMSApiLevel: +++
06-30 10:34:26.163  7540  7540 E HfmClient: Failed to load meta-data, NameNotFound: com.htc.hfm
06-30 10:34:26.163  7540  7540 E HfmClient: getIHFMServiceHMSApiLevel: load meta-data from HtcSpeak
06-30 10:34:26.163  7540  7683 I Messaging: mccmnc> 
,06-30 10:34:26.173  3443  3481 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
06-30 10:34:26.173  3443  3443 D IccSmsInterfaceManager: [IccSmsInterfaceManager] Cannot get carrier id
06-30 10:34:26.173  7540  7684 D MmsConfig: Carrier ID is NULL
06-30 10:34:26.173  7540  7540 D HfmClient: getIHFMServiceHMSApiLevel: Level = 1
,06-30 10:34:26.173  7540  7540 D HfmClient: HfmServiceHMS API Level = 1
,06-30 10:34:26.173  3443  4505 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 106
,06-30 10:34:26.173  7540  7693 D Jerry   : start to preload cursor >>>>>>>
,06-30 10:34:26.183  3443  4032 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 75
06-30 10:34:26.183  3443  4032 D MmsSmsV2Provider:  slotId = -1
06-30 10:34:26.183  3443  4032 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,06-30 10:34:26.193  7540  7681 D Messaging: mNeedToUpdateDate2: false
06-30 10:34:26.193  7540  7540 D ew      : createReceiver
06-30 10:34:26.193  3443  4497 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 105
06-30 10:34:26.193  3443  4497 D MmsSmsV2Provider:  slotId = -1
06-30 10:34:26.193  3443  4497 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,06-30 10:34:26.203  3443  3481 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
06-30 10:34:26.203  3443  3481 D MmsSmsV2Provider:  slotId = -1
06-30 10:34:26.203  7540  7682 D Messaging: mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,06-30 10:34:26.203  7540  7540 D HtcBuildUtils: getRATByHtcTelephonyCapability:1,
,06-30 10:34:26.213  3443  4497 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 105
06-30 10:34:26.213  7540  7703 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.sense.mms/files,
06-30 10:34:26.213  1121  3766 E MountService: mkdirs when SD card not mounted/storage/ext_sd/Android/data/com.htc.sense.mms/files/
,06-30 10:34:26.213  3475  4338 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1467275666226
,06-30 10:34:26.213  7540  7540 W SystemReader: Cannot find support_cw, use default value instead
06-30 10:34:26.223  7540  7703 D ew      : HtcStorageHelper.getPhoneStorageDir = /storage/emulated/0
06-30 10:34:26.223  7540  7540 W SystemReader: Cannot find qct_8960_interface, use default value instead
06-30 10:34:26.223  7540  7693 D Messaging: ViewCache CreatePreload
06-30 10:34:26.223  7540  7693 D Messaging: ViewCache CreatePreloadOnlyMultipleOpsList
06-30 10:34:26.223  7540  7703 D ew      : /storage/emulated/0 : mounted
06-30 10:34:26.223  1121  3506 E MountService: mkdirs when SD card not mounted/storage/ext_sd/Android/data/com.htc.sense.mms/files/
06-30 10:34:26.223  7540  7703 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.sense.mms/files
,06-30 10:34:26.223  3475  4195 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
06-30 10:34:26.223  3443  4505 D TelephUtils: UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 106
06-30 10:34:26.223  3443  4505 V MmsProvider: Update uri=content://mms, match=0
06-30 10:34:26.223  3443  4505 V MmsProvider: selection=st=129 AND m_type!=134
,06-30 10:34:26.233  7540  7705 D Messaging: Reset downloading state: 0
,06-30 10:34:26.233  7678  7678 D CustomizationManager: ====startRecUseTime====
06-30 10:34:26.233  7678  7678 D htc.customization.log.level:  is 
06-30 10:34:26.233  7678  7678 W CustomizationLogLevel: Level value is invalid, use default level 2
,06-30 10:34:26.243  3475  4196 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467275666251
,06-30 10:34:26.243  7540  7693 D Cust_MMSMS: _has_set_default_values_2=true
,06-30 10:34:26.243  7540  7693 D TextSizeManager: [get_list_body_TextSize]__size57
06-30 10:34:26.243  7540  7693 D TextSizeManager: [get_list_body_TextSize]__size48
06-30 10:34:26.243  7540  7693 D TextSizeManager: [get_list_body_TextSize]__size0
06-30 10:34:26.243  7540  7693 D TextSizeManager: [get_list_body_TextSize]__size57
06-30 10:34:26.243  7540  7693 D TextSizeManager: [get_list_body_TextSize]__size66
06-30 10:34:26.243  7540  7693 D TextSizeManager: [get_list_body_TextSize]__size74
06-30 10:34:26.243  7540  7693 D TextSizeManager: [get_list_body_TextSize]__size83
,06-30 10:34:26.253  7540  7705 V Messaging: Start TransactionService after 2 minutes from now
,06-30 10:34:26.253  7540  7693 D MsgPreferenceUtils: def_index: 0,
,06-30 10:34:26.263  7540  7584 D DraftCache: [DraftCache/126] rebuildCache,
,06-30 10:34:26.263  7540  7693 D MsgPreferenceUtils: globalIndex = 2,
,06-30 10:34:26.263  3443  4497 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 105
,06-30 10:34:26.263  3443  4497 D Jerry   : URI_DRAFT
06-30 10:34:26.263  1121  1190 E MountService: mkdirs when SD card not mounted/storage/ext_sd/Android/data/com.htc.sense.mms/files/
06-30 10:34:26.273  7540  7693 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.sense.mms/files
,06-30 10:34:26.273  7540  7584 D DraftCache: hasDraft() = false mNeedNotifyChange = true
06-30 10:34:26.273  7540  7584 D DraftCache: [DraftCache/126] rebuildCache time: 1
,06-30 10:34:26.273  1121  3907 E MountService: mkdirs when SD card not mounted/storage/ext_sd/Android/data/com.htc.sense.mms/files/
,06-30 10:34:26.273  7540  7693 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.sense.mms/files
,06-30 10:34:26.283  7540  7693 D MsgPreferenceUtils: phone state: true
,06-30 10:34:26.283  7540  7693 D MsgPreferenceUtils: sd state: false
06-30 10:34:26.283  7540  7693 D MsgPreferenceUtils: vIndex = 1
,06-30 10:34:26.313  3475  4193 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,06-30 10:34:26.313  7678  7678 D CustomizationManager:  Read ACC file spent 0.040 (s)
,06-30 10:34:26.313  7678  7678 D CIDMapFileReader: Parsing tag item name = HTC__001
06-30 10:34:26.313  7678  7678 D CIDMapFileReader: Parsing tag item name = HTC__002
06-30 10:34:26.313  7678  7678 D CIDMapFileReader: Parsing tag item name = HTC__016
06-30 10:34:26.313  7678  7678 D CIDMapFileReader: Parsing tag item name = HTC__031
06-30 10:34:26.313  7678  7678 D CIDMapFileReader: Parsing tag item name = HTC__032
06-30 10:34:26.313  7678  7678 D CIDMapFileReader: Parsing tag item name = HTC__102
06-30 10:34:26.313  7678  7678 D CIDMapFileReader: Parsing tag item name = HTC__A07
06-30 10:34:26.313  7678  7678 D CIDMapFileReader: Parsing tag item name = HTC__J15
06-30 10:34:26.313  7678  7678 D CIDMapFileReader: Parsing tag item name = HTC__M27
06-30 10:34:26.313  7678  7678 D CIDMapFileReader: Parsing tag item name = HTC__Y13
06-30 10:34:26.313  7678  7678 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__102.xml
06-30 10:34:26.313  7678  7678 I CustomizationCIDLoader: Parsing tag category name = application
06-30 10:34:26.313  7678  7678 I CustomizationCIDLoader: Parsing tag category name = system
06-30 10:34:26.313  7678  7678 I CustomizationCIDLoader: Parsing tag category name = Settings
06-30 10:34:26.313  7678  7678 I CustomizationCIDLoader: Parsing tag category name = ACC
06-30 10:34:26.313  7678  7678 I CustomizationCIDLoader: add string-array item, value = 42507
,06-30 10:34:26.313  7678  7678 I CustomizationCIDLoader: add string-array item, value = 21902
06-30 10:34:26.313  7678  7678 I CustomizationCIDLoader: add string-array item, value = 26006:26001.26002.26003
06-30 10:34:26.313  7678  7678 I CustomizationCIDLoader: add string-array item, value = 23420
06-30 10:34:26.313  7678  7678 I CustomizationCIDLoader: add string-array item, value = 22299
,06-30 10:34:26.313  7678  7678 I CustomizationCIDLoader: add string-array item, value = 24002
,06-30 10:34:26.313  7678  7678 I CustomizationCIDLoader: add string-array item, value = 23210,
06-30 10:34:26.313  7678  7678 I CustomizationCIDLoader: add string-array item, value = 23205
06-30 10:34:26.313  7678  7678 I CustomizationCIDLoader: add string-array item, value = 23806
,06-30 10:34:26.313  7678  7678 I CustomizationCIDLoader: add string-array item, value = 23430
06-30 10:34:26.313  7678  7678 I CustomizationCIDLoader: add string-array item, value = 23408
,06-30 10:34:26.313  7678  7678 I CustomizationCIDLoader: add string-array item, value = 27205
06-30 10:34:26.313  7678  7678 I CustomizationCIDLoader: add string-array item, value = 27202:27205
06-30 10:34:26.313  7678  7678 I CustomizationCIDLoader: add string-array item, value = 27216:27202.27205
06-30 10:34:26.313  7678  7678 I CustomizationCIDLoader: add string-array item, value = 42507:C:1:0
06-30 10:34:26.313  7678  7678 I CustomizationCIDLoader: add string-array item, value = 21902:C:1:0
06-30 10:34:26.313  7678  7678 I CustomizationCIDLoader: add string-array item, value = 26006:D:1:0
06-30 10:34:26.313  7678  7678 I CustomizationCIDLoader: add string-array item, value = 23420:D:0:0,
06-30 10:34:26.313  7678  7678 I CustomizationCIDLoader: add string-array item, value = 27205:C:1:0
06-30 10:34:26.313  7678  7678 I CustomizationCIDLoader: add string-array item, value = 22299:D:0:0
06-30 10:34:26.313  7678  7678 I CustomizationCIDLoader: add string-array item, value = 24002:D:0:0
06-30 10:34:26.313  7678  7678 I CustomizationCIDLoader: add string-array item, value = 23210:D:2:0
06-30 10:34:26.313  7678  7678 I CustomizationCIDLoader: add string-array item, value = 23205:D:2:0
06-30 10:34:26.313  7678  7678 I CustomizationCIDLoader: add string-array item, value = 23806:D:0:0
06-30 10:34:26.313  7678  7678 I CustomizationCIDLoader: add string-array item, value = 23430:C:1:0
06-30 10:34:26.313  7678  7678 I CustomizationCIDLoader: add string-array item, value = 23408:C:1:0
06-30 10:34:26.313  7678  7678 I CustomizationCIDLoader: add string-array item, value = 27202:C:1:0
06-30 10:34:26.313  7678  7678 I CustomizationCIDLoader: add string-array item, value = 27216:C:1:0
06-30 10:34:26.323  7678  7678 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
06-30 10:34:26.323  7678  7678 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
06-30 10:34:26.323  7678  7678 I CustomizationCIDLoader: Parsing tag category name = AudioService
06-30 10:34:26.323  7678  7678 D CustomizationManager:  Read CID file spent 0.083 (s)
06-30 10:34:26.323  7678  7678 D CustomizationManager:  All configurations done spent 0.083 (s)
,06-30 10:34:26.333  7540  7724 D RcsWorkingHandler: handler msg:{ when=-1ms what=1 target=com.htc.sense.mms.rcschat.bo }
06-30 10:34:26.333  7540  7724 D RcsWorkingHandler: not support Rcs, return
06-30 10:34:26.333  7540  7693 D PersonalizeUtils: isHTCThemeChange_full equal time= null,old=
06-30 10:34:26.333  7540  7693 D PersonalizeUtils: isHTCThemeChange_full isChange= false
,06-30 10:34:26.333  7540  7693 D PersonalizeUtils: isHTCThemeChange_wallpaper equal time= null,old=
06-30 10:34:26.333  7540  7693 D PersonalizeUtils: isHTCThemeChange_wallpaper isChange= false
06-30 10:34:26.333  7540  7693 D PersonalizeUtils: isHTCThemeChange_CC equal time= 1440293058,old=1440293058
06-30 10:34:26.333  7540  7693 D PersonalizeUtils: isHTCThemeChange_CC isChange= false
,06-30 10:34:26.343  3475  4196 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1467275666355
,06-30 10:34:26.353  1121  3506 D PackageManager: deletePackageAsUser: pkg=com.test.thalitest user=0, pid=7678, uid=2000
,06-30 10:34:26.353  1121  1151 D Process : killProcessQuiet, pid=7562
06-30 10:34:26.353  1121  1151 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
06-30 10:34:26.353  1121  1151 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.removeProcessLocked:6195 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5997 
06-30 10:34:26.353  1121  1151 I ActivityManager: Killing 7562:com.test.thalitest/u0a0 (adj 9): stop com.test.thalitest
,06-30 10:34:26.383  1121  1189 W PackageSettings: Skipping PackageSetting{34e9aa79 com.example.hello/10193} due to missing metadata,
,06-30 10:34:26.403   550   550 W HTCLOG  : use specified tag [Vector], func [0].
06-30 10:34:26.403  3475  4627 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467275666419
06-30 10:34:26.413   550   550 W HTCLOG  : mask=0x18
,06-30 10:34:26.433  1121  3460 I ActivityManager: Recipient 7562
06-30 10:34:26.433  1121  2931 D WifiService: Client connection lost with reason: 4
,06-30 10:34:26.433  3222  3222 W HTCLOG  : use specified tag [InputEventReceiver], func [0].
06-30 10:34:26.433  3222  3222 W HTCLOG  : mask=0x18
06-30 10:34:26.433  3222  3222 E InputEventReceiver: Looper::removeFd(33) is failed, result(0), input channel 'ClientState{1cb2a64f uid 10000 pid 7562} (c)'
,06-30 10:34:26.443  3475  3992 I ContextualWidget: handleMessage, what=1017 mode=GettingOut maxcount=8,
06-30 10:34:26.443  1121  3628 D LocationManagerService: getAllProviders()=[passive, gps, network]
,06-30 10:34:26.443  1121  3766 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
06-30 10:34:26.443  1121  3754 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,06-30 10:34:26.443  1121  3506 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,06-30 10:34:26.463  1121  1189 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,06-30 10:34:26.483  3166  3166 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
06-30 10:34:26.483  1121  3460 W ActivityManager: Spurious death for ProcessRecord{2239d36e 7562:com.test.thalitest/u0a0}, curProc for 7562: null
,06-30 10:34:26.483  3166  3166 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
06-30 10:34:26.483  4969  4969 I [MirrorLinkServer]MirrorLinkServer: Broadcast Received::Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
06-30 10:34:26.483  4969  4969 D [MirrorLinkServer]MirrorLinkServer: ACTION_PACKAGE_REMOVED intent received
,06-30 10:34:26.483  4969  4969 D [MirrorLinkServer]MirrorLinkServer: Counter : 1
06-30 10:34:26.483  4969  4969 D [MirrorLinkServer]MirrorLinkConnectionReceiver: notifyMlSevrer
06-30 10:34:26.483  1121  2926 V NetworkPolicy: ACTION_UID_REMOVED for uid=10000
,06-30 10:34:26.493  1121  1141 D PMS     : acquireWL(e5ffa9c): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 4213 10020 WorkSource{10020 com.google.android.gms}
,06-30 10:34:26.493  4213  4734 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
06-30 10:34:26.493  1121  2925 D PMS     : acquireWL(4b3b87a): PARTIAL_WAKE_LOCK  NetworkStats 0x1 1121 1000 null
06-30 10:34:26.503  1121  5139 D PMS     : releaseWL(e5ffa9c): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10020 com.google.android.gms}
06-30 10:34:26.503  3655  4097 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,06-30 10:34:26.503  4969  4969 I [MirrorLinkServer]MirrorLinkServer: onStartCommand() Action : android.intent.action.PACKAGE_REMOVED
06-30 10:34:26.503  4969  4969 D [MirrorLinkServer]MirrorLinkServer: Application Removed
06-30 10:34:26.503  4969  4969 D [MirrorLinkServer]MirrorLinkServer:  Application removed : com.test.thalitest
06-30 10:34:26.503  4969  4969 D [MirrorLinkServer]d: onApplicationRemoved
06-30 10:34:26.503  4969  4969 I [MirrorLinkServer]d: Package name found : com.test.thalitest
06-30 10:34:26.503  4969  7728 I [MirrorLinkServer]c: onApplicationUpdationCompleted, sending broadcast
06-30 10:34:26.503  3655  4097 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
06-30 10:34:26.503  1121  2920 W SystemReader: Cannot find grip_rejection_width, use default value instead
06-30 10:34:26.513  4969  4969 I [MirrorLinkServer]MirrorLinkServer: Broadcast Received::Intent { act=com.htc.HTCMirrorLinkServer.PACKAGE_UPDATE_COMPLETED }
06-30 10:34:26.513  4969  4969 D [MirrorLinkServer]MirrorLinkServer: ML_PACKAGE_UPDATE_COMPLETED intent received
06-30 10:34:26.513  4969  4969 D [MirrorLinkServer]MirrorLinkServer: Counter : 0
06-30 10:34:26.513  4969  4969 I [MirrorLinkServer]MirrorLinkConnectionReceiver: checkAndStopMLSession
06-30 10:34:26.513  4969  4969 I [MirrorLinkServer]MirrorLinkConnectionReceiver: Stopping Service
06-30 10:34:26.513  3655  4097 D AccTypeManager: Registering external account type=com.google.android.gm.exchange, packageName=com.google.android.gm
,06-30 10:34:26.523  3655  4097 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,06-30 10:34:26.533  1121  2925 D PMS     : releaseWL(4b3b87a): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
06-30 10:34:26.533  1121  2926 V NetworkPolicy: writePolicyLocked()
,06-30 10:34:26.533  3475  4627 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1467275666543
,06-30 10:34:26.533  3655  4097 E ExternalAccountType: Unsupported attribute readOnly
,06-30 10:34:26.543  1121  1150 I InputMethodManagerService: [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
06-30 10:34:26.543  3443  3443 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED,
,06-30 10:34:26.543  1121  2926 V NetworkPolicy: updateNetworkEnabledLocked()
,06-30 10:34:26.543  1121  2926 D NetworkPolicy: notifyPoliciesChangeLocked: no change
06-30 10:34:26.543  1121  2926 V NetworkPolicy: updateNotificationsLocked()
06-30 10:34:26.553  3475  4210 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
,06-30 10:34:26.563  3475  4744 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467275666579
,06-30 10:34:26.603  3475  7727 D HtcTelephonyManager: wrong phone slot in non-dual projects
,06-30 10:34:26.613  1121  1150 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,06-30 10:34:26.623  1121  1121 W PackageManager: Unable to load service info ResolveInfo{13e26bef com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
06-30 10:34:26.623  1121  1121 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
06-30 10:34:26.623  1121  1121 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:509)
06-30 10:34:26.623  1121  1121 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:345)
06-30 10:34:26.623  1121  1121 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:171)
06-30 10:34:26.623  1121  1121 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:71)
06-30 10:34:26.623  1121  1121 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:180)
06-30 10:34:26.623  1121  1121 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:927)
06-30 10:34:26.623  1121  1121 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
06-30 10:34:26.623  1121  1121 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
06-30 10:34:26.623  1121  1121 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
06-30 10:34:26.623  1121  1121 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:331)
06-30 10:34:26.623  1121  1121 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:232)
06-30 10:34:26.623  1121  1121 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 10:34:26.623  1121  1121 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 10:34:26.623  1121  1121 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
06-30 10:34:26.623  1121  1121 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
,06-30 10:34:26.653  1121  1189 I art     : Explicit concurrent mark sweep GC freed 23641(1799KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 17MB/26MB, paused 1.699ms total 161.053ms
,06-30 10:34:26.663  3475  4744 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1467275666679
,06-30 10:34:26.673  7678  7678 I art     : System.exit called, status: 0
,06-30 10:34:26.673  7678  7678 W HTCLOG  : use specified tag [Vector], func [0].
06-30 10:34:26.673  7678  7678 W HTCLOG  : mask=0x18
06-30 10:34:26.683  3475  4508 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467275666698
,06-30 10:34:26.723  3475  7727 D HtcTelephonyManager: wrong phone slot in non-dual projects
,06-30 10:34:26.733  3414  3414 D Nfc-Utils: isNxpCodebase: isNxp=false
,06-30 10:34:26.773  1121  1121 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,06-30 10:34:26.793  3475  3854 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
06-30 10:34:26.793  3475  3854 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,06-30 10:34:26.823  3475  4508 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1467275666834
,06-30 10:34:26.833  3475  4486 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
,06-30 10:34:26.853  3475  4195 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467275666860
,06-30 10:34:26.853  3475  4195 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml.bak
,06-30 10:34:26.923  3475  7727 D libc    : [NET] android_getaddrinfofornet+,hn 28(0x7265636f6d6d65),sn(),hints(known),family 0,flags 4
06-30 10:34:26.923  3475  7727 D libc    : [NET] android_getaddrinfofornet-, err=8
06-30 10:34:26.923  3475  7727 D libc    : [NET] android_getaddrinfofornet+,hn 28(0x7265636f6d6d65),sn(),hints(known),family 0,flags 1024
06-30 10:34:26.923  3475  7727 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
06-30 10:34:26.923  3475  7727 D libc    : [NET] android_getaddrinfo_proxy+,
06-30 10:34:26.923  3475  7727 D libc    : [NET] android_getaddrinfo_proxy get netid:0
06-30 10:34:26.923   526  7732 D libc    : [NET] android_getaddrinfofornet+,hn 28(0x7265636f6d6d65),sn(),hints(known),family 0,flags 1024
06-30 10:34:26.923   526  7732 D libc    : [NET] _dns_getaddrinfo+, netid:0, mark:917504
06-30 10:34:26.923   526  7732 D libc    : [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
06-30 10:34:26.923  3475  4195 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1467275666940
,06-30 10:34:26.933   526  7732 D libc    : [NET] android_getaddrinfofornet-, err=7,
06-30 10:34:26.933  3475  7727 D libc    : [NET] android_getaddrinfo_proxy-, NODATA
06-30 10:34:26.933  3475  7727 E ServerCorridor: BaseException: ServiceUnavailableException java.lang.Throwable: Unable to resolve host "recommend-prism.htcsense.com": No address associated with hostname
06-30 10:34:26.933  3475  7727 W System.err: com.htc.prism.feed.corridor.exceptions.ServiceUnavailableException: java.lang.Throwable: Unable to resolve host "recommend-prism.htcsense.com": No address associated with hostname
06-30 10:34:26.933  3475  7727 W System.err: 	at com.htc.prism.feed.corridor.RestClient.sendHTTPRequest(RestClient.java:192)
06-30 10:34:26.933  3475  7727 W System.err: 	at com.htc.prism.feed.corridor.RestClient.sendHTTPRequest(RestClient.java:98)
,06-30 10:34:26.933  3475  7727 W System.err: 	at com.htc.prism.feed.corridor.RestClient.getString(RestClient.java:367)
,06-30 10:34:26.933  3475  7727 W System.err: 	at com.htc.prism.feed.corridor.recommendation.RecommendationNService.getWelcomeAppSuggest(RecommendationNService.java:125)
06-30 10:34:26.933  3475  7727 W System.err: 	at com.htc.launcher.htcwidget.HtcContextualWidgetService.syncRecommendedApps(HtcContextualWidgetService.java:374)
06-30 10:34:26.933  3475  7727 W System.err: 	at com.htc.launcher.htcwidget.HtcContextualWidgetService.onHandleIntent(HtcContextualWidgetService.java:168)
06-30 10:34:26.933  3475  7727 W System.err: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
06-30 10:34:26.933  3475  7727 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,06-30 10:34:26.933  3475  7727 W System.err: 	at android.os.Looper.loop(Looper.java:155)
06-30 10:34:26.933  3475  7727 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:34:26.933  3475  7727 W System.err: Caused by: java.lang.Throwable: Unable to resolve host "recommend-prism.htcsense.com": No address associated with hostname
06-30 10:34:26.933  3475  7727 W System.err: 	at java.net.InetAddress.lookupHostByName(InetAddress.java:457)
06-30 10:34:26.933  3475  7727 W System.err: 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
06-30 10:34:26.933  3475  7727 W System.err: 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
06-30 10:34:26.933  3475  7727 W System.err: 	at com.android.okhttp.HostResolver$1.getAllByName(HostResolver.java:29)
06-30 10:34:26.933  3475  7727 W System.err: 	at com.android.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:232)
06-30 10:34:26.933  3475  7727 W System.err: 	at com.android.okhttp.internal.http.RouteSelector.next(RouteSelector.java:124)
06-30 10:34:26.933  3475  7727 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:272)
,06-30 10:34:26.933  3475  7727 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:211)
06-30 10:34:26.933  3475  7727 W System.err: 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:403)
,06-30 10:34:26.933  3475  7727 W System.err: 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.connect(HttpURLConnectionImpl.java:116)
06-30 10:34:26.933  3475  7727 W System.err: 	at com.android.okhttp.internal.http.DelegatingHttpsURLConnection.connect(DelegatingHttpsURLConnection.java:89)
06-30 10:34:26.933  3475  7727 W System.err: 	at com.android.okhttp.internal.http.HttpsURLConnectionImpl.connect(HttpsURLConnectionImpl.java:25)
06-30 10:34:26.933  3475  7727 W System.err: 	at com.htc.prism.feed.corridor.RestClient.sendHTTPRequest(RestClient.java:137)
06-30 10:34:26.933  3475  7727 W System.err: 	... 9 more
06-30 10:34:26.933  3475  3743 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/com.htc.launcher.prefs.contextualwidget.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/com.htc.launcher.prefs.contextualwidget.xml.bak
06-30 10:34:26.943  3475  4338 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467275666951
06-30 10:34:26.943  3475  4338 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml.bak
,06-30 10:34:26.993  3475  4338 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1467275667008
,06-30 10:34:27.003  3475  4759 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.,
,06-30 10:34:27.013  3475  4483 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467275667027,
06-30 10:34:27.023  3475  4483 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml.bak
,06-30 10:34:27.083  3475  4483 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1467275667097
,06-30 10:34:27.093  3475  4196 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467275667108,
06-30 10:34:27.103  3475  4196 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml.bak
,06-30 10:34:27.173  3475  4196 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1467275667183
,06-30 10:34:27.183  3475  4408 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
,06-30 10:34:27.193  3475  4210 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467275667204
,06-30 10:34:27.193  3475  4210 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml.bak
,06-30 10:34:27.253  3443  3637 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC >>
,06-30 10:34:27.253  3443  3637 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC <<
,06-30 10:34:27.263  3475  4210 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1467275667270
,06-30 10:34:27.273  3475  4627 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
,06-30 10:34:27.283  3475  4744 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467275667290
,06-30 10:34:27.283  3475  4744 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml.bak
,06-30 10:34:27.283  1121  2886 V AlarmManager: sending alarm PendingIntent{9def697: PendingIntentRecord{32db3084 android broadcastIntent}}, i=NextAlarmTracker.trigger, t=0, cnt=1, w=1467275667298, Int=0
06-30 10:34:27.283  1121  3960 I ActivityManager: Resuming delayed broadcast
06-30 10:34:27.293  1121  1121 D PMS     : acquireWL(3a34106d): PARTIAL_WAKE_LOCK  NextAlarmTracker 0x1 1121 1000 null
,06-30 10:34:27.313  1121  3960 I ActivityManager: Start proc 7733:com.htc.sdm/u0a64 for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver
,06-30 10:34:27.313  1121  3754 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.realtimechat.RequestWriter$NetworkStateReceiver, state=1, flag=1, pid=6551, uid=10102, userID:0,
,06-30 10:34:27.313  7733  7733 W HTCLOG  : use specified tag [FDManager], func [0].
06-30 10:34:27.313  1121  3754 F PackageManager: Unable to backup user packages state file, current changes will be lost at reboot
06-30 10:34:27.313  7733  7733 W HTCLOG  : mask=0x18
,06-30 10:34:27.323  1121  1151 E DropBoxManagerService: Can't write: system_server_wtf
06-30 10:34:27.323  1121  1151 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop27.tmp: open failed: EROFS (Read-only file system)
06-30 10:34:27.323  1121  1151 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 10:34:27.323  1121  1151 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 10:34:27.323  1121  1151 E DropBoxManagerService: 	,at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
06-30 10:34:27.323  1121  1151 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
06-30 10:34:27.323  1121  1151 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
06-30 10:34:27.323  1121  1151 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
06-30 10:34:27.323  1121  1151 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12689)
06-30 10:34:27.323  1121  1151 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12493)
06-30 10:34:27.323  1121  1151 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:12465)
06-30 10:34:27.323  1121  1151 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
06-30 10:34:27.323  1121  1151 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
06-30 10:34:27.323  1121  1151 E DropBoxManagerService: 	,at android.os.Looper.loop(Looper.java:155)
06-30 10:34:27.323  1121  1151 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:34:27.323  1121  1151 E DropBoxManagerService: ,	at com.android.server.ServiceThread.run(ServiceThread.java:46)
06-30 10:34:27.323  1121  1151 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 10:34:27.323  1121  1151 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
06-30 10:34:27.323  1121  1151 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 10:34:27.323  1121  1151 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 10:34:27.323  1121  1151 E DropBoxManagerService: 	... 13 more
,06-30 10:34:27.343  1121  1151 I ActivityManager: Waited long enough for: ServiceRecord{3a42357d u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService},
,06-30 10:34:27.363  3475  4744 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1467275667373
,06-30 10:34:27.373  7733  7733 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED,
06-30 10:34:27.373  3475  4294 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467275667383
,06-30 10:34:27.373  7733  7733 I SoundPicker: SoundPickerReceiver [onReceive] startService
,06-30 10:34:27.383  3475  4294 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml.bak,
06-30 10:34:27.383  1121  3460 I ActivityManager: Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,06-30 10:34:27.383  7733  7754 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) },
06-30 10:34:27.383  7733  7754 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
,06-30 10:34:27.393  7733  7754 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
,06-30 10:34:27.403  7733  7754 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm),
,06-30 10:34:27.403  7733  7754 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/132 type=1
06-30 10:34:27.403  7733  7754 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/132
06-30 10:34:27.403  7733  7754 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
,06-30 10:34:27.403  7733  7754 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/132 type=2
06-30 10:34:27.403  7733  7754 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/132
06-30 10:34:27.403  7733  7754 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
06-30 10:34:27.403  7733  7754 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/132 type=3
06-30 10:34:27.403  7733  7754 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/132
06-30 10:34:27.403  7733  7754 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
06-30 10:34:27.403  7733  7754 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/105 type=4
06-30 10:34:27.403  7733  7754 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/105
06-30 10:34:27.403  7733  7754 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
06-30 10:34:27.413  7733  7754 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/31 type=5
06-30 10:34:27.413  7733  7754 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/31
,06-30 10:34:27.413  7733  7754 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/103 type=6
,06-30 10:34:27.413  7733  7754 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/103
06-30 10:34:27.413  7733  7754 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/109 type=7
06-30 10:34:27.413  7733  7754 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/109
06-30 10:34:27.413  7733  7754 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=8
06-30 10:34:27.413  7733  7754 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
06-30 10:34:27.413  7733  7754 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/105 type=9
06-30 10:34:27.413  7733  7754 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/105
,06-30 10:34:27.423  1121  3766 I ActivityManager: Resuming delayed broadcast,
,06-30 10:34:27.433  1121  3506 I ActivityManager: Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
06-30 10:34:27.433  3475  4294 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1467275667449
,06-30 10:34:27.443  1121  3782 I ActivityManager: Resuming delayed broadcast
,06-30 10:34:27.453  1121  3782 I ActivityManager: Start proc 7758:com.htc.updater/u0a68 for broadcast com.htc.updater/.UpdaterReceiver
,06-30 10:34:27.463  3475  4369 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
,06-30 10:34:27.473  7758  7758 W HTCLOG  : use specified tag [FDManager], func [0].,
06-30 10:34:27.473  7758  7758 W HTCLOG  : mask=0x18
,06-30 10:34:27.473  3475  4508 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467275667485
,06-30 10:34:27.483  3475  4508 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml.bak
,06-30 10:34:27.533  1121  3782 I ActivityManager: Delay finish: com.htc.updater/.UpdaterReceiver,
,06-30 10:34:27.543  7758  7779 W HTCLOG  : use specified tag [SQLiteConnection], func [0].,
06-30 10:34:27.543  3475  4508 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1467275667555
06-30 10:34:27.543  7758  7779 W HTCLOG  : mask=0x18
,06-30 10:34:27.543  7758  7758 V UpdaterAPK | DownloadService: Service onStart
06-30 10:34:27.543  7758  7780 V UpdaterAPK | DownloadService: Updating for startId 1
,06-30 10:34:27.553  7758  7779 E SQLiteDatabase: Failed to open database '/data/data/com.htc.updater/databases/fota.db'.,
06-30 10:34:27.553  7758  7779 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 10:34:27.553  7758  7779 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 10:34:27.553  7758  7779 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 10:34:27.553  7758  7779 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 10:34:27.553  7758  7779 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 10:34:27.553  7758  7779 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
06-30 10:34:27.553  7758  7779 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
06-30 10:34:27.553  7758  7779 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
06-30 10:34:27.553  7758  7779 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
06-30 10:34:27.553  7758  7779 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752),
06-30 10:34:27.553  7758  7779 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
06-30 10:34:27.553  7758  7779 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-30 10:34:27.553  7758  7779 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 10:34:27.553  7758  7779 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
06-30 10:34:27.553  7758  7779 E SQLiteDatabase: 	at com.htc.updater.db.UpdaterProvider.query(UpdaterProvider.java:609)
06-30 10:34:27.553  7758  7779 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:976)
06-30 10:34:27.553  7758  7779 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
06-30 10:34:27.553  7758  7779 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:499)
06-30 10:34:27.553  7758  7779 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:443)
06-30 10:34:27.553  7758  7779 E SQLiteDatabase: 	at com.htc.updater.db.FOTASettings$NameValueCache.getString(FOTASettings.java:309)
06-30 10:34:27.553  7758  7779 E SQLiteDatabase: 	at com.htc.updater.db.FOTASettings.getString(FOTASettings.java:184)
06-30 10:34:27.553  7758  7779 E SQLiteDatabase: 	at com.htc.updater.db.FOTASettings.getBoolean(FOTASettings.java:256)
06-30 10:34:27.553  7758  7779 E SQLiteDatabase: 	at com.htc.updater.UpdaterReceiver$CheckActionThread.run(UpdaterReceiver.java:186)
,06-30 10:34:27.553  7758  7779 E SQLiteOpenHelper: Couldn't open fota.db for writing (will try read-only):
06-30 10:34:27.553  7758  7779 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 10:34:27.553  7758  7779 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 10:34:27.553  7758  7779 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 10:34:27.553  7758  7779 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 10:34:27.553  7758  7779 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 10:34:27.553  7758  7779 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
06-30 10:34:27.553  7758  7779 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
06-30 10:34:27.553  7758  7779 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
06-30 10:34:27.553  7758  7779 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
06-30 10:34:27.553  7758  7779 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
06-30 10:34:27.553  7758  7779 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
06-30 10:34:27.553  7758  7779 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-30 10:34:27.553  7758  7779 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 10:34:27.553  7758  7779 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
06-30 10:34:27.553  7758  7779 E SQLiteOpenHelper: 	at com.htc.updater.db.UpdaterProvider.query(UpdaterProvider.java:609)
06-30 10:34:27.553  7758  7779 E SQLiteOpenHelper: 	at android.content.ContentProvider.query(ContentProvider.java:976)
06-30 10:34:27.553  7758  7779 E SQLiteOpenHelper: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
06-30 10:34:27.553  7758  7779 E SQLiteOpenHelper: 	at android.content.ContentResolver.query(ContentResolver.java:499)
06-30 10:34:27.553  7758  7779 E SQLiteOpenHelper: 	at android.content.ContentResolver.query(ContentResolver.java:443)
06-30 10:34:27.553  7758  7779 E SQLiteOpenHelper: 	at com.htc.updater.db.FOTASettings$NameValueCache.getString(FOTASettings.java:309)
06-30 10:34:27.553  7758  7779 E SQLiteOpenHelper: 	at com.htc.updater.db.FOTASettings.getString(FOTASettings.java:184)
06-30 10:34:27.553  7758  7779 E SQLiteOpenHelper: 	at com.htc.updater.db.FOTASettings.getBoolean(FOTASettings.java:256)
06-30 10:34:27.553  7758  7779 E SQLiteOpenHelper: 	at com.htc.updater.UpdaterReceiver$CheckActionThread.run(UpdaterReceiver.java:186)
06-30 10:34:27.553  3475  4486 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467275667566
,06-30 10:34:27.553  7758  7780 E SQLiteDatabase: Failed to open database '/data/data/com.htc.updater/databases/downloads.db'.
06-30 10:34:27.553  7758  7780 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 10:34:27.553  7758  7780 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 10:34:27.553  7758  7780 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 10:34:27.553  7758  7780 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 10:34:27.553  7758  7780 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 10:34:27.553  7758  7780 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
06-30 10:34:27.553  7758  7780 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
06-30 10:34:27.553  7758  7780 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
06-30 10:34:27.553  7758  7780 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
06-30 10:34:27.553  7758  7780 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
06-30 10:34:27.553  7758  7780 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
06-30 10:34:27.553  7758  7780 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-30 10:34:27.553  7758  7780 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 10:34:27.553  7758  7780 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
06-30 10:34:27.553  7758  7780 E SQLiteDatabase: 	at com.htc.updater.download.DownloadProvider.query(DownloadProvider.java:1001)
06-30 10:34:27.553  7758  7780 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:976)
06-30 10:34:27.553  7758  7780 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
06-30 10:34:27.553  7758  7780 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:499)
06-30 10:34:27.553  7758  7780 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:443)
06-30 10:34:27.553  7758  7780 E SQLiteDatabase: 	at com.htc.updater.download.DownloadService.updateLocked(DownloadService.java:380)
06-30 10:34:27.553  7758  7780 E SQLiteDatabase: 	at com.htc.updater.download.DownloadService.access$200(DownloadService.java:79)
06-30 10:34:27.553  7758  7780 E SQLiteDatabase: 	at com.htc.updater.download.DownloadService$2.handleMessage(DownloadService.java:313)
06-30 10:34:27.553  7758  7780 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:98)
06-30 10:34:27.553  7758  7780 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
06-30 10:34:27.553  7758  7780 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 10:34:27.553  7758  7779 W SQLiteOpenHelper: Opened fota.db in read-only mode
06-30 10:34:27.553  7758  7780 E SQLiteOpenHelper: Couldn't open downloads.db for writing (will try read-only):
06-30 10:34:27.553  7758  7780 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 10:34:27.553  7758  7780 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 10:34:27.553  7758  7780 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 10:34:27.553  7758  7780 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 10:34:27.553  7758  7780 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 10:34:27.553  7758  7780 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
06-30 10:34:27.553  7758  7780 E SQLiteOpenHelper: ,	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
06-30 10:34:27.553  7758  7780 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
06-30 10:34:27.553  7758  7780 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
06-30 10:34:27.553  7758  7780 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
06-30 10:34:27.553  7758  7780 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
06-30 10:34:27.553  7758  7780 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-30 10:34:27.553  7758  7780 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 10:34:27.553  7758  7780 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
06-30 10:34:27.553  7758  7780 E SQLiteOpenHelper: 	at com.htc.updater.download.DownloadProvider.query(DownloadProvider.java:1001)
06-30 10:34:27.553  7758  7780 E SQLiteOpenHelper: ,	at android.content.ContentProvider.query(ContentProvider.java:976)
06-30 10:34:27.553  7758  7780 E SQLiteOpenHelper: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
06-30 10:34:27.553  7758  7780 E SQLiteOpenHelper: 	at android.content.ContentResolver.query(ContentResolver.java:499)
06-30 10:34:27.553  7758  7780 E SQLiteOpenHelper: 	,at android.content.ContentResolver.query(ContentResolver.java:443)
06-30 10:34:27.553  7758  7780 E SQLiteOpenHelper: 	at com.htc.updater.download.DownloadService.updateLocked(DownloadService.java:380)
06-30 10:34:27.553  7758  7780 E SQLiteOpenHelper: 	at com.htc.updater.download.DownloadService.access$200(DownloadService.java:79)
06-30 10:34:27.553  7758  7780 E SQLiteOpenHelper: 	at com.htc.updater.download.DownloadService$2.handleMessage(DownloadService.java:313)
06-30 10:34:27.553  7758  7780 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:98)
06-30 10:34:27.553  7758  7780 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:155)
06-30 10:34:27.553  7758  7780 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:34:27.563  3475  4486 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml.bak
06-30 10:34:27.563  7758  7780 W SQLiteOpenHelper: Opened downloads.db in read-only mode
,06-30 10:34:27.563  7758  7780 V UpdaterAPK | DownloadProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
06-30 10:34:27.563  7758  7779 V UpdaterAPK | DownloadProvider: starting query, database is not null; projection[0] is status; selection is update_type=?; selectionArgs[0] is FOTA; sort is null.
,06-30 10:34:27.573  7758  7780 V UpdaterAPK | DownloadProvider: created cursor android.database.sqlite.SQLiteCursor@d7bd0b on behalf of 7758
06-30 10:34:27.573  7758  7779 V UpdaterAPK | DownloadProvider: created cursor android.database.sqlite.SQLiteCursor@18f707e8 on behalf of 7758
,06-30 10:34:27.573  1121  3506 I ActivityManager: Resuming delayed broadcast
06-30 10:34:27.573  7758  7779 E UpdaterAPK | COTASettings: Can't set key cota_notify_download
06-30 10:34:27.573  7758  7779 E UpdaterAPK | COTASettings: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 10:34:27.573  7758  7779 E UpdaterAPK | COTASettings: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 10:34:27.573  7758  7779 E UpdaterAPK | COTASettings: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 10:34:27.573  7758  7779 E UpdaterAPK | COTASettings: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 10:34:27.573  7758  7779 E UpdaterAPK | COTASettings: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 10:34:27.573  7758  7779 E UpdaterAPK | COTASettings: 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:311)
06-30 10:34:27.573  7758  7779 E UpdaterAPK | COTASettings: 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:843)
06-30 10:34:27.573  7758  7779 E UpdaterAPK | COTASettings: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
06-30 10:34:27.573  7758  7779 E UpdaterAPK | COTASettings: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 10:34:27.573  7758  7779 E UpdaterAPK | COTASettings: 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:616)
06-30 10:34:27.573  7758  7779 E UpdaterAPK | COTASettings: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:338)
06-30 10:34:27.573  7758  7779 E UpdaterAPK | COTASettings: 	at android.content.ContentResolver.update(ContentResolver.java:1398)
06-30 10:34:27.573  7758  7779 E UpdaterAPK | COTASettings: 	at com.htc.updater.db.COTASettings$NameValueCache.putString(COTASettings.java:97)
06-30 10:34:27.573  7758  7779 E UpdaterAPK | COTASettings: 	at com.htc.updater.db.COTASettings.putString(COTASettings.java:153)
06-30 10:34:27.573  7758  7779 E UpdaterAPK | COTASettings: 	at com.htc.updater.db.COTASettings.putBoolean(COTASettings.java:167)
06-30 10:34:27.573  7758  7779 E UpdaterAPK | COTASettings: 	at com.htc.updater.UpdaterReceiver.checkConfirmStatus(UpdaterReceiver.java:725)
06-30 10:34:27.573  7758  7779 E UpdaterAPK | COTASettings: 	at com.htc.updater.UpdaterReceiver.access$200(UpdaterReceiver.java:57)
06-30 10:34:27.573  7758  7779 E UpdaterAPK | COTASettings: 	at com.htc.updater.UpdaterReceiver$CheckActionThread.run(UpdaterReceiver.java:198)
06-30 10:34:27.573  7758  7780 V UpdaterAPK | DownloadService: Nothing left; stopped
06-30 10:34:27.573  7758  7758 V UpdaterAPK | DownloadService: Service onDestroy
,06-30 10:34:27.573  1121  3754 D PMS     : acquireWL(1e67e5fa): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 7173 10008 null
,06-30 10:34:27.583  1121  3489 I ActivityManager: Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,06-30 10:34:27.593  1121  3506 E SQLiteDatabase: Failed to open database '/data/data/com.htc.checkinprovider/databases/htcCheckin.db'.
06-30 10:34:27.593  1121  3506 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 10:34:27.593  1121  3506 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 10:34:27.593  1121  3506 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 10:34:27.593  1121  3506 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 10:34:27.593  1121  3506 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 10:34:27.593  1121  3506 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
06-30 10:34:27.593  1121  3506 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
06-30 10:34:27.593  1121  3506 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
06-30 10:34:27.593  1121  3506 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
06-30 10:34:27.593  1121  3506 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
06-30 10:34:27.593  1121  3506 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
06-30 10:34:27.593  1121  3506 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 10:34:27.593  1121  3506 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
06-30 10:34:27.593  1121  3506 E SQLiteDatabase: 	at com.htc.checkinprovider.db.htcCheckinProvider.query(htcCheckinProvider.java:245)
06-30 10:34:27.593  1121  3506 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:976)
06-30 10:34:27.593  1121  3506 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
06-30 10:34:27.593  1121  3506 E SQLiteDatabase: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
06-30 10:34:27.593  1121  3506 E SQLiteDatabase: 	at android.os.Binder.execTransact(Binder.java:454)
06-30 10:34:27.593  7173  7783 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
06-30 10:34:27.593  1121  3460 D PMS     : releaseWL(1e67e5fa): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
06-30 10:34:27.593  1121  3506 E SQLiteOpenHelper: Couldn't open htcCheckin.db for writing (will try read-only):
06-30 10:34:27.593  1121  3506 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 10:34:27.593  1121  3506 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 10:34:27.593  1121  3506 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 10:34:27.593  1121  3506 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 10:34:27.593  1121  3506 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 10:34:27.593  1121  3506 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
06-30 10:34:27.593  1121  3506 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
06-30 10:34:27.593  1121  3506 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
06-30 10:34:27.593  1121  3506 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
06-30 10:34:27.593  1121  3,506 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
06-30 10:34:27.593  1121  3506 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
06-30 10:34:27.593  1121  3506 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 10:34:27.593  1121  3506 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
06-30 10:34:27.593  1121  3506 E SQLiteOpenHelper: 	at com.htc.checkinprovider.db.htcCheckinProvider.query(htcCheckinProvider.java:245)
06-30 10:34:27.593  1121  3506 E SQLiteOpenHelper: 	at android.content.ContentProvider.query(ContentProvider.java:976)
06-30 10:34:27.593  1121  3506 E SQLiteOpenHelper: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
06-30 10:34:27.593  1121  3506 E SQLiteOpenHelper: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
06-30 10:34:27.593  1121  3506 E SQLiteOpenHelper: 	at android.os.Binder.execTransact(Binder.java:454)
06-30 10:34:27.593  7173  7783 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
06-30 10:34:27.593  7173  7783 W HTCLOG  : mask=0x18
06-30 10:34:27.593  7173  7783 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.android.providers.calendar/databases/calendar.db, handle: 0x55858a0b80
06-30 10:34:27.593  7173  7783 W CalendarAlarmManager: runScheduleNextAlarm : SQLiteException,android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
06-30 10:34:27.593  7173  7783 W System.err: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
06-30 10:34:27.593  7173  7783 W System.err: 	at android.database.sqlite.SQLiteSession.throwIfNoTransaction(SQLiteSession.java:915)
06-30 10:34:27.593  7173  7783 W System.err: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:398)
06-30 10:34:27.593  7173  7783 W System.err: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:580)
06-30 10:34:27.593  7173  7783 W System.err: 	at com.android.providers.calendar.CalendarAlarmManager.runScheduleNextAlarm(CalendarAlarmManager.java:276)
06-30 10:34:27.593  7173  7783 W System.err: 	at com.android.providers.calendar.CalendarProviderIntentService.onHandleIntent(CalendarProviderIntentService.java:46)
06-30 10:34:27.593  7173  7783 W System.err: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
06-30 10:34:27.593  7173  7783 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:34:27.593  7173  7783 W System.err: 	at android.os.Looper.loop(Looper.java:155)
06-30 10:34:27.593  7173  7783 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:34:27.593  1121  3506 W SQLiteOpenHelper: Opened htcCheckin.db in read-only mode
06-30 10:34:27.623  3475  4486 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1467275667638
06-30 10:34:27.623  1121  5139 I ActivityManager: Killing 6551:com.google.android.talk/u0a102 (adj 15): empty #17
06-30 10:34:27.623  1121  5139 D Process : killProcessQuiet, pid=6551
06-30 10:34:27.623  1121  5139 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19304 
,06-30 10:34:27.633  3475  4351 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
,06-30 10:34:27.643  3475  4501 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467275667658,
,06-30 10:34:27.653  3475  4501 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml.bak
,06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: Can't set key backup_uri_string
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:311),
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:843)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:616)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:338)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.content.ContentResolver.update(ContentResolver.java:1398)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:295)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:198)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:181)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:71)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	,at android.os.Looper.loop(Looper.java:155)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: Can't set key download_sdcard
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: ,	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:311)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:843)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212),
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:616)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:338)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.content.ContentResolver.update(ContentResolver.java:1398)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:295)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updat,er.db.FOTASettings.putString(FOTASettings.java:198)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.db.FOTASettings.putBoolean(FOTASettings.java:279)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:182)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:71)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	,at android.os.Looper.loop(Looper.java:155)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: Can't set key fota_prompt_version
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:311)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:843)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
,06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:616)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:338)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.content.ContentResolver.update(ContentResolver.java:1398)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:295)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:198)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:183)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:71)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.os.Looper.loop(Looper.java:155)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: Can't set key fota_prompt_feature
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:311)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:843)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
,06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:616)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:338)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.content.ContentResolver.update(ContentResolver.java:1398)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:295)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:198)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:184)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:71)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.os.Looper.loop(Looper.java:155)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: Can't set key fota_prompt_size
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:311)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:843)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:616)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:338)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.content.ContentResolver.update(ContentResolver.java:1398)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:295)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:198)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:185)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	,at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:71)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.os.Looper.loop(Looper.java:155)
06-30 10:34:27.653  7758  7782 E UpdaterAPK | FOTASettings: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: Can't set key fota_force_update
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:311)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:843)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:616)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:338)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.content.ContentResolver.update(ContentResolver.java:1398)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:295)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:198)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:186)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:71)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.os.Looper.loop(Looper.java:155)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: Can't set key fota_notify_download
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 10:34:27.663  7,758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:311)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:843)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:616)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:338)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.content.ContentResolver.update(ContentResolver.java:1398)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:295)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:198)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.db.FOTASettings.putBoolean(FOTASettings.java:279)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:187)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:71)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.os.Looper.loop(Looper.java:155)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: Can't set key fota_need_token
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:311)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:843)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:616)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:338)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.content.ContentResolver.update(ContentResolver.java:1398)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:295)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:198)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.db.FOTASettings.putBoolean(FOTASettings.java:279)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:190)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:71)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.os.Looper.loop(Looper.java:155)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: Can't set key fota_reserve_data_size
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:311)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:843)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:616)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:338)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.content.ContentResolver.update(ContentResolver.java:1398)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:295)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:198)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.db.FOTASettings.putInt(FOTASettings.java:238)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:195)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:71)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.os.Looper.loop(Looper.java:155)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: Can't set key fota_package_download_via_wifi
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:311)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:843)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:616)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:338)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.content.ContentResolver.update(ContentResolver.java:1398)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:295)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:198)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.db.FOTASettings.putBoolean(FOTASettings.java:279)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:201)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:71)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.os.Looper.loop(Looper.java:155)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: Can't set key fota_prompt_message
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:311)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:843)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:616)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:338)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.content.ContentResolver.update(ContentResolver.java:1398)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:295)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:198)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:203)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:71)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.os.Looper.loop(Looper.java:155)
06-30 10:34:27.663  7758  7782 E UpdaterAPK | FOTASettings: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:34:27.703  3475  4501 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1467275667716
,06-30 10:34:27.713  3475  4195 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
06-30 10:34:27.723  3475  4759 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
06-30 10:34:27.733  3475  4483 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
06-30 10:34:27.743  3475  4408 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
06-30 10:34:27.753  3475  4627 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
,06-30 10:34:27.753  1121  3460 I ActivityManager: Recipient 6551
,06-30 10:34:27.763  3475  4744 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
,06-30 10:34:27.763  3475  4369 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
,06-30 10:34:27.773  3475  4508 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
,06-30 10:34:27.783  3475  4351 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.,
,06-30 10:34:27.843  7758  7782 W HtcThemeUtils: Can not get alternative color from specificInfo:C:0:0:0:0:0:0:0:0:0:0:0:0, with category(0)
06-30 10:34:27.843  7758  7782 W HtcThemeUtils: java.lang.IllegalArgumentException: Unknown color
06-30 10:34:27.843  7758  7782 W HtcThemeUtils: 	,at android.graphics.Color.parseColor(Color.java:216)
06-30 10:34:27.843  7758  7782 W HtcThemeUtils: 	at com.htc.lib1.cc.util.HtcThemeUtils$CommonCategoryResources.setAlternativeColor(HtcThemeUtils.java:611)
06-30 10:34:27.843  7758  7782 W HtcThemeUtils: 	at com.htc.lib1.cc.util.HtcThemeUtils$CommonCategoryResources.checkResourceSrc(HtcThemeUtils.java:534)
06-30 10:34:27.843  7758  7782 W HtcThemeUtils: 	at com.htc.lib1.cc.util.HtcThemeUtils$CommonCategoryResources.createResourceInstance(HtcThemeUtils.java:486)
06-30 10:34:27.843  7758  7782 W HtcThemeUtils: 	at com.htc.lib1.cc.util.HtcThemeUtils$CommonCategoryResources.init(HtcThemeUtils.java:476),
06-30 10:34:27.843  7758  7782 W HtcThemeUtils: 	at com.htc.lib1.cc.util.HtcThemeUtils$CommonCategoryResources.access$600(HtcThemeUtils.java:451)
06-30 10:34:27.843  7758  7782 W HtcThemeUtils: 	at com.htc.lib1.cc.util.HtcThemeUtils.init(HtcThemeUtils.java:390)
06-30 10:34:27.843  7758  7782 W HtcThemeUtils: 	at com.htc.lib1.cc.util.HtcCommonUtil.initTheme(HtcCommonUtil.java:315)
06-30 10:34:27.843  7758  7782 W HtcThemeUtils: 	at com.htc.updater.util.NotificationUtil.getNotificationThemeColor(NotificationUtil.java:472)
06-30 10:34:27.843  7758  7782 W HtcThemeUtils: ,	at com.htc.updater.util.NotificationUtil.notifyDownload(NotificationUtil.java:152)
06-30 10:34:27.843  7758  7782 W HtcThemeUtils: 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:259)
06-30 10:34:27.843  7758  7782 W HtcThemeUtils: 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:71)
06-30 10:34:27.843  7758  7782 W HtcThemeUtils: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
06-30 10:34:27.843  7758  7782 W HtcThemeUtils: 	,at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:34:27.843  7758  7782 W HtcThemeUtils: 	at android.os.Looper.loop(Looper.java:155)
06-30 10:34:27.843  7758  7782 W HtcThemeUtils: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:34:27.853  7758  7782 W HTCLOG  : use specified tag [asset], func [0].
,06-30 10:34:27.853  7758  7782 W HTCLOG  : mask=0x18
,06-30 10:34:27.853  7758  7782 W asset   : Asset path /data/data/com.htc.launcher/files/.htc_theme/CResources.apk is neither a directory nor file (type=0).
06-30 10:34:27.853  7758  7782 D HtcThemeUtils: AssetMaanger addAssetPath CResources fail!
,06-30 10:34:27.863  1121  2886 I ActivityManager: Start proc 7785:com.htc.mobiledata:remote/u0a39 for service com.htc.mobiledata/.MobileDataService
06-30 10:34:27.863  1121  2886 V AlarmManager: sending alarm PendingIntent{2554b387: PendingIntentRecord{152dc2b4 com.htc.mobiledata startService}}, i=com.htc.mobiledata.intent.REQUEST, t=2, cnt=1, w=54626, Int=0
,06-30 10:34:27.863  1121  2886 V AlarmManager: sending alarm PendingIntent{106eedd: PendingIntentRecord{28a93a52 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=54638, Int=0
,06-30 10:34:27.863  7785  7785 W HTCLOG  : use specified tag [FDManager], func [0].
06-30 10:34:27.863  7785  7785 W HTCLOG  : mask=0x18
,06-30 10:34:27.863  1121  1121 D ValidateNoPeople: setContact(com.htc.updater,0.0,false)
,06-30 10:34:27.873  1121  1121 D PMS     : acquireWL(d3f0123): PARTIAL_WAKE_LOCK  *vibrator* 0x1 1121 1000 WorkSource{10068}
,06-30 10:34:27.873  7758  7782 E UpdaterAPK | FOTASettings: Can't set key fota_optional
06-30 10:34:27.873  7758  7782 E UpdaterAPK | FOTASettings: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 10:34:27.873  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 10:34:27.873  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 10:34:27.873  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 10:34:27.873  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 10:34:27.873  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:311)
06-30 10:34:27.873  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:843)
06-30 10:34:27.873  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
06-30 10:34:27.873  7758  7782 E UpdaterAPK | FOTASettings: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 10:34:27.873  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:616)
06-30 10:34:27.873  7758  7782 E UpdaterAPK | FOTASettings: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:338)
06-30 10:34:27.873  7758  7782 E UpdaterAPK | FOTASettings: 	at android.content.ContentResolver.update(ContentResolver.java:1398)
06-30 10:34:27.873  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:295)
06-30 10:34:27.873  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:198)
06-30 10:34:27.873  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:283)
06-30 10:34:27.873  7758  7782 E UpdaterAPK | FOTASettings: 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:71)
06-30 10:34:27.873  7758  7782 E UpdaterAPK | FOTASettings: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
06-30 10:34:27.873  7758  7782 E UpdaterAPK | FOTASettings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:34:27.873  7758  7782 E UpdaterAPK | FOTASettings: 	at android.os.Looper.loop(Looper.java:155)
06-30 10:34:27.873  7758  7782 E UpdaterAPK | FOTASettings: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:34:27.873  1121  3907 I ActivityManager: Resuming delayed broadcast
06-30 10:34:27.883  3166  3207 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837684, tag: null, isClearable: false, isForDotMatrix: false
06-30 10:34:27.893  7807  7807 W HTCLOG  : use specified tag [FDManager], func [0].
06-30 10:34:27.893  7807  7807 W HTCLOG  : mask=0x18
06-30 10:34:27.903  3053  3053 I RemoteViews: apply:com.htc.updater 0 12 2 37
06-30 10:34:27.903  1121  3907 I ActivityManager: Start proc 7807:com.htc.autobot/u0a27 for broadcast com.htc.autobot/.AlarmReceiver
06-30 10:34:27.903  1121  3628 D Process : killProcessQuiet, pid=6790
06-30 10:34:27.903  1121  3628 I ActivityManager: Killing 6790:com.android.smith/1000 (adj 15): empty #17
06-30 10:34:27.903  1121  3628 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19304 
,06-30 10:34:27.913  3053  3053 I NotificationStackScrollLayout: setBlockTouchEnabled:false
06-30 10:34:27.923   574   574 I art     : Explicit concurrent mark sweep GC freed 8644(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 163KB/4MB, paused 123us total 25.022ms,
,06-30 10:34:27.943   574   574 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 163KB/4MB, paused 103us total 17.473ms
,06-30 10:34:27.963   574   574 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 163KB/4MB, paused 105us total 17.783ms
,06-30 10:34:28.013  1121  3440 I ActivityManager: Recipient 6790,
,06-30 10:34:28.083   499   499 E qdoverlay: Cant open device /dev/graphics/fb0 err=108
06-30 10:34:28.083   499   499 E qdoverlay: Ctrl failed to init fbnum=0
06-30 10:34:28.083   499   499 E qdoverlay: Cant open device /dev/graphics/fb0 err=108
06-30 10:34:28.083   499   499 E qdoverlay: Ctrl failed to init fbnum=0
06-30 10:34:28.083   499   499 E qdoverlay: Cant open device /dev/graphics/fb0 err=108
06-30 10:34:28.083   499   499 E qdoverlay: Ctrl failed to init fbnum=0
06-30 10:34:28.083   499   499 E qdoverlay: Cant open device /dev/graphics/fb0 err=108
06-30 10:34:28.083   499   499 E qdoverlay: Ctrl failed to init fbnum=0
06-30 10:34:28.083   499   499 E qdoverlay: Cant open device /dev/graphics/fb0 err=108
06-30 10:34:28.083   499   499 E qdoverlay: Ctrl failed to init fbnum=0
06-30 10:34:28.083   499   499 E qdoverlay: Cant open device /dev/graphics/fb0 err=108
06-30 10:34:28.083   499   499 E qdoverlay: Ctrl failed to init fbnum=0
06-30 10:34:28.083   499   499 E qdoverlay: validateAndSet failed, error 108: Cannot send after transport endpoint shutdown
06-30 10:34:28.083   499   499 E qdoverlay: Bad ov dump:  mdp_overlay z=0 alpha=255 mask=-1 flags=0x0 id=8
06-30 10:34:28.083   499   499 E qdoverlay: src msmfb_img w=2176 h=1920 format=15 MDP_RGBX_8888
,06-30 10:34:28.083   499   499 E qdoverlay: src_rect mdp_rect x=540 y=0 w=1080 h=1920
06-30 10:34:28.083   499   499 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
06-30 10:34:28.083   499   499 E qdoverlay: Cant open device /dev/graphics/fb0 err=108
06-30 10:34:28.083   499   499 E qdoverlay: Ctrl failed to init fbnum=0
06-30 10:34:28.083   499   499 E qdoverlay: Cant open device /dev/graphics/fb0 err=108
06-30 10:34:28.083   499   499 E qdoverlay: Ctrl failed to init fbnum=0
,06-30 10:34:28.083   499   499 E qdoverlay: Cant open device /dev/graphics/fb0 err=108
06-30 10:34:28.083   499   499 E qdoverlay: Ctrl failed to init fbnum=0
,06-30 10:34:28.083   499   499 E qdoverlay: Cant open device /dev/graphics/fb0 err=108
06-30 10:34:28.083   499   499 E qdoverlay: Ctrl failed to init fbnum=0
06-30 10:34:28.083   499   499 E qdoverlay: Cant open device /dev/graphics/fb0 err=108
06-30 10:34:28.083   499   499 E qdoverlay: Ctrl failed to init fbnum=0
06-30 10:34:28.083   499   499 E qdoverlay: Cant open device /dev/graphics/fb0 err=108
06-30 10:34:28.083   499   499 E qdoverlay: Ctrl failed to init fbnum=0
06-30 10:34:28.083   499   499 E qdoverlay: validateAndSet failed, error 108: Cannot send after transport endpoint shutdown
06-30 10:34:28.083   499   499 E qdoverlay: Bad ov dump:  mdp_overlay z=0 alpha=255 mask=-1 flags=0x0 id=8
06-30 10:34:28.083   499   499 E qdoverlay: src msmfb_img w=2176 h=1920 format=15 MDP_RGBX_8888
06-30 10:34:28.083   499   499 E qdoverlay: src_rect mdp_rect x=540 y=75 w=1080 h=1701
06-30 10:34:28.083   499   499 E qdoverlay: dst_rect mdp_rect x=0 y=75 w=1080 h=1701
06-30 10:34:28.083   499   499 E qdoverlay: Cant open device /dev/graphics/fb0 err=108
06-30 10:34:28.083   499   499 E qdoverlay: Ctrl failed to init fbnum=0
06-30 10:34:28.083   499   499 E qdoverlay: Cant open device /dev/graphics/fb0 err=108
06-30 10:34:28.083   499   499 E qdoverlay: Ctrl failed to init fbnum=0
06-30 10:34:28.083   499   499 E qdoverlay: validateAndSet failed, error 108: Cannot send after transport endpoint shutdown
06-30 10:34:28.083   499   499 E qdoverlay: Bad ov dump:  mdp_overlay z=0 alpha=255 mask=-1 flags=0x220000 id=8
06-30 10:34:28.083   499   499 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
06-30 10:34:28.083   499   499 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
06-30 10:34:28.083   499   499 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
06-30 10:34:28.083   499   499 E qdoverlay: Cant open device /dev/graphics/fb0 err=108
06-30 10:34:28.083   499   499 E qdoverlay: Ctrl failed to init fbnum=0
06-30 10:34:28.083   499   499 E qdoverlay: Cant open device /dev/graphics/fb0 err=108
06-30 10:34:28.083   499   499 E qdoverlay: Ctrl failed to init fbnum=0
06-30 10:34:28.083   499   499 E qdoverlay: Cant open device /dev/graphics/fb0 err=108
06-30 10:34:28.083   499   499 E qdoverlay: Ctrl failed to init fbnum=0
06-30 10:34:28.083   499   499 E qdoverlay: Cant open device /dev/graphics/fb0 err=108
06-30 10:34:28.083   499   499 E qdoverlay: Ctrl failed to init fbnum=0
06-30 10:34:28.083   499   499 E qdoverlay: validateAndSet failed, error 108: Cannot send after transport endpoint shutdown
06-30 10:34:28.083   499   499 E qdoverlay: Bad ov dump:  mdp_overlay z=2 alpha=255 mask=-1 flags=0x220000 id=8
06-30 10:34:28.083   499   499 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
06-30 10:34:28.083   499   499 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
06-30 10:34:28.083   499   499 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
06-30 10:34:28.083   499   499 E qdoverlay: Cant open device /dev/graphics/fb0 err=108
06-30 10:34:28.083   499   499 E qdoverlay: Ctrl failed to init fbnum=0
06-30 10:34:28.083   499   499 E qdoverlay: Cant open device /dev/graphics/fb0 err=108
06-30 10:34:28.083   499   499 E qdoverlay: Ctrl failed to init fbnum=0
06-30 10:34:28.083   499   499 E qdoverlay: validateAndSet failed, error 108: Cannot send after transport endpoint shutdown
06-30 10:34:28.083   499   499 E qdoverlay: Bad ov dump:  mdp_overlay z=1 alpha=255 mask=-1 flags=0x220000 id=8
06-30 10:34:28.083   499   499 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
06-30 10:34:28.083   499   499 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
06-30 10:34:28.083   499   499 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
06-30 10:34:28.083   499   499 E qdoverlay: validateAndSet failed, error 108: Cannot send after transport endpoint shutdown
06-30 10:34:28.083   499   499 E qdoverlay: Bad ov dump:  mdp_overlay z=0 alpha=255 mask=-1 flags=0x220000 id=8
06-30 10:34:28.083   499   499 E qdoverlay: src msmfb_img w=1152 h=1,920 format=13 MDP_RGBA_8888
06-30 10:34:28.083   499   499 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
06-30 10:34:28.083   499   499 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
06-30 10:34:28.083   499   499 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Cannot send after transport endpoint shutdown
06-30 10:34:28.083   499   499 E qdoverlay: MdpCtrl close error in unset
06-30 10:34:28.103   499   876 E qdhwcomposer: hwc_vsync_control: vsync control failed. Dpy=0, enable=1 : Cannot send after transport endpoint shutdown
06-30 10:34:28.103   499   876 E SurfaceFlinger: eventControl(0, 1) failed Cannot send after transport endpoint shutdown

```
