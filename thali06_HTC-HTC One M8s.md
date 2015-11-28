#### Test 50388019809f971_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
D/Process (  937): killProcessQuiet, pid=4092
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
--------- beginning of system
I/ActivityManager(  937): Killing 4092:com.htc.updater/u0a84 (adj 15): empty #17
D/libc    ( 4596): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
D/libc    ( 4596): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4596): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    ( 4596): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4596): [NET] android_getaddrinfo_proxy+
D/libc    ( 4596): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  415): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    (  415): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  415): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  415): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4596): [NET] android_getaddrinfo_proxy-, success
D/libc    ( 4596): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 4596): [NET] android_getaddrinfofornet-, SUCCESS
I/ActivityManager(  937): Recipient 4092
D/libc    ( 4596): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
D/libc    ( 4596): [NET] android_getaddrinfofornet-, err=8
V/AlarmManager(  937): sending alarm PendingIntent{1038d4b6: PendingIntentRecord{33c635b7 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.hangouts.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=54992, Int=259200000
V/AlarmManager(  937): sending alarm PendingIntent{3846348d: PendingIntentRecord{bf58642 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1448709369397, Int=0
V/AlarmManager(  937): sending alarm PendingIntent{350b022b: PendingIntentRecord{89b3688 android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1448709360776, Int=20000
W/ActivityManager(  937): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/WifiStateMachine(  937): handleMessage: E msg.what=131155
E/WifiStateMachine(  937): processMsg: ConnectedState
E/WifiStateMachine(  937):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2462 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=3.7 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:1305390840] gl hn u24 rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  937): processMsg: L2ConnectedState
E/WifiStateMachine(  937):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2462 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=3.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1305390841] gl hn u24 rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  937):  get link layer stats 0
W/WifiHW  (  937): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1365): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1365): environment dirty rate=25 [12][3][0]
E/WifiStateMachine(  937): fetchRssiLinkSpeedAndFrequencyNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  937): fetchRssiLinkSpeedAndFrequencyNative rssi=-56 linkspeed=72
E/WifiConfigStore(  937): updateConfiguration freq=2462 BSSID=c0:ff:d4:d3:aa:48 RSSI=-56 "NG700"WPA_PSK
E/WifiStateMachine(  937): calculateWifiScore freq=2462 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=6.18 txretriesrate=0.00 rxrate=7.34 userTriggerdPenalty0
E/WifiStateMachine(  937):  good link -> stuck count =0
E/WifiStateMachine(  937):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  937):  isHighRSSI       ---> score=65
D/WifiWatchdogStateMachine(  937): RSSI current: 3 new: -56, 3
E/WifiStateMachine(  937): handleMessage: X
D/WIFI_ICON( 1218): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
I/iu.UploadsManager( 4460): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
I/iu.UploadsManager( 4460): End new media; added: 0, uploading: 0, time: 46 ms
I/Gmail   ( 4678): getAccountsCursor
V/GLSActivity( 1925): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 4678): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ActivityManager(  937): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/PackageManager(  937):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.AttachmentService, state=2, flag=1, pid=4678, uid=10106, userID:0
W/ActivityManager(  937): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
E/Gmail   ( 4678): Error finding the version of the Email provider.....
E/Gmail   ( 4678): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 4678): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 4678): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 4678): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 4678): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4678): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4678): 	at android.os.Looper.loop(Looper.java:155)
E/Gmail   ( 4678): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 4678): We do not support migrating this version of the Email provider.
I/Gmail   ( 4678): Observing account changes for notifications
W/ActivityManager(  937): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/PackageManager(  937):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=4678, uid=10106, userID:0
I/PackageManager(  937):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=4678, uid=10106, userID:0
I/PackageManager(  937):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GoogleMailWidgetProvider, state=2, flag=1, pid=4678, uid=10106, userID:0
I/PackageManager(  937):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GmailWidgetProvider, state=1, flag=1, pid=4678, uid=10106, userID:0
I/PackageManager(  937):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGoogleMail, state=2, flag=1, pid=4678, uid=10106, userID:0
I/PackageManager(  937):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGmail, state=1, flag=1, pid=4678, uid=10106, userID:0
I/ActivityManager(  937): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=4724 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
W/ActivityManager(  937): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/PackageManager(  937):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=4678, uid=10106, userID:0
I/PackageManager(  937):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=4678, uid=10106, userID:0
W/ActivityManager(  937): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/ActivityThread( 4678): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@2f9eb4a6 that was originally bound here
E/ActivityThread( 4678): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@2f9eb4a6 that was originally bound here
E/ActivityThread( 4678): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1183)
E/ActivityThread( 4678): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1077)
E/ActivityThread( 4678): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1906)
E/ActivityThread( 4678): 	at android.app.ContextImpl.bindService(ContextImpl.java:1889)
E/ActivityThread( 4678): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4678): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4678): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4678): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4678): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4678): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4678): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4678): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4678): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4678): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4678): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread( 4678): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager(  937): Unbind failed: could not find connection for android.os.BinderProxy@bfdd766
I/art     (  937): Explicit concurrent mark sweep GC freed 18014(1008KB) AllocSpace objects, 5(100KB) LOS objects, 33% free, 16MB/24MB, paused 1.708ms total 182.952ms
I/Gmail   ( 4678): getAccountsCursor
V/GLSActivity( 1925): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1925): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/SQLiteLog( 4678): (283) recovered 493 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL true Token 11 num clients 5
E/WifiTrafficPoller(  937):  packet count Tx=50 Rx=71
D/WIFI_ICON( 1218): WifiActivity: 3
E/WifiTrafficPoller(  937): notifying of data activity 3
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/Gmail   ( 4678): notifyAccountChanged
I/Gmail   ( 4678): getAccountsCursor
I/Gmail   ( 4678): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1925): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 4678): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
D/PMS     (  937): acquireWL(3bfcfd6d): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 4678 10106 null
I/Gmail   ( 4678): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
D/PMS     (  937): acquireWL(3bfcfd6d): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 4678 10106 null
I/Gmail   ( 4678): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
D/PMS     (  937): acquireWL(3bfcfd6d): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 4678 10106 null
I/Gmail   ( 4678): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
I/PackageManager(  937):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.ComposeActivityGmail, state=1, flag=1, pid=4678, uid=10106, userID:0
I/Gmail   ( 4678): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/Process (  937): killProcessQuiet, pid=4124
I/ActivityManager(  937): Killing 4124:com.htc.android.worldclock/u0a90 (adj 15): empty #17
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/Gmail   ( 4678): calculateUnknownSyncRationalesAndPurgeInBackground: running
E/AndroidHttpClient( 4396): Leak found
E/AndroidHttpClient( 4396): java.lang.IllegalStateException: AndroidHttpClient created and never closed
E/AndroidHttpClient( 4396): 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 4396): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 4396): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 4396): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 4396): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 4396): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 4396): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 4396): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 4396): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 4396): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 4396): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 4396): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 4396): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 4396): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 4396): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 4396): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
I/ActivityManager(  937): Recipient 4124
I/Gmail   ( 4678): master sync=false, engine sync=true
D/LocationManagerService(  937): getProviders()=[passive]
E/cutils-trace( 4753): Error opening trace file: Permission denied (13)
I/Gmail   ( 4678): getAccountsCursor
V/GLSActivity( 1925): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 4678): master sync=false, engine sync=true
I/ActivityManager(  937): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4775 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a
I/art     ( 1925): Explicit concurrent mark sweep GC freed 10931(629KB) AllocSpace objects, 3(252KB) LOS objects, 49% free, 4MB/8MB, paused 1.092ms total 56.773ms
I/PackageManager(  937):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.googlequicksearchbox.SearchActivity, state=1, flag=1, pid=4724, uid=10085, userID:0
I/PackageManager(  937):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.googlequicksearchbox.VoiceSearchActivity, state=1, flag=1, pid=4724, uid=10085, userID:0
I/PackageManager(  937):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.search.core.icingsync.ApplicationLaunchReceiver, state=1, flag=1, pid=4724, uid=10085, userID:0
D/CustomizationManager( 4753): ====startRecUseTime====
D/htc.customization.log.level( 4753):  is 
W/CustomizationLogLevel( 4753): Level value is invalid, use default level 2
E/WifiDataStallTracker(  937): DATA_MONITOR_POLL true Token 1
D/WifiDataStallTracker(  937): updateDataStallInfo: mDataStallTxRxSum={txSum=37 rxSum=28} preTxRxSum={txSum=25 rxSum=17}
D/WifiDataStallTracker(  937): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  937): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
W/BroadcastQueue(  937): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to pl.k2.droidoaudioteka/.ford.AppLinkReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
I/ActivityManager(  937): Start proc com.htc.club for broadcast com.htc.club/com.mcrm.autonotification.Autostart: pid=4813 uid=10181 gids={50181, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/Process (  937): killProcessQuiet, pid=3733
I/ActivityManager(  937): Killing 3733:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/CustomizationManager( 4753):  Read ACC file spent 0.058 (s)
D/CIDMapFileReader( 4753): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4753): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4753): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4753): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4753): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4753): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4753): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4753): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 4753): Parsing tag category name = system
I/CustomizationCIDLoader( 4753): Parsing tag category name = application
I/CustomizationCIDLoader( 4753): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4753): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4753): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4753): Parsing tag category name = Settings
I/CustomizationCIDLoader( 4753): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4753): add string-array item, value = 42507
I/CustomizationCIDLoader( 4753): add string-array item, value = 21902
I/CustomizationCIDLoader( 4753): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 4753): add string-array item, value = 23420
I/CustomizationCIDLoader( 4753): add string-array item, value = 22299
I/CustomizationCIDLoader( 4753): add string-array item, value = 24002
I/CustomizationCIDLoader( 4753): add string-array item, value = 23210
I/CustomizationCIDLoader( 4753): add string-array item, value = 23205
I/CustomizationCIDLoader( 4753): add string-array item, value = 23806
I/CustomizationCIDLoader( 4753): add string-array item, value = 23430
I/CustomizationCIDLoader( 4753): add string-array item, value = 23408
I/CustomizationCIDLoader( 4753): add string-array item, value = 27205
I/CustomizationCIDLoader( 4753): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 4753): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 4753): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 4753): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 4753): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 4753): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 4753): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 4753): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 4753): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 4753): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 4753): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 4753): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 4753):  Read CID file spent 0.099 (s)
D/CustomizationManager( 4753):  All configurations done spent 0.099 (s)
I/ActivityManager(  937): Recipient 3733
D/Process (  937): killProcessQuiet, pid=4167
I/ActivityManager(  937): Killing 4167:com.google.android.configupdater/u0a98 (adj 15): empty #18
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  937): Recipient 4167
D/PMS     (  937): acquireHCC(34f17623): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 937 1000 null
D/PMS     (  937): acquireHCC(1ee02720): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 937 1000 null
I/ActivityManager(  937): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 pid 4753 on display 0
W/asset   (  937): Copying FileAsset 0x5568b46730 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/PMS     (  937): acquireWL(32db517f): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 937 1000 null
I/FeedHostManager( 1484): [onPause]
I/FeedProviderManager( 1484): onPause
I/FeedHostManager( 1484): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@2aa72da1
I/SocialFeedProvider( 1484): +onPause
I/SocialFeedProvider( 1484): -onPause
W/HtcSystemUPManager(  937): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/AnimationUtil(  937): isHTCRecent(HelloWorld/Recent screens.)/11
I/ActivityManager(  937): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4838 uid=10373 gids={50373, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/WifiService(  937): New client listening to asynchronous messages
E/WifiTrafficPoller(  937): ADD_CLIENT: 6
I/ActivityManager(  937): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=4855 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
I/SearchBackgroundTaskFac( 4724): refreshing internal icing corpora
D/libc    ( 4813): [NET] android_getaddrinfofornet+,hn 48(0x6874632d636c75),sn(),hints(known),family 0,flags 4
D/libc    ( 4813): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4813): [NET] android_getaddrinfofornet+,hn 48(0x6874632d636c75),sn(),hints(known),family 0,flags 1024
D/libc    ( 4813): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4813): [NET] android_getaddrinfo_proxy+
D/libc    ( 4813): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  415): [NET] android_getaddrinfofornet+,hn 48(0x6874632d636c75),sn(),hints(known),family 0,flags 1024
D/libc    (  415): [NET] _dns_getaddrinfo+, netid:100, mark:917604
W/asset   ( 4838): Copying FileAsset 0xaca86b50 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/StatusBarManagerService(  937): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  937): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  937): hiding MENU key
D/libc    (  415): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  415): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4813): [NET] android_getaddrinfo_proxy-, success
D/libc    ( 4813): [NET] android_getaddrinfofornet+,hn 14(0x35342e3233312e),sn(),hints(known),family 0,flags 4
D/libc    ( 4813): [NET] android_getaddrinfofornet-, SUCCESS
I/UpdateIcingCorporaServi( 4724): Updating corpora: APPS=MAYBE, CONTACTS=MAYBE
D/PMS     (  937): acquireWL(220e1981): PARTIAL_WAKE_LOCK  Icing 0x1 4460 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  937): releaseWL(220e1981): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
I/TrimMemoryManager( 1484): [trimMemory] 20
E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/ContactMessageStore( 1441): MSG_NOTIFY_CS_TO_SYNC >>
E/WifiTrafficPoller(  937):  packet count Tx=52 Rx=72
D/ContactMessageStore( 1441): MSG_NOTIFY_CS_TO_SYNC <<
D/libc    ( 4813): [NET] android_getaddrinfofornet+,hn 3,sn(),hints(known),family 0,flags 4
D/libc    ( 4813): [NET] android_getaddrinfofornet-, err=8
,D/PMS     (  937): acquireWL(1dedb580): PARTIAL_WAKE_LOCK  Icing 0x1 4460 10024 WorkSource{10024 com.google.android.gms}
I/GLSUser ( 1925): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
I/GLSUser ( 1925): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1925): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1925): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1925): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 4460): Storage manager: low false usage 1.77MB avail 5.80GB capacity 7.95GB
I/WebViewFactory( 4838): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
D/DotMatrix( 1313): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1313): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1218): reapply : com.google.android.gms 2 40
W/Search.LoginHelper( 4724): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 4724): com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
W/Search.LoginHelper( 4724): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 4724): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4724): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4724): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 4724): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 4724): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 4724): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 4724): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 4724): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 4724): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4724): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 4724): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4724): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 4724): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 4724): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 4724): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
W/Search.LoginHelper( 4724): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 4724): com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
W/Search.LoginHelper( 4724): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 4724): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4724): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4724): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 4724): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 4724): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 4724): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 4724): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 4724): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 4724): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4724): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 4724): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4724): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 4724): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 4724): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 4724): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
E/VelvetNetworkClient( 4724): Failed to get auth token
W/Search.LoginHelper( 4724): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 4724): com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
W/Search.LoginHelper( 4724): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 4724): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4724): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4724): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 4724): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 4724): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 4724): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 4724): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 4724): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 4724): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4724): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 4724): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4724): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 4724): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 4724): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 4724): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
W/art     ( 4460): Suspending all threads took: 55.004ms
I/art     ( 4460): Background sticky concurrent mark sweep GC freed 2955(291KB) AllocSpace objects, 4(80KB) LOS objects, 7% free, 5MB/5MB, paused 64.913ms total 99.796ms
W/Icing   ( 4460): Received bad json for section weights override -- ignoring.
I/WebViewFactory( 4724): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
I/LibraryLoader( 4838): Time to load native libraries: 21 ms (timestamps 8458-8479)
I/LibraryLoader( 4838): Expected native library version number "",actual native library version number ""
W/ResourcesManager( 4724): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/LibraryLoader( 4724): Time to load native libraries: 33 ms (timestamps 8471-8504)
W/Icing   ( 4460): Received bad json for corpus context scoring override -- ignoring.
W/Icing   ( 4460): Received bad json for section weights override -- ignoring.
W/Icing   ( 4460): Received bad json for corpus context scoring override -- ignoring.
I/LibraryLoader( 4724): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 4838): Binding Chromium to main looper Looper (main, tid 1) {276d3b9c}
I/LibraryLoader( 4838): Expected native library version number "",actual native library version number ""
I/chromium( 4838): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
D/libc    ( 4813): [NET] android_getaddrinfofornet+,hn 28(0x6874632d636c75),sn(),hints(known),family 0,flags 4
D/libc    ( 4813): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4813): [NET] android_getaddrinfofornet+,hn 28(0x6874632d636c75),sn(),hints(known),family 0,flags 1024
D/libc    ( 4813): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4813): [NET] android_getaddrinfo_proxy+
D/libc    ( 4813): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  415): [NET] android_getaddrinfofornet+,hn 28(0x6874632d636c75),sn(),hints(known),family 0,flags 1024
D/libc    (  415): [NET] _dns_getaddrinfo+, netid:100, mark:917604
W/art     ( 4724): Attempt to remove local handle scope entry from IRT, ignoring
I/BrowserStartupController( 4838): Initializing chromium process, singleProcess=true
W/art     ( 4838): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4838): ApplicationContext is null in ApplicationStatus
I/MusicStore( 4855): Database version: 120
D/libc    (  415): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  415): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4813): [NET] android_getaddrinfo_proxy-, success
D/libc    ( 4813): [NET] android_getaddrinfofornet+,hn 13(0x3130342e38312e),sn(),hints(known),family 0,flags 4
D/libc    ( 4813): [NET] android_getaddrinfofornet-, SUCCESS
W/ResourcesManager( 4724): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/chromium( 4838): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
W/art     ( 4724): Attempt to remove local handle scope entry from IRT, ignoring
E/libEGL  ( 4838): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4838): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 4838): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 4838): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 4838): Build Date: 03/09/15 Mon
I/Adreno-EGL( 4838): Local Branch: 
I/Adreno-EGL( 4838): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 4838): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 4838):                  d74aa161a12b9c6fc6332151
D/libc    ( 4724): [NET] android_getaddrinfofornet+,hn 13(0x7777772e676f6f),sn(),hints(known),family 2,flags 1024
D/libc    ( 4724): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4724): [NET] android_getaddrinfo_proxy+
D/libc    ( 4724): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  415): [NET] android_getaddrinfofornet+,hn 13(0x7777772e676f6f),sn(),hints(known),family 2,flags 1024
D/libc    (  415): [NET] _dns_getaddrinfo+, netid:100, mark:917604
W/ResourcesManager( 4724): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
E/Icing   ( 4460): Loading extension by file descriptor -1 failed
W/System.err(  937): java.lang.Throwable: stack dump
W/System.err(  937): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  937): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  937): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  937): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  937): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  937): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7726c61:true
D/libc    (  415): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  415): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4724): [NET] android_getaddrinfo_proxy-, success
D/BluetoothAdapter( 4838): 316700040: getState(). Returning 12
D/VoldConnector(  937): SND -> {17 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 4855): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
D/VoldConnector(  937): SND -> {18 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 4855): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
D/VoldConnector(  937): SND -> {19 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 4855): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/art     ( 4838): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 4838): onDetachedFromWindow called when already detached. Ignoring
W/ResourcesManager( 4855): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
D/SystemWebViewEngine( 4838): CordovaWebView is running on device made by: HTC
W/ResourcesManager( 4855): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/art     ( 4838): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4838): Attempt to remove local handle scope entry from IRT, ignoring
V/JNIHelp ( 4855): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
W/asset   ( 4724): Copying FileAsset 0x556878b3d0 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
W/chromium( 4838): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
W/System  ( 4855): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@206fac89: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
W/ActivityThread( 4855): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ProviderInstaller( 4855): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 4855): GMSCore installation verified
I/ConfigStore( 4855): Config Database version: 1
D/FindExtension( 4838): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
W/asset   ( 4724): Copying FileAsset 0x55687bafc0 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/PackageManager(  937):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4855, uid=10159, userID:0
D/WifiDisplayAdapter(  937): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  937):     Client/Owner: Client
D/WifiDisplayAdapter(  937):     GroupId: 
D/WifiDisplayAdapter(  937):     Passphrase: 
D/WifiDisplayAdapter(  937):     SessionId: 0
D/WifiDisplayAdapter(  937):     IP Address: }
E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  937):  packet count Tx=102 Rx=131
I/InputMethodManager( 4838): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@28ea9e91, mServedView=org.apache.cordova.engine.SystemWebView{1d5be1f6 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@393c59f7
I/InputMethodManagerService(  937): Disable input method client, pid=1484
D/StatusBarManagerService(  937): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  937): Enable input method client, pid=4838
I/PhoneStatusBar( 1218): setImeWindowStatus(false,false)
I/ActivityManager(  937): Displayed com.example.hello/.MainActivity: +1s223ms
D/PMS     (  937): releaseWL(32db517f): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,W/XT9_C   ( 1380): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1380): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1380): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1380): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,W/BindingManager( 4838): Cannot call determinedVisibility() - never saw a connection for the pid: 4838,
,I/Icing   ( 4460): updateResources: need to parse f{com.google.android.gms}
,W/Atfwd_Sendcmd(  459): AtCmdFwd service not published, waiting... retryCnt : 4,
,I/chromium( 4838): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,I/art     (  937): Explicit concurrent mark sweep GC freed 12178(609KB) AllocSpace objects, 1(84KB) LOS objects, 33% free, 16MB/24MB, paused 2.025ms total 172.239ms,
,D/MediaRouterService(  937): Client com.google.android.music (pid 4855): Registered
,D/WifiDisplayAdapter(  937): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  937):     Client/Owner: Client
D/WifiDisplayAdapter(  937):     GroupId: 
,D/WifiDisplayAdapter(  937):     Passphrase: 
D/WifiDisplayAdapter(  937):     SessionId: 0
D/WifiDisplayAdapter(  937):     IP Address: }
D/PMS     (  937): releaseWL(3bfcfd6d): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 null
,I/MediaRouter( 4855): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 4855): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 4855): type=WIFI subType= reason=null isConnected=true
,I/Icing   ( 4460): Internal init done: storage state 0
,D/JsMessageQueue( 4838): Set native->JS mode to OnlineEventsBridgeMode
,I/Icing   ( 4460): Post-init done
,E/AndroidProtocolHandler( 4838): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/NetworkMonitor( 4855): type=WIFI subType= reason=null isConnected=true,
,I/Icing   ( 4460): Query from com.google.android.googlequicksearchbox start 0 num 1000
,I/ActivityManager(  937): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=4968 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,I/PackageManager(  937):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=4855, uid=10159, userID:0
,E/Icing   ( 4460): Loading extension by file descriptor -1 failed
I/GHttpClientFactory( 4855): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/Icing   ( 4460): Query from com.google.android.googlequicksearchbox start 0 num 1000
,I/ApplicationLogger( 4724): logBytes() : Old Hash = 1936733727 : New Hash = -407635623
I/GoogleURLConnFactory( 4855): Using platform SSLCertificateSocketFactory
E/Icing   ( 4460): No scoring data for corpus [20]
E/Icing   ( 4460): Loading extension by file descriptor -1 failed
,W/ResourcesManager( 4968): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 4724): UpdateCorporaTask done [took 1405 ms] updated apps [took 1404 ms] 
,I/ApplicationLogger( 4724): logEvent(): Logged 2742 bytes in 1541 ms
,I/ActivityManager(  937): Killing 4209:com.htc.backupreset/1000 (adj 15): empty #17
D/Process (  937): killProcessQuiet, pid=4209
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
,D/jxcore_app_log( 4838): JniHelper::setJavaVM(0xab9188f8), pthread_self() = -1396479632
,D/JX-Cordova( 4838): jxcore cordova android initializing
,W/jxcore-log( 4838): Initializing JXcore engine,
W/jxcore-log( 4838): JXcore engine is ready
,W/jxcore-log( 4838): Starting JXcore engine,
,I/ActivityManager(  937): Recipient 4209,
,I/CalendarProvider2( 4968): Created com.android.providers.calendar.CalendarAlarmManager@85419a5(com.htc.providers.calendar.HtcCalendarProvider@263d617a),
E/WifiStateMachine(  937): handleMessage: E msg.what=131155
E/WifiStateMachine(  937): processMsg: ConnectedState
,E/WifiStateMachine(  937):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2462 sc=60 link=72 tx=6.2, 0.0, 0.0  rx=7.3 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:1305393853] gl hn u24 rssi=-51 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  937): processMsg: L2ConnectedState
E/WifiStateMachine(  937):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2462 sc=60 link=72 tx=6.2, 0.0, 0.0  rx=7.3 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:1305393855] gl hn u24 rssi=-51 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  937):  get link layer stats 0
W/WifiHW  (  937): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/wpa_supplicant( 1365): wlan0: Control interface command 'SIGNAL_POLL'
,D/CalendarProvider2( 4968): wait start:true
,I/wpa_supplicant( 1365): environment dirty rate=0 [53][0][0]
,E/WifiStateMachine(  937): fetchRssiLinkSpeedAndFrequencyNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  937): fetchRssiLinkSpeedAndFrequencyNative rssi=-56 linkspeed=72
E/WifiConfigStore(  937): updateConfiguration freq=2462 BSSID=c0:ff:d4:d3:aa:48 RSSI=-56 "NG700"WPA_PSK
,E/WifiStateMachine(  937): calculateWifiScore freq=2462 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=29.59 txretriesrate=0.00 rxrate=35.17 userTriggerdPenalty0
E/WifiStateMachine(  937):  good link -> stuck count =0
E/WifiStateMachine(  937):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  937):  isHighRSSI       ---> score=65
,D/WifiWatchdogStateMachine(  937): RSSI current: 3 new: -56, 3
D/WIFI_ICON( 1218): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,E/WifiStateMachine(  937): handleMessage: X
,I/ActivityManager(  937): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=4999 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,V/AlarmManager(  937): sending alarm PendingIntent{10e351d0: PendingIntentRecord{a9765c9 com.htc.mobiledata startService}}, i=com.htc.mobiledata.intent.REQUEST, t=2, cnt=1, w=59790, Int=0
,D/CalendarProvider2( 4968): wait end:false,
D/AutoSetting( 1589): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  937): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=5022 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a,
,D/AutoSetting( 1589): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1589): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1589): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1589): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 1589): service - handleMessage() setting current location null
,W/jxcore-log( 4838): Platform android
W/jxcore-log( 4838): 
W/jxcore-log( 4838): Process ARCH arm
W/jxcore-log( 4838): 
,I/art     (  439): Explicit concurrent mark sweep GC freed 8648(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 188us total 19.397ms,
D/Process (  937): killProcessQuiet, pid=4237,
I/ActivityManager(  937): Killing 4237:com.htc.htccupd/u0a13 (adj 15): empty #17
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/art     (  439): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 136us total 16.356ms
,I/art     (  439): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 121us total 16.618ms
,I/jxcore-log( 4838): JXcore Cordova bridge is ready!,
I/jxcore-log( 4838): 
W/jxcore-log( 4838): JXcore engine is started
,I/ActivityManager(  937): Recipient 4237,
,I/ActivityManager(  937): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=5045 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,E/jxcore-log( 4838): >> HTC-HTC One M8s,
E/jxcore-log( 4838): 
,I/jxcore-log( 4838): Total memory 1931808768,
I/jxcore-log( 4838): 
I/jxcore-log( 4838): Free memory 84729856
I/jxcore-log( 4838): 
,I/jxcore-log( 4838): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4838): 
I/jxcore-log( 4838): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4838): 
,I/jxcore-log( 4838): userPath [ 'www' ],
I/jxcore-log( 4838): 
,I/jxcore-log( 4838): Size 1080 1776
I/jxcore-log( 4838): 
,I/jxcore-log( 4838): Screen Brightness 142
I/jxcore-log( 4838): 
,E/jxcore-log( 4838): Dummy Error Log.
E/jxcore-log( 4838): 
,D/PhoneMonitor( 5022): Register our PhoneStateListener,
,D/PMS     (  937): releaseHCC(34f17623): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     (  937): releaseHCC(1ee02720): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,D/MobileConnectivityChangeReceiver( 5022): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5022): onReceive CONNECTIVITY_CHANGE networkType=1,
I/ActivityManager(  937): Killing 4307:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17,
D/Process (  937): killProcessQuiet, pid=4307
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,D/PhoneMonitor( 5022): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,D/MdScBoot( 4999): [7e9.1.] 30@-111542 -> 40
,D/PhoneMonitor( 5022): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,D/MdScBootUi( 4999): [7e9.1.2.] boot 118,
,D/MdScSimSt( 4999): [7e9.1.2.] qry 118: 0+1 running 0,
,I/ActivityManager(  937): Recipient 4307
,I/HtcModeClient( 3223): handler message = 4011,
E/HtcModeClient( 3223): Check connection and retry 4 times.
,E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL true Token 11 num clients 6
,E/WifiTrafficPoller(  937):  packet count Tx=103 Rx=132
,I/ActivityManager(  937): Killing 4328:com.android.settings:remote/1000 (adj 15): empty #17
,D/Process (  937): killProcessQuiet, pid=4328
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/ActivityManager(  937): Recipient 4328
,D/Process (  937): killProcessQuiet, pid=4352,
I/ActivityManager(  937): Killing 4352:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/jxcore-log( 4838): getBuffer is called!!!!,
I/jxcore-log( 4838): 
,I/Icing   ( 4460): Indexing FBE7E5D8BA1B80556F1315772AF6A2582D6BF376 from com.google.android.googlequicksearchbox,
,I/ActivityManager(  937): Recipient 4352,
,I/ActivityManager(  937): Waited long enough for: ServiceRecord{26389779 u0 com.htc.HTCSpeaker/.NGFService}
,D/PMS     (  937): acquireWL(31d10501): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4460 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  937): acquireWL(2c3bbde7): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4460 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  937): releaseWL(31d10501): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
,I/CheckinService( 4460): Checking schedule, now: 1448709373581 next: 1448628270795
I/CheckinService( 4460): active receiver: enabled
,I/PackageManager(  937):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=4460, uid=10024, userID:0
,I/CheckinService( 4460): Preparing to send checkin request,
I/EventLogService( 4460): Accumulating logs since 1448709367324
,I/PackageManager(  937):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4460, uid=10024, userID:0,
,I/CalendarProvider2( 4968): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
W/ContentResolver( 4968): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/iu.SyncManager( 4460): SYNC; picasa accounts
,D/NetworkLogImpl( 4460): Loaded NetworkSpeedPredictor,
,I/iu.Environment( 4460): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 4460): num queued entries: 0
,I/iu.UploadsManager( 4460): num updated entries: 0
,I/iu.SyncManager( 4460): NEXT; no task
,I/Icing   ( 4460): Indexing done FBE7E5D8BA1B80556F1315772AF6A2582D6BF376
,D/Process (  937): killProcessQuiet, pid=4375
I/ActivityManager(  937): Killing 4375:com.android.smith/1000 (adj 15): empty #17
,D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/ActivityManager(  937): Recipient 4375
,D/ChimeraCfgMgr( 4460): Loading module com.google.android.gms.kids from APK com.google.android.gms,
,D/ChimeraCfgMgr( 4460): Loading module com.google.android.gms.kids from APK com.google.android.gms,
,I/CheckinRequestBuilder( 4460): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  937): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5080 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a
,E/WifiTrafficPoller(  937): ADD_CLIENT: 7
D/WifiService(  937): New client listening to asynchronous messages
D/PMS     (  937): releaseWL(1dedb580): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,D/libc    ( 4560): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 4560): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4560): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
I/ActivityManager(  937): Cannot resolve ContentProvider=com.google.android.wearable.settings
D/libc    ( 4560): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4560): [NET] android_getaddrinfo_proxy+
D/libc    ( 4560): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  415): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  415): [NET] _dns_getaddrinfo+, netid:100, mark:917604
E/ActivityThread( 4460): Failed to find provider info for com.google.android.wearable.settings
,I/GLSUser ( 1925): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1925): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1925): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1925): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1925): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    (  415): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  415): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4560): [NET] android_getaddrinfo_proxy-, success
,I/Babel   ( 4560): connection state changed from UNKNOWN to CONNECTED,
W/Kids    ( 4460): [AccountUtils] Account not ready
W/Kids    ( 4460): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4460): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4460): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4460): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4460): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4460): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4460): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4460): 	,at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4460): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4460): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4460): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4460): 	at java.lang.Thread.run(Thread.java:818)
D/DotMatrix( 1313): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1313): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1218): reapply : com.google.android.gms 2 40
,E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  937):  packet count Tx=108 Rx=136
,I/GLSUser ( 1925): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer,
I/GLSUser ( 1925): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1925): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1925): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1925): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/art     ( 1925): Explicit concurrent mark sweep GC freed 11470(641KB) AllocSpace objects, 6(504KB) LOS objects, 49% free, 4MB/8MB, paused 956us total 55.821ms,
,W/CheckinRequestBuilder( 4460): awaiting user notification for token,
,D/DotMatrix( 1313): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1313): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1218): reapply : com.google.android.gms 3 40
,D/VoldConnector(  937): SND -> {20 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 5080): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  937): SND -> {21 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/},
,W/ContextImpl( 5080): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,I/GAv4    ( 5080): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5080):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5080):   adb logcat -s GAv4
D/VoldConnector(  937): SND -> {22 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
,E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 5080): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  937): SND -> {23 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
,E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl( 5080): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/ActivityManager(  937): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5113 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/GAv4    ( 5080): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5080): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/ResourcesManager( 5113): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
,W/ResourcesManager( 5113): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/GAv4    ( 5080): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/MultiDex( 5113): VM with version 2.1.0 has multidex support,
I/MultiDex( 5113): install
I/MultiDex( 5113): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 5113): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 5113): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 5113): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@39fe1fd7: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5113): Installed default security provider GmsCore_OpenSSL
,W/global  ( 5080): [apache-http] Connection GC has been deprecated!
,W/global  ( 5080): [apache-http] Connection GC has been deprecated!,
,I/WebViewFactory( 5080): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 5080): Time to load native libraries: 6 ms (timestamps 1819-1825),
I/LibraryLoader( 5080): Expected native library version number "",actual native library version number ""
,I/WVCdm   (  425): CdmEngine::OpenSession
,I/WVCdm   (  425): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  425): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory,
,V/WebViewChromiumFactoryProvider( 5080): Binding Chromium to main looper Looper (main, tid 1) {979b72e},
,D/DrmWidevineDash(  425): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  425): Service_Initialize: starts!,
D/QSEECOMAPI: (  425): QSEECom_get_handle sb_length = 0x19000,
D/QSEECOMAPI: (  425): App is not loaded in QSEE
E/QSEECOMAPI: (  425): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  425): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  425): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  425): App is not loaded in QSEE
,I/LibraryLoader( 5080): Expected native library version number "",actual native library version number "",
D/QSEECOMAPI: (  425): Loaded image: APP id = 6
D/DrmWidevineDash(  425): Service_Initialize: ends! returns 0
,D/QSAPPSVER(  425): qsapps_get_capabilities: Capability from secure side: 0x0,
D/QSAPPSVER(  425): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  425): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4b51000
E/DrmWidevineDash(  425): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4b51000,
D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/DrmLibTime(  577): got the req here! ret=0
D/DrmLibTime(  577): command id, time_cmd_id = 770
D/DrmLibTime(  577): time_getutcsec starts!
D/DrmLibTime(  577): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  577): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  577): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  577): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  577): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  577): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  577): QSEE Time Listener: Retrieved Android system time: 1448709374
D/DrmLibTime(  577): time_getutcsec returns 0, sec = 1448709374; nsec = 0
D/DrmLibTime(  577): time_getutcsec finished! 
D/DrmLibTime(  577): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  577): before calling ioctl to read the next time_cmd
E/QC-time-services(  465): Daemon: Time-services: Waiting to acceptconnection
,D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  425): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  425): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  425): hlos api version =  9
D/DrmWidevineDash(  425): tz api version =  9
D/DrmWidevineDash(  425): OEMCrypto_APIVersion: ends! returns version 9
,D/DrmWidevineDash(  425): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
I/GoogleURLConnFactory( 5113): Using platform SSLCertificateSocketFactory
,I/GAV2    ( 4678): Thread[GAThread,5,main]: No campaign data found.,
I/chromium( 5080): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/GAv4-SVC( 4460): Google Analytics 7.8.99 is starting up.,
D/libc    ( 5113): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 5113): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5113): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5113): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5113): [NET] android_getaddrinfo_proxy+
D/libc    ( 5113): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  415): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    (  415): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,I/BrowserStartupController( 5080): Initializing chromium process, singleProcess=true,
,W/art     ( 5080): Attempt to remove local handle scope entry from IRT, ignoring
,D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  425): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  425): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  425): OEMCrypto_OpenSession: starts! SID=0xf4d7a928
,D/DrmWidevineDash(  425): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  425): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  425): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  425): OEMCrypto_GetRandom: starts! randomData=0xab2b45f8, dataLength=8
D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  425): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  425): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab3050a8, wrapped_rsa_key_length=1280,
D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  425): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  425): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  425): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  425): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  425): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  425): OEMCrypto_GetDeviceID: starts! deviceID=0xab2c6f28, idLength=0xffda5788
D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
E/SysUtils( 5080): ApplicationContext is null in ApplicationStatus
,D/libc    (  415): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  415): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 5113): [NET] android_getaddrinfo_proxy-, success
,D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  425): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  425): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  425): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  425): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  425): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  425): OEMCrypto_GetHDCPCapability: starts!, current = 0xffda579e, maximum = 0xffda579f
D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  425): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  425): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  425): hlos api version =  9
D/DrmWidevineDash(  425): tz api version =  9
D/DrmWidevineDash(  425): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  425): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xffda580c
D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  425): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  425): PrepareKeyRequest: nonce=3162994583
D/DrmWidevineDash(  425): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab2d2c18
D/DrmWidevineDash(  425): message_length=1611, signature=0xab2c2b60, signature_length=0xffda576c
,D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,W/chromium( 5080): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 5080): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 5080): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5080): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 5080): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 5080): Build Date: 03/09/15 Mon
I/Adreno-EGL( 5080): Local Branch: 
I/Adreno-EGL( 5080): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 5080): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 5080):                  d74aa161a12b9c6fc6332151
,D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  425): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  425): CdmEngine::CloseSession,
D/DrmWidevineDash(  425): OEMCrypto_CloseSession: starts! SID=1,
D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  425): OEMCrypto_CloseSession: ends! returns 0,
I/WVCdm   (  425): L3 Terminate.
D/DrmWidevineDash(  425): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  425): Service_Uninitialize: starts!
D/QSEECOMAPI: (  425): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  425): QSEECom_shutdown_app, app_id = 6,
D/DrmWidevineDash(  425): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  425): OEMCrypto_Terminate: ends! returns 0
D/libc    ( 5113): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
D/libc    ( 5113): [NET] android_getaddrinfofornet-, err=8,
D/libc    ( 5113): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
D/libc    ( 5113): [NET] android_getaddrinfofornet-, err=8
,W/AudioManagerAndroid( 5080): Requires BLUETOOTH permission,
,I/NSApplication( 5080): Starting up...
,I/ActivityManager(  937): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=5178 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a,
D/Process (  937): killProcessQuiet, pid=4285
I/ActivityManager(  937): Killing 4285:com.android.settings/1000 (adj 15): empty #17
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  937):  packet count Tx=133 Rx=175
,I/ActivityManager(  937): Recipient 4285
,I/art     ( 5113): Background partial concurrent mark sweep GC freed 13359(796KB) AllocSpace objects, 8(288KB) LOS objects, 50% free, 3MB/7MB, paused 5.339ms total 58.743ms
,I/SocialFeedProvider( 1484): +disConnect socialManager
,I/SocialFeedProvider( 1484): disconnect socialManager
,I/SocialFeedProvider( 1484): -disConnect socialManager
,I/ActivityManager(  937): Start proc com.htc.sense.news for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper: pid=5199 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a
,V/AlarmManager(  937): sending alarm PendingIntent{123a9bcb: PendingIntentRecord{286e5fa8 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1448709375240, Int=0
,I/art     (  937): Explicit concurrent mark sweep GC freed 15535(817KB) AllocSpace objects, 4(208KB) LOS objects, 33% free, 16MB/24MB, paused 1.333ms total 153.168ms,
,E/WifiDataStallTracker(  937): DATA_MONITOR_POLL true Token 1
,D/WifiDataStallTracker(  937): updateDataStallInfo: mDataStallTxRxSum={txSum=115 rxSum=125} preTxRxSum={txSum=37 rxSum=28}
D/WifiDataStallTracker(  937): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  937): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,I/ActivityManager(  937): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=5226 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
D/Process (  937): killProcessQuiet, pid=4434
I/ActivityManager(  937): Killing 4434:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ImageRamCache( 5199): create image Cache, size: 31457280.
,I/ImageRamCache( 5199): [resize] ImageRamCache resized to: 30Mb.
I/ImageRamCache( 5199): create image Cache, size: 31457280.
,I/FeedSettings( 5199): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 5199): GroupBudget 0.500000 0.380000
I/FeedSettings( 5199): GroupBudget 60 45 15,
I/Prism.ExternalStringMa_( 5199): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 5199): loadSortType() with Custom,
I/Prism.AllAppsOptionsMa_( 5199): loadGridSize() with Alternative
,E/WifiStateMachine(  937): handleMessage: E msg.what=131155
E/WifiStateMachine(  937): processMsg: ConnectedState
,E/WifiStateMachine(  937):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2462 sc=60 link=72 tx=29.6, 0.0, 0.0  rx=35.2 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1305396874] gl hn u24 rssi=-51 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  937): processMsg: L2ConnectedState
E/WifiStateMachine(  937):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2462 sc=60 link=72 tx=29.6, 0.0, 0.0  rx=35.2 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1305396875] gl hn u24 rssi=-51 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine(  937):  get link layer stats 0
W/WifiHW  (  937): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1365): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1365): environment dirty rate=25 [31][8][0]
,E/WifiStateMachine(  937): fetchRssiLinkSpeedAndFrequencyNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  937): fetchRssiLinkSpeedAndFrequencyNative rssi=-56 linkspeed=72
E/WifiConfigStore(  937): updateConfiguration freq=2462 BSSID=c0:ff:d4:d3:aa:48 RSSI=-56 "NG700"WPA_PSK
,E/WifiStateMachine(  937): calculateWifiScore freq=2462 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=30.30 txretriesrate=0.00 rxrate=39.59 userTriggerdPenalty0
E/WifiStateMachine(  937):  good link -> stuck count =0
E/WifiStateMachine(  937):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  937):  isHighRSSI       ---> score=65
,E/cutils-trace( 5240): Error opening trace file: Permission denied (13),
I/dex2oat ( 5240): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=41 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 5240): dex2oat: override thread count:4
,I/ActivityManager(  937): Recipient 4434
,D/WifiWatchdogStateMachine(  937): RSSI current: 3 new: -56, 3,
E/WifiStateMachine(  937): handleMessage: X
,D/WIFI_ICON( 1218): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,W/ResourcesManager( 5226): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/SocialManager[SocialBiLogHelper]( 5199): action: com.htc.sense.hsp.HANDLE_ULOG,
I/SocialManager[SocialBiLogHelper]( 5199): last commit ulog time 1448689891703
I/SocialManager[SocialBiLogHelper]( 5199): skip commit this time
,D/Process (  937): killProcessQuiet, pid=4396
I/ActivityManager(  937): Killing 4396:com.android.vending/u0a72 (adj 15): empty #17
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/dex2oat ( 5240): dex2oat took 81.143ms (threads: 4),
,I/Adreno-EGL( 5113): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 5113): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 5113): Build Date: 03/09/15 Mon
I/Adreno-EGL( 5113): Local Branch: 
I/Adreno-EGL( 5113): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 5113): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 5113):                  d74aa161a12b9c6fc6332151
,I/ActivityManager(  937): Recipient 4396,
,I/Adreno-EGL( 5113): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 5113): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 5113): Build Date: 03/09/15 Mon
I/Adreno-EGL( 5113): Local Branch: 
I/Adreno-EGL( 5113): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 5113): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 5113):                  d74aa161a12b9c6fc6332151
,I/WVCdm   (  425): CdmEngine::OpenSession,
I/WVCdm   (  425): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  425): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  937):  packet count Tx=139 Rx=180
,D/DrmWidevineDash(  425): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15,
D/DrmWidevineDash(  425): Service_Initialize: starts!
D/QSEECOMAPI: (  425): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  425): App is not loaded in QSEE
E/QSEECOMAPI: (  425): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  425): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  425): QSEECom_get_handle sb_length = 0x19000,
D/QSEECOMAPI: (  425): App is not loaded in QSEE
,D/QSEECOMAPI: (  425): Loaded image: APP id = 7
,D/DrmWidevineDash(  425): Service_Initialize: ends! returns 0,
,D/QSAPPSVER(  425): qsapps_get_capabilities: Capability from secure side: 0x0
D/QSAPPSVER(  425): qsapps_get_capabilities: returns 0
,D/DrmWidevineDash(  425): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4b50000
E/DrmWidevineDash(  425): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4b50000
D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/DrmLibTime(  577): got the req here! ret=0,
D/DrmLibTime(  577): command id, time_cmd_id = 770
D/DrmLibTime(  577): time_getutcsec starts!
D/DrmLibTime(  577): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  577): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  577): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  577): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  577): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
,D/DrmLibTime(  577): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  577): QSEE Time Listener: Retrieved Android system time: 1448709376
D/DrmLibTime(  577): time_getutcsec returns 0, sec = 1448709376; nsec = 0
D/DrmLibTime(  577): time_getutcsec finished! 
D/DrmLibTime(  577): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  577): before calling ioctl to read the next time_cmd
D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
E/QC-time-services(  465): Daemon: Time-services: Waiting to acceptconnection
,D/DrmWidevineDash(  425): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  425): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  425): hlos api version =  9
D/DrmWidevineDash(  425): tz api version =  9
D/DrmWidevineDash(  425): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  425): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  425): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  425): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  425): OEMCrypto_OpenSession: starts! SID=0xffda59b8
D/DrmWidevineDash(  425): OEMCrypto_OpenSession Session ID = 0
,D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  425): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  425): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  425): OEMCrypto_GetRandom: starts! randomData=0xab307c78, dataLength=8
D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  425): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  425): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab3050a8, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  425): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  425): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  425): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  425): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  425): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  425): OEMCrypto_GetDeviceID: starts! deviceID=0xab2c6f68, idLength=0xf4d7a6f8
D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  425): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  425): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  425): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  425): OEMCrypto_SupportsUsageTable: wv_app_version = 24
,D/DrmWidevineDash(  425): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  425): OEMCrypto_GetHDCPCapability: starts!, current = 0xf4d7a70e, maximum = 0xf4d7a70f
D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  425): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  425): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  425): hlos api version =  9
D/DrmWidevineDash(  425): tz api version =  9
D/DrmWidevineDash(  425): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  425): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf4d7a77c
D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  425): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  425): PrepareKeyRequest: nonce=2917890270
D/DrmWidevineDash(  425): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab2d2c18
D/DrmWidevineDash(  425): message_length=1646, signature=0xab2dfd80, signature_length=0xf4d7a6dc
D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,I/ActivityManager(  937): Killing 3487:com.android.defcontainer/u0a15 (adj 15): empty #17,
D/Process (  937): killProcessQuiet, pid=3487
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  937): Recipient 3487
,D/CustomHighlightReceiver( 5199): [custom highlight] onReceive,
,D/CustomHighlightService( 5199): [custom highlight] onHandleIntent,
,D/NewsDB  ( 5199): set custom highlight [],
D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  425): OEMCrypto_GenerateRSASignature returns 0
I/ActivityManager(  937): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=5271 uid=10035 gids={50035, 9997} abi=arm64-v8a
I/WVCdm   (  425): CdmEngine::CloseSession,
D/DrmWidevineDash(  425): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  425): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  425): L3 Terminate.
D/DrmWidevineDash(  425): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  425): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  425): Service_Uninitialize: starts!
D/QSEECOMAPI: (  425): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  425): QSEECom_shutdown_app, app_id = 7
D/DrmWidevineDash(  425): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  425): OEMCrypto_Terminate: ends! returns 0
,I/CheckinRequestBuilder( 4460): Classify the device as Phone.
,D/CustomHighlightService( 5199): [custom highlight] set tags ,
,I/ActivityManager(  937): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=5295 uid=10076 gids={50076, 9997} abi=arm64-v8a
,D/Process (  937): killProcessQuiet, pid=3956,
I/ActivityManager(  937): Killing 3956:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  937): Recipient 3956
,D/libc    ( 4460): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4460): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4460): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 4460): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4460): [NET] android_getaddrinfo_proxy+
D/libc    ( 4460): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  415): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  415): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/SMSBackup( 5295): Got a database change event,
,I/ActivityManager(  937): Start proc com.htc.sense.mms for broadcast com.htc.sense.mms/.ui.MessagingShortcutReceiver: pid=5319 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
,D/libc    (  415): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  415): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4460): [NET] android_getaddrinfo_proxy-, success
,D/Process (  937): killProcessQuiet, pid=4596,
I/ActivityManager(  937): Killing 4596:com.google.android.youtube/u0a176 (adj 15): empty #17
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/libc    ( 4460): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4460): [NET] android_getaddrinfofornet-, err=8
,I/ActivityManager(  937): Recipient 4596
,D/libc    ( 4460): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
,D/libc    ( 4460): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 4460): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4460): [NET] android_getaddrinfofornet-, err=8
,I/CheckinTask( 4460): Sending checkin request (8470 bytes),
,W/HtcWrapAdjustableCursorFactory( 5319): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.,
,D/MessageFrequencyProvider( 5319): onCreate,
,V/GetPrviateResource( 5319): GetPrviateResource
,V/GetPrviateResource( 5319): GetPrviateResource
,I/PackageManager(  937):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService, state=2, flag=1, pid=4460, uid=10024, userID:0
,I/PackageManager(  937):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateActivity, state=2, flag=1, pid=4460, uid=10024, userID:0
,I/PackageManager(  937):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver, state=2, flag=1, pid=4460, uid=10024, userID:0
,D/MessageCustFlag( 5319): sense_version=6.0
,I/PackageManager(  937):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$Receiver, state=2, flag=1, pid=4460, uid=10024, userID:0
,D/BTAccessoryUtil( 5319): createReceiver
,D/BTAccessoryUtil( 5319): registerReceiver return intent = null
,D/MessageCustFlag( 5319): sku_id=118
,D/HtcBuildUtils( 5319): getRATByHtcTelephonyCapability:1
,W/SystemReader( 5319): Cannot find qct_8960_interface, use default value instead
,D/MmsConfig( 5319): packageName: com.htc.vvm.att does not exist,
,D/MessageCustFlag( 5319): sku_id=118,
,D/MessagingShortcutReceiver( 5319): keep hiding shortcut bubble,
,D/MessagingShortcut( 5319): updateMsgShortcut, msg count> -1,
,D/SettingsManager( 5319): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@85419a5,
,D/MessagingShortcut( 5319): After query: 0
,D/MessagingShortcut( 5319): mPresentUnreadCount: -1
,D/MessageUtils( 5319): [getShortcut] com.htc.sense.mms.ui.ConversationList, false
D/MessagingShortcut( 5319): setMsgShortcutDrawable> 0, false
,D/MessagingShortcut( 5319): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
,D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1313): [EventService] reorderNotification, total:0
D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1313): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/ActivityManager(  937): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=5344 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a,
,I/ActivityManager(  937): Killing 4678:com.google.android.gm/u0a106 (adj 15): empty #17
,D/Process (  937): killProcessQuiet, pid=4678
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  937): Recipient 4678
,W/SystemReader(  937): Cannot find grip_rejection_width, use default value instead,
D/AccTypeManager( 1709): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,W/ResourcesManager( 1441): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 5344): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/AccTypeManager( 1709): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/ResourcesManager(  937): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/Prism.AllAppsManager( 1484): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/Prism.ItemManager( 1484): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1484): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/CheckinRequestBuilder( 4460): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  937): Cannot resolve ContentProvider=com.google.android.wearable.settings
,I/Launcher( 1484): Deferring update until onResume
E/ActivityThread( 4460): Failed to find provider info for com.google.android.wearable.settings
D/Launcher( 1484): waitUntilResume // bindAppsUpdated
,D/AccTypeManager( 1709): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/PhoneApp( 1441): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Prism.ItemManager( 5199): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 5199): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
E/ExternalAccountType( 1709): Unsupported attribute readOnly
,D/TodoTaskshortcut( 5344): update TASK shortcut>,
,W/PackageManager(  937): Unable to load service info ResolveInfo{36c002 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  937): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  937): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  937): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  937): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  937): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  937): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  937): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  937): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  937): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  937): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  937): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  937): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  937): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  937): 	at java.lang.reflect.Method.invoke(Method.java:372)
,W/PackageManager(  937): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  937): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/ActivityManager(  937): Killing 4775:com.google.android.partnersetup/u0a27 (adj 15): empty #17,
D/Process (  937): killProcessQuiet, pid=4775
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/PMS     (  937): acquireWL(19455a55): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1925 10024 WorkSource{10024 com.google.android.gms},
,I/BackupManagerService(  937): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService},
,I/ActivityManager(  937): Recipient 4775,
,D/PMS     (  937): releaseWL(19455a55): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  937):  packet count Tx=157 Rx=195
,D/PMS     (  937): acquireWL(3e3d1540): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 5344 10069 null
,D/PMS     (  937): acquireWL(bfbbc79): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 5344 10069 null
,D/PMS     (  937): releaseWL(3e3d1540): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null,
,E/TodoTaskNotifyService( 5344): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
,W/System.err( 5344): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
W/System.err( 5344): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 5344): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 5344): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5344): 	at android.os.Looper.loop(Looper.java:155)
W/System.err( 5344): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/PMS     (  937): releaseWL(bfbbc79): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,W/NotifyReceiver( 5344): stopSelfResult true,
D/MtpReceiver( 3914): [MTP][handleUsbStateAsync]+
D/MtpReceiver( 3914): [MTP][handleUsbStateAsync]1:1-
D/MtpReceiver( 3914): [MTP][handleUsbState]+
,I/GCoreNlp( 1825): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/ActivityManager(  937): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=5371 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a
,D/MtpReceiver( 3914): [MTP][scanExternalVolumeIfNeed] scan external volume
D/MtpService( 3914): updating state; isCurrentUser=true, mMtpLocked=false
,D/MtpDatabase( 3914): TotalSize=1886532,MediaCacheLimit=6000
D/MtpReceiver( 3914): [MTP][handleUsbState]-
D/MtpReceiver( 3914): [MTP][handleMessage]-
,D/MtpService( 3914): [isMtpConnected] connected: true
,D/LocationProviderProxy(  937): applying state to connected service
,D/PMS     (  937): acquireWL(171cc7a5): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1825 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  937): releaseWL(171cc7a5): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,I/GLSUser ( 1925): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1925): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1925): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1925): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GmsNetworkLocationProvi( 1825): DISABLE
,V/GLSActivity( 1925): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  937): acquireWL(3a373921): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1825 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  937): releaseWL(3a373921): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/LocationProviderProxy(  937): applying state to connected service
,D/PMS     (  937): acquireWL(2d719146): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1825 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  937): acquireWL(15c25f07): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1825 10024 WorkSource{10024 com.google.android.gms},
W/CheckinRequestBuilder( 4460): awaiting user notification for token
D/PMS     (  937): releaseWL(2d719146): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
D/DotMatrix( 1313): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/PMS     (  937): releaseWL(15c25f07): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/DotMatrix( 1313): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1218): reapply : com.google.android.gms 3 40
,D/PMS     (  937): acquireWL(320c834): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 937 1000 null
I/BatteryService(  937): n_update end
D/PMS     (  937): releaseWL(320c834): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/MediaScannerService( 3914): [onStartCommand] --- Should not be here, redirect request. ----
D/HtcPowerSaver(  937): updateBatteryInfo
,E/MediaScannerService( 3914): [handleMessage] --- Should not be here, ignore request. ----
D/NotificationService(  937): plugged=true pluggin=true
D/UsbnetService(  937): BroadcastReceiver::onReceive+
D/PMS     (  937): runPSCheck
D/UsbnetService(  937): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  937): Checking...
D/UsbnetService(  937):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  937): >> updateStatus
D/UsbnetService(  937): BroadcastReceiver::onReceive-
D/WifiController(  937): battery changed pluggedType: 2
D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1218): closing low battery warning: level=100
D/DotMatrix( 1313): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  937): handleMessage: E msg.what=155652
I/HtcPowerSaver(  937): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1313): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  937): << updateStatus
,D/WifiController(  937): processMsg: DeviceActiveState
D/WifiController(  937): processMsg: StaEnabledState
D/WifiController(  937): processMsg: DefaultState
,I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  937): handleMessage: X
D/HeadsetStateMachine( 3102): Disconnected process message: 10, size: 0
,I/CheckinRequestBuilder( 4460): Classify the device as Phone.
,D/SyncApplication( 5371): Loading default preferences
,W/Resources( 5371): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,I/CheckinTask( 4460): Checkin success: https://android.clients.google.com/checkin (1 requests sent),
,I/CheckinService( 4460): Checking schedule, now: 1448709377550 next: 1449246209543
I/CheckinService( 4460): active receiver: disabled
I/PackageManager(  937):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4460, uid=10024, userID:0
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  937): releaseWL(2c3bbde7): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms},
,E/WifiTrafficPoller(  937): ADD_CLIENT: 8,
D/WifiService(  937): New client listening to asynchronous messages
,D/SyncApplication( 5371): Overriding preferences with custom values,
,E/MediaScannerServiceEx( 3914): [getStorageMaskIdFromPath] path is null,
D/MediaScannerServiceEx( 3914): [ServiceHandler][handleMessage] , action: null, Id: 0, path: /storage/emulated/0
,D/SyncApplication( 5371): Updating preferences succeeded
D/MediaScannerServiceEx( 3914): [handleExternalVolume] ext storage
,D/MediaProviderUtils( 3914): calcVolumeId: /storage/emulated/0
,E/SyncApplication( 5371): Application created.
D/MediaProviderUtils( 3914): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3914): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3914): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0,
D/MediaScannerServiceEx( 3914): [AliveExtStorageRows]+65537, 11223344
,D/MediaProvider( 3914): [update][5]#0#,
I/CalendarDefines( 5371): getNewCalendarAuthority()...
,D/MediaProvider( 3914): [update][2]#0#
,W/VolumeInfo( 5371): Unable to read mount points
W/VolumeInfo( 5371): java.io.FileNotFoundException: /etc/vold.fstab: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 5371): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/VolumeInfo( 5371): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/VolumeInfo( 5371): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/VolumeInfo( 5371): 	at java.io.FileReader.<init>(FileReader.java:66)
W/VolumeInfo( 5371): 	at com.nero.android.common.VolumeInfo.getVolumeMountPoints(VolumeInfo.java:194)
W/VolumeInfo( 5371): 	at com.nero.android.common.VolumeInfo.getVolumes(VolumeInfo.java:153),
W/VolumeInfo( 5371): 	at com.nero.android.common.VolumeInfo.initializeVolumeIDs(VolumeInfo.java:474)
W/VolumeInfo( 5371): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:51)
W/VolumeInfo( 5371): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:1)
W/VolumeInfo( 5371): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/VolumeInfo( 5371): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/VolumeInfo( 5371): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/VolumeInfo( 5371): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/VolumeInfo( 5371): 	at java.lang.Thread.run(Thread.java:818)
W/VolumeInfo( 5371): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 5371): 	at libcore.io.Posix.open(Native Method)
W/VolumeInfo( 5371): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/VolumeInfo( 5371): ,	at libcore.io.IoBridge.open(IoBridge.java:442)
W/VolumeInfo( 5371): 	... 13 more
I/PackageManager(  937):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=5371, uid=10005, userID:0,
V/VolumeInfo( 5371): Found 0 mount point(s)
W/PackageManager(  937): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
V/VolumeInfo( 5371): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
I/PackageManager(  937):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=5371, uid=10005, userID:0
D/SyncApplication( 5371): enableAppOperation()+
W/PackageManager(  937): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/SyncApplication( 5371): enableAppOperation()-
,D/VolumeInfo( 5371): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,D/HTCUtilities( 5371): isNeorSinged() + 
,D/VolumeInfo( 5371): Read the volume-id from the sd card: {9B5E872B-8520-47C6-8BD3-3081C2E38355}
,W/VolumeInfo( 5371): Can not create volume ID for unmounted volume null
,D/MediaProvider( 3914): [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
,D/MtpService( 3914): [sendStorageAdded] Already send to MTP: /storage/emulated/0
,D/MediaProvider( 3914): [update][18]#1#
,D/MediaScannerServiceEx( 3914): [AliveExtStorageRows]-0, 0
D/HTCUtilities( 5371): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 5371): isNeorSinged() return false,
D/PMS     (  937): acquireWL(19bb831e): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3914 10017 null
D/CDMountReceiver( 5371): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
D/CDMountReceiver( 5371): USB connected to PC
,D/MediaScanner( 3914): =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1,
,D/FOTAReceiver( 5371): onReceive() enter 
,D/FOTAReceiver( 5371): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,I/ActivityManager(  937): Start proc com.android.settings for broadcast com.android.settings/.NSReceiver: pid=5403 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,D/Process (  937): killProcessQuiet, pid=4813
I/ActivityManager(  937): Killing 4813:com.htc.club/u0a181 (adj 15): empty #17
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  937): Recipient 4813,
,D/BluetoothManagerService(  937): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  937): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@24588112 mBinding = false
W/Settings:Agent(  937): MONITOR_LOG
,W/Settings:Agent(  937): name: bluetooth_on
,W/Settings:Agent(  937): value: 0
,W/Settings:Agent(  937): >> traceCallingStack()
W/Settings:Agent(  937): Process.myPid(): 937
W/Settings:Agent(  937): Process.myTid(): 1718
W/Settings:Agent(  937): Process.myUid(): 1000
,W/Settings:Agent(  937): 
W/Settings:Agent(  937): 
W/System.err(  937): java.lang.Throwable: stack dump
,W/System.err(  937): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  937): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  937): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  937): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
,W/System.err(  937): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  937): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  937): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:378)
W/System.err(  937): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:624),
W/System.err(  937): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  937): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  937): 
W/Settings:Agent(  937): << traceCallingStack(): 17(ms)
,D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 5403): -onCreate()
,D/BluetoothManagerService(  937): Message: MESSAGE_DISABLE,
,D/BluetoothManagerService(  937): Sending off request.
D/BluetoothAdapterState( 3102): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3102): Setting state to 13
I/BluetoothAdapterState( 3102): Bluetooth adapter state changed: 12-> 13
D/BluetoothManagerService(  937): +onBluetoothStateChange prev=12 new=13
,D/BluetoothManagerService(  937): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/PMS     (  937): acquireWL(1dfe27ff): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3102 1002 null
D/BluetoothManagerService(  937): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  937): Bluetooth State Change Intent: 12 -> 13
V/Settings:HtcSettingsApplication( 5403): [5403/5403] onCreate()
D/BluetoothAdapterProperties( 3102): onBluetoothDisable()
I/bt-btm  ( 3102): BTM_SetDiscoverability
I/bt-btm  ( 3102): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3102): disc_mode 0000
I/bt-btm  ( 3102): evt_type=0x0 p-cb->evt_type=0x0 
I/BluetoothAdapterState( 3102): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/bt-btm  ( 3102): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btif ( 3102): HAL bt_hal_cbacks->adapter_properties_cb
I/IntentController( 1218): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/WifiManager( 4838): setWifiEnabled: Base Package Name=com.example.hello, uid=10373
D/NGFService( 3791): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
I/bt-btm  ( 3102): BTM_SetConnectability
D/WifiService(  937): setWifiEnabled: false pid=4838, uid=10373
I/bt-btm  ( 3102): btm_ble_set_connectability mode=0x0 combined_mode=0x1
E/WifiService(  937): Invoking mWifiStateMachine.setWifiEnabled
D/bt-btm  ( 3102): disc_mode 0000
I/WifiService(  937): isSprintWifiRestricted(): false
I/bt-btm  ( 3102): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/WifiService(  937): isMdmWifiRestricted(): false
E/WifiStateMachine(  937): WiFiDisplay: getWifidisplayApEnabled=false
,D/BluetoothAdapterProperties( 3102): Scan Mode:21
W/Settings:Agent(  937): MONITOR_LOG
W/Settings:Agent(  937): name: wifi_on
W/Settings:Agent(  937): value: 0
W/Settings:Agent(  937): >> traceCallingStack()
W/Settings:Agent(  937): Process.myPid(): 937
W/Settings:Agent(  937): Process.myTid(): 1421
W/Settings:Agent(  937): Process.myUid(): 1000
W/Settings:Agent(  937): 
W/Settings:Agent(  937): 
D/WifiService(  937): New client listening to asynchronous messages
,D/BluetoothAdapterState( 3102): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,E/WifiTrafficPoller(  937): ADD_CLIENT: 9
I/bt-btif ( 3102): BTA_JvDeleteRecord
I/bt-btif ( 3102): BTA_JvRfcommStopServer
D/bt-btm  ( 3102): BTM_FreeSCN 
I/bt-btif ( 3102): BTA_JvDeleteRecord
I/bt-btif ( 3102): BTA_JvRfcommStopServer
D/bt-btm  ( 3102): BTM_FreeSCN 
I/bt-btif ( 3102): BTA_JvDeleteRecord
I/bt-btif ( 3102): BTA_JvRfcommStopServer
D/bt-btm  ( 3102): BTM_FreeSCN 
I/bt-btif ( 3102): BTA_JvDeleteRecord
I/bt-btif ( 3102): BTA_JvRfcommStopServer
D/bt-btm  ( 3102): BTM_FreeSCN 
I/bt-btif ( 3102): BTA_JvDeleteRecord
I/bt-btif ( 3102): BTA_JvRfcommStopServer
,D/bt-btm  ( 3102): BTM_FreeSCN 
I/bt-btif ( 3102): BTA_JvDeleteRecord
I/bt-btif ( 3102): BTA_JvRfcommStopServer
D/bt-btm  ( 3102): BTM_FreeSCN 
E/bt-btif ( 3102): cmd socket is not created
D/bt-sdp  ( 3102): SDP_DeleteRecord ok, num_records:14
E/BtOppRfcommListener( 3102): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothSapService( 3102): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/TetherSettings( 5403): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5403): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5403): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5403): Cust_ConnectToPC   : spcsc>false
W/System.err(  937): java.lang.Throwable: stack dump
,D/        ( 5403): Cust_ConnectToPC   : IPT>true
D/        ( 5403): Cust_ConnectToPC   : Singel_USB>false
,I/bt-btm  ( 3102): BTM_SEC_CLR[13]: id 55
D/bt-sdp  ( 3102): SDP_DeleteRecord ok, num_records:13
I/bt-btm  ( 3102): BTM_SEC_CLR[14]: id 56
,D/bt-sdp  ( 3102): SDP_DeleteRecord ok, num_records:12
I/bt-btm  ( 3102): BTM_SEC_CLR[15]: id 57
D/bt-sdp  ( 3102): SDP_DeleteRecord ok, num_records:11
I/bt-btm  ( 3102): BTM_SEC_CLR[16]: id 58
D/bt-sdp  ( 3102): SDP_DeleteRecord ok, num_records:10
I/bt-btm  ( 3102): BTM_SEC_CLR[17]: id 59
D/bt-sdp  ( 3102): SDP_DeleteRecord ok, num_records:9
I/bt-btm  ( 3102): BTM_SEC_CLR[18]: id 60
D/bt-sdp  ( 3102): SDP_DeleteRecord ok, num_records:8
I/bt-btm  ( 3102): Write Extended Inquiry Response to controller
I/bt-btm  ( 3102): Write Extended Inquiry Response to controller
I/bt-btm  ( 3102): Write Extended Inquiry Response to controller
I/bt-btm  ( 3102): Write Extended Inquiry Response to controller
,W/bt-l2cap( 3102): L2CAP - L2CA_Deregister() called for PSM: 0x000f
I/bt-btm  ( 3102): BTM_SetDiscoverability
,I/bt-btm  ( 3102): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3102): disc_mode 0000
I/bt-btm  ( 3102): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 3102): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3102): BTM_SetConnectability
I/bt-btm  ( 3102): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3102): disc_mode 0000
D/bt-btm  ( 3102): btm_ble_update_adv_flag new=0x1c
D/bt-btm  ( 3102): btm_ble_update_adv_flag old=0x18
I/bt-btm  ( 3102): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 3102): BTM_IsInquiryActive
I/bt-btm  ( 3102): BTM_CancelRemoteDeviceName()
I/bt-btm  ( 3102): btm_ble_clear_white_list
W/bt-btif ( 3102): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
D/bt-btif ( 3102): AG evt (hdl 0x0001): State 0, Event 0x0501
D/bt-btif ( 3102): AG evt (hdl 0x0002): State 0, Event 0x0501
D/bt-sdp  ( 3102): SDP_DeleteRecord ok, num_records:7
D/bt-btm  ( 3102): BTM_FreeSCN 
I/bt-btm  ( 3102): BTM_SEC_CLR[3]: id 12
D/bt-sdp  ( 3102): SDP_DeleteRecord ok, num_records:6
D/bt-btm  ( 3102): BTM_FreeSCN 
I/bt-btm  ( 3102): BTM_SEC_CLR[4]: id 29
D/bt-avp  ( 3102): AVRC_Close handle:0
D/bt-btif ( 3102): AV Sevent(0x41)=0x120a(API_CLOSE) state=0(INIT)
D/bt-btif ( 3102): btif_hf_upstreams_evt: event=BTA_AG_DISABLE_EVT
W/Settings( 5403): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5403): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5403): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5403): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
,D/bt-sdp  ( 3102): SDP_DeleteRecord ok, num_records:5
D/bt-sdp  ( 3102): SDP_DeleteRecord ok, num_records:4
W/bt-l2cap( 3102): L2CAP - L2CA_Deregister() called for PSM: 0x0019
D/bt-sdp  ( 3102): SDP_DeleteRecord ok, num_records:3
W/bt-l2cap( 3102): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3102): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3102): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3102): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3102): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3102): L2CAP - L2CA_Deregister() called for PSM: 0x0011
W/bt-l2cap( 3102): L2CAP - L2CA_Deregister() called for PSM: 0x0013
I/bt-att  ( 3102): GATT_Deregister gatt_if=3
D/SmartNS_Utility( 5403): usb_cable_connect = 1
I/bt-att  ( 3102): GATT_Listen gatt_if=3
I/bt-btm  ( 3102): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3102): BTM_ReadConnectability
I/bt-btm  ( 3102): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3102): disc_mode 0000
I/bt-att  ( 3102): GATT_Deregister gatt_if=4
I/bt-att  ( 3102): GATT_Listen gatt_if=4
I/bt-btm  ( 3102): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3102): BTM_ReadConnectability
I/bt-btm  ( 3102): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3102): disc_mode 0000
E/bt-btif ( 3102): bta_gattc_deregister Deregister Failedm unknown client cif
D/SmartNS_Utility( 5403): usb_denied = 0
V/BluetoothPbapReceiver( 3102): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 3102): ***********state = 13
I/BtOppRfcommListener( 3102): stopping Accept Thread
I/BtOppRfcommListener( 3102): BluetoothSocket listen thread finished
W/System.err(  937): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  937): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  937): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  937): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  937): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  937): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  937): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  937): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:112)
W/System.err(  937): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  937): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  937): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  937): ,
W/Settings:Agent(  937): << traceCallingStack(): 41(ms)
I/SmartNS_NSReceiver( 5403): locked:falsesecurity:falseisLocked:false
D/SmartNS_NSReceiver( 5403): USB = true hasTethered = false isNSOpening: false
I/QuickSettingBluetooth( 1218): receive.ACTION_STATE_CHANGE:STATE_TURNING_OFF
I/bt-btm  ( 3102): btm_ble_clear_white_list_complete
,I/ActivityManager(  937): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=5429 uid=10034 gids={50034, 9997, 3002, 3001} abi=arm64-v8a
,D/PMS     (  937): acquireWL(23a0e9cc): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 5403 1000 null
D/Process (  937): killProcessQuiet, pid=4855
I/ActivityManager(  937): Killing 4855:com.google.android.music:main/u0a159 (adj 15): empty #17
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
W/ContextImpl( 5403): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 ,
,I/art     (  439): Explicit concurrent mark sweep GC freed 8623(366KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 232us total 29.405ms
I/HtcModeClient( 3223): handler message = 4011
E/HtcModeClient( 3223): Check connection and retry 5 times.
D/WifiController(  937): handleMessage: E msg.what=155656
D/WifiController(  937): processMsg: DeviceActiveState
D/WifiController(  937): processMsg: StaEnabledState
I/jxcore-log( 4838): ****TEST TOOK:  5258  ms ****
I/jxcore-log( 4838): 
,I/jxcore-log( 4838): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4838): 
,D/WifiController(  937): transitionTo: destState=ApStaDisabledState
D/WifiController(  937): handleMessage: new destination call exit/enter
D/WifiController(  937): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiController(  937): invokeExitMethods: DeviceActiveState
D/WifiController(  937): invokeExitMethods: StaEnabledState
D/WifiController(  937): moveTempStackToStateStack: i=0,j=1
D/WifiController(  937): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=ApStaDisabledState
D/WifiController(  937): invokeEnterMethods: ApStaDisabledState
D/WifiDisplayAdapter(  937): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  937):     Client/Owner: Client
D/WifiDisplayAdapter(  937):     GroupId: 
D/WifiDisplayAdapter(  937):     Passphrase: 
D/WifiDisplayAdapter(  937):     SessionId: 0
D/WifiDisplayAdapter(  937):     IP Address: }
D/WifiController(  937): handleMessage: X
E/WifiStateMachine(  937): handleMessage: E msg.what=131084
E/WifiStateMachine(  937): processMsg: ConnectedState
E/WifiStateMachine(  937):  ConnectedState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  937): processMsg: L2ConnectedState
E/WifiStateMachine(  937):  L2ConnectedState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  937): processMsg: ConnectModeState
E/WifiStateMachine(  937):  ConnectModeState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  937): processMsg: DriverStartedState
E/WifiStateMachine(  937):  DriverStartedState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  937): processMsg: SupplicantStartedState
E/WifiStateMachine(  937):  SupplicantStartedState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  937): transitionTo: destState=WaitForP2pDisableState
E/WifiStateMachine(  937): handleMessage: new destination call exit/enter
E/WifiStateMachine(  937): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=SupplicantStartedState,active=true,parent=DefaultState
E/WifiStateMachine(  937): invokeExitMethods: ConnectedState
E/WifiStateMachine(  937): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  937): release()
E/WifiStateMachine(  937): PerfLock released for exiting ConnectedState
E/WifiStateMachine(  937): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
E/WifiStateMachine(  937): invokeExitMethods: L2ConnectedState
E/WifiStateMachine(  937): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
E/WifiStateMachine(  937): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  937): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  937): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  937): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1365): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1365): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1365): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  937): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1365): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1365): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1365): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1365): CTRL_IFACE: SAVE_CONFIG - Configuration updated
,E/WifiStateMachine(  937): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  937): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1365): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1365): Power_Mode_Type mode = 0
I/wpa_supplicant( 1365): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  937): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1365): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  937): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1365): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiP2pService(  937): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDataStallTracker(  937): setDhcpActive: false
D/PMS     (  937): acquireWL(1287e415): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1925 10024 WorkSource{10024 com.google.android.gms}
I/art     (  439): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 200us total 22.494ms
V/NativeCrypto( 1925): Read error: ssl=0x556854f3d0: I/O error during system call, Connection timed out
D/libc    (  937): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  937): [NET] android_getaddrinfofornet-, SUCCESS
V/NativeCrypto( 1925): SSL shutdown failed: ssl=0x556854f3d0: I/O error during system call, Broken pipe
E/WifiStateMachine(  937): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  937): setDetailed state send new extra info<unknown ssid>
E/WifiStateMachine(  937): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  937): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/ConnectivityService(  937): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
D/libc    (  937): [NET] android_getaddrinfofornet-, SUCCESS
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  937): ValidatedState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  937): DefaultState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  937): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  937): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  937): Validated
D/ConnectivityService(  937): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  937): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  937):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  937):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  937): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  937): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  937):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  937):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  937): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1218): CM callback handler got msg 524290
D/libc    (  937): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  937): [NET] android_getaddrinfofornet-, SUCCESS
I/SecurityController( 1218): onAvailable 100 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/art     (  439): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 158us total 24.044ms
,I/ActivityManager(  937): Recipient 4855
D/MediaRouterService(  937): Client com.google.android.music (pid 4855): Died!
,V/BluetoothPbapService( 3102): Pbap Service closeService in
,V/BluetoothPbapService( 3102): successfully stopped pbap service
V/BluetoothPbapService( 3102): Pbap Service closeService out
,D/PMS     (  937): releaseWL(23a0e9cc): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null,
E/WifiStateMachine(  937): NetworkAgent != null
D/ConnectivityService(  937): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
E/WifiStateMachine(  937): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
V/NetworkPolicy(  937): mWifiStateReceiver: meteredHint=false,EPS mode=false
,E/WifiTrafficPoller(  937): ENABLE_TRAFFIC_STATS_POLL true Token 11
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED connected
V/BluetoothPbapService( 3102): Pbap Service onDestroy
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiTrafficPoller(  937):  packet count Tx=157 Rx=196
D/ConnectivityService(  937): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiTrafficPoller(  937): notifying of data activity 1
D/WIFI_ICON( 1218): WifiActivity: 1
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiStateMachine(  937): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiDataStallTracker(  937): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  937): stopDataStallAlarm 
E/WifiTrafficPoller(  937): ENABLE_TRAFFIC_STATS_POLL false Token 12
E/WifiDataStallTracker(  937): ENABLE_DATA_MONITOR_POLL false Token 1
,D/PMS     (  937): acquireWL(2c17451b): PARTIAL_WAKE_LOCK  StartingDockService 0x1 5403 1000 null
V/BluetoothPbapService( 3102): Pbap Service closeService in
V/BluetoothPbapService( 3102): Pbap Service closeService out
D/PMS     (  937): releaseWL(1287e415): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/bt-btm  ( 3102): BTM_BleGetVendorCapabilities
W/bt-btif ( 3102): ag scb idx 1 not allocated
W/bt-btif ( 3102): ag scb idx 2 not allocated
E/bt-btif ( 3102): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3102): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3102): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3102): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3102): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3102): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3102): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3102): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3102): L2CAP - PSM: 0x0017 not found for deregistration
,W/bt-l2cap( 3102): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3102): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3102): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3102): L2CAP - PSM: 0x0017 not found for deregistration
E/bt-btif ( 3102): bta_gattc_deregister Deregister Failedm unknown client cif
W/System.err(  937): java.lang.Throwable: stack dump
W/System.err(  937): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  937): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  937): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  937): 	at android.os.Binder.execTransact(Binder.java:454)
E/bt_userial_mct( 3102): pthread_join() FAILED result:3
D/BluetoothManagerService(  937): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  937): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2866d7f6:true
,D/HtcBtWidget_BTWidgetProvider( 5429): onBTStateChanged() for widget: 
D/HtcBtWidget_BTWidgetProvider( 5429): updateWidget(context) for widget: 
,I/QuickSettingWifi( 1218): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:1,
,I/QuickSettingWifi( 1218): receive.wifiConnect:false wifiAPname:null elapse:1
,D/ConnectivityService(  937): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler( 1218): CM callback handler got msg 524292
D/ConnectivityService(  937):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/SecurityController( 1218): onLost 100
D/ConnectivityService(  937):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/usbnet  (  937): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  937): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/usbnet  (  937):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  937): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/Nat464Xlat(  937): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  937): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  937): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  937): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  937): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  937): Disconnected - quitting
D/NetworkManagementService(  937): Removing idletimer
D/PMS     (  937): acquireWL(7db17f7): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 937 1000 null
D/CSLegacyTypeTracker(  937): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
D/ConnectivityService(  937): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL false Token 13 num clients 9
,I/art     (  937): Explicit concurrent mark sweep GC freed 27986(1498KB) AllocSpace objects, 2(104KB) LOS objects, 33% free, 16MB/25MB, paused 1.646ms total 183.551ms,
E/WifiStateMachine(  937): autoRoamSetBSSID any key="NG700"WPA_PSK
E/WifiConfigStore(  937): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  937): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1365): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1365): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1365): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  937): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1365): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1365): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1365): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1365): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  937): invokeExitMethods: ConnectModeState
E/WifiStateMachine(  937): invokeExitMethods: DriverStartedState
W/WifiHW  (  937): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/wpa_supplicant( 1365): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 1365): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  937): Unexpected BatchedScanResults :null
W/WifiHW  (  937): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/wpa_supplicant( 1365): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 1365): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  937): noteBatchedScanstop()
D/BluetoothAdapter( 5403): 145759046: getState(). Returning 13
,E/WifiTrafficPoller(  937): ENABLE_TRAFFIC_STATS_POLL false Token 13
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/PMS     (  937): releaseWL(1dfe27ff): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
D/BluetoothFtpService( 3102): ACTION_STATE_CHANGED: state: 13mHasStarted: true
E/BluetoothFtpService:RfcommSocketAcceptThread( 3102): Shutdown
D/BluetoothInputDevice( 5403): BluetoothInputDevice()
,D/BluetoothManagerService(  937): registerStateChangeCallback+
D/WifiService(  937): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
D/BluetoothManagerService(  937): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  937): Registered receivers: 9
,D/ConnectivityService(  937): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  937): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
E/ConnectivityService(  937): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/Tethering(  937): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
V/NetworkPolicy(  937): ensureActiveMobilePolicyLocked()
D/PMS     (  937): acquireWL(1af3c4d0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 937 1000 null
,D/NetworkPolicy(  937): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
,V/NetworkPolicy(  937): updateNetworkEnabledLocked()
V/NetworkPolicy(  937): updateIfacesLocked()
,D/DATA_ICON( 1218): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
,V/NetworkPolicy(  937): updateNotificationsLocked()
D/DATA_ICON( 1218): dataConnected: false/false
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/NetworkManagementService(  937): isBandwidthControlEnabled: doneSignal.getCount()= 0
E/WifiStateMachine(  937): [1,448,709,378,381 ms] noteScanEnd no scan source
E/WifiStateMachine(  937): moveTempStackToStateStack: i=0,j=2
,E/WifiStateMachine(  937): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=2,Top=WaitForP2pDisableState
E/WifiStateMachine(  937): invokeEnterMethods: WaitForP2pDisableState
E/WifiStateMachine(  937): handleMessage: X
E/WifiStateMachine(  937): handleMessage: E msg.what=131212
E/WifiStateMachine(  937): processMsg: WaitForP2pDisableState
D/MediaProvider( 3914): [update][40]#1#
,E/WifiStateMachine(  937):  WaitForP2pDisableState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  937): processMsg: SupplicantStartedState
E/WifiStateMachine(  937):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  937): processMsg: DefaultState
,E/WifiStateMachine(  937):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine(  937): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  937): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  937): handleMessage: X
E/WifiStateMachine(  937): handleMessage: E msg.what=131212
,D/WifiService(  937): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
E/WifiStateMachine(  937): processMsg: WaitForP2pDisableState
D/WifiScanningService(  937): SCAN_AVAILABLE : 1
E/WifiStateMachine(  937):  WaitForP2pDisableState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  937): processMsg: SupplicantStartedState
D/BluetoothMasReceiver( 3102): Bluetooth STATE CHANGED to 13
E/WifiStateMachine(  937):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  937): processMsg: DefaultState
D/RttService(  937): SCAN_AVAILABLE : 1
E/WifiStateMachine(  937):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
D/RttService(  937): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  937): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothPan( 5403): BluetoothPan()
D/WifiP2pService(  937): P2pEnabledState{ when=-9ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService(  937): registerStateChangeCallback+
D/WifiScanningService(  937): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService(  937): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  937): Registered receivers: 10
E/WifiStateMachine(  937): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  937): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  937): handleMessage: X
E/WifiStateMachine(  937): handleMessage: E msg.what=131212
E/WifiStateMachine(  937): processMsg: WaitForP2pDisableState
D/WifiMonitor(  937): stopMonitoring(p2p0) = com.android.server.wifi.p2p.WifiP2pServiceImpl$P2pStateMachine@3f78c215
E/WifiStateMachine(  937):  WaitForP2pDisableState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  937): processMsg: SupplicantStartedState
E/WifiStateMachine(  937):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  937): processMsg: DefaultState
E/WifiStateMachine(  937):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
V/BluetoothSapReceiver( 3102): SapReceiver onReceive 
V/BluetoothSapReceiver( 3102): action = android.bluetooth.adapter.action.STATE_CHANGED
D/WifiP2pService(  937): P2pDisablingState
V/BluetoothSapReceiver( 3102):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 3102): startService = false
D/WifiP2pService(  937): P2pDisablingState{ when=-2ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  937): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
D/WifiP2pService(  937): p2p socket connection lost
E/WifiStateMachine(  937): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiP2pService(  937): P2pDisabledState
E/WifiStateMachine(  937): handleMessage: X
D/WifiNetworkAgent(  937): NetworkAgent: NetworkAgent channel lost
D/WIFI    (  937): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  937):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  937): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
E/WifiStateMachine(  937): enter WifiNetworkFactory ,startNetwork. mIPTStart:false
E/WifiStateMachine(  937): handleMessage: E msg.what=131205
E/WifiStateMachine(  937): processMsg: WaitForP2pDisableState
D/AuthorizationBluetoothService( 1925): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
E/WifiStateMachine(  937):  WaitForP2pDisableState !CMD_DISABLE_P2P_RSP uid=1000 0 0
E/WifiStateMachine(  937): transitionTo: destState=SupplicantStoppingState
E/WifiStateMachine(  937): handleMessage: new destination call exit/enter
E/WifiStateMachine(  937): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  937): invokeExitMethods: WaitForP2pDisableState
E/WifiStateMachine(  937): invokeExitMethods: SupplicantStartedState
E/WifiStateMachine(  937): moveTempStackToStateStack: i=0,j=1
E/WifiStateMachine(  937): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStoppingState
E/WifiStateMachine(  937): invokeEnterMethods: SupplicantStoppingState
D/WifiP2pService(  937): P2pDisabledState{ when=0 what=131333 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  937): Call handleNetworkDisconnect() in SupplicantStoppingState
D/WifiP2pService(  937): DefaultState{ when=0 what=131333 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  937): releaseWL(1af3c4d0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/WifiService(  937): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
D/WifiDisplayController(  937): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,V/NetworkPolicy(  937): updateNetworkEnabledLocked(),
V/NetworkPolicy(  937): updateNotificationsLocked()
E/WifiStateMachine(  937): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - enter - invokeEnterMethods
D/WifiDisplayAdapter(  937): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  937):     Client/Owner: Client
D/WifiDisplayAdapter(  937):     GroupId: 
D/WifiDisplayAdapter(  937):     Passphrase: 
D/WifiDisplayAdapter(  937):     SessionId: 0
D/WifiDisplayAdapter(  937):     IP Address: }
E/WifiStateMachine(  937): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  937): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/WifiP2pService(  937): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1365): wlan0: Control interface command 'DRIVER POWERMODE 0'
D/WifiP2pService(  937): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1365): Power_Mode_Type mode = 0
I/wpa_supplicant( 1365): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  937): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1365): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1365): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  937): setDhcpActive: false
D/BluetoothMap( 5403): Create BluetoothMap proxy object
D/BluetoothManagerService(  937): registerStateChangeCallback+
V/AudioService(  937): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  937):     Client/Owner: Client
V/AudioService(  937):     GroupId: 
V/AudioService(  937):     Passphrase: 
V/AudioService(  937):     SessionId: 0
V/AudioService(  937):     IP Address: }
D/BluetoothManagerService(  937): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/HtcEffectManagerBase(  937): onEventChanged id=5 status=false
D/HtcEffectManager(  937): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true mAllPlayOn=false
D/HtcEffectManager(  937): convertEffect before=902
D/HtcEffectManager(  937): convertEffect after=902
E/BluetoothMap( 5403): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,D/BluetoothManagerService(  937): Registered receivers: 11
E/WifiStateMachine(  937): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  937): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiService(  937): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
,I/QuickSettingWifi( 1218): receive.wifiConnect:false wifiAPname:null elapse:0
E/WifiStateMachine(  937): stopping supplicant
W/WifiHW  (  937): QCOM Debug wifi_send_command "TERMINATE"
D/wpa_supplicant( 1365): RX global ctrl_iface - hexdump(len=9): 54 45 52 4d 49 4e 41 54 45
D/wpa_supplicant( 1365): wlan0: Removing interface wlan0
D/BluetoothManagerService(  937): registerStateChangeCallback+
D/BluetoothManagerService(  937): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
E/WifiStateMachine(  937): setWifiState: disabling
D/BluetoothManagerService(  937): Registered receivers: 12
D/BluetoothSap( 5403): BluetoothSap() call bindService
D/wpa_supplicant( 1365): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1365): TDLS: Tear down peers
D/wpa_supplicant( 1365): wpa_driver_nl80211_disconnect(reason_code=3)
,E/WifiTrafficPoller(  937): ENABLE_TRAFFIC_STATS_POLL false Token 14
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,E/WifiStateMachine(  937): handleMessage: X
,E/WifiStateMachine(  937): handleMessage: E msg.what=196614
E/WifiStateMachine(  937): processMsg: SupplicantStoppingState
E/WifiStateMachine(  937):  SupplicantStoppingState !CMD_ON_QUIT 0 0
E/WifiStateMachine(  937): processMsg: DefaultState
E/WifiStateMachine(  937):  DefaultState !CMD_ON_QUIT 0 0
E/WifiStateMachine(  937): handleMessage: X
,D/WIFI_ICON( 1218): updateWifiState: WIFI_STATE_CHANGED disabled
I/IntentController( 1218): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WifiService(  937): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
W/ContextImpl( 5403): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1888 android.content.ContextWrapper.bindService:538 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1423 
,D/BluetoothPbap( 5403): BluetoothPbap()
D/BluetoothManagerService(  937): registerStateChangeCallback+
,D/BluetoothManagerService(  937): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/WifiService(  937): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
D/BluetoothManagerService(  937): Registered receivers: 13
,D/LocalBluetoothProfileManager( 5403): LocalBluetoothProfileManager construction complete
,D/WifiService(  937): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
,D/DockEventReceiver( 5403): finishStartingService: stopping service,
D/WifiService(  937): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
,I/PSReceiver( 5403): onReceive:com.htc.intent.action.USB_CONNECT2PC
,W/ContextImpl( 5403): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2712 
D/WifiService(  937): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
D/MdScPhnSt( 4999): [d2a.2.]  listen tmrbb8
,D/wpa_supplicant( 1365): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 1365): wlan0: Deauthentication notification
D/wpa_supplicant( 1365): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1365): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1365): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1365): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
E/wpa_supplicant( 1365): enter disconnect check
I/wpa_supplicant( 1365): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1365): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 1365): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/WifiMonitor(  937): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462]
E/WifiMonitor(  937): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
E/WifiMonitor(  937): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/HTCRequest(  937): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
E/WifiMonitor(  937): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
E/WifiStateMachine(  937): handleMessage: E msg.what=147460
E/WifiStateMachine(  937): processMsg: SupplicantStoppingState
D/Tethering(  937): interfaceLinkStateChanged wlan0, false
D/Tethering(  937): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  937): WiFiDisplay: getWifidisplayApEnabled=false
,E/WifiStateMachine(  937):  SupplicantStoppingState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=65608,
E/WifiStateMachine(  937): processMsg: DefaultState
D/Tethering(  937): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
D/Tethering(  937): interfaceLinkStateChanged wlan0, false
E/WifiStateMachine(  937):  DefaultState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=65608
D/Tethering(  937): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  937): WiFiDisplay: getWifidisplayApEnabled=false
V/Tethering(  937): TetherInterfaceSM: wlan0: exit InitialState
E/WifiStateMachine(  937): handleMessage: X
V/Tethering(  937): TetherInterfaceSM: wlan0: enter UnavailableState
D/wpa_supplicant( 1365): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1365): wlan0: Disconnect event - remove keys
,D/wpa_supplicant( 1365): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1365): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1365): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x5585f57f88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1365):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1365): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1365): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1365): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1365): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1365): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1365): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1365): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1365): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1365): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1365): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1365): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1365): nl80211: Set wlan0 operstate 0->0 (DORMANT)
,D/wpa_supplicant( 1365): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1365): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1365): EAPOL: External notification - portValid=0
D/WifiMonitor(  937): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  937): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  937): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  937): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  937): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  937): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/WifiStateMachine(  937): handleMessage: E msg.what=147462
E/WifiStateMachine(  937): processMsg: SupplicantStoppingState
E/WifiStateMachine(  937): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  937):  SupplicantStoppingState !SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=65611  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  937): processMsg: DefaultState
E/WifiStateMachine(  937):  DefaultState !SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=65612  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  937): handleMessage: X
,D/BluetoothInputDevice( 5403): Proxy object connected,
,D/WISPrService( 5403): >>>>>WISPrService start isConnected = true<<<<<
,D/HidProfile( 5403): Bluetooth service connected
I/ActivityManager(  937): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=5464 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
I/QuickSettingWifi( 1218): receive.wifiConnect:false wifiAPname:null elapse:0
,D/WifiService(  937): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
D/Tethering(  937): sendTetherStateChangedBroadcast 0, 0, 0
D/PMS     (  937): acquireWL(12f91df): PARTIAL_WAKE_LOCK  NetworkStats 0x1 937 1000 null
D/UsbnetService(  937): BroadcastReceiver::onReceive+
D/UsbDeviceManager(  937): [USBNET] bCheckSuppFunc: cdc_network
D/UsbnetService(  937): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  937): BroadcastReceiver::onReceive-
E/WifiStateMachine(  937): handleMessage: E msg.what=131101
E/WifiStateMachine(  937): processMsg: SupplicantStoppingState
E/WifiStateMachine(  937):  SupplicantStoppingState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  937): processMsg: DefaultState
E/WifiStateMachine(  937):  DefaultState !CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  937): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  937): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  937): handleMessage: X
D/WifiService(  937): New client listening to asynchronous messages
D/BluetoothAdapter( 5403): 145759046: getState(). Returning 13
E/WifiTrafficPoller(  937): ADD_CLIENT: 10
D/BluetoothPan( 5403): BluetoothPAN Proxy object connected
I/QuickSettingWifi( 1218): receive.wifiState:WIFI_STATE_DISABLING setEnable:false
D/PanProfile( 5403): Bluetooth service connected
D/SapServerProfile( 5403): Bluetooth service connected
,D/PMS     (  937): releaseWL(12f91df): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null,
V/NetworkPolicy(  937): updateNetworkEnabledLocked()
V/NetworkPolicy(  937): updateNotificationsLocked()
D/PMS     (  937): releaseWL(2c17451b): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
,D/WifiService(  937): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
,I/SmartNS_PSService( 5403): onReceive:com.htc.intent.action.USB_CONNECT2PC
,D/WifiService(  937): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
,W/Settings( 5403): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 5403):  defaultType:0
E/WifiStateMachine(  937): handleMessage: E msg.what=131131
I/SmartNS_PSService( 5403): fail notificaiton:false
E/WifiStateMachine(  937): processMsg: SupplicantStoppingState
E/WifiStateMachine(  937):  SupplicantStoppingState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  937): processMsg: DefaultState
D/WifiService(  937): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
E/WifiStateMachine(  937):  DefaultState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  937): handleMessage: X
D/SmartNS_Utility( 5403): usb_cable_connect = 1
,D/SmartNS_Utility( 5403): usb_denied = 0
I/SmartNS_PSService( 5403): usb notificaiton:true
E/WifiStateMachine(  937): WiFiDisplay: getWifidisplayApEnabled=false
,D/WISPrService( 5403): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5403): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiService(  937): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
,D/WISPrService( 5403): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 5403): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/ActionCombine( 5403): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
I/bt-btif ( 3102): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 3102): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterService( 3102): mProfilesStarted : true supportedProfileServices.length : 6
E/cutils-trace( 5451): Error opening trace file: Permission denied (13)
,D/WISPrService( 5403): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 5403): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/HeadsetService( 3102): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 3102): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@85419a5
D/HeadsetStateMachine( 3102): Exit Disconnected: -1
D/BluetoothHeadset(  937): Proxy object disconnected
,D/BluetoothHeadset( 3791): Proxy object disconnected
D/NGFService( 3791): BluetoothHeadset onServiceDisconnected: main
D/BluetoothHeadset( 1218): Proxy object disconnected
I/QuickSettingMiniLite( 1218): btListener.disconnect:HEADSET
D/A2dpService( 3102): Received stop request...Stopping profile...
D/A2dpStateMachine( 3102): Exit Disconnected: -1
,D/BluetoothAdapterService( 3102): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@85419a5
D/SmartNS_Utility( 5403): usb_cable_connect = 1
D/SmartNS_Utility( 5403): usb_denied = 0
I/SmartNS_PSService( 5403): usb notificaiton:true
E/WifiStateMachine(  937): WiFiDisplay: getWifidisplayApEnabled=false,
,I/Prism.ItemManager( 1484): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1484): loadItems() com.htc.launcher.pageview.WidgetManager@3f4ca7ed +
I/Prism.WidgetManager( 1484): onLoadItems() +
,D/CustomizationManager( 5451): ====startRecUseTime====,
D/htc.customization.log.level( 5451):  is 
W/CustomizationLogLevel( 5451): Level value is invalid, use default level 2
,I/Prism.ItemManager( 5199): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
I/Prism.ItemManager( 5199): loadItems() com.htc.launcher.pageview.WidgetManager@39014d1e +
I/Prism.WidgetManager( 5199): onLoadItems() +
W/BluetoothHeadset( 1218): Proxy not attached to service
I/QuickSettingMiniLite( 1218): updateLiteState:no connect device!
,E/wpa_supplicant( 1365): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1365): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush
D/wpa_supplicant( 1365): wlan0: BSS: Remove id 2 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush
D/wpa_supplicant( 1365): wlan0: BSS: Remove id 1 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700' due to wpa_bss_flush
D/wpa_supplicant( 1365): wlan0: BSS: Remove id 3 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush
D/wpa_supplicant( 1365): wlan0: Cancelling delayed sched scan
D/wpa_supplicant( 1365): wlan0: Cancelling scan request
D/wpa_supplicant( 1365): wlan0: Cancelling authentication timeout
E/wpa_supplicant( 1365): wlan0: BLACKLIST REMOVE 00:00:00:00:00:00
D/WifiMonitor(  937): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  937): WifiMonitor:wlan0 cnt=28 dispatchEvent: BLACKLIST CLEAR 
D/WifiMonitor(  937): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  937): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  937): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48]
E/WifiMonitor(  937): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48
D/WifiMonitor(  937): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:48]
E/WifiMonitor(  937): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:48
D/WifiMonitor(  937): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 a0:c5:62:7a:49:97]
E/WifiMonitor(  937): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 a0:c5:62:7a:49:97
D/WifiMonitor(  937): Event [IFNAME=wlan0 BLACKLIST REMOVE 00:00:00:00:00:00]
E/WifiMonitor(  937): WifiMonitor:wlan0 cnt=33 dispatchEvent: BLACKLIST REMOVE 00:00:00:00:00:00
,E/WifiStateMachine(  937): handleMessage: E msg.what=131155
E/WifiStateMachine(  937): processMsg: SupplicantStoppingState
,E/WifiStateMachine(  937):  SupplicantStoppingState !CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2943] from screen [on:0 period:1305399890] gl hn u24 rssi=-51 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine(  937): processMsg: DefaultState
E/WifiStateMachine(  937):  DefaultState !CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1305399891] gl hn u24 rssi=-51 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  937): handleMessage: X
D/wpa_supplicant( 1365): Remove interface wlan0 from radio phy0
,D/BluetoothA2dp( 3791): Proxy object disconnected
D/NGFService( 3791): BluetoothA2dp onServiceDisconnected: main
,D/HidService( 3102): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3102): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@85419a5
D/MdProvGlob( 5045): remove item 101 (p2d11in102) for 15:android.intent.action.ANY_DATA_STATE
D/BluetoothAdapterState( 3102): Stopping profile services that were post enabled
D/CustomizationManager( 5451):  Read ACC file spent 0.034 (s)
,D/CIDMapFileReader( 5451): Parsing tag item name = HTC__001,
D/WifiService(  937): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
D/CIDMapFileReader( 5451): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5451): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5451): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5451): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5451): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5451): Parsing tag item name = HTC__031
D/BluetoothA2dp(  937): Proxy object disconnected
V/CustomizationCIDLoader( 5451): full path : /system/customize/CID/HTC__102.xml
D/MdScDataSum( 4999): [d2a.2.] summary 118:p2 ignore
I/CustomizationCIDLoader( 5451): Parsing tag category name = system
I/CustomizationCIDLoader( 5451): Parsing tag category name = application
I/CustomizationCIDLoader( 5451): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5451): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5451): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5451): Parsing tag category name = Settings
I/CustomizationCIDLoader( 5451): Parsing tag category name = ACC
I/CustomizationCIDLoader( 5451): add string-array item, value = 42507
I/CustomizationCIDLoader( 5451): add string-array item, value = 21902
I/CustomizationCIDLoader( 5451): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 5451): add string-array item, value = 23420
I/CustomizationCIDLoader( 5451): add string-array item, value = 22299
I/CustomizationCIDLoader( 5451): add string-array item, value = 24002
I/CustomizationCIDLoader( 5451): add string-array item, value = 23210
I/CustomizationCIDLoader( 5451): add string-array item, value = 23205
I/CustomizationCIDLoader( 5451): add string-array item, value = 23806
I/CustomizationCIDLoader( 5451): add string-array item, value = 23430
I/CustomizationCIDLoader( 5451): add string-array item, value = 23408
I/CustomizationCIDLoader( 5451): add string-array item, value = 27205
I/CustomizationCIDLoader( 5451): add string-array item, value = 42507:C:1:0
D/DotMatrix( 1313): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/CustomizationCIDLoader( 5451): add string-array item, value = 21902:C:1:0
,I/CustomizationCIDLoader( 5451): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 5451): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 5451): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 5451): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 5451): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 5451): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 5451): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 5451): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 5451): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 5451): add string-array item, value = 27205:C:1:0
W/BluetoothHeadsetServiceJni( 3102): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3102): Cleaning up Bluetooth Handsfree callback object
D/CustomizationManager( 5451):  Read CID file spent 0.100 (s)
D/CustomizationManager( 5451):  All configurations done spent 0.101 (s)
,D/SmartNS_Utility( 5403): usb_cable_connect = 1
D/SmartNS_Utility( 5403): usb_denied = 0
D/HealthService( 3102): Received stop request...Stopping profile...
I/RemoteViews( 1218): reapply : com.android.settings 2 36
D/BluetoothAdapterService( 3102): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@85419a5
I/RemoteViews( 1218): reapply : com.android.settings 1 36
D/PanService( 3102): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3102): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@85419a5
D/DotMatrix( 1313): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/SmartNS_PSService( 5403): KeyGuard locked:falseKeyGuard is secured:false
D/SmartNS_PSService( 5403): USB Plugged, Set USBPlugged=  truePSenabled:false
,D/BtGatt.DebugUtils( 3102): handleDebugAction() action=null
,D/BtGatt.GattService( 3102): Received stop request...Stopping profile...
D/BtGatt.GattService( 3102): stop()
D/BtGatt.AdvertiseManager( 3102): advertise clients cleared
D/MdProvGlob( 5045): remove item 101 (p2d2in186) for 15:android.intent.action.ANY_DATA_STATE
D/BluetoothInputDevice( 5403): Proxy object disconnected
D/HidProfile( 5403): Bluetooth service disconnected
D/BluetoothPan( 5403): BluetoothPAN Proxy object disconnected
D/PanProfile( 5403): Bluetooth service disconnected
D/BluetoothAdapterService( 3102): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@85419a5
W/BluetoothHidServiceJni( 3102): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 3102): Cleaning up Bluetooth GID callback object
,W/BluetoothHealthServiceJni( 3102): Cleaning up Bluetooth Health Interface...,
,W/BluetoothHealthServiceJni( 3102): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3102): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3102): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterState( 3102): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3102): Setting state to 10
,I/BluetoothAdapterState( 3102): Bluetooth adapter state changed: 13-> 10
D/BluetoothManagerService(  937): +onBluetoothStateChange prev=13 new=10
I/BluetoothAdapterState( 3102): Entering OffState
D/BluetoothManagerService(  937): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  937): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  937): Broadcasting onBluetoothStateChange(false) to 13 receivers.
D/BluetoothPan( 5403): onBluetoothStateChange on: false
D/BluetoothHeadset( 1218): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1441): Proxy object disconnected
D/BluetoothPhoneService( 1441): BluetoothHeadset onServiceDisconnected
D/BluetoothHeadset( 1441): Proxy object disconnected
,D/BluetoothHeadset( 1441): Proxy object disconnected
D/BluetoothHeadset( 1441): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1441): onBluetoothStateChange: up=false
D/BluetoothA2dp(  937): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1441): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 3791): onBluetoothStateChange: up=false
,D/BluetoothHeadset(  937): onBluetoothStateChange: up=false
D/BluetoothMap( 5403): onBluetoothStateChange: up=false
E/BluetoothMap( 5403): 
E/BluetoothMap( 5403): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothMap$2@1d5be1f6
E/BluetoothMap( 5403): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1135)
E/BluetoothMap( 5403): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1940)
E/BluetoothMap( 5403): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
E/BluetoothMap( 5403): 	at android.bluetooth.BluetoothMap$1.onBluetoothStateChange(BluetoothMap.java:64)
E/BluetoothMap( 5403): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothMap( 5403): 	at android.os.Binder.execTransact(Binder.java:454)
W/ContextImpl( 5464): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.backupreset.receiver.BackupResetReceiver.onReceive:45 android.app.ActivityThread.handleReceiver:2712 
D/BluetoothHeadset( 3791): onBluetoothStateChange: up=false
,D/BluetoothSap( 5403): onBluetoothStateChange on: false
W/ResourcesManager( 1484): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
V/BluetoothSapService( 3102): cleanup: mService: com.android.bluetooth.sap.BluetoothSapService@fd6b971
W/ResourcesManager( 5199): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/BluetoothPbap( 5403): onBluetoothStateChange: up=false
D/MdProvGlob( 5045): remove item 101 (p2d2in35) for 15:android.intent.action.ANY_DATA_STATE
D/BluetoothInputDevice( 5403): onBluetoothStateChange: up=false
,D/BluetoothManagerService(  937): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  937): Broadcasting onBluetoothServiceDown() to 10 receivers.,
D/BluetoothAdapter( 1441): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@38ebffda
D/BluetoothAdapter( 1441): onBluetoothServiceDown: done
,D/BluetoothAdapter( 1218): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@29fa5829
D/BluetoothAdapter( 1218): onBluetoothServiceDown: done
,D/BluetoothAdapter( 2374): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@2fb0ae3b
D/BluetoothAdapter( 2374): onBluetoothServiceDown: done
,D/BluetoothAdapter( 5403): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@393c59f7
D/BluetoothAdapter( 5403): onBluetoothServiceDown: done
,D/BluetoothAdapter( 3102): onBluetoothServiceDown: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@1c91ab21
D/BluetoothAdapter( 3102): onBluetoothServiceDown: done
,D/BluetoothAdapter( 3791): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@37711d2a
D/BluetoothAdapter( 3791): onBluetoothServiceDown: done,
D/BluetoothAdapter(  937): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@24588112
D/BluetoothAdapter(  937): onBluetoothServiceDown: done
D/BluetoothAdapter( 4838): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@1758d5e9
D/BluetoothAdapter( 4838): onBluetoothServiceDown: done
D/BluetoothAdapter( 1825): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@24e85bc7
D/BluetoothAdapter( 1825): onBluetoothServiceDown: done
D/BluetoothAdapter( 1460): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@2e4129ff
D/BluetoothAdapter( 1460): onBluetoothServiceDown: done
D/BluetoothManagerService(  937): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@24588112 mBinding = false
D/BluetoothManagerService(  937): Sending unbind request.
,D/BluetoothManagerService(  937): Bluetooth State Change Intent: 13 -> 10
,D/MdProvGlob( 5045): remove item 101 (p2d1in29) for 15:android.intent.action.ANY_DATA_STATE
,D/wpa_supplicant( 1365): nl80211: Remove monitor interface: refcount=0
D/wpa_supplicant( 1365): netlink: Operstate: ifindex=29 linkmode=0 (kernel-control), operstate=6 (IF_OPER_UP)
,I/bt-btif ( 3102): HAL bt_hal_cbacks->thread_evt_cb
D/NGFService( 3791): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
D/NGFService( 3791): Bluetooth Adapter: OFF
,I/IntentController( 1218): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/LocalBluetoothProfileManager( 5403): setBluetoothStateOff
W/BluetoothEventManager( 5403): unregister mProfileBroadcastReceiver fail
D/FlexNetS( 4968): updateSvcAllowedInSettings:false
,I/art     ( 3102): System.exit called, status: 0
,D/NfcHandover( 1460): onReceive: mBound=false, BTByNfc=false->false, BTHConnected=false->false
,D/TetherPref( 5403): persistRestoreBluetoothState false
,D/MdProvGlob( 5045): remove item 101 (p2in21) for 15:android.intent.action.ANY_DATA_STATE
,D/PackageManager(  937): deletePackageAsUser: pkg=com.example.hello, pid=5451, uid=2000 userid=0
,D/Messaging( 5319): supportCMAS(SIE)/init? false/true
D/MmsConfig( 5319): networkCode: 
D/MmsConfig( 5319): SIE smsPri: null
I/ActivityManager(  937): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5509 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a
D/MmsConfig( 5319): networkCode: 
,D/wpa_supplicant( 1365): nl80211: Set mode ifindex 29 iftype 2 (STATION)
D/wpa_supplicant( 1365): nl80211: Unsubscribe mgmt frames handle 0x888888dd0d7d1989 (mode change)
I/ActivityManager(  937): Force stopping com.example.hello appid=10373 user=-1: uninstall pkg
I/wpa_supplicant( 1365): htc_wext_command_deinit +
I/wpa_supplicant( 1365): htc_wext_command_deinit -
I/wpa_supplicant( 1365): wlan0: CTRL-EVENT-TERMINATING 
D/WifiMonitor(  937): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
E/WifiMonitor(  937): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-TERMINATING 
D/wpa_supplicant( 1365): Control interface directory not empty - leaving it behind
D/wpa_supplicant( 1365): p2p0: Removing interface p2p0
D/wpa_supplicant( 1365): p2p0: Request to deauthenticate - bssid=00:00:00:00:00:00 pending_bssid=00:00:00:00:00:00 reason=3 state=DISCONNECTED
D/wpa_supplicant( 1365): TDLS: Tear down peers
D/wpa_supplicant( 1365): p2p0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1365): nl80211: Set p2p0 operstate 0->0 (DORMANT)
D/WifiMonitor(  937): Disconnecting from the supplicant, no more events
D/wpa_supplicant( 1365): netlink: Operstate: ifindex=30 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1365): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1365): EAPOL: External notification - portValid=0
E/WifiStateMachine(  937): handleMessage: E msg.what=147458
E/WifiStateMachine(  937): processMsg: SupplicantStoppingState
D/Tethering(  937): interfaceLinkStateChanged wlan0, false
D/Tethering(  937): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  937): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  937):  SupplicantStoppingState !SUP_DISCONNECTION_EVENT 34 0
E/WifiStateMachine(  937): Supplicant connection lost
,D/Process (  937): killProcessQuiet, pid=4838,
I/ActivityManager(  937): Killing 4838:com.example.hello/u0a373 (adj 0): stop com.example.hello
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
,W/PackageSettings(  937): Skipping PackageSetting{2757b964 com.test.thalitest/10366} due to missing metadata
,I/ActivityManager(  937): Recipient 3102
,D/BluetoothAdapter( 1218): 263815788: getState() :  mService = null. Returning STATE_OFF
I/QuickSettingBluetooth( 1218): receive.ACTION_STATE_CHANGE:STATE_OFF/(false,false)
,D/Messaging( 5319): mNeedToUpdateDate2 start
,D/ReportIndicatorCache( 5319): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 5319): 
D/MmsAsyncWorkHandler( 5319): HM tk = 20001
D/ReportIndicatorCache( 5319): MSG_QUERY_REPORTS >>
,D/DraftCache( 5319): [DraftCache/1] DraftCache.constructor
D/DraftCache( 5319): [DraftCache/1] refresh
,I/Messaging( 5319): mccmnc> 
,D/MmsConfig( 5319): networkCode: 
,D/Messaging( 5319): ViewCache CreatePreloadOnlyConversationList
,I/ActivityManager(  937): Recipient 4838
I/WindowState(  937): WIN DEATH: Window{357a5d3 u0 com.example.hello/com.example.hello.MainActivity}
D/WifiService(  937): Client connection lost with reason: 4
,D/MessageCustFlag( 5319): sense_version=6.0
E/InputEventReceiver( 1380): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{1330fe7d uid 10373 pid 4838} (c)'
D/Jerry   ( 5319): start to preload cursor >>>>>>>
,W/ActivityManager(  937): Force removing ActivityRecord{141c98d9 u0 com.example.hello/.MainActivity t8}: app died, no saved state
,I/ActivityManager(  937): Force stopping com.example.hello appid=10373 user=0: pkg removed
,D/MdProvGlob( 5045): remove item 101 (p2in131) for 15:android.intent.action.ANY_DATA_STATE
,D/TelephUtils( 1441): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
V/AlarmManager(  937): sending alarm PendingIntent{3c9ac771: PendingIntentRecord{29118956 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=66149, Int=0
D/AccFlag ( 1441): sku_id=118
I/ActivityManager(  937): Process com.android.bluetooth (pid 3102) has died
W/ActivityManager(  937): Scheduling restart of crashed service com.android.bluetooth/.sap.BluetoothSapService in 1000ms
D/DraftCache( 5319): [DraftCache/121] rebuildCache
W/ActivityManager(  937): Scheduling restart of crashed service com.android.bluetooth/.map.BluetoothMasService in 1000ms
W/ResourcesManager( 5199): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/BroadcastQueue(  937): Schedule to resend BroadcastRecord{22d3ddd7 u-1 android.bluetooth.adapter.action.STATE_CHANGED callingPid=937 callingUid=1000} for ResolveInfo{d1726c4 com.android.bluetooth/.pbap.BluetoothPbapReceiver m=0x108000} of com.android.bluetooth
,W/ResourcesManager( 1484): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/PhoneApp( 1441): EVENT_QUERY_MO_PACKAGES
D/DotMatrix( 1313): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1313): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1313): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
,D/PhoneApp( 1441): -- N1 =0,
,D/PhoneApp( 1441): -- N2 =0
D/PhoneApp( 1441): -- N3 =0
W/SystemReader(  937): Cannot find grip_rejection_width, use default value instead
,D/PMS     (  937): acquireWL(168e8073): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1825 10024 WorkSource{10024 com.google.android.gms}
I/InputMethodManagerService(  937): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/ActivityManager(  937): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=5540 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3008} abi=armeabi-v7a
,W/ActivityManager(  937): Spurious death for ProcessRecord{1b128a5c 4838:com.example.hello/u0a373}, curProc for 4838: null
W/GeofencerStateMachine( 1825): Ignoring removeGeofence because network location is disabled.
D/PMS     (  937): releaseWL(168e8073): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/AccTypeManager( 1709): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,I/FeedHostManager( 1484): [onResume]
,I/FeedProviderManager( 1484): onResume
D/TelephUtils( 1441): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 89
D/MmsSmsV2Provider( 1441):  slotId = -1000
D/MmsSmsV2Provider( 1441): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
I/SocialFeedProvider( 1484): +onResume
I/SocialFeedProvider( 1484): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1484): -onResume
I/ConnectivityHelper( 1484): [getCurrentConnectionType] no network connection
D/AccTypeManager( 1709): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/TelephUtils( 1441): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
,D/MmsSmsV2Provider( 1441):  slotId = -1000
D/MmsSmsV2Provider( 1441): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/StatusBarManagerService(  937): setSystemUiVisibility(0x700)
,D/StatusBarManagerService(  937): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  937): hiding MENU key
,D/PhoneStorageUtil( 5319): HtcWrapEnvironment.getSupportedStorages() >1
,D/PhoneStorageUtil( 5319): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 5319): createReceiver
,D/TelephUtils( 1441): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/MmsSmsV2Provider( 1441):  slotId = -1000,
W/ResourcesManager( 5540): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
D/FindExtension( 1484): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
D/AccTypeManager( 1709): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/MediaProvider( 3914): [update][17]#1#
I/ThreadedRenderer( 1484): Defer allocateBuffers to drawing time
,D/PhoneApp( 1441): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,D/MdProvGlob( 5045): remove item 101 (p2d2in285) for 15:android.intent.action.ANY_DATA_STATE
W/InputMethodManagerService(  937): Got RemoteException sending setActive(false) notification to pid 4838 uid 10373
D/StatusBarManagerService(  937): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  937): Enable input method client, pid=1484
D/TelephUtils( 1441): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 89
V/MmsProvider( 1441): Update uri=content://mms, match=0
V/MmsProvider( 1441): selection=st=129 AND m_type!=134
D/Messaging( 5319): ViewCache CreatePreload
D/Messaging( 5319): ViewCache CreatePreloadOnlyMultipleOpsList
E/ExternalAccountType( 1709): Unsupported attribute readOnly
D/Messaging( 5319): Reset downloading state: 0
V/MmsSystemEventReceiver( 5319): TransactionService is going to be woken up.
,D/TelephUtils( 1441): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/Jerry   ( 1441): URI_DRAFT
W/PackageManager(  937): Unable to load service info ResolveInfo{279dcd31 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  937): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  937): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  937): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  937): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  937): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  937): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  937): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  937): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  937): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  937): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  937): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  937): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  937): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  937): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  937): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  937): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
W/ResourcesManager(  937): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/Cust_MMSMS( 5319): _has_set_default_values_2=true
D/DraftCache( 5319): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 5319): [DraftCache/121] rebuildCache time: 5
D/MmsAsyncWorkHandler( 5319): 
D/MmsAsyncWorkHandler( 5319): HM tk = 20002
,D/MsgPreferenceUtils( 5319): def_index: 0
,I/[PluginManager]RegisterService( 1589): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello
D/TelephUtils( 1441): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/MmsSmsV2Provider( 1441):  slotId = -1000
D/MmsSmsV2Provider( 1441): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,I/[PluginManager]RegisterService( 1589): handle notify Blinkfeed plugin client changed
D/AdapterServiceConfig( 5540): Adding HeadsetService
D/MsgPreferenceUtils( 5319): globalIndex = 1
D/AdapterServiceConfig( 5540): Adding A2dpService
D/AdapterServiceConfig( 5540): Adding HidService
D/AdapterServiceConfig( 5540): Adding HealthService
V/TransactionService( 5319): 1-Creating TransactionService
D/AdapterServiceConfig( 5540): Adding PanService
D/Prism.PackageStateRece_( 1484): action: android.intent.action.PACKAGE_ADDED
D/AdapterServiceConfig( 5540): Adding GattService
,E/[PluginManager]RegisterService( 1589): Unable to getApplicationInfo for com.example.hello
E/[PluginManager]RegisterService( 1589): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
E/[PluginManager]RegisterService( 1589): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:281)
E/[PluginManager]RegisterService( 1589): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
E/[PluginManager]RegisterService( 1589): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
E/[PluginManager]RegisterService( 1589): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/[PluginManager]RegisterService( 1589): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/[PluginManager]RegisterService( 1589): 	at android.os.Looper.loop(Looper.java:155)
E/[PluginManager]RegisterService( 1589): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/MdProvGlob( 5045): remove item 101 (p2d1in85) for 15:android.intent.action.ANY_DATA_STATE
V/BluetoothPbapReceiver( 5540): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapReceiver( 5540): ***********state = 10
D/MdScDataSum( 4999): [d2a.14.] summary 118:p1 ignore
E/BluetoothMasService( 5540): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
D/StatusBarManagerService(  937): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  937): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/MsgPreferenceUtils( 5319): phone state: true
D/StatusBarManagerService(  937): hiding MENU key
D/MsgPreferenceUtils( 5319): sd state: false
D/MsgPreferenceUtils( 5319): vIndex = 0
,D/Messaging( 5319): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/PMS     (  937): acquireWL(2108c7e4): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 5403 1000 null
D/MdProvGlob( 5045): remove item 101 (p2in20) for 15:android.intent.action.ANY_DATA_STATE
,W/ContextImpl( 5403): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
V/TransactionService( 5319): onStartCommand: 1
D/MmsSystemEventReceiver( 5319): unRegisterForConnectionStateChanges
V/TransactionService( 5319): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 5319): Loading previous transactions.
,D/TelephUtils( 1441): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
,D/MmsSmsV2Provider( 1441):  slotId = -1000
D/MmsSmsV2Provider( 1441): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/BluetoothMasService( 5540): Add permission for SmsProvider.
I/wpa_ctrl(  937): [wpa_ctrl_close] ctrl=0x55685e3310
I/wpa_ctrl(  937): [wpa_ctrl_close] ctrl=0x55685f5070
,D/Messaging( 5319): mNeedToUpdateDate2: false
,I/ActivityManager(  937): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5576 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,W/System.err(  937): java.lang.Throwable: stack dump
D/BluetoothManagerService(  937): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  937): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  937): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  937): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
D/BluetoothManagerService(  937): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2d1ff214:true
W/System.err(  937): 	at android.os.Binder.execTransact(Binder.java:454)
,V/BluetoothMasService( 5540): Starting MAS instances
,D/BluetoothAdapter( 5540): 112724080: getState() :  mService = null. Returning STATE_OFF
,E/WifiStateMachine(  937): setWifiState: disabled
I/MailMessageReceiver( 5540): reg:com.android.bluetooth.btservice.AdapterApp@258de7e9 with com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@14aec6e
,W/Settings( 4560): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiStateMachine(  937): Enter handleNetworkDisconnect
I/art     (  937): Explicit concurrent mark sweep GC freed 31838(2MB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 16MB/25MB, paused 12.108ms total 228.375ms
D/PMS     (  937): releaseWL(2108c7e4): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
,E/WifiStateMachine(  937): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - handleNetworkDisconnect - access$12300 - processMessage
,I/MailManager( 5540): MailManager contruct! com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@14aec6e
V/EmailUtils( 5540): Manager Instance is not NULL
,E/WifiStateMachine(  937): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/PMS     (  937): acquireWL(1ab62ed6): PARTIAL_WAKE_LOCK  StartingDockService 0x1 5403 1000 null
,E/WifiStateMachine(  937): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/TelephUtils( 1441): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/AccFlag ( 1441): device_type: 1
D/TelephUtils( 1441): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/AccFlag ( 1441): sku_id=118
,D/WifiStateMachine(  937): Exit handleNetworkDisconnect
I/ActivityManager(  937): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=5606 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a,
E/WifiStateMachine(  937): [MLHD] Error! unhandled message 6 { when=-581ms what=147458 arg1=34 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  937): acquireWL(92564b0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 937 1000 null
E/WifiStateMachine(  937): transitionTo: destState=InitialState
E/WifiStateMachine(  937): handleMessage: new destination call exit/enter
E/WifiStateMachine(  937): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  937): invokeExitMethods: SupplicantStoppingState
E/WifiStateMachine(  937): moveTempStackToStateStack: i=0,j=1
D/PMS     (  937): releaseWL(1ab62ed6): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
E/WifiStateMachine(  937): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=InitialState
E/WifiStateMachine(  937): invokeEnterMethods: InitialState
D/DockEventReceiver( 5403): finishStartingService: stopping service
I/IntentController( 1218): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/WIFI_ICON( 1218): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
W/Settings( 1825): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HtcBtWidget_BTWidgetProvider( 5429): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 5429): updateWidget(context) for widget: 
,D/TransactionService( 5319): Force clearing mTransactionList
D/TransactionService( 5319): Force set service start id to 1
,V/TransactionService( 5319): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 5319): unRegisterForConnectionStateChanges
,D/TransactionService( 5319): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 5319): Destroying TransactionService
,V/TransactionService( 5319): 4-Handling incoming message: { when=-6ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/WISPrService( 5403): >>>>>WISPrService start isConnected = false<<<<<,
,I/ActivityManager(  937): Killing 5022:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  937): killProcessQuiet, pid=5022
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/WISPrService( 5403): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,I/QuickSettingWifi( 1218): receive.wifiState:WIFI_STATE_DISABLED setEnable:true
I/QuickSettingWifi( 1218): receive.wifiConnect:false wifiAPname:null elapse:1,
,I/DeviceManagement( 5576): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=5576 dbg=false s=true
,I/DeviceManagement( 5576): PackageUpdateReceiver: vvv Package added: [com.example.hello]
,W/asset   ( 1484): Copying FileAsset 0x55689c9270 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,W/asset   ( 5199): Copying FileAsset 0x55685f1ac0 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,D/JobSchedulerService(  937): Receieved: android.intent.action.PACKAGE_REMOVED,
,I/ActivityManager(  937): Recipient 5022
,E/Prism.WidgetManager( 1484): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1484): onLoadItems() -
,I/Prism.ItemManager( 1484): loadItems() com.htc.launcher.pageview.WidgetManager@3f4ca7ed -
,I/Prism.ItemManager( 1484): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1484): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,D/TelephUtils( 1441): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50,
,I/ActivityManager(  937): Killing 4724:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/AccFlag ( 1441): sku_id=118
I/Prism.WidgetManager( 5199): onLoadItems() -
I/Prism.ItemManager( 5199): loadItems() com.htc.launcher.pageview.WidgetManager@39014d1e -
I/Prism.ItemManager( 5199): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 5199): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/Process (  937): killProcessQuiet, pid=4724
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  937): Recipient 4724
D/WifiService(  937): Client connection lost with reason: 4
,W/OpenGLRenderer( 1484): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,D/Process (  937): killProcessQuiet, pid=5080,
I/ActivityManager(  937): Killing 5080:com.google.android.apps.magazines/u0a161 (adj 15): empty #17
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  937): Recipient 5080
,D/Process (  937): killProcessQuiet, pid=5178
I/ActivityManager(  937): Killing 5178:com.android.chrome/u0a96 (adj 15): empty #17
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/Tethering(  937): interfaceRemoved wlan0
E/Tethering(  937): attempting to remove unknown iface (wlan0), ignoring
,D/Tethering(  937): interfaceLinkStateChanged p2p0, false
D/Tethering(  937): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  937): WiFiDisplay: getWifidisplayApEnabled=false
,I/ActivityManager(  937): Recipient 5178
,I/ActivityManager(  937): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=5631 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a
,D/TaskPersister(  937): removeObsoleteFile: deleting file=8_task.xml,
,E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL false Token 15 num clients 9
E/WifiTrafficPoller(  937): ENABLE_TRAFFIC_STATS_POLL false Token 15,
,I/PhoneStatusBar( 1218): setImeWindowStatus(false,false),
,D/Tethering(  937): interfaceRemoved p2p0
E/Tethering(  937): attempting to remove unknown iface (p2p0), ignoring
,D/HtcAdjCursorFactory( 5606): Set CursorWindow size to: 4194304 KB, Tid: 5625
,E/SQLiteDatabase( 5606): Failed to open database '/data/user/0/com.htc.android.mail/databases/mail.db'.
E/SQLiteDatabase( 5606): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SQLiteDatabase( 5606): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5606): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5606): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5606): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5606): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5606): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5606): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5606): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5606): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5606): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 5606): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5606): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5606): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5606): 	at com.htc.android.mail.kq.a(MailProvider.java:5368)
E/SQLiteDatabase( 5606): 	at com.htc.android.mail.kq.a(MailProvider.java:5433)
E/SQLiteDatabase( 5606): 	at com.htc.android.mail.MailProvider.query(MailProvider.java:2114)
E/SQLiteDatabase( 5606): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 5606): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 5606): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
E/SQLiteDatabase( 5606): 	at android.os.Binder.execTransact(Binder.java:454)
,E/SQLiteOpenHelper( 5606): Couldn't open mail.db for writing (will try read-only):
E/SQLiteOpenHelper( 5606): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5606): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5606): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteOpenHelper( 5606): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteOpenHelper( 5606): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5606): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5606): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5606): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteOpenHelper( 5606): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteOpenHelper( 5606): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteOpenHelper( 5606): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteOpenHelper( 5606): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 5606): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5606): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187),
E/SQLiteOpenHelper( 5606): 	at com.htc.android.mail.kq.a(MailProvider.java:5368)
E/SQLiteOpenHelper( 5606): 	at com.htc.android.mail.kq.a(MailProvider.java:5433)
E/SQLiteOpenHelper( 5606): 	at com.htc.android.mail.MailProvider.query(MailProvider.java:2114)
E/SQLiteOpenHelper( 5606): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteOpenHelper( 5606): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteOpenHelper( 5606): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
E/SQLiteOpenHelper( 5606): 	at android.os.Binder.execTransact(Binder.java:454)
W/SQLiteOpenHelper( 5606): Opened mail.db in read-only mode
,D/HtcCupdReceiver(Provider)( 5631):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED
,I/ActivityManager(  937): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5655 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a,
D/Process (  937): killProcessQuiet, pid=5226
I/ActivityManager(  937): Killing 5226:com.google.android.apps.plus/u0a167 (adj 15): empty #17
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,D/Settings:HtcWirelessFeatureFlags( 5403): id/is att sku: 118/false
,E/Settings:HtcWrapHeaderInfo( 5403): no such activity!,
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 5403): The wrap header doesn't exist in header list.,
,I/ActivityManager(  937): Recipient 5226,
,E/Settings:HtcWrapHeaderInfo( 5403): updateDevelopment, bPrefShow = true,
,E/Settings:HtcUmcWidgetEnabler( 5403): isSupportMusicChannel(): false,
,E/WifiDataStallTracker(  937): DATA_MONITOR_POLL false Token 2,
,D/EmailUtils( 5540): ============NULL aList========
V/EmailUtils( 5540): <-getEmailAccountIdList
V/BluetoothMasService( 5540): onCreate: mIsEmailEnabled: true
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5403): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5403): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5403): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5403): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5403): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5403): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5403): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5403): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5403): [supportHomeButton]support         :false
D/Process (  937): killProcessQuiet, pid=5199
I/ActivityManager(  937): Killing 5199:com.htc.sense.news/u0a74 (adj 15): empty #17
,D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/ActivityManager(  937): Recipient 5199
,D/BluetoothMasReceiver( 5540): Bluetooth STATE CHANGED to 10
,V/BluetoothMasService( 5540): onDestroy: mIsEmailEnabled: true,
,V/BluetoothSapReceiver( 5540): SapReceiver onReceive 
V/BluetoothSapReceiver( 5540): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 5540):  Bluetooth Adapter state = 10,
V/BluetoothSapReceiver( 5540): startService = false
D/Process (  937): killProcessQuiet, pid=5271
I/ActivityManager(  937): Killing 5271:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 

```
