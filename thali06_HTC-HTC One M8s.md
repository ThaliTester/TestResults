#### Test 50242285ae22b3b_thali06_HTC-HTC One M8s Logs


```
--------- beginning of system
I/ActivityManager(  953): Recipient 4212
--------- beginning of main
D/GCM     ( 1986): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 1986): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/libc    ( 4848): [NET] android_getaddrinfofornet+,hn 48(0x6874632d636c75),sn(),hints(known),family 0,flags 4
D/libc    ( 4848): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4848): [NET] android_getaddrinfofornet+,hn 48(0x6874632d636c75),sn(),hints(known),family 0,flags 1024
D/libc    ( 4848): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4848): [NET] android_getaddrinfo_proxy+
D/libc    ( 4848): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 48(0x6874632d636c75),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:100, mark:917604
V/GmsCoreStatsServiceLauncher( 4507): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/ActivityManager(  953): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=4881 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
I/PackageManager(  953):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4507, uid=10024, userID:0
D/libc    (  400): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  400): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4848): [NET] android_getaddrinfo_proxy-, success
D/libc    ( 4848): [NET] android_getaddrinfofornet+,hn 12(0x35342e3233312e),sn(),hints(known),family 0,flags 4
D/libc    ( 4848): [NET] android_getaddrinfofornet-, SUCCESS
I/WebViewFactory( 4772): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
W/ResourcesManager( 4881): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4881): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/TelephUtils( 1556): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 93
I/MultiDex( 4881): VM with version 2.1.0 has multidex support
I/MultiDex( 4881): install
I/MultiDex( 4881): VM has multidex support, MultiDex support library is disabled.
D/AccFlag ( 1556): sku_id=118
D/libc    ( 4848): [NET] android_getaddrinfofornet+,hn 3,sn(),hints(known),family 0,flags 4
D/libc    ( 4848): [NET] android_getaddrinfofornet-, err=8
I/ActivityManager(  953): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=4910 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/LocationInitializer( 4507): Restart initialization of location
I/LibraryLoader( 4772): Time to load native libraries: 32 ms (timestamps 9320-9352)
I/LibraryLoader( 4772): Expected native library version number "",actual native library version number ""
D/TelephUtils( 1556): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 92
D/AccFlag ( 1556): sku_id=118
V/JNIHelp ( 4881): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
W/Atfwd_Sendcmd(  475): AtCmdFwd service not published, waiting... retryCnt : 4
W/art     ( 4772): Attempt to remove local handle scope entry from IRT, ignoring
D/TelephUtils( 1556): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 50
D/AccFlag ( 1556): sku_id=118
I/art     ( 1986): Explicit concurrent mark sweep GC freed 13013(746KB) AllocSpace objects, 3(252KB) LOS objects, 49% free, 4MB/8MB, paused 941us total 84.978ms
D/TelephUtils( 1556): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 49
D/AccFlag ( 1556): sku_id=118
W/ActivityThread( 4881): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 4881): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@35a2365e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4881): Installed default security provider GmsCore_OpenSSL
D/WearableService( 4881): callingUid 10024, callindPid: 4881
E/MDM     ( 1842): [141] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/GLSUser ( 1986): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
I/GLSUser ( 1986): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1986): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1986): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1986): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/art     ( 4772): Attempt to remove local handle scope entry from IRT, ignoring
I/RemoteViews( 1232): reapply : com.google.android.gms 2 40
D/DotMatrix( 1342): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1342): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/Search.LoginHelper( 4772): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 4772): com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
W/Search.LoginHelper( 4772): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 4772): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4772): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4772): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 4772): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 4772): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 4772): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 4772): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 4772): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 4772): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4772): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 4772): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4772): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 4772): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 4772): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 4772): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
E/VelvetNetworkClient( 4772): Failed to get auth token
D/libc    ( 4772): [NET] android_getaddrinfofornet+,hn 13(0x7777772e676f6f),sn(),hints(known),family 2,flags 1024
D/libc    ( 4772): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4772): [NET] android_getaddrinfo_proxy+
D/libc    ( 4772): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 13(0x7777772e676f6f),sn(),hints(known),family 2,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  400): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  400): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4772): [NET] android_getaddrinfo_proxy-, success
I/MusicStore( 4910): Database version: 120
D/libc    ( 4848): [NET] android_getaddrinfofornet+,hn 28(0x6874632d636c75),sn(),hints(known),family 0,flags 4
D/libc    ( 4848): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4848): [NET] android_getaddrinfofornet+,hn 28(0x6874632d636c75),sn(),hints(known),family 0,flags 1024
D/libc    ( 4848): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4848): [NET] android_getaddrinfo_proxy+
D/libc    ( 4848): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 28(0x6874632d636c75),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  400): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  400): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4848): [NET] android_getaddrinfo_proxy-, success
D/libc    ( 4848): [NET] android_getaddrinfofornet+,hn 13(0x3130342e38312e),sn(),hints(known),family 0,flags 4
D/libc    ( 4848): [NET] android_getaddrinfofornet-, SUCCESS
,D/VoldConnector(  953): SND -> {17 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 4910): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  953):  packet count Tx=96 Rx=141
E/WifiTrafficPoller(  953): notifying of data activity 3
D/WIFI_ICON( 1232): WifiActivity: 3
D/StatusBar.NetworkController( 1232): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
I/ActivityManager(  953): Killing 3992:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  953): killProcessQuiet, pid=3992
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/VoldConnector(  953): SND -> {18 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 4910): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
D/VoldConnector(  953): SND -> {19 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 4910): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
I/ActivityManager(  953): Recipient 3992
W/ResourcesManager( 4910): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4910): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/PMS     (  953): releaseWL(3965e12a): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 null
E/cutils-trace( 4956): Error opening trace file: Permission denied (13)
V/JNIHelp ( 4910): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/HtcModeClient( 3238): handler message = 4011
E/HtcModeClient( 3238): Check connection and retry 4 times.
I/ActivityManager(  953): Waited long enough for: ServiceRecord{428dd1b u0 com.htc.HTCSpeaker/.NGFService}
D/CustomizationManager( 4956): ====startRecUseTime====
D/htc.customization.log.level( 4956):  is 
W/CustomizationLogLevel( 4956): Level value is invalid, use default level 2
W/ActivityThread( 4910): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 4910): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1d9aca58: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4910): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 4910): GMSCore installation verified
I/ConfigStore( 4910): Config Database version: 1
I/ActivityManager(  953): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=4972 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
V/AlarmManager(  953): sending alarm PendingIntent{379b408c: PendingIntentRecord{330d53d5 com.htc.mobiledata startService}}, i=com.htc.mobiledata.intent.REQUEST, t=2, cnt=1, w=60228, Int=0
I/art     (  458): Explicit concurrent mark sweep GC freed 8665(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 154us total 20.075ms
D/CustomizationManager( 4956):  Read ACC file spent 0.041 (s)
D/CIDMapFileReader( 4956): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4956): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4956): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4956): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4956): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4956): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4956): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4956): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 4956): Parsing tag category name = system
I/CustomizationCIDLoader( 4956): Parsing tag category name = application
I/CustomizationCIDLoader( 4956): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4956): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4956): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4956): Parsing tag category name = Settings
I/CustomizationCIDLoader( 4956): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4956): add string-array item, value = 42507
I/CustomizationCIDLoader( 4956): add string-array item, value = 21902
I/CustomizationCIDLoader( 4956): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 4956): add string-array item, value = 23420
I/CustomizationCIDLoader( 4956): add string-array item, value = 22299
I/CustomizationCIDLoader( 4956): add string-array item, value = 24002
I/CustomizationCIDLoader( 4956): add string-array item, value = 23210
I/CustomizationCIDLoader( 4956): add string-array item, value = 23205
I/CustomizationCIDLoader( 4956): add string-array item, value = 23806
I/CustomizationCIDLoader( 4956): add string-array item, value = 23430
I/CustomizationCIDLoader( 4956): add string-array item, value = 23408
I/CustomizationCIDLoader( 4956): add string-array item, value = 27205
I/CustomizationCIDLoader( 4956): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 4956): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 4956): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 4956): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 4956): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 4956): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 4956): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 4956): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 4956): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 4956): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 4956): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 4956): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 4956):  Read CID file spent 0.088 (s)
D/CustomizationManager( 4956):  All configurations done spent 0.088 (s)
I/art     (  458): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 165us total 17.162ms
I/art     (  458): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 156us total 17.052ms
I/PackageManager(  953):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4910, uid=10159, userID:0
D/WifiDisplayAdapter(  953): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  953):     Client/Owner: Client
D/WifiDisplayAdapter(  953):     GroupId: 
D/WifiDisplayAdapter(  953):     Passphrase: 
D/WifiDisplayAdapter(  953):     SessionId: 0
D/WifiDisplayAdapter(  953):     IP Address: }
D/MediaRouterService(  953): Client com.google.android.music (pid 4910): Registered
D/WifiDisplayAdapter(  953): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  953):     Client/Owner: Client
D/WifiDisplayAdapter(  953):     GroupId: 
D/WifiDisplayAdapter(  953):     Passphrase: 
D/WifiDisplayAdapter(  953):     SessionId: 0
D/WifiDisplayAdapter(  953):     IP Address: }
I/MediaRouter( 4910): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
I/ActivityManager(  953): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=4999 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
I/ActivityManager(  953): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 pid 4956 on display 0
V/MusicLeanback( 4910): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
W/asset   (  953): Copying FileAsset 0x5591858710 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/NetworkMonitor( 4910): type=WIFI subType= reason=null isConnected=true
D/PMS     (  953): acquireHCC(2b4fcea7): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 953 1000 null
D/PMS     (  953): acquireHCC(3e1c0f54): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 953 1000 null
D/PMS     (  953): acquireWL(2d964efd): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 953 1000 null
E/WifiStateMachine(  953): handleMessage: E msg.what=131155
E/WifiStateMachine(  953): processMsg: ConnectedState
E/WifiStateMachine(  953):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=3.6, 0.0, 0.0  rx=7.1 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:562126144] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  953): processMsg: L2ConnectedState
E/WifiStateMachine(  953):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=3.6, 0.0, 0.0  rx=7.1 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:562126145] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  953):  get link layer stats 0
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SIGNAL_POLL'
I/FeedHostManager( 1604): [onPause]
I/FeedProviderManager( 1604): onPause
I/FeedHostManager( 1604): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@2e0f67b8
I/SocialFeedProvider( 1604): +onPause
I/SocialFeedProvider( 1604): -onPause
I/wpa_supplicant( 1330): environment dirty rate=12 [58][7][0]
E/WifiStateMachine(  953): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  953): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  953): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
I/AnimationUtil(  953): isHTCRecent(HelloWorld/Recent screens.)/6
I/ActivityManager(  953): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5020 uid=10374 gids={50374, 9997, 3003, 3001, 3002} abi=armeabi-v7a
E/WifiStateMachine(  953): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=30.82 txretriesrate=0.00 rxrate=35.56 userTriggerdPenalty0
E/WifiStateMachine(  953):  good link -> stuck count =0
E/WifiStateMachine(  953):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  953):  isHighRSSI       ---> score=65
E/WifiStateMachine(  953): handleMessage: X
D/WIFI_ICON( 1232): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1232): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/WifiWatchdogStateMachine(  953): RSSI current: 3 new: -60, 3
W/HtcSystemUPManager(  953): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/TrimMemoryManager( 1604): [trimMemory] 20
E/ActivityThread( 1604): Performing stop of activity that is not resumed: {com.htc.launcher/com.htc.launcher.Launcher}
E/ActivityThread( 1604): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.htc.launcher/com.htc.launcher.Launcher}
E/ActivityThread( 1604): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3624)
E/ActivityThread( 1604): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3712)
E/ActivityThread( 1604): 	at android.app.ActivityThread.access$1100(ActivityThread.java:144)
E/ActivityThread( 1604): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1388)
E/ActivityThread( 1604): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 1604): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread( 1604): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/ActivityThread( 1604): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 1604): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 1604): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread( 1604): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
W/asset   ( 5020): Copying FileAsset 0xac654928 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/NetworkMonitor( 4910): type=WIFI subType= reason=null isConnected=true
D/StatusBarManagerService(  953): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  953): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  953): hiding MENU key
I/PackageManager(  953):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=4910, uid=10159, userID:0
I/ActivityManager(  953): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=5047 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
I/ActivityManager(  953): Activity reported stop, but no longer stopping: ActivityRecord{1e2341c6 u0 com.htc.launcher/.Launcher t7}
D/MdScBoot( 4972): [b38.1.] 30@-135042 -> 40
D/MdScBootUi( 4972): [b38.1.2.] boot 118
D/MdScSimSt( 4972): [b38.1.2.] qry 118: 0+1 running 0
I/GHttpClientFactory( 4910): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 4910): Using platform SSLCertificateSocketFactory
W/ResourcesManager( 5047): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/ActivityManager(  953): Killing 4256:com.htc.backupreset/1000 (adj 15): empty #17
D/Process (  953): killProcessQuiet, pid=4256
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/WebViewFactory( 5020): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
I/ActivityManager(  953): Recipient 4256
D/Process (  953): killProcessQuiet, pid=4285
I/ActivityManager(  953): Killing 4285:com.htc.htccupd/u0a13 (adj 15): empty #17
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
I/CalendarProvider2( 5047): Created com.android.providers.calendar.CalendarAlarmManager@18a2e2e4(com.htc.providers.calendar.HtcCalendarProvider@3ed4434d)
I/LibraryLoader( 5020): Time to load native libraries: 9 ms (timestamps 734-743)
I/LibraryLoader( 5020): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5020): Binding Chromium to main looper Looper (main, tid 1) {29c67677}
I/LibraryLoader( 5020): Expected native library version number "",actual native library version number ""
I/chromium( 5020): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/ActivityManager(  953): Recipient 4285
I/BrowserStartupController( 5020): Initializing chromium process, singleProcess=true
W/art     ( 5020): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5020): ApplicationContext is null in ApplicationStatus
D/Process (  953): killProcessQuiet, pid=4333
I/ActivityManager(  953): Killing 4333:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/CalendarProvider2( 5047): wait start:true
E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  953):  packet count Tx=99 Rx=145
W/chromium( 5020): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5020): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5020): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5020): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 5020): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 5020): Build Date: 03/09/15 Mon
I/Adreno-EGL( 5020): Local Branch: 
I/Adreno-EGL( 5020): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 5020): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 5020):                  d74aa161a12b9c6fc6332151
W/System.err(  953): java.lang.Throwable: stack dump
W/System.err(  953): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  953): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  953): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  953): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  953): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  953): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@31a55d95:true
D/BluetoothAdapter( 5020): 124800514: getState(). Returning 12
I/ActivityManager(  953): Recipient 4333
D/Process (  953): killProcessQuiet, pid=4376
I/ActivityManager(  953): Killing 4376:com.android.settings:remote/1000 (adj 15): empty #17
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  953): Recipient 4376
D/CalendarProvider2( 5047): wait end:false
D/AutoSetting( 1643): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  953): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=5095 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a
D/AutoSetting( 1643): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1643): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1643): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1643): service - onStartCommand() REMOVE current location bundle
D/AutoSetting( 1643): service - handleMessage() setting current location null
W/art     ( 5020): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5020): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 5020): CordovaWebView is running on device made by: HTC
W/art     ( 5020): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5020): Attempt to remove local handle scope entry from IRT, ignoring
D/PhoneMonitor( 5095): Register our PhoneStateListener
D/MobileConnectivityChangeReceiver( 5095): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 5095): onReceive CONNECTIVITY_CHANGE networkType=1
D/Process (  953): killProcessQuiet, pid=4400
I/ActivityManager(  953): Killing 4400:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
D/PhoneMonitor( 5095): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
D/PhoneMonitor( 5095): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/ActivityManager(  953): Recipient 4400
W/chromium( 5020): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/PMS     (  953): acquireWL(376fcf5f): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4507 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  953): acquireWL(b954a75): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4507 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  953): releaseWL(376fcf5f): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
I/CheckinService( 4507): Checking schedule, now: 1452261073282 next: 1452248450522
I/CheckinService( 4507): active receiver: enabled
I/PackageManager(  953):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=4507, uid=10024, userID:0
I/CheckinService( 4507): Preparing to send checkin request
I/EventLogService( 4507): Accumulating logs since 1452261066758
I/CheckinRequestBuilder( 4507): Checkin reason type: 8 attempt count: 1
I/PackageManager(  953):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4507, uid=10024, userID:0
E/WifiTrafficPoller(  953): ADD_CLIENT: 7
D/WifiService(  953): New client listening to asynchronous messages
I/ActivityManager(  953): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4507): Failed to find provider info for com.google.android.wearable.settings
I/iu.SyncManager( 4507): SYNC; picasa accounts
D/NetworkLogImpl( 4507): Loaded NetworkSpeedPredictor
I/iu.Environment( 4507): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 4507): num queued entries: 0
I/iu.UploadsManager( 4507): num updated entries: 0
I/iu.SyncManager( 4507): NEXT; no task
D/ChimeraCfgMgr( 4507): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/art     (  953): Explicit concurrent mark sweep GC freed 14038(720KB) AllocSpace objects, 2(104KB) LOS objects, 33% free, 16MB/24MB, paused 1.267ms total 142.223ms
D/ChimeraCfgMgr( 4507): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/ActivityManager(  953): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5134 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/libc    ( 4610): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 4610): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4610): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 4610): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4610): [NET] android_getaddrinfo_proxy+
D/libc    ( 4610): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/FindExtension( 5020): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
D/libc    (  400): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  400): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4610): [NET] android_getaddrinfo_proxy-, success
,I/GLSUser ( 1986): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1986): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1986): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1986): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1986): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 4507): [AccountUtils] Account not ready
W/Kids    ( 4507): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4507): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4507): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4507): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4507): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4507): 	at com.google.android.gms.kids.account.k.d(SourceFile:103),
W/Kids    ( 4507): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4507): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4507): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4507): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4507): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4507): 	at java.lang.Thread.run(Thread.java:818)
,I/RemoteViews( 1232): reapply : com.google.android.gms 1 40
D/DotMatrix( 1342): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1342): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/Babel   ( 4610): connection state changed from UNKNOWN to CONNECTED,
I/InputMethodManager( 5020): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@4fda680, mServedView=org.apache.cordova.engine.SystemWebView{2fbb14b9 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@130e60fe
,I/InputMethodManagerService(  953): Disable input method client, pid=1604
D/StatusBarManagerService(  953): swetImeWindowStatus vis=0 backDisposition=0
,I/InputMethodManagerService(  953): Enable input method client, pid=5020
,I/PhoneStatusBar( 1232): setImeWindowStatus(false,false)
I/art     ( 4507): Explicit concurrent mark sweep GC freed 24432(1869KB) AllocSpace objects, 24(480KB) LOS objects, 47% free, 4MB/8MB, paused 3.418ms total 66.216ms
,I/ActivityManager(  953): Displayed com.example.hello/.MainActivity: +1s363ms
,D/PMS     (  953): releaseWL(2d964efd): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,W/BindingManager( 5020): Cannot call determinedVisibility() - never saw a connection for the pid: 5020
,I/chromium( 5020): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
W/XT9_C   ( 1419): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1419): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1419): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1419): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7
,E/WifiTrafficPoller(  953):  packet count Tx=104 Rx=149
,I/GLSUser ( 1986): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer,
I/GLSUser ( 1986): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1986): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1986): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1986): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/JsMessageQueue( 5020): Set native->JS mode to OnlineEventsBridgeMode,
,E/AndroidProtocolHandler( 5020): Unable to open asset URL: file:///android_asset/www/jxcore.js
,W/CheckinRequestBuilder( 4507): awaiting user notification for token
,D/DotMatrix( 1342): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1342): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1232): reapply : com.google.android.gms 3 40
,D/VoldConnector(  953): SND -> {20 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
W/ContextImpl( 5134): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
I/ActivityManager(  953): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5168 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,D/VoldConnector(  953): SND -> {21 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/ContextImpl( 5134): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 5134): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5134):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5134):   adb logcat -s GAv4
,D/VoldConnector(  953): SND -> {22 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 5134): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  953): SND -> {23 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/},
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl( 5134): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 5134): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/ResourcesManager( 5168): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
I/CalendarProvider2( 5047): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ResourcesManager( 5168): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ContentResolver( 5047): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  953): Killing 4423:com.android.smith/1000 (adj 15): empty #17,
D/Process (  953): killProcessQuiet, pid=4423
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
,W/GAv4    ( 5134): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/MultiDex( 5168): VM with version 2.1.0 has multidex support
I/MultiDex( 5168): install
I/MultiDex( 5168): VM has multidex support, MultiDex support library is disabled.
,W/GAv4    ( 5134): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  953): Recipient 4423,
,V/JNIHelp ( 5168): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/jxcore_app_log( 5020): JniHelper::setJavaVM(0xab4e78f8), pthread_self() = -1400867936
D/JX-Cordova( 5020): jxcore cordova android initializing
,W/ActivityThread( 5168): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5168): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@35a2365e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5168): Installed default security provider GmsCore_OpenSSL,
,W/jxcore-log( 5020): Initializing JXcore engine
W/jxcore-log( 5020): JXcore engine is ready
,D/PMS     (  953): releaseHCC(2b4fcea7): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     (  953): releaseHCC(3e1c0f54): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/global  ( 5134): [apache-http] Connection GC has been deprecated!,
,W/global  ( 5134): [apache-http] Connection GC has been deprecated!
,W/jxcore-log( 5020): Starting JXcore engine
,W/google-breakpad( 5207): -----BEGIN BREAKPAD MICRODUMP-----,
W/google-breakpad( 5207): O A arm 08 aarch64 3.10.49-g6be0435 #1 SMP PREEMPT Thu May 14 23:15:34 CST 2015
W/google-breakpad( 5207): S 0 D7A07DC0 D7A07000 00003000
,W/google-breakpad( 5207): S D7A07000 000000006077A0D73470A0D738AAD9D71802B4AC4816B4AC40FBBBAC6077A0D748000000F4407BF710D0CCACF4407BF7208B74D7AB3578F740000000C0ED7AF7E12778F701000000B874A0D7400000008052B6AC208B74D70000000010D0CCACB874A0D74000000000000000202A02D80000000000000000000000000000000001000000E086DBD71A000000170000001B0000000800000040B380D708000000C079A0D7000000004071A0D705000000309475D7B874A0D700000000040000001471A0D7782E02D808DFB6AC309475D77877A0D7010000000100000048F4B5AC08000000000000006077A0D7309475D748F4B5ACB874A0D74071A0D7208B74D7309475D7189475D700000000C874A0D73C71A0D7E02F02D854F4B5AC8C71A0D77471A0D748F4B5ACB874A0D78C71A0D78471A0D7B874A0D76C71A0D7F4950ED8309475D718DA4CD8608EA0D7E6FFFFFF54F4B5AC8C71A0D70000000001000000E42D7BF748F4B5ACFC71A0D7C0C90ED8A471A0D700A5D9D70000000000000000
W/google-breakpad( 5207): S D7A07180 00000000189475D76077A0D7B09072D7003582D7040000000100A0D700000000FCDEB6ACB071A0D700E87BDD0100000030E37BDD01000000F07CA0D700000000E875A0D7FCDEB6AC0804000002400000D0EDCCACB2503365F9FFFFFF0000000048F4B5AC60DB4DD801000000B874A0D7FFFFFF00C874A0D7CC72A0D704DA0ED800000000FFFFFF00010000000000000000000000010000008876A0D700000000003582D7606675D7F806CCAC0500000048F4B5ACFC06CCAC7472A0D75075DAD700000000000000000000000048F4B5AC01000000FC06CCAC7472A0D77C7000D848F4B5AC0100000001000000FC06CCACA472A0D770C500D81802B4AC4816B4AC40FBBBAC00000000AC72A0D748F4B5AC309475D748F4B5AC208B74D7003582D7CC72A0D7340902D8E074A0D7B874A0D7C874A0D748F4B5AC60DB4DD80100000000000000010000006473A0D7307F02D8E074A0D7FFFFFF00010000000000000048F4B5ACC874A0D76473A0D7549D02D83473A0D7E42D7BF7705EFBD7585EFBD7
,W/google-breakpad( 5207): S D7A07300 01000000309475D71C73A0D73C73A0D700F4B5ACA473A0D710C072D74816B4AC40FBBBAC017A63D900000000702375D7A474A0D760DB4DD8B073A0D7B250336560DB4DD848F4B5ACB874A0D7C874A0D7208B74D748F4B5AC60DB4DD8585EFBD7EC73A0D714FC02D8705EFBD701000000E074A0D70100000000000000C874A0D7C874A0D7A873A0D7705EFBD73500000001000000208B74D700000000C874A0D710C072D70000000000000000C073A0D70100000060DB4DD80000000008DFB6AC80FF72D7760000013876A0D748F4B5ACE074A0D7CD37C8AC48F4B5AC01000000CD37C8ACC874A0D76475A0D7D01B0CD801000000E074A0D700000000D8DDB6AC40DEB6AC68DEB6AC58DFB6AC08DFB6AC01DFB6AC90DEB6AC3874A0D7000000000000000048F4B5AC350000000000B5AC00000000F46340D8FC74A0D7E42D7BF780FF72D7008174D7408C74D700000000000000000200000000000000000000000200000048F4B5AC3876A0D7010000008876A0D7FFFFFFFFAC74A0D7683FE1D7
W/google-breakpad( 5207): S D7A07480 48F4B5AC11000000000000003876A0D73876A0D70E00000048F4B5AC68DEB6AC58DFB6AC003582D70000000082FFFFFF0000000082FFFFFF208B74D7A0CECCAC80CECCAC2B000000003582D700000000DC74A0D70875A0D7E12778F78A04AA830A00000081FFFFFF89CECCAC48F4B5AC504EB4AC4076A0D71400110058CBCCAC10CBCCAC53000000308D74D7AB3578F740000000C0ED7AF7E12778F7010000009079A0D7400000008052B6AC308D74D70000000010CBCCAC9079A0D74000000000000000202A02D8A075A0D76875A0D7209074D780FF72D7B2503365010000008C75A0D798980CD800000000273B78F7D0EDCCACE42D7BF701000000000000001876A0D705000000309475D79079A0D70000000004000000EC75A0D7782E02D828FF4CD80100000080FF72D79875A0D70000000048F4B5AC08000000000000001500000002000000FFFFFF009079A0D71876A0D7308D74D7309475D7189475D700000000A079A0D71476A0D7E02F02D84073C8AC000000000000000048F4B5AC
W/google-breakpad( 5207): S D7A07600 9079A0D76476A0D75C76A0D79079A0D74476A0D7F4950ED8309475D718DA4CD85091A0D7E6FFFFFF54F4B5AC6476A0D70000000001000000E42D7BF748F4B5ACD476A0D7C0C90ED848F4B5AC5876A0D70000000000000000E882A0D7189475D748F4B5ACB09072D7003582D704000000010074D74DE976F7000000001500000000000000E076A0D748F4B5ACD0EDCCAC1200000000040000287EA0D7E42D7BF748F4B5ACC8E9CCAC04000000B2503365D076A0D70000000048F4B5AC60DB4DD8010000009079A0D7FFFFFF00A079A0D7A477A0D704DA0ED800000000FFFFFF00010000000000000000000000010000000500000000000000000000000000000048F4B5AC1077A0D7000000000000000000000000E42D7BF70000000000000000000000000000000048F4B5AC48F4B5AC0100000001000000606675D7003582D7B879A0D7003582D77C77A0D7BCC400D81802B4AC4816B4AC40FBBBAC00000000300D4BD848F4B5AC309475D748F4B5AC308D74D7003582D7A477A0D7340902D8
W/google-breakpad( 5207): S D7A07780 B879A0D79079A0D7A079A0D748F4B5AC60DB4DD80100000000000000010000003C78A0D7307F02D8B879A0D7FFFFFF00010000000000000048F4B5ACA079A0D73C78A0D7549D02D810D0CCACE42D7BF7705EFBD7585EFBD748F4B5AC309475D7F477A0D700000000000000007C78A0D710C072D70000000008AFB4AC0100000000000000702375D77C79A0D760DB4DD88878A0D7B250336560DB4DD848F4B5AC9079A0D7A079A0D7308D74D748F4B5AC60DB4DD8585EFBD7C478A0D714FC02D8705EFBD701000000B879A0D70100000000000000A079A0D7A079A0D78078A0D7705EFBD73500000001000000308D74D700000000A079A0D710C072D700000000000000009878A0D70100000060DB4DD8105840D80700000080FF72D7760000010178A0D748F4B5ACB879A0D7CD37C8AC48F4B5AC01000000CD37C8ACA079A0D73C7AA0D7D01B0CD801000000B879A0D70000000000000000E878A0D70000000000000000000000000100000000000000B01C4BD8B2503365208B74D788FFFFFF
W/google-breakpad( 5207): S D7A07900 35000000D8D0FED73879A0D7F46340D8D479A0D7E42D7BF780FF72D7008174D7C08D74D7000000000000000002000000000000000000000008F6BDAC010000000004000008000000000000000800000058EACCAC0000008000000080000000007079A0D700000000000100000000000001000000000000008879A0D7003582D70000000082FFFFFF0000000082FFFFFF308D74D7010000001A00000017000000003582D70800000040B380D708000000C079A0D7000000000A00000081FFFFFF1C000000000000000001000000000000017AA0D748F4B5AC40FBBBAC9C82A0D700000000000000000000000000000000787AA0D760F6BDACD337C8AC20F6BDAC20F6BDAC00000000247AA0D7A089EAD780FF72D7B250336548F4B5AC48F4B5AC787AA0D7407AA0D7209074D780FF72D7B250336501000000647AA0D798980CD8000000000000000048F4B5ACE42D7BF70100000048F4B5AC08F6BDAC707AA0D7EC7DA0D7B09A0CD8787AA0D70000000008F6BDAC0000000028FF4CD801000000
W/google-breakpad( 5207): S D7A07A80 80FF72D7707AA0D700000000000000005600000048F4B5AC00000000000000000000010000010000000000000000000000000000000000000000000000000000010100000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000100000100000000000000000000000000000000000000000100010000010101000000000000000000000000000000000000000000000000000000000000000000000000000000000000609174D700000000010000000100000000000000
W/google-breakpad( 5207): S D7A07C00 00000000000000000000000048F4B5AC6C7DA0D760DB4DD8787CA0D7687CA0D748F4B5AC6C7DA0D7B47CA0D778A402D80000000000000000000000000000000000000000907DA0D7907DA0D7707CA0D76C7CA0D700000000000000000000000020D072D738A272D720D072D70000000000000000687EA0D720D072D7687CA0D76C7DA0D70000000000000000000000000000000048F4B5AC08F6BDAC0000000048F4B5AC010000000000000088FFFFFF2C7EA0D7D01B0CD800F6BDAC00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000B80000000000000048F4B5ACF46340D8C47DA0D7E42D7BF7003B75D70000000000000000E0D072D70000000002000000000000000000000048F4B5AC5C02B4AC000000007877A0D701000000C0F174D7000000000000000020B872D7B25033657C7DA0D7247EA0D748F4B5AC030000009C7DA0D79031B4AC003B75D7301B81D70000000082FFFFFF0000000082FFFFFF
W/google-breakpad( 5207): S D7A07D80 40B072D79001B4AC08F6BDAC01000000609174D748F4B5ACC0F174D700000000000000000000000003000000AA0000006B0000006E41010000000000F07DA0D7387EA0D700000000387EA0D71C7EA0D7087EA0D700000000548EA0D7F0B31BD8107EA0D700000000047EA0D784D1FED70000000000000000E42D7BF7000000008C81A0D7349B0CD848F4B5AC48F4B5AC08F6BDAC01000000801D75D7003B75D748F4B5AC00000000F8F4BDAC08F5BDAC010000002F007BF700100000E42D7BF70010000048F4B5ACA0F5BDAC607EA0D7DC81A0D7B09A0CD80200000000000000A0F5BDAC0000000028FF4CD801000000003B75D7607EA0D7000000000000008000000000000000000000000000000000020000006176A0D700017EDDFFFFFFFF34200181C059C9AC8059C9AC4B00000040B972D7AB3578F740000000C0ED7AF7E12778F701000000D882A0D7400000008052B6AC40B972D70C0000008059C9ACD882A0D7400000000C000000202A02D8D083A0D701000000D0967EDD68000000
W/google-breakpad( 5207): S D7A07F00 00000000000000000000000000000000207FA0D700000000100000003880A0D7307FA0D700000000C07FA0D711000000A09375D7D882A0D70000000010000000947FA0D7947FA0D748F4B5ACB89375D70000000000000000AE01000048F4B5AC080000000800000014000000B89375D748F4B5ACD882A0D7C07FA0D740B972D7B89375D7A09375D700000000D482A0D7BC7FA0D7E02F02D854F4B5AC0C80A0D72602000048F4B5ACD882A0D70C80A0D70480A0D7D882A0D7EC7FA0D7F4950ED8B89375D718DA4CD8F084A0D7E6FFFFFF54F4B5AC0C80A0D7300000002480A0D71480A0D7C0DFB6AC7C80A0D72E3CC2AC608DA0D7E08AA0D700000000000000002C0000001480A0D7B090A0D75C02B4AC2480A0D77839E2D7E88AA0D7E88AA0D7D480A0D7280EB7AC5C80A0D77479DBD700000000C0F0B5AC40FBBBAC04000000143CC2AC60DB4DD848F4B5AC00000000E8347BC19001B4ACB480A0D7D087DBD79480A0D7C0F0B5AC01000000D882A0D7C8C1CAACE8347BC1143CC2AC00D381D7
W/google-breakpad( 5207): S D7A08080 040000000000000001000000B16CF6EEE88AA0D7008BA0D704000000143CC2AC60DB4DD8000000000200000044D7FFFFFC80A0D710A4E2D7E88AA0D7E88AA0D7A0EDB6AC2E3CC2ACA0EDB6AC00000000FC80A0D7101FD9D7C894CAAC100EB7ACE88AA0D7380EB7AC29020000380EB7AC00000000A890A0D74C81A0D7FC9AD9D748F4B5AC00000000E851CC8D2481A0D76C81A0D701000000008BA0D7B090A0D70000000000000000C894CAACE88AA0D711000000008BA0D71A0200000100000050EDB6ACE88AA0D77C81A0D700A5D9D7FFFFFFFFD08DA0D7008BA0D727000000E88AA0D7E88AA0D76882A0D7008BA0D70100000050EDB6AC2C82A0D7E0A7D9D7488BA0D7E88AA0D7E88AA0D7E8E1B6ACC8000000943A40D8383A40D800000000008BA0D7383A40D8383A40D8943A40D874000000CC81A0D70900000001000000008BA0D7B090A0D70100000044D7FFFF1C82A0D7E88AA0D713000000008BA0D7C80000006082A0D7B090A0D7C0E1B6ACC0E1B6AC70DE81D7E88AA0D700000000
W/google-breakpad( 5207): S D7A08200 2C82A0D700B2D8D700000000E88AA0D7000000006882A0D7008BA0D76C82A0D7C089A0D7000000000100000050D381D7C0E673D7000000004082A0D7803E75D7C0E673D7F6EBCCAC0400000000020000C089A0D7880000000000000078EDB6AC7C82A0D77C82A0D700020000505C40D8C089A0D7000000009C82A0D7B830E1D778EDB6AC01000000C089A0D78800000048F4B5AC00000000BC82A0D7345EE1D7C089A0D778EDB6AC60DB4DD848F4B5ACA0EDB6AC260100004483A0D74476E1D7C089A0D7FBEBCCACC089A0D7C089A0D7105840D80A000000A8010000350000000483A0D70483A0D7C089A0D76039B6AC35000000C089A0D7B839B6AC48F4B5AC4483A0D700ECCCAC00000000C089A0D7C089A0D73E0000000000000048F4B5AC3C83A0D73C83A0D700000000C089A0D700000000000000006483A0D7FC3AE1D76483A0D76CF6E1D7C089A0D7C089A0D7100EB7AC60DB4DD848F4B5AC02000000EC83A0D76076E1D7C089A0D7DCEBCCAC0400000000020000C089A0D7E7EBCCAC
W/google-breakpad( 5207): S D7A08380 03000000C089A0D7C089A0D7560000005600000048F4B5ACB483A0D7F2EBCCAC03000000C089A0D7C089A0D7560000005600000001ECCCAC08000000C089A0D7370000003700000048F4B5AC02000000EC83A0D7EC83A0D7C089A0D73700000088000000450000001C84A0D7983EE1D7C089A0D70000000060DB4DD8880000004500000048F4B5ACC089A0D701000000108AA0D7FFFFFFFF4C84A0D7683FE1D7E839B6AC110000006C84A0D7C089A0D7C089A0D71000000048F4B5AC020000000000000048F4B5AC7484A0D702ECCCAC00000000C089A0D7C089A0D7020000003A000000000000008C84A0D78C84A0D700000000C089A0D728EDB6AC3A000000105840D8020000001485A0D74084E1D70200000001000000108AA0D7FFFFFFFFD484A0D7683FE1D7D839B6AC00000000F484A0D7C089A0D7C089A0D70300000048F4B5AC010000000000000048F4B5ACFC84A0D7D4EBCCAC0000000005ECCCAC01000000C089A0D7C089A0D73800000000000000FFFFFFFF1485A0D71485A0D7
W/google-breakpad( 5207): S D7A08500 B0ECB6ACC089A0D748F4B5AC000000005C85A0D710E4E1D70100000001000000108AA0D720EBB6AC5C85A0D7683FE1D73A000000000000005C85A0D7C089A0D7600EB7AC60DB4DD800000000600EB7AC0C01000048F4B5ACE485A0D7887BE1D728EDB6ACDBEBCCAC01000000C089A0D7600000005100000000000000570000009C85A0D79C85A0D7C089A0D76000000048F4B5AC00000000E485A0D768DCE1D7BC85A0D7A83FE1D7C8FFFFFF06ECCCAC05000000C089A0D7880EB7AC5100000000000000600EB7ACE485A0D7E485A0D7C089A0D7880EB7AC60DB4DD8000000006C86A0D7F476E1D700000000570000007C86A0D76076E1D7C089A0D71486A0D701000000C089A0D74486A0D748F4B5AC3486A0D73486A0D7010000004486A0D7C089A0D774E0B6AC48F4B5AC00000000D4FFFFFFA8EBCCACB85C40D8C089A0D7D300000051000000B7000000C089A0D7F8EAB6ACC089A0D7F8EAB6AC00000000B00EB7ACEE000000F486A0D7EC6BE1D70100000048F4B5AC9486A0D764C0E1D7
W/google-breakpad( 5207): S D7A08680 D0EAB6ACB7000000A3EBCCAC000000001C87A0D74478E1D7C089A0D7010000000400A0D700000000000000001C87A0D700000000F3000000FFFFFFFFFFFFFFFF30F4CCACC089A0D7C089A0D707000000B00EB7ACC089A0D748F4B5ACC089A0D748F4B5AC00000000B00EB7ACBEEBCCAC6487A0D7A4A0E1D70000000000000000010000001C87A0D7C089A0D76000000048F4B5AC000000006487A0D70100E0D700000000000000002088A0D700000000EE000000FFFFFFFFFFFFFFFF12000000C887A0D7C089A0D7B00EB7AC60DB4DD80000000000000000B200000048F4B5ACEC87A0D77474E1D700000000F022E2D7C03182D73015E2D7C03182D748F4B5AC01000000D8DDB6AC40DEB6AC68DEB6ACB00EB7ACF8EAB6AC880EB7AC600EB7AC28EDB6AC380EB7AC100EB7AC78EDB6AC60E2B6AC0000B6AC000040D8D8DDB6AC944A40D818DEB6AC8D000000470000000488A0D7983EE1D768DEB6AC0000000060DB4DD88D0000004700000048F4B5ACC089A0D701000000108AA0D748F4B5AC
W/google-breakpad( 5207): S D7A08800 3488A0D7683FE1D748F4B5AC1100000000000000C089A0D7C089A0D71D00000048F4B5AC68DEB6AC90DEB6AC48F4B5AC58000000F4407BF7C8FBCCACF4407BF7D801000001000000C0F0CCAC01000000F2FFFFFF000000006488A0D79088A0D7E12778F7F470043CC0F0CCAC9001B4ACC9F0CCAC48F4B5AC504EB4ACC889A0D7BC88A0D7BC88A0D7B8A8C5014BF2CCACC9F0CCACC701000006000000C089A0D700000000C089A0D7D89DA0D719000000D89DA0D7EBE976F7000000000000000002000000B4427BF70200000000000000D89DA0D71900000078F8CCACDC01B4ACE88AA0D7C089A0D780F8CCAC273B78F780F8CCACC0ED7AF7008BA0D7DC01B4ACE88AA0D7C089A0D70100000079A176F7E08DA0D7EC5CE2D79041B4ACE88AA0D73489A0D79C62D8D71091A0D748F4B5ACFC90A0D7C8E1E0D76C89A0D700000000944A40D8010000007E05000002000000D8DDB6AC7889A0D7D8DDB6AC7089A0D7603374D7C0E673D790E472D7803E75D7A04C4BD800000000583EBAAC00000000
W/google-breakpad( 5207): S D7A08980 00000000B9000000000000007E05000018000000010001000001000000010000000000000000000000000000000000000000000000000000000000000000000000DEB6AC00000000803E75D7D0EACCAC48F4B5ACE089A0D7000000000000000048F4B5ACF089A0D748F4B5ACF889A0D700000000000000000000000070040000000000007E0500000000000030F4CCAC48F4B5ACD0EACCAC380100000004000048F4B5ACB8EFCCAC48F4B5AC30F4CCAC49000000000400001E00000071040000370100009A0500002D000000E08AA0D7108AA0D7E88AA0D7944A40D80000000000000000000000000000000048F4B5AC7E05000000000000090000000000000000000000908AA0D748F4B5AC988AA0D7000000000000000000000000000000000100000048E0B6AC000000000000000048F4B5ACB0FBCCAC010000000100000048F4B5ACD08AA0D748F4B5AC78F0B3AC01000000010000000500E0AC020000001F0060D802000000300D4BD82097A0D7FDFFFFFF54F4B5AC48F4B5AC5C02B4AC
W/google-breakpad( 5207): S D7A08B00 48F4B5AC108BA0D72000000080000000000000001C000000250000002A0000003D000000480000005700000098000000C800000008010000190100001B0100001C01000025010000450100004F010000650100006C0100008C0100008E0100008F0100009001000091010000920100009301000094010000AD010000E3010000FE0100002C0200002E020000FFFFFFFFF4010000150200002B020000320200003F0200006C0200006E0200006F0200007D0200007F02000080020000A2020000A5020000A6020000D0020000F3020000010300001F03000020030000440300005603000067030000690300006B0300006C030000780300007B030000FFFFFFFF48F4B5AC048EA0D7481B4ED860DB4DD80C8EA0D701000000BC8CA0D74C8502D8705EFBD75100000060E340D80000000000000000108EA0D7548CA0D750050DD8D8EACCAC01000000E42D7BF760E340D8705EFBD7808675D7848CA0D7000000000000000082FFFFFF018DA0D7D08CA0D7F8344BD82097A0D7E6FFFFFF54F4B5AC
W/google-breakpad( 5207): S D7A08C80 518DA0D7548CA0D7508CA0D7648DA0D70C8DA0D7B250336540FBBBAC51000000A88DA0D7208EA0D7048EA0D7000000000C8EA0D701000000548DA0D7A8E602D8808675D7000000005100000010C072D70000000024DA4CD800FCBBAC40FBBBAC5C8DA0D7DCEF0ED8F0E9CCAC5F8DA0D7188DA0D7608DA0D760DB4DD801000000048EA0D748F4B5AC70040000010000007E0500001C0000007089A0D73E00000010000000290200002A020000688DA0D7B0D181D700002440100000003A000000030000002A0200002B020000108EA0D70000000000000000000000003B0000000E0000002C0200002D02000082FFFFFF0000000000000000000000003C0000000E0000002E0200002F020000885AB5ACB0D181D70000F03F000000000000000003000000000000009C050000E218C2AC2C3CC2AC283CC2ACD037C2AC2E3CC2AC2E3CC2AC583EBAAC000000000000000048F4B5AC80F8CCAC04000000400000004500720072006F0072003A00200059006F00750020006D006100790020006E00
W/google-breakpad( 5207): S D7A08E00 6F00740020006800610076006500200061002000720065006100640020006100000000000000000000000100000100000000000000000000E42D7BF70000000048F4B5AC1CB31BD8608EA0D700000000DC91A0D7349B0CD8000000000000000008F5BDAC0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000100000100000000000000000000000000000000000000000100010000010101000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000001000000
W/google-breakpad( 5207): S D7A08F80 0100000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000100000001010001000000000001000100010000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000048F4B5AC00000000E88AA0D700000000C8DDB6ACD8DDB6AC48E0B6AC000000000000000000000000DC01B4AC01D072D748F4B5AC5C02B4AC40E9B6AC008BA0D70190A0D7904474D7000000000000000048F4B5ACB25033655491A0D7AC91A0D748F4B5AC030000002491A0D79031B4AC803E75D79041B4AC6C91A0D71CB3FED7
W/google-breakpad( 5207): S D7A09100 00000000585EFBD75491A0D79001B4AC904474D71802B4AC803E75D748F4B5AC904474D7000000000000000000000000600000000501000030020000F7E05200905B2E05F7EFE55248F4B5AC9492A0D7DC91A0D778A402D80000000078D14CD860DB4DD89093A0D7DC91A0D7B892A0D7B892A0D79891A0D79491A0D77C044DD8904474D71802B4AC70E072D7D0D973D770E072D708AE0BD8CC91A0D748F4B5AC0000000090F4BDAC50F4BDACC03FC8AC30F3BDAC4C92A0D748F4B5ACB250336548F4B5AC88FFFFFF0000000088FFFFFFB092A0D760DB4DD85493A0D7905E0CD800F5BDACD092A0D70000000000000000000000000000000000000000000000000000000000000000D08F73D7000000003700000000000000B80000000000000000000000F46340D8EC92A0D7E42D7BF7803E75D7F08D74D7208E74D7E0E173D700000000002281D700000000803E75D70000000000000000000000000000000078F8BDAC70F8BDAC0000000031F3BDAC000000000000000031F3BDAC00000000
W/google-breakpad( 5207): S D7A09280 00000000E0A272D740B072D740B072D748F4B5AC50D281D7F08A74D788FFFFFF0000000082FFFFFF40B072D70000000008F5BDAC0000000070E072D781F572D748F4B5AC5C02B4AC00000000108DA0D728FF4CD801000000803E75D7B092A0D700000000005033650000000048F4B5AC40FBBBAC00000000000000000000000000000000000000009093A0D708F5BDACDBF0CCAC90F4BDAC50F2BDAC000000003C93A0D7A089EAD780F672D7B250336548F4B5AC48F4B5AC9093A0D75893A0D7C0E673D780F672D7000000004807B7AC7C93A0D78C980CD800000000E42D7BF700100000E42D7BF70010000048F4B5AC5097A0D78893A0D70497A0D7B09A0CD830AD73D748F4B5AC5097A0D70100000028FF4CD80100000080F672D78893A0D7000000000000000000000000000000000000000000000000010100000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
W/google-breakpad( 5207): S D7A09400 00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000048F4B5AC48F4B5ACE094A0D76495A0D730054DD8D494A0D790FC0ED848F4B5ACB896A0D7EC94A0D7703D0FD8B896A0D740B072D70100000000000000C8034DD86495A0D76CF2BDAC30054DD80495A0D764C50BD80000000000F672D740B072D7A896A0D70495A0D748F4B5AC48F4B5AC0100000060F2BDAC000000007C96A0D7D01B0CD80000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000F46340D81496A0D7E42D7BF700F672D70000000000000000C0E673D7000000000200000000000000000000000000000000000000
W/google-breakpad( 5207): S D7A09580 000000000000000000000000000000010000000101000100000000000100010001000000000000000000000000000000000000000000000000000000000000000000000082FFFFFF0000000082FFFFFF00000000000000000000000000000000000000000000000000000000000000D748F4B5AC000000005890A0D735000000C8DDB6ACD8DDB6AC0CDEB6AC000000006887A0D748F4B5AC40FBBBAC0000000000000000000000000000000000000000A896A0D7A0F2BDAC7701B4AC60F2BDAC60F2BDAC000000006496A0D7A089EAD700F672D7B250336548F4B5AC48F4B5ACA896A0D78096A0D70000000000F672D7B250336501000000A496A0D798980CD800000000AC97A0D7D897A0D700F672D73497A0D748F4B5ACA896A0D71097A0D7F496A0D794A30CD818FF4CD80000000000F672D70100000040B072D788FFFFFF40B072D7000000005897A0D7042D1ED86E6100003497A0D75897A0D748F4B5AC5097A0D7B25033654807B7ACE42D7BF74097A0D748F4B5ACF097A0D7B897A0D7
W/google-breakpad( 5207): S D7A09700 AC97A0D7649F0CD80001000040B072D740B072D740B072D75097A0D70100000000000000F6FFFFFF54F4B5ACFCCCFBD748F4B5AC4097A0D70300000008000000C0E673D788FFFFFF40B072D788FFFFFF70E072D788FFFFFFC0E673D788FFFFFF7897A0D77497A0D7000000007897A0D79C97A0D72C5C1ED8000002004807B7AC4007B7ACB25033656898A0D748F4B5AC0098A0D7F097A0D7F897A0D7EC97A0D782FFFFFF4007B7ACDC97A0D7D0D1FBD74007B7ACF897A0D740B072D788FFFFFF88FFFFFF8898A0D7010000009898A0D70898A0D7000000003C98A0D770631ED8F897A0D7000000000000000040B072D7C0E673D788FFFFFF0000000082FFFFFF010000004007B7AC0000000082FFFFFF48F4B5AC000000007898A0D7A898A0D7C498A0D75898A0D7E898A0D79898A0D7E098A0D78898A0D72499A0D7A4201CD88898A0D775BCA4F51066B1F57898A0D76898A0D74099A0D7C0E673D788FFFFFF48F4B5AC00000000C0E673D788FFFFFF48F4B5AC0000000040B072D788FFFFFF
W/google-breakpad( 5207): S D7A09880 48F4B5AC0000000070E072D788FFFFFF48F4B5AC00000000409BB1F5C0C24DAB23370000C86FBFACF0A6BFAC6E6100006E61000001F0B3AC00000000002D7BF748F4B5ACC8F9B6AC070000000000000001D9ADF50000000000D1ADF548F4B5AC01D1ADF5D4D1ADF50000000082FFFFFF000000000001000048F4B5AC82FFFFFF000055003099A0D74099A0D7083A1E7600D1EC128054F212D8CAB5AC00FCFA125C99A0D7B46F1BD80896B3AC8B03000070E072D788FFFFFF48F4B5AC0000000070E072D788FFFFFF48F4B5AC00000000D0F337D8B8DCB5AC6C99A0D72C591BD88B03000040FBFA12000000002DB065F488411E760000000001000000004EEC120000000040FBFA12083A1E7600D1EC128054F21200FCFA12000000009B9965F4083A1E76004EEC1220FCFA12A088F612D83C1E76E0D0EC1220FCFA122031ED12D8CAB5AC20FBFA12D09BA0D7FC9800006040F21240D1EC12004EEC12E0D0EC12FC40ED12D83C1E76E0D0EC12004EEC12004EEC12D0D9E312D09BA0D7C5A265F4
W/google-breakpad( 5207): S D7A09A00 D83C1E76004EEC12E0D0EC12DF8D8CF5D83C1E76D0D9E312149AA0D700000000249AA0D7483B1E7680D5C712483B1E7680D5C7125082C712004EEC12299C65F4483B1E76D0D9E312884A1E76CD5C64F4884A1E76004EEC1280D5C7125082C712D8CAB5ACB2503365D09BA0D7D8CAB5AC0000000040E1DA12D0D9E31240E1DA12482A1D71482C1D7100000000A17FFC74482A1D71AB03000040772571E12E0974D0D9E31240E1DA12A0D0EC12F77FFC74482C1D7148F3000000000000A7332475D806F6754077257140E1DA124077257140E1DA12A0D0EC12A0D0EC12E32C24754077257148F3000000000000689BA0D7A09BA0D748F3000000000000000000000000000000351D71A0D0EC124792FC7400351D7158B4A7AC0000000048F300009C13000086280000D0D9E312B77EFC740000000060D0EC1238301D7100000000D0D9E312000000004020ED121188FC7448F300000000000040E1DA120000000000000000A0D0EC1200EBEB122F5264F400000000684B1E7600EBEB12A0D0EC12
W/google-breakpad( 5207): S D7A09B80 D0D9E31200000000D09BA0D7535364F4684B1E7613000000E42D7BF7AB3578F70C000000C0ED7AF7E12778F7C09BA0D7F8AFB1F5F09BA0D7089CA0D7497A8CF50000000000EBEB1258084EABD8CAB5AC684B1E765CCBB5ACD8CAB5AC684B1E76809CA0D73956A0F5689CA0D7330863F404000000330863F4689CA0D7E42D7BF70000000000000000000000000000000000000000000000007887A4AC0100000000000000B250336580000000689CA0D700EBEB12609DA0D7589CA0D7684B1E76409DA0D700000000330863F437E3A3F5689CA0D7330863F4D8CAB5ACDD665AF6010000000A0000000000000000000000330863F40100000004000000809CA0D700EBEB12B250336500000000B085B5AC00000000B2503365C49CA0D78B9DA0D7E42D7BF7D89DA0D7309DA0D7F8AFB1F5609DA0D7D7ABA6F5F8AFB1F5609DA0D700000000A9CBAAF561642D31819DA0D700000000D8CAB5AC98B1B1F5309DA0D7F8AFB1F5409DA0D73C9DA0D7DB3EA5F500000000000000000000000000000000
W/google-breakpad( 5207): S D7A09D00 0000000000000000409BB1F5E42D7BF7E0C24DAB389DA0D730D9ADF5FCD1ADF510B0B1F530D9ADF51CD1ADF530D1ADF50000000000005500FFFFFFFF00005500D8CAB5ACB085B5ACF8784EABD8CAB5AC430000005500000000000000B8CEB5AC00004300C0CEB5ACC0CEB5ACD11477F7FFFFFFFF000000000000000000000000145468726561642D31333100B2503365FFFFFFFFB8CEB5ACF8CEB5ACB8CEB5AC78000000C0CEB5ACC0CEB5AC39E176F7D09DA0D759E176F739E176F7C0CEB5AC39E176F71DC276F7D09DA0D700000000D09DA0D7B8CEB5AC160000000000000000000000B25033650000000000000000000000000000000000000000000000000000000000000000D8CAB5AC0000000000000000F855B2ACC828A3AC00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000B085B5AC6CD1B5ACDC01B4AC0000000000000000E44757D8
W/google-breakpad( 5207): S D7A09E80 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
W/google-breakpad( 5207): C 0600004000000000000000000000000000000000387EA0D7F87DA0D748F4B5ACF87DA0D700000000347EA0D79093A0D7DC7DA0D7A0DB4DD8C07DA0D708431ED88CB676F730000D600000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
W/google-breakpad( 5207): M AB1E5000 00000000 00003000 C750FD6E7CED0F0AD7CEB1759DE7603D0 app_process32
W/google-breakpad( 5207): M D7A0A000 00000000 00AE1000 10FB4E5C3E6238990CCE2CA03AC6B3420 libjxcore.so
W/google-breakpad( 5207): M DF34F000 00000000 0046A000 F1E6740F7B1AC1EEA523202463736E350 libsc-a3xx.so
W/google-breakpad( 5207): M E1651000 00000000 01AE1000 488126E5C3908224A6BF664CC97A94320 libwebviewchromium.so
I/WebViewFactory( 5134): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
I/WVCdm   (  451): CdmEngine::OpenSession
I/WVCdm   (  451): Level3 Library Sep 25 2014 17:10:03
,I/LibraryLoader( 5134): Time to load native libraries: 4 ms (timestamps 2529-2533)
I/LibraryLoader( 5134): Expected native library version number "",actual native library version number ""
W/WVCdm   (  451): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/google-breakpad( 5207): M E7A51000 00000000 00141000 A2F452629C440CEF0204E3028EB5B4E60 libGLESv2_adreno.so
D/DrmWidevineDash(  451): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  451): Service_Initialize: starts!
W/google-breakpad( 5207): M E8147000 00000000 0000E000 65B4EE8C28DFCF943EF3BAB5CE2CF57E0 libstagefright_amrnb_common.so
D/QSEECOMAPI: (  451): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  451): App is not loaded in QSEE
E/QSEECOMAPI: (  451): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  451): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  451): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  451): App is not loaded in QSEE
W/google-breakpad( 5207): M E8155000 00000000 0001B000 68801872D531A43011451250F1F30D060 libvorbisidec.so
W/google-breakpad( 5207): M E8170000 00000000 00004000 2D20AD2AF70917F2323F8CEFA22146320 libstagefright_yuv.so
W/google-breakpad( 5207): M E8174000 00000000 0001E000 9FD75EA01749CDE56F2A63C51648E9600 libstagefright_omx.so
W/google-breakpad( 5207): M E8192000 00000000 00007000 BE9998F628EA6A5C32345D001998B9DE0 libstagefright_avc_common.so
W/google-breakpad( 5207): M E8199000 00000000 00005000 89B5E9B7BF6412D458C721055A152C4A0 libpowermanager.so
V/WebViewChromiumFactoryProvider( 5134): Binding Chromium to main looper Looper (main, tid 1) {deeecd1}
D/QSEECOMAPI: (  451): Loaded image: APP id = 6
D/DrmWidevineDash(  451): Service_Initialize: ends! returns 0
W/google-breakpad( 5207): M E819E000 00000000 00039000 34D438FC59A243B4B79B29B3300A98C30 libopus.so
,D/QSAPPSVER(  451): qsapps_get_capabilities: Capability from secure side: 0x0
D/QSAPPSVER(  451): qsapps_get_capabilities: returns 0
,D/DrmWidevineDash(  451): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf491d000
E/DrmWidevineDash(  451): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf491d000
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,W/google-breakpad( 5207): M E81D7000 00000000 0000A000 6A10C54036040C7624C8FFA1322786330 libqservice.so,
D/DrmLibTime(  560): got the req here! ret=0
D/DrmLibTime(  560): command id, time_cmd_id = 770
D/DrmLibTime(  560): time_getutcsec starts!
D/DrmLibTime(  560): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  560): QSEE Time Listener: get_utc_seconds,
D/DrmLibTime(  560): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  560): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  560): Receive Passed == base = 13, unit = 1, operation = 2, result = 0,
D/DrmLibTime(  560): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  560): QSEE Time Listener: Retrieved Android system time: 1452261074
D/DrmLibTime(  560): time_getutcsec returns 0, sec = 1452261074; nsec = 0
,D/DrmLibTime(  560): time_getutcsec finished! 
D/DrmLibTime(  560): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  560): before calling ioctl to read the next time_cmd
W/google-breakpad( 5207): M E81E1000 00000000 00009000 491B0CC47077062396369A22534AEA900 libqdutils.so
W/google-breakpad( 5207): M E81EA000 00000000 00006000 214BA1A75864DD2F2D276469B9531D730 libmemalloc.so
E/QC-time-services(  478): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
I/LibraryLoader( 5134): Expected native library version number "",actual native library version number ""
D/DrmWidevineDash(  451): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  451): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  451): hlos api version =  9
D/DrmWidevineDash(  451): tz api version =  9
D/DrmWidevineDash(  451): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  451): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
W/google-breakpad( 5207): M E81F0000 00000000 0001A000 34501D177FD1B1914CCDB545A3C6883A0 libdrmframework.so
,W/google-breakpad( 5207): M E820A000 00000000 00167000 8AFFCF2CC5CDBDE8646329330A9654EE0 libstagefright.so
,W/google-breakpad( 5207): M E8372000 00000000 00018000 4DE76E791A449354336837B8134C57870 libmtp.so
,W/google-breakpad( 5207): M E838A000 00000000 0000C000 4166C62672C7BAB460911D9DD5DF7D630 libjhead.so,
W/google-breakpad( 5207): M E8397000 00000000 0002C000 7923B3A93CE3D3DB91F22F126DE518730 libexif.so
,I/chromium( 5134): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,W/google-breakpad( 5207): M E83C3000 00000000 00040000 93F01B725FC991D258B33ABBDFF901BC0 libmedia_jni.so
,W/google-breakpad( 5207): M EEFB3000 00000000 00011000 892DC0C8AA2DB695C92A0FD89FD616490 libandroid.so,
W/google-breakpad( 5207): M EEFC4000 00000000 00034000 684DED99CC59C3906C82B7457EDB45F00 libGLESv1_CM_adreno.so
,W/google-breakpad( 5207): M EEFF8000 00000000 00035000 D4319C304A7C55D9B6AE6B0BD39D81DE0 libgsl.so
W/google-breakpad( 5207): M EF02D000 00000000 00029000 020C64F7B71FD39A3292263F53703FED0 libEGL_adreno.so,
W/google-breakpad( 5207): M EF056000 00000000 00003000 03B0255D304C04BA1CB893EF055C0D880 libstagefright_enc_common.so
,W/google-breakpad( 5207): M EF15C000 00000000 00008000 F5D3384E9BEEEDF600C2C4D02CB7146A0 libcompiler_rt.so,
,W/google-breakpad( 5207): M EF253000 00000000 00007000 8E32AFBB1F4F95D2A7D1AE942F1CC6E70 libaudioeffect_jni.so
W/google-breakpad( 5207): M EF25A000 00000000 00004000 DDE93E59B3E4C9F7F6E9E9B6387B90710 libsoundpool.so
W/google-breakpad( 5207): M EF367000 00000000 00009000 14B88732FC4F52EFF0CBF245F13D035D0 librs_jni.so
,W/google-breakpad( 5207): M EF3A6000 00000000 00018000 D7375A6BCE9B0B26065B4D94ECEBF2570 libjavacrypto.so,
W/google-breakpad( 5207): M EF463000 00000000 00003000 1DF77085094EED6363FE1B2151F12F740 libwebviewchromium_loader.so
,I/BrowserStartupController( 5134): Initializing chromium process, singleProcess=true
W/google-breakpad( 5207): M F0643000 00000000 00003000 9CC225316387148CDC8D097664140C3F0 libqdMetaData.so
W/google-breakpad( 5207): M F0647000 00000000 00006000 88CC6FD3BA87FC7722C310758B5C92F80 gralloc.msm8916.so
W/google-breakpad( 5207): M F1D30000 00000000 00038000 C7E9D1C3D996AA238E92371AA7A93FB10 libjavacore.so
,D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
W/google-breakpad( 5207): M F1DA4000 00000000 00004000 7969E81D0F5763BFDBC09C2B6D2F08250 libadreno_utils.so
D/DrmWidevineDash(  451): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  451): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  451): OEMCrypto_OpenSession: starts! SID=0xf4ded928
D/DrmWidevineDash(  451): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
W/art     ( 5134): Attempt to remove local handle scope entry from IRT, ignoring
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  451): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  451): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  451): OEMCrypto_GetRandom: starts! randomData=0xab0533d0, dataLength=8
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  451): OEMCrypto_GetRandom: ends! returns 0
I/GoogleURLConnFactory( 5168): Using platform SSLCertificateSocketFactory
,W/google-breakpad( 5207): M F1DAF000 00000000 00003000 80B32B0876CF3F38D2FD0F46F035FEAE0 libjnigraphics.so
D/DrmWidevineDash(  451): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab02b050, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  451): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  451): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  451): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  451): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  451): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  451): OEMCrypto_GetDeviceID: starts! deviceID=0xab0141a0, idLength=0xf4b926f8
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,W/google-breakpad( 5207): M F1DB3000 00000000 00003000 900F180B6ED1813B019148541FEBC4850 memtrack.msm8916.so
,E/SysUtils( 5134): ApplicationContext is null in ApplicationStatus,
W/google-breakpad( 5207): M F1DB6000 00000000 00004000 A5D156DB5288811021E8A33ADD46575D0 libhtcflag-jni.so
W/google-breakpad( 5207): M F45D0000 00000000 00009000 77FE44517AE2BC3F7112ACC653DD56190 eglsubAndroid.so
W/google-breakpad( 5207): M F4676000 00000000 00004000 F6B8E3B47357B4905A70F8F4DCDDF95F0 libwebviewchromium_plat_support.so
W/google-breakpad( 5207): M F581D000 00000000 00009000 A33E53229717A18B8A727CBF4B7E733A0 libbacktrace_libc++.so
W/google-breakpad( 5207): M F5827000 00000000 002F3000 82D4A832811A783569FD593EBB60720E0 libart.so
,W/google-breakpad( 5207): M F5B1D000 00000000 00003000 9258F0DE2668790937DBED7BAB5D46F00 libcnefeatureconfig.so
,W/google-breakpad( 5207): M F5B20000 00000000 00006000 5E93EF8DAA762237A237CBEE445B1DE20 libvendorconn.so,
,W/google-breakpad( 5207): M F5B46000 00000000 00004000 62EFD3D29964E6B599D4FAE01272421C0 libusbhost.so
W/google-breakpad( 5207): M F5B4A000 00000000 0003F000 EF56E4832FD620AEF216122E274174FD0 libssl.so
,D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  451): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  451): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  451): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  451): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  451): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  451): OEMCrypto_GetHDCPCapability: starts!, current = 0xf4b9270e, maximum = 0xf4b9270f
,D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  451): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  451): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  451): hlos api version =  9
D/DrmWidevineDash(  451): tz api version =  9
D/DrmWidevineDash(  451): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  451): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf4b9277c
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,I/GAV2    ( 4730): Thread[GAThread,5,main]: No campaign data found.
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  451): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  451): PrepareKeyRequest: nonce=859002244
D/DrmWidevineDash(  451): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab02c360
,D/DrmWidevineDash(  451): message_length=1611, signature=0xab018e60, signature_length=0xf4b926dc,
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
W/google-breakpad( 5207): M F5B89000 00000000 0005F000 ABD0869F9BDC9324245CFD137B909CD90 libsqlite.so
,W/google-breakpad( 5207): M F5BE9000 00000000 0000E000 DD9CC624EF32ACC1510AB3DEA32715310 libsoundtrigger.so,
W/google-breakpad( 5207): M F5BF7000 00000000 0000E000 0F80235EA9BE7693F3169190DC1563370 libselinux.so
,D/libc    ( 5168): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 5168): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5168): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5168): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5168): [NET] android_getaddrinfo_proxy+
D/libc    ( 5168): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,W/google-breakpad( 5207): M F5C05000 00000000 00004000 099B10F2EAA0144B6769F0BF764BE16D0 libprocessgroup.so,
,W/google-breakpad( 5207): M F5C09000 00000000 00447000 F96B93EA164BBEFDAF535E908AE475720 libpdfium.so
W/google-breakpad( 5207): M F6055000 00000000 00004000 3E430EDD7A489F9B69658ADED8164E970 libnetd_client.so
W/google-breakpad( 5207): M F6059000 00000000 00007000 0C1B1C861068F1F5F02ED11E94A2CAC40 libnativehelper.so
W/google-breakpad( 5207): M F6060000 00000000 00004000 53D444BF55933A8A3B1A3D56428157490 libnativebridge.so
,W/google-breakpad( 5207): M F6064000 00000000 0000B000 D7C8D0DD22BFD9FA03E254E8964626260 libminikin.so
,I/GAv4-SVC( 4507): Google Analytics 7.8.99 is starting up.
W/google-breakpad( 5207): M F606F000 00000000 00003000 3A297E4800A3E2A2881399ECB557DD800 libmemtrack.so
,W/google-breakpad( 5207): M F6072000 00000000 00014000 6B1480867A607CA029CF04E44A2B514D0 libstagefright_foundation.so,
,W/google-breakpad( 5207): M F6086000 00000000 00050000 EC16351BBCFD02238537E51BAE2784340 libsonivox.so,
,W/google-breakpad( 5207): M F60DB000 00000000 0000F000 D5ED9236D25CE04149331D781E23A60C0 libcommon_time_client.so
,D/libc    (  400): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  400): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 5168): [NET] android_getaddrinfo_proxy-, success
W/google-breakpad( 5207): M F60EA000 00000000 0000A000 E237A3F236BE2D39A2B89F3233C80EB10 libnbaio.so
W/google-breakpad( 5207): M F60F4000 00000000 000A1000 75483B3506E0577F787A0DEE014DF8AD0 libmedia.so
,W/google-breakpad( 5207): M F6195000 00000000 0003C000 A5AB1250C666FD4D95BDF1EC4CE30D0F0 libinputflinger.so,
W/google-breakpad( 5207): M F61D1000 00000000 0001B000 26C21B27B18AD33097855FE55272007A0 libinput.so
,W/google-breakpad( 5207): M F61EC000 00000000 0000E000 F53A4FC8B77980603D72451B64F3D6110 libimg_utils.so
,W/google-breakpad( 5207): M F61FA000 00000000 00031000 5E853F759F0F20B2C46E95661CD23ABF0 libjpeg.so
W/google-breakpad( 5207): M F622B000 00000000 00211000 9BB817457BD5B9D902795CCECA27F9420 libskia.so
W/google-breakpad( 5207): M F6441000 00000000 0001D000 DA74BA5F3169A4A897CCA717B354B7920 libRScpp.so
W/google-breakpad( 5207): M F645E000 00000000 00027000 DEA73078522E3E6820C3C1312B8CEB540 libpng.so
,W/google-breakpad( 5207): M F6487000 00000000 00059000 54828C4F4B56D81127BD1BAF9A48D64E0 libft2.so
W/google-breakpad( 5207): M F64E0000 00000000 0003D000 D79BF10EF6E7C872980F16B4E7CA364A0 libbcinfo.so
W/google-breakpad( 5207): M F651D000 00000000 00024000 D7B64EAA04E4820A363599A27C92DD9E0 libbcc.so
W/google-breakpad( 5207): M F6561000 00000000 0008C000 87F163D71143D1661656594288E8FF3D0 libc++.so
W/google-breakpad( 5207): M F65EF000 00000000 008FE000 AF5D7FB9B3957FF38E5A0110952B99830 libLLVM.so
W/google-breakpad( 5207): M F6EF4000 00000000 00038000 9ACCAD335631F6C0BFEAFF4000026F0B0 libRS.so
W/google-breakpad( 5207): M F6F2C000 00000000 0004D000 E7BF8968C06F02F40CCB572D8FE2046E0 libhwui.so
W/google-breakpad( 5207): M F6F79000 00000000 00004000 B10F6B2DE42715DA716F1D0B3B5635A00 libhtc_framework.so
W/google-breakpad( 5207): M F6F7D000 00000000 000FF000 24D405D2C9B637FC33CF5029217299690 libicuuc.so
,W/google-breakpad( 5207): M F7080000 00000000 00006000 6AC3328D55BE7167DD1549E59E88D8420 libgabi++.so
,W/google-breakpad( 5207): M F7086000 00000000 0014A000 30D014A51C507F017588CD57CC7ABDAD0 libicui18n.so
,W/google-breakpad( 5207): M F71D0000 00000000 00064000 0A4C86F854CC1FC957A2604EB3703BB50 libharfbuzz_ng.so
,W/google-breakpad( 5207): M F7234000 00000000 00005000 83C65B431178639D25C0512E4FDA55CD0 libwpa_client.so
,W/google-breakpad( 5207): M F7239000 00000000 00007000 34BC97F86C64F306A8DF4132F83E6EAC0 libnetutils.so
,W/google-breakpad( 5207): M F7240000 00000000 00009000 E83FD2A7213BE1E60419E008C10BA60A0 libhostapd_client.so
,W/google-breakpad( 5207): M F7249000 00000000 0000A000 7A91BF90203362DD9AAD39F6E797932C0 libhardware_legacy.so,
W/google-breakpad( 5207): M F7254000 00000000 00017000 D1B32BE53493EE80553E5CF9729A5E320 libexpat.so
W/google-breakpad( 5207): M F726B000 00000000 000F6000 32536031C4AB5FAF2AF54C974CA69C730 libcrypto.so
W/google-breakpad( 5207): M F7363000 00000000 00003000 4D02055D5873A4955D03859291CA4C3B0 libhardware.so
W/google-breakpad( 5207): M F7366000 00000000 0000C000 66710B9BAE0ABBFA03CE722F9D13CC280 libui.so
W/google-breakpad( 5207): M F7372000 00000000 00003000 7C24A254F6B1768D1FF8ADFB9A8A11500 libsync.so
W/google-breakpad( 5207): M F7375000 00000000 00053000 DC5E85D678571850531E4D07BA830AD20 libgui.so
W/google-breakpad( 5207): M F73C8000 00000000 00008000 D8696F2D0F90725A85A007DFA22762E60 libcamera_metadata.so
W/chromium( 5134): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
W/google-breakpad( 5207): M F73D0000 00000000 00043000 6BDE8BFBD026F9A66A917BECDD3584E20 libcamera_client.so
W/google-breakpad( 5207): M F7413000 00000000 00006000 20E951BEE083EAAC8A0EC8C9659BC90C0 libspeexresampler.so
W/google-breakpad( 5207): M F7419000 00000000 00006000 CEDFF00912202B3BE66FA6091F5033210 libaudioutils.so
W/google-breakpad( 5207): M F741F000 00000000 00018000 F5FE4EF4E136FE6B8489E4B9D841950E0 libz.so
W/google-breakpad( 5207): M F7437000 00000000 0002E000 C420991A642D33C062B69EF0817BC3040 libbinder.so
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  451): OEMCrypto_GenerateRSASignature returns 0,
I/WVCdm   (  451): CdmEngine::CloseSession
D/DrmWidevineDash(  451): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  451): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  451): L3 Terminate.
D/DrmWidevineDash(  451): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  451): Service_Uninitialize: starts!
D/QSEECOMAPI: (  451): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  451): QSEECom_shutdown_app, app_id = 6
D/DrmWidevineDash(  451): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  451): OEMCrypto_Terminate: ends! returns 0
W/google-breakpad( 5207): M F7465000 00000000 00028000 CE3A8D8301FC6F030CE534873D98D1FA0 libandroidfw.so
W/google-breakpad( 5207): M F748D000 00000000 0000B000 E2F67EE50006FD0ED1482E1463C5CCFF0 libGLESv2.so
,W/google-breakpad( 5207): M F7498000 00000000 00007000 EFE6ADDAF48E0BCED48FF0E60558C2F60 libGLESv1_CM.so
,W/google-breakpad( 5207): M F749F000 00000000 00004000 C10A3FF24BC314BDB4276E3588B5CFEF0 libETC1.so
,W/google-breakpad( 5207): M F74A3000 00000000 00004000 9A82E5E5DC0FF6464E020C95D6C265430 libunwind-ptrace.so
W/google-breakpad( 5207): M F74A7000 00000000 0000E000 FCC4CF7B44EE2AEE89CCE84DDB0A34E30 libunwind.so
W/google-breakpad( 5207): M F74FB000 00000000 00007000 9AD603917CEBD0A26C5300A4455555250 libgccdemangle.so
W/google-breakpad( 5207): M F7503000 00000000 00008000 B1D0D9E481294ED9CC235497923180870 libbacktrace.so
W/google-breakpad( 5207): M F750D000 00000000 0001B000 9D5E00077F110562E43B9D57D21F59AD0 libutils.so
W/google-breakpad( 5207): M F7528000 00000000 00036000 A86B4524AFE0B8B31C00A4A9DA14FB720 libstlport.so
E/libEGL  ( 5134): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5134): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5134): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 5134): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 5134): Build Date: 03/09/15 Mon
I/Adreno-EGL( 5134): Local Branch: 
I/Adreno-EGL( 5134): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 5134): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 5134):                  d74aa161a12b9c6fc6332151
,W/google-breakpad( 5207): M F755F000 00000000 0006D000 07CC805CFD246906AD1D1909740021BF0 libGLES_trace.so
,W/google-breakpad( 5207): M F75CC000 00000000 00072000 7F0004D0AF4E874B42135FA0E63B146F0 libEGL.so
,W/google-breakpad( 5207): M F7641000 00000000 000E2000 4932864EF33D43B3A705E7CF5CF0CB410 libandroid_runtime.so
,W/google-breakpad( 5207): M F7724000 00000000 0000E000 FB49BAE8D805F1585732970603ADF24D0 libcutils.so
W/google-breakpad( 5207): M F7732000 00000000 00004000 D1AC53E65CCF0819F62D0CBCB34992B60 libNimsWrap.so
W/google-breakpad( 5207): M F7736000 00000000 00004000 D44FDF94BA8D734E5BC46C426F7316DE0 libstdc++.so
,W/google-breakpad( 5207): M F773A000 00000000 00018000 3D2BCD0A8F5E726801091CC87EA86DCC0 libm.so
W/google-breakpad( 5207): M F7753000 00000000 00007000 BB5314B7B66F66866701A1CF846A36450 liblog.so
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  953):  packet count Tx=111 Rx=156
,W/google-breakpad( 5207): M F775B000 00000000 00057000 E8305BB9B317B77A60EAFD0AEE1CB7E30 libc.so
,W/google-breakpad( 5207): M F77BC000 00000000 00003000 6942576880529816BD6C80C55563D51C0 libsigchain.so
W/google-breakpad( 5207): M F77C3000 00000000 0000F000 55FA1B3647FDFF2D5215BEC36C50EA7C0 linker
W/google-breakpad( 5207): -----END BREAKPAD MICRODUMP-----
,D/libc    ( 5168): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
D/libc    ( 5168): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5168): [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
D/libc    ( 5168): [NET] android_getaddrinfofornet-, err=8
,W/google-breakpad( 5020): ### ### ### ### ### ### ### ### ### ### ### ### ###,
W/google-breakpad( 5020): Chrome build fingerprint:
W/google-breakpad( 5020): 0.0.1
W/google-breakpad( 5020): 18
W/google-breakpad( 5020): 0ac25ff3-fa94-4ee3-b183-8999384c3b93
W/google-breakpad( 5020): ### ### ### ### ### ### ### ### ### ### ### ### ###
E/chromium( 5020): ### WebView Version 44.0.2403.117 (code 240311750)
,F/libc    ( 5020): Fatal signal 11 (SIGSEGV), code 1, fault addr 0x0 in tid 5195 (Thread-131)
W/libc    ( 5020): Security Level: (1), Debug inforamtion is controlled by the DUMPABLE flag.
,I/SocialFeedProvider( 1604): +disConnect socialManager
I/SocialFeedProvider( 1604): disconnect socialManager
,I/SocialFeedProvider( 1604): -disConnect socialManager
,W/AudioManagerAndroid( 5134): Requires BLUETOOTH permission
,I/NSApplication( 5134): Starting up...,
,I/DEBUG   (  441): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
,I/DEBUG   (  441): Build fingerprint: 'htc/m8qlul_htc_europe/htc_m8qlul:5.0.2/LRX22G/531284.2:user/release-keys'
I/DEBUG   (  441): Revision: '0',
I/DEBUG   (  441): ABI: 'arm'
I/DEBUG   (  441): pid: 5020, tid: 5195, name: Thread-131  >>> com.example.hello <<<
,I/DEBUG   (  441): signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
,I/DEBUG   (  441):     r0 00000000  r1 00000000  r2 00000000  r3 00000000
I/DEBUG   (  441):     r4 d7a07e38  r5 d7a07df8  r6 acb5f448  r7 d7a07df8
I/DEBUG   (  441):     r8 00000000  r9 d7a07e34  sl d7a09390  fp d7a07ddc
I/DEBUG   (  441):     ip d84ddba0  sp d7a07dc0  lr d81e4308  pc f776b68c  cpsr 600d0030
I/DEBUG   (  441): 
I/DEBUG   (  441): backtrace:
I/DEBUG   (  441):     #00 pc 0001068c  /system/lib/libc.so (strlen+83)
I/DEBUG   (  441):     #01 pc 007da304  /data/app/com.example.hello-1/lib/arm/libjxcore.so (MozJS::String::FromUTF8(JSContext*, char const*, int)+40)
,I/ActivityManager(  953): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=5238 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a,
I/ActivityManager(  953): Killing 4347:com.android.settings/1000 (adj 15): empty #17
D/Process (  953): killProcessQuiet, pid=4347
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/art     ( 1986): Explicit concurrent mark sweep GC freed 11397(610KB) AllocSpace objects, 8(672KB) LOS objects, 49% free, 4MB/8MB, paused 777us total 46.879ms,
,I/ActivityManager(  953): Recipient 4347
,I/ActivityManager(  953): Start proc com.htc.sense.news for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper: pid=5259 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a
V/AlarmManager(  953): sending alarm PendingIntent{129250ca: PendingIntentRecord{326223b com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1452261074984, Int=0,
,I/ActivityManager(  953): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=5282 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
D/Process (  953): killProcessQuiet, pid=4481
I/ActivityManager(  953): Killing 4481:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/WVCdm   (  451): CdmEngine::OpenSession
I/WVCdm   (  451): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  451): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  451): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
,D/DrmWidevineDash(  451): Service_Initialize: starts!
D/QSEECOMAPI: (  451): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  451): App is not loaded in QSEE
E/QSEECOMAPI: (  451): Error::Cannot open the file /vendor/firmware/widevine.mdt,
E/QSEECOMAPI: (  451): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  451): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  451): App is not loaded in QSEE
,D/QSEECOMAPI: (  451): Loaded image: APP id = 7,
D/DrmWidevineDash(  451): Service_Initialize: ends! returns 0
,D/QSAPPSVER(  451): qsapps_get_capabilities: Capability from secure side: 0x0,
D/QSAPPSVER(  451): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  451): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf491d000
E/DrmWidevineDash(  451): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf491d000
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/DrmLibTime(  560): got the req here! ret=0,
D/DrmLibTime(  560): command id, time_cmd_id = 770
D/DrmLibTime(  560): time_getutcsec starts!
D/DrmLibTime(  560): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  560): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  560): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  560): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  560): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  560): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  560): QSEE Time Listener: Retrieved Android system time: 1452261075
D/DrmLibTime(  560): time_getutcsec returns 0, sec = 1452261075; nsec = 0
,D/DrmLibTime(  560): time_getutcsec finished! 
D/DrmLibTime(  560): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  560): before calling ioctl to read the next time_cmd
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
E/QC-time-services(  478): Daemon: Time-services: Waiting to acceptconnection
,D/DrmWidevineDash(  451): OEMCrypto_Initialize: ends! returns 0,
D/DrmWidevineDash(  451): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  451): hlos api version =  9
D/DrmWidevineDash(  451): tz api version =  9
D/DrmWidevineDash(  451): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  451): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  451): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  451): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  451): OEMCrypto_OpenSession: starts! SID=0xf4b92928
D/DrmWidevineDash(  451): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  451): OEMCrypto_OpenSession SID = 1,
D/DrmWidevineDash(  451): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  451): OEMCrypto_GetRandom: starts! randomData=0xab0151e0, dataLength=8
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  451): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  451): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab02b050, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  451): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  451): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  451): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  451): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  451): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  451): OEMCrypto_GetDeviceID: starts! deviceID=0xab0141e0, idLength=0xf4b926f8
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  451): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  451): OEMCrypto_SupportsUsageTable: starts!
,D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  451): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  451): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  451): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  451): OEMCrypto_GetHDCPCapability: starts!, current = 0xf4b9270e, maximum = 0xf4b9270f
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  451): OEMCrypto_GetHDCPCapability: ends! returns 0
,D/DrmWidevineDash(  451): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  451): hlos api version =  9
D/DrmWidevineDash(  451): tz api version =  9
D/DrmWidevineDash(  451): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  451): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf4b9277c
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  451): OEMCrypto_GenerateNonce: ends! returns 0
,D/WVCdm   (  451): PrepareKeyRequest: nonce=1101095919
D/DrmWidevineDash(  451): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab029328
D/DrmWidevineDash(  451): message_length=1646, signature=0xab0543f0, signature_length=0xf4b926dc
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,E/WifiStateMachine(  953): handleMessage: E msg.what=131155,
E/WifiStateMachine(  953): processMsg: ConnectedState
E/WifiStateMachine(  953):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=30.8, 0.0, 0.0  rx=35.6 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:562129169] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  953): processMsg: L2ConnectedState
,E/WifiStateMachine(  953):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=30.8, 0.0, 0.0  rx=35.6 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:562129170] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  953):  get link layer stats 0
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SIGNAL_POLL'
,I/ActivityManager(  953): Recipient 4481,
,I/wpa_supplicant( 1330): environment dirty rate=12 [32][4][0],
E/WifiStateMachine(  953): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  953): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  953): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
E/WifiStateMachine(  953): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=30.91 txretriesrate=0.00 rxrate=38.78 userTriggerdPenalty0
E/WifiStateMachine(  953):  good link -> stuck count =0
E/WifiStateMachine(  953):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  953):  isHighRSSI       ---> score=65
,D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  451): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  451): CdmEngine::CloseSession
D/DrmWidevineDash(  451): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  451): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  451): L3 Terminate.
D/DrmWidevineDash(  451): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0,
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  451): Service_Uninitialize: starts!
D/QSEECOMAPI: (  451): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  451): QSEECom_shutdown_app, app_id = 7
D/DrmWidevineDash(  451): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  451): OEMCrypto_Terminate: ends! returns 0
,E/WifiStateMachine(  953): handleMessage: X
D/WifiWatchdogStateMachine(  953): RSSI current: 3 new: -60, 3
E/ActivityManager(  953): App crashed! Process: com.example.hello
D/WIFI_ICON( 1232): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1232): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/BootReceiver(  953): Copying /data/tombstones/tombstone_05 to DropBox (SYSTEM_TOMBSTONE)
E/SharedPreferencesImpl(  953): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,W/ActivityManager(  953):   Force finishing activity com.example.hello/.MainActivity
,W/ResourcesManager( 5282): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ImageRamCache( 5259): create image Cache, size: 31457280.
,I/ImageRamCache( 5259): [resize] ImageRamCache resized to: 30Mb.
I/ImageRamCache( 5259): create image Cache, size: 31457280.
,W/art     ( 5168): Suspending all threads took: 13.642ms
,I/FeedSettings( 5259): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 5259): GroupBudget 0.500000 0.380000
I/FeedSettings( 5259): GroupBudget 60 45 15
I/art     ( 5168): Background sticky concurrent mark sweep GC freed 18(528B) AllocSpace objects, 0(0B) LOS objects, 1% free, 4MB/4MB, paused 16.327ms total 26.041ms
E/JavaBinder(  953): !!! FAILED BINDER TRANSACTION !!!
,I/Prism.ExternalStringMa_( 5259): changeLocale(): en_GB
,W/ActivityManager(  953): Exception thrown during pause
W/ActivityManager(  953): android.os.TransactionTooLargeException
W/ActivityManager(  953): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  953): 	at android.os.BinderProxy.transact(Binder.java:504)
W/ActivityManager(  953): 	at android.app.ApplicationThreadProxy.schedulePauseActivity(ApplicationThreadNative.java:718)
W/ActivityManager(  953): 	at com.android.server.am.ActivityStack.startPausingLocked(ActivityStack.java:882)
W/ActivityManager(  953): 	at com.android.server.am.ActivityStack.finishActivityLocked(ActivityStack.java:2953)
W/ActivityManager(  953): 	at com.android.server.am.ActivityStack.finishTopRunningActivityLocked(ActivityStack.java:2808)
W/ActivityManager(  953): 	at com.android.server.am.ActivityStackSupervisor.finishTopRunningActivityLocked(ActivityStackSupervisor.java:2560)
W/ActivityManager(  953): 	at com.android.server.am.ActivityManagerService.handleAppCrashLocked(ActivityManagerService.java:12140)
W/ActivityManager(  953): 	at com.android.server.am.ActivityManagerService.makeAppCrashingLocked(ActivityManagerService.java:12032)
W/ActivityManager(  953): 	at com.android.server.am.ActivityManagerService.crashApplication(ActivityManagerService.java:12740)
W/ActivityManager(  953): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12246)
W/ActivityManager(  953): 	at com.android.server.am.NativeCrashListener$NativeCrashReporter.run(NativeCrashListener.java:86)
,D/PMS     (  953): acquireWL(2e6d9eb1): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 953 1000 null
,E/lowmemorykiller(  382): Error writing /proc/5020/oom_score_adj; errno=22,
,I/Prism.AllAppsOptionsMa_( 5259): loadSortType() with Custom
I/Prism.AllAppsOptionsMa_( 5259): loadGridSize() with Alternative
,I/ActivityManager(  953): Recipient 5020
I/WindowState(  953): WIN DEATH: Window{2c97abfe u0 com.example.hello/com.example.hello.MainActivity}
E/InputEventReceiver( 1419): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{1c84f529 uid 10374 pid 5020} (c)'
I/art     ( 5168): Background sticky concurrent mark sweep GC freed 79(4KB) AllocSpace objects, 0(0B) LOS objects, 0% free, 4MB/4MB, paused 10.830ms total 17.635ms
,D/StatusBarManagerService(  953): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  953): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  953): hiding MENU key
,E/cutils-trace( 5314): Error opening trace file: Permission denied (13)
I/dex2oat ( 5314): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=41 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 5314): dex2oat: override thread count:4
,E/WifiDataStallTracker(  953): DATA_MONITOR_POLL true Token 1
I/ActivityManager(  953): Process com.example.hello (pid 5020) has died
,D/WifiDataStallTracker(  953): updateDataStallInfo: mDataStallTxRxSum={txSum=111 rxSum=120} preTxRxSum={txSum=33 rxSum=26}
D/WifiDataStallTracker(  953): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  953): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
W/HtcSystemUPManager(  953): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,I/FeedHostManager( 1604): [onResume],
I/FeedProviderManager( 1604): onResume
I/SocialFeedProvider( 1604): +onResume
I/SocialFeedProvider( 1604): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1604): -onResume
,D/FindExtension( 1604): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/ThreadedRenderer( 1604): Defer allocateBuffers to drawing time
,I/SocialManager[SocialBiLogHelper]( 5259): action: com.htc.sense.hsp.HANDLE_ULOG,
I/SocialManager[SocialBiLogHelper]( 5259): last commit ulog time 1452231782962
I/SocialManager[SocialBiLogHelper]( 5259): skip commit this time
,D/Process (  953): killProcessQuiet, pid=4444
I/ActivityManager(  953): Killing 4444:com.android.vending/u0a72 (adj 15): empty #17
,D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/dex2oat ( 5314): dex2oat took 60.627ms (threads: 4)
,D/StatusBarManagerService(  953): setSystemUiVisibility(0xc0000000)
D/StatusBarManagerService(  953): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  953): hiding MENU key
,I/Adreno-EGL( 5168): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 5168): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 5168): Build Date: 03/09/15 Mon
I/Adreno-EGL( 5168): Local Branch: 
I/Adreno-EGL( 5168): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 5168): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 5168):                  d74aa161a12b9c6fc6332151,
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  953):  packet count Tx=129 Rx=186
,I/Adreno-EGL( 5168): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 5168): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 5168): Build Date: 03/09/15 Mon
I/Adreno-EGL( 5168): Local Branch: 
I/Adreno-EGL( 5168): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 5168): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 5168):                  d74aa161a12b9c6fc6332151
,I/ActivityManager(  953): Recipient 4444,
,D/PMS     (  953): releaseWL(2e6d9eb1): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,I/CheckinRequestBuilder( 4507): Classify the device as Phone.
,D/libc    ( 4507): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4507): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4507): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 4507): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4507): [NET] android_getaddrinfo_proxy+
D/libc    ( 4507): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,W/OpenGLRenderer( 1604): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...,
,D/Process (  953): killProcessQuiet, pid=3636
,I/ActivityManager(  953): Killing 3636:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,D/libc    (  400): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  400): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4507): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 4507): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4507): [NET] android_getaddrinfofornet-, err=8
,I/ActivityManager(  953): Recipient 3636,
,I/ActivityManager(  953): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=5336 uid=10035 gids={50035, 9997} abi=arm64-v8a
,D/libc    ( 4507): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,D/libc    ( 4507): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 4507): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,D/libc    ( 4507): [NET] android_getaddrinfofornet-, err=8
,I/CheckinTask( 4507): Sending checkin request (8434 bytes)
,I/ActivityManager(  953): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=5358 uid=10076 gids={50076, 9997} abi=arm64-v8a
D/Process (  953): killProcessQuiet, pid=3967
I/ActivityManager(  953): Killing 3967:com.htc.sense.mms/u0a64 (adj 15): empty #17,
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/PackageManager(  953):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService, state=2, flag=1, pid=4507, uid=10024, userID:0,
I/PackageManager(  953):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateActivity, state=2, flag=1, pid=4507, uid=10024, userID:0
I/PackageManager(  953):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver, state=2, flag=1, pid=4507, uid=10024, userID:0
I/PackageManager(  953):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$Receiver, state=2, flag=1, pid=4507, uid=10024, userID:0
,I/ActivityManager(  953): Recipient 3967
,D/PMS     (  953): acquireWL(3d450985): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 953 1000 null
I/BatteryService(  953): n_update end
,D/PMS     (  953): releaseWL(3d450985): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
,D/Process (  953): killProcessQuiet, pid=4645,
I/ActivityManager(  953): Killing 4645:com.google.android.youtube/u0a176 (adj 15): empty #17
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  953): Recipient 4645
,D/DotMatrix( 1342): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/PowerUI ( 1232): closing low battery warning: level=100
D/HeadsetStateMachine( 3115): Disconnected process message: 10, size: 0
D/PowerUI ( 1232): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1232): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  953): updateBatteryInfo
D/DotMatrix( 1342): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1342): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/SMSBackup( 5358): Got a database change event
W/SystemReader(  953): Cannot find grip_rejection_width, use default value instead
,D/AccTypeManager( 1757): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,D/NotificationService(  953): plugged=true pluggin=true
D/UsbnetService(  953): BroadcastReceiver::onReceive+
D/UsbnetService(  953): onReceive BATTERY_CHANGED
D/UsbnetService(  953):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  953): BroadcastReceiver::onReceive-
D/WifiController(  953): handleMessage: E msg.what=155652
D/WifiController(  953): battery changed pluggedType: 2
D/WifiController(  953): processMsg: DeviceActiveState
D/WifiController(  953): processMsg: StaEnabledState
D/WifiController(  953): processMsg: DefaultState
D/WifiController(  953): handleMessage: X
,W/ResourcesManager( 1556): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
I/BatteryController( 1232): status:5 level:100 unsupport:false plugged:true
D/AccTypeManager( 1757): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/CheckinRequestBuilder( 4507): Checkin reason type: 8 attempt count: 1
,D/CustomHighlightReceiver( 5259): [custom highlight] onReceive
I/ActivityManager(  953): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4507): Failed to find provider info for com.google.android.wearable.settings
W/Prism.AllAppsManager( 1604): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/Prism.ItemManager( 1604): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1604): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,D/CustomHighlightService( 5259): [custom highlight] onHandleIntent
,D/NewsDB  ( 5259): set custom highlight [],
W/ResourcesManager(  953): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/Prism.ItemManager( 5259): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Prism.ItemManager( 5259): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/AccTypeManager( 1757): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/ActivityManager(  953): Start proc com.htc.sense.mms for broadcast com.htc.sense.mms/.ui.MessagingShortcutReceiver: pid=5383 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,D/PhoneApp( 1556): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,E/ExternalAccountType( 1757): Unsupported attribute readOnly
,D/CustomHighlightService( 5259): [custom highlight] set tags ,
,I/ActivityManager(  953): Killing 4730:com.google.android.gm/u0a106 (adj 15): empty #17
D/Process (  953): killProcessQuiet, pid=4730
,D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
,W/HtcWrapAdjustableCursorFactory( 5383): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.,
,D/MessageFrequencyProvider( 5383): onCreate
,W/PackageManager(  953): Unable to load service info ResolveInfo{2d08451d com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
W/PackageManager(  953): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  953): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  953): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  953): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  953): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  953): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  953): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  953): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  953): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  953): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  953): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  953): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  953): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  953): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  953): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  953): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/BackupManagerService(  953): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService},
,I/ActivityManager(  953): Recipient 4730
,V/GetPrviateResource( 5383): GetPrviateResource,
V/GetPrviateResource( 5383): GetPrviateResource
,D/PMS     (  953): runPSCheck,
D/HtcPowerSaver(  953): Checking...
,I/HtcPowerSaver(  953): >> updateStatus
,I/HtcPowerSaver(  953): updateStatus (8000,100,-1,false,false,false,-1)
E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7
I/HtcPowerSaver(  953): << updateStatus
E/WifiTrafficPoller(  953):  packet count Tx=155 Rx=206
,D/MessageCustFlag( 5383): sense_version=6.0
,D/BTAccessoryUtil( 5383): createReceiver
,D/BTAccessoryUtil( 5383): registerReceiver return intent = null
,D/MessageCustFlag( 5383): sku_id=118
,D/HtcBuildUtils( 5383): getRATByHtcTelephonyCapability:1
W/SystemReader( 5383): Cannot find qct_8960_interface, use default value instead
,I/HtcModeClient( 3238): handler message = 4011
,E/HtcModeClient( 3238): Check connection and retry 5 times.
,D/MmsConfig( 5383): packageName: com.htc.vvm.att does not exist
D/MessageCustFlag( 5383): sku_id=118
,D/MessagingShortcutReceiver( 5383): keep hiding shortcut bubble
,D/MessagingShortcut( 5383): updateMsgShortcut, msg count> -1,
D/SettingsManager( 5383): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@18a2e2e4
,D/MessagingShortcut( 5383): After query: 0
D/MessagingShortcut( 5383): mPresentUnreadCount: -1
,D/MessageUtils( 5383): [getShortcut] com.htc.sense.mms.ui.ConversationList, false,
D/MessagingShortcut( 5383): setMsgShortcutDrawable> 0, false
,I/art     (  953): Explicit concurrent mark sweep GC freed 27733(1555KB) AllocSpace objects, 10(1048KB) LOS objects, 33% free, 18MB/28MB, paused 1.731ms total 157.930ms
,D/MessagingShortcut( 5383): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
,D/DotMatrix( 1342): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/GCoreNlp( 1842): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/DotMatrix( 1342): [EventService] reorderNotification, total:0
D/DotMatrix( 1342): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1342): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/ActivityManager(  953): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=5409 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager(  953): Killing 4805:com.google.android.partnersetup/u0a27 (adj 15): empty #17
,D/Process (  953): killProcessQuiet, pid=4805
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  953): Recipient 4805
,W/ResourcesManager( 5409): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/PMS     (  953): acquireWL(26eba481): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1842 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): releaseWL(26eba481): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/LocationProviderProxy(  953): applying state to connected service
,D/LocationProviderProxy(  953): applying state to connected service
,V/GmsNetworkLocationProvi( 1842): DISABLE
,D/PMS     (  953): acquireWL(b6b3314): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1842 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  953): acquireWL(1bad07bd): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1842 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): releaseWL(1bad07bd): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): releaseWL(b6b3314): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  953): acquireWL(3a3611b2): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1842 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): releaseWL(3a3611b2): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/TodoTaskshortcut( 5409): update TASK shortcut>,
,I/GLSUser ( 1986): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer,
I/GLSUser ( 1986): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1986): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1986): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1986): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  953): acquireWL(2878de5f): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 5409 10069 null
,D/Process (  953): killProcessQuiet, pid=4772
,I/ActivityManager(  953): Killing 4772:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/PMS     (  953): acquireWL(2bb1d0ac): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 5409 10069 null
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  953): Recipient 4772,
D/WifiService(  953): Client connection lost with reason: 4
,D/PMS     (  953): releaseWL(2878de5f): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,E/TodoTaskNotifyService( 5409): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference,
W/System.err( 5409): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference,
W/System.err( 5409): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
D/PMS     (  953): releaseWL(2bb1d0ac): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
W/System.err( 5409): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 5409): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5409): 	at android.os.Looper.loop(Looper.java:155)
W/System.err( 5409): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 5409): stopSelfResult true
,D/PMS     (  953): acquireWL(19e5aff1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1986 10024 WorkSource{10024 com.google.android.gms}
,D/MtpReceiver( 3893): [MTP][handleUsbStateAsync]+
D/MtpReceiver( 3893): [MTP][handleUsbStateAsync]1:1-
D/MtpReceiver( 3893): [MTP][handleUsbState]+
,I/ActivityManager(  953): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=5434 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a,
,D/MtpReceiver( 3893): [MTP][scanExternalVolumeIfNeed] scan external volume
D/MtpReceiver( 3893): [MTP][handleUsbState]-
D/MtpReceiver( 3893): [MTP][handleMessage]-
,D/MtpService( 3893): updating state; isCurrentUser=true, mMtpLocked=false
,D/PMS     (  953): acquireWL(c4b8944): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 4507 10024 null
D/MtpDatabase( 3893): TotalSize=1886532,MediaCacheLimit=6000
D/PMS     (  953): releaseWL(19e5aff1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/MtpService( 3893): [isMtpConnected] connected: true
,I/art     (  458): Explicit concurrent mark sweep GC freed 8644(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 246us total 37.805ms
,I/art     (  458): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 195us total 28.644ms
,W/CheckinRequestBuilder( 4507): awaiting user notification for token
,I/RemoteViews( 1232): reapply : com.google.android.gms 3 40
I/art     (  458): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 182us total 20.066ms
,D/DotMatrix( 1342): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1342): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/CheckinRequestBuilder( 4507): Classify the device as Phone.,
,I/iu.UploadsManager( 4507): End new media; added: 0, uploading: 0, time: 82 ms,
D/PMS     (  953): releaseWL(c4b8944): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 null
,I/CheckinTask( 4507): Checkin success: https://android.clients.google.com/checkin (1 requests sent),
,I/CheckinService( 4507): Checking schedule, now: 1452261077854 next: 1452797909847,
I/CheckinService( 4507): active receiver: disabled
,E/MediaScannerService( 3893): [onStartCommand] --- Should not be here, redirect request. ----,
I/PackageManager(  953):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4507, uid=10024, userID:0
E/MediaScannerService( 3893): [handleMessage] --- Should not be here, ignore request. ----
,D/PMS     (  953): releaseWL(b954a75): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms},
,D/SyncApplication( 5434): Loading default preferences,
,W/Resources( 5434): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,E/WifiTrafficPoller(  953): ADD_CLIENT: 7,
D/WifiService(  953): New client listening to asynchronous messages
,D/SyncApplication( 5434): Overriding preferences with custom values
,D/SyncApplication( 5434): Updating preferences succeeded
,E/SyncApplication( 5434): Application created.,
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  953):  packet count Tx=157 Rx=210
,I/CalendarDefines( 5434): getNewCalendarAuthority()...,
,I/PackageManager(  953):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=5434, uid=10005, userID:0,
D/SyncApplication( 5434): enableAppOperation()+
W/PackageManager(  953): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  953):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=5434, uid=10005, userID:0
,W/VolumeInfo( 5434): Unable to read mount points
W/VolumeInfo( 5434): java.io.FileNotFoundException: /etc/vold.fstab: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 5434): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/VolumeInfo( 5434): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/VolumeInfo( 5434): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/VolumeInfo( 5434): 	at java.io.FileReader.<init>(FileReader.java:66)
W/VolumeInfo( 5434): 	at com.nero.android.common.VolumeInfo.getVolumeMountPoints(VolumeInfo.java:194)
W/VolumeInfo( 5434): 	at com.nero.android.common.VolumeInfo.getVolumes(VolumeInfo.java:153)
W/VolumeInfo( 5434): 	at com.nero.android.common.VolumeInfo.initializeVolumeIDs(VolumeInfo.java:474)
W/VolumeInfo( 5434): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:51)
W/VolumeInfo( 5434): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:1)
W/VolumeInfo( 5434): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/VolumeInfo( 5434): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/VolumeInfo( 5434): 	,at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/VolumeInfo( 5434): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/VolumeInfo( 5434): 	at java.lang.Thread.run(Thread.java:818)
W/VolumeInfo( 5434): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 5434): 	at libcore.io.Posix.open(Native Method)
W/VolumeInfo( 5434): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/VolumeInfo( 5434): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/VolumeInfo( 5434): 	... 13 more
W/PackageManager(  953): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
V/VolumeInfo( 5434): Found 0 mount point(s)
,V/VolumeInfo( 5434): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
D/SyncApplication( 5434): enableAppOperation()-
,D/HTCUtilities( 5434): isNeorSinged() + 
,D/VolumeInfo( 5434): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,D/HTCUtilities( 5434): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,E/MediaScannerServiceEx( 3893): [getStorageMaskIdFromPath] path is null
,D/MediaScannerServiceEx( 3893): [ServiceHandler][handleMessage] , action: null, Id: 0, path: /storage/emulated/0
D/VolumeInfo( 5434): Read the volume-id from the sd card: {9B5E872B-8520-47C6-8BD3-3081C2E38355}
D/HTCUtilities( 5434): isNeorSinged() return false
W/VolumeInfo( 5434): Can not create volume ID for unmounted volume null
,D/MediaScannerServiceEx( 3893): [handleExternalVolume] ext storage
D/CDMountReceiver( 5434): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
D/CDMountReceiver( 5434): USB connected to PC,
D/MediaProviderUtils( 3893): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3893): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3893): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3893): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
D/MediaScannerServiceEx( 3893): [AliveExtStorageRows]+65537, 11223344,
,D/MediaProvider( 3893): [update][6]#0#
,D/MediaProvider( 3893): [update][2]#0#
,D/MediaProvider( 3893): [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
D/MtpService( 3893): [sendStorageAdded] Already send to MTP: /storage/emulated/0
,D/MediaProvider( 3893): [update][20]#1#,
D/MediaScannerServiceEx( 3893): [AliveExtStorageRows]-0, 0
,D/PMS     (  953): acquireWL(25adbbae): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3893 10017 null
,D/FOTAReceiver( 5434): onReceive() enter 
D/FOTAReceiver( 5434): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/MediaScanner( 3893): =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
,I/ActivityManager(  953): Start proc com.android.settings for broadcast com.android.settings/.NSReceiver: pid=5468 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
I/ActivityManager(  953): Killing 4848:com.htc.club/u0a181 (adj 15): empty #17
D/Process (  953): killProcessQuiet, pid=4848
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  953): Recipient 4848,
,I/Prism.ItemManager( 1604): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
I/Prism.ItemManager( 1604): loadItems() com.htc.launcher.pageview.WidgetManager@11dbeab4 +
I/Prism.WidgetManager( 1604): onLoadItems() +
,E/WifiStateMachine(  953): handleMessage: E msg.what=131155,
E/WifiStateMachine(  953): processMsg: ConnectedState
I/Prism.ItemManager( 5259): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 5259): loadItems() com.htc.launcher.pageview.WidgetManager@d431681 +
,I/Prism.WidgetManager( 5259): onLoadItems() +
E/WifiStateMachine(  953):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=30.9, 0.0, 0.0  rx=38.8 bcn=0 [on:0 tx:0 rx:0 period:2926] from screen [on:0 period:562132197] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  953): processMsg: L2ConnectedState
D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 5468): -onCreate()
E/WifiStateMachine(  953):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=30.9, 0.0, 0.0  rx=38.8 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:562132198] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  953):  get link layer stats 0
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1330): environment dirty rate=7 [28][2][0],
E/WifiStateMachine(  953): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  953): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
,E/WifiConfigStore(  953): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
,E/WifiStateMachine(  953): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=29.46 txretriesrate=0.00 rxrate=31.39 userTriggerdPenalty0
D/WIFI_ICON( 1232): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  953):  good link -> stuck count =0
E/WifiStateMachine(  953):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  953):  isHighRSSI       ---> score=65
D/WifiWatchdogStateMachine(  953): RSSI current: 3 new: -60, 3
D/StatusBar.NetworkController( 1232): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiStateMachine(  953): handleMessage: X
,V/Settings:HtcSettingsApplication( 5468): [5468/5468] onCreate(),
,D/TetherSettings( 5468): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5468): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5468): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5468): Cust_ConnectToPC   : spcsc>false
D/        ( 5468): Cust_ConnectToPC   : IPT>true
D/        ( 5468): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 5468): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 5468): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5468): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
W/ResourcesManager( 5259): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/SmartNS_NSReceiver( 5468): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 5468): usb_cable_connect = 1
D/SmartNS_Utility( 5468): usb_denied = 0
,I/SmartNS_NSReceiver( 5468): locked:falsesecurity:falseisLocked:false
,D/SmartNS_NSReceiver( 5468): USB = true hasTethered = false isNSOpening: false
,I/PSReceiver( 5468): onReceive:com.htc.intent.action.USB_CONNECT2PC
,W/ContextImpl( 5468): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2712 
,I/SmartNS_PSService( 5468): onReceive:com.htc.intent.action.USB_CONNECT2PC
,W/Settings( 5468): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 5468):  defaultType:0
,I/SmartNS_PSService( 5468): fail notificaiton:false
,D/SmartNS_Utility( 5468): usb_cable_connect = 1
D/SmartNS_Utility( 5468): usb_denied = 0
I/SmartNS_PSService( 5468): usb notificaiton:true
,E/WifiStateMachine(  953): WiFiDisplay: getWifidisplayApEnabled=false
,I/ActivityManager(  953): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=5491 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/ActionCombine( 5468): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,D/SmartNS_Utility( 5468): usb_cable_connect = 1
,D/SmartNS_Utility( 5468): usb_denied = 0
,I/SmartNS_PSService( 5468): usb notificaiton:true
D/DotMatrix( 1342): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,E/WifiStateMachine(  953): WiFiDisplay: getWifidisplayApEnabled=false
,I/RemoteViews( 1232): reapply : com.android.settings 0 36
,D/SmartNS_Utility( 5468): usb_cable_connect = 1,
D/SmartNS_Utility( 5468): usb_denied = 0
,I/RemoteViews( 1232): reapply : com.android.settings 0 36
D/DotMatrix( 1342): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/SmartNS_PSService( 5468): KeyGuard locked:falseKeyGuard is secured:false
D/SmartNS_PSService( 5468): USB Plugged, Set USBPlugged=  truePSenabled:false
,I/ActivityManager(  953): Killing 4999:com.htc.mobiledata/u0a46 (adj 15): empty #17
D/Process (  953): killProcessQuiet, pid=4999
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  953): Recipient 4999
,E/WifiStateMachine(  953): handleMessage: E msg.what=131165,
E/WifiStateMachine(  953): processMsg: ConnectedState
E/WifiStateMachine(  953):  ConnectedState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine(  953): processMsg: L2ConnectedState
E/WifiStateMachine(  953):  L2ConnectedState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine(  953): processMsg: ConnectModeState
E/WifiStateMachine(  953):  ConnectModeState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine(  953): processMsg: DriverStartedState
E/WifiStateMachine(  953):  DriverStartedState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine(  953): processMsg: SupplicantStartedState
E/WifiStateMachine(  953):  SupplicantStartedState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine(  953): processMsg: DefaultState
E/WifiStateMachine(  953):  DefaultState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine(  953): handleMessage: X
,W/ContextImpl( 5491): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.backupreset.receiver.BackupResetReceiver.onReceive:45 android.app.ActivityThread.handleReceiver:2712 ,
,D/FlexNetS( 5047): updateSvcAllowedInSettings:false
,D/MediaProvider( 3893): [update][13]#1#
,I/ActivityManager(  953): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=5516 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,D/Process (  953): killProcessQuiet, pid=4910
I/ActivityManager(  953): Killing 4910:com.google.android.music:main/u0a159 (adj 15): empty #17
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
W/ResourcesManager( 5259): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/PhoneApp( 1556): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1556): -- N1 =0
,D/PhoneApp( 1556): -- N2 =0
,D/PhoneApp( 1556): -- N3 =0
,E/Prism.WidgetManager( 1604): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1604): onLoadItems() -
I/Prism.ItemManager( 1604): loadItems() com.htc.launcher.pageview.WidgetManager@11dbeab4 -
,I/ActivityManager(  953): Recipient 4910,
D/MediaRouterService(  953): Client com.google.android.music (pid 4910): Died!
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  953):  packet count Tx=157 Rx=210
D/WIFI_ICON( 1232): WifiActivity: 0
E/WifiTrafficPoller(  953): notifying of data activity 0
D/StatusBar.NetworkController( 1232): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,W/ContextImpl( 5516): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/Messaging( 5383): supportCMAS(SIE)/init? false/true
D/MmsConfig( 5383): networkCode: 
,D/MmsConfig( 5383): SIE smsPri: null
,D/MmsConfig( 5383): networkCode: 
,D/PowerUsageList:PowerUsageHelper( 5516): MY_DEBUG = false
,D/Messaging( 5383): mNeedToUpdateDate2 start
D/PMS     (  953): acquireWL(311de4ba): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5516 1000 null
D/ReportIndicatorCache( 5383): startAsyncQueryReports ---
,D/MmsAsyncWorkHandler( 5383): 
D/MmsAsyncWorkHandler( 5383): HM tk = 20001
D/ReportIndicatorCache( 5383): MSG_QUERY_REPORTS >>
,D/DraftCache( 5383): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 5383): [DraftCache/1] refresh
I/ActivityManager(  953): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=5545 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a
,D/MmsConfig( 5383): networkCode: 
,D/PowerUsageService( 5516): repeat time = 1452261979003
I/Messaging( 5383): mccmnc> 
,D/TelephUtils( 1556): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50,
D/MmsSmsV2Provider( 1556):  slotId = -1000
D/MmsSmsV2Provider( 1556): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,W/asset   ( 5259): Copying FileAsset 0x55915fe5b0 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,D/Messaging( 5383): ViewCache CreatePreloadOnlyConversationList
,D/WeatherUtility( 1643): Weather sync is On
,D/TelephUtils( 1556): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/AccFlag ( 1556): sku_id=118
,D/WSP     ( 1643): [Receiver] auto sync agent, auto sync is enabled, reset schedule
,D/DraftCache( 5383): [DraftCache/121] rebuildCache
D/TelephUtils( 1556): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/MmsSmsV2Provider( 1556):  slotId = -1000
D/MmsSmsV2Provider( 1556): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/PhoneStorageUtil( 5383): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 5383): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/MessageCustFlag( 5383): sense_version=6.0
D/PhoneStorageUtil( 5383): createReceiver
D/Jerry   ( 5383): start to preload cursor >>>>>>>
,D/TelephUtils( 1556): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92,
D/MmsSmsV2Provider( 1556):  slotId = -1000
D/MmsSmsV2Provider( 1556): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/TelephUtils( 1556): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
,D/Messaging( 5383): mNeedToUpdateDate2: false
D/TelephUtils( 1556): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 93
D/Jerry   ( 1556): URI_DRAFT
V/MmsProvider( 1556): Update uri=content://mms, match=0
V/MmsProvider( 1556): selection=st=129 AND m_type!=134
D/Messaging( 5383): Reset downloading state: 0
V/MmsSystemEventReceiver( 5383): TransactionService is going to be woken up.
D/DraftCache( 5383): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 5383): [DraftCache/121] rebuildCache time: 6
D/MmsAsyncWorkHandler( 5383): 
D/MmsAsyncWorkHandler( 5383): HM tk = 20002
,D/TelephUtils( 1556): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
,D/MmsSmsV2Provider( 1556):  slotId = -1000
,V/TransactionService( 5383): 1-Creating TransactionService,
,D/TelephUtils( 1556): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/MmsSmsV2Provider( 1556):  slotId = -1000
D/MmsSmsV2Provider( 1556): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 5383): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1556): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92,
D/AccFlag ( 1556): sku_id=118
,D/Messaging( 5383): ViewCache CreatePreload
D/Messaging( 5383): ViewCache CreatePreloadOnlyMultipleOpsList
D/PMS     (  953): acquireWL(2e726f2f): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 5047 10011 null
,V/TransactionService( 5383): onStartCommand: 1
,D/MmsSystemEventReceiver( 5383): unRegisterForConnectionStateChanges
,V/TransactionService( 5383): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 5383): Loading previous transactions.
D/Cust_MMSMS( 5383): _has_set_default_values_2=true
,D/MsgPreferenceUtils( 5383): def_index: 0
,D/MsgPreferenceUtils( 5383): globalIndex = 1
,D/TelephUtils( 1556): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/AccFlag ( 1556): sku_id=118
D/TelephUtils( 1556): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
,D/AccFlag ( 1556): device_type: 1
,E/SQLiteLog( 5047): (284) automatic index on view_events(_id)
,I/Prism.WidgetManager( 5259): onLoadItems() -
I/Prism.ItemManager( 5259): loadItems() com.htc.launcher.pageview.WidgetManager@d431681 -
,I/ActivityManager(  953): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=5577 uid=10028 gids={50028, 9997, 1028, 1015, 1023, 3003, 2001, 3002} abi=armeabi-v7a
,D/MsgPreferenceUtils( 5383): phone state: true
D/MsgPreferenceUtils( 5383): sd state: false
D/MsgPreferenceUtils( 5383): vIndex = 0
,I/PowerUsageList:PowerUsageHelper( 5516): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/WeatherUtility( 5545): Weather sync is On
,W/ResourcesManager( 5577): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/PowerUsageList:BatterySipperExt( 5516): gen(), null == sipper.uidObj, userId = 0
,W/WeatherRequest( 5545): request cur loc, but there is no sys cur
W/Settings( 5545): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActionCombine( 5545): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,I/RemoteViews( 1604): reapply : com.htc.widget.weatherclock 10 17,
,I/art     (  953): Explicit concurrent mark sweep GC freed 19161(1056KB) AllocSpace objects, 4(388KB) LOS objects, 33% free, 18MB/28MB, paused 1.589ms total 150.968ms
,D/TransactionService( 5383): Force clearing mTransactionList,
D/TransactionService( 5383): Force set service start id to 1
V/TransactionService( 5383): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 5383): unRegisterForConnectionStateChanges
D/TransactionService( 5383): stopSelfResult: true, mLastHandledServiceId: 1
V/TransactionService( 5383): Destroying TransactionService
V/TransactionService( 5383): 4-Handling incoming message: { when=-1ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/PMS     (  953): releaseWL(2e726f2f): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,D/MediaProvider( 3893): [update][19]#1#
,I/ActivityManager(  953): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=5614 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,D/Process (  953): killProcessQuiet, pid=5095
I/ActivityManager(  953): Killing 5095:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/SQLiteLog( 5577): (283) recovered 15 frames from WAL file /data/data/com.htc.album/databases/MMexternal.db-wal,
,I/ActivityManager(  953): Recipient 5095
,I/MusicStore( 5614): Database version: 120,
,D/VoldConnector(  953): SND -> {24 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/,
,W/ContextImpl( 5614): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files,
,D/VoldConnector(  953): SND -> {25 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 5614): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files,
W/ContextImpl( 5614): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files,
D/VoldConnector(  953): SND -> {26 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ResourcesManager( 5614): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5614): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5614): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 5614): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5614): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1d9aca58: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5614): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5614): GMSCore installation verified
,I/ConfigStore( 5614): Config Database version: 1,
,D/MediaProvider( 3893): [update][12]#1#,
,D/MediaScanner( 3893):  prescan time: 671ms,
D/MediaScanner( 3893):     scan time: 1197ms
D/MediaScanner( 3893): postscan time: 2ms
D/MediaScanner( 3893):    total time: 1870ms
D/MediaScanner( 3893): -----------------------------------------------------------------
,D/MediaScanner( 3893): firstscan(media) time: 653ms
D/MediaScanner( 3893): secondscan(non-media) time: 543ms
D/MediaScanner( 3893):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 1
D/MediaScanner( 3893):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3893):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0,
D/MediaScanner( 3893):  [Total]    File(Image+Video+Audio+Others) in database : 1546
,D/MediaProvider( 3893): [delete][10]
,D/MediaProvider( 3893): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
,D/MediaProvider( 3893): [recoverParentNodes] - 0,
D/MediaProvider( 3893): [update][5]
,D/MediaScannerServiceEx( 3893): [scan] Recover Parent Node is finished!
D/MediaScannerServiceEx( 3893): [updateImage]+
,D/MediaScannerServiceEx( 3893): [updateImage]-0,
,D/PMS     (  953): releaseWL(25adbbae): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
,D/MediaScannerServiceEx( 3893): [1] scan finished
,D/MediaProviderUtils( 3893): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3893): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3893): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3893): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1
W/MediaScannerServiceEx( 3893): Process mounted intent for unmounted storage: /storage/ext_sd
,D/MediaScannerServiceEx( 3893): [disAliveExtStorageRows]+131073
,D/MediaProvider( 3893): [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted,
D/MediaProvider( 3893): [update][19]#1#
E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  953):  packet count Tx=157 Rx=212
E/WifiTrafficPoller(  953): notifying of data activity 1
,D/WIFI_ICON( 1232): WifiActivity: 1
D/StatusBar.NetworkController( 1232): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/PackageManager(  953):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=5614, uid=10159, userID:0
,D/WifiDisplayAdapter(  953): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  953):     Client/Owner: Client
D/WifiDisplayAdapter(  953):     GroupId: 
D/WifiDisplayAdapter(  953):     Passphrase: 
D/WifiDisplayAdapter(  953):     SessionId: 0
D/WifiDisplayAdapter(  953):     IP Address: }
,D/MediaProvider( 3893): [update][26]#0#
,D/MediaScannerServiceEx( 3893): [disAliveExtStorageRows]--1, 0,
D/MediaRouterService(  953): Client com.google.android.music (pid 5614): Registered
,D/MediaProviderUtils( 3893): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3893): calcVolumeId: /storage/ext_sd,
D/MediaProviderUtils( 3893): calcVolumeId: /storage/usb
,D/MediaScannerServiceEx( 3893): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
W/MediaScannerServiceEx( 3893): Process mounted intent for unmounted storage: /storage/usb
D/MediaScannerServiceEx( 3893): [disAliveExtStorageRows]+196609
,D/WifiDisplayAdapter(  953): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  953):     Client/Owner: Client
D/WifiDisplayAdapter(  953):     GroupId: 
D/WifiDisplayAdapter(  953):     Passphrase: 
D/WifiDisplayAdapter(  953):     SessionId: 0
D/WifiDisplayAdapter(  953):     IP Address: }
,D/MediaProvider( 3893): [sendStorageAddedIfNeed]: /storage/usb : unmounted
D/MediaProvider( 3893): [update][6]#1#
,I/MediaRouter( 5614): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android },
,I/NetworkMonitor( 5614): type=WIFI subType= reason=null isConnected=true,
,I/ActivityManager(  953): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5646 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a,
,D/MediaProvider( 3893): [update][43]#0#,
,D/MediaScannerServiceEx( 3893): [disAliveExtStorageRows]--1, 0
,V/AlarmManager(  953): sending alarm PendingIntent{3ccc7f88: PendingIntentRecord{1d1ded21 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1452261080040, Int=0
,I/NetworkMonitor( 5614): type=WIFI subType= reason=null isConnected=true,
,I/PackageManager(  953):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=5614, uid=10159, userID:0
,I/GHttpClientFactory( 5614): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 5614): Using platform SSLCertificateSocketFactory,
,D/Prism.PackageStateRece_( 1604): action: android.intent.action.PACKAGE_ADDED
,I/[PluginManager]RegisterService( 1643): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello
I/ActivityManager(  953): Killing 5134:com.google.android.apps.magazines/u0a161 (adj 15): empty #17
D/Process (  953): killProcessQuiet, pid=5134
I/[PluginManager]RegisterService( 1643): handle notify Blinkfeed plugin client changed
,D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  953): Recipient 5134
,I/ActivityManager(  953): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5675 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,D/Process (  953): killProcessQuiet, pid=5238
,I/ActivityManager(  953): Killing 5238:com.android.chrome/u0a96 (adj 15): empty #17
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  953): Recipient 5238,
,D/Process (  953): killProcessQuiet, pid=5282,
I/ActivityManager(  953): Killing 5282:com.google.android.apps.plus/u0a167 (adj 15): empty #17
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiDataStallTracker(  953): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  953): updateDataStallInfo: mDataStallTxRxSum={txSum=138 rxSum=139} preTxRxSum={txSum=111 rxSum=120}
D/WifiDataStallTracker(  953): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  953): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,I/ActivityManager(  953): Recipient 5282
,I/DeviceManagement( 5675): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=5675 dbg=false s=true
,I/DeviceManagement( 5675): PackageUpdateReceiver: vvv Package added: [com.example.hello]
,D/Process (  953): killProcessQuiet, pid=5336,
I/ActivityManager(  953): Killing 5336:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17,
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 ,
,I/ActivityManager(  953): Recipient 5336
,D/PMS     (  953): releaseWL(311de4ba): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,D/Process (  953): killProcessQuiet, pid=4881,
I/ActivityManager(  953): Killing 4881:com.google.android.gms.wearable/u0a24 (adj 15): empty #17
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  953):  packet count Tx=157 Rx=215
,I/ActivityManager(  953): Recipient 4881
,I/ActivityManager(  953): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=5698 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a
,D/Process (  953): killProcessQuiet, pid=5358
I/ActivityManager(  953): Killing 5358:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  953): Recipient 5358
,E/WifiStateMachine(  953): handleMessage: E msg.what=131155,
E/WifiStateMachine(  953): processMsg: ConnectedState
E/WifiStateMachine(  953):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=29.5, 0.0, 0.0  rx=31.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:562135218] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  953): processMsg: L2ConnectedState
E/WifiStateMachine(  953):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=29.5, 0.0, 0.0  rx=31.4 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:562135220] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  953):  get link layer stats 0
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1330): environment dirty rate=0 [0][0][0],
E/WifiStateMachine(  953): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  953): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  953): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
E/WifiStateMachine(  953): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=14.73 txretriesrate=0.00 rxrate=18.19 userTriggerdPenalty0,
E/WifiStateMachine(  953):  good link -> stuck count =0
E/WifiStateMachine(  953):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  953):  isHighRSSI       ---> score=65
,I/ActivityManager(  953): Waited long enough for: ServiceRecord{3427ef42 u0 com.google.android.gms/.config.ConfigFetchService},
D/WifiWatchdogStateMachine(  953): RSSI current: 3 new: -60, 3
V/AlarmManager(  953): sending alarm PendingIntent{36c6ea64: PendingIntentRecord{1b7474cd android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=69438, Int=0
D/WIFI_ICON( 1232): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1232): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiStateMachine(  953): handleMessage: X
,D/HtcCupdReceiver(Provider)( 5698):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED
,I/ActivityManager(  953): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5720 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/Process (  953): killProcessQuiet, pid=5259,
I/ActivityManager(  953): Killing 5259:com.htc.sense.news/u0a74 (adj 15): empty #17
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,D/Settings:HtcWirelessFeatureFlags( 5468): id/is att sku: 118/false,
,E/Settings:HtcWrapHeaderInfo( 5468): no such activity!,
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 5468): The wrap header doesn't exist in header list.,
,E/Settings:HtcWrapHeaderInfo( 5468): updateDevelopment, bPrefShow = true,
,I/ActivityManager(  953): Recipient 5259
,E/Settings:HtcUmcWidgetEnabler( 5468): isSupportMusicChannel(): false,
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5468): [supportRecentAppsButton]hasNavigationBar:true,
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5468): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5468): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5468): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5468): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5468): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5468): [supportHomeButton]hasBackKey      :false,
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5468): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5468): [supportHomeButton]support         :false
,I/ActivityManager(  953): Cannot resolve ContentProvider=com.htc.vowifi
,E/ActivityThread( 5468): Failed to find provider info for com.htc.vowifi,
E/Settings:HtcVoWifiWidgetEnabler( 5468): isSupportVoWifi: null
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 5468): The wrap header doesn't exist in header list.,
,E/Settings:HtcWrapHeaderInfo( 5468): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 5468): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5468): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5468): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5468): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5468): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5468): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5468): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5468): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5468): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5468): [supportHomeButton]support         :false
,I/ActivityManager(  953): Cannot resolve ContentProvider=com.htc.vowifi
,E/Settings:HtcVoWifiWidgetEnabler( 5468): isSupportVoWifi: null
E/ActivityThread( 5468): Failed to find provider info for com.htc.vowifi
,I/PackageManager(  953):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=5720, uid=10072, userID:0,
,W/global  ( 5720): [apache-http] Connection GC has been deprecated!,
,D/Finsky  ( 5720): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/,
,W/global  ( 5720): [apache-http] Connection GC has been deprecated!,
,W/global  ( 5720): [apache-http] Connection GC has been deprecated!,
,D/Finsky  ( 5720): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.,
,I/ActivityManager(  953): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5761 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/Settings( 5720): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5720): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 5761): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5761): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/PackageManager(  953):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=5720, uid=10072, userID:0
,I/MultiDex( 5761): VM with version 2.1.0 has multidex support
I/MultiDex( 5761): install
,I/MultiDex( 5761): VM has multidex support, MultiDex support library is disabled.
,D/Process (  953): killProcessQuiet, pid=4972
,I/ActivityManager(  953): Killing 4972:com.htc.mobiledata:remote/u0a46 (adj 15): empty #17
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,V/JNIHelp ( 5761): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  953):  packet count Tx=157 Rx=218
,W/ActivityThread( 5761): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,W/System  ( 5761): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@35a2365e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5761): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  953): Recipient 4972
,I/HtcModeClient( 3238): handler message = 4011,
E/HtcModeClient( 3238): Check connection and retry 6 times.
,D/Finsky  ( 5720): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5720): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 5720): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/ChimeraCfgMgr( 4507): Loading module com.google.android.gms.games from APK com.google.android.play.games,
D/ChimeraModuleLdr( 4507): Loading module APK com.google.android.play.games,
D/PackageBroadcastService( 4507): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,D/Finsky  ( 5720): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  953): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=5793 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
D/PMS     (  953): acquireWL(35d22f32): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4507 10024 null
,I/art     (  458): Explicit concurrent mark sweep GC freed 8708(370KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 200us total 30.125ms,
,W/ResourcesManager( 5793): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5793): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/art     (  458): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 173us total 19.908ms
,I/MultiDex( 5793): VM with version 2.1.0 has multidex support
I/MultiDex( 5793): install
I/MultiDex( 5793): VM has multidex support, MultiDex support library is disabled.
,I/art     (  458): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 139us total 21.383ms
,V/JNIHelp ( 5793): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 5793): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 5793): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@35a2365e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5793): Installed default security provider GmsCore_OpenSSL
,D/Process (  953): killProcessQuiet, pid=4610,
I/ActivityManager(  953): Killing 4610:com.google.android.talk/u0a112 (adj 15): empty #17
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  953): Recipient 4610
,I/ConfigFetchService( 4507): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,D/PMS     (  953): acquireWL(10807b71): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 4507 10024 WorkSource{10374 com.example.hello},
,I/ConfigFetchService( 4507): launchTask
,D/PMS     (  953): releaseWL(35d22f32): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,V/ConfigFetchTask( 4507): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1ULzU4IoSkIiCz9MqSEjrp62ceen8jM7L1PU5Ri9qW1bINNnaH21duuIvTD8BXFBBM1wjeXZApVABLohcX2hcidtmt1lWm0K7GJZw4yduOx3shLAQK0JuXkmN6pC6kMeohNJktmuXteVR6VfRSdl44LHDmckrT6oLrQ3_eZ9cch5OWokIz1EFzYbaCUf7Bs39Yw2QPY
D/PMS     (  953): acquireWL(16b72d56): PARTIAL_WAKE_LOCK  Icing 0x1 4507 10024 WorkSource{10024 com.google.android.gms}
,I/GoogleURLConnFactory( 4507): Using platform SSLCertificateSocketFactory
,D/Process (  953): killProcessQuiet, pid=5409
I/ActivityManager(  953): Killing 5409:com.htc.task/u0a69 (adj 15): empty #17
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/ChimeraCfgMgr( 4507): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4507): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 4507): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/Vision  ( 4507): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package: flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
,D/Vision  ( 4507): Failed to find package metadata for com.example.hello
D/Vision  ( 4507): No vision deps
,I/ActivityManager(  953): Recipient 5409,
,I/ActivityManager(  953): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5826 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a
,D/libc    ( 4507): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4507): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4507): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 4507): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4507): [NET] android_getaddrinfo_proxy+
D/libc    ( 4507): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  400): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  400): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  400): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4507): [NET] android_getaddrinfo_proxy-, success
,V/Finsky  ( 5720): [1] GearheadStateMonitor.onReady: sIsProjecting:false
V/AlarmManager(  953): sending alarm PendingIntent{3c10c8e2: PendingIntentRecord{31269473 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452261082800, Int=0
,D/Finsky  ( 5720): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,I/PeopleContactsSync( 4507): CP2 sync disabled
,I/PackageManager(  953):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4507, uid=10024, userID:0
,W/BaseAppContext( 4507): Using Auth Proxy for data requests.,
,W/BaseAppContext( 4507): Using Auth Proxy for data requests.
,V/GLSActivity( 1986): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/Icing   ( 4507): Storage manager: low false usage 1.98MB avail 5.80GB capacity 7.95GB
,W/Icing   ( 4507): Received bad json for section weights override -- ignoring.,
,W/Icing   ( 4507): Received bad json for corpus context scoring override -- ignoring.
W/Icing   ( 4507): Received bad json for section weights override -- ignoring.
W/Icing   ( 4507): Received bad json for corpus context scoring override -- ignoring.
,D/libc    ( 4507): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4507): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 4507): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,D/libc    ( 4507): [NET] android_getaddrinfofornet-, err=8
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7
,E/WifiTrafficPoller(  953):  packet count Tx=169 Rx=232
E/WifiTrafficPoller(  953): notifying of data activity 3
,D/WIFI_ICON( 1232): WifiActivity: 3
D/StatusBar.NetworkController( 1232): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/ConfigFetchService( 4507): fetch service done; releasing wakelock,
D/PMS     (  953): releaseWL(10807b71): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 WorkSource{10374 com.example.hello}
I/ConfigFetchService( 4507): stopping self
,I/art     (  953): Explicit concurrent mark sweep GC freed 25560(1238KB) AllocSpace objects, 1(264KB) LOS objects, 33% free, 18MB/27MB, paused 1.607ms total 142.090ms
,I/art     ( 1986): Explicit concurrent mark sweep GC freed 7178(359KB) AllocSpace objects, 3(252KB) LOS objects, 49% free, 4MB/8MB, paused 726us total 40.705ms
,E/Icing   ( 4507): Loading extension by file descriptor -1 failed
,I/GLSUser ( 1986): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1986): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1986): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1986): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/BaseAppContext( 4507): Using Auth Proxy for data requests.
,V/GLSActivity( 1986): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BaseAppContext( 4507): Using Auth Proxy for data requests.
,W/Finsky  ( 5720): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,W/BaseAppContext( 4507): Using Auth Proxy for data requests.
,V/GLSActivity( 1986): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BaseAppContext( 4507): Using Auth Proxy for data requests.,
,I/GLSUser ( 1986): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1986): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1986): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1986): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1986): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1986): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1986): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1986): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1986): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1986): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1986): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5720): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Icing   ( 4507): updateResources: need to parse f{com.google.android.gms},
,I/Icing   ( 4507): Internal init done: storage state 0
,I/Icing   ( 4507): Post-init done,
,D/PMS     (  953): releaseWL(16b72d56): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,E/AndroidHttpClient( 5720): Leak found
E/AndroidHttpClient( 5720): java.lang.IllegalStateException: AndroidHttpClient created and never closed
E/AndroidHttpClient( 5720): 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 5720): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 5720): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 5720): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 5720): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 5720): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 5720): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 5720): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 5720): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 5720): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 5720): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 5720): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 5720): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 5720): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 5720): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 5720): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/GAv4    ( 5826): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:,
I/GAv4    ( 5826):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5826):   adb logcat -s GAv4
,W/GAv4    ( 5826): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 5826): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 5826): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,W/AnalyticsTrackerProxyImpl( 5826): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.45,
,V/GLSActivity( 1986): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1986): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1986): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1986): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1986): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1986): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5720): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/ChimeraCfgMgr( 4507): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4507): Module APK com.google.android.play.games already loaded
,D/Finsky  ( 5720): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 5720): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5720): [1] DailyHygiene.reschedule: Scheduling new run in 9 minutes (failures=1)
,D/DeviceConnectionService( 1842): client connected with version: 7571000,
,D/VoldConnector(  953): SND -> {27 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
D/Process (  953): killProcessQuiet, pid=5434
I/ActivityManager(  953): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5874 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
W/ContextImpl( 5826): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache
I/ActivityManager(  953): Killing 5434:com.nero.android.htc.sync/u0a5 (adj 15): empty #17
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,W/ResourcesManager( 5826): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5826): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  953): Recipient 5434
D/WifiService(  953): Client connection lost with reason: 4
,W/ResourcesManager( 5874): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,V/JNIHelp ( 5826): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/System  ( 5826): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5826): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1986): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 6
,E/WifiTrafficPoller(  953):  packet count Tx=170 Rx=239
,D/PMS     (  953): acquireWL(2c71ff6d): PARTIAL_WAKE_LOCK  AsyncService 0x1 5874 10167 null,
,D/PMS     (  953): acquireWL(1f3f6c33): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 5874 10167 null
D/PMS     (  953): releaseWL(2c71ff6d): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  953): releaseWL(1f3f6c33): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,I/ActivityManager(  953): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5906 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a,
,I/ActivityManager(  953): Killing 5491:com.htc.backupreset/1000 (adj 15): empty #17
D/Process (  953): killProcessQuiet, pid=5491
,D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  953): Recipient 5491
,D/Process (  953): killProcessQuiet, pid=5516
I/ActivityManager(  953): Killing 5516:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiStateMachine(  953): handleMessage: E msg.what=131155,
E/WifiStateMachine(  953): processMsg: ConnectedState
E/WifiStateMachine(  953):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=14.7, 0.0, 0.0  rx=18.2 bcn=0 [on:0 tx:0 rx:0 period:2974] from screen [on:0 period:562138240] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  953): processMsg: L2ConnectedState
E/WifiStateMachine(  953):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=14.7, 0.0, 0.0  rx=18.2 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:562138241] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  953):  get link layer stats 0
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1330): environment dirty rate=15 [13][2][0],
E/WifiStateMachine(  953): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  953): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  953): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
E/WifiStateMachine(  953): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=13.86 txretriesrate=0.00 rxrate=21.10 userTriggerdPenalty0
E/WifiStateMachine(  953):  good link -> stuck count =0,
E/WifiStateMachine(  953):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  953):  isHighRSSI       ---> score=65
,I/ActivityManager(  953): Recipient 5516
,E/WifiStateMachine(  953): handleMessage: X,
,D/WifiWatchdogStateMachine(  953): RSSI current: 3 new: -60, 3
,D/WIFI_ICON( 1232): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1232): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/ActivityManager(  953): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=5928 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a,
,W/ResourcesManager( 5928): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,D/TelephonyReceiver( 1556): bind: true,
,I/ActivityManager(  953): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=5953 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,D/GenericMessagesProvider( 5383): query uri: content://htc-messages/wappush/count
E/SQLiteLog( 5383): (14) cannot open file at line 30058 of [9491ba7d73]
E/SQLiteLog( 5383): (14) os_unix.c:30058: (2) open(/data/data/com.htc.sense.mms/databases/wappush.db) - 
E/SQLiteConnection( 5383): DB info: sqlite3_open_v2, path: /data/data/com.htc.sense.mms/databases/wappush.db, flag: 1, ret: 14
E/SQLiteConnection( 5383): DB info: errno = 2, errno message = No such file or directory
,E/SQLiteDatabase( 5383): Failed to open database '/data/data/com.htc.sense.mms/databases/wappush.db'.,
E/SQLiteDatabase( 5383): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 5383): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5383): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5383): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5383): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5383): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5383): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5383): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5383): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5383): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5383): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:712)
E/SQLiteDatabase( 5383): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
E/SQLiteDatabase( 5383): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 5383): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 5383): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
E/SQLiteDatabase( 5383): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err( 5383): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
W/System.err( 5383): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 5383): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
W/System.err( 5383): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
W/System.err( 5383): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/System.err( 5383): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/System.err( 5383): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/System.err( 5383): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
W/System.err( 5383): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
W/System.err( 5383): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
W/System.err( 5383): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:712)
W/System.err( 5383): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
W/System.err( 5383): 	at android.content.ContentProvider.query(ContentProvider.java:960)
W/System.err( 5383): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
W/System.err( 5383): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
W/System.err( 5383): 	at android.os.Binder.execTransact(Binder.java:454)
,D/TelephonyReceiver( 1556): switchBindHtcMsgCursor: null
,D/DFPI.PIReciver( 5953): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED,
,I/ActivityManager(  953): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=5976 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a,
D/LocationManagerService(  953): getProviders()=[passive]
,I/DFPI.ApkInstallService( 5953): onHandleIntent
I/DFPI.ApkInstallService( 5953): Media Scan Finished Case 
,D/DFPI.ApkInstallService( 5953): check CID = HTC__102
,I/DFPI.ApkInstallService( 5953): There is no Demo.apk in sd card or phone storage
,I/ActivityManager(  953): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=5995 uid=10049 gids={50049, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  953): Killing 5545:com.htc.widget.hmsproc2/u0a40 (adj 15): empty #17
D/Process (  953): killProcessQuiet, pid=5545
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  953): Recipient 5545
,I/UpdateIcingCorporaServi( 5906): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE,
,I/ActivityManager(  953): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=6030 uid=10079 gids={50079, 9997, 5001, 1028, 1015} abi=arm64-v8a,
,W/BroadcastQueue(  953): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_MEDIA due to registered receiver BroadcastFilter{38b66176 u0 ReceiverList{2a296c11 5995 com.htc.musicenhancer/10049/u0 remote:b4be438}},
,D/VoldConnector(  953): SND -> {28 volume mkdirs /storage/ext_sd/Android/data/com.htc.musicenhancer/cache/},
W/ContextImpl( 5995): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.htc.musicenhancer/cache/
,W/asset   ( 5906): Copying FileAsset 0x5591471190 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.,
,I/SoundPicker( 6030): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 6030): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 6030): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) },
V/SoundPicker( 6030): TurnFileToMediaUriService fromMediaScanned = true
,I/SoundPicker( 6030): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
,D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1,
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
,D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
D/DFPI.PIReciver( 5953): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
,D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
,W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 4)
,I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
,I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
,I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 6030): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/EASAppSvc( 5976): [ NA ]onCreate
I/DFPI.ApkInstallService( 5953): onHandleIntent
I/DFPI.ApkInstallService( 5953): Media Scan Finished Case 
,D/DFPI.ApkInstallService( 5953): check CID = HTC__102
I/DFPI.ApkInstallService( 5953): There is no Demo.apk in sd card or phone storage
,I/SoundPicker( 6030): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  953):  packet count Tx=170 Rx=243
E/WifiTrafficPoller(  953): notifying of data activity 1
D/WIFI_ICON( 1232): WifiActivity: 1
,I/SoundPicker( 6030): SoundPickerReceiver [onReceive] startService
D/StatusBar.NetworkController( 1232): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/VersionUtil( 5976): [ NA ]setIsFOTAing: true
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/VersionUtil( 5976): [ NA ]onUpgrade: current version=100, latest version=100
I/VersionUtil( 5976): [ NA ]setIsFOTAing: false
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
,I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
D/HtcAdjCursorFactory( 5976): Set CursorWindow size to: 4194304 KB, Tid: 6057
,D/DFPI.PIReciver( 5953): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED,
,I/DFPI.ApkInstallService( 5953): onHandleIntent
,I/DFPI.ApkInstallService( 5953): Media Scan Finished Case 
,D/DFPI.ApkInstallService( 5953): check CID = HTC__102
,I/DFPI.ApkInstallService( 5953): There is no Demo.apk in sd card or phone storage
,I/SoundPicker( 6030): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 6030): SoundPickerReceiver [onReceive] startService,
,D/PMS     (  953): acquireWL(115d8c5a): PARTIAL_WAKE_LOCK  Icing 0x1 4507 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  953): releaseWL(115d8c5a): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,D/DFPI.PIReciver( 5953): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/ActivityManager(  953): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/DFPI.ApkInstallService( 5953): onHandleIntent
I/DFPI.ApkInstallService( 5953): Media Scan Finished Case 
,D/DFPI.ApkInstallService( 5953): check CID = HTC__102
,I/DFPI.ApkInstallService( 5953): There is no Demo.apk in sd card or phone storage
D/PMS     (  953): acquireWL(292c7b81): PARTIAL_WAKE_LOCK  Icing 0x1 4507 10024 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  953): Resuming delayed broadcast
,I/SoundPicker( 6030): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED,
,I/SoundPicker( 6030): SoundPickerReceiver [onReceive] startService,
,I/ActivityManager(  953): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=6066 uid=10084 gids={50084, 9997, 3003, 1028, 1015, 1023, 2001, 5006, 5001} abi=arm64-v8a,
,D/PMS     (  953): releaseWL(292c7b81): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  953): acquireWL(22381403): PARTIAL_WAKE_LOCK  Icing 0x1 4507 10024 WorkSource{10024 com.google.android.gms},
,I/UpdateIcingCorporaServi( 5906): UpdateCorporaTask done [took 380 ms] updated apps [took 380 ms] ,
,I/art     (  953): Explicit concurrent mark sweep GC freed 15711(714KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 18MB/28MB, paused 1.646ms total 159.090ms
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4,
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 4)
,I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,D/ORMLib  ( 5928): put()
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac,
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,E/WifiTrafficPoller(  953): ADD_CLIENT: 7
,D/WifiService(  953): New client listening to asynchronous messages
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac,
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/EASAppSvc( 5976): [ NA ]onDestroy,
I/EASAppSvc( 5976): [ NA ]> uninitEASService
,I/EASAppSvc( 5976): [ NA ]onCreate
,I/EASRequestController( 5976): [ NA ]release
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/VersionUtil( 5976): [ NA ]setIsFOTAing: true
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/DFPI.PIReciver( 5953): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 6030): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 6030): TurnFileToMediaUriService fromMediaScanned = true
,I/SoundPicker( 6030): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
,I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 6030): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/VersionUtil( 5976): [ NA ]onUpgrade: current version=100, latest version=100
I/VersionUtil( 5976): [ NA ]setIsFOTAing: false
,I/DFPI.ApkInstallService( 5953): onHandleIntent
I/DFPI.ApkInstallService( 5953): Media Scan Finished Case 
,I/MediaStoreImporter( 5614): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
D/DFPI.ApkInstallService( 5953): check CID = HTC__102
I/DFPI.ApkInstallService( 5953): There is no Demo.apk in sd card or phone storage
,I/SoundPicker( 6030): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED,
D/ORMLib  ( 5928): put()
I/ActivityManager(  953): Killing 5047:com.htc.bgp/u0a11 (adj 15): empty #17
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_cdma)
,I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
D/Process (  953): killProcessQuiet, pid=5047
D/EASPublicBinder( 5976): [ NA ]release
D/TaskBinder( 5976): [ NA ]release
D/TaskBinder( 5976): [ NA ]release
I/EASAppSvc( 5976): [ NA ]< uninitEASService
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  953): Recipient 5047
,I/SoundPicker( 6030): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/EASAppSvc( 5976): [ NA ]onDestroy
,I/EASAppSvc( 5976): [ NA ]> uninitEASService
,I/ActivityManager(  953): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=6107 uid=10066 gids={50066, 9997, 3003} abi=arm64-v8a
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/EASRequestController( 5976): [ NA ]release
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98,
,D/DFPI.PIReciver( 5953): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,D/EASPublicBinder( 5976): [ NA ]release
D/TaskBinder( 5976): [ NA ]release
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,D/TaskBinder( 5976): [ NA ]release
I/EASAppSvc( 5976): [ NA ]< uninitEASService
,I/DFPI.ApkInstallService( 5953): onHandleIntent
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/DFPI.ApkInstallService( 5953): Media Scan Finished Case 
,I/SoundPicker( 6030): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 6030): SoundPickerReceiver [onReceive] startService
,D/DFPI.ApkInstallService( 5953): check CID = HTC__102
I/DFPI.ApkInstallService( 5953): There is no Demo.apk in sd card or phone storage
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac,
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,D/DFPI.PIReciver( 5953): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac,
I/MediaStoreImporter( 5614): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
I/DFPI.ApkInstallService( 5953): onHandleIntent
I/DFPI.ApkInstallService( 5953): Media Scan Finished Case 
,D/DFPI.ApkInstallService( 5953): check CID = HTC__102
,I/DFPI.ApkInstallService( 5953): There is no Demo.apk in sd card or phone storage
,I/SoundPicker( 6030): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED,
,I/SoundPicker( 6030): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,D/TelephonyReceiver( 1556): bind: false
,D/TelephonyReceiver( 1556): switchBindHtcMsgCursor: null
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/GCM     ( 1986): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE,
I/SoundPicker( 6030): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 6030): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 6030): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1,
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
,D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
,D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 2),
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 4)
,I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 6030): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
D/AuthorizationBluetoothService( 1986): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
V/GmsCoreStatsServiceLauncher( 4507): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
,I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,D/WearableService( 5793): callingUid 10024, callindPid: 5793
I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
I/PackageManager(  953):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4507, uid=10024, userID:0
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,D/LocationInitializer( 4507): Restart initialization of location
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac,
,I/MediaStoreImporter( 5614): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
D/GCM     ( 1986): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/ORMLib  ( 5928): put()
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,D/AuthorizationBluetoothService( 1986): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/art     ( 5793): Background sticky concurrent mark sweep GC freed 27406(1411KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 2MB/4MB, paused 5.307ms total 39.905ms
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
V/GmsCoreStatsServiceLauncher( 4507): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,E/MDM     ( 1842): [145] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/PackageManager(  953):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4507, uid=10024, userID:0
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,E/MDM     ( 1842): [146] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,D/LocationInitializer( 4507): Restart initialization of location
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
,V/SoundPicker( 6030): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 6030): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 6030): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
E/WifiDataStallTracker(  953): DATA_MONITOR_POLL true Token 1
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
D/WifiDataStallTracker(  953): updateDataStallInfo: mDataStallTxRxSum={txSum=151 rxSum=150} preTxRxSum={txSum=138 rxSum=139}
D/WifiDataStallTracker(  953): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  953): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/MediaStoreImporter( 5614): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac,
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac,
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104,
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/ActionCombine( 6066): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 6030): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 6030): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
,W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 6030): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
,D/PMS     (  953): acquireWL(813ef9d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1986 10024 WorkSource{10024 com.google.android.gms},
,D/DotMatrix( 1342): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false,
D/PMS     (  953): releaseWL(813ef9d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
D/PMS     (  953): acquireWL(33ed0c12): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1986 10024 WorkSource{10024 com.google.android.gms}
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
I/RemoteViews( 1232): setHTCTheme(com.htc.updater,true,33751145)
I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/MediaStoreImporter( 5614): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
I/RemoteViews( 1232): apply : com.htc.updater 0 12 2 36
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
D/PMS     (  953): releaseWL(33ed0c12): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,D/FindExtension( 1232): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,I/ThreadedRenderer( 1232): Defer allocateBuffers to drawing time,
,I/art     (  953): Explicit concurrent mark sweep GC freed 8606(375KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 18MB/28MB, paused 3.008ms total 171.549ms,
I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac,
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,D/PMS     (  953): acquireWL(35ba0b6a): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 4507 10024 WorkSource{10024 com.google.android.gms}
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 6030): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 6030): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 2),
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
,W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 6030): TurnFileToMediaUriService [checkFileExistence]
,D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/MediaStoreImporter( 5614): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/ActivityManager(  953): Killing 5646:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  953): killProcessQuiet, pid=5646
,D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  953):  packet count Tx=170 Rx=246
,I/ActivityManager(  953): Recipient 5646
,V/AlarmManager(  953): sending alarm PendingIntent{dad585b: PendingIntentRecord{151c88f8 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1452261086007, Int=0,
,I/ActivityManager(  953): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6157 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac,
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,D/PMS     (  953): releaseWL(35ba0b6a): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 WorkSource{10024 com.google.android.gms}
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac,
D/PhoneMonitor( 6157): Register our PhoneStateListener
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/ActivityManager(  953): Killing 5675:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  953): killProcessQuiet, pid=5675
,D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,D/PhoneMonitor( 6157): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false,
,D/PhoneMonitor( 6157): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,I/Icing   ( 4507): Indexing FBE7E5D8BA1B80556F1315772AF6A2582D6BF376 from com.google.android.googlequicksearchbox,
,I/ActivityManager(  953): Recipient 5675,
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac,
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac,
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 6030): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
,V/SoundPicker( 6030): TurnFileToMediaUriService fromMediaScanned = true
D/PMS     (  953): acquireWL(2bfc77d3): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4507 10024 WorkSource{10024 com.google.android.gms}
I/SoundPicker( 6030): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_cdma)
D/GCM     ( 1986): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
,W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 6030): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,D/PMS     (  953): acquireWL(38042a09): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4507 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): releaseWL(2bfc77d3): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,D/ChimeraCfgMgr( 4507): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,D/ChimeraCfgMgr( 4507): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/PackageManager(  953):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4507, uid=10024, userID:0
,I/CheckinService( 4507): Checking schedule, now: 1452261086262 next: 1452261107847,
,I/CheckinService( 4507): active receiver: disabled
D/PMS     (  953): releaseWL(38042a09): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,D/PMS     (  953): acquireWL(17402028): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1986 10024 WorkSource{10024 com.google.android.gms}
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,D/PMS     (  953): releaseWL(17402028): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/PackageManager(  953):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=4507, uid=10024, userID:0
,I/PackageManager(  953):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=4507, uid=10024, userID:0
I/PackageManager(  953):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=4507, uid=10024, userID:0
I/ActivityManager(  953): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent: pid=6183 uid=10035 gids={50035, 9997} abi=arm64-v8a
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
I/GLSUser ( 1986): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1986): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1986): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1986): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/Icing   ( 4507): Indexing done FBE7E5D8BA1B80556F1315772AF6A2582D6BF376
,I/CheckinService( 4507): Done disabling old GoogleServicesFramework version
I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
V/GLSActivity( 1986): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/ActivityManager(  953): Killing 5168:com.google.android.gms.unstable/u0a24 (adj 15): empty #17,
,D/Process (  953): killProcessQuiet, pid=5168
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  953): Recipient 5168
,D/PMS     (  953): releaseWL(22381403): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,W/Kids    ( 4507): [AccountUtils] Account not ready,
W/Kids    ( 4507): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4507): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4507): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4507): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4507): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4507): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4507): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4507): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4507): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4507): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4507): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4507): 	,at java.lang.Thread.run(Thread.java:818)
D/DotMatrix( 1342): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1342): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1232): reapply : com.google.android.gms 4 40
,I/ActivityManager(  953): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=6206 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  953): Killing 5698:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
,D/Process (  953): killProcessQuiet, pid=5698
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  953): Recipient 5698,
,W/ResourcesManager( 6206): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7
D/WIFI_ICON( 1232): WifiActivity: 3
E/WifiTrafficPoller(  953):  packet count Tx=172 Rx=250,
E/WifiTrafficPoller(  953): notifying of data activity 3
D/StatusBar.NetworkController( 1232): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/HtcModeClient( 3238): handler message = 4011
,E/HtcModeClient( 3238): Check connection and retry 7 times.
,I/Babel_SMS( 6206): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6206): MmsConfig.loadMmsSettings
,D/MmsCustomizationProvider( 5383): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 5383): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/Babel_SMS( 6206): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,I/Babel_SMS( 6206): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6206): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 6206): MmsConfig.loadFromResources
,I/PackageManager(  953):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=6206, uid=10112, userID:0,
,E/Babel_SMS( 6206): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6206): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,W/Settings( 6206): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,I/Babel_Crash( 6206): startup - clean
,I/Babel   ( 6206): deleted: false for 0
,I/PackageManager(  953):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=6206, uid=10112, userID:0
,I/PackageManager(  953):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=6206, uid=10112, userID:0
,I/PackageManager(  953):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=6206, uid=10112, userID:0
,I/PackageManager(  953):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=6206, uid=10112, userID:0
,I/PackageManager(  953):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=6206, uid=10112, userID:0
,D/PMS     (  953): acquireWL(6cfe358): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 6206 10112 null
,E/WifiStateMachine(  953): WiFiStateMachine SCAN ALARM
D/WifiDisplayAdapter(  953): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  953):     Client/Owner: Client
D/WifiDisplayAdapter(  953):     GroupId: 
D/WifiDisplayAdapter(  953):     Passphrase: 
D/WifiDisplayAdapter(  953):     SessionId: 0
D/WifiDisplayAdapter(  953):     IP Address: }
E/WifiStateMachine(  953): handleMessage: E msg.what=131143
E/WifiStateMachine(  953): processMsg: ConnectedState
E/WifiStateMachine(  953):  ConnectedState !CMD_START_SCAN -2 -2 ic=2 proc(ms):1 dur:6239 rssi=-60 f=2412 sc=60 link=72 tx=13.9, 0.0, 0.0  rx=21.1 fiv=60000 [on:0 tx:0 rx:0 period:2795] from screen [on:0 period:562141167]
E/WifiStateMachine(  953): processMsg: L2ConnectedState
,E/WifiStateMachine(  953):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=2 proc(ms):2 dur:6239 rssi=-60 f=2412 sc=60 link=72 tx=13.9, 0.0, 0.0  rx=21.1 fiv=60000 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:562141169]
E/WifiStateMachine(  953): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=13.86 rxSuccessRate=21.10 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-60
E/WifiStateMachine(  953): WifiStateMachine CMD_START_SCAN with age=38306 interval=60000 maxinterval=300000
E/WifiStateMachine(  953): WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
E/WifiStateMachine(  953): WifiStateMachine CMD_START_SCAN full=false
,E/WifiConfigStore(  953): makeChannelList age=3600000 for "NG700"WPA_PSK max=6 bssids=1
E/WifiConfigStore(  953): has c0:ff:d4:d3:aa:48 freq=2412 age=2915 ?=true
W/VideoCapabilities( 6206): Unrecognized profile 2130706433 for video/avc
E/WifiStateMachine(  953): WifiStateMachine starting scan for "NG700"WPA_PSK with 2412
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY freq=2412"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SCAN TYPE=ONLY freq=2412'
D/wpa_supplicant( 1330): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1330): wpa_supplicant_scan enter
D/wpa_supplicant( 1330): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1330): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1330): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1330): WPS:  * Request Type
,D/wpa_supplicant( 1330): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1330): WPS:  * UUID-E
D/wpa_supplicant( 1330): WPS:  * Primary Device Type
D/wpa_supplicant( 1330): WPS:  * RF Bands (3)
D/wpa_supplicant( 1330): WPS:  * Association State
D/wpa_supplicant( 1330): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1330): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1330): WPS:  * Manufacturer
D/wpa_supplicant( 1330): WPS:  * Model Name
D/wpa_supplicant( 1330): WPS:  * Model Number
D/wpa_supplicant( 1330): WPS:  * Device Name
D/wpa_supplicant( 1330): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1330): P2P: * P2P IE header
D/wpa_supplicant( 1330): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1330): P2P: * Listen Channel: Regulatory Class 81 Channel 1
D/wpa_supplicant( 1330): wlan0: Limit manual scan to specified channels
D/wpa_supplicant( 1330): wlan0: Add radio work 'scan'@0x55c1e20680
D/wpa_supplicant( 1330): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1330): wlan0: Starting radio work 'scan'@0x55c1e20680 after 0.000052 second wait
D/wpa_supplicant( 1330): wlan0: nl80211: scan request
D/wpa_supplicant( 1330): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1330): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1330): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1330): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1330): wlan0: Own scan request started a scan in 0.000133 seconds
I/wpa_supplicant( 1330): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  953): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  953): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  953): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor(  953): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  953): [1,452,261,087,232 ms] noteScanstart no scan source
E/WifiStateMachine(  953): handleMessage: X
,I/ActivityManager(  953): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6238 uid=10106 gids={50106, 9997, 3003, 1028, 1015} abi=arm64-v8a
,W/VideoCapabilities( 6206): Unsupported mime video/x-ms-wmv
,W/Utils   ( 6206): could not parse size range '64x64-1920X1080',
,W/AudioCapabilities( 6206): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6206): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6206): Unsupported mime audio/qcelp
,W/VideoCapabilities( 6206): Unsupported mime video/x-ms-wmv
,E/WifiStateMachine(  953): handleMessage: E msg.what=131155
E/WifiStateMachine(  953): processMsg: ConnectedState
,D/wpa_supplicant( 1330): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1330): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1330): nl80211: Scan included frequencies: 2412
D/wpa_supplicant( 1330): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1330): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1330): wlan0: Scan completed in 0.075676 seconds
D/wpa_supplicant( 1330): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1330): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1330): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1330): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
,I/wpa_supplicant( 1330): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1330): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1330): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1330): [NULL] a0:c5:62:7a:49:97 freq=5260 level=-82
I/wpa_supplicant( 1330): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-83
I/wpa_supplicant( 1330): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1330): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
D/wpa_supplicant( 1330): wlan0: BSS: Start scan result update 3
D/wpa_supplicant( 1330): BSS: last_scan_res_used=7/32
D/wpa_supplicant( 1330): wlan0: Scan-only results received
D/wpa_supplicant( 1330): wlan0: Radio work 'scan'@0x55c1e20680 done in 0.076727 seconds
E/WifiStateMachine(  953):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=13.9, 0.0, 0.0  rx=21.1 bcn=0 [on:0 tx:0 rx:0 period:75] from screen [on:0 period:562141260] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  953): processMsg: L2ConnectedState
E/WifiMonitor(  953): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  953): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  953):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=13.9, 0.0, 0.0  rx=21.1 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:562141261] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  953):  get link layer stats 0
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1330): environment dirty rate=0 [2][0][0]
E/WifiStateMachine(  953): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  953): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  953): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
,E/WifiStateMachine(  953): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=7.93 txretriesrate=0.00 rxrate=17.05 userTriggerdPenalty0
D/WIFI_ICON( 1232): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  953):  good link -> stuck count =0
D/StatusBar.NetworkController( 1232): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiStateMachine(  953):  badRSSI count0 lowRSSI count0 --> score 60
,E/WifiStateMachine(  953):  isHighRSSI       ---> score=65
W/ContextImpl(  953): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
E/WifiStateMachine(  953): handleMessage: X
E/WifiStateMachine(  953): handleMessage: E msg.what=147461
E/WifiStateMachine(  953): processMsg: ConnectedState
E/WifiStateMachine(  953):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 bcn=0
E/WifiStateMachine(  953): processMsg: L2ConnectedState
E/WifiStateMachine(  953):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 bcn=0
E/WifiStateMachine(  953): processMsg: ConnectModeState
E/WifiStateMachine(  953):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 bcn=0
E/WifiStateMachine(  953): processMsg: DriverStartedState
E/WifiStateMachine(  953):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 bcn=0
E/WifiStateMachine(  953): processMsg: SupplicantStartedState
E/WifiStateMachine(  953):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 bcn=0
D/WifiWatchdogStateMachine(  953): RSSI current: 3 new: -60, 3
D/WifiStateMachine(  953): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1330): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  953): [1,452,261,087,317 ms] noteScanEnd no scan source
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1330): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  953): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@211cb9ce sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  953): NG7005g c0:ff:d4:d3:aa:4a rssi=-47 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  953): NG700 c0:ff:d4:d3:aa:48 rssi=-60 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  953): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  953): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  953):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-60 freq=2412
E/WifiAutoJoinController (  953): UPC Wi-Free 06:7c:34:12:7f:81 rssi=-84 cap [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  953): UPC5999698 64:7c:34:12:7f:81 rssi=-85 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS] is not scored
E/WifiAutoJoinController (  953): 01ABC c2:ff:d4:d3:aa:48 rssi=-60 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  953): UPC503894600 a0:c5:62:7a:49:97 rssi=-82 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
,E/WifiAutoJoinController (  953): DIRECT-qjWorkCentre 3025 9e:93:4e:3e:ba:c5 rssi=-83 cap [WPA2-PSK-CCMP][WPS-AUTH][ESS][P2P] is not scored
E/WifiAutoJoinController (  953): ageScanResultsOut delay 40000 size 7 now 1452261087320
E/WifiAutoJoinController (  953): newSupplicantResults size=7 known=1 true
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1330): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  953): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
E/WifiAutoJoinController (  953): ssid=NG700
E/WifiAutoJoinController (  953): id=0
E/WifiAutoJoinController (  953): mode=station
E/WifiAutoJoinController (  953): pairwise_cipher=CCMP
E/WifiAutoJoinController (  953): group_cipher=CCMP
E/WifiAutoJoinController (  953): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  953): wpa_state=COMPLETED
E/WifiAutoJoinController (  953): ip_address=192.168.1.130
E/WifiAutoJoinController (  953): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  953): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  953): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  953): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController (  953): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-60,-127) num=(1,0)
E/WifiAutoJoinController (  953): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  953): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-60 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  953): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  953): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  953): Done attemptAutoJoin status=0
E/WifiConfigStore(  953):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  953): handleMessage: X
,I/VideoCapabilities( 6206): Unsupported profile 4 for video/mp4v-es,
,W/VideoCapabilities( 6206): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6206): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 6206): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 6206): Unrecognized profile 2130706433 for video/avc,
,W/ActivityManager(  953): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,I/vclib   ( 6206): onServiceConnected,
W/Babel   ( 6206): Attempted to change video mute state without an active call.
,W/ResourcesManager( 6206): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6206): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/Gmail   ( 6238): getAccountsCursor,
,W/GAV2    ( 6238): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,V/GLSActivity( 1986): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PackageManager(  953):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.AttachmentService, state=2, flag=1, pid=6238, uid=10106, userID:0
,W/ActivityManager(  953): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Gmail   ( 6238): Observing account changes for notifications
,W/ActivityManager(  953): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/PackageManager(  953):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=6238, uid=10106, userID:0
I/PackageManager(  953):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=6238, uid=10106, userID:0
,W/ActivityManager(  953): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 6238): Error finding the version of the Email provider.....
E/Gmail   ( 6238): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6238): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6238): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6238): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
,E/Gmail   ( 6238): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6238): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6238): 	at android.os.Looper.loop(Looper.java:155)
E/Gmail   ( 6238): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 6238): We do not support migrating this version of the Email provider.
,I/Gmail   ( 6238): getAccountsCursor,
,V/GLSActivity( 1986): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/GCM     ( 1986): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1986): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 4507): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,W/art     ( 6206): Suspending all threads took: 7.648ms
,I/PackageManager(  953):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4507, uid=10024, userID:0
,E/SQLiteLog( 6238): (283) recovered 924 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,E/MDM     ( 1842): [147] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/ActivityManager(  953): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=6285 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
D/LocationInitializer( 4507): Restart initialization of location,
,I/art     (  459): Explicit concurrent mark sweep GC freed 8671(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 256us total 18.058ms
,I/art     (  459): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 228us total 14.265ms,
,I/art     (  459): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 228us total 14.519ms,
,V/JNIHelp ( 6206): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ResourcesManager( 6285): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/Gmail   ( 6238): notifyAccountChanged,
D/CalendarApplication( 6285): onCreate
,I/Gmail   ( 6238): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/ProviderChangeReceiver( 6285): ---------------------------------------------------,
D/ProviderChangeReceiver( 6285): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
I/Gmail   ( 6238): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/ActivityManager(  953): Killing 5468:com.android.settings/1000 (adj 15): empty #17
,D/Process (  953): killProcessQuiet, pid=5468
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,D/HtcAlertService( 6285): start to updateAlertNotification!
,I/art     ( 1986): Explicit concurrent mark sweep GC freed 18464(1027KB) AllocSpace objects, 3(252KB) LOS objects, 49% free, 4MB/8MB, paused 1.187ms total 38.421ms,
I/art     (  953): Explicit concurrent mark sweep GC freed 14313(738KB) AllocSpace objects, 1(84KB) LOS objects, 33% free, 18MB/28MB, paused 2.215ms total 158.317ms
,I/Gmail   ( 6238): calculateUnknownSyncRationalesAndPurgeInBackground: running,
I/Gmail   ( 6238): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/System  ( 6206): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
I/ProviderInstaller( 6206): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  953): Recipient 5468
,V/AlarmManager(  953): sending alarm PendingIntent{2f17121e: PendingIntentRecord{358c0aff com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1452261087740, Int=0
,I/ActivityManager(  953): Start proc com.htc.bgp for content provider com.android.providers.calendar/com.htc.providers.calendar.HtcCalendarProvider: pid=6312 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,V/AlarmManager(  953): sending alarm PendingIntent{5276a50: PendingIntentRecord{3e0cd449 android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1452261080597, Int=20000
,V/GLSActivity( 1986): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Prism.ItemManager( 1604): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1604): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/Prism.AllAppsManager( 1604): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
D/AccTypeManager( 1757): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
W/SystemReader(  953): Cannot find grip_rejection_width, use default value instead
D/GCM     ( 1986): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/art     (  458): Explicit concurrent mark sweep GC freed 8646(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 340us total 45.861ms
,D/AccTypeManager( 1757): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/AuthorizationBluetoothService( 1986): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/ConfigService( 1986): onDestroy
,W/ResourcesManager(  953): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/art     (  458): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 163us total 25.130ms
V/GmsCoreStatsServiceLauncher( 4507): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/ActivityManager(  953): Killing 5761:com.google.android.gms:car/u0a24 (adj 15): empty #17
,D/Process (  953): killProcessQuiet, pid=5761
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.attachApplicationLocked:6650 
,D/AccTypeManager( 1757): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/PhoneApp( 1556): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/art     (  458): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 168us total 20.436ms
,E/ExternalAccountType( 1757): Unsupported attribute readOnly
,W/PackageManager(  953): Unable to load service info ResolveInfo{2b33fffb com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
W/PackageManager(  953): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  953): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  953): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  953): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  953): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  953): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  953): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  953): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  953): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  953): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  953): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  953): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  953): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  953): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  953): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  953): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/ActivityManager(  953): Recipient 5761,
,I/Gmail   ( 6238): getAccountsCursor
,W/ResourcesManager( 6312): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/PackageManager(  953):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4507, uid=10024, userID:0
,E/MDM     ( 1842): [148] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 4507): Restart initialization of location
,I/BackupManagerService(  953): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  953):  packet count Tx=172 Rx=253
,E/WifiTrafficPoller(  953): notifying of data activity 1
D/WIFI_ICON( 1232): WifiActivity: 1
D/StatusBar.NetworkController( 1232): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/PhoneInterfaceManager( 1556): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,W/VideoCapabilities( 6206): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6206): Unrecognized profile 2130706433 for video/avc
I/CalendarProvider2( 6312): Created com.android.providers.calendar.CalendarAlarmManager@18a2e2e4(com.htc.providers.calendar.HtcCalendarProvider@3ed4434d)
W/VideoCapabilities( 6206): Unrecognized profile 2130706433 for video/avc
,I/[PluginManager]RegisterService( 1643): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1643): handle notify Blinkfeed plugin client changed
,I/GCoreNlp( 1842): shouldConfirmNlp, NLP off. Ensuring opt-in disabled,
,I/ActivityManager(  953): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=6343 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/iu.UploadsManager( 4507): End new media; added: 0, uploading: 0, time: 355 ms
,D/CalendarProvider2( 6312): wait start:true
,D/CalendarProvider2( 6312): wait end:false
,D/PMS     (  953): acquireWL(35363303): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1842 10024 WorkSource{10024 com.google.android.gms},
D/LocationProviderProxy(  953): applying state to connected service
,D/PMS     (  953): releaseWL(35363303): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/HtcAlertService( 6285): No fired or scheduled alerts
,D/HtcAlertUtils( 6285): -- cancelReminderNotification --
,D/LocationProviderProxy(  953): applying state to connected service
,D/HtcAlertUtils( 6285): broadcastExistReminder!
,D/DotMatrix( 1342): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  953): releaseWL(6cfe358): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,V/GmsNetworkLocationProvi( 1842): DISABLE
,D/PMS     (  953): acquireWL(3c436cfe): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1842 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): acquireWL(3e5efc5f): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1842 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  953): releaseWL(3c436cfe): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): releaseWL(3e5efc5f): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
I/Gmail   ( 6238): master sync=false, engine sync=true
,I/NotifUtils( 6238): Validating Notification, mapSize: 0 getAttention: true ignoreUnobtrusive: false
,D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 6343): -onCreate()
,I/Gmail   ( 6238): getAccountsCursor
,V/GLSActivity( 1986): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/Gmail   ( 6238): master sync=false, engine sync=true
,V/Settings:HtcSettingsApplication( 6343): [6343/6343] onCreate(),
,I/NotifUtils( 6238): validateNotifications - cancelling 1729800001 for 61035162 / -317575340
,D/Settings:HtcWirelessFeatureFlags( 6343): id/is att sku: 118/false,
,D/Process (  953): killProcessQuiet, pid=5826
I/ActivityManager(  953): Killing 5826:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,E/Settings:HtcWrapHeaderInfo( 6343): no such activity!,
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 6343): The wrap header doesn't exist in header list.,
,E/Settings:HtcWrapHeaderInfo( 6343): updateDevelopment, bPrefShow = true,
,E/Settings:HtcUmcWidgetEnabler( 6343): isSupportMusicChannel(): false,
,I/ActivityManager(  953): Recipient 5826,
,D/PackageBroadcastService( 4507): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms,
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6343): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6343): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6343): [supportRecentAppsButton]support         :false
I/PackageBroadcastService( 4507): Null package name or gms related package.  Ignoreing.
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6343): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6343): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6343): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6343): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6343): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6343): [supportHomeButton]support         :false
,D/PMS     (  953): acquireWL(1cc65a29): PARTIAL_WAKE_LOCK  Icing 0x1 4507 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  953): acquireWL(14a311ae): PARTIAL_WAKE_LOCK  AsyncService 0x1 5874 10167 null
D/PMS     (  953): releaseWL(14a311ae): PARTIAL_WAKE_LOCK  AsyncService 0x1 null,
,I/Icing   ( 4507): updateResources: need to parse f{com.google.android.gms}
D/PMS     (  953): acquireWL(2f7d02dc): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 5874 10167 null
I/GLSUser ( 1986): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1986): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1986): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1986): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/PMS     (  953): releaseWL(2f7d02dc): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,V/GLSActivity( 1986): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/UpdateIcingCorporaServi( 5906): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  953): Cannot resolve ContentProvider=com.htc.vowifi
,D/PMS     (  953): acquireWL(37bfa886): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 5614 10159 null
,E/Settings:HtcVoWifiWidgetEnabler( 6343): isSupportVoWifi: null
E/ActivityThread( 6343): Failed to find provider info for com.htc.vowifi
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 6343): The wrap header doesn't exist in header list.
D/PMS     (  953): releaseWL(1cc65a29): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
E/Settings:HtcWrapHeaderInfo( 6343): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 6343): isSupportMusicChannel(): false
E/Babel   ( 6206): UserRecoverableAuthException.
E/Babel   ( 6206): eei: BadAuthentication
E/Babel   ( 6206): 	at eeg.a(Unknown Source)
E/Babel   ( 6206): 	at eeg.a(Unknown Source)
E/Babel   ( 6206): 	at eeg.a(Unknown Source)
E/Babel   ( 6206): 	at g.a(Unknown Source)
E/Babel   ( 6206): 	at cae.a(SourceFile:3089)
E/Babel   ( 6206): 	at cae.a(SourceFile:1131)
E/Babel   ( 6206): 	at cws.a(SourceFile:4333)
E/Babel   ( 6206): 	at cws.a(SourceFile:1419)
E/Babel   ( 6206): 	at crl.a(SourceFile:492)
E/Babel   ( 6206): 	at crl.a(SourceFile:1468)
E/Babel   ( 6206): 	at cqu.a(SourceFile:4416)
E/Babel   ( 6206): 	at cas.b(SourceFile:106)
E/Babel   ( 6206): 	at cap.d(SourceFile:335)
E/Babel   ( 6206): 	at caq.run(SourceFile:81)
E/Babel   ( 6206): Error getting auth token
E/Babel   ( 6206): dvm
E/Babel   ( 6206): 	at g.a(Unknown Source)
E/Babel   ( 6206): 	at cae.a(SourceFile:3089)
E/Babel   ( 6206): 	at cae.a(SourceFile:1131)
E/Babel   ( 6206): 	at cws.a(SourceFile:4333)
E/Babel   ( 6206): 	at cws.a(SourceFile:1419)
E/Babel   ( 6206): 	at crl.a(SourceFile:492)
E/Babel   ( 6206): 	at crl.a(SourceFile:1468)
E/Babel   ( 6206): 	at cqu.a(SourceFile:4416)
E/Babel   ( 6206): 	at cas.b(SourceFile:106)
E/Babel   ( 6206): 	at cap.d(SourceFile:335)
E/Babel   ( 6206): 	at caq.run(SourceFile:81)
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6343): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6343): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6343): [supportRecentAppsButton]support         :false
E/Babel   ( 6206): Account registration failed 1-Redacted-21
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6343): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6343): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6343): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6343): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6343): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6343): [supportHomeButton]support         :false,
E/Babel   ( 6206): cyp: null -- null
E/Babel   ( 6206): 	at cae.a(SourceFile:3121)
E/Babel   ( 6206): 	at cae.a(SourceFile:1131)
E/Babel   ( 6206): 	at cws.a(SourceFile:4333)
E/Babel   ( 6206): 	at cws.a(SourceFile:1419)
E/Babel   ( 6206): 	at crl.a(SourceFile:492)
E/Babel   ( 6206): 	at crl.a(SourceFile:1468)
E/Babel   ( 6206): 	at cqu.a(SourceFile:4416)
E/Babel   ( 6206): 	at cas.b(SourceFile:106)
E/Babel   ( 6206): 	at cap.d(SourceFile:335)
E/Babel   ( 6206): 	at caq.run(SourceFile:81)
,E/Settings:HtcVoWifiWidgetEnabler( 6343): isSupportVoWifi: null
,I/ActivityManager(  953): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 6343): Failed to find provider info for com.htc.vowifi
,D/libc    ( 6206): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 6206): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 6206): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 6206): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6206): [NET] android_getaddrinfo_proxy+
D/libc    ( 6206): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  400): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  400): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  400): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6206): [NET] android_getaddrinfo_proxy-, success
,I/art     ( 6206): Note: end time exceeds epoch: 
,I/PackageManager(  953):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=5614, uid=10159, userID:0,
I/UpdateIcingCorporaServi( 5906): UpdateCorporaTask done [took 88 ms] updated apps [took 88 ms] ,
D/PMS     (  953): releaseWL(37bfa886): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,I/MusicLeanback( 5614): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 5614): Stop autocaching.
,I/GLSUser ( 1986): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1986): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1986): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1986): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1986): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Babel   ( 6206): connection state changed from UNKNOWN to CONNECTED,
V/SetupWizard( 6157): Connected to Gservices successfully
,W/ResourcesManager( 1986): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/ChimeraCfgMgr( 4507): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 4507): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/GCM     ( 1986): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE,
E/GmsUtils( 5614): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 5614): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/DFPI.PIReciver( 5953): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/DFPI.ApkInstallService( 5953): onHandleIntent
,I/DFPI.ApkInstallService( 5953): Media Scan Finished Case 
E/Babel   ( 6206): Unexpected exception while authenticating.
E/Babel   ( 6206): eej: User intervention required. Notification has been pushed.
E/Babel   ( 6206): 	at eeg.b(Unknown Source)
E/Babel   ( 6206): 	at eeg.b(Unknown Source)
E/Babel   ( 6206): 	at g.a(Unknown Source)
E/Babel   ( 6206): 	at cae.b(SourceFile:1146)
E/Babel   ( 6206): 	at dcg.run(SourceFile:5617)
E/Babel   ( 6206): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 6206): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 6206): 	at java.lang.Thread.run(Thread.java:818)
,D/DFPI.ApkInstallService( 5953): check CID = HTC__102
I/DFPI.ApkInstallService( 5953): There is no Demo.apk in sd card or phone storage
,D/DotMatrix( 1342): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1342): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1232): reapply : com.google.android.gms 2 40
,I/SoundPicker( 6030): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
I/SoundPicker( 6030): SoundPickerReceiver [onReceive] startService
,I/GLSUser ( 1986): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm,
I/GLSUser ( 1986): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1986): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1986): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
I/SoundPicker( 6030): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
,V/SoundPicker( 6030): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 6030): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
,V/GLSActivity( 1986): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
,I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 6030): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/art     (  953): Explicit concurrent mark sweep GC freed 20426(1075KB) AllocSpace objects, 1(84KB) LOS objects, 33% free, 18MB/28MB, paused 1.541ms total 132.606ms
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac,
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
D/DFPI.PIReciver( 5953): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
I/DFPI.ApkInstallService( 5953): onHandleIntent
I/DFPI.ApkInstallService( 5953): Media Scan Finished Case 
D/DFPI.ApkInstallService( 5953): check CID = HTC__102,
I/DFPI.ApkInstallService( 5953): There is no Demo.apk in sd card or phone storage,
W/Kids    ( 4507): [AccountUtils] Account not ready
W/Kids    ( 4507): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4507): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4507): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4507): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4507): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4507): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4507): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4507): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4507): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4507): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4507): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4507): 	at java.lang.Thread.run(Thread.java:818)
D/DotMatrix( 1342): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1342): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 6030): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/RemoteViews( 1232): reapply : com.google.android.gms 2 40
,I/SoundPicker( 6030): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,D/DFPI.PIReciver( 5953): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/DFPI.ApkInstallService( 5953): onHandleIntent
,I/DFPI.ApkInstallService( 5953): Media Scan Finished Case 
D/DFPI.ApkInstallService( 5953): check CID = HTC__102
I/DFPI.ApkInstallService( 5953): There is no Demo.apk in sd card or phone storage
,I/SoundPicker( 6030): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 6030): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  953):  packet count Tx=176 Rx=256
,E/WifiTrafficPoller(  953): notifying of data activity 3
D/WIFI_ICON( 1232): WifiActivity: 3
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
D/StatusBar.NetworkController( 1232): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/MediaStoreImporter( 5614): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,D/PMS     (  953): acquireWL(236e19d4): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 953 1000 null
,D/PMS     (  953): acquireWL(2fb7c77d): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 953 1000 null
,D/PMS     (  953): releaseWL(236e19d4): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,I/WSP     ( 1643): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
,D/PMS     (  953): releaseWL(2fb7c77d): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/WeatherUtility( 1643): Weather sync is On
D/GCM     ( 1986): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1986): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 4507): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/WSP     ( 1643): [Receiver] next auto-sync alarm event is 60 mins later, at time: Fri Jan 08 15:51:29 CET 2016
,I/art     ( 6030): Explicit concurrent mark sweep GC freed 13442(844KB) AllocSpace objects, 2(40KB) LOS objects, 87% free, 305KB/2MB, paused 541us total 37.254ms
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac,
,I/PackageManager(  953):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4507, uid=10024, userID:0
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,E/MDM     ( 1842): [150] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,D/LocationInitializer( 4507): Restart initialization of location
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac,
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/GCM     ( 1986): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/SoundPicker( 6030): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 6030): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 6030): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
,D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 6030): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,D/AuthorizationBluetoothService( 1986): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
V/GmsCoreStatsServiceLauncher( 4507): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/CalendarProvider2( 6312): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac,
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122,
W/ContentResolver( 6312): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/MediaStoreImporter( 5614): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/PackageManager(  953):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4507, uid=10024, userID:0
,E/MDM     ( 1842): [126] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 2)
,D/LocationInitializer( 4507): Restart initialization of location
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac,
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac,
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8,
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 6030): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 6030): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_cdma)
,I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
,W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
,D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 6030): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 6030): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/MediaStoreImporter( 5614): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 6030): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac,
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 6030): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,D/PMS     (  953): acquireWL(3ed2cf6c): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 5614 10159 null
,I/PackageManager(  953):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=5614, uid=10159, userID:0,
,D/PMS     (  953): releaseWL(3ed2cf6c): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,I/MusicLeanback( 5614): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 5614): Stop autocaching.
,I/art     ( 3893): Explicit concurrent mark sweep GC freed 4727(261KB) AllocSpace objects, 0(0B) LOS objects, 72% free, 1515KB/5MB, paused 670us total 25.225ms
,I/Task_Calendar( 5928): Set ICALENDAR_UID to sync_data7 due to SDK_INT is 21
I/ActivityManager(  953): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=6417 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a
,I/SoundPicker( 6030): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac,
I/SoundPicker( 6030): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/TodoTaskshortcut( 5928): update TASK shortcut>
,E/GmsUtils( 5614): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 5614): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/Process (  953): killProcessQuiet, pid=5976
I/ActivityManager(  953): Killing 5976:com.htc.android.mail:sync/u0a62 (adj 15): empty #17
,D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/Prism.ItemManager( 1604): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1604): loadItems() com.htc.launcher.pageview.WidgetManager@11dbeab4 +
I/Prism.WidgetManager( 1604): onLoadItems() +
,I/ActivityManager(  953): Recipient 5976
D/WifiService(  953): Client connection lost with reason: 4
,E/Prism.WidgetManager( 1604): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1604): onLoadItems() -
I/Prism.ItemManager( 1604): loadItems() com.htc.launcher.pageview.WidgetManager@11dbeab4 -
,D/SyncApplication( 6417): Loading default preferences
,W/Resources( 6417): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a},
,D/WifiService(  953): New client listening to asynchronous messages,
E/WifiTrafficPoller(  953): ADD_CLIENT: 7
,D/SyncApplication( 6417): Overriding preferences with custom values,
,D/SyncApplication( 6417): Updating preferences succeeded
,E/SyncApplication( 6417): Application created.,
,W/VolumeInfo( 6417): Unable to read mount points,
W/VolumeInfo( 6417): java.io.FileNotFoundException: /etc/vold.fstab: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 6417): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/VolumeInfo( 6417): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/VolumeInfo( 6417): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/VolumeInfo( 6417): 	at java.io.FileReader.<init>(FileReader.java:66)
W/VolumeInfo( 6417): 	at com.nero.android.common.VolumeInfo.getVolumeMountPoints(VolumeInfo.java:194)
W/VolumeInfo( 6417): 	at com.nero.android.common.VolumeInfo.getVolumes(VolumeInfo.java:153)
W/VolumeInfo( 6417): 	at com.nero.android.common.VolumeInfo.initializeVolumeIDs(VolumeInfo.java:474)
W/VolumeInfo( 6417): 	,at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:51)
W/VolumeInfo( 6417): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:1)
W/VolumeInfo( 6417): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/VolumeInfo( 6417): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/VolumeInfo( 6417): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/VolumeInfo( 6417): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/VolumeInfo( 6417): 	at java.lang.Thread.run(Thread.java:818)
W/VolumeInfo( 6417): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 6417): 	at libcore.io.Posix.open(Native Method)
W/VolumeInfo( 6417): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/VolumeInfo( 6417): 	at libcore.io.IoBridge.open(IoBridge.java:442)
,W/VolumeInfo( 6417): 	... 13 more
V/VolumeInfo( 6417): Found 0 mount point(s)
V/VolumeInfo( 6417): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
I/CalendarDefines( 6417): getNewCalendarAuthority()...
,I/PackageManager(  953):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=6417, uid=10005, userID:0,
W/PackageManager(  953): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
D/SyncApplication( 6417): enableAppOperation()+,
I/PackageManager(  953):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=6417, uid=10005, userID:0
,W/PackageManager(  953): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/VolumeInfo( 6417): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
D/SyncApplication( 6417): enableAppOperation()-
,D/HTCUtilities( 6417): isNeorSinged() + ,
,D/HTCUtilities( 6417): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 6417): isNeorSinged() return false
,D/VolumeInfo( 6417): Read the volume-id from the sd card: {9B5E872B-8520-47C6-8BD3-3081C2E38355}
,W/VolumeInfo( 6417): Can not create volume ID for unmounted volume null
,D/CDMountReceiver( 6417): whether to enable CD Auto-mount: true,
D/CDMountReceiver( 6417): showNotification() contentText=If HTC Sync Manager setup doesn't start automatically on your computer, download it from www.htc.com/hsm
,I/ActionCombine( 6417): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal],
,D/CDMountReceiver( 6417): enable CD Auto-mount: true,
,D/DotMatrix( 1342): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
D/HTCUtilities( 6417): enable auto-mount
D/VoldConnector(  953): SND -> {29 mountISO mount /system/etc/PCTOOL.ISO /sys/class/android_usb/f_mass_storage/lun0/file}
I/HtcMountManagerAdapter( 6417): mHtcMountManager is  null
D/VoldConnector(  953): SND -> {30 mountISO mount /system/etc/PCTOOL.ISO /sys/class/android_usb/f_mass_storage/lun0/file}
I/HtcMountManagerAdapter( 6417): mStorageManager is  not null
D/HTCUtilities( 6417): enable auto-mount
I/HtcMountManagerAdapter( 6417): mHtcMountManager is  null,
I/HtcMountManagerAdapter( 6417): mStorageManager is  not null
D/MountService(  953): mountISO: /system/etc/PCTOOL.ISO
D/MountService(  953): mountISO: /system/etc/PCTOOL.ISO
,D/GCM     ( 1986): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  953): Killing 6066:com.htc.updater/u0a84 (adj 15): empty #17
,D/Process (  953): killProcessQuiet, pid=6066
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/RemoteViews( 1232): apply : com.nero.android.htc.sync 0 16 5 38,
,I/RemoteViews( 1232): apply : com.nero.android.htc.sync 0 13 3 53,
,I/ActivityManager(  953): Recipient 6066,
,D/PhoneApp( 1556): EVENT_QUERY_MO_PACKAGES,
D/PhoneApp( 1556): -- N1 =0
D/PhoneApp( 1556): -- N2 =0
D/PhoneApp( 1556): -- N3 =0
,D/ChimeraCfgMgr( 4507): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 4507): Loading module com.google.android.gms.kids from APK com.google.android.gms
,E/WifiStateMachine(  953): WiFiStateMachine SCAN ALARM
,D/WifiDisplayAdapter(  953): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  953):     Client/Owner: Client
D/WifiDisplayAdapter(  953):     GroupId: 
D/WifiDisplayAdapter(  953):     Passphrase: 
D/WifiDisplayAdapter(  953):     SessionId: 0
D/WifiDisplayAdapter(  953):     IP Address: }
E/WifiStateMachine(  953): handleMessage: E msg.what=131143
E/WifiStateMachine(  953): processMsg: ConnectedState
E/WifiStateMachine(  953):  ConnectedState !CMD_START_SCAN -2 -2 ic=3 proc(ms):1 dur:85 rssi=-60 f=2412 sc=60 link=72 tx=7.9, 0.0, 0.0  rx=17.0 list=2412 [on:0 tx:0 rx:0 period:2838] from screen [on:0 period:562144104]
E/WifiStateMachine(  953): processMsg: L2ConnectedState
D/PMS     (  953): releaseWL(35f240a2): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  953):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=3 proc(ms):2 dur:85 rssi=-60 f=2412 sc=60 link=72 tx=7.9, 0.0, 0.0  rx=17.0 list=2412 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:562144105]
E/WifiStateMachine(  953): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=7.93 rxSuccessRate=17.05 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-60
E/WifiStateMachine(  953): WifiStateMachine CMD_START_SCAN with age=41242 interval=60000 maxinterval=300000
E/WifiStateMachine(  953): WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
E/WifiStateMachine(  953): WifiStateMachine CMD_START_SCAN full=false
E/WifiConfigStore(  953): makeChannelList age=3600000 for "NG700"WPA_PSK max=6 bssids=1
E/WifiConfigStore(  953): has c0:ff:d4:d3:aa:48 freq=2412 age=2834 ?=true
E/WifiStateMachine(  953): WifiStateMachine starting scan for "NG700"WPA_PSK with 2412
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY freq=2412"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SCAN TYPE=ONLY freq=2412'
,D/wpa_supplicant( 1330): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1330): wpa_supplicant_scan enter
D/wpa_supplicant( 1330): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1330): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1330): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1330): WPS:  * Request Type
D/wpa_supplicant( 1330): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1330): WPS:  * UUID-E
D/wpa_supplicant( 1330): WPS:  * Primary Device Type
D/wpa_supplicant( 1330): WPS:  * RF Bands (3)
D/wpa_supplicant( 1330): WPS:  * Association State
D/wpa_supplicant( 1330): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1330): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1330): WPS:  * Manufacturer
D/PMS     (  953): acquireWL(2d2c85d): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 6206 10112 null
D/wpa_supplicant( 1330): WPS:  * Model Name
,D/wpa_supplicant( 1330): WPS:  * Model Number
D/wpa_supplicant( 1330): WPS:  * Device Name
D/wpa_supplicant( 1330): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1330): P2P: * P2P IE header
D/wpa_supplicant( 1330): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1330): P2P: * Listen Channel: Regulatory Class 81 Channel 1
D/wpa_supplicant( 1330): wlan0: Limit manual scan to specified channels
D/wpa_supplicant( 1330): wlan0: Add radio work 'scan'@0x55c1e20680
D/wpa_supplicant( 1330): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1330): wlan0: Starting radio work 'scan'@0x55c1e20680 after 0.000042 second wait
D/wpa_supplicant( 1330): wlan0: nl80211: scan request
D/wpa_supplicant( 1330): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1330): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1330): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1330): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1330): wlan0: Own scan request started a scan in 0.000095 seconds
I/wpa_supplicant( 1330): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  953): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiStateMachine(  953): [1,452,261,090,155 ms] noteScanstart no scan source
E/WifiMonitor(  953): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  953): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor(  953): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  953): handleMessage: X
,I/GLSUser ( 1986): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1986): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
D/PMS     (  953): releaseWL(2d2c85d): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
I/GLSUser ( 1986): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1986): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/[PluginManager]RegisterService( 1643): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1643): handle notify Blinkfeed plugin client changed
V/GLSActivity( 1986): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  953):  packet count Tx=176 Rx=259
D/WIFI_ICON( 1232): WifiActivity: 1
E/WifiTrafficPoller(  953): notifying of data activity 1
D/StatusBar.NetworkController( 1232): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PackageBroadcastService( 4507): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms,
,I/PackageBroadcastService( 4507): Null package name or gms related package.  Ignoreing.
D/wpa_supplicant( 1330): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1330): wlan0: nl80211: New scan results available,
D/wpa_supplicant( 1330): nl80211: Scan included frequencies: 2412
D/wpa_supplicant( 1330): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1330): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1330): wlan0: Scan completed in 0.084769 seconds
W/ContextImpl(  953): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
D/wpa_supplicant( 1330): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1330): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1330): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1330): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1330): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1330): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1330): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-60
,I/wpa_supplicant( 1330): [NULL] a0:c5:62:7a:49:97 freq=5260 level=-82
I/wpa_supplicant( 1330): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-83
I/wpa_supplicant( 1330): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1330): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
D/wpa_supplicant( 1330): wlan0: BSS: Start scan result update 4
D/wpa_supplicant( 1330): BSS: last_scan_res_used=7/32
D/wpa_supplicant( 1330): wlan0: Scan-only results received
D/wpa_supplicant( 1330): wlan0: Radio work 'scan'@0x55c1e20680 done in 0.086518 seconds
E/WifiMonitor(  953): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS ,
E/WifiMonitor(  953): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  953): handleMessage: E msg.what=147461
E/WifiStateMachine(  953): processMsg: ConnectedState
E/WifiStateMachine(  953):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 bcn=0
E/WifiStateMachine(  953): processMsg: L2ConnectedState
E/WifiStateMachine(  953):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 bcn=0
E/WifiStateMachine(  953): processMsg: ConnectModeState
E/WifiStateMachine(  953):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 bcn=0
E/WifiStateMachine(  953): processMsg: DriverStartedState
E/WifiStateMachine(  953):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 bcn=0
E/WifiStateMachine(  953): processMsg: SupplicantStartedState
E/WifiStateMachine(  953):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 bcn=0
D/WifiStateMachine(  953): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1330): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  953): [1,452,261,090,250 ms] noteScanEnd no scan source
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1330): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
,E/WifiStateMachine(  953): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@211cb9ce sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  953): NG7005g c0:ff:d4:d3:aa:4a rssi=-47 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  953): NG700 c0:ff:d4:d3:aa:48 rssi=-60 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  953): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  953): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  953):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-60 freq=2412
E/WifiAutoJoinController (  953): UPC Wi-Free 06:7c:34:12:7f:81 rssi=-84 cap [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  953): UPC5999698 64:7c:34:12:7f:81 rssi=-85 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS] is not scored
E/WifiAutoJoinController (  953): 01ABC c2:ff:d4:d3:aa:48 rssi=-60 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  953): UPC503894600 a0:c5:62:7a:49:97 rssi=-82 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  953): DIRECT-qjWorkCentre 3025 9e:93:4e:3e:ba:c5 rssi=-83 cap [WPA2-PSK-CCMP][WPS-AUTH][ESS][P2P] is not scored
E/WifiAutoJoinController (  953): ageScanResultsOut delay 40000 size 7 now 1452261090256
E/WifiAutoJoinController (  953): newSupplicantResults size=7 known=1 true
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1330): wlan0: Control interface command 'STATUS-NO_EVENTS'
D/PMS     (  953): acquireWL(c1d8e91): PARTIAL_WAKE_LOCK  Icing 0x1 4507 10024 WorkSource{10024 com.google.android.gms}
E/WifiAutoJoinController (  953): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
E/WifiAutoJoinController (  953): ssid=NG700
E/WifiAutoJoinController (  953): id=0
E/WifiAutoJoinController (  953): mode=station
E/WifiAutoJoinController (  953): pairwise_cipher=CCMP
E/WifiAutoJoinController (  953): group_cipher=CCMP
E/WifiAutoJoinController (  953): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  953): wpa_state=COMPLETED
E/WifiAutoJoinController (  953): ip_address=192.168.1.130
E/WifiAutoJoinController (  953): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  953): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  953): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  953): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController (  953): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-60,-127) num=(1,0)
E/WifiAutoJoinController (  953): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  953): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-60 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  953): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  953): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  953): Done attemptAutoJoin status=0
E/WifiConfigStore(  953):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  953): handleMessage: X
,D/PMS     (  953): acquireWL(3f2c11f6): PARTIAL_WAKE_LOCK  AsyncService 0x1 5874 10167 null
,D/PMS     (  953): releaseWL(3f2c11f6): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/Icing   ( 4507): updateResources: need to parse f{com.google.android.gms}
,D/DotMatrix( 1342): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/PMS     (  953): acquireWL(9697064): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 5874 10167 null
D/DotMatrix( 1342): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/Kids    ( 4507): [AccountUtils] Account not ready
W/Kids    ( 4507): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
,W/Kids    ( 4507): ,	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4507): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4507): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4507): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4507): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4507): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4507): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4507): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4507): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4507): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4507): 	at java.lang.Thread.run(Thread.java:818)
I/RemoteViews( 1232): reapply : com.google.android.gms 4 40
,I/UpdateIcingCorporaServi( 5906): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PMS     (  953): releaseWL(9697064): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,D/ProviderChangeReceiver( 6285): ---------------------------------------------------
D/ProviderChangeReceiver( 6285): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,D/HtcAlertService( 6285): start to updateAlertNotification!
,D/PMS     (  953): releaseWL(c1d8e91): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
E/WifiStateMachine(  953): handleMessage: E msg.what=131155
E/WifiStateMachine(  953): processMsg: ConnectedState
E/WifiStateMachine(  953):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=7.9, 0.0, 0.0  rx=17.0 bcn=0 [on:0 tx:0 rx:0 period:159] from screen [on:0 period:562144266] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  953): processMsg: L2ConnectedState
,E/WifiStateMachine(  953):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=7.9, 0.0, 0.0  rx=17.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:562144268] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  953):  get link layer stats 0
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SIGNAL_POLL'
,D/HtcAlertService( 6285): No fired or scheduled alerts
D/HtcAlertUtils( 6285): -- cancelReminderNotification --
D/HtcAlertUtils( 6285): broadcastExistReminder!
,I/wpa_supplicant( 1330): environment dirty rate=0 [4][0][0]
D/DotMatrix( 1342): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
E/WifiStateMachine(  953): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  953): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  953): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-60 "NG700"WPA_PSK
E/WifiStateMachine(  953): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=5.97 txretriesrate=0.00 rxrate=12.02 userTriggerdPenalty0
E/WifiStateMachine(  953):  good link -> stuck count =0
E/WifiStateMachine(  953):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  953):  isHighRSSI       ---> score=65
E/WifiStateMachine(  953): handleMessage: X
D/WifiWatchdogStateMachine(  953): RSSI current: 3 new: -60, 3
,D/WIFI_ICON( 1232): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1232): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/UpdateIcingCorporaServi( 5906): UpdateCorporaTask done [took 67 ms] updated apps [took 67 ms] ,
,E/WifiDataStallTracker(  953): DATA_MONITOR_POLL true Token 1
,D/WifiDataStallTracker(  953): updateDataStallInfo: mDataStallTxRxSum={txSum=157 rxSum=154} preTxRxSum={txSum=151 rxSum=150}
D/WifiDataStallTracker(  953): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  953): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  953):  packet count Tx=176 Rx=261
,I/HtcModeClient( 3238): handler message = 4011,
E/HtcModeClient( 3238): Check connection and retry 8 times.
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  953):  packet count Tx=176 Rx=262
,I/GAV2    ( 6238): Thread[GAThread,5,main]: No campaign data found.
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  953):  packet count Tx=176 Rx=265
,E/WifiStateMachine(  953): handleMessage: E msg.what=131155,
E/WifiStateMachine(  953): processMsg: ConnectedState
E/WifiStateMachine(  953):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=6.0, 0.0, 0.0  rx=12.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:562147289] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  953): processMsg: L2ConnectedState
E/WifiStateMachine(  953):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=6.0, 0.0, 0.0  rx=12.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:562147290] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  953):  get link layer stats 0,
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1330): environment dirty rate=0 [0][0][0]
,D/WIFI_ICON( 1232): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  953): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
D/StatusBar.NetworkController( 1232): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiStateMachine(  953): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  953): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-60 "NG700"WPA_PSK
E/WifiStateMachine(  953): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=2.98 txretriesrate=0.00 rxrate=9.01 userTriggerdPenalty0
E/WifiStateMachine(  953):  good link -> stuck count =0,
E/WifiStateMachine(  953):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  953):  isHighRSSI       ---> score=61
E/WifiStateMachine(  953): handleMessage: X
D/WifiWatchdogStateMachine(  953): RSSI current: 3 new: -60, 3
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  953):  packet count Tx=176 Rx=266
,D/Process (  953): killProcessQuiet, pid=6107,
I/ActivityManager(  953): Killing 6107:com.htc.task.gtask/u0a66 (adj 15): empty #17
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  953): Recipient 6107,
,D/Process (  953): killProcessQuiet, pid=6183
I/ActivityManager(  953): Killing 6183:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  953): Recipient 6183
,D/AutomaticBrightnessController(  953): setAmbientLux to darker = 90.0
D/HABCtrl (  953): lsvalue=160(3th)->90(2th), lValue=90->64
,D/Process (  953): killProcessQuiet, pid=5383
I/ActivityManager(  953): Killing 5383:com.htc.sense.mms/u0a64 (adj 15): empty #17
,D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  953):  packet count Tx=176 Rx=268
,I/ActivityManager(  953): Recipient 5383,
,E/WifiDataStallTracker(  953): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  953): updateDataStallInfo: mDataStallTxRxSum={txSum=157 rxSum=154} preTxRxSum={txSum=157 rxSum=154}
D/WifiDataStallTracker(  953): updateDataStallInfo: NONE
D/WifiDataStallTracker(  953): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,W/Atfwd_Sendcmd(  475): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  953):  packet count Tx=176 Rx=271
,E/WifiStateMachine(  953): handleMessage: E msg.what=131155
E/WifiStateMachine(  953): processMsg: ConnectedState
E/WifiStateMachine(  953):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=3.0, 0.0, 0.0  rx=9.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:562150312] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine(  953): processMsg: L2ConnectedState
E/WifiStateMachine(  953):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=3.0, 0.0, 0.0  rx=9.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:562150313] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  953):  get link layer stats 0
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1330): environment dirty rate=0 [0][0][0],
E/WifiStateMachine(  953): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  953): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  953): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
E/WifiStateMachine(  953): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=1.49 txretriesrate=0.00 rxrate=7.51 userTriggerdPenalty0
D/WIFI_ICON( 1232): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  953):  good link -> stuck count =0
D/StatusBar.NetworkController( 1232): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiStateMachine(  953):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  953):  isHighRSSI       ---> score=61
E/WifiStateMachine(  953): handleMessage: X
D/WifiWatchdogStateMachine(  953): RSSI current: 3 new: -60, 3
,D/PMS     (  953): acquireWL(cf69ce): PARTIAL_WAKE_LOCK  *alarm* 0x1 953 1000 WorkSource{1000}
V/AlarmManager(  953): sending alarm PendingIntent{2de100ef: PendingIntentRecord{3ef067fc android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=85171, Int=0
D/PMS     (  953): releaseWL(cf69ce): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,I/HtcModeClient( 3238): handler message = 4011,
E/HtcModeClient( 3238): Check connection and retry 9 times.
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7
D/WIFI_ICON( 1232): WifiActivity: 0
E/WifiTrafficPoller(  953):  packet count Tx=176 Rx=271
E/WifiTrafficPoller(  953): notifying of data activity 0
D/StatusBar.NetworkController( 1232): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  953): acquireWL(87c54da): PARTIAL_WAKE_LOCK  *alarm* 0x1 953 1000 WorkSource{10072}
V/AlarmManager(  953): sending alarm PendingIntent{3966bd0b: PendingIntentRecord{3fda07e8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452261098206, Int=0
D/PMS     (  953): releaseWL(87c54da): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10072}
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  953):  packet count Tx=176 Rx=271
,D/Finsky  ( 5720): [562] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
,D/Finsky  ( 5720): [1] 5.onFinished: Installation state replication succeeded.
,E/WifiStateMachine(  953): handleMessage: E msg.what=131326
E/WifiStateMachine(  953): processMsg: ConnectedState,
E/WifiStateMachine(  953):  ConnectedState !what:131326 1 0
E/WifiStateMachine(  953): processMsg: L2ConnectedState
E/WifiStateMachine(  953):  L2ConnectedState !what:131326 1 0
E/WifiStateMachine(  953): handleMessage: X
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7,
D/WIFI_ICON( 1232): WifiActivity: 1
E/WifiTrafficPoller(  953):  packet count Tx=176 Rx=272
D/StatusBar.NetworkController( 1232): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  953): notifying of data activity 1
,E/WifiStateMachine(  953): handleMessage: E msg.what=131155,
E/WifiStateMachine(  953): processMsg: ConnectedState
E/WifiStateMachine(  953):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=7.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:562153331] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  953): processMsg: L2ConnectedState
E/WifiStateMachine(  953):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=7.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:562153332] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  953):  get link layer stats 0
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1330): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  953): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  953): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
,E/WifiConfigStore(  953): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
,E/WifiStateMachine(  953): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.75 txretriesrate=0.00 rxrate=4.25 userTriggerdPenalty0
D/WIFI_ICON( 1232): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  953):  good link -> stuck count =0
D/StatusBar.NetworkController( 1232): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiStateMachine(  953):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  953):  isHighRSSI       ---> score=61
E/WifiStateMachine(  953): handleMessage: X
D/WifiWatchdogStateMachine(  953): RSSI current: 3 new: -60, 3
,I/ActivityManager(  953): Waited long enough for: ServiceRecord{382acdb4 u0 com.htc.album/com.htc.mediamanager.providers.media.MMPScanService}
,I/art     (  953): Explicit concurrent mark sweep GC freed 27489(1379KB) AllocSpace objects, 3(188KB) LOS objects, 33% free, 18MB/28MB, paused 1.492ms total 156.194ms,
I/ActivityManager(  953): Waited long enough for: ServiceRecord{13ec3ad9 u0 com.htc.musicenhancer/.EnhancerService},
,W/MediaManager( 5577): [DualLensScanUtil],	mmpCursor count is 0
,D/Process (  953): killProcessQuiet, pid=5953
I/ActivityManager(  953): Killing 5953:com.htc.demoflopackageinstaller/u0a16 (adj 15): empty #17
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  953): Recipient 5953
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  953):  packet count Tx=176 Rx=273
,E/WifiDataStallTracker(  953): DATA_MONITOR_POLL true Token 1
D/ContactMessageStore( 1556): MSG_NOTIFY_CS_TO_SYNC >>
D/ContactMessageStore( 1556): MSG_NOTIFY_CS_TO_SYNC <<
,D/WifiDataStallTracker(  953): updateDataStallInfo: mDataStallTxRxSum={txSum=157 rxSum=154} preTxRxSum={txSum=157 rxSum=154},
D/WifiDataStallTracker(  953): updateDataStallInfo: NONE
D/WifiDataStallTracker(  953): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7,
D/WIFI_ICON( 1232): WifiActivity: 0
E/WifiTrafficPoller(  953):  packet count Tx=176 Rx=273
D/StatusBar.NetworkController( 1232): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  953): notifying of data activity 0
,I/HtcModeClient( 3238): handler message = 4011,
E/HtcModeClient( 3238): Check connection and retry 10 times.
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  953):  packet count Tx=176 Rx=274
,E/WifiTrafficPoller(  953): notifying of data activity 1
D/WIFI_ICON( 1232): WifiActivity: 1
D/StatusBar.NetworkController( 1232): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/WifiStateMachine(  953): handleMessage: E msg.what=131155,
E/WifiStateMachine(  953): processMsg: ConnectedState
E/WifiStateMachine(  953):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=4.3 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:562156353] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  953): processMsg: L2ConnectedState
E/WifiStateMachine(  953):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=4.3 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:562156354] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  953):  get link layer stats 0
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1330): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  953): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
,E/WifiStateMachine(  953): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  953): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
E/WifiStateMachine(  953): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.37 txretriesrate=0.00 rxrate=3.13 userTriggerdPenalty0
D/WIFI_ICON( 1232): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  953):  good link -> stuck count =0
D/StatusBar.NetworkController( 1232): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiStateMachine(  953):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  953):  isHighRSSI       ---> score=61
E/WifiStateMachine(  953): handleMessage: X
D/WifiWatchdogStateMachine(  953): RSSI current: 3 new: -60, 3
,D/AutoSetting( 1643): service - handleMessage() stop self,
,D/AutoSetting( 1643): service - onDestroy() END,
D/AutoSetting( 1643): service - handleMessage() quit looper,
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7
D/WIFI_ICON( 1232): WifiActivity: 0
E/WifiTrafficPoller(  953):  packet count Tx=176 Rx=274
E/WifiTrafficPoller(  953): notifying of data activity 0
,D/StatusBar.NetworkController( 1232): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  953):  packet count Tx=176 Rx=274
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7
,E/WifiTrafficPoller(  953):  packet count Tx=176 Rx=275
E/WifiTrafficPoller(  953): notifying of data activity 1
D/WIFI_ICON( 1232): WifiActivity: 1
D/StatusBar.NetworkController( 1232): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/WifiStateMachine(  953): handleMessage: E msg.what=131155,
E/WifiStateMachine(  953): processMsg: ConnectedState
E/WifiStateMachine(  953):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=3.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:562159376] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  953): processMsg: L2ConnectedState
E/WifiStateMachine(  953):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=3.1 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:562159378] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  953):  get link layer stats 0
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1330): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  953): fetchRssiLinkSpeedAndFrequencyNative RSSI = -61 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  953): fetchRssiLinkSpeedAndFrequencyNative rssi=-61 linkspeed=72
,E/WifiConfigStore(  953): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-60 "NG700"WPA_PSK
,E/WifiStateMachine(  953): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.19 txretriesrate=0.00 rxrate=2.06 userTriggerdPenalty0
E/WifiStateMachine(  953):  good link -> stuck count =0
,E/WifiStateMachine(  953):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  953):  isHighRSSI       ---> score=61
D/WifiWatchdogStateMachine(  953): RSSI current: 3 new: -61, 3
E/WifiStateMachine(  953): handleMessage: X
,D/WIFI_ICON( 1232): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1232): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/WifiDataStallTracker(  953): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  953): updateDataStallInfo: mDataStallTxRxSum={txSum=157 rxSum=154} preTxRxSum={txSum=157 rxSum=154}
D/WifiDataStallTracker(  953): updateDataStallInfo: NONE
D/WifiDataStallTracker(  953): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7
,E/WifiTrafficPoller(  953):  packet count Tx=176 Rx=275
D/WIFI_ICON( 1232): WifiActivity: 0
E/WifiTrafficPoller(  953): notifying of data activity 0
D/StatusBar.NetworkController( 1232): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/HtcModeClient( 3238): handler message = 4011,
E/HtcModeClient( 3238): Check connection and retry 11 times.
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  953):  packet count Tx=176 Rx=275
,D/PMS     (  953): acquireWL(3ddae4a6): PARTIAL_WAKE_LOCK  *alarm* 0x1 953 1000 WorkSource{10024},
V/AlarmManager(  953): sending alarm PendingIntent{6421ee7: PendingIntentRecord{1d3bba94 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1452261107847, Int=536832000
V/AlarmManager(  953): sending alarm PendingIntent{5276a50: PendingIntentRecord{3e0cd449 android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1452261100597, Int=20000
,V/CheckinService( 4507): unknown intent received for checkin (Intent { flg=0x14 cmp=com.google.android.gms/.checkin.CheckinService$Receiver (has extras) })
,D/PMS     (  953): acquireWL(7bfb93d): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4507 10024 WorkSource{10024 com.google.android.gms}
,E/WifiStateMachine(  953): WiFiStateMachine SCAN ALARM
D/WifiDisplayAdapter(  953): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  953):     Client/Owner: Client
D/WifiDisplayAdapter(  953):     GroupId: 
D/WifiDisplayAdapter(  953):     Passphrase: 
D/WifiDisplayAdapter(  953):     SessionId: 0
D/WifiDisplayAdapter(  953):     IP Address: }
E/WifiStateMachine(  953): handleMessage: E msg.what=131143
D/PMS     (  953): releaseWL(3ddae4a6): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  953): processMsg: ConnectedState
,E/WifiStateMachine(  953):  ConnectedState !CMD_START_SCAN -2 -2 ic=4 proc(ms):2 dur:95 rssi=-61 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=2.1 list=2412 [on:0 tx:0 rx:0 period:2432] from screen [on:0 period:562161817]
E/WifiStateMachine(  953): processMsg: L2ConnectedState
E/WifiStateMachine(  953):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=4 proc(ms):4 dur:95 rssi=-61 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=2.1 list=2412 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:562161818]
E/WifiStateMachine(  953): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.19 rxSuccessRate=2.06 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-61
E/WifiStateMachine(  953): WifiStateMachine CMD_START_SCAN with age=58955 interval=60000 maxinterval=300000
E/WifiStateMachine(  953): WifiStateMachine CMD_START_SCAN full=false
E/WifiConfigStore(  953): makeChannelList age=3600000 for "NG700"WPA_PSK max=6 bssids=1
E/WifiConfigStore(  953): has c0:ff:d4:d3:aa:48 freq=2412 age=2438 ?=true
E/WifiStateMachine(  953): WifiStateMachine starting scan for "NG700"WPA_PSK with 2412
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY freq=2412"
,D/wpa_supplicant( 1330): wlan0: Control interface command 'SCAN TYPE=ONLY freq=2412'
D/wpa_supplicant( 1330): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1330): wpa_supplicant_scan enter
D/wpa_supplicant( 1330): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1330): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1330): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1330): WPS:  * Request Type
D/wpa_supplicant( 1330): WPS:  * Config Methods (4288)
,D/wpa_supplicant( 1330): WPS:  * UUID-E
D/wpa_supplicant( 1330): WPS:  * Primary Device Type
D/wpa_supplicant( 1330): WPS:  * RF Bands (3)
D/wpa_supplicant( 1330): WPS:  * Association State
D/wpa_supplicant( 1330): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1330): WPS:  * Device Password ID (0)
,D/wpa_supplicant( 1330): WPS:  * Manufacturer
D/wpa_supplicant( 1330): WPS:  * Model Name
D/wpa_supplicant( 1330): WPS:  * Model Number
,D/PMS     (  953): acquireWL(987c283): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4507 10024 WorkSource{10024 com.google.android.gms}
D/wpa_supplicant( 1330): WPS:  * Device Name
D/wpa_supplicant( 1330): WPS:  * Version2 (0x20)
,D/PMS     (  953): releaseWL(7bfb93d): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
D/wpa_supplicant( 1330): P2P: * P2P IE header
D/wpa_supplicant( 1330): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1330): P2P: * Listen Channel: Regulatory Class 81 Channel 1
D/wpa_supplicant( 1330): wlan0: Limit manual scan to specified channels
,D/wpa_supplicant( 1330): wlan0: Add radio work 'scan'@0x55c1e20680
D/wpa_supplicant( 1330): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1330): wlan0: Starting radio work 'scan'@0x55c1e20680 after 0.000057 second wait
D/wpa_supplicant( 1330): wlan0: nl80211: scan request
D/wpa_supplicant( 1330): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1330): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1330): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1330): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1330): wlan0: Own scan request started a scan in 0.000133 seconds
I/wpa_supplicant( 1330): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  953): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  953): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-SCAN-STARTED ,
E/WifiMonitor(  953): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  953): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  953): [1,452,261,107,869 ms] noteScanstart no scan source
E/WifiStateMachine(  953): handleMessage: X
,I/CheckinService( 4507): Checking schedule, now: 1452261107883 next: 1452261107847
I/CheckinService( 4507): active receiver: enabled
,I/PackageManager(  953):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=4507, uid=10024, userID:0
,I/CheckinService( 4507): Preparing to send checkin request,
I/EventLogService( 4507): Accumulating logs since 1452261073296
,I/CheckinRequestBuilder( 4507): Checkin reason type: 11 attempt count: 1
,I/ActivityManager(  953): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4507): Failed to find provider info for com.google.android.wearable.settings
,D/wpa_supplicant( 1330): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1330): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1330): nl80211: Scan included frequencies: 2412
,D/wpa_supplicant( 1330): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1330): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1330): wlan0: Scan completed in 0.080405 seconds
,D/wpa_supplicant( 1330): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1330): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1330): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1330): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1330): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1330): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-61
I/wpa_supplicant( 1330): [NULL] a0:c5:62:7a:49:97 freq=5260 level=-82
I/wpa_supplicant( 1330): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-83
I/wpa_supplicant( 1330): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1330): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85,
D/wpa_supplicant( 1330): wlan0: BSS: Start scan result update 5
W/ContextImpl(  953): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
D/wpa_supplicant( 1330): BSS: last_scan_res_used=6/32
D/wpa_supplicant( 1330): wlan0: Scan-only results received
D/wpa_supplicant( 1330): wlan0: Radio work 'scan'@0x55c1e20680 done in 0.081543 seconds
E/WifiMonitor(  953): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  953): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  953): handleMessage: E msg.what=147461
E/WifiStateMachine(  953): processMsg: ConnectedState
E/WifiStateMachine(  953):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 bcn=0
E/WifiStateMachine(  953): processMsg: L2ConnectedState
E/WifiStateMachine(  953):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 bcn=0
E/WifiStateMachine(  953): processMsg: ConnectModeState
E/WifiStateMachine(  953):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 bcn=0,
E/WifiStateMachine(  953): processMsg: DriverStartedState
E/WifiStateMachine(  953):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 bcn=0
E/WifiStateMachine(  953): processMsg: SupplicantStartedState
E/WifiStateMachine(  953):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 bcn=0
D/WifiStateMachine(  953): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1330): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  953): [1,452,261,107,956 ms] noteScanEnd no scan source
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1330): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
,E/WifiStateMachine(  953): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@211cb9ce sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  953): NG7005g c0:ff:d4:d3:aa:4a rssi=-47 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
,E/WifiAutoJoinController (  953): NG700 c0:ff:d4:d3:aa:48 rssi=-61 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  953): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  953): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  953):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-61 freq=2412
E/WifiAutoJoinController (  953): UPC Wi-Free 06:7c:34:12:7f:81 rssi=-84 cap [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  953): UPC5999698 64:7c:34:12:7f:81 rssi=-85 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS] is not scored
E/WifiAutoJoinController (  953): 01ABC c2:ff:d4:d3:aa:48 rssi=-60 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  953): UPC503894600 a0:c5:62:7a:49:97 rssi=-82 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  953): DIRECT-qjWorkCentre 3025 9e:93:4e:3e:ba:c5 rssi=-83 cap [WPA2-PSK-CCMP][WPS-AUTH][ESS][P2P] is not scored
E/WifiAutoJoinController (  953): ageScanResultsOut delay 40000 size 7 now 1452261107961
E/WifiAutoJoinController (  953): newSupplicantResults size=7 known=1 true
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1330): wlan0: Control interface command 'STATUS-NO_EVENTS'
,E/WifiAutoJoinController (  953): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
E/WifiAutoJoinController (  953): ssid=NG700
E/WifiAutoJoinController (  953): id=0
E/WifiAutoJoinController (  953): mode=station
E/WifiAutoJoinController (  953): pairwise_cipher=CCMP
E/WifiAutoJoinController (  953): group_cipher=CCMP
E/WifiAutoJoinController (  953): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  953): wpa_state=COMPLETED
E/WifiAutoJoinController (  953): ip_address=192.168.1.130
E/WifiAutoJoinController (  953): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  953): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  953): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  953): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController (  953): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-61,-127) num=(1,0)
E/WifiAutoJoinController (  953): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  953): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-61 freq=2412 Current: c0:ff:d4:d3:aa:48
,D/HtcWifiControlRoamOffload: (  953): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  953): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  953): Done attemptAutoJoin status=0
E/WifiConfigStore(  953):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  953): handleMessage: X
,I/GLSUser ( 1986): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer,
I/GLSUser ( 1986): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1986): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1986): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1986): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/CheckinRequestBuilder( 4507): awaiting user notification for token,
I/RemoteViews( 1232): reapply : com.google.android.gms 2 40
,D/DotMatrix( 1342): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1342): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/ActivityManager(  953): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6480 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,W/ResourcesManager( 6480): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6480): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6480): VM with version 2.1.0 has multidex support,
I/MultiDex( 6480): install
I/MultiDex( 6480): VM has multidex support, MultiDex support library is disabled.,
,V/JNIHelp ( 6480): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7,
D/WIFI_ICON( 1232): WifiActivity: 1
E/WifiTrafficPoller(  953):  packet count Tx=176 Rx=276
D/StatusBar.NetworkController( 1232): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  953): notifying of data activity 1
,W/System  ( 6480): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@35a2365e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,W/ActivityThread( 6480): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ProviderInstaller( 6480): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1986): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1986): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 4507): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/PackageManager(  953):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4507, uid=10024, userID:0
D/WearableService( 5793): callingUid 10024, callindPid: 5793
,E/MDM     ( 1842): [129] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,D/LocationInitializer( 4507): Restart initialization of location,
,E/WifiStateMachine(  953): handleMessage: E msg.what=131155,
E/WifiStateMachine(  953): processMsg: ConnectedState
,E/WifiStateMachine(  953):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:564] from screen [on:0 period:562162386] gl hn u24 rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  953): processMsg: L2ConnectedState
E/WifiStateMachine(  953):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:562162387] gl hn u24 rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  953):  get link layer stats 0
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SIGNAL_POLL'
I/WVCdm   (  451): CdmEngine::OpenSession
I/WVCdm   (  451): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  451): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,I/wpa_supplicant( 1330): environment dirty rate=0 [0][0][0],
E/WifiStateMachine(  953): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  953): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  953): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-60 "NG700"WPA_PSK
D/WIFI_ICON( 1232): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  953): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.09 txretriesrate=0.00 rxrate=1.53 userTriggerdPenalty0
D/StatusBar.NetworkController( 1232): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiStateMachine(  953):  good link -> stuck count =0
,E/WifiStateMachine(  953):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  953):  isHighRSSI       ---> score=61
D/WifiWatchdogStateMachine(  953): RSSI current: 3 new: -60, 3
E/WifiStateMachine(  953): handleMessage: X
,D/DrmWidevineDash(  451): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  451): Service_Initialize: starts!
D/QSEECOMAPI: (  451): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  451): App is not loaded in QSEE
E/QSEECOMAPI: (  451): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  451): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  451): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  451): App is not loaded in QSEE
,D/QSEECOMAPI: (  451): Loaded image: APP id = 8,
,D/DrmWidevineDash(  451): Service_Initialize: ends! returns 0,
,D/QSAPPSVER(  451): qsapps_get_capabilities: Capability from secure side: 0x0,
D/QSAPPSVER(  451): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  451): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf491d000
E/DrmWidevineDash(  451): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf491d000
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/DrmLibTime(  560): got the req here! ret=0
D/DrmLibTime(  560): command id, time_cmd_id = 770
D/DrmLibTime(  560): time_getutcsec starts!
D/DrmLibTime(  560): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  560): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  560): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  560): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  560): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  560): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  560): QSEE Time Listener: Retrieved Android system time: 1452261108
D/DrmLibTime(  560): time_getutcsec returns 0, sec = 1452261108; nsec = 0
D/DrmLibTime(  560): time_getutcsec finished! 
E/QC-time-services(  478): Daemon: Time-services: Waiting to acceptconnection
D/DrmLibTime(  560): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  560): before calling ioctl to read the next time_cmd
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  451): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  451): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  451): hlos api version =  9
D/DrmWidevineDash(  451): tz api version =  9
D/DrmWidevineDash(  451): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  451): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  451): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  451): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  451): OEMCrypto_OpenSession: starts! SID=0xf4b92928
,D/DrmWidevineDash(  451): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  451): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  451): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  451): OEMCrypto_GetRandom: starts! randomData=0xab143b18, dataLength=8
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  451): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  451): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab02b050, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  451): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  451): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  451): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  451): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  451): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  451): OEMCrypto_GetDeviceID: starts! deviceID=0xab0141c0, idLength=0xfff2b5f8
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  451): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  451): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  451): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  451): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  451): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  451): OEMCrypto_GetHDCPCapability: starts!, current = 0xfff2b60e, maximum = 0xfff2b60f
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  451): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  451): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  451): hlos api version =  9
D/DrmWidevineDash(  451): tz api version =  9
D/DrmWidevineDash(  451): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  451): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xfff2b67c
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  451): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  451): PrepareKeyRequest: nonce=2284445387
D/DrmWidevineDash(  451): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab02c360,
D/DrmWidevineDash(  451): message_length=1611, signature=0xab036750, signature_length=0xfff2b5dc
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  451): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  451): CdmEngine::CloseSession
D/DrmWidevineDash(  451): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  451): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  451): L3 Terminate.
,D/DrmWidevineDash(  451): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  451): Service_Uninitialize: starts!
D/QSEECOMAPI: (  451): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  451): QSEECom_shutdown_app, app_id = 8
D/DrmWidevineDash(  451): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  451): OEMCrypto_Terminate: ends! returns 0
,I/WVCdm   (  451): CdmEngine::OpenSession,
I/WVCdm   (  451): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  451): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  451): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15,
D/DrmWidevineDash(  451): Service_Initialize: starts!
D/QSEECOMAPI: (  451): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  451): App is not loaded in QSEE
E/QSEECOMAPI: (  451): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  451): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  451): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  451): App is not loaded in QSEE
,D/QSEECOMAPI: (  451): Loaded image: APP id = 9,
,D/DrmWidevineDash(  451): Service_Initialize: ends! returns 0,
,D/QSAPPSVER(  451): qsapps_get_capabilities: Capability from secure side: 0x0,
D/QSAPPSVER(  451): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  451): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf491d000
E/DrmWidevineDash(  451): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf491d000
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/DrmLibTime(  560): got the req here! ret=0
,D/DrmLibTime(  560): command id, time_cmd_id = 770
D/DrmLibTime(  560): time_getutcsec starts!
D/DrmLibTime(  560): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  560): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  560): QSEE Time Listener: time_get_modem_time
,D/DrmLibTime(  560): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  560): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  560): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  560): QSEE Time Listener: Retrieved Android system time: 1452261108,
D/DrmLibTime(  560): time_getutcsec returns 0, sec = 1452261108; nsec = 0
D/DrmLibTime(  560): time_getutcsec finished! 
,D/DrmLibTime(  560): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  560): before calling ioctl to read the next time_cmd
E/QC-time-services(  478): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  451): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  451): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  451): hlos api version =  9
D/DrmWidevineDash(  451): tz api version =  9
D/DrmWidevineDash(  451): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  451): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  451): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  451): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  451): OEMCrypto_OpenSession: starts! SID=0xf4ded928
D/DrmWidevineDash(  451): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  451): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  451): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  451): OEMCrypto_GetRandom: starts! randomData=0xab029618, dataLength=8
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  451): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  451): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab02ce70, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  451): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  451): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  451): BufferReader::Read<T> : Failure during parse: Not enough bytes (4),
W/WVCdm   (  451): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  451): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  451): OEMCrypto_GetDeviceID: starts! deviceID=0xab0141e0, idLength=0xf4ded6f8
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  451): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  451): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  451): OEMCrypto_SupportsUsageTable: is_supported = 1
,D/DrmWidevineDash(  451): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  451): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  451): OEMCrypto_GetHDCPCapability: starts!, current = 0xf4ded70e, maximum = 0xf4ded70f
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  451): OEMCrypto_GetHDCPCapability: ends! returns 0
,D/DrmWidevineDash(  451): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  451): hlos api version =  9
D/DrmWidevineDash(  451): tz api version =  9
D/DrmWidevineDash(  451): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  451): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf4ded77c
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  451): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  451): PrepareKeyRequest: nonce=3857885574
D/DrmWidevineDash(  451): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab02d8d0
D/DrmWidevineDash(  451): message_length=1646, signature=0xab02b6c8, signature_length=0xf4ded6dc
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  451): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  451): CdmEngine::CloseSession
D/DrmWidevineDash(  451): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  451): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  451): L3 Terminate.
D/DrmWidevineDash(  451): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  451): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  451): Service_Uninitialize: starts!
D/QSEECOMAPI: (  451): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  451): QSEECom_shutdown_app, app_id = 9
D/DrmWidevineDash(  451): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  451): OEMCrypto_Terminate: ends! returns 0
,E/cutils-trace( 6513): Error opening trace file: Permission denied (13),
I/dex2oat ( 6513): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6513): dex2oat: override thread count:4
,I/dex2oat ( 6513): dex2oat took 118.652ms (threads: 4),
,I/Adreno-EGL( 6480): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 6480): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6480): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6480): Local Branch: 
I/Adreno-EGL( 6480): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6480): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6480):                  d74aa161a12b9c6fc6332151
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7
,E/WifiTrafficPoller(  953):  packet count Tx=176 Rx=276
E/WifiTrafficPoller(  953): notifying of data activity 0
,D/WIFI_ICON( 1232): WifiActivity: 0
D/StatusBar.NetworkController( 1232): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/Adreno-EGL( 6480): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 6480): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6480): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6480): Local Branch: 
I/Adreno-EGL( 6480): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6480): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6480):                  d74aa161a12b9c6fc6332151
,I/CheckinRequestBuilder( 4507): Classify the device as Phone.,
,D/libc    ( 4507): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,D/libc    ( 4507): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4507): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
,D/libc    ( 4507): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4507): [NET] android_getaddrinfo_proxy+
,D/libc    ( 4507): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  400): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  400): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4507): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 4507): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4507): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 4507): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4507): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 4507): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4507): [NET] android_getaddrinfofornet-, err=8
,I/CheckinTask( 4507): Sending checkin request (8405 bytes),
,I/CheckinRequestBuilder( 4507): Checkin reason type: 11 attempt count: 1,
,I/ActivityManager(  953): Cannot resolve ContentProvider=com.google.android.wearable.settings
,E/ActivityThread( 4507): Failed to find provider info for com.google.android.wearable.settings
,I/art     ( 1986): Explicit concurrent mark sweep GC freed 19698(1150KB) AllocSpace objects, 10(840KB) LOS objects, 49% free, 4MB/8MB, paused 1.006ms total 53.026ms,
,I/GLSUser ( 1986): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1986): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1986): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1986): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1986): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/CheckinRequestBuilder( 4507): awaiting user notification for token
D/DotMatrix( 1342): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1342): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7
D/WIFI_ICON( 1232): WifiActivity: 3
E/WifiTrafficPoller(  953):  packet count Tx=192 Rx=289
D/StatusBar.NetworkController( 1232): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,E/WifiTrafficPoller(  953): notifying of data activity 3
,I/RemoteViews( 1232): reapply : com.google.android.gms 3 40
,I/CheckinRequestBuilder( 4507): Classify the device as Phone.
,I/CheckinTask( 4507): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4507): Checking schedule, now: 1452261110305 next: 1452797942299
,I/CheckinService( 4507): active receiver: disabled
I/PackageManager(  953):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4507, uid=10024, userID:0
,D/PMS     (  953): releaseWL(987c283): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
,D/ChimeraCfgMgr( 4507): Loading module com.google.android.gms.kids from APK com.google.android.gms,
,D/ChimeraCfgMgr( 4507): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/GCM     ( 1986): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE,
,I/GLSUser ( 1986): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1986): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1986): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1986): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1986): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Kids    ( 4507): [AccountUtils] Account not ready
W/Kids    ( 4507): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4507): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4507): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4507): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4507): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4507): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4507): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4507): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4507): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4507): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4507): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4507): 	at java.lang.Thread.run(Thread.java:818)
D/DotMatrix( 1342): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1342): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1232): reapply : com.google.android.gms 2 40
,E/WifiDataStallTracker(  953): DATA_MONITOR_POLL true Token 1
,D/WifiDataStallTracker(  953): updateDataStallInfo: mDataStallTxRxSum={txSum=173 rxSum=167} preTxRxSum={txSum=157 rxSum=154},
D/WifiDataStallTracker(  953): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  953): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7,
D/WIFI_ICON( 1232): WifiActivity: 1
E/WifiTrafficPoller(  953):  packet count Tx=192 Rx=290
D/StatusBar.NetworkController( 1232): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  953): notifying of data activity 1
,W/ContextImpl(  953): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,E/WifiStateMachine(  953): handleMessage: E msg.what=131155,
E/WifiStateMachine(  953): processMsg: ConnectedState
E/WifiStateMachine(  953):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:562165408] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  953): processMsg: L2ConnectedState
E/WifiStateMachine(  953):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:562165409] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  953):  get link layer stats 0
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1330): environment dirty rate=12 [16][2][0],
E/WifiStateMachine(  953): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  953): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  953): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-60 "NG700"WPA_PSK
,E/WifiStateMachine(  953): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=8.05 txretriesrate=0.00 rxrate=7.77 userTriggerdPenalty0
E/WifiStateMachine(  953):  good link -> stuck count =0
E/WifiStateMachine(  953):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  953):  isHighRSSI       ---> score=65
,D/WifiWatchdogStateMachine(  953): RSSI current: 3 new: -60, 3
D/WIFI_ICON( 1232): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  953): handleMessage: X
D/StatusBar.NetworkController( 1232): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/HtcModeClient( 3238): handler message = 4011,
E/HtcModeClient( 3238): Check connection and retry 12 times.
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7,
D/WIFI_ICON( 1232): WifiActivity: 0
E/WifiTrafficPoller(  953):  packet count Tx=192 Rx=290
D/StatusBar.NetworkController( 1232): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  953): notifying of data activity 0
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  953):  packet count Tx=192 Rx=290
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7,
D/WIFI_ICON( 1232): WifiActivity: 1
E/WifiTrafficPoller(  953):  packet count Tx=192 Rx=291
D/StatusBar.NetworkController( 1232): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  953): notifying of data activity 1
,E/WifiStateMachine(  953): handleMessage: E msg.what=131155,
E/WifiStateMachine(  953): processMsg: ConnectedState
E/WifiStateMachine(  953):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=8.0, 0.0, 0.0  rx=7.8 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:562168430] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  953): processMsg: L2ConnectedState
E/WifiStateMachine(  953):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=8.0, 0.0, 0.0  rx=7.8 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:562168431] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  953):  get link layer stats 0
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SIGNAL_POLL'
,D/Process (  953): killProcessQuiet, pid=6030,
I/ActivityManager(  953): Killing 6030:com.htc.sdm/u0a79 (adj 15): empty #17
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/wpa_supplicant( 1330): environment dirty rate=0 [0][0][0]
,E/WifiStateMachine(  953): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72,
E/WifiStateMachine(  953): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  953): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
E/WifiStateMachine(  953): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=4.02 txretriesrate=0.00 rxrate=4.38 userTriggerdPenalty0
E/WifiStateMachine(  953):  good link -> stuck count =0
E/WifiStateMachine(  953):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  953):  isHighRSSI       ---> score=61
,I/ActivityManager(  953): Recipient 6030,
,E/WifiStateMachine(  953): handleMessage: X,
,D/WifiWatchdogStateMachine(  953): RSSI current: 3 new: -60, 3
D/WIFI_ICON( 1232): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1232): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  953):  packet count Tx=192 Rx=291
D/WIFI_ICON( 1232): WifiActivity: 0,
E/WifiTrafficPoller(  953): notifying of data activity 0
D/StatusBar.NetworkController( 1232): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiDataStallTracker(  953): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  953): updateDataStallInfo: mDataStallTxRxSum={txSum=173 rxSum=167} preTxRxSum={txSum=173 rxSum=167}
,D/WifiDataStallTracker(  953): updateDataStallInfo: NONE
D/WifiDataStallTracker(  953): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  953):  packet count Tx=192 Rx=291
,I/HtcModeClient( 3238): handler message = 4011
E/HtcModeClient( 3238): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 3238): Don't start project servcice
,D/HtcModeClient( 3238): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 3238): connectState: CONNECTION_READY = false
D/SilentMusic( 3238): call stop
D/HtcModeClient( 3238): close connection
W/HtcModeClient( 3238): leaveProjectMode: It does not enter ProjectMode
W/CANMesgAgentLocalSocket( 3238): read the terminate packet, so break
,D/Process (  953): killProcessQuiet, pid=3238
I/ActivityManager(  953): Killing 3238:com.htc.autobot/u0a47 (adj 15): empty #17
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7
D/WIFI_ICON( 1232): WifiActivity: 1
E/WifiTrafficPoller(  953):  packet count Tx=192 Rx=292
E/WifiTrafficPoller(  953): notifying of data activity 1
D/StatusBar.NetworkController( 1232): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/ActivityManager(  953): Recipient 3238,
,E/WifiStateMachine(  953): handleMessage: E msg.what=131155
E/WifiStateMachine(  953): processMsg: ConnectedState
E/WifiStateMachine(  953):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=4.0, 0.0, 0.0  rx=4.4 bcn=0 [on:0 tx:0 rx:0 period:2798] from screen [on:0 period:562171451] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  953): processMsg: L2ConnectedState
E/WifiStateMachine(  953):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=4.0, 0.0, 0.0  rx=4.4 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:562171452] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  953):  get link layer stats 0
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/wpa_supplicant( 1330): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1330): environment dirty rate=100 [1][1][0]
E/WifiStateMachine(  953): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  953): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  953): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
E/WifiStateMachine(  953): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=2.01 txretriesrate=0.00 rxrate=2.69 userTriggerdPenalty0
E/WifiStateMachine(  953):  good link -> stuck count =0
E/WifiStateMachine(  953):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  953):  isHighRSSI       ---> score=61
E/WifiStateMachine(  953): handleMessage: X
D/WifiWatchdogStateMachine(  953): RSSI current: 3 new: -60, 3
,D/WIFI_ICON( 1232): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1232): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  953): acquireWL(106fefd5): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 6206 10112 null,
,I/Prism.ItemManager( 1604): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1604): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/Prism.ItemManager( 1604): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/SystemReader(  953): Cannot find grip_rejection_width, use default value instead
D/AccTypeManager( 1757): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,D/AccTypeManager( 1757): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/ResourcesManager(  953): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,D/PMS     (  953): releaseWL(106fefd5): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
D/PhoneApp( 1556): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/[PluginManager]RegisterService( 1643): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
I/[PluginManager]RegisterService( 1643): handle notify Blinkfeed plugin client changed
,W/ResourcesManager( 6206): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6206): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/AccTypeManager( 1757): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1757): Unsupported attribute readOnly
,D/PackageBroadcastService( 4507): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4507): Null package name or gms related package.  Ignoreing.
,W/PackageManager(  953): Unable to load service info ResolveInfo{270b1f0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  953): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  953): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  953): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  953): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  953): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  953): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  953): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  953): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  953): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  953): 	,at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  953): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  953): 	,at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  953): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  953): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  953): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  953): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/BackupManagerService(  953): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/art     (  953): Explicit concurrent mark sweep GC freed 31382(1711KB) AllocSpace objects, 5(292KB) LOS objects, 33% free, 18MB/28MB, paused 1.616ms total 166.292ms
,D/PMS     (  953): acquireWL(6f4c3c8): PARTIAL_WAKE_LOCK  AsyncService 0x1 5874 10167 null
D/PMS     (  953): releaseWL(6f4c3c8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  953): acquireWL(2a817447): PARTIAL_WAKE_LOCK  Icing 0x1 4507 10024 WorkSource{10024 com.google.android.gms}
,V/GmsNetworkLocationProvi( 1842): DISABLE
,D/PMS     (  953): acquireWL(1662a53f): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 5874 10167 null
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7
,E/WifiTrafficPoller(  953):  packet count Tx=192 Rx=292
E/WifiTrafficPoller(  953): notifying of data activity 0
,I/Icing   ( 4507): updateResources: need to parse f{com.google.android.gms}
D/WIFI_ICON( 1232): WifiActivity: 0
,D/StatusBar.NetworkController( 1232): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  953): releaseWL(1662a53f): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,I/GCoreNlp( 1842): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/UpdateIcingCorporaServi( 5906): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PMS     (  953): releaseWL(2a817447): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  953): acquireWL(11258c4b): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1842 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  953): releaseWL(11258c4b): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
D/LocationProviderProxy(  953): applying state to connected service
,D/LocationProviderProxy(  953): applying state to connected service
,D/PMS     (  953): acquireWL(abdc628): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1842 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): releaseWL(abdc628): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): acquireWL(101dbf41): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1842 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): releaseWL(101dbf41): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,I/UpdateIcingCorporaServi( 5906): UpdateCorporaTask done [took 56 ms] updated apps [took 56 ms] 
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  953):  packet count Tx=192 Rx=292
,D/PMS     (  953): acquireWL(356c7172): PARTIAL_WAKE_LOCK  Icing 0x1 4507 10024 WorkSource{10024 com.google.android.gms}
,I/Prism.ItemManager( 1604): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1604): loadItems() com.htc.launcher.pageview.WidgetManager@11dbeab4 +
I/Prism.WidgetManager( 1604): onLoadItems() +
,D/PMS     (  953): releaseWL(356c7172): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): acquireWL(71f326c): PARTIAL_WAKE_LOCK  Icing 0x1 4507 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  953): releaseWL(71f326c): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): acquireWL(454bcca): PARTIAL_WAKE_LOCK  Icing 0x1 4507 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): releaseWL(454bcca): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): acquireWL(20030958): PARTIAL_WAKE_LOCK  Icing 0x1 4507 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  953): releaseWL(20030958): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,E/Prism.WidgetManager( 1604): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1604): onLoadItems() -
I/Prism.ItemManager( 1604): loadItems() com.htc.launcher.pageview.WidgetManager@11dbeab4 -
,D/PMS     (  953): acquireWL(2033fab1): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 953 1000 WorkSource{1000}
V/AlarmManager(  953): sending alarm PendingIntent{2c407186: PendingIntentRecord{dab5a47 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=108188, Int=0
,D/PhoneApp( 1556): EVENT_QUERY_MO_PACKAGES
,D/PMS     (  953): releaseWL(2033fab1): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/PhoneApp( 1556): -- N1 =0
,D/PhoneApp( 1556): -- N2 =0
D/PhoneApp( 1556): -- N3 =0
D/WeatherUtility( 1232): Weather sync is On
,W/WeatherTimeKeeper( 1232): [refreshWeatherData] no weather data
,I/ClockController( 1232): schedule update now=1452261120060 next=59940,
,I/Clock   ( 1232): updateClock:14:52 Europe/Warsaw
,I/Clock   ( 1232): updateClock:14:52 Europe/Warsaw
I/Clock   ( 1232): updateClock:14:52 Europe/Warsaw
,I/ActivityManager(  953): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=6541 uid=10076 gids={50076, 9997} abi=arm64-v8a
D/PMS     (  953): acquireWL(2269db96): PARTIAL_WAKE_LOCK  *alarm* 0x1 953 1000 WorkSource{10076}
V/AlarmManager(  953): sending alarm PendingIntent{13fe6317: PendingIntentRecord{4b6304 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1452261120128, Int=60000
,D/PMS     (  953): releaseWL(2269db96): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,D/SMSBackup( 6541): SMSBackupAgentService started,
D/SMSBackup( 6541): Checking restore status,
,D/SMSBackup( 6541): Restore complete
,D/SMSBackup( 6541): cancelCheckAlarm
,D/SMSBackup( 6541): SMSBackupAgentService completed: completed in 0.0 seconds,
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7,
,E/WifiTrafficPoller(  953):  packet count Tx=192 Rx=293
D/WIFI_ICON( 1232): WifiActivity: 1
E/WifiTrafficPoller(  953): notifying of data activity 1
,D/StatusBar.NetworkController( 1232): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/WifiDataStallTracker(  953): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  953): updateDataStallInfo: mDataStallTxRxSum={txSum=173 rxSum=167} preTxRxSum={txSum=173 rxSum=167}
D/WifiDataStallTracker(  953): updateDataStallInfo: NONE
D/WifiDataStallTracker(  953): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiStateMachine(  953): handleMessage: E msg.what=131155
E/WifiStateMachine(  953): processMsg: ConnectedState
E/WifiStateMachine(  953):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=2.0, 0.0, 0.0  rx=2.7 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:562174471] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  953): processMsg: L2ConnectedState
E/WifiStateMachine(  953):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=2.0, 0.0, 0.0  rx=2.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:562174472] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine(  953):  get link layer stats 0
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1330): environment dirty rate=0 [0][0][0],
E/WifiStateMachine(  953): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  953): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  953): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
E/WifiStateMachine(  953): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=1.01 txretriesrate=0.00 rxrate=1.85 userTriggerdPenalty0
E/WifiStateMachine(  953):  good link -> stuck count =0
D/WIFI_ICON( 1232): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  953):  badRSSI count0 lowRSSI count0 --> score 56
D/StatusBar.NetworkController( 1232): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/WifiStateMachine(  953):  isHighRSSI       ---> score=61
E/WifiStateMachine(  953): handleMessage: X
D/WifiWatchdogStateMachine(  953): RSSI current: 3 new: -60, 3
,E/WifiStateMachine(  953): WiFiStateMachine SCAN ALARM
D/PMS     (  953): acquireWL(3ce01b22): PARTIAL_WAKE_LOCK  *alarm* 0x1 953 1000 WorkSource{1000}
E/WifiStateMachine(  953): handleMessage: E msg.what=131143
D/WifiDisplayAdapter(  953): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  953):     Client/Owner: Client
D/WifiDisplayAdapter(  953):     GroupId: 
D/WifiDisplayAdapter(  953):     Passphrase: 
D/WifiDisplayAdapter(  953):     SessionId: 0
D/WifiDisplayAdapter(  953):     IP Address: }
E/WifiStateMachine(  953): processMsg: ConnectedState
V/AlarmManager(  953): sending alarm PendingIntent{5276a50: PendingIntentRecord{3e0cd449 android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1452261120597, Int=20000
E/WifiStateMachine(  953):  ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):1 dur:87 rssi=-60 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.8 list=2412 [on:0 tx:0 rx:0 period:62] from screen [on:0 period:562174551]
D/PMS     (  953): releaseWL(3ce01b22): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  953): processMsg: L2ConnectedState
E/WifiStateMachine(  953):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):2 dur:87 rssi=-60 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.8 list=2412 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:562174552]
E/WifiStateMachine(  953): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.01 rxSuccessRate=1.85 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-60
E/WifiStateMachine(  953): WifiStateMachine CMD_START_SCAN with age=71689 interval=60000 maxinterval=300000
E/WifiStateMachine(  953): WifiStateMachine CMD_START_SCAN try full band scan age=71689 interval=60000 maxinterval=300000
E/WifiStateMachine(  953): WifiStateMachine CMD_START_SCAN full=true
E/WifiStateMachine(  953): WifiStateMachine CMD_START_SCAN bump interval =90000
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 1330): wlan0: Setting scan request: 0.000000 sec
,I/wpa_supplicant( 1330): wpa_supplicant_scan enter
D/wpa_supplicant( 1330): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1330): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1330): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1330): WPS:  * Request Type
D/wpa_supplicant( 1330): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1330): WPS:  * UUID-E,
D/wpa_supplicant( 1330): WPS:  * Primary Device Type
D/wpa_supplicant( 1330): WPS:  * RF Bands (3)
D/wpa_supplicant( 1330): WPS:  * Association State
D/wpa_supplicant( 1330): WPS:  * Configuration Error (0)
,D/wpa_supplicant( 1330): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1330): WPS:  * Manufacturer
D/wpa_supplicant( 1330): WPS:  * Model Name
D/wpa_supplicant( 1330): WPS:  * Model Number
D/wpa_supplicant( 1330): WPS:  * Device Name
D/wpa_supplicant( 1330): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1330): P2P: * P2P IE header
,D/wpa_supplicant( 1330): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1330): P2P: * Listen Channel: Regulatory Class 81 Channel 1
D/wpa_supplicant( 1330): wlan0: Add radio work 'scan'@0x55c1e20680
D/wpa_supplicant( 1330): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1330): wlan0: Starting radio work 'scan'@0x55c1e20680 after 0.000085 second wait
D/wpa_supplicant( 1330): wlan0: nl80211: scan request
D/wpa_supplicant( 1330): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1330): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1330): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1330): wlan0: Event SCAN_STARTED (49) received
,D/wpa_supplicant( 1330): wlan0: Own scan request started a scan in 0.000135 seconds
I/wpa_supplicant( 1330): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  953): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  953): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  953): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  953): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  953): [1,452,261,120,605 ms] noteScanstart no scan source
E/WifiStateMachine(  953): handleMessage: X
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7
D/WIFI_ICON( 1232): WifiActivity: 0
E/WifiTrafficPoller(  953):  packet count Tx=192 Rx=293
E/WifiTrafficPoller(  953): notifying of data activity 0
D/StatusBar.NetworkController( 1232): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  953):  packet count Tx=192 Rx=293
,D/wpa_supplicant( 1330): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0,
D/wpa_supplicant( 1330): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1330): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1330): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1330): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1330): wlan0: Scan completed in 2.101039 seconds
,D/wpa_supplicant( 1330): nl80211: Associated on 2412 MHz
W/ContextImpl(  953): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
D/wpa_supplicant( 1330): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1330): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1330): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1330): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1330): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1330): [NULL] a0:c5:62:7a:49:97 freq=5260 level=-81
I/wpa_supplicant( 1330): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1330): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-84
I/wpa_supplicant( 1330): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1330): [NULL] 34:36:3b:bd:89:28 freq=2437 level=-92
D/wpa_supplicant( 1330): wlan0: BSS: Start scan result update 6
D/wpa_supplicant( 1330): wlan0: BSS: Add new id 7 BSSID 34:36:3b:bd:89:28 SSID 'andilabs'
D/wpa_supplicant( 1330): wlan0: BSS: Remove id 4 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to no match in scan
D/wpa_supplicant( 1330): BSS: last_scan_res_used=7/32
D/wpa_supplicant( 1330): wlan0: Scan-only results received
D/wpa_supplicant( 1330): wlan0: Radio work 'scan'@0x55c1e20680 done in 2.102488 seconds
D/WifiMonitor(  953): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 7 34:36:3b:bd:89:28]
D/WifiMonitor(  953): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 c2:ff:d4:d3:aa:48]
E/WifiMonitor(  953): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 c2:ff:d4:d3:aa:48
E/WifiMonitor(  953): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  953): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  953): handleMessage: E msg.what=147461
E/WifiStateMachine(  953): processMsg: ConnectedState
E/WifiStateMachine(  953):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 bcn=0
E/WifiStateMachine(  953): processMsg: L2ConnectedState
E/WifiStateMachine(  953):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 bcn=0
E/WifiStateMachine(  953): processMsg: ConnectModeState
E/WifiStateMachine(  953):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 bcn=0
E/WifiStateMachine(  953): processMsg: DriverStartedState
E/WifiStateMachine(  953):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 bcn=0
E/WifiStateMachine(  953): processMsg: SupplicantStartedState
E/WifiStateMachine(  953):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=7 known=1 got=7 bcn=0
D/WifiStateMachine(  953): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1330): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  953): [1,452,261,122,710 ms] noteScanEnd no scan source
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1330): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  953): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@211cb9ce sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  953): NG7005g c0:ff:d4:d3:aa:4a rssi=-47 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  953): NG700 c0:ff:d4:d3:aa:48 rssi=-60 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  953): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  953): updateSavedNetworkHistory: HTC improve mode
,E/WifiConfigStore(  953):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-60 freq=2412
E/WifiAutoJoinController (  953): UPC Wi-Free 06:7c:34:12:7f:81 rssi=-88 cap [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS] is not scored
,E/WifiAutoJoinController (  953): UPC5999698 64:7c:34:12:7f:81 rssi=-84 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS] is not scored
E/WifiAutoJoinController (  953): UPC503894600 a0:c5:62:7a:49:97 rssi=-81 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  953): DIRECT-qjWorkCentre 3025 9e:93:4e:3e:ba:c5 rssi=-84 cap [WPA2-PSK-CCMP][WPS-AUTH][ESS][P2P] is not scored
E/WifiAutoJoinController (  953): andilabs 34:36:3b:bd:89:28 rssi=-92 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  953): ageScanResultsOut delay 40000 size 8 now 1452261122715
E/WifiAutoJoinController (  953): newSupplicantResults size=8 known=1 true
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1330): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  953): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
E/WifiAutoJoinController (  953): ssid=NG700,
E/WifiAutoJoinController (  953): id=0
E/WifiAutoJoinController (  953): mode=station
E/WifiAutoJoinController (  953): pairwise_cipher=CCMP
E/WifiAutoJoinController (  953): group_cipher=CCMP
E/WifiAutoJoinController (  953): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  953): wpa_state=COMPLETED
E/WifiAutoJoinController (  953): ip_address=192.168.1.130
E/WifiAutoJoinController (  953): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  953): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  953): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  953): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController (  953): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-60,-127) num=(1,0)
E/WifiAutoJoinController (  953): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  953): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-60 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  953): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
,E/WifiStateMachine(  953): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  953): Done attemptAutoJoin status=0
E/WifiConfigStore(  953):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  953): handleMessage: X
D/WifiManager( 1842): getScanResults: Base Package Name=com.google.android.gms, uid=10024
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7
,E/WifiTrafficPoller(  953):  packet count Tx=192 Rx=294
E/WifiTrafficPoller(  953): notifying of data activity 1
D/WIFI_ICON( 1232): WifiActivity: 1
,D/StatusBar.NetworkController( 1232): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/Process (  953): killProcessQuiet, pid=5614
,I/ActivityManager(  953): Killing 5614:com.google.android.music:main/u0a159 (adj 15): empty #17
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  953): Recipient 5614,
D/MediaRouterService(  953): Client com.google.android.music (pid 5614): Died!
,E/WifiStateMachine(  953): handleMessage: E msg.what=131155,
E/WifiStateMachine(  953): processMsg: ConnectedState
E/WifiStateMachine(  953):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.8 bcn=0 [on:0 tx:0 rx:0 period:2932] from screen [on:0 period:562177490] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  953): processMsg: L2ConnectedState
E/WifiStateMachine(  953):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.8 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:562177491] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  953):  get link layer stats 0
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1330): environment dirty rate=0 [0][0][0],
E/WifiStateMachine(  953): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  953): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  953): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-60 "NG700"WPA_PSK
,E/WifiStateMachine(  953): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.50 txretriesrate=0.00 rxrate=1.42 userTriggerdPenalty0
E/WifiStateMachine(  953):  good link -> stuck count =0
E/WifiStateMachine(  953):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  953):  isHighRSSI       ---> score=61
D/WIFI_ICON( 1232): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  953): handleMessage: X
D/WifiWatchdogStateMachine(  953): RSSI current: 3 new: -60, 3
D/StatusBar.NetworkController( 1232): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 11 num clients 7
,D/WIFI_ICON( 1232): WifiActivity: 0
E/WifiTrafficPoller(  953):  packet count Tx=192 Rx=294
D/StatusBar.NetworkController( 1232): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  953): notifying of data activity 0
,I/PMS     (  953): Going to sleep due to screen timeout (uid 1000)...,
,I/SensorManager(  953): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@494209b
D/ActivityManager(  953): getTaskThumbnailLocked mainThumbnail is null, TaskRecord{11fc19b3 #7 A=.Prism U=0 sz=1}
W/SensorService(  953): Following SensorService logs are not warning, just make sure they are printed
W/PMS     (  953): mWirelessDisplayManager is null
W/SensorService(  953): disable: get sensor name = Accelerometer Sensor
W/PMS     (  953): mWirelessDisplayManager is still null
,W/SensorService(  953): pid=953, uid=1000
W/PMN     (  953): goingToSleep
W/SensorService(  953): Active sensors: size = 4
D/PMS     (  953): acquireWL(b9dab70): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 953 1000 null
W/SensorService(  953): Accelerometer Sensor (handle=0x00000000, connections=1)
W/PMN     (  953): goingToSleep done
W/SensorService(  953): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  953): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  953): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  953): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@494209b, eanble = 0, strlen(mName) = 90
W/SensorService(  953): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  953): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@3119c7ff
W/SensorService(  953): Listener[1] = com.htc.smartdim.sensor_eye@12320ff5
W/SensorService(  953): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/FeedHostManager( 1604): [onPause]
I/FeedProviderManager( 1604): onPause
I/FeedHostManager( 1604): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@2e0f67b8
I/SocialFeedProvider( 1604): +onPause
I/SocialFeedProvider( 1604): -onPause
,I/PMS     (  953): Sleeping (uid 1000)...
D/XAN-DPS (  953): prepareColorFade 1
,W/HtcSystemUPManager(  953): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,D/PMS     (  953): releaseWL(b9dab70): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/AlarmManager(  953): ACTION_SCREEN_ON
,I/AlarmManager(  953): [AlarmQueuing] recover blocked alarms
,I/AlarmManager(  953): [AlarmQueuing] done recovering
I/AlarmManager(  953): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  953): [AlarmQueuing] done EPS screen off alarm recovering
I/Adreno-EGL(  953): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL(  953): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  953): Build Date: 03/09/15 Mon
I/Adreno-EGL(  953): Local Branch: 
I/Adreno-EGL(  953): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  953): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  953):                  d74aa161a12b9c6fc6332151
,E/WifiTrafficPoller(  953): ENABLE_TRAFFIC_STATS_POLL true Token 11
,E/WifiTrafficPoller(  953):  packet count Tx=192 Rx=294
,E/WifiDataStallTracker(  953): ENABLE_DATA_MONITOR_POLL true Token 1
W/HtcLockScreen( 1232): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,E/WifiStateMachine(  953): handleMessage: E msg.what=131167
E/WifiStateMachine(  953): processMsg: ConnectedState
E/WifiStateMachine(  953):  ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  953): processMsg: L2ConnectedState
E/WifiStateMachine(  953):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  953): processMsg: ConnectModeState,
E/WifiStateMachine(  953):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  953): processMsg: DriverStartedState
,D/WifiDataStallTracker(  953): updateDataStallInfo: mDataStallTxRxSum={txSum=173 rxSum=167} preTxRxSum={txSum=173 rxSum=167}
,D/WifiDataStallTracker(  953): updateDataStallInfo: NONE
D/WifiDisplayAdapter(  953): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  953):     Client/Owner: Client
D/WifiDisplayAdapter(  953):     GroupId: 
D/WifiDisplayAdapter(  953):     Passphrase: 
D/WifiDisplayAdapter(  953):     SessionId: 0
D/WifiDisplayAdapter(  953):     IP Address: }
D/WifiDataStallTracker(  953): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
E/WifiStateMachine(  953):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  953): processMsg: SupplicantStartedState
E/WifiStateMachine(  953):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  953): processMsg: DefaultState
E/WifiStateMachine(  953):  DefaultState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  953):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SET_SCREEN_ON 1'
I/wpa_supplicant( 1330): SET_SCREEN_ON:On
I/wpa_supplicant( 1330): htc_wext_set_keepalive +
I/wpa_supplicant( 1330): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1330): getPrivFuncNum +	
V/SRS_Proc(  451): ParamSet string: screen_state=on
I/wpa_supplicant( 1330): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1330): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1330): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1330): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1330): htc_wext_set_TX_TRACKING - ret = 0
D/NetworkPolicy(  953): updateScreenOn: false
E/audio_a2dp_hw(  451): adev_set_parameters: ERROR: set param called even when stream out is null
V/NetworkPolicy(  953): updateIfacesLocked()
E/WifiStateMachine(  953): setScanAlarm true period 20000 initial delay 200mAlarmEnabledtrue
D/WifiStateMachine(  953): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  953): handleScreenStateChanged Exit: true
E/WifiStateMachine(  953): handleMessage: X
E/WifiStateMachine(  953): handleMessage: E msg.what=131154
E/WifiStateMachine(  953): processMsg: ConnectedState
E/WifiStateMachine(  953):  ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
,E/WifiStateMachine(  953): processMsg: L2ConnectedState
E/WifiStateMachine(  953):  L2ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SIGNAL_POLL'
D/WifiController(  953): handleMessage: E msg.what=155650
D/WifiController(  953): processMsg: DeviceActiveState
D/WifiController(  953): processMsg: StaEnabledState
D/WifiController(  953): processMsg: DefaultState
D/WifiController(  953): handleMessage: X
,D/NetworkManagementService(  953): isBandwidthControlEnabled: doneSignal.getCount()= 0
I/wpa_supplicant( 1330): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  953): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  953): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  953): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-60 "NG700"WPA_PSK
E/WifiStateMachine(  953): handleMessage: X
E/WifiStateMachine(  953): handleMessage: E msg.what=131127
E/WifiStateMachine(  953): processMsg: ConnectedState
,E/WifiStateMachine(  953):  ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  953): processMsg: L2ConnectedState
E/WifiStateMachine(  953):  L2ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  953): processMsg: ConnectModeState
E/WifiStateMachine(  953):  ConnectModeState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  953): handleMessage: X
E/WifiStateMachine(  953): handleMessage: E msg.what=131129
E/WifiStateMachine(  953): processMsg: ConnectedState
E/WifiStateMachine(  953):  ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  953): processMsg: L2ConnectedState
E/WifiStateMachine(  953):  L2ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  953): processMsg: ConnectModeState
E/WifiStateMachine(  953):  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1330): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1330): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  953): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  953): WifiMonitor:wlan0 cnt=39 dispatchEvent: BLACKLIST CLEAR 
,E/WifiStateMachine(  953): handleMessage: X
,D/DotMatrix( 1342): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/GpsLocationProvider(  953): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/IntentController( 1232): receive(android.intent.action.SCREEN_ON,1,false)
E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL true Token 12 num clients 7
,D/PMS     (  953): acquireWL(388a0e9c): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1842 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  953): acquireWL(be3f0a5): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1842 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  953): releaseWL(388a0e9c): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): releaseWL(be3f0a5): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/XAN-DPS (  953): prepareColorFade done,
D/XAN-DPS (  953): setBrightness to 0,
,I/ActivityManager(  953): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=6571 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/SensorManager(  953): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@3119c7ff
W/SensorService(  953): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  953): disable: get sensor name = CM32181 Light sensor
I/DisplayManagerService(  953): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  953): Display changed displayId=0
,D/DotMatrix( 1342): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1342): [EventService] mbHDMIConnect: false, mCoverOn:false
W/SensorService(  953): pid=953, uid=1000
W/SensorService(  953): Active sensors: size = 3
W/SensorService(  953): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  953): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  953): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  953): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@3119c7ff, eanble = 0, strlen(mName) = 67
W/SensorService(  953): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  953): Listener[0] = com.htc.smartdim.sensor_eye@12320ff5
W/SensorService(  953): void android::SensorService::listenerSensor(const char*, int32_t)--:
,E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
,D/AlarmManager(  953): ACTION_SCREEN_OFF
,I/AlarmManager(  953): [AlarmQueuing] screen off now: 
I/AlarmManager(  953): [AlarmQueuing] data connection: true
I/AlarmManager(  953): [AlarmQueuing] wifi connection: true
E/WifiTrafficPoller(  953): ENABLE_TRAFFIC_STATS_POLL false Token 12
D/WifiDataStallTracker(  953): stopDataStallAlarm 
E/WifiDataStallTracker(  953): ENABLE_DATA_MONITOR_POLL false Token 2
E/WifiStateMachine(  953): handleMessage: E msg.what=131167
E/WifiStateMachine(  953): processMsg: ConnectedState
E/WifiStateMachine(  953):  ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  953): processMsg: L2ConnectedState
E/WifiStateMachine(  953):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  953): processMsg: ConnectModeState
,E/WifiStateMachine(  953):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  953): processMsg: DriverStartedState
E/WifiStateMachine(  953):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  953): processMsg: SupplicantStartedState
V/SRS_Proc(  451): ParamSet string: screen_state=off
E/WifiStateMachine(  953):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  953): processMsg: DefaultState
E/audio_a2dp_hw(  451): adev_set_parameters: ERROR: set param called even when stream out is null
E/WifiStateMachine(  953):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  953):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/wpa_supplicant( 1330): wlan0: Control interface command 'SET_SCREEN_ON 0'
I/wpa_supplicant( 1330): SET_SCREEN_ON:Off
,I/wpa_supplicant( 1330): htc_wext_set_keepalive +
I/wpa_supplicant( 1330): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1330): getPrivFuncNum +	
I/wpa_supplicant( 1330): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1330): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1330): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1330): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1330): htc_wext_set_keepalive - ret = 0
,D/WifiController(  953): handleMessage: E msg.what=155651
E/WifiStateMachine(  953): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
D/WifiController(  953): processMsg: DeviceActiveState
D/WifiController(  953): processMsg: StaEnabledState
D/WifiDisplayAdapter(  953): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  953):     Client/Owner: Client
D/WifiDisplayAdapter(  953):     GroupId: 
D/WifiDisplayAdapter(  953):     Passphrase: 
D/WifiDisplayAdapter(  953):     SessionId: 0
D/WifiDisplayAdapter(  953):     IP Address: }
D/WifiController(  953): processMsg: DefaultState
D/WifiController(  953): handleMessage: X
D/NetworkPolicy(  953): updateScreenOn: false
D/WifiStateMachine(  953): backgroundScan enabled=true startBackgroundScanIfNeeded:false
V/NetworkPolicy(  953): updateIfacesLocked()
E/WifiStateMachine(  953): handleScreenStateChanged Exit: false
E/WifiStateMachine(  953): handleMessage: X
E/WifiStateMachine(  953): handleMessage: E msg.what=131154
E/WifiStateMachine(  953): processMsg: ConnectedState
E/WifiStateMachine(  953):  ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  953): processMsg: L2ConnectedState
E/WifiStateMachine(  953):  L2ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  953): handleMessage: X
D/NetworkManagementService(  953): isBandwidthControlEnabled: doneSignal.getCount()= 0
,E/WifiDataStallTracker(  953): DATA_MONITOR_POLL false Token 3
,W/ContextImpl( 6571): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,I/SensorManager( 1232): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@1dacf824, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null,
W/SensorService(  953): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  953): enable: get sensor name = hTC Gesture Motion HIDI
,W/ContextImpl( 6571): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 ,
W/SensorService(  953): pid=1232, uid=10041
W/SensorService(  953): Active sensors: size = 4
W/SensorService(  953): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  953): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  953): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  953): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
,W/SensorService(  953): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@1dacf824, eanble = 1, strlen(mName) = 57
W/SensorService(  953): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  953): Listener[0] = com.htc.smartdim.sensor_eye@12320ff5
W/SensorService(  953): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@1dacf824
W/SensorService(  953): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PowerUsageList:PowerUsageHelper( 6571): MY_DEBUG = false
,D/DotMatrix( 1342): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/SmartSyncUtils( 6571): isEpsOn(), nState = 0
,D/DotMatrix( 1342): [EventService] getTotalRam: 1842 Mb
,D/GpsLocationProvider(  953): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,D/PMS     (  953): acquireWL(d6e5646): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6571 1000 null,
D/ContactMessageStore( 1556): start background delete task...
D/ContactMessageStore( 1556): size: 0 , 0
D/ContactMessageStore( 1556): Background delete complete
I/IntentController( 1232): receive(android.intent.action.SCREEN_OFF,1,false)
,D/PMS     (  953): acquireWL(16684007): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1842 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  953): releaseWL(16684007): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  953): releaseWL(d6e5646): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  953): acquireWL(1a4f9534): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1842 10024 WorkSource{10024 com.google.android.gms}
,W/ContextImpl(  953): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 
,D/SmartDim(  953): Init customizeScreenOffDelayClass error,
E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
D/PMS     (  953): releaseWL(1a4f9534): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
D/PMS     (  953): Setting HAL interactive mode to false
D/SurfaceControl(  953): Excessive delay in setPowerMode(): 295ms
,D/PMS     (  953): Setting HAL interactive mode to false done
,D/PMS     (  953): Setting HAL auto-suspend mode to true
D/PMS     (  953): Setting HAL auto-suspend mode done
,I/InputMethodManagerService(  953): screenObserver, isScreenOn=false
D/StatusBarManagerService(  953): swetImeWindowStatus vis=0 backDisposition=0
,W/InputMethodManagerService(  953): Got RemoteException sending setActive(false) notification to pid 5020 uid 10374
W/HtcSystemUPManager(  953): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
I/PhoneStatusBar( 1232): setImeWindowStatus(false,false)
,D/HABCtrl (  953): TPE algorithm. remove timeout.
D/PMS     (  953): OOBE c monitor 11
,D/PMS     (  953): acquireWL(d908f5d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 953 1000 null,
I/BatteryService(  953): n_update end
,D/PMS     (  953): releaseWL(d908f5d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  953): updateBatteryInfo
D/NotificationService(  953): plugged=true pluggin=true
D/UsbnetService(  953): BroadcastReceiver::onReceive+
D/PowerUI ( 1232): closing low battery warning: level=100
,D/UsbnetService(  953): onReceive BATTERY_CHANGED
D/UsbnetService(  953):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1232): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  953): BroadcastReceiver::onReceive-
D/PMS     (  953): runPSCheck
I/IntentController( 1232): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  953): Checking...
D/HeadsetStateMachine( 3115): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  953): >> updateStatus
D/DotMatrix( 1342): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1342): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1342): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/WifiController(  953): handleMessage: E msg.what=155652
D/WifiController(  953): battery changed pluggedType: 2
D/WifiController(  953): processMsg: DeviceActiveState
D/WifiController(  953): processMsg: StaEnabledState
D/WifiController(  953): processMsg: DefaultState
D/WifiController(  953): handleMessage: X
,I/HtcPowerSaver(  953): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  953): << updateStatus
,D/NfcService( 1572): ScreenObserver: OFF,
D/NfcService( 1572): applyRouting - 0
,D/PMS     (  953): acquireWL(112990d2): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1572 1027 null
,D/NfcService( 1572): applyRouting -2,
D/NfcService( 1572): applyRouting
D/NfcService( 1572): Ignore this applyRouting...
,D/PMS     (  953): releaseWL(112990d2): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,I/InputManager(  953): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false
,I/IntentController( 1232): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,I/RemoteViews( 1232): setHTCTheme(com.htc.updater,true,33751145)
,W/ContextImpl( 6571): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 6571): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,I/RemoteViews( 1232): apply : com.htc.updater 0 11 1 36,
,D/SmartSyncUtils( 6571): isEpsOn(), nState = 0
D/SmartSyncUtils( 6571): isEpsOn(), nState = 0
,W/ContextImpl( 6571): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,I/BatteryController( 1232): status:5 level:100 unsupport:false plugged:true
,W/ContextImpl(  953): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
,I/SensorManager(  953): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@12320ff5
W/SensorService(  953): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  953): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  953): pid=953, uid=1000
W/SensorService(  953): Active sensors: size = 3
W/SensorService(  953): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  953): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  953): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  953): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@12320ff5, eanble = 0, strlen(mName) = 36
W/SensorService(  953): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  953): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@1dacf824
,W/SensorService(  953): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  953): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  953): disable: get sensor name = CM36686 Proximity sensor
,W/SensorService(  953): pid=953, uid=1000
,W/SensorService(  953): Active sensors: size = 2
W/SensorService(  953): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  953): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  953): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@12320ff5, eanble = 0, strlen(mName) = 36
W/SensorService(  953): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  953): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@1dacf824
W/SensorService(  953): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  953): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@12320ff5
,I/ActivityManager(  953): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=6604 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a,
I/PowerUsageList:PowerUsageHelper( 6571): PowerProfile::POWER_SCREEN_FULL = 154.8
E/ActivityThread(  953): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@caba18a that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  953): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@caba18a that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  953): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  953): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread(  953): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  953): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  953): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  953): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  953): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  953): 	at android.app.Service.onStartCommand(Service.java:458)
E/ActivityThread(  953): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
E/ActivityThread(  953): 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
E/ActivityThread(  953): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
E/ActivityThread(  953): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,E/ActivityThread(  953): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  953): 	at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  953): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  953): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  953): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  953): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread(  953): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/ClockController( 1232): stop clock update:screen off
,D/PowerUsageList:BatterySipperExt( 6571): gen(), null == sipper.uidObj, userId = 0,
,D/Process (  953): killProcessQuiet, pid=5928
I/ActivityManager(  953): Killing 5928:com.htc.task/u0a69 (adj 15): empty #17
,D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
D/WifiService(  953): New client listening to asynchronous messages
D/SmartSyncUtils( 6571): getMobilePolicyEnabled, result = true
E/WifiTrafficPoller(  953): ADD_CLIENT: 8
,I/ActivityManager(  953): Recipient 5928
,D/PowerUsageList:PowerUsageHelper( 6571): MY_DEBUG = false
,D/Process (  953): killProcessQuiet, pid=6417,
I/ActivityManager(  953): Killing 6417:com.nero.android.htc.sync/u0a5 (adj 15): empty #17
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiTrafficPoller(  953): TRAFFIC_STATS_POLL false Token 13 num clients 8,
,D/PMS     (  953): releaseWL(2ef32b53): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null,
,I/ActivityManager(  953): Recipient 6417
D/WifiService(  953): Client connection lost with reason: 4
,E/WifiStateMachine(  953): handleMessage: E msg.what=131155,
E/WifiStateMachine(  953): processMsg: ConnectedState
E/WifiStateMachine(  953):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:562180512] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  953): processMsg: L2ConnectedState
E/WifiStateMachine(  953):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:562180514] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  953): handleMessage: X
,E/WifiStateMachine(  953): handleMessage: E msg.what=131155,
E/WifiStateMachine(  953): processMsg: ConnectedState
,E/WifiStateMachine(  953):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1681] from screen [on:0 period:562182196] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
E/WifiStateMachine(  953): processMsg: L2ConnectedState
E/WifiStateMachine(  953):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:562182200] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine(  953): handleMessage: X
,D/HtcUPManager( 1232): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60,
,E/WifiDataStallTracker(  953): DATA_MONITOR_POLL false Token 3,
,D/ContactMessageStore( 1556): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1556): MSG_NOTIFY_CS_TO_SYNC <<
,W/Atfwd_Sendcmd(  475): AtCmdFwd service not published, waiting... retryCnt : 1,
,W/Atfwd_Sendcmd(  475): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/Process (  953): killProcessQuiet, pid=5995
,I/ActivityManager(  953): Killing 5995:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  953): Recipient 5995
,D/PMS     (  953): acquireWL(64bc459): PARTIAL_WAKE_LOCK  *alarm* 0x1 953 1000 WorkSource{10024},
V/AlarmManager(  953): sending alarm PendingIntent{39ebe81e: PendingIntentRecord{2f5f28ff com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=143840, Int=0
,D/PMS     (  953): releaseWL(64bc459): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024},
,W/Atfwd_Sendcmd(  475): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  953): [handleMessage] DOWNLOAD_XTRA_DATA
D/PMS     (  953): acquireWL(1e3c56cc): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 953 1000 null
D/GpsLocationProvider(  953): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/libc    (  953): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4,
D/libc    (  953): [NET] android_getaddrinfofornet-, err=8
D/libc    (  953): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024,
D/libc    (  953): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  953): [NET] android_getaddrinfo_proxy+
,D/libc    (  953): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  400): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  400): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  953): [NET] android_getaddrinfo_proxy-, success
D/libc    (  953): [NET] android_getaddrinfofornet+,hn 14(0x35342e3233302e),sn(),hints(known),family 0,flags 4
D/libc    (  953): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  953): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/GpsLocationProvider(  953): [reportHTCStatus] eventMask = 3 , status = 0,
D/GpsLocationProvider(  953): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/GpsLocationProvider(  953):  [handleDownloadXtraData]inject done.
D/GpsLocationProvider(  953): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
D/PMS     (  953): acquireWL(383e13b8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 953 1000 null
D/PMS     (  953): releaseWL(1e3c56cc): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
,D/PMS     (  953): releaseWL(383e13b8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  953): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,W/Atfwd_Sendcmd(  475): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  953): acquireWL(14c0a591): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 953 1000 null
I/BatteryService(  953): n_update end
D/PMS     (  953): releaseWL(14c0a591): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/NotificationService(  953): plugged=true pluggin=true
D/UsbnetService(  953): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  953): updateBatteryInfo
D/UsbnetService(  953): onReceive BATTERY_CHANGED
D/WifiController(  953): battery changed pluggedType: 2
D/UsbnetService(  953):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  953): runPSCheck
D/UsbnetService(  953): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  953): Checking...
D/WifiController(  953): handleMessage: E msg.what=155652
I/HtcPowerSaver(  953): >> updateStatus
D/WifiController(  953): processMsg: DeviceActiveState
D/WifiController(  953): processMsg: StaEnabledState
D/WifiController(  953): processMsg: DefaultState
D/WifiController(  953): handleMessage: X
I/IntentController( 1232): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1342): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1342): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1342): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3115): Disconnected process message: 10, size: 0
D/PowerUI ( 1232): closing low battery warning: level=100
D/PowerUI ( 1232): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  953): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  953): << updateStatus
,I/BatteryController( 1232): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  475): AtCmdFwd service not published, waiting... retryCnt : 5
,D/TelephonyReceiver( 1556): switchBindHtcMsgCursor: null,
,D/PMS     (  953): acquireWL(279edcf6): PARTIAL_WAKE_LOCK  *alarm* 0x1 953 1000 WorkSource{1000},
D/PMS     (  953): acquireWL(223b38f7): PARTIAL_WAKE_LOCK  *backup* 0x1 953 1000 null,
,V/AlarmManager(  953): sending alarm PendingIntent{249cb364: PendingIntentRecord{38b909cd android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1452261178272, Int=0,
V/AlarmManager(  953): sending alarm PendingIntent{2c407186: PendingIntentRecord{dab5a47 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=168189, Int=0
V/AlarmManager(  953): sending alarm PendingIntent{2953d282: PendingIntentRecord{35606d93 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=169331, Int=0
,V/AlarmManager(  953): sending alarm PendingIntent{2e23a1d0: PendingIntentRecord{375975c9 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=193768, Int=0
W/BackupManagerService(  953): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  953): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  953): releaseWL(223b38f7): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/PMS     (  953): acquireWL(357094ce): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1986 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): releaseWL(279edcf6): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/WeatherUtility( 1232): Weather sync is On
W/WeatherTimeKeeper( 1232): [refreshWeatherData] no weather data
,D/PMS     (  953): acquireWL(339a4fef): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1986 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): releaseWL(357094ce): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1986): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/PMS     (  953): releaseWL(339a4fef): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): acquireWL(12c51501): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1986 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): releaseWL(12c51501): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  953): acquireWL(a166fa6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1986 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): releaseWL(a166fa6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): acquireWL(21f64de7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1986 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): acquireWL(2945bd94): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1986 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): acquireWL(1529e032): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1986 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): releaseWL(21f64de7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/VacuumService( 1986): Vacuum at: now=1452261205834 tag=VacuumService
,D/PMS     (  953): releaseWL(2945bd94): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  953): acquireWL(368b1f00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1986 10024 WorkSource{10024 com.google.android.gms},
I/GoogleURLConnFactory( 1986): Using platform SSLCertificateSocketFactory
,D/PMS     (  953): releaseWL(368b1f00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  953): acquireWL(16ae6339): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1986 10024 WorkSource{10024 com.google.android.gms},
,W/Uploader( 1986): No account for auth token provided,
,D/PMS     (  953): releaseWL(16ae6339): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/libc    ( 1986): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1986): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1986): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 1986): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1986): [NET] android_getaddrinfo_proxy+
D/libc    ( 1986): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  400): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  400): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1986): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1986): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 1986): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1986): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1986): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1986): No account for auth token provided,
,W/Uploader( 1986): No account for auth token provided,
,W/Uploader( 1986):  no longer exists, so no auth token.,
,W/Uploader( 1986): No account for auth token provided,
,W/Uploader( 1986): No account for auth token provided,
,I/GLSUser ( 1986): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1986): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1986): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1986): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1986): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1986): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1986): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1986): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1986): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1986): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1986): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1986): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1986): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1986): ,	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1986): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1986): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1986): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1986): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/RemoteViews( 1232): reapply : com.google.android.gms 3 40
D/DotMatrix( 1342): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1342): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/PMS     (  953): releaseWL(1529e032): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  953): acquireWL(2d36b9e2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1986 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): releaseWL(2d36b9e2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  953): acquireWL(13bc3173): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1986 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): releaseWL(13bc3173): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/HtcUPManager( 1232): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
D/HtcUPManager( 1232): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,D/HtcAppUPService( 1643): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@1687f12f
D/Process (  953): killProcessQuiet, pid=6285
I/ActivityManager(  953): Killing 6285:com.htc.calendar/u0a10 (adj 15): empty #17
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  953): Recipient 6285,
,TIME-OUT KILL (timeout was 150000ms)
```
