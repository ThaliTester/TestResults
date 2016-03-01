#### Test 61248225a3bd1fe_thali06_HTC-HTC One M8s Logs


```
--------- beginning of system
W/ActivityManager(  942): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=4738, uid=10106, userID:0
I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=4738, uid=10106, userID:0
--------- beginning of main
D/libc    ( 4658): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
D/libc    ( 4658): [NET] android_getaddrinfofornet-, err=8
E/Gmail   ( 4738): Error finding the version of the Email provider.....
E/Gmail   ( 4738): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 4738): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 4738): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 4738): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 4738): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4738): 	at android.os.Looper.loop(Looper.java:155)
E/Gmail   ( 4738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 4738): We do not support migrating this version of the Email provider.
I/Gmail   ( 4738): getAccountsCursor
I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GoogleMailWidgetProvider, state=2, flag=1, pid=4738, uid=10106, userID:0
I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GmailWidgetProvider, state=1, flag=1, pid=4738, uid=10106, userID:0
V/GLSActivity( 1797): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGoogleMail, state=2, flag=1, pid=4738, uid=10106, userID:0
I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGmail, state=1, flag=1, pid=4738, uid=10106, userID:0
V/GLSActivity( 1797): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  942): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=4782 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
E/WifiTrafficPoller(  942): TRAFFIC_STATS_POLL true Token 11 num clients 5
E/WifiTrafficPoller(  942):  packet count Tx=91 Rx=146
E/WifiTrafficPoller(  942): notifying of data activity 3
D/WIFI_ICON( 1222): WifiActivity: 3
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
W/ActivityManager(  942): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
V/AlarmManager(  942): sending alarm PendingIntent{128c48a7: PendingIntentRecord{3c080154 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.hangouts.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=55466, Int=259200000
V/AlarmManager(  942): sending alarm PendingIntent{31929f2: PendingIntentRecord{1faac843 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1456842824955, Int=0
V/AlarmManager(  942): sending alarm PendingIntent{2b8ddec0: PendingIntentRecord{dc687f9 com.htc.launcher broadcastIntent}}, i=com.htc.launcher.action.BI_LOG_ALARM, t=1, cnt=1, w=1456830000000, Int=86400000
V/AlarmManager(  942): sending alarm PendingIntent{e189a41: PendingIntentRecord{ebfabe6 android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1456842817783, Int=20000
I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=4738, uid=10106, userID:0
I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=4738, uid=10106, userID:0
W/ActivityManager(  942): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
V/GLSActivity( 1797): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ActivityThread( 4738): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@cdafee1 that was originally bound here
E/ActivityThread( 4738): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@cdafee1 that was originally bound here
E/ActivityThread( 4738): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1183)
E/ActivityThread( 4738): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1077)
E/ActivityThread( 4738): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1906)
E/ActivityThread( 4738): 	at android.app.ContextImpl.bindService(ContextImpl.java:1889)
E/ActivityThread( 4738): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4738): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4738): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4738): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4738): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4738): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4738): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4738): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4738): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4738): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread( 4738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager(  942): Unbind failed: could not find connection for android.os.BinderProxy@2d0054a
I/iu.UploadsManager( 2169): End new media; added: 0, uploading: 0, time: 81 ms
E/SQLiteLog( 4738): (283) recovered 1407 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
I/Gmail   ( 4738): notifyAccountChanged
I/Gmail   ( 4738): getAccountsCursor
I/Gmail   ( 4738): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1797): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 4738): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
D/PMS     (  942): acquireWL(56bf3a2): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 4738 10106 null
I/Gmail   ( 4738): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
D/PMS     (  942): acquireWL(56bf3a2): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 4738 10106 null
I/Gmail   ( 4738): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
D/PMS     (  942): acquireWL(56bf3a2): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 4738 10106 null
I/Gmail   ( 4738): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 4738): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
I/Gmail   ( 4738): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.ComposeActivityGmail, state=1, flag=1, pid=4738, uid=10106, userID:0
D/Process (  942): killProcessQuiet, pid=4235
I/ActivityManager(  942): Killing 4235:com.htc.android.worldclock/u0a90 (adj 15): empty #17
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
E/cutils-trace( 4809): Error opening trace file: Permission denied (13)
D/CustomizationManager( 4809): ====startRecUseTime====
D/htc.customization.log.level( 4809):  is 
W/CustomizationLogLevel( 4809): Level value is invalid, use default level 2
I/ActivityManager(  942): Recipient 4235
D/CustomizationManager( 4809):  Read ACC file spent 0.038 (s)
D/CIDMapFileReader( 4809): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4809): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4809): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4809): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4809): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4809): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4809): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4809): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 4809): Parsing tag category name = system
I/CustomizationCIDLoader( 4809): Parsing tag category name = application
I/CustomizationCIDLoader( 4809): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4809): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4809): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4809): Parsing tag category name = Settings
I/CustomizationCIDLoader( 4809): Parsing tag category name = ACC
I/Gmail   ( 4738): master sync=false, engine sync=true
I/CustomizationCIDLoader( 4809): add string-array item, value = 42507
I/CustomizationCIDLoader( 4809): add string-array item, value = 21902
I/CustomizationCIDLoader( 4809): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 4809): add string-array item, value = 23420
I/CustomizationCIDLoader( 4809): add string-array item, value = 22299
I/CustomizationCIDLoader( 4809): add string-array item, value = 24002
I/CustomizationCIDLoader( 4809): add string-array item, value = 23210
I/CustomizationCIDLoader( 4809): add string-array item, value = 23205
I/CustomizationCIDLoader( 4809): add string-array item, value = 23806
I/CustomizationCIDLoader( 4809): add string-array item, value = 23430
I/CustomizationCIDLoader( 4809): add string-array item, value = 23408
I/CustomizationCIDLoader( 4809): add string-array item, value = 27205
I/CustomizationCIDLoader( 4809): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 4809): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 4809): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 4809): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 4809): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 4809): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 4809): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 4809): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 4809): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 4809): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 4809): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 4809): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 4809):  Read CID file spent 0.086 (s)
D/CustomizationManager( 4809):  All configurations done spent 0.086 (s)
E/WifiStateMachine(  942): handleMessage: E msg.what=131155
E/WifiStateMachine(  942): processMsg: ConnectedState
E/WifiStateMachine(  942):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-58 f=2437 sc=60 link=150 tx=10.4, 0.0, 0.0  rx=12.8 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:848912088] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  942): processMsg: L2ConnectedState
E/WifiStateMachine(  942):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-58 f=2437 sc=60 link=150 tx=10.4, 0.0, 0.0  rx=12.8 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:848912090] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  942):  get link layer stats 0
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1407): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1407): environment dirty rate=92 [13][12][0]
E/WifiStateMachine(  942): fetchRssiLinkSpeedAndFrequencyNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 150
E/WifiStateMachine(  942): fetchRssiLinkSpeedAndFrequencyNative rssi=-58 linkspeed=150
E/WifiConfigStore(  942): updateConfiguration freq=2437 BSSID=f4:f2:6d:22:99:3e RSSI=-58 "NG700"WPA_PSK
D/WIFI_ICON( 1222): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  942): calculateWifiScore freq=2437 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=11.72 txretriesrate=0.00 rxrate=21.40 userTriggerdPenalty0
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiStateMachine(  942):  good link -> stuck count =0
E/WifiStateMachine(  942):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  942):  isHighRSSI       ---> score=65
E/WifiStateMachine(  942): handleMessage: X
D/WifiWatchdogStateMachine(  942): RSSI current: 3 new: -58, 3
I/Gmail   ( 4738): getAccountsCursor
I/ActivityManager(  942): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 pid 4809 on display 0
W/asset   (  942): Copying FileAsset 0x55c3f214e0 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/PMS     (  942): acquireHCC(de9a423): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 942 1000 null
V/GLSActivity( 1797): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  942): acquireHCC(328fbd20): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 942 1000 null
D/PMS     (  942): acquireWL(e285f7f): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 942 1000 null
I/Gmail   ( 4738): master sync=false, engine sync=true
I/AnimationUtil(  942): isHTCRecent(HelloWorld/Recent screens.)/4
I/art     (  942): Explicit concurrent mark sweep GC freed 16235(915KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 16MB/24MB, paused 1.289ms total 137.565ms
I/FeedHostManager( 1479): [onPause]
I/FeedProviderManager( 1479): onPause
D/LocationManagerService(  942): getProviders()=[passive]
I/FeedHostManager( 1479): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@31382e81
I/SocialFeedProvider( 1479): +onPause
I/SocialFeedProvider( 1479): -onPause
W/HtcSystemUPManager(  942): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  942): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4835 uid=10374 gids={50374, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/ActivityManager(  942): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4857 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a
,D/StatusBarManagerService(  942): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  942): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  942): hiding MENU key
I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.googlequicksearchbox.SearchActivity, state=1, flag=1, pid=4782, uid=10085, userID:0
I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.googlequicksearchbox.VoiceSearchActivity, state=1, flag=1, pid=4782, uid=10085, userID:0
I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.search.core.icingsync.ApplicationLaunchReceiver, state=1, flag=1, pid=4782, uid=10085, userID:0
W/asset   ( 4835): Copying FileAsset 0xac5f66d8 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/TrimMemoryManager( 1479): [trimMemory] 20
D/WifiService(  942): New client listening to asynchronous messages
W/BroadcastQueue(  942): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to pl.k2.droidoaudioteka/.ford.AppLinkReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
E/WifiTrafficPoller(  942): ADD_CLIENT: 6
I/ActivityManager(  942): Start proc com.htc.club for broadcast com.htc.club/com.mcrm.autonotification.Autostart: pid=4893 uid=10181 gids={50181, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/Process (  942): killProcessQuiet, pid=4260
I/ActivityManager(  942): Killing 4260:com.google.android.configupdater/u0a98 (adj 15): empty #17
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
I/WebViewFactory( 4835): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
I/SearchBackgroundTaskFac( 4782): refreshing internal icing corpora
I/SearchBackgroundTaskFac( 4782): Checking for language pack updates
E/WifiTrafficPoller(  942): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  942):  packet count Tx=94 Rx=154
E/AndroidHttpClient( 4496): Leak found
E/AndroidHttpClient( 4496): java.lang.IllegalStateException: AndroidHttpClient created and never closed
E/AndroidHttpClient( 4496): 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 4496): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 4496): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 4496): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 4496): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 4496): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 4496): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 4496): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 4496): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 4496): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 4496): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 4496): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 4496): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 4496): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 4496): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 4496): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
I/ActivityManager(  942): Recipient 4260
I/GservicesUpdateTask( 4782): Updating Gservices keys
D/GCM     ( 1797): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/UpdateIcingCorporaServi( 4782): Updating corpora: APPS=MAYBE, CONTACTS=MAYBE
D/AuthorizationBluetoothService( 1797): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 2169): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/LibraryLoader( 4835): Time to load native libraries: 23 ms (timestamps 8674-8697)
I/LibraryLoader( 4835): Expected native library version number "",actual native library version number ""
D/libc    ( 4893): [NET] android_getaddrinfofornet+,hn 48(0x6874632d636c75),sn(),hints(known),family 0,flags 4
D/libc    ( 4893): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4893): [NET] android_getaddrinfofornet+,hn 48(0x6874632d636c75),sn(),hints(known),family 0,flags 1024
D/libc    ( 4893): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4893): [NET] android_getaddrinfo_proxy+
D/libc    ( 4893): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 48(0x6874632d636c75),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=2169, uid=10024, userID:0
V/WebViewChromiumFactoryProvider( 4835): Binding Chromium to main looper Looper (main, tid 1) {186594d0}
I/LibraryLoader( 4835): Expected native library version number "",actual native library version number ""
I/chromium( 4835): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/ActivityManager(  942): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=4941 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
I/BrowserStartupController( 4835): Initializing chromium process, singleProcess=true
D/LocationInitializer( 2169): Restart initialization of location
W/art     ( 4835): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4835): ApplicationContext is null in ApplicationStatus
D/ContactMessageStore( 1424): MSG_NOTIFY_CS_TO_SYNC >>
D/ContactMessageStore( 1424): MSG_NOTIFY_CS_TO_SYNC <<
I/ActivityManager(  942): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=4967 uid=10035 gids={50035, 9997} abi=arm64-v8a
D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4893): [NET] android_getaddrinfo_proxy-, success
D/libc    ( 4893): [NET] android_getaddrinfofornet+,hn 13(0x35342e3233312e),sn(),hints(known),family 0,flags 4
D/libc    ( 4893): [NET] android_getaddrinfofornet-, SUCCESS
I/art     (  439): Explicit concurrent mark sweep GC freed 8665(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 289us total 29.171ms
I/art     (  439): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 130us total 22.370ms
W/ResourcesManager( 4941): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4941): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/art     (  439): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 222us total 20.332ms
I/MultiDex( 4941): VM with version 2.1.0 has multidex support
I/MultiDex( 4941): install
I/MultiDex( 4941): VM has multidex support, MultiDex support library is disabled.
D/libc    ( 4893): [NET] android_getaddrinfofornet+,hn 3,sn(),hints(known),family 0,flags 4
D/libc    ( 4893): [NET] android_getaddrinfofornet-, err=8
V/JNIHelp ( 4941): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/VoldConnector(  942): SND -> {17 volume mkdirs /storage/ext_sd/Android/data/com.google.android.googlequicksearchbox/files/download_cache/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.googlequicksearchbox/files/download_cache/
W/ContextImpl( 4782): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.googlequicksearchbox/files/download_cache
I/ActivityManager(  942): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4994 uid=10076 gids={50076, 9997} abi=arm64-v8a
D/Process (  942): killProcessQuiet, pid=3834
I/ActivityManager(  942): Killing 3834:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
W/chromium( 4835): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 4835): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4835): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 4835): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 4835): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 4835): Build Date: 03/09/15 Mon
I/Adreno-EGL( 4835): Local Branch: 
I/Adreno-EGL( 4835): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 4835): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 4835):                  d74aa161a12b9c6fc6332151
W/System  ( 4941): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1c7a14db: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
W/ActivityThread( 4941): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ProviderInstaller( 4941): Installed default security provider GmsCore_OpenSSL
I/WebViewFactory( 4782): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
I/ActivityManager(  942): Recipient 3834
W/System.err(  942): java.lang.Throwable: stack dump
W/System.err(  942): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  942): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  942): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  942): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  942): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  942): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@22495c7b:true
D/BluetoothAdapter( 4835): 699342575: getState(). Returning 12
I/UpdateIcingCorporaServi( 4782): UpdateCorporaTask done [took 420 ms] updated apps [took 417 ms] 
I/GLSUser ( 1797): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
I/GLSUser ( 1797): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1797): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1797): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/SMSBackup( 4994): Got a database change event
D/WearableService( 4941): callingUid 10024, callindPid: 4941
I/GLSUser ( 1797): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
I/GLSUser ( 1797): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1797): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1797): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1797): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
I/GLSUser ( 1797): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1797): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1797): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1797): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  942): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=5036 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a
D/Process (  942): killProcessQuiet, pid=4305
I/ActivityManager(  942): Killing 4305:com.htc.backupreset/1000 (adj 15): empty #17
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/LibraryLoader( 4782): Time to load native libraries: 31 ms (timestamps 9137-9168)
I/LibraryLoader( 4782): Expected native library version number "",actual native library version number ""
W/art     ( 4782): Attempt to remove local handle scope entry from IRT, ignoring
I/ActivityManager(  942): Recipient 4305
V/GLSActivity( 1797): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1797): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 1797): Explicit concurrent mark sweep GC freed 14693(875KB) AllocSpace objects, 1(20KB) LOS objects, 49% free, 4MB/8MB, paused 728us total 52.128ms
E/MDM     ( 1866): [153] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
W/art     ( 4835): Attempt to remove local handle scope entry from IRT, ignoring
I/ImageRamCache( 5036): create image Cache, size: 31457280.
I/ImageRamCache( 5036): [resize] ImageRamCache resized to: 30Mb.
I/ImageRamCache( 5036): create image Cache, size: 31457280.
W/AwContents( 4835): onDetachedFromWindow called when already detached. Ignoring
I/FeedSettings( 5036): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 5036): GroupBudget 0.500000 0.380000
I/FeedSettings( 5036): GroupBudget 60 45 15
W/art     ( 4782): Attempt to remove local handle scope entry from IRT, ignoring
I/Prism.ExternalStringMa_( 5036): changeLocale(): en_GB
D/SystemWebViewEngine( 4835): CordovaWebView is running on device made by: HTC
W/art     ( 4835): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4835): Attempt to remove local handle scope entry from IRT, ignoring
I/Prism.AllAppsOptionsMa_( 5036): loadSortType() with Custom
I/Prism.AllAppsOptionsMa_( 5036): loadGridSize() with Alternative
I/ActionCombine( 1797): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
D/CustomHighlightReceiver( 5036): [custom highlight] onReceive
W/ResourcesManager( 1222): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1222): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 1301): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1301): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 1301): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1301): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/DotMatrix( 1301): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1301): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/Search.LoginHelper( 4782): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 4782): com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
W/Search.LoginHelper( 4782): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 4782): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4782): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 4782): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4782): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 4782): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4782): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 4782): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 4782): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
W/Search.LoginHelper( 4782): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 4782): com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
W/Search.LoginHelper( 4782): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 4782): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4782): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 4782): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4782): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 4782): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4782): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 4782): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 4782): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
E/VelvetNetworkClient( 4782): Failed to get auth token
W/Search.LoginHelper( 4782): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 4782): com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
W/Search.LoginHelper( 4782): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 4782): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4782): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 4782): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4782): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 4782): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4782): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 4782): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 4782): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
D/DotMatrix( 1301): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 3, tag: null, isClearable: true
D/DotMatrix( 1301): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/ActivityManager(  942): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5085 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/DotMatrix( 1301): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 2, tag: null, isClearable: true
D/DotMatrix( 1301): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
D/CustomHighlightService( 5036): [custom highlight] onHandleIntent
W/Search.LoginHelper( 4782): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 4782): com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
W/Search.LoginHelper( 4782): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 4782): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4782): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 4782): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4782): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 4782): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4782): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 4782): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 4782): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
W/Search.LoginHelper( 4782): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 4782): com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
W/Search.LoginHelper( 4782): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 4782): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4782): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 4782): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4782): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 4782): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4782): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 4782): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 4782): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
I/RemoteViews( 1222): apply : com.google.android.gms 0 15 5 40
D/NewsDB  ( 5036): set custom highlight []
E/WifiTrafficPoller(  942): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  942):  packet count Tx=112 Rx=171
W/chromium( 4835): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/RemoteViews( 1222): apply : com.google.android.gms 0 9 2 40
W/Search.LoginHelper( 4782): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 4782): com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
W/Search.LoginHelper( 4782): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 4782): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4782): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 4782): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4782): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 4782): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4782): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 4782): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 4782): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
E/VelvetNetworkClient( 4782): Failed to get auth token
D/FindExtension( 4835): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
D/CustomHighlightService( 5036): [custom highlight] set tags 
I/ActivityManager(  942): Killing 4332:com.htc.htccupd/u0a13 (adj 15): empty #17
D/Process (  942): killProcessQuiet, pid=4332
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/RemoteViews( 1222): apply : com.google.android.gms 0 11 3 40
I/ActivityManager(  942): Recipient 4332
I/InputMethodManager( 4835): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@1e9fa0f5, mServedView=org.apache.cordova.engine.SystemWebView{1f805e8a VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@2f327cfb
I/InputMethodManagerService(  942): Disable input method client, pid=1479
D/StatusBarManagerService(  942): swetImeWindowStatus vis=0 backDisposition=0
I/ActivityManager(  942): Displayed com.example.hello/.MainActivity: +1s511ms
I/InputMethodManagerService(  942): Enable input method client, pid=4835
I/PhoneStatusBar( 1222): setImeWindowStatus(false,false)
D/PMS     (  942): releaseWL(e285f7f): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/libc    ( 4782): [NET] android_getaddrinfofornet+,hn 13(0x7777772e676f6f),sn(),hints(known),family 2,flags 1024
D/libc    ( 4782): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4782): [NET] android_getaddrinfo_proxy+
D/libc    ( 4782): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 13(0x7777772e676f6f),sn(),hints(known),family 2,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
W/BindingManager( 4835): Cannot call determinedVisibility() - never saw a connection for the pid: 4835
W/Atfwd_Sendcmd(  467): AtCmdFwd service not published, waiting... retryCnt : 4
I/chromium( 4835): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
W/XT9_C   ( 1356): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1356): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1356): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1356): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/MusicStore( 5085): Database version: 120
D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4782): [NET] android_getaddrinfo_proxy-, success
D/PMS     (  942): releaseWL(56bf3a2): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 null
D/JsMessageQueue( 4835): Set native->JS mode to OnlineEventsBridgeMode
E/AndroidProtocolHandler( 4835): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/jxcore_app_log( 4835): JniHelper::setJavaVM(0xab4888f8), pthread_self() = -1401251400
D/JX-Cordova( 4835): jxcore cordova android initializing
,D/PMS     (  942): releaseHCC(de9a423): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,D/PMS     (  942): releaseHCC(328fbd20): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null,
,I/art     (  942): Explicit concurrent mark sweep GC freed 11968(562KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.775ms total 180.139ms
,W/jxcore-log( 4835): Initializing JXcore engine
W/jxcore-log( 4835): JXcore engine is ready
,W/jxcore-log( 4835): Starting JXcore engine,
,D/VoldConnector(  942): SND -> {18 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 5085): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/WifiDataStallTracker(  942): DATA_MONITOR_POLL true Token 1,
D/WifiDataStallTracker(  942): updateDataStallInfo: mDataStallTxRxSum={txSum=129 rxSum=102} preTxRxSum={txSum=68 rxSum=49}
D/WifiDataStallTracker(  942): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  942): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,D/VoldConnector(  942): SND -> {19 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 5085): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
D/VoldConnector(  942): SND -> {20 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 5085): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/ResourcesManager( 5085): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5085): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5085): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/jxcore-log( 4835): Platform android,
W/jxcore-log( 4835): 
W/jxcore-log( 4835): Process ARCH arm
W/jxcore-log( 4835): 
,W/ActivityThread( 5085): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 5085): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@18059b6d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5085): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5085): GMSCore installation verified
,I/ConfigStore( 5085): Config Database version: 1
,I/jxcore-log( 4835): JXcore Cordova bridge is ready!,
I/jxcore-log( 4835): 
W/jxcore-log( 4835): JXcore engine is started
,I/ActivityManager(  942): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=5136 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,V/AlarmManager(  942): sending alarm PendingIntent{3f12349c: PendingIntentRecord{33701ea5 com.htc.mobiledata startService}}, i=com.htc.mobiledata.intent.REQUEST, t=2, cnt=1, w=60301, Int=0
,E/jxcore-log( 4835): >> HTC-HTC One M8s
E/jxcore-log( 4835): 
,I/jxcore-log( 4835): Total memory 1931808768,
I/jxcore-log( 4835): 
I/jxcore-log( 4835): Free memory 85102592
I/jxcore-log( 4835): 
,I/jxcore-log( 4835): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4835): 
I/jxcore-log( 4835): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4835): 
,I/jxcore-log( 4835): userPath [ 'www', 'www' ],
I/jxcore-log( 4835): 
,I/jxcore-log( 4835): Size 1080 1776
I/jxcore-log( 4835): 
,I/jxcore-log( 4835): Screen Brightness 142,
I/jxcore-log( 4835): 
E/jxcore-log( 4835): Dummy Error Log.
E/jxcore-log( 4835): 
,I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=5085, uid=10159, userID:0,
,D/WifiDisplayAdapter(  942): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  942):     Client/Owner: Client
D/WifiDisplayAdapter(  942):     GroupId: 
D/WifiDisplayAdapter(  942):     Passphrase: 
D/WifiDisplayAdapter(  942):     SessionId: 0
D/WifiDisplayAdapter(  942):     IP Address: }
,I/ActivityManager(  942): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=5161 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,D/MediaRouterService(  942): Client com.google.android.music (pid 5085): Registered
,D/WifiDisplayAdapter(  942): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  942):     Client/Owner: Client
D/WifiDisplayAdapter(  942):     GroupId: 
D/WifiDisplayAdapter(  942):     Passphrase: 
D/WifiDisplayAdapter(  942):     SessionId: 0
D/WifiDisplayAdapter(  942):     IP Address: }
,D/libc    ( 4893): [NET] android_getaddrinfofornet+,hn 28(0x6874632d636c75),sn(),hints(known),family 0,flags 4
,D/libc    ( 4893): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4893): [NET] android_getaddrinfofornet+,hn 28(0x6874632d636c75),sn(),hints(known),family 0,flags 1024
D/libc    ( 4893): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4893): [NET] android_getaddrinfo_proxy+
D/libc    ( 4893): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 28(0x6874632d636c75),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
I/MediaRouter( 5085): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
V/MusicLeanback( 5085): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 5085): type=WIFI subType= reason=null isConnected=true,
E/WifiTrafficPoller(  942): TRAFFIC_STATS_POLL true Token 11 num clients 6
,E/WifiTrafficPoller(  942):  packet count Tx=166 Rx=222,
,I/GLSUser ( 1797): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.googlequicksearchbox, service: weblogin:service%3Dhist%26continue%3Dhttps%253A%252F%252Fwww.google.pl&de=1
I/GLSUser ( 1797): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> weblogin:service%3Dhist%26continue%3Dhttps%253A%252F%252Fwww.google.pl&de=1 without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1797): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1797): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1797): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/MdScBoot( 5136): [cd.1.] 30@-143317 -> 40,
,I/NetworkMonitor( 5085): type=WIFI subType= reason=null isConnected=true
,D/MdScBootUi( 5136): [cd.1.2.] boot 118
,W/Search.LoginHelper( 4782): User recoverable exception for scope: weblogin:service%3Dhist%26continue%3Dhttps%253A%252F%252Fwww.google.pl&de=1
,W/Search.LoginHelper( 4782): com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
W/Search.LoginHelper( 4782): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 4782): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4782): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 4782): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4782): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 4782): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4782): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 4782): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 4782): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 4782): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
D/MdScSimSt( 5136): [cd.1.2.] qry 118: 0+1 running 0
,I/ActivityManager(  942): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=5195 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a,
,I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=5085, uid=10159, userID:0
,D/DotMatrix( 1301): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 2, tag: null, isClearable: true
,D/DotMatrix( 1301): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1222): reapply : com.google.android.gms 2 40
D/Process (  942): killProcessQuiet, pid=4381
I/ActivityManager(  942): Killing 4381:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
,I/ActivityManager(  942): Recipient 4381
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4893): [NET] android_getaddrinfo_proxy-, success
D/libc    ( 4893): [NET] android_getaddrinfofornet+,hn 13(0x32332e35392e31),sn(),hints(known),family 0,flags 4
D/libc    ( 4893): [NET] android_getaddrinfofornet-, SUCCESS
,I/HtcModeClient( 3270): handler message = 4011
E/HtcModeClient( 3270): Check connection and retry 4 times.
,D/Process (  942): killProcessQuiet, pid=4425
I/ActivityManager(  942): Killing 4425:com.android.settings:remote/1000 (adj 15): empty #17
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,W/ResourcesManager( 5195): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/jxcore-log( 4835): getBuffer is called!!!!,
I/jxcore-log( 4835): 
I/ActivityManager(  942): Recipient 4425,
,D/Process (  942): killProcessQuiet, pid=4452
,I/ActivityManager(  942): Killing 4452:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiStateMachine(  942): handleMessage: E msg.what=131155
E/WifiStateMachine(  942): processMsg: ConnectedState
,E/WifiStateMachine(  942):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-58 f=2437 sc=60 link=150 tx=11.7, 0.0, 0.0  rx=21.4 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:848915113] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0,
E/WifiStateMachine(  942): processMsg: L2ConnectedState
E/WifiStateMachine(  942):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-58 f=2437 sc=60 link=150 tx=11.7, 0.0, 0.0  rx=21.4 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:848915114] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  942):  get link layer stats 0
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1407): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1407): environment dirty rate=100 [80][80][0],
E/WifiStateMachine(  942): fetchRssiLinkSpeedAndFrequencyNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 150
E/WifiStateMachine(  942): fetchRssiLinkSpeedAndFrequencyNative rssi=-58 linkspeed=150
E/WifiConfigStore(  942): updateConfiguration freq=2437 BSSID=f4:f2:6d:22:99:3e RSSI=-58 "NG700"WPA_PSK
,E/WifiStateMachine(  942): calculateWifiScore freq=2437 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=45.86 txretriesrate=0.00 rxrate=49.70 userTriggerdPenalty0
E/WifiStateMachine(  942):  good link -> stuck count =0
E/WifiStateMachine(  942):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  942):  isHighRSSI       ---> score=65,
,I/ActivityManager(  942): Recipient 4452
,E/WifiStateMachine(  942): handleMessage: X
,D/WifiWatchdogStateMachine(  942): RSSI current: 3 new: -58, 3,
D/WIFI_ICON( 1222): updateWifiState: RSSI_CHANGED 3 -> 3
I/CalendarProvider2( 5195): Created com.android.providers.calendar.CalendarAlarmManager@3f77ecc9(com.htc.providers.calendar.HtcCalendarProvider@3cab3fce)
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/CalendarProvider2( 5195): wait start:true
,I/GHttpClientFactory( 5085): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 5085): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  942): Waited long enough for: ServiceRecord{1e77ee9c u0 com.htc.HTCSpeaker/.NGFService}
,I/ActivityManager(  942): Killing 4475:com.android.smith/1000 (adj 15): empty #17
D/Process (  942): killProcessQuiet, pid=4475
,D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/CalendarProvider2( 5195): wait end:false
,I/ActivityManager(  942): Recipient 4475
,D/AutoSetting( 1569): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  942): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=5223 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a,
,D/AutoSetting( 1569): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1569): Util - check NLP state, Allowned:false, Enabled:false,
D/AutoSetting( 1569): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1569): service - onStartCommand() REMOVE current location bundle
D/AutoSetting( 1569): service - handleMessage() setting current location null,
,D/PhoneMonitor( 5223): Register our PhoneStateListener
,E/WifiTrafficPoller(  942): TRAFFIC_STATS_POLL true Token 11 num clients 6
,E/WifiTrafficPoller(  942):  packet count Tx=176 Rx=236
,D/MobileConnectivityChangeReceiver( 5223): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5223): onReceive CONNECTIVITY_CHANGE networkType=1,
,I/ActivityManager(  942): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.NetworkChangeReceiver: pid=5245 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a,
,D/Process (  942): killProcessQuiet, pid=4403
,I/ActivityManager(  942): Killing 4403:com.android.settings/1000 (adj 15): empty #17
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
D/PhoneMonitor( 5223): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,D/PhoneMonitor( 5223): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,I/ActivityManager(  942): Recipient 4403,
,D/PMS     (  942): acquireWL(1036c82e): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2169 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  942): acquireWL(37dbdd5c): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2169 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  942): releaseWL(1036c82e): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
,I/CheckinService( 2169): Checking schedule, now: 1456842829131 next: 1456765623471,
,I/CheckinService( 2169): active receiver: enabled
I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2169, uid=10024, userID:0
,I/CheckinService( 2169): Preparing to send checkin request,
,I/EventLogService( 2169): Accumulating logs since 1456842202235
,I/DeviceManagement( 5245): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=5245 dbg=false s=true,
,I/DeviceManagement( 5245): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.NetworkChangeWorkflow] args=[Bundle[{networkChangeIntent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.htc.cs.dm/.receiver.NetworkChangeReceiver (has extras) }}]]
,I/DeviceManagement( 5245): WorkflowService: Starting workflow service,
,I/DeviceManagement( 5245): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.NetworkChangeWorkflow@36d72dfc] args=[Bundle[mParcelledData.dataSize=720]]
,I/DeviceManagement( 5245): NetworkChangeWorkflow: ==================================================
I/DeviceManagement( 5245): NetworkChangeWorkflow: NetworkChange: networkAvailable=true
I/DeviceManagement( 5245): NetworkChangeWorkflow: ==================================================
,I/DeviceManagement( 5245): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 5245): SessionStateController: Checking invariants...
,I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2169, uid=10024, userID:0,
,I/iu.SyncManager( 2169): SYNC; picasa accounts
,D/NetworkLogImpl( 2169): Loaded NetworkSpeedPredictor,
,I/iu.Environment( 2169): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2169): num queued entries: 0
,I/iu.UploadsManager( 2169): num updated entries: 0
I/iu.SyncManager( 2169): NEXT; no task
,I/CheckinRequestBuilder( 2169): Checkin reason type: 8 attempt count: 1
,E/WifiTrafficPoller(  942): ADD_CLIENT: 7
,D/WifiService(  942): New client listening to asynchronous messages
,I/ActivityManager(  942): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2169): Failed to find provider info for com.google.android.wearable.settings
,D/ChimeraCfgMgr( 2169): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 2169): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
,I/ActivityManager(  942): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5277 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,D/libc    ( 4622): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4,
D/libc    ( 4622): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4622): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 4622): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4622): [NET] android_getaddrinfo_proxy+
,D/libc    ( 4622): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604,
,I/DeviceManagement( 5245): BackgroundController: Invariants are unchanged.,
,I/DeviceManagement( 5245): SessionStateController: Checking invariants...,
,I/DeviceManagement( 5245): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4622): [NET] android_getaddrinfo_proxy-, success
,I/GLSUser ( 1797): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer,
,I/GLSUser ( 1797): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1797): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1797): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1797): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/CheckinRequestBuilder( 2169): awaiting user notification for token,
,D/DotMatrix( 1301): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 2, tag: null, isClearable: true
D/DotMatrix( 1301): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1222): reapply : com.google.android.gms 3 40
,I/DeviceManagement( 5245): Perf: *** Cache update - start...
,I/DeviceManagement( 5245): Perf: *** Enabled app cache update - start...
I/DeviceManagement( 5245): EnabledAppController: *** Updating enabled app database...,
I/DeviceManagement( 5245): Perf: *** Enabled app cache update - complete: 1 ms
,I/DeviceManagement( 5245): Perf: *** Config cache update - start...,
,I/DeviceManagement( 5245): ConfigCacheController: *** Updating config cache...
I/DeviceManagement( 5245): ConfigCacheController: *** Updating stale config cache entries...
,I/DeviceManagement( 5245): ConfigCacheController: *** Update config cache: updating 0 entries...,
I/DeviceManagement( 5245): ConfigCacheController: No changes need to be broadcasted.
,I/DeviceManagement( 5245): AlarmController: Scheduling TTL alarm for: 2016.03.02 at 15:33:41.823 CET (due to: com.htc.launcher),
,I/PackageManager(  942):  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=2, flag=1, pid=5245, uid=10099, userID:0
I/DeviceManagement( 5245): Perf: *** Config cache update - complete: 17 ms
,I/DeviceManagement( 5245): Perf: *** Cache update - complete: 22 ms
,I/DeviceManagement( 5245): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.NetworkChangeWorkflow@36d72dfc]
,I/DeviceManagement( 5245): WorkflowService: Stopping workflow service
,I/ActivityManager(  942): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5306 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/ResourcesManager( 5306): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 5306): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/VoldConnector(  942): SND -> {21 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 5277): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache,
,D/VoldConnector(  942): SND -> {22 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/,
W/ContextImpl( 5277): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/MultiDex( 5306): VM with version 2.1.0 has multidex support
I/MultiDex( 5306): install
I/MultiDex( 5306): VM has multidex support, MultiDex support library is disabled.
,I/GAv4    ( 5277): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:,
I/GAv4    ( 5277):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5277):   adb logcat -s GAv4
,D/VoldConnector(  942): SND -> {23 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
W/ContextImpl( 5277): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  942): SND -> {24 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl( 5277): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,V/JNIHelp ( 5306): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,I/CalendarProvider2( 5195): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: },
,W/ContentResolver( 5195): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
W/GAv4    ( 5277): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
I/ActivityManager(  942): Killing 4533:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  942): killProcessQuiet, pid=4533
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/ActivityThread( 5306): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 5306): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1c7a14db: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5306): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  942): Recipient 4533
,W/GAv4    ( 5277): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,I/GAV2    ( 4738): Thread[GAThread,5,main]: No campaign data found.,
,W/GAv4    ( 5277): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 4622): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  942): Killing 4496:com.android.vending/u0a72 (adj 15): empty #17
D/Process (  942): killProcessQuiet, pid=4496
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiTrafficPoller(  942): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  942):  packet count Tx=181 Rx=242
,I/ActivityManager(  942): Recipient 4496
,W/global  ( 5277): [apache-http] Connection GC has been deprecated!,
,W/global  ( 5277): [apache-http] Connection GC has been deprecated!,
,I/art     (  942): Explicit concurrent mark sweep GC freed 15588(863KB) AllocSpace objects, 4(208KB) LOS objects, 33% free, 16MB/24MB, paused 1.817ms total 178.861ms
,I/GAv4-SVC( 2169): Google Analytics 7.8.99 is starting up.
,I/WebViewFactory( 5277): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 5277): Time to load native libraries: 1 ms (timestamps 2839-2840),
I/LibraryLoader( 5277): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5277): Binding Chromium to main looper Looper (main, tid 1) {c29cc42}
,I/LibraryLoader( 5277): Expected native library version number "",actual native library version number "",
,I/chromium( 5277): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5277): Initializing chromium process, singleProcess=true,
,W/art     ( 5277): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5277): ApplicationContext is null in ApplicationStatus
,I/WVCdm   (  402): CdmEngine::OpenSession
I/WVCdm   (  402): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  402): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
D/DrmWidevineDash(  402): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  402): Service_Initialize: starts!
D/QSEECOMAPI: (  402): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  402): App is not loaded in QSEE
E/QSEECOMAPI: (  402): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  402): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  402): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  402): App is not loaded in QSEE
,W/chromium( 5277): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
D/QSEECOMAPI: (  402): Loaded image: APP id = 6
,D/DrmWidevineDash(  402): Service_Initialize: ends! returns 0
,D/QSAPPSVER(  402): qsapps_get_capabilities: Capability from secure side: 0x0,
D/QSAPPSVER(  402): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  402): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf458f000
E/DrmWidevineDash(  402): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf458f000
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/DrmLibTime(  545): got the req here! ret=0
D/DrmLibTime(  545): command id, time_cmd_id = 770
,D/DrmLibTime(  545): time_getutcsec starts!
D/DrmLibTime(  545): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  545): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  545): QSEE Time Listener: time_get_modem_time
,D/DrmLibTime(  545): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  545): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  545): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  545): QSEE Time Listener: Retrieved Android system time: 1456842830
D/DrmLibTime(  545): time_getutcsec returns 0, sec = 1456842830; nsec = 0
D/DrmLibTime(  545): time_getutcsec finished! 
D/DrmLibTime(  545): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  545): before calling ioctl to read the next time_cmd
E/QC-time-services(  471): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,I/GoogleURLConnFactory( 5306): Using platform SSLCertificateSocketFactory
D/DrmWidevineDash(  402): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  402): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): hlos api version =  9
D/DrmWidevineDash(  402): tz api version =  9
D/DrmWidevineDash(  402): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  402): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
E/libEGL  ( 5277): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5277): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5277): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 5277): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 5277): Build Date: 03/09/15 Mon
I/Adreno-EGL( 5277): Local Branch: 
I/Adreno-EGL( 5277): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 5277): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 5277):                  d74aa161a12b9c6fc6332151
,I/SocialFeedProvider( 1479): +disConnect socialManager
,I/SocialFeedProvider( 1479): disconnect socialManager
I/SocialFeedProvider( 1479): -disConnect socialManager
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  402): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  402): OEMCrypto_OpenSession: starts! SID=0xffdd1e58,
D/DrmWidevineDash(  402): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  402): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  402): OEMCrypto_GetRandom: starts! randomData=0xab19a260, dataLength=8
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  402): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab14a650, wrapped_rsa_key_length=1280,
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/libc    ( 5306): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 5306): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5306): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5306): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5306): [NET] android_getaddrinfo_proxy+
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  402): CdmEngine::QueryKeyControlInfo
D/libc    ( 5306): [NET] android_getaddrinfo_proxy get netid:0
,W/WVCdm   (  402): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  402): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  402): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  402): OEMCrypto_GetDeviceID: starts! deviceID=0xab267958, idLength=0xf47b86f8
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  402): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  402): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  402): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  402): OEMCrypto_GetHDCPCapability: starts!, current = 0xf47b870e, maximum = 0xf47b870f
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  402): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): hlos api version =  9
D/DrmWidevineDash(  402): tz api version =  9
D/DrmWidevineDash(  402): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  402): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf47b877c
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  402): PrepareKeyRequest: nonce=1982118203
D/DrmWidevineDash(  402): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab199360
D/DrmWidevineDash(  402): message_length=1611, signature=0xab119500, signature_length=0xf47b86dc
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,W/AudioManagerAndroid( 5277): Requires BLUETOOTH permission
,I/NSApplication( 5277): Starting up...
,D/Process (  942): killProcessQuiet, pid=3565
I/ActivityManager(  942): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=5376 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  942): Killing 3565:com.android.defcontainer/u0a15 (adj 15): empty #17
,I/art     (  439): Explicit concurrent mark sweep GC freed 8636(366KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 137us total 29.880ms
,I/art     (  439): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 118us total 14.935ms
,D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  402): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  402): CdmEngine::CloseSession
D/DrmWidevineDash(  402): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  402): L3 Terminate.
,D/DrmWidevineDash(  402): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): Service_Uninitialize: starts!
D/QSEECOMAPI: (  402): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  402): QSEECom_shutdown_app, app_id = 6
D/DrmWidevineDash(  402): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  402): OEMCrypto_Terminate: ends! returns 0
,I/art     (  439): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 121us total 15.530ms
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 5306): [NET] android_getaddrinfo_proxy-, success
,I/ActivityManager(  942): Recipient 3565,
,V/AlarmManager(  942): sending alarm PendingIntent{ea4eea2: PendingIntentRecord{303b2733 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1456842830729, Int=0
,I/SocialManager[SocialBiLogHelper]( 5036): action: com.htc.sense.hsp.HANDLE_ULOG
,I/SocialManager[SocialBiLogHelper]( 5036): last commit ulog time 1456811608463
I/SocialManager[SocialBiLogHelper]( 5036): skip commit this time
,D/Process (  942): killProcessQuiet, pid=4046
I/ActivityManager(  942): Killing 4046:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiTrafficPoller(  942): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  942):  packet count Tx=184 Rx=249
,I/ActivityManager(  942): Recipient 4046
,I/ActivityManager(  942): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=5402 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/Process (  942): killProcessQuiet, pid=4658
I/ActivityManager(  942): Killing 4658:com.google.android.youtube/u0a176 (adj 15): empty #17
,D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  942): Recipient 4658
,D/libc    ( 5306): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
,D/libc    ( 5306): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 5306): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
D/libc    ( 5306): [NET] android_getaddrinfofornet-, err=8
,W/ResourcesManager( 5402): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/WifiStateMachine(  942): handleMessage: E msg.what=131155,
E/WifiStateMachine(  942): processMsg: ConnectedState
E/WifiStateMachine(  942):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-58 f=2437 sc=60 link=150 tx=45.9, 0.0, 0.0  rx=49.7 bcn=0 [on:0 tx:0 rx:0 period:2848] from screen [on:0 period:848918123] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine(  942): processMsg: L2ConnectedState
E/WifiStateMachine(  942):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-58 f=2437 sc=60 link=150 tx=45.9, 0.0, 0.0  rx=49.7 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:848918125] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  942):  get link layer stats 0
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1407): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1407): environment dirty rate=88 [25][22][0],
E/WifiStateMachine(  942): fetchRssiLinkSpeedAndFrequencyNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 150
E/WifiStateMachine(  942): fetchRssiLinkSpeedAndFrequencyNative rssi=-58 linkspeed=150
E/WifiConfigStore(  942): updateConfiguration freq=2437 BSSID=f4:f2:6d:22:99:3e RSSI=-58 "NG700"WPA_PSK
E/WifiStateMachine(  942): calculateWifiScore freq=2437 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=37.93 txretriesrate=0.00 rxrate=44.85 userTriggerdPenalty0
E/WifiStateMachine(  942):  good link -> stuck count =0
E/WifiStateMachine(  942):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  942):  isHighRSSI       ---> score=65
E/WifiStateMachine(  942): handleMessage: X
D/WifiWatchdogStateMachine(  942): RSSI current: 3 new: -58, 3
,D/WIFI_ICON( 1222): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/ActivityManager(  942): Killing 4738:com.google.android.gm/u0a106 (adj 15): empty #17
,D/Process (  942): killProcessQuiet, pid=4738
,D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  942): Recipient 4738,
,E/WifiTrafficPoller(  942): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  942):  packet count Tx=217 Rx=298
,I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService, state=2, flag=1, pid=2169, uid=10024, userID:0
I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateActivity, state=2, flag=1, pid=2169, uid=10024, userID:0
I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver, state=2, flag=1, pid=2169, uid=10024, userID:0
,I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$Receiver, state=2, flag=1, pid=2169, uid=10024, userID:0,
,I/Prism.ItemManager( 1479): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1479): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/ResourcesManager( 1424): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/SystemReader(  942): Cannot find grip_rejection_width, use default value instead
D/AccTypeManager( 1736): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
W/SystemReader(  942): Cannot find grip_rejection_width, use default value instead
D/AccTypeManager( 1736): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/Prism.ItemManager( 5036): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 5036): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/ResourcesManager(  942): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/Prism.ItemManager( 5036): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 5036): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,D/AccTypeManager( 1736): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/PhoneApp( 1424): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,D/Process (  942): killProcessQuiet, pid=4857,
,I/ActivityManager(  942): Killing 4857:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 ,
,E/ExternalAccountType( 1736): Unsupported attribute readOnly
,D/AccTypeManager( 1736): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
D/PhoneApp( 1424): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,D/AccTypeManager( 1736): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/AccTypeManager( 1736): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1736): Unsupported attribute readOnly
,W/PackageManager(  942): Unable to load service info ResolveInfo{2c9d756f com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
W/PackageManager(  942): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  942): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  942): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  942): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  942): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  942): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  942): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  942): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  942): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  942): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  942): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  942): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  942): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  942): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/ActivityManager(  942): Recipient 4857,
,W/PackageManager(  942): Unable to load service info ResolveInfo{2f0dab40 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  942): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  942): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  942): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  942): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  942): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  942): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  942): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  942): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  942): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  942): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  942): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  942): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  942): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  942): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/ActivityManager(  942): Start proc com.htc.sense.mms for broadcast com.htc.sense.mms/.ui.MessagingShortcutReceiver: pid=5433 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
I/BackupManagerService(  942): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService},
,V/GmsNetworkLocationProvi( 1866): DISABLE
,I/GCoreNlp( 1866): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  942): applying state to connected service,
W/HtcWrapAdjustableCursorFactory( 5433): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.
D/PMS     (  942): acquireWL(21bb9e83): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1866 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  942): releaseWL(21bb9e83): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/MessageFrequencyProvider( 5433): onCreate
,D/LocationProviderProxy(  942): applying state to connected service
,V/GetPrviateResource( 5433): GetPrviateResource
,V/GetPrviateResource( 5433): GetPrviateResource
,D/PMS     (  942): acquireWL(23809800): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1866 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  942): acquireWL(1c10e839): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1866 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  942): releaseWL(23809800): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  942): releaseWL(1c10e839): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms},
D/MessageCustFlag( 5433): sense_version=6.0
,D/BTAccessoryUtil( 5433): createReceiver
,D/BTAccessoryUtil( 5433): registerReceiver return intent = null
,D/MessageCustFlag( 5433): sku_id=118
,D/HtcBuildUtils( 5433): getRATByHtcTelephonyCapability:1
,W/SystemReader( 5433): Cannot find qct_8960_interface, use default value instead
,I/art     ( 1797): Explicit concurrent mark sweep GC freed 13661(761KB) AllocSpace objects, 14(1176KB) LOS objects, 48% free, 4MB/8MB, paused 674us total 43.419ms
,D/MmsConfig( 5433): packageName: com.htc.vvm.att does not exist,
D/MessageCustFlag( 5433): sku_id=118
,D/MessagingShortcutReceiver( 5433): keep hiding shortcut bubble,
,D/MessagingShortcut( 5433): updateMsgShortcut, msg count> -1
,D/SettingsManager( 5433): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@3f77ecc9,
,D/MessagingShortcut( 5433): After query: 0,
D/MessagingShortcut( 5433): mPresentUnreadCount: -1
,D/MessageUtils( 5433): [getShortcut] com.htc.sense.mms.ui.ConversationList, false,
D/MessagingShortcut( 5433): setMsgShortcutDrawable> 0, false
,D/MessagingShortcut( 5433): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2,
,D/DotMatrix( 1301): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1301): [EventService] reorderNotification, total:0
D/DotMatrix( 1301): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1301): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/ActivityManager(  942): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=5465 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a
,D/Process (  942): killProcessQuiet, pid=4893
I/ActivityManager(  942): Killing 4893:com.htc.club/u0a181 (adj 15): empty #17
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,E/cutils-trace( 5477): Error opening trace file: Permission denied (13),
I/dex2oat ( 5477): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=41 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 5477): dex2oat: override thread count:4
,I/dex2oat ( 5477): dex2oat took 30.376ms (threads: 4),
,I/Adreno-EGL( 5306): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 5306): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 5306): Build Date: 03/09/15 Mon
I/Adreno-EGL( 5306): Local Branch: 
I/Adreno-EGL( 5306): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 5306): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 5306):                  d74aa161a12b9c6fc6332151
,E/WifiDataStallTracker(  942): DATA_MONITOR_POLL true Token 1
,D/WifiDataStallTracker(  942): updateDataStallInfo: mDataStallTxRxSum={txSum=198 rxSum=181} preTxRxSum={txSum=129 rxSum=102},
D/WifiDataStallTracker(  942): updateDataStallInfo: IN/OUT,
D/WifiDataStallTracker(  942): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,I/ActivityManager(  942): Recipient 4893
,D/PMS     (  942): acquireWL(60ecef5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 942 1000 null,
,I/BatteryService(  942): n_update end
D/DotMatrix( 1301): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  942): releaseWL(60ecef5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1301): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  942): updateBatteryInfo
D/DotMatrix( 1301): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1222): closing low battery warning: level=100
D/UsbnetService(  942): BroadcastReceiver::onReceive+
D/NotificationService(  942): plugged=true pluggin=true
D/UsbnetService(  942): onReceive BATTERY_CHANGED
D/PMS     (  942): runPSCheck
D/UsbnetService(  942):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/HtcPowerSaver(  942): Checking...
D/UsbnetService(  942): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  942): >> updateStatus
D/WifiController(  942): handleMessage: E msg.what=155652
D/WifiController(  942): battery changed pluggedType: 2
D/WifiController(  942): processMsg: DeviceActiveState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  942): processMsg: StaEnabledState
W/ResourcesManager( 5465): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/WifiController(  942): processMsg: DefaultState
D/WifiController(  942): handleMessage: X
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3187): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  942): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  942): << updateStatus
,I/Adreno-EGL( 5306): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 5306): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 5306): Build Date: 03/09/15 Mon
I/Adreno-EGL( 5306): Local Branch: 
I/Adreno-EGL( 5306): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 5306): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 5306):                  d74aa161a12b9c6fc6332151
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/TodoTaskshortcut( 5465): update TASK shortcut>,
,D/PMS     (  942): acquireWL(19785afb): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 5465 10069 null,
,D/PMS     (  942): acquireWL(1d196718): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 5465 10069 null
,D/PMS     (  942): releaseWL(19785afb): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,E/TodoTaskNotifyService( 5465): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
,W/System.err( 5465): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
W/System.err( 5465): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 5465): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 5465): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/PMS     (  942): releaseWL(1d196718): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
W/System.err( 5465): 	at android.os.Looper.loop(Looper.java:155)
W/System.err( 5465): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 5465): stopSelfResult true
,I/ActivityManager(  942): Killing 4782:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  942): killProcessQuiet, pid=4782
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  942): Recipient 4782
,D/WifiService(  942): Client connection lost with reason: 4
,I/WVCdm   (  402): CdmEngine::OpenSession,
I/WVCdm   (  402): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  402): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  402): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15,
,D/DrmWidevineDash(  402): Service_Initialize: starts!
D/QSEECOMAPI: (  402): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  402): App is not loaded in QSEE
E/QSEECOMAPI: (  402): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  402): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  402): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  402): App is not loaded in QSEE
,D/QSEECOMAPI: (  402): Loaded image: APP id = 7,
D/DrmWidevineDash(  402): Service_Initialize: ends! returns 0
,D/QSAPPSVER(  402): qsapps_get_capabilities: Capability from secure side: 0x0,
D/QSAPPSVER(  402): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  402): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf458e000
E/DrmWidevineDash(  402): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf458e000
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/DrmLibTime(  545): got the req here! ret=0
,D/DrmLibTime(  545): command id, time_cmd_id = 770
D/DrmLibTime(  545): time_getutcsec starts!
D/DrmLibTime(  545): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  545): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  545): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  545): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  545): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  545): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  545): QSEE Time Listener: Retrieved Android system time: 1456842832
D/DrmLibTime(  545): time_getutcsec returns 0, sec = 1456842832; nsec = 0
D/DrmLibTime(  545): time_getutcsec finished! 
D/DrmLibTime(  545): iotcl_continue_command finished! and return 0 
E/QC-time-services(  471): Daemon: Time-services: Waiting to acceptconnection
D/DrmLibTime(  545): before calling ioctl to read the next time_cmd
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  402): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  402): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): hlos api version =  9
D/DrmWidevineDash(  402): tz api version =  9
D/DrmWidevineDash(  402): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  402): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/BluetoothManagerService(  942): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  942): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@21a8109 mBinding = false
W/Settings:Agent(  942): MONITOR_LOG
W/Settings:Agent(  942): name: bluetooth_on
W/Settings:Agent(  942): value: 0
W/Settings:Agent(  942): >> traceCallingStack()
W/Settings:Agent(  942): Process.myPid(): 942
W/Settings:Agent(  942): Process.myTid(): 1796
W/Settings:Agent(  942): Process.myUid(): 1000
W/Settings:Agent(  942): 
W/Settings:Agent(  942): 
W/System.err(  942): java.lang.Throwable: stack dump
E/WifiTrafficPoller(  942): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  942):  packet count Tx=220 Rx=300
,W/System.err(  942): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  942): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
,W/System.err(  942): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  942): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  942): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  942): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
,W/System.err(  942): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:378)
W/System.err(  942): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:624)
W/System.err(  942): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  942): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  942): 
W/Settings:Agent(  942): << traceCallingStack(): 13(ms)
,D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  402): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  402): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  402): OEMCrypto_OpenSession: starts! SID=0xf46b8928
D/DrmWidevineDash(  402): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  402): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  402): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  402): OEMCrypto_GetRandom: starts! randomData=0xab131848, dataLength=8
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  402): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  402): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab119810, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  402): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  402): BufferReader::Read<T> : Failure during parse: Not enough bytes (4),
W/WVCdm   (  402): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  402): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  402): OEMCrypto_GetDeviceID: starts! deviceID=0xab267998, idLength=0xf47b86f8
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  402): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  402): OEMCrypto_SupportsUsageTable: starts!
,D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  402): OEMCrypto_SupportsUsageTable: wv_app_version = 24
,D/DrmWidevineDash(  402): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  402): OEMCrypto_GetHDCPCapability: starts!, current = 0xf47b870e, maximum = 0xf47b870f
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  402): OEMCrypto_APIVersion: starts!
,D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): hlos api version =  9
D/DrmWidevineDash(  402): tz api version =  9
,D/DrmWidevineDash(  402): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  402): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf47b877c
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  402): PrepareKeyRequest: nonce=832612622
D/DrmWidevineDash(  402): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab14a650,
D/DrmWidevineDash(  402): message_length=1646, signature=0xab119e88, signature_length=0xf47b86dc
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/BluetoothManagerService(  942): Message: MESSAGE_DISABLE
,D/BluetoothManagerService(  942): Sending off request.
D/BluetoothAdapterState( 3187): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
,D/BluetoothAdapterProperties( 3187): Setting state to 13
I/BluetoothAdapterState( 3187): Bluetooth adapter state changed: 12-> 13
D/PMS     (  942): acquireWL(387bcf56): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3187 1002 null
D/BluetoothManagerService(  942): +onBluetoothStateChange prev=12 new=13
D/BluetoothManagerService(  942): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  942): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothAdapterProperties( 3187): onBluetoothDisable()
I/bt-btm  ( 3187): BTM_SetDiscoverability
I/bt-btm  ( 3187): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3187): disc_mode 0000
I/BluetoothAdapterState( 3187): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/bt-btm  ( 3187): HAL bt_hal_cbacks->evt_type=0x0 
I/bt-btif ( 3187): BTM_SetDiscoverability: mode 0 [NonDisc-
I/bt-btm  ( 3187): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
D/BluetoothManagerService(  942): Bluetooth State Change Intent: 12 -> 13
I/bt-btm  ( 3187): BTM_SetConnectability
I/bt-btm  ( 3187): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 3187): disc_mode 0000
I/bt-btm  ( 3187): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
D/BluetoothAdapterProperties( 3187): Scan Mode:21
D/WifiManager( 4835): setWifiEnabled: Base Package Name=com.example.hello, uid=10374
D/PMS     (  942): acquireWL(3867abd7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1797 10024 WorkSource{10024 com.google.android.gms}
,D/MtpReceiver( 4007): [MTP][handleUsbStateAsync]+
D/MtpReceiver( 4007): [MTP][handleUsbStateAsync]1:1-
D/MtpReceiver( 4007): [MTP][handleUsbState]+
D/WifiService(  942): New client listening to asynchronous messages
E/WifiTrafficPoller(  942): ADD_CLIENT: 7
,D/BluetoothAdapterState( 3187): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
D/WifiService(  942): setWifiEnabled: false pid=4835, uid=10374
E/WifiStateMachine(  942): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiService(  942): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent(  942): MONITOR_LOG
I/WifiService(  942): isSprintWifiRestricted(): false
W/Settings:Agent(  942): name: wifi_on
I/WifiService(  942): isMdmWifiRestricted(): false
W/Settings:Agent(  942): value: 0
W/Settings:Agent(  942): >> traceCallingStack()
W/Settings:Agent(  942): Process.myPid(): 942
W/Settings:Agent(  942): Process.myTid(): 1520
W/Settings:Agent(  942): Process.myUid(): 1000
W/Settings:Agent(  942): 
W/Settings:Agent(  942): 
I/bt-btif ( 3187): BTA_JvDeleteRecord
I/bt-btif ( 3187): BTA_JvRfcommStopServer
D/bt-btm  ( 3187): BTM_FreeSCN 
D/bt-sdp  ( 3187): SDP_DeleteRecord ok, num_records:14
I/bt-btif ( 3187): BTA_JvDeleteRecord
I/bt-btif ( 3187): BTA_JvRfcommStopServer
D/bt-btm  ( 3187): BTM_FreeSCN 
I/bt-btif ( 3187): BTA_JvDeleteRecord
I/bt-btif ( 3187): BTA_JvRfcommStopServer
D/bt-btm  ( 3187): BTM_FreeSCN 
I/bt-btif ( 3187): BTA_JvDeleteRecord
I/bt-btif ( 3187): BTA_JvRfcommStopServer
D/bt-btm  ( 3187): BTM_FreeSCN 
I/bt-btif ( 3187): BTA_JvDeleteRecord
I/bt-btif ( 3187): BTA_JvRfcommStopServer
D/bt-btm  ( 3187): BTM_FreeSCN 
I/bt-btif ( 3187): BTA_JvDeleteRecord
I/bt-btif ( 3187): BTA_JvRfcommStopServer
D/bt-btm  ( 3187): BTM_FreeSCN 
E/bt-btif ( 3187): cmd socket is not created
I/IntentController( 1222): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
V/BluetoothSapService( 3187): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/NGFService( 3882): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,W/System.err(  942): java.lang.Throwable: stack dump
I/bt-btm  ( 3187): BTM_SEC_CLR[13]: id 55
D/bt-sdp  ( 3187): SDP_DeleteRecord ok, num_records:13
I/bt-btm  ( 3187): BTM_SEC_CLR[14]: id 56
D/bt-sdp  ( 3187): SDP_DeleteRecord ok, num_records:12
I/bt-btm  ( 3187): BTM_SEC_CLR[15]: id 57
D/bt-sdp  ( 3187): SDP_DeleteRecord ok, num_records:11
I/bt-btm  ( 3187): BTM_SEC_CLR[16]: id 58
D/bt-sdp  ( 3187): SDP_DeleteRecord ok, num_records:10
I/bt-btm  ( 3187): BTM_SEC_CLR[17]: id 59
D/bt-sdp  ( 3187): SDP_DeleteRecord ok, num_records:9
I/bt-btm  ( 3187): BTM_SEC_CLR[18]: id 60
E/BtOppRfcommListener( 3187): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/bt-sdp  ( 3187): SDP_DeleteRecord ok, num_records:8
I/bt-btm  ( 3187): Write Extended Inquiry Response to controller
I/bt-btm  ( 3187): Write Extended Inquiry Response to controller
I/bt-btm  ( 3187): Write Extended Inquiry Response to controller
I/bt-btm  ( 3187): Write Extended Inquiry Response to controller
W/bt-l2cap( 3187): L2CAP - L2CA_Deregister() called for PSM: 0x000f
I/bt-btm  ( 3187): BTM_SetDiscoverability
I/bt-btm  ( 3187): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3187): disc_mode 0000
I/bt-btm  ( 3187): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 3187): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3187): BTM_SetConnectability
I/bt-btm  ( 3187): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3187): disc_mode 0000
D/bt-btm  ( 3187): btm_ble_update_adv_flag new=0x1c
D/bt-btm  ( 3187): btm_ble_update_adv_flag old=0x18
I/bt-btm  ( 3187): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 3187): BTM_IsInquiryActive
I/bt-btm  ( 3187): BTM_CancelRemoteDeviceName()
I/bt-btm  ( 3187): btm_ble_clear_white_list
W/bt-btif ( 3187): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
D/bt-btif ( 3187): AG evt (hdl 0x0001): State 0, Event 0x0501
D/bt-btif ( 3187): AG evt (hdl 0x0002): State 0, Event 0x0501
D/bt-sdp  ( 3187): SDP_DeleteRecord ok, num_records:7
D/bt-btm  ( 3187): BTM_FreeSCN 
I/bt-btm  ( 3187): BTM_SEC_CLR[3]: id 12
D/bt-sdp  ( 3187): SDP_DeleteRecord ok, num_records:6
D/bt-btm  ( 3187): BTM_FreeSCN 
I/bt-btm  ( 3187): BTM_SEC_CLR[4]: id 29
D/bt-avp  ( 3187): AVRC_Close handle:0
D/bt-btif ( 3187): btif_hf_upstreams_evt: event=BTA_AG_DISABLE_EVT
D/bt-btif ( 3187): btif_hf_upstreams_evt: event=BTA_AG_DISABLE_EVT
D/bt-sdp  ( 3187): SDP_DeleteRecord ok, num_records:5
D/bt-sdp  ( 3187): SDP_DeleteRecord ok, num_records:4
W/bt-l2cap( 3187): L2CAP - L2CA_Deregister() called for PSM: 0x0019
D/bt-sdp  ( 3187): SDP_DeleteRecord ok, num_records:3
W/bt-l2cap( 3187): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3187): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3187): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3187): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3187): L2CAP - PSM: 0x0017 not found for deregistration
I/ActivityManager(  942): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=5502 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a
W/bt-l2cap( 3187): L2CAP - L2CA_Deregister() called for PSM: 0x0011
W/bt-l2cap( 3187): L2CAP - L2CA_Deregister() called for PSM: 0x0013
I/bt-att  ( 3187): GATT_Deregister gatt_if=3
I/bt-att  ( 3187): GATT_Listen gatt_if=3
I/bt-btm  ( 3187): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3187): BTM_ReadConnectability
I/bt-btm  ( 3187): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3187): disc_mode 0000
I/bt-att  ( 3187): GATT_Deregister gatt_if=4
I/bt-att  ( 3187): GATT_Listen gatt_if=4
I/bt-btm  ( 3187): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3187): BTM_ReadConnectability
I/bt-btm  ( 3187): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3187): disc_mode 0000
E/bt-btif ( 3187): bta_gattc_deregister Deregister Failedm unknown client cif
V/BluetoothPbapReceiver( 3187): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 3187): ***********state = 13
I/BtOppRfcommListener( 3187): stopping Accept Thread
I/BtOppRfcommListener( 3187): BluetoothSocket listen thread finished
W/System.err(  942): ,	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  942): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
D/MtpReceiver( 4007): [MTP][scanExternalVolumeIfNeed] scan external volume
W/System.err(  942): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  942): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  942): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  942): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  942): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  942): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:112)
W/System.err(  942): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  942): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  942): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  942): 
W/Settings:Agent(  942): << traceCallingStack(): 35(ms)
I/ActivityManager(  942): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=5515 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
I/QuickSettingBluetooth( 1222): receive.ACTION_STATE_CHANGE:STATE_TURNING_OFF
D/MtpReceiver( 4007): [MTP][handleUsbState]-
D/MtpReceiver( 4007): [MTP][handleMessage]-
V/BluetoothPbapService( 3187): Pbap Service closeService in
D/MtpService( 4007): updating state; isCurrentUser=true, mMtpLocked=false
V/BluetoothPbapService( 3187): successfully stopped pbap service
V/BluetoothPbapService( 3187): Pbap Service closeService out
D/MtpDatabase( 4007): TotalSize=1886532,MediaCacheLimit=6000
V/BluetoothPbapService( 3187): Pbap Service onDestroy
V/BluetoothPbapService( 3187): Pbap Service closeService in
V/BluetoothPbapService( 3187): Pbap Service closeService out
D/PMS     (  942): acquireWL(127d8ae2): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 2169 10024 null
I/bt-btm  ( 3187): btm_ble_clear_white_list_complete
D/MtpService( 4007): [isMtpConnected] connected: true
,D/WifiController(  942): handleMessage: E msg.what=155656
,D/WifiController(  942): processMsg: DeviceActiveState
D/WifiController(  942): processMsg: StaEnabledState
D/PMS     (  942): acquireWL(2c912e73): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1797 10024 WorkSource{10024 com.google.android.gms}
I/jxcore-log( 4835): ****TEST TOOK:  5314  ms ****
I/jxcore-log( 4835): 
D/WifiController(  942): transitionTo: destState=ApStaDisabledState
D/WifiController(  942): handleMessage: new destination call exit/enter
D/WifiController(  942): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiController(  942): invokeExitMethods: DeviceActiveState
D/WifiController(  942): invokeExitMethods: StaEnabledState
D/WifiController(  942): moveTempStackToStateStack: i=0,j=1
D/WifiController(  942): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=ApStaDisabledState
D/WifiController(  942): invokeEnterMethods: ApStaDisabledState
D/WifiController(  942): handleMessage: X
E/WifiStateMachine(  942): handleMessage: E msg.what=131084
E/WifiStateMachine(  942): processMsg: ConnectedState
I/jxcore-log( 4835): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4835): 
,E/WifiStateMachine(  942):  ConnectedState !CMD_STOP_SUPPLICANT 0 0
,E/WifiStateMachine(  942): processMsg: L2ConnectedState,
E/WifiStateMachine(  942):  L2ConnectedState !CMD_STOP_SUPPLICANT 0 0
D/WifiDisplayAdapter(  942): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  942):     Client/Owner: Client
D/WifiDisplayAdapter(  942):     GroupId: 
D/WifiDisplayAdapter(  942):     Passphrase: 
D/WifiDisplayAdapter(  942):     SessionId: 0
D/WifiDisplayAdapter(  942):     IP Address: }
E/WifiStateMachine(  942): processMsg: ConnectModeState
E/WifiStateMachine(  942):  ConnectModeState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  942): processMsg: DriverStartedState
E/WifiStateMachine(  942):  DriverStartedState !CMD_STOP_SUPPLICANT 0 0
D/WifiP2pService(  942): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  942): processMsg: SupplicantStartedState
D/WifiP2pService(  942): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  942):  SupplicantStartedState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  942): transitionTo: destState=WaitForP2pDisableState
E/WifiStateMachine(  942): handleMessage: new destination call exit/enter
E/WifiStateMachine(  942): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=SupplicantStartedState,active=true,parent=DefaultState
E/WifiStateMachine(  942): invokeExitMethods: ConnectedState
E/WifiStateMachine(  942): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  942): release()
E/WifiStateMachine(  942): PerfLock released for exiting ConnectedState
E/WifiStateMachine(  942): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
E/WifiStateMachine(  942): invokeExitMethods: L2ConnectedState
E/WifiStateMachine(  942): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
E/WifiStateMachine(  942): handleNetworkDisconnect f4:f2:6d:22:99:3e config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  942): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  942): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  942): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1407): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1407): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1407): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_GenerateRSASignature returns 0
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1407): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1407): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1407): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1407): CTRL_IFACE: SAVE_CONFIG - Configuration updated
I/WVCdm   (  402): CdmEngine::CloseSession
D/DrmWidevineDash(  402): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
E/WifiStateMachine(  942): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  402): L3 Terminate.
D/DrmWidevineDash(  402): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/wpa_supplicant( 1407): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1407): Pow,er_Mode_Type mode = 0
I/wpa_supplicant( 1407): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): Service_Uninitialize: starts!
D/QSEECOMAPI: (  402): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  402): QSEECom_shutdown_app, app_id = 7
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1407): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1407): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/DrmWidevineDash(  402): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  402): OEMCrypto_Terminate: ends! returns 0
D/WifiDataStallTracker(  942): setDhcpActive: false
V/NativeCrypto( 1797): Read error: ssl=0x55c3c1d420: I/O error during system call, Connection timed out
E/WifiStateMachine(  942): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  942): setDetailed state send new extra info<unknown ssid>
D/PMS     (  942): acquireWL(15ea0130): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1797 10024 WorkSource{10024 com.google.android.gms}
E/WifiStateMachine(  942): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  942): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  942): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  942): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  942): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  942): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  942): [NET] android_getaddrinfofornet-, SUCCESS
V/NativeCrypto( 1797): SSL shutdown failed: ssl=0x55c3c1d420: I/O error during system call, Broken pipe
E/WifiStateMachine(  942): NetworkAgent != null
D/ConnectivityService(  942): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
E/WifiStateMachine(  942): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
V/NetworkPolicy(  942): mWifiStateReceiver: meteredHint=false,EPS mode=false
I/ConfigFetchService( 2169): onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
D/ConnectivityService(  942): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiStateMachine(  942): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED connected
E/WifiStateMachine(  942): autoRoamSetBSSID any key="NG700"WPA_PSK
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiConfigStore(  942): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
W/WifiHW  (  942): QCOM Debug skip set_network part for security concern!
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1407): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/ConnectivityService(  942): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
D/wpa_supplicant( 1407): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1407): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
D/WifiDataStallTracker(  942): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDat,aStallTracker(  942): stopDataStallAlarm 
E/WifiTrafficPoller(  942): ENABLE_TRAFFIC_STATS_POLL true Token 11
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1407): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1407): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
E/WifiTrafficPoller(  942):  packet count Tx=220 Rx=300
E/WifiTrafficPoller(  942): notifying of data activity 0
D/wpa_supplicant( 1407): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1407): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiTrafficPoller(  942): ENABLE_TRAFFIC_STATS_POLL false Token 12
E/WifiDataStallTracker(  942): ENABLE_DATA_MONITOR_POLL false Token 1
E/WifiTrafficPoller(  942): ENABLE_TRAFFIC_STATS_POLL false Token 13
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  942): ValidatedState{ when=0 what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  942): invokeExitMethods: ConnectModeState
E/WifiStateMachine(  942): invokeExitMethods: DriverStartedState
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/wpa_supplicant( 1407): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 1407): wpa_driver_nl80211_driver_cmd: failed to issue private commands
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  942): DefaultState{ when=0 what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  942): Forcing reevaluation
I/ConfigFetchService( 2169): running network task: configservice_periodic
E/WifiStateMachine(  942): Unexpected BatchedScanResults :null
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  942): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  942): Validated
D/wpa_supplicant( 1407): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 1407): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  942): noteBatchedScanstop()
E/WifiStateMachine(  942): [1,456,842,833,163 ms] noteScanEnd no scan source
D/WifiP2pService(  942): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  942): moveTempStackToStateStack: i=0,j=2
D/WifiP2pService(  942): P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  942): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=2,Top=WaitForP2pDisableState
E/WifiStateMachine(  942): invokeEnterMethods: WaitForP2pDisableState
E/WifiStateMachine(  942): handleMessage: X
E/WifiStateMachine(  942): handleMessage: E msg.what=131212
D/WifiP2pService(  942): P2pDisablingState
E/WifiStateMachine(  942): processMsg: WaitForP2pDisableState
D/WifiScanningService(  942): SCAN_AVAILABLE : 1
E/WifiStateMachine(  942):  WaitForP2pDisableState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  942): processMsg: SupplicantStartedState
D/WifiDisplayController(  942): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiMonitor(  942): stopMonitoring(p2p0) = com.android.server.wifi.p2p.WifiP2pServiceImpl$P2pStateMachine@3956e639
D/RttService(  942): SCAN_AVAILABLE : 1
D/RttService(  942): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  942): P2pDisablingState{ when=-3ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  942):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiDisplayAdapter(  942): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  942):     Client/Owner: Client
D/WifiDisplayAdapter(  942):     GroupId: 
D/WifiDisplayAdapter(  942):     Passphrase: 
D/WifiDisplayAdapter(  942):     SessionId: 0
D/WifiDisplayAdapter(  942):     IP Address: }
E/WifiStateMachine(  942): processMsg: DefaultState
D/WifiP2pService(  942): p2p socket connection lost
D/WifiScanningService(  942): DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  942): P2pDisabledState
E/WifiStateMachine(  942):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  942): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  942): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  942): handleMessage: X
E/WifiStateMachine(  942): handleMessage: E msg.what=131212
E/WifiStateMachine(  942): processMsg: WaitForP2pDisableState
E/WifiStateMachine(  942):  WaitForP2pDisableState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  942): processMsg: SupplicantStartedState
E/WifiStateMachine(  942):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  942): processMsg: DefaultState
E/WifiStateMachine(  942):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
D/PMS     (  942): releaseWL(15ea0130): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
E/WifiStateMachine(  942): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  942): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  942): handleMessage: X
E/WifiStateMachine(  942): handleMessage: E msg.what=131212
E/WifiStateMachine(  942): processMsg: WaitForP2pDisableState
E/WifiStateMachine(  942):  WaitForP2pDisableState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  942): processMsg: SupplicantStartedState
E/WifiStateMachine(  942):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  942): processMsg: DefaultState
V/AudioService(  942): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  942):     Client/Owner: Client
V/AudioService(  942):     GroupId: 
V/AudioService(  942):     Passphrase: 
V/AudioService(  942):     SessionId: 0
V/AudioService(  942):     IP Address: }
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/HtcEffectManagerBase(  942): onEventChanged id=5 status=false
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/HtcEffectManager(  942): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true mAllPlayOn=false
D/HtcEffectManager(  942): convertEffect before=902
D/HtcEffectManager(  942): convertEffect after=902
E/WifiStateMachine(  942):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  942): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  942): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  942): handleMessage: X
D/WifiNetworkAgent(  942): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  942): handleMessage: E msg.what=131205
E/WifiStateMachine(  942): processMsg: WaitForP2pDisableState
E/WakeLock( 2169): callingPackage is not supposed to be empty for wakelock Config Service fetch!
E/WifiStateMachine(  942):  WaitForP2pDisableState !CMD_DISABLE_P2P_RSP uid=1000 0 0
E/WifiStateMachine(  942): transitionTo: destState=SupplicantStoppingState
E/WifiStateMachine(  942): handleMessage: new destination call exit/enter
E/WifiStateMachine(  942): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  942): invokeExitMethods: WaitForP2pDisableState
E/WifiStateMachine(  942): invokeExitMethods: SupplicantStartedState
E/WifiStateMachine(  942): moveTempStackToStateStack: i=0,j=1
E/WifiStateMachine(  942): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStoppingState
E/WifiStateMachine(  942): invokeEnterMethods: SupplicantStoppingState
E/WifiStateMachine(  942): Call handleNetworkDisconnect() in SupplicantStoppingState
D/WifiP2pService(  942): P2pDisabledState{ when=-1ms what=131333 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  942): DefaultState{ when=-1ms what=131333 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  942): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - enter - invokeEnterMethods
E/WifiStateMachine(  942): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1407): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1407): Power_Mode_Type mode = 0
I/wpa_supplicant( 1407): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1407): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  942): P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1407): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiP2pService(  942): DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDataStallTracker(  942): setDhcpActive: false
D/PMS     (  942): acquireWL(35ed732e): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 2169 10024 WorkSource{10024 com.google.android.gms}
I/ConfigFetchService( 2169): launchTask
D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 5515): -onCreate()
I/iu.UploadsManager( 2169): End new media; added: 0, uploading: 0, time: 93 ms
,D/PMS     (  942): releaseWL(127d8ae2): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 null
V/ConfigFetchTask( 2169): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1WKcWMWvCU23ME-060oMI-0Nt2IjOb3iC_tLRYeRUCexn4OtPmmJcXEgqD3ZCQtJ-bFpFS_Ud9Gl0JMrv656wJP4FJRw9Yser-Q7_IOhdj7HzT8Olja7A3gGIHINz5t70wYo6olADobN6Ier3TB-mXNIhOx9wtE1MCFa8SbOLKn9wnkIVvfXavfqa9XQEjp-EPn0pB_
I/QuickSettingWifi( 1222): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:1
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:1
E/MediaScannerService( 4007): [onStartCommand] --- Should not be here, redirect request. ----
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:1
E/MediaScannerService( 4007): [handleMessage] --- Should not be here, ignore request. ----
V/Settings:HtcSettingsApplication( 5515): [5515/5515] onCreate()
,D/PMS     (  942): acquireWL(8a6005c): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 5515 1000 null
,W/ContextImpl( 5515): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
D/SyncApplication( 5502): Loading default preferences
I/CheckinRequestBuilder( 2169): Classify the device as Phone.
,I/HtcModeClient( 3270): handler message = 4011
,E/HtcModeClient( 3270): Check connection and retry 5 times.
,W/bt-btif ( 3187): ag scb idx 1 not allocated
W/bt-btif ( 3187): ag scb idx 2 not allocated
E/bt-btif ( 3187): BTA AG is already disabled, ignoring ...
D/bt-btm  ( 3187): L2CAP - L2CA_Deregister() called for PSM
W/bt-l2cap( 3187): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3187): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3187): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3187): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3187): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3187): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3187): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3187): L2CAP - PSM: 0x0017 not found for deregistration
,W/bt-l2cap( 3187): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3187): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3187): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3187): L2CAP - PSM: 0x0017 not found for deregistration
E/bt-btif ( 3187): bta_gattc_deregister Deregister Failedm unknown client cif
E/bt_userial_mct( 3187): pthread_join() FAILED result:3
I/ActivityManager(  942): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=5561 uid=10034 gids={50034, 9997, 3002, 3001} abi=arm64-v8a
,I/GoogleURLConnFactory( 2169): Using platform SSLCertificateSocketFactory,
,D/WISPrService( 5515): >>>>>WISPrService start isConnected = true<<<<<
W/Resources( 5502): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
D/PMS     (  942): releaseWL(8a6005c): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
,D/PMS     (  942): acquireWL(dc0c648): PARTIAL_WAKE_LOCK  StartingDockService 0x1 5515 1000 null
,E/WifiTrafficPoller(  942): ADD_CLIENT: 8
,D/WifiService(  942): New client listening to asynchronous messages
,D/libc    ( 2169): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,D/libc    ( 2169): [NET] android_getaddrinfofornet-, err=8
W/System.err(  942): java.lang.Throwable: stack dump
D/BluetoothManagerService(  942): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  942): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  942): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
D/BluetoothManagerService(  942): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@38c4ba06:true
W/System.err(  942): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  942): 	at android.os.Binder.execTransact(Binder.java:454)
D/libc    ( 2169): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 2169): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    ( 2169): [NET] android_getaddrinfo_proxy+
,D/ConnectivityService(  942): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,E/WifiStateMachine(  942): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false,
D/ConnectivityService(  942):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1222): CM callback handler got msg 524292
D/ConnectivityService(  942):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine(  942): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/ConnectivityService(  942): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
I/SecurityController( 1222): onLost 100
D/Nat464Xlat(  942): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  942): ValidatedState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  942): DefaultState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  942): Disconnected - quitting
D/ConnectivityService(  942): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  942): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/usbnet  (  942): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService(  942): Removing idletimer
D/usbnet  (  942):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  942): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/PMS     (  942): acquireWL(23e27092): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 942 1000 null
D/libc    ( 2169): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/CSLegacyTypeTracker(  942): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/ConnectivityService(  942): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine(  942): stopping supplicant
W/WifiHW  (  942): QCOM Debug wifi_send_command "TERMINATE"
D/wpa_supplicant( 1407): RX global ctrl_iface - hexdump(len=9): 54 45 52 4d 49 4e 41 54 45
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/wpa_supplicant( 1407): wlan0: Removing interface wlan0
D/BluetoothAdapter( 5515): 375860712: getState(). Returning 13
E/WifiTrafficPoller(  942): ENABLE_TRAFFIC_STATS_POLL false Token 14
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
D/ConnectivityService(  942): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
E/WifiStateMachine(  942): setWifiState: disabling
E/ConnectivityService(  942): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/Tethering(  942): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
V/NetworkPolicy(  942): ensureActiveMobilePolicyLocked()
D/Tethering(  942): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/wpa_supplicant( 1407): wlan0: Request to deauthenticate - bssid=f4:f2:6d:22:99:3e pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/PMS     (  942): acquireWL(28a29a63): PARTIAL_WAKE_LOCK  NetworkStats 0x1 942 1000 null
D/wpa_supplicant( 1407): TDLS: Tear down peers
E/ConnectivityService(  942): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilitie,s: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/wpa_supplicant( 1407): wpa_driver_nl80211_disconnect(reason_code=3)
D/libc    ( 2169): [NET] android_getaddrinfo_proxy-, NODATA
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  942): handleMessage: X
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  942): handleMessage: E msg.what=131131
D/DATA_ICON( 1222): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
E/WifiStateMachine(  942): processMsg: SupplicantStoppingState
E/WifiStateMachine(  942):  SupplicantStoppingState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  942): processMsg: DefaultState
E/WifiStateMachine(  942):  DefaultState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  942): handleMessage: X
D/WIFI    (  942): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  942):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  942): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
E/WifiStateMachine(  942): enter WifiNetworkFactory startNetwork. mIPTStart:false
I/IntentController( 1222): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
I/art     ( 2169): Background partial concurrent mark sweep GC freed 8855(398KB) AllocSpace objects, 2(40KB) LOS objects, 40% free, 5MB/9MB, paused 7.817ms total 61.128ms
,E/MediaScannerServiceEx( 4007): [getStorageMaskIdFromPath] path is null
D/NetworkPolicy(  942): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
D/MediaScannerServiceEx( 4007): [ServiceHandler][handleMessage] , action: null, Id: 0, path: /storage/emulated/0
V/NetworkPolicy(  942): updateNetworkEnabledLocked()
D/WISPrService( 5515): >>>>>WISPrService start isConnected = false<<<<<
V/NetworkPolicy(  942): updateIfacesLocked()
D/WISPrService( 5515): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
V/NetworkPolicy(  942): updateNotificationsLocked()
D/DATA_ICON( 1222): dataConnected: false/false
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WIFI_ICON( 1222): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/MediaScannerServiceEx( 4007): [handleExternalVolume] ext storage
,D/NetworkManagementService(  942): isBandwidthControlEnabled: doneSignal.getCount()= 0
,D/WISPrService( 5515): >>>>>WISPrService start isConnected = false<<<<<
D/PMS     (  942): releaseWL(28a29a63): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
W/ConfigFetchTask( 2169): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/WISPrService( 5515): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/MediaProviderUtils( 4007): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 4007): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 4007): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 4007): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
D/MediaScannerServiceEx( 4007): [AliveExtStorageRows]+65537, 11223344
I/ConfigFetchService( 2169): fetch service done; releasing wakelock
V/NetworkPolicy(  942): updateNetworkEnabledLocked()
V/NetworkPolicy(  942): updateNotificationsLocked()
,D/PMS     (  942): releaseWL(35ed732e): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 WorkSource{10024 com.google.android.gms}
D/MediaProvider( 4007): [update][4]#0#
I/ConfigFetchService( 2169): stopping self
,D/MediaProvider( 4007): [update][2]#0#
,D/PMS     (  942): releaseWL(2c912e73): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/WifiService(  942): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
,E/WifiStateMachine(  942): handleMessage: E msg.what=196614
E/WifiStateMachine(  942): processMsg: SupplicantStoppingState
E/WifiStateMachine(  942):  SupplicantStoppingState !CMD_ON_QUIT 0 0
E/WifiStateMachine(  942): processMsg: DefaultState
E/WifiStateMachine(  942):  DefaultState !CMD_ON_QUIT 0 0
,E/WifiStateMachine(  942): handleMessage: X
,D/BluetoothInputDevice( 5515): BluetoothInputDevice()
D/BluetoothManagerService(  942): registerStateChangeCallback+
D/BluetoothManagerService(  942): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  942): Registered receivers: 9,
,D/WifiService(  942): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
,D/BluetoothPan( 5515): BluetoothPan()
,D/BluetoothManagerService(  942): registerStateChangeCallback+
D/BluetoothManagerService(  942): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/MediaProvider( 4007): [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
D/MtpService( 4007): [sendStorageAdded] Already send to MTP: /storage/emulated/0
D/BluetoothManagerService(  942): Registered receivers: 10
,D/HtcBtWidget_BTWidgetProvider( 5561): onBTStateChanged() for widget: 
D/WifiService(  942): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
D/HtcBtWidget_BTWidgetProvider( 5561): updateWidget(context) for widget: 
D/PMS     (  942): releaseWL(387bcf56): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:0
,D/wpa_supplicant( 1407): wlan0: Event DEAUTH (12) received
,D/wpa_supplicant( 1407): wlan0: Deauthentication notification
D/wpa_supplicant( 1407): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1407): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1407): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1407): wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1 ssid='NG700' freq=2437
E/wpa_supplicant( 1407): enter disconnect check
I/wpa_supplicant( 1407): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/Tethering(  942): interfaceLinkStateChanged wlan0, false
D/Tethering(  942): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  942): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1407): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 1407): wlan0: Ignore connection failure indication since interface has been put into disconnected state
I/QuickSettingWifi( 1222): receive.wifiState:WIFI_STATE_DISABLING setEnable:false
,D/Tethering(  942): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  942): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  942): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiStateMachine(  942): WiFiDisplay: getWifidisplayApEnabled=false
D/WifiMonitor(  942): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1 ssid='NG700' freq=2437]
,E/WifiMonitor(  942): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1 ssid='NG700' freq=2437
E/WifiMonitor(  942): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1 ssid='NG700' freq=2437
D/HTCRequest(  942): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1 ssid='NG700' freq=2437
,D/wpa_supplicant( 1407): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1407): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 1407): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1407): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1407): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x5596724f88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1407):    addr=f4:f2:6d:22:99:3e
D/wpa_supplicant( 1407): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1407): nl80211: Set wlan0 operstate 1->0 (DORMANT)
,D/wpa_supplicant( 1407): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1407): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1407): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1407): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1407): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1407): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1407): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1407): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1407): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1407): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1407): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1407): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1407): EAPOL: External notification - portValid=0
D/Tethering(  942): interfaceLinkStateChanged wlan0, false
D/Tethering(  942): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  942): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiMonitor(  942): WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
D/WifiMonitor(  942): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
E/WifiStateMachine(  942): handleMessage: E msg.what=147460
E/WifiStateMachine(  942): processMsg: SupplicantStoppingState
E/WifiStateMachine(  942):  SupplicantStoppingState !NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=65920
E/WifiStateMachine(  942): processMsg: DefaultState
E/WifiMonitor(  942): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
D/HTCRequest(  942): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
D/HTCRequest(  942): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
E/WifiStateMachine(  942):  DefaultState !NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=65921
D/HTCRequest(  942): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/WifiStateMachine(  942): handleMessage: X
,D/WifiMonitor(  942): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/WifiStateMachine(  942): handleMessage: E msg.what=147462
E/WifiStateMachine(  942): processMsg: SupplicantStoppingState
E/WifiStateMachine(  942):  SupplicantStoppingState !SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=65922  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
E/WifiStateMachine(  942): processMsg: DefaultState,
E/WifiStateMachine(  942):  DefaultState !SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=65924  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
E/WifiStateMachine(  942): handleMessage: X
,D/MediaProvider( 4007): [update][42]#1#
D/BluetoothFtpService( 3187): ACTION_STATE_CHANGED: state: 13mHasStarted: true
D/PMS     (  942): acquireWL(24637051): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1797 10024 WorkSource{10024 com.google.android.gms}
E/BluetoothFtpService:RfcommSocketAcceptThread( 3187): Shutdown
D/MediaScannerServiceEx( 4007): [AliveExtStorageRows]-0, 0
,D/PMS     (  942): acquireWL(3a35b0b6): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 4007 10017 null
D/BluetoothMap( 5515): Create BluetoothMap proxy object
D/BluetoothManagerService(  942): registerStateChangeCallback+
D/Tethering(  942): sendTetherStateChangedBroadcast 0, 0, 0
,E/BluetoothMap( 5515): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/BluetoothManagerService(  942): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  942): Registered receivers: 11
,D/BluetoothManagerService(  942): registerStateChangeCallback+
D/UsbnetService(  942): BroadcastReceiver::onReceive+,
D/UsbDeviceManager(  942): [USBNET] bCheckSuppFunc: cdc_network
D/UsbnetService(  942): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/WifiService(  942): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
D/UsbnetService(  942): BroadcastReceiver::onReceive-
D/PMS     (  942): acquireWL(3f5b0d24): PARTIAL_WAKE_LOCK  NetworkStats 0x1 942 1000 null
D/BluetoothMasReceiver( 3187): Bluetooth STATE CHANGED to 13
E/WifiStateMachine(  942): handleMessage: E msg.what=131101
E/WifiStateMachine(  942): processMsg: SupplicantStoppingState
E/WifiStateMachine(  942):  SupplicantStoppingState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  942): processMsg: DefaultState
D/BluetoothSap( 5515): BluetoothSap() call bindService
D/BluetoothManagerService(  942): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  942): Registered receivers: 12
E/WifiStateMachine(  942):  DefaultState !CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  942): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  942): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  942): handleMessage: X
V/BluetoothSapReceiver( 3187): SapReceiver onReceive 
V/BluetoothSapReceiver( 3187): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3187):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 3187): startService = false
,D/MediaScanner( 4007): =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1,
V/NetworkPolicy(  942): updateNetworkEnabledLocked()
D/PMS     (  942): releaseWL(3f5b0d24): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
V/NetworkPolicy(  942): updateNotificationsLocked()
D/SyncApplication( 5502): Overriding preferences with custom values
,W/ContextImpl( 5515): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1888 android.content.ContextWrapper.bindService:538 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1423 
D/WifiService(  942): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
,D/BluetoothPbap( 5515): BluetoothPbap()
,D/BluetoothManagerService(  942): registerStateChangeCallback+
D/PMS     (  942): releaseWL(3867abd7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/BluetoothManagerService(  942): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  942): Registered receivers: 13
,D/PMS     (  942): acquireWL(a16208e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1797 10024 WorkSource{10024 com.google.android.gms}
D/LocalBluetoothProfileManager( 5515): LocalBluetoothProfileManager construction complete
,D/WifiService(  942): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
,D/SyncApplication( 5502): Updating preferences succeeded
D/WifiService(  942): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
D/MdScPhnSt( 5136): [87e.2.]  listen tmrbb8
E/SyncApplication( 5502): Application created.
D/DockEventReceiver( 5515): finishStartingService: stopping service
,D/BluetoothInputDevice( 5515): Proxy object connected
D/WifiService(  942): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
D/WISPrService( 5515): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5515): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/HidProfile( 5515): Bluetooth service connected
,D/BluetoothAdapter( 5515): 375860712: getState(). Returning 13
,D/BluetoothPan( 5515): BluetoothPAN Proxy object connected
D/WifiService(  942): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
D/PanProfile( 5515): Bluetooth service connected
D/SapServerProfile( 5515): Bluetooth service connected
D/PMS     (  942): releaseWL(dc0c648): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
,W/VolumeInfo( 5502): Unable to read mount points
W/VolumeInfo( 5502): java.io.FileNotFoundException: /etc/vold.fstab: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 5502): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/VolumeInfo( 5502): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/VolumeInfo( 5502): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/VolumeInfo( 5502): 	at java.io.FileReader.<init>(FileReader.java:66)
W/VolumeInfo( 5502): 	at com.nero.android.common.VolumeInfo.getVolumeMountPoints(VolumeInfo.java:194)
W/VolumeInfo( 5502): 	at com.nero.android.common.VolumeInfo.getVolumes(VolumeInfo.java:153)
W/VolumeInfo( 5502): 	at com.nero.android.common.VolumeInfo.initializeVolumeIDs(VolumeInfo.java:474),
W/VolumeInfo( 5502): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:51)
W/VolumeInfo( 5502): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:1)
W/VolumeInfo( 5502): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/VolumeInfo( 5502): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/VolumeInfo( 5502): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/VolumeInfo( 5502): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/VolumeInfo( 5502): 	at java.lang.Thread.run(Thread.java:818)
W/VolumeInfo( 5502): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 5502): 	at libcore.io.Posix.open(Native Method)
W/VolumeInfo( 5502): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/VolumeInfo( 5502): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/VolumeInfo( 5502): 	... 13 more
V/VolumeInfo( 5502): Found 0 mount point(s)
V/VolumeInfo( 5502): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,I/CalendarDefines( 5502): getNewCalendarAuthority()...,
,I/art     (  942): Explicit concurrent mark sweep GC freed 41129(2MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/25MB, paused 6.290ms total 172.205ms
D/WifiService(  942): New client listening to asynchronous messages
I/Prism.ItemManager( 1479): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1479): loadItems() com.htc.launcher.pageview.WidgetManager@1b9c392a +
I/Prism.WidgetManager( 1479): onLoadItems() +
,I/bt-btif ( 3187): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 3187): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterService( 3187): mProfilesStarted : true supportedProfileServices.length : 6
,I/PackageManager(  942):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=5502, uid=10005, userID:0
,E/WifiTrafficPoller(  942): ADD_CLIENT: 9
D/VolumeInfo( 5502): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,W/PackageManager(  942): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  942):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=5502, uid=10005, userID:0
D/SyncApplication( 5502): enableAppOperation()+
W/PackageManager(  942): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/HeadsetService( 3187): Received stop request...Stopping profile...
,D/SyncApplication( 5502): enableAppOperation()-
,D/PMS     (  942): releaseWL(a16208e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/AuthorizationBluetoothService( 1797): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/Prism.ItemManager( 5036): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
I/Prism.ItemManager( 5036): loadItems() com.htc.launcher.pageview.WidgetManager@8749b32 +
I/Prism.WidgetManager( 5036): onLoadItems() +
D/HTCUtilities( 5502): isNeorSinged() + 
,D/VolumeInfo( 5502): Read the volume-id from the sd card: {9B5E872B-8520-47C6-8BD3-3081C2E38355}
W/VolumeInfo( 5502): Can not create volume ID for unmounted volume null
D/WifiService(  942): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
,D/BluetoothAdapterService( 3187): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f77ecc9
D/WifiService(  942): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
D/HeadsetStateMachine( 3187): Exit Disconnected: -1
D/BluetoothHeadset(  942): Proxy object disconnected,
D/BluetoothHeadset( 1222): Proxy object disconnected
D/BluetoothHeadset( 3882): Proxy object disconnected
D/NGFService( 3882): BluetoothHeadset onServiceDisconnected: main
I/QuickSettingMiniLite( 1222): btListener.disconnect:HEADSET
D/A2dpService( 3187): Received stop request...Stopping profile...
,D/A2dpStateMachine( 3187): Exit Disconnected: -1
D/HTCUtilities( 5502): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
D/BluetoothAdapterService( 3187): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f77ecc9
,D/libc    ( 2169): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,D/libc    ( 2169): [NET] android_getaddrinfofornet-, err=8
E/CheckinTask( 2169): Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,E/wpa_supplicant( 1407): wlan0: BLACKLIST CLEAR 
,D/wpa_supplicant( 1407): wlan0: BSS: Remove id 0 BSSID f0:f2:6d:22:99:3e SSID 'NG700_GUEST' due to wpa_bss_flush
D/wpa_supplicant( 1407): wlan0: BSS: Remove id 1 BSSID f4:f2:6d:22:99:3e SSID 'NG700' due to wpa_bss_flush
D/wpa_supplicant( 1407): wlan0: BSS: Remove id 3 BSSID 00:1f:27:54:70:c0 SSID 'ktwtestwifi' due to wpa_bss_flush
D/wpa_supplicant( 1407): wlan0: BSS: Remove id 2 BSSID 00:1f:27:54:70:c1 SSID 'TEST_KTW01' due to wpa_bss_flush
D/wpa_supplicant( 1407): wlan0: BSS: Remove id 4 BSSID 34:4d:f7:73:42:46 SSID '_Aya' due to wpa_bss_flush
D/wpa_supplicant( 1407): wlan0: BSS: Remove id 9 BSSID 00:1f:27:54:dd:e4 SSID '\x00' due to wpa_bss_flush
D/wpa_supplicant( 1407): wlan0: BSS: Remove id 5 BSSID 00:1f:27:54:dd:e2 SSID '\x00' due to wpa_bss_flush
D/wpa_supplicant( 1407): wlan0: BSS: Remove id 6 BSSID 00:1e:4a:8f:e3:63 SSID 'RA-WINGS' due to wpa_bss_flush
D/wpa_supplicant( 1407): wlan0: BSS: Remove id 8 BSSID 00:1f:27:54:dd:e3 SSID 'RA-WINGS' due to wpa_bss_flush
D/wpa_supplicant( 1407): wlan0: BSS: Remove id 7 BSSID 00:22:0d:46:1c:a3 SSID 'RA-WINGS' due to wpa_bss_flush
D/wpa_supplicant( 1407): wlan0: BSS: Remove id 10 BSSID 00:1e:4a:8f:df:d3 SSID 'RA-WINGS' due to wpa_bss_flush
D/wpa_supplicant( 1407): wlan0: Cancelling delayed sched scan
D/wpa_supplicant( 1407): wlan0: Cancelling scan request
D/wpa_supplicant( 1407): wlan0: Cancelling authentication timeout
E/wpa_supplicant( 1407): wlan0: BLACKLIST REMOVE 00:00:00:00:00:00
D/WifiMonitor(  942): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  942): WifiMonitor:wlan0 cnt=35 dispatchEvent: BLACKLIST CLEAR 
,D/WifiMonitor(  942): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 f0:f2:6d:22:99:3e]
E/WifiMonitor(  942): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 f0:f2:6d:22:99:3e
D/WifiMonitor(  942): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 f4:f2:6d:22:99:3e]
E/WifiMonitor(  942): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 f4:f2:6d:22:99:3e
D/WifiMonitor(  942): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 00:1f:27:54:70:c0]
E/WifiMonitor(  942): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 00:1f:27:54:70:c0
D/HTCUtilities( 5502): isNeorSinged() return false
D/WifiMonitor(  942): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 00:1f:27:54:70:c1]
E/WifiMonitor(  942): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 00:1f:27:54:70:c1
D/WifiMonitor(  942): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 34:4d:f7:73:42:46]
E/WifiMonitor(  942): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 34:4d:f7:73:42:46
D/BluetoothAdapterState( 3187): Stopping profile services that were post enabled
D/WifiMonitor(  942): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 9 00:1f:27:54:dd:e4]
E/WifiMonitor(  942): WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-BSS-REMOVED 9 00:1f:27:54:dd:e4
D/WifiMonitor(  942): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 00:1f:27:54:dd:e2]
E/WifiMonitor(  942): WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-BSS-REMOVED 5 00:1f:27:54:dd:e2
D/WifiMonitor(  942): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 00:1e:4a:8f:e3:63]
E/WifiMonitor(  942): WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-BSS-REMOVED 6 00:1e:4a:8f:e3:63
D/WifiMonitor(  942): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 00:1f:27:54:dd:e3]
E/WifiMonitor(  942): WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-BSS-REMOVED 8 00:1f:27:54:dd:e3
D/WifiMonitor(  942): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 00:22:0d:46:1c:a3]
E/WifiMonitor(  942): WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-BSS-REMOVED 7 00:22:0d:46:1c:a3
D/WifiMonitor(  942): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 10 00:1e:4a:8f:df:d3]
E/WifiMonitor(  942): WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-BSS-REMOVED 10 00:1e:4a:8f:df:d3
D/WifiMonitor(  942): Event [IFNAME=wlan0 BLACKLIST REMOVE 00:00:00:00:00:00]
,E/WifiMonitor(  942): WifiMonitor:wlan0 cnt=47 dispatchEvent: BLACKLIST REMOVE 00:00:00:00:00:00
D/BluetoothA2dp(  942): Proxy object disconnected
D/BluetoothA2dp( 3882): Proxy object disconnected
D/NGFService( 3882): BluetoothA2dp onServiceDisconnected: main
D/wpa_supplicant( 1407): Remove interface wlan0 from radio phy0
D/CDMountReceiver( 5502): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
D/CDMountReceiver( 5502): USB connected to PC
D/WifiService(  942): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
D/HidService( 3187): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3187): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f77ecc9
D/BluetoothInputDevice( 5515): Proxy object disconnected
D/HidProfile( 5515): Bluetooth service disconnected
,D/WifiService(  942): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
,D/HealthService( 3187): Received stop request...Stopping profile...
,I/CheckinService( 2169): Checking schedule, now: 1456842833607 next: 1456842843584
I/CheckinService( 2169): active receiver: disabled
,I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2169, uid=10024, userID:0
,D/BluetoothAdapterService( 3187): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f77ecc9
,W/ResourcesManager( 1479): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/GoogleURLConnFactory( 1797): Using platform SSLCertificateSocketFactory
,W/BluetoothHeadsetServiceJni( 3187): Cleaning up Bluetooth Handsfree Interface...
D/WifiService(  942): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
W/BluetoothHeadsetServiceJni( 3187): Cleaning up Bluetooth Handsfree callback object
D/PanService( 3187): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3187): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f77ecc9,
D/BtGatt.DebugUtils( 3187): handleDebugAction() action=null
D/BtGatt.GattService( 3187): Received stop request...Stopping profile...
D/BtGatt.GattService( 3187): stop()
D/BtGatt.AdvertiseManager( 3187): advertise clients cleared
,D/MdProvGlob( 5161): remove item 101 (p2d9in227) for 15:android.intent.action.ANY_DATA_STATE
,D/BluetoothPan( 5515): BluetoothPAN Proxy object disconnected,
D/PMS     (  942): releaseWL(37dbdd5c): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
D/PanProfile( 5515): Bluetooth service disconnected
,D/BluetoothAdapterService( 3187): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f77ecc9
D/FOTAReceiver( 5502): onReceive() enter 
D/PMS     (  942): acquireWL(2a85f5f9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1797 10024 WorkSource{10024 com.google.android.gms}
D/FOTAReceiver( 5502): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
D/MdScDataSum( 5136): [87e.2.] summary 118:p2 ignore
D/BluetoothHeadset( 1424): Proxy object disconnected
D/BluetoothHeadset( 1424): Proxy object disconnected
D/BluetoothHeadset( 1424): Proxy object disconnected
,D/WifiService(  942): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
,W/BluetoothHidServiceJni( 3187): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 3187): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 3187): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3187): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3187): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3187): Cleaning up Bluetooth PAN callback object
,D/BluetoothPhoneService( 1424): BluetoothHeadset onServiceDisconnected
,D/BluetoothAdapterState( 3187): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3187): Setting state to 10
I/BluetoothAdapterState( 3187): Bluetooth adapter state changed: 13-> 10
D/BluetoothManagerService(  942): +onBluetoothStateChange prev=13 new=10
I/BluetoothAdapterState( 3187): Entering OffState
D/BluetoothManagerService(  942): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  942): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  942): Broadcasting onBluetoothStateChange(false) to 13 receivers.
D/BluetoothSap( 5515): onBluetoothStateChange on: false
,V/BluetoothSapService( 3187): cleanup: mService: com.android.bluetooth.sap.BluetoothSapService@3e34bdd5
D/PMS     (  942): releaseWL(2a85f5f9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  942): acquireWL(2391c93e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1797 10024 WorkSource{10024 com.google.android.gms}
,D/MdProvGlob( 5161): remove item 101 (p2d1in24) for 15:android.intent.action.ANY_DATA_STATE
,D/BluetoothHeadset(  942): onBluetoothStateChange: up=false
,D/BluetoothMap( 5515): onBluetoothStateChange: up=false
E/BluetoothMap( 5515): 
E/BluetoothMap( 5515): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothMap$2@ad89a39
E/BluetoothMap( 5515): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1135)
E/BluetoothMap( 5515): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1940)
E/BluetoothMap( 5515): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
E/BluetoothMap( 5515): 	at android.bluetooth.BluetoothMap$1.onBluetoothStateChange(BluetoothMap.java:64),
E/BluetoothMap( 5515): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothMap( 5515): 	at android.os.Binder.execTransact(Binder.java:454)
D/wpa_supplicant( 1407): nl80211: Remove monitor interface: refcount=0
D/wpa_supplicant( 1407): netlink: Operstate: ifindex=29 linkmode=0 (kernel-control), operstate=6 (IF_OPER_UP)
W/ResourcesManager( 5036): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/TetherSettings( 5515): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5515): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5515): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5515): Cust_ConnectToPC   : spcsc>false
D/        ( 5515): Cust_ConnectToPC   : IPT>true
D/        ( 5515): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 5515): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/BluetoothHeadset( 1222): Proxy not attached to service
I/QuickSettingMiniLite( 1222): updateLiteState:no connect device!
D/BluetoothInputDevice( 5515): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1424): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1424): onBluetoothStateChange: up=false
D/BluetoothPbap( 5515): onBluetoothStateChange: up=false
,E/SmartNS_Utility( 5515): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5515): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5515): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
D/BluetoothHeadset( 3882): onBluetoothStateChange: up=false
D/SmartNS_Utility( 5515): usb_cable_connect = 1
,D/SmartNS_Utility( 5515): usb_denied = 0
,D/BluetoothHeadset( 1424): onBluetoothStateChange: up=false
,D/BluetoothA2dp(  942): onBluetoothStateChange: up=false
,D/BluetoothPan( 5515): onBluetoothStateChange on: false
,I/SmartNS_NSReceiver( 5515): locked:falsesecurity:falseisLocked:false
D/SmartNS_NSReceiver( 5515): USB = true hasTethered = false isNSOpening: false
D/BluetoothA2dp( 3882): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1222): onBluetoothStateChange: up=false
,D/wpa_supplicant( 1407): nl80211: Set mode ifindex 29 iftype 2 (STATION)
D/wpa_supplicant( 1407): nl80211: Unsubscribe mgmt frames handle 0x888888dd1efae989 (mode change)
I/wpa_supplicant( 1407): htc_wext_command_deinit +
I/wpa_supplicant( 1407): htc_wext_command_deinit -
I/wpa_supplicant( 1407): wlan0: CTRL-EVENT-TERMINATING 
D/WifiMonitor(  942): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
E/WifiMonitor(  942): WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-TERMINATING 
,D/wpa_supplicant( 1407): Control interface directory not empty - leaving it behind
D/Tethering(  942): interfaceLinkStateChanged wlan0, false
D/Tethering(  942): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1407): p2p0: Removing interface p2p0
D/wpa_supplicant( 1407): p2p0: Request to deauthenticate - bssid=00:00:00:00:00:00 pending_bssid=00:00:00:00:00:00 reason=3 state=DISCONNECTED
D/wpa_supplicant( 1407): TDLS: Tear down peers
E/WifiStateMachine(  942): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1407): p2p0: State: DISCONNECTED -> DISCONNECTED
D/WifiMonitor(  942): Disconnecting from the supplicant, no more events
D/wpa_supplicant( 1407): nl80211: Set p2p0 operstate 0->0 (DORMANT)
W/ContextImpl( 5515): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2712 
D/wpa_supplicant( 1407): netlink: Operstate: ifindex=30 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
E/WifiStateMachine(  942): handleMessage: E msg.what=147458
D/wpa_supplicant( 1407): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1407): EAPOL: External notification - portValid=0
E/WifiStateMachine(  942): processMsg: SupplicantStoppingState
,I/PSReceiver( 5515): onReceive:com.htc.intent.action.USB_CONNECT2PC
E/WifiStateMachine(  942):  SupplicantStoppingState !SUP_DISCONNECTION_EVENT 48 0
E/WifiStateMachine(  942): Supplicant connection lost
,D/BluetoothManagerService(  942): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  942): Broadcasting onBluetoothServiceDown() to 10 receivers.
,D/BluetoothAdapter( 4835): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@32f51ecd
D/BluetoothAdapter( 4835): onBluetoothServiceDown: done
,D/BluetoothAdapter( 3882): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@1e4d387e
D/BluetoothAdapter( 3882): onBluetoothServiceDown: done,
D/BluetoothAdapter( 3187): onBluetoothServiceDown: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@36898c85
,D/BluetoothAdapter( 3187): onBluetoothServiceDown: done
D/BluetoothAdapter( 1450): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@1b9b8083
,D/BluetoothAdapter( 1450): onBluetoothServiceDown: done
I/SmartNS_PSService( 5515): onReceive:com.htc.intent.action.USB_CONNECT2PC
D/BluetoothAdapter( 1424): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@2bdb59eb
D/BluetoothAdapter( 1424): onBluetoothServiceDown: done
,D/BluetoothAdapter( 1866): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@b115ef9
D/BluetoothAdapter( 1866): onBluetoothServiceDown: done
D/BluetoothAdapter(  942): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@21a8109
D/BluetoothAdapter(  942): onBluetoothServiceDown: done
,D/BluetoothAdapter( 2393): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@2a6c1e2a
D/BluetoothAdapter( 2393): onBluetoothServiceDown: done
D/BluetoothAdapter( 5515): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@31400e2c
D/BluetoothAdapter( 5515): onBluetoothServiceDown: done
,D/BluetoothAdapter( 1222): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@18a584c2
D/BluetoothAdapter( 1222): onBluetoothServiceDown: done
D/BluetoothManagerService(  942): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@21a8109 mBinding = false
W/Settings( 5515): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 5515):  defaultType:0
I/SmartNS_PSService( 5515): fail notificaiton:false
D/BluetoothManagerService(  942): Sending unbind request.
,D/SmartNS_Utility( 5515): usb_cable_connect = 1
D/MdProvGlob( 5161): remove item 101 (p2d2in49) for 15:android.intent.action.ANY_DATA_STATE
,D/SmartNS_Utility( 5515): usb_denied = 0
I/SmartNS_PSService( 5515): usb notificaiton:true
,E/WifiStateMachine(  942): WiFiDisplay: getWifidisplayApEnabled=false
,I/ActivityManager(  942): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=5604 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,D/MdProvGlob( 5161): remove item 101 (p2in24) for 15:android.intent.action.ANY_DATA_STATE
,D/BluetoothManagerService(  942): Bluetooth State Change Intent: 13 -> 10
,I/ActionCombine( 5515): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,I/bt-btif ( 3187): HAL bt_hal_cbacks->thread_evt_cb
,D/NfcHandover( 1450): onReceive: mBound=false, BTByNfc=false->false, BTHConnected=false->false
D/NGFService( 3882): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
I/IntentController( 1222): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/NGFService( 3882): Bluetooth Adapter: OFF
,I/art     ( 3187): System.exit called, status: 0
D/SmartNS_Utility( 5515): usb_cable_connect = 1
D/SmartNS_Utility( 5515): usb_denied = 0
I/SmartNS_PSService( 5515): usb notificaiton:true
E/WifiStateMachine(  942): WiFiDisplay: getWifidisplayApEnabled=false
,D/PMS     (  942): acquireWL(1fefabb): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1797 10024 WorkSource{10024 com.google.android.gms}
E/cutils-trace( 5553): Error opening trace file: Permission denied (13)
D/DotMatrix( 1301): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,D/CustomizationManager( 5553): ====startRecUseTime====,
D/htc.customization.log.level( 5553):  is 
W/CustomizationLogLevel( 5553): Level value is invalid, use default level 2
,I/ActivityManager(  942): Recipient 3187,
,D/BluetoothAdapter( 1222): 18717900: getState() :  mService = null. Returning STATE_OFF
I/QuickSettingBluetooth( 1222): receive.ACTION_STATE_CHANGE:STATE_OFF/(false,false)
,I/RemoteViews( 1222): reapply : com.android.settings 1 36
D/MdProvGlob( 5161): remove item 101 (p2in42) for 15:android.intent.action.ANY_DATA_STATE
D/SmartNS_Utility( 5515): usb_cable_connect = 1
D/SmartNS_Utility( 5515): usb_denied = 0
,I/SmartNS_PSService( 5515): KeyGuard locked:falseKeyGuard is secured:false
D/SmartNS_PSService( 5515): USB Plugged, Set USBPlugged=  truePSenabled:false
,I/ActivityManager(  942): Process com.android.bluetooth (pid 3187) has died
W/ActivityManager(  942): Scheduling restart of crashed service com.android.bluetooth/.map.BluetoothMasService in 1000ms,
W/ActivityManager(  942): Scheduling restart of crashed service com.android.bluetooth/.sap.BluetoothSapService in 10999ms
I/BroadcastQueue(  942): Schedule to resend BroadcastRecord{3197ebd8 u-1 android.bluetooth.adapter.action.STATE_CHANGED callingPid=942 callingUid=1000} for ResolveInfo{289b6b31 com.android.bluetooth/.pbap.BluetoothPbapReceiver m=0x108000} of com.android.bluetooth
,D/LocalBluetoothProfileManager( 5515): setBluetoothStateOff
W/BluetoothEventManager( 5515): unregister mProfileBroadcastReceiver fail
,D/TetherPref( 5515): persistRestoreBluetoothState false
,I/RemoteViews( 1222): reapply : com.android.settings 1 36
,D/DotMatrix( 1301): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/ActivityManager(  942): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=5642 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3008} abi=armeabi-v7a
,I/ActivityManager(  942): Killing 4967:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17
D/Process (  942): killProcessQuiet, pid=4967
,D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/PMS     (  942): releaseWL(2391c93e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 5604): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.backupreset.receiver.BackupResetReceiver.onReceive:45 android.app.ActivityThread.handleReceiver:2712 
,D/CustomizationManager( 5553):  Read ACC file spent 0.045 (s)
,D/CIDMapFileReader( 5553): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5553): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5553): Parsing tag item name = HTC__Y13
,D/CIDMapFileReader( 5553): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5553): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5553): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5553): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 5553): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 5553): Parsing tag category name = system
I/CustomizationCIDLoader( 5553): Parsing tag category name = application
I/CustomizationCIDLoader( 5553): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5553): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5553): Parsing tag category name = AudioService
,I/CustomizationCIDLoader( 5553): Parsing tag category name = Settings
I/CustomizationCIDLoader( 5553): Parsing tag category name = ACC
I/CustomizationCIDLoader( 5553): add string-array item, value = 42507
I/CustomizationCIDLoader( 5553): add string-array item, value = 21902
I/CustomizationCIDLoader( 5553): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 5553): add string-array item, value = 23420
I/CustomizationCIDLoader( 5553): add string-array item, value = 22299
I/CustomizationCIDLoader( 5553): add string-array item, value = 24002
I/CustomizationCIDLoader( 5553): add string-array item, value = 23210
I/CustomizationCIDLoader( 5553): add string-array item, value = 23205
I/CustomizationCIDLoader( 5553): add string-array item, value = 23806
I/CustomizationCIDLoader( 5553): add string-array item, value = 23430
I/CustomizationCIDLoader( 5553): add string-array item, value = 23408
I/CustomizationCIDLoader( 5553): add string-array item, value = 27205
I/CustomizationCIDLoader( 5553): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 5553): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 5553): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 5553): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 5553): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 5553): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 5553): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 5553): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 5553): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 5553): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 5553): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 5553): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 5553):  Read CID file spent 0.097 (s)
D/CustomizationManager( 5553):  All configurations done spent 0.097 (s)
,E/WifiTrafficPoller(  942): TRAFFIC_STATS_POLL false Token 15 num clients 9,
,I/ActivityManager(  942): Recipient 4967
,I/wpa_ctrl(  942): [wpa_ctrl_close] ctrl=0x55c3d87b90
,I/wpa_ctrl(  942): [wpa_ctrl_close] ctrl=0x55c3d88050
D/PackageManager(  942): deletePackageAsUser: pkg=com.example.hello, pid=5553, uid=2000 userid=0
,W/PackageSettings(  942): Skipping PackageSetting{ebaca18 com.test.thalitest/10366} due to missing metadata
,D/MediaProvider( 4007): [update][12]#1#
,I/ActivityManager(  942): Force stopping com.example.hello appid=10374 user=-1: uninstall pkg,
E/WifiStateMachine(  942): setWifiState: disabled
I/ActivityManager(  942): Killing 4835:com.example.hello/u0a374 (adj 0): stop com.example.hello
D/Process (  942): killProcessQuiet, pid=4835
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
,W/ResourcesManager( 5642): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/PhoneApp( 1424): EVENT_QUERY_MO_PACKAGES,
D/PhoneApp( 1424): -- N1 =0
,D/PhoneApp( 1424): -- N2 =0,
D/PhoneApp( 1424): -- N3 =0
,W/InputDispatcher(  942): channel '211fcd41 com.example.hello.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  942): channel '211fcd41 com.example.hello.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!,
I/WindowManager(  942): WINDOW DIED Window{211fcd41 u0 com.example.hello/com.example.hello.MainActivity}
W/InputDispatcher(  942): Attempted to unregister already unregistered input channel '211fcd41 com.example.hello.MainActivity (s)'
,D/WifiService(  942): Client connection lost with reason: 4
,E/InputEventReceiver( 1356): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{24d9c772 uid 10374 pid 4835} (c)'
I/ActivityManager(  942): Recipient 4835,
,E/WifiTrafficPoller(  942): TRAFFIC_STATS_POLL false Token 15 num clients 8
,W/ResourcesManager( 1479): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 5036): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,W/asset   ( 1479): Copying FileAsset 0x55c3f9c450 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,W/asset   ( 5036): Copying FileAsset 0x55c3cbda60 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,
,W/ActivityManager(  942): Force removing ActivityRecord{399376d9 u0 com.example.hello/.MainActivity t10}: app died, no saved state
,D/WifiStateMachine(  942): Enter handleNetworkDisconnect
,E/WifiStateMachine(  942): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - handleNetworkDisconnect - access$12300 - processMessage
,E/WifiStateMachine(  942): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
W/ActivityManager(  942): Spurious death for ProcessRecord{13d40633 4835:com.example.hello/u0a374}, curProc for 4835: null
E/WifiStateMachine(  942): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/ActivityManager(  942): Force stopping com.example.hello appid=10374 user=0: pkg removed
D/AdapterServiceConfig( 5642): Adding HeadsetService
D/AdapterServiceConfig( 5642): Adding A2dpService
,D/AdapterServiceConfig( 5642): Adding HidService
D/AdapterServiceConfig( 5642): Adding HealthService
D/AdapterServiceConfig( 5642): Adding PanService
D/AdapterServiceConfig( 5642): Adding GattService
,V/BluetoothPbapReceiver( 5642): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapReceiver( 5642): ***********state = 10
E/Prism.WidgetManager( 1479): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1479): onLoadItems() -
I/Prism.ItemManager( 1479): loadItems() com.htc.launcher.pageview.WidgetManager@1b9c392a -
,I/Prism.WidgetManager( 5036): onLoadItems() -
I/Prism.ItemManager( 5036): loadItems() com.htc.launcher.pageview.WidgetManager@8749b32 -
,I/Prism.ItemManager( 1479): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1479): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Settings( 4622): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/IntentController( 1222): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/WIFI_ICON( 1222): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/DotMatrix( 1301): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1301): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1301): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
E/BluetoothMasService( 5642): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
,W/Settings( 1866): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/PMS     (  942): acquireWL(13d34f69): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1866 10024 WorkSource{10024 com.google.android.gms}
W/GeofencerStateMachine( 1866): Ignoring removeGeofence because network location is disabled.
D/PMS     (  942): releaseWL(13d34f69): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/AccTypeManager( 1736): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,W/SystemReader(  942): Cannot find grip_rejection_width, use default value instead
D/BluetoothMasService( 5642): Add permission for SmsProvider.
,I/ActivityManager(  942): Killing 4994:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
,D/Process (  942): killProcessQuiet, pid=4994
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,D/AccTypeManager( 1736): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana,
,W/System.err(  942): java.lang.Throwable: stack dump,
D/BluetoothManagerService(  942): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  942): 	,at java.lang.Thread.dumpStack(Thread.java:490)
I/InputMethodManagerService(  942): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
W/System.err(  942): ,	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  942): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  942): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  942): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@222c82a1:true,
,V/BluetoothMasService( 5642): Starting MAS instances
D/BluetoothAdapter( 5642): 345339492: getState() :  mService = null. Returning STATE_OFF
,I/MailMessageReceiver( 5642): reg:com.android.bluetooth.btservice.AdapterApp@30e10cd with com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@21a9cd82
,D/AccTypeManager( 1736): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/Messaging( 5433): supportCMAS(SIE)/init? false/true
D/MmsConfig( 5433): networkCode: 
D/MmsConfig( 5433): SIE smsPri: null
D/MmsConfig( 5433): networkCode: 
,I/QuickSettingWifi( 1222): receive.wifiState:WIFI_STATE_DISABLED setEnable:true
W/ResourcesManager(  942): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,E/ExternalAccountType( 1736): Unsupported attribute readOnly
,D/ReportIndicatorCache( 5433): startAsyncQueryReports ---
,D/MmsAsyncWorkHandler( 5433): 
D/MmsAsyncWorkHandler( 5433): HM tk = 20001
,D/ReportIndicatorCache( 5433): MSG_QUERY_REPORTS >>
D/Messaging( 5433): mNeedToUpdateDate2 start
,D/DraftCache( 5433): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 5433): [DraftCache/1] refresh
,D/MmsConfig( 5433): networkCode: 
,I/Messaging( 5433): mccmnc> 
,D/Messaging( 5433): ViewCache CreatePreloadOnlyConversationList
,D/MessageCustFlag( 5433): sense_version=6.0,
,D/Jerry   ( 5433): start to preload cursor >>>>>>>
,W/PackageManager(  942): Unable to load service info ResolveInfo{3abbe581 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
W/PackageManager(  942): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  942): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  942): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  942): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  942): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  942): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  942): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  942): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  942): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  942): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  942): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  942): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  942): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  942): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/ActivityManager(  942): Recipient 4994
,I/art     (  942): Explicit concurrent mark sweep GC freed 26547(1830KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 16MB/25MB, paused 1.845ms total 186.024ms
,W/asset   (  942): Copying FileAsset 0x55c3e40bb0 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.,
D/JobSchedulerService(  942): Receieved: android.intent.action.PACKAGE_REMOVED
,I/FeedHostManager( 1479): [onResume]
I/FeedProviderManager( 1479): onResume
,I/SocialFeedProvider( 1479): +onResume
I/SocialFeedProvider( 1479): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1479): -onResume
I/ConnectivityHelper( 1479): [getCurrentConnectionType] no network connection
I/MailManager( 5642): MailManager contruct! com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@21a9cd82
V/EmailUtils( 5642): Manager Instance is not NULL
D/libc    ( 1797): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
D/libc    ( 1797): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1797): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1797): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1797): [NET] android_getaddrinfo_proxy+
D/libc    ( 1797): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1797): [NET] android_getaddrinfo_proxy-, NODATA
,W/PhenotypeConfigurator( 1797): IOException while sending for: 
D/TaskPersister(  942): removeObsoleteFile: deleting file=10_task.xml
,D/PMS     (  942): acquireWL(376c4f04): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 5515 1000 null
,W/ContextImpl( 5515): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
D/MediaProvider( 4007): [update][9]#1#
,D/WifiStateMachine(  942): Exit handleNetworkDisconnect
,E/WifiStateMachine(  942): [MLHD] Error! unhandled message 6 { when=-921ms what=147458 arg1=48 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  942): transitionTo: destState=InitialState
E/WifiStateMachine(  942): handleMessage: new destination call exit/enter
E/WifiStateMachine(  942): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  942): invokeExitMethods: SupplicantStoppingState
D/PMS     (  942): acquireWL(16368ae9): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 942 1000 null
E/WifiStateMachine(  942): moveTempStackToStateStack: i=0,j=1
E/WifiStateMachine(  942): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=InitialState
E/WifiStateMachine(  942): invokeEnterMethods: InitialState
,D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
,E/WifiTrafficPoller(  942): ENABLE_TRAFFIC_STATS_POLL false Token 15
,D/TelephUtils( 1424): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
,D/AccFlag ( 1424): sku_id=118
,D/PhoneApp( 1424): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,D/FlexNetS( 5195): updateSvcAllowedInSettings:false
I/ActivityManager(  942): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=5682 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a
D/DraftCache( 5433): [DraftCache/126] rebuildCache
,D/TelephUtils( 1424): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/MmsSmsV2Provider( 1424):  slotId = -1000
D/MmsSmsV2Provider( 1424): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/StatusBarManagerService(  942): setSystemUiVisibility(0x700),
D/StatusBarManagerService(  942): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/Batterystats( 2169): User is not opted-in to Usage & Diagnostics.
D/StatusBarManagerService(  942): hiding MENU key
D/PhoneStorageUtil( 5433): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 5433): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PMS     (  942): releaseWL(1fefabb): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PhoneStorageUtil( 5433): createReceiver
D/PMS     (  942): releaseWL(376c4f04): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
D/WISPrService( 5515): >>>>>WISPrService start isConnected = false<<<<<
D/FindExtension( 1479): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
D/WISPrService( 5515): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/PMS     (  942): acquireWL(3204a488): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1797 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  942): acquireWL(3f4bae21): PARTIAL_WAKE_LOCK  StartingDockService 0x1 5515 1000 null
,I/ThreadedRenderer( 1479): Defer allocateBuffers to drawing time
D/TelephUtils( 1424): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/MmsSmsV2Provider( 1424):  slotId = -1000
D/MmsSmsV2Provider( 1424): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
W/Prism.AllAppsManager( 1479): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:0
D/TelephUtils( 1424): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/MmsSmsV2Provider( 1424):  slotId = -1000
,I/ActivityManager(  942): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=5704 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,D/Messaging( 5433): ViewCache CreatePreload
D/PMS     (  942): releaseWL(3f4bae21): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
D/Messaging( 5433): ViewCache CreatePreloadOnlyMultipleOpsList
D/DockEventReceiver( 5515): finishStartingService: stopping service
,D/HtcBtWidget_BTWidgetProvider( 5561): onBTStateChanged() for widget: 
W/InputMethodManagerService(  942): Got RemoteException sending setActive(false) notification to pid 4835 uid 10374,
I/PhoneStatusBar( 1222): setImeWindowStatus(false,false)
D/StatusBarManagerService(  942): swetImeWindowStatus vis=0 backDisposition=0
D/TelephUtils( 1424): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
I/InputMethodManagerService(  942): Enable input method client, pid=1479
D/Jerry   ( 1424): URI_DRAFT
D/HtcBtWidget_BTWidgetProvider( 5561): updateWidget(context) for widget: 
,D/TelephUtils( 1424): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 92,
V/MmsProvider( 1424): Update uri=content://mms, match=0
V/MmsProvider( 1424): selection=st=129 AND m_type!=134
D/TelephUtils( 1424): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/MmsSmsV2Provider( 1424):  slotId = -1000
D/MmsSmsV2Provider( 1424): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
D/MdService( 5136): [784.] v648303190-6.1.860197 onStartCommand(dying) flag:0, id:2, failed(resend)
D/Messaging( 5433): Reset downloading state: 0
V/MmsSystemEventReceiver( 5433): TransactionService is going to be woken up.
,D/DraftCache( 5433): hasDraft() = false mNeedNotifyChange = true
,D/PMS     (  942): releaseWL(3204a488): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/DraftCache( 5433): [DraftCache/126] rebuildCache time: 3
D/PMS     (  942): acquireWL(229e82): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1797 10024 WorkSource{10024 com.google.android.gms}
D/MmsAsyncWorkHandler( 5433): 
D/MmsAsyncWorkHandler( 5433): HM tk = 20002
D/TelephUtils( 1424): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/MmsSmsV2Provider( 1424):  slotId = -1000
D/MmsSmsV2Provider( 1424): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/Messaging( 5433): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/Cust_MMSMS( 5433): _has_set_default_values_2=true
,D/Messaging( 5433): mNeedToUpdateDate2: false
,D/MsgPreferenceUtils( 5433): def_index: 0
,D/PMS     (  942): releaseWL(229e82): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
V/TransactionService( 5433): 1-Creating TransactionService
,D/TelephUtils( 1424): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
,D/AccFlag ( 1424): sku_id=118
,I/PhenotypeFlagCommitter( 1797): Experiment Configs successfully retrieved for com.google.android.gms.phenotype,
,D/MsgPreferenceUtils( 5433): globalIndex = 1
,V/TransactionService( 5433): onStartCommand: 1
D/MmsSystemEventReceiver( 5433): unRegisterForConnectionStateChanges
V/TransactionService( 5433): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 5433): Loading previous transactions.
D/MsgPreferenceUtils( 5433): phone state: true
,D/MsgPreferenceUtils( 5433): sd state: false
D/MsgPreferenceUtils( 5433): vIndex = 0
D/StatusBarManagerService(  942): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  942): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  942): hiding MENU key
,D/TelephUtils( 1424): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 66
D/AccFlag ( 1424): sku_id=118
D/MdScPhnSt( 5136): [833.1.]  listen tmrbb8
,D/TelephUtils( 1424): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/AccFlag ( 1424): device_type: 1,
,D/TransactionService( 5433): Force clearing mTransactionList
D/TransactionService( 5433): Force set service start id to 1
V/TransactionService( 5433): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 5433): unRegisterForConnectionStateChanges
,D/TransactionService( 5433): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 5433): Destroying TransactionService
,V/TransactionService( 5433): 4-Handling incoming message: { when=-1ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,W/ContextImpl( 5704): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  942): releaseWL(24637051): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  942): acquireWL(2de17bda): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1797 10024 WorkSource{10024 com.google.android.gms}
,D/PowerUsageList:PowerUsageHelper( 5704): MY_DEBUG = false
D/PMS     (  942): acquireWL(215a580b): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5704 1000 null
,I/ActivityManager(  942): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=5754 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a
,D/MdProvGlob( 5161): remove item 101 (p2d7in270) for 15:android.intent.action.ANY_DATA_STATE,
D/MdScDataSum( 5136): [833.1.] summary 118:p2 ignore
,D/PowerUsageService( 5704): repeat time = 1456843734962
,D/WeatherUtility( 1569): Weather sync is On
,D/WSP     ( 1569): [Receiver] auto sync agent, auto sync is enabled, reset schedule
,D/Process (  942): killProcessQuiet, pid=5085
I/ActivityManager(  942): Killing 5085:com.google.android.music:main/u0a159 (adj 15): empty #17
,D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,D/MediaProvider( 4007): [update][29]#1#,
,D/MediaScanner( 4007):  prescan time: 649ms
D/MediaScanner( 4007):     scan time: 1023ms
D/MediaScanner( 4007): postscan time: 4ms,
D/MediaScanner( 4007):    total time: 1676ms
D/MediaScanner( 4007): -----------------------------------------------------------------
D/MediaScanner( 4007): firstscan(media) time: 539ms
D/MediaScanner( 4007): secondscan(non-media) time: 484ms
D/MediaScanner( 4007):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 1
D/MediaScanner( 4007):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 4007):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 4007):  [Total]    File(Image+Video+Audio+Others) in database : 1549
D/PMS     (  942): releaseWL(2de17bda): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  942): acquireWL(1dcd06e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1797 10024 WorkSource{10024 com.google.android.gms}
,D/MediaProvider( 4007): [delete][15]
D/MediaProvider( 4007): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
,D/MediaProvider( 4007): [recoverParentNodes] - 0
,D/MediaProvider( 4007): [update][4]
D/MediaScannerServiceEx( 4007): [scan] Recover Parent Node is finished!
D/MediaScannerServiceEx( 4007): [updateImage]+
,D/MediaScannerServiceEx( 4007): [updateImage]-0
,D/Tethering(  942): interfaceRemoved wlan0
E/Tethering(  942): attempting to remove unknown iface (wlan0), ignoring
,I/ActivityManager(  942): Recipient 5085
,D/MediaRouterService(  942): Client com.google.android.music (pid 5085): Died!
,W/OpenGLRenderer( 1479): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...,
,E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
,D/Process (  942): killProcessQuiet, pid=5223
I/ActivityManager(  942): Killing 5223:com.google.android.setupwizard/u0a77 (adj 15): empty #17
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
D/PMS     (  942): releaseWL(1dcd06e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/PMS     (  942): acquireWL(295469e7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1797 10024 WorkSource{10024 com.google.android.gms}
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2079)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLite,Database( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2079)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2079)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOf,fTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
I/ActivityManager(  942): Recipient 5223
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2079)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2079)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2079)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
D/Tethering(  942): interfaceLinkStateChanged p2p0, false
D/Tethering(  942): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  942): WiFiDisplay: getWifidisplayApEnabled=false
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2079)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2079)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2079)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2079)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2079)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2079)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2079)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2079)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2079)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2079)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2079)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.la,ng.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDataba,se( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDataba,se( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWo,rker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.execute,Insert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsy,ncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
,E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
,E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
,E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
,E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
,E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
,E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): ,	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	,at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
,E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): ,	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
,E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
,E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
,E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	,at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
,E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
,E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	,at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
,E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
D/Tethering(  942): interfaceRemoved p2p0
E/Tethering(  942): attempting to remove unknown iface (p2p0), ignoring
,E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	,at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
,E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	,at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	,at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
,E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
,E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
,E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
,E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
,E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
,E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	,at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
,E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	,at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
,E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	,at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
,E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
,E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	,at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
,E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
,E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	,at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
,E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
,E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
,E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
,E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	,at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
,E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	,at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
,E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLit,eDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
,E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	,at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
,E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
,E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
,E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): ,	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 5704): (3850) statement aborts at 3: [DELETE FROM smartsync_golden_tue] disk I/O error
,E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
,D/SmartSyncProvider( 5704): An Disk IO error occured while accessing the SQLite database file.
,E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
,E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
,E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.ClearDataReWriteGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2310)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2251)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
I/PowerUsageList:PowerUsageHelper( 5704): PowerProfile::POWER_SCREEN_FULL = 154.8
D/PMS     (  942): releaseWL(3a35b0b6): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
,E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
D/MediaScannerServiceEx( 4007): [1] scan finished
D/MediaProviderUtils( 4007): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 4007): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 4007): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 4007): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1
W/MediaScannerServiceEx( 4007): Process mounted intent for unmounted storage: /storage/ext_sd
,E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.ClearDataReWriteGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2310)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2251)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
D/MediaScannerServiceEx( 4007): [disAliveExtStorageRows]+131073
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
D/HtcAdjCursorFactory( 5682): Set CursorWindow size to: 4194304 KB, Tid: 5730
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transpor,t.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.ClearDataReWriteGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2310)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2251)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 1797): Failed to open database '/data/data/com.google.android.gms/databases/ns.db'.
E/SQLiteDatabase( 1797): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1797): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1797): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 1797): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 1797): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1797): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1797): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1797): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 1797): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 1797): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 1797): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 1797): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1797): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1797): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1797): 	at com.google.android.gms.gcm.nts.n.b(SourceFile:252)
E/SQLiteDatabase( 1797): 	at com.google.android.gms.gcm.nts.k.a(SourceFile:54)
E/SQLiteDatabase( 1797): 	at com.google.android.gms.gcm.nts.l.handleMessage(SourceFile:175)
E/SQLiteDatabase( 1797): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1797): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 1797): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/SQLiteDatabase( 1797): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 1797): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 1797): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/SQLiteDatabase( 1797): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
D/PMS     (  942): releaseWL(295469e7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
D/WeatherUtility( 5754): Weather sync is On
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.ClearDataReWriteGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2310)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2251)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.ClearDataReWriteGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2310)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2251)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
,E/AndroidRuntime( 1797): FATAL EXCEPTION: main
E/AndroidRuntime( 1797): Process: com.google.process.gapps, PID: 1797
E/AndroidRuntime( 1797): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 1797): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 1797): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 1797): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 1797): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 1797): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 1797): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 1797): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 1797): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 1797): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 1797): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 1797): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 1797): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 1797): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 1797): 	at com.google.android.gms.gcm.nts.n.b(SourceFile:252)
E/AndroidRuntime( 1797): 	at com.google.android.gms.gcm.nts.k.a(SourceFile:54)
E/AndroidRuntime( 1797): 	at com.google.android.gms.gcm.nts.l.handleMessage(SourceFile:175)
E/AndroidRuntime( 1797): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1797): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 1797): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 1797): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1797): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1797): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 1797): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.ClearDataReWriteGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2310)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2251)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteData,base( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.ClearDataReWriteGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2310)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2251)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1693): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDBG( 1693): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.android.providers.contacts/databases/contacts2.db, handle: 0x55c3ac6700
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.ClearDataReWriteGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2310)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2251)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTas,k.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.ClearDataReWriteGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2310)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2251)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
W/ContactsProvider( 1693): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
W/ContactsProvider( 1693): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
W/ContactsProvider( 1693): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
W/ContactsProvider( 1693): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
W/ContactsProvider( 1693): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
W/ContactsProvider( 1693): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
W/ContactsProvider( 1693): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
W/ContactsProvider( 1693): 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:381)
W/ContactsProvider( 1693): 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:350)
W/ContactsProvider( 1693): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2230)
W/ContactsProvider( 1693): 	at com.android.providers.contacts.HtcContactsProvider2.performBackgroundTask(HtcContactsProvider2.java:11485)
W/ContactsProvider( 1693): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1887)
W/ContactsProvider( 1693): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ContactsProvider( 1693): 	at android.os.Looper.loop(Looper.java:155)
W/ContactsProvider( 1693): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.ClearDataReWriteGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2310)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2251)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5682): Failed to open database '/data/user/0/com.htc.android.mail/databases/mail.db'.
E/SQLiteDatabase( 5682): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5682): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5682): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5682): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5682): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5682): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5682): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5682): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5682): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5682): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5682): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 5682): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5682): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5682): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5682): 	at com.htc.android.mail.kq.a(MailProvider.java:5368)
E/SQLiteDatabase( 5682): 	at com.htc.android.mail.kq.a(MailProvider.java:5433)
E/SQLiteDatabase( 5682): 	at com.htc.android.mail.MailProvider.query(MailProvider.java:2114)
E/SQLiteDatabase( 5682): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 5682): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 5682): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
E/SQLiteDatabase( 5682): 	at android.os.Binder.execTransact(Binder.java:454)
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.ClearDataReWriteGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2310)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2251)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 5682): Couldn't open mail.db for writing (will try read-only):
E/SQLiteOpenHelper( 5682): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5682): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5682): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteOpenHelper( 5682): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteOpenHelper( 5682): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5682): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5682): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5682): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteOpenHelper( 5682): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteOpenHelper( 5682): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteOpenHelper( 5682): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteOpenHelper( 5682): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 5682): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5682): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5682): 	at com.htc.android.mail.kq.a(MailProvider.java:5368)
E/SQLiteOpenHelper( 5682): 	at com.htc.android.mail.kq.a(MailProvider.java:5433)
E/SQLiteOpenHelper( 5682): 	at com.htc.android.mail.MailProvider.query(MailProvider.java:2114)
E/SQLiteOpenHelper( 5682): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteOpenHelper( 5682): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteOpenHelper( 5682): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
E/SQLiteOpenHelper( 5682): 	at android.os.Binder.execTransact(Binder.java:454)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.ClearDataReWriteGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2310)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2251)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
W/SQLiteOpenHelper( 5682): Opened mail.db in read-only mode
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
I/ActivityManager(  942): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5780 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.ClearDataReWriteGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2310)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2251)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/ActivityManager(  942): App crashed! Process: com.google.process.gapps
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.ClearDataReWriteGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2310)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2251)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.ClearDataReWriteGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2310)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2251)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.ClearDataReWriteGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2310)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2251)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.ClearDataReWriteGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2310)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2251)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.sm,artsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.ClearDataReWriteGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2310)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2251)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.ClearDataReWriteGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2310)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2251)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.ClearDataReWriteGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2310)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2251)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.ClearDataReWriteGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2310)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2251)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.ClearDataReWriteGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2310)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2251)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.ClearDataReWriteGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2310)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2251)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5704): (3850) statement aborts at 19: [INSERT INTO smartsync_golden_tue(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5704): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x55c3aac180
D/PowerUsageList:BatterySipperExt( 5704): gen(), null == sipper.uidObj, userId = 0
E/SQLiteDatabase( 5704): Error inserting ...
E/SQLiteDatabase( 5704): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5704): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5704): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5704): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.ClearDataReWriteGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2310)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2251)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5704): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5704): 	at java.lang.Thread.run(Thread.java:818)
D/PowerUsageList:BatterySipperExt( 5704): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageList:BatterySipperExt( 5704): gen(), null == sipper.uidObj, userId = 0
D/PMS     (  942): releaseWL(215a580b): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/PowerUsageList:BatterySipperExt( 5704): gen(), null == sipper.uidObj, userId = 0
E/SQLiteLog(  942): (3850) statement aborts at 36: [INSERT INTO secure(name,value) VALUES (?,?)] disk I/O error
E/DropBoxManagerService(  942): Can't write: system_app_crash
E/DropBoxManagerService(  942): java.io.FileNotFoundException: /data/system/dropbox/drop133.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  942): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  942): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  942): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  942): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  942): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  942): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  942): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  942): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  942): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  942): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  942): 	... 5 more
E/SQLiteDBG(  942): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.android.providers.settings/databases/settings.db, handle: 0x55c3ba2330
E/SQLiteDatabase(  942): Error inserting ...
E/SQLiteDatabase(  942): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase(  942): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase(  942): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase(  942): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase(  942): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase(  942): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase(  942): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase(  942): 	at com.android.providers.settings.SettingsProvider.insertForUser(SettingsProvider.java:1526)
E/SQLiteDatabase(  942): 	at com.android.providers.settings.SettingsProvider.call(SettingsProvider.java:845)
E/SQLiteDatabase(  942): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:377)
E/SQLiteDatabase(  942): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:318)
E/SQLiteDatabase(  942): 	at android.os.Binder.execTransact(Binder.java:454)
D/PowerUsageService( 5704): calcPower(), no data
D/StatusBarManagerService(  942): setSystemUiVisibility(0xc0000000)
D/StatusBarManagerService(  942): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  942): hiding MENU key
D/EmailUtils( 5642): ============NULL aList========
V/EmailUtils( 5642): <-getEmailAccountIdList
V/BluetoothMasService( 5642): onCreate: mIsEmailEnabled: true
I/ActivityManager(  942): Killing 5245:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  942): killProcessQuiet, pid=5245
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
W/WeatherRequest( 5754): request cur loc, but there is no sys cur
W/Settings( 5754): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActionCombine( 5754): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,I/ActivityManager(  942): Recipient 5245
,I/ActivityManager(  942): Killing 5277:com.google.android.apps.magazines/u0a161 (adj 15): empty #17
D/Process (  942): killProcessQuiet, pid=5277
,D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/Prism.ItemManager( 5036): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
I/Prism.ItemManager( 5036): loadItems() com.htc.launcher.pageview.WidgetManager@8749b32 +
I/Prism.WidgetManager( 5036): onLoadItems() +
,I/Prism.ItemManager( 1479): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1479): loadItems() com.htc.launcher.pageview.WidgetManager@1b9c392a +
,I/Prism.WidgetManager( 1479): onLoadItems() +
,I/ActivityManager(  942): Recipient 5277,
,D/BluetoothMasReceiver( 5642): Bluetooth STATE CHANGED to 10
,V/AlarmManager(  942): sending alarm PendingIntent{37f3f430: PendingIntentRecord{3465c8a9 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1456842836017, Int=0,
V/BluetoothMasService( 5642): onDestroy: mIsEmailEnabled: true
,V/BluetoothSapReceiver( 5642): SapReceiver onReceive 
,V/BluetoothSapReceiver( 5642): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 5642):  Bluetooth Adapter state = 10
V/BluetoothSapReceiver( 5642): startService = false
,I/ActivityManager(  942): Killing 5376:com.android.chrome/u0a96 (adj 15): empty #17,
,D/Process (  942): killProcessQuiet, pid=5376
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
I/RemoteViews( 1479): reapply : com.htc.widget.weatherclock 12 17
,I/ActivityManager(  942): Recipient 5376
,W/ResourcesManager( 5036): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  942): Killing 5036:com.htc.sense.news/u0a74 (adj 15): empty #17
D/Process (  942): killProcessQuiet, pid=5036
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/Prism.WidgetManager( 1479): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1479): onLoadItems() -
I/Prism.ItemManager( 1479): loadItems() com.htc.launcher.pageview.WidgetManager@1b9c392a -
,I/Prism.ItemManager( 1479): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1479): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/ActivityManager(  942): Recipient 5036,

```
