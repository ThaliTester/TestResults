#### Test 5065027865f659b_thali07_samsung-SM-A500FU Logs


```
--------- beginning of main
D/Mms/MmsConfig( 5742):  enable multiwindow = true
E/Mms/MessageUtils( 5742): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 5742): updateCountryIso : update country iso info 
D/Mms/MmsConfig( 5742): [end]    init() consume time = 136.653854
D/Mms/Contact( 5742): [start]    init() consume time = 0.554531
D/Mms/Contact( 5742): [end]    init consume time = 6.030521
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
--------- beginning of system
D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
D/Mms/DraftCache( 5742): [start]    rebuildCache consume time = 13.334063
D/TP/MmsSmsProvider( 1457): query,matched:13, calling pid = 5742
D/TP/MmsSmsProvider( 1457): match 13:Elapsed time : 2.097 ms
D/TP/MmsSmsProvider( 1457): query,matched:12, calling pid = 5742
D/TP/MmsSmsProvider( 1457): match 12:Elapsed time : 1.341 ms
D/Mms/DraftCache( 5742): [end]    rebuildCache consume time = 12.197604
D/Mms/MethodReflector( 5742): getSubId is called
D/Mms/TelephonyUtils( 5742): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 5742): getTelephonyProperty is called
D/Mms/DownloadManager( 5742): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5742): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5742): auto download without roaming -> true
D/Mms/DownloadManager( 5742): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/MethodReflector( 5742): getSubId is called
D/Mms/MethodReflector( 5742): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 5742): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 5742): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 5742): getTelephonyProperty is called
D/Mms/DownloadManager( 5742): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 5742): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 5742): auto download without roaming -> true
D/Mms/DownloadManager( 5742): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 5742): auto download during roaming secondary -> false
D/Mms/DownloadManager( 5742): mAutoDownload ------> true
D/ComposerPerformance( 5742): 1449598337219 ms / [DONE] Composer constructor
E/CII     ( 5742): CommonIMSInterface: VoLTE CSC feature disabled.
I/Mms/ReservationManager( 5742): ReservationManager()
I/Mms/ReservationManager( 5742): resetAfterConnected()
D/TP/MmsSmsProvider( 1457): query,matched:7, calling pid = 5742
D/TP/MmsSmsProvider( 1457): match 7:Elapsed time : 1.932 ms
I/Mms/ReservationManager( 5742): getReservedSendMessageCount(): retMessageCount=0
D/Mms/Conversation( 5742): [start]    init() consume time = 36.289687
I/DBG_POLICYDM( 5808): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
D/Mms/MmsApp( 5742): [end]    onCreate() consume time = 1.421771
D/TP/MmsSmsProvider( 1457): deleteConversation threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1457): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1457): updateThread(), thread_id = 9223372036854775807
V/TP/MmsSmsDatabaseHelper( 1457): sUpgradeVersion = 0, db.getVersion() = 81
I/DBG_POLICYDM( 5808): [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
D/TP/MmsSmsProvider( 1457): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1457): need read changed broadcast:false
D/Mms/Conversation( 5742): [end]    init consume time = 8.900834
D/Mms/MessagingNotification( 5742): [start]    init() consume time = 1.244322
D/Mms/MessagingNotification( 5742): [end]    init consume time = 1.84224
D/TP/MmsSmsProvider( 1457): query,matched:0, calling pid = 5742
V/TP/MmsSmsProvider( 1457): getSimpleConversations entered.
D/TP/MmsSmsProvider( 1457): match 0:Elapsed time : 1.100 ms
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/Mms/Synchronizer( 5742): [start]    doSync consume time = 13.301094
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/Mms/DownloadManager( 5742): Service state changed: Bundle[mParcelledData.dataSize=744]
D/Mms/SpamFilter( 5742): [start]    SpamFilter fill() begin consume time = 2.194531
D/Mms/DownloadManager( 5742): roaming ------> false, mSimSlot = 0
D/Mms/MethodReflector( 5742): getSubId is called
D/Mms/TelephonyUtils( 5742): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 5742): getTelephonyProperty is called
D/Mms/DownloadManager( 5742): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5742): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5742): auto download without roaming -> true
D/Mms/DownloadManager( 5742): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5742): mAutoDownload ------> true
E/Zygote  ( 5922): MountEmulatedStorage()
E/Zygote  ( 5922): v2
I/libpersona( 5922): KNOX_SDCARD checking this for 10072
I/libpersona( 5922): KNOX_SDCARD not a persona
I/SELinux ( 5922): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5922): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5922): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5922 uid=10072 gids={50072, 9997} abi=armeabi-v7a
D/Mms/ArtClassLoader( 5742): init [DONE] art
D/TP/MmsSmsProvider( 1457): update, matched:300, calling pid = 5742
V/TP/MmsSmsProvider( 1457): syncDBData start
V/TP/MmsSmsProvider( 1457): syncDBData sms end
V/TP/MmsSmsProvider( 1457): syncDBData mms end
V/TP/MmsSmsProvider( 1457): syncDBData end
D/Mms/Synchronizer( 5742): [end]    doSync consume time = 40.673802
D/TP/MmsSmsProvider( 1457): query,matched:400, calling pid = 5742
D/Mms/SpamFilter( 5742): [end]    SpamFilter fill() finished consume time = 8.753073
D/TimaKeyStoreProvider( 5922): TimaSignature is unavailable
D/ActivityThread( 5922): Added TimaKeyStore provider
D/ActivityManager( 1020): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ConfigFetchService( 1923): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
D/Mms/FreeMessageStatusReceiver( 5742): onReceive, action : android.intent.action.PACKAGE_ADDED
D/ActivityManager( 1020): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
I/ConfigFetchService( 1923): launchTask
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/BadgeProvider( 5922): onCreate
D/BadgeProvider( 5922): DatabaseHelper
E/Zygote  ( 5941): MountEmulatedStorage()
E/Zygote  ( 5941): v2
I/libpersona( 5941): KNOX_SDCARD checking this for 10047
I/libpersona( 5941): KNOX_SDCARD not a persona
I/SELinux ( 5941): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5941 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
I/SELinux ( 5941): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/SELinux ( 5941): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
D/ChimeraCfgMgr( 1923): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1923): Module APK com.google.android.play.games already loaded
I/PeopleContactsSync( 1923): CP2 sync disabled
D/Mms/FreeMessageReceiverService( 5742): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 5742): onHandleIntent: ACTION_PACKAGE_ADDED
I/ActivityManager( 1020): Killing 3798:com.android.providers.calendar/u0a42 (adj 15): empty #31
I/ActivityManager( 1020): Killing 5177:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #32
D/TimaKeyStoreProvider( 5941): TimaSignature is unavailable
D/ChimeraCfgMgr( 1923): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/ActivityThread( 5941): Added TimaKeyStore provider
D/Vision  ( 1923): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1923): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1923): No vision deps
V/ConfigFetchTask( 1923): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1XthS64CiQjYy6hQB7nj3mphv59HZNQhVEMJJjEXvjeEJ-0vghaIXNVJGGU917qOXpLXpJufG9HqqAUJDWfWySzOOeGnGFjWjmz9jAce_1L21WAgU9_sXUOx5nYGK8T_DKW5Pa4PMcJXECh-DLOcoGljfx5_2L_r80mbie96IuDgZxohgax2aqR8TxQUYrusDCxbOfmDt3xyCLWWiXDiwMZugNHEP-NBWT0xVlfo22zyngyZRI
D/Mms/MessagingNotification( 5742): checkBadgeCount unreadCount=0 badgeCount=0
D/TP/SmsProvider( 1457): query,matched:26, calling pid = 5742
D/TP/SmsProvider( 1457): match 26:Elapsed time : 1.440 ms
W/ResourcesManager( 5941): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5941): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5941): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/TP/MmsSmsProvider( 1457): query,matched:6, calling pid = 5742
D/TP/MmsSmsProvider( 1457): match 6:Elapsed time : 1.632 ms
I/SL_DEBUG( 5863): isLoggable:: isProductShip = 1
I/SL_DEBUG( 5863): isLoggable:: SL_DEBUG_EXIST = false
D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5964): MountEmulatedStorage()
E/Zygote  ( 5964): v2
I/libpersona( 5964): KNOX_SDCARD checking this for 10025
I/libpersona( 5964): KNOX_SDCARD not a persona
I/SELinux ( 5964): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5964): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5964): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5964 uid=10025 gids={50025, 9997} abi=armeabi-v7a
I/GoogleURLConnFactory( 1923): Using platform SSLCertificateSocketFactory
W/libprocessgroup( 1020): failed to open /acct/uid_10042/pid_3798/cgroup.procs: No such file or directory
D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_5177/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 5964): TimaSignature is unavailable
D/ActivityThread( 5964): Added TimaKeyStore provider
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1020): Killing 3927:com.google.android.talk/u0a104 (adj 15): empty #31
I/DBG_POLICYDM( 5808): [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
W/ResourcesManager( 5964): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/MyFiles ( 5941): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
I/ActivityManager( 1020): Killing 5439:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
D/ActivityManager( 1020): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
I/TactileAssist( 1020): enable value -1
I/TactileAssist( 1020): internal enable value -1
I/TactileAssist( 1020): intensity value -1
I/TactileAssist( 1020): saveAppList value true
I/TactileAssist( 1020): List of disabled apps :
E/installd(  285): system dir 0 : /system/app/
E/installd(  285): system dir 1 : /system/priv-app/
E/installd(  285): system dir 2 : /vendor/app/
E/installd(  285): system dir 3 : /oem/app/
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1020): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=5981 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
E/Zygote  ( 5981): MountEmulatedStorage()
I/libpersona( 5981): KNOX_SDCARD checking this for 10053
E/Zygote  ( 5981): v2
I/libpersona( 5981): KNOX_SDCARD not a persona
I/DBG_POLICYDM( 5808): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
I/SELinux ( 5981): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5981): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5981): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/OMACP   ( 5964): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
D/Mms/Omacp( 5742): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
D/TimaKeyStoreProvider( 5981): TimaSignature is unavailable
D/ActivityThread( 5981): Added TimaKeyStore provider
D/PackageManager( 1020): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
W/libprocessgroup( 1020): failed to open /acct/uid_10104/pid_3927/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10069/pid_5439/cgroup.procs: No such file or directory
I/DBG_POLICYDM( 5808): [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
I/OMACP   ( 5964): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
W/ResourcesManager( 5981): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
I/OMACP   ( 5964): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
I/OMACP   ( 5964): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
I/OMACP   ( 5964): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
I/OMACP   ( 5964): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
E/SMD     (  289): DCD OFF
I/OMACP   ( 5964): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
I/OMACP   ( 5964): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
I/OMACP   ( 5964): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
I/OMACP   ( 5964): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
I/OMACP   ( 5964): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
I/OMACP   ( 5964): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
I/OMACP   ( 5964): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
I/OMACP   ( 5964): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
I/ServiceManager(  322): Waiting for service AtCmdFwd...
I/System.out( 1923): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1923): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1923): (HTTPLog)-Static: isShipBuild true
I/System.out( 1923): (HTTPLog)-Thread-276-279969365: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1923): (HTTPLog)-Static: isSBSettingEnabled false
W/BaseAppContext( 1923): Using Auth Proxy for data requests.
W/BaseAppContext( 1923): Using Auth Proxy for data requests.
D/EnterpriseController(  279): uids 10012
D/EnterpriseController(  279): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10012
I/GAv4    ( 5763): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5763):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5763):   adb logcat -s GAv4
D/Compatibility( 5981): onReceive() it will make start service
D/ActivityManager( 1020): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
W/ContextImpl( 5863): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/Compatibility( 5981): onHandleIntent()
D/Compatibility( 5981): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10175, android.intent.extra.user_handle=0}]
D/Compatibility( 5981): found: 2
D/Compatibility( 5981): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5981): skipping ResolveInfo{11540756 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5981): considering ResolveInfo{3d8783d7 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5981): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5981): enabling receiver ResolveInfo{c28d4c4 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
E/Zygote  ( 6006): MountEmulatedStorage()
E/Zygote  ( 6006): v2
I/libpersona( 6006): KNOX_SDCARD checking this for 1000
I/libpersona( 6006): KNOX_SDCARD not a persona
I/ActivityManager( 1020): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6006 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 6006): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6006): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6006): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Compatibility( 5981): enabling receiver ResolveInfo{31ce7fad com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
W/GAv4    ( 5763): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
D/ActivityManager( 1020): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
D/Compatibility( 5981): enabling receiver ResolveInfo{ca142e2 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
I/System.out( 1923): KnoxVpnUidStorageknoxVpnSupported API value returned is false
D/Compatibility( 5981): enabling receiver ResolveInfo{1fd68673 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
W/GAv4    ( 5763): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
D/Compatibility( 5981): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
W/BaseAppContext( 1923): Using Auth Proxy for data requests.
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
I/qtaguid ( 1923): Tagging socket 100 with tag 40b00000000{1035,0} for uid -1, pid: 1923, getuid(): 10012
W/ContextImpl( 5863): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
D/TimaKeyStoreProvider( 6006): TimaSignature is unavailable
D/ActivityThread( 6006): Added TimaKeyStore provider
W/AnalyticsTrackerProxyImpl( 5763): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
W/BaseAppContext( 1923): Using Auth Proxy for data requests.
D/ActivityManager( 1020): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
W/BaseAppContext( 1923): Using Auth Proxy for data requests.
I/qtaguid ( 1923): Tagging socket 106 with tag 40b00000000{1035,0} for uid -1, pid: 1923, getuid(): 10012
W/ContextImpl( 6006): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
D/ActivityManager( 1020): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
W/GAv4    ( 5763): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/BaseAppContext( 1923): Using Auth Proxy for data requests.
E/Zygote  ( 6026): MountEmulatedStorage()
I/libpersona( 6026): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6026): v2
I/libpersona( 6026): KNOX_SDCARD not a persona
I/ActivityManager( 1020): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=6026 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1020): Killing 5454:com.sec.knox.bridge/1000 (adj 15): empty #31
I/SELinux ( 6026): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6026): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6026): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 6026): TimaSignature is unavailable
D/ActivityThread( 6026): Added TimaKeyStore provider
E/Zygote  ( 6044): MountEmulatedStorage()
E/Zygote  ( 6044): v2
I/libpersona( 6044): KNOX_SDCARD checking this for 10041
I/libpersona( 6044): KNOX_SDCARD not a persona
I/SELinux ( 6044): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=6044 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6044): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6044): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6044): TimaSignature is unavailable
D/ActivityThread( 6044): Added TimaKeyStore provider
W/ResourcesManager( 6026): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
I/qtaguid ( 1923): Untagging socket 100
W/art     ( 5763): Suspending all threads took: 9.728ms
I/ConfigFetchService( 1923): fetch service done; releasing wakelock
I/ConfigFetchService( 1923): stopping self
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_5454/cgroup.procs: No such file or directory
I/SA      ( 6044): [SSP] onCreated
I/ActivityManager( 1020): Killing 5470:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
I/SA      ( 6044): [TPM] There is no property file
I/SA      ( 6044): [SCU] isHaveSA() - false
I/SA      ( 6044): [TPM] getModelProperty : null
I/SA      ( 6044): [TPM] getCSCProperty : null
I/SA      ( 6044): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 6044): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 6044): [DM] TFT FEATURE: false
I/SA      ( 6044): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 6044): [DM] init START
I/SA      ( 6044): [DM] This device is not a Vodafone
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
W/ResourceType( 6044): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 6044): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 6044): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 6044): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 6044): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 6044): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 6044): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
E/Zygote  ( 6064): MountEmulatedStorage()
E/Zygote  ( 6064): v2
I/libpersona( 6064): KNOX_SDCARD checking this for 1000
I/libpersona( 6064): KNOX_SDCARD not a persona
I/SELinux ( 6064): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
W/ResourceType( 6044): No package identifier when getting value for resource number 0x00000000
I/SELinux ( 6064): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1020): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6064 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 6064): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Killing 5531:com.google.android.apps.plus/u0a120 (adj 15): empty #31
W/ResourceType( 6044): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 6044): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 6044): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 6044): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
D/TimaKeyStoreProvider( 6064): TimaSignature is unavailable
W/ResourceType( 6044): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 6044): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
D/ActivityThread( 6064): Added TimaKeyStore provider
W/ResourceType( 6044): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 6044): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 6044): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
W/ResourceType( 6044): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 6044): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourcesManager( 6064): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourceType( 6044): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 6044): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 6044): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 6044): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 6044): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 6044): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
I/ActivityManager( 1020): Killing 5380:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
I/SA      ( 6044): [SCU] isHaveSA() - false
W/ContextImpl( 5763): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.docs/cache
I/SA      ( 6044): support phone number id : false
I/SA      ( 6044): [DM] Supports Ref Jpn : true
I/SA      ( 6044): [DM] init END
I/SA      ( 6044): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
I/ActivityManager( 1020): Killing 4958:com.samsung.android.app.mirrorlink/1000 (adj 15): empty #31
I/SA      ( 6044): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10175 extra.user_handle.:0 ]
E/JavaBinder( 1020): !!! FAILED BINDER TRANSACTION !!!
W/BroadcastQueue( 1020): Exception when sending broadcast to ComponentInfo{com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor}
W/BroadcastQueue( 1020): android.os.TransactionTooLargeException
W/BroadcastQueue( 1020): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue( 1020): 	at android.os.BinderProxy.transact(Binder.java:511)
W/BroadcastQueue( 1020): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
W/BroadcastQueue( 1020): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:309)
W/BroadcastQueue( 1020): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1236)
W/BroadcastQueue( 1020): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20387)
W/BroadcastQueue( 1020): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
W/BroadcastQueue( 1020): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3368)
W/BroadcastQueue( 1020): 	at android.os.Binder.execTransact(Binder.java:461)
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6085): MountEmulatedStorage()
E/Zygote  ( 6085): v2
I/libpersona( 6085): KNOX_SDCARD checking this for 10120
I/libpersona( 6085): KNOX_SDCARD not a persona
I/SELinux ( 6085): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6085): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6085): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6085 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
W/ResourcesManager( 5763): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5763): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager( 1020): Killing 5588:com.sec.android.diagmonagent/1000 (adj 15): empty #31
I/art     (  308): Explicit concurrent mark sweep GC freed 8734(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 883us total 26.217ms
D/TimaKeyStoreProvider( 6085): TimaSignature is unavailable
D/ActivityThread( 6085): Added TimaKeyStore provider
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_5470/cgroup.procs: No such file or directory
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 628us total 20.433ms
W/ResourcesManager( 6085): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 620us total 17.588ms
,V/JNIHelp ( 5763): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/art     ( 1020): Explicit concurrent mark sweep GC freed 219403(14MB) AllocSpace objects, 4(4MB) LOS objects, 33% free, 26MB/40MB, paused 3.061ms total 188.097ms
W/libprocessgroup( 1020): failed to open /acct/uid_10120/pid_5531/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10057/pid_5380/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_4958/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_5588/cgroup.procs: No such file or directory
W/ActivityThread( 5763): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5763): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1f2f2980: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5763): Installed default security provider GmsCore_OpenSSL
D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/AlarmManager( 1020): waitForAlarm result :4
D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
D/AndroidRuntime( 6103): 
D/AndroidRuntime( 6103): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6103): CheckJNI is OFF
D/AndroidRuntime( 6103): readGMSProperty: start
D/AndroidRuntime( 6103): readGMSProperty: already setted!!
D/AndroidRuntime( 6103): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6103): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6103): readGMSProperty: end
D/AndroidRuntime( 6103): addProductProperty: start
D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6121): MountEmulatedStorage()
I/libpersona( 6121): KNOX_SDCARD checking this for 10057
E/Zygote  ( 6121): v2
I/libpersona( 6121): KNOX_SDCARD not a persona
I/SELinux ( 6121): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6121): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6121): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6121 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
D/TimaKeyStoreProvider( 6121): TimaSignature is unavailable
D/ActivityThread( 6121): Added TimaKeyStore provider
I/ActivityManager( 1020): Killing 5017:com.google.android.gms:car/u0a12 (adj 15): empty #31
I/art     ( 1923): Background sticky concurrent mark sweep GC freed 13657(1031KB) AllocSpace objects, 14(800KB) LOS objects, 13% free, 13MB/15MB, paused 12.087ms total 68.771ms
E/AffinityControl( 6103): AffinityControl: registerfunction enter
D/ChimeraCfgMgr( 1923): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1923): Module APK com.google.android.play.games already loaded
W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 5
D/AndroidRuntime( 6103): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1020): inState():  stateMachine is null !!
I/PersonaManagerService( 1020): PersonaId don't exist
I/ActivityManager( 1020): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/ActivityManager( 1020): mDVFSHelper.acquire()
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1020): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1020): *FMB* installDecor flags : 25362712
E/Zygote  ( 6142): MountEmulatedStorage()
I/ActivityManager( 1020): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6142 uid=10175 gids={50175, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1020): Focused application set to: xxxx
D/InputDispatcher( 1020): Focus left window: 2990
E/Zygote  ( 6142): v2
I/libpersona( 6142): KNOX_SDCARD checking this for 10175
D/AndroidRuntime( 6103): Shutting down VM
I/libpersona( 6142): KNOX_SDCARD not a persona
D/PhoneWindow( 1020): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1020): *FMB* isFloatingMenuEnabled return false
I/SELinux ( 6142): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SurfaceFlinger(  258): id=13 createSurf (1x1),1 flag=404, uhalitest
W/ActivityManager( 1020): Scheduling restart of crashed service com.google.android.gms/.car.InCallServiceImpl in 1000ms
W/libprocessgroup( 1020): failed to open /acct/uid_10012/pid_5017/cgroup.procs: No such file or directory
I/SELinux ( 6142): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6142): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 6142): TimaSignature is unavailable
D/ActivityThread( 6142): Added TimaKeyStore provider
E/Zygote  ( 6158): MountEmulatedStorage()
E/Zygote  ( 6158): v2
I/libpersona( 6158): KNOX_SDCARD checking this for 10010
I/libpersona( 6158): KNOX_SDCARD not a persona
I/SELinux ( 6158): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6158): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6158): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=6158 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
V/ActivityManager( 1020): Display changed displayId=0
D/StatusBarManagerService( 1020): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1020): isKioskContainerExistOnDevice
I/SurfaceFlinger(  258): id=11 Removed YUIInstallC (5/9)
I/SurfaceFlinger(  258): id=11 Removed YUIInstallC (-2/9)
D/TimaKeyStoreProvider( 6158): TimaSignature is unavailable
D/ActivityThread( 6158): Added TimaKeyStore provider
V/ActivityThread( 2990): updateVisibility : ActivityRecord{fb1a35d token=android.os.BinderProxy@384eca9b {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
I/splitIntent( 1020): Queue : backgroundsplit_2 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
I/ActivityManager( 1020): Killing 5192:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
D/KeyguardViewMediator( 1182): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
D/KeyguardViewMediator( 1182): doKeyguard: not showing because lockscreen is off
V/KeyguardEffectViewController( 1182): *** Keyguard wallpaper service already unbounded
W/art     ( 6103): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,I/WebViewFactory( 6142): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,I/LibraryLoader( 6142): Time to load native libraries: 2 ms (timestamps 3389-3391)
I/LibraryLoader( 6142): Expected native library version number "",actual native library version number ""
,W/libprocessgroup( 1020): failed to open /acct/uid_10150/pid_5192/cgroup.procs: No such file or directory
,D/LocationManagerService( 1020): getProviders()=[passive]
,V/WebViewChromiumFactoryProvider( 6142): Binding Chromium to main looper Looper (main, tid 1) {ca142e2}
,I/LibraryLoader( 6142): Expected native library version number "",actual native library version number ""
,I/chromium( 6142): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6142): Initializing chromium process, singleProcess=true
,W/art     ( 6142): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6142): ApplicationContext is null in ApplicationStatus
,W/chromium( 6142): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6142): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6142): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6142): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6142): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6142): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6142): Local Branch: 
I/Adreno-EGL( 6142): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6142): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6142):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/UpdateIcingCorporaServi( 6121): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/PowerManagerService( 1020): [PWL] Off : 5s ago
,I/PowerManagerService( 1020): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1020): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 1020): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=1923, ws=null) (elapsedTime=47749)
,I/Mms/MmsApp( 5742):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 5742): [start]    fillCache consume time = 1924.046926
,D/Mms/ComposeMessageFragment( 5742): fillCache, easy = false
,I/UpdateIcingCorporaServi( 6121): UpdateCorporaTask done [took 117 ms] updated apps [took 116 ms] 
,I/ActivityManager( 1020): Killing 5607:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
,D/AbsListView( 5742): Get MotionRecognitionManager
,D/MotionRecognitionService( 1020):  ssp status : false
,D/Mms/ComposeMessageFragment( 5742): [end]    fillCache consume time = 68.613125
,D/Mms/BubbleViewCache( 5742): fillCache bubble = 1
,W/art     ( 6142): Attempt to remove local handle scope entry from IRT, ignoring,
,W/AwContents( 6142): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 6142): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 6142): *FMB* installDecor flags : 8456448
W/libprocessgroup( 1020): failed to open /acct/uid_10142/pid_5607/cgroup.procs: No such file or directory
,D/SystemWebViewEngine( 6142): CordovaWebView is running on device made by: samsung
,W/ActivityManager( 1020): Activity pause timeout for ActivityRecord{2a4c6b08 u0 com.test.thalitest/.MainActivity t229}
,W/art     ( 6142): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6142): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6142): Render dirty regions requested: true
,D/ActivityManager( 1020): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1020): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1020): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1020): handleActiveUserChange for user 0
,D/PersonaManagerService( 1020): getPersonasForUser(): returning null!
,W/chromium( 6142): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,V/ActivityThread( 6142): updateVisibility : ActivityRecord{1cc351bf token=android.os.BinderProxy@3cea0f19 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PhoneWindow( 6142): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 6142): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  258): id=14 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1020): Focus entered window: 6142
,D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 6142): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 6142): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6142): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 6142): Enabling debug mode 0
,D/InputMethodManagerService( 1020): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/PanelView( 1182): There is/are notification(s) 
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/SamsungIME( 1764): getCurrentCandidateView
,I/ActivityManager( 1020): Displayed Component not be shown by security: +659ms (total +765ms)
,W/ActivityManager( 1020): mDVFSHelper.release()
I/Timeline( 1020): Timeline: Activity_windows_visible id: ActivityRecord{2a4c6b08 u0 com.test.thalitest/.MainActivity t229} time:83882
,W/IInputConnectionWrapper( 6142): showStatusIcon on inactive InputConnection
,I/Timeline( 6142): Timeline: Activity_idle id: android.os.BinderProxy@3cea0f19 time:83887
,I/SurfaceFlinger(  258): id=13 Removed uhalitest (7/9)
,I/SurfaceFlinger(  258): id=13 Removed uhalitest (-2/9)
,D/SamsungIME( 1764): Dismiss ExpandCandiate
,I/SamsungIME( 1764): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1764): getDebugLevel  : 0x4f4c
,W/BindingManager( 6142): Cannot call determinedVisibility() - never saw a connection for the pid: 6142
,I/SamsungIME( 1764): KeybaordView init() : load resources
,I/SamsungIME( 1764): getCurrentKeyboard
I/SamsungIME( 1764): getTextKeyboard
,D/SamsungIME( 1764): [SwiftkeyWrapper] currentLangauge : 1701729619
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6212): MountEmulatedStorage(),
E/Zygote  ( 6212): v2
I/libpersona( 6212): KNOX_SDCARD checking this for 10012
I/libpersona( 6212): KNOX_SDCARD not a persona,
I/SELinux ( 6212): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.google.android.gms:car for service com.google.android.gms/.car.InCallServiceImpl: pid=6212 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,I/SELinux ( 6212): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
E/SELinux ( 6212): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6212): TimaSignature is unavailable
,D/ActivityThread( 6212): Added TimaKeyStore provider
,D/JsMessageQueue( 6142): Set native->JS mode to OnlineEventsBridgeMode
,W/ResourcesManager( 6212): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6212): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6212): VM with version 2.1.0 has multidex support
I/MultiDex( 6212): install
I/MultiDex( 6212): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6212): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 6212): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6212): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3b62216d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6212): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1020): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1020): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
,I/splitIntent( 1020): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
,I/splitIntent( 1020): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,D/GCM     ( 1670): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1670): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/jxcore_app_log( 6142): JniHelper::setJavaVM(0xb88a8450), pthread_self() = -1193270152
,D/JX-Cordova( 6142): jxcore cordova android initializing
W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 1923): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1020): Killing 5102:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1020): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 4475): callingUid 10012, callindPid: 4475
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1020): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
E/MDM     ( 1725): [186] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1020): failed to open /acct/uid_10040/pid_5102/cgroup.procs: No such file or directory
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/AcmsKeyStoreHelper( 5824):  getKeyStoreForApplication Enter
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1923): Restart initialization of location
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AcmsKeyStoreHelper( 5824): Key Store exist
I/AcmsKeyStoreHelper( 5824): Hence loading the keystore file
,D/ActivityManager( 1020): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/AcmsKeyStoreHelper( 5824):  getKeyStoreForApplication Exit
,I/AcmsCertificateMngr( 5824): getKeyStoreForApplication success 
D/AcmsCore( 5824): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 5824): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5824): Decrementing - Counter value: 1
D/AcmsCore( 5824): AcmsCore: ACMS_APP_INSTALLED
D/AcmsCore( 5824): This is NOT a valid MirrorLink app
D/AcmsCore( 5824): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 5824): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5824): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 5824): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 5824): getSvcCounter - Counter value: 0
,D/AcmsService( 5824): Enter onDestroy
I/AcmsService( 5824): cleanUp(): inside service clean up
D/AcmsCore( 5824): AcmsCore: inside DeInit
D/AcmsCore( 5824): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 5824): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 5824): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 5824): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 5824): AppEntryInterface: Inside CleanUp
D/AcmsServiceMonitor( 5824): getSvcCounter - Counter value: 0
D/AcmsService( 5824): killing acms process
I/Process ( 5824): Sending signal. PID: 5824 SIG: 9
,I/DBG_POLICYDM( 5808): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5808): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5808): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5808): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5808): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5808): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5808): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5808): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/ActivityManager( 1020): Process ACMS.Process (pid 5824)(adj 0) has died(32,1102)
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/jxcore-log( 6142): Initializing JXcore engine
,W/jxcore-log( 6142): JXcore engine is ready
,W/jxcore-log( 6142): Starting JXcore engine
,E/audit   ( 1855): type=1400 msg=audit(1449598341.443:205): avc:  denied  { ioctl } for  pid=6142 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1855):  SEPF_SM-A500FU_5.0.2_0027
E/audit   ( 1855): type=1300 msg=audit(1449598341.443:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=be8f9d58 items=0 ppid=308 ppcomm=main pid=6142 auid=4294967295 uid=10175 gid=10175 euid=10175 suid=10175 fsuid=10175 egid=10175 sgid=10175 fsgid=10175 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1855): type=1320 msg=audit(1449598341.443:205): 
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4132, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,W/jxcore-log( 6142): Platform android,
W/jxcore-log( 6142): 
W/jxcore-log( 6142): Process ARCH arm
W/jxcore-log( 6142): 
,I/jxcore-log( 6142): JXcore Cordova bridge is ready!
I/jxcore-log( 6142): 
,W/jxcore-log( 6142): JXcore engine is started
,I/Choreographer( 6142): Skipped 137 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6142): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 6142): Error!: missing ) after argument list
E/jxcore  ( 6142): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 6142): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/InputDispatcher( 1020): Focused application set to: xxxx
,I/ActivityManager( 1020): Killing 4992:com.google.android.music:main/u0a111 (adj 15): empty #31
,I/SurfaceFlinger(  258): id=14 Removed NainActivit (6/8)
,I/SurfaceFlinger(  258): id=14 Removed NainActivit (-2/8)
,D/InputDispatcher( 1020): Focus left window: 6142
,D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
,E/ViewRootImpl( 6142): sendUserActionEvent() mView == null
,W/ActivityManager( 1020): mDVFSHelper.acquire()
,I/DBG_DM  ( 2990): [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,I/DBG_DM  ( 2990): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 5
,I/DBG_DM  ( 2990): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,I/DBG_DM  ( 2990): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 2990): [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 5
,I/DBG_DM  ( 2990): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,I/DBG_DM  ( 2990): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,I/DBG_DM  ( 2990): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 2990): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,W/libprocessgroup( 1020): failed to open /acct/uid_10111/pid_4992/cgroup.procs: No such file or directory
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1182): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/DBG_DM  ( 2990): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 5
,D/PersonaManager( 1182): isKioskContainerExistOnDevice
,D/PersonaManager( 1182): isKioskContainerExistOnDevice
,D/PanelView( 1182): There is/are notification(s) 
,D/PanelView( 1182): kidsfalse mQsExpansionEnabled:true
,I/DBG_DM  ( 2990): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,D/PersonaManager( 1182): isKioskContainerExistOnDevice
,D/PanelView( 1182): There is/are notification(s) 
,D/PanelView( 1182): kidsfalse mQsExpansionEnabled:true
,I/DBG_DM  ( 2990): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 2990): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 2990): [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,I/DBG_DM  ( 2990): [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,D/ActivityManager( 1020): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1020): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1020): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1020): handleActiveUserChange for user 0
,I/DBG_DM  ( 2990): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
D/PersonaManagerService( 1020): getPersonasForUser(): returning null!
,I/SurfaceFlinger(  258): id=15 createSurf (720x1280),1 flag=404, YUIInstallC
,D/StatusBarManagerService( 1020): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 1020): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/InputDispatcher( 1020): Focus entered window: 2990
,D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 2990): log_dcs ThreadedRenderer::initialize entered! 
,V/ActivityThread( 2990): updateVisibility : ActivityRecord{fb1a35d token=android.os.BinderProxy@384eca9b {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/InputMethodManagerService( 1020): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/IInputConnectionWrapper( 6142): showStatusIcon on inactive InputConnection
,D/SamsungIME( 1764): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PanelView( 1182): There is/are notification(s) 
,I/Timeline( 2990): Timeline: Activity_idle id: android.os.BinderProxy@384eca9b time:86883
,D/PanelView( 1182): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,W/ActivityManager( 1020): mDVFSHelper.release()
,I/Timeline( 1020): Timeline: Activity_windows_visible id: ActivityRecord{1d48d2d u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t228} time:86907
,I/ConfigService( 1670): onDestroy
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 380
,I/ActivityManager( 1020): Killing 5332:com.google.android.gm/u0a101 (adj 15): empty #31
,D/PersonaManager( 1020): isKioskContainerExistOnDevice
,W/libprocessgroup( 1020): failed to open /acct/uid_10101/pid_5332/cgroup.procs: No such file or directory
,V/AlarmManager( 1020): waitForAlarm result :4
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1020): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6238 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
E/Zygote  ( 6238): MountEmulatedStorage()
I/libpersona( 6238): KNOX_SDCARD checking this for 10075
E/Zygote  ( 6238): v2
I/libpersona( 6238): KNOX_SDCARD not a persona
,I/SELinux ( 6238): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6238): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6238): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6238): TimaSignature is unavailable
,D/ActivityThread( 6238): Added TimaKeyStore provider
,D/TaskPersister( 1020): removeObsoleteFile: deleting file=228_task.xml
,D/ActivityManager( 1020): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/GAV2    ( 6238): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 6238): Created application version: 3.6.9 (30609)
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1020): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1020): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/BooksSync( 6238): Starting books sync for 61035162, extras: ade
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SQLiteLog( 6238): (284) automatic index on view_volumes(volume_id)
,I/BooksConfig( 6238): GmsCore Version = 7.8.99 (2134222-436)
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1020): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found,
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
D/StatusBar( 1182): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/PersonaManager( 1182): isKioskContainerExistOnDevice
,D/PersonaManager( 1182): isKioskContainerExistOnDevice
D/PanelView( 1182): There is/are notification(s) 
D/PanelView( 1182): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1182): isKioskContainerExistOnDevice
,D/PanelView( 1182): There is/are notification(s) 
D/PanelView( 1182): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1020): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6238): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6238): Soft error
E/BooksSync( 6238): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6238): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6238): Sync error
E/BooksSync( 6238): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6238): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 6238): Finished books sync
,D/SyncManager( 1020): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 63780, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager( 1020): Killing 5122:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,D/PanelView( 1182): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1020): mCursor = null
,W/libprocessgroup( 1020): failed to open /acct/uid_10044/pid_5122/cgroup.procs: No such file or directory
,E/SMD     (  289): DCD OFF
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 30703(1619KB) AllocSpace objects, 9(164KB) LOS objects, 33% free, 26MB/40MB, paused 2.516ms total 175.701ms
,D/PackageManager( 1020): [MSG] MCS_UNBIND
,I/ActivityManager( 1020): Killing 4201:com.sec.spp.push/u0a35 (adj 15): empty #31
,W/libprocessgroup( 1020): failed to open /acct/uid_10035/pid_4201/cgroup.procs: No such file or directory
,I/PowerManagerService( 1020): [PWL] Off : 15s ago
,I/PowerManagerService( 1020): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1020): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1020): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=1923, ws=null) (elapsedTime=57752)
,E/SMD     (  289): DCD OFF
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,I/GAV2    ( 6238): Thread[GAThread,5,main]: No campaign data found.
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4181, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,I/ActivityManager( 1020): Waited long enough for: ServiceRecord{245e68c7 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 340
,E/SMD     (  289): DCD OFF
,D/ActivityManager( 1020): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000,
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.android.vending
,D/Finsky  ( 5487): [919] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1020): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5487): [919] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4188, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1020): !@Sync 3
,I/Atfwd_Sendcmd(  322): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  322): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,V/AlarmManager( 1020): waitForAlarm result :4
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/SSRM:n  ( 1020): SIOP:: AP = 320
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1020): userId = 0, bbcId = -10000,
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1020): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5487): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5487): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5487): [1] 5.onFinished: Scheduling replication attempt 2.
,I/PowerManagerService( 1020): [PWL] Off : 30s ago
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF,
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4191, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/FactoryTest( 5559): Not factory mode
,D/FactoryTest( 5559): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 5559): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 5559): still no open session command from host, so toast
,W/ContextImpl( 5559): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 5559): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
I/Timeline( 5559): Timeline: Activity_launch_request id:com.android.settings time:116458
,E/PersonaManagerService( 1020): inState():  stateMachine is null !!
I/PersonaManagerService( 1020): PersonaId don't exist
,I/ActivityManager( 1020): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.android.settings,
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1020): mDVFSHelper.acquire()
,D/PersonaManager( 1020): isKioskContainerExistOnDevice
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/InputDispatcher( 1020): Focused application set to: xxxx
,D/InputDispatcher( 1020): Focus left window: 2990
,E/MTPRx   ( 5559): started activity for popup,
D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
,W/ResourcesManager( 5559): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 5559): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5559): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5559): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5559): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5559): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 5559): PREF_DONT_ASK_AGAIN : true
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.android.settings
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/InputDispatcher( 1020): Focused application set to: xxxx
,D/InputDispatcher( 1020): Focus entered window: 2990
,D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
,D/InputMethodManagerService( 1020): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService( 1020): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@cc3982b attribute=null, token = android.os.BinderProxy@30a7f9e0
,D/SettingsReceiverActivity( 5559): dev.kiessupport is : TRUE
,D/PhoneWindow( 5559): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 5559): *FMB* installDecor flags : 8388610
,I/DBG_DM  ( 2990): [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,I/DBG_DM  ( 2990): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 5
,I/DBG_DM  ( 2990): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,I/DBG_DM  ( 2990): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 2990): [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 5
,I/DBG_DM  ( 2990): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,I/DBG_DM  ( 2990): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,I/DBG_DM  ( 2990): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 2990): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1182): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/DBG_DM  ( 2990): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 5
,D/PersonaManager( 1182): isKioskContainerExistOnDevice
,D/PersonaManager( 1182): isKioskContainerExistOnDevice
,D/PanelView( 1182): There is/are notification(s) 
,D/PanelView( 1182): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1182): isKioskContainerExistOnDevice
,D/PanelView( 1182): There is/are notification(s) 
,D/PanelView( 1182): kidsfalse mQsExpansionEnabled:true
I/DBG_DM  ( 2990): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,I/DBG_DM  ( 2990): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 2990): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 2990): [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,I/DBG_DM  ( 2990): [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,D/ActivityManager( 1020): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1020): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1020): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1020): handleActiveUserChange for user 0
D/PersonaManagerService( 1020): getPersonasForUser(): returning null!
,I/DBG_DM  ( 2990): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] ,
,V/ActivityThread( 2990): updateVisibility : ActivityRecord{fb1a35d token=android.os.BinderProxy@384eca9b {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,I/Timeline( 2990): Timeline: Activity_idle id: android.os.BinderProxy@384eca9b time:116713
,D/PersonaManager( 1020): isKioskContainerExistOnDevice
,D/PanelView( 1182): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 310
,W/ActivityManager( 1020): mDVFSHelper.release()
,V/AlarmManager( 1020): waitForAlarm result :4
,D/TaskPersister( 1020): removeObsoleteFile: deleting file=228_task.xml
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :8
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4193, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:n  ( 1020): SIOP:: AP = 300
,V/AlarmManager( 1020): waitForAlarm result :4
D/ActivityManager( 1020): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,I/PowerManagerService( 1020): [PWL] Off : 50s ago
,I/PowerManagerService( 1020): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1020): [PWL]     mWakeLockSummary : 0x1
,V/AlarmManager( 1020): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManagerEXT( 1020): <AppSync3 Whitelist>
V/AlarmManagerEXT( 1020): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1182): handleTimeUpdate
,D/SecKeyguardClockView( 1182): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1182): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1182): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1182): *** don't update sliding image ***
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1020): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1670): Explicit concurrent mark sweep GC freed 17644(1006KB) AllocSpace objects, 3(108KB) LOS objects, 40% free, 10MB/17MB, paused 1.222ms total 52.711ms
,D/Finsky  ( 5487): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5487): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5487): [1] 5.onFinished: Scheduling replication attempt 3.
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4191, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,E/Watchdog( 1020): !@Sync 4
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1020): SIOP:: AP = 300
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF,
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4196, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED,
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 290
,V/AlarmManager( 1020): waitForAlarm result :4
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1020): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure,
I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5487): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5487): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5487): [1] 5.onFinished: Scheduling replication attempt 4.
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1020): [PWL] Off : 75s ago
,V/AlarmManager( 1020): waitForAlarm result :4
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0
,I/BooksSync( 6238): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6238): GmsCore Version = 7.8.99 (2134222-436)
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1020): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,E/SMD     (  289): DCD OFF
,D/StatusBar( 1182): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,D/PersonaManager( 1182): isKioskContainerExistOnDevice
D/PersonaManager( 1182): isKioskContainerExistOnDevice
W/ActivityManager( 1020): userId = 0, bbcId = -10000
D/PanelView( 1182): There is/are notification(s) 
D/PanelView( 1182): kidsfalse mQsExpansionEnabled:true
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
D/PersonaManager( 1182): isKioskContainerExistOnDevice
D/PanelView( 1182): There is/are notification(s) 
D/PanelView( 1182): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1020): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6238): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6238): Soft error
E/BooksSync( 6238): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6238): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6238): Sync error
E/BooksSync( 6238): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6238): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6238): Finished books sync
,D/PanelView( 1182): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SyncManager( 1020): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 153912, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1020): mCursor = null
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4193, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2,
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1020): SIOP:: AP = 290
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4196, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,E/Watchdog( 1020): !@Sync 5
,D/SSRM:n  ( 1020): SIOP:: AP = 290
,E/SMD     (  289): DCD OFF,
,V/AlarmManager( 1020): waitForAlarm result :4
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1020): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5487): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5487): [1] 5.onFinished: Installation state replication failed.,
D/Finsky  ( 5487): [1] 5.onFinished: Scheduling replication attempt 5.
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4198, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2,
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 290
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1020): [PWL] Off : 105s ago
,V/AlarmManager( 1020): waitForAlarm result :4
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :8
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF,
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:n  ( 1020): SIOP:: AP = 290
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1020): !@Sync 6
,D/SSRM:n  ( 1020): SIOP:: AP = 290
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :4
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1182): handleTimeUpdate
,D/SecKeyguardClockView( 1182): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1182): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1182): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1182): *** don't update sliding image ***
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.uploader.UploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/VacuumService( 1670): Vacuum at: now=1449598458959 tag=VacuumService
,I/GoogleURLConnFactory( 1670): Using platform SSLCertificateSocketFactory
,W/Uploader( 1670): No account for auth token provided
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1670): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1670): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 1670): (HTTPLog)-Static: isShipBuild true
I/System.out( 1670): (HTTPLog)-Thread-186-712975040: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1670): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): uids 10012
D/EnterpriseController(  279): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10012
,I/System.out( 1670): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1670): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1670, getuid(): 10012
,I/qtaguid ( 1670): Tagging socket 62 with tag 120100000000{4609,0} for uid -1, pid: 1670, getuid(): 10012
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1020): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1020): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5487): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5487): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5487): [1] 5.onFinished: Giving up after 6 failures.
,D/ActivityManager( 1020): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Uploader( 1670): No account for auth token provided
,I/System.out( 1670): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1670): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1670, getuid(): 10012
,W/Uploader( 1670): No account for auth token provided
,I/System.out( 1670): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1670): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1670, getuid(): 10012
,W/Uploader( 1670):  no longer exists, so no auth token.
,I/System.out( 1670): (HTTPLog)-Static: isSBSettingEnabled false,
I/qtaguid ( 1670): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1670, getuid(): 10012
,W/Uploader( 1670): No account for auth token provided,
,I/System.out( 1670): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1670): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1670, getuid(): 10012
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 44288(2MB) AllocSpace objects, 49(804KB) LOS objects, 33% free, 27MB/40MB, paused 2.497ms total 159.872ms
D/ActivityManager( 1020): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1182): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1182): isKioskContainerExistOnDevice
,D/PersonaManager( 1182): isKioskContainerExistOnDevice
,D/PanelView( 1182): There is/are notification(s) 
,D/PanelView( 1182): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1182): isKioskContainerExistOnDevice
,D/PanelView( 1182): There is/are notification(s) 
,D/PanelView( 1182): kidsfalse mQsExpansionEnabled:true
,E/Uploader( 1670): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1670): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1670): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1670): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1670): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1670): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1670): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1670): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1670): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1670): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1670): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1670): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1670): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/System.out( 1670): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1670): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1670, getuid(): 10012
,D/PanelView( 1182): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true,
,E/SQLiteLog( 1670): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4196, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1020): Plugged,
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate,
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 290
,E/SMD     (  289): DCD OFF
,I/Atfwd_Sendcmd(  322): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  322): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4198, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 290
,I/PowerManagerService( 1020): [PWL] Off : 140s ago
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/Watchdog( 1020): !@Sync 7,
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 1
,D/SSRM:n  ( 1020): SIOP:: AP = 290
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4200, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 290
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :8,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1020): SIOP:: AP = 290
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4201, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,E/Watchdog( 1020): !@Sync 8
,I/PowerManagerService( 1020): [PWL] Off : 180s ago
,D/SSRM:n  ( 1020): SIOP:: AP = 290,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 290
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 290
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1182): handleTimeUpdate
,D/SecKeyguardClockView( 1182): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
,D/SecKeyguardClockView( 1182): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1182): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1182): *** don't update sliding image ***
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0
,I/BooksSync( 6238): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6238): GmsCore Version = 7.8.99 (2134222-436)
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1020): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1182): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1182): isKioskContainerExistOnDevice
D/PersonaManager( 1182): isKioskContainerExistOnDevice
,D/PanelView( 1182): There is/are notification(s) 
D/PanelView( 1182): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1182): isKioskContainerExistOnDevice
D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
D/PanelView( 1182): There is/are notification(s) 
D/PanelView( 1182): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1020): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000,
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6238): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6238): Soft error
E/BooksSync( 6238): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6238): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6238): Sync error
E/BooksSync( 6238): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6238): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6238): Finished books sync
,D/SyncManager( 1020): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 280326, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1182): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1020): mCursor = null
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4197, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,E/Watchdog( 1020): !@Sync 9
,D/SSRM:n  ( 1020): SIOP:: AP = 290
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4201, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 290
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1020): [PWL] Off : 225s ago
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :8
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1020): SIOP:: AP = 290
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1182): handleTimeUpdate
,D/SecKeyguardClockView( 1182): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
D/SecKeyguardClockView( 1182): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1182): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1182): *** don't update sliding image ***
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  289): DCD OFF
,D/TimaService( 1020): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1020): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1020): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1020): initializing...
,I/TLC_TIMA_PKM_initialize( 1020): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1020): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1020): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1020): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1020): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1020): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1020): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1020): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: ( 1020): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1020): Loaded image: APP id = 12
,I/TZ: qc_tlc_communication( 1020): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1020): Trustlet response is completed
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1020): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1020): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1020): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1020): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4197, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1020): Plugged
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,E/Watchdog( 1020): !@Sync 10
,D/SSRM:n  ( 1020): SIOP:: AP = 290
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/Atfwd_Sendcmd(  322): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  322): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4201, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 290
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1020): SIOP:: AP = 280
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4201, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,E/Watchdog( 1020): !@Sync 11
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1020): SIOP:: AP = 270
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 2
,I/PowerManagerService( 1020): [PWL] Off : 275s ago,
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1020): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms,
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1182): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/GLSActivity( 1670): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1670): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1670): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1670): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1670): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1670): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1670): 	at android.os.Binder.execTransact(Binder.java:461)
,D/PersonaManager( 1182): isKioskContainerExistOnDevice
D/PersonaManager( 1182): isKioskContainerExistOnDevice
E/PlayEventLogger( 5487): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5487): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5487): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 5487): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5487): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 5487): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5487): 	at android.os.Binder.execTransact(Binder.java:461)
D/PanelView( 1182): There is/are notification(s) 
D/PanelView( 1182): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1182): isKioskContainerExistOnDevice
,D/PanelView( 1182): There is/are notification(s) 
D/PanelView( 1182): kidsfalse mQsExpansionEnabled:true
,W/System  ( 5487): Ignoring header User-Agent because its value was null.
,I/System.out( 5487): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 5487): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 5487): (HTTPLog)-Static: isShipBuild true
I/System.out( 5487): (HTTPLog)-Thread-943-643514333: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 5487): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): uids 10028
D/EnterpriseController(  279): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10028
,I/System.out( 5487): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/PanelView( 1182): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4198, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 290
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :8
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4202, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate,
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2,
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2,
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/SSRM:n  ( 1020): SIOP:: AP = 290,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1020): !@Sync 12,
,D/SSRM:n  ( 1020): SIOP:: AP = 270
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 270
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1020): SIOP:: AP = 270
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4201, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,E/Watchdog( 1020): !@Sync 13
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1020): [PWL] Off : 330s ago
,D/SSRM:n  ( 1020): SIOP:: AP = 270
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4203, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 270
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4201, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/SSRM:n  ( 1020): SIOP:: AP = 270
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1020): !@Sync 14,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4203, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/Atfwd_Sendcmd(  322): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  322): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate,
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94,
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/SSRM:n  ( 1020): SIOP:: AP = 270
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4202, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2628): Disconnected process message: 10,
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2,
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 270
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1020): SIOP:: AP = 270
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1020): !@Sync 15
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4202, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,I/PowerManagerService( 1020): [PWL] Off : 390s ago
,D/SSRM:n  ( 1020): SIOP:: AP = 270
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF,
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  289): DCD OFF,
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4203, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/SSRM:n  ( 1020): SIOP:: AP = 270
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/bootchecker(  319): bootchecker wake up!!
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 3
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1020): SIOP:: AP = 270
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1020): !@Sync 16,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1020): SIOP:: AP = 270
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1020): SIOP:: AP = 270
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1020): SIOP:: AP = 270
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1020): !@Sync 17
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4203, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,D/PowerManagerService( 1020): [PSM] lowPowerModeEnabled: false (mLowPowerModeSetting: false, mAutoLowPowerModeConfigured: false, mBatteryLevel: 93, mLowBatteryTriggerLevel: 0)
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/SecKeyguardStatusUtils( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2628): Disconnected process message: 10
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1020): SIOP:: AP = 270
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF,
,V/AlarmManager( 1020): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1182): handleTimeUpdate
,D/SecKeyguardClockView( 1182): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1182): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1182): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1182): *** don't update sliding image ***
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6238): Starting books sync for 61035162, extras: ade,
,D/SecKeyguardStatusUtils( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksConfig( 6238): GmsCore Version = 7.8.99 (2134222-436)
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1020): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 5
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1182): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1182): isKioskContainerExistOnDevice
D/PersonaManager( 1182): isKioskContainerExistOnDevice
,D/PanelView( 1182): There is/are notification(s) 
D/PanelView( 1182): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1182): isKioskContainerExistOnDevice
D/PanelView( 1182): There is/are notification(s) 
,D/PanelView( 1182): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1020): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6238): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6238): Soft error
E/BooksSync( 6238): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6238): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6238): Sync error
E/BooksSync( 6238): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6238): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6238): Finished books sync
,D/PanelView( 1182): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SyncManager( 1020): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 532959, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1020): mCursor = null
,I/PowerManagerService( 1020): [PWL] Off : 455s ago
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4196, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1020): stay LED for charging
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/SSRM:n  ( 1020): SIOP:: AP = 270
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :8,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4203, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2,
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/SSRM:n  ( 1020): SIOP:: AP = 270
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1020): !@Sync 18,
,I/Atfwd_Sendcmd(  322): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  322): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1020): SIOP:: AP = 270
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1182): handleTimeUpdate
,D/SecKeyguardClockView( 1182): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1182): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1182): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1182): *** don't update sliding image ***
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4202, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/SSRM:n  ( 1020): SIOP:: AP = 270
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4203, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/SSRM:n  ( 1020): SIOP:: AP = 270
,E/SMD     (  289): DCD OFF
,I/Atfwd_Daemon(  322): Stop the daemon....,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1020): !@Sync 19,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 270
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4203, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/SSRM:n  ( 1020): SIOP:: AP = 270
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1020): [PWL] Off : 525s ago
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :8
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1020): SIOP:: AP = 270,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/TimaService( 1020): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1020): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1020): TimaServiceHandler.handleMessage what =1
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/TLC_TIMA_PKM_measure_kernel( 1020): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1020): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1020): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1020): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1020): !@Sync 20
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 270,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1020): SIOP:: AP = 270,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1020): SIOP:: AP = 270
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1020): !@Sync 21
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4201, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/SSRM:n  ( 1020): SIOP:: AP = 270
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4203, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
D/SSRM:n  ( 1020): SIOP:: AP = 270
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 270
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1020): !@Sync 22
,I/PowerManagerService( 1020): [PWL] Off : 600s ago
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 270
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4202, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/BatteryService( 1020): stay LED for charging
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4203, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4211, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1020): !@Sync 23
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4203, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1020): Plugged,
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2,
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4211, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4206, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1020): !@Sync 24
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4205, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged,
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2,
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4212, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate,
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93,
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,I/PowerManagerService( 1020): [PWL] Off : 680s ago
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4208, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1020): !@Sync 25,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4212, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4213, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 1020): stay LED for charging
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1020): !@Sync 26
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4212, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1020): Plugged
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4213, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,I/MotionRecognitionService( 1020): Plugged,
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1020): !@Sync 27,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4213, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1020): [PWL] Off : 765s ago
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4203, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1020): !@Sync 28
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4213, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1020): !@Sync 29
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4215, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4203, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4215, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1020): Plugged,
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,E/SMD     (  289): DCD OFF
,D/TimaService( 1020): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1020): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1020): TimaServiceHandler.handleMessage what =1
,E/SMD     (  289): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1020): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1020): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1020): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1020): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1020): !@Sync 30
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4212, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged,
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1182): handleTimeUpdate
,D/SecKeyguardClockView( 1182): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1182): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1182): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1182): *** don't update sliding image ***
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.EventLogService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1020): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 1923): Aggregate from 1449596761363 (log), 1449596761363 (data)
,E/SMD     (  289): DCD OFF
,D/GCM     ( 1670): Message class com.google.f.a.a.i
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4215, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2,
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1020): [PWL] Off : 855s ago
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1020): !@Sync 31
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,V/AlarmManager( 1020): waitForAlarm result :8
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1020): !@Sync 32,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1020): !@Sync 33
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4215, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4216, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1020): Plugged
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate,
I/MotionRecognitionService( 1020): mGripSensorEnabled= false,
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93,
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1020): [PWL] Off : 950s ago,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4212, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1020): Plugged
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93,
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
D/HeadsetStateMachine( 2628): Disconnected process message: 10
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,V/AlarmManager( 1020): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1182): handleTimeUpdate
,D/SecKeyguardClockView( 1182): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1182): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1182): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1182): *** don't update sliding image ***
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/Watchdog( 1020): !@Sync 34
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0
,I/BooksSync( 6238): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6238): GmsCore Version = 7.8.99 (2134222-436)
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1020): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1182): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1182): isKioskContainerExistOnDevice
,D/PersonaManager( 1182): isKioskContainerExistOnDevice
D/PanelView( 1182): There is/are notification(s) 
D/PanelView( 1182): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1182): isKioskContainerExistOnDevice
,D/PanelView( 1182): There is/are notification(s) 
D/PanelView( 1182): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1020): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6238): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6238): Soft error
E/BooksSync( 6238): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6238): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6238): Sync error
E/BooksSync( 6238): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6238): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6238): Finished books sync
,D/PanelView( 1182): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SyncManager( 1020): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1037859, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1020): mCursor = null
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4205, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4215, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1020): !@Sync 35
,V/AlarmManager( 1020): waitForAlarm result :4
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4216, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,V/AlarmManager( 1020): waitForAlarm result :8
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1020): !@Sync 36,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4216, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED,
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2,
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1020): !@Sync 37,
,I/PowerManagerService( 1020): [PWL] Off : 1050s ago
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4210, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4216, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1020): !@Sync 38
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4215, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 1020): stay LED for charging
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93,
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4213, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED,
,I/MotionRecognitionService( 1020): Plugged
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService( 1020): mGripSensorEnabled= false,
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1020): !@Sync 39
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4216, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4206, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4216, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2,
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,E/SMD     (  289): DCD OFF
,D/TimaService( 1020): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1020): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1020): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 1020): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 1020): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 1020): Updating Usage Statistics in DB @ 1449599471418
,I/ApplicationPolicy( 1020): updateDataUsageMap
,I/TLC_TIMA_PKM_measure_kernel( 1020): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1020): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1020): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1020): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/NetworkDataUsageDb( 1020): ::getAppControlDB: DB is Created 
,I/NetworkDataUsageDb( 1020): ::isTableExists: Table exists 
,I/ApplicationUsage( 1020): Done Updating Usage Statistics in DB @ 1449599471749
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1020): !@Sync 40
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4217, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4215, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService( 1020): Plugged
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,I/PowerManagerService( 1020): [PWL] Off : 1155s ago
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4206, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1020): !@Sync 41,
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4217, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
D/BatteryService( 1020): stay LED for charging
D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.,
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1020): !@Sync 42,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1020): !@Sync 43
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4216, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1020): Plugged
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4217, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93,
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4216, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1020): !@Sync 44
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,I/PowerManagerService( 1020): [PWL] Off : 1265s ago
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:93, scale:100, status:2, health:2, present:true, voltage: 4217, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4216, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,D/PowerManagerService( 1020): [PSM] lowPowerModeEnabled: false (mLowPowerModeSetting: false, mAutoLowPowerModeConfigured: false, mBatteryLevel: 94, mLowBatteryTriggerLevel: 0)
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
D/SecKeyguardStatusUtils( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4217, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2,
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1020): !@Sync 45,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4218, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1020): Plugged
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4217, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged,
D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1020): !@Sync 46
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4218, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false,
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1020): !@Sync 47
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1020): !@Sync 48
,I/PowerManagerService( 1020): [PWL] Off : 1380s ago
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1020): !@Sync 49
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1182): handleTimeUpdate
,D/SecKeyguardClockView( 1182): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1182): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1182): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1182): *** don't update sliding image ***
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1020): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.sync.FitnessSyncAdapterService; callingUser = 0; userId(target) = 0
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4216, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,V/AlarmManager( 1020): waitForAlarm result :8
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4218, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/TimaService( 1020): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1020): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1020): TimaServiceHandler.handleMessage what =1
,E/SMD     (  289): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1020): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1020): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1020): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1020): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1020): !@Sync 50
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1182): handleTimeUpdate
,D/SecKeyguardClockView( 1182): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1182): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1182): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1182): *** don't update sliding image ***
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1020): !@Sync 51,
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,V/AlarmManager( 1020): waitForAlarm result :8
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4215, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4220, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1020): !@Sync 52
,I/PowerManagerService( 1020): [PWL] Off : 1500s ago,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4218, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged,
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4218, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4217, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1020): !@Sync 53
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4220, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4218, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4220, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging,
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1020): !@Sync 54
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4218, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1020): Plugged
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4220, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged,
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate,
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1020): !@Sync 55
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1020): !@Sync 56
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,I/PowerManagerService( 1020): [PWL] Off : 1625s ago,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4218, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1020): Plugged
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4220, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94,
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1020): !@Sync 57
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4221, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1020): !@Sync 58
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4218, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
D/BatteryService( 1020): stay LED for charging
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4221, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4220, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2,
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1020): !@Sync 59
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/NetworkStatsFactory( 1020): UpdateStatsForKnox updated
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4218, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/TimaService( 1020): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1020): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1020): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1020): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1020): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1020): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1020): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4217, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1020): !@Sync 60
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4218, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2,
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,I/PowerManagerService( 1020): [PWL] Off : 1755s ago
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4220, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4216, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2,
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,E/Watchdog( 1020): !@Sync 61,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4217, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4218, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2,
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4216, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,E/Watchdog( 1020): !@Sync 62
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4217, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,TIME-OUT KILL (timeout was 1800000ms),E/SMD     (  289): DCD OFF
D/AndroidRuntime( 7037): 
D/AndroidRuntime( 7037): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7037): CheckJNI is OFF
D/AndroidRuntime( 7037): readGMSProperty: start
D/AndroidRuntime( 7037): readGMSProperty: already setted!!
D/AndroidRuntime( 7037): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 7037): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 7037): readGMSProperty: end
D/AndroidRuntime( 7037): addProductProperty: start
E/AffinityControl( 7037): AffinityControl: registerfunction enter
D/AndroidRuntime( 7037): Calling main entry com.android.commands.pm.Pm
D/PackageManager( 1020): START PACKAGE DELETE: observer{265437500}
D/PackageManager( 1020): pkg{<packageName>}
D/PackageManager( 1020): user{0}
D/PackageManager( 1020): caller{2000}
D/PackageManager( 1020): flags{3}
D/PersonaManagerService( 1020): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 1020): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1020): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1020): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1020): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1020): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManager( 1020): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1020): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1020): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1020): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 1020): !@killApplicatoin: 10175, uninstall pkg
I/ActivityManager( 1020): Force stopping com.test.thalitest appid=10175 user=-1: uninstall pkg
I/ActivityManager( 1020): Killing 6142:com.test.thalitest/u0a175 (adj 13): stop com.test.thalitest cause uninstall pkg
I/art     ( 1020): Background sticky concurrent mark sweep GC freed 58479(7MB) AllocSpace objects, 354(5MB) LOS objects, 30% free, 28MB/40MB, paused 3.335ms total 101.948ms
W/PackageSettings( 1020): Skipping PackageSetting{ae2cb70 com.example.hello/10174} due to missing metadata
I/ActivityManager( 1020): Killing 6026:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty for 1814s
I/ActivityManager( 1020): Killing 6006:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1814s
I/ActivityManager( 1020): Killing 5863:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty for 1814s
I/ActivityManager( 1020): Killing 5981:com.sec.android.app.soundalive/u0a53 (adj 15): empty for 1815s
I/ActivityManager( 1020): Killing 5964:com.wsomacp/u0a25 (adj 15): empty for 1815s
I/ActivityManager( 1020): Killing 5941:com.sec.android.app.myfiles/u0a47 (adj 15): empty for 1815s
I/ActivityManager( 1020): Killing 5742:com.android.mms/u0a46 (adj 15): empty for 1815s
I/ActivityManager( 1020): Killing 5922:com.sec.android.provider.badge/u0a72 (adj 15): empty for 1815s
I/ActivityManager( 1020): Killing 5882:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty for 1815s
I/ActivityManager( 1020): Killing 5847:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty for 1815s
I/ActivityManager( 1020): Killing 5808:com.policydm/1000 (adj 15): empty for 1816s
I/ActivityManager( 1020): Killing 5420:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty for 1816s
I/ActivityManager( 1020): Killing 5793:com.samsung.helphub/1000 (adj 15): empty for 1816s
I/ActivityManager( 1020): Killing 5772:com.sec.pcw.device/1000 (adj 15): empty for 1816s
I/ActivityManager( 1020): Killing 5763:com.google.android.apps.docs/u0a91 (adj 15): empty for 1816s
I/ActivityManager( 1020): Killing 5405:com.google.android.partnersetup/u0a15 (adj 15): empty for 1816s
I/ActivityManager( 1020): Killing 5730:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty for 1816s
I/ActivityManager( 1020): Killing 5314:com.sec.spp.push:RemoteNotiProcess/u0a35 (adj 15): empty for 1816s
W/ActivityManager( 1020): Spurious death for ProcessRecord{3cce3ec5 6142:com.test.thalitest/u0a175}, curProc for 6142: null
I/ProcessStatsService( 1020): Prepared write state in 6ms
I/ActivityManager( 1020): Force stopping com.test.thalitest appid=10175 user=0: pkg removed
E/JavaBinder( 1020): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1020): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1020): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1020): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1020): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1020): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1020): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1020): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1020): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1020): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1020): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1020): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1020): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1020): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1020): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1020): !!! FAILED BINDER TRANSACTION !!!
W/ActivityManager( 1020): CustomStartingWindow se packge removed so remove capture also
I/art     ( 5085): Explicit concurrent mark sweep GC freed 2021(111KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 716us total 28.014ms
I/InputReader( 1020): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 1764): mOCRHelper is null
W/GeofencerStateMachine( 1725): Ignoring removeGeofence because network location is disabled.
I/art     ( 6121): Explicit concurrent mark sweep GC freed 372(26KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 8MB/11MB, paused 744us total 51.288ms
D/CountryDetector( 1020): No listener is left
I/KLMS-2.5.183: ( 3617): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Dec 08 19:42:32 GMT+01:00 2015
D/ActivityManager( 1020): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
D/RegisteredComponentCache( 1444): Collect Tech packages for Knox
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
I/KLMS-2.5.183: ( 3617): KLMSAbstractReciever(): onReceive().END.
I/KLMS-2.5.183: ( 3617): KLMSIntentService(): onCreate()
I/KLMS-2.5.183: ( 3617): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.5.183: ( 3617): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/KLMS-2.5.183: ( 3617): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/KLMS-2.5.183: ( 3617): KLMSIntentService(): PACKAGE_REMOVED
I/KLMS-2.5.183: ( 3617): KLMSIntentService(): listeningToPackageRemoved().START
D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1020): mCursor = null
I/KLMS-2.5.183: ( 3617): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
D/RCPManagerService( 1020): PackageReceiver onReceive()
I/HarmonyEASService( 1020): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy( 1020): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1020): PackageRemovalReceiver::onReceive Enter
D/OTPFW   ( 1020): OtpDbHelper::getInstance New instance created
D/OTPFW   ( 1020): DBIntegrity::getInstance - New instance created
D/PersonaManager( 1444): isKioskContainerExistOnDevice
D/OTPFW   ( 1020): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10175 container id = 0
I/OTPFW   ( 1020): ProvisionData::getAllEntries Enter
E/OTPFW   ( 1020): ProvisionData::getAllEntries Table is empty
D/BackupManagerService( 1020): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1020): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1020): uID is 10175
V/EnterpriseBillingPolicy( 1020): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - end - null
I/splitIntent( 1020): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=28
I/splitIntent( 1020): base  index=28, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1020): other index=31, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1020): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1020): level:94, scale:100, status:2, health:2, present:true, voltage: 4205, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1020): stay LED for charging
E/Zygote  ( 7051): MountEmulatedStorage()
E/Zygote  ( 7051): v2
I/libpersona( 7051): KNOX_SDCARD checking this for 10094
I/libpersona( 7051): KNOX_SDCARD not a persona
I/SELinux ( 7051): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 7051): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 7051): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7051 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/SSRM:aZ ( 1020): MSG_TYPE_APP_REMOVED::
D/TaskPersister( 1020): removeObsoleteFile: deleting file=229_task.xml
I/KLMS-2.5.183: ( 3617): KLMSIntentService(): listeningToPackageRemoved().END
I/KLMS-2.5.183: ( 3617): KLMSIntentService(): onDestroy()
D/TimaKeyStoreProvider( 7051): TimaSignature is unavailable
D/ActivityThread( 7051): Added TimaKeyStore provider
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1020): uID is 10175
V/EnterpriseBillingPolicy( 1020): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - end - null
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
D/PersonaManager( 1444): isKioskContainerExistOnDevice
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
I/art     ( 1020): Explicit concurrent mark sweep GC freed 27715(1923KB) AllocSpace objects, 7(132KB) LOS objects, 33% free, 27MB/41MB, paused 3.666ms total 204.840ms
D/elm:15183( 7051): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15183( 7051): ELMEngine.ELMEngine( context ).
D/elm:15183( 7051): MDMBridge.setEnterpriseBridge()
V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2628): Disconnected process message: 10
D/ActivityManager( 1020): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
D/RegisteredServicesCache( 1444): empty dynamic service
D/PackageManager( 1020): delete codoeFile: 
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
D/AASAuninstall( 1020): userId = 0, info.removedAppID = -1, info.uid = 10175, packageName = com.test.thalitest
I/AASA_removePackage( 1020): UID=10175 Target=com.test.thalitest
D/PackageManager( 1020): result of delete: 1{265437500}
D/AndroidRuntime( 7037): Shutting down VM
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:94 status:2 health:2
D/elm:15183( 7051): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:15183( 7051): ElmAgentService : onCreate()
D/elm:15183( 7051): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/elm:15183( 7051): MainReceiver.listeningToPackageRemoved()
D/elm:15183( 7051): MDMBridge.getInstance()
D/elm:15183( 7051): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:15183( 7051): MDMBridge.getAllLicenseInfoFromSDK()
E/Zygote  ( 7068): MountEmulatedStorage()
E/Zygote  ( 7068): v2
I/libpersona( 7068): KNOX_SDCARD checking this for 1000
I/libpersona( 7068): KNOX_SDCARD not a persona
I/SELinux ( 7068): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7068 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 7068): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 7068): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/elm:15183( 7051): ElmAgentService : onDestroy().
I/ActivityManager( 1020): Killing 6044:com.osp.app.signin/u0a41 (adj 15): empty for 1815s
D/TimaKeyStoreProvider( 7068): TimaSignature is unavailable
D/ActivityThread( 7068): Added TimaKeyStore provider
I/ProcessStatsService( 1020): Pruning old procstats: /data/system/procstats/state-2015-12-07-22-17-49.bin
D/EnterpriseDeviceManagerService( 1020): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1020): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1020): no available spell checker services found
I/PCWCLIENTTRACE_LOG( 7068): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 7068): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 7068): new DMDBOpenHelper instance
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PCWCLIENTTRACE_PushUtil( 7068): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7068): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7068): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7068): [onReceive] - android.intent.action.PACKAGE_REMOVED
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/Zygote  ( 7084): MountEmulatedStorage()
E/Zygote  ( 7084): v2
I/libpersona( 7084): KNOX_SDCARD checking this for 10032
I/libpersona( 7084): KNOX_SDCARD not a persona
I/SELinux ( 7084): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 7084): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 7084): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7084 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/ActivityManager( 1020): Killing 6064:com.sec.knox.bridge/1000 (adj 15): empty for 1815s
D/TimaKeyStoreProvider( 7084): TimaSignature is unavailable
D/ActivityThread( 7084): Added TimaKeyStore provider
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/FeatureConfig( 7084): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
W/ResourceType( 1020): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/art     ( 7037): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
W/ResourcesManager( 1020): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1020): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1020): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/Zygote  ( 7101): MountEmulatedStorage()
I/libpersona( 7101): KNOX_SDCARD checking this for 10038
E/Zygote  ( 7101): v2
I/libpersona( 7101): KNOX_SDCARD not a persona
I/SELinux ( 7101): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 7101): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 7101): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=7101 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1020): Killing 6085:com.google.android.apps.plus/u0a120 (adj 15): empty for 1814s
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TimaKeyStoreProvider( 7101): TimaSignature is unavailable
D/ActivityThread( 7101): Added TimaKeyStore provider
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/UsbSettingsManager( 1020): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 1020): onPackageRemoved : com.test.thalitest
W/libprocessgroup( 1020): failed to open /acct/uid_10025/pid_5964/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10100/pid_5730/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10047/pid_5941/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10035/pid_5314/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10038/pid_5863/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_5793/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_6026/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10032/pid_5420/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10046/pid_5742/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_5772/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10072/pid_5922/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10053/pid_5981/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_6006/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_5808/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10156/pid_5882/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10015/pid_5405/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10091/pid_5763/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10152/pid_5847/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10041/pid_6044/cgroup.procs: No such file or directory
W/ResourcesManager( 7084): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
W/ResourcesManager( 7101): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7101): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_6064/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10120/pid_6085/cgroup.procs: No such file or directory
W/ResourcesManager( 7084): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
E/SQLiteLog( 7101): (28) failed to open "/data/data/com.samsung.android.sdk.samsunglink/databases/asp.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 7101): Failed to open database '/data/data/com.samsung.android.sdk.samsunglink/databases/asp.db'.
E/SQLiteDatabase( 7101): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7101): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7101): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 7101): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 7101): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7101): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7101): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7101): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 7101): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 7101): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 7101): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 7101): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 7101): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7101): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7101): 	at com.mfluent.asp.datamodel.ASPMediaStoreProvider.onCreate(SourceFile:471)
E/SQLiteDatabase( 7101): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
E/SQLiteDatabase( 7101): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
E/SQLiteDatabase( 7101): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/SQLiteDatabase( 7101): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
E/SQLiteDatabase( 7101): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
E/SQLiteDatabase( 7101): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteDatabase( 7101): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteDatabase( 7101): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7101): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 7101): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 7101): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7101): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7101): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 7101): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime( 7101): Shutting down VM
E/AndroidRuntime( 7101): FATAL EXCEPTION: main
E/AndroidRuntime( 7101): Process: com.samsung.android.sdk.samsunglink, PID: 7101
E/AndroidRuntime( 7101): java.lang.RuntimeException: Unable to get provider com.mfluent.asp.datamodel.ASPMediaStoreProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7101): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5705)
E/AndroidRuntime( 7101): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
E/AndroidRuntime( 7101): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
E/AndroidRuntime( 7101): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/AndroidRuntime( 7101): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/AndroidRuntime( 7101): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7101): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 7101): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/AndroidRuntime( 7101): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 7101): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 7101): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 7101): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime( 7101): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7101): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7101): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime( 7101): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime( 7101): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7101): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7101): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7101): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/AndroidRuntime( 7101): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/AndroidRuntime( 7101): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime( 7101): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/AndroidRuntime( 7101): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime( 7101): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7101): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7101): 	at com.mfluent.asp.datamodel.ASPMediaStoreProvider.onCreate(SourceFile:471)
E/AndroidRuntime( 7101): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
E/AndroidRuntime( 7101): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
E/AndroidRuntime( 7101): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/AndroidRuntime( 7101): 	... 11 more
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.samsung.android.sdk.samsunglink
W/ResourcesManager( 7084): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7120): MountEmulatedStorage()
I/libpersona( 7120): KNOX_SDCARD checking this for 10041
E/Zygote  ( 7120): v2
I/libpersona( 7120): KNOX_SDCARD not a persona
E/DropBoxManagerService( 1020): Can't write: system_app_crash
E/DropBoxManagerService( 1020): java.io.FileNotFoundException: /data/system/dropbox/drop181.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1020): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 1020): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 1020): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 1020): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1020): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 1020): 	at com.android.server.am.ActivityManagerService$25.run(ActivityManagerService.java:15884)
E/DropBoxManagerService( 1020): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1020): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1020): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 1020): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 1020): 	... 5 more
I/SELinux ( 7120): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 7120): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
W/ResourcesManager( 7084): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
E/SELinux ( 7120): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
W/ResourcesManager( 7084): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
I/ActivityManager( 1020): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.msc.sa.selfupdate.SelfUpgradeReceiver: pid=7120 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/Process ( 7101): Sending signal. PID: 7101 SIG: 9
W/ResourcesManager( 7084): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.

```
