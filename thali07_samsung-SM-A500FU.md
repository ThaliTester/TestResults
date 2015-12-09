#### Test 506502789252e15_thali07_samsung-SM-A500FU Logs


```
--------- beginning of main
E/CscParser( 5022): mps_code.dat does not exist
E/CscParser( 5022): customer_path =/system/csc/customer.xml
E/CscParser( 5022): fileName + /system/csc/customer.xml
D/CscParser( 5022): getInstance fileName =/system/csc/customer.xml
D/Mms/MmsConfig( 5022):  enable multiwindow = true
E/Mms/MessageUtils( 5022): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 5022): updateCountryIso : update country iso info 
D/Mms/MmsConfig( 5022): [end]    init() consume time = 134.530938
D/Mms/Contact( 5022): [start]    init() consume time = 0.552135
D/TP/MmsSmsProvider( 1464): query,matched:13, calling pid = 5022
D/Mms/Contact( 5022): [end]    init consume time = 14.697552
D/TP/MmsSmsProvider( 1464): match 13:Elapsed time : 1.157 ms
D/Mms/DraftCache( 5022): [start]    rebuildCache consume time = 11.186875
D/TP/MmsSmsProvider( 1464): query,matched:12, calling pid = 5022
D/Mms/MethodReflector( 5022): getSubId is called
D/Mms/TelephonyUtils( 5022): getLongSubId from simSlot 0, return Value = -1
D/TP/MmsSmsProvider( 1464): match 12:Elapsed time : 2.871 ms
W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/Mms/MethodReflector( 5022): getTelephonyProperty is called
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Mms/DownloadManager( 5022): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5022): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5022): auto download without roaming -> true
D/Mms/DownloadManager( 5022): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
I/ConfigFetchService( 1833): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
D/Mms/MethodReflector( 5022): getSubId is called
--------- beginning of system
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/Mms/MethodReflector( 5022): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 5022): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 5022): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 5022): getTelephonyProperty is called
D/Mms/DownloadManager( 5022): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 5022): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 5022): auto download without roaming -> true
D/Mms/DownloadManager( 5022): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 5022): auto download during roaming secondary -> false
D/Mms/DownloadManager( 5022): mAutoDownload ------> true
I/ConfigFetchService( 1833): launchTask
D/Mms/DraftCache( 5022): [end]    rebuildCache consume time = 24.171354
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ChimeraCfgMgr( 1833): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1833): Module APK com.google.android.play.games already loaded
D/ComposerPerformance( 5022): 1449683604180 ms / [DONE] Composer constructor
E/CII     ( 5022): CommonIMSInterface: VoLTE CSC feature disabled.
I/Mms/ReservationManager( 5022): ReservationManager()
I/Mms/ReservationManager( 5022): resetAfterConnected()
D/TP/MmsSmsProvider( 1464): query,matched:7, calling pid = 5022
D/TP/MmsSmsProvider( 1464): match 7:Elapsed time : 2.638 ms
D/Mms/Conversation( 5022): [start]    init() consume time = 18.631302
I/Mms/ReservationManager( 5022): getReservedSendMessageCount(): retMessageCount=0
D/TP/MmsSmsProvider( 1464): deleteConversation threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1464): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1464): updateThread(), thread_id = 9223372036854775807
V/TP/MmsSmsDatabaseHelper( 1464): sUpgradeVersion = 0, db.getVersion() = 81
D/TP/MmsSmsProvider( 1464): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1464): need read changed broadcast:false
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/Mms/MmsApp( 5022): [end]    onCreate() consume time = 10.911094
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Mms/Conversation( 5022): [end]    init consume time = 1.390625
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
D/Mms/MessagingNotification( 5022): [start]    init() consume time = 1.503594
D/Mms/MessagingNotification( 5022): [end]    init consume time = 1.982552
D/Mms/ArtClassLoader( 5022): init [DONE] art
D/TP/MmsSmsProvider( 1464): query,matched:0, calling pid = 5022
V/TP/MmsSmsProvider( 1464): getSimpleConversations entered.
D/TP/MmsSmsProvider( 1464): match 0:Elapsed time : 0.940 ms
V/ConfigFetchTask( 1833): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1XthS64CiQjYy6hQB7nj3mphv59HZNQhVEMJJjEXvjeEJ-0vghaIXNVJGGU917qOXpLXpJufG9HqqAUJDWfWySzOOeGnGFjWjmz9jAce_1L21WAgU9_sXUOx5nYGK8T_DKW5Pa4PMcJXECh-DLOcoGljfx5_2L_r80mbie96IuDgZxohgax2aqR8TxQUYrusDCxbOfmDt3xyCLWWiXDiwMZugNHEP-NBWT0xVlfo22zyngyZRI
D/ChimeraCfgMgr( 1833): Loading module com.google.android.gms.vision from APK com.google.android.gms
I/PeopleContactsSync( 1833): CP2 sync disabled
D/Vision  ( 1833): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1833): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1833): No vision deps
D/Mms/DownloadManager( 5022): Service state changed: Bundle[mParcelledData.dataSize=744]
D/Mms/DownloadManager( 5022): roaming ------> false, mSimSlot = 0
D/Mms/MethodReflector( 5022): getSubId is called
D/Mms/TelephonyUtils( 5022): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 5022): getTelephonyProperty is called
D/Mms/DownloadManager( 5022): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5022): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5022): auto download without roaming -> true
D/Mms/DownloadManager( 5022): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5022): mAutoDownload ------> true
I/GoogleURLConnFactory( 1833): Using platform SSLCertificateSocketFactory
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
D/Mms/Synchronizer( 5022): [start]    doSync consume time = 30.324583
D/Mms/SpamFilter( 5022): [start]    SpamFilter fill() begin consume time = 3.771354
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TP/MmsSmsProvider( 1464): update, matched:300, calling pid = 5022
V/TP/MmsSmsProvider( 1464): syncDBData start
V/TP/MmsSmsProvider( 1464): syncDBData sms end
V/TP/MmsSmsProvider( 1464): syncDBData mms end
V/TP/MmsSmsProvider( 1464): syncDBData end
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5201): MountEmulatedStorage()
I/libpersona( 5201): KNOX_SDCARD checking this for 10072
E/Zygote  ( 5201): v2
I/libpersona( 5201): KNOX_SDCARD not a persona
I/SELinux ( 5201): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5201 uid=10072 gids={50072, 9997} abi=armeabi-v7a
D/Mms/Synchronizer( 5022): [end]    doSync consume time = 21.582917
I/SELinux ( 5201): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5201): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/TP/MmsSmsProvider( 1464): query,matched:400, calling pid = 5022
D/Mms/SpamFilter( 5022): [end]    SpamFilter fill() finished consume time = 13.732448
D/TimaKeyStoreProvider( 5201): TimaSignature is unavailable
D/ActivityThread( 5201): Added TimaKeyStore provider
D/BadgeProvider( 5201): onCreate
D/BadgeProvider( 5201): DatabaseHelper
D/Mms/MessagingNotification( 5022): checkBadgeCount unreadCount=0 badgeCount=0
D/TP/SmsProvider( 1464): query,matched:26, calling pid = 5022
D/TP/SmsProvider( 1464): match 26:Elapsed time : 1.368 ms
D/TP/MmsSmsProvider( 1464): query,matched:6, calling pid = 5022
D/TP/MmsSmsProvider( 1464): match 6:Elapsed time : 1.316 ms
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/System.out( 1833): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1833): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1833): (HTTPLog)-Static: isShipBuild true
I/System.out( 1833): (HTTPLog)-Thread-240-662877855: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/libpersona( 5219): KNOX_SDCARD checking this for 10025
I/System.out( 1833): (HTTPLog)-Static: isSBSettingEnabled false
I/libpersona( 5219): KNOX_SDCARD not a persona
E/Zygote  ( 5219): MountEmulatedStorage()
E/Zygote  ( 5219): v2
D/Mms/FreeMessageStatusReceiver( 5022): onReceive, action : android.intent.action.PACKAGE_ADDED
I/SELinux ( 5219): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5219): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1016): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5219 uid=10025 gids={50025, 9997} abi=armeabi-v7a
D/EnterpriseController(  277): uids 10012
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 10012
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
E/SELinux ( 5219): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ConfigFetchTask( 1833): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/art     (  311): Explicit concurrent mark sweep GC freed 8750(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 637us total 24.840ms
D/TimaKeyStoreProvider( 5219): TimaSignature is unavailable
D/ActivityThread( 5219): Added TimaKeyStore provider
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/ConfigFetchService( 1833): fetch service done; releasing wakelock
I/ConfigFetchService( 1833): stopping self
I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 615us total 17.012ms
I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 610us total 18.587ms
E/Zygote  ( 5239): MountEmulatedStorage()
E/Zygote  ( 5239): v2
I/libpersona( 5239): KNOX_SDCARD checking this for 10047
I/libpersona( 5239): KNOX_SDCARD not a persona
I/SELinux ( 5239): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5239): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5239): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5239 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
D/TimaKeyStoreProvider( 5239): TimaSignature is unavailable
D/ActivityThread( 5239): Added TimaKeyStore provider
W/ResourcesManager( 5219): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/Mms/FreeMessageReceiverService( 5022): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 5022): onHandleIntent: ACTION_PACKAGE_ADDED
I/ActivityManager( 1016): Killing 3518:com.android.providers.calendar/u0a42 (adj 15): empty #31
I/ActivityManager( 1016): Killing 4245:com.samsung.android.app.mirrorlink/1000 (adj 15): empty #32
W/ResourcesManager( 5239): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5239): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5239): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/SL_DEBUG( 5154): isLoggable:: isProductShip = 1
I/SL_DEBUG( 5154): isLoggable:: SL_DEBUG_EXIST = false
D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4141, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/OMACP   ( 5219): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
W/BaseAppContext( 1833): Using Auth Proxy for data requests.
W/BaseAppContext( 1833): Using Auth Proxy for data requests.
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
W/libprocessgroup( 1016): failed to open /acct/uid_10042/pid_3518/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_4245/cgroup.procs: No such file or directory
D/Mms/Omacp( 5022): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
I/GAv4    ( 5037): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5037):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5037):   adb logcat -s GAv4
W/BaseAppContext( 1833): Using Auth Proxy for data requests.
I/OMACP   ( 5219): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
I/OMACP   ( 5219): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
I/OMACP   ( 5219): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
I/OMACP   ( 5219): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
I/OMACP   ( 5219): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
I/OMACP   ( 5219): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
I/OMACP   ( 5219): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
W/BaseAppContext( 1833): Using Auth Proxy for data requests.
I/OMACP   ( 5219): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
I/OMACP   ( 5219): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
I/OMACP   ( 5219): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
W/GAv4    ( 5037): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
I/OMACP   ( 5219): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
I/OMACP   ( 5219): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
I/OMACP   ( 5219): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
W/BaseAppContext( 1833): Using Auth Proxy for data requests.
W/GAv4    ( 5037): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 5037): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
W/GAv4    ( 5037): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/BaseAppContext( 1833): Using Auth Proxy for data requests.
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5154): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
D/MyFiles ( 5239): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
E/installd(  286): system dir 0 : /system/app/
E/installd(  286): system dir 1 : /system/priv-app/
E/installd(  286): system dir 2 : /vendor/app/
E/installd(  286): system dir 3 : /oem/app/
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
I/TactileAssist( 1016): enable value -1
I/TactileAssist( 1016): internal enable value -1
I/TactileAssist( 1016): intensity value -1
I/TactileAssist( 1016): saveAppList value true
I/TactileAssist( 1016): List of disabled apps :
D/PackageManager( 1016): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5268): MountEmulatedStorage()
E/Zygote  ( 5268): v2
I/libpersona( 5268): KNOX_SDCARD checking this for 10053
I/libpersona( 5268): KNOX_SDCARD not a persona
I/SELinux ( 5268): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5268): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5268): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=5268 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
D/TimaKeyStoreProvider( 5268): TimaSignature is unavailable
D/ActivityThread( 5268): Added TimaKeyStore provider
W/ResourcesManager( 5268): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5154): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
E/SMD     (  290): DCD OFF
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/Compatibility( 5268): onReceive() it will make start service
E/Zygote  ( 5287): MountEmulatedStorage()
E/Zygote  ( 5287): v2
I/libpersona( 5287): KNOX_SDCARD checking this for 10041
I/libpersona( 5287): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=5287 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 5287): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
I/SELinux ( 5287): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/Compatibility( 5268): onHandleIntent()
D/Compatibility( 5268): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10175, android.intent.extra.user_handle=0}]
E/SELinux ( 5287): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/Compatibility( 5268): found: 2
E/Zygote  ( 5298): MountEmulatedStorage()
E/Zygote  ( 5298): v2
I/libpersona( 5298): KNOX_SDCARD checking this for 1000
I/libpersona( 5298): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=5298 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 5298): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5298): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5298): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Compatibility( 5268): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5268): skipping ResolveInfo{3790d273 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5268): considering ResolveInfo{bad530 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5268): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/TimaKeyStoreProvider( 5287): TimaSignature is unavailable
D/ActivityThread( 5287): Added TimaKeyStore provider
D/Compatibility( 5268): enabling receiver ResolveInfo{fa195a9 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/TimaKeyStoreProvider( 5298): TimaSignature is unavailable
D/ActivityThread( 5298): Added TimaKeyStore provider
D/Compatibility( 5268): enabling receiver ResolveInfo{d1c672e com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 5268): enabling receiver ResolveInfo{381c22cf com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 5268): enabling receiver ResolveInfo{31b0145c com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 5268): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,I/ActivityManager( 1016): Killing 4709:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
I/SA      ( 5287): [SSP] onCreated
W/ContextImpl( 5298): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5324): MountEmulatedStorage()
E/Zygote  ( 5324): v2
I/libpersona( 5324): KNOX_SDCARD checking this for 1000
I/libpersona( 5324): KNOX_SDCARD not a persona
I/SELinux ( 5324): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5324): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1016): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=5324 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 5324): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1016): failed to open /acct/uid_10069/pid_4709/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 5324): TimaSignature is unavailable
D/ActivityThread( 5324): Added TimaKeyStore provider
I/ActivityManager( 1016): Killing 4724:com.sec.knox.bridge/1000 (adj 15): empty #31
W/ResourcesManager( 5324): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
I/ActivityManager( 1016): Killing 4740:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
I/ActivityManager( 1016): Killing 4816:com.google.android.apps.plus/u0a120 (adj 15): empty #31
E/JavaBinder( 1016): !!! FAILED BINDER TRANSACTION !!!
W/BroadcastQueue( 1016): Exception when sending broadcast to ComponentInfo{com.sec.knox.bridge/com.sec.knox.bridge.PersonaShortcutReceiver}
W/BroadcastQueue( 1016): android.os.TransactionTooLargeException
W/BroadcastQueue( 1016): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue( 1016): 	at android.os.BinderProxy.transact(Binder.java:511)
W/BroadcastQueue( 1016): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
W/BroadcastQueue( 1016): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:309)
W/BroadcastQueue( 1016): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1236)
W/BroadcastQueue( 1016): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20387)
W/BroadcastQueue( 1016): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
W/BroadcastQueue( 1016): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3368)
W/BroadcastQueue( 1016): 	at android.os.Binder.execTransact(Binder.java:461)
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1016): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=5342 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 5342): MountEmulatedStorage()
I/libpersona( 5342): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5342): v2
I/libpersona( 5342): KNOX_SDCARD not a persona
I/SELinux ( 5342): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5342): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5342): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5342): TimaSignature is unavailable
D/ActivityThread( 5342): Added TimaKeyStore provider
I/ActivityManager( 1016): Killing 4173:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
W/ResourcesManager( 5342): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/SA      ( 5287): [TPM] There is no property file
I/SA      ( 5287): [SCU] isHaveSA() - false
I/SA      ( 5287): [TPM] getModelProperty : null
I/SA      ( 5287): [TPM] getCSCProperty : null
I/SA      ( 5287): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 5287): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 5287): [DM] TFT FEATURE: false
I/SA      ( 5287): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 5287): [DM] init START
W/ResourcesManager( 5037): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5037): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/SA      ( 5287): [DM] This device is not a Vodafone
D/AndroidRuntime( 5322): 
D/AndroidRuntime( 5322): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5322): CheckJNI is OFF
W/ResourceType( 5287): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
D/AndroidRuntime( 5322): readGMSProperty: start
D/AndroidRuntime( 5322): readGMSProperty: already setted!!
D/AndroidRuntime( 5322): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5322): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5322): readGMSProperty: end
D/AndroidRuntime( 5322): addProductProperty: start
W/ResourceType( 5287): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 5287): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 5287): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 5287): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 5287): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 5287): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
I/ActivityManager( 1016): Killing 4790:com.google.android.gms:car/u0a12 (adj 15): empty #31
W/ResourceType( 5287): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 5287): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 5287): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 5287): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 5287): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 5287): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 5287): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 5287): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 5287): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 5287): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
W/ResourceType( 5287): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 5287): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 5287): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 5287): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 5287): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 5287): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 5287): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 5287): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
I/SA      ( 5287): [SCU] isHaveSA() - false
I/SA      ( 5287): support phone number id : false
I/SA      ( 5287): [DM] Supports Ref Jpn : true
I/SA      ( 5287): [DM] init END
I/SA      ( 5287): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
I/SA      ( 5287): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10175 extra.user_handle.:0 ]
I/ActivityManager( 1016): Killing 4464:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
I/art     ( 1016): Explicit concurrent mark sweep GC freed 217614(14MB) AllocSpace objects, 3(4MB) LOS objects, 33% free, 26MB/40MB, paused 3.548ms total 226.188ms
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
W/ContextImpl( 5037): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.docs/cache
V/JNIHelp ( 5037): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/ActivityManager( 1016): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PhotosAppTransitionMonitor: pid=5368 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 5368): MountEmulatedStorage()
W/ActivityManager( 1016): Scheduling restart of crashed service com.google.android.gms/.car.InCallServiceImpl in 1000ms
E/Zygote  ( 5368): v2
I/libpersona( 5368): KNOX_SDCARD checking this for 10120
I/libpersona( 5368): KNOX_SDCARD not a persona
I/SELinux ( 5368): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5368): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5368): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
W/ActivityThread( 5037): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5037): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2268b5f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5037): Installed default security provider GmsCore_OpenSSL
D/TimaKeyStoreProvider( 5368): TimaSignature is unavailable
D/ActivityThread( 5368): Added TimaKeyStore provider
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_4724/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_4740/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10057/pid_4173/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10120/pid_4816/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10012/pid_4790/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10150/pid_4464/cgroup.procs: No such file or directory
W/ResourcesManager( 5368): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/AffinityControl( 5322): AffinityControl: registerfunction enter
D/ChimeraCfgMgr( 1833): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1833): Module APK com.google.android.play.games already loaded
D/AndroidRuntime( 5322): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1016): inState():  stateMachine is null !!
I/PersonaManagerService( 1016): PersonaId don't exist
I/ActivityManager( 1016): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/ActivityManager( 1016): mDVFSHelper.acquire()
D/FocusedStackFrame( 1016): Set to : 0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1016): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1016): *FMB* installDecor flags : 25362712
E/Zygote  ( 5394): MountEmulatedStorage()
E/Zygote  ( 5394): v2
I/libpersona( 5394): KNOX_SDCARD checking this for 10175
I/libpersona( 5394): KNOX_SDCARD not a persona
I/SELinux ( 5394): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5394 uid=10175 gids={50175, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1016): Focused application set to: xxxx
D/InputDispatcher( 1016): Focus left window: 1489
D/AndroidRuntime( 5322): Shutting down VM
I/SELinux ( 5394): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
D/PhoneWindow( 1016): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1016): *FMB* isFloatingMenuEnabled return false
E/SELinux ( 5394): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1016): userId = 0, bbcId = -10000
I/SurfaceFlinger(  256): id=11 createSurf (1x1),1 flag=404, uhalitest
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 5394): TimaSignature is unavailable
D/ActivityThread( 5394): Added TimaKeyStore provider
V/WindowManager( 1016): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/ActivityManager( 1016): Display changed displayId=0
D/StatusBarManagerService( 1016): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1016): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1016):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  256): id=8 Removed Mauncher (5/9)
I/SurfaceFlinger(  256): id=8 Removed Mauncher (-2/9)
V/ActivityThread( 1489): updateVisibility : ActivityRecord{395b8116 token=android.os.BinderProxy@2409a8ff {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1489): onTrimMemory. Level: 20
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5412): MountEmulatedStorage()
E/Zygote  ( 5412): v2
I/libpersona( 5412): KNOX_SDCARD checking this for 10057
I/libpersona( 5412): KNOX_SDCARD not a persona
I/SELinux ( 5412): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5412 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
I/SELinux ( 5412): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5412): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Killing 4080:com.google.android.gm/u0a101 (adj 15): empty #31
D/TimaKeyStoreProvider( 5412): TimaSignature is unavailable
D/ActivityThread( 5412): Added TimaKeyStore provider
W/art     ( 5322): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
I/WebViewFactory( 5394): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,I/LibraryLoader( 5394): Time to load native libraries: 2 ms (timestamps 7182-7184)
I/LibraryLoader( 5394): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5394): Binding Chromium to main looper Looper (main, tid 1) {381c22cf}
,I/LibraryLoader( 5394): Expected native library version number "",actual native library version number ""
,I/chromium( 5394): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5430): MountEmulatedStorage()
I/libpersona( 5430): KNOX_SDCARD checking this for 10010
E/Zygote  ( 5430): v2
I/libpersona( 5430): KNOX_SDCARD not a persona
,I/SELinux ( 5430): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 5430): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 5430): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
,W/libprocessgroup( 1016): failed to open /acct/uid_10101/pid_4080/cgroup.procs: No such file or directory
,I/ActivityManager( 1016): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=5430 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/BrowserStartupController( 5394): Initializing chromium process, singleProcess=true
,W/art     ( 5394): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5394): ApplicationContext is null in ApplicationStatus
,W/chromium( 5394): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,D/TimaKeyStoreProvider( 5430): TimaSignature is unavailable
,D/ActivityThread( 5430): Added TimaKeyStore provider
,W/chromium( 5394): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5394): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5394): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5394): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5394): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5394): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5394): Local Branch: 
I/Adreno-EGL( 5394): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5394): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5394):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/BluetoothAdapter( 5394): 1062738504: getState() :  mService = null. Returning STATE_OFF
,D/AcmsKeyStoreHelper( 5102):  getKeyStoreForApplication Enter
,D/LocationManagerService( 1016): getProviders()=[passive]
,I/AcmsKeyStoreHelper( 5102): Key Store exist
I/AcmsKeyStoreHelper( 5102): Hence loading the keystore file
,D/AcmsKeyStoreHelper( 5102):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 5102): getKeyStoreForApplication success 
D/AcmsCore( 5102): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 5102): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5102): Decrementing - Counter value: 1
D/AcmsCore( 5102): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 5102): This is NOT a valid MirrorLink app
D/AcmsCore( 5102): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 5102): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5102): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 5102): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 5102): getSvcCounter - Counter value: 0
D/AcmsService( 5102): Enter onDestroy
I/AcmsService( 5102): cleanUp(): inside service clean up
D/AcmsCore( 5102): AcmsCore: inside DeInit
D/AcmsCore( 5102): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 5102): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 5102): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 5102): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 5102): AppEntryInterface: Inside CleanUp
,D/AcmsServiceMonitor( 5102): getSvcCounter - Counter value: 0
D/AcmsService( 5102): killing acms process
I/Process ( 5102): Sending signal. PID: 5102 SIG: 9
,I/UpdateIcingCorporaServi( 5412): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/Mms/MmsApp( 5022):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 5022): [start]    fillCache consume time = 1928.718489
D/Mms/ComposeMessageFragment( 5022): fillCache, easy = false
,W/ActivityManager( 1016): Activity pause timeout for ActivityRecord{f0df710 u0 com.test.thalitest/.MainActivity t228}
,W/art     ( 5394): Attempt to remove local handle scope entry from IRT, ignoring
,I/ActivityManager( 1016): Process ACMS.Process (pid 5102)(adj 0) has died(40,1111)
,D/AbsListView( 5022): Get MotionRecognitionManager
D/MotionRecognitionService( 1016):  ssp status : false
D/Mms/ComposeMessageFragment( 5022): [end]    fillCache consume time = 83.704062,
,I/splitIntent( 1016): Queue : backgroundsplit_2 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1016): Killing 4372:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
,W/AwContents( 5394): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 5394): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 5394): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 5394): CordovaWebView is running on device made by: samsung
,W/art     ( 5394): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 5394): Attempt to remove local handle scope entry from IRT, ignoring
,I/UpdateIcingCorporaServi( 5412): UpdateCorporaTask done [took 131 ms] updated apps [took 131 ms] 
,I/ActivityManager( 1016): Killing 4266:com.google.android.music:main/u0a111 (adj 15): empty #31
,D/Mms/BubbleViewCache( 5022): fillCache bubble = 1
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.google.android.gms:car for service com.google.android.gms/.car.InCallServiceImpl: pid=5476 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a,
,E/Zygote  ( 5476): MountEmulatedStorage()
E/Zygote  ( 5476): v2
I/libpersona( 5476): KNOX_SDCARD checking this for 10012
I/libpersona( 5476): KNOX_SDCARD not a persona
,I/SELinux ( 5476): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 5476): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 5476): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/OpenGLRenderer( 5394): Render dirty regions requested: true,
,D/ActivityManager( 1016): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1016): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1016): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1016): handleActiveUserChange for user 0
D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
W/libprocessgroup( 1016): failed to open /acct/uid_10040/pid_4372/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10111/pid_4266/cgroup.procs: No such file or directory
,I/art     (  311): Explicit concurrent mark sweep GC freed 8740(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 634us total 28.489ms
,W/chromium( 5394): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,V/ActivityThread( 5394): updateVisibility : ActivityRecord{16a33451 token=android.os.BinderProxy@282816db {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PhoneWindow( 5394): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 5394): *FMB* isFloatingMenuEnabled return false
,D/TimaKeyStoreProvider( 5476): TimaSignature is unavailable
,D/ActivityThread( 5476): Added TimaKeyStore provider
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 636us total 17.110ms
,I/SurfaceFlinger(  256): id=12 createSurf (1x1),1 flag=404, NainActivit
,W/ResourcesManager( 5476): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5476): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 615us total 16.856ms
,D/InputDispatcher( 1016): Focus entered window: 5394
D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 5394): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 5394): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5394): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 5394): Enabling debug mode 0
,I/MultiDex( 5476): VM with version 2.1.0 has multidex support
I/MultiDex( 5476): install
I/MultiDex( 5476): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 5476): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/InputMethodManagerService( 1016): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PanelView( 1178): There is/are notification(s) 
,I/SamsungIME( 1783): getCurrentCandidateView
,I/ActivityManager( 1016): Displayed Component not be shown by security: +798ms (total +886ms)
,W/ActivityManager( 1016): mDVFSHelper.release()
,I/Timeline( 1016): Timeline: Activity_windows_visible id: ActivityRecord{f0df710 u0 com.test.thalitest/.MainActivity t228} time:77819
,W/ActivityThread( 5476): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5476): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@a3f1ee: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5476): Installed default security provider GmsCore_OpenSSL
,W/IInputConnectionWrapper( 5394): showStatusIcon on inactive InputConnection
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,V/AlarmManager( 1016): waitForAlarm result :8
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1016): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
D/GCM     ( 1697): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/splitIntent( 1016): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1016): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1016): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,I/Timeline( 5394): Timeline: Activity_idle id: android.os.BinderProxy@282816db time:77842
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
I/SurfaceFlinger(  256): id=11 Removed uhalitest (7/9)
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/SurfaceFlinger(  256): id=11 Removed uhalitest (-2/9)
D/SamsungIME( 1783): Dismiss ExpandCandiate
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1697): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/ActivityManager( 1016): Killing 4901:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 1833): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/SamsungIME( 1783): getDebugLevel  : 0x4f4c
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 4212): callingUid 10012, callindPid: 4212
,E/MDM     ( 1653): [176] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SamsungIME( 1783): getDebugLevel  : 0x4f4c
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/BindingManager( 5394): Cannot call determinedVisibility() - never saw a connection for the pid: 5394
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,I/SamsungIME( 1783): KeybaordView init() : load resources
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1833): Restart initialization of location
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_4901/cgroup.procs: No such file or directory
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/SamsungIME( 1783): getCurrentKeyboard
I/SamsungIME( 1783): getTextKeyboard
,D/SamsungIME( 1783): [SwiftkeyWrapper] currentLangauge : 1701729619
,E/Watchdog( 1016): !@Sync 2
,D/JsMessageQueue( 5394): Set native->JS mode to OnlineEventsBridgeMode
,I/ServiceManager(  324): Waiting for service AtCmdFwd...,
,D/jxcore_app_log( 5394): JniHelper::setJavaVM(0xb8133450), pthread_self() = -1201110952
,D/JX-Cordova( 5394): jxcore cordova android initializing
,V/AlarmManager( 1016): waitForAlarm result :8
,D/NtpTrustedTime( 1016): forceRefresh() from cache miss
,D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
,D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
,D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
,D/NtpTrustedTime( 1016): forceRefresh Fail.
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/jxcore-log( 5394): Initializing JXcore engine,
W/jxcore-log( 5394): JXcore engine is ready
,W/jxcore-log( 5394): Starting JXcore engine
,E/audit   ( 1828): type=1400 msg=audit(1449683608.177:203): avc:  denied  { ioctl } for  pid=5394 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1828):  SEPF_SM-A500FU_5.0.2_0027
E/audit   ( 1828): type=1300 msg=audit(1449683608.177:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=be89ed58 items=0 ppid=311 ppcomm=main pid=5394 auid=4294967295 uid=10175 gid=10175 euid=10175 suid=10175 fsuid=10175 egid=10175 sgid=10175 fsgid=10175 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1828): type=1320 msg=audit(1449683608.177:203): 
,W/jxcore-log( 5394): Platform android
W/jxcore-log( 5394): 
W/jxcore-log( 5394): Process ARCH arm
W/jxcore-log( 5394): 
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/jxcore-log( 5394): JXcore Cordova bridge is ready!
I/jxcore-log( 5394): 
,W/jxcore-log( 5394): JXcore engine is started
,I/Choreographer( 5394): Skipped 131 frames!  The application may be doing too much work on its main thread.
,I/chromium( 5394): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 5394): Toggling radios to true
I/jxcore-log( 5394): 
,D/BluetoothAdapter( 5394): enable()
,W/ActivityManager( 1016): Permission Denial: getCurrentUser() from pid=5394, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
,W/BluetoothManagerService( 1016): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService( 1016): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5394, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService( 1016): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/BluetoothManagerService( 1016): 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
W/BluetoothManagerService( 1016): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
W/BluetoothManagerService( 1016): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/BluetoothManagerService( 1016): 	at android.os.Binder.execTransact(Binder.java:461)
,E/DevicePolicyManagerService( 1016): getAllowBluetoothMode - value retunrs : 2
,E/DevicePolicyManagerService( 1016): getAllowBluetoothMode - value retunrs : 2
,D/SettingsProvider( 1016): name = bluetooth_on,
,E/DevicePolicyManagerService( 1016): getAllowBluetoothMode - value retunrs : 2
,E/DevicePolicyManagerService( 1016): getAllowBluetoothMode - value retunrs : 2
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/SecContentProvider( 1016): uri = 18 selection = isWifiEnabled,
,D/SecContentProvider2( 1016): uri = 20 selection = isWifiStateChangeAllowed
D/WifiService( 1016): setWifiEnabled: true pid=5394, uid=10175
D/SecContentProvider2( 1016): mCursor = null
W/ActivityManager( 1016): Permission Denial: getCurrentUser() from pid=5394, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1016): Failed getting userId using ActivityManagerNative
W/WifiService( 1016): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5394, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1016): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/WifiService( 1016): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1016): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1016): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1016): 	at android.os.Binder.execTransact(Binder.java:461)
,I/libpersona( 5508): KNOX_SDCARD checking this for 1002
D/SettingsProvider( 1016): name = wifi_on
I/libpersona( 5508): KNOX_SDCARD not a persona
E/Zygote  ( 5508): MountEmulatedStorage()
I/ActivityManager( 1016): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=5508 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
E/Zygote  ( 5508): v2
I/SELinux ( 5508): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/WifiService( 1016): disconnect: pid=5394, uid=10175
,E/WifiHW  ( 1016): ##################### set firmware type 0 #####################
I/SELinux ( 5508): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5508): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/jxcore-log( 5394): Radios toggled,
I/jxcore-log( 5394): 
,D/TimaKeyStoreProvider( 5508): TimaSignature is unavailable
,D/ActivityThread( 5508): Added TimaKeyStore provider
,W/ResourcesManager( 5508): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,W/ResourcesManager( 5508): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/BluetoothA2dpSinkServiceJni( 5508): register_com_android_bluetooth_a2dp_sink
,D/BtSettings.ProfileConfig( 5508): Adding GattService
,D/BtSettings.ProfileConfig( 5508): Adding HeadsetService
,D/BtSettings.ProfileConfig( 5508): Adding A2dpService
,D/BtSettings.ProfileConfig( 5508): Adding HidService
,D/BtSettings.ProfileConfig( 5508): Adding HealthService
,D/BtSettings.ProfileConfig( 5508): Adding PanService
D/BtSettings.ProfileConfig( 5508): Adding BluetoothMapService
,D/BtSettings.ProfileConfig( 5508): Adding SapService
,D/BtSettings.ProfileConfig( 5508): Adding HeadsetClientService
,D/BtSettings.ProfileConfig( 5508): Adding A2dpSinkService
,D/BtSettings.ProfileConfig( 5508): Adding SapClientService
D/BtSettings.ProfileConfig( 5508): Adding HidDevService
,I/BtSettings.ProfileConfig( 5508): *********Initializing Bluetooth Profile Settings*******
,D/SettingsProvider( 1016): name = bt_svcst_com.android.bluetooth.gatt.GattService
,D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1002
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1016): ret = -1
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1016): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1002
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
D/SettingsProvider( 1016): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1002
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
D/SettingsProvider( 1016): name = bt_svcst_com.android.bluetooth.hid.HidService
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1002
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1016): name = bt_svcst_com.android.bluetooth.hdp.HealthService
,D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1002
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1016): name = bt_svcst_com.android.bluetooth.pan.PanService
,D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
,D/SettingsProvider( 1016): selectionArgs: 1002
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1016): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1002
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
,D/SettingsProvider( 1016): name = bt_svcst_com.broadcom.bt.service.sap.SapService
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1002
,D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1016): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1002
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1016): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1002
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1016): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
,D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
,D/SettingsProvider( 1016): selectionArgs: 1002
,D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1016): name = bt_svcst_com.android.bluetooth.hid.HidDevService
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1002
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
,D/BluetoothAdapterState( 5508): make
,I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
,I/bluedroid( 5508): init
,I/BluetoothAdapterState( 5508): Entering OffState
,I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
,I/bte_conf( 5508): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 5508): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 5508): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 5508): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,E/bt-btif ( 5508): btif_fetch_local_ble_random_bdaddr
I/bluedroid( 5508): get_profile_interface socket
I/bluedroid( 5508): get_profile_interface map_client
,I/GKI_LINUX( 5508): gki_task_entry task_id=1 [BTIF] starting
I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
,D/BluetoothAdapterService( 5508): checkAddrForIOP: Loading from conf
D/BluetoothAdapterProperties( 5508): Address is:7C:F9:0E:51:18:22
E/BluetoothServiceJni( 5508): populateRssiValuesNative
I/bluedroid( 5508): getModelRssiValues
E/BluetoothServiceJni( 5508): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 5508): modelRssiValuesCallback, low, mid, high = -70,-60,127
,D/BluetoothAdapterProperties( 5508): Name is: Thali Test (Galaxy A5)
,I/ConfigService( 1697): onDestroy
,D/SettingsProvider( 1016): name = bluetooth_name
,D/BluetoothA2dp( 5508): doBind(): CallingUid(myUserHandle) = 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
,I/bluedroid( 5508): config_hci_snoop_log
,D/BluetoothManagerService( 1016): Broadcasting onBluetoothServiceUp() to 9 receivers.
,D/BluetoothManagerService( 1016): Ble is always on enable gatt
,I/BluetoothManagerService( 1016): enableGattForLeMode, doBind called
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,I/BtGatt.JNI( 5508): classInitNative(L900): classInitNative: Success!
,E/DevicePolicyManagerService( 1016): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 1016): getAllowBluetoothMode - value retunrs : 2
,D/SecContentProvider( 1016): uri = 3 selection = isBluetoothEnabled
,D/BluetoothManagerService( 1016): Broadcasting onBluetoothServiceUp() to 0 receivers.
,D/BluetoothAdapterState( 5508): CURRENT_STATE=OFF, MSG = USER_TURN_ON
,D/BluetoothAdapterProperties( 5508): Setting state to 11
I/BluetoothAdapterState( 5508): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 5508): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5508): updateAdapterState state is 11
,D/BluetoothAdapterService( 5508): Autoconnection is available 
,D/BluetoothAdapterService( 5508): updateAdapterState prevState = 10newState = 11
,D/BluetoothSecureManager( 5508): getInstant: null
D/BluetoothSecureManager( 5508): calling getMethod for getService
D/BluetoothSecureManager( 5508): calling getService
,W/InputMethodManagerService( 1016): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService( 1016): [BT Setting State] State =11
,D/BluetoothTile( 1178):  onBluetoothPairedDevicesChanged:
,D/BluetoothSecureManager( 5508): getService return binder: android.os.BinderProxy@14d33e63
D/BluetoothTile( 1178): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1178):  getBluetoothState : 11
,D/BluetoothSecureManagerService( 1016): isSecureModeEnabled
,D/BluetoothSecureManagerService( 1016): getSecureModeSetting, name: secure_mode_enable
,D/BtConfig.SecureMode( 5508): isSecureModeOn:false
D/BtSettings.ProfileConfig( 5508): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,I/SamsungIME( 1783): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/BluetoothTile( 1178):  handleUpdatestate:false name:null
,W/BluetoothAdapterService( 5508): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 5508): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,D/STATUSBAR-QSTileView( 1178): onStateChanged: Bluetooth
,W/BluetoothAdapterService( 5508): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5508): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 5508): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 5508): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 5508): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5508): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 5508): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 5508): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 5508): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 5508): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/StatusBarManagerService( 1016): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,W/BluetoothAdapterService( 5508): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 5508): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/StatusBarManagerService( 1016): setIconVisibility slot=bluetooth visible=false
,W/BluetoothAdapterService( 5508): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 5508): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,D/PhoneStatusBar( 1178): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,W/BluetoothAdapterService( 5508): processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 5508): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,W/BluetoothAdapterService( 5508): processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 5508): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,W/BluetoothAdapterService( 5508): processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 5508): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,W/BluetoothAdapterService( 5508): processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,D/BluetoothBondStateMachine( 5508): make
,W/BluetoothAdapterService( 5508): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 5508): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 5508): Not skipping com.android.bluetooth.gatt.GattService
,I/BluetoothBondStateMachine( 5508): StableState(): Entering Off State
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
D/BluetoothNotiBroadcastReceiver( 1306): onReceive
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5508): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5508): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 5508): Not skipping com.android.bluetooth.hfp.HeadsetService
,D/BtGatt.DebugUtils( 5508): handleDebugAction() action=null
,D/BtGatt.GattService( 5508): Received start request. Starting profile...
D/BtGatt.GattService( 5508): start()
D/BtGatt.GattService( 5508): start()
I/bluedroid( 5508): get_profile_interface gatt
D/BluetoothAdapterService( 5508): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2954e365
D/BtGatt.AdvertiseManager( 5508): advertise manager created
,V/BluetoothStatusReceiver( 1178): Received android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothStatusReceiver( 1178): AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5508): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,D/BtSettings.ProfileConfig( 5508): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 5508): Not skipping com.android.bluetooth.a2dp.A2dpService
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/BtGatt.GattService( 5508): mStartError = false
D/BluetoothAdapterService( 5508): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2954e365
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=5548 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,E/Zygote  ( 5548): MountEmulatedStorage()
E/Zygote  ( 5548): v2
I/libpersona( 5548): KNOX_SDCARD checking this for 10003
I/libpersona( 5548): KNOX_SDCARD not a persona
,I/SELinux ( 5548): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/HeadsetService( 5508): Received start request. Starting profile...
D/HeadsetService( 5508): start()
,I/BluetoothHeadsetServiceJni( 5508): classInitNative: succeeds
,I/SELinux ( 5548): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
E/SELinux ( 5548): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/HeadsetStateMachine( 5508): make
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5508): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5508): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 5508): Not skipping com.android.bluetooth.hid.HidService
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
E/HeadsetStateMachine( 5508): # of Max HF connection is 2
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
W/BluetoothAdapterService( 5508): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 5508): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 5508): Not skipping com.android.bluetooth.hdp.HealthService
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
I/bluedroid( 5508): get_profile_interface handsfree
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/DualScoManager( 5508): Instantiating Dual Sco Manager
I/DualScoManager( 5508): Set HeadsetServiceHelper
,D/BluetoothAtMessage( 5508): createCMTIContentObservers
,D/SettingsProvider( 1016): name = bluetooth_hfp_allowed_bvra
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1002
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,W/BluetoothAdapterService( 5508): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService,
W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=1002,
D/BtSettings.ProfileConfig( 5508): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0,
W/BluetoothAdapterService( 5508): Not skipping com.android.bluetooth.pan.PanService
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/HeadsetStateMachine( 5508): Enter Disconnected: -2
W/BluetoothAdapterService( 5508): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
D/BtSettings.ProfileConfig( 5508): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 5508): Not skipping com.android.bluetooth.map.BluetoothMapService
D/HeadsetService( 5508): mStartError = false
D/BluetoothAdapterService( 5508): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2954e365
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/HeadsetStateMachine( 5508): Clear mHeadsetBrsf
,D/HeadsetStateMachine( 5508): map size, before remove : 0
D/HeadsetStateMachine( 5508): map size, after remove: 0
W/BluetoothAdapterService( 5508): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 5508): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 5508): Not skipping com.broadcom.bt.service.sap.SapService
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5508): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 5508): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService( 5508): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 5508): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 5508): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,W/BluetoothAdapterService( 5508): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 5508): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 5508): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
,W/BluetoothAdapterService( 5508): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 5508): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
,D/BtSettings.ProfileConfig( 5508): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,W/BluetoothAdapterService( 5508): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,E/BluetoothAdapterService(693429093)( 5508): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,D/Tethering( 1016): interfaceAdded wlan0
I/BluetoothAdapterState( 5508): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/BluetoothA2dp( 2669): Proxy object connected
,D/BluetoothA2dp( 1016): Proxy object connected
,D/A2dpService( 5508): Received start request. Starting profile...
D/A2dpService( 5508): start()
,I/BluetoothAvrcpServiceJni( 5508): classInitNative: succeeds
I/bluedroid( 5508): get_profile_interface avrcp
,E/Tethering( 1016): No numeric data
,D/Tethering( 1016): sendTetherStateChangedBroadcast 1, 0, 0
,D/Tethering( 1016): clearTetheredNotification()
,D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
D/Tethering( 1016): interfaceStatusChanged wlan0, false
,D/TimaKeyStoreProvider( 5548): TimaSignature is unavailable
,I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
,D/NtpTrustedTime( 1016): forceRefresh() from cache miss
,D/Tethering( 1016): InitialState.processMessage what=4
,D/HotspotTile( 1178): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1178): updateTetherState():false, false
D/Tethering( 1016): interfaceAdded p2p0
,D/ActivityThread( 5548): Added TimaKeyStore provider
,E/RemoteController( 5508): Cannot set synchronization mode on an unregistered RemoteController
E/Tethering( 1016): No numeric data
,D/Tethering( 1016): sendTetherStateChangedBroadcast 0, 0, 0
,D/Tethering( 1016): clearTetheredNotification()
D/Tethering( 1016): p2p0 is not a tetherable iface, ignoring
,D/Tethering( 1016): interfaceLinkStateChanged p2p0, false
D/Tethering( 1016): interfaceStatusChanged p2p0, false
,I/Nat464Xlat( 1016): interfaceLinkStateChanged p2p0, false
,D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
,D/HotspotTile( 1178): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1178): updateTetherState():false, false
,D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
,I/WifiHW  (  277): wifi_change_fw_path(): fwpath = sta,
D/SoftapController(  277): Softap fwReload - Ok
D/NtpTrustedTime( 1016): forceRefresh Fail.
,V/NetworkStats( 1016): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1016): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1016): UpdateStatsForKnox main else ---
,D/CommandListener(  277): Setting iface cfg
D/CommandListener(  277): Trying to bring down wlan0
,D/CommandListener(  277): Clearing all IP addresses on wlan0
,V/NetworkStats( 1016): performPollLocked() took 7ms
,D/NtpTrustedTime( 1016): forceRefresh() from cache miss
,D/NtpTrustedTime( 1016): forceRefresh() from cache miss
,D/NtpTrustedTime( 1016): forceRefresh Fail.
D/NtpTrustedTime( 1016): forceRefresh Fail.
,V/NetworkStats( 1016): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1016): UpdateStatsForKnox updated
,I/Avrcp   ( 5508):  Updating now playing list upon AVRCP Start
D/NetworkStatsFactory( 1016): UpdateStatsForKnox main else ---
D/BluetoothMediaBrowser( 5508):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,V/NetworkStats( 1016): performPollLocked() took 3ms
,I/BluetoothA2dpServiceJni( 5508): classInitNative: succeeds
D/A2dpStateMachine( 5508): make
,I/bluedroid( 5508): get_profile_interface a2dp
I/GKI_LINUX( 5508): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,E/bt-btif ( 5508): warning : media task started media_task_refcnt 1 
,D/A2dpService( 5508): mStartError = false,
D/BluetoothAdapterService( 5508): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2954e365
D/A2dpStateMachine( 5508): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 5508): classInitNative: succeeds
,D/NtpTrustedTime( 1016): forceRefresh() from cache miss
D/NtpTrustedTime( 1016): forceRefresh Fail.
,D/HidService( 5508): Received start request. Starting profile...
D/HidService( 5508): start()
I/bluedroid( 5508): get_profile_interface hidhost
D/HidService( 5508): setHidService(): set to: null
D/HidService( 5508): mStartError = false
D/BluetoothAdapterService( 5508): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2954e365
D/HeadsetStateMachine( 5508): Proxy object connected
D/HeadsetPhoneState( 5508): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,D/HeadsetStateMachine( 5508): Disconnected process message: 11
,I/BluetoothHealthServiceJni( 5508): classInitNative: succeeds
D/HealthService( 5508): Received start request. Starting profile...
D/HealthService( 5508): start()
,I/bluedroid( 5508): get_profile_interface health
D/HealthService( 5508): mStartError = false
D/BluetoothAdapterService( 5508): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2954e365
,E/WifiHW  ( 1016): supplicant_name : p2p_supplicant
D/HeadsetStateMachine( 5508): Try to query the phonestate on bind
,D/WifiMonitor( 1016): startMonitoring(wlan0) with mConnected = false
,I/Telecom ( 1441): BluetoothPhoneService: queryPhoneState
,I/Telecom ( 1441): BluetoothPhoneService: handleMessage(7) / param 0
,I/Telecom ( 1441): BluetoothPhoneService: updateHeadsetWithCallState
,D/UserAnalysis.PlaceProvider( 5548): PlaceProvider onCreate()
,I/Telecom ( 1441): BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,I/Telecom ( 1441): BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,I/Telecom ( 1441): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/STATUSBAR-QSTileView( 1178): onStateChanged: Wi-Fi
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/STATUSBAR-WifiQuickSettingButton( 1178): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1178): Wifi onReceive(2),
,D/HotspotTile( 1178): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/WifiCredService( 1306): Action received :android.net.wifi.WIFI_STATE_CHANGED
,W/BluetoothHeadset( 1441): Proxy not attached to service
,I/Telecom ( 1441): BluetoothPhoneService: Result of Message : true
D/HeadsetPhoneState( 5508): sendDeviceDataStateChanged
D/HeadsetPhoneState( 5508): Signal level : previous=0 curr=0
,D/HeadsetStateMachine( 5508): Disconnected process message: 18
,I/BluetoothPanServiceJni( 5508): classInitNative(L105): succeeds
,E/BluetoothAdapterService(693429093)( 5508): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,D/HotspotTile( 1178): onReceive : 2, 0
,D/BluetoothPan( 1016): BluetoothPAN Proxy object connected
,D/BluetoothMediaBrowser( 5508): no now playing list
D/BluetoothMediaBrowser( 5508):  getNowPlayingId now playing id : -1
,D/PanService( 5508): Received start request. Starting profile...
D/PanService( 5508): start()
D/BluetoothPanServiceJni( 5508): initializeNative(L110): pan
I/bluedroid( 5508): get_profile_interface pan
,D/PanService( 5508): mStartError = false
,D/BluetoothAdapterService( 5508): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2954e365
,V/HeadsetService( 5508): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5508): Disconnected process message: 10
D/HeadsetPhoneState( 5508): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 5508): Disconnected process message: 11
,D/BluetoothMapService( 5508): Received start request. Starting profile...
D/BluetoothMapService( 5508): start()
,D/BluetoothMapService( 5508): mStartError = false
,D/BluetoothAdapterService( 5508): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2954e365
I/wpa_supplicant( 5576): [wpa_supplicant_init]: use SECRIL
I/wpa_supplicant( 5576): Successfully initialized wpa_supplicant
,I/SecureStorage( 5576): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/BluetoothSAPServiceJni( 5508): classInitNative(L204): succeeds
,D/UserAnalysis.SecureDbManager( 5548): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 5548): SecurePlaceDbHelper() 
D/UserAnalysis( 5548): Create SecureDbHelper
,D/IntelligenceServiceApplication( 5548): onCreate(),
D/SapService( 5508): Received start request. Starting profile...
D/SapService( 5508): start()
D/BluetoothSAPServiceJni( 5508): initializeNative(L209): sap
I/bluedroid( 5508): get_profile_interface sap
D/SapService( 5508): mStartError = false
D/BluetoothAdapterService( 5508): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2954e365
D/BluetoothA2dp( 5508): Proxy object connected
D/BluetoothAdapterService( 5508): Bluetooth A2dp source service connected
E/BluetoothAdapterService(693429093)( 5508): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
E/BluetoothAdapterService(693429093)( 5508): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
E/BluetoothAdapterService(693429093)( 5508): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,E/BluetoothAdapterService(693429093)( 5508): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true,
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/SecureStorage( 5576): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage(  382): [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 5576
I/SecureStorage(  382): [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
I/SecureStorage( 5576): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 5576): ssSupport state is = 1
,I/wpa_supplicant( 5576): >>>>> GET KEY, IV <<<<<
I/SecureStorage( 5576): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  382): [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 5576
I/SecureStorage(  382): [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,I/ActivityManager( 1016): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=5578 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,D/IntelligenceServiceApplication( 5548): no applications having user consent for prediction
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,V/PlaceDetection v1.0.19 ( 5548): [PlaceDetection::stopService] Service stopped.,
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/Zygote  ( 5578): MountEmulatedStorage()
I/libpersona( 5578): KNOX_SDCARD checking this for 10145
E/Zygote  ( 5578): v2
I/libpersona( 5578): KNOX_SDCARD not a persona
,I/SELinux ( 5578): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,V/PlaceDetection v1.0.19 ( 5548): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,I/SELinux ( 5578): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 5578): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5578): TimaSignature is unavailable
D/ActivityThread( 5578): Added TimaKeyStore provider
,W/ResourcesManager( 5578): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 5578): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5578): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5578): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5578): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,I/SecureStorage(  382): [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,I/SecureStorage( 5576): [INFO]: SPID(0x00000002)Processing data has been completed
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,E/BluetoothAdapterService(693429093)( 5508): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,E/BluetoothAdapterService(693429093)( 5508): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,I/ActivityManager( 1016): Killing 4923:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
,D/BluetoothAdapterState( 5508): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 5508): enable
,I/bt_hci_bdroid( 5508): init
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,I/bt_vendor( 5508): bt-vendor : init
I/bt_vendor( 5508): bt-vendor : get_bt_soc_type
E/bt_vendor( 5508): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 5508): init: Local BD Address : 22:18:51:0e:f9:7c
D/bt_userial_mct( 5508): userial_init
,I/bt_vendor( 5508): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 5508): Starting hciattach daemon
,I/bt_vendor( 5508): try to set false
,D/AuthorizationBluetoothService( 1697): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/bt_vendor( 5508): bt-vendor : BT_VND_OP_POWER_CTRL: On,
,I/bt_vendor( 5508): Starting hciattach daemon
I/bt_vendor( 5508): try to set true
I/GKI_LINUX( 5508): gki_task_entry task_id=0 [BTU] starting
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,I/qcom-bluetooth( 5606): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3385): Starting #2
,I/wpa_supplicant( 5576): Ctrl_iface: loading cred from phone
I/SecureStorage( 5576): [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,I/Hs20UtilService( 3385): Message received 5011
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0,
,I/SecureStorage( 5576): [INFO]: SPID(0x00000002)This device supports Secure Storage
I/SecureStorage(  382): [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 5576
I/SecureStorage(  382): [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
I/SecureStorage( 5576): [INFO]: SPID(0x00000002)SS Daemon is running
I/wpa_supplicant( 5576): ssSupport state is = 1
I/wpa_supplicant( 5576): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5576): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5576): SIM READ ERROR
I/wpa_supplicant( 5576): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5576): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5576): SIM READ ERROR
I/wpa_supplicant( 5576): Blacklist: Clear (all) 
,I/wpa_supplicant( 5576): wpa_default_ap_write_once
I/wpa_supplicant( 5576): There is no /data/misc/wifi/default_ap.check. Start copy default ap
I/wpa_supplicant( 5576): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5576): getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
I/wpa_supplicant( 5576): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5576): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,I/wpa_supplicant( 5576): rfkill: Cannot open RFKILL control device,
E/Zygote  ( 5610): MountEmulatedStorage()
E/Zygote  ( 5610): v2
,I/libpersona( 5610): KNOX_SDCARD checking this for 1000
I/libpersona( 5610): KNOX_SDCARD not a persona
I/SELinux ( 5610): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 5610): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
D/Tethering( 1016): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
E/SELinux ( 5610): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1016): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=5610 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 5610): TimaSignature is unavailable
D/ActivityThread( 5610): Added TimaKeyStore provider
,I/qcom-bluetooth( 5628): /system/etc/init.qcom.bt.sh: Transport : smd ,
,I/qcom-bluetooth( 5629): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,I/qcom-bluetooth( 5631): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,I/qcom-bluetooth( 5632): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,I/qcom-bluetooth( 5633): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,I/qcom-bluetooth( 5634): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,I/wpa_supplicant( 5576): wlan0: Setting scan request: 0 sec 100000 usec,
,W/libprocessgroup( 1016): failed to open /acct/uid_10142/pid_4923/cgroup.procs: No such file or directory
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 29191(1580KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 26MB/40MB, paused 2.488ms total 145.819ms
,D/BadgeProvider( 5201): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 5201): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5201): sendNotify, [notify] : null
D/BadgeProvider( 5201): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5201): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5201): update, [UpdateCount] : 1
D/Launcher.Model( 1489): reloadBadges entered.
,D/SecurityLogAgent( 5610): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 5610): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 5610): StateMachine : Current State = 1
,D/SecurityLogAgent( 5610): StateMachine : Changed Current State = 1
,I/ActivityManager( 1016): Killing 3671:com.google.android.talk/u0a104 (adj 15): empty #31
,I/wpa_supplicant( 5576): wlan0: State: DISCONNECTED -> DISCONNECTED
,I/SecureStorage( 5576): [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,V/AlarmManager( 1016): waitForAlarm result :4
,I/SecureStorage( 5576): [INFO]: SPID(0x00000002)This device supports Secure Storage
,I/SecureStorage(  382): [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 5576
I/SecureStorage(  382): [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
I/SecureStorage( 5576): [INFO]: SPID(0x00000002)SS Daemon is running
I/wpa_supplicant( 5576): ssSupport state is = 1
,I/wpa_supplicant( 5576): Ctrl_iface: loading cred from phone
I/SecureStorage( 5576): [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,I/qcom-bluetooth( 5640): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:51:18:22 ,
,I/SecureStorage( 5576): [INFO]: SPID(0x00000002)This device supports Secure Storage,
I/SecureStorage(  382): [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 5576
I/SecureStorage(  382): [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
I/SecureStorage( 5576): [INFO]: SPID(0x00000002)SS Daemon is running
I/wpa_supplicant( 5576): ssSupport state is = 1
I/wpa_supplicant( 5576): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
E/wpa_supplicant( 5576): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5576): SIM READ ERROR
I/wpa_supplicant( 5576): wpa_default_ap_write_once
I/wpa_supplicant( 5576): There is no /data/misc/wifi/default_ap.check. Start copy default ap
I/wpa_supplicant( 5576): rfkill: Cannot open RFKILL control device
D/Tethering( 1016): interfaceLinkStateChanged p2p0, false
D/Tethering( 1016): interfaceStatusChanged p2p0, false
I/Nat464Xlat( 1016): interfaceLinkStateChanged p2p0, false
,D/Tethering( 1016): interfaceLinkStateChanged p2p0, false
D/Tethering( 1016): interfaceStatusChanged p2p0, false
,I/Nat464Xlat( 1016): interfaceLinkStateChanged p2p0, false
I/qcom-bluetooth( 5641): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,I/bt_vendor( 5508): bluetooth satus is on
D/bt_userial_mct( 5508): userial_open(port:0)
I/bt_vendor( 5508): bt-vendor : BT_VND_OP_USERIAL_OPEN
,I/bt_vendor( 5508): Done intiailizing UART
,I/bt_vendor( 5508): Done intiailizing UART
,I/bt_userial_mct( 5508): CMD=65, EVT=65, ACL_Out=66, ACL_In=66
I/bt_vendor( 5508): Bluetooth Firmware and transport layer are initialized
D/bt_userial_mct( 5508): Entering userial_read_thread()
,D/SSRM:n  ( 1016): SIOP:: AP = 370
,I/        ( 5508): BTE_InitTraceLevels -- TRC_HCI
,I/        ( 5508): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 5508): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 5508): BTE_InitTraceLevels -- TRC_AVDT
,I/        ( 5508): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 5508): BTE_InitTraceLevels -- TRC_A2D
I/        ( 5508): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 5508): BTE_InitTraceLevels -- TRC_BTM
I/        ( 5508): BTE_InitTraceLevels -- TRC_GAP
,I/        ( 5508): BTE_InitTraceLevels -- TRC_PAN
I/        ( 5508): BTE_InitTraceLevels -- TRC_SAP
I/        ( 5508): BTE_InitTraceLevels -- TRC_SDP
I/        ( 5508): BTE_InitTraceLevels -- TRC_GATT
,I/        ( 5508): BTE_InitTraceLevels -- TRC_SMP
I/        ( 5508): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 5508): BTE_InitTraceLevels -- TRC_BTIF
I/        ( 5508): BTE_InitTraceLevels -- TRC_PROTOCOL
,W/libprocessgroup( 1016): failed to open /acct/uid_10104/pid_3671/cgroup.procs: No such file or directory
,I/wpa_supplicant( 5576): p2p0: State: DISCONNECTED -> INACTIVE
I/wpa_supplicant( 5576): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 5576): p2p0: State: INACTIVE -> DISCONNECTED,
I/wpa_supplicant( 5576): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=,
I/wpa_supplicant( 5576): Skip scan - bUseNetwork false
,E/WifiStateMachine( 1016): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
,D/WifiNative-wlan0( 1016): callSECApiBoolean - ID [21]
,I/wpa_supplicant( 5576): HOTSPOT20_ENABLE called
I/wpa_supplicant( 5576): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5576): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5576): SIM READ ERROR
I/wpa_supplicant( 5576): Blacklist: Clear (all) 
,I/wpa_supplicant( 5576): wlan0: Setting scan request: 0 sec 0 usec
,I/PowerManagerService( 1016): [PWL] Off : 30s ago
,I/PowerManagerService( 1016): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService( 1016): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1016): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=1833, ws=null) (elapsedTime=47948)
,I/PowerManagerService( 1016): [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=5508, ws=null) (elapsedTime=116)
,W/bt-l2cap( 5508): l2c_link_processs_ble_num_bufs 16
,I/wpa_supplicant( 5576): Skip scan - bUseNetwork false,
,E/bt-btm  ( 5508): BTM_SecRegister:p_cb_info->p_le_callback == 0xa44076e9 
E/bt-btm  ( 5508): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa44076e9 
,D/WifiNative-wlan0( 1016): callSECApiInt - ID [210]
,D/WifiConfigStore( 1016): Loading config and enabling all networks 
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/STATUSBAR-WifiQuickSettingButton( 1178): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/HotspotTile( 1178): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1178): Wifi onReceive(3)
,D/STATUSBAR-QSTileView( 1178): onStateChanged: Wi-Fi
D/HotspotTile( 1178): onReceive : 3, 0
,D/WifiCredService( 1306): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,E/WifiConfigStore( 1016): Not a HS20
,I/Hs20UtilService( 3385): Starting #3
,E/WifiConfigStore( 1016): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,I/Hs20UtilService( 3385): Message received 5011
,D/SecurityLogAgent( 5610): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 5610): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5610): StateMachine : Current State = 1
D/SecurityLogAgent( 5610): StateMachine : Changed Current State = 1
,D/Tethering( 1016): interfaceLinkStateChanged p2p0, false
,D/WifiNative-wlan0( 1016): callSECApiInt - ID [65]
,D/Tethering( 1016): interfaceStatusChanged p2p0, false
,I/Nat464Xlat( 1016): interfaceLinkStateChanged p2p0, false
,D/BluetoothAdapterProperties( 5508): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,D/WifiNative-wlan0( 1016): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 5576): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant( 5576): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 5576): reset timer : RESET_TIMER 0
I/wpa_supplicant( 5576): P2P: Current p2p state = IDLE
I/wpa_supplicant( 5576): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 5576): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 5576): First Scan Start
,I/wpa_supplicant( 5576): Scan requested (ret=0) - scan timeout 30 seconds
,E/bt-btif ( 5508): BTA got event 0x122c
E/bt-btif ( 5508): btif_storage_get_adapter_property service_mask:0x2120048
D/BluetoothAdapterProperties( 5508): Address is:7C:F9:0E:51:18:22
E/BluetoothServiceJni( 5508): populateRssiValuesNative
I/bluedroid( 5508): getModelRssiValues
E/BluetoothServiceJni( 5508): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 5508): modelRssiValuesCallback, low, mid, high = -70,-60,127
,D/WifiNative-wlan0( 1016): Setting external_sim to 1
,D/WifiStateMachine( 1016): Setting OUI to DA-A1-19
I/WifiNative-HAL( 1016): startHal
E/wifi    ( 1016): getStaticLongField sWifiHalHandle 0x9d28b88c
I/WifiNative-HAL( 1016): Could not start hal
,D/BluetoothAdapterProperties( 5508): Name is: Thali Test (Galaxy A5)
,D/SettingsProvider( 1016): name = bluetooth_name
,E/WifiNative-wlan0( 1016): do suspend true
,E/WifiStateMachine( 1016): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,D/WifiScanningService( 1016): SCAN_AVAILABLE : 3
,D/WifiScanningService( 1016): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1016): P2pDisabledState{ what=131203 }
,I/WifiNative-HAL( 1016): startHal
E/WifiStateMachine( 1016): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-wlan0( 1016): callSECStringApiVoid - ID [215]
E/WifiNative-wlan0( 1016): invaild command id : 215
,E/wifi    ( 1016): getStaticLongField sWifiHalHandle 0x9e6cb9bc
I/WifiNative-HAL( 1016): Could not start hal
E/WifiStateMachine( 1016): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-wlan0( 1016): callSECStringApiVoid - ID [215]
E/WifiScanningService( 1016): could not start HAL
E/WifiNative-wlan0( 1016): invaild command id : 215
,D/RttService( 1016): SCAN_AVAILABLE : 3
,D/CommandListener(  277): Setting iface cfg
D/CommandListener(  277): Trying to bring up p2p0
,D/RttService( 1016): DefaultState got{ when=-2ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiMonitor( 1016): startMonitoring(p2p0) with mConnected = true
,D/BluetoothUtils( 5508): getBtEnabledContainers(): btContainers = []
,D/BluetoothAdapterProperties( 5508): Scan Mode:20
,D/BluetoothAdapterProperties( 5508): Discoverable Timeout:120
D/BluetoothAdapterProperties( 5508): LE Address is:FC:F3:1C:A2:30:44
I/wpa_supplicant( 5576): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
E/bt-btif ( 5508): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif ( 5508): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
E/bt-btif ( 5508): btif_sock_init: !radio_req && !rfc_init
E/bt-btif ( 5508): btif_sock_init: !vhci_init
E/bt_mct  ( 5508): hci lib postload completed
D/IOP_DB_BT( 5508): db_open: file /etc/bluetooth/iop_bt.db
,I/wpa_supplicant( 5576): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
D/IOP_DB_BT( 5508): db_open: db_open : handle 3028078608l, read 13894 bytes onto local cache
D/IOP_DB_BT( 5508): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/WifiP2pService( 1016): P2pEnablingState
D/IOP_DB_BT( 5508): db_query: result 1
I/        ( 5508): iop_db_open: iop_db_open status 0
,D/bte_conf( 5508): Device ID record 1 : primary
,D/bte_conf( 5508):   vendorId            = 0075
D/bte_conf( 5508):   vendorIdSource      = 0001
D/bte_conf( 5508):   product             = 0100
,D/bte_conf( 5508):   version             = 0200
D/bte_conf( 5508):   clientExecutableURL = 
D/bte_conf( 5508):   serviceDescription  = 
D/bte_conf( 5508):   documentationURL    = 
D/bte_conf( 5508): bte_load_did_conf no section named DID2.,
D/BluetoothPanServiceJni( 5508): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
I/wpa_supplicant( 5576): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,D/BluetoothAdapterState( 5508): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 5508): ScanMode =  20
D/BluetoothAdapterProperties( 5508): State =  11
D/WifiP2pService( 1016): P2pEnablingState{ what=147457 }
,D/WifiP2pService( 1016): P2p socket connection successful
D/SecContentProvider( 1016): uri = 3 selection = isDiscoverableEnabled
,D/BluetoothAdapterProperties( 5508): Setting state to 12
I/BluetoothAdapterState( 5508): Bluetooth adapter state changed: 11-> 12
,D/WifiP2pService( 1016): P2pEnabledState
,D/SecContentProvider2( 1016): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1016): mCursor = null
,D/BluetoothUtils( 5508): getBtEnabledContainers(): btContainers = []
D/BluetoothAdapterProperties( 5508): Scan Mode:21
D/BluetoothAdapterProperties( 5508): Discoverable Timeout:120
,D/WifiP2pService( 1016): sending p2p connection changed broadcast: IDLE
,D/SecContentProvider2( 1016): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1016): mCursor = null
,D/SettingsProvider( 1016): name = bluetooth_a2dp_sink_mode
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1002
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,D/WifiP2pService( 1016): create mNetworkAgent
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/BluetoothAdapterService( 5508): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5508): updateAdapterState state is 12
,E/WifiStateMachine( 1016): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,D/WifiDisplayController( 1016): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,D/WifiDisplayController( 1016): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 1016): disconnect
D/WifiDisplayController( 1016): updateConnection
D/WifiDisplayController( 1016): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothAdapter( 1653): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1653): onBluetoothStateChange: Bluetooth is on
,D/BluetoothAdapterService( 5508): Autoconnection is available 
D/BluetoothAdapterService( 5508): updateAdapterState prevState = 11newState = 12
D/BluetoothAdapterService( 5508): starting service from this receiver
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,D/BluetoothAdapter( 1464): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1464): onBluetoothStateChange: Bluetooth is on
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothAdapter( 5508): onBluetoothStateChange: up=true
D/BluetoothAdapter( 5508): onBluetoothStateChange: Bluetooth is on
,I/BluetoothAdapterState( 5508): Entering On State from state = 11
,D/BluetoothAdapter( 1178): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1178): onBluetoothStateChange: Bluetooth is on
,I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
,D/BluetoothAdapter( 1441): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1441): onBluetoothStateChange: Bluetooth is on
,D/BluetoothAdapter( 5394): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 5394): onBluetoothStateChange: Bluetooth is on
,D/BluetoothA2dp( 2669): onBluetoothStateChange: up=true
,D/BluetoothA2dp( 5508): onBluetoothStateChange: up=true
,I/BluetoothPbapService( 5508): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,D/BluetoothA2dp( 1016): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 1450): onBluetoothStateChange: up=true
D/AllShareCastTile( 1178): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/BluetoothAdapter( 1450): onBluetoothStateChange: Bluetooth is on
,D/ConnectivityService( 1016): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 1016): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 1016): updateNetworkInfo()
D/ConnectivityService( 1016): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from null to UNKNOWN, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,E/CSLegacyTypeTracker( 1016): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} } for legacy network type 13
,D/BluetoothAdapter( 2669): onBluetoothStateChange: up=true
D/BluetoothAdapter( 2669): onBluetoothStateChange: Bluetooth is on
,D/WifiDisplayController( 1016): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BluetoothAdapter( 1016): onBluetoothStateChange: up=true
D/AllShareCastTile( 1178): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
D/BluetoothAdapter( 1016): onBluetoothStateChange: Bluetooth is on
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,I/BluetoothPbapService( 5508): Handler(): got msg=1
,D/SecContentProvider( 1016): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,W/InputMethodManagerService( 1016): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService( 1016): [BT Setting State] State =12
,D/WifiNative-p2p0( 1016): p2pGetDeviceAddress
I/InputMethodManagerService( 1016): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
V/BluetoothPbapService( 5508): PBAP Service initSocket try: 0
,D/NearbySettings( 1306): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/WifiNative-p2p0( 1016): p2pGetDeviceAddress returning 7e:f9:0e:51:18:23
,V/NearbySettings( 1306): DMSUtil.isNetworkConnected - flag-null, state-null
,D/BluetoothHeadset( 1441): registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@1a47aa43, true
D/BluetoothTile( 1178):  onBluetoothStateChange:
,D/BluetoothHeadset( 1441): registerMessageListener
,I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/BluetoothTile( 1178):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1178): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothTile( 1178):  getBluetoothState : 12
,D/WifiP2pService( 1016): DeviceAddress: 7e:18:23
,D/WifiDisplayController( 1016): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A5)
D/WifiDisplayController( 1016):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiDisplayController( 1016):  primary type: 10-0050F204-5
D/WifiDisplayController( 1016):  secondary type: null
D/WifiDisplayController( 1016):  wps: 0
D/WifiDisplayController( 1016):  grpcapab: 0
D/WifiDisplayController( 1016):  devcapab: 0
D/WifiDisplayController( 1016):  status: 3
D/WifiDisplayController( 1016):  wfdInfo: null
D/WifiDisplayController( 1016):  groupownerAddress: null
D/WifiDisplayController( 1016):  GOdeviceName: null
D/WifiDisplayController( 1016):  interfaceAddress: 
D/WifiDisplayController( 1016):  SConnectInfo : null
,I/SamsungIME( 1783): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,I/NearbySettings( 1306): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1306): MountReceiver.onReceive - Set preference state off
,D/BluetoothTile( 1178):  handleUpdatestate:false name:null
D/BluetoothMapMasInstance( 5508): set MAP SDP message type : 1
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/HeadsetService( 5508): registerMessageListener
,V/NearbySettings( 1306): MountReceiver.mPrefHandler - 7002,
D/StatusBarManagerService( 1016): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
D/BluetoothSocket( 5508): bindListen(): myUserId = 0
D/StatusBarManagerService( 1016): setIconVisibility slot=bluetooth visible=true,
W/BluetoothAdapter( 5508): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothTile( 1178):  handleUpdatestate:false name:null
,D/PhoneStatusBar( 1178): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
D/WifiP2pService( 1016): sending p2p persistent groups changed broadcast
D/HeadsetService( 5508): registerMessageListener
D/BluetoothTile( 1178):  handleUpdatestate:false name:null
D/HeadsetStateMachine( 5508): Disconnected process message: 70
,I/libpersona( 5657): KNOX_SDCARD checking this for 10068
D/HeadsetStateMachine( 5508): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@10e43616
I/libpersona( 5657): KNOX_SDCARD not a persona
E/Zygote  ( 5657): MountEmulatedStorage()
E/Zygote  ( 5657): v2
,I/SELinux ( 5657): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=5657 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5657): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
D/WifiP2pService( 1016): InactiveState
E/SELinux ( 5657): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/WifiP2pService( 1016): InactiveState{ what=143376 }
D/WifiP2pService( 1016): P2pEnabledState{ what=143376 }
I/wpa_supplicant( 5576): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
I/Telecom ( 1441): BluetoothPhoneService: handleMessage(7) / param null
I/Telecom ( 1441): BluetoothPhoneService: updateHeadsetWithCallState
,E/ConnectivityService( 1016): updateNetworkInfo()
D/WifiP2pService( 1016): InactiveState{ what=143376 }
D/WifiP2pService( 1016): P2pEnabledState{ what=143376 }
,D/BluetoothSocket( 5508): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
D/BluetoothSocket( 5508): bindListen(), new LocalSocket 
D/BluetoothSocket( 5508): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 5508): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@24a9eb97
D/BluetoothSocket( 5508): channel: 19
I/Telecom ( 1441): BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
D/BluetoothPbapService( 5508): PBAP Socket is BluetoothServerSocket
I/Telecom ( 1441): BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
I/Telecom ( 1441): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/BluetoothSocket( 5508): bindListen(): myUserId = 0
W/BluetoothAdapter( 5508): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 5508): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
D/BluetoothSocket( 5508): bindListen(), new LocalSocket 
D/BluetoothSocket( 5508): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 5508): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2feb8184
D/BluetoothSocket( 5508): channel: 5
,D/HeadsetStateMachine( 5508): Disconnected process message: 9
D/HeadsetStateMachine( 5508): mNumActive: 0 mNumHeld: 0 mCallState: 6
,D/audio_hw_primary(  285): adev_set_parameters: enter: A2dpSuspended=false
V/voice   (  285): voice_set_parameters: enter: A2dpSuspended=false
V/voice   (  285): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  285): platform_set_parameters: enter: A2dpSuspended=false
V/msm8974_platform(  285): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  285): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  285): adev_set_parameters: exit
,E/HeadsetStateMachine( 5508): terminateScoUsingVirtualVoiceCall:No present call to terminate
,E/SMD     (  290): DCD OFF
,D/TimaKeyStoreProvider( 5657): TimaSignature is unavailable
,D/ActivityThread( 5657): Added TimaKeyStore provider
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/ResourcesManager( 5657): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/FileShare-Client( 5657): ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/FileShare-Client( 5657): ClientBroadcastReceiver.onReceive - disconnected
,D/FileShare-Client( 5657): Outbound.stopDelayTimer - 
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5672): MountEmulatedStorage(),
E/Zygote  ( 5672): v2
I/libpersona( 5672): KNOX_SDCARD checking this for 10069
I/libpersona( 5672): KNOX_SDCARD not a persona
,I/SELinux ( 5672): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 5672): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1016): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=5672 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,E/SELinux ( 5672): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Killing 4387:com.sec.android.gallery3d/u0a44 (adj 15): empty #31,
,D/TimaKeyStoreProvider( 5672): TimaSignature is unavailable
,D/ActivityThread( 5672): Added TimaKeyStore provider
,D/FileShare-Server( 5672): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,I/ActivityManager( 1016): Killing 3915:com.sec.spp.push/u0a35 (adj 15): empty #31
,W/ContextImpl( 1306): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,D/LocalBluetoothProfileManager( 1306): Adding local A2DP profile
,D/BluetoothA2dp( 1306): doBind(): CallingUid(myUserHandle) = 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/LocalBluetoothProfileManager( 1306): Adding local HEADSET profile
,E/BluetoothHeadset( 1306): BTStateChangeCB is registed
,D/BluetoothHeadset( 1306): doBind(): CallingUid(myUserHandle) = 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 1306): BluetoothHeadset service is binded
,D/BluetoothMap( 1306): Create BluetoothMap proxy object
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,W/ContextImpl( 1306): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/Bluetoothsap( 1306): bindService called to Bluetooth SAP Service
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/LocalBluetoothProfileManager( 1306): PANU : true
W/LocalBluetoothProfileManager( 1306): Warning: SAP profile was previously added.
,D/LocalBluetoothProfileManager( 1306): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 1306): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1306): onReceive
,D/BluetoothA2dp( 1306): Proxy object connected
D/A2dpProfile( 1306): Bluetooth service connected
,V/BluetoothStatusReceiver( 1178): Received android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothStatusReceiver( 1178): AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,D/HeadsetProfile( 1306): Bluetooth service connected
,D/BluetoothAdapterService( 5508): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2954e365
,D/BtConfig.SecureMode( 5508): isSecureModeOn:false
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/AuthorizationBluetoothService( 1697): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothMap( 1306): Proxy object connected
,D/MapProfile( 1306): Bluetooth service connected
D/BluetoothMap( 1306): getConnectedDevices()
,D/BluetoothPbap( 1306): Proxy object connected
,D/PbapServerProfile( 1306): Bluetooth service connected
D/Bluetoothsap( 1306): BluetoothSAP Proxy object connected
,D/SapProfile( 1306): Bluetooth service connected
D/Bluetoothsap( 1306): getConnectedDevices()
,D/BluetoothInputDevice( 1306): Proxy object connected
,D/HidProfile( 1306): Bluetooth service connected
,D/BluetoothPan( 1306): BluetoothPAN Proxy object connected
,D/PanProfile( 1306): Bluetooth service connected
,W/libprocessgroup( 1016): failed to open /acct/uid_10044/pid_4387/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10035/pid_3915/cgroup.procs: No such file or directory
,D/SecContentProvider( 1016): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/BluetoothSocket( 5508): bindListen(): myUserId = 0
,W/BluetoothAdapter( 5508): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 5508): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
D/BluetoothSocket( 5508): bindListen(), new LocalSocket 
D/BluetoothSocket( 5508): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 5508): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@a3f1ee
,D/BluetoothSocket( 5508): channel: 12,
I/BtOppRfcommListener( 5508): Accept thread started.
,I/wpa_supplicant( 5576): nl80211: Received scan results (4 BSSes),
I/wpa_supplicant( 5576): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 5576): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 5576): Trying to associate with  'G700'
I/wpa_supplicant( 5576): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 5576): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,D/WifiMonitor( 1016): didn't find BSSID Trying to associate with SSID 'NG700'
,I/WifiNative-HAL( 1016): startHal
,E/wifi    ( 1016): getStaticLongField sWifiHalHandle 0x9d28b8ac
I/WifiNative-HAL( 1016): Could not start hal
,D/SecContentProvider2( 1016): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1016): mCursor = null
,I/ActivityManager( 1016): Killing 4626:com.sec.spp.push:RemoteNotiProcess/u0a35 (adj 15): empty #31
,E/wpa_supplicant( 5576): Cmd 35605 not handled
,I/wpa_supplicant( 5576): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 5576): wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
I/wpa_supplicant( 5576): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 5576): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 5576): Associated with C0.AA.48
I/wpa_supplicant( 5576): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 5576): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 5576): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
D/Tethering( 1016): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
D/Tethering( 1016): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
D/Tethering( 1016): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1016): interfaceLinkStateChanged wlan0, true
,D/Tethering( 1016): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 5576): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
,I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, true
I/wpa_supplicant( 5576): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
I/wpa_supplicant( 5576): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,I/wpa_supplicant( 5576): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 5576): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 5576): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 5576): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 5576): Blacklist: Clear (temp) 
I/wpa_supplicant( 5576): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
E/Tethering( 1016): No numeric data
D/Tethering( 1016): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1016): clearTetheredNotification()
,D/Tethering( 1016): interfaceLinkStateChanged wlan0, true
D/Tethering( 1016): interfaceStatusChanged wlan0, true
D/SecContentProvider2( 1016): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1016): mCursor = null
,I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, true
,D/NtpTrustedTime( 1016): forceRefresh() from cache miss
,D/HotspotTile( 1178): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
,D/HotspotTile( 1178): updateTetherState():false, false
,D/EnterpriseController(  277): uids 1000
,D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
,D/NtpTrustedTime( 1016): forceRefresh Fail.
,V/NetworkStats( 1016): performPollLocked(flags=0x1)
D/WifiNative-wlan0( 1016): callSECApiVoid - ID [50]
I/ActivityManager( 1016): Killing 5001:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
D/NetworkStatsFactory( 1016): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1016): UpdateStatsForKnox main else ---
V/NetworkStats( 1016): performPollLocked() took 3ms
,D/NtpTrustedTime( 1016): forceRefresh() from cache miss
,D/NtpTrustedTime( 1016): forceRefresh Fail.
E/WifiConfigStore( 1016): setLastSelectedConfiguration -1
,D/ConnectivityService( 1016): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 1016): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 1016): updateNetworkInfo()
D/ConnectivityService( 1016): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiConfigStore( 1016): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/NearbySettings( 1306): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1306): DMSUtil.isNetworkConnected - flag-null, state-null
,I/Hs20UtilService( 3385): Starting #4
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/Hs20UtilService( 3385): Message received 5007
,I/NearbySettings( 1306): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1306): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1306): MountReceiver.mPrefHandler - 7002
E/WifiConfigStore( 1016): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  277): Setting iface cfg
,E/WifiStateMachine( 1016): Start Dhcp Watchdog 1
,D/SecContentProvider2( 1016): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1016): mCursor = null
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiNative-wlan0( 1016): do suspend false
,D/SecContentProvider2( 1016): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1016): mCursor = null
,D/WifiP2pService( 1016): InactiveState{ what=143375 }
,D/WifiP2pService( 1016): P2pEnabledState{ what=143375 }
,W/libprocessgroup( 1016): failed to open /acct/uid_10035/pid_4626/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10100/pid_5001/cgroup.procs: No such file or directory
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 5
,E/dhcpcd  ( 5697): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,I/dhcpcd  ( 5697): version 5.5.6 starting,
,E/dhcpcd  ( 5697): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,I/dhcpcd  ( 5697): wlan0: sending IPv6 Router Solicitation,
E/dhcpcd  ( 5697): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 5697): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 5697): bssid match,
,I/dhcpcd  ( 5697): wlan0: rebinding lease of 192.168.1.137
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,I/dhcpcd  ( 5697): wlan0: acknowledged 192.168.1.137 from 192.168.1.1
,I/dhcpcd  ( 5697): wlan0: leased 192.168.1.137 for 86400 seconds
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4190, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged,
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate,
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,V/HeadsetService( 5508): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5508): Disconnected process message: 10
,D/PackageManager( 1016): [MSG] MCS_UNBIND,
,I/ActivityManager( 1016): Killing 4992:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,W/ProcessCpuTracker( 1016): Skipping unknown process pid 5706
,W/ProcessCpuTracker( 1016): Skipping unknown process pid 5725
,E/WifiNative-wlan0( 1016): do suspend true
,D/WifiP2pService( 1016): InactiveState{ what=143375 }
,D/WifiP2pService( 1016): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiStateMachine( 1016): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
E/WifiStateMachine( 1016): VerifyingLinkState enter
,D/WifiNative-wlan0( 1016): callSECApiInt - ID [210]
,E/ConnectivityService( 1016): updateNetworkInfo()
,D/ConnectivityService( 1016): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,D/ConnectivityService( 1016): Adding iface wlan0 to network 502
,D/WifiWatchdogStateMachine( 1016): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 1016): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 1016): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker( 1016): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1016): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1016): Adding Route [fe80::/64 -> :: wlan0] to network 502
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/ConnectivityService( 1016): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 502
,D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1016): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 502
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/ConnectivityService( 1016): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1016): Setting Dns servers for network 502 to [/192.168.1.1]
,D/ConnectivityService( 1016): LTETest block dns file not exists
W/libprocessgroup( 1016): failed to open /acct/uid_10015/pid_4992/cgroup.procs: No such file or directory
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,E/WifiStateMachine( 1016): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
D/ConnectivityService( 1016): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3385): Starting #5
,I/Hs20UtilService( 3385): Message received 5007
,D/NearbySettings( 1306): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1306): MountReceiver.onReceive - Keep current state
,E/ConnectivityService( 1016): updateNetworkInfo()
E/ConnectivityService( 1016): updateNetworkInfo()
D/ConnectivityService( 1016): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1016): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService( 1016): rematching NetworkAgentInfo [WIFI () - 502]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,I/WifiTrafficPoller( 1016): evaluateTrafficStatsPolling
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,D/ConnectivityService( 1016):    accepting network in place of null
,D/WIFI_P2P( 1016): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/ConnectivityService( 1016): Setting tx/rx TCP buffers to 524288,1048576,4525824,524288,1048576,4525824
,D/TelephonyNetworkFactory( 1464): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/TelephonyNetworkFactory( 1464): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/System.out( 1016): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1016): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1016): (HTTPLog)-Static: isShipBuild true
I/System.out( 1016): (HTTPLog)-Thread-172-321465789: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1016): (HTTPLog)-Static: isSBSettingEnabled false
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiStateMachine( 1016): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/WifiStateMachine( 1016): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/WIFI    ( 1016): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 1000
,I/WifiTrafficPoller( 1016): evaluateTrafficStatsPolling
I/WifiTrafficPoller( 1016): mBoosterFLAG : 0
I/WifiTrafficPoller( 1016): current booster mode : FullMode
D/WifiNative-wlan0( 1016): callSECApiVoid - ID [212]
,E/CSLegacyTypeTracker( 1016): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1016): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
D/ConnectivityService( 1016): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056a/com.android.systemui:drawable/stat_sys_wifi_signal_3 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056a/com.android.systemui:drawable/stat_sys_wifi_signal_3 mQSWifiIconId=0x7f02014e/com.android.systemui:drawable/ic_qs_wifi_3 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1016): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/Tethering( 1016): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1016): MasterInitialState.processMessage what=3
,V/NetworkStats( 1016): updateIfacesLocked()
V/NetworkStats( 1016): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1016): UpdateStatsForKnox updated
D/NtpTrustedTime( 1016): forceRefresh() from cache miss
D/NetworkStatsFactory( 1016): UpdateStatsForKnox main else ---
,D/ConnectivityService( 1016): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
,D/EnterpriseController(  277): uids 1000
V/NetworkStats( 1016): performPollLocked() took 3ms
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 1000
,D/EntConnectivity( 1016): Not allowed due to - mEnabled false - primarySimSlot false
,D/ConnectivityManager.CallbackHandler( 1178): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1178): EthernetConnected: false
D/StatusBar.NetworkController( 1178): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1178): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1178): updateDataNetType()
D/StatusBar.NetworkController( 1178): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1178): updateLTEICONDataNetType:0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3385): Starting #6
,I/Hs20UtilService( 3385): Message received 5007
,D/NearbySettings( 1306): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1306): DMSUtil.isNetworkConnected - flag-null, state-null
,D/StatusBar.NetworkController( 1178): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056a/com.android.systemui:drawable/stat_sys_wifi_signal_3 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056a/com.android.systemui:drawable/stat_sys_wifi_signal_3 mQSWifiIconId=0x7f02014e/com.android.systemui:drawable/ic_qs_wifi_3 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/NearbySettings( 1306): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1306): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/NearbySettings( 1306): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1306): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 3385): Starting #7
,D/WifiStateMachine( 1016): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/Hs20UtilService( 3385): Message received 5007
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravity
,D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravityXOffset
,D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravityYOffset
,D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1016): mCursor = null
,D/NtpTrustedTime( 1016): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1449683615248 mCachedNtpElapsedRealtime : 86325 mCachedNtpCertainty : 18
,D/SecContentProvider2( 1016): uri = 15 selection = getToastShowPackageNameState
D/SecContentProvider2( 1016): mCursor = null
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
I/System.out( 1016): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
V/NetworkStats( 1016): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,I/SurfaceFlinger(  256): id=13 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 1016): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1016
,D/SRIB_DCS( 1178): log_dcs ThreadedRenderer::initialize entered! 
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 09 Dec 2015 17:53:35 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449683615101], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449683615083]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Validated
D/ConnectivityService( 1016): Validated NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1016): rematching NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1016): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
D/ConnectivityService( 1016): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService( 1016): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1178): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1178): EthernetConnected: false
,D/StatusBar.NetworkController( 1178): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1178): getUpdateDataNetType(): mDataTypeBrand = LTE
,D/StatusBar.NetworkController( 1178): updateDataNetType()
D/StatusBar.NetworkController( 1178): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1178): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1178): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056a/com.android.systemui:drawable/stat_sys_wifi_signal_3 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056a/com.android.systemui:drawable/stat_sys_wifi_signal_3 mQSWifiIconId=0x7f02014e/com.android.systemui:drawable/ic_qs_wifi_3 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1016): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/AlarmManagerService( 1016): Setting time of day to sec=1449683615
D/AlarmManagerService( 1016): Trying to open a file
,I/DBG_DM  ( 2789): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 2789): [com.wssyncmldm.llllIIIllIlIIIIllllI(230/onReceive)] ----------- XEVENT_DM_INIT WIFI ok
,D/AlarmManagerService( 1016): File Open Success
D/AlarmManagerService( 1016): File Close Success
I/AlarmManagerService( 1016): DRM_TIME_PATH CHMOD 666 for resetState done 
,V/AlarmManager( 1016): waitForAlarm result :65536
W/AlarmManagerService( 1016): Unable to set rtc to 1449683615: Invalid argument
,I/DBG_DM  ( 2789): [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,V/AlarmManager( 1016): No more alarm at this time.nowELAPSED=86778 batch.start=95011
,I/PCWCLIENTTRACE_PushUtil( 5053): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5053): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5053): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5053): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1016): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=22
I/splitIntent( 1016): base  index=22, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1016): other index=24, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1016): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,D/OTPFW   ( 1016): OTPTimeChangeLogger :: TimeChangeListener$onReceive | Device Time Changed. Current time = 1449683615698
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_SET
D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/WifiStateMachine( 1016): android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
I/DowntimeConditions( 1016): android.intent.action.TIME_SET ignored because schedule turned off.
,D/SecKeyguardClockView( 1178): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1178): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_SET
,I/DBG_DM  ( 2789): [IlIlllIlllllIlIllllI(403/llIIllllIIlllIIIIlll)] Check completed.
,I/DBG_DM  ( 2789): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,W/Settings( 1016): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SettingsProvider( 1016): name = lockscreen_zoom_panning_effect
I/libpersona( 5742): KNOX_SDCARD checking this for 10111
,D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
I/libpersona( 5742): KNOX_SDCARD not a persona
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 10054
,D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
E/Zygote  ( 5742): MountEmulatedStorage()
E/Zygote  ( 5742): v2
,I/SELinux ( 5742): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1016): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5742 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 5742): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 5742): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=10054
,D/KeyguardEffectViewUtil( 1178): isStrongPowerSavingMode() :false
I/DBG_DM  ( 2789): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 2789): [IIlIIIlllllIIlIIIlII(91/llllIIIllIlIIIIllllI)] 
,D/KeyguardEffectViewController( 1178): isPreloadedWallpaper=true
I/GeometricMosaic_Keyguard( 1178): update
,D/KeyguardEffectViewUtil( 1178): getCurrentWallpaper() mWallpaperPath :null
,W/SEC_DRM_PLUGIN_Playready(  284): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK after: 1449683615 after conversion: 1449683615
W/SEC_DRM_PLUGIN_Playready(  284): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK before: 1449683615 after conversion: 1449683615
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncService; callingUser = 0; userId(target) = 0
,I/DBG_DM  ( 2789): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,D/TimaKeyStoreProvider( 5742): TimaSignature is unavailable
,D/ActivityThread( 5742): Added TimaKeyStore provider
,I/DBG_DM  ( 2789): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,I/DBG_DM  ( 2789): [com.wssyncmldm.db.file.XDB(6236/IlIIlIIlIllllIlllIII)] Initiated Type: 2
,I/DBG_DM  ( 2789): [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,I/DBG_DM  ( 2789): [IlIlllIlllllIlIllllI(251/lllIlIlIIIllIIlIllIl)] XDL_STATE_READY_TO_UPDATE
,I/DBG_DM  ( 2789): [IlIIlIIlIllllIlllIII(274/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,I/DBG_DM  ( 2789): [llllIIIllIllIlllIIlI(772/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0
,I/DBG_DM  ( 2789): [llllIlllIIIlIlIlIIII(49/llIIIIlllllIIllIIllI)] 
,I/DBG_DM  ( 2789): [IlIIlIIlIllllIlllIII(1901/llllIIIllIlIIIIllllI)] 
,I/DBG_DM  ( 2789): [com.wssyncmldm.DMSecBroadcastReceiver(572/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,I/DBG_DM  ( 2789): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(503/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 2789): [IIllIIIIlIlIlIlIllII(49/IIIlIIllIlIIllIlllII)] FirmwareObjectSize:387678779
,I/DBG_DM  ( 2789): [IIllIIIIlIlIlIlIllII(1715/llllllIllIlIlllIIlIl)] 
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/KeyguardEffectViewUtil( 1178): set current wallpaper info
D/SettingsProvider( 1016): name = keyguard_current_wallpaper_type
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 10054
I/libpersona( 5758): KNOX_SDCARD checking this for 10075
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
I/libpersona( 5758): KNOX_SDCARD not a persona
D/SettingsProvider( 1016): ret = -1
D/SettingsProvider( 1016): name = keyguard_current_wallpaper_file_path
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 10054
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
E/Zygote  ( 5758): MountEmulatedStorage()
E/Zygote  ( 5758): v2
I/SELinux ( 5758): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/SettingsProvider( 1016): ret = -1
,D/SettingsProvider( 1016): name = keyguard_current_wallpaper_res_id
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 10054
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,I/ActivityManager( 1016): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=5758 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 5758): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 5758): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5758): TimaSignature is unavailable
,D/ActivityThread( 5758): Added TimaKeyStore provider
,I/DBG_DM  ( 2789): [com.wssyncmldm.db.file.XDB(5178/IIIIlIllIlllIlIIIIlI)] Data Margin : 500
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.metadata.sync.syncadapter.SyncAdapterService; callingUser = 0; userId(target) = 0
,I/DBG_DM  ( 2789): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Data App Weight : 0.0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.gallery3d/com.sec.android.gallery3d.remote.picasa.PicasaService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 2789): [com.wssyncmldm.db.file.XDB(5258/llllIIlIlIIIIllIlIIl)] Delta Weight : 0.5
,D/TEST    ( 1178): run!!!
,I/DBG_DM  ( 2789): [com.wssyncmldm.db.file.llllIIIllIlIIIIllllI(194/llIIIIlllllIIllIIllI)] ### Data Margin only: 718127389
I/MusicStore( 5742): Database version: 120
,I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
,I/GeometricMosaic_Renderer( 1178): setBackgroundBitmap
,I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text,
I/DBG_DM  ( 2789): [com.wssyncmldm.llIIllllIIlllIIIIlll(1125/handleMessage)] event ->220
,D/KeyguardEffectViewController( 1178): isPreloadedWallpaper=true
,E/Zygote  ( 5776): MountEmulatedStorage(),
I/ActivityManager( 1016): Start proc com.sec.android.gallery3d for service com.sec.android.gallery3d/.remote.picasa.PicasaService: pid=5776 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a,
E/Zygote  ( 5776): v2
I/libpersona( 5776): KNOX_SDCARD checking this for 10044,
I/libpersona( 5776): KNOX_SDCARD not a persona
,I/SELinux ( 5776): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,D/GpsLocationProvider( 1016): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/SELinux ( 5776): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 5776): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/DBG_DM  ( 2789): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 2789): [com.wssyncmldm.XDMService(712/lllIIIIllIlIlllllllI)] 
,I/DBG_DM  ( 2789): [com.wssyncmldm.db.file.XDB(5018/IIllIIllIIIlllIlIIll)] Get Autoinstall status : false
,I/DBG_DM  ( 2789): [com.wssyncmldm.XDMService(468/lIllIllllIIIlllIlllI)] 
,E/DBG_DM  ( 2789): [com.wssyncmldm.XDMService(476/lIllIllllIIIlllIlllI)] didn't register
,E/DBG_DM  ( 2789): [com.wssyncmldm.XDMService(477/lIllIllllIIIlllIlllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@2b3f7d1c
,I/DBG_DM  ( 2789): [llllIIIllIllIlllIIlI(726/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
,I/DBG_DM  ( 2789): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,D/TimaKeyStoreProvider( 5776): TimaSignature is unavailable
,D/ActivityThread( 5776): Added TimaKeyStore provider
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5742): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,I/DBG_DM  ( 2789): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,I/DBG_DM  ( 2789): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(649/IIIIllIlIIlIIIIlllIl)] nWidgetStatus : 2
,W/ContextImpl( 2789): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.wssyncmldm.ui.llllIIIllIlIIIIllllI.IIIIllIlIIlIIIIlllIl:652 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:172 llllIIIllIllIlllIIlI.llIIIIlllllIIllIIllI:732 
,W/ResourcesManager( 5776): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5776): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5776): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5776): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5776): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 5776): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 5776): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5776): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/SettingsProvider( 1016): name = SOFTWARE_UPDATE_NOTIFICATION_STATUS
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
,I/DBG_DM  ( 2789): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 2789): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,E/GpsLocationProvider( 1016): No APN found to select.
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5742): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5742): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/WindowManager( 1016): showStatusBarByNotification() mOpenByNotification=false
,I/DBG_DM  ( 2789): [com.wssyncmldm.ui.XUIFotaPostponeActivity(337/llIIIIlllllIIllIIllI)] 
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravityEnabledState
W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
D/SecContentProvider2( 1016): mCursor = null
,W/ResourcesManager( 1178): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravity
D/SecContentProvider2( 1016): mCursor = null
,I/DBG_DM  ( 2789): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravityXOffset
D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravityYOffset
D/SecContentProvider2( 1016): mCursor = null
,D/NearbySource( 5776): Nearby Source Create!
,D/NearbyContext( 5776): Nearby Context Create!
,W/ResourcesManager( 5742): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
,W/ResourcesManager( 5742): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5776): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource( 5776): Samsung link source created
,D/KnoxNotification( 1178): ----- inflateViews : modified publicViewLocal -----
,E/Auth.Api.Credentials( 1833): [CredentialSyncAdapter] Unknown sync event.
,D/KnoxNotification( 1178): ----- inflateViews : modified KnoxViewLocal -----
,D/SecContentProvider2( 1016): uri = 15 selection = getToastEnabledState
D/SecContentProvider2( 1016): mCursor = null
,D/PersonaManager( 1178): PersonaID is invalid or persona doesn't exists. : 0
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
D/PersonaManager( 1178): isKioskContainerExistOnDevice
,D/ContactProvider( 5776): getAllContactInfoList Start
,D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
V/JNIHelp ( 5742): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/DriveInitializer( 1833): Background init thread started
,D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,W/ActivityThread( 5742): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5742): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1de55cbd: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5742): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5742): GMSCore installation verified
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncService; callingUser = 0; userId(target) = 0
,I/DBG_DM  ( 2789): [com.wssyncmldm.db.file.XDB(5457/lllIIIIllIlIlllllllI)] Set Download Postpone status : 8
,I/DBG_DM  ( 2789): [com.wssyncmldm.ui.XUIFotaPostponeActivity(386/llIIIIlllllIIllIIllI)] No idle Postpone
,I/DBG_DM  ( 2789): [com.wssyncmldm.ui.XUIFotaPostponeActivity(474/llIIIIlllllIIllIIllI)] 
,W/GAV2    ( 5758): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ConfigStore( 5742): Config Database version: 1
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,I/dhcpcd  ( 5697): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 5697): wlan0: sendmsg: Cannot assign requested address
W/ContextImpl( 1833): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,I/BooksApp( 5758): Created application version: 3.6.9 (30609)
,W/DriveInitializer( 1833): Awaiting to be initialized
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 58316(3MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 26MB/40MB, paused 2.614ms total 199.615ms,
D/SecContentProvider2( 1016): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1016): mCursor = null
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ContactProvider( 5776): getAllContactInfoList End
,I/syncContacts( 5776): thread: 988, sync time = 282
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 1697): Explicit concurrent mark sweep GC freed 8725(442KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 10MB/17MB, paused 999us total 44.468ms
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/BooksSync( 5758): Starting books sync for 61035162, extras: ade
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,W/DriveInitializer( 1833): Background init thread ended
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1016): getStreamVolume 3 index 0
,I/MediaRouter( 5742): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,V/MusicLeanback( 5742): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/NetworkMonitor( 5742): type=WIFI subType= reason=null isConnected=true
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,D/btif_config_util( 5508): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/NetworkMonitor( 5742): type=WIFI subType= reason=null isConnected=true
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5836): MountEmulatedStorage()
,E/Zygote  ( 5836): v2
I/libpersona( 5836): KNOX_SDCARD checking this for 10002
I/libpersona( 5836): KNOX_SDCARD not a persona
,I/SELinux ( 5836): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5836): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5836): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=5836 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SQLiteLog( 5758): (284) automatic index on view_volumes(volume_id)
,I/GHttpClientFactory( 5742): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 5836): TimaSignature is unavailable
,I/GoogleURLConnFactory( 5742): Using platform SSLCertificateSocketFactory
,D/ActivityThread( 5836): Added TimaKeyStore provider
,I/art     ( 1833): WaitForGcToComplete blocked for 5.118ms for cause DisableMovingGc
,I/art     ( 1833): WaitForGcToComplete blocked for 5.116ms for cause DisableMovingGc
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SMD     (  290): DCD OFF
,I/BooksConfig( 5758): GmsCore Version = 7.8.99 (2134222-436)
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1016): Killing 5037:com.google.android.apps.docs/u0a91 (adj 15): empty #31
,I/ActivityManager( 1016): Killing 5070:com.samsung.helphub/1000 (adj 15): empty #31
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5858): MountEmulatedStorage()
E/Zygote  ( 5858): v2
I/libpersona( 5858): KNOX_SDCARD checking this for 1000
I/libpersona( 5858): KNOX_SDCARD not a persona
,I/SELinux ( 5858): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=5858 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
I/SELinux ( 5858): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,E/SELinux ( 5858): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/TimaKeyStoreProvider( 5858): TimaSignature is unavailable
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/ActivityThread( 5858): Added TimaKeyStore provider
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
I/art     (  311): Explicit concurrent mark sweep GC freed 8708(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 633us total 28.628ms
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 652us total 16.878ms,
,D/ConnectivityService( 1016): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,fe80::7ef9:eff:fe51:1823/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1016): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService( 1016): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityManager.CallbackHandler( 1178): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1178): CM callback handler got msg 524295
,I/GLSUser ( 1697): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1697): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1697): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1697): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 619us total 19.251ms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/DIAGMON_AGENT( 5858): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/WindowManager( 1016): showStatusBarByNotification() mOpenByNotification=false
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ResourcesManager( 1178): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1178): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.gallery3d/com.sec.android.gallery3d.remote.picasa.PicasaService; callingUser = 0; userId(target) = 0
,W/libprocessgroup( 1016): failed to open /acct/uid_10091/pid_5037/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5070/cgroup.procs: No such file or directory
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/KnoxNotification( 1178): ----- inflateViews : modified publicViewLocal -----
,D/KnoxNotification( 1178): ----- inflateViews : modified KnoxViewLocal -----
,D/PersonaManager( 1178): PersonaID is invalid or persona doesn't exists. : 0
,I/GLSUser ( 1697): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1697): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1697): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1697): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
D/PersonaManager( 1178): isKioskContainerExistOnDevice
,D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 5758): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 5758): Soft error
E/BooksSync( 5758): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5758): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 5758): Sync error
E/BooksSync( 5758): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5758): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 5758): Finished books sync
,D/SyncManager( 1016): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 22306, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/DIAGMON_AGENT( 5858): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/ActivityManager( 1016): Killing 4686:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
,I/DIAGMON_AGENT( 5858): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,D/PicasaService( 5776): start picasa sync,
,D/PicasaService( 5776): end picasa sync
,E/SQLiteLog( 1697): (10) POSIX Error : 11 SQLite Error : 3850
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.metadata.sync.syncadapter.SyncAdapterService; callingUser = 0; userId(target) = 0
,D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/DIAGMON_AGENT( 5858): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 5858): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 5858): ./extraInfo: "NG700"
,I/DIAGMON_AGENT( 5858): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1016): mCursor = null
,W/libprocessgroup( 1016): failed to open /acct/uid_10032/pid_4686/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 5087): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.sync.FitnessSyncAdapterService; callingUser = 0; userId(target) = 0
,I/DBG_POLICYDM( 5087): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5087): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 5087): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5087): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5087): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5880): MountEmulatedStorage()
I/ActivityManager( 1016): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=5880 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 5880): v2
I/libpersona( 5880): KNOX_SDCARD checking this for 10009
I/libpersona( 5880): KNOX_SDCARD not a persona
,I/SELinux ( 5880): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 5880): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 5880): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5880): TimaSignature is unavailable
,D/ActivityThread( 5880): Added TimaKeyStore provider
,I/ActivityManager( 1016): Killing 5139:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,I/ActivityManager( 1016): Killing 5122:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #32
,I/FOTA_Client( 5880): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,W/FOTA_Client( 5880): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/ActivityManager( 1016): Killing 4756:com.android.vending/u0a28 (adj 15): empty #31
,I/KLMS-2.5.183: ( 3417): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Dec 09 18:53:37 GMT+01:00 2015
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.183: ( 3417): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.183: ( 3417): KLMSIntentService(): onCreate()
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
I/KLMS-2.5.183: ( 3417): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
I/KLMS-2.5.183: ( 3417): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.183: ( 3417): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3417): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,E/Zygote  ( 5900): MountEmulatedStorage()
E/Zygote  ( 5900): v2
I/libpersona( 5900): KNOX_SDCARD checking this for 10034
I/libpersona( 5900): KNOX_SDCARD not a persona
,I/SELinux ( 5900): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/ActivityManager( 1016): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=5900 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a,
,I/SELinux ( 5900): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/KLMS-2.5.183: ( 3417): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,E/SELinux ( 5900): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.183: ( 3417): StateImplV2(): networkChangeListener().START
,I/KLMS-2.5.183: ( 3417): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.5.183: ( 3417): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.5.183: ( 3417): StateImplV2(): networkChangeListener().END
,D/TimaKeyStoreProvider( 5900): TimaSignature is unavailable
,I/KLMS-2.5.183: ( 3417): KLMSIntentService(): onDestroy()
,D/ActivityThread( 5900): Added TimaKeyStore provider
,W/libprocessgroup( 1016): failed to open /acct/uid_10156/pid_5139/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10152/pid_5122/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10028/pid_4756/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 5087): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/SA      ( 5287): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
,I/SA      ( 5287): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 5287): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5287): [SLFUCHKMGR] constructor called
,I/SA      ( 5287): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5287): [OR] == isSIMCardReady false ==
,I/DBG_POLICYDM( 5087): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected,
I/DBG_POLICYDM( 5087): [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
I/SA      ( 5287): [SCU] == networkStateCheck == true
I/SA      ( 5287): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5287): isChinaCountryCode : false
I/SA      ( 5287): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 5287): [OR] == networkStateCheck true ==
E/DBG_POLICYDM( 5087): [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,E/DBG_POLICYDM( 5087): [com.policydm.XDMBroadcastReceiver(240/xdmNotInitSetResume)] DM Not Init
,I/DBG_POLICYDM( 5087): [com.policydm.XDMApplication(246/xdmInitializing)] ----------- XEVENT_DM_INIT WIFI ok
,I/DBG_POLICYDM( 5087): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/DBG_POLICYDM( 5087): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/SA      ( 5287): [OR] GetMyCountryZoneTask
,I/SA      ( 5287): [OR] onReceive END
,I/ActivityManager( 1016): Killing 5201:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,I/DBG_POLICYDM( 5087): [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
,V/DownloadManager( 1230): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/DBG_POLICYDM( 5087): [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
,D/accuweather( 1568): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/SA      ( 5287): [SRS] prepareGetMyCountryZone
,I/DBG_POLICYDM( 5087): [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
,D/SecContentProvider2( 1016): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1016): mCursor = null
,D/daemonapp( 1285): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 8
,D/accuweather( 1568): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1568): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1568): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,I/SA      ( 5287): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
D/accuweather( 1568): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,I/SA      ( 5287): [SSP] query invoked
,I/SA      ( 5287): [TPMU] GetMccFromDB : null
I/SA      ( 5287): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5287): [TPM] isNoProxy(default) : true
,D/accuweather( 1568): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1568): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/DBG_POLICYDM( 5087): [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/File    ( 5287): fail readDirectory() errno=2
,I/DBG_POLICYDM( 5087): [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,E/Zygote  ( 5925): MountEmulatedStorage(),
E/Zygote  ( 5925): v2
,I/libpersona( 5925): KNOX_SDCARD checking this for 10125
I/libpersona( 5925): KNOX_SDCARD not a persona
I/SELinux ( 5925): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 5925): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
E/SELinux ( 5925): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=5925 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
I/DBG_POLICYDM( 5087): [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
,I/DBG_POLICYDM( 5087): [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,I/DBG_POLICYDM( 5087): [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
,I/DBG_POLICYDM( 5087): [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
,I/DBG_POLICYDM( 5087): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2015/12/15/15:15:43
,I/DBG_POLICYDM( 5087): [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2015/12/09/18:53:37
,I/DBG_POLICYDM( 5087): [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
,I/DBG_POLICYDM( 5087): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
,D/TimaKeyStoreProvider( 5925): TimaSignature is unavailable
,D/ActivityThread( 5925): Added TimaKeyStore provider
,I/DBG_POLICYDM( 5087): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5087): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/DBG_POLICYDM( 5087): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,W/ResourcesManager( 5925): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5925): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 5925): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/DBG_POLICYDM( 5087): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,I/DBG_POLICYDM( 5087): [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,I/DBG_POLICYDM( 5087): [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,I/DBG_POLICYDM( 5087): [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
,W/libprocessgroup( 1016): failed to open /acct/uid_10072/pid_5201/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 5087): [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
,I/DBG_POLICYDM( 5087): [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
,I/DBG_POLICYDM( 5087): [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,D/QuickConnect( 5925): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 5925): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 5925): PeriphStartReceiver.onReceive - no need to start
,I/DBG_POLICYDM( 5087): [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
I/DBG_POLICYDM( 5087): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
,D/SecurityLogAgent( 5610): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 5610): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5610): StateMachine : Current State = 1
,I/DBG_POLICYDM( 5087): [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,D/SecurityLogAgent( 5610): StateMachine : Changed Current State = 1
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5940): MountEmulatedStorage()
I/libpersona( 5940): KNOX_SDCARD checking this for 10159
E/Zygote  ( 5940): v2
I/libpersona( 5940): KNOX_SDCARD not a persona
I/SELinux ( 5940): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1016): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=5940 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5940): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1016): Killing 5022:com.android.mms/u0a46 (adj 15): empty #31
E/SELinux ( 5940): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/DBG_POLICYDM( 5087): [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
,D/TimaKeyStoreProvider( 5940): TimaSignature is unavailable
,D/ActivityThread( 5940): Added TimaKeyStore provider
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,I/ActivityManager( 1016): Killing 5219:com.wsomacp/u0a25 (adj 15): empty #31
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/CountryDetector( 1016): No listener is left
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
,I/DBG_POLICYDM( 5087): [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
,I/DBG_POLICYDM( 5087): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,W/libprocessgroup( 1016): failed to open /acct/uid_10046/pid_5022/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10025/pid_5219/cgroup.procs: No such file or directory
,I/iu.SyncManager( 1833): SYNC; picasa accounts
,I/DBG_POLICYDM( 5087): [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
,D/NetworkLogImpl( 1833): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1833): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1833): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1833): Loading module com.google.android.gms.kids from APK com.google.android.gms
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/iu.UploadsManager( 1833): num queued entries: 0
,I/iu.UploadsManager( 1833): num updated entries: 0
,I/iu.SyncManager( 1833): NEXT; no task
,E/Zygote  ( 5963): MountEmulatedStorage(),
E/Zygote  ( 5963): v2
,I/libpersona( 5963): KNOX_SDCARD checking this for 10104
I/libpersona( 5963): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5963 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SELinux ( 5963): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5963): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5963): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5963): TimaSignature is unavailable
,D/ActivityThread( 5963): Added TimaKeyStore provider
,W/ResourcesManager( 5963): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 31486(1521KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 26MB/40MB, paused 2.781ms total 164.903ms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1697): Connected
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1697): Message class com.google.f.a.a.p
,I/GLSUser ( 1697): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1697): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1697): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1697): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
D/PersonaManager( 1178): isKioskContainerExistOnDevice
,D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
W/Kids    ( 1833): [AccountUtils] Account not ready
W/Kids    ( 1833): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1833): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1833): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1833): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1833): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1833): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1833): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1833): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1833): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1833): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1833): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1833): 	at java.lang.Thread.run(Thread.java:818)
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,I/Babel_SMS( 5963): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 5963): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5963): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,I/Babel_SMS( 5963): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5963): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5963): MmsConfig.loadFromResources
,E/Babel_SMS( 5963): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 5963): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,W/QCamera2Factory(  285): getCameraInfo: E, camera_id = 0
W/QCamera2Factory(  285): getCameraInfo: X
,W/QCamera2Factory(  285): getCameraInfo: E, camera_id = 1
W/QCamera2Factory(  285): getCameraInfo: X
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/Settings( 5963): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5963): startup - clean
,I/Babel   ( 5963): deleted: false for 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,I/SurfaceFlinger(  256): id=13 Removed Uoast (8/9)
,I/SurfaceFlinger(  256): id=13 Removed Uoast (-2/9)
,D/PowerManagerService( 1016): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1016) eventTime = 89854
,D/PowerManagerService( 1016): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1016 (0x0)
,D/PowerManagerService( 1016): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1016, ws=WorkSource{10054}) (elapsedTime=3489)
,D/OpenGLRenderer( 2789): Render dirty regions requested: true
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/SurfaceFlinger(  256): id=14 createSurf (1x1),1 flag=4, Uoast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/PowerManagerService( 1016): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1016,
,E/Zygote  ( 5991): MountEmulatedStorage(),
I/ActivityManager( 1016): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=5991 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 5991): v2
I/libpersona( 5991): KNOX_SDCARD checking this for 10035
I/libpersona( 5991): KNOX_SDCARD not a persona,
,I/SELinux ( 5991): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 5991): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 5991): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
,D/SRIB_DCS( 2789): log_dcs ThreadedRenderer::initialize entered! 
,I/Adreno-EGL( 2789): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 2789): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 2789): Build Date: 04/06/15 Mon
I/Adreno-EGL( 2789): Local Branch: 
I/Adreno-EGL( 2789): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 2789): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 2789):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/OpenGLRenderer( 2789): Initialized EGL, version 1.4
,W/VideoCapabilities( 5963): Unrecognized profile 2130706433 for video/avc
,D/TimaKeyStoreProvider( 5991): TimaSignature is unavailable
,D/OpenGLRenderer( 2789): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 2789): Enabling debug mode 0
D/ActivityThread( 5991): Added TimaKeyStore provider
,W/AudioCapabilities( 5963): Unsupported mime audio/evrc
,W/AudioCapabilities( 5963): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5963): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 5963): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 5963): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 5963): Unsupported mime audio/x-ima
,W/AudioCapabilities( 5963): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5963): Unsupported mime audio/evrc
,W/VideoCapabilities( 5963): Unsupported mime video/wvc1
,W/VideoCapabilities( 5963): Unsupported mime video/x-ms-wmv
,I/SA      ( 5287): [RC New] Execute method=[GET] start
,W/VideoCapabilities( 5963): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 5963): Unsupported mime video/wvc1
,W/VideoCapabilities( 5963): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 5963): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 5963): Unsupported mime video/x-ms-wmv8
,E/SPPClientService( 5991): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 5991): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
E/SPPClientService( 5991): [SystemStateMoniter] Current Time : 90070
E/SPPClientService( 5991): [PushClientApplication] Push log off : This is Ship build version
,W/VideoCapabilities( 5963): Unsupported mime video/mp43
E/SPPClientService( 5991): [SystemStateMoniter] No Connect : false
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/VideoCapabilities( 5963): Unsupported mime video/sorenson
,W/VideoCapabilities( 5963): Unsupported mime video/mp4v-esdp
,D/SPPClientService( 5991): PushLog.txt file is not deleted.
,D/SPPClientService( 5991): PushLog.txt file is not deleted.
D/SPPClientService( 5991): ============PushLog. stop!
,I/SA      ( 5287): [RC New] Security=[true]
,E/Zygote  ( 6009): MountEmulatedStorage()
E/Zygote  ( 6009): v2
I/libpersona( 6009): KNOX_SDCARD checking this for 10113
I/libpersona( 6009): KNOX_SDCARD not a persona
,I/SELinux ( 6009): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/System.out( 5287): Thread-905(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/ActivityManager( 1016): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6009 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
I/SELinux ( 6009): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6009): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/System.out( 5287): Thread-905(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5287): Thread-905(ApacheHTTPLog):isShipBuild true
I/System.out( 5287): Thread-905(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5287): Thread-905(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  277): uids 10041
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10041
,I/VideoCapabilities( 5963): Unsupported profile 4 for video/mp4v-es
,D/TimaKeyStoreProvider( 6009): TimaSignature is unavailable
,D/ActivityThread( 6009): Added TimaKeyStore provider
,W/VideoCapabilities( 5963): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5963): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5963): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager( 1016): Killing 5239:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,W/VideoCapabilities( 5963): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 5963): onServiceConnected
,W/Babel   ( 5963): Attempted to change video mute state without an active call.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 5963): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 5963): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 5963): (HTTPLog)-Static: isShipBuild true
I/System.out( 5963): (HTTPLog)-Thread-1031-711344088: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 5963): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10104
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10104
,I/System.out( 5963): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6009): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,I/GAv4    ( 6009): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6009):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6009):   adb logcat -s GAv4
,W/ContextImpl( 6009): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/ActivityManager( 1016): Waited long enough for: ServiceRecord{1a749381 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6009): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,W/GAv4    ( 6009): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup( 1016): failed to open /acct/uid_10047/pid_5239/cgroup.procs: No such file or directory
,I/Babel   ( 5963): connection state changed from UNKNOWN to CONNECTED
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6009): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/ActivityManager( 1016): Killing 5154:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty #31
,W/GAv4    ( 6009): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6009): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup( 1016): failed to open /acct/uid_10038/pid_5154/cgroup.procs: No such file or directory
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/WebViewFactory( 6009): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/LibraryLoader( 6009): Time to load native libraries: 1 ms (timestamps 514-515)
,I/LibraryLoader( 6009): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6009): Binding Chromium to main looper Looper (main, tid 1) {31742cab}
,I/LibraryLoader( 6009): Expected native library version number "",actual native library version number ""
,I/chromium( 6009): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6009): Initializing chromium process, singleProcess=true
,W/art     ( 6009): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6009): ApplicationContext is null in ApplicationStatus
,W/chromium( 6009): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6009): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6009): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6009): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6009): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6009): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6009): Local Branch: 
I/Adreno-EGL( 6009): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6009): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6009):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/NSApplication( 6009): Starting up...
,W/AudioManagerAndroid( 6009): Requires BLUETOOTH permission
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6069): MountEmulatedStorage()
E/Zygote  ( 6069): v2
I/libpersona( 6069): KNOX_SDCARD checking this for 10081
I/libpersona( 6069): KNOX_SDCARD not a persona
,I/SELinux ( 6069): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 6069): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 6069): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6069 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 5268:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6069): TimaSignature is unavailable
,D/ActivityThread( 6069): Added TimaKeyStore provider
,E/SQLiteLog( 1697): (10) POSIX Error : 11 SQLite Error : 3850
,I/SA      ( 5287): [RC New] [v2liruge] api execute + 703
,I/SA      ( 5287): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out( 5287): AsyncTask #1 calls detatch()
,I/SA      ( 5287): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 5287): [OCP] update openData : PL
,I/SA      ( 5287): [TPMU] getNetworkMcc : 
,I/SA      ( 5287): [SCU] saveMccToPreferece Start
,I/SA      ( 5287): [SCU] RegionMCC : 260
I/SA      ( 5287): [SSP] query invoked
,I/SA      ( 5287): [TPMU] GetMccFromDB : null
,I/SA      ( 5287): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5287): [SCU] saveMccToPreferece End
,I/SA      ( 5287): [RC New] executeRequest [v2liruge] end. 787
I/SA      ( 5287): [RC New] Execute end
I/SA      ( 5287): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 5287): [OR] GetMyCountryZoneTask Success
,W/libprocessgroup( 1016): failed to open /acct/uid_10053/pid_5268/cgroup.procs: No such file or directory
,D/WaitQueueForNetworkActivate( 5430): notifyNetworkActivated
,W/ContextImpl( 5430): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,I/splitIntent( 1016): Split this intent : android.intent.action.TIME_SET, mSplitNum[0]=7, mSplitNum[1]=12, mSplitNum[2]=17, mBgSplitQueueNum=3 divideNum= 5 r.nextReceiver= 1 receivers.size=23
,I/splitIntent( 1016): finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,D/hcjo    ( 5430): AutoUpdateManager:IDLE:execute
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/InitializeManagerStateMachine( 5430): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 5430): exit::IDLE
D/InitializeManagerStateMachine( 5430): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 5430): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5430): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5430): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5430): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5430): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5430): entry::SUCCESS
D/hcjo    ( 5430): AutoUpdateManager:INITCHECK:onInitializeSuccess
E/SMD     (  290): DCD OFF
,E/Zygote  ( 6092): MountEmulatedStorage()
E/Zygote  ( 6092): v2
I/libpersona( 6092): KNOX_SDCARD checking this for 10062
I/libpersona( 6092): KNOX_SDCARD not a persona
,I/SELinux ( 6092): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1016): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=6092 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6092): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/SELinux ( 6092): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6102): MountEmulatedStorage()
,I/ActivityManager( 1016): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6102 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
E/Zygote  ( 6102): v2
,I/libpersona( 6102): KNOX_SDCARD checking this for 10135,
I/SELinux ( 6102): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/libpersona( 6102): KNOX_SDCARD not a persona
,D/hcjo    ( 5430): AutoUpdateTriggerManager:IDLE:setInterval:345600000
I/SELinux ( 6102): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6102): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/FOTA_Client( 5880): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,D/TimaKeyStoreProvider( 6092): TimaSignature is unavailable
,D/ActivityThread( 6092): Added TimaKeyStore provider
,D/hcjo    ( 5430): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5430): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5430): exit::SUCCESS
D/InitializeManagerStateMachine( 5430): entry::IDLE
,D/daemonapp( 1285): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1285): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1285): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/TimaKeyStoreProvider( 6102): TimaSignature is unavailable
,D/ActivityThread( 6102): Added TimaKeyStore provider
,I/FOTA_Client( 5880): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,I/ActivityManager( 1016): Killing 5298:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,D/daemonapp( 1285): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/KLMS-2.5.183: ( 3417): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Wed Dec 09 18:53:40 GMT+01:00 2015
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/daemonapp( 1285): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,I/KLMS-2.5.183: ( 3417): KLMSAbstractReciever(): onReceive().END.
,D/daemonapp( 1285): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,D/comsamsunglog( 1285): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1285): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1285): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1285): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1285): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1285): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/KLMS-2.5.183: ( 3417): KLMSIntentService(): onCreate()
,I/SA      ( 5287): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,I/KLMS-2.5.183: ( 3417): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.183: ( 3417): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,W/ResourcesManager( 6102): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6102): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6102): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KLMS-2.5.183: ( 3417): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,I/KLMS-2.5.183: ( 3417): KLMSIntentService(): TIME_CHANGED
,I/KLMS-2.5.183: ( 3417): StateImplV2(): dateTimeChanged().START : Wed Dec 09 18:53:40 GMT+01:00 2015
,D/daemonapp( 1285): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/daemonapp( 1285): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1285): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1285): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1285): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/KLMS-2.5.183: ( 3417): StateImplV2(): dateTimeChanged().END
,I/KLMS-2.5.183: ( 3417): KLMSIntentService(): onDestroy()
,E/daemonapp( 1285): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ExternalOEMControlProvider( 6092): onCreate
,I/ActivityManager( 1016): Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=6125 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
D/comdaemonstockapp( 1285): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
D/comdaemonstockapp( 1285): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,E/Zygote  ( 6125): MountEmulatedStorage()
E/Zygote  ( 6125): v2
I/libpersona( 6125): KNOX_SDCARD checking this for 10046
I/libpersona( 6125): KNOX_SDCARD not a persona
,I/SELinux ( 6125): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6125): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6125): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/accuweather( 1568): [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,D/accuweather( 1568): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/TimaKeyStoreProvider( 6125): TimaSignature is unavailable
D/ActivityThread( 6125): Added TimaKeyStore provider
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/art     (  311): Explicit concurrent mark sweep GC freed 8672(369KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 647us total 44.006ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 598us total 21.319ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 598us total 16.472ms
,E/Zygote  ( 6141): MountEmulatedStorage(),
E/Zygote  ( 6141): v2
,I/SELinux ( 6141): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/libpersona( 6141): KNOX_SDCARD checking this for 10085
I/SELinux ( 6141): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/libpersona( 6141): KNOX_SDCARD not a persona
E/SELinux ( 6141): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=6141 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,I/ Time Manager ( 6092): Time Difference not stored. TIME_DIFFERENCE
,D/TimaKeyStoreProvider( 6141): TimaSignature is unavailable
D/ActivityThread( 6141): Added TimaKeyStore provider
,W/ResourcesManager( 6125): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 6125): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6125): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6125): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6125): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6125): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/daemonapp( 1285): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5298/cgroup.procs: No such file or directory
,W/ResourcesManager( 6141): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6141): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6141): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6141): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6141): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6141): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/SecurityLogAgent( 5610): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 5610): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5610): StateMachine : Current State = 1
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6162): MountEmulatedStorage(),
E/Zygote  ( 6162): v2
I/libpersona( 6162): KNOX_SDCARD checking this for 10042
I/libpersona( 6162): KNOX_SDCARD not a persona
I/SELinux ( 6162): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/SELinux ( 6162): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6162): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/dhcpcd  ( 5697): wlan0: sending IPv6 Router Solicitation,
I/ActivityManager( 1016): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6162 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Mms/MmsApp( 6125): [start]    onCreate() consume time = 0.0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 6162): TimaSignature is unavailable
,D/ActivityThread( 6162): Added TimaKeyStore provider
,E/Zygote  ( 6177): MountEmulatedStorage()
,E/Zygote  ( 6177): v2
I/libpersona( 6177): KNOX_SDCARD checking this for 10157
I/libpersona( 6177): KNOX_SDCARD not a persona
,I/SELinux ( 6177): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1016): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=6177 uid=10157 gids={50157, 9997} abi=armeabi-v7a
,I/SELinux ( 6177): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6177): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6177): TimaSignature is unavailable
,D/ActivityThread( 6177): Added TimaKeyStore provider
,W/ResourcesManager( 6162): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/ResourcesManager( 6177): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SettingsProvider( 1016): name = next_alarm_formatted
,D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 10085
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,I/ActivityManager( 1016): Killing 5324:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,I/CalendarProvider2( 6162): CalendarProvider2.onCreate() called,
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/jxcore-log( 5394): Test app app.js loaded,
I/jxcore-log( 5394): 
I/ActivityManager( 1016): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6193 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
I/ActivityManager( 1016): Killing 5342:com.sec.knox.bridge/1000 (adj 15): empty #31
,E/Zygote  ( 6193): MountEmulatedStorage(),
,E/Zygote  ( 6193): v2
I/libpersona( 6193): KNOX_SDCARD checking this for 1000,
I/libpersona( 6193): KNOX_SDCARD not a persona
,I/SELinux ( 6193): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6193): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 6193): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/Choreographer( 5394): Skipped 678 frames!  The application may be doing too much work on its main thread.
,I/chromium( 5394): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/TimaKeyStoreProvider( 6193): TimaSignature is unavailable
,D/ActivityThread( 6193): Added TimaKeyStore provider
,D/TimeService( 6193): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449683620682
,D/        ( 6193): TimeServiceNative: User Time to be set is 1449683620682
,D/QC-time-services( 6193): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6193): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6193): Lib:time_genoff_operation: pargs->ts_val = 1449683620682
,D/QC-time-services(  326): Daemon: Connection accepted:time_genoff
,D/QC-time-services( 6193): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  326): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449683620682
D/QC-time-services(  326): Daemon:genoff_opr: Base = 2, val = 1449683620682, operation = 0
D/QC-time-services(  326): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/1/70 9:8:7
,D/QC-time-services(  326): Daemon:Value read from RTC seconds = 13079287000
D/QC-time-services(  326): Daemon:new time 1449683620682 
D/QC-time-services(  326): Daemon: delta 1436604333682 genoff 1436604333682 
D/QC-time-services(  326): Daemon:genoff_persistent_update: Writing genoff = 1436604333682 to memory
D/QC-time-services(  326): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  326): Daemon:time_persistent_memory_opr:Genoff write operation 
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5053): mConnectivityHandler : connected
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5324/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5342/cgroup.procs: No such file or directory
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
D/QC-time-services(  326): Updating the TOD offset
,D/QC-time-services(  326): Daemon:genoff_persistent_update: Writing genoff = 1436604333682 to memory
D/QC-time-services(  326): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  326): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  326): Daemon:Update to modem bit set
D/QC-time-services(  326): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  326): Daemon: Base = 2, Value being sent to MODEM = 1120639533682
,E/QC-time-services( 6193): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,E/QC-time-services(  326): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,E/QC-time-services(  326): Daemon: Time-services: Waiting to acceptconnection
,I/ActivityManager( 1016): Killing 5412:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,W/art     ( 6125): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 227.980ms
,W/PCWCLIENTTRACE_AccountUtil( 5053): [hasSamungAccount] - No Samsung Account
,D/SSRM:n  ( 1016): SIOP:: AP = 390
,W/art     ( 6141): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 171.130ms
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5053): [GetString-S]
,I/ReactiveServiceManager( 5053): Supported : 1
,D/QSEECOMAPI: ( 1016): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1016): App is not loaded in QSEE,
,I/ActivityManager( 1016): Killing 5476:com.google.android.gms:car/u0a12 (adj 15): empty #31
,W/libprocessgroup( 1016): failed to open /acct/uid_10057/pid_5412/cgroup.procs: No such file or directory
,D/QSEECOMAPI: ( 1016): Loaded image: APP id = 10
,D/QSEECOMAPI: ( 1016): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1016): QSEECom_shutdown_app, app_id = 10
,E/terrier ( 1016): handleString: Failed to handle string(-4)
E/terrier ( 1016): Java_com_android_server_ReactiveService_GetString: error code = [-4]
,D/PCWCLIENTTRACE_SecurePreferencesJNI( 5053): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5053): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5053): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5053): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5053): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 5053): [ensureRegistration] - No Samsung account
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6217): MountEmulatedStorage(),
E/Zygote  ( 6217): v2
I/libpersona( 6217): KNOX_SDCARD checking this for 10094,
I/libpersona( 6217): KNOX_SDCARD not a persona
,I/SELinux ( 6217): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6217 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 5657:com.samsung.android.app.FileShareClient/u0a68 (adj 15): empty #31,
,I/SELinux ( 6217): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,D/Mms/ArtClassLoader( 6125): init before art
E/SELinux ( 6217): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/Mms/TelephonyPermission( 6125): start operation mode monitor
,W/ResourcesManager( 6125): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 6217): TimaSignature is unavailable
,D/ActivityThread( 6217): Added TimaKeyStore provider
,D/Mms/TelephonyPermission( 6125): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission( 6125): isDefault true
,D/Mms/MmsApp( 6125): onCreate() com.android.mms
,D/Mms/MmsApp( 6125): [start]    initCountryIso consume time = 414.406406
,D/CountryDetector( 1016): The first listener is added
,D/elm:15183( 6217): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:15183( 6217): ELMEngine.ELMEngine( context ).
,D/Mms/MmsApp( 6125): [end]    initCountryIso consume time = 8.603802
D/Mms/MmsConfig( 6125): [start]    MmsConfig.init() consume time = 0.454636
,D/elm:15183( 6217): MDMBridge.setEnterpriseBridge()
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15183( 6217): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/elm:15183( 6217): ElmAgentService : onCreate()
,D/elm:15183( 6217): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,D/Mms/MmsConfig( 6125): before partial update
,D/elm:15183( 6217): ELMAgentService.listeningToTimeDateChanges( context, intent ).
,D/elm:15183( 6217): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). ,
D/elm:15183( 6217): ModuleBase.ModifySetAlarm()
D/elm:15183( 6217): MDMBridge.getInstance()
D/elm:15183( 6217): MDMBridge.getAllLicenseInfoFromSDK()
,D/Mms/MmsConfig( 6125): Load Resize quality : 80
,D/EasySignUpManager_1.0.1( 6125): serviceId : 1, features : -1
,D/EasySignUpManager_1.0.1( 6125): isAuth is false
,D/Mms/MmsConfig( 6125): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,E/Zygote  ( 6237): MountEmulatedStorage()
,E/Zygote  ( 6237): v2
I/libpersona( 6237): KNOX_SDCARD checking this for 10134
I/libpersona( 6237): KNOX_SDCARD not a persona
,I/SELinux ( 6237): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6237): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1016): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=6237 uid=10134 gids={50134, 9997} abi=armeabi-v7a
E/SELinux ( 6237): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1016): Scheduling restart of crashed service com.google.android.gms/.car.InCallServiceImpl in 1000ms
,D/TP/MmsSmsProvider( 1464): query,matched:2117, calling pid = 6125
,D/elm:15183( 6217): ElmAgentService : onDestroy().
,D/TP/MmsSmsProvider( 1464): match 2117:Elapsed time : 1.506 ms
,I/ActivityManager( 1016): Killing 5672:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,D/EasySignUpManager_1.0.1( 6125): isAuth is false
,D/EasySignUpManager_1.0.1( 6125): getServiceStatus : serviceId (1) is OFF
,D/TimaKeyStoreProvider( 6237): TimaSignature is unavailable
,D/ActivityThread( 6237): Added TimaKeyStore provider
,E/CscParser( 6125): mps_code.dat does not exist
E/CscParser( 6125): customer_path =/system/csc/customer.xml
E/CscParser( 6125): fileName + /system/csc/customer.xml
,W/libprocessgroup( 1016): failed to open /acct/uid_10012/pid_5476/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10068/pid_5657/cgroup.procs: No such file or directory
,E/CscParser( 6125): mps_code.dat does not exist
E/CscParser( 6125): customer_path =/system/csc/customer.xml
E/CscParser( 6125): fileName + /system/csc/customer.xml
,W/ResourcesManager( 6237): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6237): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/CscParser( 6125): getInstance fileName =/system/csc/customer.xml
,D/Mms/MmsConfig( 6125):  enable multiwindow = true
,E/Mms/MessageUtils( 6125): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 6125): updateCountryIso : update country iso info 
,D/Mms/MmsConfig( 6125): [end]    init() consume time = 106.748802
,D/Mms/Contact( 6125): [start]    init() consume time = 0.625625
,I/ActivityManager( 1016): Killing 5548:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,D/Mms/Contact( 6125): [end]    init consume time = 13.626927
,D/TP/MmsSmsProvider( 1464): query,matched:13, calling pid = 6125
,D/TP/MmsSmsProvider( 1464): match 13:Elapsed time : 2.016 ms
D/Mms/DraftCache( 6125): [start]    rebuildCache consume time = 4.961354
,D/TP/MmsSmsProvider( 1464): query,matched:12, calling pid = 6125
,D/TP/MmsSmsProvider( 1464): match 12:Elapsed time : 1.673 ms
,D/Mms/MethodReflector( 6125): getSubId is called
D/Mms/TelephonyUtils( 6125): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 6125): getTelephonyProperty is called
D/Mms/DownloadManager( 6125): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 6125): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 6125): auto download without roaming -> true
D/Mms/DownloadManager( 6125): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,D/Mms/DraftCache( 6125): [end]    rebuildCache consume time = 11.970469
,D/Mms/MethodReflector( 6125): getSubId is called
,D/Mms/MethodReflector( 6125): getDefaultSmsSubId is called
,E/Mms/TelephonyUtils( 6125): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 6125): getLongSubId from simSlot 1, return Value = -1000
,D/Mms/MethodReflector( 6125): getTelephonyProperty is called
D/Mms/DownloadManager( 6125): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 6125): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 6125): auto download without roaming -> true
D/Mms/DownloadManager( 6125): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 6125): auto download during roaming secondary -> false
D/Mms/DownloadManager( 6125): mAutoDownload ------> true
,D/ComposerPerformance( 6125): 1449683621046 ms / [DONE] Composer constructor
,E/CII     ( 6125): CommonIMSInterface: VoLTE CSC feature disabled.
,I/Mms/ReservationManager( 6125): ReservationManager()
I/Mms/ReservationManager( 6125): resetAfterConnected()
,D/TP/MmsSmsProvider( 1464): query,matched:7, calling pid = 6125
,D/TP/MmsSmsProvider( 1464): match 7:Elapsed time : 4.281 ms
,I/Mms/ReservationManager( 6125): getReservedSendMessageCount(): retMessageCount=0
D/Mms/Conversation( 6125): [start]    init() consume time = 21.235781
,D/TP/MmsSmsProvider( 1464): deleteConversation threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1464): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
D/Mms/MmsApp( 6125): [end]    onCreate() consume time = 5.638854
,V/TP/MmsSmsDatabaseHelper( 1464): updateThread(), thread_id = 9223372036854775807
,V/TP/MmsSmsDatabaseHelper( 1464): sUpgradeVersion = 0, db.getVersion() = 81
,D/Mms/DownloadManager( 6125): Service state changed: Bundle[mParcelledData.dataSize=744]
,D/Mms/DownloadManager( 6125): roaming ------> false, mSimSlot = 0
,I/splitIntent( 1016): Queue : background intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart  false.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/TP/MmsSmsProvider( 1464): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1464): need read changed broadcast:false
,W/libprocessgroup( 1016): failed to open /acct/uid_10069/pid_5672/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10003/pid_5548/cgroup.procs: No such file or directory
,D/Mms/MethodReflector( 6125): getSubId is called
D/Mms/TelephonyUtils( 6125): getLongSubId from simSlot 0, return Value = -1
,D/Mms/Conversation( 6125): [end]    init consume time = 15.857708
D/Mms/MessagingNotification( 6125): [start]    init() consume time = 0.078646
,I/DBG_POLICYDM( 5087): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,D/Mms/MethodReflector( 6125): getTelephonyProperty is called
D/Mms/DownloadManager( 6125): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 6125): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 6125): auto download without roaming -> true
D/Mms/DownloadManager( 6125): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 6125): mAutoDownload ------> true
,D/Mms/ArtClassLoader( 6125): init [DONE] art
,I/DBG_POLICYDM( 5087): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5087): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5087): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5087): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5087): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5087): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5087): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_POLICYDM( 5087): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,I/DBG_POLICYDM( 5087): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,E/DBG_POLICYDM( 5087): [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,I/DBG_POLICYDM( 5087): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5087): [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 18979(1030KB) AllocSpace objects, 5(100KB) LOS objects, 33% free, 26MB/40MB, paused 2.615ms total 144.296ms
,I/ActivityManager( 1016): Killing 4212:com.google.android.gms.wearable/u0a12 (adj 15): empty #31
,D/Mms/MessagingNotification( 6125): [end]    init consume time = 155.60474
,D/Mms/Synchronizer( 6125): [start]    doSync consume time = 1.898854
,D/TP/MmsSmsProvider( 1464): query,matched:0, calling pid = 6125
V/TP/MmsSmsProvider( 1464): getSimpleConversations entered.
D/TP/MmsSmsProvider( 1464): update, matched:300, calling pid = 6125
V/TP/MmsSmsProvider( 1464): syncDBData start
,V/TP/MmsSmsProvider( 1464): syncDBData sms end
D/TP/MmsSmsProvider( 1464): match 0:Elapsed time : 1.351 ms
V/TP/MmsSmsProvider( 1464): syncDBData mms end
,V/TP/MmsSmsProvider( 1464): syncDBData end
,D/Mms/SpamFilter( 6125): [start]    SpamFilter fill() begin consume time = 4.189167
,D/Mms/Synchronizer( 6125): [end]    doSync consume time = 0.571666
,D/TP/MmsSmsProvider( 1464): query,matched:400, calling pid = 6125
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6261): MountEmulatedStorage(),
E/Zygote  ( 6261): v2
I/libpersona( 6261): KNOX_SDCARD checking this for 10072,
I/libpersona( 6261): KNOX_SDCARD not a persona
,I/SELinux ( 6261): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/ActivityManager( 1016): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6261 uid=10072 gids={50072, 9997} abi=armeabi-v7a
,D/Mms/SpamFilter( 6125): [end]    SpamFilter fill() finished consume time = 24.370677
,I/SELinux ( 6261): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6261): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 6261): TimaSignature is unavailable
,D/ActivityThread( 6261): Added TimaKeyStore provider
,I/ActivityManager( 1016): Killing 4959:com.android.defcontainer/u0a4 (adj 15): empty #31
,D/BadgeProvider( 6261): onCreate
,D/BadgeProvider( 6261): DatabaseHelper
,D/Mms/MessagingNotification( 6125): checkBadgeCount unreadCount=0 badgeCount=0
,D/TP/SmsProvider( 1464): query,matched:26, calling pid = 6125
,D/TP/SmsProvider( 1464): match 26:Elapsed time : 1.306 ms
,D/TP/MmsSmsProvider( 1464): query,matched:6, calling pid = 6125
,D/TP/MmsSmsProvider( 1464): match 6:Elapsed time : 1.040 ms
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6276): MountEmulatedStorage(),
E/Zygote  ( 6276): v2
I/libpersona( 6276): KNOX_SDCARD checking this for 10025
I/libpersona( 6276): KNOX_SDCARD not a persona
,I/SELinux ( 6276): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/ActivityManager( 1016): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=6276 uid=10025 gids={50025, 9997} abi=armeabi-v7a,
,I/SELinux ( 6276): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 6276): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 6276): TimaSignature is unavailable
,D/ActivityThread( 6276): Added TimaKeyStore provider
,I/ActivityManager( 1016): Killing 5053:com.sec.pcw.device/1000 (adj 15): empty #31
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ResourcesManager( 6276): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,I/GAV2    ( 5758): Thread[GAThread,5,main]: No campaign data found.
,W/libprocessgroup( 1016): failed to open /acct/uid_10012/pid_4212/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10004/pid_4959/cgroup.procs: No such file or directory
,I/OMACP   ( 6276): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,D/Mms/Omacp( 6125): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,I/OMACP   ( 6276): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,I/OMACP   ( 6276): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   ( 6276): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,I/OMACP   ( 6276): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   ( 6276): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5053/cgroup.procs: No such file or directory
,I/OMACP   ( 6276): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,I/OMACP   ( 6276): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,I/OMACP   ( 6276): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,I/OMACP   ( 6276): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,I/OMACP   ( 6276): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/OMACP   ( 6276): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/OMACP   ( 6276): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,I/OMACP   ( 6276): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,I/CalendarProvider2( 6162): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,I/ActivityManager( 1016): Killing 5742:com.google.android.music:main/u0a111 (adj 15): empty #31
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6295): MountEmulatedStorage(),
E/Zygote  ( 6295): v2
I/libpersona( 6295): KNOX_SDCARD checking this for 10012
,I/libpersona( 6295): KNOX_SDCARD not a persona
,I/ActivityManager( 1016): Start proc com.google.android.gms:car for service com.google.android.gms/.car.InCallServiceImpl: pid=6295 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a,
I/SELinux ( 6295): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6295): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6295): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,W/libprocessgroup( 1016): failed to open /acct/uid_10111/pid_5742/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6295): TimaSignature is unavailable
,D/ActivityThread( 6295): Added TimaKeyStore provider
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,W/ResourcesManager( 6295): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6295): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6295): VM with version 2.1.0 has multidex support
I/MultiDex( 6295): install
I/MultiDex( 6295): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6295): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 6295): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6295): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@a3f1ee: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6295): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1697): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE,
I/splitIntent( 1016): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1016): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver,
W/ActivityManager( 1016): userId = 0, bbcId = -10000
I/splitIntent( 1016): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
I/splitIntent( 1016): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1697): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 1833): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1016): Killing 5836:com.sec.android.cloudagent/u0a2 (adj 15): empty #31
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6314): MountEmulatedStorage(),
,E/Zygote  ( 6314): v2
I/libpersona( 6314): KNOX_SDCARD checking this for 10012
I/libpersona( 6314): KNOX_SDCARD not a persona
,I/ActivityManager( 1016): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=6314 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,I/SELinux ( 6314): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/SELinux ( 6314): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6314): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SurfaceFlinger(  256): id=14 Removed Uoast (8/9)
I/SurfaceFlinger(  256): id=14 Removed Uoast (-2/9)
,D/TimaKeyStoreProvider( 6314): TimaSignature is unavailable
,D/ActivityThread( 6314): Added TimaKeyStore provider
,D/PowerManagerService( 1016): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1016) eventTime = 93352
,D/PowerManagerService( 1016): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1016 (0x0)
,D/PowerManagerService( 1016): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1016, ws=WorkSource{1000}) (elapsedTime=3446)
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1833): Restart initialization of location
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ResourcesManager( 6314): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6314): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/MultiDex( 6314): VM with version 2.1.0 has multidex support
I/MultiDex( 6314): install
I/MultiDex( 6314): VM has multidex support, MultiDex support library is disabled.
,W/libprocessgroup( 1016): failed to open /acct/uid_10002/pid_5836/cgroup.procs: No such file or directory
,V/JNIHelp ( 6314): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 6314): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6314): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@a3f1ee: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6314): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 6314): callingUid 10012, callindPid: 6314
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1697): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/splitIntent( 1016): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1016): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1016): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1016): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1697): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 1833): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1653): [177] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/MDM     ( 1653): [177] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1833): Restart initialization of location
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Mms/MmsApp( 6125):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 6125): [start]    fillCache consume time = 1799.829531
D/Mms/ComposeMessageFragment( 6125): fillCache, easy = false
,E/SMD     (  290): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/AbsListView( 6125): Get MotionRecognitionManager
,D/MotionRecognitionService( 1016):  ssp status : false
,D/Mms/ComposeMessageFragment( 6125): [end]    fillCache consume time = 83.38901
,D/Mms/BubbleViewCache( 6125): fillCache bubble = 1
,V/AlarmManager( 1016): waitForAlarm result :4
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6336): MountEmulatedStorage()
,E/Zygote  ( 6336): v2
I/libpersona( 6336): KNOX_SDCARD checking this for 10028
I/libpersona( 6336): KNOX_SDCARD not a persona
,I/SELinux ( 6336): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/ActivityManager( 1016): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6336 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6336): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6336): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6336): TimaSignature is unavailable
,D/ActivityThread( 6336): Added TimaKeyStore provider
,I/art     (  311): Explicit concurrent mark sweep GC freed 8695(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.146ms total 42.250ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 977us total 28.577ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 936us total 26.466ms
,D/Finsky  ( 6336): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 6336): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,W/Settings( 6336): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6336): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 6336): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6336): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 6336): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/Finsky  ( 6336): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/dhcpcd  ( 5697): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 5697): wlan0: no IPv6 Routers available
,I/art     ( 1697): Explicit concurrent mark sweep GC freed 14772(840KB) AllocSpace objects, 8(248KB) LOS objects, 39% free, 10MB/17MB, paused 1.010ms total 57.382ms
,V/Finsky  ( 6336): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1697): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1697): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1697): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1697): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6336): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6336): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6336): [1] 5.onFinished: Scheduling replication attempt 2.
,I/ActivityManager( 1016): Killing 5858:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5858/cgroup.procs: No such file or directory
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4206, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5508): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5508): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,V/AlarmManager( 1016): waitForAlarm result :4
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.DailyHygiene; callingUser = 0; userId(target) = 0
,D/Finsky  ( 6336): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1697): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1697): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1697): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1697): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 6336): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1697): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1697): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1697): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1697): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1697): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1697): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1697): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1697): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 6336): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1697): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1697): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1697): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1697): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 6336): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6336): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6336): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6336): [1] DailyHygiene.reschedule: Scheduling new run in 30 minutes (failures=2)
,D/DeviceConnectionService( 1653): client connected with version: 7571000
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SQLiteLog( 1697): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  290): DCD OFF,
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.android.vending
,D/Finsky  ( 6336): [1101] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1697): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1697): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1697): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1697): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 24072(1122KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/40MB, paused 2.444ms total 151.900ms
,D/Finsky  ( 6336): [1101] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,I/ActivityManager( 1016): Killing 5758:com.google.android.apps.books/u0a75 (adj 15): empty #31
,W/libprocessgroup( 1016): failed to open /acct/uid_10075/pid_5758/cgroup.procs: No such file or directory
,E/SMD     (  290): DCD OFF
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.preloadupdate.PreloadUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 5430): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5430): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5430): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5430): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 5430): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5430): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5430): exit::CHECK_TIMEOUT_FOR_UPDATE,
D/PreloadUpdateManagerStateMachine( 5430): entry::IDLE,
,D/SSRM:n  ( 1016): SIOP:: AP = 350
,I/PowerManagerService( 1016): [PWL] Off : 50s ago
,E/SMD     (  290): DCD OFF
,I/ActivityManager( 1016): Waited long enough for: ServiceRecord{3c0baa73 u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4225, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1016): Plugged,
D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5508): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5508): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  290): DCD OFF
,D/FactoryTest( 4658): Not factory mode
,D/FactoryTest( 4658): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 4658): DRIVER_TIME_OUT 60s lapsed,
D/MTPRx   ( 4658): still no open session command from host, so toast
,W/ContextImpl( 4658): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 4658): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,I/Timeline( 4658): Timeline: Activity_launch_request id:com.android.settings time:107076
,E/PersonaManagerService( 1016): inState():  stateMachine is null !!
,I/PersonaManagerService( 1016): PersonaId don't exist
,I/ActivityManager( 1016): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.android.settings,
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1016): mDVFSHelper.acquire()
,D/PersonaManager( 1016): isKioskContainerExistOnDevice
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.android.settings
D/InputDispatcher( 1016): Focused application set to: xxxx
,D/InputDispatcher( 1016): Focus left window: 5394
,E/MTPRx   ( 4658): started activity for popup
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,W/ResourcesManager( 4658): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 4658): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 4658): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4658): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4658): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4658): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 4658): PREF_DONT_ASK_AGAIN : true
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.android.settings
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,D/InputDispatcher( 1016): Focused application set to: xxxx
,D/InputDispatcher( 1016): Focus entered window: 5394
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/InputMethodManagerService( 1016): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService( 1016): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@eb7ab64 attribute=null, token = android.os.BinderProxy@20b3e62b
,D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,D/SettingsReceiverActivity( 4658): dev.kiessupport is : TRUE
,D/PhoneWindow( 4658): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 4658): *FMB* installDecor flags : 8388610
,D/ActivityManager( 1016): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1016): postActiveUserChange for user 0
,I/KnoxTimeoutHandler( 1016): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1016): handleActiveUserChange for user 0
,D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
,V/ActivityThread( 5394): updateVisibility : ActivityRecord{16a33451 token=android.os.BinderProxy@282816db {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/Timeline( 5394): Timeline: Activity_idle id: android.os.BinderProxy@282816db time:107255
,D/PersonaManager( 1016): isKioskContainerExistOnDevice
,E/Watchdog( 1016): !@Sync 3
,I/Atfwd_Sendcmd(  324): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  324): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  290): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.,
,W/ActivityManager( 1016): mDVFSHelper.release()
,V/AlarmManager( 1016): waitForAlarm result :8
,D/SSRM:n  ( 1016): SIOP:: AP = 330
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  324): Waiting for service AtCmdFwd...,
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4227, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5508): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5508): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,V/AlarmManager( 1016): waitForAlarm result :4
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,V/AlarmManager( 1016): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManagerEXT( 1016): <AppSync3 Whitelist>
V/AlarmManagerEXT( 1016): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/SecKeyguardClockView( 1178): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1178): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1697): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1697): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1697): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1697): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6336): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6336): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6336): [1] 5.onFinished: Scheduling replication attempt 3.
,V/AlarmManager( 1016): waitForAlarm result :4
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 310
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4228, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for charging
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,V/HeadsetService( 5508): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5508): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/PowerManagerService( 1016): [PWL] Off : 75s ago
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 2
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 310
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4231, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5508): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5508): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,V/AlarmManager( 1016): waitForAlarm result :4
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1697): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1697): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1697): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1697): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6336): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6336): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6336): [1] 5.onFinished: Scheduling replication attempt 4.
,E/Watchdog( 1016): !@Sync 4
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1016): SIOP:: AP = 300,
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,V/AlarmManager( 1016): waitForAlarm result :4
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0,
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6416): MountEmulatedStorage()
,E/Zygote  ( 6416): v2
I/libpersona( 6416): KNOX_SDCARD checking this for 10075
I/libpersona( 6416): KNOX_SDCARD not a persona
,I/ActivityManager( 1016): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6416 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6416): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 6416): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6416): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6416): TimaSignature is unavailable
,D/ActivityThread( 6416): Added TimaKeyStore provider
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/GAV2    ( 6416): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/BooksApp( 6416): Created application version: 3.6.9 (30609)
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/BooksSync( 6416): Starting books sync for 61035162, extras: ade
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SQLiteLog( 6416): (284) automatic index on view_volumes(volume_id)
,I/BooksConfig( 6416): GmsCore Version = 7.8.99 (2134222-436)
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1697): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1697): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1697): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1697): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
D/PersonaManager( 1178): isKioskContainerExistOnDevice
D/PersonaManager( 1178): isKioskContainerExistOnDevice
,D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1697): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1697): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1697): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1697): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6416): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6416): Soft error
E/BooksSync( 6416): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6416): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6416): Sync error
E/BooksSync( 6416): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6416): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6416): Finished books sync
,I/ActivityManager( 1016): Killing 5776:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SyncManager( 1016): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 120423, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1016): mCursor = null
,W/libprocessgroup( 1016): failed to open /acct/uid_10044/pid_5776/cgroup.procs: No such file or directory
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 300
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,I/GAV2    ( 6416): Thread[GAThread,5,main]: No campaign data found.
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4232, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5508): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5508): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/PowerManagerService( 1016): [PWL] Off : 105s ago
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :4
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.android.vending
,D/Finsky  ( 6336): [1101] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1697): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1697): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1697): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1697): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6336): [1101] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1697): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1697): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1697): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1697): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6336): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6336): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6336): [1] 5.onFinished: Scheduling replication attempt 5.
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1016): SIOP:: AP = 300,
,I/ServiceManager(  324): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4233, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5508): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5508): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1016): !@Sync 5
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,V/AlarmManager( 1016): waitForAlarm result :8
,D/SSRM:n  ( 1016): SIOP:: AP = 300
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4233, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 5508): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5508): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,V/AlarmManager( 1016): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/SecKeyguardClockView( 1178): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1178): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/AlarmManager( 1016): waitForAlarm result :4
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1697): Explicit concurrent mark sweep GC freed 29425(1730KB) AllocSpace objects, 3(108KB) LOS objects, 39% free, 10MB/17MB, paused 1.337ms total 56.871ms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1697): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1697): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1697): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1697): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6336): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6336): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6336): [1] 5.onFinished: Giving up after 6 failures.
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 5
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 140s ago
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4235, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5508): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 5508): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,V/AlarmManager( 1016): waitForAlarm result :4
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 40887(2MB) AllocSpace objects, 43(708KB) LOS objects, 33% free, 27MB/40MB, paused 2.418ms total 155.036ms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.stats.PlatformStatsCollectorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/VacuumService( 1697): Vacuum at: now=1449683726215 tag=VacuumService
,D/Batterystats( 1833): User is not opted-in to Usage & Diagnostics.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.uploader.UploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GoogleURLConnFactory( 1697): Using platform SSLCertificateSocketFactory
,W/Uploader( 1697): No account for auth token provided
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1697): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1697): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1697): (HTTPLog)-Static: isShipBuild true
I/System.out( 1697): (HTTPLog)-Thread-210-169737517: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 1697): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
,I/System.out( 1697): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1697): Tagging socket 57 with tag 120100000000{4609,0} for uid -1, pid: 1697, getuid(): 10012
,I/qtaguid ( 1697): Tagging socket 61 with tag 120100000000{4609,0} for uid -1, pid: 1697, getuid(): 10012
,W/Uploader( 1697): No account for auth token provided
,I/System.out( 1697): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1697): Tagging socket 57 with tag 120100000000{4609,0} for uid -1, pid: 1697, getuid(): 10012
,W/Uploader( 1697): No account for auth token provided
,I/System.out( 1697): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1697): Tagging socket 57 with tag 120100000000{4609,0} for uid -1, pid: 1697, getuid(): 10012
,W/Uploader( 1697):  no longer exists, so no auth token.
,I/System.out( 1697): (HTTPLog)-Static: isSBSettingEnabled false,
I/qtaguid ( 1697): Tagging socket 57 with tag 120100000000{4609,0} for uid -1, pid: 1697, getuid(): 10012
,W/Uploader( 1697): No account for auth token provided
,I/System.out( 1697): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1697): Tagging socket 57 with tag 120100000000{4609,0} for uid -1, pid: 1697, getuid(): 10012
,W/Uploader( 1697): No account for auth token provided
,I/System.out( 1697): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1697): Tagging socket 57 with tag 120100000000{4609,0} for uid -1, pid: 1697, getuid(): 10012
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1697): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1697): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1697): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1697): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1016): userId = 0, bbcId = -10000
E/Watchdog( 1016): !@Sync 6
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
D/PersonaManager( 1178): isKioskContainerExistOnDevice
,D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,E/Uploader( 1697): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1697): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1697): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1697): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1697): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1697): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1697): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1697): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1697): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1697): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1697): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1697): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1697): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/System.out( 1697): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1697): Tagging socket 57 with tag 120100000000{4609,0} for uid -1, pid: 1697, getuid(): 10012
,W/Uploader( 1697): No account for auth token provided
,D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/System.out( 1697): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1697): Tagging socket 57 with tag 120100000000{4609,0} for uid -1, pid: 1697, getuid(): 10012
,E/SQLiteLog( 1697): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4230, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5508): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 5508): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :4
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0
,I/BooksSync( 6416): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6416): GmsCore Version = 7.8.99 (2134222-436)
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1697): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1697): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1697): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1697): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1697): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1697): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1697): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1697): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6416): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6416): Soft error
E/BooksSync( 6416): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6416): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6416): Sync error
E/BooksSync( 6416): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6416): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6416): Finished books sync
,D/SyncManager( 1016): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 211525, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1016): mCursor = null
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,I/Atfwd_Sendcmd(  324): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  324): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4235, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
D/BatteryService( 1016): stay LED for charging
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5508): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5508): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290,
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/Watchdog( 1016): !@Sync 7,
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,V/AlarmManager( 1016): waitForAlarm result :8
,I/PowerManagerService( 1016): [PWL] Off : 180s ago
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/SecKeyguardClockView( 1178): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1178): HomeTimezone(): 1,
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1016): SIOP:: AP = 290,
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4236, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5508): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 5508): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1016): !@Sync 8
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 4
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 225s ago
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4236, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5508): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5508): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4235, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate,
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.,
D/BatteryService( 1016): stay LED for charging
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5508): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5508): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1016): !@Sync 9
,E/SMD     (  290): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,V/AlarmManager( 1016): waitForAlarm result :8
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  324): Waiting for service AtCmdFwd...,
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4236, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 1016): stay LED for charging,
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5508): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5508): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService( 1016): TIMA: TimaService scheduler is intialized. 
D/TimaService( 1016): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1016): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1016): initializing...
,I/TLC_TIMA_PKM_initialize( 1016): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1016): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1016): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1016): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1016): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1016): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1016): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1016): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1016): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1016): Loaded image: APP id = 11
,I/TZ: qc_tlc_communication( 1016): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1016): Trustlet response is completed
,E/SMD     (  290): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4232, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1016): Plugged,
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5508): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5508): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1016): !@Sync 10
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,I/Atfwd_Sendcmd(  324): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  324): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 275s ago
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4231, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5508): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5508): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4236, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5508): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5508): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,V/AlarmManager( 1016): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/SecKeyguardClockView( 1178): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1178): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0
,I/BooksSync( 6416): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6416): GmsCore Version = 7.8.99 (2134222-436)
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1697): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1697): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1697): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1697): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
D/PersonaManager( 1178): isKioskContainerExistOnDevice
,D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1697): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1697): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1697): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1697): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6416): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6416): Soft error
E/BooksSync( 6416): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6416): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6416): Sync error
E/BooksSync( 6416): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6416): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6416): Finished books sync
,D/SyncManager( 1016): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 339437, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1016): mCursor = null
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1016): !@Sync 11
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,V/AlarmManager( 1016): waitForAlarm result :8
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 2
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,I/jxcore-log( 5394): Toggling radios to false
I/jxcore-log( 5394): 
,D/BluetoothAdapter( 5394): disable()
,D/SettingsProvider( 1016): name = bluetooth_on
,D/BluetoothAdapterState( 5508): CURRENT_STATE=ON, MSG = USER_TURN_OFF
,D/BluetoothAdapterProperties( 5508): Setting state to 13
I/BluetoothAdapterState( 5508): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 5508): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5508): updateAdapterState state is 13
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
I/BluetoothPbapService( 5508): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
D/BluetoothAdapterService( 5508): Autoconnection is available 
D/BluetoothSocket( 5508): close() in, this: android.bluetooth.BluetoothSocket@598b68f, channel: 19, state: LISTENING
,D/BluetoothSocket( 5508): close() this: android.bluetooth.BluetoothSocket@598b68f, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@24a9eb97, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2b3f7d1cmSocket: android.net.LocalSocket@21cefd25 impl:android.net.LocalSocketImpl@25e13efa fd:FileDescriptor[74]
D/BluetoothSocket( 5508): Closing mSocket: android.net.LocalSocket@21cefd25 impl:android.net.LocalSocketImpl@25e13efa fd:FileDescriptor[74]
D/BluetoothAdapterService( 5508): updateAdapterState prevState = 12newState = 13
D/BluetoothAdapterService( 5508): terminating service from this receiver
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothAdapterProperties( 5508): onBluetoothDisable()
D/SecContentProvider( 1016): uri = 18 selection = isWifiEnabled
D/BluetoothAdapterProperties( 5508): mDiscovering is false
D/SecContentProvider2( 1016): uri = 20 selection = isWifiStateChangeAllowed
D/WifiService( 1016): setWifiEnabled: false pid=5394, uid=10175
D/SecContentProvider2( 1016): mCursor = null
D/SecContentProvider( 1016): uri = 3 selection = isDiscoverableEnabled
D/SettingsProvider( 1016): name = wifi_on
,I/BluetoothAdapterState( 5508): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,I/jxcore-log( 5394): Radios toggled
I/jxcore-log( 5394): 
,D/BluetoothPbap( 1306): Proxy object disconnected
W/InputMethodManagerService( 1016): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
D/PbapServerProfile( 1306): Bluetooth service disconnected
,E/WifiStateMachine( 1016): WifiStateMachine: Leaving Connected state
I/InputMethodManagerService( 1016): [BT Setting State] State =13
,I/wpa_supplicant( 5576): reset timer : RESET_TIMER 0
I/wpa_supplicant( 5576): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 5576): P2P: Current p2p state = IDLE
,I/wpa_supplicant( 5576): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiConfigStore( 1016): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/BluetoothTile( 1178):  onBluetoothStateChange:
,D/BluetoothTile( 1178): onReceive : android.bluetooth.adapter.action.STATE_CHANGED,
D/BluetoothTile( 1178):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 1178):  getBluetoothState : 13
D/BluetoothTile( 1178):  handleUpdatestate:false name:null
,E/WifiNative-wlan0( 1016): do suspend true
,D/BluetoothTile( 1178):  handleUpdatestate:false name:null
,I/SamsungIME( 1783): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,V/BluetoothEventManager( 1306): Received android.bluetooth.adapter.action.STATE_CHANGED
,D/STATUSBAR-QSTileView( 1178): onStateChanged: Bluetooth
,D/BluetoothUtils( 5508): getBtEnabledContainers(): btContainers = [],
D/BluetoothAdapterProperties( 5508): Scan Mode:20
D/StatusBarManagerService( 1016): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
D/StatusBarManagerService( 1016): setIconVisibility slot=bluetooth visible=false
,W/ContextImpl( 1306): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
D/PhoneStatusBar( 1178): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,D/BluetoothAdapterState( 5508): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
E/bt-btif ( 5508): btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,E/bt-btif ( 5508): HAL bt_hal_cbacks->log_collector_cb
E/bt-btif ( 5508): cmd socket is not created
E/BtOppRfcommListener( 5508): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btm  ( 5508): btm_ble_start_auto_conn start : 0, 0
W/bt-btif ( 5508): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
W/bt-l2cap( 5508): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 5508): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 5508): L2CAP - PSM: 0x001b not found for deregistration
W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/btif_config_util( 5508): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,D/BluetoothSocket( 5508): close() in, this: android.bluetooth.BluetoothSocket@2b554f08, channel: 5, state: LISTENING
,D/BluetoothSocket( 5508): close() this: android.bluetooth.BluetoothSocket@2b554f08, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2feb8184, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@199746a1mSocket: android.net.LocalSocket@3e7450c6 impl:android.net.LocalSocketImpl@746e887 fd:FileDescriptor[76]
D/BluetoothSocket( 5508): Closing mSocket: android.net.LocalSocket@3e7450c6 impl:android.net.LocalSocketImpl@746e887 fd:FileDescriptor[76]
I/BtOppRfcommListener( 5508): stopping Accept Thread
D/BluetoothSocket( 5508): close() in, this: android.bluetooth.BluetoothSocket@137453b4, channel: 12, state: LISTENING
D/BluetoothSocket( 5508): close() this: android.bluetooth.BluetoothSocket@137453b4, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@a3f1ee, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2b40abddmSocket: android.net.LocalSocket@28d4b352 impl:android.net.LocalSocketImpl@349f8623 fd:FileDescriptor[79]
D/BluetoothSocket( 5508): Closing mSocket: android.net.LocalSocket@28d4b352 impl:android.net.LocalSocketImpl@349f8623 fd:FileDescriptor[79]
I/BtOppRfcommListener( 5508): BluetoothSocket listen thread finished
,V/BluetoothOppManager( 5508): cleanUp...
,D/DockEventReceiver( 1306): finishStartingService: stopping service
D/BluetoothNotiBroadcastReceiver( 1306): onReceive
,V/BluetoothStatusReceiver( 1178): Received android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothStatusReceiver( 1178): AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6561): MountEmulatedStorage(),
E/Zygote  ( 6561): v2
I/libpersona( 6561): KNOX_SDCARD checking this for 10003
I/libpersona( 6561): KNOX_SDCARD not a persona
,I/SELinux ( 6561): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6561 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a,
,I/SELinux ( 6561): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6561): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6561): TimaSignature is unavailable
,D/ActivityThread( 6561): Added TimaKeyStore provider
,D/CommandListener(  277): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1697): Read error: ssl=0xb87125f0: I/O error during system call, Connection timed out
,D/WifiP2pService( 1016): InactiveState{ what=143375 }
,D/WifiP2pService( 1016): P2pEnabledState{ what=143375 }
,E/ConnectivityService( 1016): updateNetworkInfo()
D/ConnectivityService( 1016): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1016): updateNetworkInfo()
D/ConnectivityService( 1016): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,V/NativeCrypto( 1697): SSL shutdown failed: ssl=0xb87125f0: I/O error during system call, Broken pipe
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056a/com.android.systemui:drawable/stat_sys_wifi_signal_3 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056a/com.android.systemui:drawable/stat_sys_wifi_signal_3 mQSWifiIconId=0x7f02014e/com.android.systemui:drawable/ic_qs_wifi_3 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1016): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): ValidatedState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): DefaultState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
I/WifiTrafficPoller( 1016): evaluateTrafficStatsPolling
,I/System.out( 1016): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1016): Tagging socket 396 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1016, getuid(): 1000
,I/qtaguid ( 1016): Untagging socket 396
,I/System.out( 1016): (HTTPLog)-Static: isSBSettingEnabled false
,D/UserAnalysis.PlaceProvider( 6561): PlaceProvider onCreate(),
D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/WifiP2pService( 1016): InactiveState{ what=131204 }
D/WifiNetworkAgent( 1016): NetworkAgent: NetworkAgent channel lost
D/WifiP2pService( 1016): P2pEnabledState{ what=131204 }
D/WifiScanningService( 1016): SCAN_AVAILABLE : 1
D/WifiScanningService( 1016): DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1016): sending p2p connection changed broadcast: FAILED
D/RttService( 1016): SCAN_AVAILABLE : 1
,D/RttService( 1016): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiDisplayController( 1016): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WifiDisplayAdapter( 1016): onP2pDisconnected
,D/WifiP2pService( 1016): sending p2p connection changed broadcast: DISCONNECTED
D/IpRemoteDisplayController( 1016): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 1016): WfdBridgeServer is already null
E/WifiStateMachine( 1016): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED,
D/WifiDisplayController( 1016): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,D/WifiDisplayController( 1016): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 1016): disconnect
D/WifiDisplayController( 1016): updateConnection
D/WifiDisplayController( 1016): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiP2pService( 1016): P2pDisablingState
,D/WifiP2pService( 1016): P2pDisablingState{ what=147458 }
D/WifiP2pService( 1016): p2p socket connection lost
D/WifiP2pService( 1016): P2pDisabledState
,D/AllShareCastTile( 1178): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/AllShareCastTile( 1178): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,D/WifiDisplayController( 1016): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter( 1016): onP2pDisconnected
D/IpRemoteDisplayController( 1016): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 1016): WfdBridgeServer is already null
E/WifiNative-wlan0( 1016): do suspend true
,D/EnterpriseController(  277): uids 1000
D/WifiP2pService( 1016): P2pDisabledState{ what=143375 },
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/WifiP2pService( 1016): DefaultState{ what=143375 }
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Validated
D/ConnectivityService( 1016): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/ConnectivityService( 1016): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,D/CommandListener(  277): Clearing all IP addresses on wlan0
D/ConnectivityService( 1016): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WIFI_P2P( 1016): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/CSLegacyTypeTracker( 1016): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,fe80::7ef9:eff:fe51:1823/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/TelephonyNetworkFactory( 1464): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/CSLegacyTypeTracker( 1016): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/TelephonyNetworkFactory( 1464): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1016): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1178): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): ValidatedState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/EntConnectivity( 1016): Not allowed due to - mEnabled false - primarySimSlot false
D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1016): nai.networkMonitor.doQuit()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): doQuit - quitNow()
E/ConnectivityService( 1016): updateNetworkInfo()
D/ConnectivityService( 1016): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1016): updateNetworkInfo()
D/Tethering( 1016): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,D/EntConnectivity( 1016): Not allowed due to - mEnabled false - primarySimSlot false
D/Tethering( 1016): MasterInitialState.processMessage what=3
,V/NetworkStats( 1016): updateIfacesLocked()
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
V/NetworkStats( 1016): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1016): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1016): UpdateStatsForKnox main else ---
,V/NetworkStats( 1016): performPollLocked() took 4ms,
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit,
,V/NetworkStats( 1016): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1178): EthernetConnected: false
D/StatusBar.NetworkController( 1178): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1178): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1178): updateDataNetType()
D/UserAnalysis.SecureDbManager( 6561): Key for secure DB is newly created
,D/StatusBar.NetworkController( 1178): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1178): updateLTEICONDataNetType:0
D/UserAnalysis.SecurePlaceDbHelper( 6561): SecurePlaceDbHelper() 
D/UserAnalysis( 6561): Create SecureDbHelper
,W/bt-l2cap( 5508): L2CAP - PSM: 0x0019 not found for deregistration
I/bt_userial_mct( 5508): exiting userial_read_thread
D/bt_userial_mct( 5508): Leaving userial_evt_read_thread()
W/bt-l2cap( 5508): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 5508): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 5508): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 5508): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 5508): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 5508): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 5508): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 5508): L2CAP - PSM: 0x001b not found for deregistration
W/bt-btif ( 5508): ag scb idx 1 not allocated
W/bt-btif ( 5508): ag scb idx 2 not allocated
E/bt-btif ( 5508): BTA AG is already disabled, ignoring ...
D/bt_userial_mct( 5508): userial_close_reader Joined userial reader thread: 0
I/bt_vendor( 5508): hw_epilog_process
,I/WifiTrafficPoller( 1016): evaluateTrafficStatsPolling
D/bt_userial_mct( 5508): userial_close
I/bt_vendor( 5508): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
I/wpa_supplicant( 5576): p2p0: State: DISCONNECTED -> DISCONNECTED
D/StatusBar.NetworkController( 1178): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/WIFI    ( 1016): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/IntelligenceServiceApplication( 6561): onCreate()
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/HotspotTile( 1178): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/SecContentProvider2( 1016): uri = 20 selection = getPromptCredentialsEnabled
D/STATUSBAR-QSTileView( 1178): onStateChanged: Wi-Fi
D/SecContentProvider2( 1016): mCursor = null
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/HotspotTile( 1178): onReceive : 0, 0
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/STATUSBAR-WifiQuickSettingButton( 1178): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1178): Wifi onReceive(0)
,D/WifiCredService( 1306): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/IntelligenceServiceApplication( 6561): no applications having user consent for prediction
,I/ActivityManager( 1016): Killing 5900:com.sec.android.soagent/u0a34 (adj 15): empty #31
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,V/PlaceDetection v1.0.19 ( 6561): [PlaceDetection::stopService] Service stopped.
,V/PlaceDetection v1.0.19 ( 6561): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,D/AuthorizationBluetoothService( 1697): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3385): Starting #8
,I/Hs20UtilService( 3385): Message received 5007
,D/NearbySettings( 1306): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1306): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1306): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1306): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1306): MountReceiver.mPrefHandler - 7002
,W/libprocessgroup( 1016): failed to open /acct/uid_10034/pid_5900/cgroup.procs: No such file or directory
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/NearbySettings( 1306): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 1306): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1306): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1306): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1306): MountReceiver.mPrefHandler - 7002
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6584): MountEmulatedStorage(),
E/Zygote  ( 6584): v2
I/libpersona( 6584): KNOX_SDCARD checking this for 10068
I/libpersona( 6584): KNOX_SDCARD not a persona
,I/SELinux ( 6584): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6584 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6584): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
E/SELinux ( 6584): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/wpa_supplicant( 5576): Blacklist: Clear (all) 
,D/PhoneApp( 1464): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
,D/PhoneApp( 1464): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
D/PhoneApp( 1464): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
,D/PhoneApp( 1464): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/TimaKeyStoreProvider( 6584): TimaSignature is unavailable
,D/ActivityThread( 6584): Added TimaKeyStore provider
D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
D/PhoneApp( 1464): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
,D/PhoneApp( 1464): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
D/PhoneApp( 1464): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
D/PhoneApp( 1464): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
,D/PhoneApp( 1464): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
D/PhoneApp( 1464): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,W/ResourcesManager( 6584): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
,D/PhoneApp( 1464): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
,D/PhoneApp( 1464): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
,D/PhoneApp( 1464): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
D/PhoneApp( 1464): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
,D/PhoneApp( 1464): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1464): FileWriteThread : threadType = 3
,D/FileShare-Client( 6584): ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/FileShare-Client( 6584): ClientBroadcastReceiver.onReceive - disconnected
,I/wpa_supplicant( 5576): p2p0: CTRL-EVENT-TERMINATING 
,D/Tethering( 1016): interfaceLinkStateChanged p2p0, false
D/Tethering( 1016): interfaceStatusChanged p2p0, false
,I/Nat464Xlat( 1016): interfaceLinkStateChanged p2p0, false
,D/FileShare-Client( 6584): Outbound.stopDelayTimer - 
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/wpa_supplicant( 5576): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/libpersona( 6615): KNOX_SDCARD checking this for 10069
E/Zygote  ( 6615): MountEmulatedStorage()
I/libpersona( 6615): KNOX_SDCARD not a persona
E/Zygote  ( 6615): v2
I/wpa_supplicant( 5576): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 5576): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 5576): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 5576): wlan0: State: DISCONNECTED -> DISCONNECTED
D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
D/Tethering( 1016): interfaceStatusChanged wlan0, false
D/Tethering( 1016): InitialState.processMessage what=4
D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
D/Tethering( 1016): interfaceStatusChanged wlan0, false
I/SELinux ( 6615): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
I/ActivityManager( 1016): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6615 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/Tethering( 1016): interfaceStatusChanged wlan0, false
E/Tethering( 1016): No numeric data
,I/ActivityManager( 1016): Killing 5087:com.policydm/1000 (adj 15): empty #31
I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14949 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6950 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
,D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
D/Tethering( 1016): interfaceStatusChanged wlan0, false
I/SELinux ( 6615): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
D/Tethering( 1016): sendTetherStateChangedBroadcast 0, 0, 0
I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
D/Tethering( 1016): clearTetheredNotification()
E/SELinux ( 6615): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
V/NetworkStats( 1016): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1016): UpdateStatsForKnox updated
D/HotspotTile( 1178): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/NetworkStatsFactory( 1016): UpdateStatsForKnox main else ---
D/HotspotTile( 1178): updateTetherState():false, false
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
V/NetworkStats( 1016): performPollLocked() took 3ms
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/TimaKeyStoreProvider( 6615): TimaSignature is unavailable
,D/ActivityThread( 6615): Added TimaKeyStore provider
,D/FileShare-Server( 6615): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,I/ActivityManager( 1016): Killing 5925:com.samsung.android.sconnect/u0a125 (adj 15): empty #31
,I/rmt_storage(  270): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb74977c8
I/rmt_storage(  270): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
I/rmt_storage(  270): wakelock acquired: 1, error no: 42
I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1219922632)
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
I/Hs20UtilService( 3385): Starting #9
,I/Hs20UtilService( 3385): Message received 5007,
I/bt_vendor( 5508): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 5508): bluetooth satus is on
I/bt_vendor( 5508): bt-vendor : resetting BT status
I/bt_vendor( 5508): Starting hciattach daemon
I/bt_vendor( 5508): try to set false
I/bt_vendor( 5508): Starting hciattach daemon
I/bt_vendor( 5508): try to set false
,I/bt_vendor( 5508): cleanup
I/GKI_LINUX( 5508): gki_task task_id=0 [BTU] terminating,
D/NearbySettings( 1306): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1306): DMSUtil.isNetworkConnected - flag-null, state-null
I/GKI_LINUX( 5508): GKI_exit_task 0 done
I/GKI_LINUX( 5508): GKI_shutdown(): task [BTU] terminated
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/BluetoothAdapterState( 5508): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BtConfig.SecureMode( 5508): isSecureModeOn:false
D/BluetoothAdapterService( 5508): mProfilesStarted : true supportedProfileServices.length : 12
W/BluetoothAdapterService( 5508): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 5508): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 5508): Not skipping com.android.bluetooth.gatt.GattService,
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1306): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1306): MountReceiver.mPrefHandler - 7002
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5508): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5508): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,D/BtGatt.DebugUtils( 5508): handleDebugAction() action=null
,D/BtGatt.GattService( 5508): Received stop request...Stopping profile...
D/BtGatt.GattService( 5508): stop()
D/BtGatt.AdvertiseManager( 5508): advertise clients cleared
W/BluetoothAdapterService( 5508): Not skipping com.android.bluetooth.hfp.HeadsetService
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/BluetoothAdapterService( 5508): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2954e365
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5508): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 5508): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 5508): Not skipping com.android.bluetooth.a2dp.A2dpService
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 5508): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5508): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 5508): Not skipping com.android.bluetooth.hid.HidService
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/BluetoothAdapterService( 5508): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 5508): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,W/BluetoothAdapterService( 5508): Not skipping com.android.bluetooth.hdp.HealthService
,I/Hs20UtilService( 3385): Starting #10
,I/Hs20UtilService( 3385): Message received 5011
,I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1219922632) wakelock released: 1, error no: 0
I/rmt_storage(  270): 
,I/rmt_storage(  270): rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb74977c8
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5508): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/SecurityLogAgent( 5610): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 5610): KnoxConfiguration : Current State Mapping Found 
D/BtSettings.ProfileConfig( 5508): getProfileSaveSetting: com.android.bluetooth.pan.PanService
D/SecurityLogAgent( 5610): StateMachine : Current State = 1
D/SecurityLogAgent( 5610): StateMachine : Changed Current State = 1
W/BluetoothAdapterService( 5508): Not skipping com.android.bluetooth.pan.PanService
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5508): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/BtSettings.ProfileConfig( 5508): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 5508): Not skipping com.android.bluetooth.map.BluetoothMapService
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5508): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 5508): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 5508): Not skipping com.broadcom.bt.service.sap.SapService
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5508): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 5508): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService( 5508): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 5508): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 5508): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 5508): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,W/BluetoothAdapterService( 5508): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 5508): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,W/BluetoothAdapterService( 5508): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 5508): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 5508): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,W/BluetoothAdapterService( 5508): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService,
D/BluetoothAdapterState( 5508): Stopping profile services that were post enabled
E/BluetoothAdapterService(693429093)( 5508): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
D/HeadsetService( 5508): Received stop request...Stopping profile...
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/BluetoothAdapterService( 5508): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2954e365
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/HeadsetProfile( 1306): Bluetooth service disconnected
D/A2dpService( 5508): Received stop request...Stopping profile...
D/A2dpStateMachine( 5508): Exit Disconnected: -1
,D/BluetoothAdapterService( 5508): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2954e365
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/HidService( 5508): Received stop request...Stopping profile...
D/HidService( 5508): Stopping Bluetooth HidService
W/BluetoothHidServiceJni( 5508): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 5508): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 5508): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 5508): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2954e365
D/BluetoothA2dp( 2669): Proxy object disconnected
D/BluetoothA2dp( 1306): Proxy object disconnected
D/A2dpProfile( 1306): Bluetooth service disconnected
D/AudioService( 1016): onServiceDisconnected: Bluetooth profile: 1
,D/HealthService( 5508): Received stop request...Stopping profile...
D/BluetoothAdapterService( 5508): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2954e365
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/BluetoothInputDevice( 1306): Proxy object disconnected
D/HidProfile( 1306): Bluetooth service disconnected
,D/BluetoothA2dp( 1016): Proxy object disconnected
D/AudioService( 1016): onServiceDisconnected: Bluetooth profile: 2
,D/PanService( 5508): Received stop request...Stopping profile...
D/BluetoothAdapterService( 5508): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2954e365
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/BluetoothMapService( 5508): Received stop request...Stopping profile...
,D/BluetoothPan( 1306): BluetoothPAN Proxy object disconnected
D/PanProfile( 1306): Bluetooth service disconnected
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/BluetoothPan( 1016): BluetoothPAN Proxy object disconnected,
D/BluetoothAdapterService( 5508): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2954e365
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/SapService( 5508): Received stop request...Stopping profile...
D/SapService( 5508): Stopping Bluetooth SapService
D/BluetoothAdapterService( 5508): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2954e365
,D/BluetoothMap( 1306): Proxy object disconnected
D/MapProfile( 1306): Bluetooth service disconnected
E/BluetoothAdapterService(693429093)( 5508): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5508): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 5508): Profile still running: com.android.bluetooth.hid.HidService
,D/Bluetoothsap( 1306): BluetoothSAP Proxy object disconnected
D/SapProfile( 1306): Bluetooth service disconnected
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/BluetoothHeadsetServiceJni( 5508): Cleaning up Bluetooth Handsfree Interface...
,W/BluetoothHeadsetServiceJni( 5508): Cleaning up Bluetooth Handsfree callback object
E/BluetoothAdapterService(693429093)( 5508): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5508): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 5508): Profile still running: com.android.bluetooth.hid.HidService
D/BluetoothA2dp( 5508): Proxy object disconnected
D/BluetoothAdapterService( 5508): Bluetooth A2dp source service disconnected
I/GKI_LINUX( 5508): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 5508): GKI_exit_task 2 done
I/GKI_LINUX( 5508): GKI_shutdown(): task [A2DP-MEDIA] terminated
,E/BluetoothAdapterService(693429093)( 5508): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5508): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 5508): Profile still running: com.android.bluetooth.map.BluetoothMapService
E/BluetoothAdapterService(693429093)( 5508): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5508): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 5508): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 5508): Cleaning up Bluetooth Health Interface...
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/BluetoothHealthServiceJni( 5508): Cleaning up Bluetooth Health object
E/BluetoothAdapterService(693429093)( 5508): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5508): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 5508): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 5508): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 5508): Cleaning up Bluetooth PAN callback object
,I/wpa_supplicant( 5576): Blacklist: Clear (all) 
E/BluetoothAdapterService(693429093)( 5508): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5508): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 5508): Profile still running: com.broadcom.bt.service.sap.SapService
E/BluetoothAdapterService(693429093)( 5508): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,W/BluetoothSAPServiceJni( 5508): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 5508): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/BluetoothAdapterState( 5508): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,D/BluetoothAdapterProperties( 5508): Setting state to 10
I/BluetoothAdapterState( 5508): Bluetooth adapter state changed: 13-> 10
,D/BluetoothAdapterService( 5508): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5508): updateAdapterState state is 10
D/BluetoothAdapterService( 5508): Autoconnection is available 
,D/BluetoothAdapterService( 5508): updateAdapterState prevState = 13newState = 10
I/BluetoothAdapterState( 5508): Entering OffState
,D/BluetoothAdapter( 1653): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1653): Bluetooth is turned off, stop adv and scan
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/BluetoothAdapter( 1464): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1464): Bluetooth is turned off, stop adv and scan
,D/BluetoothAdapter( 5508): onBluetoothStateChange: up=false
D/BluetoothAdapter( 5508): Bluetooth is turned off, stop adv and scan
D/BluetoothAdapter( 1178): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1178): Bluetooth is turned off, stop adv and scan
,D/BluetoothAdapter( 1441): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1441): Bluetooth is turned off, stop adv and scan
,D/BluetoothMap( 1306): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 5394): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 5394): Bluetooth is turned off, stop adv and scan
,D/BluetoothA2dp( 2669): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 5508): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 1306): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 1016): onBluetoothStateChange: up=false
,D/BluetoothPbap( 1306): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1306): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1306): Bluetooth is turned off, stop adv and scan
,D/BluetoothAdapter( 1450): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1450): Bluetooth is turned off, stop adv and scan
,D/BluetoothAdapter( 2669): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 2669): Bluetooth is turned off, stop adv and scan
D/BluetoothInputDevice( 1306): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1016): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1016): Bluetooth is turned off, stop adv and scan
,D/Bluetoothsap( 1306): onBluetoothStateChange: up=false
D/Bluetoothsap( 1306): Unbinding service...
,D/BluetoothManagerService( 1016): Broadcasting onBluetoothServiceDown() to 10 receivers.
,D/BluetoothManagerService( 1016): Broadcasting onBluetoothServiceUp() to 0 receivers.
,D/ConnectivityService( 1016): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 1016): updateDataUsageMap
,D/GpsLocationProvider( 1016): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5087/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10125/pid_5925/cgroup.procs: No such file or directory
,I/DBG_DM  ( 2789): [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
,I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
D/Tethering( 1016): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 5576): wlan0: CTRL-EVENT-TERMINATING 
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 2789): [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,E/Zygote  ( 6631): MountEmulatedStorage()
E/Zygote  ( 6631): v2
I/libpersona( 6631): KNOX_SDCARD checking this for 1000
I/libpersona( 6631): KNOX_SDCARD not a persona
I/SELinux ( 6631): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6631 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 6631): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/GKI_LINUX( 5508): gki_task task_id=1 [BTIF] terminating
E/SELinux ( 6631): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/GKI_LINUX( 5508): GKI_exit_task 1 done
I/GKI_LINUX( 5508): GKI_shutdown(): task [BTIF] terminated
,I/BluetoothServiceJni( 5508): cleanupNative: return from cleanup
,D/BluetoothAdapter( 1178): 747014874: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1178): 747014874: getState() :  mService = null. Returning STATE_OFF
D/BluetoothTile( 1178):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 1178): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1178):  getBluetoothState : 10
D/BluetoothAdapter( 1178): 747014874: getState() :  mService = null. Returning STATE_OFF
D/StatusBarManagerService( 1016): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
D/BluetoothAdapter( 1178): 747014874: getState() :  mService = null. Returning STATE_OFF
D/StatusBarManagerService( 1016): setIconVisibility slot=bluetooth visible=false
D/BluetoothAdapter( 1178): 747014874: getState() :  mService = null. Returning STATE_OFF
D/PhoneStatusBar( 1178): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,V/BluetoothEventManager( 1306): Received android.bluetooth.adapter.action.STATE_CHANGED
I/SamsungIME( 1783): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,I/art     ( 5508): System.exit called, status: 0
I/AndroidRuntime( 5508): VM exiting with result code 0, cleanup skipped.
,D/TimaKeyStoreProvider( 6631): TimaSignature is unavailable
,D/ActivityThread( 6631): Added TimaKeyStore provider
,I/PCWCLIENTTRACE_LOG( 6631): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 6631): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 6631): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil( 6631): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6631): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6631): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6631): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1016): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=22
I/splitIntent( 1016): base  index=22, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1016): other index=24, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1016): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6631): noConnectivity : true
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6649): MountEmulatedStorage(),
E/Zygote  ( 6649): v2
I/libpersona( 6649): KNOX_SDCARD checking this for 10111
I/libpersona( 6649): KNOX_SDCARD not a persona
I/SELinux ( 6649): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1016): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6649 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 5578:com.android.email/u0a145 (adj 15): empty #31
I/SELinux ( 6649): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6649): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/WifiStateMachine( 1016): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,D/WifiNative-wlan0( 1016): callSECApiBoolean - ID [21]
E/WifiConfigStore( 1016): setLastSelectedConfiguration -1
,W/Settings( 5963): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/STATUSBAR-WifiQuickSettingButton( 1178): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1178): Wifi onReceive(1)
D/HotspotTile( 1178): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/HotspotTile( 1178): onReceive : 1, 0
,D/STATUSBAR-QSTileView( 1178): onStateChanged: Wi-Fi
W/Settings( 1653): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiCredService( 1306): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/TimaKeyStoreProvider( 6649): TimaSignature is unavailable
,D/ActivityThread( 6649): Added TimaKeyStore provider
,I/ActivityManager( 1016): Process com.android.bluetooth (pid 5508)(adj 0) has died(79,1037),
,I/MusicStore( 6649): Database version: 120
,W/libprocessgroup( 1016): failed to open /acct/uid_10145/pid_5578/cgroup.procs: No such file or directory
,W/InputMethodManagerService( 1016): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 1016): [BT Setting State] State =10
I/InputMethodManagerService( 1016): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6649): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6649): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6649): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/ResourcesManager( 6649): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6649): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6649): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 6649): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6649): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1de55cbd: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6649): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6649): GMSCore installation verified
,I/ConfigStore( 6649): Config Database version: 1
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1016): getStreamVolume 3 index 0
,I/MediaRouter( 6649): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6649): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6675): MountEmulatedStorage()
I/libpersona( 6675): KNOX_SDCARD checking this for 10002
E/Zygote  ( 6675): v2
I/libpersona( 6675): KNOX_SDCARD not a persona
I/SELinux ( 6675): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6675 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6675): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6675): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/GHttpClientFactory( 6649): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/TimaKeyStoreProvider( 6675): TimaSignature is unavailable
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
D/ActivityThread( 6675): Added TimaKeyStore provider
,I/GoogleURLConnFactory( 6649): Using platform SSLCertificateSocketFactory
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ActivityManager( 1016): Killing 5940:com.samsung.android.service.travel/u0a159 (adj 15): empty #31
,I/ActivityManager( 1016): Killing 6009:com.google.android.apps.magazines/u0a113 (adj 15): empty #31
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6694): MountEmulatedStorage(),
E/Zygote  ( 6694): v2
I/libpersona( 6694): KNOX_SDCARD checking this for 1000
I/libpersona( 6694): KNOX_SDCARD not a persona
,I/SELinux ( 6694): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/ActivityManager( 1016): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6694 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
I/SELinux ( 6694): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 6694): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6694): TimaSignature is unavailable
,D/ActivityThread( 6694): Added TimaKeyStore provider
,D/Tethering( 1016): interfaceRemoved wlan0
E/Tethering( 1016): attempting to remove unknown iface (wlan0), ignoring
,W/libprocessgroup( 1016): failed to open /acct/uid_10113/pid_6009/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10159/pid_5940/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 6694): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] ,
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/DIAGMON_AGENT( 6694): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 6694): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 6694): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE,
I/DIAGMON_AGENT( 6694): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6694): ./extraInfo: <unknown ssid>
,W/DIAGMON_AGENT( 6694): [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,I/ActivityManager( 1016): Killing 6069:com.android.chrome/u0a81 (adj 15): empty #31
,I/KLMS-2.5.183: ( 3417): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Dec 09 18:58:13 GMT+01:00 2015
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.183: ( 3417): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.183: ( 3417): KLMSIntentService(): onCreate()
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3417): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.183: ( 3417): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.183: ( 3417): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,E/Zygote  ( 6710): MountEmulatedStorage()
,E/Zygote  ( 6710): v2
I/libpersona( 6710): KNOX_SDCARD checking this for 10034
I/libpersona( 6710): KNOX_SDCARD not a persona
,I/SELinux ( 6710): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/KLMS-2.5.183: ( 3417): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/SELinux ( 6710): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1016): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6710 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
,E/SELinux ( 6710): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.183: ( 3417): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.183: ( 3417): StateImplV2(): networkChangeListener().END
,I/KLMS-2.5.183: ( 3417): KLMSIntentService(): onDestroy()
,D/Tethering( 1016): interfaceRemoved p2p0
,E/Tethering( 1016): attempting to remove unknown iface (p2p0), ignoring
,D/TimaKeyStoreProvider( 6710): TimaSignature is unavailable
,D/ActivityThread( 6710): Added TimaKeyStore provider
,I/SO_AGENT( 6710): [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1016): failed to open /acct/uid_10081/pid_6069/cgroup.procs: No such file or directory
,E/Zygote  ( 6725): MountEmulatedStorage()
,E/Zygote  ( 6725): v2
,I/libpersona( 6725): KNOX_SDCARD checking this for 1000
I/libpersona( 6725): KNOX_SDCARD not a persona
,I/SELinux ( 6725): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/ActivityManager( 1016): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=6725 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 5368:com.google.android.apps.plus/u0a120 (adj 15): empty #31,
,I/SELinux ( 6725): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6725): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6725): TimaSignature is unavailable
,D/ActivityThread( 6725): Added TimaKeyStore provider
,I/DBG_POLICYDM( 6725): [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,I/DBG_POLICYDM( 6725): [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,I/DBG_POLICYDM( 6725): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,I/DBG_POLICYDM( 6725): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,I/DBG_POLICYDM( 6725): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,I/DBG_POLICYDM( 6725): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,I/DBG_POLICYDM( 6725): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
,I/DBG_POLICYDM( 6725): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
,I/DBG_POLICYDM( 6725): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,I/DBG_POLICYDM( 6725): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,I/DBG_POLICYDM( 6725): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/data/com.policydm/cache]
,I/DBG_POLICYDM( 6725): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,I/DBG_POLICYDM( 6725): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,I/DBG_POLICYDM( 6725): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 6725): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
,I/DBG_POLICYDM( 6725): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,I/DBG_POLICYDM( 6725): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/SA      ( 5287): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
,I/SA      ( 5287): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 5287): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/DBG_POLICYDM( 6725): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/DBG_POLICYDM( 6725): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
I/SA      ( 5287): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 5287): [OR] == isSIMCardReady false ==
,I/SA      ( 5287): [SCU] == networkStateCheck == false
I/SA      ( 5287): [OR] onReceive END
,E/DBG_POLICYDM( 6725): [com.policydm.XDMBroadcastReceiver$2(109/run)] network is unserviceable
,I/ActivityManager( 1016): Killing 6092:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
,V/DownloadManager( 1230): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,E/DBG_POLICYDM( 6725): [com.policydm.XDMApplication(437/isNetworkChanged)] network not changed.... 
,D/accuweather( 1568): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 1285): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/accuweather( 1568): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1568): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1568): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1568): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1568): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1568): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6745): MountEmulatedStorage()
E/Zygote  ( 6745): v2
I/libpersona( 6745): KNOX_SDCARD checking this for 10125
I/libpersona( 6745): KNOX_SDCARD not a persona
,I/SELinux ( 6745): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1016): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6745 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 6745): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
W/libprocessgroup( 1016): failed to open /acct/uid_10120/pid_5368/cgroup.procs: No such file or directory
,E/SELinux ( 6745): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_POLICYDM( 6725): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/DBG_POLICYDM( 6725): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/DBG_POLICYDM( 6725): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/DBG_POLICYDM( 6725): [com.policydm.agent.XDMTask(174/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized
,I/art     (  311): Explicit concurrent mark sweep GC freed 8718(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 650us total 23.094ms
,D/TimaKeyStoreProvider( 6745): TimaSignature is unavailable
,D/ActivityThread( 6745): Added TimaKeyStore provider
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 601us total 16.841ms
,W/ResourcesManager( 6745): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6745): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6745): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 601us total 16.651ms
,W/libprocessgroup( 1016): failed to open /acct/uid_10062/pid_6092/cgroup.procs: No such file or directory
,D/QuickConnect( 6745): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6745): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 6745): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6760): MountEmulatedStorage(),
E/Zygote  ( 6760): v2
I/libpersona( 6760): KNOX_SDCARD checking this for 10145,
I/libpersona( 6760): KNOX_SDCARD not a persona
I/SELinux ( 6760): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6760 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 6125:com.android.mms/u0a46 (adj 15): empty #31
,I/SELinux ( 6760): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6760): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 6760): TimaSignature is unavailable
,D/ActivityThread( 6760): Added TimaKeyStore provider
,W/ResourcesManager( 6760): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6760): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6760): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6760): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6760): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/CountryDetector( 1016): No listener is left
,W/libprocessgroup( 1016): failed to open /acct/uid_10046/pid_6125/cgroup.procs: No such file or directory
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/BadgeProvider( 6261): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/Launcher.Model( 1489): reloadBadges entered.
D/BadgeProvider( 6261): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 6261): sendNotify, [notify] : null
D/BadgeProvider( 6261): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 6261): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 6261): update, [UpdateCount] : 1
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/SecurityLogAgent( 5610): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 5610): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5610): StateMachine : Current State = 1
D/SecurityLogAgent( 5610): StateMachine : Changed Current State = 1
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6783): MountEmulatedStorage()
,E/Zygote  ( 6783): v2
I/libpersona( 6783): KNOX_SDCARD checking this for 10159
I/libpersona( 6783): KNOX_SDCARD not a persona
,I/SELinux ( 6783): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6783 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6783): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6783): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6783): TimaSignature is unavailable
,D/ActivityThread( 6783): Added TimaKeyStore provider
,I/ActivityManager( 1016): Killing 6141:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/iu.Environment( 1833): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1833): num queued entries: 0
,I/iu.UploadsManager( 1833): num updated entries: 0
,I/iu.SyncManager( 1833): NEXT; no task
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1833): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 70828(4MB) AllocSpace objects, 75(1308KB) LOS objects, 33% free, 27MB/40MB, paused 3.016ms total 174.462ms
,E/SPPClientService( 5991): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5991): [SystemStateMoniter] Current Time : 365133
,I/Babel   ( 5963): connection state changed from CONNECTED to DISCONNECTED
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,E/SPPClientService( 5991): [SystemStateMoniter] No Connect : true
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/SPPClientService( 5991): [[SystemStateMonitorService]] No Active Internet
,E/Zygote  ( 6802): MountEmulatedStorage()
E/Zygote  ( 6802): v2
I/libpersona( 6802): KNOX_SDCARD checking this for 10113
I/libpersona( 6802): KNOX_SDCARD not a persona
,I/SELinux ( 6802): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6802 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/WifiStateMachine( 1016): skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,I/SELinux ( 6802): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6802): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Killing 6177:com.sec.android.app.taskmanager/u0a157 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6802): TimaSignature is unavailable
,D/ActivityThread( 6802): Added TimaKeyStore provider
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/libprocessgroup( 1016): failed to open /acct/uid_10085/pid_6141/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10157/pid_6177/cgroup.procs: No such file or directory
,W/ContextImpl( 6802): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6802): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6802): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6802):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6802):   adb logcat -s GAv4
,W/GAv4    ( 6802): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6802): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6802): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6802): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6802): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/WebViewFactory( 6802): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,I/LibraryLoader( 6802): Time to load native libraries: 3 ms (timestamps 5547-5550)
,I/LibraryLoader( 6802): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6802): Binding Chromium to main looper Looper (main, tid 1) {21cefd25}
,I/LibraryLoader( 6802): Expected native library version number "",actual native library version number ""
,I/chromium( 6802): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6802): Initializing chromium process, singleProcess=true
,W/art     ( 6802): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6802): ApplicationContext is null in ApplicationStatus
,W/chromium( 6802): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6802): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6802): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6802): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6802): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6802): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6802): Local Branch: 
I/Adreno-EGL( 6802): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6802): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6802):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/NSApplication( 6802): Starting up...
,W/AudioManagerAndroid( 6802): Requires BLUETOOTH permission
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6856): MountEmulatedStorage()
I/ActivityManager( 1016): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6856 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 6856): v2
I/libpersona( 6856): KNOX_SDCARD checking this for 10081
I/libpersona( 6856): KNOX_SDCARD not a persona
,I/SELinux ( 6856): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1016): Killing 6193:com.qualcomm.timeservice/1000 (adj 15): empty #31
,I/SELinux ( 6856): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6856): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6856): TimaSignature is unavailable,
D/ActivityThread( 6856): Added TimaKeyStore provider
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_6193/cgroup.procs: No such file or directory
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6873): MountEmulatedStorage()
,I/ActivityManager( 1016): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6873 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 6873): v2
I/libpersona( 6873): KNOX_SDCARD checking this for 10120
I/libpersona( 6873): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Killing 6162:com.android.providers.calendar/u0a42 (adj 15): empty #31
,I/SELinux ( 6873): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6873): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6873): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6873): TimaSignature is unavailable
,D/ActivityThread( 6873): Added TimaKeyStore provider
,W/ResourcesManager( 6873): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/libprocessgroup( 1016): failed to open /acct/uid_10042/pid_6162/cgroup.procs: No such file or directory
,I/ActivityManager( 1016): Killing 6217:com.sec.esdk.elm/u0a94 (adj 15): empty #31
,W/ContextImpl( 1306): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,D/DockEventReceiver( 1306): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1306): onReceive
,V/BluetoothStatusReceiver( 1178): Received android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothStatusReceiver( 1178): AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6896): MountEmulatedStorage(),
I/ActivityManager( 1016): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6896 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
E/Zygote  ( 6896): v2
I/libpersona( 6896): KNOX_SDCARD checking this for 1002
I/libpersona( 6896): KNOX_SDCARD not a persona
,I/SELinux ( 6896): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 6896): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 6896): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1016): failed to open /acct/uid_10094/pid_6217/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6896): TimaSignature is unavailable
,D/ActivityThread( 6896): Added TimaKeyStore provider
,W/ResourcesManager( 6896): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,W/ResourcesManager( 6896): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/BluetoothA2dpSinkServiceJni( 6896): register_com_android_bluetooth_a2dp_sink
,D/BtSettings.ProfileConfig( 6896): Adding GattService
,D/BtSettings.ProfileConfig( 6896): Adding HeadsetService
D/BtSettings.ProfileConfig( 6896): Adding A2dpService
D/BtSettings.ProfileConfig( 6896): Adding HidService
,D/BtSettings.ProfileConfig( 6896): Adding HealthService
D/BtSettings.ProfileConfig( 6896): Adding PanService
D/BtSettings.ProfileConfig( 6896): Adding BluetoothMapService
D/BtSettings.ProfileConfig( 6896): Adding SapService
D/BtSettings.ProfileConfig( 6896): Adding HeadsetClientService
,D/BtSettings.ProfileConfig( 6896): Adding A2dpSinkService
D/BtSettings.ProfileConfig( 6896): Adding SapClientService
D/BtSettings.ProfileConfig( 6896): Adding HidDevService
I/BtSettings.ProfileConfig( 6896): *********Initializing Bluetooth Profile Settings*******
,D/SettingsProvider( 1016): name = bt_svcst_com.android.bluetooth.gatt.GattService
,D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
,D/SettingsProvider( 1016): selectionArgs: 1002
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1016): ret = -1
,D/SettingsProvider( 1016): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1002
,D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,D/SettingsProvider( 1016): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1002
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,D/SettingsProvider( 1016): name = bt_svcst_com.android.bluetooth.hid.HidService
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1002
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,D/SettingsProvider( 1016): name = bt_svcst_com.android.bluetooth.hdp.HealthService
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1002
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,D/SettingsProvider( 1016): name = bt_svcst_com.android.bluetooth.pan.PanService
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1002
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
D/SettingsProvider( 1016): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1002
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,D/SettingsProvider( 1016): name = bt_svcst_com.broadcom.bt.service.sap.SapService
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1002
,D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,D/SettingsProvider( 1016): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1002
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1016): ret = -1
D/SettingsProvider( 1016): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
,D/SettingsProvider( 1016): selectionArgs: 1002
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
D/SettingsProvider( 1016): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1002
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1,
D/SettingsProvider( 1016): name = bt_svcst_com.android.bluetooth.hid.HidDevService
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1002
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
I/ActivityManager( 1016): Killing 6276:com.wsomacp/u0a25 (adj 15): empty #31
D/AuthorizationBluetoothService( 1697): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3385): Starting #11
,I/Hs20UtilService( 3385): Message received 5011
,D/SecurityLogAgent( 5610): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 5610): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5610): StateMachine : Current State = 1
D/SecurityLogAgent( 5610): StateMachine : Changed Current State = 1
,W/libprocessgroup( 1016): failed to open /acct/uid_10025/pid_6276/cgroup.procs: No such file or directory
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4233, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/WearableService( 6314): callingUid 10012, callindPid: 6314
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/MusicLeanback( 6649): Conditions not met for autocaching. okToAttempt=false
,I/MusicLeanback( 6649): Stop autocaching.
,E/GmsUtils( 6649): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6649): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,V/AlarmManager( 1016): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/SecKeyguardClockView( 1178): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1178): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK,
I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :4
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 10012
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/SSRM:n  ( 1016): SIOP:: AP = 300
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4235, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1016): !@Sync 12
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 330s ago
,I/PowerManagerService( 1016): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1016): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1016): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1016, ws=null) (elapsedTime=19078)
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  324): Waiting for service AtCmdFwd...,
,I/ServiceManager(  324): Waiting for service AtCmdFwd...,
,I/ServiceManager(  324): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  324): Waiting for service AtCmdFwd...,
,I/ServiceManager(  324): Waiting for service AtCmdFwd...,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4236, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate,
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1697): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1697): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1697): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1697): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
D/PersonaManager( 1178): isKioskContainerExistOnDevice
,D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,W/GLSActivity( 1697): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1697): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1697): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1697): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1697): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1697): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1697): 	at android.os.Binder.execTransact(Binder.java:461)
,D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,E/PlayEventLogger( 6336): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6336): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6336): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 6336): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6336): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 6336): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6336): 	at android.os.Binder.execTransact(Binder.java:461)
,W/System  ( 6336): Ignoring header User-Agent because its value was null.
,I/System.out( 6336): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 6336): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 6336): (HTTPLog)-Static: isShipBuild true
I/System.out( 6336): (HTTPLog)-Thread-1124-23507614: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 6336): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10028
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 10028
,D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1016): !@Sync 13
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  324): Waiting for service AtCmdFwd...,
,V/AlarmManager( 1016): waitForAlarm result :8,
,I/ServiceManager(  324): Waiting for service AtCmdFwd...,
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,D/ConnectivityService( 1016): Failed to find a new network - expiring NetTransition Wakelock
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4233, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 14,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4236, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging,
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/Atfwd_Sendcmd(  324): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  324): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 390s ago
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4237, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  324): Waiting for service AtCmdFwd...,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4236, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 15
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 2
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4237, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/bootchecker(  320): bootchecker wake up!!
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 3
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 16,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1016): [PWL] Off : 455s ago
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 17
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 18
,I/Atfwd_Sendcmd(  324): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  324): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 525s ago
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,I/Atfwd_Daemon(  324): Stop the daemon....,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1016): !@Sync 19
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4235, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.,
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4237, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged,
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/TimaService( 1016): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1016): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1016): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 20
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 21
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,I/PowerManagerService( 1016): [PWL] Off : 600s ago
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4237, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 22,
,E/SMD     (  290): DCD OFF
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED,
D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
D/BatteryService( 1016): level:99, scale:100, status:2, health:2, present:true, voltage: 4237, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
D/PowerManagerService( 1016): [PSM] lowPowerModeEnabled: false (mLowPowerModeSetting: false, mAutoLowPowerModeConfigured: false, mBatteryLevel: 99, mLowBatteryTriggerLevel: 0),
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 99
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0,
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1697): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1697): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1697): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1697): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/GLSActivity( 1697): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1697): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1697): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1697): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1697): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1697): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1697): 	at android.os.Binder.execTransact(Binder.java:461)
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,E/PlayEventLogger( 6336): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6336): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6336): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 6336): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6336): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 6336): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6336): 	at android.os.Binder.execTransact(Binder.java:461)
W/System  ( 6336): Ignoring header User-Agent because its value was null.
,I/System.out( 6336): (HTTPLog)-Static: isSBSettingEnabled false
D/PersonaManager( 1178): isKioskContainerExistOnDevice
,D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,D/EnterpriseController(  277): uids 10028
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 10028
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 23,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 680s ago
,D/SSRM:n  ( 1016): SIOP:: AP = 290,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 24
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 25
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 26
,V/AlarmManager( 1016): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/SecKeyguardClockView( 1178): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1178): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:99, scale:100, status:2, health:2, present:true, voltage: 4243, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 99,
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 765s ago
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:99, scale:100, status:2, health:2, present:true, voltage: 4237, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 1016): stay LED for charging
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 99
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 27
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:99, scale:100, status:2, health:2, present:true, voltage: 4245, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for charging
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 99
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,V/AlarmManager( 1016): waitForAlarm result :8
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): !@[BatteryInfo] type : 3, read from efs = 0
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4245, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryService( 1016): Excessive delay in BatteryService : sendIntentLocked(): 13ms,
D/LightsService( 1016): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1016) 
,D/LightsService( 1016): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=3) set On
,E/lights  ( 1016): write_int failed to open -1
D/BatteryService( 1016): turn on LED for fully charged
D/LightsService( 1016): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1016): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/SecContentProvider2( 1016): uri = 14 selection = getSealedState
D/PowerManagerService( 1016): [PSM] lowPowerModeEnabled: false (mLowPowerModeSetting: false, mAutoLowPowerModeConfigured: false, mBatteryLevel: 100, mLowBatteryTriggerLevel: 0)
D/SecContentProvider2( 1016): mCursor = null
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = -1
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId -1 pkgname com.android.systemui
,I/ValidateNoPeople( 1016): skipping global notification
,D/WindowManager( 1016): showStatusBarByNotification() mOpenByNotification=false
,D/PowerManagerService( 1016): [api] acquire WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1178
,I/PowerManagerService( 1016): !@[ps] Screen__On  - 1 :  wl: PowerUI.Notification (14)
I/PowerManagerService( 1016): Waking up from sleep (uid 10054)...
,D/PowerManagerService( 1016): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService( 1016): [s] UserActivityState : 0 -> 1
D/PowerManagerService( 1016): [PWL] sb acquire: PowerManagerService.Display
,I/DisplayPowerController( 1016): Blocking screen on until initial contents have been drawn.
,D/WindowOrientationListener( 1016): sensor enabled
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/DisplayPowerController( 1016): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1016): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1016): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/libsuspend( 1016): !@autosuspend_wakeup_count_disable
I/libsuspend( 1016): !@autosuspend_wakeup_count_disable done
D/DisplayManagerService( 1016): !@display_state: OFF -> ON
,I/Sensors ( 1016): AccelerometerSensor(0) setDelay : 66000000(ns)
,D/SurfaceFlinger(  256): Set power mode=2, type=0 flinger=0xb816a690
D/qdhwcomposer(  256): hwc_setPowerMode: Setting mode 2 on display: 0
,E/qdutils (  256): int qdutils::getHDMINode(): Failed to open fb node 2,
,E/qdutils (  256): int qdutils::getHDMINode(): Failed to find HDMI node
I/DisplayManagerService( 1016): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,D/SensorService( 1016): [SO] changed settle time [1]
V/ActivityManager( 1016): Display changed displayId=0
D/SensorService( 1016): [SO] setDelay [66000000]
D/SensorService( 1016): [SO] activate (ident=0xb8c323a8, enabled=1)
D/SensorService( 1016): [SO] AR_init
I/Sensors ( 1016): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/SensorManager( 1016): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,V/KeyguardServiceDelegate( 1016): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@780c4a6)
,D/KeyguardViewMediator( 1178): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1178): notifyScreenOnLocked
,D/KeyguardViewMediator( 1178): handleNotifyScreenOn
,D/StatusBarKeyguardViewManager( 1178): onScreenTurnedOn()
,D/BatteryMeterView( 1178): onDraw batteryColor : -1
,D/SensorService( 1016): [SO] currT = 840932670000, prevT = 51231096000, diff = 789701574000, [0.172 0.096 10.190]
D/SensorService( 1016): [SO] Reset Rotation Old [100], Init [1]
,V/ActivityManager( 1016): Display changed displayId=0
,D/PersonaManager( 1016): isKioskContainerExistOnDevice
,D/CoverManagerWhiteLists( 1016): isAllowedToUse : SIGNATURE_MATCH
,I/PalmMotion( 1016): [PALM] 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
,I/PalmMotion( 1016): [PALM] SURFACE_PALM_SWIPE: 1
D/PalmMotion( 1016): [PALM] SETTINGS : [TOUCH: true] [SWEEP: true]
,E/MotionRecognitionService( 1016):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
D/PalmMotion( 1016): [PALM] ACCEPTED : [default] PALM_CNT : 3, M_TOUCH : 1000.0, M_SWEEP : 100.0, E_SWEEP : 2.0, IGNORE_M_SWEEP : false
D/LightsService( 1016): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1016) 
D/LightsService( 1016): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,D/LightsService( 1016): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1016): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/KnoxNotification( 1178): ----- inflateViews : modified publicViewLocal -----
,D/qdhwcomposer(  256): hwc_setPowerMode: Done setting mode 2 on display 0
I/qdhwcomposer(  256): handle_blank_event: dpy:0 panel power state: 1
D/NfcService( 1450): call the applyRouting
,E/qdutils (  256): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  256): int qdutils::getHDMINode(): Failed to find HDMI node
,D/SamsungIME( 1783): showDlgMsgBox : false true true
,D/SurfaceControl( 1016): Excessive delay in setPowerMode(): 146ms
D/PowerManagerService( 1016): Excessive delay in !@display_state: ON: 147ms
,D/MISC PowerHAL( 1016): sysfs_write +: /sys/class/input/event3/device/enabled: 1
D/MISC PowerHAL( 1016): sysfs_write +: /sys/class/input/event1/device/enabled: 1
,D/SensorService( 1016): [SO] currT = 841001857000, prevT = 51231096000, diff = 789770761000, [0.172 0.038 10.094]
,D/SensorService( 1016): [SO] 0.172 0.038 10.094
D/SensorService( 1016): [SO] [100 -> 255]
,D/SSRM:a  ( 1016): DeviceInfo:: 000000000000
,D/SSRM:a  ( 1016): SettingsAirViewInfo:: 000000000
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,D/KnoxNotification( 1178): ----- inflateViews : modified KnoxViewLocal -----
,D/PersonaManager( 1178): PersonaID is invalid or persona doesn't exists. : -1
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1178): Icon Only
,I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,D/SecKeyguardClockSingleView( 1178): onScreenTurnedOn
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/StatusBarKeyguardViewManager( 1178): callback.onShown()
V/KeyguardServiceDelegate( 1016): **** SHOWN CALLED ****
,D/DisplayPowerController( 1016): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
,I/DisplayPowerController( 1016): Unblocked screen on after 203 ms
D/DisplayPowerState( 1016): !@ ColorFade exit
,D/ActivityManager( 1016): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1016): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1016): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1016): handleActiveUserChange for user 0
D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
,D/LightsService( 1016): [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 1016) 
,I/SurfaceFlinger(  256): id=10 Removed DolorFade (8/8)
,I/SurfaceFlinger(  256): id=10 Removed DolorFade (-2/8)
D/StatusBar.NetworkController( 1178): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
,D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,E/libEGL  ( 1016): call to OpenGL ES API with no current context (logged once per thread)
D/PowerManagerService( 1016): Excessive delay in ColorFade : dismiss: 15ms
D/LightsService( 1016): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
D/BatteryService( 1016): turn off LED
E/lights  ( 1016): write_led_info failed to open -1
D/LightsService( 1016): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
E/lights  ( 1016): write_led_info failed to open -1
D/LightsService( 1016): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
E/lights  ( 1016): write_led_info failed to open -1
E/lights  ( 1016): write_led_info failed to open -1
E/lights  ( 1016): write_led_info failed to open -1
E/lights  ( 1016): write_led_info failed to open -1
E/lights  ( 1016): write_led_info failed to open -1
E/lights  ( 1016): write_led_info failed to open -1
E/lights  ( 1016): write_led_info failed to open -1
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 5 -> 5
E/SmartFaceService( 1016): onReceive: android.intent.action.SCREEN_ON
D/DisplayPowerController( 1016): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
W/System.err( 1016): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
W/System.err( 1016): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1016): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1016): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1016): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1016): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1016): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:468)
W/System.err( 1016): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1016): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1016): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1016): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1016): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SmartFaceService( 1016): fail to set sysfs 1
W/System.err( 1016): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1016): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1016): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1016): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1016): 	... 10 more
D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/lights  ( 1016): lcd : 5 +
D/StatusBar.NetworkController( 1178): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/BatteryMeterView( 1178): onDraw batteryColor : -1
D/lights  ( 1016): lcd : 5 -
D/DisplayPowerController( 1016): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1016): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/MISC PowerHAL( 1016): sysfs_write -: /sys/class/input/event3/device/enabled: 1
D/PowerManagerService( 1016): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1016): SecHardwareInterface.setBatteryADC : true
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
D/InputMethodManagerService( 1016): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
V/UserPresentBroadcastReceiver( 1653): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
D/MotionRecognitionService( 1016):   mReceiver.onReceive : ACTION_SCREEN_ON
D/SecKeyguardClockView( 1178): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
D/SecKeyguardClockView( 1178): HomeTimezone(): 1
E/MotionRecognitionService( 1016):  handler : SCREEN_ON end
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/WifiNative-HAL( 1016): startHal
,E/wifi    ( 1016): getStaticLongField sWifiHalHandle 0x9d28b7fc
,I/WifiNative-HAL( 1016): Could not start hal
,D/NotificationService( 1016): ACTION_SCREEN_ON
D/LightsService( 1016): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1016) 
,D/LightsService( 1016): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 1016): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1016): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/MISC PowerHAL( 1016): sysfs_write -: /sys/class/input/event1/device/enabled: 1
,D/MISC PowerHAL( 1016): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
D/MISC PowerHAL( 1016): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
D/PowerManagerService-JNI( 1016): Excessive delay in MISC setInteractive(true) while turning screen on: 165ms
I/QCOM PowerHAL( 1016): Got set_interactive hint
,D/lights  ( 1016): button : 1 +
D/PowerManagerService( 1016): Excessive delay in nativeSetInteractive(true): 167ms
D/PowerManagerService( 1016): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 314ms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/Timeline( 5394): Timeline: Activity_idle id: android.os.BinderProxy@282816db time:841174
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/lights  ( 1016): button : 1 -
,D/audio_hw_primary(  285): adev_set_parameters: enter: screen_state=on
,V/voice   (  285): voice_set_parameters: enter: screen_state=on
V/voice   (  285): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  285): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  285): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  285): audio_extn_hfp_set_parameters: enter
,V/audio_hw_primary(  285): adev_set_parameters: exit
,D/IpRemoteDisplayController( 1016): intent received android.intent.action.SCREEN_ON
,D/IpRemoteDisplayController( 1016): Bridge Server is not available
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  290): DCD OFF
,E/SQLiteLog( 1697): (10) POSIX Error : 11 SQLite Error : 3850
,D/GpsLocationProvider( 1016): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/PersonaManagerService( 1016): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler( 1016): MSG_ACTION_SCREEN_ON called
,D/CoverManagerWhiteLists( 1016): isAllowedToUse : SIGNATURE_MATCH
,I/NfcService( 1450): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/NfcService( 1450): call the applyRouting
,D/accuweather( 1568): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
,D/accuweather( 1568): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/accuweather( 1568): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/accuweather( 1568): [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,D/accuweather( 1568): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
D/accuweather( 1568): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
D/accuweather( 1568): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
D/accuweather( 1568): [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 2
D/accuweather( 1568): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1568): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,E/accuweather( 1568): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 19 06
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,I/SamsungIME( 1783): getNextShiftState() cursorCapsMode : 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PowerManagerService( 1016): [PWL] sb release: PowerManagerService.Broadcasts
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,D/daemonapp( 1285): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1285): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1285): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1285): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1285): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1285): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1285): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1285): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1285): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1285): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1285): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1285): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1285): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1285): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1285): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1449705120000
D/daemonapp( 1285): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1449684371272
,D/daemonapp( 1285): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1285): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/daemonapp( 1285): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1285): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1285): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1285): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 1285): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/lights  ( 1016): button : 0 +
,D/lights  ( 1016): button : 0 -
,D/SSRM:a  ( 1016): DeviceInfo:: 000000000000
,D/SSRM:a  ( 1016): SettingsAirViewInfo:: 000000000
,E/SMD     (  290): DCD OFF,
,D/SensorService( 1016): [SO] 0.172 0.038 10.113
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1178): Icon Only
,I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4231, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate,
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,D/SensorService( 1016): [SO] 0.172 0.038 10.094
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1016): !@Sync 28,
,E/SMD     (  290): DCD OFF
,D/PowerManagerService( 1016): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1178 (0x0)
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4230, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1016): Plugged
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate,
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,D/PowerManagerService( 1016): [s] UserActivityState : 1 -> 2
D/DisplayPowerController( 1016): getFinalBrightness : Summary is 1 -> 1
D/DisplayPowerController( 1016): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 1016): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  ( 1016): lcd : 1 +
D/DisplayPowerController( 1016): getFinalBrightness : Summary is 1 -> 1
D/DisplayPowerController( 1016): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 1016): lcd : 1 -
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 1 -> 1
D/DisplayPowerController( 1016): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/SMD     (  290): DCD OFF
,D/SensorService( 1016): [SO] 0.172 0.057 10.094
,E/SMD     (  290): DCD OFF
,D/PowerManagerService( 1016): [s] UserActivityState : 2 -> 4
,I/PowerManagerService( 1016): Nap time (uid 1000)...
D/PowerManagerService( 1016): handleSandman : startDreaming: false  (canDreamLocked: false  canDozeLocked: false)
I/PowerManagerService( 1016): !@[ps] Screen__Off - 1 :  dream(timeout) (2)
I/PowerManagerService( 1016): Going to sleep due to screen timeout (uid 1000)...
,D/PowerManagerService( 1016): [PWL] sb acquire: PowerManagerService.Broadcasts
V/WindowOrientationListener( 1016): WindowOrientationListener disabled
,D/SensorService( 1016): [SO] activate (ident=0xb8c323a8, enabled=0)
D/PowerManagerService( 1016): SecHardwareInterface.setBatteryADC : false
,D/PowerManagerService( 1016): handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
I/Sensors ( 1016): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
D/PowerManagerService( 1016): handleSandman : startDream(true)
,E/PowerManagerService( 1016): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService( 1016): Sleeping (uid 1000)...
,D/PowerManagerService( 1016): [s] UserActivityState : 4 -> 0
,I/SurfaceFlinger(  256): id=15 createSurf (720x1280),-1 flag=20004, DolorFade
,D/SensorManager( 1016): unregisterListener ::   ,
D/KeyguardViewMediator( 1178): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 1178): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1178): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1178): notifyScreenOffLocked
,D/KeyguardViewMediator( 1178): timeout : 5000
,D/PowerManagerService( 1016): Excessive delay in ColorFade : createSurface: 15ms
,D/PowerManagerService( 1016): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 24ms
,D/DisplayPowerController( 1016): ColorFade: onAnimationStart
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1016): performScreenOffTransition : no brightness animation
,V/ActivityThread( 5394): updateVisibility : ActivityRecord{16a33451 token=android.os.BinderProxy@282816db {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/KeyguardViewMediator( 1178): setting alarm to turn off keyguard, seq = 2
D/KeyguardViewMediator( 1178): handleNotifyScreenOff
,D/VolumePanel( 1178): onScreenTurnedOff()
D/VolumePanel( 1178): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
D/VolumePanel( 1178): mCoverBroadcastReceiver: Screen OFF end
,D/SecKeyguardClockSingleView( 1178): onScreenTurnedOff
,D/LightsService( 1016): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1016) 
,D/LightsService( 1016): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/BatteryService( 1016): turn on LED for fully charged
,D/LightsService( 1016): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
E/lights  ( 1016): write_int failed to open -1
D/LightsService( 1016): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SmartFaceService( 1016): onReceive: android.intent.action.SCREEN_OFF
,W/System.err( 1016): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
,W/System.err( 1016): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1016): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1016): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1016): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1016): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
,W/System.err( 1016): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:474)
W/System.err( 1016): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1016): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1016): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1016): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 1016): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1016): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1016): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1016): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
,W/System.err( 1016): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1016): 	... 10 more
E/SmartFaceService( 1016): fail to set sysfs 0
,I/StatusBar( 1178): Icon Only
,D/PanelView( 1178): There is/are notification(s) 
D/MotionRecognitionService( 1016):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService( 1016):  handler : SCREEN_OFF end 
,D/NotificationService( 1016): ACTION_SCREEN_OFF
D/LightsService( 1016): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1016) 
,D/LightsService( 1016): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/LightsService( 1016): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1016): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/audio_hw_primary(  285): adev_set_parameters: enter: screen_state=off
,V/voice   (  285): voice_set_parameters: enter: screen_state=off
V/voice   (  285): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  285): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  285): platform_set_parameters: exit with code(-2)
,D/audio_hw_hfp(  285): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  285): adev_set_parameters: exit
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/IpRemoteDisplayController( 1016): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 1016): Bridge Server is not available
,D/DisplayPowerState( 1016): !@ ColorFade entry
,D/DisplayPowerController( 1016): ColorFade: onAnimationEnd
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 0 -> 0
,D/lights  ( 1016): lcd : 0 +
D/DisplayPowerController( 1016): performScreenOffTransition : no brightness animation
,D/lights  ( 1016): lcd : 0 -
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 0 -> 0
D/DisplayPowerController( 1016): performScreenOffTransition : no brightness animation
D/PowerManagerService( 1016): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1016): [PWL] sb release: PowerManagerService.Display
D/MISC PowerHAL( 1016): sysfs_write +: /sys/class/input/event3/device/enabled: 0
,D/MISC PowerHAL( 1016): sysfs_write +: /sys/class/input/event1/device/enabled: 0
D/MISC PowerHAL( 1016): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/MISC PowerHAL( 1016): sysfs_write -: /sys/class/input/event3/device/enabled: 0
,D/MISC PowerHAL( 1016): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 1016): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
I/QCOM PowerHAL( 1016): Got set_interactive hint
,D/DisplayManagerService( 1016): !@display_state: ON -> OFF
,I/DisplayManagerService( 1016): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager( 1016): Display changed displayId=0
,D/SurfaceFlinger(  256): Set power mode=0, type=0 flinger=0xb816a690
D/qdhwcomposer(  256): hwc_setPowerMode: Setting mode 0 on display: 0
,E/qdutils (  256): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  256): int qdutils::getHDMINode(): Failed to find HDMI node
,D/StatusBar.NetworkController( 1178): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
,D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/qdhwcomposer(  256): handle_blank_event: dpy:0 panel power state: 0
,E/qdutils (  256): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  256): int qdutils::getHDMINode(): Failed to find HDMI node
,D/qdhwcomposer(  256): hwc_setPowerMode: Done setting mode 0 on display 0
D/SurfaceControl( 1016): Excessive delay in setPowerMode(): 256ms
D/PowerManagerService( 1016): Excessive delay in !@display_state: OFF: 261ms
,I/libsuspend( 1016): !@autosuspend_wakeup_count_enable
I/libsuspend( 1016): !@autosuspend_wakeup_count_enable done
D/PowerManagerService( 1016): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 267ms
I/PowerManagerService( 1016): [PWL] Off : 0s ago
I/PowerManagerService( 1016): [PWL]   PowerManagerService.Broadcasts: ref count=1
,E/SMD     (  290): DCD OFF
,D/GpsLocationProvider( 1016): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.SCREEN_OFF
,V/EmergencyMode( 1418): [EmergencyStateReceiver] binteractive [false] why[3]
,D/PersonaManagerService( 1016): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 1016): MSG_ACTION_SCREEN_OFF called
,D/NfcService( 1450): call the applyRouting
,D/accuweather( 1568): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 1568): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1568): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/daemonapp( 1285): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 7
,D/accuweather( 1568): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1568): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1568): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1568): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,E/LibSecureUISvc( 1867): svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
,D/PowerManagerService( 1016): [PWL] sb release: PowerManagerService.Broadcasts
,D/daemonapp( 1285): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1285): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,D/accuweather( 1568): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! ,
D/accuweather( 1568): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
D/accuweather( 1568): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
D/accuweather( 1568): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1568): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
,D/accuweather( 1568): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/accuweather( 1568): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :4
,D/KeyguardViewMediator( 1178): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/KeyguardViewMediator( 1178): doKeyguard: not showing because lockscreen is off
V/KeyguardEffectViewController( 1178): *** Keyguard wallpaper service already unbounded
,I/PowerManagerService( 1016): [PWL] Off : 5s ago
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4243, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 290,
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 15s ago
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 29
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :8
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1016): SIOP:: AP = 290,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4235, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 1016): [PWL] Off : 30s ago
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/SecKeyguardClockView( 1178): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
,D/SecKeyguardClockView( 1178): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4243, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,D/TimaService( 1016): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 1016): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1016): TimaServiceHandler.handleMessage what =1
,E/SMD     (  290): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response_id = 3,
I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1016): !@Sync 30,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4245, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate,
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 1016): [PWL] Off : 50s ago
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 280
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 270,
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 75s ago
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 31,
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :8
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4246, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 105s ago,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 32
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4246, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4245, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/BatteryService( 1016): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,E/SMD     (  290): DCD OFF
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 57170(6MB) AllocSpace objects, 261(4MB) LOS objects, 33% free, 27MB/40MB, paused 2.511ms total 169.993ms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1697): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1697): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1697): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1697): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/GLSActivity( 1697): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1697): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1697): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1697): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1697): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1697): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1697): 	at android.os.Binder.execTransact(Binder.java:461)
,E/PlayEventLogger( 6336): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6336): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6336): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 6336): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6336): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 6336): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6336): 	at android.os.Binder.execTransact(Binder.java:461)
D/PersonaManager( 1178): isKioskContainerExistOnDevice
W/System  ( 6336): Ignoring header User-Agent because its value was null.
D/PersonaManager( 1178): isKioskContainerExistOnDevice
,I/System.out( 6336): (HTTPLog)-Static: isSBSettingEnabled false
I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1178): Icon Only,
I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,D/EnterpriseController(  277): uids 10028
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 10028
,D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4246, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 33
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 140s ago
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 34
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 180s ago
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4245, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 35
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4245, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4241, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1016): Plugged
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 225s ago,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 36,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4242, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4243, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4246, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 37
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :8
,V/AlarmManager( 1016): No more alarm at this time.nowELAPSED=1131086 batch.start=1956585
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/SecKeyguardClockView( 1178): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1178): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4247, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 275s ago
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1016): !@Sync 38
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4247, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 39
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :8
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 330s ago
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4237, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4247, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 1016): stay LED for fully charged
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,D/TimaService( 1016): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1016): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1016): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 1016): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 1016): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 1016): Updating Usage Statistics in DB @ 1449684744757
,I/NetworkDataUsageDb( 1016): ::getAppControlDB: DB is Created 
,I/NetworkDataUsageDb( 1016): ::isTableExists: Table exists 
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/ApplicationUsage( 1016): Done Updating Usage Statistics in DB @ 1449684744792
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 40
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4247, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 41
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 390s ago
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4248, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 42
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4247, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4248, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1016): Plugged
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
I/MotionRecognitionService( 1016): mGripSensorEnabled= false,
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1697): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1697): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1697): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1697): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/GLSActivity( 1697): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1697): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1697): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1697): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1697): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1697): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1697): 	at android.os.Binder.execTransact(Binder.java:461)
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
D/PersonaManager( 1178): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
,E/PlayEventLogger( 6336): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6336): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6336): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 6336): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6336): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 6336): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6336): 	at android.os.Binder.execTransact(Binder.java:461)
D/PanelView( 1178): There is/are notification(s) 
W/System  ( 6336): Ignoring header User-Agent because its value was null.
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
I/System.out( 6336): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10028
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 10028
,D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 43
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 455s ago
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 44
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4248, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 45
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4248, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1016): Plugged
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4248, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,I/PowerManagerService( 1016): [PWL] Off : 525s ago
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 46
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 47
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 48
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 600s ago
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4250, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.,
D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1016): Plugged
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate,
I/MotionRecognitionService( 1016): mGripSensorEnabled= false,
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4248, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 49,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4248, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/TimaService( 1016): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 1016): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1016): TimaServiceHandler.handleMessage what =1
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1016): !@Sync 50,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4247, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1016): Plugged
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4248, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 51
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 680s ago
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4250, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4248, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4250, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 52
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1697): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1697): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1697): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1697): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/GLSActivity( 1697): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1697): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1697): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1697): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1697): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1697): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1697): 	at android.os.Binder.execTransact(Binder.java:461)
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,E/PlayEventLogger( 6336): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6336): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6336): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 6336): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6336): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 6336): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6336): 	at android.os.Binder.execTransact(Binder.java:461)
,W/System  ( 6336): Ignoring header User-Agent because its value was null.
D/PersonaManager( 1178): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1178): Icon Only
I/System.out( 6336): (HTTPLog)-Static: isSBSettingEnabled false
I/StatusBar( 1178): Icon Only
,D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,D/EnterpriseController(  277): uids 10028
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 10028
,D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 53
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1016): [PWL] Off : 765s ago
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 54
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 55
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 56
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4250, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,I/PowerManagerService( 1016): [PWL] Off : 855s ago
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 57
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1016): !@Sync 58,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1016): !@Sync 59
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/NetworkStatsFactory( 1016): UpdateStatsForKnox updated
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/TimaService( 1016): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1016): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1016): TimaServiceHandler.handleMessage what =1
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4248, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged,
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 1016): !@Sync 60
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 950s ago,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4250, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1016): !@Sync 61
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1016): !@Sync 62
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,TIME-OUT KILL (timeout was 1800000ms),D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4238, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
E/SMD     (  290): DCD OFF
D/AndroidRuntime( 7573): 
D/AndroidRuntime( 7573): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7573): CheckJNI is OFF
D/AndroidRuntime( 7573): readGMSProperty: start
D/AndroidRuntime( 7573): readGMSProperty: already setted!!
D/AndroidRuntime( 7573): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 7573): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 7573): readGMSProperty: end
D/AndroidRuntime( 7573): addProductProperty: start
E/AffinityControl( 7573): AffinityControl: registerfunction enter
D/AndroidRuntime( 7573): Calling main entry com.android.commands.pm.Pm
D/PackageManager( 1016): START PACKAGE DELETE: observer{850329951}
D/PackageManager( 1016): pkg{<packageName>}
D/PackageManager( 1016): user{0}
D/PackageManager( 1016): caller{2000}
D/PackageManager( 1016): flags{3}
D/PersonaManagerService( 1016): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 1016): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1016): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1016): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1016): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1016): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManager( 1016): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1016): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1016): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1016): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 1016): !@killApplicatoin: 10175, uninstall pkg
I/ActivityManager( 1016): Force stopping com.test.thalitest appid=10175 user=-1: uninstall pkg
I/ActivityManager( 1016): Killing 5394:com.test.thalitest/u0a175 (adj 0): stop com.test.thalitest cause uninstall pkg
W/PackageSettings( 1016): Skipping PackageSetting{3c754ca0 com.example.hello/10174} due to missing metadata
I/ActivityManager( 1016): Killing 6336:com.android.vending/u0a28 (adj 15): empty #31
I/ActivityManager( 1016): Killing 6295:com.google.android.gms:car/u0a12 (adj 15): empty #32
I/ActivityManager( 1016): Killing 6102:com.android.calendar/u0a135 (adj 15): empty #33
I/ActivityManager( 1016): Killing 6237:com.sec.android.widgetapp.SPlannerAppWidget/u0a134 (adj 15): empty #34
I/ActivityManager( 1016): Killing 2789:com.wssyncmldm/1000 (adj 15): SPC_empty #35
I/ActivityManager( 1016): Killing 2580:com.sec.phone/1001 (adj 15): SPC_empty #36
I/ActivityManager( 1016): Killing 3555:com.sec.bcservice/1000 (adj 15): SPC_empty #37
I/ActivityManager( 1016): Killing 3314:com.sec.android.pagebuddynotisvc/u0a116 (adj 15): SPC_empty #38
I/ActivityManager( 1016):   Force finishing activity ActivityRecord{f0df710 u0 com.test.thalitest/.MainActivity t228}
I/WindowState( 1016): WIN DEATH: Window{2cfc4a88 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  256): id=12 Removed NainActivit (6/8)
I/SurfaceFlinger(  256): id=12 Removed NainActivit (-2/8)
D/InputDispatcher( 1016): Focus left window: 5394
I/ProcessStatsService( 1016): Prepared write state in 8ms
I/SurfaceFlinger(  256): id=12 Removed NainActivit (-2/8)
D/InputDispatcher( 1016): Focused application released
D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
I/ActivityManager( 1016): Force stopping com.test.thalitest appid=10175 user=0: pkg removed
E/JavaBinder( 1016): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1016): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1016): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1016): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1016): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1016): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1016): !!! FAILED BINDER TRANSACTION !!!
W/ActivityManager( 1016): CustomStartingWindow se packge removed so remove capture also
W/ActivityManager( 1016): Scheduling restart of crashed service com.google.android.gms/.car.InCallServiceImpl in 1000ms
I/art     ( 3691): Explicit concurrent mark sweep GC freed 2829(169KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 6MB/11MB, paused 763us total 23.189ms
W/ActivityManager( 1016): ProcessRecord{1568b7ac 2580:com.sec.phone/1001} is already killed
E/lowmemorykiller(  253): Error writing /proc/2580/oom_score_adj; errno=22
W/ActivityManager( 1016): Exception when unbinding service com.sec.phone/.SecPhoneService
W/ActivityManager( 1016): android.os.DeadObjectException
W/ActivityManager( 1016): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager( 1016): 	at android.os.BinderProxy.transact(Binder.java:511)
W/ActivityManager( 1016): 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:1029)
W/ActivityManager( 1016): 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1997)
W/ActivityManager( 1016): 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2381)
W/ActivityManager( 1016): 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:18582)
W/ActivityManager( 1016): 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:6593)
W/ActivityManager( 1016): 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:6806)
W/ActivityManager( 1016): 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1606)
W/ActivityManager( 1016): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:566)
W/ActivityManager( 1016): ProcessRecord{1568b7ac 2580:com.sec.phone/1001} is already killed
W/ActivityManager( 1016): Scheduling restart of crashed service com.sec.bcservice/.BroadcastService in 10988ms
I/InputReader( 1016): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1653): Ignoring removeGeofence because network location is disabled.
E/SamsungIME( 1783): mOCRHelper is null
W/ActivityManager( 1016): Scheduling restart of crashed service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc in 20919ms
I/KLMS-2.5.183: ( 3417): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Dec 09 19:23:40 GMT+01:00 2015
D/RegisteredComponentCache( 1450): Collect Tech packages for Knox
W/ActivityManager( 1016): Scheduling restart of crashed service com.wssyncmldm/.XDMService in 30905ms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
D/PersonaManager( 1450): isKioskContainerExistOnDevice
I/KLMS-2.5.183: ( 3417): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 1016): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=28
I/splitIntent( 1016): base  index=28, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1016): other index=31, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1016): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7587): MountEmulatedStorage()
E/Zygote  ( 7587): v2
I/libpersona( 7587): KNOX_SDCARD checking this for 10094
I/libpersona( 7587): KNOX_SDCARD not a persona
I/KLMS-2.5.183: ( 3417): KLMSIntentService(): onCreate()
I/SELinux ( 7587): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/KLMS-2.5.183: ( 3417): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/SELinux ( 7587): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 7587): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7587 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
I/KLMS-2.5.183: ( 3417): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
I/KLMS-2.5.183: ( 3417): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
D/SecContentProvider2( 1016): mCursor = null
D/TimaKeyStoreProvider( 7587): TimaSignature is unavailable
D/ActivityThread( 7587): Added TimaKeyStore provider
I/KLMS-2.5.183: ( 3417): KLMSIntentService(): PACKAGE_REMOVED
I/KLMS-2.5.183: ( 3417): KLMSIntentService(): listeningToPackageRemoved().START
I/KLMS-2.5.183: ( 3417): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
I/art     ( 1016): Explicit concurrent mark sweep GC freed 49467(7MB) AllocSpace objects, 369(5MB) LOS objects, 33% free, 27MB/40MB, paused 3.564ms total 238.916ms
I/art     ( 1016): WaitForGcToComplete blocked for 218.498ms for cause Explicit
D/elm:15183( 7587): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15183( 7587): ELMEngine.ELMEngine( context ).
D/elm:15183( 7587): MDMBridge.setEnterpriseBridge()
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
D/elm:15183( 7587): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:15183( 7587): ElmAgentService : onCreate()
D/PersonaManager( 1450): isKioskContainerExistOnDevice
D/RegisteredServicesCache( 1450): empty dynamic service
D/elm:15183( 7587): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15183( 7587): MainReceiver.listeningToPackageRemoved()
D/elm:15183( 7587): MDMBridge.getInstance()
D/elm:15183( 7587): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:15183( 7587): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:15183( 7587): ElmAgentService : onDestroy().
I/ActivityManager( 1016): Killing 6416:com.google.android.apps.books/u0a75 (adj 15): empty #31
I/KLMS-2.5.183: ( 3417): KLMSIntentService(): listeningToPackageRemoved().END
I/KLMS-2.5.183: ( 3417): KLMSIntentService(): onDestroy()
D/RCPManagerService( 1016): PackageReceiver onReceive()
I/HarmonyEASService( 1016): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy( 1016): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1016): PackageRemovalReceiver::onReceive Enter
D/OTPFW   ( 1016): OtpDbHelper::getInstance New instance created
D/OTPFW   ( 1016): DBIntegrity::getInstance - New instance created
D/OTPFW   ( 1016): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10175 container id = 0
I/OTPFW   ( 1016): ProvisionData::getAllEntries Enter
E/OTPFW   ( 1016): ProvisionData::getAllEntries Table is empty
D/BackupManagerService( 1016): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
D/JobSchedulerService( 1016): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1016): uID is 10175
V/EnterpriseBillingPolicy( 1016): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - end - null
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1016): uID is 10175
V/EnterpriseBillingPolicy( 1016): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - end - null
D/SSRM:aZ ( 1016): MSG_TYPE_APP_REMOVED::
D/TaskPersister( 1016): removeObsoleteFile: deleting file=228_task.xml
I/ProcessStatsService( 1016): Pruning old procstats: /data/system/procstats/state-2015-12-09-06-39-38.bin
W/libprocessgroup( 1016): failed to open /acct/uid_10012/pid_6295/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10135/pid_6102/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3555/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1001/pid_2580/cgroup.procs: No such file or directory
I/PCWCLIENTTRACE_PushUtil( 6631): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6631): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6631): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6631): [onReceive] - android.intent.action.PACKAGE_REMOVED
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/art     ( 1016): Explicit concurrent mark sweep GC freed 12532(631KB) AllocSpace objects, 2(79KB) LOS objects, 33% free, 27MB/40MB, paused 14.806ms total 200.493ms
E/Zygote  ( 7604): MountEmulatedStorage()
E/Zygote  ( 7604): v2
I/libpersona( 7604): KNOX_SDCARD checking this for 10032
I/libpersona( 7604): KNOX_SDCARD not a persona
I/SELinux ( 7604): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 7604): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1016): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7604 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
E/SELinux ( 7604): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7604): TimaSignature is unavailable
D/ActivityThread( 7604): Added TimaKeyStore provider
D/EnterpriseDeviceManagerService( 1016): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1016): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1016): no available spell checker services found
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/FeatureConfig( 7604): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/PackageManager( 1016): delete codoeFile: 
D/AASAuninstall( 1016): userId = 0, info.removedAppID = -1, info.uid = 10175, packageName = com.test.thalitest
I/AASA_removePackage( 1016): UID=10175 Target=com.test.thalitest
D/PackageManager( 1016): result of delete: 1{850329951}
E/Zygote  ( 7621): MountEmulatedStorage()
E/Zygote  ( 7621): v2
I/libpersona( 7621): KNOX_SDCARD checking this for 10038
I/libpersona( 7621): KNOX_SDCARD not a persona
I/SELinux ( 7621): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=7621 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
I/SELinux ( 7621): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 7621): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Killing 6584:com.samsung.android.app.FileShareClient/u0a68 (adj 15): empty #31
D/AndroidRuntime( 7573): Shutting down VM
D/TimaKeyStoreProvider( 7621): TimaSignature is unavailable
D/ActivityThread( 7621): Added TimaKeyStore provider
W/ResourcesManager( 7621): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7621): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourceType( 1016): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ResourcesManager( 1016): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1016): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1016): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/UsbSettingsManager( 1016): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 1016): onPackageRemoved : com.test.thalitest
W/libprocessgroup( 1016): failed to open /acct/uid_10134/pid_6237/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10116/pid_3314/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10028/pid_6336/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2789/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10075/pid_6416/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10068/pid_6584/cgroup.procs: No such file or directory
W/ResourcesManager( 7604): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
I/SL_DEBUG( 7621): isLoggable:: isProductShip = 1
I/SL_DEBUG( 7621): isLoggable:: SL_DEBUG_EXIST = false
W/ResourcesManager( 7604): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/art     ( 7573): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
W/ResourcesManager( 7604): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 7604): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/GalaxyFinderApplication( 7604): system/finder_cp/cpdata.xml file not found
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7621): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7621): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
I/SA      ( 5287): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
I/SA      ( 5287): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10175 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7649): MountEmulatedStorage()
E/Zygote  ( 7649): v2
I/libpersona( 7649): KNOX_SDCARD checking this for 10044
I/libpersona( 7649): KNOX_SDCARD not a persona
I/SELinux ( 7649): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 7649): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 7649): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7649 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
V/AlarmManager( 1016): waitForAlarm result :4
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
V/AlarmManager( 1016): waitForAlarm result :8
V/AlarmManager( 1016): No more alarm at this time.nowELAPSED=1891916 batch.start=1956585
D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
D/TimaKeyStoreProvider( 7649): TimaSignature is unavailable
D/ActivityThread( 7649): Added TimaKeyStore provider
E/SQLiteLog( 1547): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 1547): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
D/SecKeyguardClockView( 1178): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
D/SecKeyguardClockView( 1178): HomeTimezone(): 1
E/DatabaseUtils( 1547): Writing exception to parcel
E/DatabaseUtils( 1547): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DatabaseUtils( 1547): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DatabaseUtils( 1547): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/DatabaseUtils( 1547): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DatabaseUtils( 1547): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DatabaseUtils( 1547): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/DatabaseUtils( 1547): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
E/DatabaseUtils( 1547): 	at com.sec.android.provider.logsprovider.LogsProvider.delete(LogsProvider.java:3550)
E/DatabaseUtils( 1547): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:324)
E/DatabaseUtils( 1547): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:206)
E/DatabaseUtils( 1547): 	at android.os.Binder.execTransact(Binder.java:461)
D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
E/AndroidRuntime( 1746): FATAL EXCEPTION: IntentService[VoicemailCleanupService]
E/AndroidRuntime( 1746): Process: android.process.acore, PID: 1746
E/AndroidRuntime( 1746): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1746): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:179)
E/AndroidRuntime( 1746): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
E/AndroidRuntime( 1746): 	at android.content.ContentProviderProxy.delete(ContentProviderNative.java:543)
E/AndroidRuntime( 1746): 	at android.content.ContentResolver.delete(ContentResolver.java:1352)
E/AndroidRuntime( 1746): 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:476)
E/AndroidRuntime( 1746): 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:130)
E/AndroidRuntime( 1746): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:324)
E/AndroidRuntime( 1746): 	at android.content.ContentResolver.delete(ContentResolver.java:1352)
E/AndroidRuntime( 1746): 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
E/AndroidRuntime( 1746): 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
E/AndroidRuntime( 1746): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1746): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1746): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 1746): 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
