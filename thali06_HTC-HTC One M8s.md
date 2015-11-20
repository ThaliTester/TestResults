#### Test 50388019aa1a16d_thali06_HTC-HTC One M8s Logs


```
--------- beginning of system
W/ResourcesManager( 4794): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4794): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
--------- beginning of main
V/JNIHelp ( 4794): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
W/ActivityThread( 4794): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 4794): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@6f5ff22: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4794): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 4794): GMSCore installation verified
I/ConfigStore( 4794): Config Database version: 1
I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4794, uid=10159, userID:0
D/WifiDisplayAdapter(  968): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  968):     Client/Owner: Client
D/WifiDisplayAdapter(  968):     GroupId: 
D/WifiDisplayAdapter(  968):     Passphrase: 
D/WifiDisplayAdapter(  968):     SessionId: 0
D/WifiDisplayAdapter(  968):     IP Address: }
D/MediaRouterService(  968): Client com.google.android.music (pid 4794): Registered
D/WifiDisplayAdapter(  968): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  968):     Client/Owner: Client
D/WifiDisplayAdapter(  968):     GroupId: 
D/WifiDisplayAdapter(  968):     Passphrase: 
D/WifiDisplayAdapter(  968):     SessionId: 0
D/WifiDisplayAdapter(  968):     IP Address: }
I/MediaRouter( 4794): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
V/MusicLeanback( 4794): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 4794): type=WIFI subType= reason=null isConnected=true
D/PMS     (  968): releaseWL(2f2d1717): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 null
W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 4
I/NetworkMonitor( 4794): type=WIFI subType= reason=null isConnected=true
I/ActivityManager(  968): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=4855 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=4794, uid=10159, userID:0
I/GHttpClientFactory( 4794): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 4794): Using platform SSLCertificateSocketFactory
W/ResourcesManager( 4855): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/Process (  968): killProcessQuiet, pid=4177
I/ActivityManager(  968): Killing 4177:com.htc.htccupd/u0a13 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  968):  packet count Tx=76 Rx=128
I/ActivityManager(  968): Recipient 4177
I/CalendarProvider2( 4855): Created com.android.providers.calendar.CalendarAlarmManager@1178a34e(com.htc.providers.calendar.HtcCalendarProvider@e737c6f)
D/CalendarProvider2( 4855): wait start:true
D/CalendarProvider2( 4855): wait end:false
D/AutoSetting( 1565): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  968): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=4883 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a
D/AutoSetting( 1565): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1565): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1565): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1565): service - onStartCommand() REMOVE current location bundle
D/AutoSetting( 1565): service - handleMessage() setting current location null
I/ActivityManager(  968): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=4904 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
V/AlarmManager(  968): sending alarm PendingIntent{180b0a9a: PendingIntentRecord{270a9fcb com.htc.mobiledata startService}}, i=com.htc.mobiledata.intent.REQUEST, t=2, cnt=1, w=59861, Int=0
,D/PhoneMonitor( 4883): Register our PhoneStateListener
D/MobileConnectivityChangeReceiver( 4883): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4883): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  968): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=4930 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
D/Process (  968): killProcessQuiet, pid=4223
I/ActivityManager(  968): Killing 4223:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
D/PhoneMonitor( 4883): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
I/HtcModeClient( 3169): handler message = 4011
E/HtcModeClient( 3169): Check connection and retry 4 times.
D/PhoneMonitor( 4883): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/art     (  406): Explicit concurrent mark sweep GC freed 8646(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 199us total 30.645ms
I/art     (  406): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 182us total 25.132ms
I/art     (  406): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 172us total 21.431ms
I/ActivityManager(  968): Recipient 4223
D/PMS     (  968): acquireWL(2ded3d43): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4401 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  968): acquireWL(2b6a84f9): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4401 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  968): releaseWL(2ded3d43): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
I/CheckinService( 4401): Checking schedule, now: 1448020222995 next: 1448016196132
I/CheckinService( 4401): active receiver: enabled
I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=4401, uid=10024, userID:0
D/MdScBoot( 4904): [902.1.] 30@-114952 -> 40
D/MdScBootUi( 4904): [902.1.2.] boot 118
I/CheckinService( 4401): Preparing to send checkin request
I/EventLogService( 4401): Accumulating logs since 1448018959157
I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4401, uid=10024, userID:0
D/MdScSimSt( 4904): [902.1.2.] qry 118: 0+1 running 0
I/iu.SyncManager( 4401): SYNC; picasa accounts
E/cutils-trace( 4927): Error opening trace file: Permission denied (13)
D/NetworkLogImpl( 4401): Loaded NetworkSpeedPredictor
I/iu.Environment( 4401): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 4401): num queued entries: 0
I/iu.UploadsManager( 4401): num updated entries: 0
I/iu.SyncManager( 4401): NEXT; no task
D/ChimeraCfgMgr( 4401): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/ChimeraCfgMgr( 4401): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/ActivityManager(  968): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4978 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/CustomizationManager( 4927): ====startRecUseTime====
D/htc.customization.log.level( 4927):  is 
W/CustomizationLogLevel( 4927): Level value is invalid, use default level 2
D/libc    ( 4503): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 4503): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4503): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 4503): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4503): [NET] android_getaddrinfo_proxy+
D/libc    ( 4503): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
I/DropBoxManagerService(  968): Usage (1282) > Quota (1280)
E/WifiStateMachine(  968): handleMessage: E msg.what=131155
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2462 sc=60 link=72 tx=6.6, 0.0, 0.0  rx=10.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:616244421] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2462 sc=60 link=72 tx=6.6, 0.0, 0.0  rx=10.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:616244424] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  968):  get link layer stats 0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1348): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1348): environment dirty rate=6 [31][2][0]
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative rssi=-56 linkspeed=72
E/WifiConfigStore(  968): updateConfiguration freq=2462 BSSID=c0:ff:d4:d3:aa:48 RSSI=-56 "NG700"WPA_PSK
E/WifiStateMachine(  968): calculateWifiScore freq=2462 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=18.82 txretriesrate=0.00 rxrate=18.49 userTriggerdPenalty0
E/WifiStateMachine(  968):  good link -> stuck count =0
E/WifiStateMachine(  968):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  968):  isHighRSSI       ---> score=65
D/WifiWatchdogStateMachine(  968): RSSI current: 3 new: -56, 3
E/WifiStateMachine(  968): handleMessage: X
D/WIFI_ICON( 1222): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
I/GLSUser ( 1953): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1953): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1953): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1953): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1953): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4503): [NET] android_getaddrinfo_proxy-, success
I/CheckinRequestBuilder( 4401): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  968): Killing 4095:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  968): killProcessQuiet, pid=4095
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/WifiService(  968): New client listening to asynchronous messages
E/WifiTrafficPoller(  968): ADD_CLIENT: 7
I/Babel   ( 4503): connection state changed from UNKNOWN to CONNECTED
D/CustomizationManager( 4927):  Read ACC file spent 0.071 (s)
D/CIDMapFileReader( 4927): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4927): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4927): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4927): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4927): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4927): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4927): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4927): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 4927): Parsing tag category name = system
I/CustomizationCIDLoader( 4927): Parsing tag category name = application
I/CustomizationCIDLoader( 4927): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4927): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4927): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4927): Parsing tag category name = Settings
I/CustomizationCIDLoader( 4927): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4927): add string-array item, value = 42507
I/CustomizationCIDLoader( 4927): add string-array item, value = 21902
I/CustomizationCIDLoader( 4927): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 4927): add string-array item, value = 23420
I/CustomizationCIDLoader( 4927): add string-array item, value = 22299
I/CustomizationCIDLoader( 4927): add string-array item, value = 24002
I/CustomizationCIDLoader( 4927): add string-array item, value = 23210
I/CustomizationCIDLoader( 4927): add string-array item, value = 23205
I/CustomizationCIDLoader( 4927): add string-array item, value = 23806
I/CustomizationCIDLoader( 4927): add string-array item, value = 23430
I/CustomizationCIDLoader( 4927): add string-array item, value = 23408
I/CustomizationCIDLoader( 4927): add string-array item, value = 27205
I/CustomizationCIDLoader( 4927): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 4927): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 4927): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 4927): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 4927): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 4927): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 4927): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 4927): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 4927): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 4927): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 4927): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 4927): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 4927):  Read CID file spent 0.118 (s)
D/CustomizationManager( 4927):  All configurations done spent 0.118 (s)
I/ActivityManager(  968): Recipient 4095
I/ActivityManager(  968): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4401): Failed to find provider info for com.google.android.wearable.settings
I/ActivityManager(  968): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 pid 4927 on display 0
W/asset   (  968): Copying FileAsset 0x55771f0e40 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/PMS     (  968): acquireHCC(26c7fd33): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 968 1000 null
D/PMS     (  968): acquireHCC(3abe88f0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 968 1000 null
D/PMS     (  968): acquireWL(2a799e69): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 968 1000 null
I/ActivityManager(  968): Killing 4270:com.android.settings:remote/1000 (adj 15): empty #17
D/Process (  968): killProcessQuiet, pid=4270
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
W/Kids    ( 4401): [AccountUtils] Account not ready
W/Kids    ( 4401): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4401): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4401): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4401): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4401): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4401): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4401): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4401): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4401): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4401): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4401): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4401): 	at java.lang.Thread.run(Thread.java:818)
I/AnimationUtil(  968): isHTCRecent(HelloWorld/Recent screens.)/9
I/ActivityManager(  968): Recipient 4270
I/FeedHostManager( 1472): [onPause]
I/FeedProviderManager( 1472): onPause
I/FeedHostManager( 1472): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@38190494
I/SocialFeedProvider( 1472): +onPause
I/SocialFeedProvider( 1472): -onPause
E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  968):  packet count Tx=81 Rx=132
D/DotMatrix( 1302): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1302): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/HtcSystemUPManager(  968): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/RemoteViews( 1222): reapply : com.google.android.gms 3 40
I/ActivityManager(  968): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5004 uid=10373 gids={50373, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/StatusBarManagerService(  968): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  968): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  968): hiding MENU key
W/asset   ( 5004): Copying FileAsset 0xac8d5e98 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/TrimMemoryManager( 1472): [trimMemory] 20
,I/CalendarProvider2( 4855): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
W/ContentResolver( 4855): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
D/Process (  968): killProcessQuiet, pid=4294
I/ActivityManager(  968): Killing 4294:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/VoldConnector(  968): SND -> {20 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
W/ContextImpl( 4978): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
I/GAv4    ( 4978): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4978):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4978):   adb logcat -s GAv4
D/VoldConnector(  968): SND -> {21 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl( 4978): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
D/VoldConnector(  968): SND -> {22 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
W/ContextImpl( 4978): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
D/VoldConnector(  968): SND -> {23 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl( 4978): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
I/ActivityManager(  968): Recipient 4294
I/WebViewFactory( 5004): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
W/GAv4    ( 4978): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 4978): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 4978): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/LibraryLoader( 5004): Time to load native libraries: 12 ms (timestamps 921-933)
I/LibraryLoader( 5004): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5004): Binding Chromium to main looper Looper (main, tid 1) {e737c6f}
I/LibraryLoader( 5004): Expected native library version number "",actual native library version number ""
I/chromium( 5004): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5004): Initializing chromium process, singleProcess=true
W/art     ( 5004): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5004): ApplicationContext is null in ApplicationStatus
W/global  ( 4978): [apache-http] Connection GC has been deprecated!
I/GLSUser ( 1953): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1953): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1953): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1953): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/global  ( 4978): [apache-http] Connection GC has been deprecated!
V/GLSActivity( 1953): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/CheckinRequestBuilder( 4401): awaiting user notification for token
I/RemoteViews( 1222): reapply : com.google.android.gms 5 40
D/DotMatrix( 1302): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1302): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/chromium( 5004): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5004): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5004): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5004): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 5004): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 5004): Build Date: 03/09/15 Mon
I/Adreno-EGL( 5004): Local Branch: 
I/Adreno-EGL( 5004): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 5004): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 5004):                  d74aa161a12b9c6fc6332151
I/ActivityManager(  968): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5052 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
W/ResourcesManager( 5052): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5052): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/System.err(  968): java.lang.Throwable: stack dump
W/System.err(  968): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  968): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  968): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  968): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  968): Message: MESSAGE_REGISTER_ADAPTER
I/WebViewFactory( 4978): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
D/BluetoothAdapter( 5004): 553481576: getState(). Returning 12
I/MultiDex( 5052): VM with version 2.1.0 has multidex support
I/MultiDex( 5052): install
I/MultiDex( 5052): VM has multidex support, MultiDex support library is disabled.
I/LibraryLoader( 4978): Time to load native libraries: 5 ms (timestamps 1188-1193)
I/LibraryLoader( 4978): Expected native library version number "",actual native library version number ""
V/JNIHelp ( 5052): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
V/WebViewChromiumFactoryProvider( 4978): Binding Chromium to main looper Looper (main, tid 1) {d0ae910}
I/LibraryLoader( 4978): Expected native library version number "",actual native library version number ""
I/chromium( 4978): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/ActivityThread( 5052): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5052): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@18d8b2f8: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5052): Installed default security provider GmsCore_OpenSSL
W/art     ( 5004): Attempt to remove local handle scope entry from IRT, ignoring
I/BrowserStartupController( 4978): Initializing chromium process, singleProcess=true
W/AwContents( 5004): onDetachedFromWindow called when already detached. Ignoring
W/art     ( 4978): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4978): ApplicationContext is null in ApplicationStatus
D/SystemWebViewEngine( 5004): CordovaWebView is running on device made by: HTC
W/art     ( 5004): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5004): Attempt to remove local handle scope entry from IRT, ignoring
I/art     (  968): Explicit concurrent mark sweep GC freed 15280(796KB) AllocSpace objects, 4(272KB) LOS objects, 33% free, 16MB/25MB, paused 3.014ms total 201.142ms
D/BluetoothManagerService(  968): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2cdb7b62:true
W/chromium( 5004): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
W/chromium( 4978): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 4978): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4978): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 4978): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 4978): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 4978): Build Date: 03/09/15 Mon
I/Adreno-EGL( 4978): Local Branch: 
I/Adreno-EGL( 4978): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 4978): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 4978):                  d74aa161a12b9c6fc6332151
D/FindExtension( 5004): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/WVCdm   (  400): CdmEngine::OpenSession
I/WVCdm   (  400): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  400): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
D/DrmWidevineDash(  400): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  400): Service_Initialize: starts!
D/QSEECOMAPI: (  400): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  400): App is not loaded in QSEE
E/QSEECOMAPI: (  400): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  400): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  400): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  400): App is not loaded in QSEE
D/QSEECOMAPI: (  400): Loaded image: APP id = 6
D/DrmWidevineDash(  400): Service_Initialize: ends! returns 0
D/QSAPPSVER(  400): qsapps_get_capabilities: Capability from secure side: 0x0
D/QSAPPSVER(  400): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  400): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf455b000
E/DrmWidevineDash(  400): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf455b000
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
W/AudioManagerAndroid( 4978): Requires BLUETOOTH permission
D/DrmLibTime(  518): got the req here! ret=0
D/DrmLibTime(  518): command id, time_cmd_id = 770
D/DrmLibTime(  518): time_getutcsec starts!
D/DrmLibTime(  518): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  518): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  518): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  518): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  518): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  518): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  518): QSEE Time Listener: Retrieved Android system time: 1448020224
D/DrmLibTime(  518): time_getutcsec returns 0, sec = 1448020224; nsec = 0
D/DrmLibTime(  518): time_getutcsec finished! 
D/DrmLibTime(  518): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  518): before calling ioctl to read the next time_cmd
E/QC-time-services(  430): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  400): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): hlos api version =  9
D/DrmWidevineDash(  400): tz api version =  9
D/DrmWidevineDash(  400): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  400): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
I/NSApplication( 4978): Starting up...
I/InputMethodManager( 5004): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@62d0898, mServedView=org.apache.cordova.engine.SystemWebView{175b28f1 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@13b00cd6
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  400): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/ActivityManager(  968): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=5118 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/DrmWidevineDash(  400): OEMCrypto_OpenSession: starts! SID=0xf4884928
D/DrmWidevineDash(  400): OEMCrypto_OpenSession Session ID = 0
I/ActivityManager(  968): Killing 4317:com.android.smith/1000 (adj 15): empty #17
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  400): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  400): OEMCrypto_GetRandom: starts! randomData=0xab5cdb18, dataLength=8
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_GetRandom: ends! returns 0
D/Process (  968): killProcessQuiet, pid=4317
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
D/DrmWidevineDash(  400): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab5e1e78, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
I/InputMethodManagerService(  968): Disable input method client, pid=1472
D/DrmWidevineDash(  400): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
D/StatusBarManagerService(  968): swetImeWindowStatus vis=0 backDisposition=0
I/WVCdm   (  400): CdmEngine::QueryKeyControlInfo
I/InputMethodManagerService(  968): Enable input method client, pid=5004
W/WVCdm   (  400): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  400): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  400): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  400): OEMCrypto_GetDeviceID: starts! deviceID=0xab609a38, idLength=0xf46846f8
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
I/PhoneStatusBar( 1222): setImeWindowStatus(false,false)
E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  968):  packet count Tx=81 Rx=133
E/WifiTrafficPoller(  968): notifying of data activity 1
D/WIFI_ICON( 1222): WifiActivity: 1
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  400): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  400): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  400): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  400): OEMCrypto_GetHDCPCapability: starts!, current = 0xf468470e, maximum = 0xf468470f
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  400): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): hlos api version =  9
D/DrmWidevineDash(  400): tz api version =  9
D/DrmWidevineDash(  400): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  400): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf468477c
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  400): PrepareKeyRequest: nonce=824677495
D/DrmWidevineDash(  400): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab5e5b58
D/DrmWidevineDash(  400): message_length=1611, signature=0xab5e2368, signature_length=0xf46846dc
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
I/art     ( 5052): Background partial concurrent mark sweep GC freed 17079(1047KB) AllocSpace objects, 2(40KB) LOS objects, 57% free, 3MB/7MB, paused 6.262ms total 40.987ms
W/XT9_C   ( 1374): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1374): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1374): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1374): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/BindingManager( 5004): Cannot call determinedVisibility() - never saw a connection for the pid: 5004
I/chromium( 5004): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
I/ActivityManager(  968): Recipient 4317
D/JsMessageQueue( 5004): Set native->JS mode to OnlineEventsBridgeMode
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  400): CdmEngine::CloseSession
D/DrmWidevineDash(  400): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  400): L3 Terminate.
D/DrmWidevineDash(  400): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): Service_Uninitialize: starts!
D/QSEECOMAPI: (  400): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  400): QSEECom_shutdown_app, app_id = 6
D/DrmWidevineDash(  400): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  400): OEMCrypto_Terminate: ends! returns 0
E/AndroidProtocolHandler( 5004): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/PMS     (  968): releaseWL(2a799e69): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/ActivityManager(  968): Displayed com.example.hello/.MainActivity: +1s172ms
,I/GAV2    ( 4622): Thread[GAThread,5,main]: No campaign data found.,
,I/GAv4-SVC( 4401): Google Analytics 7.8.99 is starting up.,
,E/cutils-trace( 5146): Error opening trace file: Permission denied (13),
,I/dex2oat ( 5146): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=36 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 5146): dex2oat: override thread count:4
,D/jxcore_app_log( 5004): JniHelper::setJavaVM(0xab7688f8), pthread_self() = -1398076776
,D/JX-Cordova( 5004): jxcore cordova android initializing
,I/dex2oat ( 5146): dex2oat took 56.126ms (threads: 4)
,I/Adreno-EGL( 5052): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 5052): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 5052): Build Date: 03/09/15 Mon
I/Adreno-EGL( 5052): Local Branch: 
I/Adreno-EGL( 5052): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 5052): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 5052):                  d74aa161a12b9c6fc6332151
,I/art     ( 1953): Explicit concurrent mark sweep GC freed 9573(492KB) AllocSpace objects, 8(672KB) LOS objects, 49% free, 4MB/8MB, paused 1.017ms total 44.462ms
W/jxcore-log( 5004): Initializing JXcore engine
W/jxcore-log( 5004): JXcore engine is ready
,W/jxcore-log( 5004): Starting JXcore engine,
,I/ActivityManager(  968): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=5159 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  968): Killing 4247:com.android.settings/1000 (adj 15): empty #17
D/Process (  968): killProcessQuiet, pid=4247
,D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/Adreno-EGL( 5052): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 5052): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 5052): Build Date: 03/09/15 Mon
I/Adreno-EGL( 5052): Local Branch: 
I/Adreno-EGL( 5052): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 5052): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 5052):                  d74aa161a12b9c6fc6332151
,I/ActivityManager(  968): Recipient 4247
,W/jxcore-log( 5004): Platform android
W/jxcore-log( 5004): 
W/jxcore-log( 5004): Process ARCH arm
W/jxcore-log( 5004): 
,W/ResourcesManager( 5159): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,I/jxcore-log( 5004): JXcore Cordova bridge is ready!,
I/jxcore-log( 5004): 
W/jxcore-log( 5004): JXcore engine is started
,E/jxcore-log( 5004): >> HTC-HTC One M8s,
E/jxcore-log( 5004): 
,I/jxcore-log( 5004): Total memory 1931808768,
I/jxcore-log( 5004): 
I/jxcore-log( 5004): Free memory 84639744
I/jxcore-log( 5004): 
I/jxcore-log( 5004): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5004): 
I/jxcore-log( 5004): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5004): 
,I/jxcore-log( 5004): userPath [ 'www' ],
I/jxcore-log( 5004): 
,I/jxcore-log( 5004): Size 1080 1776
I/jxcore-log( 5004): 
,I/jxcore-log( 5004): Screen Brightness 142,
I/jxcore-log( 5004): 
E/jxcore-log( 5004): Dummy Error Log.
E/jxcore-log( 5004): 
,I/WVCdm   (  400): CdmEngine::OpenSession
I/WVCdm   (  400): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  400): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  400): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  400): Service_Initialize: starts!
D/QSEECOMAPI: (  400): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  400): App is not loaded in QSEE
E/QSEECOMAPI: (  400): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  400): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  400): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  400): App is not loaded in QSEE
D/QSEECOMAPI: (  400): Loaded image: APP id = 7
D/DrmWidevineDash(  400): Service_Initialize: ends! returns 0
D/QSAPPSVER(  400): qsapps_get_capabilities: Capability from secure side: 0x0
D/QSAPPSVER(  400): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  400): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf455b000
E/DrmWidevineDash(  400): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf455b000
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/DrmLibTime(  518): got the req here! ret=0
D/DrmLibTime(  518): command id, time_cmd_id = 770
D/DrmLibTime(  518): time_getutcsec starts!
D/DrmLibTime(  518): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  518): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  518): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  518): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  518): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  518): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  518): QSEE Time Listener: Retrieved Android system time: 1448020225
D/DrmLibTime(  518): time_getutcsec returns 0, sec = 1448020225; nsec = 0
D/DrmLibTime(  518): time_getutcsec finished! 
D/DrmLibTime(  518): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  518): before calling ioctl to read the next time_cmd
E/QC-time-services(  430): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  400): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  400): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): hlos api version =  9
D/DrmWidevineDash(  400): tz api version =  9
D/DrmWidevineDash(  400): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  400): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  400): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  400): OEMCrypto_OpenSession: starts! SID=0xf4884928
D/DrmWidevineDash(  400): OEMCrypto_OpenSession Session ID = 0
,D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  400): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  400): OEMCrypto_GetRandom: starts! randomData=0xab5bb610, dataLength=8
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  400): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab5e1e78, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  400): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  400): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  400): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  400): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  400): OEMCrypto_GetDeviceID: starts! deviceID=0xab609a78, idLength=0xf47846f8
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  400): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  400): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  400): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  400): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  400): OEMCrypto_GetHDCPCapability: starts!, current = 0xf478470e, maximum = 0xf478470f
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  400): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): hlos api version =  9
D/DrmWidevineDash(  400): tz api version =  9
D/DrmWidevineDash(  400): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  400): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf478477c
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  400): PrepareKeyRequest: nonce=3280756724
D/DrmWidevineDash(  400): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab5e5b58
D/DrmWidevineDash(  400): message_length=1646, signature=0xab5e61d0, signature_length=0xf47846dc
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/PMS     (  968): releaseHCC(26c7fd33): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  968): releaseHCC(3abe88f0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null,
,D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  400): CdmEngine::CloseSession
D/DrmWidevineDash(  400): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_CloseSession: ends! returns 0
,I/WVCdm   (  400): L3 Terminate.
D/DrmWidevineDash(  400): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): Service_Uninitialize: starts!
D/QSEECOMAPI: (  400): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  400): QSEECom_shutdown_app, app_id = 7
,D/DrmWidevineDash(  400): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  400): OEMCrypto_Terminate: ends! returns 0
,I/CheckinRequestBuilder( 4401): Classify the device as Phone.
,I/SocialFeedProvider( 1472): +disConnect socialManager,
I/SocialFeedProvider( 1472): disconnect socialManager
,I/SocialFeedProvider( 1472): -disConnect socialManager
,I/art     ( 4401): Explicit concurrent mark sweep GC freed 14846(1256KB) AllocSpace objects, 25(500KB) LOS objects, 47% free, 4MB/8MB, paused 895us total 60.660ms
,I/ActivityManager(  968): Killing 4375:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  968): killProcessQuiet, pid=4375
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  968):  packet count Tx=81 Rx=133
,E/WifiTrafficPoller(  968): notifying of data activity 0
D/WIFI_ICON( 1222): WifiActivity: 0
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/ActivityManager(  968): Recipient 4375
,I/jxcore-log( 5004): getBuffer is called!!!!,
I/jxcore-log( 5004): 
,I/ActivityManager(  968): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=5194 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a,
,D/libc    ( 4401): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,D/libc    ( 4401): [NET] android_getaddrinfofornet-, err=8,
,D/libc    ( 4401): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024,
D/libc    ( 4401): [NET] android_getaddrinfofornet-, pass to proxy,
D/libc    ( 4401): [NET] android_getaddrinfo_proxy+
D/libc    ( 4401): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,V/AlarmManager(  968): sending alarm PendingIntent{bdea9a4: PendingIntentRecord{3e56630d com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1448020225777, Int=0,
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4401): [NET] android_getaddrinfo_proxy-, success
,I/ImageRamCache( 5194): create image Cache, size: 31457280.,
I/ImageRamCache( 5194): [resize] ImageRamCache resized to: 30Mb.
I/ImageRamCache( 5194): create image Cache, size: 31457280.
,I/FeedSettings( 5194): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
,I/FeedSettings( 5194): GroupBudget 0.500000 0.380000
,I/FeedSettings( 5194): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 5194): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 5194): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 5194): loadGridSize() with Alternative
,D/libc    ( 4401): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,D/libc    ( 4401): [NET] android_getaddrinfofornet-, err=8
,D/CustomHighlightReceiver( 5194): [custom highlight] onReceive
,D/libc    ( 4401): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
,D/libc    ( 4401): [NET] android_getaddrinfofornet-, err=8,
D/libc    ( 4401): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
I/ActivityManager(  968): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=5222 uid=10035 gids={50035, 9997} abi=arm64-v8a
D/libc    ( 4401): [NET] android_getaddrinfofornet-, err=8,
,I/SocialManager[SocialBiLogHelper]( 5194): action: com.htc.sense.hsp.HANDLE_ULOG
,I/SocialManager[SocialBiLogHelper]( 5194): last commit ulog time 1448013060829
I/SocialManager[SocialBiLogHelper]( 5194): skip commit this time
D/CustomHighlightService( 5194): [custom highlight] onHandleIntent
,D/NewsDB  ( 5194): set custom highlight []
,I/CheckinTask( 4401): Sending checkin request (8443 bytes)
,E/WifiDataStallTracker(  968): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  968): updateDataStallInfo: mDataStallTxRxSum={txSum=76 rxSum=55} preTxRxSum={txSum=33 rxSum=26}
D/WifiDataStallTracker(  968): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  968): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,D/CustomHighlightService( 5194): [custom highlight] set tags 
,D/Process (  968): killProcessQuiet, pid=4338,
,I/ActivityManager(  968): Killing 4338:com.android.vending/u0a72 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
,I/ActivityManager(  968): Recipient 4338
,I/ActivityManager(  968): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=5248 uid=10076 gids={50076, 9997} abi=arm64-v8a,
D/Process (  968): killProcessQuiet, pid=3838
I/ActivityManager(  968): Killing 3838:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,E/WifiStateMachine(  968): handleMessage: E msg.what=131155
,E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2462 sc=60 link=72 tx=18.8, 0.0, 0.0  rx=18.5 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:616247434] gl hn u24 rssi=-51 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
,E/WifiStateMachine(  968):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2462 sc=60 link=72 tx=18.8, 0.0, 0.0  rx=18.5 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:616247436] gl hn u24 rssi=-51 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine(  968):  get link layer stats 0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1348): wlan0: Control interface command 'SIGNAL_POLL'
I/ActivityManager(  968): Recipient 3838
,I/wpa_supplicant( 1348): environment dirty rate=11 [18][2][0]
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative rssi=-57 linkspeed=72
E/WifiConfigStore(  968): updateConfiguration freq=2462 BSSID=c0:ff:d4:d3:aa:48 RSSI=-56 "NG700"WPA_PSK
,E/WifiStateMachine(  968): calculateWifiScore freq=2462 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=17.91 txretriesrate=0.00 rxrate=15.74 userTriggerdPenalty0
,E/WifiStateMachine(  968):  good link -> stuck count =0
E/WifiStateMachine(  968):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  968):  isHighRSSI       ---> score=65
,E/WifiStateMachine(  968): handleMessage: X
,D/WifiWatchdogStateMachine(  968): RSSI current: 3 new: -57, 3
,D/WIFI_ICON( 1222): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/ActivityManager(  968): Killing 3576:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  968): killProcessQuiet, pid=3576
,D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/CheckinRequestBuilder( 4401): Checkin reason type: 8 attempt count: 1,
,I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService, state=2, flag=1, pid=4401, uid=10024, userID:0,
I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateActivity, state=2, flag=1, pid=4401, uid=10024, userID:0,
I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver, state=2, flag=1, pid=4401, uid=10024, userID:0,
,I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$Receiver, state=2, flag=1, pid=4401, uid=10024, userID:0
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 11 num clients 7,
D/WIFI_ICON( 1222): WifiActivity: 3
E/WifiTrafficPoller(  968):  packet count Tx=96 Rx=145
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiTrafficPoller(  968): notifying of data activity 3
,I/ActivityManager(  968): Recipient 3576
,D/SMSBackup( 5248): Got a database change event
I/ActivityManager(  968): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4401): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  968): Start proc com.htc.sense.mms for broadcast com.htc.sense.mms/.ui.MessagingShortcutReceiver: pid=5270 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
,W/SystemReader(  968): Cannot find grip_rejection_width, use default value instead,
,D/AccTypeManager( 1713): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,W/ResourcesManager( 1429): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/AccTypeManager( 1713): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/Prism.ItemManager( 1472): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,W/Prism.AllAppsManager( 1472): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/Prism.ItemManager( 1472): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/ResourcesManager(  968): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,I/Launcher( 1472): Deferring update until onResume
,D/Launcher( 1472): waitUntilResume // bindAppsUpdated
,I/Prism.ItemManager( 5194): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 5194): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/ActivityManager(  968): Killing 4538:com.google.android.youtube/u0a176 (adj 15): empty #17
D/Process (  968): killProcessQuiet, pid=4538
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/AccTypeManager( 1713): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/PhoneApp( 1429): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,E/ExternalAccountType( 1713): Unsupported attribute readOnly
,W/HtcWrapAdjustableCursorFactory( 5270): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.
,D/MessageFrequencyProvider( 5270): onCreate
,W/PackageManager(  968): Unable to load service info ResolveInfo{141add21 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
W/PackageManager(  968): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  968): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  968): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  968): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  968): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  968): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169),
W/PackageManager(  968): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
,W/PackageManager(  968): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  968): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  968): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  968): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  968): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  968): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  968): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  968): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  968): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/ActivityManager(  968): Recipient 4538,
,I/BackupManagerService(  968): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService},
,V/GetPrviateResource( 5270): GetPrviateResource,
V/GetPrviateResource( 5270): GetPrviateResource,
,D/MessageCustFlag( 5270): sense_version=6.0,
,D/BTAccessoryUtil( 5270): createReceiver
,D/BTAccessoryUtil( 5270): registerReceiver return intent = null
,D/MessageCustFlag( 5270): sku_id=118
,D/HtcBuildUtils( 5270): getRATByHtcTelephonyCapability:1,
,W/SystemReader( 5270): Cannot find qct_8960_interface, use default value instead
,I/GCoreNlp( 1829): shouldConfirmNlp, NLP off. Ensuring opt-in disabled,
,D/MmsConfig( 5270): packageName: com.htc.vvm.att does not exist
D/MessageCustFlag( 5270): sku_id=118
,D/MessagingShortcutReceiver( 5270): keep hiding shortcut bubble
,D/MessagingShortcut( 5270): updateMsgShortcut, msg count> -1,
,D/SettingsManager( 5270): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@3effd7c
,D/MessagingShortcut( 5270): After query: 0,
D/MessagingShortcut( 5270): mPresentUnreadCount: -1
D/MessageUtils( 5270): [getShortcut] com.htc.sense.mms.ui.ConversationList, false
D/MessagingShortcut( 5270): setMsgShortcutDrawable> 0, false
,D/MessagingShortcut( 5270): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2,
,D/DotMatrix( 1302): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1302): [EventService] reorderNotification, total:0
D/DotMatrix( 1302): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1302): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/ActivityManager(  968): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=5297 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a
,D/Process (  968): killProcessQuiet, pid=4622
I/ActivityManager(  968): Killing 4622:com.google.android.gm/u0a106 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  968): Recipient 4622,
,D/LocationProviderProxy(  968): applying state to connected service
D/PMS     (  968): acquireWL(9d9c166): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1829 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  968): releaseWL(9d9c166): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,V/GmsNetworkLocationProvi( 1829): DISABLE
,W/ResourcesManager( 5297): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
D/LocationProviderProxy(  968): applying state to connected service
,D/PMS     (  968): acquireWL(5889ca7): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1829 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): acquireWL(b0fc554): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1829 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  968): releaseWL(5889ca7): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(b0fc554): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  968): acquireWL(36ceccfd): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1829 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(36ceccfd): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/TodoTaskshortcut( 5297): update TASK shortcut>
,I/GLSUser ( 1953): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1953): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1953): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1953): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1953): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  968): acquireWL(bbf9eb5): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 5297 10069 null
,D/PMS     (  968): acquireWL(17efe94a): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 5297 10069 null
W/CheckinRequestBuilder( 4401): awaiting user notification for token
D/DotMatrix( 1302): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1302): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1222): reapply : com.google.android.gms 3 40
,D/PMS     (  968): releaseWL(bbf9eb5): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,E/TodoTaskNotifyService( 5297): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
,W/System.err( 5297): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
W/System.err( 5297): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 5297): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 5297): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5297): 	at android.os.Looper.loop(Looper.java:155)
W/System.err( 5297): 	,at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  968): releaseWL(17efe94a): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,W/NotifyReceiver( 5297): stopSelfResult true
,D/Process (  968): killProcessQuiet, pid=4697,
I/ActivityManager(  968): Killing 4697:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/CheckinRequestBuilder( 4401): Classify the device as Phone.
,D/PMS     (  968): acquireWL(2c6d49d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1953 10024 WorkSource{10024 com.google.android.gms},
,I/ActivityManager(  968): Recipient 4697
,D/MtpReceiver( 3796): [MTP][handleUsbStateAsync]+,
D/MtpReceiver( 3796): [MTP][handleUsbStateAsync]1:1-
D/MtpReceiver( 3796): [MTP][handleUsbState]+
,D/PMS     (  968): releaseWL(2c6d49d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 11 num clients 7
,E/WifiTrafficPoller(  968):  packet count Tx=96 Rx=146
D/WIFI_ICON( 1222): WifiActivity: 1
E/WifiTrafficPoller(  968): notifying of data activity 1,
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/ActivityManager(  968): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=5324 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a,
D/MtpReceiver( 3796): [MTP][scanExternalVolumeIfNeed] scan external volume
,D/MtpService( 3796): updating state; isCurrentUser=true, mMtpLocked=false
D/MtpReceiver( 3796): [MTP][handleUsbState]-
D/MtpReceiver( 3796): [MTP][handleMessage]-
D/MtpDatabase( 3796): TotalSize=1886532,MediaCacheLimit=6000
,D/PMS     (  968): acquireWL(20fbfd97): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 4401 10024 null
D/MtpService( 3796): [isMtpConnected] connected: true
,I/CheckinTask( 4401): Checkin success: https://android.clients.google.com/checkin (1 requests sent),
,I/CheckinService( 4401): Checking schedule, now: 1448020227542 next: 1448557059517,
I/CheckinService( 4401): active receiver: disabled,
,I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4401, uid=10024, userID:0,
,D/PMS     (  968): releaseWL(2b6a84f9): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
,E/MediaScannerService( 3796): [onStartCommand] --- Should not be here, redirect request. ----,
E/MediaScannerService( 3796): [handleMessage] --- Should not be here, ignore request. ----
D/SyncApplication( 5324): Loading default preferences,
,W/Resources( 5324): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a},
,D/PMS     (  968): acquireWL(1a2457a2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null,
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  968): n_update end
D/DotMatrix( 1302): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  968): releaseWL(1a2457a2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1302): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiService(  968): New client listening to asynchronous messages
D/DotMatrix( 1302): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  968): plugged=true pluggin=true
D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/PowerUI ( 1222): closing low battery warning: level=100
D/HeadsetStateMachine( 3073): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  968): updateBatteryInfo
D/UsbnetService(  968): onReceive BATTERY_CHANGED
D/WifiController(  968): battery changed pluggedType: 2
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  968): runPSCheck
D/UsbnetService(  968): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  968): Checking...
E/WifiTrafficPoller(  968): ADD_CLIENT: 8
I/HtcPowerSaver(  968): >> updateStatus
D/WifiController(  968): handleMessage: E msg.what=155652
,D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  968): processMsg: DeviceActiveState
I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  968): processMsg: StaEnabledState
I/HtcPowerSaver(  968): << updateStatus
D/WifiController(  968): processMsg: DefaultState
D/WifiController(  968): handleMessage: X
,D/SyncApplication( 5324): Overriding preferences with custom values
,I/art     (  968): Explicit concurrent mark sweep GC freed 22146(1215KB) AllocSpace objects, 3(124KB) LOS objects, 33% free, 16MB/25MB, paused 1.541ms total 168.539ms
I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,E/MediaScannerServiceEx( 3796): [getStorageMaskIdFromPath] path is null
D/MediaScannerServiceEx( 3796): [ServiceHandler][handleMessage] , action: null, Id: 0, path: /storage/emulated/0
,D/MediaScannerServiceEx( 3796): [handleExternalVolume] ext storage
,D/MediaProviderUtils( 3796): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3796): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3796): calcVolumeId: /storage/usb
,D/SyncApplication( 5324): Updating preferences succeeded
D/MediaScannerServiceEx( 3796): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
,D/MediaScannerServiceEx( 3796): [AliveExtStorageRows]+65537, 11223344
,E/SyncApplication( 5324): Application created.
,D/MediaProvider( 3796): [update][5]#0#
,I/iu.UploadsManager( 4401): End new media; added: 0, uploading: 0, time: 220 ms
D/MediaProvider( 3796): [update][1]#0#
D/PMS     (  968): releaseWL(20fbfd97): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 null
,W/VolumeInfo( 5324): Unable to read mount points,
W/VolumeInfo( 5324): java.io.FileNotFoundException: /etc/vold.fstab: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 5324): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/VolumeInfo( 5324): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/VolumeInfo( 5324): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/VolumeInfo( 5324): 	at java.io.FileReader.<init>(FileReader.java:66)
W/VolumeInfo( 5324): 	at com.nero.android.common.VolumeInfo.getVolumeMountPoints(VolumeInfo.java:194)
W/VolumeInfo( 5324): 	at com.nero.android.common.VolumeInfo.getVolumes(VolumeInfo.java:153)
W/VolumeInfo( 5324): 	at com.nero.android.common.VolumeInfo.initializeVolumeIDs(VolumeInfo.java:474)
W/VolumeInfo( 5324): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:51)
W/VolumeInfo( 5324): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:1)
W/VolumeInfo( 5324): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/VolumeInfo( 5324): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/VolumeInfo( 5324): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/VolumeInfo( 5324): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/VolumeInfo( 5324): 	at java.lang.Thread.run(Thread.java:818)
W/VolumeInfo( 5324): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 5324): 	at libcore.io.Posix.open(Native Method)
W/VolumeInfo( 5324): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/VolumeInfo( 5324): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/VolumeInfo( 5324): 	... 13 more
V/VolumeInfo( 5324): Found 0 mount point(s)
V/VolumeInfo( 5324): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 5324): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
D/VolumeInfo( 5324): Read the volume-id from the sd card: {9B5E872B-8520-47C6-8BD3-3081C2E38355}
W/VolumeInfo( 5324): Can not create volume ID for unmounted volume null
D/MediaProvider( 3796): [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
D/MtpService( 3796): [sendStorageAdded] Already send to MTP: /storage/emulated/0
D/MediaProvider( 3796): [update][22]#1#
I/CalendarDefines( 5324): getNewCalendarAuthority()...
D/MediaScannerServiceEx( 3796): [AliveExtStorageRows]-0, 0
D/PMS     (  968): acquireWL(4144bee): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3796 10017 null
D/MediaScanner( 3796): =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
D/SyncApplication( 5324): enableAppOperation()+
I/PackageManager(  968):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=5324, uid=10005, userID:0
D/SyncApplication( 5324): enableAppOperation()-
W/PackageManager(  968): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  968):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=5324, uid=10005, userID:0
W/PackageManager(  968): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/HTCUtilities( 5324): isNeorSinged() + 
,D/HTCUtilities( 5324): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>,
,D/HTCUtilities( 5324): isNeorSinged() return false
,D/CDMountReceiver( 5324): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/CDMountReceiver( 5324): USB connected to PC
,D/FOTAReceiver( 5324): onReceive() enter 
,D/FOTAReceiver( 5324): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/Process (  968): killProcessQuiet, pid=4664,
I/ActivityManager(  968): Start proc com.android.settings for broadcast com.android.settings/.NSReceiver: pid=5356 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  968): Killing 4664:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
,I/HtcModeClient( 3169): handler message = 4011
,E/HtcModeClient( 3169): Check connection and retry 5 times.
,I/ActivityManager(  968): Recipient 4664,
D/WifiService(  968): Client connection lost with reason: 4
,I/Prism.ItemManager( 1472): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1472): loadItems() com.htc.launcher.pageview.WidgetManager@30ca3377 +
I/Prism.WidgetManager( 1472): onLoadItems() +
,I/Prism.ItemManager( 5194): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
I/Prism.ItemManager( 5194): loadItems() com.htc.launcher.pageview.WidgetManager@17396603 +
I/Prism.WidgetManager( 5194): onLoadItems() +
,W/ResourcesManager( 1472): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 5356): -onCreate()
,W/ResourcesManager( 5194): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,V/Settings:HtcSettingsApplication( 5356): [5356/5356] onCreate(),
D/MediaProvider( 3796): [update][17]#1#
,D/TetherSettings( 5356): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5356): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5356): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5356): Cust_ConnectToPC   : spcsc>false
D/        ( 5356): Cust_ConnectToPC   : IPT>true
D/        ( 5356): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 5356): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 5356): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5356): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5356): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 5356): usb_cable_connect = 1
,D/SmartNS_Utility( 5356): usb_denied = 0
,I/ActivityManager(  968): Waited long enough for: ServiceRecord{4cb4b1b u0 com.htc.backup/.notifications.contextual.ContextualReminderControlService},
I/SmartNS_NSReceiver( 5356): locked:falsesecurity:falseisLocked:false,
D/SmartNS_NSReceiver( 5356): USB = true hasTethered = false isNSOpening: false
,I/PSReceiver( 5356): onReceive:com.htc.intent.action.USB_CONNECT2PC
,W/ContextImpl( 5356): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2712 
,I/SmartNS_PSService( 5356): onReceive:com.htc.intent.action.USB_CONNECT2PC
,W/Settings( 5356): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 5356):  defaultType:0
I/SmartNS_PSService( 5356): fail notificaiton:false
,D/SmartNS_Utility( 5356): usb_cable_connect = 1
D/SmartNS_Utility( 5356): usb_denied = 0
I/SmartNS_PSService( 5356): usb notificaiton:true
I/ActivityManager(  968): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=5379 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
,I/ActionCombine( 5356): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,D/SmartNS_Utility( 5356): usb_cable_connect = 1
,D/SmartNS_Utility( 5356): usb_denied = 0
I/SmartNS_PSService( 5356): usb notificaiton:true
,E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
,D/DotMatrix( 1302): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/RemoteViews( 1222): reapply : com.android.settings 1 36
,D/SmartNS_Utility( 5356): usb_cable_connect = 1
,D/SmartNS_Utility( 5356): usb_denied = 0
D/DotMatrix( 1302): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/SmartNS_PSService( 5356): KeyGuard locked:falseKeyGuard is secured:false
,D/SmartNS_PSService( 5356): USB Plugged, Set USBPlugged=  truePSenabled:false,
D/Process (  968): killProcessQuiet, pid=4794
I/ActivityManager(  968): Killing 4794:com.google.android.music:main/u0a159 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/RemoteViews( 1222): reapply : com.android.settings 1 36,
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 11 num clients 7
,E/WifiTrafficPoller(  968):  packet count Tx=98 Rx=148
I/ActivityManager(  968): Recipient 4794
E/WifiTrafficPoller(  968): notifying of data activity 3
,D/WIFI_ICON( 1222): WifiActivity: 3
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/MediaRouterService(  968): Client com.google.android.music (pid 4794): Died!
,W/ResourcesManager( 5194): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/PhoneApp( 1429): EVENT_QUERY_MO_PACKAGES,
,D/MediaProvider( 3796): [update][50]#1#,
D/PhoneApp( 1429): -- N1 =0
D/PhoneApp( 1429): -- N2 =0
,D/PhoneApp( 1429): -- N3 =0
,W/ContextImpl( 5379): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.backupreset.receiver.BackupResetReceiver.onReceive:45 android.app.ActivityThread.handleReceiver:2712 
,D/FlexNetS( 4855): updateSvcAllowedInSettings:false
,I/ActivityManager(  968): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=5402 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,D/Process (  968): killProcessQuiet, pid=4883
I/ActivityManager(  968): Killing 4883:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/art     (  406): Explicit concurrent mark sweep GC freed 8678(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 197us total 26.411ms,
W/asset   ( 1472): Copying FileAsset 0x5576f78f80 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,I/art     (  406): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 176us total 22.147ms
,D/Messaging( 5270): supportCMAS(SIE)/init? false/true
D/MmsConfig( 5270): networkCode: 
,D/MmsConfig( 5270): SIE smsPri: null
,D/MmsConfig( 5270): networkCode: 
,W/asset   ( 5194): Copying FileAsset 0x5576d864c0 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,D/Messaging( 5270): mNeedToUpdateDate2 start,
I/ActivityManager(  968): Recipient 4883
,D/ReportIndicatorCache( 5270): startAsyncQueryReports ---
,I/art     (  406): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 170us total 21.231ms
,D/MmsAsyncWorkHandler( 5270): 
D/MmsAsyncWorkHandler( 5270): HM tk = 20001
D/ReportIndicatorCache( 5270): MSG_QUERY_REPORTS >>
,D/DraftCache( 5270): [DraftCache/1] DraftCache.constructor
D/DraftCache( 5270): [DraftCache/1] refresh
,I/Messaging( 5270): mccmnc> 
,D/MmsConfig( 5270): networkCode: 
,D/Messaging( 5270): ViewCache CreatePreloadOnlyConversationList
,E/Prism.WidgetManager( 1472): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1472): onLoadItems() -
I/Prism.ItemManager( 1472): loadItems() com.htc.launcher.pageview.WidgetManager@30ca3377 -
,D/MediaProvider( 3796): [update][74]#1#
D/MessageCustFlag( 5270): sense_version=6.0
,D/TelephUtils( 1429): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/MmsSmsV2Provider( 1429):  slotId = -1000
,D/MmsSmsV2Provider( 1429): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/PhoneStorageUtil( 5270): HtcWrapEnvironment.getSupportedStorages() >1
D/MediaScanner( 3796):  prescan time: 432ms
D/MediaScanner( 3796):     scan time: 862ms
D/MediaScanner( 3796): postscan time: 10ms
D/MediaScanner( 3796):    total time: 1304ms
D/MediaScanner( 3796): -----------------------------------------------------------------
D/MediaScanner( 3796): firstscan(media) time: 454ms
D/MediaScanner( 3796): secondscan(non-media) time: 408ms
D/PhoneStorageUtil( 5270): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/MediaScanner( 3796):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 1
D/MediaScanner( 3796):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3796):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/PhoneStorageUtil( 5270): createReceiver
D/MediaScanner( 3796):  [Total]    File(Image+Video+Audio+Others) in database : 1546
,D/Jerry   ( 5270): start to preload cursor >>>>>>>
,I/Prism.WidgetManager( 5194): onLoadItems() -
,I/Prism.ItemManager( 5194): loadItems() com.htc.launcher.pageview.WidgetManager@17396603 -
D/TelephUtils( 1429): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 95
D/MmsSmsV2Provider( 1429):  slotId = -1000
D/MmsSmsV2Provider( 1429): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/MediaProvider( 3796): [delete][22]
,D/TelephUtils( 1429): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
V/MmsProvider( 1429): Update uri=content://mms, match=0
V/MmsProvider( 1429): selection=st=129 AND m_type!=134
D/TelephUtils( 1429): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 91
D/AccFlag ( 1429): sku_id=118
D/MediaProvider( 3796): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
D/Messaging( 5270): Reset downloading state: 0
,V/MmsSystemEventReceiver( 5270): TransactionService is going to be woken up.
,D/DraftCache( 5270): [DraftCache/121] rebuildCache,
,D/MediaProvider( 3796): [recoverParentNodes] - 0
D/MediaProvider( 3796): [update][7]
D/MediaScannerServiceEx( 3796): [scan] Recover Parent Node is finished!
D/MediaScannerServiceEx( 3796): [updateImage]+
D/TelephUtils( 1429): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
,D/MmsSmsV2Provider( 1429):  slotId = -1000
D/MmsSmsV2Provider( 1429): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
V/TransactionService( 5270): 1-Creating TransactionService
,D/Messaging( 5270): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1429): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
W/ContextImpl( 5402): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
D/MmsSmsV2Provider( 1429):  slotId = -1000
,D/TelephUtils( 1429): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/MmsSmsV2Provider( 1429):  slotId = -1000
D/MmsSmsV2Provider( 1429): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/MediaScannerServiceEx( 3796): [updateImage]-0
D/Messaging( 5270): mNeedToUpdateDate2: false
,D/PMS     (  968): releaseWL(4144bee): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
,D/MediaScannerServiceEx( 3796): [1] scan finished
D/TelephUtils( 1429): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/Jerry   ( 1429): URI_DRAFT
D/MediaProviderUtils( 3796): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3796): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3796): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3796): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1
W/MediaScannerServiceEx( 3796): Process mounted intent for unmounted storage: /storage/ext_sd
,V/TransactionService( 5270): onStartCommand: 1
,D/MmsSystemEventReceiver( 5270): unRegisterForConnectionStateChanges
D/MediaScannerServiceEx( 3796): [disAliveExtStorageRows]+131073
D/PowerUsageList:PowerUsageHelper( 5402): MY_DEBUG = false
D/Messaging( 5270): ViewCache CreatePreload
D/Messaging( 5270): ViewCache CreatePreloadOnlyMultipleOpsList
,D/DraftCache( 5270): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 5270): [DraftCache/121] rebuildCache time: 2
D/MmsAsyncWorkHandler( 5270): 
D/MmsAsyncWorkHandler( 5270): HM tk = 20002
,V/TransactionService( 5270): 4-Handling incoming message: { when=-6ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 5270): Loading previous transactions.
D/PMS     (  968): acquireWL(106b7c49): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5402 1000 null
,D/TelephUtils( 1429): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 95
D/AccFlag ( 1429): device_type: 1
,I/ActivityManager(  968): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=5437 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a
,D/Cust_MMSMS( 5270): _has_set_default_values_2=true
,D/PowerUsageService( 5402): repeat time = 1448021129142
D/TransactionService( 5270): Force clearing mTransactionList
D/TransactionService( 5270): Force set service start id to 1
V/TransactionService( 5270): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 5270): unRegisterForConnectionStateChanges
D/TelephUtils( 1429): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
,D/TransactionService( 5270): stopSelfResult: true, mLastHandledServiceId: 1
,D/AccFlag ( 1429): sku_id=118
D/MsgPreferenceUtils( 5270): def_index: 0
V/TransactionService( 5270): Destroying TransactionService
V/TransactionService( 5270): 4-Handling incoming message: { when=0 what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
D/MsgPreferenceUtils( 5270): globalIndex = 1
,D/MediaProvider( 3796): [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted
,D/TelephUtils( 1429): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/AccFlag ( 1429): sku_id=118
,D/MediaProvider( 3796): [update][47]#1#
D/MsgPreferenceUtils( 5270): phone state: true
D/MsgPreferenceUtils( 5270): sd state: false
D/MsgPreferenceUtils( 5270): vIndex = 0
,D/WeatherUtility( 1565): Weather sync is On
,D/WSP     ( 1565): [Receiver] auto sync agent, auto sync is enabled, reset schedule
,E/WifiStateMachine(  968): handleMessage: E msg.what=131155,
E/WifiStateMachine(  968): processMsg: ConnectedState
,E/WifiStateMachine(  968):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2462 sc=60 link=72 tx=17.9, 0.0, 0.0  rx=15.7 bcn=0 [on:0 tx:0 rx:0 period:2908] from screen [on:0 period:616250454] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2462 sc=60 link=72 tx=17.9, 0.0, 0.0  rx=15.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:616250455] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  968):  get link layer stats 0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1348): wlan0: Control interface command 'SIGNAL_POLL'
,I/ActivityManager(  968): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=5471 uid=10028 gids={50028, 9997, 1028, 1015, 1023, 3003, 2001, 3002} abi=armeabi-v7a
,I/wpa_supplicant( 1348): environment dirty rate=25 [4][1][0],
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative rssi=-57 linkspeed=72
E/WifiConfigStore(  968): updateConfiguration freq=2462 BSSID=c0:ff:d4:d3:aa:48 RSSI=-56 "NG700"WPA_PSK
,E/WifiStateMachine(  968): calculateWifiScore freq=2462 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=10.96 txretriesrate=0.00 rxrate=11.37 userTriggerdPenalty0
E/WifiStateMachine(  968):  good link -> stuck count =0
E/WifiStateMachine(  968):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  968):  isHighRSSI       ---> score=65
,E/WifiStateMachine(  968): handleMessage: X
D/WIFI_ICON( 1222): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/WifiWatchdogStateMachine(  968): RSSI current: 3 new: -57, 3
,D/MediaProvider( 3796): [update][52]#0#
,D/MediaScannerServiceEx( 3796): [disAliveExtStorageRows]--1, 0
,D/MediaProviderUtils( 3796): calcVolumeId: /storage/emulated/0,
D/MediaProviderUtils( 3796): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3796): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3796): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
W/MediaScannerServiceEx( 3796): Process mounted intent for unmounted storage: /storage/usb
D/MediaScannerServiceEx( 3796): [disAliveExtStorageRows]+196609
,D/MediaProvider( 3796): [sendStorageAddedIfNeed]: /storage/usb : unmounted
,D/MediaProvider( 3796): [update][4]#1#
,D/WeatherUtility( 5437): Weather sync is On,
,D/MediaProvider( 3796): [update][23]#0#
,W/ResourcesManager( 5471): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/MediaScannerServiceEx( 3796): [disAliveExtStorageRows]--1, 0
W/WeatherRequest( 5437): request cur loc, but there is no sys cur
W/Settings( 5437): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/PowerUsageList:PowerUsageHelper( 5402): PowerProfile::POWER_SCREEN_FULL = 154.8
I/ActionCombine( 5437): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,I/RemoteViews( 1472): reapply : com.htc.widget.weatherclock 7 17,
,D/PowerUsageList:BatterySipperExt( 5402): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageList:BatterySipperExt( 5402): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageList:BatterySipperExt( 5402): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageService( 5402): calcPower(), no data
,D/Process (  968): killProcessQuiet, pid=4930,
I/ActivityManager(  968): Killing 4930:com.htc.mobiledata/u0a46 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiStateMachine(  968): handleMessage: E msg.what=131165,
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
,E/WifiStateMachine(  968):  ConnectModeState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
,E/WifiStateMachine(  968):  SupplicantStartedState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiStateMachine(  968):  DefaultState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine(  968): handleMessage: X
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 11 num clients 7,
D/WIFI_ICON( 1222): WifiActivity: 0,
E/WifiTrafficPoller(  968):  packet count Tx=98 Rx=148
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  968): notifying of data activity 0
,I/ActivityManager(  968): Recipient 4930,
,I/ActivityManager(  968): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=5498 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,E/SQLiteLog( 5471): (283) recovered 15 frames from WAL file /data/data/com.htc.album/databases/MMexternal.db-wal
,I/MusicStore( 5498): Database version: 120,
,D/VoldConnector(  968): SND -> {24 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
,W/ContextImpl( 5498): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,D/VoldConnector(  968): SND -> {25 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 5498): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files,
D/VoldConnector(  968): SND -> {26 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 5498): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/ResourcesManager( 5498): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5498): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5498): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 5498): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5498): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@6f5ff22: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
I/ProviderInstaller( 5498): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5498): GMSCore installation verified
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  968): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3e103f24 mBinding = false
W/Settings:Agent(  968): MONITOR_LOG
W/Settings:Agent(  968): name: bluetooth_on
W/Settings:Agent(  968): value: 0
W/Settings:Agent(  968): >> traceCallingStack()
W/Settings:Agent(  968): Process.myPid(): 968
W/Settings:Agent(  968): Process.myTid(): 2027
W/Settings:Agent(  968): Process.myUid(): 1000
W/Settings:Agent(  968): 
W/Settings:Agent(  968): 
W/System.err(  968): java.lang.Throwable: stack dump
,I/ConfigStore( 5498): Config Database version: 1
W/System.err(  968): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  968): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  968): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  968): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
,W/System.err(  968): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  968): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  968): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:378)
W/System.err(  968): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:624)
W/System.err(  968): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  968): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  968): ,
W/Settings:Agent(  968): << traceCallingStack(): 7(ms)
,D/BluetoothManagerService(  968): Message: MESSAGE_DISABLE
,D/BluetoothManagerService(  968): Sending off request.
,I/DropBoxManagerService(  968): Usage (1281) > Quota (1280)
D/BluetoothAdapterState( 3073): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3073): Setting state to 13
I/BluetoothAdapterState( 3073): Bluetooth adapter state changed: 12-> 13
D/BluetoothManagerService(  968): +onBluetoothStateChange prev=12 new=13
D/BluetoothManagerService(  968): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  968): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  968): Bluetooth State Change Intent: 12 -> 13
I/IntentController( 1222): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/BluetoothAdapterProperties( 3073): onBluetoothDisable()
I/BluetoothAdapterState( 3073): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/bt-btif ( 3073): HAL bt_hal_cbacks->adapter_properties_cb
,I/bt-btm  ( 3073): BTM_SetDiscoverability
I/bt-btm  ( 3073): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3073): disc_mode 0000
I/bt-btm  ( 3073): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 3073): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
D/BluetoothAdapterProperties( 3073): Scan Mode:21
,D/WifiManager( 5004): setWifiEnabled: Base Package Name=com.example.hello, uid=10373
D/PMS     (  968): acquireWL(d8f09b9): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3073 1002 null
I/bt-btm  ( 3073): BTM_SetConnectability
D/WifiService(  968): New client listening to asynchronous messages
I/bt-btm  ( 3073): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 3073): disc_mode 0000
I/bt-btm  ( 3073): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
E/WifiTrafficPoller(  968): ADD_CLIENT: 8
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
,D/WifiService(  968): setWifiEnabled: false pid=5004, uid=10373
W/Settings:Agent(  968): MONITOR_LOG
E/WifiService(  968): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent(  968): name: wifi_on
I/WifiService(  968): isSprintWifiRestricted(): false
W/Settings:Agent(  968): value: 0
I/WifiService(  968): isMdmWifiRestricted(): false
W/Settings:Agent(  968): >> traceCallingStack()
W/Settings:Agent(  968): Process.myPid(): 968
W/Settings:Agent(  968): Process.myTid(): 1521
W/Settings:Agent(  968): Process.myUid(): 1000
W/Settings:Agent(  968): 
W/Settings:Agent(  968): 
,D/BluetoothAdapterState( 3073): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
I/bt-btif ( 3073): BTA_JvDeleteRecord
I/bt-btif ( 3073): BTA_JvRfcommStopServer
,D/bt-btm  ( 3073): BTM_FreeSCN 
I/bt-btif ( 3073): BTA_JvDeleteRecord
I/bt-btif ( 3073): BTA_JvRfcommStopServer
,D/bt-btm  ( 3073): BTM_FreeSCN 
I/bt-btif ( 3073): BTA_JvDeleteRecord
I/bt-btif ( 3073): BTA_JvRfcommStopServer
D/bt-btm  ( 3073): BTM_FreeSCN 
I/bt-btif ( 3073): BTA_JvDeleteRecord
I/bt-btif ( 3073): BTA_JvRfcommStopServer
D/bt-btm  ( 3073): BTM_FreeSCN 
I/bt-btif ( 3073): BTA_JvDeleteRecord
I/bt-btif ( 3073): BTA_JvRfcommStopServer
D/bt-btm  ( 3073): BTM_FreeSCN 
I/bt-btif ( 3073): BTA_JvDeleteRecord
I/bt-btif ( 3073): BTA_JvRfcommStopServer
D/bt-btm  ( 3073): BTM_FreeSCN 
E/bt-btif ( 3073): cmd socket is not created
E/BtOppRfcommListener( 3073): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothSapService( 3073): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/bt-sdp  ( 3073): SDP_DeleteRecord ok, num_records:14
,D/NGFService( 3676): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,W/System.err(  968): java.lang.Throwable: stack dump
,I/bt-btm  ( 3073): BTM_SEC_CLR[13]: id 55
,D/bt-sdp  ( 3073): SDP_DeleteRecord ok, num_records:13
I/bt-btm  ( 3073): BTM_SEC_CLR[14]: id 56
D/bt-sdp  ( 3073): SDP_DeleteRecord ok, num_records:12
I/bt-btm  ( 3073): BTM_SEC_CLR[15]: id 57
D/bt-sdp  ( 3073): SDP_DeleteRecord ok, num_records:11
I/bt-btm  ( 3073): BTM_SEC_CLR[16]: id 58
D/bt-sdp  ( 3073): SDP_DeleteRecord ok, num_records:10
I/bt-btm  ( 3073): BTM_SEC_CLR[17]: id 59
D/bt-sdp  ( 3073): SDP_DeleteRecord ok, num_records:9
I/bt-btm  ( 3073): BTM_SEC_CLR[18]: id 60
D/bt-sdp  ( 3073): SDP_DeleteRecord ok, num_records:8
I/bt-btm  ( 3073): Write Extended Inquiry Response to controller
V/AlarmManager(  968): sending alarm PendingIntent{2b0d8875: PendingIntentRecord{33d4f00a com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1448020230190, Int=0
I/bt-btm  ( 3073): Write Extended Inquiry Response to controller
I/bt-btm  ( 3073): Write Extended Inquiry Response to controller
I/bt-btm  ( 3073): Write Extended Inquiry Response to controller
,V/BluetoothPbapReceiver( 3073): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 3073): ***********state = 13
,I/BtOppRfcommListener( 3073): stopping Accept Thread
,I/BtOppRfcommListener( 3073): BluetoothSocket listen thread finished
W/bt-l2cap( 3073): L2CAP - L2CA_Deregister() called for PSM: 0x000f
I/bt-btm  ( 3073): BTM_SetDiscoverability
I/bt-btm  ( 3073): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3073): disc_mode 0000
I/bt-btm  ( 3073): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 3073): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3073): BTM_SetConnectability
I/bt-btm  ( 3073): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3073): disc_mode 0000
D/bt-btm  ( 3073): btm_ble_update_adv_flag new=0x1c
D/bt-btm  ( 3073): btm_ble_update_adv_flag old=0x18
I/bt-btm  ( 3073): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 3073): BTM_IsInquiryActive
I/bt-btm  ( 3073): BTM_CancelRemoteDeviceName()
I/bt-btm  ( 3073): btm_ble_clear_white_list
W/bt-btif ( 3073): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,D/bt-btif ( 3073): AG evt (hdl 0x0001): State 0, Event 0x0501
D/bt-btif ( 3073): AG evt (hdl 0x0002): State 0, Event 0x0501
D/bt-sdp  ( 3073): SDP_DeleteRecord ok, num_records:7
D/bt-btm  ( 3073): BTM_FreeSCN 
I/bt-btm  ( 3073): BTM_SEC_CLR[3]: id 12
D/bt-sdp  ( 3073): SDP_DeleteRecord ok, num_records:6
D/bt-btm  ( 3073): BTM_FreeSCN 
I/bt-btm  ( 3073): BTM_SEC_CLR[4]: id 29
D/bt-avp  ( 3073): AVRC_Close handle:0
D/bt-btif ( 3073): AV Sevent(0x41)=0x120a(API_CLOSE) state=0(INIT)
,D/bt-btif ( 3073): btif_hf_upstreams_evt: event=BTA_AG_DISABLE_EVT
,V/BluetoothPbapService( 3073): Pbap Service closeService in
,V/BluetoothPbapService( 3073): successfully stopped pbap service
V/BluetoothPbapService( 3073): Pbap Service closeService out
,V/BluetoothPbapService( 3073): Pbap Service onDestroy
,D/bt-sdp  ( 3073): SDP_DeleteRecord ok, num_records:5
,D/bt-sdp  ( 3073): SDP_DeleteRecord ok, num_records:4
W/bt-l2cap( 3073): L2CAP - L2CA_Deregister() called for PSM: 0x0019
D/bt-sdp  ( 3073): SDP_DeleteRecord ok, num_records:3
W/bt-l2cap( 3073): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3073): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3073): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3073): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3073): L2CAP - PSM: 0x0017 not found for deregistration,
W/bt-l2cap( 3073): L2CAP - L2CA_Deregister() called for PSM: 0x0011
,W/bt-l2cap( 3073): L2CAP - L2CA_Deregister() called for PSM: 0x0013
I/bt-att  ( 3073): GATT_Deregister gatt_if=3
I/bt-att  ( 3073): GATT_Listen gatt_if=3
I/bt-btm  ( 3073): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3073): BTM_ReadConnectability
I/bt-btm  ( 3073): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3073): disc_mode 0000
I/bt-att  ( 3073): GATT_Deregister gatt_if=4
I/bt-att  ( 3073): GATT_Listen gatt_if=4
I/bt-btm  ( 3073): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3073): BTM_ReadConnectability
I/bt-btm  ( 3073): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3073): disc_mode 0000
E/bt-btif ( 3073): bta_gattc_deregister Deregister Failedm unknown client cif
V/BluetoothPbapService( 3073): Pbap Service closeService in
V/BluetoothPbapService( 3073): Pbap Service closeService out
,W/System.err(  968): 	at java.lang.Thread.dumpStack(Thread.java:490)
,W/System.err(  968): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  968): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  968): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  968): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  968): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  968): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  968): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:112)
W/System.err(  968): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  968): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  968): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  968): 
W/Settings:Agent(  968): << traceCallingStack(): 53(ms)
I/QuickSettingBluetooth( 1222): receive.ACTION_STATE_CHANGE:STATE_TURNING_OFF
,D/PMS     (  968): acquireWL(28ec8e98): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 5356 1000 null,
W/ContextImpl( 5356): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
I/bt-btm  ( 3073): btm_ble_clear_white_list_complete
,D/PMS     (  968): releaseWL(28ec8e98): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
,D/PMS     (  968): acquireWL(16da02d6): PARTIAL_WAKE_LOCK  StartingDockService 0x1 5356 1000 null,
,W/System.err(  968): java.lang.Throwable: stack dump,
W/System.err(  968): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  968): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  968): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
,W/System.err(  968): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  968): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  968): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1067fc44:true
,D/WifiController(  968): handleMessage: E msg.what=155656
D/WifiController(  968): processMsg: DeviceActiveState
D/WifiController(  968): processMsg: StaEnabledState
D/WifiController(  968): transitionTo: destState=ApStaDisabledState
D/WifiController(  968): handleMessage: new destination call exit/enter
D/WifiController(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiController(  968): invokeExitMethods: DeviceActiveState,
D/WifiController(  968): invokeExitMethods: StaEnabledState
D/WifiController(  968): moveTempStackToStateStack: i=0,j=1
D/WifiController(  968): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=ApStaDisabledState
D/WifiController(  968): invokeEnterMethods: ApStaDisabledState
I/jxcore-log( 5004): ****TEST TOOK:  5158  ms ****
I/jxcore-log( 5004): 
I/ActivityManager(  968): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=5532 uid=10034 gids={50034, 9997, 3002, 3001} abi=arm64-v8a
,D/WifiController(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131084
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
I/jxcore-log( 5004): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5004): 
D/WifiDisplayAdapter(  968): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  968):     Client/Owner: Client
D/WifiDisplayAdapter(  968):     GroupId: 
D/WifiDisplayAdapter(  968):     Passphrase: 
D/WifiDisplayAdapter(  968):     SessionId: 0
D/WifiDisplayAdapter(  968):     IP Address: }
E/WifiStateMachine(  968):  L2ConnectedState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState !CMD_STOP_SUPPLICANT 0 0
,E/WifiStateMachine(  968): transitionTo: destState=WaitForP2pDisableState
E/WifiStateMachine(  968): handleMessage: new destination call exit/enter
E/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=SupplicantStartedState,active=true,parent=DefaultState
E/WifiStateMachine(  968): invokeExitMethods: ConnectedState
E/WifiStateMachine(  968): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  968): release()
E/WifiStateMachine(  968): PerfLock released for exiting ConnectedState
E/WifiStateMachine(  968): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
E/WifiStateMachine(  968): invokeExitMethods: L2ConnectedState
E/WifiStateMachine(  968): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
E/WifiStateMachine(  968): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  968): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  968): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  968): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1348): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1348): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1348): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1348): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1348): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1348): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1348): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/BluetoothAdapter( 5356): 809011815: getState(). Returning 13
,E/WifiStateMachine(  968): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1348): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1348): Power_Mode_Type mode = 0
I/wpa_supplicant( 1348): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,D/BluetoothInputDevice( 5356): BluetoothInputDevice()
D/BluetoothManagerService(  968): registerStateChangeCallback+
D/BluetoothManagerService(  968): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  968): Registered receivers: 9
,W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/WifiP2pService(  968): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/wpa_supplicant( 1348): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1348): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  968): setDhcpActive: false
V/NativeCrypto( 1953): Read error: ssl=0x5576ce8420: I/O error during system call, Connection timed out
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
D/PMS     (  968): acquireWL(1f88fdc): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1953 10024 WorkSource{10024 com.google.android.gms}
V/NativeCrypto( 1953): SSL shutdown failed: ssl=0x5576ce8420: I/O error during system call, Broken pipe
E/WifiStateMachine(  968): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  968): setDetailed state send new extra info<unknown ssid>
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/libc    (  968): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
,D/ConnectivityService(  968): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024,
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): ValidatedState{ when=0 what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  968): Validated NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): DefaultState{ when=0 what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  968): rematching NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): Forcing reevaluation
D/ConnectivityService(  968):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  968):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): Validated
D/ConnectivityService(  968): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  968): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  968): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1222): CM callback handler got msg 524290
,I/SecurityController( 1222): onAvailable 100 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/bt-btm  ( 3073): BTM_BleGetVendorCapabilities,
W/bt-btif ( 3073): ag scb idx 1 not allocated
W/bt-btif ( 3073): ag scb idx 2 not allocated
E/bt-btif ( 3073): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3073): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3073): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3073): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3073): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3073): L2CAP - L2CA_Deregister() called for PSM: 0x0019
,W/bt-l2cap( 3073): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3073): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3073): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3073): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3073): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3073): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3073): L2CAP - PSM: 0x0017 not found for deregistration
E/bt-btif ( 3073): bta_gattc_deregister Deregister Failedm unknown client cif,
E/bt_userial_mct( 3073): pthread_join() FAILED result:3
,I/art     (  968): Explicit concurrent mark sweep GC freed 28631(1455KB) AllocSpace objects, 2(552KB) LOS objects, 33% free, 16MB/25MB, paused 2.135ms total 185.504ms
,I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=5498, uid=10159, userID:0
,E/WifiStateMachine(  968): NetworkAgent != null
D/ConnectivityService(  968): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  968): ignoring duplicate network state non-change
D/BluetoothPan( 5356): BluetoothPan()
D/PMS     (  968): releaseWL(1f88fdc): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
D/BluetoothManagerService(  968): registerStateChangeCallback+
D/ConnectivityService(  968): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
V/NetworkPolicy(  968): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/BluetoothManagerService(  968): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  968): Registered receivers: 10
E/WifiStateMachine(  968): autoRoamSetBSSID any key="NG700"WPA_PSK
E/WifiConfigStore(  968): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  968): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1348): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1348): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1348): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1348): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1348): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1348): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1348): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  968): invokeExitMethods: ConnectModeState
E/WifiStateMachine(  968): invokeExitMethods: DriverStartedState
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL true Token 11
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
,I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiTrafficPoller(  968):  packet count Tx=98 Rx=150
E/WifiTrafficPoller(  968): notifying of data activity 1
D/WifiDataStallTracker(  968): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  968): stopDataStallAlarm 
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 12
E/WifiDataStallTracker(  968): ENABLE_DATA_MONITOR_POLL false Token 1
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 13
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1348): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/wpa_supplicant( 1348): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WIFI_ICON( 1222): WifiActivity: 1
E/WifiStateMachine(  968): Unexpected BatchedScanResults :null
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/wpa_supplicant( 1348): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 1348): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  968): noteBatchedScanstop()
D/BluetoothMap( 5356): Create BluetoothMap proxy object
D/BluetoothManagerService(  968): registerStateChangeCallback+
I/ActivityManager(  968): Killing 4978:com.google.android.apps.magazines/u0a161 (adj 15): empty #17
D/Process (  968): killProcessQuiet, pid=4978
E/BluetoothMap( 5356): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/BluetoothManagerService(  968): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  968): Registered receivers: 11
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/BluetoothManagerService(  968): registerStateChangeCallback+
D/BluetoothSap( 5356): BluetoothSap() call bindService
D/BluetoothManagerService(  968): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  968): Registered receivers: 12
E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL false Token 14 num clients 8
W/ContextImpl( 5356): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1888 android.content.ContextWrapper.bindService:538 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1423 
,D/HtcBtWidget_BTWidgetProvider( 5532): onBTStateChanged() for widget: 
D/HtcBtWidget_BTWidgetProvider( 5532): updateWidget(context) for widget: 
D/ConnectivityService(  968): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  968): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1222): CM callback handler got msg 524292
D/Nat464Xlat(  968): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  968): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  968): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/usbnet  (  968): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService(  968): Removing idletimer
I/QuickSettingWifi( 1222): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:1
D/usbnet  (  968):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/PMS     (  968): acquireWL(13c23c12): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 968 1000 null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): Disconnected - quitting
D/usbnet  (  968): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/CSLegacyTypeTracker(  968): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
D/ConnectivityService(  968): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/SecurityController( 1222): onLost 100
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:12
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:0
,I/ActivityManager(  968): Recipient 4978
,E/cutils-trace( 5554): Error opening trace file: Permission denied (13)
,I/ActivityManager(  968): Killing 5118:com.android.chrome/u0a96 (adj 15): empty #17
D/Process (  968): killProcessQuiet, pid=5118
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,D/CustomizationManager( 5554): ====startRecUseTime====
D/htc.customization.log.level( 5554):  is 
W/CustomizationLogLevel( 5554): Level value is invalid, use default level 2
,I/ActivityManager(  968): Recipient 5118,
,D/ConnectivityService(  968): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE,
E/WifiStateMachine(  968): [1,448,020,230,809 ms] noteScanEnd no scan source
D/WifiP2pService(  968): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=2
E/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=2,Top=WaitForP2pDisableState
E/WifiStateMachine(  968): invokeEnterMethods: WaitForP2pDisableState
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131212
E/WifiStateMachine(  968): processMsg: WaitForP2pDisableState
D/BluetoothPbap( 5356): BluetoothPbap()
E/WifiStateMachine(  968):  WaitForP2pDisableState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiStateMachine(  968):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  968): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131212
E/WifiStateMachine(  968): processMsg: WaitForP2pDisableState
E/WifiStateMachine(  968):  WaitForP2pDisableState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: DefaultState
D/BluetoothManagerService(  968): registerStateChangeCallback+
E/WifiStateMachine(  968):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine(  968): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
D/WifiP2pService(  968): P2pEnabledState{ when=-5ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  968): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
V/NetworkPolicy(  968): ensureActiveMobilePolicyLocked()
E/WifiStateMachine(  968): handleMessage: X
D/PMS     (  968): acquireWL(2684075e): PARTIAL_WAKE_LOCK  NetworkStats 0x1 968 1000 null
E/WifiStateMachine(  968): handleMessage: E msg.what=131212
D/DATA_ICON( 1222): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
E/WifiStateMachine(  968): processMsg: WaitForP2pDisableState
D/PMS     (  968): releaseWL(d8f09b9): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
E/WifiStateMachine(  968):  WaitForP2pDisableState !CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
D/WifiP2pService(  968): P2pDisablingState
E/WifiStateMachine(  968):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiP2pService(  968): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  968): processMsg: DefaultState
D/WifiP2pService(  968): p2p socket connection lost
,D/BluetoothManagerService(  968): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/WifiP2pService(  968): P2pDisabledState
D/BluetoothManagerService(  968): Registered receivers: 13
D/WifiP2pService(  968): P2pDisabledState{ when=-1ms what=131333 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  968):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiP2pService(  968): DefaultState{ when=-1ms what=131333 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  968): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
D/NetworkPolicy(  968): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
E/WifiStateMachine(  968): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
V/NetworkPolicy(  968): updateNetworkEnabledLocked()
E/WifiStateMachine(  968): handleMessage: X
V/NetworkPolicy(  968): updateIfacesLocked()
,D/WifiNetworkAgent(  968): NetworkAgent: NetworkAgent channel lost
D/WIFI    (  968): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  968):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/NetworkPolicy(  968): updateNotificationsLocked()
D/WIFI    (  968): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
E/WifiStateMachine(  968): enter WifiNetworkFactory startNetwork. mIPTStart:false
D/Tethering(  968): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering(  968): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/WifiMonitor(  968): stopMonitoring(p2p0) = com.android.server.wifi.p2p.WifiP2pServiceImpl$P2pStateMachine@2c0d7fe
D/WifiScanningService(  968): SCAN_AVAILABLE : 1
D/RttService(  968): SCAN_AVAILABLE : 1
D/RttService(  968): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
I/bt-btif ( 3073): HAL bt_hal_cbacks->adapter_state_changed_cb
D/WifiScanningService(  968): DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothAdapterState( 3073): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
E/WifiStateMachine(  968): handleMessage: E msg.what=131205
E/WifiStateMachine(  968): processMsg: WaitForP2pDisableState
D/BluetoothAdapterService( 3073): mProfilesStarted : true supportedProfileServices.length : 6
E/WifiStateMachine(  968):  WaitForP2pDisableState !CMD_DISABLE_P2P_RSP uid=1000 0 0
E/WifiStateMachine(  968): transitionTo: destState=SupplicantStoppingState
E/WifiStateMachine(  968): handleMessage: new destination call exit/enter
E/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  968): invokeExitMethods: WaitForP2pDisableState
E/WifiStateMachine(  968): invokeExitMethods: SupplicantStartedState
E/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=1
E/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStoppingState
E/WifiStateMachine(  968): invokeEnterMethods: SupplicantStoppingState
E/WifiStateMachine(  968): Call handleNetworkDisconnect() in SupplicantStoppingState
D/NetworkManagementService(  968): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/DATA_ICON( 1222): dataConnected: false/false
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WifiDisplayAdapter(  968): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  968):     Client/Owner: Client
D/WifiDisplayAdapter(  968):     GroupId: 
D/WifiDisplayAdapter(  968):     Passphrase: 
D/WifiDisplayAdapter(  968):     SessionId: 0
D/WifiDisplayAdapter(  968):     IP Address: }
,I/ActivityManager(  968): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=5576 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,D/LocalBluetoothProfileManager( 5356): LocalBluetoothProfileManager construction complete
D/WifiDisplayController(  968): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayAdapter(  968): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  968):     Client/Owner: Client
D/WifiDisplayAdapter(  968):     GroupId: 
D/WifiDisplayAdapter(  968):     Passphrase: 
D/WifiDisplayAdapter(  968):     SessionId: 0
D/WifiDisplayAdapter(  968):     IP Address: }
E/WifiStateMachine(  968): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - enter - invokeEnterMethods
,D/Process (  968): killProcessQuiet, pid=5159
I/ActivityManager(  968): Killing 5159:com.google.android.apps.plus/u0a167 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
E/WifiStateMachine(  968): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1348): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1348): Power_Mode_Type mode = 0
I/wpa_supplicant( 1348): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1348): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  968): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1348): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiP2pService(  968): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDataStallTracker(  968): setDhcpActive: false
,E/WifiStateMachine(  968): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false,
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/CustomizationManager( 5554):  Read ACC file spent 0.044 (s)
,D/CIDMapFileReader( 5554): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5554): Parsing tag item name = HTC__102
,D/CIDMapFileReader( 5554): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5554): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5554): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5554): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5554): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 5554): full path : /system/customize/CID/HTC__102.xml
,I/CustomizationCIDLoader( 5554): Parsing tag category name = system
,I/CustomizationCIDLoader( 5554): Parsing tag category name = application
,I/CustomizationCIDLoader( 5554): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5554): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5554): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5554): Parsing tag category name = Settings
I/CustomizationCIDLoader( 5554): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 5554): add string-array item, value = 42507
I/CustomizationCIDLoader( 5554): add string-array item, value = 21902
I/CustomizationCIDLoader( 5554): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 5554): add string-array item, value = 23420
I/CustomizationCIDLoader( 5554): add string-array item, value = 22299
I/CustomizationCIDLoader( 5554): add string-array item, value = 24002
,I/CustomizationCIDLoader( 5554): add string-array item, value = 23210
I/CustomizationCIDLoader( 5554): add string-array item, value = 23205
I/CustomizationCIDLoader( 5554): add string-array item, value = 23806
I/CustomizationCIDLoader( 5554): add string-array item, value = 23430
I/CustomizationCIDLoader( 5554): add string-array item, value = 23408
I/CustomizationCIDLoader( 5554): add string-array item, value = 27205
I/CustomizationCIDLoader( 5554): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 5554): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 5554): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 5554): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 5554): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 5554): add string-array item, value = 24002:D:0:0
,I/CustomizationCIDLoader( 5554): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 5554): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 5554): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 5554): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 5554): add string-array item, value = 23408:C:1:0,
I/CustomizationCIDLoader( 5554): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 5554):  Read CID file spent 0.089 (s)
D/CustomizationManager( 5554):  All configurations done spent 0.089 (s)
,D/PackageManager(  968): deletePackageAsUser: pkg=com.example.hello, pid=5554, uid=2000 userid=0
,E/WifiDataStallTracker(  968): DATA_MONITOR_POLL false Token 2,
,W/PackageSettings(  968): Skipping PackageSetting{6f25df1 com.test.thalitest/10366} due to missing metadata,
,I/ActivityManager(  968): Recipient 5159,
,D/PMS     (  968): releaseWL(2684075e): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,E/WifiStateMachine(  968): stopping supplicant
W/WifiHW  (  968): QCOM Debug wifi_send_command "TERMINATE"
D/wpa_supplicant( 1348): RX global ctrl_iface - hexdump(len=9): 54 45 52 4d 49 4e 41 54 45
D/wpa_supplicant( 1348): wlan0: Removing interface wlan0
D/HeadsetService( 3073): Received stop request...Stopping profile...
E/WifiStateMachine(  968): setWifiState: disabling
D/wpa_supplicant( 1348): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1348): TDLS: Tear down peers
D/wpa_supplicant( 1348): wpa_driver_nl80211_disconnect(reason_code=3)
D/DockEventReceiver( 5356): finishStartingService: stopping service
D/BluetoothInputDevice( 5356): Proxy object connected
,I/ActivityManager(  968): Force stopping com.example.hello appid=10373 user=0: pkg removed
D/Process (  968): killProcessQuiet, pid=5004
I/ActivityManager(  968): Killing 5004:com.example.hello/u0a373 (adj 0): stop com.example.hello
D/HidProfile( 5356): Bluetooth service connected
,D/BluetoothAdapter( 5356): 809011815: getState(). Returning 13
,D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
,D/BluetoothPan( 5356): BluetoothPAN Proxy object connected
,D/PanProfile( 5356): Bluetooth service connected
,D/SapServerProfile( 5356): Bluetooth service connected
,D/WISPrService( 5356): >>>>>WISPrService start isConnected = true<<<<<
,D/PMS     (  968): releaseWL(16da02d6): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
,D/WifiService(  968): New client listening to asynchronous messages
E/WifiTrafficPoller(  968): ADD_CLIENT: 9
,D/wpa_supplicant( 1348): wlan0: Event DEAUTH (12) received,
D/wpa_supplicant( 1348): wlan0: Deauthentication notification
D/wpa_supplicant( 1348): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1348): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1348): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1348): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
E/wpa_supplicant( 1348): enter disconnect check
I/wpa_supplicant( 1348): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1348): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 1348): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
E/WifiMonitor(  968): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/HTCRequest(  968): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
E/WifiMonitor(  968): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/Tethering(  968): interfaceLinkStateChanged wlan0, false
D/Tethering(  968): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  968): interfaceLinkStateChanged wlan0, false
D/Tethering(  968): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1348): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1348): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 1348): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1348): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1348): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x5580fb4f88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/Tethering(  968): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
D/wpa_supplicant( 1348):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1348): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1348): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1348): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1348): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1348): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1348): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1348): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1348): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1348): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1348): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1348): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1348): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1348): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1348): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1348): EAPOL: External notification - portValid=0
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
V/Tethering(  968): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  968): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  968): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  968): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
,D/PMS     (  968): releaseWL(106b7c49): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/ActivityManager(  968): Recipient 5004
I/WindowState(  968): WIN DEATH: Window{3379ebae u0 com.example.hello/com.example.hello.MainActivity}
D/WifiService(  968): Client connection lost with reason: 4
,E/InputEventReceiver( 1374): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{2aab7b74 uid 10373 pid 5004} (c)'
,W/ActivityManager(  968): Force removing ActivityRecord{3799e86d u0 com.example.hello/.MainActivity t8}: app died, no saved state
,E/wpa_supplicant( 1348): wlan0: BLACKLIST CLEAR 
,D/WifiMonitor(  968): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=29 dispatchEvent: BLACKLIST CLEAR 
D/wpa_supplicant( 1348): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush
D/wpa_supplicant( 1348): wlan0: BSS: Remove id 1 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700' due to wpa_bss_flush
D/wpa_supplicant( 1348): wlan0: BSS: Remove id 3 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush
D/wpa_supplicant( 1348): wlan0: BSS: Remove id 2 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush
D/wpa_supplicant( 1348): wlan0: BSS: Remove id 4 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush
D/wpa_supplicant( 1348): wlan0: Cancelling delayed sched scan
,D/wpa_supplicant( 1348): wlan0: Cancelling scan request
D/wpa_supplicant( 1348): wlan0: Cancelling authentication timeout
E/wpa_supplicant( 1348): wlan0: BLACKLIST REMOVE 00:00:00:00:00:00
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:48]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:48
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 c2:ff:d4:d3:aa:48]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 c2:ff:d4:d3:aa:48
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 64:7c:34:12:7f:81]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 64:7c:34:12:7f:81
D/WifiMonitor(  968): Event [IFNAME=wlan0 BLACKLIST REMOVE 00:00:00:00:00:00]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=35 dispatchEvent: BLACKLIST REMOVE 00:00:00:00:00:00
D/wpa_supplicant( 1348): Remove interface wlan0 from radio phy0
,D/Tethering(  968): sendTetherStateChangedBroadcast 0, 0, 0,
,I/ActivityManager(  968): Force stopping com.example.hello appid=10373 user=-1: uninstall pkg
,V/NetworkPolicy(  968): updateNetworkEnabledLocked()
V/NetworkPolicy(  968): updateNotificationsLocked()
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
,V/AudioService(  968): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  968):     Client/Owner: Client
V/AudioService(  968):     GroupId: 
V/AudioService(  968):     Passphrase: 
V/AudioService(  968):     SessionId: 0
,V/AudioService(  968):     IP Address: }
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/HtcEffectManagerBase(  968): onEventChanged id=5 status=false
D/PMS     (  968): acquireWL(25d338f8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 968 1000 null
D/HtcEffectManager(  968): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true mAllPlayOn=false
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/HtcEffectManager(  968): convertEffect before=902
D/PMS     (  968): acquireWL(3e1b01d1): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1829 10024 WorkSource{10024 com.google.android.gms}
D/HtcEffectManager(  968): convertEffect after=902
D/DotMatrix( 1302): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1302): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1302): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
D/AccTypeManager( 1713): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
I/Prism.ItemManager( 5194): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 5194): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/GeofencerStateMachine( 1829): Ignoring removeGeofence because network location is disabled.
,D/PMS     (  968): releaseWL(3e1b01d1): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/AccTypeManager( 1713): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,E/WifiStateMachine(  968): handleMessage: X
D/MediaRouterService(  968): Client com.google.android.music (pid 5498): Registered
,E/WifiStateMachine(  968): handleMessage: E msg.what=147460
W/ActivityManager(  968): Spurious death for ProcessRecord{22102f10 5004:com.example.hello/u0a373}, curProc for 5004: null
E/WifiStateMachine(  968): processMsg: SupplicantStoppingState
D/PMS     (  968): releaseWL(25d338f8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
W/SystemReader(  968): Cannot find grip_rejection_width, use default value instead
D/WifiDisplayAdapter(  968): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  968):     Client/Owner: Client
D/WifiDisplayAdapter(  968):     GroupId: 
D/WifiDisplayAdapter(  968):     Passphrase: 
D/WifiDisplayAdapter(  968):     SessionId: 0
D/WifiDisplayAdapter(  968):     IP Address: }
E/WifiStateMachine(  968):  SupplicantStoppingState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=68556
E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiStateMachine(  968):  DefaultState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=68557
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131131
E/WifiStateMachine(  968): processMsg: SupplicantStoppingState
E/WifiStateMachine(  968):  SupplicantStoppingState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiStateMachine(  968):  DefaultState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=147462
E/WifiStateMachine(  968): processMsg: SupplicantStoppingState
E/WifiStateMachine(  968):  SupplicantStoppingState !SUPPLICANT_STATE_CHANGE_EVENT 28 0 rt=68558  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
,E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiStateMachine(  968):  DefaultState !SUPPLICANT_STATE_CHANGE_EVENT 28 0 rt=68558  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=196614
E/WifiStateMachine(  968): processMsg: SupplicantStoppingState
D/BluetoothAdapterState( 3073): Stopping profile services that were post enabled
E/WifiStateMachine(  968):  SupplicantStoppingState !CMD_ON_QUIT 0 0
E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiStateMachine(  968):  DefaultState !CMD_ON_QUIT 0 0
E/WifiStateMachine(  968): handleMessage: X
,I/FeedHostManager( 1472): [onResume]
I/FeedProviderManager( 1472): onResume
I/SocialFeedProvider( 1472): +onResume
I/SocialFeedProvider( 1472): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1472): -onResume
D/WISPrService( 5356): >>>>>WISPrService start isConnected = false<<<<<
,D/wpa_supplicant( 1348): nl80211: Remove monitor interface: refcount=0
D/wpa_supplicant( 1348): netlink: Operstate: ifindex=29 linkmode=0 (kernel-control), operstate=6 (IF_OPER_UP)
D/AccTypeManager( 1713): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/WISPrService( 5356): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/ConnectivityHelper( 1472): [getCurrentConnectionType] no network connection
I/MediaRouter( 5498): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/InputMethodManagerService(  968): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,D/WISPrService( 5356): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 5356): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:1
,D/BluetoothAdapterService( 3073): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3effd7c
,D/HeadsetStateMachine( 3073): Exit Disconnected: -1
,D/BluetoothHeadset( 1222): Proxy object disconnected
D/BluetoothFtpService( 3073): ACTION_STATE_CHANGED: state: 13mHasStarted: true
E/BluetoothFtpService:RfcommSocketAcceptThread( 3073): Shutdown
I/QuickSettingMiniLite( 1222): btListener.disconnect:HEADSET
D/BluetoothHeadset( 3676): Proxy object disconnected
D/WIFI_ICON( 1222): updateWifiState: WIFI_STATE_CHANGED disabled
I/IntentController( 1222): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
V/NetworkPolicy(  968): updateNetworkEnabledLocked()
,D/A2dpService( 3073): Received stop request...Stopping profile...
D/A2dpStateMachine( 3073): Exit Disconnected: -1
V/NetworkPolicy(  968): updateNotificationsLocked()
,D/NGFService( 3676): BluetoothHeadset onServiceDisconnected: main,
,D/BluetoothAdapterService( 3073): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3effd7c
,D/BluetoothA2dp( 3676): Proxy object disconnected
D/StatusBarManagerService(  968): setSystemUiVisibility(0x700)
D/WISPrService( 5356): >>>>>WISPrService start isConnected = false<<<<<
D/StatusBarManagerService(  968): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/NGFService( 3676): BluetoothA2dp onServiceDisconnected: main
D/StatusBarManagerService(  968): hiding MENU key
D/BluetoothMasReceiver( 3073): Bluetooth STATE CHANGED to 13
,D/HidService( 3073): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3073): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3effd7c
D/WISPrService( 5356): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/ExternalAccountType( 1713): Unsupported attribute readOnly
D/BluetoothInputDevice( 5356): Proxy object disconnected
D/HidProfile( 5356): Bluetooth service disconnected
D/HealthService( 3073): Received stop request...Stopping profile...
,D/wpa_supplicant( 1348): nl80211: Set mode ifindex 29 iftype 2 (STATION)
I/ActivityManager(  968): Waited long enough for: ServiceRecord{10b829a9 u0 com.google.android.gms/.config.ConfigFetchService}
D/wpa_supplicant( 1348): nl80211: Unsubscribe mgmt frames handle 0x888888dd0873e989 (mode change)
I/wpa_supplicant( 1348): htc_wext_command_deinit +
I/wpa_supplicant( 1348): htc_wext_command_deinit -
I/wpa_supplicant( 1348): wlan0: CTRL-EVENT-TERMINATING 
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
D/wpa_supplicant( 1348): Control interface directory not empty - leaving it behind
D/wpa_supplicant( 1348): p2p0: Removing interface p2p0
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-TERMINATING 
D/wpa_supplicant( 1348): p2p0: Request to deauthenticate - bssid=00:00:00:00:00:00 pending_bssid=00:00:00:00:00:00 reason=3 state=DISCONNECTED
D/Tethering(  968): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1348): TDLS: Tear down peers
D/Tethering(  968): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1348): p2p0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1348): nl80211: Set p2p0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1348): netlink: Operstate: ifindex=30 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1348): EAPOL: External notification - portEnabled=0
D/WifiMonitor(  968): Disconnecting from the supplicant, no more events
D/wpa_supplicant( 1348): EAPOL: External notification - portValid=0
E/WifiStateMachine(  968): handleMessage: E msg.what=147458
E/WifiStateMachine(  968): processMsg: SupplicantStoppingState
E/WifiStateMachine(  968):  SupplicantStoppingState !SUP_DISCONNECTION_EVENT 36 0
E/WifiStateMachine(  968): Supplicant connection lost
,D/BluetoothAdapterService( 3073): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3effd7c
,D/FindExtension( 1472): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/ThreadedRenderer( 1472): Defer allocateBuffers to drawing time
,D/PanService( 3073): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3073): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3effd7c
I/Prism.ItemManager( 1472): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1472): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/ResourcesManager(  968): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/BtGatt.DebugUtils( 3073): handleDebugAction() action=null
,D/BtGatt.GattService( 3073): Received stop request...Stopping profile...
D/BtGatt.GattService( 3073): stop()
W/InputMethodManagerService(  968): Got RemoteException sending setActive(false) notification to pid 5004 uid 10373
D/BtGatt.AdvertiseManager( 3073): advertise clients cleared
,I/QuickSettingWifi( 1222): receive.wifiState:WIFI_STATE_DISABLING setEnable:false
D/StatusBarManagerService(  968): swetImeWindowStatus vis=0 backDisposition=0
,I/InputMethodManagerService(  968): Enable input method client, pid=1472
,D/BluetoothPan( 5356): BluetoothPAN Proxy object disconnected
D/PanProfile( 5356): Bluetooth service disconnected
D/BluetoothAdapterService( 3073): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3effd7c
,W/BluetoothHeadsetServiceJni( 3073): Cleaning up Bluetooth Handsfree Interface...
,W/BluetoothHeadsetServiceJni( 3073): Cleaning up Bluetooth Handsfree callback object
,V/BluetoothSapReceiver( 3073): SapReceiver onReceive 
,V/BluetoothSapReceiver( 3073): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3073):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 3073): startService = false
W/BluetoothHidServiceJni( 3073): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 3073): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 3073): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3073): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3073): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3073): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterState( 3073): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3073): Setting state to 10
I/BluetoothAdapterState( 3073): Bluetooth adapter state changed: 13-> 10
D/BluetoothManagerService(  968): +onBluetoothStateChange prev=13 new=10
I/BluetoothAdapterState( 3073): Entering OffState
D/BluetoothManagerService(  968): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  968): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  968): Broadcasting onBluetoothStateChange(false) to 13 receivers.
D/BluetoothHeadset( 1429): onBluetoothStateChange: up=false
D/AuthorizationBluetoothService( 1953): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothHeadset( 1429): onBluetoothStateChange: up=false
,D/MdScPhnSt( 4904): [f5f.2.]  listen tmrbb8
,D/BluetoothHeadset( 1222): onBluetoothStateChange: up=false
,W/BluetoothHeadset( 1222): Proxy not attached to service
,I/QuickSettingMiniLite( 1222): updateLiteState:no connect device!
,D/BluetoothHeadset(  968): onBluetoothStateChange: up=false
,D/BluetoothPbap( 5356): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 3676): onBluetoothStateChange: up=false
,D/BluetoothA2dp(  968): onBluetoothStateChange: up=false
,D/BluetoothMap( 5356): onBluetoothStateChange: up=false
,E/BluetoothMap( 5356): 
E/BluetoothMap( 5356): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothMap$2@8f7927b
E/BluetoothMap( 5356): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1135)
E/BluetoothMap( 5356): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1940),
E/BluetoothMap( 5356): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
E/BluetoothMap( 5356): 	at android.bluetooth.BluetoothMap$1.onBluetoothStateChange(BluetoothMap.java:64)
E/BluetoothMap( 5356): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothMap( 5356): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothInputDevice( 5356): onBluetoothStateChange: up=false
,D/BluetoothPan( 5356): onBluetoothStateChange on: false
I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=5498, uid=10159, userID:0
,D/BluetoothHeadset( 3676): onBluetoothStateChange: up=false
D/BluetoothSap( 5356): onBluetoothStateChange on: false
V/BluetoothSapService( 3073): cleanup: mService: com.android.bluetooth.sap.BluetoothSapService@18d8b2f8
D/BluetoothHeadset( 1429): onBluetoothStateChange: up=false
,D/StatusBarManagerService(  968): setSystemUiVisibility(0xc0000700)
,D/StatusBarManagerService(  968): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  968): hiding MENU key
D/BluetoothManagerService(  968): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  968): Broadcasting onBluetoothServiceDown() to 9 receivers.
D/BluetoothAdapter( 1829): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@29599be6
D/BluetoothAdapter( 1829): onBluetoothServiceDown: done
D/BluetoothAdapter( 1222): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@1f2aa6af
D/BluetoothAdapter( 1222): onBluetoothServiceDown: done
D/BluetoothAdapter( 1429): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@1032ad4f
,D/BluetoothAdapter( 1429): onBluetoothServiceDown: done
D/BluetoothAdapter( 3676): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@23ebbdac
D/BluetoothAdapter( 3676): onBluetoothServiceDown: done
,D/BluetoothAdapter(  968): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@3e103f24
D/BluetoothAdapter(  968): onBluetoothServiceDown: done
,D/BluetoothAdapter( 5356): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@62d0898
,I/art     (  968): Explicit concurrent mark sweep GC freed 27247(1812KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 16MB/25MB, paused 8.692ms total 258.714ms
D/BluetoothAdapter( 5356): onBluetoothServiceDown: done
W/PackageManager(  968): Unable to load service info ResolveInfo{104376f6 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  968): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  968): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  968): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  968): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  968): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  968): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  968): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  968): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  968): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  968): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  968): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  968): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  968): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  968): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  968): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  968): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
D/BluetoothAdapter( 3073): onBluetoothServiceDown: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@20fd7568
D/BluetoothAdapter( 3073): onBluetoothServiceDown: done
,W/asset   (  968): Copying FileAsset 0x55771bbff0 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,D/BluetoothAdapter( 1444): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@9d78980
D/BluetoothAdapter( 1444): onBluetoothServiceDown: done
,D/BluetoothAdapter( 2376): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@1f098c4c
D/BluetoothAdapter( 2376): onBluetoothServiceDown: done
D/BluetoothManagerService(  968): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3e103f24 mBinding = false
,D/BluetoothManagerService(  968): Sending unbind request.
,D/BluetoothManagerService(  968): Bluetooth State Change Intent: 13 -> 10
,I/IntentController( 1222): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,D/NGFService( 3676): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
D/NGFService( 3676): Bluetooth Adapter: OFF
,I/bt-btif ( 3073): HAL bt_hal_cbacks->thread_evt_cb
D/LocalBluetoothProfileManager( 5356): setBluetoothStateOff
W/BluetoothEventManager( 5356): unregister mProfileBroadcastReceiver fail
,D/MdProvGlob( 5576): remove item 101 (p2d7in159) for 15:android.intent.action.ANY_DATA_STATE
,I/art     ( 3073): System.exit called, status: 0
V/AlarmManager(  968): sending alarm PendingIntent{3021ddc4: PendingIntentRecord{199554ad android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=68811, Int=0
,D/TetherPref( 5356): persistRestoreBluetoothState false
D/MdScDataSum( 4904): [f5f.2.] summary 118:p2 ignore
,D/MdProvGlob( 5576): remove item 101 (p2d1in50) for 15:android.intent.action.ANY_DATA_STATE
,I/GHttpClientFactory( 5498): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 5498): Using platform SSLCertificateSocketFactory
,D/BluetoothAdapter( 1222): 166839423: getState() :  mService = null. Returning STATE_OFF
I/QuickSettingBluetooth( 1222): receive.ACTION_STATE_CHANGE:STATE_OFF/(false,false)
,D/PhoneApp( 1429): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/MdProvGlob( 5576): remove item 101 (p2d1in25) for 15:android.intent.action.ANY_DATA_STATE
,I/ActivityManager(  968): Recipient 3073
I/ActivityManager(  968): Process com.android.bluetooth (pid 3073) has died
,W/ActivityManager(  968): Scheduling restart of crashed service com.android.bluetooth/.sap.BluetoothSapService in 1000ms
W/ActivityManager(  968): Scheduling restart of crashed service com.android.bluetooth/.map.BluetoothMasService in 1000ms
,D/TelephonyReceiver( 1429): bind: true
,I/BroadcastQueue(  968): Schedule to resend BroadcastRecord{346b1dcb u-1 android.bluetooth.adapter.action.STATE_CHANGED callingPid=968 callingUid=1000} for ResolveInfo{ab1b9a8 com.android.bluetooth/.pbap.BluetoothPbapReceiver m=0x108000} of com.android.bluetooth
,D/MdProvGlob( 5576): remove item 101 (p2in11) for 15:android.intent.action.ANY_DATA_STATE
,I/ActivityManager(  968): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=5618 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,D/MdProvGlob( 5576): remove item 101 (p2in23) for 15:android.intent.action.ANY_DATA_STATE
I/ActivityManager(  968): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=5629 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3008} abi=armeabi-v7a,
,D/GenericMessagesProvider( 5270): query uri: content://htc-messages/wappush/count
,E/SQLiteLog( 5270): (14) cannot open file at line 30058 of [9491ba7d73]
E/SQLiteLog( 5270): (14) os_unix.c:30058: (2) open(/data/data/com.htc.sense.mms/databases/wappush.db) - 
E/SQLiteConnection( 5270): DB info: sqlite3_open_v2, path: /data/data/com.htc.sense.mms/databases/wappush.db, flag: 1, ret: 14
E/SQLiteConnection( 5270): DB info: errno = 2, errno message = No such file or directory
,E/SQLiteDatabase( 5270): Failed to open database '/data/data/com.htc.sense.mms/databases/wappush.db'.
E/SQLiteDatabase( 5270): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 5270): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5270): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5270): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5270): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5270): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5270): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5270): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5270): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5270): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5270): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:712)
E/SQLiteDatabase( 5270): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
E/SQLiteDatabase( 5270): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 5270): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 5270): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
E/SQLiteDatabase( 5270): 	at android.os.Binder.execTransact(Binder.java:454)
I/wpa_ctrl(  968): [wpa_ctrl_close] ctrl=0x5576e090d0
I/wpa_ctrl(  968): [wpa_ctrl_close] ctrl=0x5576e091e0
,W/System.err( 5270): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/WifiStateMachine(  968): setWifiState: disabled
W/System.err( 5270): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 5270): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
D/WifiStateMachine(  968): Enter handleNetworkDisconnect
W/System.err( 5270): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
W/System.err( 5270): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/System.err( 5270): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/WifiStateMachine(  968): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - handleNetworkDisconnect - access$12300 - processMessage
W/System.err( 5270): ,	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/System.err( 5270): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
W/System.err( 5270): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
W/System.err( 5270): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
W/System.err( 5270): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:712)
W/System.err( 5270): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
W/System.err( 5270): 	at android.content.ContentProvider.query(ContentProvider.java:960)
W/System.err( 5270): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
W/System.err( 5270): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
W/System.err( 5270): 	at android.os.Binder.execTransact(Binder.java:454)
E/WifiStateMachine(  968): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  968): Exit handleNetworkDisconnect
E/WifiStateMachine(  968): [MLHD] Error! unhandled message 6 { when=-313ms what=147458 arg1=36 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  968): transitionTo: destState=InitialState
E/WifiStateMachine(  968): handleMessage: new destination call exit/enter
,W/Settings( 4503): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WIFI_ICON( 1222): updateWifiState: WIFI_STATE_CHANGED disabled
,E/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  968): invokeExitMethods: SupplicantStoppingState
D/PMS     (  968): acquireWL(f34889f): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 968 1000 null
E/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=1
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=InitialState
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  968): invokeEnterMethods: InitialState
I/IntentController( 1222): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
W/Settings( 1829): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/JobSchedulerService(  968): Receieved: android.intent.action.PACKAGE_REMOVED
,D/MdProvGlob( 5576): remove item 101 (p2d2in53) for 15:android.intent.action.ANY_DATA_STATE
,D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/UsbDeviceManager(  968): [USBNET] bCheckSuppFunc: cdc_network
D/UsbnetService(  968): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
D/UsbnetService(  968): BroadcastReceiver::onReceive-
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 14
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL false Token 15 num clients 8
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 15
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
I/PhoneStatusBar( 1222): setImeWindowStatus(false,false)
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
D/TelephonyReceiver( 1429): switchBindHtcMsgCursor: null
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
,D/TaskPersister(  968): removeObsoleteFile: deleting file=8_task.xml,
D/WISPrService( 5356): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5356): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,I/ActivityManager(  968): Killing 5194:com.htc.sense.news/u0a74 (adj 15): empty #17
D/Process (  968): killProcessQuiet, pid=5194
W/ResourcesManager( 5629): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/DFPI.PIReciver( 5618): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED,
,I/QuickSettingWifi( 1222): receive.wifiState:WIFI_STATE_DISABLED setEnable:true
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:1
,I/ActivityManager(  968): Recipient 5194
,D/NfcHandover( 1444): onReceive: mBound=false, BTByNfc=false->false, BTHConnected=false->false,
I/DFPI.ApkInstallService( 5618): onHandleIntent
I/DFPI.ApkInstallService( 5618): Media Scan Finished Case 
D/DFPI.ApkInstallService( 5618): check CID = HTC__102
I/DFPI.ApkInstallService( 5618): There is no Demo.apk in sd card or phone storage
,D/AdapterServiceConfig( 5629): Adding HeadsetService
D/AdapterServiceConfig( 5629): Adding A2dpService
D/AdapterServiceConfig( 5629): Adding HidService
D/AdapterServiceConfig( 5629): Adding HealthService
,D/AdapterServiceConfig( 5629): Adding PanService
D/AdapterServiceConfig( 5629): Adding GattService
,V/BluetoothPbapReceiver( 5629): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 5629): ***********state = 10
,E/BluetoothMasService( 5629): BluetoothMasObexConnectionManager: mIsEmailEnabled: true,
,I/ActivityManager(  968): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=5667 uid=10049 gids={50049, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/BluetoothMasService( 5629): Add permission for SmsProvider.,
D/PMS     (  968): acquireWL(20ea9b16): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 5356 1000 null
,W/System.err(  968): java.lang.Throwable: stack dump
,W/ContextImpl( 5356): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
,W/System.err(  968): 	at java.lang.Thread.dumpStack(Thread.java:490)
D/PMS     (  968): releaseWL(20ea9b16): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
W/System.err(  968): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
D/PMS     (  968): acquireWL(3f6d52a2): PARTIAL_WAKE_LOCK  StartingDockService 0x1 5356 1000 null
D/BluetoothManagerService(  968): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  968): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  968): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  968): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3085f66d:true
V/BluetoothMasService( 5629): Starting MAS instances
D/BluetoothAdapter( 5629): 31969811: getState() :  mService = null. Returning STATE_OFF
D/HtcBtWidget_BTWidgetProvider( 5532): onBTStateChanged() for widget: 
I/MailMessageReceiver( 5629): reg:com.android.bluetooth.btservice.AdapterApp@3f686c50 with com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@2656ae49
D/HtcBtWidget_BTWidgetProvider( 5532): updateWidget(context) for widget: 
,D/DockEventReceiver( 5356): finishStartingService: stopping service
I/MailManager( 5629): MailManager contruct! com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@2656ae49
D/PMS     (  968): releaseWL(3f6d52a2): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
V/EmailUtils( 5629): Manager Instance is not NULL
D/MdProvGlob( 5576): remove item 101 (p2d4in202) for 15:android.intent.action.ANY_DATA_STATE
,I/ActivityManager(  968): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=5688 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a
,W/OpenGLRenderer( 1472): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
D/MdProvGlob( 5576): remove item 101 (p2in17) for 15:android.intent.action.ANY_DATA_STATE
,D/MdScDataSum( 4904): [f5f.12.] summary 118:p1 ignore
,D/MdProvGlob( 5576): remove item 101 (p2d2in44) for 15:android.intent.action.ANY_DATA_STATE,
,D/MdProvGlob( 5576): remove item 101 (p2d1in25) for 15:android.intent.action.ANY_DATA_STATE,
,D/MdScDataSum( 4904): [f5f.17.] summary 118:p1 ignore
,D/Process (  968): killProcessQuiet, pid=5222
,I/ActivityManager(  968): Killing 5222:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/ActivityManager(  968): Recipient 5222,
,D/Process (  968): killProcessQuiet, pid=5248,
I/ActivityManager(  968): Killing 5248:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/Tethering(  968): interfaceRemoved wlan0,
E/Tethering(  968): attempting to remove unknown iface (wlan0), ignoring
,I/ActivityManager(  968): Recipient 5248
,D/HtcAdjCursorFactory( 5688): Set CursorWindow size to: 4194304 KB, Tid: 5710,
I/ActivityManager(  968): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=5715 uid=10079 gids={50079, 9997, 5001, 1028, 1015} abi=arm64-v8a
,E/SQLiteDatabase( 5688): Failed to open database '/data/user/0/com.htc.android.mail/databases/mail.db'.
E/SQLiteDatabase( 5688): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5688): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5688): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5688): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5688): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5688): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5688): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5688): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5688): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5688): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5688): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 5688): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5688): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5688): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5688): 	at com.htc.android.mail.kq.a(MailProvider.java:5368)
E/SQLiteDatabase( 5688): 	at com.htc.android.mail.kq.a(MailProvider.java:5433)
E/SQLiteDatabase( 5688): 	at com.htc.android.mail.MailProvider.query(MailProvider.java:2114)
E/SQLiteDatabase( 5688): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 5688): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 5688): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
E/SQLiteDatabase( 5688): 	at android.os.Binder.execTransact(Binder.java:454)
E/SQLiteOpenHelper( 5688): Couldn't open mail.db for writing (will try read-only):
E/SQLiteOpenHelper( 5688): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5688): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5688): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteOpenHelper( 5688): ,	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteOpenHelper( 5688): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5688): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5688): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5688): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteOpenHelper( 5688): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteOpenHelper( 5688): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteOpenHelper( 5688): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteOpenHelper( 5688): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 5688): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5688): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5688): 	at com.htc.android.mail.kq.a(MailProvider.java:5368)
E/SQLiteOpenHelper( 5688): 	at com.htc.android.mail.kq.a(MailProvider.java:5433)
E/SQLiteOpenHelper( 5688): 	at com.htc.android.mail.MailProvider.query(MailProvider.java:2114)
E/SQLiteOpenHelper( 5688): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteOpenHelper( 5688): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteOpenHelper( 5688): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
E/SQLiteOpenHelper( 5688): 	at android.os.Binder.execTransact(Binder.java:454)
W/SQLiteOpenHelper( 5688): Opened mail.db in read-only mode
W/BroadcastQueue(  968): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_MEDIA due to registered receiver BroadcastFilter{1e8b00b4 u0 ReceiverList{3d082987 5667 com.htc.musicenhancer/10049/u0 remote:135df5c6}}
,D/VoldConnector(  968): SND -> {27 volume mkdirs /storage/ext_sd/Android/data/com.htc.musicenhancer/cache/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.htc.musicenhancer/cache/
W/ContextImpl( 5667): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
,D/Tethering(  968): interfaceLinkStateChanged p2p0, false,
D/Tethering(  968): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
,D/EmailUtils( 5629): ============NULL aList========
V/EmailUtils( 5629): <-getEmailAccountIdList
V/BluetoothMasService( 5629): onCreate: mIsEmailEnabled: true
,D/Process (  968): killProcessQuiet, pid=4767
I/ActivityManager(  968): Killing 4767:com.google.android.gms.wearable/u0a24 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/SoundPicker( 5715): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,D/Tethering(  968): interfaceRemoved p2p0,
E/Tethering(  968): attempting to remove unknown iface (p2p0), ignoring
,I/ActivityManager(  968): Recipient 4767,
,D/BluetoothMasReceiver( 5629): Bluetooth STATE CHANGED to 10
,I/SoundPicker( 5715): SoundPickerReceiver [onReceive] startService
V/BluetoothMasService( 5629): onDestroy: mIsEmailEnabled: true
,V/BluetoothSapReceiver( 5629): SapReceiver onReceive 
V/BluetoothSapReceiver( 5629): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 5629):  Bluetooth Adapter state = 10
V/BluetoothSapReceiver( 5629): startService = false
,D/PMS     (  968): acquireWL(1333a852): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 4855 10011 null
D/AuthorizationBluetoothService( 1953): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/SoundPicker( 5715): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5715): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5715): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
,E/SQLiteLog( 4855): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 4855): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.android.providers.calendar/databases/calendar.db, handle: 0x5576b83070
,W/CalendarAlarmManager( 4855): runScheduleNextAlarm : SQLiteException,android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
,W/System.err( 4855): java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
,D/RingtoneManager( 5715): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,W/System.err( 4855): 	at android.database.sqlite.SQLiteSession.throwIfNoTransaction(SQLiteSession.java:915)
,W/System.err( 4855): 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:398)
,D/PMS     (  968): releaseWL(1333a852): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
W/System.err( 4855): ,	,at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:565)
W/System.err( 4855): 	at com.android.providers.calendar.CalendarAlarmManager.runScheduleNextAlarm(CalendarAlarmManager.java:276)
W/System.err( 4855): 	at com.android.providers.calendar.CalendarProviderIntentService.onHandleIntent(CalendarProviderIntentService.java:46)
,W/System.err( 4855): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 4855): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4855): 	at android.os.Looper.loop(Looper.java:155)
W/System.err( 4855): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/SoundPicker( 5715): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5715): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5715): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5715): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5715): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5715): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5715): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5715): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5715): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5715): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5715): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5715): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5715): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5715): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5715): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5715): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5715): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5715): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
,I/SoundPicker( 5715): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5715): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5715): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5715): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5715): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5715): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5715): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5715): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,E/SQLiteLog( 1671): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 1671): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.android.providers.contacts/databases/contacts2.db, handle: 0x5576b8e000
,W/ContactsProvider( 1671): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
W/ContactsProvider( 1671): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
W/ContactsProvider( 1671): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
W/ContactsProvider( 1671): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
W/ContactsProvider( 1671): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
W/ContactsProvider( 1671): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
W/ContactsProvider( 1671): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
W/ContactsProvider( 1671): 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:381)
W/ContactsProvider( 1671): 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:350)
W/ContactsProvider( 1671): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2230)
W/ContactsProvider( 1671): 	at com.android.providers.contacts.HtcContactsProvider2.performBackgroundTask(HtcContactsProvider2.java:11485)
W/ContactsProvider( 1671): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1887)
W/ContactsProvider( 1671): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ContactsProvider( 1671): 	at android.os.Looper.loop(Looper.java:155)
W/ContactsProvider( 1671): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ActivityManager(  968): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5745 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a
,I/SoundPicker( 5715): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
,I/SoundPicker( 5715): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5715): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5715): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5715): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5715): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5715): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5715): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5715): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5715): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5715): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5715): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5715): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5715): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac,
I/SoundPicker( 5715): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5715): getActualDefaultRingtoneUri(context, 2)
,I/SoundPicker( 5715): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
,I/SoundPicker( 5715): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5715): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5715): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5715): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5715): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5715): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5715): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5715): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5715): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5715): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5715): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5715): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/EASAppSvc( 5688): [ NA ]onCreate
,I/SoundPicker( 5715): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac,
,I/SoundPicker( 5715): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5715): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5715): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5715): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,D/Process (  968): killProcessQuiet, pid=4503
I/ActivityManager(  968): Killing 4503:com.google.android.talk/u0a112 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/VersionUtil( 5688): [ NA ]setIsFOTAing: true
,I/VersionUtil( 5688): [ NA ]onUpgrade: current version=100, latest version=100,
I/VersionUtil( 5688): [ NA ]setIsFOTAing: false
,D/ORMLib  ( 5297): put()
,E/SQLiteLog( 5297): (3850) statement aborts at 25: [UPDATE TaskSource SET SupportedColumns=?,IsTimePrecision2Sec=?,Description=?,PackageName=?,ServiceClassPath=?,last_update=?,VersionName=?,VersionCode=?,AccountType=? WHERE _id=2] disk ,
E/SQLiteDBG( 5297): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.task/databases/MyDB.db, handle: 0x5576b80200
E/DBProvider( 5297): disk I/O error (code 3850)
W/System.err( 5297): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
,W/System.err( 5297): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
W/System.err( 5297): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
W/System.err( 5297): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
,W/System.err( 5297): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/System.err( 5297): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1654)
W/System.err( 5297): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1600)
W/System.err( 5297): 	at com.htc.task.dm.DBProvider.update(DBProvider.java:552)
W/System.err( 5297): ,	at com.htc.task.APICProviderDecorator.update(APICProviderDecorator.java:490)
W/System.err( 5297): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
W/System.err( 5297): 	at android.content.ContentProviderClient.update(ContentProviderClient.java:251)
W/System.err( 5297): 	at com.htc.orm.Model.put(Model.java:143)
W/System.err( 5297): 	at com.htc.orm.Model.put(Model.java:170)
W/System.err( 5297): ,	at com.htc.task.sm.PluginUpdatedServiceConnection.updateDB(PluginUpdatedServiceConnection.java:195)
W/System.err( 5297): 	at com.htc.task.sm.PluginUpdatedServiceConnection$1.run(PluginUpdatedServiceConnection.java:125)
W/System.err( 5297): 	at java.lang.Thread.run(Thread.java:818)
,I/ActivityManager(  968): Recipient 4503
,I/EASAppSvc( 5688): [ NA ]onDestroy,
,I/SoundPicker( 5715): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5715): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5715): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
,I/EASAppSvc( 5688): [ NA ]onCreate
I/SoundPicker( 5715): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5715): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/HtcModeClient( 3169): handler message = 4011
E/HtcModeClient( 3169): Check connection and retry 6 times.
,D/WifiService(  968): New client listening to asynchronous messages
,E/WifiTrafficPoller(  968): ADD_CLIENT: 9
,I/SoundPicker( 5715): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac,
,W/EAS_NetworkUtil( 5688): [ NA ]getNetworkInfo: NetworkInfo is null
I/VersionUtil( 5688): [ NA ]setIsFOTAing: true
,I/SoundPicker( 5715): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/EASAppSvc( 5688): [ NA ]> uninitEASService
I/SoundPicker( 5715): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5715): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5715): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/EASRequestController( 5688): [ NA ]release
,I/VersionUtil( 5688): [ NA ]onUpgrade: current version=100, latest version=100
I/VersionUtil( 5688): [ NA ]setIsFOTAing: false
,W/EAS_NetworkUtil( 5688): [ NA ]getNetworkInfo: NetworkInfo is null
,I/SoundPicker( 5715): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,D/Prism.PackageStateRece_( 1472): action: android.intent.action.PACKAGE_ADDED
,I/SoundPicker( 5715): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5715): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/[PluginManager]RegisterService( 1565): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello
,I/[PluginManager]RegisterService( 1565): handle notify Blinkfeed plugin client changed
,D/ORMLib  ( 5297): put()
,E/SQLiteLog( 5297): (3850) statement aborts at 25: [UPDATE TaskSource SET SupportedColumns=?,IsTimePrecision2Sec=?,Description=?,PackageName=?,ServiceClassPath=?,last_update=?,VersionName=?,VersionCode=?,AccountType=? WHERE _id=3] disk 
E/SQLiteDBG( 5297): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.task/databases/MyDB.db, handle: 0x5576b80200
,E/DBProvider( 5297): disk I/O error (code 3850)
W/System.err( 5297): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
,W/System.err( 5297): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
W/System.err( 5297): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
,W/System.err( 5297): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
W/System.err( 5297): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/System.err( 5297): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1654)
W/System.err( 5297): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1600)
W/System.err( 5297): 	at com.htc.task.dm.DBProvider.update(DBProvider.java:552)
W/System.err( 5297): 	at com.htc.task.APICProviderDecorator.update(APICProviderDecorator.java:490)
W/System.err( 5297): 	,at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
W/System.err( 5297): 	at android.content.ContentProviderClient.update(ContentProviderClient.java:251)
W/System.err( 5297): 	at com.htc.orm.Model.put(Model.java:143)
W/System.err( 5297): 	at com.htc.orm.Model.put(Model.java:170)
W/System.err( 5297): 	at com.htc.task.sm.PluginUpdatedServiceConnection.updateDB(PluginUpdatedServiceConnection.java:195)
W/System.err( 5297): 	at com.htc.task.sm.PluginUpdatedServiceConnection$1.run(PluginUpdatedServiceConnection.java:125)
W/System.err( 5297): 	at java.lang.Thread.run(Thread.java:818)
,E/[PluginManager]RegisterService( 1565): Unable to getApplicationInfo for com.example.hello
E/[PluginManager]RegisterService( 1565): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
E/[PluginManager]RegisterService( 1565): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:281)
E/[PluginManager]RegisterService( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
E/[PluginManager]RegisterService( 1565): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
E/[PluginManager]RegisterService( 1565): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/[PluginManager]RegisterService( 1565): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/[PluginManager]RegisterService( 1565): 	at android.os.Looper.loop(Looper.java:155)
E/[PluginManager]RegisterService( 1565): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/EASPublicBinder( 5688): [ NA ]release
D/TaskBinder( 5688): [ NA ]release
D/TaskBinder( 5688): [ NA ]release
I/EASAppSvc( 5688): [ NA ]< uninitEASService
I/ActivityManager(  968): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5786 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/EASAppSvc( 5688): [ NA ]onDestroy
I/EASAppSvc( 5688): [ NA ]> uninitEASService
,I/ActivityManager(  968): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=5807 uid=10066 gids={50066, 9997, 3003} abi=arm64-v8a,
D/Process (  968): killProcessQuiet, pid=5324
I/ActivityManager(  968): Killing 5324:com.nero.android.htc.sync/u0a5 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/EASRequestController( 5688): [ NA ]release
,I/Prism.ItemManager( 1472): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1472): loadItems() com.htc.launcher.pageview.WidgetManager@30ca3377 +
I/Prism.WidgetManager( 1472): onLoadItems() +
,D/EASPublicBinder( 5688): [ NA ]release
,D/TaskBinder( 5688): [ NA ]release
D/TaskBinder( 5688): [ NA ]release
I/EASAppSvc( 5688): [ NA ]< uninitEASService
,W/ResourcesManager( 1472): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,I/ActivityManager(  968): Recipient 5324
,D/WifiService(  968): Client connection lost with reason: 4,
,W/ResourcesManager( 1472): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,D/Process (  968): killProcessQuiet, pid=5379,
I/ActivityManager(  968): Killing 5379:com.htc.backupreset/1000 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/Prism.WidgetManager( 1472): The same lists. No need to update. skip it.,
I/Prism.WidgetManager( 1472): onLoadItems() -
I/Prism.ItemManager( 1472): loadItems() com.htc.launcher.pageview.WidgetManager@30ca3377 -,
,E/SQLiteLog( 1472): (3850) statement aborts at 10: [DELETE FROM appscustomize WHERE _id=75] disk I/O error,
E/SQLiteDBG( 1472): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.htc.launcher/databases/launcher.db, handle: 0x5576b85b60
,I/ActivityManager(  968): Recipient 5379
E/AndroidRuntime( 1472): FATAL EXCEPTION: TaskWorker
E/AndroidRuntime( 1472): Process: com.htc.launcher, PID: 1472
E/AndroidRuntime( 1472): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1472): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1472): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/AndroidRuntime( 1472): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1472): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1472): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 1472): 	at com.htc.launcher.LauncherProvider.delete(LauncherProvider.java:344)
E/AndroidRuntime( 1472): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
E/AndroidRuntime( 1472): 	at android.content.ContentResolver.delete(ContentResolver.java:1320)
E/AndroidRuntime( 1472): 	at com.htc.launcher.pageview.RearrangeDBHelper$3.run(RearrangeDBHelper.java:151)
E/AndroidRuntime( 1472): 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
E/AndroidRuntime( 1472): 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
E/AndroidRuntime( 1472): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1472): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 1472): 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
