#### Test 58380500c26a9ef_thali06_HTC-HTC One M8s Logs


```
--------- beginning of system,
D/PMS     (  951): acquireWL(1a824623): PARTIAL_WAKE_LOCK  *alarm* 0x1 951 1000 WorkSource{10072}
V/AlarmManager(  951): sending alarm PendingIntent{1ce8b720: PendingIntentRecord{39a1e8d9 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454983629488, Int=0
V/AlarmManager(  951): sending alarm PendingIntent{fb8729e: PendingIntentRecord{28a9217f com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1454983631363, Int=536832000
V/AlarmManager(  951): sending alarm PendingIntent{135beac: PendingIntentRecord{902c775 android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1454983621600, Int=20000
--------- beginning of main
V/CheckinService( 4506): unknown intent received for checkin (Intent { flg=0x14 cmp=com.google.android.gms/.checkin.CheckinService$Receiver (has extras) })
E/WifiDataStallTracker(  951): DATA_MONITOR_POLL true Token 1
D/WifiDataStallTracker(  951): updateDataStallInfo: mDataStallTxRxSum={txSum=136 rxSum=118} preTxRxSum={txSum=136 rxSum=118}
D/WifiDataStallTracker(  951): updateDataStallInfo: NONE
D/WifiDataStallTracker(  951): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
D/PMS     (  951): acquireWL(3f72254c): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4506 10024 WorkSource{10024 com.google.android.gms}
E/WifiStateMachine(  951): WiFiStateMachine SCAN ALARM
D/WifiDisplayAdapter(  951): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  951):     Client/Owner: Client
D/WifiDisplayAdapter(  951):     GroupId: 
D/WifiDisplayAdapter(  951):     Passphrase: 
D/WifiDisplayAdapter(  951):     SessionId: 0
D/WifiDisplayAdapter(  951):     IP Address: }
E/WifiStateMachine(  951): handleMessage: E msg.what=131143
D/PMS     (  951): releaseWL(1a824623): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  951): processMsg: ConnectedState
E/WifiStateMachine(  951):  ConnectedState !CMD_START_SCAN -2 -2 ic=4 proc(ms):1 dur:416 rssi=-66 f=2412 sc=60 link=57 tx=0.4, 0.0, 0.0  rx=1.3 list=2412 [on:0 tx:0 rx:0 period:2166] from screen [on:0 period:-1010281946]
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=4 proc(ms):1 dur:416 rssi=-66 f=2412 sc=60 link=57 tx=0.4, 0.0, 0.0  rx=1.3 list=2412 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1010281945]
E/WifiStateMachine(  951): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.42 rxSuccessRate=1.31 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-66
E/WifiStateMachine(  951): WifiStateMachine CMD_START_SCAN with age=61510 interval=60000 maxinterval=300000
E/WifiStateMachine(  951): WifiStateMachine CMD_START_SCAN try full band scan age=61510 interval=60000 maxinterval=300000
E/WifiStateMachine(  951): WifiStateMachine CMD_START_SCAN full=true
E/WifiStateMachine(  951): WifiStateMachine CMD_START_SCAN bump interval =90000
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
D/wpa_supplicant( 1354): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 1354): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1354): wpa_supplicant_scan enter
D/wpa_supplicant( 1354): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1354): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1354): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1354): WPS:  * Request Type
D/wpa_supplicant( 1354): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1354): WPS:  * UUID-E
D/wpa_supplicant( 1354): WPS:  * Primary Device Type
D/wpa_supplicant( 1354): WPS:  * RF Bands (3)
D/wpa_supplicant( 1354): WPS:  * Association State
D/wpa_supplicant( 1354): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1354): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1354): WPS:  * Manufacturer
D/wpa_supplicant( 1354): WPS:  * Model Name
D/wpa_supplicant( 1354): WPS:  * Model Number
D/wpa_supplicant( 1354): WPS:  * Device Name
D/wpa_supplicant( 1354): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1354): P2P: * P2P IE header
D/wpa_supplicant( 1354): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1354): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 1354): wlan0: Add radio work 'scan'@0x55b5fe3680
D/wpa_supplicant( 1354): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1354): wlan0: Starting radio work 'scan'@0x55b5fe3680 after 0.000043 second wait
D/wpa_supplicant( 1354): wlan0: nl80211: scan request
D/wpa_supplicant( 1354): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1354): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1354): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1354): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1354): wlan0: Own scan request started a scan in 0.000083 seconds
I/wpa_supplicant( 1354): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  951): [1,454,983,631,401 ms] noteScanstart no scan source
E/WifiStateMachine(  951): handleMessage: X
D/WifiMonitor(  951): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  951): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  951): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
D/PMS     (  951): acquireWL(36351aaa): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4506 10024 WorkSource{10024 com.google.android.gms}
E/WifiMonitor(  951): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/PMS     (  951): releaseWL(3f72254c): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
I/CheckinService( 4506): Checking schedule, now: 1454983631423 next: 1454983631363
I/CheckinService( 4506): active receiver: enabled
I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=4506, uid=10024, userID:0
I/CheckinService( 4506): Preparing to send checkin request
I/EventLogService( 4506): Accumulating logs since 1454983595287
I/CheckinRequestBuilder( 4506): Checkin reason type: 11 attempt count: 1
I/ActivityManager(  951): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4506): Failed to find provider info for com.google.android.wearable.settings
E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  951):  packet count Tx=154 Rx=199
I/art     (  951): Explicit concurrent mark sweep GC freed 37092(2MB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 16MB/25MB, paused 1.899ms total 161.940ms
E/cutils-trace( 6423): Error opening trace file: Permission denied (13)
D/Finsky  ( 6055): [612] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 6055): [1] 5.onFinished: Installation state replication succeeded.
I/GLSUser ( 1854): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1854): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1854): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1854): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1854): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/CustomizationManager( 6423): ====startRecUseTime====
D/htc.customization.log.level( 6423):  is 
W/CustomizationLogLevel( 6423): Level value is invalid, use default level 2
W/CheckinRequestBuilder( 4506): awaiting user notification for token
D/DotMatrix( 1350): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1350): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1244): reapply : com.google.android.gms 2 40
I/ActivityManager(  951): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6439 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
D/CustomizationManager( 6423):  Read ACC file spent 0.051 (s)
D/CIDMapFileReader( 6423): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6423): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6423): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6423): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6423): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6423): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6423): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6423): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6423): Parsing tag category name = system
I/CustomizationCIDLoader( 6423): Parsing tag category name = application
I/CustomizationCIDLoader( 6423): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6423): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6423): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6423): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6423): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6423): add string-array item, value = 42507
I/CustomizationCIDLoader( 6423): add string-array item, value = 21902
I/CustomizationCIDLoader( 6423): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6423): add string-array item, value = 23420
I/CustomizationCIDLoader( 6423): add string-array item, value = 22299
I/CustomizationCIDLoader( 6423): add string-array item, value = 24002
I/CustomizationCIDLoader( 6423): add string-array item, value = 23210
I/CustomizationCIDLoader( 6423): add string-array item, value = 23205
W/ResourcesManager( 6439): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
I/CustomizationCIDLoader( 6423): add string-array item, value = 23806
W/ResourcesManager( 6439): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/CustomizationCIDLoader( 6423): add string-array item, value = 23430
I/CustomizationCIDLoader( 6423): add string-array item, value = 23408
I/CustomizationCIDLoader( 6423): add string-array item, value = 27205
I/CustomizationCIDLoader( 6423): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6423): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6423): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6423): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6423): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6423): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6423): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6423): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6423): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6423): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6423): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6423): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6423):  Read CID file spent 0.109 (s)
D/CustomizationManager( 6423):  All configurations done spent 0.109 (s)
I/MultiDex( 6439): VM with version 2.1.0 has multidex support
I/MultiDex( 6439): install
I/MultiDex( 6439): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 6439): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/ActivityManager(  951): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6423 on display 0
D/PMS     (  951): acquireHCC(b21825a): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 951 1000 null
D/PMS     (  951): acquireHCC(1e981c8b): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 951 1000 null
W/asset   (  951): Copying FileAsset 0x5590a3aab0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/PMS     (  951): acquireWL(2d656a26): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 951 1000 null
I/FeedHostManager( 1639): [onPause]
I/FeedProviderManager( 1639): onPause
I/FeedHostManager( 1639): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@35e39494
I/SocialFeedProvider( 1639): +onPause
I/SocialFeedProvider( 1639): -onPause
I/AnimationUtil(  951): isHTCRecent(ThaliTest/Recent screens.)/5
W/ActivityThread( 6439): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6439): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@d5887c2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6439): Installed default security provider GmsCore_OpenSSL
W/HtcSystemUPManager(  951): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  951): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6464 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/art     (  408): Explicit concurrent mark sweep GC freed 8668(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 235us total 19.138ms
I/art     (  408): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 290us total 15.851ms
I/art     (  408): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 293us total 18.968ms
D/GCM     ( 1854): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 1854): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 4506): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
W/asset   ( 6464): Copying FileAsset 0xac7cbe40 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/StatusBarManagerService(  951): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  951): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  951): hiding MENU key
D/WearableService( 5731): callingUid 10024, callindPid: 5731
E/MDM     ( 1925): [139] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/TrimMemoryManager( 1639): [trimMemory] 20
,E/WifiStateMachine(  951): handleMessage: E msg.what=131155
E/WifiStateMachine(  951): processMsg: ConnectedState
E/WifiStateMachine(  951):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-66 f=2412 sc=60 link=57 tx=0.4, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:830] from screen [on:0 period:-1010281112] gl hn u24 rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-66 f=2412 sc=60 link=57 tx=0.4, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1010281110] gl hn u24 rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  951):  get link layer stats 0
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1354): wlan0: Control interface command 'SIGNAL_POLL'
I/WebViewFactory( 6464): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
I/WVCdm   (  401): CdmEngine::OpenSession
I/WVCdm   (  401): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  401): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4506, uid=10024, userID:0
D/DrmWidevineDash(  401): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  401): Service_Initialize: starts!
D/QSEECOMAPI: (  401): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  401): App is not loaded in QSEE
E/QSEECOMAPI: (  401): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  401): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  401): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  401): App is not loaded in QSEE
D/LocationInitializer( 4506): Restart initialization of location
I/LibraryLoader( 6464): Time to load native libraries: 12 ms (timestamps 9201-9213)
I/LibraryLoader( 6464): Expected native library version number "",actual native library version number ""
D/QSEECOMAPI: (  401): Loaded image: APP id = 8
D/DrmWidevineDash(  401): Service_Initialize: ends! returns 0
D/QSAPPSVER(  401): qsapps_get_capabilities: Capability from secure side: 0x0
D/QSAPPSVER(  401): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  401): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4922000
E/DrmWidevineDash(  401): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4922000
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/DrmLibTime(  515): got the req here! ret=0
D/DrmLibTime(  515): command id, time_cmd_id = 770
D/DrmLibTime(  515): time_getutcsec starts!
D/DrmLibTime(  515): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  515): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  515): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  515): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  515): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  515): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  515): QSEE Time Listener: Retrieved Android system time: 1454983632
D/DrmLibTime(  515): time_getutcsec returns 0, sec = 1454983632; nsec = 0
D/DrmLibTime(  515): time_getutcsec finished! 
D/DrmLibTime(  515): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  515): before calling ioctl to read the next time_cmd
E/QC-time-services(  430): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): hlos api version =  9
D/DrmWidevineDash(  401): tz api version =  9
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  401): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
V/WebViewChromiumFactoryProvider( 6464): Binding Chromium to main looper Looper (main, tid 1) {80b2d81}
I/LibraryLoader( 6464): Expected native library version number "",actual native library version number ""
I/chromium( 6464): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  401): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  401): OEMCrypto_OpenSession: starts! SID=0xf4c4e928
D/DrmWidevineDash(  401): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  401): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_GetRandom: starts! randomData=0xaaf75500, dataLength=8
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xaaf78550, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
I/BrowserStartupController( 6464): Initializing chromium process, singleProcess=true
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  401): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  401): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  401): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  401): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  401): OEMCrypto_GetDeviceID: starts! deviceID=0xaaf5f688, idLength=0xff9ece88
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
W/art     ( 6464): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6464): ApplicationContext is null in ApplicationStatus
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_GetHDCPCapability: starts!, current = 0xff9ece9e, maximum = 0xff9ece9f
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): hlos api version =  9
D/DrmWidevineDash(  401): tz api version =  9
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  401): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xff9ecf0c
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  401): PrepareKeyRequest: nonce=673739252
D/DrmWidevineDash(  401): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab06a340
D/DrmWidevineDash(  401): message_length=1611, signature=0xab06a990, signature_length=0xff9ece6c
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  401): CdmEngine::CloseSession
D/DrmWidevineDash(  401): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  401): L3 Terminate.
D/DrmWidevineDash(  401): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): Service_Uninitialize: starts!
D/QSEECOMAPI: (  401): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  401): QSEECom_shutdown_app, app_id = 8
D/DrmWidevineDash(  401): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  401): OEMCrypto_Terminate: ends! returns 0
E/cutils-trace( 6495): Error opening trace file: Permission denied (13)
I/dex2oat ( 6495): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=36 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6495): dex2oat: override thread count:4
I/dex2oat ( 6495): dex2oat took 35.297ms (threads: 4)
I/Adreno-EGL( 6439): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6439): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6439): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6439): Local Branch: 
I/Adreno-EGL( 6439): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6439): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6439):                  d74aa161a12b9c6fc6332151
E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  951):  packet count Tx=154 Rx=199
I/Adreno-EGL( 6439): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6439): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6439): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6439): Local Branch: 
I/Adreno-EGL( 6439): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6439): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6439):                  d74aa161a12b9c6fc6332151
I/WVCdm   (  401): CdmEngine::OpenSession
I/WVCdm   (  401): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  401): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
D/DrmWidevineDash(  401): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  401): Service_Initialize: starts!
D/QSEECOMAPI: (  401): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  401): App is not loaded in QSEE
E/QSEECOMAPI: (  401): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  401): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  401): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  401): App is not loaded in QSEE
D/QSEECOMAPI: (  401): Loaded image: APP id = 9
D/DrmWidevineDash(  401): Service_Initialize: ends! returns 0
D/QSAPPSVER(  401): qsapps_get_capabilities: Capability from secure side: 0x0
D/QSAPPSVER(  401): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  401): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4922000
E/DrmWidevineDash(  401): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4922000
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/DrmLibTime(  515): got the req here! ret=0
D/DrmLibTime(  515): command id, time_cmd_id = 770
D/DrmLibTime(  515): time_getutcsec starts!
D/DrmLibTime(  515): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  515): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  515): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  515): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  515): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  515): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  515): QSEE Time Listener: Retrieved Android system time: 1454983632
D/DrmLibTime(  515): time_getutcsec returns 0, sec = 1454983632; nsec = 0
D/DrmLibTime(  515): time_getutcsec finished! 
D/DrmLibTime(  515): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  515): before calling ioctl to read the next time_cmd
E/QC-time-services(  430): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): hlos api version =  9
D/DrmWidevineDash(  401): tz api version =  9
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  401): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  401): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  401): OEMCrypto_OpenSession: starts! SID=0xf4c4e928
D/DrmWidevineDash(  401): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  401): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_GetRandom: starts! randomData=0xaaff6900, dataLength=8
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xaaf78550, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  401): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  401): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  401): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  401): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  401): OEMCrypto_GetDeviceID: starts! deviceID=0xaaf5f6a8, idLength=0xf4b4e6f8
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_GetHDCPCapability: starts!, current = 0xf4b4e70e, maximum = 0xf4b4e70f
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): hlos api version =  9
D/DrmWidevineDash(  401): tz api version =  9
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  401): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf4b4e77c
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  401): PrepareKeyRequest: nonce=547562555
D/DrmWidevineDash(  401): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab06a340
D/DrmWidevineDash(  401): message_length=1646, signature=0xab06a9b8, signature_length=0xf4b4e6dc
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  401): CdmEngine::CloseSession
D/DrmWidevineDash(  401): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  401): L3 Terminate.
D/DrmWidevineDash(  401): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): Service_Uninitialize: starts!
D/QSEECOMAPI: (  401): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  401): QSEECom_shutdown_app, app_id = 9
D/DrmWidevineDash(  401): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  401): OEMCrypto_Terminate: ends! returns 0
W/ContextImpl(  951): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
I/wpa_supplicant( 1354): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative RSSI = -65 abnormalRssiCnt = 0 newLinkSpeed = 65
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative rssi=-65 linkspeed=65
E/WifiConfigStore(  951): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-65 "NG700"WPA_PSK
E/WifiStateMachine(  951): calculateWifiScore freq=2412 speed=65 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.21 txretriesrate=0.00 rxrate=0.66 userTriggerdPenalty0
E/WifiStateMachine(  951):  good link -> stuck count =0
E/WifiStateMachine(  951):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  951):  isHighRSSI       ---> score=61
D/WIFI_ICON( 1244): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  951): handleMessage: X
D/StatusBar.NetworkController( 1244): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WifiWatchdogStateMachine(  951): RSSI current: 3 new: -65, 3
W/chromium( 6464): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6464): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6464): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6464): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6464): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6464): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6464): Local Branch: 
I/Adreno-EGL( 6464): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6464): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6464):                  d74aa161a12b9c6fc6332151
I/CheckinRequestBuilder( 4506): Classify the device as Phone.
D/libc    ( 4506): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4506): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4506): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 4506): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4506): [NET] android_getaddrinfo_proxy+
D/libc    ( 4506): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4506): [NET] android_getaddrinfo_proxy-, success
D/BluetoothManagerService(  951): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  951): java.lang.Throwable: stack dump
W/System.err(  951): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  951): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  951): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  951): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  951): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3635fcae:true
D/BluetoothAdapter( 6464): 700195005: getState(). Returning 12
W/art     ( 6464): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6464): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6464): CordovaWebView is running on device made by: HTC
W/art     ( 6464): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6464): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6464): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/FindExtension( 6464): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/InputMethodManager( 6464): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@11313062, mServedView=org.apache.cordova.engine.SystemWebView{1c7ba5f3 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@1a27e2b0
I/InputMethodManagerService(  951): Disable input method client, pid=1639
D/StatusBarManagerService(  951): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  951): Enable input method client, pid=6464
D/PMS     (  951): releaseWL(2d656a26): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/ActivityManager(  951): Displayed com.test.thalitest/.MainActivity: +1s431ms
I/PhoneStatusBar( 1244): setImeWindowStatus(false,false)
D/wpa_supplicant( 1354): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1354): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1354): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1354): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1354): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1354): wlan0: Scan completed in 2.050280 seconds
D/wpa_supplicant( 1354): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1354): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1354): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1354): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1354): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-55
I/wpa_supplicant( 1354): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-65
I/wpa_supplicant( 1354): [NULL] a0:c5:62:7a:49:97 freq=5260 level=-83
I/wpa_supplicant( 1354): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
D/wpa_supplicant( 1354): wlan0: BSS: Start scan result update 5
D/wpa_supplicant( 1354): BSS: last_scan_res_used=4/32
D/wpa_supplicant( 1354): wlan0: Scan-only results received
D/wpa_supplicant( 1354): wlan0: Radio work 'scan'@0x55b5fe3680 done in 2.051103 seconds
E/WifiMonitor(  951): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  951): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  951): handleMessage: E msg.what=147461
E/WifiStateMachine(  951): processMsg: ConnectedState
E/WifiStateMachine(  951):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  951): processMsg: ConnectModeState
E/WifiStateMachine(  951):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  951): processMsg: DriverStartedState
E/WifiStateMachine(  951):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  951): processMsg: SupplicantStartedState
E/WifiStateMachine(  951):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
D/WifiStateMachine(  951): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1354): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  951): [1,454,983,633,455 ms] noteScanEnd no scan source
W/ContextImpl(  951): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1354): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  951): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@3c087032 sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  951): NG7005g c0:ff:d4:d3:aa:4a rssi=-55 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  951): NG700 c0:ff:d4:d3:aa:48 rssi=-65 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  951): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  951): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  951):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-65 freq=2412
E/WifiAutoJoinController (  951): UPC503894600 a0:c5:62:7a:49:97 rssi=-83 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  951): Gonzos 38:f8:89:11:e9:11 rssi=-81 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  951): ageScanResultsOut delay 40000 size 4 now 1454983633457
E/WifiAutoJoinController (  951): newSupplicantResults size=4 known=1 true
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1354): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  951): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
E/WifiAutoJoinController (  951): ssid=NG700
E/WifiAutoJoinController (  951): id=0
E/WifiAutoJoinController (  951): mode=station
E/WifiAutoJoinController (  951): pairwise_cipher=CCMP
E/WifiAutoJoinController (  951): group_cipher=CCMP
E/WifiAutoJoinController (  951): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  951): wpa_state=COMPLETED
E/WifiAutoJoinController (  951): ip_address=192.168.1.130
E/WifiAutoJoinController (  951): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  951): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  951): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  951): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController (  951): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-65,-127) num=(1,0)
E/WifiAutoJoinController (  951): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  951): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-65 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  951): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  951): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  951): Done attemptAutoJoin status=0
E/WifiConfigStore(  951):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  951): handleMessage: X
D/WifiManager( 1925): getScanResults: Base Package Name=com.google.android.gms, uid=10024
D/libc    ( 4506): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4506): [NET] android_getaddrinfofornet-, err=8
W/XT9_C   ( 1426): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1426): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1426): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1426): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/BindingManager( 6464): Cannot call determinedVisibility() - never saw a connection for the pid: 6464
D/libc    ( 4506): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4506): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4506): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4506): [NET] android_getaddrinfofornet-, err=8
I/CheckinTask( 4506): Sending checkin request (8410 bytes)
D/JsMessageQueue( 6464): Set native->JS mode to OnlineEventsBridgeMode
E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  951):  packet count Tx=169 Rx=209
E/WifiTrafficPoller(  951): notifying of data activity 3
D/WIFI_ICON( 1244): WifiActivity: 3
D/StatusBar.NetworkController( 1244): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/jxcore_app_log( 6464): JniHelper::setJavaVM(0xab65f8f8), pthread_self() = -1399360920
I/chromium( 6464): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/HtcModeClient( 3296): handler message = 4011
,E/HtcModeClient( 3296): Check connection and retry 12 times.
,D/PMS     (  951): releaseHCC(b21825a): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     (  951): releaseHCC(1e981c8b): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,I/CheckinRequestBuilder( 4506): Checkin reason type: 11 attempt count: 1
,I/ActivityManager(  951): Cannot resolve ContentProvider=com.google.android.wearable.settings
,E/ActivityThread( 4506): Failed to find provider info for com.google.android.wearable.settings
,I/GLSUser ( 1854): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1854): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1854): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1854): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1854): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/CheckinRequestBuilder( 4506): awaiting user notification for token
,D/DotMatrix( 1350): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1350): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1244): reapply : com.google.android.gms 2 40
,I/CheckinRequestBuilder( 4506): Classify the device as Phone.
,I/CheckinTask( 4506): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4506): Checking schedule, now: 1454983634299 next: 1455520466284
I/CheckinService( 4506): active receiver: disabled,
I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4506, uid=10024, userID:0
,D/PMS     (  951): releaseWL(36351aaa): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms},
,I/ActivityManager(  951): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6539 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a
,D/PhoneMonitor( 6539): Register our PhoneStateListener
,V/SetupWizard( 6539): Connected to Gservices successfully,
,D/ChimeraCfgMgr( 4506): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 4506): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
,D/PhoneMonitor( 6539): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,D/PhoneMonitor( 6539): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,D/GCM     ( 1854): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  951):  packet count Tx=171 Rx=213,
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  951):  packet count Tx=171 Rx=213
D/WIFI_ICON( 1244): WifiActivity: 0
E/WifiTrafficPoller(  951): notifying of data activity 0
D/StatusBar.NetworkController( 1244): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,W/jxcore-log( 6464): Initializing JXcore engine,
W/jxcore-log( 6464): JXcore engine is ready
,W/jxcore-log( 6464): Starting JXcore engine,
,W/jxcore-log( 6464): Platform android,
W/jxcore-log( 6464): 
W/jxcore-log( 6464): Process ARCH arm
W/jxcore-log( 6464): 
,E/WifiStateMachine(  951): handleMessage: E msg.what=131155,
E/WifiStateMachine(  951): processMsg: ConnectedState
E/WifiStateMachine(  951):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.2, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1010277304] gl hn u24 rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.2, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1010277303] gl hn u24 rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  951):  get link layer stats 0
,W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1354): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1354): environment dirty rate=5 [17][1][0],
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative RSSI = -65 abnormalRssiCnt = 0 newLinkSpeed = 65,
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative rssi=-65 linkspeed=65
E/WifiConfigStore(  951): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-65 "NG700"WPA_PSK
E/WifiStateMachine(  951): calculateWifiScore freq=2412 speed=65 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=8.60 txretriesrate=0.00 rxrate=7.33 userTriggerdPenalty0
E/WifiStateMachine(  951):  good link -> stuck count =0,
E/WifiStateMachine(  951):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  951):  isHighRSSI       ---> score=65
E/WifiStateMachine(  951): handleMessage: X
,D/WifiWatchdogStateMachine(  951): RSSI current: 3 new: -65, 3
D/WIFI_ICON( 1244): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1244): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/jxcore-log( 6464): JXcore Cordova bridge is ready!,
I/jxcore-log( 6464): 
W/jxcore-log( 6464): JXcore engine is started
,E/WifiDataStallTracker(  951): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  951): updateDataStallInfo: mDataStallTxRxSum={txSum=153 rxSum=131} preTxRxSum={txSum=136 rxSum=118}
D/WifiDataStallTracker(  951): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  951): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/jxcore  ( 6464): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
E/jxcore  ( 6464): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6464): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37),
,D/PMS     (  951): acquireWL(adcff41): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 951 1000 null
,W/PluginManager( 6464): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 65ms. Plugin should use CordovaInterface.getThreadPool().
W/HtcSystemUPManager(  951): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,I/FeedHostManager( 1639): [onResume],
I/FeedProviderManager( 1639): onResume
I/SocialFeedProvider( 1639): +onResume
I/SocialFeedProvider( 1639): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1639): -onResume
,D/FindExtension( 1639): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
D/StatusBarManagerService(  951): setSystemUiVisibility(0x700)
I/ThreadedRenderer( 1639): Defer allocateBuffers to drawing time
D/StatusBarManagerService(  951): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  951): hiding MENU key
,I/PhoneStatusBar( 1244): setImeWindowStatus(false,false)
I/InputMethodManagerService(  951): Disable input method client, pid=6464
D/StatusBarManagerService(  951): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  951): Enable input method client, pid=1639
,W/IInputConnectionWrapper( 6464): reportFullscreenMode on inactive InputConnection
,D/PMS     (  951): releaseWL(adcff41): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null,
,D/StatusBarManagerService(  951): setSystemUiVisibility(0xc0000700),
D/StatusBarManagerService(  951): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  951): hiding MENU key
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  951):  packet count Tx=171 Rx=213
,W/BindingManager( 6464): Cannot call determinedVisibility() - never saw a connection for the pid: 6464
,W/OpenGLRenderer( 1639): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,D/Process (  951): killProcessQuiet, pid=5893
I/ActivityManager(  951): Killing 5893:com.google.android.gm/u0a106 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  951): Recipient 5893
,D/Process (  951): killProcessQuiet, pid=5852
I/ActivityManager(  951): Killing 5852:com.google.android.talk/u0a112 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  951): Recipient 5852
,D/Process (  951): killProcessQuiet, pid=5939
I/ActivityManager(  951): Killing 5939:com.htc.calendar/u0a10 (adj 15): empty #18
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  951): Recipient 5939
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 6
,E/WifiTrafficPoller(  951):  packet count Tx=173 Rx=215
D/WIFI_ICON( 1244): WifiActivity: 3
E/WifiTrafficPoller(  951): notifying of data activity 3
D/StatusBar.NetworkController( 1244): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 6
,D/WIFI_ICON( 1244): WifiActivity: 0
E/WifiTrafficPoller(  951):  packet count Tx=173 Rx=215
D/StatusBar.NetworkController( 1244): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  951): notifying of data activity 0
,I/HtcModeClient( 3296): handler message = 4011,
,E/HtcModeClient( 3296): Check connection and retry 12 times. Stop service and kill this process.,
,D/HtcModeClient( 3296): Don't start project servcice
,D/HtcModeClient( 3296): setEject: MEDIA_EJECT_STATE = true,
,D/HtcModeClient( 3296): connectState: CONNECTION_READY = false
D/SilentMusic( 3296): call stop,
D/HtcModeClient( 3296): close connection
,W/HtcModeClient( 3296): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 3296): read the terminate packet, so break
,D/Process (  951): killProcessQuiet, pid=3296
I/ActivityManager(  951): Killing 3296:com.htc.autobot/u0a47 (adj 15): empty #17
,D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  951): Recipient 3296
,E/WifiStateMachine(  951): handleMessage: E msg.what=131155
E/WifiStateMachine(  951): processMsg: ConnectedState
E/WifiStateMachine(  951):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=8.6, 0.0, 0.0  rx=7.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1010274287] gl hn u24 rssi=-60 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=8.6, 0.0, 0.0  rx=7.3 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1010274286] gl hn u24 rssi=-60 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  951):  get link layer stats 0
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1354): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1354): environment dirty rate=0 [2][0][0]
,E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative RSSI = -65 abnormalRssiCnt = 0 newLinkSpeed = 65
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative rssi=-65 linkspeed=65
E/WifiConfigStore(  951): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-65 "NG700"WPA_PSK
,E/WifiStateMachine(  951): calculateWifiScore freq=2412 speed=65 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=5.30 txretriesrate=0.00 rxrate=4.66 userTriggerdPenalty0
D/WIFI_ICON( 1244): updateWifiState: RSSI_CHANGED 3 -> 3
,E/WifiStateMachine(  951):  good link -> stuck count =0
D/StatusBar.NetworkController( 1244): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  951):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  951):  isHighRSSI       ---> score=65
E/WifiStateMachine(  951): handleMessage: X
D/WifiWatchdogStateMachine(  951): RSSI current: 3 new: -65, 3
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  951):  packet count Tx=173 Rx=215
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/WIFI_ICON( 1244): WifiActivity: 1
E/WifiTrafficPoller(  951):  packet count Tx=173 Rx=216,
D/StatusBar.NetworkController( 1244): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  951): notifying of data activity 1
,I/ActivityManager(  951): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=6565 uid=10076 gids={50076, 9997} abi=arm64-v8a
D/PMS     (  951): acquireWL(30f4ef1f): PARTIAL_WAKE_LOCK  *alarm* 0x1 951 1000 WorkSource{10076}
V/AlarmManager(  951): sending alarm PendingIntent{a1f726c: PendingIntentRecord{fc8d035 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454983640944, Int=60000
D/PMS     (  951): releaseWL(30f4ef1f): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,D/SMSBackup( 6565): SMSBackupAgentService started,
D/SMSBackup( 6565): Checking restore status
,D/SMSBackup( 6565): Restore complete,
D/SMSBackup( 6565): cancelCheckAlarm,
,D/SMSBackup( 6565): SMSBackupAgentService completed: completed in 0.0 seconds,
,D/Process (  951): killProcessQuiet, pid=6004,
I/ActivityManager(  951): Killing 6004:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  951): Recipient 6004
,E/WifiDataStallTracker(  951): DATA_MONITOR_POLL true Token 1
,D/WifiDataStallTracker(  951): updateDataStallInfo: mDataStallTxRxSum={txSum=155 rxSum=132} preTxRxSum={txSum=153 rxSum=131}
D/WifiDataStallTracker(  951): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  951): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,I/Prism.ItemManager( 1639): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1639): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/Prism.AllAppsManager( 1639): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
W/SystemReader(  951): Cannot find grip_rejection_width, use default value instead
D/AccTypeManager( 1783): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,W/ResourcesManager(  951): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/ActivityManager(  951): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6588 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/AccTypeManager( 1783): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/AccTypeManager( 1783): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/PhoneApp( 1580): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,E/ExternalAccountType( 1783): Unsupported attribute readOnly
,D/PMS     (  951): acquireWL(10dbd0d2): PARTIAL_WAKE_LOCK  *alarm* 0x1 951 1000 WorkSource{1000}
V/AlarmManager(  951): sending alarm PendingIntent{135beac: PendingIntentRecord{902c775 android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1454983641600, Int=20000
,W/ResourcesManager( 6588): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/PackageManager(  951): Unable to load service info ResolveInfo{166fe591 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
W/PackageManager(  951): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  951): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  951): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  951): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  951): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  951): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  951): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  951): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  951): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  951): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  951): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  951): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  951): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  951): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  951): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  951): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,V/GmsNetworkLocationProvi( 1925): DISABLE
,I/GCoreNlp( 1925): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/BackupManagerService(  951): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/WIFI_ICON( 1244): WifiActivity: 0
E/WifiTrafficPoller(  951):  packet count Tx=173 Rx=216
E/WifiTrafficPoller(  951): notifying of data activity 0
D/StatusBar.NetworkController( 1244): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/LocationProviderProxy(  951): applying state to connected service
,D/PMS     (  951): acquireWL(29664ef2): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1925 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  951): releaseWL(29664ef2): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/LocationProviderProxy(  951): applying state to connected service,
,D/PMS     (  951): acquireWL(126f8631): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1925 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): acquireWL(1c570484): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1925 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): releaseWL(126f8631): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  951): releaseWL(1c570484): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): acquireWL(1685546d): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1925 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): releaseWL(1685546d): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,I/Babel_SMS( 6588): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6588): MmsConfig.loadMmsSettings
,I/art     (  951): Explicit concurrent mark sweep GC freed 31264(1707KB) AllocSpace objects, 5(228KB) LOS objects, 33% free, 18MB/28MB, paused 1.898ms total 150.344ms,
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=6588, uid=10112, userID:0
,I/ActivityManager(  951): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=6618 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,W/Settings( 6588): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6588): startup - clean
,W/HtcWrapAdjustableCursorFactory( 6618): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.
,D/MessageFrequencyProvider( 6618): onCreate,
,D/MmsCustomizationProvider( 6618): query uri: content://htc-mms-customization/mms-ua/ua_string,
V/GetPrviateResource( 6618): GetPrviateResource
V/GetPrviateResource( 6618): GetPrviateResource
,I/Babel   ( 6588): deleted: false for 0
,D/MmsCustomizationProvider( 6618): query uri: content://htc-mms-customization/mms-ua/ua_profile
,D/MessageCustFlag( 6618): sense_version=6.0
D/BTAccessoryUtil( 6618): createReceiver
,D/BTAccessoryUtil( 6618): registerReceiver return intent = null,
,I/Babel_SMS( 6588): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
I/Babel_SMS( 6588): MmsConfig.loadFromDatabase
D/MessageCustFlag( 6618): sku_id=118
,D/HtcBuildUtils( 6618): getRATByHtcTelephonyCapability:1,
W/SystemReader( 6618): Cannot find qct_8960_interface, use default value instead
,E/Babel_SMS( 6588): canonicalizeMccMnc: invalid mccmnc ,
I/Babel_SMS( 6588): MmsConfig.loadFromResources
E/Babel_SMS( 6588): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6588): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=6588, uid=10112, userID:0
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=6588, uid=10112, userID:0,
,I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=6588, uid=10112, userID:0,
I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=6588, uid=10112, userID:0
I/PackageManager(  951):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=6588, uid=10112, userID:0
D/PMS     (  951): acquireWL(fbc5787): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 6588 10112 null
E/WifiStateMachine(  951): handleMessage: E msg.what=131155
E/WifiStateMachine(  951): processMsg: ConnectedState
E/WifiStateMachine(  951):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=5.3, 0.0, 0.0  rx=4.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1010271266] gl hn u24 rssi=-60 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=5.3, 0.0, 0.0  rx=4.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1010271265] gl hn u24 rssi=-60 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  951):  get link layer stats 0
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1354): wlan0: Control interface command 'SIGNAL_POLL'
W/VideoCapabilities( 6588): Unrecognized profile 2130706433 for video/avc
I/wpa_supplicant( 1354): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative RSSI = -66 abnormalRssiCnt = 0 newLinkSpeed = 57
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative rssi=-66 linkspeed=57
E/WifiConfigStore(  951): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-65 "NG700"WPA_PSK
E/WifiStateMachine(  951): calculateWifiScore freq=2412 speed=57 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=2.65 txretriesrate=0.00 rxrate=2.83 userTriggerdPenalty0
E/WifiStateMachine(  951):  good link -> stuck count =0
E/WifiStateMachine(  951):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  951):  isHighRSSI       ---> score=61
D/WifiWatchdogStateMachine(  951): RSSI current: 3 new: -66, 3
E/WifiStateMachine(  951): handleMessage: X
D/WIFI_ICON( 1244): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1244): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/[PluginManager]RegisterService( 1562): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1562): handle notify Blinkfeed plugin client changed
,D/PackageBroadcastService( 4506): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms,
,I/PackageBroadcastService( 4506): Null package name or gms related package.  Ignoreing.
,D/PMS     (  951): acquireWL(39aedd9e): PARTIAL_WAKE_LOCK  Icing 0x1 4506 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  951): acquireWL(1d2eb07f): PARTIAL_WAKE_LOCK  AsyncService 0x1 6125 10167 null
D/PMS     (  951): releaseWL(1d2eb07f): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/Icing   ( 4506): updateResources: need to parse f{com.google.android.gms}
D/PMS     (  951): acquireWL(108ce095): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6125 10167 null
,D/PMS     (  951): releaseWL(108ce095): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,I/UpdateIcingCorporaServi( 5970): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
E/WifiStateMachine(  951): WiFiStateMachine SCAN ALARM
D/WifiDisplayAdapter(  951): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  951):     Client/Owner: Client
D/WifiDisplayAdapter(  951):     GroupId: 
D/WifiDisplayAdapter(  951):     Passphrase: 
D/WifiDisplayAdapter(  951):     SessionId: 0
D/WifiDisplayAdapter(  951):     IP Address: }
,E/WifiStateMachine(  951): handleMessage: E msg.what=131143
E/WifiStateMachine(  951): processMsg: ConnectedState
W/VideoCapabilities( 6588): Unsupported mime video/x-ms-wmv
E/WifiStateMachine(  951):  ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):0 dur:2054 rssi=-66 f=2412 sc=60 link=57 tx=2.7, 0.0, 0.0  rx=2.8 fiv=90000 [on:0 tx:0 rx:0 period:50] from screen [on:0 period:-1010271197]
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):1 dur:2054 rssi=-66 f=2412 sc=60 link=57 tx=2.7, 0.0, 0.0  rx=2.8 fiv=90000 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1010271196]
E/WifiStateMachine(  951): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=2.65 rxSuccessRate=2.83 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-66
E/WifiStateMachine(  951): WifiStateMachine CMD_START_SCAN with age=10749 interval=90000 maxinterval=300000
E/WifiStateMachine(  951): WifiStateMachine CMD_START_SCAN full=false
E/WifiConfigStore(  951): makeChannelList age=3600000 for "NG700"WPA_PSK max=6 bssids=1
E/WifiConfigStore(  951): has c0:ff:d4:d3:aa:48 freq=2412 age=55 ?=true
E/WifiStateMachine(  951): WifiStateMachine starting scan for "NG700"WPA_PSK with 2412
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY freq=2412"
D/wpa_supplicant( 1354): wlan0: Control interface command 'SCAN TYPE=ONLY freq=2412'
D/wpa_supplicant( 1354): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1354): wpa_supplicant_scan enter
D/wpa_supplicant( 1354): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1354): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1354): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1354): WPS:  * Request Type
D/wpa_supplicant( 1354): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1354): WPS:  * UUID-E
D/wpa_supplicant( 1354): WPS:  * Primary Device Type
D/wpa_supplicant( 1354): WPS:  * RF Bands (3)
D/wpa_supplicant( 1354): WPS:  * Association State
D/wpa_supplicant( 1354): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1354): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1354): WPS:  * Manufacturer
D/wpa_supplicant( 1354): WPS:  * Model Name
D/wpa_supplicant( 1354): WPS:  * Model Number
D/wpa_supplicant( 1354): WPS:  * Device Name
D/wpa_supplicant( 1354): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1354): P2P: * P2P IE header
,D/wpa_supplicant( 1354): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1354): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 1354): wlan0: Limit manual scan to specified channels
D/wpa_supplicant( 1354): wlan0: Add radio work 'scan'@0x55b5fe3680
D/wpa_supplicant( 1354): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1354): wlan0: Starting radio work 'scan'@0x55b5fe3680 after 0.000039 second wait
D/wpa_supplicant( 1354): wlan0: nl80211: scan request
D/wpa_supplicant( 1354): Scan requested (ret=0) - scan timeout 30 seconds
D/PMS     (  951): releaseWL(10dbd0d2): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/wpa_supplicant( 1354): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1354): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1354): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1354): wlan0: Own scan request started a scan in 0.000091 seconds
I/wpa_supplicant( 1354): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  951): [1,454,983,642,150 ms] noteScanstart no scan source
E/WifiStateMachine(  951): handleMessage: X
D/WifiMonitor(  951): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  951): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  951): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  951): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,D/PMS     (  951): releaseWL(39aedd9e): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,W/Utils   ( 6588): could not parse size range '64x64-1920X1080'
,W/AudioCapabilities( 6588): Unsupported mime audio/qcelp,
,W/AudioCapabilities( 6588): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6588): Unsupported mime audio/qcelp
,W/VideoCapabilities( 6588): Unsupported mime video/x-ms-wmv
,I/UpdateIcingCorporaServi( 5970): UpdateCorporaTask done [took 63 ms] updated apps [took 63 ms] ,
,I/VideoCapabilities( 6588): Unsupported profile 4 for video/mp4v-es,
,W/VideoCapabilities( 6588): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6588): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6588): Unrecognized profile 2130706433 for video/avc
D/wpa_supplicant( 1354): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1354): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1354): nl80211: Scan included frequencies: 2412
D/wpa_supplicant( 1354): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1354): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1354): wlan0: Scan completed in 0.101212 seconds,
D/wpa_supplicant( 1354): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1354): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1354): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1354): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1354): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-55
I/wpa_supplicant( 1354): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-66
I/wpa_supplicant( 1354): [NULL] a0:c5:62:7a:49:97 freq=5260 level=-83
I/wpa_supplicant( 1354): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
D/wpa_supplicant( 1354): wlan0: BSS: Start scan result update 6
D/wpa_supplicant( 1354): BSS: last_scan_res_used=4/32
D/wpa_supplicant( 1354): wlan0: Scan-only results received
D/wpa_supplicant( 1354): wlan0: Radio work 'scan'@0x55b5fe3680 done in 0.102053 seconds
E/WifiMonitor(  951): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  951): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  951): handleMessage: E msg.what=147461
E/WifiStateMachine(  951): processMsg: ConnectedState
E/WifiStateMachine(  951):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  951): processMsg: ConnectModeState
E/WifiStateMachine(  951):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  951): processMsg: DriverStartedState
E/WifiStateMachine(  951):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  951): processMsg: SupplicantStartedState
E/WifiStateMachine(  951):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
D/WifiStateMachine(  951): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1354): wlan0: Control interface command 'LIST_DONGLES'
W/ContextImpl(  951): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
E/WifiStateMachine(  951): [1,454,983,642,256 ms] noteScanEnd no scan source
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1354): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
,W/VideoCapabilities( 6588): Unrecognized profile 2130706433 for video/avc
E/WifiStateMachine(  951): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@3c087032 sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  951): NG7005g c0:ff:d4:d3:aa:4a rssi=-55 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  951): NG700 c0:ff:d4:d3:aa:48 rssi=-66 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  951): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  951): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  951):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-66 freq=2412
E/WifiAutoJoinController (  951): UPC503894600 a0:c5:62:7a:49:97 rssi=-83 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  951): Gonzos 38:f8:89:11:e9:11 rssi=-81 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  951): ageScanResultsOut delay 40000 size 4 now 1454983642259
E/WifiAutoJoinController (  951): newSupplicantResults size=4 known=1 true
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1354): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  951): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
E/WifiAutoJoinController (  951): ssid=NG700
E/WifiAutoJoinController (  951): id=0
E/WifiAutoJoinController (  951): mode=station
E/WifiAutoJoinController (  951): pairwise_cipher=CCMP
E/WifiAutoJoinController (  951): group_cipher=CCMP
E/WifiAutoJoinController (  951): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  951): wpa_state=COMPLETED
E/WifiAutoJoinController (  951): ip_address=192.168.1.130
E/WifiAutoJoinController (  951): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  951): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  951): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  951): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController (  951): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-66,-127) num=(1,0)
,E/WifiAutoJoinController (  951): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  951): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-66 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  951): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  951): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  951): Done attemptAutoJoin status=0
E/WifiConfigStore(  951):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  951): handleMessage: X
,I/vclib   ( 6588): onServiceConnected
,W/Babel   ( 6588): Attempted to change video mute state without an active call.
,D/PMS     (  951): releaseWL(fbc5787): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null,
,W/ResourcesManager( 6588): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6588): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6588): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/System  ( 6588): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6588): Installed default security provider GmsCore_OpenSSL
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 6,
D/WIFI_ICON( 1244): WifiActivity: 1
E/WifiTrafficPoller(  951):  packet count Tx=173 Rx=217
D/StatusBar.NetworkController( 1244): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  951): notifying of data activity 1
,I/Prism.ItemManager( 1639): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1639): loadItems() com.htc.launcher.pageview.WidgetManager@24286013 +
I/Prism.WidgetManager( 1639): onLoadItems() +
,W/ResourcesManager( 1639): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,W/asset   ( 1639): Copying FileAsset 0x55907e1f90 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,
,E/Prism.WidgetManager( 1639): The same lists. No need to update. skip it.,
I/Prism.WidgetManager( 1639): onLoadItems() -
I/Prism.ItemManager( 1639): loadItems() com.htc.launcher.pageview.WidgetManager@24286013 -
,D/PhoneApp( 1580): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1580): -- N1 =0,
,D/PhoneApp( 1580): -- N2 =0
,D/PhoneApp( 1580): -- N3 =0,
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  951):  packet count Tx=173 Rx=221
,D/Messaging( 6618): supportCMAS(SIE)/init? false/true,
D/MmsConfig( 6618): networkCode: 
,D/MessageCustFlag( 6618): sku_id=118
D/MmsConfig( 6618): SIE smsPri: null
D/MmsConfig( 6618): networkCode: ,
,D/MmsConfig( 6618): packageName: com.htc.vvm.att does not exist,
,D/ReportIndicatorCache( 6618): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 6618): 
D/MmsAsyncWorkHandler( 6618): HM tk = 20001
,D/ReportIndicatorCache( 6618): MSG_QUERY_REPORTS >>
,D/SettingsManager( 6618): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@765de26,
,D/DraftCache( 6618): [DraftCache/1] DraftCache.constructor,
D/DraftCache( 6618): [DraftCache/1] refresh
D/TelephUtils( 1580): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 54
D/MmsSmsV2Provider( 1580):  slotId = -1000
D/MmsSmsV2Provider( 1580): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/Messaging( 6618): mNeedToUpdateDate2 start
,D/MmsConfig( 6618): networkCode: 
,D/TelephUtils( 1580): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 83
D/AccFlag ( 1580): sku_id=118
,D/Messaging( 6618): ViewCache CreatePreloadOnlyConversationList
,D/DraftCache( 6618): [DraftCache/161] rebuildCache
D/TelephUtils( 1580): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 55
I/Messaging( 6618): mccmnc> 
,D/MmsSmsV2Provider( 1580):  slotId = -1000
D/MmsSmsV2Provider( 1580): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 6618): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1580): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 83,
D/MmsSmsV2Provider( 1580):  slotId = -1000
D/MmsSmsV2Provider( 1580): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/TelephUtils( 1580): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 54
,D/MmsSmsV2Provider( 1580):  slotId = -1000
D/MmsSmsV2Provider( 1580): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 6618): mNeedToUpdateDate2: false,
,D/TelephUtils( 1580): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 55
D/Jerry   ( 1580): URI_DRAFT
D/PhoneStorageUtil( 6618): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 6618): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 6618): createReceiver
,D/DraftCache( 6618): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 6618): [DraftCache/161] rebuildCache time: 13
,D/MmsAsyncWorkHandler( 6618): 
D/MmsAsyncWorkHandler( 6618): HM tk = 20002
D/MessageCustFlag( 6618): sense_version=6.0
,D/Jerry   ( 6618): start to preload cursor >>>>>>>
,D/TelephUtils( 1580): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 83
D/AccFlag ( 1580): sku_id=118
,D/TelephUtils( 1580): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 55
V/MmsProvider( 1580): Update uri=content://mms, match=0
V/MmsProvider( 1580): selection=st=129 AND m_type!=134
,D/Messaging( 6618): Reset downloading state: 0
,V/MmsSystemEventReceiver( 6618): TransactionService is going to be woken up.
,V/TransactionService( 6618): 1-Creating TransactionService
D/TelephUtils( 1580): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 55
D/MmsSmsV2Provider( 1580):  slotId = -1000
,V/TransactionService( 6618): onStartCommand: 1,
D/MmsSystemEventReceiver( 6618): unRegisterForConnectionStateChanges
V/TransactionService( 6618): 4-Handling incoming message: { when=-1ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 6618): Loading previous transactions.
D/TelephUtils( 1580): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 54
D/AccFlag ( 1580): sku_id=118
,D/Messaging( 6618): ViewCache CreatePreload
D/Messaging( 6618): ViewCache CreatePreloadOnlyMultipleOpsList
,D/TelephUtils( 1580): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 83
,D/AccFlag ( 1580): device_type: 1
,D/TransactionService( 6618): Force clearing mTransactionList
,D/TransactionService( 6618): Force set service start id to 1
V/TransactionService( 6618): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 6618): unRegisterForConnectionStateChanges
,D/TransactionService( 6618): stopSelfResult: true, mLastHandledServiceId: 1
V/TransactionService( 6618): Destroying TransactionService
,V/TransactionService( 6618): 4-Handling incoming message: { when=-2ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/Cust_MMSMS( 6618): _has_set_default_values_2=true,
,D/MsgPreferenceUtils( 6618): def_index: 0
,D/MsgPreferenceUtils( 6618): globalIndex = 1,
,D/MsgPreferenceUtils( 6618): phone state: true,
D/MsgPreferenceUtils( 6618): sd state: false
D/MsgPreferenceUtils( 6618): vIndex = 0,
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  951):  packet count Tx=173 Rx=221
D/WIFI_ICON( 1244): WifiActivity: 0
E/WifiTrafficPoller(  951): notifying of data activity 0
,D/StatusBar.NetworkController( 1244): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiStateMachine(  951): handleMessage: E msg.what=131155,
E/WifiStateMachine(  951): processMsg: ConnectedState
E/WifiStateMachine(  951):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-66 f=2412 sc=60 link=57 tx=2.7, 0.0, 0.0  rx=2.8 bcn=0 [on:0 tx:0 rx:0 period:2950] from screen [on:0 period:-1010268244] gl hn u24 rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-66 f=2412 sc=60 link=57 tx=2.7, 0.0, 0.0  rx=2.8 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1010268243] gl hn u24 rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  951):  get link layer stats 0
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1354): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1354): environment dirty rate=0 [0][0][0],
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative RSSI = -65 abnormalRssiCnt = 0 newLinkSpeed = 65
D/WIFI_ICON( 1244): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative rssi=-65 linkspeed=65
D/StatusBar.NetworkController( 1244): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T],
E/WifiConfigStore(  951): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-65 "NG700"WPA_PSK
E/WifiStateMachine(  951): calculateWifiScore freq=2412 speed=65 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=1.33 txretriesrate=0.00 rxrate=3.92 userTriggerdPenalty0
E/WifiStateMachine(  951):  good link -> stuck count =0
E/WifiStateMachine(  951):  badRSSI count0 lowRSSI count0 --> score 56,
E/WifiStateMachine(  951):  isHighRSSI       ---> score=61
E/WifiStateMachine(  951): handleMessage: X
D/WifiWatchdogStateMachine(  951): RSSI current: 3 new: -65, 3
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL true Token 11 num clients 6
,E/WifiTrafficPoller(  951):  packet count Tx=173 Rx=221
,I/PMS     (  951): Going to sleep due to screen timeout (uid 1000)...,
D/ActivityManager(  951): getTaskThumbnailLocked mainThumbnail is null, TaskRecord{3faf4bf1 #7 A=.Prism U=0 sz=1}
,W/PMS     (  951): mWirelessDisplayManager is null
,I/SensorManager(  951): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@3b82474d
W/PMS     (  951): mWirelessDisplayManager is still null
W/SensorService(  951): Following SensorService logs are not warning, just make sure they are printed
I/PMS     (  951): Sleeping (uid 1000)...
W/SensorService(  951): disable: get sensor name = Accelerometer Sensor
D/XAN-DPS (  951): prepareColorFade 1
W/SensorService(  951): pid=951, uid=1000
W/SensorService(  951): Active sensors: size = 4
W/SensorService(  951): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  951): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  951): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  951): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  951): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@3b82474d, eanble = 0, strlen(mName) = 91
W/PMN     (  951): goingToSleep
W/SensorService(  951): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  951): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@36887b93
W/SensorService(  951): Listener[1] = com.htc.smartdim.sensor_eye@3d924fb0
W/SensorService(  951): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/PMS     (  951): acquireWL(342cf3d6): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 951 1000 null
,W/PMN     (  951): goingToSleep done
,I/Adreno-EGL(  951): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL(  951): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  951): Build Date: 03/09/15 Mon
I/Adreno-EGL(  951): Local Branch: 
I/Adreno-EGL(  951): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  951): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  951):                  d74aa161a12b9c6fc6332151
,I/ActivityManager(  951): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=6681 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,I/FeedHostManager( 1639): [onPause]
I/FeedProviderManager( 1639): onPause
,I/FeedHostManager( 1639): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@35e39494
D/AlarmManager(  951): ACTION_SCREEN_ON
I/SocialFeedProvider( 1639): +onPause
I/SocialFeedProvider( 1639): -onPause
,W/HtcSystemUPManager(  951): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,D/PMS     (  951): releaseWL(342cf3d6): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
I/AlarmManager(  951): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  951): [AlarmQueuing] done recovering
I/AlarmManager(  951): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  951): [AlarmQueuing] done EPS screen off alarm recovering
,W/HtcLockScreen( 1244): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,E/WifiTrafficPoller(  951): ENABLE_TRAFFIC_STATS_POLL true Token 11
,E/WifiTrafficPoller(  951):  packet count Tx=173 Rx=221
,E/WifiDataStallTracker(  951): ENABLE_DATA_MONITOR_POLL true Token 1,
,E/WifiStateMachine(  951): handleMessage: E msg.what=131167
E/WifiStateMachine(  951): processMsg: ConnectedState
E/WifiStateMachine(  951):  ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  951): processMsg: ConnectModeState
E/WifiStateMachine(  951):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  951): processMsg: DriverStartedState
E/WifiStateMachine(  951):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  951): processMsg: SupplicantStartedState
D/WifiDataStallTracker(  951): updateDataStallInfo: mDataStallTxRxSum={txSum=155 rxSum=132} preTxRxSum={txSum=155 rxSum=132}
D/WifiDataStallTracker(  951): updateDataStallInfo: NONE
D/WifiDataStallTracker(  951): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
E/WifiStateMachine(  951):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  951): processMsg: DefaultState
E/WifiStateMachine(  951):  DefaultState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  951):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/wpa_supplicant( 1354): wlan0: Control interface command 'SET_SCREEN_ON 1'
I/wpa_supplicant( 1354): SET_SCREEN_ON:On
I/wpa_supplicant( 1354): htc_wext_set_keepalive +
I/wpa_supplicant( 1354): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1354): getPrivFuncNum +	
I/wpa_supplicant( 1354): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1354): htc_wext_set_keepalive fnum = 0x8bf6
D/WifiDisplayAdapter(  951): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  951):     Client/Owner: Client
D/WifiDisplayAdapter(  951):     GroupId: 
D/WifiDisplayAdapter(  951):     Passphrase: 
D/WifiDisplayAdapter(  951):     SessionId: 0
D/WifiDisplayAdapter(  951):     IP Address: }
I/wpa_supplicant( 1354): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1354): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1354): htc_wext_set_TX_TRACKING - ret = 0
E/WifiStateMachine(  951): setScanAlarm true period 20000 initial delay 200mAlarmEnabledtrue
D/WifiStateMachine(  951): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  951): handleScreenStateChanged Exit: true
E/WifiStateMachine(  951): handleMessage: X
E/WifiStateMachine(  951): handleMessage: E msg.what=131154
E/WifiStateMachine(  951): processMsg: ConnectedState
E/WifiStateMachine(  951):  ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1354): wlan0: Control interface command 'SIGNAL_POLL'
,V/SRS_Proc(  401): ParamSet string: screen_state=on,
E/audio_a2dp_hw(  401): adev_set_parameters: ERROR: set param called even when stream out is null
,I/wpa_supplicant( 1354): environment dirty rate=0 [0][0][0]
D/WifiController(  951): handleMessage: E msg.what=155650
E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative RSSI = -65 abnormalRssiCnt = 0 newLinkSpeed = 65
,E/WifiStateMachine(  951): fetchRssiLinkSpeedAndFrequencyNative rssi=-65 linkspeed=65
E/WifiConfigStore(  951): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-65 "NG700"WPA_PSK
E/WifiStateMachine(  951): handleMessage: X
E/WifiStateMachine(  951): handleMessage: E msg.what=131127
E/WifiStateMachine(  951): processMsg: ConnectedState
D/WifiController(  951): processMsg: DeviceActiveState
D/WifiController(  951): processMsg: StaEnabledState
D/NetworkPolicy(  951): updateScreenOn: false
D/WifiController(  951): processMsg: DefaultState
V/NetworkPolicy(  951): updateIfacesLocked()
E/WifiStateMachine(  951):  ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
D/WifiController(  951): handleMessage: X
E/WifiStateMachine(  951):  L2ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  951): processMsg: ConnectModeState
D/NetworkManagementService(  951): isBandwidthControlEnabled: doneSignal.getCount()= 0
,E/WifiStateMachine(  951):  ConnectModeState !CMD_ENABLE_ALL_NETWORKS 0 0,
E/WifiStateMachine(  951): handleMessage: X
E/WifiStateMachine(  951): handleMessage: E msg.what=131129
E/WifiStateMachine(  951): processMsg: ConnectedState
E/WifiStateMachine(  951):  ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
,E/WifiStateMachine(  951):  L2ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  951): processMsg: ConnectModeState
E/WifiStateMachine(  951):  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1354): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1354): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  951): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
,E/WifiMonitor(  951): WifiMonitor:wlan0 cnt=34 dispatchEvent: BLACKLIST CLEAR 
E/WifiStateMachine(  951): handleMessage: X
,W/ResourcesManager( 6681): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/DotMatrix( 1350): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/CalendarProvider2( 6681): Created com.android.providers.calendar.CalendarAlarmManager@3bdf0568(com.htc.providers.calendar.HtcCalendarProvider@80b2d81),
,D/CalendarProvider2( 6681): wait start:true,
D/GpsLocationProvider(  951): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/IntentController( 1244): receive(android.intent.action.SCREEN_ON,1,false)
,D/XAN-DPS (  951): prepareColorFade done
,D/XAN-DPS (  951): setBrightness to 0
,I/SensorManager(  951): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@36887b93
,W/SensorService(  951): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  951): disable: get sensor name = CM32181 Light sensor
I/DisplayManagerService(  951): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  951): Display changed displayId=0
D/DotMatrix( 1350): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1350): [EventService] mbHDMIConnect: false, mCoverOn:false
W/SensorService(  951): pid=951, uid=1000,
,W/SensorService(  951): Active sensors: size = 3
W/SensorService(  951): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  951): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  951): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  951): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@36887b93, eanble = 0, strlen(mName) = 67
W/SensorService(  951): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  951): Listener[0] = com.htc.smartdim.sensor_eye@3d924fb0
W/SensorService(  951): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/CalendarProvider2( 6681): wait end:false
,E/qdutils (  387): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  387): int qdutils::getHDMINode(): Failed to find HDMI node
,D/PMS     (  951): acquireWL(3fe456c8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1925 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): acquireWL(2d5a1361): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1925 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): releaseWL(2d5a1361): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): releaseWL(3fe456c8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,I/SensorManager( 1244): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@3d62cecb, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null
,W/SensorService(  951): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  951): enable: get sensor name = hTC Gesture Motion HIDI,
,W/SensorService(  951): pid=1244, uid=10041
W/SensorService(  951): Active sensors: size = 4
,I/ActivityManager(  951): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=6712 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
W/SensorService(  951): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  951): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  951): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  951): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  951): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@3d62cecb, eanble = 1, strlen(mName) = 57
W/SensorService(  951): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  951): Listener[0] = com.htc.smartdim.sensor_eye@3d924fb0
W/SensorService(  951): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@3d62cecb
W/SensorService(  951): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/AlarmManager(  951): ACTION_SCREEN_OFF
,I/AlarmManager(  951): [AlarmQueuing] screen off now: 
I/AlarmManager(  951): [AlarmQueuing] data connection: true
I/AlarmManager(  951): [AlarmQueuing] wifi connection: true
,E/WifiTrafficPoller(  951): ENABLE_TRAFFIC_STATS_POLL false Token 12
D/WifiDataStallTracker(  951): stopDataStallAlarm 
E/WifiDataStallTracker(  951): ENABLE_DATA_MONITOR_POLL false Token 2
E/WifiStateMachine(  951): handleMessage: E msg.what=131167
E/WifiStateMachine(  951): processMsg: ConnectedState
E/WifiStateMachine(  951):  ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  951): processMsg: ConnectModeState
E/WifiStateMachine(  951):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  951): processMsg: DriverStartedState
E/WifiStateMachine(  951):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 0 0
V/SRS_Proc(  401): ParamSet string: screen_state=off
E/WifiStateMachine(  951): processMsg: SupplicantStartedState
E/audio_a2dp_hw(  401): adev_set_parameters: ERROR: set param called even when stream out is null
,E/WifiStateMachine(  951):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  951): processMsg: DefaultState
E/WifiStateMachine(  951):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  951):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
D/WifiController(  951): handleMessage: E msg.what=155651
W/WifiHW  (  951): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/WifiController(  951): processMsg: DeviceActiveState
D/WifiController(  951): processMsg: StaEnabledState
D/WifiController(  951): processMsg: DefaultState
D/wpa_supplicant( 1354): wlan0: Control interface command 'SET_SCREEN_ON 0'
D/WifiController(  951): handleMessage: X
I/wpa_supplicant( 1354): SET_SCREEN_ON:Off
I/wpa_supplicant( 1354): htc_wext_set_keepalive +
I/wpa_supplicant( 1354): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/WifiDisplayAdapter(  951): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  951):     Client/Owner: Client
D/WifiDisplayAdapter(  951):     GroupId: 
D/WifiDisplayAdapter(  951):     Passphrase: 
D/WifiDisplayAdapter(  951):     SessionId: 0
D/WifiDisplayAdapter(  951):     IP Address: }
D/wpa_supplicant( 1354): getPrivFuncNum +,	
I/wpa_supplicant( 1354): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1354): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1354): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1354): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1354): htc_wext_set_keepalive - ret = 0
E/WifiStateMachine(  951): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
D/NetworkPolicy(  951): updateScreenOn: false
V/NetworkPolicy(  951): updateIfacesLocked()
D/WifiStateMachine(  951): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  951): handleScreenStateChanged Exit: false
E/WifiStateMachine(  951): handleMessage: X
D/NetworkManagementService(  951): isBandwidthControlEnabled: doneSignal.getCount()= 0
E/WifiStateMachine(  951): handleMessage: E msg.what=131154
E/WifiStateMachine(  951): processMsg: ConnectedState
,E/WifiStateMachine(  951):  ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  951): handleMessage: X
,D/DotMatrix( 1350): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,E/WifiDataStallTracker(  951): DATA_MONITOR_POLL false Token 3
,D/DotMatrix( 1350): [EventService] getTotalRam: 1842 Mb
,D/GpsLocationProvider(  951): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,D/ContactMessageStore( 1580): start background delete task...
,I/IntentController( 1244): receive(android.intent.action.SCREEN_OFF,1,false)
,D/ContactMessageStore( 1580): size: 0 , 0
,D/ContactMessageStore( 1580): Background delete complete
D/PMS     (  951): acquireWL(144c1774): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1925 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  951): releaseWL(144c1774): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): acquireWL(2b43849d): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1925 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): releaseWL(2b43849d): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 6712): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,E/qdutils (  387): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  387): int qdutils::getHDMINode(): Failed to find HDMI node
D/PMS     (  951): Setting HAL interactive mode to false
D/SurfaceControl(  951): Excessive delay in setPowerMode(): 304ms
D/PMS     (  951): Setting HAL interactive mode to false done
W/HtcSystemUPManager(  951): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
D/PMS     (  951): Setting HAL auto-suspend mode to true
D/PMS     (  951): Setting HAL auto-suspend mode done
W/ContextImpl( 6712): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,I/InputMethodManagerService(  951): screenObserver, isScreenOn=false
D/StatusBarManagerService(  951): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  951): Disable input method client, pid=1639
D/HABCtrl (  951): TPE algorithm. remove timeout.
,I/IntentController( 1244): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/PMS     (  951): OOBE c monitor 11
I/InputManager(  951): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false
D/PMS     (  951): acquireWL(13cd36e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 951 1000 null
I/BatteryService(  951): n_update end
D/PMS     (  951): releaseWL(13cd36e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/RemoteViews( 1244): setHTCTheme(com.htc.updater,true,33751145)
I/IntentController( 1244): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  951): plugged=true pluggin=true
D/DotMatrix( 1350): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  951): battery changed pluggedType: 2
D/DotMatrix( 1350): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1350): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  951): BroadcastReceiver::onReceive+
D/UsbnetService(  951): onReceive BATTERY_CHANGED
D/UsbnetService(  951):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  951): BroadcastReceiver::onReceive-
D/HeadsetStateMachine( 3147): Disconnected process message: 10, size: 0
D/WifiController(  951): handleMessage: E msg.what=155652
D/WifiController(  951): processMsg: DeviceActiveState
D/WifiController(  951): processMsg: StaEnabledState
D/WifiController(  951): processMsg: DefaultState
D/WifiController(  951): handleMessage: X
,D/HtcPowerSaver(  951): updateBatteryInfo
,D/NfcService( 1599): ScreenObserver: OFF
D/PMS     (  951): runPSCheck
D/HtcPowerSaver(  951): Checking...
I/HtcPowerSaver(  951): >> updateStatus
D/NfcService( 1599): applyRouting - 0
,D/PMS     (  951): acquireWL(658cd99): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1599 1027 null
D/NfcService( 1599): applyRouting -2
D/NfcService( 1599): applyRouting
D/NfcService( 1599): Ignore this applyRouting...
D/PMS     (  951): releaseWL(658cd99): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PowerUsageList:PowerUsageHelper( 6712): MY_DEBUG = false
,I/HtcPowerSaver(  951): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  951): << updateStatus
,I/RemoteViews( 1244): apply : com.htc.updater 1 29 2 36
,D/SmartSyncUtils( 6712): isEpsOn(), nState = 0
,I/PhoneStatusBar( 1244): setImeWindowStatus(false,false)
D/PowerUI ( 1244): closing low battery warning: level=100
I/ClockController( 1244): stop clock update:screen off,
D/PowerUI ( 1244): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/BatteryController( 1244): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  951): acquireWL(1fca585e): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6712 1000 null
,W/ContextImpl(  951): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 ,
,D/SmartDim(  951): Init customizeScreenOffDelayClass error,
D/PMS     (  951): releaseWL(1fca585e): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl( 6712): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 6712): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 ,
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL false Token 13 num clients 6,
,D/SmartSyncUtils( 6712): isEpsOn(), nState = 0
,D/SmartSyncUtils( 6712): isEpsOn(), nState = 0,
,W/ContextImpl( 6712): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 ,
,W/ContextImpl(  951): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 ,
I/SensorManager(  951): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@3d924fb0
W/SensorService(  951): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  951): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  951): pid=951, uid=1000
,W/SensorService(  951): Active sensors: size = 3
W/SensorService(  951): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  951): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  951): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  951): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@3d924fb0, eanble = 0, strlen(mName) = 36
W/SensorService(  951): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  951): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@3d62cecb
W/SensorService(  951): void android::SensorService::listenerSensor(const char*, int32_t)--:
,W/SensorService(  951): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  951): disable: get sensor name = CM36686 Proximity sensor
,W/SensorService(  951): pid=951, uid=1000,
W/SensorService(  951): Active sensors: size = 2
W/SensorService(  951): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  951): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  951): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@3d924fb0, eanble = 0, strlen(mName) = 36
W/SensorService(  951): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  951): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@3d62cecb
W/SensorService(  951): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  951): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@3d924fb0
,I/ActivityManager(  951): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=6745 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,E/ActivityThread(  951): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@1db3be29 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  951): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@1db3be29 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  951): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  951): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread(  951): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  951): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  951): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  951): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  951): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  951): 	at android.app.Service.onStartCommand(Service.java:458)
E/ActivityThread(  951): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
E/ActivityThread(  951): 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
E/ActivityThread(  951): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
E/ActivityThread(  951): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  951): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  951): 	at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  951): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  951): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  951): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  951): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029),
E/ActivityThread(  951): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824),
,D/Process (  951): killProcessQuiet, pid=6309,
I/ActivityManager(  951): Killing 6309:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  951): Recipient 6309,
,I/PowerUsageList:PowerUsageHelper( 6712): PowerProfile::POWER_SCREEN_FULL = 154.8,
,D/PowerUsageList:BatterySipperExt( 6712): gen(), null == sipper.uidObj, userId = 0
,I/ActivityManager(  951): Killing 6332:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  951): killProcessQuiet, pid=6332
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,D/SmartSyncUtils( 6712): getMobilePolicyEnabled, result = true
,E/WifiTrafficPoller(  951): TRAFFIC_STATS_POLL false Token 13 num clients 6,
,I/ActivityManager(  951): Recipient 6332
,E/WifiTrafficPoller(  951): ADD_CLIENT: 7,
D/WifiService(  951): New client listening to asynchronous messages
,I/CalendarProvider2( 6681): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 6681): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  951): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=6769 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,D/PowerUsageList:PowerUsageHelper( 6712): MY_DEBUG = false
,I/ActivityManager(  951): Killing 6096:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  951): killProcessQuiet, pid=6096
,D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  951): Recipient 6096
,W/ResourcesManager( 6769): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,D/Process (  951): killProcessQuiet, pid=6363,
I/ActivityManager(  951): Killing 6363:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/CalendarApplication( 6769): onCreate,
,D/ProviderChangeReceiver( 6769): ---------------------------------------------------
,D/ProviderChangeReceiver( 6769): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,D/HtcAlertService( 6769): start to updateAlertNotification!,
,I/ActivityManager(  951): Recipient 6363
,D/PMS     (  951): releaseWL(3281f5e6): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,I/ActivityManager(  951): Killing 5783:com.android.defcontainer/u0a15 (adj 15): empty #17
,D/Process (  951): killProcessQuiet, pid=5783,
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/ActivityManager(  951): Recipient 5783
,D/Process (  951): killProcessQuiet, pid=5499,
I/ActivityManager(  951): Killing 5499:com.htc.mediamanager/u0a28 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  951): Recipient 5499
,D/HtcAlertService( 6769): No fired or scheduled alerts,
,D/HtcAlertUtils( 6769): -- cancelReminderNotification --
,D/HtcAlertUtils( 6769): broadcastExistReminder!
,D/DotMatrix( 1350): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,
,E/WifiStateMachine(  951): handleMessage: E msg.what=131155,
E/WifiStateMachine(  951): processMsg: ConnectedState
,E/WifiStateMachine(  951):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1010265220] gl hn u24 rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1010265217] gl hn u24 rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  951): handleMessage: X
,E/WifiStateMachine(  951): handleMessage: E msg.what=131155
,E/WifiStateMachine(  951): processMsg: ConnectedState
E/WifiStateMachine(  951):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1027] from screen [on:0 period:-1010264189] gl hn u24 rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  951): processMsg: L2ConnectedState
E/WifiStateMachine(  951):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1010264186] gl hn u24 rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  951): handleMessage: X
,D/HtcUPManager( 1244): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60,
,E/WifiDataStallTracker(  951): DATA_MONITOR_POLL false Token 3,
,D/ContactMessageStore( 1580): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1580): MSG_NOTIFY_CS_TO_SYNC <<
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 1,
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 2
,I/ActivityManager(  951): Killing 5647:com.htc.musicenhancer/u0a49 (adj 15): empty #17,
D/Process (  951): killProcessQuiet, pid=5647
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  951): Recipient 5647,
,D/PMS     (  951): acquireWL(1fdfaa55): PARTIAL_WAKE_LOCK  *alarm* 0x1 951 1000 WorkSource{10024}
,V/AlarmManager(  951): sending alarm PendingIntent{26da155b: PendingIntentRecord{2dbd96d1 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=143446, Int=0
,D/PMS     (  951): releaseWL(1fdfaa55): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024},
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  951): [handleMessage] DOWNLOAD_XTRA_DATA,
D/GpsLocationProvider(  951): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true,
D/PMS     (  951): acquireWL(34531536): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 951 1000 null,
,D/libc    (  951): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4,
D/libc    (  951): [NET] android_getaddrinfofornet-, err=8,
D/libc    (  951): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  951): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  951): [NET] android_getaddrinfo_proxy+
D/libc    (  951): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  951): [NET] android_getaddrinfo_proxy-, success
D/libc    (  951): [NET] android_getaddrinfofornet+,hn 14(0x35342e3233302e),sn(),hints(known),family 0,flags 4
D/libc    (  951): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  951): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/GpsLocationProvider(  951): [reportHTCStatus] eventMask = 3 , status = 0
D/PMS     (  951): acquireWL(3ab34ec2): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 951 1000 null
D/GpsLocationProvider(  951): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/GpsLocationProvider(  951):  [handleDownloadXtraData]inject done.
D/PMS     (  951): releaseWL(34531536): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
,D/GpsLocationProvider(  951): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  951): releaseWL(3ab34ec2): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ContactMessageStore( 1580): MSG_NOTIFY_CS_TO_SYNC >>
D/ContactMessageStore( 1580): MSG_NOTIFY_CS_TO_SYNC <<
,W/ContextImpl(  951): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  951): acquireWL(c63d4d3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 951 1000 null
I/BatteryService(  951): n_update end
D/PMS     (  951): releaseWL(c63d4d3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1350): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  951): updateBatteryInfo,
D/DotMatrix( 1350): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  951): plugged=true pluggin=true
D/DotMatrix( 1350): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  951): runPSCheck
,D/UsbnetService(  951): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  951): Checking...
D/UsbnetService(  951): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  951): >> updateStatus
D/UsbnetService(  951):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/WifiController(  951): battery changed pluggedType: 2
D/UsbnetService(  951): BroadcastReceiver::onReceive-
D/PowerUI ( 1244): closing low battery warning: level=100
D/WifiController(  951): handleMessage: E msg.what=155652
D/PowerUI ( 1244): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  951): processMsg: DeviceActiveState
I/HtcPowerSaver(  951): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  951): processMsg: StaEnabledState
I/HtcPowerSaver(  951): << updateStatus
D/WifiController(  951): processMsg: DefaultState
D/WifiController(  951): handleMessage: X
,D/HeadsetStateMachine( 3147): Disconnected process message: 10, size: 0
I/IntentController( 1244): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1244): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 5
,D/TelephonyReceiver( 1580): switchBindHtcMsgCursor: null
,D/PMS     (  951): acquireWL(1f8c1810): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 951 1000 WorkSource{1000},
V/AlarmManager(  951): sending alarm PendingIntent{3636d3f9: PendingIntentRecord{35844f3e android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=146897, Int=0
V/AlarmManager(  951): sending alarm PendingIntent{a5b4f09: PendingIntentRecord{24eb950e android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1454983701785, Int=0
V/AlarmManager(  951): sending alarm PendingIntent{168ceb2f: PendingIntentRecord{1f02a53c android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=203869, Int=0
V/AlarmManager(  951): sending alarm PendingIntent{ae0d2c5: PendingIntentRecord{2b4ff41a com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1454983703679, Int=1800000
,V/AlarmManager(  951): sending alarm PendingIntent{33870b4b: PendingIntentRecord{1cf2d928 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=191090, Int=0
,D/PMS     (  951): acquireWL(2e80d641): PARTIAL_WAKE_LOCK  *backup* 0x1 951 1000 null
,W/BackupManagerService(  951): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService,
E/BackupManagerService(  951): Requested init for com.google.android.gms.backup.BackupTransportService but not found
,D/PMS     (  951): releaseWL(2e80d641): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/WeatherUtility( 1244): Weather sync is On
D/PMS     (  951): acquireWL(56937e6): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4506 10024 WorkSource{10024 com.google.android.gms}
W/WeatherTimeKeeper( 1244): [refreshWeatherData] no weather data
,D/PMS     (  951): releaseWL(1f8c1810): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{10024}
D/PMS     (  951): acquireWL(3305fd4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1854 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): acquireWL(ac3957d): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4506 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): releaseWL(56937e6): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): acquireWL(b790c79): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1854 10024 WorkSource{10024 com.google.android.gms}
,I/EventLogService( 4506): Aggregate from 1454983631453 (log), 1454981903648 (data)
,D/PMS     (  951): releaseWL(3305fd4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1854): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/PMS     (  951): releaseWL(ac3957d): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms},
,I/art     ( 1854): Explicit concurrent mark sweep GC freed 12665(678KB) AllocSpace objects, 5(420KB) LOS objects, 49% free, 4MB/8MB, paused 839us total 64.236ms
,D/PMS     (  951): releaseWL(b790c79): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  951): acquireWL(1155d3b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1854 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  951): releaseWL(1155d3b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  951): acquireWL(f22dc58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1854 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  951): releaseWL(f22dc58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): acquireWL(150ad1b1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1854 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): acquireWL(21656696): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1854 10024 WorkSource{10024 com.google.android.gms}
,I/art     (  951): Explicit concurrent mark sweep GC freed 33892(1873KB) AllocSpace objects, 4(1052KB) LOS objects, 33% free, 18MB/28MB, paused 2.133ms total 198.992ms
,D/PMS     (  951): acquireWL(1d156604): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1854 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  951): releaseWL(150ad1b1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
I/VacuumService( 1854): Vacuum at: now=1454983737555 tag=VacuumService
,D/PMS     (  951): releaseWL(21656696): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): acquireWL(37895622): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1854 10024 WorkSource{10024 com.google.android.gms}
I/GoogleURLConnFactory( 1854): Using platform SSLCertificateSocketFactory
,D/PMS     (  951): releaseWL(37895622): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): acquireWL(3e0438b3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1854 10024 WorkSource{10024 com.google.android.gms}
,W/Uploader( 1854): No account for auth token provided
,D/PMS     (  951): releaseWL(3e0438b3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1854): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1854): [NET] android_getaddrinfofornet-, err=8,
D/libc    ( 1854): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1854): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1854): [NET] android_getaddrinfo_proxy+
D/libc    ( 1854): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1854): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1854): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1854): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1854): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
,D/libc    ( 1854): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1854): No account for auth token provided,
,W/Uploader( 1854): No account for auth token provided,
,W/Uploader( 1854):  no longer exists, so no auth token.,
,W/Uploader( 1854): No account for auth token provided,
,I/GLSUser ( 1854): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1854): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1854): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1854): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1854): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/RemoteViews( 1244): reapply : com.google.android.gms 3 40
,D/DotMatrix( 1350): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1350): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/Uploader( 1854): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1854): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1854): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1854): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1854): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1854): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1854): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1854): 	,at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1854): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1854): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1854): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1854): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1854): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/PMS     (  951): releaseWL(1d156604): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  951): acquireWL(1b205834): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1854 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): releaseWL(1b205834): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  951): acquireWL(13dd965d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1854 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  951): releaseWL(13dd965d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/HtcUPManager( 1244): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
D/HtcUPManager( 1244): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
D/HtcAppUPService( 1562): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@19ae1dc3
,D/Process (  951): killProcessQuiet, pid=6539
I/ActivityManager(  951): Killing 6539:com.google.android.setupwizard/u0a77 (adj 15): empty #17
,D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  951): Recipient 6539
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 1,
,I/IntentController( 1244): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  951): acquireWL(22178bd2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 951 1000 null
D/DotMatrix( 1350): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  951): n_update end
D/DotMatrix( 1350): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  951): releaseWL(22178bd2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1350): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1244): closing low battery warning: level=100
D/HeadsetStateMachine( 3147): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  951): updateBatteryInfo
D/UsbnetService(  951): BroadcastReceiver::onReceive+
D/NotificationService(  951): plugged=true pluggin=true
D/UsbnetService(  951): onReceive BATTERY_CHANGED
D/PMS     (  951): runPSCheck
D/UsbnetService(  951):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  951): Checking...
D/UsbnetService(  951): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  951): >> updateStatus
,D/WifiController(  951): handleMessage: E msg.what=155652
D/PowerUI ( 1244): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  951): processMsg: DeviceActiveState
D/WifiController(  951): battery changed pluggedType: 2
D/WifiController(  951): processMsg: StaEnabledState
D/WifiController(  951): processMsg: DefaultState
D/WifiController(  951): handleMessage: X
I/HtcPowerSaver(  951): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  951): << updateStatus
,I/BatteryController( 1244): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1354): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1354): wlan0: BSS: Remove id 2 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1354): wlan0: BSS: Remove id 3 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/WifiMonitor(  951): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  951): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  951): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 a0:c5:62:7a:49:97]
E/WifiMonitor(  951): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 a0:c5:62:7a:49:97
D/WifiMonitor(  951): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11]
E/WifiMonitor(  951): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  951): acquireWL(270cb4a3): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 951 1000 WorkSource{1000},
,V/AlarmManager(  951): sending alarm PendingIntent{3636d3f9: PendingIntentRecord{35844f3e android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=206897, Int=0,
,V/AlarmManager(  951): sending alarm PendingIntent{11e23b59: PendingIntentRecord{b3e931e com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1454983873788, Int=0
,D/PMS     (  951): releaseWL(270cb4a3): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1244): Weather sync is On
W/WeatherTimeKeeper( 1244): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  951): acquireWL(1abf7ff): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 951 1000 null
I/BatteryService(  951): n_update end
D/PMS     (  951): releaseWL(1abf7ff): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  951): updateBatteryInfo
D/PMS     (  951): runPSCheck,
,D/HtcPowerSaver(  951): Checking...
I/HtcPowerSaver(  951): >> updateStatus
D/DotMatrix( 1350): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1350): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1244): closing low battery warning: level=100
D/DotMatrix( 1350): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1244): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1244): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HeadsetStateMachine( 3147): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  951): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  951): << updateStatus
D/NotificationService(  951): plugged=true pluggin=true
D/UsbnetService(  951): BroadcastReceiver::onReceive+
D/UsbnetService(  951): onReceive BATTERY_CHANGED
D/WifiController(  951): battery changed pluggedType: 2
D/UsbnetService(  951):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  951): BroadcastReceiver::onReceive-
D/WifiController(  951): handleMessage: E msg.what=155652
D/WifiController(  951): processMsg: DeviceActiveState
D/WifiController(  951): processMsg: StaEnabledState
D/WifiController(  951): processMsg: DefaultState
D/WifiController(  951): handleMessage: X
,I/BatteryController( 1244): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 3
,V/GLSActivity( 1854): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1854): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1854): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1854): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1854): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1854): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1350): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1350): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1244): reapply : com.google.android.gms 3 40
,W/GLSActivity( 1854): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1854): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1854): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1854): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1854): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1854): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1854): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 6055): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6055): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6055): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6055): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6055): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6055): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6055): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 6055): Ignoring header User-Agent because its value was null.
,D/libc    ( 6055): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 6055): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 6055): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 6055): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    ( 6055): [NET] android_getaddrinfo_proxy+
D/libc    ( 6055): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6055): [NET] android_getaddrinfo_proxy-, success
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  951): acquireWL(3cfbacc9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 951 1000 null
D/UsbnetService(  951): BroadcastReceiver::onReceive+
I/BatteryService(  951): n_update end
D/DotMatrix( 1350): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  951): releaseWL(3cfbacc9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  951): onReceive BATTERY_CHANGED
D/DotMatrix( 1350): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  951): plugged=true pluggin=true
D/UsbnetService(  951):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  951): updateBatteryInfo
D/DotMatrix( 1350): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1244): closing low battery warning: level=100
D/UsbnetService(  951): BroadcastReceiver::onReceive-
D/PMS     (  951): runPSCheck
I/IntentController( 1244): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  951): Checking...
D/WifiController(  951): handleMessage: E msg.what=155652
I/HtcPowerSaver(  951): >> updateStatus
D/HeadsetStateMachine( 3147): Disconnected process message: 10, size: 0
D/WifiController(  951): battery changed pluggedType: 2
D/WifiController(  951): processMsg: DeviceActiveState
D/PowerUI ( 1244): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  951): processMsg: StaEnabledState
D/WifiController(  951): processMsg: DefaultState
D/WifiController(  951): handleMessage: X
,I/HtcPowerSaver(  951): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  951): << updateStatus
,I/BatteryController( 1244): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 5,
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  951): acquireWL(1243ffce): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 951 1000 null
I/BatteryService(  951): n_update end
D/PMS     (  951): releaseWL(1243ffce): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  951): updateBatteryInfo
,D/DotMatrix( 1350): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1244): closing low battery warning: level=100
I/IntentController( 1244): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  951): plugged=true pluggin=true
D/DotMatrix( 1350): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  951): runPSCheck
D/DotMatrix( 1350): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1244): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 3147): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  951): Checking...
D/UsbnetService(  951): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  951): >> updateStatus
D/UsbnetService(  951): onReceive BATTERY_CHANGED
D/UsbnetService(  951):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  951): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  951): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  951): << updateStatus
,D/WifiController(  951): handleMessage: E msg.what=155652
D/WifiController(  951): processMsg: DeviceActiveState
D/WifiController(  951): processMsg: StaEnabledState
D/WifiController(  951): processMsg: DefaultState
D/WifiController(  951): handleMessage: X
D/WifiController(  951): battery changed pluggedType: 2
,I/BatteryController( 1244): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  951): acquireWL(2638deef): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 951 1000 null
I/BatteryService(  951): n_update end
D/PMS     (  951): releaseWL(2638deef): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1350): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  951): updateBatteryInfo
D/DotMatrix( 1350): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  951): plugged=true pluggin=true
D/DotMatrix( 1350): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  951): runPSCheck
D/UsbnetService(  951): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  951): Checking...
D/UsbnetService(  951): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  951): >> updateStatus
D/UsbnetService(  951):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  951): battery changed pluggedType: 2
,D/UsbnetService(  951): BroadcastReceiver::onReceive-
D/PowerUI ( 1244): closing low battery warning: level=100
D/WifiController(  951): handleMessage: E msg.what=155652
D/PowerUI ( 1244): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  951): processMsg: DeviceActiveState
I/HtcPowerSaver(  951): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  951): processMsg: StaEnabledState
I/HtcPowerSaver(  951): << updateStatus
D/WifiController(  951): processMsg: DefaultState
D/WifiController(  951): handleMessage: X
D/HeadsetStateMachine( 3147): Disconnected process message: 10, size: 0
I/IntentController( 1244): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1244): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  951): acquireWL(35fdedfc): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 951 1000 null,
I/BatteryService(  951): n_update end
D/PMS     (  951): releaseWL(35fdedfc): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  951): updateBatteryInfo
D/DotMatrix( 1350): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1350): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1350): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1244): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HeadsetStateMachine( 3147): Disconnected process message: 10, size: 0
D/PowerUI ( 1244): closing low battery warning: level=100
D/UsbnetService(  951): BroadcastReceiver::onReceive+
D/NotificationService(  951): plugged=true pluggin=true
D/UsbnetService(  951): onReceive BATTERY_CHANGED
D/PMS     (  951): runPSCheck
D/UsbnetService(  951):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  951): Checking...
D/UsbnetService(  951): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  951): >> updateStatus
D/PowerUI ( 1244): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  951): handleMessage: E msg.what=155652
D/WifiController(  951): processMsg: DeviceActiveState
D/WifiController(  951): battery changed pluggedType: 2
D/WifiController(  951): processMsg: StaEnabledState
D/WifiController(  951): processMsg: DefaultState
D/WifiController(  951): handleMessage: X
,I/HtcPowerSaver(  951): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  951): << updateStatus
,I/BatteryController( 1244): status:5 level:100 unsupport:false plugged:true,
,E/PNP_UPDATERD(  388): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1580): MSG_CHECK_DELETION >>,
D/ContactMessageStore( 1580): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1580): sku_id=118
,D/ContactMessageStore( 1580): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1580): start background delete task...
D/ContactMessageStore( 1580): size: 0 , 0
,D/ContactMessageStore( 1580): Background delete complete
,D/PMS     (  951): acquireWL(28894c85): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 951 1000 null
I/BatteryService(  951): n_update end
D/PMS     (  951): releaseWL(28894c85): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HeadsetStateMachine( 3147): Disconnected process message: 10, size: 0
D/NotificationService(  951): plugged=true pluggin=true
D/UsbnetService(  951): BroadcastReceiver::onReceive+
D/WifiController(  951): battery changed pluggedType: 2
D/UsbnetService(  951): onReceive BATTERY_CHANGED
D/UsbnetService(  951):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  951): BroadcastReceiver::onReceive-
D/WifiController(  951): handleMessage: E msg.what=155652
D/WifiController(  951): processMsg: DeviceActiveState
D/WifiController(  951): processMsg: StaEnabledState
D/WifiController(  951): processMsg: DefaultState
D/WifiController(  951): handleMessage: X
,D/HtcPowerSaver(  951): updateBatteryInfo
D/PMS     (  951): runPSCheck
D/DotMatrix( 1350): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  951): Checking...
D/DotMatrix( 1350): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  951): >> updateStatus
D/DotMatrix( 1350): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1244): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1244): closing low battery warning: level=100
,I/HtcPowerSaver(  951): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  951): << updateStatus
D/PowerUI ( 1244): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1244): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  951): acquireWL(ba44ada): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 951 1000 null
I/BatteryService(  951): n_update end
D/UsbnetService(  951): BroadcastReceiver::onReceive+
D/PMS     (  951): releaseWL(ba44ada): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  951): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  951): updateBatteryInfo
D/UsbnetService(  951):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  951): plugged=true pluggin=true
D/UsbnetService(  951): BroadcastReceiver::onReceive-
D/WifiController(  951): battery changed pluggedType: 2
D/WifiController(  951): handleMessage: E msg.what=155652
D/PowerUI ( 1244): closing low battery warning: level=100
D/WifiController(  951): processMsg: DeviceActiveState
D/PowerUI ( 1244): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  951): processMsg: StaEnabledState
D/PMS     (  951): runPSCheck
D/WifiController(  951): processMsg: DefaultState
D/HtcPowerSaver(  951): Checking...
D/WifiController(  951): handleMessage: X
I/HtcPowerSaver(  951): >> updateStatus
D/HeadsetStateMachine( 3147): Disconnected process message: 10, size: 0
D/DotMatrix( 1350): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1350): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1350): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1244): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  951): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  951): << updateStatus
,I/BatteryController( 1244): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  951): acquireWL(25e7b0b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 951 1000 null
I/BatteryService(  951): n_update end
D/PMS     (  951): releaseWL(25e7b0b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1244): receive(android.intent.action.BATTERY_CHANGED,1,false),
D/DotMatrix( 1350): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1244): closing low battery warning: level=100
D/HeadsetStateMachine( 3147): Disconnected process message: 10, size: 0
D/NotificationService(  951): plugged=true pluggin=true
D/DotMatrix( 1350): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1244): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1350): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  951): battery changed pluggedType: 2
D/UsbnetService(  951): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  951): updateBatteryInfo
D/UsbnetService(  951): onReceive BATTERY_CHANGED
D/PMS     (  951): runPSCheck
D/UsbnetService(  951):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  951): Checking...
D/UsbnetService(  951): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  951): >> updateStatus
D/WifiController(  951): handleMessage: E msg.what=155652
,D/WifiController(  951): processMsg: DeviceActiveState
D/WifiController(  951): processMsg: StaEnabledState
D/WifiController(  951): processMsg: DefaultState
D/WifiController(  951): handleMessage: X
,I/HtcPowerSaver(  951): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  951): << updateStatus
,I/BatteryController( 1244): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  951): acquireWL(139ede8): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 951 1000 WorkSource{1000}
V/AlarmManager(  951): sending alarm PendingIntent{3636d3f9: PendingIntentRecord{35844f3e android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=386897, Int=0
V/AlarmManager(  951): sending alarm PendingIntent{34e10c6: PendingIntentRecord{307da887 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=804744, Int=0
V/AlarmManager(  951): sending alarm PendingIntent{15972c01: PendingIntentRecord{a8c3aa6 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=940554, Int=0
,I/ActivityManager(  951): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6808 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
V/AlarmManager(  951): sending alarm PendingIntent{39f7bce7: PendingIntentRecord{2bb40094 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1454984112098, Int=0
,I/bt-btm  ( 3147): Received oneshot timer event complete
D/PMS     (  951): acquireWL(3a49873d): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3147 1002 null
I/bt-btm  ( 3147): btm_ble_timeout
I/bt-btm  ( 3147): btm_gen_resolvable_private_addr
,D/bt-btm  ( 3147): btm_ble_rand_enc_complete
I/bt-btm  ( 3147): btm_gen_resolve_paddr_low
D/bt-smp  ( 3147): smp_encrypt_data
,W/bt-smp  ( 3147): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3147): Plain text(LSB ~ MSB) = 54 35 79 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3147): Encrypted text(LSB ~ MSB) = 95 ed e4 41 66 46 28 94 2b 18 4b e4 3f 19 6e a2 
I/bt-btm  ( 3147): btm_gen_resolve_paddr_cmpl,
W/bt-btm  ( 3147): Stopping oneshot timer
D/bt-btm  ( 3147): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  951): releaseWL(139ede8): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1244): Weather sync is On
,W/WeatherTimeKeeper( 1244): [refreshWeatherData] no weather data
,E/cutils-trace( 6829): Error opening trace file: Permission denied (13),
I/dex2oat ( 6829): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6829): dex2oat: override thread count:4
,I/dex2oat ( 6829): dex2oat took 686.811ms (threads: 4),
,I/PushClient( 6808): ApplicationMonitor {f513603}: logBasicAppInfo(): PackageName:             com.htc.cs.pns,
,I/PushClient( 6808): ApplicationMonitor {f513603}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns,
,I/PushClient( 6808): ApplicationMonitor {f513603}: logBasicAppInfo(): VersionName:             1.2.853019
,I/PushClient( 6808): ApplicationMonitor {f513603}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6808): ApplicationMonitor {f513603}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 6808): ApplicationMonitor {f513603}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 6808): ApplicationMonitor {f513603}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6808): ApplicationMonitor {f513603}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6808): ApplicationMonitor {f513603}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6808): PnsModel {2641b6b2}: update(): Update registration caused by: alarm
,I/PushClient( 6808): PnsConfigModel {1a7978f1}: <init>(): Use dm-client for provisioning.
,D/PMS     (  951): releaseWL(3a49873d): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,W/System.err( 6808): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 6808): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6808): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6808): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  951): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6837 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/art     (  407): Explicit concurrent mark sweep GC freed 8644(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 490us total 54.024ms
,I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 169us total 22.117ms,
,I/DeviceManagement( 6837): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6837 dbg=false s=true,
I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 166us total 25.050ms
,I/DeviceManagement( 6837): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL],
I/DeviceManagement( 6837): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6837): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
,I/DeviceManagement( 6837): WorkflowService: Starting workflow service
,I/DeviceManagement( 6837): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@29bc20bd] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6837): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6837): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6837): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6837): SessionStateController: Checking invariants...
,I/DeviceManagement( 6837): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6837): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6837): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6837): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@29bc20bd],
,I/DeviceManagement( 6837): WorkflowService: Stopping workflow service
,D/Process (  951): killProcessQuiet, pid=6464
I/ActivityManager(  951): Killing 6464:com.test.thalitest/u0a366 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  951): Recipient 6464,
E/InputEventReceiver( 1426): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{335a816a uid 10366 pid 6464} (c)'
,I/PushClient( 6808): PnsModel {2641b6b2}: update(): The registration record has not expired yet. No need to update.,
,D/Process (  951): killProcessQuiet, pid=6439,
I/ActivityManager(  951): Killing 6439:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  951): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  951): Recipient 6439
,D/PMS     (  951): acquireWL(35ae9956): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 951 1000 null
I/BatteryService(  951): n_update end
D/PMS     (  951): releaseWL(35ae9956): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1244): closing low battery warning: level=100
D/UsbnetService(  951): BroadcastReceiver::onReceive+
D/UsbnetService(  951): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  951): updateBatteryInfo
D/UsbnetService(  951):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  951): plugged=true pluggin=true
D/UsbnetService(  951): BroadcastReceiver::onReceive-
D/PMS     (  951): runPSCheck
,D/WifiController(  951): handleMessage: E msg.what=155652
D/HtcPowerSaver(  951): Checking...
D/WifiController(  951): processMsg: DeviceActiveState
I/HtcPowerSaver(  951): >> updateStatus
D/WifiController(  951): processMsg: StaEnabledState
D/PowerUI ( 1244): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  951): processMsg: DefaultState
D/WifiController(  951): battery changed pluggedType: 2
D/WifiController(  951): handleMessage: X
I/IntentController( 1244): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1350): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1350): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1350): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3147): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  951): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  951): << updateStatus
,I/BatteryController( 1244): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  951): acquireWL(3c93add7): PARTIAL_WAKE_LOCK  *alarm* 0x1 951 1000 WorkSource{10024},
V/AlarmManager(  951): sending alarm PendingIntent{1522b6c4: PendingIntentRecord{330fb9ad com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=936521, Int=0
V/AlarmManager(  951): sending alarm PendingIntent{1112f4e2: PendingIntentRecord{18f7e1b8 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1454984500915, Int=0
D/PMS     (  951): acquireWL(147b5073): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1854 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): releaseWL(147b5073): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 6712): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  951): releaseWL(3c93add7): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PowerUsageList:PowerUsageHelper( 6712): MY_DEBUG = false
,D/PowerUsageService( 6712): repeat time = 1454985400961
,D/GCM     ( 1854): Message class com.google.f.a.a.i,
D/PMS     (  951): acquireWL(379b43a9): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1854 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  951): releaseWL(379b43a9): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,I/PowerUsageList:PowerUsageHelper( 6712): PowerProfile::POWER_SCREEN_FULL = 154.8,
,D/PowerUsageList:BatterySipperExt( 6712): gen(), null == sipper.uidObj, userId = 0,
,D/PMS     (  951): acquireWL(396f7d2e): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 951 1000 WorkSource{1000},
V/AlarmManager(  951): sending alarm PendingIntent{3636d3f9: PendingIntentRecord{35844f3e android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=986897, Int=0
V/AlarmManager(  951): sending alarm PendingIntent{2c3080cf: PendingIntentRecord{7001a5c com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1454984546738, Int=0
,D/SmartSyncUtils( 6712): isEpsOn(), nState = 0
,D/PMS     (  951): acquireWL(23b7165): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6712 1000 null,
,D/PMS     (  951): releaseWL(396f7d2e): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 6712): [updateNmRange] bManual = false,
,D/SmartSyncScreenOnOffTimeReceiver( 6712): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/WeatherUtility( 1244): Weather sync is On
,W/WeatherTimeKeeper( 1244): [refreshWeatherData] no weather data
,D/SmartSyncScreenOnOffTimeReceiver( 6712): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 6712): SettingOnTime = 1454997600000, randomSettingOnTime = 1454996092000
,D/SmartSyncScreenOnOffTimeReceiver( 6712): SettingOffTime = 1455062400000, randomSettingOffTime = 1455066845000
,D/SmartSyncScreenOnOffTimeReceiver( 6712): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 6712): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 6712): bNightModeTurnOffOnce = false
,D/PMS     (  951): acquireWL(28fa3e3a): PARTIAL_WAKE_LOCK  *alarm* 0x1 951 1000 WorkSource{1000},
V/AlarmManager(  951): sending alarm PendingIntent{c5e5aeb: PendingIntentRecord{a28048 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_TURN_OFF_NETWORK_BY_CHECK, t=0, cnt=1, w=1454984546785, Int=0
,D/PMS     (  951): releaseWL(23b7165): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,W/ContextImpl( 6712): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/SmartSyncDataLinkTurnOffService( 6712): SMARTSYNC_TURN_OFF_NETWORK, current time = 1454984546807, randomOffTime = 1455066845000, newRandomOffTime = 1455066845000,
,D/SmartSyncDataLinkTurnOffService( 6712): SMARTSYNC_TURN_OFF_NETWORK, randomWifiOnTime = 1454996092000, randomMobileOnTime = 1454996092000,
,D/SmartSyncUtils( 6712): getMobilePolicyEnabled, result = true
,D/SmartSyncDataLinkTurnOffService( 6712): turnOffMobile bPolicyEnabled = true
,D/SmartSyncUtils( 6712): isWifiHotSpotEnabled = false
D/PMS     (  951): releaseWL(28fa3e3a): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/SmartSyncDataLinkTurnOffService( 6712): turnOffMobile bCheckMobileData = false,
,D/LocationManagerService(  951): getProviders()=[gps, network],
D/LocationManagerService(  951): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
,D/LocationManagerService(  951): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1],
,D/SmartSyncDataLinkTurnOffService( 6712): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0
,D/SmartSyncUtils( 6712): isCharging status = 5
,D/SmartSyncDataLinkTurnOffService( 6712): turnOffWifi ui setting = true,
,D/SmartSyncUtils( 6712): isWifiHotSpotEnabled = false
,I/ActivityManager(  951): Cannot resolve ContentProvider=com.htc.vowifi,
D/SmartSyncUtils( 6712): state = 0
E/ActivityThread( 6712): Failed to find provider info for com.htc.vowifi
,D/SmartSyncDataLinkTurnOffService( 6712): turnOffWifi bCheckWifiData = true
,D/SmartSyncDataLinkTurnOffService( 6712): turnOffWifi bWifiConnected = true
,D/PMS     (  951): acquireWL(153e0406): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 951 1000 null
I/BatteryService(  951): n_update end
D/PMS     (  951): releaseWL(153e0406): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  951): updateBatteryInfo
D/PMS     (  951): runPSCheck
D/HtcPowerSaver(  951): Checking...
I/HtcPowerSaver(  951): >> updateStatus
D/PowerUI ( 1244): closing low battery warning: level=100
D/PowerUI ( 1244): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1244): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1350): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1350): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1350): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HeadsetStateMachine( 3147): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  951): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  951): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  951): << updateStatus
,D/UsbnetService(  951): onReceive BATTERY_CHANGED
D/NotificationService(  951): plugged=true pluggin=true
D/UsbnetService(  951):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  951): battery changed pluggedType: 2
D/UsbnetService(  951): BroadcastReceiver::onReceive-
D/WifiController(  951): handleMessage: E msg.what=155652
D/WifiController(  951): processMsg: DeviceActiveState,
D/WifiController(  951): processMsg: StaEnabledState
D/WifiController(  951): processMsg: DefaultState
D/WifiController(  951): handleMessage: X
,I/BatteryController( 1244): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  951): acquireWL(1345bac7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 951 1000 null
I/BatteryService(  951): n_update end
D/PMS     (  951): releaseWL(1345bac7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1350): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  951): updateBatteryInfo
D/HeadsetStateMachine( 3147): Disconnected process message: 10, size: 0
D/NotificationService(  951): plugged=true pluggin=true
D/DotMatrix( 1350): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  951): runPSCheck
D/DotMatrix( 1350): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  951): Checking...
D/UsbnetService(  951): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  951): >> updateStatus
D/UsbnetService(  951): onReceive BATTERY_CHANGED
D/PowerUI ( 1244): closing low battery warning: level=100
D/UsbnetService(  951):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  951): battery changed pluggedType: 2
D/UsbnetService(  951): BroadcastReceiver::onReceive-
D/WifiController(  951): handleMessage: E msg.what=155652
D/WifiController(  951): processMsg: DeviceActiveState
I/IntentController( 1244): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  951): processMsg: StaEnabledState
D/WifiController(  951): processMsg: DefaultState
D/WifiController(  951): handleMessage: X
,D/PowerUI ( 1244): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  951): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  951): << updateStatus
,I/BatteryController( 1244): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  951): acquireWL(308358f4): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 951 1000 WorkSource{1000}
V/AlarmManager(  951): sending alarm PendingIntent{3636d3f9: PendingIntentRecord{35844f3e android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1046897, Int=0
V/AlarmManager(  951): sending alarm PendingIntent{2dbf681d: PendingIntentRecord{2fa65a92 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_TURN_OFF_WIFI_RETRY, t=0, cnt=1, w=1454984726884, Int=0
W/ContextImpl( 6712): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 ,
,D/SmartSyncDataLinkTurnOffService( 6712): turnOffWifi ui setting = true
,D/SmartSyncUtils( 6712): isWifiHotSpotEnabled = false
I/ActivityManager(  951): Cannot resolve ContentProvider=com.htc.vowifi
D/PMS     (  951): releaseWL(308358f4): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/SmartSyncUtils( 6712): state = 0
,E/ActivityThread( 6712): Failed to find provider info for com.htc.vowifi
D/SmartSyncDataLinkTurnOffService( 6712): turnOffWifi bCheckWifiData = false
D/SmartSyncDataLinkTurnOffService( 6712): turnOffWifi bWifiConnected = true
D/LocationManagerService(  951): getProviders()=[gps, network]
D/LocationManagerService(  951): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
,D/LocationManagerService(  951): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/WeatherUtility( 1244): Weather sync is On
D/SmartSyncDataLinkTurnOffService( 6712): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0
,W/WeatherTimeKeeper( 1244): [refreshWeatherData] no weather data
D/SmartSyncUtils( 6712): isCharging status = 5
,D/PMS     (  951): acquireWL(25f71060): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 951 1000 null,
I/BatteryService(  951): n_update end
D/PMS     (  951): releaseWL(25f71060): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/NotificationService(  951): plugged=true pluggin=true
D/UsbnetService(  951): BroadcastReceiver::onReceive+
D/WifiController(  951): battery changed pluggedType: 2
D/UsbnetService(  951): onReceive BATTERY_CHANGED
,D/HtcPowerSaver(  951): updateBatteryInfo
D/UsbnetService(  951):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  951): runPSCheck
D/UsbnetService(  951): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  951): Checking...
D/WifiController(  951): handleMessage: E msg.what=155652
I/HtcPowerSaver(  951): >> updateStatus
D/WifiController(  951): processMsg: DeviceActiveState,
D/PowerUI ( 1244): closing low battery warning: level=100
D/WifiController(  951): processMsg: StaEnabledState
D/PowerUI ( 1244): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  951): processMsg: DefaultState
I/HtcPowerSaver(  951): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  951): handleMessage: X
I/HtcPowerSaver(  951): << updateStatus
I/IntentController( 1244): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1350): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/DotMatrix( 1350): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1350): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3147): Disconnected process message: 10, size: 0
,I/BatteryController( 1244): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  388): inotify_add_watch failed. (No such file or directory),
,I/UsageStatsService(  951): User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1200000ms)
```
