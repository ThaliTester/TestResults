#### Test 503880196dc97cd_thali06_HTC-HTC One M8s Logs


```
--------- beginning of system
D/VoldConnector(  942): SND -> {12 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/}
E/Vold    (  386): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
--------- beginning of main
W/ContextImpl( 4611): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
E/WifiTrafficPoller(  942): TRAFFIC_STATS_POLL true Token 11 num clients 5
E/WifiTrafficPoller(  942):  packet count Tx=43 Rx=76
D/VoldConnector(  942): SND -> {13 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/}
E/Vold    (  386): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
W/ContextImpl( 4611): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
D/VoldConnector(  942): SND -> {14 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/files/}
E/Vold    (  386): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/
W/ContextImpl( 4611): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files
D/VoldConnector(  942): SND -> {15 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/files/}
E/Vold    (  386): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/
W/ContextImpl( 4611): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files
W/InstanceID/Rpc( 4611): Found 10024
D/VoldConnector(  942): SND -> {16 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/}
E/Vold    (  386): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
W/ContextImpl( 4611): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
D/libc    ( 4611): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
I/ActivityManager(  942): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4696 uid=10106 gids={50106, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/libc    ( 4611): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4611): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    ( 4611): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4611): [NET] android_getaddrinfo_proxy+
D/libc    ( 4611): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/Process (  942): killProcessQuiet, pid=4107
I/ActivityManager(  942): Killing 4107:com.htc.updater/u0a84 (adj 15): empty #17
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/libc    (  396): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4611): [NET] android_getaddrinfo_proxy-, success
D/libc    ( 4611): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 4611): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4611): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
D/libc    ( 4611): [NET] android_getaddrinfofornet-, err=8
I/ActivityManager(  942): Recipient 4107
,W/ActivityManager(  942): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 4696): getAccountsCursor
V/GLSActivity( 1813): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 4696): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.AttachmentService, state=2, flag=1, pid=4696, uid=10106, userID:0
W/ActivityManager(  942): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/Gmail   ( 4696): Observing account changes for notifications
W/ActivityManager(  942): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=4696, uid=10106, userID:0
I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=4696, uid=10106, userID:0
W/ActivityManager(  942): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/Gmail   ( 4696): Error finding the version of the Email provider.....
E/Gmail   ( 4696): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 4696): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 4696): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 4696): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 4696): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4696): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4696): 	at android.os.Looper.loop(Looper.java:155)
E/Gmail   ( 4696): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 4696): We do not support migrating this version of the Email provider.
I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GoogleMailWidgetProvider, state=2, flag=1, pid=4696, uid=10106, userID:0
I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GmailWidgetProvider, state=1, flag=1, pid=4696, uid=10106, userID:0
I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGoogleMail, state=2, flag=1, pid=4696, uid=10106, userID:0
I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGmail, state=1, flag=1, pid=4696, uid=10106, userID:0
I/Gmail   ( 4696): getAccountsCursor
V/GLSActivity( 1813): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  942): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=4740 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
W/ActivityManager(  942): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=4696, uid=10106, userID:0
I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=4696, uid=10106, userID:0
W/ActivityManager(  942): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
V/GLSActivity( 1813): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/WifiTrafficPoller(  942): TRAFFIC_STATS_POLL true Token 11 num clients 5
E/WifiTrafficPoller(  942):  packet count Tx=54 Rx=87
E/WifiTrafficPoller(  942): notifying of data activity 3
E/cutils-trace( 4721): Error opening trace file: Permission denied (13)
D/WIFI_ICON( 1216): WifiActivity: 3
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/ActivityThread( 4696): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@a1b0ada that was originally bound here
E/ActivityThread( 4696): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@a1b0ada that was originally bound here
E/ActivityThread( 4696): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1183)
E/ActivityThread( 4696): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1077)
E/ActivityThread( 4696): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1906)
E/ActivityThread( 4696): 	at android.app.ContextImpl.bindService(ContextImpl.java:1889)
E/ActivityThread( 4696): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4696): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4696): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4696): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4696): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4696): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4696): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4696): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4696): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4696): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4696): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread( 4696): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager(  942): Unbind failed: could not find connection for android.os.BinderProxy@3645a453
E/SQLiteLog( 4696): (283) recovered 479 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
E/WifiStateMachine(  942): handleMessage: E msg.what=131155
E/WifiStateMachine(  942): processMsg: ConnectedState
E/WifiStateMachine(  942):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=5.7 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1056727918] gl hn u24 rssi=-50 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  942): processMsg: L2ConnectedState
E/WifiStateMachine(  942):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=5.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1056727922] gl hn u24 rssi=-50 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  942):  get link layer stats 0
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1326): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1326): environment dirty rate=9 [11][1][0]
E/WifiStateMachine(  942): fetchRssiLinkSpeedAndFrequencyNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  942): fetchRssiLinkSpeedAndFrequencyNative rssi=-55 linkspeed=72
E/WifiConfigStore(  942): updateConfiguration freq=2462 BSSID=c0:ff:d4:d3:aa:48 RSSI=-55 "NG700"WPA_PSK
E/WifiStateMachine(  942): calculateWifiScore freq=2462 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=5.69 txretriesrate=0.00 rxrate=9.35 userTriggerdPenalty0
E/WifiStateMachine(  942):  good link -> stuck count =0
E/WifiStateMachine(  942):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  942):  isHighRSSI       ---> score=65
D/CustomizationManager( 4721): ====startRecUseTime====
D/htc.customization.log.level( 4721):  is 
W/CustomizationLogLevel( 4721): Level value is invalid, use default level 2
D/WifiWatchdogStateMachine(  942): RSSI current: 3 new: -55, 3
E/WifiStateMachine(  942): handleMessage: X
D/WIFI_ICON( 1216): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/CustomizationManager( 4721):  Read ACC file spent 0.036 (s)
D/CIDMapFileReader( 4721): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4721): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4721): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4721): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4721): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4721): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4721): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4721): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 4721): Parsing tag category name = system
I/CustomizationCIDLoader( 4721): Parsing tag category name = application
I/CustomizationCIDLoader( 4721): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4721): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4721): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4721): Parsing tag category name = Settings
I/CustomizationCIDLoader( 4721): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4721): add string-array item, value = 42507
I/CustomizationCIDLoader( 4721): add string-array item, value = 21902
I/CustomizationCIDLoader( 4721): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 4721): add string-array item, value = 23420
I/CustomizationCIDLoader( 4721): add string-array item, value = 22299
I/CustomizationCIDLoader( 4721): add string-array item, value = 24002
I/CustomizationCIDLoader( 4721): add string-array item, value = 23210
I/CustomizationCIDLoader( 4721): add string-array item, value = 23205
I/CustomizationCIDLoader( 4721): add string-array item, value = 23806
I/CustomizationCIDLoader( 4721): add string-array item, value = 23430
I/CustomizationCIDLoader( 4721): add string-array item, value = 23408
I/CustomizationCIDLoader( 4721): add string-array item, value = 27205
I/CustomizationCIDLoader( 4721): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 4721): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 4721): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 4721): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 4721): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 4721): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 4721): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 4721): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 4721): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 4721): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 4721): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 4721): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 4721):  Read CID file spent 0.078 (s)
D/CustomizationManager( 4721):  All configurations done spent 0.078 (s)
I/ActivityManager(  942): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 pid 4721 on display 0
D/PMS     (  942): acquireHCC(3eea7190): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 942 1000 null
D/PMS     (  942): acquireHCC(1dcc6a89): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 942 1000 null
W/asset   (  942): Copying FileAsset 0x5598b9aba0 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/PMS     (  942): acquireWL(1bad16bc): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 942 1000 null
I/FeedHostManager( 1586): [onPause]
I/FeedProviderManager( 1586): onPause
I/FeedHostManager( 1586): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@fc378d8
I/SocialFeedProvider( 1586): +onPause
I/SocialFeedProvider( 1586): -onPause
W/HtcSystemUPManager(  942): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/AnimationUtil(  942): isHTCRecent(HelloWorld/Recent screens.)/6
I/ActivityManager(  942): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4780 uid=10373 gids={50373, 9997, 3003, 3001, 3002} abi=armeabi-v7a
W/asset   ( 4780): Copying FileAsset 0xac9af048 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/StatusBarManagerService(  942): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  942): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  942): hiding MENU key
V/AlarmManager(  942): sending alarm PendingIntent{3f64a9f2: PendingIntentRecord{cd04843 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.hangouts.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=55250, Int=259200000
I/Gmail   ( 4696): notifyAccountChanged
V/AlarmManager(  942): sending alarm PendingIntent{212807f9: PendingIntentRecord{340f733e com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1448460706929, Int=0
V/AlarmManager(  942): sending alarm PendingIntent{3fa5259f: PendingIntentRecord{22c1a6ec com.htc.launcher broadcastIntent}}, i=com.htc.launcher.action.BI_LOG_ALARM, t=1, cnt=1, w=1448449200000, Int=86400000
V/AlarmManager(  942): sending alarm PendingIntent{2cb2e1fb: PendingIntentRecord{c26e218 android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1448460698664, Int=20000
I/Gmail   ( 4696): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 4696): getAccountsCursor
I/TrimMemoryManager( 1586): [trimMemory] 20
V/GLSActivity( 1813): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 4696): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 4696): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 4696): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/WebViewFactory( 4780): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
E/AndroidHttpClient( 4414): Leak found
E/AndroidHttpClient( 4414): java.lang.IllegalStateException: AndroidHttpClient created and never closed
E/AndroidHttpClient( 4414): 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 4414): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 4414): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 4414): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 4414): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 4414): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 4414): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 4414): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 4414): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 4414): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 4414): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 4414): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 4414): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 4414): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 4414): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 4414): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
I/LibraryLoader( 4780): Time to load native libraries: 10 ms (timestamps 7718-7728)
I/LibraryLoader( 4780): Expected native library version number "",actual native library version number ""
I/art     (  942): Explicit concurrent mark sweep GC freed 16287(884KB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 16MB/24MB, paused 1.892ms total 163.835ms
D/PMS     (  942): acquireWL(2637e784): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 4696 10106 null
I/Gmail   ( 4696): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
D/PMS     (  942): acquireWL(2637e784): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 4696 10106 null
I/Gmail   ( 4696): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
D/PMS     (  942): acquireWL(2637e784): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 4696 10106 null
D/LocationManagerService(  942): getProviders()=[passive]
I/Gmail   ( 4696): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.ComposeActivityGmail, state=1, flag=1, pid=4696, uid=10106, userID:0
V/WebViewChromiumFactoryProvider( 4780): Binding Chromium to main looper Looper (main, tid 1) {3b0b97ed}
I/LibraryLoader( 4780): Expected native library version number "",actual native library version number ""
I/chromium( 4780): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
D/Process (  942): killProcessQuiet, pid=4132
I/ActivityManager(  942): Killing 4132:com.htc.android.worldclock/u0a90 (adj 15): empty #17
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/BrowserStartupController( 4780): Initializing chromium process, singleProcess=true
W/art     ( 4780): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4780): ApplicationContext is null in ApplicationStatus
I/ActivityManager(  942): Recipient 4132
I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.googlequicksearchbox.SearchActivity, state=1, flag=1, pid=4740, uid=10085, userID:0
I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.googlequicksearchbox.VoiceSearchActivity, state=1, flag=1, pid=4740, uid=10085, userID:0
I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.search.core.icingsync.ApplicationLaunchReceiver, state=1, flag=1, pid=4740, uid=10085, userID:0
W/chromium( 4780): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 4780): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4780): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 4780): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 4780): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 4780): Build Date: 03/09/15 Mon
I/Adreno-EGL( 4780): Local Branch: 
I/Adreno-EGL( 4780): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 4780): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 4780):                  d74aa161a12b9c6fc6332151
I/ActivityManager(  942): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4827 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a
I/iu.UploadsManager( 4477): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
D/WifiService(  942): New client listening to asynchronous messages
E/WifiTrafficPoller(  942): ADD_CLIENT: 6
W/BroadcastQueue(  942): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to pl.k2.droidoaudioteka/.ford.AppLinkReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
W/System.err(  942): java.lang.Throwable: stack dump
D/BluetoothManagerService(  942): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  942): 	at java.lang.Thread.dumpStack(Thread.java:490)
D/BluetoothManagerService(  942): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2a473d20:true
W/System.err(  942): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  942): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  942): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothAdapter( 4780): 672581097: getState(). Returning 12
I/ActivityManager(  942): Start proc com.htc.club for broadcast com.htc.club/com.mcrm.autonotification.Autostart: pid=4864 uid=10181 gids={50181, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/Process (  942): killProcessQuiet, pid=3133
I/ActivityManager(  942): Killing 3133:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  942): Recipient 3133
E/WifiTrafficPoller(  942): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  942):  packet count Tx=54 Rx=87
D/WIFI_ICON( 1216): WifiActivity: 0
E/WifiTrafficPoller(  942): notifying of data activity 0
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/Process (  942): killProcessQuiet, pid=4179
I/ActivityManager(  942): Killing 4179:com.google.android.configupdater/u0a98 (adj 15): empty #18
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  942): Recipient 4179
I/Gmail   ( 4696): master sync=false, engine sync=true
D/GCM     ( 1813): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 1813): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 4477): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
D/libc    ( 4864): [NET] android_getaddrinfofornet+,hn 48(0x6874632d636c75),sn(),hints(known),family 0,flags 4
D/libc    ( 4864): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4864): [NET] android_getaddrinfofornet+,hn 48(0x6874632d636c75),sn(),hints(known),family 0,flags 1024
D/libc    ( 4864): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4864): [NET] android_getaddrinfo_proxy+
D/libc    ( 4864): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 48(0x6874632d636c75),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:100, mark:917604
I/iu.UploadsManager( 4477): End new media; added: 0, uploading: 0, time: 539 ms
W/art     ( 4780): Attempt to remove local handle scope entry from IRT, ignoring
I/ActivityManager(  942): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=4898 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
W/AwContents( 4780): onDetachedFromWindow called when already detached. Ignoring
I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4477, uid=10024, userID:0
D/SystemWebViewEngine( 4780): CordovaWebView is running on device made by: HTC
I/Gmail   ( 4696): getAccountsCursor
D/libc    (  396): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4864): [NET] android_getaddrinfo_proxy-, success
D/libc    ( 4864): [NET] android_getaddrinfofornet+,hn 14(0x35342e3233312e),sn(),hints(known),family 0,flags 4
D/libc    ( 4864): [NET] android_getaddrinfofornet-, SUCCESS
V/GLSActivity( 1813): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/art     ( 4780): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4780): Attempt to remove local handle scope entry from IRT, ignoring
I/Gmail   ( 4696): master sync=false, engine sync=true
D/TelephUtils( 1543): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 50
D/AccFlag ( 1543): sku_id=118
W/ResourcesManager( 4898): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4898): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  942): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=4930 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
I/MultiDex( 4898): VM with version 2.1.0 has multidex support
I/MultiDex( 4898): install
I/MultiDex( 4898): VM has multidex support, MultiDex support library is disabled.
D/LocationInitializer( 4477): Restart initialization of location
D/TelephUtils( 1543): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 49
D/AccFlag ( 1543): sku_id=118
D/libc    ( 4864): [NET] android_getaddrinfofornet+,hn 3,sn(),hints(known),family 0,flags 4
D/libc    ( 4864): [NET] android_getaddrinfofornet-, err=8
V/JNIHelp ( 4898): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
W/chromium( 4780): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/TelephUtils( 1543): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 50,
D/AccFlag ( 1543): sku_id=118
,D/TelephUtils( 1543): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 49
D/AccFlag ( 1543): sku_id=118
I/art     ( 1813): Explicit concurrent mark sweep GC freed 12786(736KB) AllocSpace objects, 3(252KB) LOS objects, 49% free, 4MB/8MB, paused 1.006ms total 57.832ms,
,D/FindExtension( 4780): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,W/ActivityThread( 4898): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,W/System  ( 4898): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3af8e2c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4898): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 4898): callingUid 10024, callindPid: 4898,
,E/MDM     ( 1892): [152] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,I/GLSUser ( 1813): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow,
I/GLSUser ( 1813): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1813): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1813): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1813): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1327): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1327): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/InputMethodManager( 4780): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@3f99531e, mServedView=org.apache.cordova.engine.SystemWebView{32cfb7ff VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@3abb39cc
W/Search.LoginHelper( 4740): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 4740): com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
W/Search.LoginHelper( 4740): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 4740): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4740): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4740): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 4740): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 4740): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 4740): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 4740): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 4740): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 4740): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4740): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 4740): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4740): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 4740): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 4740): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 4740): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
,E/VelvetNetworkClient( 4740): Failed to get auth token,
I/RemoteViews( 1216): reapply : com.google.android.gms 2 40
,I/InputMethodManagerService(  942): Disable input method client, pid=1586
D/StatusBarManagerService(  942): swetImeWindowStatus vis=0 backDisposition=0,
,I/ActivityManager(  942): Displayed com.example.hello/.MainActivity: +1s382ms
,I/InputMethodManagerService(  942): Enable input method client, pid=4780
I/PhoneStatusBar( 1216): setImeWindowStatus(false,false)
,D/PMS     (  942): releaseWL(1bad16bc): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null,
,D/libc    ( 4864): [NET] android_getaddrinfofornet+,hn 28(0x6874632d636c75),sn(),hints(known),family 0,flags 4,
D/libc    ( 4864): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4864): [NET] android_getaddrinfofornet+,hn 28(0x6874632d636c75),sn(),hints(known),family 0,flags 1024,
D/libc    ( 4864): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4864): [NET] android_getaddrinfo_proxy+
D/libc    ( 4864): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 28(0x6874632d636c75),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,W/XT9_C   ( 1397): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1397): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1397): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1397): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0,
,D/ContactMessageStore( 1543): MSG_NOTIFY_CS_TO_SYNC >>,
,D/ContactMessageStore( 1543): MSG_NOTIFY_CS_TO_SYNC <<,
,W/BindingManager( 4780): Cannot call determinedVisibility() - never saw a connection for the pid: 4780
,I/MusicStore( 4930): Database version: 120,
,I/chromium( 4780): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/libc    (  396): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4864): [NET] android_getaddrinfo_proxy-, success
D/libc    ( 4864): [NET] android_getaddrinfofornet+,hn 13(0x3130342e38312e),sn(),hints(known),family 0,flags 4
D/libc    ( 4864): [NET] android_getaddrinfofornet-, SUCCESS
,D/JsMessageQueue( 4780): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 4780): Unable to open asset URL: file:///android_asset/www/jxcore.js
,W/Atfwd_Sendcmd(  434): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/WifiDataStallTracker(  942): DATA_MONITOR_POLL true Token 1,
D/WifiDataStallTracker(  942): updateDataStallInfo: mDataStallTxRxSum={txSum=67 rxSum=68} preTxRxSum={txSum=32 rxSum=22}
D/WifiDataStallTracker(  942): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  942): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,D/VoldConnector(  942): SND -> {17 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  386): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 4930): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  942): SND -> {18 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  386): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 4930): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  942): SND -> {19 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
,E/Vold    (  386): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 4930): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/jxcore_app_log( 4780): JniHelper::setJavaVM(0xab8418f8), pthread_self() = -1397384704
,D/JX-Cordova( 4780): jxcore cordova android initializing
W/ResourcesManager( 4930): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4930): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4930): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,E/WifiTrafficPoller(  942): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/WIFI_ICON( 1216): WifiActivity: 3
E/WifiTrafficPoller(  942):  packet count Tx=84 Rx=129
E/WifiTrafficPoller(  942): notifying of data activity 3
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,W/jxcore-log( 4780): Initializing JXcore engine,
W/jxcore-log( 4780): JXcore engine is ready
,W/jxcore-log( 4780): Starting JXcore engine,
,W/ActivityThread( 4930): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 4930): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@32483ab6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4930): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 4930): GMSCore installation verified
,I/ConfigStore( 4930): Config Database version: 1,
,I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4930, uid=10159, userID:0
,D/WifiDisplayAdapter(  942): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  942):     Client/Owner: Client
D/WifiDisplayAdapter(  942):     GroupId: 
D/WifiDisplayAdapter(  942):     Passphrase: 
D/WifiDisplayAdapter(  942):     SessionId: 0
D/WifiDisplayAdapter(  942):     IP Address: }
,W/jxcore-log( 4780): Platform android
W/jxcore-log( 4780): 
,W/jxcore-log( 4780): Process ARCH arm
W/jxcore-log( 4780): 
,D/PMS     (  942): releaseHCC(3eea7190): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     (  942): releaseHCC(1dcc6a89): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,I/jxcore-log( 4780): JXcore Cordova bridge is ready!,
I/jxcore-log( 4780): 
W/jxcore-log( 4780): JXcore engine is started
,E/jxcore-log( 4780): >> HTC-HTC One M8s,
E/jxcore-log( 4780): 
,I/jxcore-log( 4780): Total memory 1931808768
I/jxcore-log( 4780): 
,I/jxcore-log( 4780): Free memory 84238336
I/jxcore-log( 4780): 
I/jxcore-log( 4780): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4780): 
I/jxcore-log( 4780): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4780): 
,I/jxcore-log( 4780): userPath [ 'www' ],
I/jxcore-log( 4780): 
,I/jxcore-log( 4780): Size 1080 1776,
I/jxcore-log( 4780): 
,I/jxcore-log( 4780): Screen Brightness 142,
I/jxcore-log( 4780): 
E/jxcore-log( 4780): Dummy Error Log.
E/jxcore-log( 4780): 
,I/art     (  942): Explicit concurrent mark sweep GC freed 10417(493KB) AllocSpace objects, 1(84KB) LOS objects, 33% free, 16MB/24MB, paused 1.354ms total 132.902ms
,D/MediaRouterService(  942): Client com.google.android.music (pid 4930): Registered
,D/WifiDisplayAdapter(  942): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  942):     Client/Owner: Client
D/WifiDisplayAdapter(  942):     GroupId: 
D/WifiDisplayAdapter(  942):     Passphrase: 
D/WifiDisplayAdapter(  942):     SessionId: 0
D/WifiDisplayAdapter(  942):     IP Address: }
,I/MediaRouter( 4930): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android },
,V/MusicLeanback( 4930): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) },
,I/NetworkMonitor( 4930): type=WIFI subType= reason=null isConnected=true,
,I/NetworkMonitor( 4930): type=WIFI subType= reason=null isConnected=true
,I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=4930, uid=10159, userID:0
I/ActivityManager(  942): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=4976 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,I/GHttpClientFactory( 4930): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/art     (  411): Explicit concurrent mark sweep GC freed 8670(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 234us total 33.640ms
,I/GoogleURLConnFactory( 4930): Using platform SSLCertificateSocketFactory
,W/ResourcesManager( 4976): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/art     (  411): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 256us total 24.296ms,
,I/art     (  411): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 190us total 21.542ms
,I/ActivityManager(  942): Killing 4225:com.htc.backupreset/1000 (adj 15): empty #17
D/Process (  942): killProcessQuiet, pid=4225
,D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/PMS     (  942): releaseWL(2637e784): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 null,
,I/ActivityManager(  942): Recipient 4225
,I/CalendarProvider2( 4976): Created com.android.providers.calendar.CalendarAlarmManager@1a881622(com.htc.providers.calendar.HtcCalendarProvider@2fbf8b3),
,D/CalendarProvider2( 4976): wait start:true
,D/CalendarProvider2( 4976): wait end:false,
D/AutoSetting( 1646): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/jxcore-log( 4780): getBuffer is called!!!!
I/jxcore-log( 4780): 
,I/ActivityManager(  942): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=5004 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a
,D/AutoSetting( 1646): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1646): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1646): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1646): service - onStartCommand() REMOVE current location bundle
D/AutoSetting( 1646): service - handleMessage() setting current location null
,D/PhoneMonitor( 5004): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 5004): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) },
,D/MobileConnectivityChangeReceiver( 5004): onReceive CONNECTIVITY_CHANGE networkType=1
,D/Process (  942): killProcessQuiet, pid=4254
I/ActivityManager(  942): Killing 4254:com.htc.htccupd/u0a13 (adj 15): empty #17
,D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,D/PhoneMonitor( 5004): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false,
,D/PhoneMonitor( 5004): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,E/WifiTrafficPoller(  942): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/WIFI_ICON( 1216): WifiActivity: 0
E/WifiTrafficPoller(  942):  packet count Tx=84 Rx=129,
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  942): notifying of data activity 0
,I/ActivityManager(  942): Recipient 4254
,E/WifiStateMachine(  942): handleMessage: E msg.what=131155,
E/WifiStateMachine(  942): processMsg: ConnectedState
E/WifiStateMachine(  942):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=5.7, 0.0, 0.0  rx=9.4 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1056730946] gl hn u24 rssi=-50 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine(  942): processMsg: L2ConnectedState
,E/WifiStateMachine(  942):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=5.7, 0.0, 0.0  rx=9.4 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1056730947] gl hn u24 rssi=-50 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  942):  get link layer stats 0
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
D/wpa_supplicant( 1326): wlan0: Control interface command 'SIGNAL_POLL',
,I/wpa_supplicant( 1326): environment dirty rate=0 [30][0][0]
E/WifiStateMachine(  942): fetchRssiLinkSpeedAndFrequencyNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72,
E/WifiStateMachine(  942): fetchRssiLinkSpeedAndFrequencyNative rssi=-55 linkspeed=72
E/WifiConfigStore(  942): updateConfiguration freq=2462 BSSID=c0:ff:d4:d3:aa:48 RSSI=-55 "NG700"WPA_PSK
E/WifiStateMachine(  942): calculateWifiScore freq=2462 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=17.84 txretriesrate=0.00 rxrate=25.68 userTriggerdPenalty0
E/WifiStateMachine(  942):  good link -> stuck count =0
E/WifiStateMachine(  942):  badRSSI count0 lowRSSI count0 --> score 60,
E/WifiStateMachine(  942):  isHighRSSI       ---> score=65
,E/WifiStateMachine(  942): handleMessage: X,
,I/ActivityManager(  942): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=5029 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a,
V/AlarmManager(  942): sending alarm PendingIntent{19727d6e: PendingIntentRecord{290b1c0f com.htc.mobiledata startService}}, i=com.htc.mobiledata.intent.REQUEST, t=2, cnt=1, w=60337, Int=0,
,D/WifiWatchdogStateMachine(  942): RSSI current: 3 new: -55, 3
D/WIFI_ICON( 1216): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  942): acquireWL(1ee1b49c): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4477 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  942): acquireWL(7cd027a): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4477 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  942): releaseWL(1ee1b49c): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
,D/Process (  942): killProcessQuiet, pid=4299,
I/ActivityManager(  942): Killing 4299:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  942): Recipient 4299,
,I/CheckinService( 4477): Checking schedule, now: 1448460709939 next: 1448460047976,
I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=4477, uid=10024, userID:0
I/CheckinService( 4477): active receiver: enabled
,I/CheckinService( 4477): Preparing to send checkin request
I/EventLogService( 4477): Accumulating logs since 1448460015560
,I/HtcModeClient( 3240): handler message = 4011
,E/HtcModeClient( 3240): Check connection and retry 4 times.
,I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4477, uid=10024, userID:0
,I/iu.SyncManager( 4477): SYNC; picasa accounts,
,D/NetworkLogImpl( 4477): Loaded NetworkSpeedPredictor,
I/iu.Environment( 4477): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/ActivityManager(  942): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=5055 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a,
,I/iu.UploadsManager( 4477): num queued entries: 0,
,I/iu.UploadsManager( 4477): num updated entries: 0
,I/iu.SyncManager( 4477): NEXT; no task
,D/ChimeraCfgMgr( 4477): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 4477): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ActivityManager(  942): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5079 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,D/libc    ( 4574): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
,D/libc    ( 4574): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4574): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 4574): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4574): [NET] android_getaddrinfo_proxy+
D/libc    ( 4574): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  396): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,I/DropBoxManagerService(  942): Usage (1282) > Quota (1280)
,D/libc    (  396): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
,D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4574): [NET] android_getaddrinfo_proxy-, success
,I/GLSUser ( 1813): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm,
I/GLSUser ( 1813): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1813): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1813): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/CheckinRequestBuilder( 4477): Checkin reason type: 8 attempt count: 1,
V/GLSActivity( 1813): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WifiService(  942): New client listening to asynchronous messages
E/WifiTrafficPoller(  942): ADD_CLIENT: 7
,I/ActivityManager(  942): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4477): Failed to find provider info for com.google.android.wearable.settings
,D/MdScBoot( 5029): [696.1.] 30@-141119 -> 40
,I/Babel   ( 4574): connection state changed from UNKNOWN to CONNECTED,
,D/MdScBootUi( 5029): [696.1.2.] boot 118
,D/MdScSimSt( 5029): [696.1.2.] qry 118: 0+1 running 0
,D/DotMatrix( 1327): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1327): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1216): reapply : com.google.android.gms 3 40
,W/Kids    ( 4477): [AccountUtils] Account not ready
W/Kids    ( 4477): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4477): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4477): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4477): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4477): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4477): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4477): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4477): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4477): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4477): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4477): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4477): 	at java.lang.Thread.run(Thread.java:818)
,I/art     ( 4477): Explicit concurrent mark sweep GC freed 23916(1821KB) AllocSpace objects, 22(440KB) LOS objects, 47% free, 4MB/8MB, paused 1.276ms total 84.593ms,
,I/CalendarProvider2( 4976): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
W/ContentResolver( 4976): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/Process (  942): killProcessQuiet, pid=4346
I/ActivityManager(  942): Killing 4346:com.android.settings:remote/1000 (adj 15): empty #17
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  942): Recipient 4346,
,I/ActivityManager(  942): Killing 4370:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17,
D/Process (  942): killProcessQuiet, pid=4370
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,D/VoldConnector(  942): SND -> {20 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
,E/Vold    (  386): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
W/ContextImpl( 5079): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache,
,D/VoldConnector(  942): SND -> {21 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
,E/Vold    (  386): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl( 5079): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files,
,E/WifiTrafficPoller(  942): TRAFFIC_STATS_POLL true Token 11 num clients 7
D/WIFI_ICON( 1216): WifiActivity: 3
E/WifiTrafficPoller(  942):  packet count Tx=90 Rx=134
E/WifiTrafficPoller(  942): notifying of data activity 3
,D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/GAv4    ( 5079): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:,
I/GAv4    ( 5079):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5079):   adb logcat -s GAv4
,D/VoldConnector(  942): SND -> {22 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
E/Vold    (  386): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 5079): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  942): SND -> {23 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
E/Vold    (  386): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/ContextImpl( 5079): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/ActivityManager(  942): Recipient 4370
,W/GAv4    ( 5079): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
I/ActivityManager(  942): Killing 4393:com.android.smith/1000 (adj 15): empty #17
,D/Process (  942): killProcessQuiet, pid=4393
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  942): Recipient 4393
,I/ActivityManager(  942): Waited long enough for: ServiceRecord{e93ee7d u0 com.htc.HTCSpeaker/.NGFService},
,W/GAv4    ( 5079): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 5079): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/GLSUser ( 1813): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer,
I/GLSUser ( 1813): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1813): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1813): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1813): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/CheckinRequestBuilder( 4477): awaiting user notification for token
D/DotMatrix( 1327): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1327): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1216): reapply : com.google.android.gms 3 40
,I/ActivityManager(  942): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5117 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/global  ( 5079): [apache-http] Connection GC has been deprecated!,
,W/global  ( 5079): [apache-http] Connection GC has been deprecated!,
,W/ResourcesManager( 5117): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5117): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 5117): VM with version 2.1.0 has multidex support,
I/MultiDex( 5117): install
I/MultiDex( 5117): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 5117): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 5117): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5117): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3af8e2c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5117): Installed default security provider GmsCore_OpenSSL
,I/WebViewFactory( 5079): Loading com.google.android.webview version 44.0.2403.117 (code 240311750),
,I/LibraryLoader( 5079): Time to load native libraries: 37 ms (timestamps 2013-2050)
,I/WVCdm   (  403): CdmEngine::OpenSession,
I/WVCdm   (  403): Level3 Library Sep 25 2014 17:10:03
,I/LibraryLoader( 5079): Expected native library version number "",actual native library version number ""
,W/WVCdm   (  403): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory,
,V/WebViewChromiumFactoryProvider( 5079): Binding Chromium to main looper Looper (main, tid 1) {f4f6dd7},
I/LibraryLoader( 5079): Expected native library version number "",actual native library version number ""
D/DrmWidevineDash(  403): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
,D/DrmWidevineDash(  403): Service_Initialize: starts!
D/QSEECOMAPI: (  403): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  403): App is not loaded in QSEE
E/QSEECOMAPI: (  403): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  403): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  403): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  403): App is not loaded in QSEE
,D/QSEECOMAPI: (  403): Loaded image: APP id = 6
D/DrmWidevineDash(  403): Service_Initialize: ends! returns 0,
I/GAV2    ( 4696): Thread[GAThread,5,main]: No campaign data found.
,D/QSAPPSVER(  403): qsapps_get_capabilities: Capability from secure side: 0x0,
D/QSAPPSVER(  403): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  403): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf487d000
E/DrmWidevineDash(  403): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf487d000
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,I/chromium( 5079): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,D/DrmLibTime(  551): got the req here! ret=0
D/DrmLibTime(  551): command id, time_cmd_id = 770
D/DrmLibTime(  551): time_getutcsec starts!
D/DrmLibTime(  551): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  551): QSEE Time Listener: get_utc_seconds
,D/DrmLibTime(  551): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  551): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  551): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  551): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  551): QSEE Time Listener: Retrieved Android system time: 1448460711
D/DrmLibTime(  551): time_getutcsec returns 0, sec = 1448460711; nsec = 0
D/DrmLibTime(  551): time_getutcsec finished! 
E/QC-time-services(  464): Daemon: Time-services: Waiting to acceptconnection
D/DrmLibTime(  551): iotcl_continue_command finished! and return 0 
,D/DrmLibTime(  551): before calling ioctl to read the next time_cmd
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  403): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): hlos api version =  9
D/DrmWidevineDash(  403): tz api version =  9
D/DrmWidevineDash(  403): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  403): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,I/BrowserStartupController( 5079): Initializing chromium process, singleProcess=true
,W/art     ( 5079): Attempt to remove local handle scope entry from IRT, ignoring
,I/GAv4-SVC( 4477): Google Analytics 7.8.99 is starting up.
,E/SysUtils( 5079): ApplicationContext is null in ApplicationStatus,
,D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  403): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  403): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  403): OEMCrypto_OpenSession: starts! SID=0xf4aa6928,
D/DrmWidevineDash(  403): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  403): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  403): OEMCrypto_GetRandom: starts! randomData=0xab249390, dataLength=8
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  403): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab22d9e0, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  403): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  403): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  403): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  403): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  403): OEMCrypto_GetDeviceID: starts! deviceID=0xab233dc8, idLength=0xf4ca66f8
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  403): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  403): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  403): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  403): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  403): OEMCrypto_GetHDCPCapability: starts!, current = 0xf4ca670e, maximum = 0xf4ca670f
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  403): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  403): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): hlos api version =  9
D/DrmWidevineDash(  403): tz api version =  9
D/DrmWidevineDash(  403): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  403): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf4ca677c,
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  403): PrepareKeyRequest: nonce=707313067
D/DrmWidevineDash(  403): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab22d1d0
D/DrmWidevineDash(  403): message_length=1611, signature=0xab22d820, signature_length=0xf4ca66dc
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,E/WifiTrafficPoller(  942): TRAFFIC_STATS_POLL true Token 11 num clients 7
,E/WifiTrafficPoller(  942):  packet count Tx=90 Rx=135
E/WifiTrafficPoller(  942): notifying of data activity 1,
D/WIFI_ICON( 1216): WifiActivity: 1
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/chromium( 5079): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 5079): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5079): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  403): CdmEngine::CloseSession
,D/DrmWidevineDash(  403): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  403): L3 Terminate.
D/DrmWidevineDash(  403): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): Service_Uninitialize: starts!
D/QSEECOMAPI: (  403): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  403): QSEECom_shutdown_app, app_id = 6
D/DrmWidevineDash(  403): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  403): OEMCrypto_Terminate: ends! returns 0
I/Adreno-EGL( 5079): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 5079): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 5079): Build Date: 03/09/15 Mon
I/Adreno-EGL( 5079): Local Branch: 
I/Adreno-EGL( 5079): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 5079): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 5079):                  d74aa161a12b9c6fc6332151
,W/AudioManagerAndroid( 5079): Requires BLUETOOTH permission,
I/NSApplication( 5079): Starting up...
,I/ActivityManager(  942): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=5178 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager(  942): Killing 4323:com.android.settings/1000 (adj 15): empty #17
D/Process (  942): killProcessQuiet, pid=4323
,D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,E/cutils-trace( 5197): Error opening trace file: Permission denied (13),
,I/dex2oat ( 5197): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=36 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 5197): dex2oat: override thread count:4
,I/dex2oat ( 5197): dex2oat took 46.742ms (threads: 4),
,I/Adreno-EGL( 5117): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 5117): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 5117): Build Date: 03/09/15 Mon
I/Adreno-EGL( 5117): Local Branch: 
I/Adreno-EGL( 5117): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 5117): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 5117):                  d74aa161a12b9c6fc6332151
I/ActivityManager(  942): Recipient 4323
,I/Adreno-EGL( 5117): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 5117): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 5117): Build Date: 03/09/15 Mon
I/Adreno-EGL( 5117): Local Branch: 
I/Adreno-EGL( 5117): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
,I/Adreno-EGL( 5117): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 5117):                  d74aa161a12b9c6fc6332151
,D/Process (  942): killProcessQuiet, pid=3395,
,I/ActivityManager(  942): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=5207 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  942): Killing 3395:com.android.defcontainer/u0a15 (adj 15): empty #17
,I/WVCdm   (  403): CdmEngine::OpenSession
,I/WVCdm   (  403): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  403): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  403): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
,D/DrmWidevineDash(  403): Service_Initialize: starts!
D/QSEECOMAPI: (  403): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  403): App is not loaded in QSEE
E/QSEECOMAPI: (  403): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  403): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  403): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  403): App is not loaded in QSEE
,D/QSEECOMAPI: (  403): Loaded image: APP id = 7,
D/DrmWidevineDash(  403): Service_Initialize: ends! returns 0
,D/QSAPPSVER(  403): qsapps_get_capabilities: Capability from secure side: 0x0
D/QSAPPSVER(  403): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  403): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf487d000
,E/DrmWidevineDash(  403): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf487d000
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/DrmLibTime(  551): got the req here! ret=0,
D/DrmLibTime(  551): command id, time_cmd_id = 770
D/DrmLibTime(  551): time_getutcsec starts!
D/DrmLibTime(  551): QSEE Time Listener: time_getutcsec
,D/DrmLibTime(  551): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  551): QSEE Time Listener: time_get_modem_time,
,D/DrmLibTime(  551): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  551): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  551): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
,D/DrmLibTime(  551): QSEE Time Listener: Retrieved Android system time: 1448460712
D/DrmLibTime(  551): time_getutcsec returns 0, sec = 1448460712; nsec = 0
D/DrmLibTime(  551): time_getutcsec finished! 
D/DrmLibTime(  551): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  551): before calling ioctl to read the next time_cmd
E/QC-time-services(  464): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  403): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): hlos api version =  9
D/DrmWidevineDash(  403): tz api version =  9
D/DrmWidevineDash(  403): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  403): OEMCrypto_IsKeyboxValid: starts!
,D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  403): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  403): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  403): OEMCrypto_OpenSession: starts! SID=0xf4ca6928
D/DrmWidevineDash(  403): OEMCrypto_OpenSession Session ID = 0,
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  403): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  403): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  403): OEMCrypto_GetRandom: starts! randomData=0xab224d08, dataLength=8
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  403): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab229268, wrapped_rsa_key_length=1280,
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  403): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  403): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  403): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  403): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  403): OEMCrypto_GetDeviceID: starts! deviceID=0xab233e08, idLength=0xf49a66f8
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  403): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  403): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  403): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  403): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  403): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  403): OEMCrypto_GetHDCPCapability: starts!, current = 0xf49a670e, maximum = 0xf49a670f
,D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  403): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): hlos api version =  9
D/DrmWidevineDash(  403): tz api version =  9
D/DrmWidevineDash(  403): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  403): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf49a677c
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0,
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  403): PrepareKeyRequest: nonce=3710022593
D/DrmWidevineDash(  403): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab22d1d0
D/DrmWidevineDash(  403): message_length=1646, signature=0xab22d848, signature_length=0xf49a66dc
,D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,I/ActivityManager(  942): Recipient 3395,
,W/ResourcesManager( 5207): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,I/SocialFeedProvider( 1586): +disConnect socialManager,
I/SocialFeedProvider( 1586): disconnect socialManager
I/SocialFeedProvider( 1586): -disConnect socialManager
,D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  403): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  403): CdmEngine::CloseSession
D/DrmWidevineDash(  403): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  403): L3 Terminate.
D/DrmWidevineDash(  403): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): Service_Uninitialize: starts!
D/QSEECOMAPI: (  403): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  403): QSEECom_shutdown_app, app_id = 7
D/DrmWidevineDash(  403): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  403): OEMCrypto_Terminate: ends! returns 0
,I/CheckinRequestBuilder( 4477): Classify the device as Phone.,
,I/ActivityManager(  942): Start proc com.htc.sense.news for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper: pid=5234 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a
V/AlarmManager(  942): sending alarm PendingIntent{18170fe2: PendingIntentRecord{3374cf73 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1448460712493, Int=0
,I/art     ( 1813): Explicit concurrent mark sweep GC freed 10499(554KB) AllocSpace objects, 8(672KB) LOS objects, 49% free, 4MB/8MB, paused 990us total 62.085ms,
,E/WifiTrafficPoller(  942): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  942):  packet count Tx=90 Rx=135
D/WIFI_ICON( 1216): WifiActivity: 0
E/WifiTrafficPoller(  942): notifying of data activity 0
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/libc    ( 4477): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,D/libc    ( 4477): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 4477): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 4477): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4477): [NET] android_getaddrinfo_proxy+
D/libc    ( 4477): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  396): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024,
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,I/ImageRamCache( 5234): create image Cache, size: 31457280.
,I/ImageRamCache( 5234): [resize] ImageRamCache resized to: 30Mb.
I/ImageRamCache( 5234): create image Cache, size: 31457280.
,I/FeedSettings( 5234): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true,
I/FeedSettings( 5234): GroupBudget 0.500000 0.380000
I/FeedSettings( 5234): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 5234): changeLocale(): en_GB,
,I/Prism.AllAppsOptionsMa_( 5234): loadSortType() with Custom,
I/Prism.AllAppsOptionsMa_( 5234): loadGridSize() with Alternative
E/WifiStateMachine(  942): handleMessage: E msg.what=131155,
E/WifiStateMachine(  942): processMsg: ConnectedState
D/libc    (  396): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  396): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4477): [NET] android_getaddrinfo_proxy-, success
E/WifiStateMachine(  942):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=17.8, 0.0, 0.0  rx=25.7 bcn=0 [on:0 tx:0 rx:0 period:2958] from screen [on:0 period:1056733973] gl hn u24 rssi=-50 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  942): processMsg: L2ConnectedState
E/WifiStateMachine(  942):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=17.8, 0.0, 0.0  rx=25.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1056733974] gl hn u24 rssi=-50 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  942):  get link layer stats 0
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1326): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1326): environment dirty rate=0 [7][0][0]
E/WifiStateMachine(  942): fetchRssiLinkSpeedAndFrequencyNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  942): fetchRssiLinkSpeedAndFrequencyNative rssi=-55 linkspeed=72
E/WifiConfigStore(  942): updateConfiguration freq=2462 BSSID=c0:ff:d4:d3:aa:48 RSSI=-55 "NG700"WPA_PSK
E/WifiStateMachine(  942): calculateWifiScore freq=2462 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=12.92 txretriesrate=0.00 rxrate=16.34 userTriggerdPenalty0
E/WifiStateMachine(  942):  good link -> stuck count =0
E/WifiStateMachine(  942):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  942):  isHighRSSI       ---> score=65
,D/WifiWatchdogStateMachine(  942): RSSI current: 3 new: -55, 3
E/WifiStateMachine(  942): handleMessage: X
D/WIFI_ICON( 1216): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/libc    ( 4477): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4477): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 4477): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4477): [NET] android_getaddrinfofornet-, err=8,
,D/libc    ( 4477): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4477): [NET] android_getaddrinfofornet-, err=8
,I/art     (  942): Explicit concurrent mark sweep GC freed 15831(838KB) AllocSpace objects, 4(208KB) LOS objects, 33% free, 16MB/25MB, paused 1.600ms total 172.160ms,
,I/CheckinTask( 4477): Sending checkin request (8471 bytes)
,I/SocialManager[SocialBiLogHelper]( 5234): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 5234): last commit ulog time 1448443175626
I/SocialManager[SocialBiLogHelper]( 5234): skip commit this time
,D/Process (  942): killProcessQuiet, pid=4451
I/ActivityManager(  942): Killing 4451:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  942): Recipient 4451
,D/Process (  942): killProcessQuiet, pid=4414
I/ActivityManager(  942): Killing 4414:com.android.vending/u0a72 (adj 15): empty #17,
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  942): Recipient 4414,
,D/Process (  942): killProcessQuiet, pid=3969
I/ActivityManager(  942): Killing 3969:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  942): Recipient 3969
,I/CheckinRequestBuilder( 4477): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  942): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=5273 uid=10035 gids={50035, 9997} abi=arm64-v8a
I/ActivityManager(  942): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4477): Failed to find provider info for com.google.android.wearable.settings
,E/WifiDataStallTracker(  942): DATA_MONITOR_POLL true Token 1
,D/WifiDataStallTracker(  942): updateDataStallInfo: mDataStallTxRxSum={txSum=95 rxSum=89} preTxRxSum={txSum=67 rxSum=68},
D/WifiDataStallTracker(  942): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  942): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,I/ActivityManager(  942): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=5297 uid=10076 gids={50076, 9997} abi=arm64-v8a
,I/ActivityManager(  942): Killing 4611:com.google.android.youtube/u0a176 (adj 15): empty #17
D/Process (  942): killProcessQuiet, pid=4611
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,D/PMS     (  942): acquireWL(34307b63): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 942 1000 null,
I/BatteryService(  942): n_update end
D/PMS     (  942): releaseWL(34307b63): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/ActivityManager(  942): Recipient 4611
,D/HtcPowerSaver(  942): updateBatteryInfo
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  942): plugged=true pluggin=true,
D/UsbnetService(  942): BroadcastReceiver::onReceive+
D/PowerUI ( 1216): closing low battery warning: level=100
D/UsbnetService(  942): onReceive BATTERY_CHANGED
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  942): runPSCheck
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  942): Checking...
D/UsbnetService(  942):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  942): >> updateStatus
D/UsbnetService(  942): BroadcastReceiver::onReceive-
D/WifiController(  942): battery changed pluggedType: 2
D/HeadsetStateMachine( 3112): Disconnected process message: 10, size: 0
D/PowerUI ( 1216): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  942): handleMessage: E msg.what=155652
I/HtcPowerSaver(  942): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  942): processMsg: DeviceActiveState
I/HtcPowerSaver(  942): << updateStatus
,D/WifiController(  942): processMsg: StaEnabledState
D/WifiController(  942): processMsg: DefaultState
D/WifiController(  942): handleMessage: X
I/IntentController( 1216): receive(android.intent.action.BATTERY_CHANGED,1,false)
,E/WifiTrafficPoller(  942): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  942):  packet count Tx=111 Rx=152
E/WifiTrafficPoller(  942): notifying of data activity 3
D/WIFI_ICON( 1216): WifiActivity: 3
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/SMSBackup( 5297): Got a database change event,
,D/CustomHighlightReceiver( 5234): [custom highlight] onReceive,
,D/CustomHighlightService( 5234): [custom highlight] onHandleIntent
,D/NewsDB  ( 5234): set custom highlight []
,I/BatteryController( 1216): status:5 level:100 unsupport:false plugged:true
,I/ActivityManager(  942): Start proc com.htc.sense.mms for broadcast com.htc.sense.mms/.ui.MessagingShortcutReceiver: pid=5321 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
,D/CustomHighlightService( 5234): [custom highlight] set tags ,
I/ActivityManager(  942): Killing 4696:com.google.android.gm/u0a106 (adj 15): empty #17
D/Process (  942): killProcessQuiet, pid=4696
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService, state=2, flag=1, pid=4477, uid=10024, userID:0,
I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateActivity, state=2, flag=1, pid=4477, uid=10024, userID:0
,I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver, state=2, flag=1, pid=4477, uid=10024, userID:0,
I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$Receiver, state=2, flag=1, pid=4477, uid=10024, userID:0
,I/ActivityManager(  942): Recipient 4696
,D/BluetoothManagerService(  942): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  942): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@38dc9b4f mBinding = false
W/Settings:Agent(  942): MONITOR_LOG
W/Settings:Agent(  942): name: bluetooth_on
W/Settings:Agent(  942): value: 0
W/Settings:Agent(  942): >> traceCallingStack()
W/Settings:Agent(  942): Process.myPid(): 942
,W/Settings:Agent(  942): Process.myTid(): 971
W/Settings:Agent(  942): Process.myUid(): 1000
W/Settings:Agent(  942): 
W/Settings:Agent(  942): 
W/System.err(  942): java.lang.Throwable: stack dump
,W/System.err(  942): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  942): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  942): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  942): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  942): 	at android.provider.Settings$Global.putString(Settings.java:7403)
,W/System.err(  942): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  942): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:378)
W/System.err(  942): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:624)
W/System.err(  942): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  942): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  942): 
W/Settings:Agent(  942): << traceCallingStack(): 20(ms)
,D/AccTypeManager( 1762): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android,
,D/AccTypeManager( 1762): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/SystemReader(  942): Cannot find grip_rejection_width, use default value instead
,W/ResourcesManager( 1543): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  942): Message: MESSAGE_DISABLE
,D/BluetoothManagerService(  942): Sending off request.
,D/BluetoothAdapterState( 3112): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3112): Setting state to 13
I/BluetoothAdapterState( 3112): Bluetooth adapter state changed: 12-> 13
D/BluetoothManagerService(  942): +onBluetoothStateChange prev=12 new=13
W/Prism.AllAppsManager( 1586): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/Prism.ItemManager( 1586): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1586): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/BluetoothAdapterProperties( 3112): onBluetoothDisable()
I/bt-btm  ( 3112): BTM_SetDiscoverability
I/bt-btm  ( 3112): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3112): disc_mode 0000
I/bt-btm  ( 3112): evt_type=0x0 p-cb->evt_type=0x0 
I/BluetoothAdapterState( 3112): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/bt-btm  ( 3112): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
D/BluetoothManagerService(  942): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  942): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
I/bt-btif ( 3112): BTM_SetDiscoverab->adapter_properties_cb
D/BluetoothManagerService(  942): Bluetooth State Change Intent: 12 -> 13
D/WifiManager( 4780): setWifiEnabled: Base Package Name=com.example.hello, uid=10373
D/WifiService(  942): New client listening to asynchronous messages
D/WifiService(  942): setWifiEnabled: false pid=4780, uid=10373
E/WifiStateMachine(  942): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiService(  942): Invoking mWifiStateMachine.setWifiEnabled
D/PMS     (  942): acquireWL(2acff2b7): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3112 1002 null
W/Settings:Agent(  942): MONITOR_LOG
W/Settings:Agent(  942): name: wifi_on
I/WifiService(  942): isSprintWifiRestricted(): false
W/Settings:Agent(  942): value: 0
I/WifiService(  942): isMdmWifiRestricted(): false
W/Settings:Agent(  942): >> traceCallingStack()
W/Settings:Agent(  942): Process.myPid(): 942
W/Settings:Agent(  942): Process.myTid(): 1617
I/IntentController( 1216): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
I/bt-btm  ( 3112): BTM_SetConnectability
I/bt-btm  ( 3112): btm_ble_set_connectability mode=0x0 combined_mode=0x1
,D/bt-btm  ( 3112): disc_mode 0000
I/bt-btm  ( 3112): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
W/Settings:Agent(  942): Process.myUid(): 1000
W/Settings:Agent(  942): 
W/Settings:Agent(  942): 
D/NGFService( 3808): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
I/Launcher( 1586): Deferring update until onResume
D/Launcher( 1586): waitUntilResume // bindAppsUpdated
D/BluetoothAdapterProperties( 3112): Scan Mode:21
W/System.err(  942): java.lang.Throwable: stack dump
D/AccTypeManager( 1762): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
W/ResourcesManager(  942): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/Prism.ItemManager( 5234): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 5234): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/BluetoothAdapterState( 3112): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
I/bt-btif ( 3112): BTA_JvDeleteRecord
I/bt-btif ( 3112): BTA_JvRfcommStopServer
D/bt-btm  ( 3112): BTM_FreeSCN 
D/bt-sdp  ( 3112): SDP_DeleteRecord ok, num_records:14
I/bt-btif ( 3112): BTA_JvDeleteRecord
I/bt-btif ( 3112): BTA_JvRfcommStopServer
D/bt-btm  ( 3112): BTM_FreeSCN 
I/bt-btif ( 3112): BTA_JvDeleteRecord
I/bt-btif ( 3112): BTA_JvRfcommStopServer
D/bt-btm  ( 3112): BTM_FreeSCN 
I/bt-btif ( 3112): BTA_JvDeleteRecord
I/bt-btif ( 3112): BTA_JvRfcommStopServer
D/bt-btm  ( 3112): BTM_FreeSCN 
I/bt-btif ( 3112): BTA_JvDeleteRecord
I/bt-btif ( 3112): BTA_JvRfcommStopServer
D/bt-btm  ( 3112): BTM_FreeSCN 
I/bt-btif ( 3112): BTA_JvDeleteRecord
I/bt-btif ( 3112): BTA_JvRfcommStopServer
D/bt-btm  ( 3112): BTM_FreeSCN 
E/bt-btif ( 3112): cmd socket is not created
E/BtOppRfcommListener( 3112): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothSapService( 3112): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/HtcWrapAdjustableCursorFactory( 5321): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.
D/MessageFrequencyProvider( 5321): onCreate
I/bt-btm  ( 3112): BTM_SEC_CLR[13]: id 55
D/bt-sdp  ( 3112): SDP_DeleteRecord ok, num_records:13
I/bt-btm  ( 3112): BTM_SEC_CLR[14]: id 56
D/bt-sdp  ( 3112): SDP_DeleteRecord ok, num_records:12
I/bt-btm  ( 3112): BTM_SEC_CLR[15]: id 57
D/bt-sdp  ( 3112): SDP_DeleteRecord ok, num_records:11
I/bt-btm  ( 3112): BTM_SEC_CLR[16]: id 58
D/bt-sdp  ( 3112): SDP_DeleteRecord ok, num_records:10
I/bt-btm  ( 3112): BTM_SEC_CLR[17]: id 59
D/bt-sdp  ( 3112): SDP_DeleteRecord ok, num_records:9
I/bt-btm  ( 3112): BTM_SEC_CLR[18]: id 60
D/bt-sdp  ( 3112): SDP_DeleteRecord ok, num_records:8
I/bt-btm  ( 3112): Write Extended Inquiry Response to controller
I/bt-btm  ( 3112): Write Extended Inquiry Response to controller
I/bt-btm  ( 3112): Write Extended Inquiry Response to controller
I/bt-btm  ( 3112): Write Extended Inquiry Response to controller
V/BluetoothPbapReceiver( 3112): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 3112): ***********state = 13
V/GetPrviateResource( 5321): GetPrviateResource
V/GetPrviateResource( 5321): GetPrviateResource
E/ExternalAccountType( 1762): Unsupported attribute readOnly
I/BtOppRfcommListener( 3112): stopping Accept Thread
I/BtOppRfcommListener( 3112): BluetoothSocket listen thread finished
W/bt-l2cap( 3112): L2CAP - L2CA_Deregister() called for PSM: 0x000f
I/bt-btm  ( 3112): BTM_SetDiscoverability
I/bt-btm  ( 3112): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3112): disc_mode 0000
I/bt-btm  ( 3112): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 3112): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3112): BTM_SetConnectability
I/bt-btm  ( 3112): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3112): disc_mode 0000
D/bt-btm  ( 3112): btm_ble_update_adv_flag new=0x1c
D/bt-btm  ( 3112): btm_ble_update_adv_flag old=0x18
I/bt-btm  ( 3112): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 3112): BTM_IsInquiryActive
I/bt-btm  ( 3112): BTM_CancelRemoteDeviceName()
I/bt-btm  ( 3112): btm_ble_clear_white_list
W/bt-btif ( 3112): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
D/PhoneApp( 1543): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,D/bt-btif ( 3112): AG evt (hdl 0x0001): State 0, Event 0x0501
D/bt-btif ( 3112): AG evt (hdl 0x0002): State 0, Event 0x0501
D/bt-sdp  ( 3112): SDP_DeleteRecord ok, num_records:7
D/bt-btm  ( 3112): BTM_FreeSCN 
I/bt-btm  ( 3112): BTM_SEC_CLR[3]: id 12
D/bt-sdp  ( 3112): SDP_DeleteRecord ok, num_records:6
D/bt-btm  ( 3112): BTM_FreeSCN 
I/bt-btm  ( 3112): BTM_SEC_CLR[4]: id 29
D/bt-avp  ( 3112): AVRC_Close handle:0
D/bt-btif ( 3112): AV Sevent(0x41)=0x120a(API_CLOSE) state=0LE_EVT
D/bt-btif ( 3112): AV Sevent(0x41)=0x120a(API_CLOSE) state=0(INIT)
D/MessageCustFlag( 5321): sense_version=6.0
D/bt-sdp  ( 3112): SDP_DeleteRecord ok, num_records:5
D/bt-sdp  ( 3112): SDP_DeleteRecord ok, num_records:4
W/bt-l2cap( 3112): L2CAP - L2CA_Deregister() called for PSM: 0x0019
D/bt-sdp  ( 3112): SDP_DeleteRecord ok, num_records:3
W/bt-l2cap( 3112): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3112): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3112): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3112): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3112): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3112): L2CAP - L2CA_Deregister() called for PSM: 0x0011
W/bt-l2cap( 3112): L2CAP - L2CA_Deregister() called for PSM: 0x0013
I/bt-att  ( 3112): GATT_Deregister gatt_if=3
I/bt-att  ( 3112): GATT_Listen gatt_if=3
I/bt-btm  ( 3112): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3112): BTM_ReadConnectability
I/bt-btm  ( 3112): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3112): disc_mode 0000
I/bt-att  ( 3112): GATT_Deregister gatt_if=4
I/bt-att  ( 3112): GATT_Listen gatt_if=4
I/bt-btm  ( 3112): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3112): BTM_ReadConnectability
I/bt-btm  ( 3112): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3112): disc_mode 0000
E/bt-btif ( 3112): bta_gattc_deregister Deregister Failedm unknown client cif
D/BTAccessoryUtil( 5321): createReceiver
I/GLSUser ( 1813): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1813): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1813): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1813): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/QuickSettingBluetooth( 1216): receive.ACTION_STATE_CHANGE:STATE_TURNING_OFF
W/System.err(  942): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  942): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
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
W/Settings:Agent(  942): << traceCallingStack(): 51(ms)
I/bt-btm  ( 3112): btm_ble_clear_white_list_complete
I/ActivityManager(  942): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=5346 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
D/BTAccessoryUtil( 5321): registerReceiver return intent = null
V/BluetoothPbapService( 3112): Pbap Service closeService in
V/BluetoothPbapService( 3112): successfully stopped pbap service
V/BluetoothPbapService( 3112): Pbap Service closeService out
D/MessageCustFlag( 5321): sku_id=118
V/BluetoothPbapService( 3112): Pbap Service onDestroy
V/GLSActivity( 1813): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/WifiController(  942): handleMessage: E msg.what=155656
D/WifiController(  942): processMsg: DeviceActiveState
D/WifiController(  942): processMsg: StaEnabledState
D/WifiController(  942): transitionTo: destState=ApStaDisabledState
D/WifiController(  942): handleMessage: new destination call exit/enter
D/WifiController(  942): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiController(  942): invokeExitMethods: DeviceActiveState
D/WifiController(  942): invokeExitMethods: StaEnabledState
D/WifiController(  942): moveTempStackToStateStack: i=0,j=1
D/WifiController(  942): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=ApStaDisabledState
D/WifiController(  942): invokeEnterMethods: ApStaDisabledState
D/WifiController(  942): handleMessage: X
V/BluetoothPbapService( 3112): Pbap Service closeService in
V/BluetoothPbapService( 3112): Pbap Service closeService out
E/WifiStateMachine(  942): handleMessage: E msg.what=131084
E/WifiStateMachine(  942): processMsg: ConnectedState
D/HtcBuildUtils( 5321): getRATByHtcTelephonyCapability:1
E/WifiStateMachine(  942):  ConnectedState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  942): processMsg: L2ConnectedState
I/jxcore-log( 4780): ****TEST TOOK:  5209  ms ****
I/jxcore-log( 4780): 
W/SystemReader( 5321): Cannot find qct_8960_interface, use default value instead
E/WifiStateMachine(  942):  L2ConnectedState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  942): processMsg: ConnectModeState
E/WifiStateMachine(  942):  ConnectModeState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  942): processMsg: DriverStartedState
I/jxcore-log( 4780): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4780): 
E/WifiStateMachine(  942):  DriverStartedState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  942): processMsg: SupplicantStartedState
E/WifiStateMachine(  942):  SupplicantStartedState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  942): transitionTo: destState=WaitForP2pDisableState
E/WifiStateMachine(  942): handleMessage: new destination call exit/enter
E/WifiStateMachine(  942): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=SupplicantStartedState,active=true,parent=DefaultState
E/WifiStateMachine(  942): invokeExitMethods: ConnectedState
E/WifiStateMachine(  942): WifiStateMachine: Leaving Connected state
D/WifiDisplayAdapter(  942): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  942):     Client/Owner: Client
D/WifiDisplayAdapter(  942):     GroupId: 
D/WifiDisplayAdapter(  942):     Passphrase: 
D/WifiDisplayAdapter(  942):     SessionId: 0
D/WifiDisplayAdapter(  942):     IP Address: }
D/WifiPerfLock(  942): release()
E/WifiStateMachine(  942): PerfLock released for exiting ConnectedState
E/WifiStateMachine(  942): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
E/WifiStateMachine(  942): invokeExitMethods: L2ConnectedState
E/WifiStateMachine(  942): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
E/WifiStateMachine(  942): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  942): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  942): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  942): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1326): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1326): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1326): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1326): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1326): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1326): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1326): CTRL_IFACE: SAVE_CONFIG - Configuration updated
,E/WifiStateMachine(  942): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1326): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1326): Power_Mode_Type mode = 0
I/wpa_supplicant( 1326): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/WifiP2pService(  942): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1326): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  942): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1326): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  942): setDhcpActive: false
V/NativeCrypto( 1813): Read error: ssl=0x5598a9aae0: I/O error during system call, Connection timed out
D/PMS     (  942): acquireWL(faf349f): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1813 10024 WorkSource{10024 com.google.android.gms}
D/libc    (  942): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  942): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  942): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  942): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  942): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityService(  942): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
E/WifiStateMachine(  942): setDetailed state send new extra info<unknown ssid>
V/NetworkPolicy(  942): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiStateMachine(  942): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  942): NetworkAgent != null
E/WifiStateMachine(  942): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  942): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  942): [NET] android_getaddrinfofornet-, SUCCESS
D/WIFI_ICON( 1216): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
V/NativeCrypto( 1813): SSL shutdown failed: ssl=0x5598a9aae0: I/O error during system call, Broken pipe
I/IntentController( 1216): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  942): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/IntentController( 1216): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1216): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  942): autoRoamSetBSSID any key="NG700"WPA_PSK
E/WifiConfigStore(  942): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  942): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1326): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1326): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1326): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/ConnectivityService(  942): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/wpa_supplicant( 1326): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1326): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1326): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1326): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  942): invokeExitMethods: ConnectModeState
E/WifiStateMachine(  942): invokeExitMethods: DriverStartedState
I/IntentController( 1216): receive(android.net.wifi.STATE_CHANGE,1,false)
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/wpa_supplicant( 1326): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 1326): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  942): Unexpected BatchedScanResults :null
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/wpa_supplicant( 1326): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 1326): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  942): noteBatchedScanstop()
E/WifiStateMachine(  942): [1,448,460,714,119 ms] noteScanEnd no scan source
E/WifiStateMachine(  942): moveTempStackToStateStack: i=0,j=2
E/WifiStateMachine(  942): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=2,Top=WaitForP2pDisableState
E/WifiStateMachine(  942): invokeEnterMethods: WaitForP2pDisableState
D/WifiP2pService(  942): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  942): handleMessage: X
D/WifiP2pService(  942): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  942): handleMessage: E msg.what=131212
E/WifiStateMachine(  942): processMsg: WaitForP2pDisableState
E/WifiStateMachine(  942):  WaitForP2pDisableState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  942): processMsg: SupplicantStartedState
E/WifiStateMachine(  942):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  942): processMsg: DefaultState
E/WifiStateMachine(  942):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  942): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  942): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  942): handleMessage: X
E/WifiStateMachine(  942): handleMessage: E msg.what=131212
E/WifiStateMachine(  942): processMsg: WaitForP2pDisableState
E/WifiStateMachine(  942):  WaitForP2pDisableState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  942): processMsg: SupplicantStartedState
E/WifiStateMachine(  942):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService(  942): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
E/WifiStateMachine(  942): processMsg: DefaultState
E/WifiStateMachine(  942):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  942): ValidatedState{ when=0 what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  942): DefaultState{ when=0 what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  942): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  942): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  942): Validated
E/WifiStateMachine(  942): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  942): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  942): handleMessage: X
D/WifiNetworkAgent(  942): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  942): handleMessage: E msg.what=131212
E/WifiStateMachine(  942): processMsg: WaitForP2pDisableState
D/MmsConfig( 5321): packageName: com.htc.vvm.att does not exist
E/WifiStateMachine(  942):  WaitForP2pDisableState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  942): processMsg: SupplicantStartedState
D/MessageCustFlag( 5321): sku_id=118
E/WifiStateMachine(  942):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  942): processMsg: DefaultState
E/WifiStateMachine(  942):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  942): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  942): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  942): handleMessage: X
D/PMS     (  942): releaseWL(faf349f): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
D/WIFI_ICON( 1216): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 5346): -onCreate()
,D/WifiMonitor(  942): stopMonitoring(p2p0) = com.android.server.wifi.p2p.WifiP2pServiceImpl$P2pStateMachine@3e48e7d2
D/WifiP2pService(  942): P2pDisablingState
D/WifiDisplayController(  942): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiP2pService(  942): P2pDisablingState{ when=-3ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  942): p2p socket connection lost
D/WifiDisplayAdapter(  942): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  942):     Client/Owner: Client
D/WifiDisplayAdapter(  942):     GroupId: 
D/WifiDisplayAdapter(  942):     Passphrase: 
D/WifiDisplayAdapter(  942):     SessionId: 0
D/WifiDisplayAdapter(  942):     IP Address: }
E/WifiStateMachine(  942): handleMessage: E msg.what=131205
D/WifiP2pService(  942): P2pDisabledState
E/WifiStateMachine(  942): processMsg: WaitForP2pDisableState
E/WifiStateMachine(  942):  WaitForP2pDisableState !CMD_DISABLE_P2P_RSP uid=1000 0 0
D/WifiP2pService(  942): P2pDisabledState{ when=0 what=131333 target=com.android.internal.util.StateMachine$SmHandler }
D/MessagingShortcutReceiver( 5321): keep hiding shortcut bubble
D/WifiP2pService(  942): DefaultState{ when=0 what=131333 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  942): transitionTo: destState=SupplicantStoppingState
E/WifiStateMachine(  942): handleMessage: new destination call exit/enter
E/WifiStateMachine(  942): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  942): invokeExitMethods: WaitForP2pDisableState
E/WifiStateMachine(  942): invokeExitMethods: SupplicantStartedState
E/WifiStateMachine(  942): moveTempStackToStateStack: i=0,j=1
E/WifiStateMachine(  942): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStoppingState
E/WifiStateMachine(  942): invokeEnterMethods: SupplicantStoppingState
E/WifiStateMachine(  942): Call handleNetworkDisconnect() in SupplicantStoppingState
E/WifiStateMachine(  942): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - enter - invokeEnterMethods
E/WifiStateMachine(  942): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1326): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1326): Power_Mode_Type mode = 0
I/wpa_supplicant( 1326): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  942): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/WifiP2pService(  942): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1326): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  942): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1326): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  942): setDhcpActive: false
D/MessagingShortcut( 5321): updateMsgShortcut, msg count> -1
D/SettingsManager( 5321): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@1a881622
D/MessagingShortcut( 5321): After query: 0
D/MessagingShortcut( 5321): mPresentUnreadCount: -1
W/CheckinRequestBuilder( 4477): awaiting user notification for token
D/MessageUtils( 5321): [getShortcut] com.htc.sense.mms.ui.ConversationList, false
D/MessagingShortcut( 5321): setMsgShortcutDrawable> 0, false
I/QuickSettingWifi( 1216): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:0
D/MessagingShortcut( 5321): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
V/Settings:HtcSettingsApplication( 5346): [5346/5346] onCreate()
I/QuickSettingWifi( 1216): receive.wifiConnect:false wifiAPname:null elapse:1
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1327): [EventService] reorderNotification, total:0
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
W/PackageManager(  942): Unable to load service info ResolveInfo{d54026d com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
I/QuickSettingWifi( 1216): receive.wifiConnect:false wifiAPname:null elapse:0
,I/CheckinRequestBuilder( 4477): Classify the device as Phone.
,I/ActivityManager(  942): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=5372 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a,
,D/PMS     (  942): acquireWL(a473b4d): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 5346 1000 null
I/ActivityManager(  942): Killing 4740:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
,D/Process (  942): killProcessQuiet, pid=4740
,D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,W/ContextImpl( 5346): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
,I/art     (  411): Explicit concurrent mark sweep GC freed 8646(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 176us total 44.054ms
,E/WifiStateMachine(  942): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityService(  942): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler( 1216): CM callback handler got msg 524292
D/ConnectivityService(  942):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine(  942): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  942):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  942): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  942): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  942): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/Nat464Xlat(  942): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
I/SecurityController( 1216): onLost 100
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  942): Disconnected - quitting
,D/ConnectivityService(  942): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  942): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/NetworkManagementService(  942): Removing idletimer
D/usbnet  (  942): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/usbnet  (  942):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  942): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
,I/BackupManagerService(  942): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/art     (  411): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 127us total 16.097ms
,D/PMS     (  942): acquireWL(301866ba): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 942 1000 null
,D/CSLegacyTypeTracker(  942): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
D/ConnectivityService(  942): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE,
,D/bt-btm  ( 3112): BTM_BleGetVendorCapabilities
,W/bt-btif ( 3112): ag scb idx 1 not allocated
W/bt-btif ( 3112): ag scb idx 2 not allocated
E/bt-btif ( 3112): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3112): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3112): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3112): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3112): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3112): L2CAP - L2CA_Deregister() called for PSM: 0x0019,
W/bt-l2cap( 3112): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3112): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3112): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3112): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3112): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3112): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3112): L2CAP - PSM: 0x0017 not found for deregistration
E/bt-btif ( 3112): bta_gattc_deregister Deregister Failedm unknown client cif
E/bt_userial_mct( 3112): pthread_join() FAILED result:3
,I/art     (  411): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 133us total 15.693ms
,I/ActivityManager(  942): Recipient 4740
D/WifiService(  942): Client connection lost with reason: 4
,E/cutils-trace( 5370): Error opening trace file: Permission denied (13),
,D/WISPrService( 5346): >>>>>WISPrService start isConnected = true<<<<<
D/PMS     (  942): releaseWL(a473b4d): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
I/ActivityManager(  942): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=5413 uid=10034 gids={50034, 9997, 3002, 3001} abi=arm64-v8a
,D/PMS     (  942): acquireWL(315e1cc8): PARTIAL_WAKE_LOCK  StartingDockService 0x1 5346 1000 null
D/BluetoothManagerService(  942): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  942): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@39596147:true
,W/System.err(  942): java.lang.Throwable: stack dump
E/WifiStateMachine(  942): stopping supplicant
W/WifiHW  (  942): QCOM Debug wifi_send_command "TERMINATE"
D/wpa_supplicant( 1326): RX global ctrl_iface - hexdump(len=9): 54 45 52 4d 49 4e 41 54 45
,D/wpa_supplicant( 1326): wlan0: Removing interface wlan0
W/System.err(  942): 	at java.lang.Thread.dumpStack(Thread.java:490)
D/PMS     (  942): releaseWL(2acff2b7): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
W/System.err(  942): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
D/WifiService(  942): New client listening to asynchronous messages
W/System.err(  942): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  942): 	at android.os.Binder.execTransact(Binder.java:454)
E/WifiStateMachine(  942): setWifiState: disabling
D/wpa_supplicant( 1326): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
,D/wpa_supplicant( 1326): TDLS: Tear down peers
D/wpa_supplicant( 1326): wpa_driver_nl80211_disconnect(reason_code=3)
E/WifiStateMachine(  942): handleMessage: X
D/WIFI    (  942): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  942):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  942): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
E/WifiStateMachine(  942): enter WifiNetworkFactory startNetwork. mIPTStart:false
E/WifiStateMachine(  942): handleMessage: E msg.what=196614
D/ConnectivityService(  942): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
E/WifiStateMachine(  942): processMsg: SupplicantStoppingState
E/ConnectivityService(  942): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
E/WifiStateMachine(  942):  SupplicantStoppingState !CMD_ON_QUIT 0 0
E/WifiStateMachine(  942): processMsg: DefaultState
,E/WifiStateMachine(  942):  DefaultState !CMD_ON_QUIT 0 0
D/BluetoothAdapter( 5346): 227334053: getState(). Returning 13
E/WifiStateMachine(  942): handleMessage: X
E/ConnectivityService(  942): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
I/IntentController( 1216): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1216): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ResourcesManager( 5372): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/WIFI_ICON( 1216): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1216): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/Tethering(  942): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
V/NetworkPolicy(  942): ensureActiveMobilePolicyLocked()
D/Tethering(  942): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/PMS     (  942): acquireWL(30ab323f): PARTIAL_WAKE_LOCK  NetworkStats 0x1 942 1000 null
D/DATA_ICON( 1216): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
,D/NetworkPolicy(  942): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.,
V/NetworkPolicy(  942): updateNetworkEnabledLocked()
V/NetworkPolicy(  942): updateIfacesLocked()
D/DATA_ICON( 1216): dataConnected: false/false
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,V/NetworkPolicy(  942): updateNotificationsLocked()
,D/BluetoothInputDevice( 5346): BluetoothInputDevice()
,D/wpa_supplicant( 1326): wlan0: Event DEAUTH (12) received
,D/wpa_supplicant( 1326): wlan0: Deauthentication notification
D/wpa_supplicant( 1326): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1326): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1326): Clean 'force_connect' when disconnect
,I/wpa_supplicant( 1326): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
,D/NetworkManagementService(  942): isBandwidthControlEnabled: doneSignal.getCount()= 0
E/wpa_supplicant( 1326): enter disconnect check
I/wpa_supplicant( 1326): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/WifiMonitor(  942): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462]
D/Tethering(  942): interfaceLinkStateChanged wlan0, false
D/Tethering(  942): interfaceStatusChanged wlan0, false
E/WifiMonitor(  942): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
E/WifiMonitor(  942): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
E/WifiStateMachine(  942): WiFiDisplay: getWifidisplayApEnabled=false
D/HTCRequest(  942): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/Tethering(  942): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  942): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  942): TetherInterfaceSM: wlan0: enter UnavailableState
D/wpa_supplicant( 1326): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 1326): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/Tethering(  942): interfaceLinkStateChanged wlan0, false
E/WifiStateMachine(  942): handleMessage: E msg.what=131131
E/WifiStateMachine(  942): processMsg: SupplicantStoppingState
D/Tethering(  942): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  942): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiMonitor(  942): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
E/WifiStateMachine(  942):  SupplicantStoppingState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  942): processMsg: DefaultState
D/CustomizationManager( 5370): ====startRecUseTime====
E/WifiStateMachine(  942):  DefaultState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/htc.customization.log.level( 5370):  is 
E/WifiStateMachine(  942): handleMessage: X
W/CustomizationLogLevel( 5370): Level value is invalid, use default level 2
E/WifiStateMachine(  942): handleMessage: E msg.what=147460
E/WifiStateMachine(  942): processMsg: SupplicantStoppingState
D/BluetoothManagerService(  942): registerStateChangeCallback+
E/WifiStateMachine(  942): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  942):  SupplicantStoppingState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=65101
I/DropBoxManagerService(  942): Usage (1281) > Quota (1280)
E/WifiStateMachine(  942): processMsg: DefaultState
E/WifiStateMachine(  942):  DefaultState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=65102
E/WifiStateMachine(  942): handleMessage: X
D/wpa_supplicant( 1326): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1326): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 1326): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1326): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1326): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x558b08ef88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1326):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1326): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1326): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1326): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1326): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1326): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1326): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1326): nl80211: Skip set_supp_port(unauthorized) while not associ,ated
D/wpa_supplicant( 1326): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1326): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1326): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1326): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1326): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1326): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1326): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1326): EAPOL: External notification - portValid=0
D/WifiMonitor(  942): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  942): WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  942): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  942): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  942): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  942): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/WifiStateMachine(  942): handleMessage: E msg.what=147462
E/WifiStateMachine(  942): processMsg: SupplicantStoppingState
E/WifiStateMachine(  942):  SupplicantStoppingState !SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=65107  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  942): processMsg: DefaultState
E/WifiStateMachine(  942):  DefaultState !SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=65108  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  942): handleMessage: X
D/Tethering(  942): sendTetherStateChangedBroadcast 0, 0, 0
D/BluetoothManagerService(  942): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  942): Registered receivers: 9
E/WifiTrafficPoller(  942): ADD_CLIENT: 8
D/WifiDataStallTracker(  942): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  942): stopDataStallAlarm 
D/WifiScanningService(  942): SCAN_AVAILABLE : 1
D/RttService(  942): SCAN_AVAILABLE : 1
V/AudioService(  942): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  942):     Client/Owner: Client
V/AudioService(  942):     GroupId: 
V/AudioService(  942):     Passphrase: 
V/AudioService(  942):     SessionId: 0
V/AudioService(  942):     IP Address: }
D/WifiService(  942): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
D/HtcEffectManagerBase(  942): onEventChanged id=5 status=false
D/HtcEffectManager(  942): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true mAllPlayOn=false
D/HtcEffectManager(  942): convertEffect before=902
D/HtcEffectManager(  942): convertEffect after=902
E/WifiTrafficPoller(  942): ADD_CLIENT: 8
D/WifiService(  942): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
E/WifiTrafficPoller(  942): ENABLE_TRAFFIC_STATS_POLL true Token 11
D/WifiScanningService(  942): DefaultState got{ when=-3ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  942): releaseWL(30ab323f): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/WISPrService( 5346): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5346): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/RttService(  942): EnabledState got{ when=-4ms what=160513 target=com.android.internal.util.StateMachine$SmHan,dler }
E/WifiTrafficPoller(  942):  packet count Tx=111 Rx=152
E/WifiTrafficPoller(  942): notifying of data activity 0
E/WifiTrafficPoller(  942): ENABLE_TRAFFIC_STATS_POLL false Token 12
E/WifiDataStallTracker(  942): ENABLE_DATA_MONITOR_POLL false Token 1
E/WifiTrafficPoller(  942): ENABLE_TRAFFIC_STATS_POLL false Token 13
E/WifiTrafficPoller(  942): ENABLE_TRAFFIC_STATS_POLL false Token 14
D/WISPrService( 5346): >>>>>WISPrService start isConnected = false<<<<<
D/WifiService(  942): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
D/PMS     (  942): acquireWL(e6a32d3): PARTIAL_WAKE_LOCK  NetworkStats 0x1 942 1000 null
V/NetworkPolicy(  942): updateNetworkEnabledLocked()
V/NetworkPolicy(  942): updateNotificationsLocked()
I/QuickSettingWifi( 1216): receive.wifiConnect:false wifiAPname:null elapse:1
D/UsbnetService(  942): BroadcastReceiver::onReceive+
D/UsbDeviceManager(  942): [USBNET] bCheckSuppFunc: cdc_network
D/UsbnetService(  942): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  942): BroadcastReceiver::onReceive-
E/WifiStateMachine(  942): handleMessage: E msg.what=131101
E/WifiStateMachine(  942): processMsg: SupplicantStoppingState
E/WifiStateMachine(  942):  SupplicantStoppingState !CMD_TETHER_STATE_CHANGE 0 0
I/QuickSettingWifi( 1216): receive.wifiState:WIFI_STATE_DISABLING setEnable:false
D/WifiService(  942): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
E/WifiStateMachine(  942): processMsg: DefaultState
I/CheckinTask( 4477): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
E/WifiStateMachine(  942):  DefaultState !CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  942): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  942): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  942): handleMessage: X
D/BluetoothPan( 5346): BluetoothPan()
D/WISPrService( 5346): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/BluetoothManagerService(  942): registerStateChangeCallback+
D/BluetoothManagerService(  942): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/PMS     (  942): releaseWL(e6a32d3): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
V/NetworkPolicy(  942): updateNetworkEnabledLocked()
D/BluetoothManagerService(  942): Registered receivers: 10
V/NetworkPolicy(  942): updateNotificationsLocked()
D/MdService( 5029): [4a3.] v648303190-6.1.860197 onStartCommand(dying) flag:0, id:2, failed(resend)
D/BluetoothMap( 5346): Create BluetoothMap proxy object
I/RemoteViews( 1216): reapply : com.google.android.gms 3 40
D/BluetoothManagerService(  942): registerStateChangeCallback+
D/BluetoothManagerService(  942): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  942): Registered receivers: 11
E/BluetoothMap( 5346): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/WifiService(  942): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
D/BluetoothManagerService(  942): registerStateChangeCallback+
D/BluetoothManagerService(  942): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/HtcBtWidget_BTWidgetProvider( 5413): onBTStateChanged() for widget: 
D/BluetoothManagerService(  942): Registered receivers: 12
D/BluetoothSap( 5346): BluetoothSap() call bindService
D/DotMatrix( 1327): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/HtcBtWidget_BTWidgetProvider( 5413): updateWidget(context) for widget: 
D/DotMatrix( 1327): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/ContextImpl( 5346): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1888 android.content.ContextWrapper.bindService:538 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1423 
,D/WifiService(  942): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
,D/BluetoothPbap( 5346): BluetoothPbap()
,D/BluetoothManagerService(  942): registerStateChangeCallback+
D/BluetoothManagerService(  942): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK,
D/BluetoothManagerService(  942): Registered receivers: 13
,I/CheckinService( 4477): Checking schedule, now: 1448460714571 next: 1448997546525,
I/CheckinService( 4477): active receiver: disabled
I/PackageManager(  942):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4477, uid=10024, userID:0
D/BluetoothFtpService( 3112): ACTION_STATE_CHANGED: state: 13mHasStarted: true
D/WifiService(  942): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800,
E/BluetoothFtpService:RfcommSocketAcceptThread( 3112): Shutdown
,I/bt-btif ( 3112): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 3112): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterService( 3112): mProfilesStarted : true supportedProfileServices.length : 6
,I/GCoreNlp( 1892): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocalBluetoothProfileManager( 5346): LocalBluetoothProfileManager construction complete
,D/BluetoothMasReceiver( 3112): Bluetooth STATE CHANGED to 13
,D/CustomizationManager( 5370):  Read ACC file spent 0.052 (s)
D/WifiService(  942): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
D/HeadsetService( 3112): Received stop request...Stopping profile...
D/CIDMapFileReader( 5370): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5370): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5370): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5370): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5370): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5370): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5370): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5370): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 5370): Parsing tag category name = system
I/CustomizationCIDLoader( 5370): Parsing tag category name = application
I/CustomizationCIDLoader( 5370): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5370): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5370): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5370): Parsing tag category name = Settings
I/CustomizationCIDLoader( 5370): Parsing tag category name = ACC,
D/PMS     (  942): releaseWL(7cd027a): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
I/CustomizationCIDLoader( 5370): add string-array item, value = 42507
D/MdScPhnSt( 5029): [31e.1.]  listen tmrbb8
I/CustomizationCIDLoader( 5370): add string-array item, value = 21902
I/CustomizationCIDLoader( 5370): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 5370): add string-array item, value = 23420
I/CustomizationCIDLoader( 5370): add string-array item, value = 22299
I/CustomizationCIDLoader( 5370): add string-array item, value = 24002
I/CustomizationCIDLoader( 5370): add string-array item, value = 23210
I/CustomizationCIDLoader( 5370): add string-array item, value = 23205
I/CustomizationCIDLoader( 5370): add string-array item, value = 23806
I/CustomizationCIDLoader( 5370): add string-array item, value = 23430
I/CustomizationCIDLoader( 5370): add string-array item, value = 23408
I/CustomizationCIDLoader( 5370): add string-array item, value = 27205
I/CustomizationCIDLoader( 5370): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 5370): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 5370): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 5370): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 5370): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 5370): add string-array item, value = 24002:D:0:0
,I/CustomizationCIDLoader( 5370): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 5370): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 5370): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 5370): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 5370): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 5370): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 5370):  Read CID file spent 0.105 (s)
D/CustomizationManager( 5370):  All configurations done spent 0.105 (s)
,D/DockEventReceiver( 5346): finishStartingService: stopping service
D/BluetoothInputDevice( 5346): Proxy object connected
,D/WISPrService( 5346): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5346): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/HidProfile( 5346): Bluetooth service connected
,D/BluetoothAdapterService( 3112): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a881622
D/WifiService(  942): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
D/HeadsetStateMachine( 3112): Exit Disconnected: -1
D/PMS     (  942): releaseWL(315e1cc8): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
D/BluetoothAdapterState( 3112): Stopping profile services that were post enabled
D/WifiService(  942): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
D/TodoTaskshortcut( 5372): update TASK shortcut>
D/BluetoothHeadset(  942): Proxy object disconnected
,D/BluetoothHeadset( 1216): Proxy object disconnected
I/QuickSettingMiniLite( 1216): btListener.disconnect:HEADSET
D/BluetoothAdapter( 5346): 227334053: getState(). Returning 13
D/BluetoothPan( 5346): BluetoothPAN Proxy object connected
D/PanProfile( 5346): Bluetooth service connected
D/BluetoothHeadset( 3808): Proxy object disconnected
D/NGFService( 3808): BluetoothHeadset onServiceDisconnected: main
D/SapServerProfile( 5346): Bluetooth service connected
D/A2dpService( 3112): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3112): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a881622
D/A2dpStateMachine( 3112): Exit Disconnected: -1
D/BluetoothA2dp(  942): Proxy object disconnected
D/HidService( 3112): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3112): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a881622
D/BluetoothA2dp( 3808): Proxy object disconnected
D/BluetoothInputDevice( 5346): Proxy object disconnected
D/HidProfile( 5346): Bluetooth service disconnected
D/NGFService( 3808): BluetoothA2dp onServiceDisconnected: main
V/BluetoothSapReceiver( 3112): SapReceiver onReceive 
V/BluetoothSapReceiver( 3112): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3112):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 3112): startService = false
D/HealthService( 3112): Received stop request...Stopping profile...
,E/WifiTrafficPoller(  942): TRAFFIC_STATS_POLL false Token 15 num clients 8
,D/BluetoothAdapterService( 3112): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a881622
,W/BluetoothHeadset( 1216): Proxy not attached to service,
I/QuickSettingMiniLite( 1216): updateLiteState:no connect device!
,E/wpa_supplicant( 1326): wlan0: BLACKLIST CLEAR ,
D/wpa_supplicant( 1326): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush
,D/wpa_supplicant( 1326): wlan0: BSS: Remove id 1 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700' due to wpa_bss_flush
D/wpa_supplicant( 1326): wlan0: Cancelling delayed sched scan
,D/wpa_supplicant( 1326): wlan0: Cancelling scan request
D/wpa_supplicant( 1326): wlan0: Cancelling authentication timeout
E/wpa_supplicant( 1326): wlan0: BLACKLIST REMOVE 00:00:00:00:00:00
D/WifiMonitor(  942): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  942): WifiMonitor:wlan0 cnt=26 dispatchEvent: BLACKLIST CLEAR ,
D/WifiMonitor(  942): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  942): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  942): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:48]
E/WifiMonitor(  942): WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:48
D/WifiMonitor(  942): Event [IFNAME=wlan0 BLACKLIST REMOVE 00:00:00:00:00:00],
E/WifiMonitor(  942): WifiMonitor:wlan0 cnt=29 dispatchEvent: BLACKLIST REMOVE 00:00:00:00:00:00
,D/wpa_supplicant( 1326): Remove interface wlan0 from radio phy0
,D/PanService( 3112): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 3112): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a881622,
D/AuthorizationBluetoothService( 1813): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/WifiService(  942): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
D/BtGatt.DebugUtils( 3112): handleDebugAction() action=null
,D/BtGatt.GattService( 3112): Received stop request...Stopping profile...
D/BtGatt.GattService( 3112): stop()
D/BtGatt.AdvertiseManager( 3112): advertise clients cleared
D/WifiService(  942): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
D/BluetoothPan( 5346): BluetoothPAN Proxy object disconnected
D/PanProfile( 5346): Bluetooth service disconnected
,D/BluetoothAdapterService( 3112): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a881622
D/LocationProviderProxy(  942): applying state to connected service
,D/PMS     (  942): acquireWL(21d485ed): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1892 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  942): releaseWL(21d485ed): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/WifiService(  942): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
,V/GmsNetworkLocationProvi( 1892): DISABLE
,W/BluetoothHeadsetServiceJni( 3112): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3112): Cleaning up Bluetooth Handsfree callback object
D/wpa_supplicant( 1326): nl80211: Remove monitor interface: refcount=0
D/wpa_supplicant( 1326): netlink: Operstate: ifindex=29 linkmode=0 (kernel-control), operstate=6 (IF_OPER_UP)
,W/BluetoothHidServiceJni( 3112): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 3112): Cleaning up Bluetooth GID callback object
D/LocationProviderProxy(  942): applying state to connected service
,D/WifiService(  942): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
D/PMS     (  942): acquireWL(2a996c22): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1892 10024 WorkSource{10024 com.google.android.gms}
W/BluetoothHealthServiceJni( 3112): Cleaning up Bluetooth Health Interface...,
W/BluetoothHealthServiceJni( 3112): Cleaning up Bluetooth Health object
D/PMS     (  942): releaseWL(2a996c22): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
W/BluetoothPanServiceJni( 3112): Cleaning up Bluetooth PAN Interface...
,D/WifiService(  942): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
W/BluetoothPanServiceJni( 3112): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterState( 3112): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3112): Setting state to 10
I/BluetoothAdapterState( 3112): Bluetooth adapter state changed: 13-> 10
D/PMS     (  942): acquireWL(269196b3): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1892 10024 WorkSource{10024 com.google.android.gms}
,D/BluetoothManagerService(  942): +onBluetoothStateChange prev=13 new=10
D/BluetoothManagerService(  942): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  942): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  942): Broadcasting onBluetoothStateChange(false) to 13 receivers.
I/BluetoothAdapterState( 3112): Entering OffState
,D/PackageManager(  942): deletePackageAsUser: pkg=com.example.hello, pid=5370, uid=2000 userid=0
,D/PMS     (  942): acquireWL(959e470): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 5372 10069 null
D/BluetoothHeadset( 1543): Proxy object disconnected
D/BluetoothHeadset( 1543): Proxy object disconnected
D/BluetoothPhoneService( 1543): BluetoothHeadset onServiceDisconnected
,D/BluetoothHeadset( 1543): Proxy object disconnected
D/BluetoothHeadset( 1216): onBluetoothStateChange: up=false
D/PMS     (  942): acquireWL(3d8093e9): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1892 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  942): releaseWL(269196b3): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  942): acquireWL(2c06286e): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 5372 10069 null
D/BluetoothMap( 5346): onBluetoothStateChange: up=false
,E/BluetoothMap( 5346): 
E/BluetoothMap( 5346): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothMap$2@22464bd2
E/BluetoothMap( 5346): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1135)
E/BluetoothMap( 5346): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1940)
E/BluetoothMap( 5346): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
E/BluetoothMap( 5346): 	at android.bluetooth.BluetoothMap$1.onBluetoothStateChange(BluetoothMap.java:64)
E/BluetoothMap( 5346): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothMap( 5346): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothHeadset( 3808): onBluetoothStateChange: up=false
,D/Process (  942): killProcessQuiet, pid=4827
I/ActivityManager(  942): Killing 4827:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/PMS     (  942): releaseWL(3d8093e9): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/wpa_supplicant( 1326): nl80211: Set mode ifindex 29 iftype 2 (STATION)
D/wpa_supplicant( 1326): nl80211: Unsubscribe mgmt frames handle 0x888888dd03818989 (mode change),
I/wpa_supplicant( 1326): htc_wext_command_deinit +
I/wpa_supplicant( 1326): htc_wext_command_deinit -
I/wpa_supplicant( 1326): wlan0: CTRL-EVENT-TERMINATING 
D/wpa_supplicant( 1326): Control interface directory not empty - leaving it behind
D/wpa_supplicant( 1326): p2p0: Removing interface p2p0
D/wpa_supplicant( 1326): p2p0: Request to deauthenticate - bssid=00:00:00:00:00:00 pending_bssid=00:00:00:00:00:00 reason=3 state=DISCONNECTED
D/wpa_supplicant( 1326): TDLS: Tear down peers
D/wpa_supplicant( 1326): p2p0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1326): nl80211: Set p2p0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1326): netlink: Operstate: ifindex=30 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
,D/wpa_supplicant( 1326): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1326): EAPOL: External notification - portValid=0
D/WifiMonitor(  942): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
E/WifiMonitor(  942): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-TERMINATING 
D/Tethering(  942): interfaceLinkStateChanged wlan0, false
D/Tethering(  942): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  942): WiFiDisplay: getWifidisplayApEnabled=false
D/WifiMonitor(  942): Disconnecting from the supplicant, no more events
E/WifiStateMachine(  942): handleMessage: E msg.what=147458
,E/WifiStateMachine(  942): processMsg: SupplicantStoppingState
E/WifiStateMachine(  942):  SupplicantStoppingState !SUP_DISCONNECTION_EVENT 30 0
E/WifiStateMachine(  942): Supplicant connection lost
,W/PackageSettings(  942): Skipping PackageSetting{14415915 com.test.thalitest/10366} due to missing metadata,
,I/ActivityManager(  942): Recipient 4827,
,D/BluetoothSap( 5346): onBluetoothStateChange on: false
I/ActivityManager(  942): Force stopping com.example.hello appid=10373 user=-1: uninstall pkg
V/BluetoothSapService( 3112): cleanup: mService: com.android.bluetooth.sap.BluetoothSapService@2450b87e
I/ActivityManager(  942): Killing 4780:com.example.hello/u0a373 (adj 0): stop com.example.hello
D/Process (  942): killProcessQuiet, pid=4780
,D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
,D/PMS     (  942): acquireWL(1204eb0f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1813 10024 WorkSource{10024 com.google.android.gms},
,I/HtcModeClient( 3240): handler message = 4011
,E/HtcModeClient( 3240): Check connection and retry 5 times.
,I/ActivityManager(  942): Recipient 4780
I/WindowState(  942): WIN DEATH: Window{1f49095f u0 com.example.hello/com.example.hello.MainActivity}
E/libprocessgroup(  942): failed to kill 1 processes for processgroup 4780
,E/InputEventReceiver( 1397): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{27c55d2d uid 10373 pid 4780} (c)'
D/WifiService(  942): Client connection lost with reason: 4
,W/ActivityManager(  942): Force removing ActivityRecord{27754a8e u0 com.example.hello/.MainActivity t8}: app died, no saved state
,I/ActivityManager(  942): Force stopping com.example.hello appid=10373 user=0: pkg removed
,D/BluetoothA2dp(  942): onBluetoothStateChange: up=false
D/DotMatrix( 1327): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/PMS     (  942): releaseWL(959e470): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/DotMatrix( 1327): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1327): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
,D/PMS     (  942): acquireWL(35752d07): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1892 10024 WorkSource{10024 com.google.android.gms}
W/GeofencerStateMachine( 1892): Ignoring removeGeofence because network location is disabled.
,D/PMS     (  942): releaseWL(35752d07): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/AccTypeManager( 1762): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
D/MtpReceiver( 3930): [MTP][handleUsbStateAsync]+
D/MtpReceiver( 3930): [MTP][handleUsbStateAsync]1:1-
D/MtpReceiver( 3930): [MTP][handleUsbState]+
,I/FeedHostManager( 1586): [onResume]
I/FeedProviderManager( 1586): onResume
I/SocialFeedProvider( 1586): +onResume
I/SocialFeedProvider( 1586): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1586): -onResume
,E/TodoTaskNotifyService( 5372): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
,W/System.err( 5372): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
W/System.err( 5372): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 5372): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 5372): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 5372): 	at android.os.Looper.loop(Looper.java:155)
W/System.err( 5372): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/SystemReader(  942): Cannot find grip_rejection_width, use default value instead,
,W/PackageManager(  942): Unable to load service info ResolveInfo{14ad92a3 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  942): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  942): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  942): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  942): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  942): 	,at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
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
,D/MdProvGlob( 5055): add item 101 (1:g3d9) for 15:android.intent.action.ANY_DATA_STATE
D/PMS     (  942): releaseWL(2c06286e): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ConnectivityHelper( 1586): [getCurrentConnectionType] no network connection
D/AccTypeManager( 1762): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/BluetoothHeadset( 1543): onBluetoothStateChange: up=false
D/MdScDataSum( 5029): [31e.1.] summary 118:p2 ignore
,D/PMS     (  942): releaseWL(1204eb0f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/wpa_ctrl(  942): [wpa_ctrl_close] ctrl=0x5598beec10
,I/wpa_ctrl(  942): [wpa_ctrl_close] ctrl=0x5598beed50
,I/InputMethodManagerService(  942): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/ActivityManager(  942): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=5456 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a
,D/AccTypeManager( 1762): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/JobSchedulerService(  942): Receieved: android.intent.action.PACKAGE_REMOVED
E/WifiStateMachine(  942): setWifiState: disabled
D/BluetoothHeadset( 1543): onBluetoothStateChange: up=false
,W/ActivityManager(  942): Spurious death for ProcessRecord{36a95cc4 4780:com.example.hello/u0a373}, curProc for 4780: null
D/WifiStateMachine(  942): Enter handleNetworkDisconnect
D/MtpReceiver( 3930): [MTP][scanExternalVolumeIfNeed] scan external volume
D/BluetoothPan( 5346): onBluetoothStateChange on: false
W/NotifyReceiver( 5372): stopSelfResult true
,I/IntentController( 1216): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
,D/WIFI_ICON( 1216): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/TaskPersister(  942): removeObsoleteFile: deleting file=8_task.xml
,D/BluetoothHeadset(  942): onBluetoothStateChange: up=false
E/WifiStateMachine(  942): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - handleNetworkDisconnect - access$12300 - processMessage
W/Settings( 1892): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 4574): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MtpReceiver( 3930): [MTP][handleUsbState]-
D/MtpReceiver( 3930): [MTP][handleMessage]-
D/StatusBarManagerService(  942): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  942): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  942): hiding MENU key
E/WifiStateMachine(  942): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  942): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  942): Exit handleNetworkDisconnect
E/WifiStateMachine(  942): [MLHD] Error! unhandled message 6 { when=-467ms what=147458 arg1=30 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  942): transitionTo: destState=InitialState
E/WifiStateMachine(  942): handleMessage: new destination call exit/enter
E/WifiStateMachine(  942): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  942): invokeExitMethods: SupplicantStoppingState
E/WifiStateMachine(  942): moveTempStackToStateStack: i=0,j=1
E/WifiStateMachine(  942): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=InitialState
E/WifiStateMachine(  942): invokeEnterMethods: InitialState
D/PMS     (  942): acquireWL(3896ae73): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 942 1000 null
D/BluetoothA2dp( 3808): onBluetoothStateChange: up=false
,E/WifiTrafficPoller(  942): ENABLE_TRAFFIC_STATS_POLL false Token 15
E/ExternalAccountType( 1762): Unsupported attribute readOnly
D/WIFI_ICON( 1216): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,I/IntentController( 1216): receive(android.net.wifi.STATE_CHANGE,1,false),
,D/BluetoothPbap( 5346): onBluetoothStateChange: up=false
D/MtpService( 3930): updating state; isCurrentUser=true, mMtpLocked=false
,D/FindExtension( 1586): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
D/PhoneApp( 1543): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,I/ThreadedRenderer( 1586): Defer allocateBuffers to drawing time
,W/InputMethodManagerService(  942): Got RemoteException sending setActive(false) notification to pid 4780 uid 10373
I/PhoneStatusBar( 1216): setImeWindowStatus(false,false)
D/StatusBarManagerService(  942): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  942): Enable input method client, pid=1586
,I/QuickSettingWifi( 1216): receive.wifiState:WIFI_STATE_DISABLED setEnable:true,
,E/Parcel  ( 1558): Reading a NULL string not supported here.,
,I/QuickSettingWifi( 1216): receive.wifiConnect:false wifiAPname:null elapse:1,
,D/StatusBarManagerService(  942): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  942): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  942): hiding MENU key
,I/art     (  942): Explicit concurrent mark sweep GC freed 48137(2MB) AllocSpace objects, 4(144KB) LOS objects, 33% free, 17MB/25MB, paused 2.348ms total 226.654ms
I/art     (  942): WaitForGcToComplete blocked for 114.283ms for cause Explicit
,W/asset   (  942): Copying FileAsset 0x5598d784e0 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,I/Prism.ItemManager( 1586): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
I/Prism.ItemManager( 1586): loadItems() com.htc.launcher.pageview.WidgetManager@3f6b25d4 +
I/Prism.WidgetManager( 1586): onLoadItems() +
,E/WifiTrafficPoller(  942): TRAFFIC_STATS_POLL false Token 16 num clients 7
,I/Prism.ItemManager( 5234): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 5234): loadItems() com.htc.launcher.pageview.WidgetManager@1e31ef07 +
I/Prism.WidgetManager( 5234): onLoadItems() +
,W/ResourcesManager( 1586): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,W/ResourcesManager( 5234): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/art     (  942): Explicit concurrent mark sweep GC freed 6623(413KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/25MB, paused 1.690ms total 168.455ms
,D/BluetoothHeadset( 1543): onBluetoothStateChange: up=false
D/PMS     (  942): acquireWL(35cbdf65): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 4477 10024 null
,D/BluetoothInputDevice( 5346): onBluetoothStateChange: up=false
,D/SyncApplication( 5456): Loading default preferences
D/WISPrService( 5346): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5346): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/MtpDatabase( 3930): TotalSize=1886532,MediaCacheLimit=6000
D/BluetoothManagerService(  942): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  942): Broadcasting onBluetoothServiceDown() to 9 receivers.
,D/BluetoothAdapter( 3112): onBluetoothServiceDown: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@3d35726e
D/BluetoothAdapter( 3112): onBluetoothServiceDown: done
,D/BluetoothAdapter( 1216): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@2efa39f1
D/BluetoothAdapter( 1216): onBluetoothServiceDown: done
D/MtpService( 3930): [isMtpConnected] connected: true
D/BluetoothAdapter( 1892): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@19549348
,D/BluetoothAdapter( 1892): onBluetoothServiceDown: done
D/BluetoothAdapter(  942): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@38dc9b4f
D/BluetoothAdapter(  942): onBluetoothServiceDown: done
D/BluetoothAdapter( 1558): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@38811834
D/BluetoothAdapter( 1558): onBluetoothServiceDown: done
D/BluetoothAdapter( 1543): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@353750fc
D/BluetoothAdapter( 1543): onBluetoothServiceDown: done
,D/BluetoothAdapter( 5346): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@7effb59
D/BluetoothAdapter( 5346): onBluetoothServiceDown: done
,D/BluetoothAdapter( 2339): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@105f08be
D/BluetoothAdapter( 2339): onBluetoothServiceDown: done
,D/BluetoothAdapter( 3808): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@397474a3
D/BluetoothAdapter( 3808): onBluetoothServiceDown: done
D/BluetoothManagerService(  942): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@38dc9b4f mBinding = false
,W/Resources( 5456): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
D/BluetoothManagerService(  942): Sending unbind request.
D/BluetoothManagerService(  942): Bluetooth State Change Intent: 13 -> 10
,I/IntentController( 1216): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,D/NGFService( 3808): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
D/NGFService( 3808): Bluetooth Adapter: OFF
D/NfcHandover( 1558): onReceive: mBound=false, BTByNfc=false->false, BTHConnected=false->false
,D/LocalBluetoothProfileManager( 5346): setBluetoothStateOff
,W/BluetoothEventManager( 5346): unregister mProfileBroadcastReceiver fail
,I/bt-btif ( 3112): HAL bt_hal_cbacks->thread_evt_cb
,I/art     ( 3112): System.exit called, status: 0
,D/TetherPref( 5346): persistRestoreBluetoothState false
,D/MdProvGlob( 5055): remove item 101 (p2d2in344) for 15:android.intent.action.ANY_DATA_STATE
,D/MdScDataSum( 5029): [31e.1.4.] summary 118:p1 ignore
,D/MdProvGlob( 5055): remove item 101 (p2d2in28) for 15:android.intent.action.ANY_DATA_STATE
D/BluetoothAdapter( 1216): 552368067: getState() :  mService = null. Returning STATE_OFF
D/WifiService(  942): New client listening to asynchronous messages
I/QuickSettingBluetooth( 1216): receive.ACTION_STATE_CHANGE:STATE_OFF/(false,false)
E/WifiTrafficPoller(  942): ADD_CLIENT: 8
,I/iu.UploadsManager( 4477): End new media; added: 0, uploading: 0, time: 110 ms
,D/PMS     (  942): releaseWL(35cbdf65): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 null
,D/MdProvGlob( 5055): remove item 101 (p2d1in22) for 15:android.intent.action.ANY_DATA_STATE
,I/ActivityManager(  942): Recipient 3112
,I/ActivityManager(  942): Process com.android.bluetooth (pid 3112) has died
,W/ActivityManager(  942): Scheduling restart of crashed service com.android.bluetooth/.sap.BluetoothSapService in 1000ms
W/ActivityManager(  942): Scheduling restart of crashed service com.android.bluetooth/.map.BluetoothMasService in 1000ms
,E/MediaScannerService( 3930): [onStartCommand] --- Should not be here, redirect request. ----
I/BroadcastQueue(  942): Schedule to resend BroadcastRecord{3c884648 u-1 android.bluetooth.adapter.action.STATE_CHANGED callingPid=942 callingUid=1000} for ResolveInfo{2f200ce1 com.android.bluetooth/.pbap.BluetoothPbapReceiver m=0x108000} of com.android.bluetooth
E/MediaScannerService( 3930): [handleMessage] --- Should not be here, ignore request. ----
,D/SyncApplication( 5456): Overriding preferences with custom values
,I/ActivityManager(  942): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=5490 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3008} abi=armeabi-v7a,
,D/MdProvGlob( 5055): remove item 101 (p2in18) for 15:android.intent.action.ANY_DATA_STATE,
D/SyncApplication( 5456): Updating preferences succeeded
,E/SyncApplication( 5456): Application created.
,D/MdProvGlob( 5055): remove item 101 (p2in24) for 15:android.intent.action.ANY_DATA_STATE
,I/CalendarDefines( 5456): getNewCalendarAuthority()...
W/ResourcesManager( 1586): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/PackageManager(  942):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=5456, uid=10005, userID:0
W/PackageManager(  942): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
,I/PackageManager(  942):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=5456, uid=10005, userID:0
W/PackageManager(  942): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/SyncApplication( 5456): enableAppOperation()+
W/VolumeInfo( 5456): Unable to read mount points
W/VolumeInfo( 5456): java.io.FileNotFoundException: /etc/vold.fstab: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 5456): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/VolumeInfo( 5456): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/VolumeInfo( 5456): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/VolumeInfo( 5456): 	at java.io.FileReader.<init>(FileReader.java:66)
W/VolumeInfo( 5456): 	at com.nero.android.common.VolumeInfo.getVolumeMountPoints(VolumeInfo.java:194)
W/VolumeInfo( 5456): 	at com.nero.android.common.VolumeInfo.getVolumes(VolumeInfo.java:153)
W/VolumeInfo( 5456): 	at com.nero.android.common.VolumeInfo.initializeVolumeIDs(VolumeInfo.java:474)
W/VolumeInfo( 5456): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:51)
W/VolumeInfo( 5456): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:1)
W/VolumeInfo( 5456): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/VolumeInfo( 5456): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/VolumeInfo( 5456): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/VolumeInfo( 5456): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/VolumeInfo( 5456): 	at java.lang.Thread.run(Thread.java:818)
W/VolumeInfo( 5456): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 5456): 	at libcore.io.Posix.open(Native Method)
W/VolumeInfo( 5456): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/VolumeInfo( 5456): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/VolumeInfo( 5456): 	... 13 more
V/VolumeInfo( 5456): Found 0 mount point(s)
V/VolumeInfo( 5456): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
D/SyncApplication( 5456): enableAppOperation()-
,D/MdProvGlob( 5055): remove item 101 (p2in8) for 15:android.intent.action.ANY_DATA_STATE
,D/HTCUtilities( 5456): isNeorSinged() + 
,D/HTCUtilities( 5456): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>,
,W/ResourcesManager( 5490): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/VolumeInfo( 5456): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,D/HTCUtilities( 5456): isNeorSinged() return false
,D/CDMountReceiver( 5456): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
D/CDMountReceiver( 5456): USB connected to PC
,D/MdProvGlob( 5055): remove item 101 (p2d2in32) for 15:android.intent.action.ANY_DATA_STATE
,D/VolumeInfo( 5456): Read the volume-id from the sd card: {9B5E872B-8520-47C6-8BD3-3081C2E38355}
W/VolumeInfo( 5456): Can not create volume ID for unmounted volume null
,D/MdProvGlob( 5055): remove item 101 (p2in12) for 15:android.intent.action.ANY_DATA_STATE,
,D/MdProvGlob( 5055): remove item 101 (p2d1in10) for 15:android.intent.action.ANY_DATA_STATE
,W/ResourcesManager( 5234): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,D/MdProvGlob( 5055): remove item 101 (p2in14) for 15:android.intent.action.ANY_DATA_STATE
,D/FOTAReceiver( 5456): onReceive() enter ,
D/FOTAReceiver( 5456): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,E/MediaScannerServiceEx( 3930): [getStorageMaskIdFromPath] path is null
D/MediaScannerServiceEx( 3930): [ServiceHandler][handleMessage] , action: null, Id: 0, path: /storage/emulated/0
D/AdapterServiceConfig( 5490): Adding HeadsetService
D/MdScDataSum( 5029): [31e.19.] summary 118:p2 ignore
D/AdapterServiceConfig( 5490): Adding A2dpService
D/AdapterServiceConfig( 5490): Adding HidService
D/AdapterServiceConfig( 5490): Adding HealthService
D/AdapterServiceConfig( 5490): Adding PanService
D/AdapterServiceConfig( 5490): Adding GattService
V/BluetoothPbapReceiver( 5490): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 5490): ***********state = 10
W/OpenGLRenderer( 1586): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
E/BluetoothMasService( 5490): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
D/TetherSettings( 5346): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5346): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5346): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5346): Cust_ConnectToPC   : spcsc>false
D/        ( 5346): Cust_ConnectToPC   : IPT>true
D/        ( 5346): Cust_ConnectToPC   : Singel_USB>false
,D/MediaScannerServiceEx( 3930): [handleExternalVolume] ext storage
D/MediaProviderUtils( 3930): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3930): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3930): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3930): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
D/MediaScannerServiceEx( 3930): [AliveExtStorageRows]+65537, 11223344
,W/Settings( 5346): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/BluetoothMasService( 5490): Add permission for SmsProvider.
D/MediaProvider( 3930): [update][8]#0#
D/MediaProvider( 3930): [update][4]#0#
,E/SmartNS_Utility( 5346): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5346): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5346): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
D/SmartNS_Utility( 5346): usb_cable_connect = 1
,D/SmartNS_Utility( 5346): usb_denied = 0
,W/System.err(  942): java.lang.Throwable: stack dump
D/BluetoothManagerService(  942): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  942): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1081a63:true
W/System.err(  942): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  942): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  942): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
,W/System.err(  942): 	at android.os.Binder.execTransact(Binder.java:454)
D/Tethering(  942): interfaceRemoved wlan0
E/Tethering(  942): attempting to remove unknown iface (wlan0), ignoring
V/BluetoothMasService( 5490): Starting MAS instances
D/BluetoothAdapter( 5490): 19960241: getState() :  mService = null. Returning STATE_OFF
,I/MailMessageReceiver( 5490): reg:com.android.bluetooth.btservice.AdapterApp@2df82696 with com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@1c6e5217
,I/SmartNS_NSReceiver( 5346): locked:falsesecurity:falseisLocked:false
D/SmartNS_NSReceiver( 5346): USB = true hasTethered = false isNSOpening: false
,I/MailManager( 5490): MailManager contruct! com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@1c6e5217
V/EmailUtils( 5490): Manager Instance is not NULL
,D/PMS     (  942): acquireWL(1557f9bf): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 5346 1000 null
,W/ContextImpl( 5346): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
,D/HtcBtWidget_BTWidgetProvider( 5413): onBTStateChanged() for widget: 
,D/MediaProvider( 3930): [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
D/MtpService( 3930): [sendStorageAdded] Already send to MTP: /storage/emulated/0
D/HtcBtWidget_BTWidgetProvider( 5413): updateWidget(context) for widget: 
D/MediaProvider( 3930): [update][14]#1#
,D/MediaScannerServiceEx( 3930): [AliveExtStorageRows]-0, 0
,D/PMS     (  942): acquireWL(d47b88c): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3930 10017 null
,I/ActivityManager(  942): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=5519 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a,
,D/PMS     (  942): releaseWL(1557f9bf): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null,
D/PMS     (  942): acquireWL(be2ffea): PARTIAL_WAKE_LOCK  StartingDockService 0x1 5346 1000 null
,D/DockEventReceiver( 5346): finishStartingService: stopping service
,I/PSReceiver( 5346): onReceive:com.htc.intent.action.USB_CONNECT2PC
,W/ContextImpl( 5346): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2712 
D/Process (  942): killProcessQuiet, pid=4864,
I/ActivityManager(  942): Killing 4864:com.htc.club/u0a181 (adj 15): empty #17
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,D/MediaScanner( 3930): =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1,
,W/asset   ( 1586): Copying FileAsset 0x5598ffc350 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
D/Tethering(  942): interfaceLinkStateChanged p2p0, false
D/Tethering(  942): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  942): WiFiDisplay: getWifidisplayApEnabled=false
,W/asset   ( 5234): Copying FileAsset 0x5598b40a60 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,D/Messaging( 5321): supportCMAS(SIE)/init? false/true,
,D/MmsConfig( 5321): networkCode: 
D/MmsConfig( 5321): SIE smsPri: null
D/MmsConfig( 5321): networkCode: ,
E/Prism.WidgetManager( 1586): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1586): onLoadItems() -
I/Prism.ItemManager( 1586): loadItems() com.htc.launcher.pageview.WidgetManager@3f6b25d4 -
,I/Prism.ItemManager( 1586): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1586): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,D/Messaging( 5321): mNeedToUpdateDate2 start
,D/ReportIndicatorCache( 5321): startAsyncQueryReports ---
,D/MmsAsyncWorkHandler( 5321): 
D/MmsAsyncWorkHandler( 5321): HM tk = 20001
D/ReportIndicatorCache( 5321): MSG_QUERY_REPORTS >>
,I/ActivityManager(  942): Recipient 4864
,D/DraftCache( 5321): [DraftCache/1] DraftCache.constructor
D/DraftCache( 5321): [DraftCache/1] refresh
I/Messaging( 5321): mccmnc> 
,D/MmsConfig( 5321): networkCode: 
,D/Messaging( 5321): ViewCache CreatePreloadOnlyConversationList,
,D/MessageCustFlag( 5321): sense_version=6.0
,D/Jerry   ( 5321): start to preload cursor >>>>>>>
,D/Tethering(  942): interfaceRemoved p2p0
,E/Tethering(  942): attempting to remove unknown iface (p2p0), ignoring
,I/Prism.WidgetManager( 5234): onLoadItems() -
,I/Prism.ItemManager( 5234): loadItems() com.htc.launcher.pageview.WidgetManager@1e31ef07 -
I/Prism.ItemManager( 5234): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 5234): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,D/PMS     (  942): releaseWL(be2ffea): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
,I/SmartNS_PSService( 5346): onReceive:com.htc.intent.action.USB_CONNECT2PC
,W/Settings( 5346): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 5346):  defaultType:0
I/SmartNS_PSService( 5346): fail notificaiton:false
,D/SmartNS_Utility( 5346): usb_cable_connect = 1
D/SmartNS_Utility( 5346): usb_denied = 0
I/SmartNS_PSService( 5346): usb notificaiton:true,
,I/ActivityManager(  942): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=5548 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
E/WifiStateMachine(  942): WiFiDisplay: getWifidisplayApEnabled=false
,D/TelephUtils( 1543): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/MmsSmsV2Provider( 1543):  slotId = -1000
D/MmsSmsV2Provider( 1543): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
I/ActionCombine( 5346): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,D/Process (  942): killProcessQuiet, pid=4930
I/ActivityManager(  942): Killing 4930:com.google.android.music:main/u0a159 (adj 15): empty #17
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/SmartNS_Utility( 5346): usb_cable_connect = 1
D/SmartNS_Utility( 5346): usb_denied = 0
I/SmartNS_PSService( 5346): usb notificaiton:true
E/WifiStateMachine(  942): WiFiDisplay: getWifidisplayApEnabled=false
,I/ActivityManager(  942): Recipient 4930,
D/MediaRouterService(  942): Client com.google.android.music (pid 4930): Died!
,D/TelephUtils( 1543): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92,
D/AccFlag ( 1543): sku_id=118,
,D/SmartNS_Utility( 5346): usb_cable_connect = 1
D/DotMatrix( 1327): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/TelephUtils( 1543): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 91
D/SmartNS_Utility( 5346): usb_denied = 0
D/DraftCache( 5321): [DraftCache/121] rebuildCache
D/MmsSmsV2Provider( 1543):  slotId = -1000
D/MmsSmsV2Provider( 1543): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/PhoneStorageUtil( 5321): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 5321): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 5321): createReceiver
,I/RemoteViews( 1216): reapply : com.android.settings 2 36
,I/SmartNS_PSService( 5346): KeyGuard locked:falseKeyGuard is secured:false
D/SmartNS_PSService( 5346): USB Plugged, Set USBPlugged=  truePSenabled:false
D/DotMatrix( 1327): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/TelephUtils( 1543): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/MmsSmsV2Provider( 1543):  slotId = -1000
,I/ActivityManager(  942): Killing 4976:com.htc.bgp/u0a11 (adj 15): empty #17
,D/Process (  942): killProcessQuiet, pid=4976
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/RemoteViews( 1216): reapply : com.android.settings 1 36
,I/ActivityManager(  942): Recipient 4976,
,D/TelephUtils( 1543): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 91,
D/MmsSmsV2Provider( 1543):  slotId = -1000
,D/MmsSmsV2Provider( 1543): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
D/TelephUtils( 1543): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
V/MmsProvider( 1543): Update uri=content://mms, match=0
W/ContextImpl( 5548): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.backupreset.receiver.BackupResetReceiver.onReceive:45 android.app.ActivityThread.handleReceiver:2712 
V/MmsProvider( 1543): selection=st=129 AND m_type!=134
D/Messaging( 5321): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true,
D/Messaging( 5321): ViewCache CreatePreload
D/Messaging( 5321): ViewCache CreatePreloadOnlyMultipleOpsList
D/Messaging( 5321): Reset downloading state: 0
,V/MmsSystemEventReceiver( 5321): TransactionService is going to be woken up.
,D/HtcAdjCursorFactory( 5519): Set CursorWindow size to: 4194304 KB, Tid: 5540
D/TelephUtils( 1543): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/Jerry   ( 1543): URI_DRAFT
,V/TransactionService( 5321): 1-Creating TransactionService
,D/DraftCache( 5321): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 5321): [DraftCache/121] rebuildCache time: 4
D/MmsAsyncWorkHandler( 5321): 
D/MmsAsyncWorkHandler( 5321): HM tk = 20002
,E/SQLiteDatabase( 5519): Failed to open database '/data/user/0/com.htc.android.mail/databases/mail.db'.
E/SQLiteDatabase( 5519): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5519): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5519): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5519): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5519): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5519): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5519): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5519): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5519): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5519): 	,at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5519): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 5519): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5519): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5519): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5519): 	at com.htc.android.mail.kq.a(MailProvider.java:5368)
E/SQLiteDatabase( 5519): 	at com.htc.android.mail.kq.a(MailProvider.java:5433)
E/SQLiteDatabase( 5519): 	at com.htc.android.mail.MailProvider.query(MailProvider.java:2114)
E/SQLiteDatabase( 5519): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 5519): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 5519): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
E/SQLiteDatabase( 5519): 	at android.os.Binder.execTransact(Binder.java:454)
E/SQLiteOpenHelper( 5519): Couldn't open mail.db for writing (will try read-only):
E/SQLiteOpenHelper( 5519): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5519): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5519): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteOpenHelper( 5519): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteOpenHelper( 5519): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5519): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5519): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5519): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteOpenHelper( 5519): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteOpenHelper( 5519): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteOpenHelper( 5519): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteOpenHelper( 5519): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 5519): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5519): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5519): 	at com.htc.android.mail.kq.a(MailProvider.java:5368)
E/SQLiteOpenHelper( 5519): 	at com.htc.android.mail.kq.a(MailProvider.java:5433)
E/SQLiteOpenHelper( 5519): 	at com.htc.android.mail.MailProvider.query(MailProvider.java:2114)
E/SQLiteOpenHelper( 5519): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteOpenHelper( 5519): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteOpenHelper( 5519): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
E/SQLiteOpenHelper( 5519): 	at android.os.Binder.execTransact(Binder.java:454)
D/Cust_MMSMS( 5321): _has_set_default_values_2=true
W/SQLiteOpenHelper( 5519): Opened mail.db in read-only mode
,V/TransactionService( 5321): onStartCommand: 1,
D/MmsSystemEventReceiver( 5321): unRegisterForConnectionStateChanges
D/MsgPreferenceUtils( 5321): def_index: 0
V/TransactionService( 5321): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 5321): Loading previous transactions.,
,I/ActivityManager(  942): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=5576 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,D/MsgPreferenceUtils( 5321): globalIndex = 1
D/TelephUtils( 1543): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
,D/AccFlag ( 1543): device_type: 1
,D/TelephUtils( 1543): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/MmsSmsV2Provider( 1543):  slotId = -1000
D/MmsSmsV2Provider( 1543): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/MsgPreferenceUtils( 5321): phone state: true
D/MsgPreferenceUtils( 5321): sd state: false
D/MsgPreferenceUtils( 5321): vIndex = 0
D/TransactionService( 5321): Force clearing mTransactionList
D/EmailUtils( 5490): ============NULL aList========
V/EmailUtils( 5490): <-getEmailAccountIdList
V/BluetoothMasService( 5490): onCreate: mIsEmailEnabled: true
D/TransactionService( 5321): Force set service start id to 1
V/TransactionService( 5321): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 5321): unRegisterForConnectionStateChanges
,D/TransactionService( 5321): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 5321): Destroying TransactionService
D/Messaging( 5321): mNeedToUpdateDate2: false
,V/TransactionService( 5321): 4-Handling incoming message: { when=-5ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,I/ActivityManager(  942): Killing 5004:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  942): killProcessQuiet, pid=5004
D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/TelephUtils( 1543): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/AccFlag ( 1543): sku_id=118
,I/ActivityManager(  942): Recipient 5004
,D/Process (  942): killProcessQuiet, pid=5079
I/ActivityManager(  942): Killing 5079:com.google.android.apps.magazines/u0a161 (adj 15): empty #17
,D/Process (  942): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/BluetoothMasReceiver( 5490): Bluetooth STATE CHANGED to 10

```
