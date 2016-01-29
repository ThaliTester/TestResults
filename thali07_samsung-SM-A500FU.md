#### Test 575312430087a60_thali07_samsung-SM-A500FU Logs


```
--------- beginning of main
D/Mms/MmsConfig( 5127):  enable multiwindow = true
E/Mms/MessageUtils( 5127): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 5127): updateCountryIso : update country iso info 
D/Mms/MmsConfig( 5127): [end]    init() consume time = 124.740729
D/Mms/Contact( 5127): [start]    init() consume time = 0.537188
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
--------- beginning of system
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
D/Mms/Contact( 5127): [end]    init consume time = 24.394531
D/PackageBroadcastService( 1871): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
D/ChimeraCfgMgr( 1871): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1871): Loading module APK com.google.android.play.games
D/TP/MmsSmsProvider( 1464): query,matched:13, calling pid = 5127
D/TP/MmsSmsProvider( 1464): match 13:Elapsed time : 1.665 ms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
D/Mms/DraftCache( 5127): [start]    rebuildCache consume time = 20.322187
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.config.ConfigFetchService; callingUser = 0; userId(target) = 0
D/TP/MmsSmsProvider( 1464): query,matched:12, calling pid = 5127
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TP/MmsSmsProvider( 1464): match 12:Elapsed time : 6.193 ms
D/Mms/ArtClassLoader( 5127): init [DONE] art
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Mms/MethodReflector( 5127): getSubId is called
D/Mms/TelephonyUtils( 5127): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 5127): getTelephonyProperty is called
D/Mms/DownloadManager( 5127): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5127): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5127): auto download without roaming -> true
D/Mms/DownloadManager( 5127): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/MethodReflector( 5127): getSubId is called
D/Mms/DraftCache( 5127): [end]    rebuildCache consume time = 32.800261
D/Mms/MethodReflector( 5127): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 5127): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 5127): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 5127): getTelephonyProperty is called
D/Mms/DownloadManager( 5127): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 5127): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 5127): auto download without roaming -> true
D/Mms/DownloadManager( 5127): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 5127): auto download during roaming secondary -> false
D/Mms/DownloadManager( 5127): mAutoDownload ------> true
D/ComposerPerformance( 5127): 1454091928492 ms / [DONE] Composer constructor
E/CII     ( 5127): CommonIMSInterface: VoLTE CSC feature disabled.
I/Mms/ReservationManager( 5127): ReservationManager()
I/Mms/ReservationManager( 5127): resetAfterConnected()
D/TP/MmsSmsProvider( 1464): query,matched:7, calling pid = 5127
D/TP/MmsSmsProvider( 1464): match 7:Elapsed time : 2.963 ms
D/Mms/Conversation( 5127): [start]    init() consume time = 25.037812
I/Mms/ReservationManager( 5127): getReservedSendMessageCount(): retMessageCount=0
D/TP/MmsSmsProvider( 1464): deleteConversation threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1464): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1464): updateThread(), thread_id = 9223372036854775807
D/Mms/MmsApp( 5127): [end]    onCreate() consume time = 6.645313
V/TP/MmsSmsDatabaseHelper( 1464): sUpgradeVersion = 0, db.getVersion() = 81
D/TP/MmsSmsProvider( 1464): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1464): need read changed broadcast:false
D/Mms/Conversation( 5127): [end]    init consume time = 10.566406
D/Mms/MessagingNotification( 5127): [start]    init() consume time = 2.523125
D/Mms/MessagingNotification( 5127): [end]    init consume time = 2.459583
D/Mms/SpamFilter( 5127): [start]    SpamFilter fill() begin consume time = 3.776823
D/Mms/Synchronizer( 5127): [start]    doSync consume time = 1.307656
D/TP/MmsSmsProvider( 1464): query,matched:0, calling pid = 5127
V/TP/MmsSmsProvider( 1464): getSimpleConversations entered.
D/Mms/DownloadManager( 5127): Service state changed: Bundle[mParcelledData.dataSize=744]
D/TP/MmsSmsProvider( 1464): update, matched:300, calling pid = 5127
V/TP/MmsSmsProvider( 1464): syncDBData start
V/TP/MmsSmsProvider( 1464): syncDBData sms end
V/TP/MmsSmsProvider( 1464): syncDBData mms end
V/TP/MmsSmsProvider( 1464): syncDBData end
D/Mms/DownloadManager( 5127): roaming ------> false, mSimSlot = 0
D/TP/MmsSmsProvider( 1464): match 0:Elapsed time : 4.590 ms
D/TP/MmsSmsProvider( 1464): query,matched:400, calling pid = 5127
D/Mms/MethodReflector( 5127): getSubId is called
D/Mms/TelephonyUtils( 5127): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 5127): getTelephonyProperty is called
D/Mms/DownloadManager( 5127): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5127): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5127): auto download without roaming -> true
D/Mms/DownloadManager( 5127): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5127): mAutoDownload ------> true
D/Mms/SpamFilter( 5127): [end]    SpamFilter fill() finished consume time = 21.232813
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/Mms/Synchronizer( 5127): [end]    doSync consume time = 2.330885
E/Zygote  ( 5303): MountEmulatedStorage()
I/libpersona( 5303): KNOX_SDCARD checking this for 10072
E/Zygote  ( 5303): v2
I/libpersona( 5303): KNOX_SDCARD not a persona
I/SELinux ( 5303): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1015): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5303 uid=10072 gids={50072, 9997} abi=armeabi-v7a
I/SELinux ( 5303): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5303): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5303): TimaSignature is unavailable
D/ActivityThread( 5303): Added TimaKeyStore provider
D/Mms/FreeMessageStatusReceiver( 5127): onReceive, action : android.intent.action.PACKAGE_ADDED
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5319): MountEmulatedStorage()
E/Zygote  ( 5319): v2
I/libpersona( 5319): KNOX_SDCARD checking this for 10047
I/libpersona( 5319): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5319 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
I/SELinux ( 5319): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5319): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5319): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5319): TimaSignature is unavailable
D/ActivityThread( 5319): Added TimaKeyStore provider
D/Mms/FreeMessageReceiverService( 5127): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 5127): onHandleIntent: ACTION_PACKAGE_ADDED
D/BadgeProvider( 5303): onCreate
D/BadgeProvider( 5303): DatabaseHelper
I/ActivityManager( 1015): Killing 3624:com.android.providers.calendar/u0a42 (adj 15): empty #31
I/ActivityManager( 1015): Killing 4554:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #32
D/Mms/MessagingNotification( 5127): checkBadgeCount unreadCount=0 badgeCount=0
D/TP/SmsProvider( 1464): query,matched:26, calling pid = 5127
D/TP/SmsProvider( 1464): match 26:Elapsed time : 1.833 ms
W/ResourcesManager( 5319): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5319): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5319): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/TP/MmsSmsProvider( 1464): query,matched:6, calling pid = 5127
D/TP/MmsSmsProvider( 1464): match 6:Elapsed time : 1.392 ms
I/SL_DEBUG( 5247): isLoggable:: isProductShip = 1
I/SL_DEBUG( 5247): isLoggable:: SL_DEBUG_EXIST = false
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5339): MountEmulatedStorage()
I/libpersona( 5339): KNOX_SDCARD checking this for 10025
E/Zygote  ( 5339): v2
I/libpersona( 5339): KNOX_SDCARD not a persona
I/SELinux ( 5339): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1015): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5339 uid=10025 gids={50025, 9997} abi=armeabi-v7a
I/SELinux ( 5339): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5339): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ConfigFetchService( 1871): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1871): launchTask
D/TimaKeyStoreProvider( 5339): TimaSignature is unavailable
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityThread( 5339): Added TimaKeyStore provider
D/ChimeraCfgMgr( 1871): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1871): Module APK com.google.android.play.games already loaded
I/ActivityManager( 1015): Killing 4347:com.samsung.android.app.mirrorlink/1000 (adj 15): empty #31
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_4554/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10042/pid_3624/cgroup.procs: No such file or directory
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/PeopleContactsSync( 1871): CP2 sync disabled
D/ChimeraCfgMgr( 1871): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 1871): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1871): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1871): No vision deps
W/ResourcesManager( 5339): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
V/ConfigFetchTask( 1871): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1ValWPmTt8y7kwHjah-UWvGF9RGC7nhEy_tb65-E4wTL8KdxfhuZOjahZV0EfouNmoRIGUXO23HiWZeNUXSsWa_RRIfT0EK_Mvi4Ej1HdpxfKer2cIkaSOGr0BgLbqSZqYscP3e8KktSxMRNCwYaNhX9EH6XR3W57kCm_sPGjKBVoZGUQK48jALHTvyuxJzzuPnqiOH-OLlc3kQWqKHsPNFlv7hrqwTeLnDF1PXO3XcNgClnC0
I/GoogleURLConnFactory( 1871): Using platform SSLCertificateSocketFactory
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/OMACP   ( 5339): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
I/System.out( 1871): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1871): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1871): (HTTPLog)-Static: isShipBuild true
I/System.out( 1871): (HTTPLog)-Thread-243-549868013: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1871): (HTTPLog)-Static: isSBSettingEnabled false
D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10012
D/MyFiles ( 5319): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
D/Mms/Omacp( 5127): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
W/ConfigFetchTask( 1871): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
E/installd(  287): system dir 0 : /system/app/
E/installd(  287): system dir 1 : /system/priv-app/
E/installd(  287): system dir 2 : /vendor/app/
E/installd(  287): system dir 3 : /oem/app/
I/ConfigFetchService( 1871): fetch service done; releasing wakelock
I/ConfigFetchService( 1871): stopping self
I/OMACP   ( 5339): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
I/OMACP   ( 5339): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
I/OMACP   ( 5339): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
I/OMACP   ( 5339): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_4347/cgroup.procs: No such file or directory
I/OMACP   ( 5339): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
I/OMACP   ( 5339): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
I/OMACP   ( 5339): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
W/ContextImpl( 5247): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
I/OMACP   ( 5339): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
I/OMACP   ( 5339): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
I/OMACP   ( 5339): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
I/OMACP   ( 5339): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
I/OMACP   ( 5339): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
I/OMACP   ( 5339): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
I/TactileAssist( 1015): enable value -1
I/TactileAssist( 1015): internal enable value -1
I/TactileAssist( 1015): intensity value -1
I/TactileAssist( 1015): saveAppList value true
I/TactileAssist( 1015): List of disabled apps :
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/PackageManager( 1015): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
E/Zygote  ( 5367): MountEmulatedStorage()
I/libpersona( 5367): KNOX_SDCARD checking this for 10053
E/Zygote  ( 5367): v2
I/libpersona( 5367): KNOX_SDCARD not a persona
I/SELinux ( 5367): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1015): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=5367 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
I/SELinux ( 5367): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/GAv4    ( 5142): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5142):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5142):   adb logcat -s GAv4
E/SELinux ( 5367): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5367): TimaSignature is unavailable
D/ActivityThread( 5367): Added TimaKeyStore provider
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5247): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
W/GAv4    ( 5142): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
W/ResourcesManager( 5367): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/GAv4    ( 5142): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 5142): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
D/Compatibility( 5367): onReceive() it will make start service
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
W/AnalyticsTrackerProxyImpl( 5142): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
I/ActivityManager( 1015): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=5392 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 5392): MountEmulatedStorage()
E/Zygote  ( 5392): v2
I/libpersona( 5392): KNOX_SDCARD checking this for 1000
D/Compatibility( 5367): onHandleIntent()
I/libpersona( 5392): KNOX_SDCARD not a persona
D/Compatibility( 5367): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10174, android.intent.extra.user_handle=0}]
I/SELinux ( 5392): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/Compatibility( 5367): found: 2
I/SELinux ( 5392): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
W/BaseAppContext( 1871): Using Auth Proxy for data requests.
E/SELinux ( 5392): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/BaseAppContext( 1871): Using Auth Proxy for data requests.
D/TimaKeyStoreProvider( 5392): TimaSignature is unavailable
D/ActivityThread( 5392): Added TimaKeyStore provider
D/Compatibility( 5367): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5367): skipping ResolveInfo{b9550e5 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5367): considering ResolveInfo{235767ba com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5367): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5367): enabling receiver ResolveInfo{21ae066b com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 5367): enabling receiver ResolveInfo{3ecf85c8 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 5367): enabling receiver ResolveInfo{39cf1661 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/Compatibility( 5367): enabling receiver ResolveInfo{26044586 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
E/Zygote  ( 5410): MountEmulatedStorage()
E/Zygote  ( 5410): v2
I/libpersona( 5410): KNOX_SDCARD checking this for 10041
I/libpersona( 5410): KNOX_SDCARD not a persona
I/SELinux ( 5410): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5410): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1015): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=5410 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/Compatibility( 5367): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
E/SELinux ( 5410): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Killing 4807:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
D/TimaKeyStoreProvider( 5410): TimaSignature is unavailable
D/ActivityThread( 5410): Added TimaKeyStore provider
W/ContextImpl( 5392): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
W/BaseAppContext( 1871): Using Auth Proxy for data requests.
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1015): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=5427 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 5427): MountEmulatedStorage()
I/libpersona( 5427): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5427): v2
I/libpersona( 5427): KNOX_SDCARD not a persona
I/SELinux ( 5427): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5427): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5427): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1015): failed to open /acct/uid_10069/pid_4807/cgroup.procs: No such file or directory
W/BaseAppContext( 1871): Using Auth Proxy for data requests.
I/SA      ( 5410): [SSP] onCreated
I/ActivityManager( 1015): Killing 4825:com.sec.knox.bridge/1000 (adj 15): empty #31
D/TimaKeyStoreProvider( 5427): TimaSignature is unavailable
D/ActivityThread( 5427): Added TimaKeyStore provider
W/ResourcesManager( 5427): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
I/SA      ( 5410): [TPM] There is no property file
I/SA      ( 5410): [SCU] isHaveSA() - false
I/SA      ( 5410): [TPM] getModelProperty : null
I/SA      ( 5410): [TPM] getCSCProperty : null
I/SA      ( 5410): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 5410): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 5410): [DM] TFT FEATURE: false
I/ActivityManager( 1015): Killing 4841:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
I/SA      ( 5410): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 5410): [DM] init START
I/SA      ( 5410): [DM] This device is not a Vodafone
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
W/ResourceType( 5410): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 5410): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 5410): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 5410): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 5410): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 5410): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 5410): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 5410): No package identifier when getting value for resource number 0x00000000
E/Zygote  ( 5447): MountEmulatedStorage()
E/Zygote  ( 5447): v2
I/libpersona( 5447): KNOX_SDCARD checking this for 1000
I/libpersona( 5447): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=5447 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 4915:com.google.android.apps.plus/u0a120 (adj 15): empty #31
I/SELinux ( 5447): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_4825/cgroup.procs: No such file or directory
W/ResourceType( 5410): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
I/SELinux ( 5447): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
W/ResourceType( 5410): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 5410): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 5410): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 5410): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 5410): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 5410): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 5410): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
E/SELinux ( 5447): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ResourceType( 5410): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
W/ResourceType( 5410): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 5410): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 5410): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 5410): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 5410): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 5410): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 5410): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 5410): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
I/SA      ( 5410): [SCU] isHaveSA() - false
I/SA      ( 5410): support phone number id : false
I/SA      ( 5410): [DM] Supports Ref Jpn : true
I/SA      ( 5410): [DM] init END
I/SA      ( 5410): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
I/SA      ( 5410): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10174 extra.user_handle.:0 ]
I/ActivityManager( 1015): Killing 4205:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
D/TimaKeyStoreProvider( 5447): TimaSignature is unavailable
,D/ActivityThread( 5447): Added TimaKeyStore provider
I/art     ( 1015): Explicit concurrent mark sweep GC freed 193671(12MB) AllocSpace objects, 4(3MB) LOS objects, 33% free, 26MB/40MB, paused 3.093ms total 191.478ms
I/art     ( 1015): WaitForGcToComplete blocked for 191.285ms for cause Explicit
W/ResourcesManager( 5447): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/BaseAppContext( 1871): Using Auth Proxy for data requests.
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5142): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.docs/cache
I/ActivityManager( 1015): Killing 4571:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
W/BaseAppContext( 1871): Using Auth Proxy for data requests.
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_4841/cgroup.procs: No such file or directory
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5470): MountEmulatedStorage()
E/Zygote  ( 5470): v2
I/libpersona( 5470): KNOX_SDCARD checking this for 10120
I/libpersona( 5470): KNOX_SDCARD not a persona
I/SELinux ( 5470): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5470): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1015): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5470 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 3660:com.google.android.talk/u0a104 (adj 15): empty #31
E/SELinux ( 5470): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/art     ( 1015): Explicit concurrent mark sweep GC freed 3874(208KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 26MB/40MB, paused 2.537ms total 158.687ms
D/TimaKeyStoreProvider( 5470): TimaSignature is unavailable
D/ActivityThread( 5470): Added TimaKeyStore provider
W/libprocessgroup( 1015): failed to open /acct/uid_10057/pid_4205/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10120/pid_4915/cgroup.procs: No such file or directory
W/ResourcesManager( 5142): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5142): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 5470): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/AndroidRuntime( 5467): 
D/AndroidRuntime( 5467): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5467): CheckJNI is OFF
D/AndroidRuntime( 5467): readGMSProperty: start
D/AndroidRuntime( 5467): readGMSProperty: already setted!!
D/AndroidRuntime( 5467): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5467): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5467): readGMSProperty: end
D/AndroidRuntime( 5467): addProductProperty: start
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/libprocessgroup( 1015): failed to open /acct/uid_10150/pid_4571/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10104/pid_3660/cgroup.procs: No such file or directory
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/GLSUser ( 1698): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1698): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1698): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1698): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/Finsky  ( 4857): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 4857): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4857): [1] 5.onFinished: Scheduling replication attempt 1.
I/ActivityManager( 1015): Killing 4113:com.google.android.gm/u0a101 (adj 15): empty #31
E/AffinityControl( 5467): AffinityControl: registerfunction enter
V/JNIHelp ( 5142): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/AndroidRuntime( 5467): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1015): inState():  stateMachine is null !!
I/PersonaManagerService( 1015): PersonaId don't exist
I/ActivityManager( 1015): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/ActivityThread( 5142): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5142): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@15165a71: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5142): Installed default security provider GmsCore_OpenSSL
W/ActivityManager( 1015): mDVFSHelper.acquire()
D/FocusedStackFrame( 1015): Set to : 0
D/PhoneWindow( 1015): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1015): *FMB* installDecor flags : 25362712
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1015): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5498 uid=10174 gids={50174, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1015): Focused application set to: xxxx
D/InputDispatcher( 1015): Focus left window: 1489
E/Zygote  ( 5498): MountEmulatedStorage()
I/libpersona( 5498): KNOX_SDCARD checking this for 10174
E/Zygote  ( 5498): v2
I/libpersona( 5498): KNOX_SDCARD not a persona
I/SELinux ( 5498): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5498): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5498): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1015): failed to open /acct/uid_10101/pid_4113/cgroup.procs: No such file or directory
D/AndroidRuntime( 5467): Shutting down VM
D/PhoneWindow( 1015): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1015): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  257): id=11 createSurf (1x1),1 flag=404, uhalitest
D/SSRM:n  ( 1015): SIOP:: AP = 370
D/TimaKeyStoreProvider( 5498): TimaSignature is unavailable
D/ActivityThread( 5498): Added TimaKeyStore provider
D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/WindowManager( 1015): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/ActivityManager( 1015): Display changed displayId=0
D/StatusBarManagerService( 1015): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1015): isKioskContainerExistOnDevice
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
D/WindowOrientationListener( 1015):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
I/SurfaceFlinger(  257): id=8 Removed Mauncher (5/9)
I/SurfaceFlinger(  257): id=8 Removed Mauncher (-2/9)
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
D/Launcher( 1489): onTrimMemory. Level: 20
V/ActivityThread( 1489): updateVisibility : ActivityRecord{27c31fe9 token=android.os.BinderProxy@b2e5f38 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
W/art     ( 5467): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,E/Zygote  ( 5518): MountEmulatedStorage(),
I/ActivityManager( 1015): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5518 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
E/Zygote  ( 5518): v2
I/libpersona( 5518): KNOX_SDCARD checking this for 10057
I/libpersona( 5518): KNOX_SDCARD not a persona
,I/SELinux ( 5518): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/WebViewFactory( 5498): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,I/SELinux ( 5518): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 5518): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Killing 4461:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
,I/art     (  312): Explicit concurrent mark sweep GC freed 8722(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 635us total 26.240ms
,D/ChimeraCfgMgr( 1871): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1871): Module APK com.google.android.play.games already loaded
,D/TimaKeyStoreProvider( 5518): TimaSignature is unavailable
,D/ActivityThread( 5518): Added TimaKeyStore provider
,I/LibraryLoader( 5498): Time to load native libraries: 4 ms (timestamps 2285-2289)
I/LibraryLoader( 5498): Expected native library version number "",actual native library version number ""
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 624us total 20.948ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 614us total 16.914ms
,V/WebViewChromiumFactoryProvider( 5498): Binding Chromium to main looper Looper (main, tid 1) {39cf1661}
I/LibraryLoader( 5498): Expected native library version number "",actual native library version number ""
I/chromium( 5498): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5498): Initializing chromium process, singleProcess=true
,W/art     ( 5498): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5498): ApplicationContext is null in ApplicationStatus
,W/libprocessgroup( 1015): failed to open /acct/uid_10040/pid_4461/cgroup.procs: No such file or directory
,W/chromium( 5498): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5498): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5498): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 5498): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5498): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5498): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5498): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5498): Local Branch: 
I/Adreno-EGL( 5498): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5498): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5498):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5544): MountEmulatedStorage()
,E/Zygote  ( 5544): v2
,I/libpersona( 5544): KNOX_SDCARD checking this for 10010
I/libpersona( 5544): KNOX_SDCARD not a persona
I/SELinux ( 5544): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1015): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=5544 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/SELinux ( 5544): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 5544): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5544): TimaSignature is unavailable
D/ActivityThread( 5544): Added TimaKeyStore provider
,D/BluetoothAdapter( 5498): 193124323: getState() :  mService = null. Returning STATE_OFF
,D/AcmsKeyStoreHelper( 5191):  getKeyStoreForApplication Enter
,I/Mms/MmsApp( 5127):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 5127): [start]    fillCache consume time = 1957.420625
D/Mms/ComposeMessageFragment( 5127): fillCache, easy = false
,D/AbsListView( 5127): Get MotionRecognitionManager
,D/MotionRecognitionService( 1015):  ssp status : false
,D/Mms/ComposeMessageFragment( 5127): [end]    fillCache consume time = 74.738437
,I/AcmsKeyStoreHelper( 5191): Key Store exist
I/AcmsKeyStoreHelper( 5191): Hence loading the keystore file
,W/ActivityManager( 1015): Activity pause timeout for ActivityRecord{1c780967 u0 com.test.thalitest/.MainActivity t233},
,D/LocationManagerService( 1015): getProviders()=[passive]
,D/Mms/BubbleViewCache( 5127): fillCache bubble = 1
,D/AcmsKeyStoreHelper( 5191):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 5191): getKeyStoreForApplication success 
D/AcmsCore( 5191): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 5191): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5191): Decrementing - Counter value: 1
D/AcmsCore( 5191): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 5191): This is NOT a valid MirrorLink app
D/AcmsCore( 5191): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 5191): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5191): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 5191): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 5191): getSvcCounter - Counter value: 0
D/AcmsService( 5191): Enter onDestroy
I/AcmsService( 5191): cleanUp(): inside service clean up
D/AcmsCore( 5191): AcmsCore: inside DeInit
D/AcmsCore( 5191): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 5191): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 5191): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 5191): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 5191): AppEntryInterface: Inside CleanUp
D/AcmsServiceMonitor( 5191): getSvcCounter - Counter value: 0
D/AcmsService( 5191): killing acms process
I/Process ( 5191): Sending signal. PID: 5191 SIG: 9
,I/UpdateIcingCorporaServi( 5518): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/splitIntent( 1015): Queue : backgroundsplit_2 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1015): Killing 4368:com.google.android.music:main/u0a111 (adj 15): empty #31
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.EventLogService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = flipboard.app/flipboard.gcm.FlipboardGCMIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = flipboard.app, destAppInfo.processName = flipboard.app
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = flipboard.app, destAppInfo.processName = com.google.process.gapps
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/EventLogService( 1871): Aggregate from 1454090127787 (log), 1454090127787 (data)
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1698): GcmService start Intent { act=com.google.android.c2dm.intent.UNREGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.UNREGISTER
,W/art     ( 5498): Attempt to remove local handle scope entry from IRT, ignoring
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1698): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10012
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = flipboard.app
,W/AwContents( 5498): onDetachedFromWindow called when already detached. Ignoring
,D/ActivityManager( 1015): retrieveServiceLocked(): component = flipboard.app/flipboard.gcm.FlipboardGCMIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = flipboard.app, destAppInfo.processName = flipboard.app
,D/PhoneWindow( 5498): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 5498): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 5498): CordovaWebView is running on device made by: samsung
,I/ActivityManager( 1015): Process ACMS.Process (pid 5191)(adj 0) has died(54,1106)
,W/art     ( 5498): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5498): Attempt to remove local handle scope entry from IRT, ignoring
,I/art     ( 1698): Explicit concurrent mark sweep GC freed 16385(910KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 10MB/17MB, paused 1.168ms total 55.216ms
,I/UpdateIcingCorporaServi( 5518): UpdateCorporaTask done [took 134 ms] updated apps [took 134 ms] 
,I/ActivityManager( 1015): Killing 4891:com.google.android.gms:car/u0a12 (adj 15): empty #31
,W/ActivityManager( 1015): Scheduling restart of crashed service com.google.android.gms/.car.InCallServiceImpl in 1000ms
,D/OpenGLRenderer( 5498): Render dirty regions requested: true
,D/ActivityManager( 1015): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1015): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1015): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1015): handleActiveUserChange for user 0
D/PersonaManagerService( 1015): getPersonasForUser(): returning null!
,W/chromium( 5498): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,V/ActivityThread( 5498): updateVisibility : ActivityRecord{12c97fd3 token=android.os.BinderProxy@168c20d {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PhoneWindow( 5498): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 5498): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  257): id=12 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1015): Focus entered window: 5498
,W/libprocessgroup( 1015): failed to open /acct/uid_10111/pid_4368/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10012/pid_4891/cgroup.procs: No such file or directory
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 5498): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 5498): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5498): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 5498): Enabling debug mode 0
,D/InputMethodManagerService( 1015): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false,
W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PanelView( 1173): There is/are notification(s) 
,I/SamsungIME( 1773): getCurrentCandidateView
,I/ActivityManager( 1015): Displayed Component not be shown by security: +955ms (total +1s44ms)
,W/ActivityManager( 1015): mDVFSHelper.release()
,I/Timeline( 1015): Timeline: Activity_windows_visible id: ActivityRecord{1c780967 u0 com.test.thalitest/.MainActivity t233} time:73049
,W/IInputConnectionWrapper( 5498): showStatusIcon on inactive InputConnection
,I/Timeline( 5498): Timeline: Activity_idle id: android.os.BinderProxy@168c20d time:73060
,I/SurfaceFlinger(  257): id=11 Removed uhalitest (7/9)
,I/SurfaceFlinger(  257): id=11 Removed uhalitest (-2/9)
,D/SamsungIME( 1773): Dismiss ExpandCandiate
,I/SamsungIME( 1773): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1773): getDebugLevel  : 0x4f4c,
,I/SamsungIME( 1773): KeybaordView init() : load resources
,I/SamsungIME( 1773): getCurrentKeyboard
,I/SamsungIME( 1773): getTextKeyboard
,W/BindingManager( 5498): Cannot call determinedVisibility() - never saw a connection for the pid: 5498
,D/SamsungIME( 1773): [SwiftkeyWrapper] currentLangauge : 1701729619
,E/SMD     (  291): DCD OFF
,D/JsMessageQueue( 5498): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5498): JniHelper::setJavaVM(0xb7180450), pthread_self() = -1217551936
,I/chromium( 5498): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5602): MountEmulatedStorage(),
E/Zygote  ( 5602): v2
I/libpersona( 5602): KNOX_SDCARD checking this for 10012
I/libpersona( 5602): KNOX_SDCARD not a persona
I/SELinux ( 5602): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1015): Start proc com.google.android.gms:car for service com.google.android.gms/.car.InCallServiceImpl: pid=5602 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,I/SELinux ( 5602): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 5602): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5602): TimaSignature is unavailable
,D/ActivityThread( 5602): Added TimaKeyStore provider
,W/ResourcesManager( 5602): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5602): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 5602): VM with version 2.1.0 has multidex support
,I/MultiDex( 5602): install
I/MultiDex( 5602): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 5602): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 5602): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5602): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@25e43a88: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5602): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1015): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1015): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1015): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1015): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,D/GCM     ( 1698): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1698): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 1871): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/ActivityManager( 1015): Killing 5008:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/WearableService( 4241): callingUid 10012, callindPid: 4241
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1679): [180] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1871): Restart initialization of location
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5008/cgroup.procs: No such file or directory
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/jxcore-log( 5498): Initializing JXcore engine
W/jxcore-log( 5498): JXcore engine is ready
,E/audit   ( 1861): type=1400 msg=audit(1454091932.602:203): avc:  denied  { ioctl } for  pid=5601 comm="Thread-957" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1861):  SEPF_SM-A500FU_5.0.2_0027
E/audit   ( 1861): type=1300 msg=audit(1454091932.602:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=3 a3=9ec008f8 items=0 ppid=312 ppcomm=main pid=5601 auid=4294967295 uid=10174 gid=10174 euid=10174 suid=10174 fsuid=10174 egid=10174 sgid=10174 fsgid=10174 ses=4294967295 tty=(none) comm="Thread-957" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1861): type=1320 msg=audit(1454091932.602:203): 
,W/jxcore-log( 5498): Starting JXcore engine
,W/jxcore-log( 5498): Platform android
W/jxcore-log( 5498): 
W/jxcore-log( 5498): Process ARCH arm
W/jxcore-log( 5498): 
,I/jxcore-log( 5498): JXcore Cordova bridge is ready!
I/jxcore-log( 5498): 
,W/jxcore-log( 5498): JXcore engine is started
,E/jxcore  ( 5498): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 5498): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5498): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,D/FocusedStackFrame( 1015): Set to : 0
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.test.thalitest,
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/InputDispatcher( 1015): Focused application set to: xxxx
D/InputDispatcher( 1015): Focus left window: 5498
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
,I/ActivityManager( 1015): Killing 5025:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
,W/PluginManager( 5498): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 22ms. Plugin should use CordovaInterface.getThreadPool().
,I/SurfaceFlinger(  257): id=12 Removed NainActivit (6/8),
I/SurfaceFlinger(  257): id=12 Removed NainActivit (-2/8)
,W/ActivityManager( 1015): mDVFSHelper.acquire()
,V/WindowManager( 1015): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,D/Launcher( 1489): onRestart, Launcher: 193124323
,D/Launcher( 1489): onStart, Launcher: 193124323
D/Launcher.HomeView( 1489): onStart
,D/Launcher( 1489): onResume, Launcher: 193124323
,D/SettingsProvider( 1015): name = kids_home_mode
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10007
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
D/Launcher.HomeView( 1489): onResume
,D/Launcher( 1489): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/MenuAppsGridFragment( 1489): onResume
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
D/WallpaperManager( 1489): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1489): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,I/splitIntent( 1015): Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=5, mSplitNum[2]=7, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=9
I/splitIntent( 1015): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,D/GalleryCacheReady( 4480): Receive : home resume
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,D/Mms/UIEventReceiver( 5127): ui event
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,D/Recents_RecreateReceiver( 2420): onReceive by home
,D/ActivityManager( 1015): handle home activity for 0
,I/WallpaperManagerService( 1015): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1015): post home show event for user 0
D/ActivityManager( 1015): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1015): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1015): postActiveUserChange, showWhenLocked: false
D/WallpaperManagerService( 1015):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 1015): handleHomeShow for 0 and current 0
D/Launcher.HomeView( 1489): onPause
D/PersonaManagerService( 1015): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1015): handleActiveUserChange for user 0
D/Launcher( 1489): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
E/JavaBinder( 1015): !!! FAILED BINDER TRANSACTION !!!
,W/BroadcastQueue( 1015): Exception when sending broadcast to ComponentInfo{com.sec.android.widgetapp.activeapplicationwidget/com.sec.android.widgetapp.activeapplicationwidget.ProgramMonitorProvider}
W/BroadcastQueue( 1015): android.os.TransactionTooLargeException
W/BroadcastQueue( 1015): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue( 1015): 	at android.os.BinderProxy.transact(Binder.java:511)
W/BroadcastQueue( 1015): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
W/BroadcastQueue( 1015): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:309)
W/BroadcastQueue( 1015): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1236)
W/BroadcastQueue( 1015): 	at com.android.server.am.BroadcastQueue$BroadcastHandler.handleMessage(BroadcastQueue.java:194)
W/BroadcastQueue( 1015): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/BroadcastQueue( 1015): 	at android.os.Looper.loop(Looper.java:145)
W/BroadcastQueue( 1015): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BroadcastQueue( 1015): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5622): MountEmulatedStorage()
I/libpersona( 5622): KNOX_SDCARD checking this for 10142
E/Zygote  ( 5622): v2
I/libpersona( 5622): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=5622 uid=10142 gids={50142, 9997, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 5622): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5622): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5622): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5633): MountEmulatedStorage(),
E/Zygote  ( 5633): v2
I/libpersona( 5633): KNOX_SDCARD checking this for 10139
I/libpersona( 5633): KNOX_SDCARD not a persona
,I/SELinux ( 5633): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1015): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=5633 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
I/SELinux ( 5633): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5633): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5622): TimaSignature is unavailable
D/ActivityThread( 5622): Added TimaKeyStore provider
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/BroadcastQueue( 1015): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1489, uid=10007) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
I/SurfaceFlinger(  257): id=13 createSurf (720x1280),1 flag=4, Mauncher
,D/StatusBarManagerService( 1015): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 1015): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,W/libprocessgroup( 1015): failed to open /acct/uid_10142/pid_5025/cgroup.procs: No such file or directory
,D/InputDispatcher( 1015): Focus entered window: 1489
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 1489): log_dcs ThreadedRenderer::initialize entered! 
,D/TimaKeyStoreProvider( 5633): TimaSignature is unavailable
,D/ActivityThread( 5633): Added TimaKeyStore provider
,D/Launcher.HomeView( 1489): onStop
V/ActivityThread( 1489): updateVisibility : ActivityRecord{27c31fe9 token=android.os.BinderProxy@b2e5f38 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/InputMethodManagerService( 1015): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/IInputConnectionWrapper( 5498): showStatusIcon on inactive InputConnection
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SamsungIME( 1773): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,V/TaskCloserActivity( 5622): TaskCloserActivity enter()
,V/TaskCloserActivity( 5622): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,W/ResourcesManager( 5633): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 5633): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5633): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 5633): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 5633): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/ActivityManager( 1015): Killing 3958:com.sec.spp.push/u0a35 (adj 15): empty #31
,D/PanelView( 1173): There is/are notification(s) 
,I/Timeline( 1489): Timeline: Activity_idle id: android.os.BinderProxy@b2e5f38 time:75389
,I/splitIntent( 1015): Queue : backgroundsplit_1 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1015): Killing 5107:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,I/Timeline( 1015): Timeline: Activity_windows_visible id: ActivityRecord{14fc5754 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t232} time:75415
,W/ActivityManager( 1015): mDVFSHelper.release()
V/TaskCloserActivity( 5622): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,D/WindowOrientationListener( 1015):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,D/PersonaManager( 1015): isKioskContainerExistOnDevice
,W/libprocessgroup( 1015): failed to open /acct/uid_10100/pid_5107/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10035/pid_3958/cgroup.procs: No such file or directory
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4232, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ConfigService( 1698): onDestroy
,E/SMD     (  291): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :8
,E/Watchdog( 1015): !@Sync 2
,I/ServiceManager(  321): Waiting for service AtCmdFwd...,
,V/AlarmManager( 1015): waitForAlarm result :8
,D/NtpTrustedTime( 1015): forceRefresh() from cache miss
,D/EnterpriseController(  278): uids 1000
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 1000
,D/EnterpriseController(  278): uids 1000
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 1000
,D/NtpTrustedTime( 1015): forceRefresh Fail.
,I/ActivityManager( 1015): Killing 4726:com.sec.spp.push:RemoteNotiProcess/u0a35 (adj 15): empty #31
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  321): Waiting for service AtCmdFwd...,
,W/libprocessgroup( 1015): failed to open /acct/uid_10035/pid_4726/cgroup.procs: No such file or directory
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,D/PackageManager( 1015): [MSG] MCS_UNBIND
,I/ActivityManager( 1015): Killing 5142:com.google.android.apps.docs/u0a91 (adj 15): empty #31
,W/libprocessgroup( 1015): failed to open /acct/uid_10091/pid_5142/cgroup.procs: No such file or directory
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,V/AlarmManager( 1015): waitForAlarm result :4,
,D/SSRM:n  ( 1015): SIOP:: AP = 340
,I/PowerManagerService( 1015): [PWL] Off : 30s ago
,I/PowerManagerService( 1015): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService( 1015): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1015): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=1871, ws=null) (elapsedTime=48375)
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 1015): Waited long enough for: ServiceRecord{3cfbaec1 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4247, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  291): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :8
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF,
,V/AlarmManager( 1015): waitForAlarm result :4
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0,
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10012
,D/ActivityManager( 1015): retrieveServiceLocked(): component = flipboard.app/flipboard.gcm.FlipboardGCMIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = flipboard.app, destAppInfo.processName = flipboard.app
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5670): MountEmulatedStorage(),
E/Zygote  ( 5670): v2
,I/libpersona( 5670): KNOX_SDCARD checking this for 10104
I/ActivityManager( 1015): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5670 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/libpersona( 5670): KNOX_SDCARD not a persona
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = flipboard.app, destAppInfo.processName = com.google.process.gapps
I/SELinux ( 5670): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 5670): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 5670): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1698): GcmService start Intent { act=com.google.android.c2dm.intent.UNREGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.UNREGISTER
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 5670): TimaSignature is unavailable
,D/ActivityThread( 5670): Added TimaKeyStore provider
,I/System.out( 1698): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10012
,W/ResourcesManager( 5670): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/SSRM:n  ( 1015): SIOP:: AP = 320
,I/Babel_SMS( 5670): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 5670): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5670): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,I/Babel_SMS( 5670): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5670): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5670): MmsConfig.loadFromResources
,E/Babel_SMS( 5670): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 5670): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,W/QCamera2Factory(  285): getCameraInfo: E, camera_id = 0
W/QCamera2Factory(  285): getCameraInfo: X
,W/QCamera2Factory(  285): getCameraInfo: E, camera_id = 1
,W/QCamera2Factory(  285): getCameraInfo: X
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 28448(1682KB) AllocSpace objects, 14(224KB) LOS objects, 33% free, 27MB/40MB, paused 2.325ms total 140.991ms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,W/Settings( 5670): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,I/Babel_Crash( 5670): startup - clean
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/Babel   ( 5670): deleted: false for 0
,I/GLSUser ( 1698): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1698): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1698): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1698): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/Finsky  ( 4857): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4857): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4857): [1] 5.onFinished: Scheduling replication attempt 2.
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = flipboard.app
,D/ActivityManager( 1015): retrieveServiceLocked(): component = flipboard.app/flipboard.gcm.FlipboardGCMIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = flipboard.app, destAppInfo.processName = flipboard.app
,W/VideoCapabilities( 5670): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5670): Unsupported mime audio/evrc
,W/AudioCapabilities( 5670): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5670): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 5670): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 5670): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 5670): Unsupported mime audio/x-ima
,W/AudioCapabilities( 5670): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5670): Unsupported mime audio/evrc
,W/VideoCapabilities( 5670): Unsupported mime video/wvc1
,W/VideoCapabilities( 5670): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 5670): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 5670): Unsupported mime video/wvc1
,W/VideoCapabilities( 5670): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 5670): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 5670): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 5670): Unsupported mime video/mp43
,W/VideoCapabilities( 5670): Unsupported mime video/sorenson
,W/VideoCapabilities( 5670): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5670): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5670): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5670): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5670): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5670): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager( 1015): Killing 5097:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,I/vclib   ( 5670): onServiceConnected
,W/Babel   ( 5670): Attempted to change video mute state without an active call.
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1015): failed to open /acct/uid_10015/pid_5097/cgroup.procs: No such file or directory
,E/SQLiteLog( 1698): (10) POSIX Error : 11 SQLite Error : 3850
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :8,
,D/SSRM:n  ( 1015): SIOP:: AP = 310
,I/PowerManagerService( 1015): [PWL] Off : 50s ago,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4253, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): Plugged,
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
I/MotionRecognitionService( 1015): mGripSensorEnabled= false,
V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  291): DCD OFF,
,D/FactoryTest( 4759): Not factory mode
,D/FactoryTest( 4759): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 4759): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 4759): still no open session command from host, so toast
,W/ContextImpl( 4759): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 4759): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,I/Timeline( 4759): Timeline: Activity_launch_request id:com.android.settings time:107510,
E/PersonaManagerService( 1015): inState():  stateMachine is null !!
I/PersonaManagerService( 1015): PersonaId don't exist
I/ActivityManager( 1015): do not start freezing screen for locked container getKeyguardshowstate = false,
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.android.settings,
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1015): mDVFSHelper.acquire(),
D/FocusedStackFrame( 1015): Set to : 0
,D/PersonaManager( 1015): isKioskContainerExistOnDevice
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/InputDispatcher( 1015): Focused application set to: xxxx
D/InputDispatcher( 1015): Focus left window: 1489
,E/MTPRx   ( 4759): started activity for popup
,D/WindowOrientationListener( 1015):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
,W/ResourcesManager( 4759): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 4759): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4759): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4759): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4759): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4759): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 4759): PREF_DONT_ASK_AGAIN : true
,D/FocusedStackFrame( 1015): Set to : 0
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/InputDispatcher( 1015): Focused application set to: xxxx
,D/InputDispatcher( 1015): Focus entered window: 1489
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
,D/InputMethodManagerService( 1015): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService( 1015): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@2fe74a64 attribute=null, token = android.os.BinderProxy@349f23ed
,D/SettingsReceiverActivity( 4759): dev.kiessupport is : TRUE
,D/PhoneWindow( 4759): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 4759): *FMB* installDecor flags : 8388610
,E/Watchdog( 1015): !@Sync 3
,I/Atfwd_Sendcmd(  321): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  321): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  291): DCD OFF
,W/ActivityManager( 1015): mDVFSHelper.release()
,D/SSRM:n  ( 1015): SIOP:: AP = 310
,E/SMD     (  291): DCD OFF,
,V/AlarmManager( 1015): waitForAlarm result :4,
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,V/AlarmManager( 1015): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManagerEXT( 1015): <AppSync3 Whitelist>
,V/AlarmManagerEXT( 1015): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1173): handleTimeUpdate
,D/SecKeyguardClockView( 1173): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
,D/SecKeyguardClockView( 1173): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1173): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1173): *** don't update sliding image ***
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1698): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1698): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1698): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1698): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4857): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4857): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4857): [1] 5.onFinished: Scheduling replication attempt 3.
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4251, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 1015): stay LED for charging
,I/MotionRecognitionService( 1015): Plugged,
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,D/WindowOrientationListener( 1015):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,E/SMD     (  291): DCD OFF,
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 300,
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4255, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): Plugged
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
,I/ServiceManager(  321): Waiting for service AtCmdFwd...,
,I/PowerManagerService( 1015): [PWL] Off : 75s ago,
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  321): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 300
,V/AlarmManager( 1015): waitForAlarm result :4
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1698): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1698): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1698): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1698): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4857): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4857): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4857): [1] 5.onFinished: Scheduling replication attempt 4.
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4256, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1015): !@Sync 4
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,I/ServiceManager(  321): Waiting for service AtCmdFwd...,
E/SMD     (  291): DCD OFF
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4257, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
,V/AlarmManager( 1015): waitForAlarm result :8
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,V/AlarmManager( 1015): waitForAlarm result :4
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): retrieveServiceLocked(): component = flipboard.app/flipboard.gcm.FlipboardGCMIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = flipboard.app, destAppInfo.processName = flipboard.app
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = flipboard.app, destAppInfo.processName = com.google.process.gapps
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1698): GcmService start Intent { act=com.google.android.c2dm.intent.UNREGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.UNREGISTER
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1698): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10012
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = flipboard.app
,D/ActivityManager( 1015): retrieveServiceLocked(): component = flipboard.app/flipboard.gcm.FlipboardGCMIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = flipboard.app, destAppInfo.processName = flipboard.app
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1698): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1698): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1698): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1698): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4857): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4857): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4857): [1] 5.onFinished: Scheduling replication attempt 5.
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4255, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/PowerManagerService( 1015): [PWL] Off : 105s ago
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  321): Waiting for service AtCmdFwd...,
,V/AlarmManager( 1015): waitForAlarm result :8
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,I/ServiceManager(  321): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4258, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 1015): stay LED for charging
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1015): !@Sync 5
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,E/SMD     (  291): DCD OFF,
,V/AlarmManager( 1015): waitForAlarm result :4
,D/NtpTrustedTime( 1015): forceRefresh() from cache miss
,D/EnterpriseController(  278): uids 1000
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 1000
,D/EnterpriseController(  278): uids 1000
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0,
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 1000
D/NtpTrustedTime( 1015): forceRefresh Fail.,
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10012
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1173): handleTimeUpdate
,D/SecKeyguardClockView( 1173): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1173): HomeTimezone(): 1
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/SecKeyguardStatusUtils( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1173): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1173): *** don't update sliding image ***
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1015): userId = 0, bbcId = -10000,
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1698): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1698): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1698): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1698): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4857): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.,
D/Finsky  ( 4857): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4857): [1] 5.onFinished: Giving up after 6 failures.
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4256, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.,
D/BatteryService( 1015): stay LED for charging
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 290,
,I/ServiceManager(  321): Waiting for service AtCmdFwd...,
,I/ServiceManager(  321): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  321): Waiting for service AtCmdFwd...,
,I/ServiceManager(  321): Waiting for service AtCmdFwd...,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4260, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  291): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 140s ago
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1015): !@Sync 6
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 290,
,I/Atfwd_Sendcmd(  321): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  321): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4261, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1015): Plugged
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,V/AlarmManager( 1015): waitForAlarm result :8
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4261, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/Watchdog( 1015): !@Sync 7,
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  291): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 180s ago
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,V/AlarmManager( 1015): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1173): handleTimeUpdate
,D/NtpTrustedTime( 1015): forceRefresh() from cache miss
,D/SecKeyguardClockView( 1173): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
D/EnterpriseController(  278): uids 1000
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 1000
,D/SecKeyguardClockView( 1173): HomeTimezone(): 1,
D/EnterpriseController(  278): uids 1000
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 1000
D/NtpTrustedTime( 1015): forceRefresh Fail.
,D/SecKeyguardStatusUtils( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1173): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1173): *** don't update sliding image ***
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  321): Waiting for service AtCmdFwd...,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1015): SIOP:: AP = 280,
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1015): waitForAlarm result :8
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1015): !@Sync 8
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 270
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1015): SIOP:: AP = 270,
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 4
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4261, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/PowerManagerService( 1015): [PWL] Off : 225s ago
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,V/AlarmManager( 1015): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1173): handleTimeUpdate
,D/SecKeyguardClockView( 1173): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1173): HomeTimezone(): 1
,D/ActivityManager( 1015): retrieveServiceLocked(): component = flipboard.app/flipboard.gcm.FlipboardGCMIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = flipboard.app, destAppInfo.processName = flipboard.app
,D/SecKeyguardStatusUtils( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1173): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1173): *** don't update sliding image ***
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = flipboard.app, destAppInfo.processName = com.google.process.gapps
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/GCM     ( 1698): GcmService start Intent { act=com.google.android.c2dm.intent.UNREGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.UNREGISTER
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1698): (HTTPLog)-Static: isSBSettingEnabled false
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10012
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = flipboard.app
,D/ActivityManager( 1015): retrieveServiceLocked(): component = flipboard.app/flipboard.gcm.FlipboardGCMIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = flipboard.app, destAppInfo.processName = flipboard.app
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 1015): SIOP:: AP = 270
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4258, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): stay LED for charging
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.,
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate,
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1015): !@Sync 9
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 270,
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  321): Waiting for service AtCmdFwd...,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4261, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate,
,D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false,
V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 270
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 270
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService( 1015): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1015): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1015): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1015): initializing...
,I/TLC_TIMA_PKM_initialize( 1015): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1015): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1015): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1015): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1015): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1015): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1015): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1015): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: ( 1015): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1015): Loaded image: APP id = 9
,I/TZ: qc_tlc_communication( 1015): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1015): Trustlet response is completed
,E/SMD     (  291): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4257, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1015): stay LED for charging
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1015): Plugged,
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1015): !@Sync 10
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 270
,I/Atfwd_Sendcmd(  321): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  321): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  291): DCD OFF,
,I/PowerManagerService( 1015): [PWL] Off : 275s ago
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4261, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :4
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10012
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,V/AlarmManager( 1015): waitForAlarm result :8
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1015): SIOP:: AP = 270
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4261, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1015): !@Sync 11
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1698): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1698): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1698): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1698): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1015): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1015): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found,
W/GLSActivity( 1698): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1698): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1698): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1698): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1698): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1698): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1698): 	at android.os.Binder.execTransact(Binder.java:461)
,E/PlayEventLogger( 4857): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4857): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4857): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 4857): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4857): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 4857): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4857): 	at android.os.Binder.execTransact(Binder.java:461)
,W/System  ( 4857): Ignoring header User-Agent because its value was null.
I/System.out( 4857): (HTTPLog)-Static: isSBSettingEnabled false
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1173): isKioskContainerExistOnDevice
,D/PersonaManager( 1173): isKioskContainerExistOnDevice
,D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): kidsfalse mQsExpansionEnabled:true
,D/EnterpriseController(  278): uids 10028
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10028
,D/PersonaManager( 1173): isKioskContainerExistOnDevice
,D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): kidsfalse mQsExpansionEnabled:true
,D/PanelView( 1173): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 270,
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 2
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 270,
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 270
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1015): !@Sync 12
,E/SMD     (  291): DCD OFF,
,I/PowerManagerService( 1015): [PWL] Off : 330s ago
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 270
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 270,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 270
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1015): !@Sync 13
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 270,
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 270
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4261, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): Plugged
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1015): !@Sync 14
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/Atfwd_Sendcmd(  321): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  321): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  291): DCD OFF,
,I/PowerManagerService( 1015): [PWL] Off : 390s ago,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1015): !@Sync 15
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 2
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1173): handleTimeUpdate
,D/ActivityManager( 1015): retrieveServiceLocked(): component = flipboard.app/flipboard.gcm.FlipboardGCMIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = flipboard.app, destAppInfo.processName = flipboard.app
,D/SecKeyguardClockView( 1173): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1173): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1173): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1173): *** don't update sliding image ***
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = flipboard.app, destAppInfo.processName = com.google.process.gapps
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1698): GcmService start Intent { act=com.google.android.c2dm.intent.UNREGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.UNREGISTER
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/System.out( 1698): (HTTPLog)-Static: isSBSettingEnabled false
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10012
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = flipboard.app
,D/ActivityManager( 1015): retrieveServiceLocked(): component = flipboard.app/flipboard.gcm.FlipboardGCMIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = flipboard.app, destAppInfo.processName = flipboard.app
,D/SecKeyguardStatusUtils( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/bootchecker(  318): bootchecker wake up!!
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF,
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 3
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4258, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged,
D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 270
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1015): !@Sync 16
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4261, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1015): [PWL] Off : 455s ago
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :8,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1015): !@Sync 17
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 5,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1015): !@Sync 18
,I/Atfwd_Sendcmd(  321): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  321): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 525s ago
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/Atfwd_Daemon(  321): Stop the daemon....,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1015): !@Sync 19
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4261, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4262, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService( 1015): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 1015): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1015): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
D/TimaService( 1015): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1015): !@Sync 20
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4261, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged,
D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate,
V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4262, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4261, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged,
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1015): !@Sync 21
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0,
,V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1698): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1698): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1698): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1698): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1015): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1015): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/GLSActivity( 1698): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1698): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1698): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1698): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1698): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1698): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1698): 	at android.os.Binder.execTransact(Binder.java:461)
,E/PlayEventLogger( 4857): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4857): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4857): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 4857): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4857): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 4857): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4857): 	at android.os.Binder.execTransact(Binder.java:461)
,W/System  ( 4857): Ignoring header User-Agent because its value was null.
I/System.out( 4857): (HTTPLog)-Static: isSBSettingEnabled false
D/PersonaManager( 1173): isKioskContainerExistOnDevice
D/PersonaManager( 1173): isKioskContainerExistOnDevice
,D/PanelView( 1173): There is/are notification(s) 
D/EnterpriseController(  278): uids 10028
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10028
D/PanelView( 1173): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1173): isKioskContainerExistOnDevice
D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): kidsfalse mQsExpansionEnabled:true
,D/PanelView( 1173): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 600s ago,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4262, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): Plugged
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1015): !@Sync 22
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4261, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1015): Plugged
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4262, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false,
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1015): !@Sync 23
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4261, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1015): Plugged
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4262, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 680s ago
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1015): !@Sync 24
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4261, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1015): !@Sync 25,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4262, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1015): !@Sync 26,
,V/AlarmManager( 1015): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1173): handleTimeUpdate
,D/SecKeyguardClockView( 1173): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1173): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1173): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1173): *** don't update sliding image ***
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10012
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4260, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 765s ago
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4262, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  291): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :8
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1015): !@Sync 27
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1015): !@Sync 28
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4262, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1015): !@Sync 29,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4260, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 855s ago
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4262, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/TimaService( 1015): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 1015): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1015): TimaServiceHandler.handleMessage what =1
,E/SMD     (  291): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1015): !@Sync 30
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1015): !@Sync 31
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1698): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1698): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1698): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1698): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1015): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1015): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/GLSActivity( 1698): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1698): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1698): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1698): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1698): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1698): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1698): 	at android.os.Binder.execTransact(Binder.java:461)
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
E/PlayEventLogger( 4857): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4857): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4857): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 4857): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4857): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 4857): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4857): 	at android.os.Binder.execTransact(Binder.java:461)
,W/System  ( 4857): Ignoring header User-Agent because its value was null.
I/System.out( 4857): (HTTPLog)-Static: isSBSettingEnabled false
,D/PersonaManager( 1173): isKioskContainerExistOnDevice
D/PersonaManager( 1173): isKioskContainerExistOnDevice
D/EnterpriseController(  278): uids 10028
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10028
,D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1173): isKioskContainerExistOnDevice
,D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): kidsfalse mQsExpansionEnabled:true
,D/PanelView( 1173): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4258, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4262, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1015): Plugged
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4261, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1015): !@Sync 32,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4262, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): Plugged
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate,
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1173): handleTimeUpdate
,D/ActivityManager( 1015): retrieveServiceLocked(): component = flipboard.app/flipboard.gcm.FlipboardGCMIntentService; callingUser = 0; userId(target) = 0
,D/SecKeyguardClockView( 1173): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = flipboard.app, destAppInfo.processName = flipboard.app
,D/SecKeyguardClockView( 1173): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1173): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1173): *** don't update sliding image ***
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = flipboard.app, destAppInfo.processName = com.google.process.gapps
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1698): GcmService start Intent { act=com.google.android.c2dm.intent.UNREGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.UNREGISTER
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1698): (HTTPLog)-Static: isSBSettingEnabled false
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10012
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = flipboard.app
,D/ActivityManager( 1015): retrieveServiceLocked(): component = flipboard.app/flipboard.gcm.FlipboardGCMIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = flipboard.app, destAppInfo.processName = flipboard.app
,D/SecKeyguardStatusUtils( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4258, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4260, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged,
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,V/AlarmManager( 1015): waitForAlarm result :8
,I/PowerManagerService( 1015): [PWL] Off : 950s ago
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1015): !@Sync 33,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4262, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4261, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1015): !@Sync 34,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4262, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4260, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4262, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): stay LED for charging,
D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.,
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1015): !@Sync 35,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4261, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): Plugged
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate,
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4260, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged,
D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate,
V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1015): !@Sync 36,
,E/SMD     (  291): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 1050s ago
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4261, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false,
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4261, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4260, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1015): !@Sync 37
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4262, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4260, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged,
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate,
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1015): !@Sync 38
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:99, scale:100, status:2, health:2, present:true, voltage: 4262, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/PowerManagerService( 1015): [PSM] lowPowerModeEnabled: false (mLowPowerModeSetting: false, mAutoLowPowerModeConfigured: false, mBatteryLevel: 99, mLowBatteryTriggerLevel: 0)
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/SecKeyguardStatusUtils( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 99
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1015): !@Sync 39
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:99, scale:100, status:2, health:2, present:true, voltage: 4260, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 99
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 1155s ago,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:99, scale:100, status:2, health:2, present:true, voltage: 4258, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 99
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/TimaService( 1015): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1015): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1015): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 1015): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 1015): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 1015): Updating Usage Statistics in DB @ 1454093073978
,I/ApplicationUsage( 1015): Done Updating Usage Statistics in DB @ 1454093073984
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1015): !@Sync 40
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:99, scale:100, status:2, health:2, present:true, voltage: 4262, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 99
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1015): !@Sync 41,
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1698): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1698): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1698): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1698): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1015): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1015): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1173): isKioskContainerExistOnDevice
D/PersonaManager( 1173): isKioskContainerExistOnDevice
,D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): kidsfalse mQsExpansionEnabled:true
,W/GLSActivity( 1698): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1698): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1698): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1698): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1698): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1698): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1698): 	at android.os.Binder.execTransact(Binder.java:461)
D/PersonaManager( 1173): isKioskContainerExistOnDevice
D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): kidsfalse mQsExpansionEnabled:true
,E/PlayEventLogger( 4857): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4857): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4857): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 4857): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4857): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 4857): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4857): 	at android.os.Binder.execTransact(Binder.java:461)
,W/System  ( 4857): Ignoring header User-Agent because its value was null.
I/System.out( 4857): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): uids 10028
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10028
,D/PanelView( 1173): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:99, scale:100, status:2, health:2, present:true, voltage: 4256, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
D/BatteryService( 1015): stay LED for charging
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false,
V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 99
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:99, scale:100, status:2, health:2, present:true, voltage: 4262, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 99
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1015): !@Sync 42
,E/SMD     (  291): DCD OFF,
,TIME-OUT KILL (timeout was 1200000ms),E/SMD     (  291): DCD OFF
D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:99, scale:100, status:2, health:2, present:true, voltage: 4261, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for charging
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): Plugged
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 99
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
D/SSRM:n  ( 1015): SIOP:: AP = 260
D/AndroidRuntime( 6237): 
D/AndroidRuntime( 6237): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6237): CheckJNI is OFF
D/AndroidRuntime( 6237): readGMSProperty: start
D/AndroidRuntime( 6237): readGMSProperty: already setted!!
D/AndroidRuntime( 6237): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6237): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6237): readGMSProperty: end
D/AndroidRuntime( 6237): addProductProperty: start
E/AffinityControl( 6237): AffinityControl: registerfunction enter
D/AndroidRuntime( 6237): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 1015): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1015): START PACKAGE DELETE: observer{41699504}
D/PackageManager( 1015): pkg{<packageName>}
D/PackageManager( 1015): user{0}
D/PackageManager( 1015): caller{2000}
D/PackageManager( 1015): flags{3}
D/PersonaManagerService( 1015): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1015): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1015): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1015): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1015): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1015): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1015): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/PackageManager( 1015): !@killApplicatoin: 10174, uninstall pkg
D/ApplicationPolicy( 1015): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1015): getApplicationUninstallationEnabled :  enabled true
I/ActivityManager( 1015): Force stopping com.test.thalitest appid=10174 user=-1: uninstall pkg
I/ActivityManager( 1015): Killing 5498:com.test.thalitest/u0a174 (adj 15): stop com.test.thalitest cause uninstall pkg
I/ActivityManager( 1015): Force stopping com.test.thalitest appid=10174 user=0: pkg removed
W/ActivityManager( 1015): CustomStartingWindow se packge removed so remove capture also
I/InputReader( 1015): Reconfiguring input devices.  changes=0x00000010
I/art     ( 3695): Explicit concurrent mark sweep GC freed 15989(949KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 6MB/11MB, paused 1.959ms total 59.940ms
E/SamsungIME( 1773): mOCRHelper is null
W/GeofencerStateMachine( 1679): Ignoring removeGeofence because network location is disabled.
I/KLMS-2.5.183: ( 3465): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jan 29 19:45:43 GMT+01:00 2016
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
I/art     ( 5518): Explicit concurrent mark sweep GC freed 29349(2MB) AllocSpace objects, 1(18KB) LOS objects, 24% free, 8MB/11MB, paused 1.385ms total 102.321ms
D/RegisteredComponentCache( 1448): Collect Tech packages for Knox
D/PersonaManager( 1448): isKioskContainerExistOnDevice
E/SMD     (  291): DCD OFF
I/KLMS-2.5.183: ( 3465): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 1015): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=28
I/splitIntent( 1015): base  index=28, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1015): other index=31, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1015): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6250): MountEmulatedStorage()
E/Zygote  ( 6250): v2
I/libpersona( 6250): KNOX_SDCARD checking this for 10094
I/libpersona( 6250): KNOX_SDCARD not a persona
I/SELinux ( 6250): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/KLMS-2.5.183: ( 3465): KLMSIntentService(): onCreate()
I/ActivityManager( 1015): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6250 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 6250): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/KLMS-2.5.183: ( 3465): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
E/SELinux ( 6250): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.5.183: ( 3465): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1015): mCursor = null
I/KLMS-2.5.183: ( 3465): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
D/TimaKeyStoreProvider( 6250): TimaSignature is unavailable
D/ActivityThread( 6250): Added TimaKeyStore provider
I/KLMS-2.5.183: ( 3465): KLMSIntentService(): PACKAGE_REMOVED
I/KLMS-2.5.183: ( 3465): KLMSIntentService(): listeningToPackageRemoved().START
I/KLMS-2.5.183: ( 3465): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
I/art     ( 1015): Explicit concurrent mark sweep GC freed 38122(4MB) AllocSpace objects, 143(2MB) LOS objects, 33% free, 27MB/40MB, paused 8.323ms total 245.647ms
I/art     ( 1015): WaitForGcToComplete blocked for 106.938ms for cause Explicit
D/PersonaManager( 1448): isKioskContainerExistOnDevice
D/RegisteredServicesCache( 1448): empty dynamic service
I/KLMS-2.5.183: ( 3465): KLMSIntentService(): listeningToPackageRemoved().END
I/KLMS-2.5.183: ( 3465): KLMSIntentService(): onDestroy()
D/elm:15183( 6250): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15183( 6250): ELMEngine.ELMEngine( context ).
D/elm:15183( 6250): MDMBridge.setEnterpriseBridge()
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
D/elm:15183( 6250): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:15183( 6250): ElmAgentService : onCreate()
D/elm:15183( 6250): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15183( 6250): MainReceiver.listeningToPackageRemoved()
D/elm:15183( 6250): MDMBridge.getInstance()
D/elm:15183( 6250): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:15183( 6250): MDMBridge.getAllLicenseInfoFromSDK()
D/RCPManagerService( 1015): PackageReceiver onReceive()
I/HarmonyEASService( 1015): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy( 1015): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1015): PackageRemovalReceiver::onReceive Enter
D/OTPFW   ( 1015): OtpDbHelper::getInstance New instance created
D/OTPFW   ( 1015): DBIntegrity::getInstance - New instance created
D/OTPFW   ( 1015): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10174 container id = 0
I/OTPFW   ( 1015): ProvisionData::getAllEntries Enter
E/OTPFW   ( 1015): ProvisionData::getAllEntries Table is empty
D/BackupManagerService( 1015): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
D/JobSchedulerService( 1015): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1015): uID is 10174
V/EnterpriseBillingPolicy( 1015): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - end - null
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/elm:15183( 6250): ElmAgentService : onDestroy().
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1015): uID is 10174
V/EnterpriseBillingPolicy( 1015): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - end - null
D/TaskPersister( 1015): removeObsoleteFile: deleting file=233_task.xml
D/SSRM:aZ ( 1015): MSG_TYPE_APP_REMOVED::
I/PCWCLIENTTRACE_PushUtil( 5175): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5175): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5175): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5175): [onReceive] - android.intent.action.PACKAGE_REMOVED
I/SA      ( 5410): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
I/SA      ( 5410): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10174 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
I/PackagesMonitor( 4480): PackagesMonitor onReceive :com.test.thalitest
D/EnterpriseDeviceManagerService( 1015): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1015): Admin package name: com.google.android.gms
I/art     ( 1015): Explicit concurrent mark sweep GC freed 12519(732KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/40MB, paused 5.488ms total 198.715ms
W/TextServicesManagerService( 1015): no available spell checker services found
D/Mms/FreeMessageStatusReceiver( 5127): onReceive, action : android.intent.action.PACKAGE_REMOVED
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
I/TactileAssist( 1015): enable value -1
I/TactileAssist( 1015): internal enable value -1
I/TactileAssist( 1015): intensity value -1
I/TactileAssist( 1015): saveAppList value true
D/Mms/FreeMessageReceiverService( 5127): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 5127): onHandleIntent: ACTION_PACKAGE_REMOVED
I/TactileAssist( 1015): List of disabled apps :
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/PackageManager( 1015): delete codoeFile: 
D/Compatibility( 5367): onReceive() it will make start service
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/AASAuninstall( 1015): userId = 0, info.removedAppID = -1, info.uid = 10174, packageName = com.test.thalitest
I/AASA_removePackage( 1015): UID=10174 Target=com.test.thalitest
D/PackageManager( 1015): result of delete: 1{41699504}
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/Compatibility( 5367): onHandleIntent()
D/AndroidRuntime( 6237): Shutting down VM
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/Compatibility( 5367): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10174, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/Compatibility( 5367): found: 2
D/Compatibility( 5367): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5367): skipping ResolveInfo{1d85b79d com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5367): considering ResolveInfo{304f3412 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5367): default: com.sec.android.app.soundalive.SAControlPanelActivity
I/libpersona( 6270): KNOX_SDCARD checking this for 10003
D/Compatibility( 5367): enabling receiver ResolveInfo{b82d7e3 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
I/libpersona( 6270): KNOX_SDCARD not a persona
E/Zygote  ( 6270): MountEmulatedStorage()
E/Zygote  ( 6270): v2
I/SELinux ( 6270): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6270): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6270): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6270 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
D/Compatibility( 5367): enabling receiver ResolveInfo{210f45e0 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 5367): enabling receiver ResolveInfo{260b3099 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 5367): enabling receiver ResolveInfo{ae87f5e com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/TimaKeyStoreProvider( 6270): TimaSignature is unavailable
D/ActivityThread( 6270): Added TimaKeyStore provider
D/Compatibility( 5367): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
D/UserAnalysis.PlaceProvider( 6270): PlaceProvider onCreate()
W/ResourceType( 1015): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ResourcesManager( 1015): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1015): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1015): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/UserAnalysis.SecureDbManager( 6270): Key for secure DB is newly created
D/UserAnalysis.SecurePlaceDbHelper( 6270): SecurePlaceDbHelper() 
D/UserAnalysis( 6270): Create SecureDbHelper
D/IntelligenceServiceApplication( 6270): onCreate()
D/UserAnalysis.UserAnalysisBroadcastReceiver( 6270): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
W/ContextImpl( 5392): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
D/IntelligenceServiceApplication( 6270): no applications having user consent for prediction
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
V/PlaceDetection v1.0.19 ( 6270): [PlaceDetection::stopService] Service stopped.
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/RCPManager( 5447):  in createShortcut() for packageName: com.test.thalitest userId0
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
V/PlaceDetection v1.0.19 ( 6270): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
D/RCPManagerService( 1015):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1015): queryAllProviders():  providerCallBack is not register for 0
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
E/Zygote  ( 6287): MountEmulatedStorage()
E/Zygote  ( 6287): v2
I/libpersona( 6287): KNOX_SDCARD checking this for 10100
I/libpersona( 6287): KNOX_SDCARD not a persona
I/SELinux ( 6287): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
V/PlaceDetection v1.0.19 ( 6270): [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
V/PlaceDetection v1.0.19 ( 6270): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
V/PlaceDetection v1.0.19 ( 6270): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
V/PlaceDetection v1.0.19 ( 6270): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 6270): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 6270): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 6270): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 6270): [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
V/PlaceDetection v1.0.19 ( 6270): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
I/ActivityManager( 1015): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=6287 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/SELinux ( 6287): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
V/PlaceDetection v1.0.19 ( 6270): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
V/PlaceDetection v1.0.19 ( 6270): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 6270): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
E/SELinux ( 6287): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/PlaceDetection v1.0.19 ( 6270): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 6270): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 6270): [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
V/PlaceDetection v1.0.19 ( 6270): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
I/ActivityManager( 1015): Killing 5157:com.samsung.helphub/1000 (adj 15): empty #31
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
V/PlaceDetection v1.0.19 ( 6270): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
V/PlaceDetection v1.0.19 ( 6270): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 6270): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 6270): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 6270): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 6270): [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
V/PlaceDetection v1.0.19 ( 6270): [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
V/PlaceDetection v1.0.19 ( 6270): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
D/BluetoothAdapter( 6270): 121189226: getState() :  mService = null. Returning STATE_OFF
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
V/PlaceDetection v1.0.19 ( 6270): [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
V/PlaceDetection v1.0.19 ( 6270): [PlaceDetection::stopService] Service stopped.
V/PlaceDetection v1.0.19 ( 6270): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
D/UsbSettingsManager( 1015): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 1015): onPackageRemoved : com.test.thalitest
D/TimaKeyStoreProvider( 6287): TimaSignature is unavailable
D/ActivityThread( 6287): Added TimaKeyStore provider
I/ActivityManager( 1015): Killing 5209:com.policydm/1000 (adj 15): empty #31
E/JavaBinder( 1015): !!! FAILED BINDER TRANSACTION !!!
W/art     ( 6237): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
W/BroadcastQueue( 1015): Exception when sending broadcast to ComponentInfo{com.samsung.helphub/com.samsung.helphub.broadcast.HelpHubBroadcastReceiver}
W/BroadcastQueue( 1015): android.os.TransactionTooLargeException
W/BroadcastQueue( 1015): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue( 1015): 	at android.os.BinderProxy.transact(Binder.java:511)
W/BroadcastQueue( 1015): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
W/BroadcastQueue( 1015): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:309)
W/BroadcastQueue( 1015): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1236)
W/BroadcastQueue( 1015): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20387)
W/BroadcastQueue( 1015): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
W/BroadcastQueue( 1015): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3368)
W/BroadcastQueue( 1015): 	at android.os.Binder.execTransact(Binder.java:461)
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6302): MountEmulatedStorage()
I/ActivityManager( 1015): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=6302 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 6302): v2
I/libpersona( 6302): KNOX_SDCARD checking this for 1000
I/libpersona( 6302): KNOX_SDCARD not a persona
I/SELinux ( 6302): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6302): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6302): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6302): TimaSignature is unavailable
D/ActivityThread( 6302): Added TimaKeyStore provider
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5157/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5209/cgroup.procs: No such file or directory
E/SQLiteLog( 6302): (28) failed to open "/data/data/com.samsung.helphub/databases/search.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 6302): Failed to open database '/data/data/com.samsung.helphub/databases/search.db'.
E/SQLiteDatabase( 6302): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6302): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6302): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6302): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6302): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6302): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6302): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6302): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6302): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6302): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6302): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6302): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6302): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6302): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 6302): 	at com.samsung.helphub.search.SearchProvider.onCreate(SearchProvider.java:63)
E/SQLiteDatabase( 6302): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
E/SQLiteDatabase( 6302): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
E/SQLiteDatabase( 6302): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/SQLiteDatabase( 6302): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
E/SQLiteDatabase( 6302): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
E/SQLiteDatabase( 6302): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteDatabase( 6302): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteDatabase( 6302): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6302): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6302): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6302): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6302): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6302): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6302): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper( 6302): Couldn't open search.db for writing (will try read-only):
E/SQLiteOpenHelper( 6302): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 6302): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 6302): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 6302): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 6302): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 6302): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 6302): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 6302): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteOpenHelper( 6302): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteOpenHelper( 6302): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 6302): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteOpenHelper( 6302): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 6302): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 6302): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 6302): 	at com.samsung.helphub.search.SearchProvider.onCreate(SearchProvider.java:63)
E/SQLiteOpenHelper( 6302): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
E/SQLiteOpenHelper( 6302): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
E/SQLiteOpenHelper( 6302): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/SQLiteOpenHelper( 6302): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
E/SQLiteOpenHelper( 6302): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
E/SQLiteOpenHelper( 6302): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteOpenHelper( 6302): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteOpenHelper( 6302): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 6302): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 6302): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteOpenHelper( 6302): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 6302): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 6302): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 6302): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper( 6302): Opened search.db in read-only mode
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6318): MountEmulatedStorage()
E/Zygote  ( 6318): v2
I/libpersona( 6318): KNOX_SDCARD checking this for 1000
I/libpersona( 6318): KNOX_SDCARD not a persona
I/SELinux ( 6318): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6318): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1015): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6318 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 5226:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
E/SELinux ( 6318): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6318): TimaSignature is unavailable
D/ActivityThread( 6318): Added TimaKeyStore provider
W/ContextImpl( 6318): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0

```
