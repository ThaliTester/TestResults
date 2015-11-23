#### Test 503880197c51433_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
D/GCM     ( 1873): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 1873): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 4506): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
D/libc    ( 4834): [NET] android_getaddrinfofornet+,hn 48(0x6874632d636c75),sn(),hints(known),family 0,flags 4
D/libc    ( 4834): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4834): [NET] android_getaddrinfofornet+,hn 48(0x6874632d636c75),sn(),hints(known),family 0,flags 1024
D/libc    ( 4834): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4834): [NET] android_getaddrinfo_proxy+
D/libc    ( 4834): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 48(0x6874632d636c75),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
E/WifiTrafficPoller(  947): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  947):  packet count Tx=48 Rx=98
--------- beginning of system
I/ActivityManager(  947): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=4864 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
I/PackageManager(  947):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4506, uid=10024, userID:0
D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4834): [NET] android_getaddrinfo_proxy-, success
D/libc    ( 4834): [NET] android_getaddrinfofornet+,hn 13(0x35342e3233312e),sn(),hints(known),family 0,flags 4
D/libc    ( 4834): [NET] android_getaddrinfofornet-, SUCCESS
W/ResourcesManager( 4864): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4864): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/TelephUtils( 1444): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 49
D/AccFlag ( 1444): sku_id=118
I/MultiDex( 4864): VM with version 2.1.0 has multidex support
I/MultiDex( 4864): install
I/MultiDex( 4864): VM has multidex support, MultiDex support library is disabled.
I/ActivityManager(  947): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=4893 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/LocationInitializer( 4506): Restart initialization of location
D/TelephUtils( 1444): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 50
D/AccFlag ( 1444): sku_id=118
D/libc    ( 4834): [NET] android_getaddrinfofornet+,hn 3,sn(),hints(known),family 0,flags 4
D/libc    ( 4834): [NET] android_getaddrinfofornet-, err=8
I/art     (  406): Explicit concurrent mark sweep GC freed 8684(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 165us total 20.813ms
V/JNIHelp ( 4864): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/art     (  406): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 139us total 16.772ms
I/art     (  406): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 172us total 17.604ms
D/TelephUtils( 1444): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 49
D/AccFlag ( 1444): sku_id=118
D/TelephUtils( 1444): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 50
D/AccFlag ( 1444): sku_id=118
W/ActivityThread( 4864): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 4864): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1a07d119: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4864): Installed default security provider GmsCore_OpenSSL
I/art     ( 1873): Explicit concurrent mark sweep GC freed 13346(774KB) AllocSpace objects, 3(252KB) LOS objects, 49% free, 4MB/8MB, paused 794us total 60.405ms
I/GLSUser ( 1873): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
I/GLSUser ( 1873): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1873): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1873): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1873): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/WearableService( 4864): callingUid 10024, callindPid: 4864
E/MDM     ( 1848): [142] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/RemoteViews( 1224): reapply : com.google.android.gms 1 40
D/DotMatrix( 1308): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1308): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/Search.LoginHelper( 4762): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 4762): com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
W/Search.LoginHelper( 4762): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 4762): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4762): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4762): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 4762): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 4762): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 4762): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 4762): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 4762): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 4762): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4762): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 4762): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4762): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 4762): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 4762): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 4762): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
E/VelvetNetworkClient( 4762): Failed to get auth token
I/MusicStore( 4893): Database version: 120
D/VoldConnector(  947): SND -> {17 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 4893): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
D/VoldConnector(  947): SND -> {18 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 4893): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
D/VoldConnector(  947): SND -> {19 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 4893): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/ResourcesManager( 4893): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4893): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4893): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
W/ActivityThread( 4893): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 4893): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@b0a04bb: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4893): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 4893): GMSCore installation verified
I/ConfigStore( 4893): Config Database version: 1
D/ContactMessageStore( 1444): MSG_NOTIFY_CS_TO_SYNC >>
D/ContactMessageStore( 1444): MSG_NOTIFY_CS_TO_SYNC <<
E/WifiDataStallTracker(  947): DATA_MONITOR_POLL true Token 1
I/PackageManager(  947):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4893, uid=10159, userID:0
D/WifiDataStallTracker(  947): updateDataStallInfo: mDataStallTxRxSum={txSum=40 rxSum=32} preTxRxSum={txSum=21 rxSum=16}
D/WifiDataStallTracker(  947): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  947): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
D/WifiDisplayAdapter(  947): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  947):     Client/Owner: Client
D/WifiDisplayAdapter(  947):     GroupId: 
D/WifiDisplayAdapter(  947):     Passphrase: 
D/WifiDisplayAdapter(  947):     SessionId: 0
D/WifiDisplayAdapter(  947):     IP Address: }
D/MediaRouterService(  947): Client com.google.android.music (pid 4893): Registered
D/WifiDisplayAdapter(  947): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  947):     Client/Owner: Client
D/WifiDisplayAdapter(  947):     GroupId: 
D/WifiDisplayAdapter(  947):     Passphrase: 
D/WifiDisplayAdapter(  947):     SessionId: 0
D/WifiDisplayAdapter(  947):     IP Address: }
I/MediaRouter( 4893): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
V/MusicLeanback( 4893): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 4893): type=WIFI subType= reason=null isConnected=true
E/WifiTrafficPoller(  947): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  947):  packet count Tx=55 Rx=104
W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 4
I/NetworkMonitor( 4893): type=WIFI subType= reason=null isConnected=true
I/PackageManager(  947):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=4893, uid=10159, userID:0
I/ActivityManager(  947): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=4936 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
I/GHttpClientFactory( 4893): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 4893): Using platform SSLCertificateSocketFactory
D/PMS     (  947): releaseWL(c3972ab): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 null
E/cutils-trace( 4927): Error opening trace file: Permission denied (13)
I/ActivityManager(  947): Killing 4257:com.htc.backupreset/1000 (adj 15): empty #17
D/Process (  947): killProcessQuiet, pid=4257
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
W/ResourcesManager( 4936): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/CustomizationManager( 4927): ====startRecUseTime====
D/htc.customization.log.level( 4927):  is 
W/CustomizationLogLevel( 4927): Level value is invalid, use default level 2
I/ActivityManager(  947): Recipient 4257
D/CustomizationManager( 4927):  Read ACC file spent 0.062 (s)
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
D/CustomizationManager( 4927):  Read CID file spent 0.103 (s)
D/CustomizationManager( 4927):  All configurations done spent 0.103 (s)
I/CalendarProvider2( 4936): Created com.android.providers.calendar.CalendarAlarmManager@1b4a8ff7(com.htc.providers.calendar.HtcCalendarProvider@26a6be64)
D/CalendarProvider2( 4936): wait start:true
I/ActivityManager(  947): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 pid 4927 on display 0
W/asset   (  947): Copying FileAsset 0x5589fcb290 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/PMS     (  947): acquireHCC(48dc827): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 947 1000 null
D/PMS     (  947): acquireHCC(18844ad4): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 947 1000 null
D/PMS     (  947): acquireWL(3318a47d): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 947 1000 null
I/FeedHostManager( 1506): [onPause]
I/FeedProviderManager( 1506): onPause
I/FeedHostManager( 1506): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@a8cdb5a
I/SocialFeedProvider( 1506): +onPause
I/SocialFeedProvider( 1506): -onPause
I/AnimationUtil(  947): isHTCRecent(HelloWorld/Recent screens.)/7
W/HtcSystemUPManager(  947): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  947): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4978 uid=10373 gids={50373, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/CalendarProvider2( 4936): wait end:false
W/asset   ( 4978): Copying FileAsset 0xac901d20 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/AutoSetting( 1587): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  947): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=5002 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a
D/AutoSetting( 1587): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1587): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1587): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1587): service - onStartCommand() REMOVE current location bundle
D/AutoSetting( 1587): service - handleMessage() setting current location null
D/StatusBarManagerService(  947): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  947): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  947): hiding MENU key
I/TrimMemoryManager( 1506): [trimMemory] 20
,D/PhoneMonitor( 5002): Register our PhoneStateListener
I/WebViewFactory( 4978): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
D/MobileConnectivityChangeReceiver( 5002): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 5002): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  947): Killing 4285:com.htc.htccupd/u0a13 (adj 15): empty #17
D/Process (  947): killProcessQuiet, pid=4285
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
D/PhoneMonitor( 5002): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
D/PhoneMonitor( 5002): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/LibraryLoader( 4978): Time to load native libraries: 10 ms (timestamps 35-45)
I/LibraryLoader( 4978): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 4978): Binding Chromium to main looper Looper (main, tid 1) {1b4a8ff7}
I/LibraryLoader( 4978): Expected native library version number "",actual native library version number ""
I/chromium( 4978): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4978): Initializing chromium process, singleProcess=true
W/art     ( 4978): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4978): ApplicationContext is null in ApplicationStatus
I/ActivityManager(  947): Recipient 4285
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
W/System.err(  947): java.lang.Throwable: stack dump
D/BluetoothManagerService(  947): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  947): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2f493970:true
W/System.err(  947): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  947): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  947): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  947): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothAdapter( 4978): 1070466: getState(). Returning 12
D/PMS     (  947): acquireWL(2c95dea0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4506 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  947): acquireWL(2680a61e): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4506 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  947): releaseWL(2c95dea0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
I/CheckinService( 4506): Checking schedule, now: 1448298983090 next: 1448298779413
I/CheckinService( 4506): active receiver: enabled
I/PackageManager(  947):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=4506, uid=10024, userID:0
I/CheckinService( 4506): Preparing to send checkin request
I/EventLogService( 4506): Accumulating logs since 1448298746914
W/art     ( 4978): Attempt to remove local handle scope entry from IRT, ignoring
E/WifiTrafficPoller(  947): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  947):  packet count Tx=55 Rx=104
E/WifiTrafficPoller(  947): notifying of data activity 0
D/WIFI_ICON( 1224): WifiActivity: 0
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/PackageManager(  947):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4506, uid=10024, userID:0
W/AwContents( 4978): onDetachedFromWindow called when already detached. Ignoring
I/iu.SyncManager( 4506): SYNC; picasa accounts
D/SystemWebViewEngine( 4978): CordovaWebView is running on device made by: HTC
D/NetworkLogImpl( 4506): Loaded NetworkSpeedPredictor
I/iu.Environment( 4506): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
W/art     ( 4978): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4978): Attempt to remove local handle scope entry from IRT, ignoring
I/iu.UploadsManager( 4506): num queued entries: 0
I/iu.UploadsManager( 4506): num updated entries: 0
I/iu.SyncManager( 4506): NEXT; no task
D/ChimeraCfgMgr( 4506): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/ChimeraCfgMgr( 4506): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/ActivityManager(  947): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5057 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/libc    ( 4606): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 4606): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4606): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 4606): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4606): [NET] android_getaddrinfo_proxy+
D/libc    ( 4606): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4606): [NET] android_getaddrinfo_proxy-, success
I/Babel   ( 4606): connection state changed from UNKNOWN to CONNECTED
I/art     (  947): Explicit concurrent mark sweep GC freed 12768(657KB) AllocSpace objects, 2(104KB) LOS objects, 33% free, 16MB/24MB, paused 1.631ms total 162.913ms
I/HtcModeClient( 3268): handler message = 4011
E/HtcModeClient( 3268): Check connection and retry 4 times.
W/chromium( 4978): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/CheckinRequestBuilder( 4506): Checkin reason type: 8 attempt count: 1
E/WifiTrafficPoller(  947): ADD_CLIENT: 7
D/WifiService(  947): New client listening to asynchronous messages
I/ActivityManager(  947): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4506): Failed to find provider info for com.google.android.wearable.settings
I/GLSUser ( 1873): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1873): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1873): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1873): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1873): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/FindExtension( 4978): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
W/Kids    ( 4506): [AccountUtils] Account not ready
W/Kids    ( 4506): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4506): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4506): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4506): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4506): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4506): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4506): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4506): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4506): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4506): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4506): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4506): 	at java.lang.Thread.run(Thread.java:818)
D/DotMatrix( 1308): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1308): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1224): reapply : com.google.android.gms 2 40
I/art     ( 4506): Explicit concurrent mark sweep GC freed 23005(1789KB) AllocSpace objects, 22(440KB) LOS objects, 47% free, 4MB/8MB, paused 1.535ms total 59.279ms
I/CalendarProvider2( 4936): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
W/ContentResolver( 4936): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
D/Process (  947): killProcessQuiet, pid=4352
I/ActivityManager(  947): Killing 4352:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/InputMethodManager( 4978): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@378f9a00, mServedView=org.apache.cordova.engine.SystemWebView{510c239 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@3466407e
I/InputMethodManagerService(  947): Disable input method client, pid=1506
D/StatusBarManagerService(  947): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  947): Enable input method client, pid=4978
I/PhoneStatusBar( 1224): setImeWindowStatus(false,false)
W/BindingManager( 4978): Cannot call determinedVisibility() - never saw a connection for the pid: 4978
I/chromium( 4978): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
I/ActivityManager(  947): Recipient 4352
W/XT9_C   ( 1382): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1382): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1382): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1382): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
E/WifiStateMachine(  947): handleMessage: E msg.what=131155
E/WifiStateMachine(  947): processMsg: ConnectedState
E/WifiStateMachine(  947):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2462 sc=60 link=72 tx=6.7, 0.0, 0.0  rx=10.4 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:895004945] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  947): processMsg: L2ConnectedState
E/WifiStateMachine(  947):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2462 sc=60 link=72 tx=6.7, 0.0, 0.0  rx=10.4 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:895004945] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  947):  get link layer stats 0
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1371): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1371): environment dirty rate=15 [13][2][0]
E/WifiStateMachine(  947): fetchRssiLinkSpeedAndFrequencyNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  947): fetchRssiLinkSpeedAndFrequencyNative rssi=-58 linkspeed=72
E/WifiConfigStore(  947): updateConfiguration freq=2462 BSSID=c0:ff:d4:d3:aa:48 RSSI=-58 "NG700"WPA_PSK
E/WifiStateMachine(  947): calculateWifiScore freq=2462 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=9.83 txretriesrate=0.00 rxrate=10.22 userTriggerdPenalty0
E/WifiStateMachine(  947):  good link -> stuck count =0
E/WifiStateMachine(  947):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  947):  isHighRSSI       ---> score=65
D/JsMessageQueue( 4978): Set native->JS mode to OnlineEventsBridgeMode
E/AndroidProtocolHandler( 4978): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/PMS     (  947): releaseWL(3318a47d): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/ActivityManager(  947): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=5088 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
V/AlarmManager(  947): sending alarm PendingIntent{268b4dda: PendingIntentRecord{2ba4c20b com.htc.mobiledata startService}}, i=com.htc.mobiledata.intent.REQUEST, t=2, cnt=1, w=60787, Int=0
I/ActivityManager(  947): Waited long enough for: ServiceRecord{6c01f20 u0 com.htc.HTCSpeaker/.NGFService}
D/WifiWatchdogStateMachine(  947): RSSI current: 3 new: -58, 3
E/WifiStateMachine(  947): handleMessage: X
D/WIFI_ICON( 1224): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/ActivityManager(  947): Displayed com.example.hello/.MainActivity: +1s264ms
D/jxcore_app_log( 4978): JniHelper::setJavaVM(0xab7938f8), pthread_self() = -1398057216
D/JX-Cordova( 4978): jxcore cordova android initializing
I/ActivityManager(  947): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=5114 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
W/jxcore-log( 4978): Initializing JXcore engine
W/jxcore-log( 4978): JXcore engine is ready
W/jxcore-log( 4978): Starting JXcore engine
W/ContextImpl( 5057): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
D/VoldConnector(  947): SND -> {20 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
D/VoldConnector(  947): SND -> {21 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl( 5057): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 5057): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5057):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5057):   adb logcat -s GAv4
,D/VoldConnector(  947): SND -> {22 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 5057): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  947): SND -> {23 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl( 5057): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 5057): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 5057): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5057): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,D/MdScBoot( 5088): [d1b.1.] 30@-171553 -> 40
,D/MdScBootUi( 5088): [d1b.1.2.] boot 118,
,D/MdScSimSt( 5088): [d1b.1.2.] qry 118: 0+1 running 0
,I/GLSUser ( 1873): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1873): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1873): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1873): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1873): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/CheckinRequestBuilder( 4506): awaiting user notification for token
,D/DotMatrix( 1308): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1308): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1224): reapply : com.google.android.gms 2 40
,W/global  ( 5057): [apache-http] Connection GC has been deprecated!
,W/global  ( 5057): [apache-http] Connection GC has been deprecated!,
,E/WifiTrafficPoller(  947): TRAFFIC_STATS_POLL true Token 11 num clients 7
,D/WIFI_ICON( 1224): WifiActivity: 3
E/WifiTrafficPoller(  947):  packet count Tx=60 Rx=108
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiTrafficPoller(  947): notifying of data activity 3
,W/jxcore-log( 4978): Platform android
W/jxcore-log( 4978): 
W/jxcore-log( 4978): Process ARCH arm
W/jxcore-log( 4978): 
,I/ActivityManager(  947): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5158 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,D/Process (  947): killProcessQuiet, pid=4376,
I/ActivityManager(  947): Killing 4376:com.android.settings:remote/1000 (adj 15): empty #17
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/jxcore-log( 4978): JXcore Cordova bridge is ready!
I/jxcore-log( 4978): 
W/jxcore-log( 4978): JXcore engine is started
,E/jxcore-log( 4978): >> HTC-HTC One M8s,
E/jxcore-log( 4978): 
I/jxcore-log( 4978): Total memory 1931808768
I/jxcore-log( 4978): 
,I/jxcore-log( 4978): Free memory 85487616
I/jxcore-log( 4978): 
I/jxcore-log( 4978): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4978): 
I/jxcore-log( 4978): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4978): 
,I/jxcore-log( 4978): userPath [ 'www' ]
I/jxcore-log( 4978): 
,I/jxcore-log( 4978): Size 1080 1776
I/jxcore-log( 4978): 
,I/jxcore-log( 4978): Screen Brightness 142
I/jxcore-log( 4978): 
E/jxcore-log( 4978): Dummy Error Log.
E/jxcore-log( 4978): 
,I/ActivityManager(  947): Recipient 4376,
,I/ActivityManager(  947): Killing 4400:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17,
D/Process (  947): killProcessQuiet, pid=4400
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/ResourcesManager( 5158): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5158): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 5158): VM with version 2.1.0 has multidex support
I/MultiDex( 5158): install
,I/MultiDex( 5158): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  947): Recipient 4400
,I/WebViewFactory( 5057): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,V/JNIHelp ( 5158): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,D/PMS     (  947): releaseHCC(48dc827): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,D/PMS     (  947): releaseHCC(18844ad4): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/ActivityThread( 5158): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 5158): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1a07d119: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5158): Installed default security provider GmsCore_OpenSSL
,I/LibraryLoader( 5057): Time to load native libraries: 24 ms (timestamps 1747-1771),
I/LibraryLoader( 5057): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5057): Binding Chromium to main looper Looper (main, tid 1) {36cc9378},
,I/LibraryLoader( 5057): Expected native library version number "",actual native library version number "",
,I/chromium( 5057): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5057): Initializing chromium process, singleProcess=true,
W/art     ( 5057): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5057): ApplicationContext is null in ApplicationStatus
,W/chromium( 5057): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,I/WVCdm   (  400): CdmEngine::OpenSession,
I/WVCdm   (  400): Level3 Library Sep 25 2014 17:10:03
E/libEGL  ( 5057): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5057): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5057): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 5057): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 5057): Build Date: 03/09/15 Mon
I/Adreno-EGL( 5057): Local Branch: 
I/Adreno-EGL( 5057): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 5057): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 5057):                  d74aa161a12b9c6fc6332151
,W/WVCdm   (  400): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  400): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  400): Service_Initialize: starts!
,D/QSEECOMAPI: (  400): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  400): App is not loaded in QSEE
E/QSEECOMAPI: (  400): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  400): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  400): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  400): App is not loaded in QSEE
,I/jxcore-log( 4978): getBuffer is called!!!!
I/jxcore-log( 4978): 
,I/GAV2    ( 4721): Thread[GAThread,5,main]: No campaign data found.
,D/QSEECOMAPI: (  400): Loaded image: APP id = 6
,D/DrmWidevineDash(  400): Service_Initialize: ends! returns 0
,D/QSAPPSVER(  400): qsapps_get_capabilities: Capability from secure side: 0x0
D/QSAPPSVER(  400): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  400): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4b79000
E/DrmWidevineDash(  400): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4b79000
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/DrmLibTime(  488): got the req here! ret=0
,D/DrmLibTime(  488): command id, time_cmd_id = 770
D/DrmLibTime(  488): time_getutcsec starts!
D/DrmLibTime(  488): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  488): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  488): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  488): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  488): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  488): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  488): QSEE Time Listener: Retrieved Android system time: 1448298984
D/DrmLibTime(  488): time_getutcsec returns 0, sec = 1448298984; nsec = 0
D/DrmLibTime(  488): time_getutcsec finished! 
D/DrmLibTime(  488): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  488): before calling ioctl to read the next time_cmd
E/QC-time-services(  422): Daemon: Time-services: Waiting to acceptconnection
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
I/GAv4-SVC( 4506): Google Analytics 7.8.99 is starting up.
,W/AudioManagerAndroid( 5057): Requires BLUETOOTH permission
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  400): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  400): OEMCrypto_OpenSession: starts! SID=0xffa3aec8
D/DrmWidevineDash(  400): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  400): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  400): OEMCrypto_GetRandom: starts! randomData=0xab2e7008, dataLength=8
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_GetRandom: ends! returns 0
,I/NSApplication( 5057): Starting up...
,D/DrmWidevineDash(  400): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab2b6aa8, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  400): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  400): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  400): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  400): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  400): OEMCrypto_GetDeviceID: starts! deviceID=0xab31a5b8, idLength=0xf4ca26f8
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,I/ActivityManager(  947): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=5205 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a,
D/Process (  947): killProcessQuiet, pid=4423
I/ActivityManager(  947): Killing 4423:com.android.smith/1000 (adj 15): empty #17
,D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  400): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  400): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  400): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  400): OEMCrypto_GetHDCPCapability: starts!, current = 0xf4ca270e, maximum = 0xf4ca270f
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  400): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): hlos api version =  9
D/DrmWidevineDash(  400): tz api version =  9
D/DrmWidevineDash(  400): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  400): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf4ca277c
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  400): PrepareKeyRequest: nonce=3092858894
D/DrmWidevineDash(  400): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab31dcb0
D/DrmWidevineDash(  400): message_length=1611, signature=0xab31e300, signature_length=0xf4ca26dc
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,I/ActivityManager(  947): Recipient 4423
,D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
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
,D/QSEECOMAPI: (  400): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  400): QSEECom_shutdown_app, app_id = 6
D/DrmWidevineDash(  400): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  400): OEMCrypto_Terminate: ends! returns 0
,E/WifiTrafficPoller(  947): TRAFFIC_STATS_POLL true Token 11 num clients 7
,E/WifiTrafficPoller(  947):  packet count Tx=60 Rx=108
E/WifiTrafficPoller(  947): notifying of data activity 0
D/WIFI_ICON( 1224): WifiActivity: 0
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/Process (  947): killProcessQuiet, pid=4333,
I/ActivityManager(  947): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=5231 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  947): Killing 4333:com.android.settings/1000 (adj 15): empty #17
,E/cutils-trace( 5251): Error opening trace file: Permission denied (13)
,I/dex2oat ( 5251): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=36 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 5251): dex2oat: override thread count:4
,I/ActivityManager(  947): Recipient 4333,
,W/ResourcesManager( 5231): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/dex2oat ( 5251): dex2oat took 81.298ms (threads: 4),
,I/Adreno-EGL( 5158): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 5158): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 5158): Build Date: 03/09/15 Mon
I/Adreno-EGL( 5158): Local Branch: 
I/Adreno-EGL( 5158): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 5158): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 5158):                  d74aa161a12b9c6fc6332151
,I/art     ( 5158): Background sticky concurrent mark sweep GC freed 1997(227KB) AllocSpace objects, 0(0B) LOS objects, 8% free, 3MB/4MB, paused 12.365ms total 32.106ms,
,I/Adreno-EGL( 5158): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 5158): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 5158): Build Date: 03/09/15 Mon
I/Adreno-EGL( 5158): Local Branch: 
I/Adreno-EGL( 5158): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 5158): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 5158):                  d74aa161a12b9c6fc6332151
,I/WVCdm   (  400): CdmEngine::OpenSession,
I/WVCdm   (  400): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  400): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  400): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15,
D/DrmWidevineDash(  400): Service_Initialize: starts!
D/QSEECOMAPI: (  400): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  400): App is not loaded in QSEE
E/QSEECOMAPI: (  400): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  400): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  400): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  400): App is not loaded in QSEE
,D/QSEECOMAPI: (  400): Loaded image: APP id = 7,
D/DrmWidevineDash(  400): Service_Initialize: ends! returns 0
,D/QSAPPSVER(  400): qsapps_get_capabilities: Capability from secure side: 0x0,
D/QSAPPSVER(  400): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  400): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4b79000
E/DrmWidevineDash(  400): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4b79000
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/DrmLibTime(  488): got the req here! ret=0,
D/DrmLibTime(  488): command id, time_cmd_id = 770
D/DrmLibTime(  488): time_getutcsec starts!
,D/DrmLibTime(  488): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  488): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  488): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  488): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  488): Receive Passed == base = 13, unit = 1, operation = 2, result = 0,
D/DrmLibTime(  488): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  488): QSEE Time Listener: Retrieved Android system time: 1448298985
D/DrmLibTime(  488): time_getutcsec returns 0, sec = 1448298985; nsec = 0
D/DrmLibTime(  488): time_getutcsec finished! 
,D/DrmLibTime(  488): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  488): before calling ioctl to read the next time_cmd
E/QC-time-services(  422): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  400): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  400): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): hlos api version =  9
D/DrmWidevineDash(  400): tz api version =  9
D/DrmWidevineDash(  400): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  400): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  400): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  400): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  400): OEMCrypto_OpenSession: starts! SID=0xf3ebd928
,D/DrmWidevineDash(  400): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  400): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  400): OEMCrypto_GetRandom: starts! randomData=0xab2ce340, dataLength=8
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  400): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab2e9820, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  400): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  400): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  400): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  400): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  400): OEMCrypto_GetDeviceID: starts! deviceID=0xab31a5f8, idLength=0xf4ca26f8
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  400): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  400): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_SupportsUsageTable: is_supported = 1,
D/DrmWidevineDash(  400): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  400): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  400): OEMCrypto_GetHDCPCapability: starts!, current = 0xf4ca270e, maximum = 0xf4ca270f
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  400): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  400): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): hlos api version =  9
D/DrmWidevineDash(  400): tz api version =  9
D/DrmWidevineDash(  400): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  400): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf4ca277c
,D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  400): PrepareKeyRequest: nonce=1659673690
D/DrmWidevineDash(  400): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab31dcb0
D/DrmWidevineDash(  400): message_length=1646, signature=0xab31e328, signature_length=0xf4ca26dc
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,I/ActivityManager(  947): Killing 4481:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  947): killProcessQuiet, pid=4481
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  400): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  400): CdmEngine::CloseSession
D/DrmWidevineDash(  400): OEMCrypto_CloseSession: starts! SID=1
,D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  400): L3 Terminate.
D/DrmWidevineDash(  400): OEMCrypto_Terminate: starts!
,D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): Service_Uninitialize: starts!
D/QSEECOMAPI: (  400): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  400): QSEECom_shutdown_app, app_id = 7
D/DrmWidevineDash(  400): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  400): OEMCrypto_Terminate: ends! returns 0
,I/CheckinRequestBuilder( 4506): Classify the device as Phone.
,I/ActivityManager(  947): Recipient 4481,
,I/ActivityManager(  947): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=5273 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a,
,I/SocialFeedProvider( 1506): +disConnect socialManager
,I/SocialFeedProvider( 1506): disconnect socialManager
,I/SocialFeedProvider( 1506): -disConnect socialManager,
,I/art     ( 1873): Explicit concurrent mark sweep GC freed 10795(564KB) AllocSpace objects, 8(672KB) LOS objects, 49% free, 4MB/8MB, paused 930us total 69.898ms
,V/AlarmManager(  947): sending alarm PendingIntent{3d016b53: PendingIntentRecord{3d802c90 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1448298986116, Int=0
,E/WifiTrafficPoller(  947): TRAFFIC_STATS_POLL true Token 11 num clients 7
D/WIFI_ICON( 1224): WifiActivity: 1
E/WifiTrafficPoller(  947):  packet count Tx=60 Rx=109
E/WifiTrafficPoller(  947): notifying of data activity 1
,D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/libc    ( 4506): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4506): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 4506): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024,
D/libc    ( 4506): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4506): [NET] android_getaddrinfo_proxy+
D/libc    ( 4506): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,I/ImageRamCache( 5273): create image Cache, size: 31457280.
,I/ImageRamCache( 5273): [resize] ImageRamCache resized to: 30Mb.
,I/ImageRamCache( 5273): create image Cache, size: 31457280.
,I/FeedSettings( 5273): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true,
I/FeedSettings( 5273): GroupBudget 0.500000 0.380000
I/FeedSettings( 5273): GroupBudget 60 45 15,
,I/Prism.ExternalStringMa_( 5273): changeLocale(): en_GB,
,I/Prism.AllAppsOptionsMa_( 5273): loadSortType() with Custom,
I/Prism.AllAppsOptionsMa_( 5273): loadGridSize() with Alternative
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4506): [NET] android_getaddrinfo_proxy-, success
,D/CustomHighlightReceiver( 5273): [custom highlight] onReceive
,I/ActivityManager(  947): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=5301 uid=10035 gids={50035, 9997} abi=arm64-v8a,
,I/SocialManager[SocialBiLogHelper]( 5273): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 5273): last commit ulog time 1448258067684
,I/SocialManager[SocialBiLogHelper]( 5273): skip commit this time
,D/CustomHighlightService( 5273): [custom highlight] onHandleIntent,
D/libc    ( 4506): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4506): [NET] android_getaddrinfofornet-, err=8
,D/NewsDB  ( 5273): set custom highlight []
,D/libc    ( 4506): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4506): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 4506): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4506): [NET] android_getaddrinfofornet-, err=8
,D/CustomHighlightService( 5273): [custom highlight] set tags 
,I/CheckinTask( 4506): Sending checkin request (8429 bytes)
,I/ActivityManager(  947): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=5326 uid=10076 gids={50076, 9997} abi=arm64-v8a
,I/ActivityManager(  947): Killing 4444:com.android.vending/u0a72 (adj 15): empty #17
,D/Process (  947): killProcessQuiet, pid=4444
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  947): Recipient 4444
,I/ActivityManager(  947): Killing 3594:com.android.defcontainer/u0a15 (adj 15): empty #17,
D/Process (  947): killProcessQuiet, pid=3594
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  947): Recipient 3594
,E/WifiStateMachine(  947): handleMessage: E msg.what=131155
E/WifiStateMachine(  947): processMsg: ConnectedState
,E/WifiStateMachine(  947):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2462 sc=60 link=72 tx=9.8, 0.0, 0.0  rx=10.2 bcn=0 [on:0 tx:0 rx:0 period:2878] from screen [on:0 period:895007960] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  947): processMsg: L2ConnectedState
,E/WifiStateMachine(  947):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2462 sc=60 link=72 tx=9.8, 0.0, 0.0  rx=10.2 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:895007961] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  947):  get link layer stats 0
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1371): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1371): environment dirty rate=0 [14][0][0]
E/WifiStateMachine(  947): fetchRssiLinkSpeedAndFrequencyNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 72
I/ActivityManager(  947): Killing 3996:com.htc.sense.mms/u0a64 (adj 15): empty #17
E/WifiStateMachine(  947): fetchRssiLinkSpeedAndFrequencyNative rssi=-58 linkspeed=72
E/WifiConfigStore(  947): updateConfiguration freq=2462 BSSID=c0:ff:d4:d3:aa:48 RSSI=-58 "NG700"WPA_PSK
D/Process (  947): killProcessQuiet, pid=3996
E/WifiStateMachine(  947): calculateWifiScore freq=2462 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=11.41 txretriesrate=0.00 rxrate=9.61 userTriggerdPenalty0
E/WifiStateMachine(  947):  good link -> stuck count =0
,E/WifiStateMachine(  947):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  947):  isHighRSSI       ---> score=65
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/PackageManager(  947):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService, state=2, flag=1, pid=4506, uid=10024, userID:0
I/PackageManager(  947):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateActivity, state=2, flag=1, pid=4506, uid=10024, userID:0
,I/PackageManager(  947):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver, state=2, flag=1, pid=4506, uid=10024, userID:0
I/PackageManager(  947):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$Receiver, state=2, flag=1, pid=4506, uid=10024, userID:0
,I/ActivityManager(  947): Recipient 3996
,I/CheckinRequestBuilder( 4506): Checkin reason type: 8 attempt count: 1,
,D/SMSBackup( 5326): Got a database change event,
E/WifiStateMachine(  947): handleMessage: X
I/ActivityManager(  947): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4506): Failed to find provider info for com.google.android.wearable.settings
,D/WifiWatchdogStateMachine(  947): RSSI current: 3 new: -58, 3
D/WIFI_ICON( 1224): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/ResourcesManager( 1444): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/AccTypeManager( 1710): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,W/SystemReader(  947): Cannot find grip_rejection_width, use default value instead
,D/AccTypeManager( 1710): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/Prism.AllAppsManager( 1506): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/Prism.ItemManager( 1506): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1506): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/ResourcesManager(  947): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,I/Launcher( 1506): Deferring update until onResume,
I/Prism.ItemManager( 5273): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Prism.ItemManager( 5273): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,D/Launcher( 1506): waitUntilResume // bindAppsUpdated
D/AccTypeManager( 1710): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/ActivityManager(  947): Start proc com.htc.sense.mms for broadcast com.htc.sense.mms/.ui.MessagingShortcutReceiver: pid=5349 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
D/PhoneApp( 1444): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,E/ExternalAccountType( 1710): Unsupported attribute readOnly
,I/ActivityManager(  947): Killing 4641:com.google.android.youtube/u0a176 (adj 15): empty #17
D/Process (  947): killProcessQuiet, pid=4641
,D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/PackageManager(  947): Unable to load service info ResolveInfo{3c1b3820 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
W/PackageManager(  947): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  947): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  947): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  947): 	,at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160),
W/PackageManager(  947): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  947): 	,at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  947): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  947): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  947): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  947): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  947): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  947): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  947): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  947): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  947): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  947): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/BackupManagerService(  947): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/ActivityManager(  947): Recipient 4641
,E/WifiDataStallTracker(  947): DATA_MONITOR_POLL true Token 1
E/WifiTrafficPoller(  947): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  947):  packet count Tx=75 Rx=120
E/WifiTrafficPoller(  947): notifying of data activity 3
,D/WIFI_ICON( 1224): WifiActivity: 3
D/WifiDataStallTracker(  947): updateDataStallInfo: mDataStallTxRxSum={txSum=58 rxSum=45} preTxRxSum={txSum=40 rxSum=32}
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/WifiDataStallTracker(  947): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  947): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,W/HtcWrapAdjustableCursorFactory( 5349): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.,
,D/MessageFrequencyProvider( 5349): onCreate
,D/PMS     (  947): acquireWL(316ef727): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 947 1000 null
I/BatteryService(  947): n_update end,
D/PMS     (  947): releaseWL(316ef727): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HeadsetStateMachine( 3142): Disconnected process message: 10, size: 0
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1224): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  947): plugged=true pluggin=true
D/UsbnetService(  947): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  947): updateBatteryInfo
D/UsbnetService(  947): onReceive BATTERY_CHANGED
D/PMS     (  947): runPSCheck
D/UsbnetService(  947):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  947): Checking...
D/UsbnetService(  947): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  947): >> updateStatus
D/WifiController(  947): handleMessage: E msg.what=155652
D/WifiController(  947): battery changed pluggedType: 2
D/WifiController(  947): processMsg: DeviceActiveState
D/PowerUI ( 1224): closing low battery warning: level=98
D/WifiController(  947): processMsg: StaEnabledState
D/PowerUI ( 1224): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  947): processMsg: DefaultState
D/WifiController(  947): handleMessage: X
,I/HtcPowerSaver(  947): updateStatus (8000,98,-1,false,false,false,-1)
I/HtcPowerSaver(  947): << updateStatus
,I/art     (  947): Explicit concurrent mark sweep GC freed 24636(1311KB) AllocSpace objects, 3(188KB) LOS objects, 33% free, 16MB/25MB, paused 1.622ms total 181.819ms,
,V/GetPrviateResource( 5349): GetPrviateResource,
V/GetPrviateResource( 5349): GetPrviateResource
,D/MessageCustFlag( 5349): sense_version=6.0
,D/BTAccessoryUtil( 5349): createReceiver
,I/BatteryController( 1224): status:2 level:98 unsupport:false plugged:true
,D/BTAccessoryUtil( 5349): registerReceiver return intent = null
,D/MessageCustFlag( 5349): sku_id=118
,I/GCoreNlp( 1848): shouldConfirmNlp, NLP off. Ensuring opt-in disabled,
D/HtcBuildUtils( 5349): getRATByHtcTelephonyCapability:1
W/SystemReader( 5349): Cannot find qct_8960_interface, use default value instead
,D/MmsConfig( 5349): packageName: com.htc.vvm.att does not exist,
D/MessageCustFlag( 5349): sku_id=118
,D/MessagingShortcutReceiver( 5349): keep hiding shortcut bubble,
,D/MessagingShortcut( 5349): updateMsgShortcut, msg count> -1
,D/SettingsManager( 5349): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@26a6be64
,D/MessagingShortcut( 5349): After query: 0
D/MessagingShortcut( 5349): mPresentUnreadCount: -1
,D/MessageUtils( 5349): [getShortcut] com.htc.sense.mms.ui.ConversationList, false
,D/MessagingShortcut( 5349): setMsgShortcutDrawable> 0, false
,D/MessagingShortcut( 5349): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
,D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1308): [EventService] reorderNotification, total:1
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/ActivityManager(  947): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=5376 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a
,D/Process (  947): killProcessQuiet, pid=4721,
,I/ActivityManager(  947): Killing 4721:com.google.android.gm/u0a106 (adj 15): empty #17
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/art     (  406): Explicit concurrent mark sweep GC freed 8632(366KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 362us total 18.328ms
,I/art     (  406): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 122us total 15.879ms
,I/art     (  406): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 130us total 15.052ms
,I/ActivityManager(  947): Recipient 4721,
,D/LocationProviderProxy(  947): applying state to connected service
,D/PMS     (  947): acquireWL(178fc279): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1848 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  947): releaseWL(178fc279): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/LocationProviderProxy(  947): applying state to connected service,
,V/GmsNetworkLocationProvi( 1848): DISABLE
D/PMS     (  947): acquireWL(380cdbbe): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1848 10024 WorkSource{10024 com.google.android.gms}
,W/ResourcesManager( 5376): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/PMS     (  947): releaseWL(380cdbbe): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  947): acquireWL(3b61a41f): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1848 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  947): acquireWL(178e836c): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1848 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  947): releaseWL(3b61a41f): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  947): releaseWL(178e836c): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,I/GLSUser ( 1873): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer,
I/GLSUser ( 1873): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1873): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1873): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1873): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TodoTaskshortcut( 5376): update TASK shortcut>,
,W/CheckinRequestBuilder( 4506): awaiting user notification for token
,D/DotMatrix( 1308): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1308): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1224): reapply : com.google.android.gms 3 40,
,D/PMS     (  947): acquireWL(333d404): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 5376 10069 null
,D/PMS     (  947): acquireWL(26c2aded): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 5376 10069 null,
D/PMS     (  947): releaseWL(333d404): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,I/CheckinRequestBuilder( 4506): Classify the device as Phone.
,E/TodoTaskNotifyService( 5376): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference,
W/System.err( 5376): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
W/System.err( 5376): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
,W/System.err( 5376): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
D/PMS     (  947): releaseWL(26c2aded): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
W/System.err( 5376): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5376): 	at android.os.Looper.loop(Looper.java:155)
W/System.err( 5376): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/NotifyReceiver( 5376): stopSelfResult true
D/Process (  947): killProcessQuiet, pid=4762
I/ActivityManager(  947): Killing 4762:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/PMS     (  947): acquireWL(4ffeb3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1873 10024 WorkSource{10024 com.google.android.gms},
,I/ActivityManager(  947): Recipient 4762
,D/WifiService(  947): Client connection lost with reason: 4
,D/MtpReceiver( 3950): [MTP][handleUsbStateAsync]+,
D/MtpReceiver( 3950): [MTP][handleUsbStateAsync]1:1-
D/MtpReceiver( 3950): [MTP][handleUsbState]+
,D/PMS     (  947): releaseWL(4ffeb3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/MtpReceiver( 3950): [MTP][scanExternalVolumeIfNeed] scan external volume
I/ActivityManager(  947): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=5403 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a
,D/MtpReceiver( 3950): [MTP][handleUsbState]-
D/MtpReceiver( 3950): [MTP][handleMessage]-
,D/MtpService( 3950): updating state; isCurrentUser=true, mMtpLocked=false
,D/MtpDatabase( 3950): TotalSize=1886532,MediaCacheLimit=6000,
,D/MtpService( 3950): [isMtpConnected] connected: true
,D/PMS     (  947): acquireWL(3c05b06e): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 4506 10024 null
,I/CheckinTask( 4506): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 4506): Checking schedule, now: 1448298988281 next: 1448835820264
I/CheckinService( 4506): active receiver: disabled
I/PackageManager(  947):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4506, uid=10024, userID:0
,D/PMS     (  947): releaseWL(2680a61e): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
,E/WifiTrafficPoller(  947): TRAFFIC_STATS_POLL true Token 11 num clients 6
,E/WifiTrafficPoller(  947):  packet count Tx=75 Rx=120
E/WifiTrafficPoller(  947): notifying of data activity 0
D/WIFI_ICON( 1224): WifiActivity: 0
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/iu.UploadsManager( 4506): End new media; added: 0, uploading: 0, time: 75 ms
,D/PMS     (  947): releaseWL(3c05b06e): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 null
,E/MediaScannerService( 3950): [onStartCommand] --- Should not be here, redirect request. ----,
E/MediaScannerService( 3950): [handleMessage] --- Should not be here, ignore request. ----
,D/SyncApplication( 5403): Loading default preferences,
,W/Resources( 5403): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a},
,D/WifiService(  947): New client listening to asynchronous messages,
E/WifiTrafficPoller(  947): ADD_CLIENT: 7
,D/SyncApplication( 5403): Overriding preferences with custom values,
,E/MediaScannerServiceEx( 3950): [getStorageMaskIdFromPath] path is null
,D/MediaScannerServiceEx( 3950): [ServiceHandler][handleMessage] , action: null, Id: 0, path: /storage/emulated/0
D/MediaScannerServiceEx( 3950): [handleExternalVolume] ext storage
,D/SyncApplication( 5403): Updating preferences succeeded
D/MediaProviderUtils( 3950): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3950): calcVolumeId: /storage/ext_sd
,D/MediaProviderUtils( 3950): calcVolumeId: /storage/usb
E/SyncApplication( 5403): Application created.
D/MediaScannerServiceEx( 3950): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
D/MediaScannerServiceEx( 3950): [AliveExtStorageRows]+65537, 11223344
,I/HtcModeClient( 3268): handler message = 4011
,E/HtcModeClient( 3268): Check connection and retry 5 times.
D/MediaProvider( 3950): [update][6]#0#
,D/MediaProvider( 3950): [update][2]#0#
,I/CalendarDefines( 5403): getNewCalendarAuthority()...
,I/PackageManager(  947):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=5403, uid=10005, userID:0
,W/PackageManager(  947): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
W/VolumeInfo( 5403): Unable to read mount points
W/VolumeInfo( 5403): java.io.FileNotFoundException: /etc/vold.fstab: open failed: ENOENT (No such file or directory),
W/VolumeInfo( 5403): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/VolumeInfo( 5403): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/VolumeInfo( 5403): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/VolumeInfo( 5403): 	at java.io.FileReader.<init>(FileReader.java:66)
W/VolumeInfo( 5403): 	at com.nero.android.common.VolumeInfo.getVolumeMountPoints(VolumeInfo.java:194)
W/VolumeInfo( 5403): 	at com.nero.android.common.VolumeInfo.getVolumes(VolumeInfo.java:153)
W/VolumeInfo( 5403): 	at com.nero.android.common.VolumeInfo.initializeVolumeIDs(VolumeInfo.java:474)
W/VolumeInfo( 5403): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:51)
W/VolumeInfo( 5403): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:1)
W/VolumeInfo( 5403): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/VolumeInfo( 5403): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/VolumeInfo( 5403): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/VolumeInfo( 5403): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/VolumeInfo( 5403): 	at java.lang.Thread.run(Thread.java:818)
W/VolumeInfo( 5403): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 5403): 	at libcore.io.Posix.open(Native Method)
W/VolumeInfo( 5403): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/VolumeInfo( 5403): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/VolumeInfo( 5403): 	... 13 more
I/PackageManager(  947):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=5403, uid=10005, userID:0
D/SyncApplication( 5403): enableAppOperation()+
W/PackageManager(  947): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,V/VolumeInfo( 5403): Found 0 mount point(s)
V/VolumeInfo( 5403): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
D/SyncApplication( 5403): enableAppOperation()-
D/HTCUtilities( 5403): isNeorSinged() + 
,D/VolumeInfo( 5403): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,D/MediaProvider( 3950): [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
,D/MtpService( 3950): [sendStorageAdded] Already send to MTP: /storage/emulated/0
,D/MediaProvider( 3950): [update][17]#1#
,D/VolumeInfo( 5403): Read the volume-id from the sd card: {9B5E872B-8520-47C6-8BD3-3081C2E38355}
D/MediaScannerServiceEx( 3950): [AliveExtStorageRows]-0, 0
,D/PMS     (  947): acquireWL(1b251988): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3950 10017 null
,D/HTCUtilities( 5403): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 5403): isNeorSinged() return false
,W/VolumeInfo( 5403): Can not create volume ID for unmounted volume null
D/CDMountReceiver( 5403): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
D/CDMountReceiver( 5403): USB connected to PC
,D/MediaScanner( 3950): =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
,I/Prism.ItemManager( 1506): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1506): loadItems() com.htc.launcher.pageview.WidgetManager@1719c12a +
I/Prism.WidgetManager( 1506): onLoadItems() +
,D/FOTAReceiver( 5403): onReceive() enter 
D/FOTAReceiver( 5403): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,I/Prism.ItemManager( 5273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
I/Prism.ItemManager( 5273): loadItems() com.htc.launcher.pageview.WidgetManager@2135f5e8 +
I/Prism.WidgetManager( 5273): onLoadItems() +
,D/Process (  947): killProcessQuiet, pid=4809,
I/ActivityManager(  947): Start proc com.android.settings for broadcast com.android.settings/.NSReceiver: pid=5434 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  947): Killing 4809:com.google.android.partnersetup/u0a27 (adj 15): empty #17
,W/ResourcesManager( 1506): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,W/ResourcesManager( 5273): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,I/ActivityManager(  947): Recipient 4809
,D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 5434): -onCreate()
,V/Settings:HtcSettingsApplication( 5434): [5434/5434] onCreate(),
,D/TetherSettings( 5434): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5434): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5434): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5434): Cust_ConnectToPC   : spcsc>false
,D/        ( 5434): Cust_ConnectToPC   : IPT>true
D/        ( 5434): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 5434): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 1506): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,E/SmartNS_Utility( 5434): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5434): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5434): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 5434): usb_cable_connect = 1
,D/SmartNS_Utility( 5434): usb_denied = 0
,I/SmartNS_NSReceiver( 5434): locked:falsesecurity:falseisLocked:false,
D/SmartNS_NSReceiver( 5434): USB = true hasTethered = false isNSOpening: false
,I/PSReceiver( 5434): onReceive:com.htc.intent.action.USB_CONNECT2PC
,W/ContextImpl( 5434): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2712 ,
W/ResourcesManager( 5273): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/SmartNS_PSService( 5434): onReceive:com.htc.intent.action.USB_CONNECT2PC
,W/Settings( 5434): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
I/SmartNS_PSService( 5434):  defaultType:0
I/SmartNS_PSService( 5434): fail notificaiton:false
,D/SmartNS_Utility( 5434): usb_cable_connect = 1
D/SmartNS_Utility( 5434): usb_denied = 0
,I/SmartNS_PSService( 5434): usb notificaiton:true
,E/WifiStateMachine(  947): WiFiDisplay: getWifidisplayApEnabled=false
D/PhoneApp( 1444): EVENT_QUERY_MO_PACKAGES
D/PhoneApp( 1444): -- N1 =0
,I/ActivityManager(  947): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=5457 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/ActionCombine( 5434): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
D/PhoneApp( 1444): -- N2 =0
,D/PhoneApp( 1444): -- N3 =0
,D/SmartNS_Utility( 5434): usb_cable_connect = 1
,D/SmartNS_Utility( 5434): usb_denied = 0
I/SmartNS_PSService( 5434): usb notificaiton:true
,E/WifiStateMachine(  947): WiFiDisplay: getWifidisplayApEnabled=false
,D/DotMatrix( 1308): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false,
I/RemoteViews( 1224): reapply : com.android.settings 0 36
,D/SmartNS_Utility( 5434): usb_cable_connect = 1,
,D/SmartNS_Utility( 5434): usb_denied = 0
D/DotMatrix( 1308): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/SmartNS_PSService( 5434): KeyGuard locked:falseKeyGuard is secured:false
D/SmartNS_PSService( 5434): USB Plugged, Set USBPlugged=  truePSenabled:false
,D/Process (  947): killProcessQuiet, pid=4893
I/ActivityManager(  947): Killing 4893:com.google.android.music:main/u0a159 (adj 15): empty #17
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/RemoteViews( 1224): reapply : com.android.settings 1 36
,W/asset   ( 1506): Copying FileAsset 0x558a18bb10 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,I/ActivityManager(  947): Recipient 4893,
D/MediaRouterService(  947): Client com.google.android.music (pid 4893): Died!
,W/asset   ( 5273): Copying FileAsset 0x5589d1c560 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,
,E/WifiTrafficPoller(  947): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  947):  packet count Tx=75 Rx=121
E/WifiTrafficPoller(  947): notifying of data activity 1
D/WIFI_ICON( 1224): WifiActivity: 1
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/BluetoothManagerService(  947): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  947): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@26a343f8 mBinding = false
W/Settings:Agent(  947): MONITOR_LOG
W/Settings:Agent(  947): name: bluetooth_on
W/Settings:Agent(  947): value: 0
W/Settings:Agent(  947): >> traceCallingStack()
W/Settings:Agent(  947): Process.myPid(): 947
W/Settings:Agent(  947): Process.myTid(): 1162
W/Settings:Agent(  947): Process.myUid(): 1000
W/Settings:Agent(  947): 
W/Settings:Agent(  947): 
W/System.err(  947): java.lang.Throwable: stack dump
,W/System.err(  947): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  947): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  947): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  947): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
,W/System.err(  947): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  947): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  947): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:378)
W/System.err(  947): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:624)
W/System.err(  947): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  947): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  947): 
W/Settings:Agent(  947): << traceCallingStack(): 15(ms)
,E/Prism.WidgetManager( 1506): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1506): onLoadItems() -
I/Prism.ItemManager( 1506): loadItems() com.htc.launcher.pageview.WidgetManager@1719c12a -
,W/ContextImpl( 5457): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.backupreset.receiver.BackupResetReceiver.onReceive:45 android.app.ActivityThread.handleReceiver:2712 ,
,D/MediaProvider( 3950): [update][12]#1#
,D/BluetoothManagerService(  947): Message: MESSAGE_DISABLE
D/BluetoothManagerService(  947): Sending off request.
,D/BluetoothAdapterState( 3142): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3142): Setting state to 13
I/BluetoothAdapterState( 3142): Bluetooth adapter state changed: 12-> 13
D/BluetoothManagerService(  947): +onBluetoothStateChange prev=12 new=13
D/BluetoothAdapterProperties( 3142): onBluetoothDisable()
I/BluetoothAdapterState( 3142): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/bt-btif ( 3142): HAL bt_hal_cbacks->adapter_properties_cb
I/bt-btm  ( 3142): BTM_SetDiscoverability
I/bt-btm  ( 3142): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3142): disc_mode 0000
I/bt-btm  ( 3142): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 3142): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
D/BluetoothManagerService(  947): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  947): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  947): Bluetooth State Change Intent: 12 -> 13
,E/WifiTrafficPoller(  947): ADD_CLIENT: 8
D/WifiService(  947): New client listening to asynchronous messages
,I/IntentController( 1224): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/PMS     (  947): acquireWL(e671507): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3142 1002 null
I/bt-btm  ( 3142): BTM_SetConnectability
I/bt-btm  ( 3142): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 3142): disc_mode 0000
I/bt-btm  ( 3142): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
D/FlexNetS( 4936): updateSvcAllowedInSettings:false
D/BluetoothAdapterProperties( 3142): Scan Mode:21
D/WifiManager( 4978): setWifiEnabled: Base Package Name=com.example.hello, uid=10373
D/NGFService( 3807): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,E/WifiStateMachine(  947): WiFiDisplay: getWifidisplayApEnabled=false,
D/WifiService(  947): setWifiEnabled: false pid=4978, uid=10373
,W/Settings:Agent(  947): MONITOR_LOG
E/WifiService(  947): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent(  947): name: wifi_on
I/WifiService(  947): isSprintWifiRestricted(): false
W/Settings:Agent(  947): value: 0
I/WifiService(  947): isMdmWifiRestricted(): false
W/Settings:Agent(  947): >> traceCallingStack()
,W/Settings:Agent(  947): Process.myPid(): 947
W/Settings:Agent(  947): Process.myTid(): 1410
W/Settings:Agent(  947): Process.myUid(): 1000
W/Settings:Agent(  947): 
W/Settings:Agent(  947): 
D/BluetoothAdapterState( 3142): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
I/bt-btif ( 3142): BTA_JvDeleteRecord
I/bt-btif ( 3142): BTA_JvRfcommStopServer
D/bt-btm  ( 3142): BTM_FreeSCN 
D/bt-sdp  ( 3142): SDP_DeleteRecord ok, num_records:14
I/bt-btif ( 3142): BTA_JvDeleteRecord
I/bt-btif ( 3142): BTA_JvRfcommStopServer
,D/bt-btm  ( 3142): BTM_FreeSCN 
I/bt-btif ( 3142): BTA_JvDeleteRecord
,I/bt-btif ( 3142): BTA_JvRfcommStopServer
,D/bt-btm  ( 3142): BTM_FreeSCN 
I/bt-btif ( 3142): BTA_JvDeleteRecord
I/bt-btif ( 3142): BTA_JvRfcommStopServer
D/bt-btm  ( 3142): BTM_FreeSCN 
I/bt-btif ( 3142): BTA_JvDeleteRecord
I/bt-btif ( 3142): BTA_JvRfcommStopServer
D/bt-btm  ( 3142): BTM_FreeSCN 
I/bt-btif ( 3142): BTA_JvDeleteRecord
I/bt-btif ( 3142): BTA_JvRfcommStopServer
D/bt-btm  ( 3142): BTM_FreeSCN 
E/bt-btif ( 3142): cmd socket is not created
V/BluetoothSapService( 3142): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/BtOppRfcommListener( 3142): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/System.err(  947): java.lang.Throwable: stack dump
,I/bt-btm  ( 3142): BTM_SEC_CLR[13]: id 55
D/bt-sdp  ( 3142): SDP_DeleteRecord ok, num_records:13
I/bt-btm  ( 3142): BTM_SEC_CLR[14]: id 56
D/bt-sdp  ( 3142): SDP_DeleteRecord ok, num_records:12
I/bt-btm  ( 3142): BTM_SEC_CLR[15]: id 57
D/bt-sdp  ( 3142): SDP_DeleteRecord ok, num_records:11
I/bt-btm  ( 3142): BTM_SEC_CLR[16]: id 58
D/bt-sdp  ( 3142): SDP_DeleteRecord ok, num_records:10
I/bt-btm  ( 3142): BTM_SEC_CLR[17]: id 59
D/bt-sdp  ( 3142): SDP_DeleteRecord ok, num_records:9
I/bt-btm  ( 3142): BTM_SEC_CLR[18]: id 60
D/bt-sdp  ( 3142): SDP_DeleteRecord ok, num_records:8
I/bt-btm  ( 3142): Write Extended Inquiry Response to controller
I/bt-btm  ( 3142): Write Extended Inquiry Response to controller
I/bt-btm  ( 3142): Write Extended Inquiry Response to controller
I/bt-btm  ( 3142): Write Extended Inquiry Response to controller
I/Prism.WidgetManager( 5273): onLoadItems() -
I/Prism.ItemManager( 5273): loadItems() com.htc.launcher.pageview.WidgetManager@2135f5e8 -
,W/bt-l2cap( 3142): L2CAP - L2CA_Deregister() called for PSM: 0x000f,
I/bt-btm  ( 3142): BTM_SetDiscoverability
I/bt-btm  ( 3142): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3142): disc_mode 0000
I/bt-btm  ( 3142): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 3142): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
,I/bt-btm  ( 3142): BTM_SetConnectability
I/bt-btm  ( 3142): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3142): disc_mode 0000
D/bt-btm  ( 3142): btm_ble_update_adv_flag new=0x1c
,D/bt-btm  ( 3142): btm_ble_update_adv_flag old=0x18
I/bt-btm  ( 3142): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 3142): BTM_IsInquiryActive
I/bt-btm  ( 3142): BTM_CancelRemoteDeviceName()
I/bt-btm  ( 3142): btm_ble_clear_white_list
W/bt-btif ( 3142): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
D/bt-btif ( 3142): AG evt (hdl 0x0001): State 0, Event 0x0501
D/bt-btif ( 3142): AG evt (hdl 0x0002): State 0, Event 0x0501
D/bt-sdp  ( 3142): SDP_DeleteRecord ok, num_records:7
D/bt-btm  ( 3142): BTM_FreeSCN 
I/bt-btm  ( 3142): BTM_SEC_CLR[3]: id 12
D/bt-sdp  ( 3142): SDP_DeleteRecord ok, num_records:6
D/bt-btm  ( 3142): BTM_FreeSCN 
I/bt-btm  ( 3142): BTM_SEC_CLR[4]: id 29
D/bt-avp  ( 3142): AVRC_Close handle:0
D/bt-btif ( 3142): btif_hf_upstreams_evt: event=BTA_AG_DISABLE_EVT
D/bt-btif ( 3142): AV Sevent(0x41)=0x120a(API_CLOSE) state=0(INIT)
I/ActivityManager(  947): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=5484 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/ActivityManager(  947): Killing 5002:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  947): killProcessQuiet, pid=5002
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,V/BluetoothPbapReceiver( 3142): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapReceiver( 3142): ***********state = 13
,D/bt-sdp  ( 3142): SDP_DeleteRecord ok, num_records:5
D/bt-sdp  ( 3142): SDP_DeleteRecord ok, num_records:4
W/bt-l2cap( 3142): L2CAP - L2CA_Deregister() called for PSM: 0x0019
D/bt-sdp  ( 3142): SDP_DeleteRecord ok, num_records:3
W/bt-l2cap( 3142): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3142): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3142): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 3142): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3142): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3142): L2CAP - L2CA_Deregister() called for PSM: 0x0011
W/bt-l2cap( 3142): L2CAP - L2CA_Deregister() called for PSM: 0x0013
I/bt-att  ( 3142): GATT_Deregister gatt_if=3
I/bt-att  ( 3142): GATT_Listen gatt_if=3
I/bt-btm  ( 3142): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3142): BTM_ReadConnectability
I/bt-btm  ( 3142): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3142): disc_mode 0000
I/bt-att  ( 3142): GATT_Deregister gatt_if=4
I/bt-att  ( 3142): GATT_Listen gatt_if=4
I/bt-btm  ( 3142): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3142): BTM_ReadConnectability
I/bt-btm  ( 3142): btm_ble_set_connectability mode=0x0 combined_mode=0x0
,D/bt-btm  ( 3142): disc_mode 0000
E/bt-btif ( 3142): bta_gattc_deregister Deregister Failedm unknown client cif
W/System.err(  947): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  947): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  947): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  947): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  947): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  947): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  947): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  947): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:112)
W/System.err(  947): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  947): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  947): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  947): 
W/Settings:Agent(  947): << traceCallingStack(): 36(ms)
,I/QuickSettingBluetooth( 1224): receive.ACTION_STATE_CHANGE:STATE_TURNING_OFF
,D/WifiController(  947): handleMessage: E msg.what=155656
D/WifiController(  947): processMsg: DeviceActiveState
D/WifiController(  947): processMsg: StaEnabledState
,D/WifiController(  947): transitionTo: destState=ApStaDisabledState
D/WifiController(  947): handleMessage: new destination call exit/enter
D/WifiController(  947): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiController(  947): invokeExitMethods: DeviceActiveState
D/WifiController(  947): invokeExitMethods: StaEnabledState
D/WifiController(  947): moveTempStackToStateStack: i=0,j=1
D/WifiController(  947): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=ApStaDisabledState
D/WifiController(  947): invokeEnterMethods: ApStaDisabledState
D/WifiController(  947): handleMessage: X
E/WifiStateMachine(  947): handleMessage: E msg.what=131084
E/WifiStateMachine(  947): processMsg: ConnectedState
E/WifiStateMachine(  947):  ConnectedState !CMD_STOP_SUPPLICANT 0 0
I/bt-btm  ( 3142): btm_ble_clear_white_list_complete
E/WifiStateMachine(  947): processMsg: L2ConnectedState
I/jxcore-log( 4978): ****TEST TOOK:  5228  ms ****
I/jxcore-log( 4978): 
E/WifiStateMachine(  947):  L2ConnectedState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  947): processMsg: ConnectModeState
,E/WifiStateMachine(  947):  ConnectModeState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  947): processMsg: DriverStartedState
E/WifiStateMachine(  947):  DriverStartedState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  947): processMsg: SupplicantStartedState
E/WifiStateMachine(  947):  SupplicantStartedState !CMD_STOP_SUPPLICANT 0 0
,E/WifiStateMachine(  947): transitionTo: destState=WaitForP2pDisableState
,D/WifiDisplayAdapter(  947): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  947):     Client/Owner: Client
D/WifiDisplayAdapter(  947):     GroupId: 
D/WifiDisplayAdapter(  947):     Passphrase: 
D/WifiDisplayAdapter(  947):     SessionId: 0
D/WifiDisplayAdapter(  947):     IP Address: }
E/WifiStateMachine(  947): handleMessage: new destination call exit/enter
E/WifiStateMachine(  947): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=SupplicantStartedState,active=true,parent=DefaultState
E/WifiStateMachine(  947): invokeExitMethods: ConnectedState
I/jxcore-log( 4978): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4978): 
E/WifiStateMachine(  947): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  947): release()
E/WifiStateMachine(  947): PerfLock released for exiting ConnectedState
E/WifiStateMachine(  947): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
E/WifiStateMachine(  947): invokeExitMethods: L2ConnectedState
E/WifiStateMachine(  947): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
E/WifiStateMachine(  947): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any,
E/WifiStateMachine(  947): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  947): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  947): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1371): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1371): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1371): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1371): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1371): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1371): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1371): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  947): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1371): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1371): Power_Mode_Type mode = 0
I/wpa_supplicant( 1371): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
D/WifiP2pService(  947): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/WifiP2pService(  947): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1371): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1371): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  947): setDhcpActive: false
V/NativeCrypto( 1873): Read error: ssl=0x5589c76030: I/O error during system call, Connection timed out
D/PMS     (  947): acquireWL(14b64634): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1873 10024 WorkSource{10024 com.google.android.gms}
E/WifiStateMachine(  947): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  947): setDetailed state send new extra info<unknown ssid>
D/libc    (  947): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
V/NativeCrypto( 1873): SSL shutdown failed: ssl=0x5589c76030: I/O error during system call, Broken pipe
D/libc    (  947): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  947): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  947): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  947): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  947): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  947): [NET] android_getaddrinfofornet-, SUCCESS
,D/ConnectivityService(  947): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  947): ValidatedState{ when=0 what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  947): DefaultState{ when=0 what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  947): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  947): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  947): Validated
D/ConnectivityService(  947): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  947): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  947):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  947):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  947): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  947): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  947):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  947):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  947): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1224): CM callback handler got msg 524290
,I/SecurityController( 1224): onAvailable 100 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/Messaging( 5349): supportCMAS(SIE)/init? false/true
,D/MmsConfig( 5349): networkCode: 
D/MmsConfig( 5349): SIE smsPri: null
D/MmsConfig( 5349): networkCode: ,
,D/Messaging( 5349): mNeedToUpdateDate2 start,
D/ReportIndicatorCache( 5349): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 5349): 
D/MmsAsyncWorkHandler( 5349): HM tk = 20001
,D/ReportIndicatorCache( 5349): MSG_QUERY_REPORTS >>
,D/DraftCache( 5349): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 5349): [DraftCache/1] refresh
,D/MmsConfig( 5349): networkCode: ,
I/Messaging( 5349): mccmnc> 
,D/Messaging( 5349): ViewCache CreatePreloadOnlyConversationList,
,D/MessageCustFlag( 5349): sense_version=6.0
,D/Jerry   ( 5349): start to preload cursor >>>>>>>
,I/ActivityManager(  947): Recipient 5002
,D/bt-btm  ( 3142): BTM_BleGetVendorCapabilities
W/bt-btif ( 3142): ag scb idx 1 not allocated
W/bt-btif ( 3142): ag scb idx 2 not allocated
E/bt-btif ( 3142): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3142): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3142): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3142): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3142): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3142): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3142): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3142): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3142): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3142): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3142): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3142): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3142): L2CAP - PSM: 0x0017 not found for deregistration
E/bt-btif ( 3142): bta_gattc_deregister Deregister Failedm unknown client cif
,E/bt_userial_mct( 3142): pthread_join() FAILED result:3
,I/BtOppRfcommListener( 3142): stopping Accept Thread,
I/BtOppRfcommListener( 3142): BluetoothSocket listen thread finished,
,E/cutils-trace( 5510): Error opening trace file: Permission denied (13),
,D/MediaProvider( 3950): [update][65]#1#,
E/WifiStateMachine(  947): NetworkAgent != null
,E/WifiStateMachine(  947): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  947): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
E/WifiStateMachine(  947): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,V/NetworkPolicy(  947): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiStateMachine(  947): autoRoamSetBSSID any key="NG700"WPA_PSK
D/ConnectivityService(  947): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiConfigStore(  947): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/PMS     (  947): releaseWL(e671507): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
E/WifiTrafficPoller(  947): ENABLE_TRAFFIC_STATS_POLL true Token 11
D/PMS     (  947): releaseWL(14b64634): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
V/BluetoothPbapService( 3142): Pbap Service closeService in
D/WIFI_ICON( 1224): updateWifiState: NETWORK_STATE_CHANGED connected
W/WifiHW  (  947): QCOM Debug skip set_network part for security concern!
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/wpa_supplicant( 1371): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/WIFI_ICON( 1224): WifiActivity: 0
D/wpa_supplicant( 1371): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/wpa_supplicant( 1371): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
E/WifiTrafficPoller(  947):  packet count Tx=75 Rx=121
E/WifiTrafficPoller(  947): notifying of data activity 0
D/WifiDataStallTracker(  947): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  947): stopDataStallAlarm 
E/WifiTrafficPoller(  947): ENABLE_TRAFFIC_STATS_POLL false Token 12
E/WifiDataStallTracker(  947): ENABLE_DATA_MONITOR_POLL false Token 1
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1371): wlan0: Control interface command 'SAVE_CONFIG'
I/IntentController( 1224): receive(android.net.wifi.STATE_CHANGE,1,false)
D/wpa_supplicant( 1371): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1371): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1371): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  947): invokeExitMethods: ConnectModeState
E/WifiStateMachine(  947): invokeExitMethods: DriverStartedState
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/wpa_supplicant( 1371): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 1371): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  947): Unexpected BatchedScanResults :null
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/wpa_supplicant( 1371): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 1371): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  947): noteBatchedScanstop()
,D/TelephUtils( 1444): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/MmsSmsV2Provider( 1444):  slotId = -1000
D/MmsSmsV2Provider( 1444): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
I/IntentController( 1224): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1224): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/IntentController( 1224): receive(android.net.wifi.STATE_CHANGE,1,false)
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WIFI_ICON( 1224): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiTrafficPoller(  947): ENABLE_TRAFFIC_STATS_POLL false Token 13
E/WifiStateMachine(  947): [1,448,298,989,789 ms] noteScanEnd no scan source
D/PMS     (  947): acquireWL(3c39dff): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 5434 1000 null
E/WifiStateMachine(  947): moveTempStackToStateStack: i=0,j=2
E/WifiStateMachine(  947): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=2,Top=WaitForP2pDisableState
E/WifiStateMachine(  947): invokeEnterMethods: WaitForP2pDisableState
E/WifiStateMachine(  947): handleMessage: X
E/WifiStateMachine(  947): handleMessage: E msg.what=131212
E/WifiStateMachine(  947): processMsg: WaitForP2pDisableState
E/WifiStateMachine(  947):  WaitForP2pDisableState !CMD_UPDATE_LINKPROPERTIES 0 0
W/ContextImpl( 5434): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
E/WifiStateMachine(  947): processMsg: SupplicantStartedState
D/WifiP2pService(  947): InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  947):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiP2pService(  947): P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  947): processMsg: DefaultState
D/WifiP2pService(  947): P2pDisablingState
E/WifiStateMachine(  947):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiP2pService(  947): P2pDisablingState{ when=-4ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  947): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
D/WifiP2pService(  947): p2p socket connection lost
E/WifiStateMachine(  947): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiP2pService(  947): P2pDisabledState
E/WifiStateMachine(  947): handleMessage: X
E/WifiStateMachine(  947): handleMessage: E msg.what=131212
E/WifiStateMachine(  947): processMsg: WaitForP2pDisableState
,D/WifiScanningService(  947): SCAN_AVAILABLE : 1
D/RttService(  947): SCAN_AVAILABLE : 1
D/WifiScanningService(  947): DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService(  947): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  947):  WaitForP2pDisableState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  947): processMsg: SupplicantStartedState
D/WifiMonitor(  947): stopMonitoring(p2p0) = com.android.server.wifi.p2p.WifiP2pServiceImpl$P2pStateMachine@1ec510e7
E/WifiStateMachine(  947):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  947): processMsg: DefaultState
E/WifiStateMachine(  947):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiP2pService(  947): P2pDisabledState{ when=0 what=131333 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  947): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
D/WifiP2pService(  947): DefaultState{ when=0 what=131333 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  947): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  947): handleMessage: X
E/WifiStateMachine(  947): handleMessage: E msg.what=131212
E/WifiStateMachine(  947): processMsg: WaitForP2pDisableState
E/WifiStateMachine(  947):  WaitForP2pDisableState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  947): processMsg: SupplicantStartedState
V/BluetoothPbapService( 3142): successfully stopped pbap service
V/BluetoothPbapService( 3142): Pbap Service closeService out
E/WifiStateMachine(  947):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  947): processMsg: DefaultState
E/WifiStateMachine(  947):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
D/PhoneStorageUtil( 5349): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 5349): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 5349): createReceiver
E/WifiStateMachine(  947): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  947): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  947): handleMessage: X
E/WifiStateMachine(  947): handleMessage: E msg.what=131155
E/WifiStateMachine(  947): processMsg: WaitForP2pDisableState
E/WifiStateMachine(  947):  WaitForP2pDisableState !CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2858] from screen [on:0 period:895011046] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  947): processMsg: SupplicantStartedState
E/WifiStateMachine(  947):  SupplicantStartedState !CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:895011047] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  947): processMsg: DefaultState
E/WifiStateMachine(  947):  DefaultState !CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:895011049] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  947): handleMessage: X
D/WifiNetworkAgent(  947): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  947): handleMessage: E msg.what=131205
E/WifiStateMachine(  947): processMsg: WaitForP2pDisableState
E/WifiStateMachine(  947):  WaitForP2pDisableState !CMD_DISABLE_P2P_RSP uid=1000 0 0
E/WifiStateMachine(  947): transitionTo: destState=SupplicantStoppingState
E/WifiStateMachine(  947): handleMessage: new destination call exit/enter
E/WifiStateMachine(  947): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  947): invokeExitMethods: WaitForP2pDisableState
E/WifiStateMachine(  947): invokeExitMethods: SupplicantStartedState
E/WifiStateMachine(  947): moveTempStackToStateStack: i=0,j=1
E/WifiStateMachine(  947): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStoppingState
E/WifiStateMachine(  947): invokeEnterMethods: SupplicantStoppingState
E/WifiStateMachine(  947): Call handleNetworkDisconnect() in SupplicantStoppingState
D/CustomizationManager( 5510): ====startRecUseTime====
D/htc.customization.log.level( 5510):  is 
W/CustomizationLogLevel( 5510): Level value is invalid, use default level 2
D/TelephUtils( 1444): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/AccFlag ( 1444): sku_id=118
D/WISPrService( 5434): >>>>>WISPrService start isConnected = true<<<<<
I/QuickSettingWifi( 1224): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:1
D/PMS     (  947): releaseWL(3c39dff): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null,
D/BluetoothManagerService(  947): Message: MESSAGE_REGISTER_ADAPTER
D/PMS     (  947): acquireWL(27be1b1b): PARTIAL_WAKE_LOCK  StartingDockService 0x1 5434 1000 null
W/System.err(  947): java.lang.Throwable: stack dump
I/ActivityManager(  947): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=5531 uid=10034 gids={50034, 9997, 3002, 3001} abi=arm64-v8a
D/BluetoothManagerService(  947): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1a397291:true
D/WifiDisplayController(  947): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
W/System.err(  947): 	at java.lang.Thread.dumpStack(Thread.java:490)
D/WifiDisplayAdapter(  947): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  947):     Client/Owner: Client
D/WifiDisplayAdapter(  947):     GroupId: 
D/WifiDisplayAdapter(  947):     Passphrase: 
D/WifiDisplayAdapter(  947):     SessionId: 0
D/WifiDisplayAdapter(  947):     IP Address: }
W/System.err(  947): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
D/WifiService(  947): New client listening to asynchronous messages
D/TelephUtils( 1444): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 83
W/System.err(  947): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  947): 	at android.os.Binder.execTransact(Binder.java:454)
D/MmsSmsV2Provider( 1444):  slotId = -1000
D/MmsSmsV2Provider( 1444): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/DraftCache( 5349): [DraftCache/121] rebuildCache
V/AudioService(  947): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  947):     Client/Owner: Client
V/AudioService(  947):     GroupId: 
V/AudioService(  947):     Passphrase: 
V/AudioService(  947):     SessionId: 0
V/AudioService(  947):     IP Address: }
D/HtcEffectManagerBase(  947): onEventChanged id=5 status=false
D/HtcEffectManager(  947): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true mAllPlayOn=false
I/QuickSettingWifi( 1224): receive.wifiConnect:false wifiAPname:null elapse:1
I/QuickSettingWifi( 1224): receive.wifiConnect:false wifiAPname:null elapse:1
V/BluetoothPbapService( 3142): Pbap Service onDestroy
E/WifiStateMachine(  947): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - enter - invokeEnterMethods
D/TelephUtils( 1444): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/MmsSmsV2Provider( 1444):  slotId = -1000
E/WifiStateMachine(  947): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/HtcEffectManager(  947): convertEffect before=902
D/HtcEffectManager(  947): convertEffect after=902
D/wpa_supplicant( 1371): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1371): Power_Mode_Type mode = 0
I/wpa_supplicant( 1371): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/WifiTrafficPoller(  947): ADD_CLIENT: 9
W/WifiHW  (  947): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/WifiP2pService(  947): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  947): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1371): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1371): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
W/ContextImpl( 5484): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
D/WifiDataStallTracker(  947): setDhcpActive: false
V/BluetoothPbapService( 3142): Pbap Service closeService in
V/BluetoothPbapService( 3142): Pbap Service closeService out
D/TelephUtils( 1444): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 83
D/MmsSmsV2Provider( 1444):  slotId = -1000
D/MmsSmsV2Provider( 1444): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
D/Messaging( 5349): ViewCache CreatePreload
D/Messaging( 5349): ViewCache CreatePreloadOnlyMultipleOpsList
D/BluetoothAdapter( 5434): 557184488: getState(). Returning 13
D/PMS     (  947): acquireWL(2d891039): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5484 1000 null
D/Cust_MMSMS( 5349): _has_set_default_values_2=true
D/TelephUtils( 1444): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
V/MmsProvider( 1444): Update uri=content://mms, match=0
V/MmsProvider( 1444): selection=st=129 AND m_type!=134
D/MsgPreferenceUtils( 5349): def_index: 0
D/PowerUsageList:PowerUsageHelper( 5484): MY_DEBUG = false
D/CustomizationManager( 5510):  Read ACC file spent 0.039 (s)
,D/CIDMapFileReader( 5510): Parsing tag item name = HTC__001,
,I/ActivityManager(  947): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=5562 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a
D/CIDMapFileReader( 5510): Parsing tag item name = HTC__102
D/ConnectivityService(  947): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/CIDMapFileReader( 5510): Parsing tag item name = HTC__Y13
D/ConnectivityService(  947):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CIDMapFileReader( 5510): Parsing tag item name = HTC__032
D/ConnectivityService(  947):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/CIDMapFileReader( 5510): Parsing tag item name = HTC__M27
D/ConnectivityService(  947): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/CIDMapFileReader( 5510): Parsing tag item name = HTC__002
D/Nat464Xlat(  947): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
D/CIDMapFileReader( 5510): Parsing tag item name = HTC__031
D/ConnectivityService(  947): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/CustomizationCIDLoader( 5510): full path : /system/customize/CID/HTC__102.xml
D/ConnectivityService(  947): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
I/CustomizationCIDLoader( 5510): Parsing tag category name = system
D/NetworkManagementService(  947): Removing idletimer
I/CustomizationCIDLoader( 5510): Parsing tag category name = application
D/PMS     (  947): acquireWL(cef42fb): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 947 1000 null
I/CustomizationCIDLoader( 5510): Parsing tag category name = SettingsProvider
D/CSLegacyTypeTracker(  947): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
I/CustomizationCIDLoader( 5510): Parsing tag category name = AutomotiveHome
D/ConnectivityService(  947): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/CustomizationCIDLoader( 5510): Parsing tag category name = AudioService
D/ConnectivityService(  947): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
I/CustomizationCIDLoader( 5510): Parsing tag category name = Settings
E/ConnectivityService(  947): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
I/CustomizationCIDLoader( 5510): Parsing tag category name = ACC
V/NetworkPolicy(  947): ensureActiveMobilePolicyLocked()
I/CustomizationCIDLoader( 5510): add string-array item, value = 42507
D/PMS     (  947): acquireWL(316a2f18): PARTIAL_WAKE_LOCK  NetworkStats 0x1 947 1000 null
I/CustomizationCIDLoader( 5510): add string-array item, value = 21902
D/DATA_ICON( 1224): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
I/CustomizationCIDLoader( 5510): add string-array item, value = 26006:26001.26002.26003
D/PMS     (  947): releaseWL(316a2f18): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
I/CustomizationCIDLoader( 5510): add string-array item, value = 23420
D/NetworkPolicy(  947): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
I/CustomizationCIDLoader( 5510): add string-array item, value = 22299
V/NetworkPolicy(  947): updateNetworkEnabledLocked()
I/CustomizationCIDLoader( 5510): add string-array item, value = 24002
V/NetworkPolicy(  947): updateIfacesLocked()
I/CustomizationCIDLoader( 5510): add string-array item, value = 23210
V/NetworkPolicy(  947): updateNotificationsLocked()
I/CustomizationCIDLoader( 5510): add string-array item, value = 23205
D/DATA_ICON( 1224): dataConnected: false/false,
I/CustomizationCIDLoader( 5510): add string-array item, value = 23806
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/CustomizationCIDLoader( 5510): add string-array item, value = 23430
D/WIFI_ICON( 1224): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/CustomizationCIDLoader( 5510): add string-array item, value = 23408
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/CustomizationCIDLoader( 5510): add string-array item, value = 27205
V/NetworkPolicy(  947): updateNetworkEnabledLocked()
I/CustomizationCIDLoader( 5510): add string-array item, value = 42507:C:1:0
V/NetworkPolicy(  947): updateNotificationsLocked()
I/CustomizationCIDLoader( 5510): add string-array item, value = 21902:C:1:0
D/WIFI_ICON( 1224): updateWifiState: WIFI_STATE_CHANGED disabled
I/CustomizationCIDLoader( 5510): add string-array item, value = 26006:D:1:0
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/CustomizationCIDLoader( 5510): add string-array item, value = 23420:D:0:0
D/NetworkManagementService(  947): isBandwidthControlEnabled: doneSignal.getCount()= 0
I/CustomizationCIDLoader( 5510): add string-array item, value = 22299:D:0:0
D/WifiService(  947): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
I/CustomizationCIDLoader( 5510): add string-array item, value = 24002:D:0:0
D/WifiService(  947): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
I/CustomizationCIDLoader( 5510): add string-array item, value = 23210:D:2:0
D/WifiService(  947): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
I/CustomizationCIDLoader( 5510): add string-array item, value = 23205:D:0:0
W/ContextImpl( 5434): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1888 android.content.ContextWrapper.bindService:538 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1423 
I/CustomizationCIDLoader( 5510): add string-array item, value = 23806:D:0:0
D/WifiService(  947): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
I/CustomizationCIDLoader( 5510): add string-array item, value = 23430:C:1:0
D/WifiService(  947): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
I/CustomizationCIDLoader( 5510): add string-array item, value = 23408:C:1:0
D/WifiService(  947): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
I/CustomizationCIDLoader( 5510): add string-array item, value = 27205:C:1:0
D/PMS     (  947): acquireWL(299c485c): PARTIAL_WAKE_LOCK  NetworkStats 0x1 947 1000 null
D/CustomizationManager( 5510):  Read CID file spent 0.086 (s)
D/UsbDeviceManager(  947): [USBNET] bCheckSuppFunc: cdc_network
D/CustomizationManager( 5510):  All configurations done spent 0.086 (s)
D/PMS     (  947): releaseWL(299c485c): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/BluetoothInputDevice( 5434): BluetoothInputDevice()
V/NetworkPolicy(  947): updateNetworkEnabledLocked()
D/BluetoothManagerService(  947): registerStateChangeCallback+
V/NetworkPolicy(  947): updateNotificationsLocked()
D/BluetoothManagerService(  947): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/WifiService(  947): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
D/BluetoothManagerService(  947): Registered receivers: 9
D/WifiService(  947): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
D/Messaging( 5349): Reset downloading state: 0
D/WifiService(  947): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
V/Mms,SystemEventReceiver( 5349): TransactionService is going to be woken up.
D/WifiService(  947): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
D/HtcBtWidget_BTWidgetProvider( 5531): onBTStateChanged() for widget: 
D/WifiService(  947): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
D/PowerUsageService( 5484): repeat time = 1448299889882
D/WifiService(  947): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
D/HtcBtWidget_BTWidgetProvider( 5531): updateWidget(context) for widget: 
V/TransactionService( 5349): 1-Creating TransactionService
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  947): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 1224): CM callback handler got msg 524292
I/SecurityController( 1224): onLost 100
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  947): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  947): Disconnected - quitting
E/WifiStateMachine(  947): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  947): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/Tethering(  947): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering(  947): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/BluetoothPan( 5434): BluetoothPan()
E/WifiStateMachine(  947): stopping supplicant
W/WifiHW  (  947): QCOM Debug wifi_send_command "TERMINATE"
D/wpa_supplicant( 1371): RX global ctrl_iface - hexdump(len=9): 54 45 52 4d 49 4e 41 54 45
D/WifiService(  947): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
D/wpa_supplicant( 1371): wlan0: Removing interface wlan0
D/BluetoothManagerService(  947): registerStateChangeCallback+
E/WifiStateMachine(  947): setWifiState: disabling
E/WifiTrafficPoller(  947): ENABLE_TRAFFIC_STATS_POLL false Token 14
D/BluetoothManagerService(  947): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/usbnet  (  947): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  947):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  947): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/BluetoothManagerService(  947): Registered receivers: 10
V/TransactionService( 5349): onStartCommand: 1
D/MmsSystemEventReceiver( 5349): unRegisterForConnectionStateChanges
V/TransactionService( 5349): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 5349): Loading previous transactions.
E/WifiStateMachine(  947): handleMessage: X
E/WifiStateMachine(  947): handleMessage: E msg.what=131131
E/WifiStateMachine(  947): processMsg: SupplicantStoppingState
E/WifiStateMachine(  947):  SupplicantStoppingState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  947): processMsg: DefaultState
I/IntentController( 1224): receive(android.net.wifi.STATE_CHANGE,1,false)
D/MsgPreferenceUtils( 5349): globalIndex = 1
E/WifiStateMachine(  947):  DefaultState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  947): handleMessage: X
D/WIFI    (  947): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  947):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&N,OT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  947): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
E/WifiStateMachine(  947): enter WifiNetworkFactory startNetwork. mIPTStart:false
E/WifiStateMachine(  947): handleMessage: E msg.what=196614
E/WifiStateMachine(  947): processMsg: SupplicantStoppingState
D/wpa_supplicant( 1371): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1371): TDLS: Tear down peers
D/wpa_supplicant( 1371): wpa_driver_nl80211_disconnect(reason_code=3)
E/WifiStateMachine(  947):  SupplicantStoppingState !CMD_ON_QUIT 0 0
E/WifiStateMachine(  947): processMsg: DefaultState
E/WifiStateMachine(  947):  DefaultState !CMD_ON_QUIT 0 0
E/WifiStateMachine(  947): handleMessage: X
I/IntentController( 1224): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/MsgPreferenceUtils( 5349): phone state: true
D/MsgPreferenceUtils( 5349): sd state: false
D/MsgPreferenceUtils( 5349): vIndex = 0
D/PMS     (  947): releaseWL(27be1b1b): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
D/WISPrService( 5434): >>>>>WISPrService start isConnected = false<<<<<
D/BluetoothMap( 5434): Create BluetoothMap proxy object
D/WISPrService( 5434): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/BluetoothManagerService(  947): registerStateChangeCallback+
D/BluetoothManagerService(  947): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  947): Registered receivers: 11
E/BluetoothMap( 5434): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
I/bt-btif ( 3142): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 3142): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterService( 3142): mProfilesStarted : true supportedProfileServices.length : 6
D/BluetoothManagerService(  947): registerStateChangeCallback+
D/BluetoothSap( 5434): BluetoothSap() call bindService
D/BluetoothManagerService(  947): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  947): Registered receivers: 12
D/BluetoothAdapterState( 3142): Stopping profile services that were post enabled
D/WeatherUtility( 1587): Weather sync is On
D/BluetoothPbap( 5434): BluetoothPbap()
D/BluetoothManagerService(  947): registerStateChangeCallback+
D/BluetoothManagerService(  947): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  947): Registered receivers: 13
D/wpa_supplicant( 1371): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 1371): wlan0: Deauthentication notification
D/wpa_supplicant( 1371): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1371): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1371): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1371): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
E/wpa_supplicant( 1371): enter disconnect check
I/wpa_supplicant( 1371): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/WifiMonitor(  947): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462]
E/WifiMonitor(  947): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
E/WifiMonitor(  947): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/HTCRequest(  947): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
E/WifiMonitor(  947): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
E/WifiStateMachine(  947): handleMessage: E msg.what=147460
E/WifiStateMachine(  947): processMsg: SupplicantStoppingState
D/wpa_supplicant( 1371): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 1371): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/LocalBluetoothProfileManager( 5434): LocalBluetoothProfileManager construction complete
D/WSP     ( 1587): [Receiver] auto sync agent, auto sync is enabled, reset schedule
E/WifiStateMachine(  947):  SupplicantStoppingState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=67170
E/WifiStateMachine(  947): processMsg: DefaultState
E/WifiStateMachine(  947):  DefaultState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=67171
E/WifiStateMachine(  947): handleMessage: X
D/Tethering(  947): interfaceLinkStateChanged wlan0, false
D/Tethering(  947): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  947): WiFiDisplay: getWifidisplayApEnabled=false
I/QuickSettingWifi( 1224): receive.wifiConnect:false wifiAPname:null elapse:0
D/Tethering(  947): interfaceLinkStateChanged wlan0, false
D/Tethering(  947): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  947): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  947): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
I/QuickSettingWifi( 1224): receive.wifiState:WIFI_STATE_DISABLING setEnable:false
V/Tethering(  947): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  947): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiStateMachine(  947): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  947): sendTetherStateChangedBroadcast 0, 0, 0
D/UsbnetService(  947): BroadcastReceiver::onReceive+
E/WifiStateMachine(  947): handleMessage: E msg.what=131101
E/WifiStateMachine(  947): processMsg: SupplicantStoppingState
D/UsbnetService(  947): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  947): BroadcastReceiver::onReceive-
E/WifiStateMachine(  947):  SupplicantStoppingState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  947): processMsg: DefaultState
E/WifiStateMachine(  947):  DefaultState !CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  947): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  947): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  947): handleMessage: X
D/wpa_supplicant( 1371): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1371): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 1371): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1371): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1371): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x5597670f88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1371):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1371): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1371): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1371): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1371): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1371): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1371): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1371): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1371): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1371): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1371): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1371): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1371): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1371): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1371): EAPOL: External notification - portEnabled=0
D/WifiMonitor(  947): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 1371): EAPOL: External notification - portValid=0
E/WifiMonitor(  947): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  947): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  947): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  947): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  947): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/WifiStateMachine(  947): handleMessage: E msg.what=147462
E/WifiStateMachine(  947): processMsg: SupplicantStoppingState
E/WifiStateMachine(  947):  SupplicantStoppingState !SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=67184  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  947): processMsg: DefaultState
E/WifiStateMachine(  947):  DefaultState !SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=67184  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  947): handleMessage: X
D/DockEventReceiver( 5434): finishStartingService: stopping service
D/WISPrService( 5434): >>>>>WISPrService start isConnected = false<<<<<
D/BluetoothInputDevice( 5434): Proxy object connected
D/WISPrService( 5434): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/HidProfile( 5434): Bluetooth service connected
D/BluetoothAdapter( 5434): 557184488: getState(). Returning 13
D/WISPrService( 5434): >>>>>WISPrService start isConnected = false<<<<<
D/BluetoothPan( 5434): BluetoothPAN Proxy object connected
D/WISPrService( 5434): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/PanProfile( 5434): Bluetooth service connected
D/SapServerProfile( 5434): Bluetooth service connected
I/ActivityManager(  947): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5606 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a
I/art     (  947): Explicit concurrent mark sweep GC freed 32950(1776KB) AllocSpace objects, 3(392KB) LOS objects, 33% free, 16MB/25MB, paused 2.085ms total 200.889ms
D/TelephUtils( 1444): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/AccFlag ( 1444): device_type: 1
D/MdScPhnSt( 5088): [f3d.2.]  listen tmrbb8
D/HeadsetService( 3142): Received stop request...Stopping profile...
,D/Messaging( 5349): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/TelephUtils( 1444): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/Jerry   ( 1444): URI_DRAFT
D/BluetoothAdapterService( 3142): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26a6be64
D/HeadsetStateMachine( 3142): Exit Disconnected: -1
D/TransactionService( 5349): Force clearing mTransactionList
D/TransactionService( 5349): Force set service start id to 1
V/TransactionService( 5349): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 5349): unRegisterForConnectionStateChanges
D/BluetoothHeadset( 1224): Proxy object disconnected
I/QuickSettingMiniLite( 1224): btListener.disconnect:HEADSET
D/BluetoothHeadset(  947): Proxy object disconnected
D/WeatherUtility( 5562): Weather sync is On
D/BluetoothHeadset( 3807): Proxy object disconnected
D/NGFService( 3807): BluetoothHeadset onServiceDisconnected: main
D/PackageManager(  947): deletePackageAsUser: pkg=com.example.hello, pid=5510, uid=2000 userid=0
D/WifiService(  947): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
D/TransactionService( 5349): stopSelfResult: true, mLastHandledServiceId: 1
D/DraftCache( 5349): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 5349): [DraftCache/121] rebuildCache time: 2
D/MmsAsyncWorkHandler( 5349): 
D/MmsAsyncWorkHandler( 5349): HM tk = 20002
I/ActivityManager(  947): Force stopping com.example.hello appid=10373 user=-1: uninstall pkg
I/ActivityManager(  947): Killing 4978:com.example.hello/u0a373 (adj 0): stop com.example.hello
D/Process (  947): killProcessQuiet, pid=4978
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
V/TransactionService( 5349): Destroying TransactionService
,W/PackageSettings(  947): Skipping PackageSetting{376b17e com.test.thalitest/10366} due to missing metadata
,E/WifiStateMachine(  947): handleMessage: E msg.what=131165
E/WifiStateMachine(  947): processMsg: SupplicantStoppingState
D/A2dpService( 3142): Received stop request...Stopping profile...
E/WifiStateMachine(  947):  SupplicantStoppingState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine(  947): processMsg: DefaultState
,E/WifiStateMachine(  947):  DefaultState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine(  947): handleMessage: X
D/A2dpStateMachine( 3142): Exit Disconnected: -1
D/BluetoothAdapterService( 3142): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26a6be64
,D/TelephUtils( 1444): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/MmsSmsV2Provider( 1444):  slotId = -1000
D/MmsSmsV2Provider( 1444): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,W/BluetoothHeadset( 1224): Proxy not attached to service
,I/QuickSettingMiniLite( 1224): updateLiteState:no connect device!
,I/ActivityManager(  947): Recipient 4978,
,E/InputEventReceiver( 1382): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{6e7b85 uid 10373 pid 4978} (c)'
I/WindowState(  947): WIN DEATH: Window{119bebc9 u0 com.example.hello/com.example.hello.MainActivity},
D/WifiService(  947): Client connection lost with reason: 4
,E/wpa_supplicant( 1371): wlan0: BLACKLIST CLEAR ,
D/wpa_supplicant( 1371): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush
D/wpa_supplicant( 1371): wlan0: BSS: Remove id 1 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700' due to wpa_bss_flush
D/wpa_supplicant( 1371): wlan0: BSS: Remove id 3 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush
D/wpa_supplicant( 1371): wlan0: BSS: Remove id 2 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush
D/wpa_supplicant( 1371): wlan0: Cancelling delayed sched scan
D/wpa_supplicant( 1371): wlan0: Cancelling scan request
D/wpa_supplicant( 1371): wlan0: Cancelling authentication timeout
D/WifiMonitor(  947): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/wpa_supplicant( 1371): wlan0: BLACKLIST REMOVE 00:00:00:00:00:00
E/WifiMonitor(  947): WifiMonitor:wlan0 cnt=28 dispatchEvent: BLACKLIST CLEAR 
D/WifiMonitor(  947): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  947): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  947): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:48]
E/WifiMonitor(  947): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:48
D/WifiMonitor(  947): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 a0:c5:62:7a:49:97]
E/WifiMonitor(  947): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 a0:c5:62:7a:49:97
D/WifiMonitor(  947): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11]
E/WifiMonitor(  947): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11
D/WifiMonitor(  947): Event [IFNAME=wlan0 BLACKLIST REMOVE 00:00:00:00:00:00]
E/WifiMonitor(  947): WifiMonitor:wlan0 cnt=33 dispatchEvent: BLACKLIST REMOVE 00:00:00:00:00:00
D/wpa_supplicant( 1371): Remove interface wlan0 from radio phy0
W/ActivityManager(  947): Force removing ActivityRecord{2252f541 u0 com.example.hello/.MainActivity t8}: app died, no saved state
,V/TransactionService( 5349): 4-Handling incoming message: { when=-217ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/Messaging( 5349): mNeedToUpdateDate2: false
D/MdProvGlob( 5114): remove item 101 (p2d9in140) for 15:android.intent.action.ANY_DATA_STATE
,D/MdScDataSum( 5088): [f3d.2.] summary 118:p2 ignore
I/ActivityManager(  947): Force stopping com.example.hello appid=10373 user=0: pkg removed
,E/WifiTrafficPoller(  947): TRAFFIC_STATS_POLL false Token 15 num clients 8
,W/ActivityManager(  947): Spurious death for ProcessRecord{221db4e1 4978:com.example.hello/u0a373}, curProc for 4978: null,
D/BluetoothA2dp( 3807): Proxy object disconnected
D/NGFService( 3807): BluetoothA2dp onServiceDisconnected: main
,D/TelephUtils( 1444): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50,
D/AccFlag ( 1444): sku_id=118
D/PMS     (  947): acquireWL(1ac8c206): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1848 10024 WorkSource{10024 com.google.android.gms}
D/BluetoothA2dp(  947): Proxy object disconnected
D/HidService( 3142): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3142): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26a6be64
D/BluetoothHeadset( 1444): Proxy object disconnected
D/BluetoothPhoneService( 1444): BluetoothHeadset onServiceDisconnected
D/BluetoothHeadset( 1444): Proxy object disconnected
D/BluetoothHeadset( 1444): Proxy object disconnected
D/DotMatrix( 1308): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1308): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1308): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
I/Prism.ItemManager( 5273): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Prism.ItemManager( 5273): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/FeedHostManager( 1506): [onResume]
I/FeedProviderManager( 1506): onResume
I/SocialFeedProvider( 1506): +onResume
I/SocialFeedProvider( 1506): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1506): -onResume
W/GeofencerStateMachine( 1848): Ignoring removeGeofence because network location is disabled.
D/AccTypeManager( 1710): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,I/PowerUsageList:PowerUsageHelper( 5484): PowerProfile::POWER_SCREEN_FULL = 154.8
I/ConnectivityHelper( 1506): [getCurrentConnectionType] no network connection
,D/PMS     (  947): releaseWL(1ac8c206): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/BluetoothInputDevice( 5434): Proxy object disconnected
D/HidProfile( 5434): Bluetooth service disconnected
D/wpa_supplicant( 1371): nl80211: Remove monitor interface: refcount=0
D/wpa_supplicant( 1371): netlink: Operstate: ifindex=29 linkmode=0 (kernel-control), operstate=6 (IF_OPER_UP)
,D/HealthService( 3142): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 3142): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26a6be64
,W/SystemReader(  947): Cannot find grip_rejection_width, use default value instead
,D/MdProvGlob( 5114): remove item 101 (p2in232) for 15:android.intent.action.ANY_DATA_STATE
D/AccTypeManager( 1710): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/TelephUtils( 1444): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
,D/AccFlag ( 1444): sku_id=118
W/WeatherRequest( 5562): request cur loc, but there is no sys cur
W/Settings( 5562): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/InputMethodManagerService(  947): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false,
D/PanService( 3142): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 3142): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26a6be64
D/BtGatt.DebugUtils( 3142): handleDebugAction() action=null
D/BtGatt.GattService( 3142): Received stop request...Stopping profile...
D/BtGatt.GattService( 3142): stop()
D/BtGatt.AdvertiseManager( 3142): advertise clients cleared
D/BluetoothPan( 5434): BluetoothPAN Proxy object disconnected
D/PanProfile( 5434): Bluetooth service disconnected
,D/BluetoothAdapterService( 3142): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26a6be64
D/AccTypeManager( 1710): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/StatusBarManagerService(  947): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  947): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  947): hiding MENU key
,D/MdProvGlob( 5114): remove item 101 (p2in71) for 15:android.intent.action.ANY_DATA_STATE,
,W/BluetoothHeadsetServiceJni( 3142): Cleaning up Bluetooth Handsfree Interface...,
W/BluetoothHeadsetServiceJni( 3142): Cleaning up Bluetooth Handsfree callback object
,W/BluetoothHidServiceJni( 3142): Cleaning up Bluetooth HID Interface...
,W/BluetoothHidServiceJni( 3142): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 3142): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3142): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3142): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3142): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterState( 3142): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothFtpService( 3142): ACTION_STATE_CHANGED: state: 13mHasStarted: true
E/BluetoothFtpService:RfcommSocketAcceptThread( 3142): Shutdown
D/BluetoothAdapterProperties( 3142): Setting state to 10
I/BluetoothAdapterState( 3142): Bluetooth adapter state changed: 13-> 10
D/BluetoothManagerService(  947): +onBluetoothStateChange prev=13 new=10
I/BluetoothAdapterState( 3142): Entering OffState
D/BluetoothManagerService(  947): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  947): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  947): Broadcasting onBluetoothStateChange(false) to 13 receivers.
D/BluetoothMasReceiver( 3142): Bluetooth STATE CHANGED to 13
,D/wpa_supplicant( 1371): nl80211: Set mode ifindex 29 iftype 2 (STATION)
,D/wpa_supplicant( 1371): nl80211: Unsubscribe mgmt frames handle 0x888888dd1fefa989 (mode change)
I/wpa_supplicant( 1371): htc_wext_command_deinit +
I/wpa_supplicant( 1371): htc_wext_command_deinit -
I/wpa_supplicant( 1371): wlan0: CTRL-EVENT-TERMINATING 
D/Tethering(  947): interfaceLinkStateChanged wlan0, false
D/Tethering(  947): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  947): WiFiDisplay: getWifidisplayApEnabled=false
D/WifiMonitor(  947): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
E/WifiMonitor(  947): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-TERMINATING 
D/wpa_supplicant( 1371): Control interface directory not empty - leaving it behind
D/wpa_supplicant( 1371): p2p0: Removing interface p2p0
D/WifiMonitor(  947): Disconnecting from the supplicant, no more events
D/wpa_supplicant( 1371): p2p0: Request to deauthenticate - bssid=00:00:00:00:00:00 pending_bssid=00:00:00:00:00:00 reason=3 state=DISCONNECTED
D/wpa_supplicant( 1371): TDLS: Tear down peers
D/wpa_supplicant( 1371): p2p0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1371): nl80211: Set p2p0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1371): netlink: Operstate: ifindex=30 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1371): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1371): EAPOL: External notification - portValid=0
E/WifiStateMachine(  947): handleMessage: E msg.what=147458
E/WifiStateMachine(  947): processMsg: SupplicantStoppingState
E/WifiStateMachine(  947):  SupplicantStoppingState !SUP_DISCONNECTION_EVENT 34 0
E/WifiStateMachine(  947): Supplicant connection lost
D/BluetoothHeadset( 1224): onBluetoothStateChange: up=false
I/ActionCombine( 5562): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
D/BluetoothPbap( 5434): onBluetoothStateChange: up=false
V/BluetoothSapReceiver( 3142): SapReceiver onReceive 
V/BluetoothSapReceiver( 3142): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3142):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 3142): startService = false
D/FindExtension( 1506): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
D/BluetoothSap( 5434): onBluetoothStateChange on: false
V/BluetoothSapService( 3142): cleanup: mService: com.android.bluetooth.sap.BluetoothSapService@7901860
E/ExternalAccountType( 1710): Unsupported attribute readOnly
,I/ThreadedRenderer( 1506): Defer allocateBuffers to drawing time,
,D/PhoneApp( 1444): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/AuthorizationBluetoothService( 1873): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/Prism.ItemManager( 1506): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1506): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/[PluginManager]RegisterService( 1587): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello
I/[PluginManager]RegisterService( 1587): handle notify Blinkfeed plugin client changed
,E/[PluginManager]RegisterService( 1587): Unable to getApplicationInfo for com.example.hello,
E/[PluginManager]RegisterService( 1587): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
E/[PluginManager]RegisterService( 1587): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:281)
E/[PluginManager]RegisterService( 1587): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
E/[PluginManager]RegisterService( 1587): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
E/[PluginManager]RegisterService( 1587): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/[PluginManager]RegisterService( 1587): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/[PluginManager]RegisterService( 1587): 	at android.os.Looper.loop(Looper.java:155)
E/[PluginManager]RegisterService( 1587): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/BluetoothHeadset( 1444): onBluetoothStateChange: up=false,
W/InputMethodManagerService(  947): Got RemoteException sending setActive(false) notification to pid 4978 uid 10373
D/StatusBarManagerService(  947): swetImeWindowStatus vis=0 backDisposition=0
D/PowerUsageList:BatterySipperExt( 5484): gen(), null == sipper.uidObj, userId = 0
I/InputMethodManagerService(  947): Enable input method client, pid=1506
,D/BluetoothA2dp( 3807): onBluetoothStateChange: up=false
,D/PowerUsageList:BatterySipperExt( 5484): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageList:BatterySipperExt( 5484): gen(), null == sipper.uidObj, userId = 0
D/BluetoothA2dp(  947): onBluetoothStateChange: up=false
D/BluetoothPan( 5434): onBluetoothStateChange on: false
D/BluetoothInputDevice( 5434): onBluetoothStateChange: up=false
D/BluetoothHeadset(  947): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1444): onBluetoothStateChange: up=false
D/BluetoothMap( 5434): onBluetoothStateChange: up=false
E/BluetoothMap( 5434): 
E/BluetoothMap( 5434): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothMap$2@378f9a00
E/BluetoothMap( 5434): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1135)
E/BluetoothMap( 5434): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1940)
E/BluetoothMap( 5434): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
E/BluetoothMap( 5434): 	at android.bluetooth.BluetoothMap$1.onBluetoothStateChange(BluetoothMap.java:64)
E/BluetoothMap( 5434): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothMap( 5434): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothHeadset( 1444): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 3807): onBluetoothStateChange: up=false
,D/PowerUsageService( 5484): calcPower(), no data
,D/Process (  947): killProcessQuiet, pid=5057
I/ActivityManager(  947): Killing 5057:com.google.android.apps.magazines/u0a161 (adj 15): empty #17,
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/BluetoothManagerService(  947): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  947): Broadcasting onBluetoothServiceDown() to 9 receivers.
D/BluetoothAdapter( 1848): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@52f21bc
D/BluetoothAdapter( 1848): onBluetoothServiceDown: done
D/BluetoothAdapter( 1444): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@240f7630
D/BluetoothAdapter( 1444): onBluetoothServiceDown: done
D/BluetoothAdapter( 3142): onBluetoothServiceDown: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@e435cd0
D/BluetoothAdapter( 3142): onBluetoothServiceDown: done
,D/BluetoothAdapter( 1463): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@2e569401
D/BluetoothAdapter( 1463): onBluetoothServiceDown: done
D/BluetoothAdapter( 1224): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@186553a4
D/BluetoothAdapter( 1224): onBluetoothServiceDown: done
,W/PackageManager(  947): Unable to load service info ResolveInfo{173eee43 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  947): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  947): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  947): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  947): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  947): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  947): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  947): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  947): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  947): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  947): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  947): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  947): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  947): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  947): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  947): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  947): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
D/BluetoothAdapter( 3807): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@3976f3d
D/BluetoothAdapter( 3807): onBluetoothServiceDown: done
D/BluetoothAdapter( 5434): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@510c239
D/BluetoothAdapter( 5434): onBluetoothServiceDown: done
D/BluetoothAdapter(  947): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@26a343f8
D/BluetoothAdapter(  947): onBluetoothServiceDown: done
D/Prism.PackageStateRece_( 1506): action: android.intent.action.PACKAGE_ADDED
W/ResourcesManager(  947): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/BluetoothAdapter( 2391): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@b756334
D/BluetoothAdapter( 2391): onBluetoothServiceDown: done
,D/BluetoothManagerService(  947): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@26a343f8 mBinding = false
D/BluetoothManagerService(  947): Sending unbind request.
,D/StatusBarManagerService(  947): setSystemUiVisibility(0xc0000700)
,D/StatusBarManagerService(  947): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  947): hiding MENU key
,D/MediaProvider( 3950): [update][15]#1#
,D/MediaScanner( 3950):  prescan time: 810ms
,D/MediaScanner( 3950):     scan time: 1268ms
D/MediaScanner( 3950): postscan time: 2ms
D/MediaScanner( 3950):    total time: 2080ms
D/MediaScanner( 3950): -----------------------------------------------------------------
D/MediaScanner( 3950): firstscan(media) time: 350ms
D/MediaScanner( 3950): secondscan(non-media) time: 918ms
D/MediaScanner( 3950):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 1
D/MediaScanner( 3950):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3950):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3950):  [Total]    File(Image+Video+Audio+Others) in database : 1546
,I/art     (  947): Explicit concurrent mark sweep GC freed 18445(1394KB) AllocSpace objects, 3(328KB) LOS objects, 33% free, 16MB/25MB, paused 1.895ms total 250.179ms,
,W/asset   (  947): Copying FileAsset 0x5589f560d0 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,D/MediaProvider( 3950): [delete][23]
D/MediaProvider( 3950): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
,D/MediaProvider( 3950): [recoverParentNodes] - 0
,D/MediaProvider( 3950): [update][7]
D/MediaScannerServiceEx( 3950): [scan] Recover Parent Node is finished!
D/MediaScannerServiceEx( 3950): [updateImage]+
I/ActivityManager(  947): Recipient 5057
,D/MediaScannerServiceEx( 3950): [updateImage]-0
,I/ActivityManager(  947): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5642 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,D/MdProvGlob( 5114): remove item 101 (p2d5in165) for 15:android.intent.action.ANY_DATA_STATE
,D/BluetoothManagerService(  947): Bluetooth State Change Intent: 13 -> 10
D/PMS     (  947): releaseWL(1b251988): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
D/MediaScannerServiceEx( 3950): [1] scan finished,
,D/MediaProviderUtils( 3950): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3950): calcVolumeId: /storage/ext_sd
D/LocalBluetoothProfileManager( 5434): setBluetoothStateOff
I/bt-btif ( 3142): HAL bt_hal_cbacks->thread_evt_cb
I/IntentController( 1224): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/NGFService( 3807): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
D/NGFService( 3807): Bluetooth Adapter: OFF
W/BluetoothEventManager( 5434): unregister mProfileBroadcastReceiver fail
D/MediaProviderUtils( 3950): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3950): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1
W/MediaScannerServiceEx( 3950): Process mounted intent for unmounted storage: /storage/ext_sd
,I/art     ( 3142): System.exit called, status: 0
D/TetherPref( 5434): persistRestoreBluetoothState false
,D/MediaScannerServiceEx( 3950): [disAliveExtStorageRows]+131073
,D/MediaProvider( 3950): [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted
,D/MediaProvider( 3950): [update][7]#1#
,D/MdProvGlob( 5114): remove item 101 (p2in129) for 15:android.intent.action.ANY_DATA_STATE
D/JobSchedulerService(  947): Receieved: android.intent.action.PACKAGE_REMOVED
,D/WifiService(  947): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
I/PhoneStatusBar( 1224): setImeWindowStatus(false,false)
D/MediaProvider( 3950): [update][24]#0#
D/TaskPersister(  947): removeObsoleteFile: deleting file=8_task.xml
D/MediaScannerServiceEx( 3950): [disAliveExtStorageRows]--1, 0
,D/MediaProviderUtils( 3950): calcVolumeId: /storage/emulated/0
,D/MediaProviderUtils( 3950): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3950): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3950): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
W/MediaScannerServiceEx( 3950): Process mounted intent for unmounted storage: /storage/usb
I/RemoteViews( 1506): reapply : com.htc.widget.weatherclock 9 17
,D/MediaScannerServiceEx( 3950): [disAliveExtStorageRows]+196609
,D/NfcHandover( 1463): onReceive: mBound=false, BTByNfc=false->false, BTHConnected=false->false
I/ActivityManager(  947): Recipient 3142
,I/ActivityManager(  947): Process com.android.bluetooth (pid 3142) has died
,W/ActivityManager(  947): Scheduling restart of crashed service com.android.bluetooth/.map.BluetoothMasService in 1000ms
W/ActivityManager(  947): Scheduling restart of crashed service com.android.bluetooth/.sap.BluetoothSapService in 11000ms
,I/BroadcastQueue(  947): Schedule to resend BroadcastRecord{2be38e4f u-1 android.bluetooth.adapter.action.STATE_CHANGED callingPid=947 callingUid=1000} for ResolveInfo{2559d9dc com.android.bluetooth/.pbap.BluetoothPbapReceiver m=0x108000} of com.android.bluetooth
,D/MediaProvider( 3950): [sendStorageAddedIfNeed]: /storage/usb : unmounted
,D/BluetoothAdapter( 1224): 328666834: getState() :  mService = null. Returning STATE_OFF
I/QuickSettingBluetooth( 1224): receive.ACTION_STATE_CHANGE:STATE_OFF/(false,false)
D/MediaProvider( 3950): [update][17]#1#
,E/WifiTrafficPoller(  947): TRAFFIC_STATS_POLL false Token 15 num clients 8
,I/ActivityManager(  947): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=5665 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3008} abi=armeabi-v7a
,D/MdProvGlob( 5114): remove item 101 (p2d2in38) for 15:android.intent.action.ANY_DATA_STATE
,D/MediaProvider( 3950): [update][28]#0#
D/MdScDataSum( 5088): [f3d.10.] summary 118:p1 ignore
D/MediaScannerServiceEx( 3950): [disAliveExtStorageRows]--1, 0
,I/DeviceManagement( 5642): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=5642 dbg=false s=true,
,D/MdProvGlob( 5114): remove item 101 (p2d1in49) for 15:android.intent.action.ANY_DATA_STATE
,I/DeviceManagement( 5642): PackageUpdateReceiver: vvv Package added: [com.example.hello]
,I/ActivityManager(  947): Killing 5205:com.android.chrome/u0a96 (adj 15): empty #17
D/Process (  947): killProcessQuiet, pid=5205
,D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/wpa_ctrl(  947): [wpa_ctrl_close] ctrl=0x5589d6ed70
I/wpa_ctrl(  947): [wpa_ctrl_close] ctrl=0x5589d6ee60
,I/ActivityManager(  947): Recipient 5205,
,W/OpenGLRenderer( 1506): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...,
,V/AlarmManager(  947): sending alarm PendingIntent{23cafae5: PendingIntentRecord{7fcc9ba com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1448298990986, Int=0
,W/ResourcesManager( 5665): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/ActivityManager(  947): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=5689 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a
,D/Process (  947): killProcessQuiet, pid=5231,
I/ActivityManager(  947): Killing 5231:com.google.android.apps.plus/u0a167 (adj 15): empty #17
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/MdProvGlob( 5114): remove item 101 (p2d2in234) for 15:android.intent.action.ANY_DATA_STATE
,I/ActivityManager(  947): Recipient 5231
,E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0,
,E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	,at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128),
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): ,	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
,E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
,E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
,E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
,E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( ,5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(Thr,eadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
,E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/WifiStateMachine(  947): setWifiState: disabled
D/WifiStateMachine(  947): Enter handleNetworkDisconnect
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/WifiStateMachine(  947): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - handleNetworkDisconnect - access$12300 - processMessage
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
D/PMS     (  947): acquireWL(2bf4c06b): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 947 1000 null
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/WifiStateMachine(  947): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  947): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
D/WifiStateMachine(  947): Exit handleNetworkDisconnect
D/WIFI_ICON( 1224): updateWifiState: WIFI_STATE_CHANGED disabled
E/WifiStateMachine(  947): [MLHD] Error! unhandled message 6 { when=-731ms what=147458 arg1=34 target=com.android.internal.util.StateMachine$SmHandler }
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  947): transitionTo: destState=InitialState
D/WIFI_ICON( 1224): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  947): handleMessage: new destination call exit/enter
D/StatusBar.NetworkController( 1224): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  947): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  947): invokeExitMethods: SupplicantStoppingState
E/WifiStateMachine(  947): moveTempStackToStateStack: i=0,j=1
E/WifiStateMachine(  947): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=InitialState
E/WifiStateMachine(  947): invokeEnterMethods: InitialState
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
I/IntentController( 1224): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/AdapterServiceConfig( 5665): Adding HeadsetService
D/AdapterServiceConfig( 5665): Adding A2dpService
D/AdapterServiceConfig( 5665): Adding HidService
D/AdapterServiceConfig( 5665): Adding HealthService
D/AdapterServiceConfig( 5665): Adding PanService
D/AdapterServiceConfig( 5665): Adding GattService
I/IntentController( 1224): receive(android.net.wifi.STATE_CHANGE,1,false)
W/Settings( 1848): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiTrafficPoller(  947): ENABLE_TRAFFIC_STATS_POLL false Token 15
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
V/BluetoothPbapReceiver( 5665): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
W/Settings( 4606): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/BluetoothPbapReceiver( 5665): ***********state = 10
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
D/PMS     (  947): acquireWL(30b56061): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 5434 1000 null
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
W/ContextImpl( 5434): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
E/BluetoothMasService( 5665): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
D/WISPrService( 5434): >>>>>WISPrService start isConnected = false<<<<<
D/PMS     (  947): releaseWL(30b56061): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
D/PMS     (  947): acquireWL(19658874): PARTIAL_WAKE_LOCK  StartingDockService 0x1 5434 1000 null
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
D/PMS     (  947): releaseWL(19658874): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
D/MdService( 5088): [f3d.] v648303190-6.1.860197 onStartCommand(dying) flag:0, id:26, failed(resend)
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
I/ActivityManager(  947): Killing 5273:com.htc.sense.news/u0a74 (adj 15): empty #17
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
D/WISPrService( 5434): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
D/HtcBtWidget_BTWidgetProvider( 5531): onBTStateChanged() for widget: 
D/HtcBtWidget_BTWidgetProvider( 5531): updateWidget(context) for widget: 
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.ja,va:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
D/BluetoothMasService( 5665): Add permission for SmsProvider.
D/DockEventReceiver( 5434): finishStartingService: stopping service
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
W/System.err(  947): java.lang.Throwable: sta,ck dump
D/BluetoothManagerService(  947): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  947): 	at java.lang.Thread.dumpStack(Thread.java:490)
D/BluetoothManagerService(  947): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ca6d1e3:true
W/System.err(  947): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  947): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  947): 	at android.os.Binder.execTransact(Binder.java:454)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
V/BluetoothMasService( 5665): Starting MAS instances
D/BluetoothAdapter( 5665): 218053915: getState() :  mService = null. Returning STATE_OFF
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
D/Process (  947): killProcessQuiet, pid=5273
D/Process (  947): com.android.server.am.ProcessRecord,.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
I/MailMessageReceiver( 5665): reg:com.android.bluetooth.btservice.AdapterApp@2b2d6eb8 with com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@14646491
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at c,om.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at andr,oid.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at and,roid.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeRecei,ver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_L,ink_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.,SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
I/QuickSettingWifi( 1224): receive.wifiState:WIFI_STATE_DISABLED setEnable:true
I/QuickSettingWifi( 1224): receive.wifiConnect:false wifiAPname:null elapse:1
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 5484): (3850) statement aborts at 19: [INSERT INTO smartsync_golden(date,Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,AutoSync_Turn_OnOff,time) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 5484): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle: 0x5589b15bf0
E/SQLiteDatabase( 5484): Error inserting ...
E/SQLiteDatabase( 5484): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
E/SQLiteDatabase( 5484): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:304)
E/SQLiteDatabase( 5484): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:245)
E/SQLiteDatabase( 5484): 	at android.content.ContentResolver.insert(ContentResolver.java:1228)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2098)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2128)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:27)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:436)
E/SQLiteDatabase( 5484): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:420)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5484): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5484): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5484): 	at java.lang.Thread.run(Thread.java:818)
D/PMS     (  947): releaseWL(2d891039): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/ActivityManager(  947): Recipient 5273
,I/MailManager( 5665): MailManager contruct! com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@14646491,
V/EmailUtils( 5665): Manager Instance is not NULL
,I/ActivityManager(  947): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=5714 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a
,D/HtcCupdReceiver(Provider)( 5689):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED
,D/MdScPhnSt( 5088): [d08.1.]  listen tmrbb8
,I/ActivityManager(  947): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5732 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/MdScDataSum( 5088): [d08.1.] summary 118:p1 ignore,
,D/Process (  947): killProcessQuiet, pid=5301,
I/ActivityManager(  947): Killing 5301:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,D/Settings:HtcWirelessFeatureFlags( 5434): id/is att sku: 118/false,
,I/ActivityManager(  947): Recipient 5301,
,E/Settings:HtcWrapHeaderInfo( 5434): no such activity!
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 5434): The wrap header doesn't exist in header list.,
,D/Process (  947): killProcessQuiet, pid=4864,
I/ActivityManager(  947): Killing 4864:com.google.android.gms.wearable/u0a24 (adj 15): empty #17,
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/Settings:HtcWrapHeaderInfo( 5434): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 5434): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5434): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5434): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5434): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5434): [supportHomeButton]hasNavigationBar:true,
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5434): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5434): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5434): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5434): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5434): [supportHomeButton]support         :false
,I/ActivityManager(  947): Recipient 4864
,D/Process (  947): killProcessQuiet, pid=5326
I/ActivityManager(  947): Killing 5326:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  947): Recipient 5326
,I/ActivityManager(  947): Waited long enough for: ServiceRecord{18bca512 u0 com.google.android.gms/.config.ConfigFetchService}
,D/Tethering(  947): interfaceRemoved wlan0
E/Tethering(  947): attempting to remove unknown iface (wlan0), ignoring
,D/HtcAdjCursorFactory( 5714): Set CursorWindow size to: 4194304 KB, Tid: 5738
,I/ActivityManager(  947): Cannot resolve ContentProvider=com.htc.vowifi
,E/ActivityThread( 5434): Failed to find provider info for com.htc.vowifi
E/Settings:HtcVoWifiWidgetEnabler( 5434): isSupportVoWifi: null,
,E/SQLiteDatabase( 5714): Failed to open database '/data/user/0/com.htc.android.mail/databases/mail.db'.
E/SQLiteDatabase( 5714): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5714): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5714): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5714): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5714): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5714): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185),
,E/SQLiteDatabase( 5714): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5714): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5714): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5714): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5714): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 5714): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5714): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5714): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5714): ,	at com.htc.android.mail.kq.a(MailProvider.java:5368)
E/SQLiteDatabase( 5714): 	at com.htc.android.mail.kq.a(MailProvider.java:5433)
E/SQLiteDatabase( 5714): 	at com.htc.android.mail.MailProvider.query(MailProvider.java:2114)
E/SQLiteDatabase( 5714): 	,at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 5714): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 5714): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
E/SQLiteDatabase( 5714): 	at android.os.Binder.execTransact(Binder.java:454)
E/SQLiteOpenHelper( 5714): Couldn't open mail.db for writing (will try read-only):
E/SQLiteOpenHelper( 5714): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5714): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5714): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteOpenHelper( 5714): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteOpenHelper( 5714): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5714): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5714): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5714): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteOpenHelper( 5714): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteOpenHelper( 5714): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteOpenHelper( 5714): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteOpenHelper( 5714): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 5714): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5714): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5714): 	at com.htc.android.mail.kq.a(MailProvider.java:5368)
E/SQLiteOpenHelper( 5714): 	at com.htc.android.mail.kq.a(MailProvider.java:5433)
E/SQLiteOpenHelper( 5714): 	at com.htc.android.mail.MailProvider.query(MailProvider.java:2114)
E/SQLiteOpenHelper( 5714): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteOpenHelper( 5714): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteOpenHelper( 5714): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
E/SQLiteOpenHelper( 5714): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 5434): The wrap header doesn't exist in header list.,
E/Settings:HtcWrapHeaderInfo( 5434): updateDevelopment, bPrefShow = true,
W/SQLiteOpenHelper( 5714): Opened mail.db in read-only mode
E/Settings:HtcUmcWidgetEnabler( 5434): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5434): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5434): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5434): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5434): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5434): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5434): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5434): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5434): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5434): [supportHomeButton]support         :false
,I/ActivityManager(  947): Cannot resolve ContentProvider=com.htc.vowifi
E/Settings:HtcVoWifiWidgetEnabler( 5434): isSupportVoWifi: null
,E/ActivityThread( 5434): Failed to find provider info for com.htc.vowifi
,I/PackageManager(  947):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=5732, uid=10072, userID:0
,W/global  ( 5732): [apache-http] Connection GC has been deprecated!,
,D/EmailUtils( 5665): ============NULL aList========
V/EmailUtils( 5665): <-getEmailAccountIdList,
V/BluetoothMasService( 5665): onCreate: mIsEmailEnabled: true
I/ActivityManager(  947): Killing 4606:com.google.android.talk/u0a112 (adj 15): empty #17
D/Process (  947): killProcessQuiet, pid=4606
D/Process (  947): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/Finsky  ( 5732): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
W/global  ( 5732): [apache-http] Connection GC has been deprecated!
,I/Prism.ItemManager( 1506): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1506): loadItems() com.htc.launcher.pageview.WidgetManager@1719c12a +,
I/Prism.WidgetManager( 1506): onLoadItems() +
D/Tethering(  947): interfaceLinkStateChanged p2p0, false
D/Tethering(  947): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  947): WiFiDisplay: getWifidisplayApEnabled=false
,W/global  ( 5732): [apache-http] Connection GC has been deprecated!,
,D/Tethering(  947): interfaceRemoved p2p0
,I/ActivityManager(  947): Recipient 4606
E/Tethering(  947): attempting to remove unknown iface (p2p0), ignoring
,E/RollingFileStream( 5732): Could not create a temp file with prefix: "eventlog.store" and suffix: ".log" in dir: "/data/data/com.android.vending/cache/logs/com.google.thalitester%40gmail.com".,
,D/Finsky  ( 5732): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.,
,D/BluetoothMasReceiver( 5665): Bluetooth STATE CHANGED to 10,
V/BluetoothMasService( 5665): onDestroy: mIsEmailEnabled: true
,V/BluetoothSapReceiver( 5665): SapReceiver onReceive 
V/BluetoothSapReceiver( 5665): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 5665):  Bluetooth Adapter state = 10
V/BluetoothSapReceiver( 5665): startService = false

```
