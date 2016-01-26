#### Test 5667282762e056f_thali07_samsung-SM-A500FU Logs


```
--------- beginning of main
D/Mms/Contact( 5150): [end]    init consume time = 14.456407
D/Mms/DraftCache( 5150): [start]    rebuildCache consume time = 9.111354
D/Mms/MethodReflector( 5150): getSubId is called
D/Mms/TelephonyUtils( 5150): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 5150): getTelephonyProperty is called
D/Mms/DownloadManager( 5150): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5150): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5150): auto download without roaming -> true
D/Mms/DownloadManager( 5150): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/MethodReflector( 5150): getSubId is called
D/Mms/MethodReflector( 5150): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 5150): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 5150): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 5150): getTelephonyProperty is called
D/Mms/DownloadManager( 5150): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 5150): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 5150): auto download without roaming -> true
D/Mms/DownloadManager( 5150): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 5150): auto download during roaming secondary -> false
D/Mms/DownloadManager( 5150): mAutoDownload ------> true
D/TP/MmsSmsProvider( 1465): query,matched:12, calling pid = 5150
D/TP/MmsSmsProvider( 1465): match 12:Elapsed time : 0.894 ms
D/Mms/DraftCache( 5150): [end]    rebuildCache consume time = 11.269844
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ComposerPerformance( 5150): 1453830948937 ms / [DONE] Composer constructor
E/CII     ( 5150): CommonIMSInterface: VoLTE CSC feature disabled.
I/Mms/ReservationManager( 5150): ReservationManager()
I/Mms/ReservationManager( 5150): resetAfterConnected()
D/TP/MmsSmsProvider( 1465): query,matched:7, calling pid = 5150
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TP/MmsSmsProvider( 1465): match 7:Elapsed time : 2.775 ms
--------- beginning of system
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
I/Mms/ReservationManager( 5150): getReservedSendMessageCount(): retMessageCount=0
D/Mms/MmsApp( 5150): [end]    onCreate() consume time = 23.584687
D/Mms/Conversation( 5150): [start]    init() consume time = 2.285625
W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/TP/MmsSmsProvider( 1465): deleteConversation threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1465): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1465): updateThread(), thread_id = 9223372036854775807
D/Mms/ArtClassLoader( 5150): init [DONE] art
V/TP/MmsSmsDatabaseHelper( 1465): sUpgradeVersion = 0, db.getVersion() = 81
D/TP/MmsSmsProvider( 1465): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1465): need read changed broadcast:false
D/Mms/DownloadManager( 5150): Service state changed: Bundle[mParcelledData.dataSize=744]
D/Mms/DownloadManager( 5150): roaming ------> false, mSimSlot = 0
D/Mms/Conversation( 5150): [end]    init consume time = 27.896771
D/Mms/MethodReflector( 5150): getSubId is called
D/Mms/TelephonyUtils( 5150): getLongSubId from simSlot 0, return Value = -1
D/Mms/MessagingNotification( 5150): [start]    init() consume time = 1.187396
D/Mms/MethodReflector( 5150): getTelephonyProperty is called
D/Mms/DownloadManager( 5150): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5150): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5150): auto download without roaming -> true
D/Mms/DownloadManager( 5150): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5150): mAutoDownload ------> true
D/Mms/MessagingNotification( 5150): [end]    init consume time = 4.440208
D/Mms/SpamFilter( 5150): [start]    SpamFilter fill() begin consume time = 5.297344
D/TP/MmsSmsProvider( 1465): query,matched:400, calling pid = 5150
D/TP/MmsSmsProvider( 1465): query,matched:0, calling pid = 5150
V/TP/MmsSmsProvider( 1465): getSimpleConversations entered.
D/TP/MmsSmsProvider( 1465): match 0:Elapsed time : 1.055 ms
D/Mms/SpamFilter( 5150): [end]    SpamFilter fill() finished consume time = 11.410833
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5309): MountEmulatedStorage()
D/Mms/Synchronizer( 5150): [start]    doSync consume time = 17.038958
E/Zygote  ( 5309): v2
I/libpersona( 5309): KNOX_SDCARD checking this for 10072
I/libpersona( 5309): KNOX_SDCARD not a persona
I/SELinux ( 5309): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5309): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5309 uid=10072 gids={50072, 9997} abi=armeabi-v7a
E/SELinux ( 5309): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/Mms/FreeMessageStatusReceiver( 5150): onReceive, action : android.intent.action.PACKAGE_ADDED
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
I/art     (  308): Explicit concurrent mark sweep GC freed 8726(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 625us total 23.358ms
D/TP/MmsSmsProvider( 1465): update, matched:300, calling pid = 5150
V/TP/MmsSmsProvider( 1465): syncDBData start
V/TP/MmsSmsProvider( 1465): syncDBData sms end
V/TP/MmsSmsProvider( 1465): syncDBData mms end
V/TP/MmsSmsProvider( 1465): syncDBData end
D/Mms/Synchronizer( 5150): [end]    doSync consume time = 30.248542
D/TimaKeyStoreProvider( 5309): TimaSignature is unavailable
D/ActivityThread( 5309): Added TimaKeyStore provider
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 614us total 20.498ms
D/BadgeProvider( 5309): onCreate
D/BadgeProvider( 5309): DatabaseHelper
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 612us total 17.178ms
E/Zygote  ( 5324): MountEmulatedStorage()
E/Zygote  ( 5324): v2
I/libpersona( 5324): KNOX_SDCARD checking this for 10047
I/libpersona( 5324): KNOX_SDCARD not a persona
I/SELinux ( 5324): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5324): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5324 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
E/SELinux ( 5324): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/Mms/FreeMessageReceiverService( 5150): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 5150): onHandleIntent: ACTION_PACKAGE_ADDED
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ConfigFetchService( 1886): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ActivityManager( 1017): Killing 3419:com.android.providers.calendar/u0a42 (adj 15): empty #31
I/ActivityManager( 1017): Killing 4568:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #32
I/ConfigFetchService( 1886): launchTask
D/Mms/MessagingNotification( 5150): checkBadgeCount unreadCount=0 badgeCount=0
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
D/TimaKeyStoreProvider( 5324): TimaSignature is unavailable
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityThread( 5324): Added TimaKeyStore provider
D/ChimeraCfgMgr( 1886): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1886): Module APK com.google.android.play.games already loaded
D/TP/SmsProvider( 1465): query,matched:26, calling pid = 5150
D/TP/SmsProvider( 1465): match 26:Elapsed time : 2.371 ms
I/DBG_POLICYDM( 5231): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
I/DBG_POLICYDM( 5231): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
I/DBG_POLICYDM( 5231): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
I/DBG_POLICYDM( 5231): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
I/DBG_POLICYDM( 5231): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
W/ResourcesManager( 5324): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5324): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5324): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/DBG_POLICYDM( 5231): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
I/DBG_POLICYDM( 5231): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
D/TP/MmsSmsProvider( 1465): query,matched:6, calling pid = 5150
I/DBG_POLICYDM( 5231): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
D/TP/MmsSmsProvider( 1465): match 6:Elapsed time : 1.656 ms
I/DBG_POLICYDM( 5231): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/data/com.policydm/cache]
I/PeopleContactsSync( 1886): CP2 sync disabled
D/ChimeraCfgMgr( 1886): Loading module com.google.android.gms.vision from APK com.google.android.gms
I/DBG_POLICYDM( 5231): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
I/DBG_POLICYDM( 5231): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
I/DBG_POLICYDM( 5231): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
W/libprocessgroup( 1017): failed to open /acct/uid_10042/pid_3419/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_4568/cgroup.procs: No such file or directory
I/DBG_POLICYDM( 5231): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
I/DBG_POLICYDM( 5231): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
D/Vision  ( 1886): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5347): MountEmulatedStorage()
I/libpersona( 5347): KNOX_SDCARD checking this for 10025
E/Zygote  ( 5347): v2
I/libpersona( 5347): KNOX_SDCARD not a persona
I/SELinux ( 5347): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5347 uid=10025 gids={50025, 9997} abi=armeabi-v7a
I/SELinux ( 5347): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5347): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Vision  ( 1886): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1886): No vision deps
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/DBG_POLICYDM( 5231): [com.policydm.XSPPReceiver(53/onReceive)] ACTION_PACKAGE_ADDED. mPkgName:com.test.thalitest
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
V/ConfigFetchTask( 1886): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1ValWPmTt8y7kwHjah-UWvGF9RGC7nhEy_tb65-E4wTL8KdxfhuZOjahZV0EfouNmoRIGUXO23HiWZeNUXSsWa_RRIfT0EK_Mvi4Ej1HdpxfKer2cIkaSOGr0BgLbqSZqYscP3e8KktSxMRNCwYaNhX9EH6XR3W57kCm_sPGjKBVoZGUQK48jALHTvyuxJzzuPnqiOH-OLlc3kQWqKHsPNFlv7hrqwTeLnDF1PXO3XcNgClnC0
E/Zygote  ( 5364): MountEmulatedStorage()
E/Zygote  ( 5364): v2
I/libpersona( 5364): KNOX_SDCARD checking this for 10038
I/libpersona( 5364): KNOX_SDCARD not a persona
I/SELinux ( 5364): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=5364 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 4359:com.samsung.android.app.mirrorlink/1000 (adj 15): empty #31
I/SELinux ( 5364): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5364): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/GoogleURLConnFactory( 1886): Using platform SSLCertificateSocketFactory
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 5347): TimaSignature is unavailable
D/ActivityThread( 5347): Added TimaKeyStore provider
I/ActivityManager( 1017): Killing 4829:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
D/TimaKeyStoreProvider( 5364): TimaSignature is unavailable
D/ActivityThread( 5364): Added TimaKeyStore provider
I/System.out( 1886): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1886): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1886): (HTTPLog)-Static: isShipBuild true
I/System.out( 1886): (HTTPLog)-Thread-254-1055062135: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1886): (HTTPLog)-Static: isSBSettingEnabled false
D/MyFiles ( 5324): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
W/ResourcesManager( 5347): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5364): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5364): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
E/installd(  286): system dir 0 : /system/app/
E/installd(  286): system dir 1 : /system/priv-app/
E/installd(  286): system dir 2 : /vendor/app/
E/installd(  286): system dir 3 : /oem/app/
I/DBG_POLICYDM( 5231): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 10012
I/DBG_POLICYDM( 5231): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
I/DBG_POLICYDM( 5231): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
W/ConfigFetchTask( 1886): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
E/DBG_POLICYDM( 5231): [com.policydm.agent.XDMTask(174/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized
I/ConfigFetchService( 1886): fetch service done; releasing wakelock
I/ConfigFetchService( 1886): stopping self
I/TactileAssist( 1017): enable value -1
I/TactileAssist( 1017): internal enable value -1
I/TactileAssist( 1017): intensity value -1
I/TactileAssist( 1017): saveAppList value true
I/TactileAssist( 1017): List of disabled apps :
I/OMACP   ( 5347): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/Mms/Omacp( 5150): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
E/Zygote  ( 5383): MountEmulatedStorage()
E/Zygote  ( 5383): v2
I/libpersona( 5383): KNOX_SDCARD checking this for 10053
I/libpersona( 5383): KNOX_SDCARD not a persona
I/SELinux ( 5383): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=5383 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
I/SELinux ( 5383): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5383): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5383): TimaSignature is unavailable
D/ActivityThread( 5383): Added TimaKeyStore provider
W/ResourcesManager( 5383): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
I/OMACP   ( 5347): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
I/OMACP   ( 5347): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
I/OMACP   ( 5347): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
I/OMACP   ( 5347): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
I/OMACP   ( 5347): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
I/OMACP   ( 5347): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
I/GAv4    ( 5165): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5165):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5165):   adb logcat -s GAv4
W/libprocessgroup( 1017): failed to open /acct/uid_10069/pid_4829/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_4359/cgroup.procs: No such file or directory
I/OMACP   ( 5347): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
I/OMACP   ( 5347): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
I/OMACP   ( 5347): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
I/OMACP   ( 5347): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
I/OMACP   ( 5347): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
I/OMACP   ( 5347): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
I/OMACP   ( 5347): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
D/Compatibility( 5383): onReceive() it will make start service
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5400): MountEmulatedStorage()
I/libpersona( 5400): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5400): v2
I/libpersona( 5400): KNOX_SDCARD not a persona
I/SELinux ( 5400): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=5400 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 5400): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5400): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Compatibility( 5383): onHandleIntent()
D/Compatibility( 5383): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10174, android.intent.extra.user_handle=0}]
D/Compatibility( 5383): found: 2
W/GAv4    ( 5165): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
D/TimaKeyStoreProvider( 5400): TimaSignature is unavailable
D/ActivityThread( 5400): Added TimaKeyStore provider
D/Compatibility( 5383): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5383): skipping ResolveInfo{27c28c8d com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5383): considering ResolveInfo{36b6fe42 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5383): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5383): enabling receiver ResolveInfo{366e8e53 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
W/GAv4    ( 5165): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
D/Compatibility( 5383): enabling receiver ResolveInfo{3a21390 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 5383): enabling receiver ResolveInfo{1f586489 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 5383): enabling receiver ResolveInfo{123abc8e com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
W/BaseAppContext( 1886): Using Auth Proxy for data requests.
W/BaseAppContext( 1886): Using Auth Proxy for data requests.
D/Compatibility( 5383): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
W/AnalyticsTrackerProxyImpl( 5165): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
I/ActivityManager( 1017): Killing 4844:com.sec.knox.bridge/1000 (adj 15): empty #31
W/ContextImpl( 5400): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
W/GAv4    ( 5165): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/PackageManager( 1017): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
E/Zygote  ( 5420): MountEmulatedStorage()
E/Zygote  ( 5420): v2
I/libpersona( 5420): KNOX_SDCARD checking this for 1000
I/libpersona( 5420): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=5420 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 4860:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
W/BaseAppContext( 1886): Using Auth Proxy for data requests.
W/BaseAppContext( 1886): Using Auth Proxy for data requests.
W/BaseAppContext( 1886): Using Auth Proxy for data requests.
W/BaseAppContext( 1886): Using Auth Proxy for data requests.
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_4860/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_4844/cgroup.procs: No such file or directory
W/art     ( 5165): Suspending all threads took: 7.359ms
I/SELinux ( 5420): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5420): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5420): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5420): TimaSignature is unavailable
D/ActivityThread( 5420): Added TimaKeyStore provider
W/ResourcesManager( 5420): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5440): MountEmulatedStorage()
E/Zygote  ( 5440): v2
I/libpersona( 5440): KNOX_SDCARD checking this for 1000
I/libpersona( 5440): KNOX_SDCARD not a persona
I/SELinux ( 5440): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=5440 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 5440): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Killing 4910:com.google.android.gms:car/u0a12 (adj 15): empty #31
E/SELinux ( 5440): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5440): TimaSignature is unavailable
D/ActivityThread( 5440): Added TimaKeyStore provider
W/ResourcesManager( 5440): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ActivityManager( 1017): Scheduling restart of crashed service com.google.android.gms/.car.InCallServiceImpl in 1000ms
I/SL_DEBUG( 5364): isLoggable:: isProductShip = 1
I/SL_DEBUG( 5364): isLoggable:: SL_DEBUG_EXIST = false
I/ActivityManager( 1017): Killing 4933:com.google.android.apps.plus/u0a120 (adj 15): empty #31
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5165): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.docs/cache
I/ActivityManager( 1017): Killing 4195:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
E/JavaBinder( 1017): !!! FAILED BINDER TRANSACTION !!!
W/libprocessgroup( 1017): failed to open /acct/uid_10012/pid_4910/cgroup.procs: No such file or directory
W/BroadcastQueue( 1017): Exception when sending broadcast to ComponentInfo{com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor}
W/BroadcastQueue( 1017): android.os.TransactionTooLargeException
W/BroadcastQueue( 1017): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue( 1017): 	at android.os.BinderProxy.transact(Binder.java:511)
W/BroadcastQueue( 1017): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
W/BroadcastQueue( 1017): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:309)
W/BroadcastQueue( 1017): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1236)
W/BroadcastQueue( 1017): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20387)
W/BroadcastQueue( 1017): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
W/BroadcastQueue( 1017): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3368)
W/BroadcastQueue( 1017): 	at android.os.Binder.execTransact(Binder.java:461)
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 5165): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5165): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/Zygote  ( 5464): MountEmulatedStorage()
E/Zygote  ( 5464): v2
I/libpersona( 5464): KNOX_SDCARD checking this for 10120
I/libpersona( 5464): KNOX_SDCARD not a persona
I/SELinux ( 5464): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5464 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 5464): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5464): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5464): TimaSignature is unavailable
D/ActivityThread( 5464): Added TimaKeyStore provider
W/libprocessgroup( 1017): failed to open /acct/uid_10120/pid_4933/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10057/pid_4195/cgroup.procs: No such file or directory
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ResourcesManager( 5464): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ContextImpl( 5364): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4182, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5364): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5488): MountEmulatedStorage()
E/Zygote  ( 5488): v2
I/libpersona( 5488): KNOX_SDCARD checking this for 10041
I/libpersona( 5488): KNOX_SDCARD not a persona
I/SELinux ( 5488): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=5488 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 5488): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5488): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/art     ( 1017): Explicit concurrent mark sweep GC freed 231445(15MB) AllocSpace objects, 3(4MB) LOS objects, 33% free, 26MB/40MB, paused 3.080ms total 201.442ms
D/TimaKeyStoreProvider( 5488): TimaSignature is unavailable
D/ActivityThread( 5488): Added TimaKeyStore provider
V/JNIHelp ( 5165): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/ActivityManager( 1017): Killing 4584:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
E/SMD     (  290): DCD OFF
D/AndroidRuntime( 5483): 
D/AndroidRuntime( 5483): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5483): CheckJNI is OFF
D/AndroidRuntime( 5483): readGMSProperty: start
D/AndroidRuntime( 5483): readGMSProperty: already setted!!
D/AndroidRuntime( 5483): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5483): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5483): readGMSProperty: end
D/AndroidRuntime( 5483): addProductProperty: start
W/libprocessgroup( 1017): failed to open /acct/uid_10150/pid_4584/cgroup.procs: No such file or directory
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
I/SA      ( 5488): [SSP] onCreated
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
D/ChimeraCfgMgr( 1886): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1886): Module APK com.google.android.play.games already loaded
W/ActivityThread( 5165): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5165): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2f771e99: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5165): Installed default security provider GmsCore_OpenSSL
I/SA      ( 5488): [TPM] There is no property file
I/SA      ( 5488): [SCU] isHaveSA() - false
I/SA      ( 5488): [TPM] getModelProperty : null
I/SA      ( 5488): [TPM] getCSCProperty : null
I/SA      ( 5488): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 5488): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 5488): [DM] TFT FEATURE: false
I/SA      ( 5488): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 5488): [DM] init START
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/SA      ( 5488): [DM] This device is not a Vodafone
W/ResourceType( 5488): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 5488): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 5488): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 5488): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 5488): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 5488): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 5488): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 5488): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 5488): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 5488): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 5488): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 5488): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 5488): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 5488): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 5488): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 5488): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 5488): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
W/ResourceType( 5488): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 5488): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 5488): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 5488): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 5488): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 5488): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 5488): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 5488): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
I/SA      ( 5488): [SCU] isHaveSA() - false
I/SA      ( 5488): support phone number id : false
I/SA      ( 5488): [DM] Supports Ref Jpn : true
I/SA      ( 5488): [DM] init END
I/SA      ( 5488): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
I/SA      ( 5488): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10174 extra.user_handle.:0 ]
I/ActivityManager( 1017): Killing 3679:com.google.android.talk/u0a104 (adj 15): empty #31
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/AcmsKeyStoreHelper( 5216):  getKeyStoreForApplication Enter
E/Zygote  ( 5524): MountEmulatedStorage()
I/libpersona( 5524): KNOX_SDCARD checking this for 10057
E/Zygote  ( 5524): v2
I/libpersona( 5524): KNOX_SDCARD not a persona
I/SELinux ( 5524): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5524): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5524 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
E/SELinux ( 5524): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Killing 4100:com.google.android.gm/u0a101 (adj 15): empty #31
E/AffinityControl( 5483): AffinityControl: registerfunction enter
D/TimaKeyStoreProvider( 5524): TimaSignature is unavailable
D/ActivityThread( 5524): Added TimaKeyStore provider
I/AcmsKeyStoreHelper( 5216): Key Store exist
I/AcmsKeyStoreHelper( 5216): Hence loading the keystore file
D/AndroidRuntime( 5483): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1017): inState():  stateMachine is null !!
I/PersonaManagerService( 1017): PersonaId don't exist
I/ActivityManager( 1017): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/libprocessgroup( 1017): failed to open /acct/uid_10104/pid_3679/cgroup.procs: No such file or directory
D/AcmsKeyStoreHelper( 5216):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 5216): getKeyStoreForApplication success 
D/AcmsCore( 5216): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 5216): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5216): Decrementing - Counter value: 1
D/AcmsCore( 5216): AcmsCore: ACMS_APP_INSTALLED
D/AcmsCore( 5216): This is NOT a valid MirrorLink app
D/AcmsCore( 5216): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 5216): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5216): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 5216): Counter value is 0: Stopping ACMS service
W/ActivityManager( 1017): mDVFSHelper.acquire()
D/FocusedStackFrame( 1017): Set to : 0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1017): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1017): *FMB* installDecor flags : 25362712
I/ActivityManager( 1017): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5542 uid=10174 gids={50174, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1017): Focused application set to: xxxx
D/InputDispatcher( 1017): Focus left window: 1493
E/Zygote  ( 5542): MountEmulatedStorage()
E/Zygote  ( 5542): v2
D/AndroidRuntime( 5483): Shutting down VM
I/libpersona( 5542): KNOX_SDCARD checking this for 10174
I/libpersona( 5542): KNOX_SDCARD not a persona
W/libprocessgroup( 1017): failed to open /acct/uid_10101/pid_4100/cgroup.procs: No such file or directory
I/SELinux ( 5542): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5542): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5542): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AcmsServiceMonitor( 5216): getSvcCounter - Counter value: 0
D/AcmsService( 5216): Enter onDestroy
I/AcmsService( 5216): cleanUp(): inside service clean up
D/AcmsCore( 5216): AcmsCore: inside DeInit
D/AcmsCore( 5216): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 5216): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 5216): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 5216): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 5216): AppEntryInterface: Inside CleanUp
D/AcmsServiceMonitor( 5216): getSvcCounter - Counter value: 0
D/AcmsService( 5216): killing acms process
I/Process ( 5216): Sending signal. PID: 5216 SIG: 9
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled return false
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
I/SurfaceFlinger(  256): id=11 createSurf (1x1),1 flag=404, uhalitest
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
I/art     (  308): Explicit concurrent mark sweep GC freed 8744(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 751us total 26.714ms
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 5542): TimaSignature is unavailable
D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/ActivityThread( 5542): Added TimaKeyStore provider
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 613us total 17.153ms
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 605us total 21.757ms
E/Zygote  ( 5558): MountEmulatedStorage()
E/Zygote  ( 5558): v2
I/libpersona( 5558): KNOX_SDCARD checking this for 10010
I/libpersona( 5558): KNOX_SDCARD not a persona
I/SELinux ( 5558): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=5558 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
V/WindowManager( 1017): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
I/SELinux ( 5558): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5558): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
V/ActivityManager( 1017): Display changed displayId=0
E/JavaBinder( 1017): !!! FAILED BINDER TRANSACTION !!!
W/DisplayManagerService( 1017): Failed to notify process 5216 that displays changed, assuming it died.
W/DisplayManagerService( 1017): android.os.TransactionTooLargeException
W/DisplayManagerService( 1017): 	at android.os.BinderProxy.transactNative(Native Method)
W/DisplayManagerService( 1017): 	at android.os.BinderProxy.transact(Binder.java:511)
W/DisplayManagerService( 1017): 	at android.hardware.display.IDisplayManagerCallback$Stub$Proxy.onDisplayEvent(IDisplayManagerCallback.java:81)
W/DisplayManagerService( 1017): 	at com.android.server.display.DisplayManagerService$CallbackRecord.notifyDisplayEventAsync(DisplayManagerService.java:1372)
W/DisplayManagerService( 1017): 	at com.android.server.display.DisplayManagerService.deliverDisplayEvent(DisplayManagerService.java:1170)
W/DisplayManagerService( 1017): 	at com.android.server.display.DisplayManagerService.access$500(DisplayManagerService.java:146)
W/DisplayManagerService( 1017): 	at com.android.server.display.DisplayManagerService$DisplayManagerHandler.handleMessage(DisplayManagerService.java:1305)
W/DisplayManagerService( 1017): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DisplayManagerService( 1017): 	at android.os.Looper.loop(Looper.java:145)
W/DisplayManagerService( 1017): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/DisplayManagerService( 1017): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1017): isKioskContainerExistOnDevice
D/TimaKeyStoreProvider( 5558): TimaSignature is unavailable
D/ActivityThread( 5558): Added TimaKeyStore provider
I/SurfaceFlinger(  256): id=8 Removed Mauncher (5/9)
I/SurfaceFlinger(  256): id=8 Removed Mauncher (-2/9)
I/ActivityManager( 1017): Process ACMS.Process (pid 5216)(adj 0) has died(63,1097)
D/Launcher( 1493): onTrimMemory. Level: 20
V/ActivityThread( 1493): updateVisibility : ActivityRecord{3ee2f877 token=android.os.BinderProxy@12f3f57e {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/WindowOrientationListener( 1017):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5574): MountEmulatedStorage()
E/Zygote  ( 5574): v2
I/libpersona( 5574): KNOX_SDCARD checking this for 10012
I/libpersona( 5574): KNOX_SDCARD not a persona
I/SELinux ( 5574): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5574): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.google.android.gms:car for service com.google.android.gms/.car.InCallServiceImpl: pid=5574 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
E/SELinux ( 5574): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
W/art     ( 5483): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
I/Mms/MmsApp( 5150):  start initViewCache mms
D/Mms/ComposeMessageFragment( 5150): [start]    fillCache consume time = 1902.089114
D/Mms/ComposeMessageFragment( 5150): fillCache, easy = false
,D/TimaKeyStoreProvider( 5574): TimaSignature is unavailable
,D/ActivityThread( 5574): Added TimaKeyStore provider
,W/ResourcesManager( 5574): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5574): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 5574): VM with version 2.1.0 has multidex support
I/MultiDex( 5574): install
I/MultiDex( 5574): VM has multidex support, MultiDex support library is disabled.
,I/WebViewFactory( 5542): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,D/AbsListView( 5150): Get MotionRecognitionManager
,I/LibraryLoader( 5542): Time to load native libraries: 3 ms (timestamps 6790-6793)
,I/LibraryLoader( 5542): Expected native library version number "",actual native library version number ""
,D/MotionRecognitionService( 1017):  ssp status : false
,D/Mms/ComposeMessageFragment( 5150): [end]    fillCache consume time = 90.922135
,V/JNIHelp ( 5574): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/LocationManagerService( 1017): getProviders()=[passive]
,V/WebViewChromiumFactoryProvider( 5542): Binding Chromium to main looper Looper (main, tid 1) {1f586489}
I/LibraryLoader( 5542): Expected native library version number "",actual native library version number ""
I/chromium( 5542): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/splitIntent( 1017): Queue : backgroundsplit_2 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1017): Killing 4494:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
,I/BrowserStartupController( 5542): Initializing chromium process, singleProcess=true
,W/art     ( 5542): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5542): ApplicationContext is null in ApplicationStatus
,D/Mms/BubbleViewCache( 5150): fillCache bubble = 1
,W/ActivityThread( 5574): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5574): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@36ddd050: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5574): Installed default security provider GmsCore_OpenSSL
,W/chromium( 5542): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1656): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/chromium( 5542): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,I/splitIntent( 1017): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1017): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1017): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1017): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/libEGL  ( 5542): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5542): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5542): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5542): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5542): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5542): Local Branch: 
I/Adreno-EGL( 5542): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5542): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5542):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/AuthorizationBluetoothService( 1656): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
V/GmsCoreStatsServiceLauncher( 1886): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/UpdateIcingCorporaServi( 5524): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1017): failed to open /acct/uid_10040/pid_4494/cgroup.procs: No such file or directory,
,I/ActivityManager( 1017): Killing 4378:com.google.android.music:main/u0a111 (adj 15): empty #31
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 4240): callingUid 10012, callindPid: 4240
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1714): [191] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/BluetoothAdapter( 5542): 436171979: getState() :  mService = null. Returning STATE_OFF
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1886): Restart initialization of location
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/UpdateIcingCorporaServi( 5524): UpdateCorporaTask done [took 126 ms] updated apps [took 126 ms] 
,W/libprocessgroup( 1017): failed to open /acct/uid_10111/pid_4378/cgroup.procs: No such file or directory
,I/art     ( 1656): Explicit concurrent mark sweep GC freed 17485(979KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 10MB/17MB, paused 1.141ms total 44.401ms
,W/ActivityManager( 1017): Activity pause timeout for ActivityRecord{be3d373 u0 com.test.thalitest/.MainActivity t233}
,W/art     ( 5542): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5542): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 5542): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 5542): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 5542): CordovaWebView is running on device made by: samsung
,W/art     ( 5542): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 5542): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5542): Render dirty regions requested: true
,D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
,I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
,W/chromium( 5542): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,V/ActivityThread( 5542): updateVisibility : ActivityRecord{393b26bb token=android.os.BinderProxy@7c444b5 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PhoneWindow( 5542): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null,
D/PhoneWindow( 5542): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  256): id=12 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1017): Focus entered window: 5542,
D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/SRIB_DCS( 5542): log_dcs ThreadedRenderer::initialize entered! 
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,I/OpenGLRenderer( 5542): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5542): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096,
D/OpenGLRenderer( 5542): Enabling debug mode 0
,D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/PanelView( 1180): There is/are notification(s) 
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 1017): Displayed Component not be shown by security: +770ms (total +905ms)
,W/ActivityManager( 1017): mDVFSHelper.release()
I/Timeline( 1017): Timeline: Activity_windows_visible id: ActivityRecord{be3d373 u0 com.test.thalitest/.MainActivity t233} time:77376
,I/SamsungIME( 1749): getCurrentCandidateView
,W/IInputConnectionWrapper( 5542): showStatusIcon on inactive InputConnection
,I/Timeline( 5542): Timeline: Activity_idle id: android.os.BinderProxy@7c444b5 time:77383
,I/SurfaceFlinger(  256): id=11 Removed uhalitest (7/9)
,I/SurfaceFlinger(  256): id=11 Removed uhalitest (-2/9)
,D/SamsungIME( 1749): Dismiss ExpandCandiate
,I/SamsungIME( 1749): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1749): getDebugLevel  : 0x4f4c
,W/BindingManager( 5542): Cannot call determinedVisibility() - never saw a connection for the pid: 5542
,I/SamsungIME( 1749): KeybaordView init() : load resources
,I/SamsungIME( 1749): getCurrentKeyboard
I/SamsungIME( 1749): getTextKeyboard
,D/SamsungIME( 1749): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/JsMessageQueue( 5542): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5542): JniHelper::setJavaVM(0xb7340450), pthread_self() = -1215719608
,I/chromium( 5542): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,V/AlarmManager( 1017): waitForAlarm result :8
,E/Watchdog( 1017): !@Sync 2
,V/AlarmManager( 1017): waitForAlarm result :8
,D/NtpTrustedTime( 1017): forceRefresh() from cache miss
,D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
,D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
,D/NtpTrustedTime( 1017): forceRefresh Fail.
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/jxcore-log( 5542): Initializing JXcore engine
W/jxcore-log( 5542): JXcore engine is ready
,E/audit   ( 1838): type=1400 msg=audit(1453830953.229:203): avc:  denied  { ioctl } for  pid=5634 comm="Thread-960" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1838):  SEPF_SM-A500FU_5.0.2_0027
E/audit   ( 1838): type=1300 msg=audit(1453830953.229:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=b a1=5451 a2=3 a3=9d6c28f8 items=0 ppid=308 ppcomm=main pid=5634 auid=4294967295 uid=10174 gid=10174 euid=10174 suid=10174 fsuid=10174 egid=10174 sgid=10174 fsgid=10174 ses=4294967295 tty=(none) comm="Thread-960" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1838): type=1320 msg=audit(1453830953.229:203): 
,W/jxcore-log( 5542): Starting JXcore engine
,E/SMD     (  290): DCD OFF
,W/jxcore-log( 5542): Platform android
W/jxcore-log( 5542): 
W/jxcore-log( 5542): Process ARCH arm
W/jxcore-log( 5542): 
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/jxcore-log( 5542): JXcore Cordova bridge is ready!
I/jxcore-log( 5542): 
,W/jxcore-log( 5542): JXcore engine is started
,E/jxcore  ( 5542): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 5542): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5542): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,D/FocusedStackFrame( 1017): Set to : 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,D/InputDispatcher( 1017): Focused application set to: xxxx
,D/InputDispatcher( 1017): Focus left window: 5542
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,I/ActivityManager( 1017): Killing 5042:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
I/ActivityManager( 1017): Killing 5017:com.sec.android.diagmonagent/1000 (adj 15): empty #32
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/PluginManager( 5542): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 21ms. Plugin should use CordovaInterface.getThreadPool().
,I/SurfaceFlinger(  256): id=12 Removed NainActivit (6/8)
I/SurfaceFlinger(  256): id=12 Removed NainActivit (-2/8)
,W/ActivityManager( 1017): mDVFSHelper.acquire()
,V/WindowManager( 1017): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,D/Launcher( 1493): onRestart, Launcher: 436171979
,D/Launcher( 1493): onStart, Launcher: 436171979
,D/Launcher.HomeView( 1493): onStart
,D/Launcher( 1493): onResume, Launcher: 436171979
,D/SettingsProvider( 1017): name = kids_home_mode
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10007
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/Launcher.HomeView( 1493): onResume
,D/Launcher( 1493): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/MenuAppsGridFragment( 1493): onResume
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,D/WallpaperManager( 1493): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,D/WallpaperManager( 1493): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,I/splitIntent( 1017): Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=5, mSplitNum[2]=7, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=9
,I/splitIntent( 1017): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,D/GalleryCacheReady( 4510): Receive : home resume
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,D/Recents_RecreateReceiver( 2293): onReceive by home
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,E/JavaBinder( 1017): !!! FAILED BINDER TRANSACTION !!!
,W/BroadcastQueue( 1017): Exception when sending broadcast to ComponentInfo{com.sec.android.widgetapp.activeapplicationwidget/com.sec.android.widgetapp.activeapplicationwidget.ProgramMonitorProvider}
W/BroadcastQueue( 1017): android.os.TransactionTooLargeException
W/BroadcastQueue( 1017): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue( 1017): 	at android.os.BinderProxy.transact(Binder.java:511)
W/BroadcastQueue( 1017): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
W/BroadcastQueue( 1017): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:309)
W/BroadcastQueue( 1017): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1236)
W/BroadcastQueue( 1017): 	at com.android.server.am.BroadcastQueue$BroadcastHandler.handleMessage(BroadcastQueue.java:194)
W/BroadcastQueue( 1017): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/BroadcastQueue( 1017): 	at android.os.Looper.loop(Looper.java:145)
W/BroadcastQueue( 1017): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BroadcastQueue( 1017): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5638): MountEmulatedStorage()
E/Zygote  ( 5638): v2
I/libpersona( 5638): KNOX_SDCARD checking this for 10142
I/libpersona( 5638): KNOX_SDCARD not a persona
I/SELinux ( 5638): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=5638 uid=10142 gids={50142, 9997, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 5638): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 5638): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
D/Mms/UIEventReceiver( 5150): ui event
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5651): MountEmulatedStorage(),
I/libpersona( 5651): KNOX_SDCARD checking this for 10139
E/Zygote  ( 5651): v2
I/libpersona( 5651): KNOX_SDCARD not a persona
,I/SELinux ( 5651): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/SELinux ( 5651): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=5651 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
D/ActivityManager( 1017): handle home activity for 0
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
E/SELinux ( 5651): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/WallpaperManagerService( 1017): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1017): post home show event for user 0
D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
D/WallpaperManagerService( 1017):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 1017): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
D/Launcher.HomeView( 1493): onPause
,D/Launcher( 1493): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/TimaKeyStoreProvider( 5638): TimaSignature is unavailable
,D/ActivityThread( 5638): Added TimaKeyStore provider
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/BroadcastQueue( 1017): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1493, uid=10007) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,W/libprocessgroup( 1017): failed to open /acct/uid_10142/pid_5042/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_5017/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 5651): TimaSignature is unavailable
,I/SurfaceFlinger(  256): id=13 createSurf (720x1280),1 flag=4, Mauncher
D/ActivityThread( 5651): Added TimaKeyStore provider
,D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/InputDispatcher( 1017): Focus entered window: 1493
,D/SRIB_DCS( 1493): log_dcs ThreadedRenderer::initialize entered! 
D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,W/ResourcesManager( 5651): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 5651): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5651): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 5651): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 5651): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,V/ActivityThread( 1493): updateVisibility : ActivityRecord{3ee2f877 token=android.os.BinderProxy@12f3f57e {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,V/TaskCloserActivity( 5638): TaskCloserActivity enter()
D/Launcher.HomeView( 1493): onStop
,D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 5542): showStatusIcon on inactive InputConnection
,D/SamsungIME( 1749): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,V/TaskCloserActivity( 5638): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,I/ActivityManager( 1017): Killing 4281:flipboard.app/u0a98 (adj 15): empty #31
,D/PanelView( 1180): There is/are notification(s) 
,I/Timeline( 1493): Timeline: Activity_idle id: android.os.BinderProxy@12f3f57e time:79912
,I/splitIntent( 1017): Queue : backgroundsplit_1 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1017): Killing 3966:com.sec.spp.push/u0a35 (adj 15): empty #31
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,V/TaskCloserActivity( 5638): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,W/ActivityManager( 1017): mDVFSHelper.release()
I/Timeline( 1017): Timeline: Activity_windows_visible id: ActivityRecord{2cb43222 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t232} time:79933
,D/PersonaManager( 1017): isKioskContainerExistOnDevice
,D/WindowOrientationListener( 1017):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,W/libprocessgroup( 1017): failed to open /acct/uid_10098/pid_4281/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10035/pid_3966/cgroup.procs: No such file or directory
,I/ConfigService( 1656): onDestroy
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,V/AlarmManager( 1017): waitForAlarm result :4
,D/SSRM:n  ( 1017): SIOP:: AP = 340,
,I/PowerManagerService( 1017): [PWL] Off : 30s ago
,I/PowerManagerService( 1017): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService( 1017): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1017): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=1886, ws=null) (elapsedTime=47727)
,E/SMD     (  290): DCD OFF
,I/ActivityManager( 1017): Killing 4743:com.sec.spp.push:RemoteNotiProcess/u0a35 (adj 15): empty #31
,W/libprocessgroup( 1017): failed to open /acct/uid_10035/pid_4743/cgroup.procs: No such file or directory
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/PackageManager( 1017): [MSG] MCS_UNBIND
,I/ActivityManager( 1017): Killing 5134:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,W/libprocessgroup( 1017): failed to open /acct/uid_10100/pid_5134/cgroup.procs: No such file or directory
,V/AlarmManager( 1017): waitForAlarm result :8
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4273, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :8
,V/AlarmManager( 1017): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManagerEXT( 1017): <AppSync3 Whitelist>
V/AlarmManagerEXT( 1017): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/SecKeyguardClockView( 1180): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1180): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ActivityManager( 1017): Waited long enough for: ServiceRecord{269c82a5 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 310
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 10012
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5682): MountEmulatedStorage()
,E/Zygote  ( 5682): v2
I/libpersona( 5682): KNOX_SDCARD checking this for 10104
I/libpersona( 5682): KNOX_SDCARD not a persona
,I/SELinux ( 5682): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5682 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SELinux ( 5682): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
E/SELinux ( 5682): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5682): TimaSignature is unavailable
,D/ActivityThread( 5682): Added TimaKeyStore provider
,W/ResourcesManager( 5682): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Babel_SMS( 5682): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 5682): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5682): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel_SMS( 5682): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5682): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5682): MmsConfig.loadFromResources
,E/Babel_SMS( 5682): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 5682): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/QCamera2Factory(  285): getCameraInfo: E, camera_id = 0
W/QCamera2Factory(  285): getCameraInfo: X
,W/QCamera2Factory(  285): getCameraInfo: E, camera_id = 1
W/QCamera2Factory(  285): getCameraInfo: X
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/GLSUser ( 1656): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1656): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1656): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1656): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Settings( 5682): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5682): startup - clean
,D/Finsky  ( 4876): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4876): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4876): [1] 5.onFinished: Scheduling replication attempt 2.
,I/Babel   ( 5682): deleted: false for 0
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,W/VideoCapabilities( 5682): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5682): Unsupported mime audio/evrc
,W/AudioCapabilities( 5682): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5682): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 5682): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 5682): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 5682): Unsupported mime audio/x-ima
,W/AudioCapabilities( 5682): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5682): Unsupported mime audio/evrc
,W/VideoCapabilities( 5682): Unsupported mime video/wvc1
,W/VideoCapabilities( 5682): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 5682): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 5682): Unsupported mime video/wvc1
,W/VideoCapabilities( 5682): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 5682): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 5682): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 5682): Unsupported mime video/mp43
,W/VideoCapabilities( 5682): Unsupported mime video/sorenson
,W/VideoCapabilities( 5682): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5682): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5682): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5682): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5682): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5682): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager( 1017): Killing 5165:com.google.android.apps.docs/u0a91 (adj 15): empty #31
,I/vclib   ( 5682): onServiceConnected
,W/Babel   ( 5682): Attempted to change video mute state without an active call.
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1017): failed to open /acct/uid_10091/pid_5165/cgroup.procs: No such file or directory
,E/SQLiteLog( 1656): (10) POSIX Error : 11 SQLite Error : 3850
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4211, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 300
,I/PowerManagerService( 1017): [PWL] Off : 50s ago
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4290, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1017): !@Sync 3
,D/FactoryTest( 4780): Not factory mode
,D/FactoryTest( 4780): Not factory mode. isFactoryMode() returend false
D/MTPRx   ( 4780): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 4780): still no open session command from host, so toast
,W/ContextImpl( 4780): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 4780): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,I/Timeline( 4780): Timeline: Activity_launch_request id:com.android.settings time:108318
,E/PersonaManagerService( 1017): inState():  stateMachine is null !!
I/PersonaManagerService( 1017): PersonaId don't exist
I/ActivityManager( 1017): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.settings
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1017): mDVFSHelper.acquire()
,D/FocusedStackFrame( 1017): Set to : 0
,D/PersonaManager( 1017): isKioskContainerExistOnDevice
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.settings
D/InputDispatcher( 1017): Focused application set to: xxxx
,D/InputDispatcher( 1017): Focus left window: 1493
,E/MTPRx   ( 4780): started activity for popup
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,D/WindowOrientationListener( 1017):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,W/ResourcesManager( 4780): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 4780): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4780): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4780): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4780): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4780): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 4780): PREF_DONT_ASK_AGAIN : true
,D/FocusedStackFrame( 1017): Set to : 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,D/InputDispatcher( 1017): Focused application set to: xxxx
,D/InputDispatcher( 1017): Focus entered window: 1493,
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false,
W/InputMethodManagerService( 1017): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@2c820c76 attribute=null, token = android.os.BinderProxy@c90b18c,
,D/SettingsReceiverActivity( 4780): dev.kiessupport is : TRUE
,D/PhoneWindow( 4780): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 4780): *FMB* installDecor flags : 8388610
,I/Atfwd_Sendcmd(  326): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  326): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  290): DCD OFF
,W/ActivityManager( 1017): mDVFSHelper.release()
,D/SSRM:n  ( 1017): SIOP:: AP = 300
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1017): waitForAlarm result :4
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,E/SMD     (  290): DCD OFF
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1656): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1656): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1656): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1656): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4876): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4876): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4876): [1] 5.onFinished: Scheduling replication attempt 3.
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4286, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged,
I/MotionRecognitionService( 1017): mGripSensorEnabled= false,
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF,
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 1
,D/WindowOrientationListener( 1017):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4291, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate,
V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,I/PowerManagerService( 1017): [PWL] Off : 75s ago,
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1017): waitForAlarm result :4,
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 38926(2MB) AllocSpace objects, 27(432KB) LOS objects, 33% free, 26MB/40MB, paused 2.345ms total 175.092ms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1656): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1656): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1656): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1656): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4876): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4876): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4876): [1] 5.onFinished: Scheduling replication attempt 4.
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4292, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1017): !@Sync 4
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :8
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4292, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1017): waitForAlarm result :4
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/SecKeyguardClockView( 1180): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1180): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1656): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1656): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1656): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1656): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4876): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4876): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4876): [1] 5.onFinished: Scheduling replication attempt 5.
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4258, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/PowerManagerService( 1017): [PWL] Off : 105s ago
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1017): SIOP:: AP = 270,
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4295, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1017): !@Sync 5
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 270,
,E/SMD     (  290): DCD OFF,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 10012
,D/NtpTrustedTime( 1017): forceRefresh() from cache miss
,D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
,D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
,D/NtpTrustedTime( 1017): forceRefresh Fail.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4296, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1656): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1656): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1656): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1656): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4876): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4876): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4876): [1] 5.onFinished: Giving up after 6 failures.
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 270
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 140s ago
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1017): !@Sync 6
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :8
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4297, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,I/Atfwd_Sendcmd(  326): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  326): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/Watchdog( 1017): !@Sync 7
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 180s ago
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,V/AlarmManager( 1017): waitForAlarm result :8,
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/SecKeyguardClockView( 1180): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1180): HomeTimezone(): 1
,D/NtpTrustedTime( 1017): forceRefresh() from cache miss
,D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
,D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
D/NtpTrustedTime( 1017): forceRefresh Fail.
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4272, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged,
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4297, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged,
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF,
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1017): !@Sync 8
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,V/AlarmManager( 1017): waitForAlarm result :8
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  290): DCD OFF,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 1017): [PWL] Off : 225s ago,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1017): !@Sync 9
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4298, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService( 1017): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1017): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1017): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1017): initializing...
,I/TLC_TIMA_PKM_initialize( 1017): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1017): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1017): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1017): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1017): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1017): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1017): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1017): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1017): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1017): Loaded image: APP id = 9
,I/TZ: qc_tlc_communication( 1017): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1017): Trustlet response is completed
,E/SMD     (  290): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4293, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1017): !@Sync 10
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,I/Atfwd_Sendcmd(  326): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  326): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 275s ago
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4298, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1017): waitForAlarm result :4,
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/SecKeyguardClockView( 1180): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1180): HomeTimezone(): 1,
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK,
I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
D/EnterpriseController(  277): uids 10012,
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 10012
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4297, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1017): Plugged,
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1017): SIOP:: AP = 270,
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1017): !@Sync 11
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1656): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1656): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1656): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1656): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/WindowManager( 1017): showStatusBarByNotification() mOpenByNotification=false,
W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/ResourcesManager( 1180): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/GLSActivity( 1656): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1656): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1656): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1656): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1656): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1656): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1656): 	at android.os.Binder.execTransact(Binder.java:461)
W/ResourcesManager( 1180): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/PlayEventLogger( 4876): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4876): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4876): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 4876): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4876): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 4876): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4876): 	at android.os.Binder.execTransact(Binder.java:461)
,D/KnoxNotification( 1180): ----- inflateViews : modified publicViewLocal -----
,D/KnoxNotification( 1180): ----- inflateViews : modified KnoxViewLocal -----
,D/PersonaManager( 1180): PersonaID is invalid or persona doesn't exists. : 0
,W/System  ( 4876): Ignoring header User-Agent because its value was null.
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
D/PersonaManager( 1180): isKioskContainerExistOnDevice
,I/System.out( 4876): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,I/System.out( 4876): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 4876): (HTTPLog)-Static: isShipBuild true
I/System.out( 4876): (HTTPLog)-Thread-818-677127357: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 4876): (HTTPLog)-Static: isSBSettingEnabled false
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
,D/EnterpriseController(  277): uids 10028
D/PanelView( 1180): There is/are notification(s) 
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 10028
,E/SMD     (  290): DCD OFF,
,D/PanelView( 1180): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF,
D/SSRM:n  ( 1017): SIOP:: AP = 260
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1017): !@Sync 12
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 330s ago,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,V/AlarmManager( 1017): waitForAlarm result :8,
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1017): !@Sync 13
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 5,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1017): !@Sync 14,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/Atfwd_Sendcmd(  326): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  326): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 390s ago,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1017): !@Sync 15
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 2
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,I/bootchecker(  322): bootchecker wake up!!
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1017): !@Sync 16
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,I/PowerManagerService( 1017): [PWL] Off : 455s ago,
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1017): !@Sync 17
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1017): !@Sync 18
,I/Atfwd_Sendcmd(  326): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  326): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 1017): [PWL] Off : 525s ago
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,I/Atfwd_Daemon(  326): Stop the daemon....
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1017): !@Sync 19
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService( 1017): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1017): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1017): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1017): !@Sync 20
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4296, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged,
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1017): !@Sync 21
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1656): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1656): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1656): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1656): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  290): DCD OFF
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/GLSActivity( 1656): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1656): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1656): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1656): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1656): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1656): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1656): 	at android.os.Binder.execTransact(Binder.java:461)
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/PlayEventLogger( 4876): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4876): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4876): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 4876): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4876): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 4876): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4876): 	at android.os.Binder.execTransact(Binder.java:461)
,W/System  ( 4876): Ignoring header User-Agent because its value was null.
I/System.out( 4876): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10028
,D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 10028
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
,D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
,D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,D/PanelView( 1180): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1017): [PWL] Off : 600s ago
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1017): !@Sync 22
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1017): !@Sync 23,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 680s ago,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1017): !@Sync 24
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1017): !@Sync 25
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1017): !@Sync 26,
,V/AlarmManager( 1017): waitForAlarm result :4,
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/SecKeyguardClockView( 1180): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 10012
,D/SecKeyguardClockView( 1180): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :8
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 765s ago,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1017): !@Sync 27
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4296, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4296, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate,
V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1017): !@Sync 28
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4297, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1017): Plugged
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1017): !@Sync 29
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4296, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1017): stay LED for charging
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,I/PowerManagerService( 1017): [PWL] Off : 855s ago,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4297, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/TimaService( 1017): TIMA: TimaService scheduler is intialized. 
D/TimaService( 1017): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1017): TimaServiceHandler.handleMessage what =1
,E/SMD     (  290): DCD OFF,
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1017): !@Sync 30
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4296, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.,
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4297, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1017): !@Sync 31
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1656): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1656): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1656): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1656): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
D/PersonaManager( 1180): isKioskContainerExistOnDevice
,D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,W/GLSActivity( 1656): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1656): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1656): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1656): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1656): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1656): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1656): 	at android.os.Binder.execTransact(Binder.java:461)
D/PersonaManager( 1180): isKioskContainerExistOnDevice
D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
E/PlayEventLogger( 4876): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4876): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4876): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 4876): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4876): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 4876): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4876): 	at android.os.Binder.execTransact(Binder.java:461)
W/System  ( 4876): Ignoring header User-Agent because its value was null.
I/System.out( 4876): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10028
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 10028
,E/SMD     (  290): DCD OFF
,D/PanelView( 1180): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4293, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged,
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4296, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4297, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1017): !@Sync 32
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4296, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4297, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4295, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/PowerManagerService( 1017): [PWL] Off : 950s ago
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1017): !@Sync 33
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4297, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1017): !@Sync 34
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4297, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/LightsService( 1017): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1017) 
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,E/lights  ( 1017): write_int failed to open -1
D/LightsService( 1017): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=3) set On
D/BatteryService( 1017): turn on LED for fully charged,
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/LightsService( 1017): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
D/LightsService( 1017): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/SecContentProvider2( 1017): uri = 14 selection = getSealedState
D/SecContentProvider2( 1017): mCursor = null
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = -1
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId -1 pkgname com.android.systemui
,I/ValidateNoPeople( 1017): skipping global notification
,D/WindowManager( 1017): showStatusBarByNotification() mOpenByNotification=false
D/PowerManagerService( 1017): [api] acquire WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1180
,I/PowerManagerService( 1017): !@[ps] Screen__On  - 1 :  wl: PowerUI.Notification (14)
I/PowerManagerService( 1017): Waking up from sleep (uid 10054)...
D/PowerManagerService( 1017): [PWL] sb acquire: PowerManagerService.Broadcasts
V/KeyguardServiceDelegate( 1017): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@3e960bb1)
D/PowerManagerService( 1017): [s] UserActivityState : 0 -> 1
D/PowerManagerService( 1017): [PWL] sb acquire: PowerManagerService.Display
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/DisplayPowerController( 1017): Blocking screen on until initial contents have been drawn.
D/WindowOrientationListener( 1017): sensor enabled
I/Sensors ( 1017): AccelerometerSensor(0) setDelay : 200000000(ns)
,D/Launcher( 1493): onRestart, Launcher: 436171979
D/KeyguardViewMediator( 1180): onScreenTurnedOn, seq = 2
D/KeyguardViewMediator( 1180): notifyScreenOnLocked
,D/DisplayPowerController( 1017): getFinalBrightness : Summary is 5 -> 5,
,I/libsuspend( 1017): !@autosuspend_wakeup_count_disable
D/DisplayPowerController( 1017): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
I/libsuspend( 1017): !@autosuspend_wakeup_count_disable done
D/DisplayPowerController( 1017): getFinalBrightness : Summary is 5 -> 5
,D/DisplayPowerController( 1017): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/SensorService( 1017): [SO] changed settle time [0]
D/DisplayManagerService( 1017): !@display_state: OFF -> ON
D/SensorService( 1017): [SO] setDelay [200000000]
D/SensorService( 1017): [SO] activate (ident=0xb7bfb638, enabled=1)
D/SensorService( 1017): [SO] AR_init
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
D/SurfaceFlinger(  256): Set power mode=2, type=0 flinger=0xb7115690
D/qdhwcomposer(  256): hwc_setPowerMode: Setting mode 2 on display: 0
E/qdutils (  256): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  256): int qdutils::getHDMINode(): Failed to find HDMI node
,I/DisplayManagerService( 1017): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager( 1017): Display changed displayId=0
,D/SensorManager( 1017): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,D/PersonaManager( 1017): isKioskContainerExistOnDevice
,D/Launcher( 1493): onStart, Launcher: 436171979
D/Launcher.HomeView( 1493): onStart
,D/KeyguardViewMediator( 1180): handleNotifyScreenOn
,D/StatusBarKeyguardViewManager( 1180): onScreenTurnedOn()
,D/Launcher( 1493): onResume, Launcher: 436171979
,D/SecKeyguardClockSingleView( 1180): onScreenTurnedOn
,D/SettingsProvider( 1017): name = kids_home_mode
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10007
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/PalmMotion( 1017): [PALM] 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
I/PalmMotion( 1017): [PALM] SURFACE_PALM_SWIPE: 1
D/PalmMotion( 1017): [PALM] SETTINGS : [TOUCH: true] [SWEEP: true]
D/PalmMotion( 1017): [PALM] ACCEPTED : [default] PALM_CNT : 3, M_TOUCH : 1000.0, M_SWEEP : 100.0, E_SWEEP : 2.0, IGNORE_M_SWEEP : false
,E/MotionRecognitionService( 1017):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
,D/LightsService( 1017): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1017) 
,D/Launcher.HomeView( 1493): onResume
,D/LightsService( 1017): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,D/LightsService( 1017): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1017): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/Launcher( 1493): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/CoverManagerWhiteLists( 1017): isAllowedToUse : SIGNATURE_MATCH
,D/SamsungIME( 1749): showDlgMsgBox : false true true
,D/SSRM:a  ( 1017): DeviceInfo:: 000000000000
I/rmt_storage(  271): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb84dd7c8
I/rmt_storage(  271): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  271): wakelock acquired: 1, error no: 42
I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1202857848)
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,D/SSRM:a  ( 1017): SettingsAirViewInfo:: 000000000
D/NfcService( 1447): call the applyRouting
,D/qdhwcomposer(  256): hwc_setPowerMode: Done setting mode 2 on display 0
,I/qdhwcomposer(  256): handle_blank_event: dpy:0 panel power state: 1
,E/qdutils (  256): int qdutils::getHDMINode(): Failed to open fb node 2
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,D/SurfaceControl( 1017): Excessive delay in setPowerMode(): 118ms
E/qdutils (  256): int qdutils::getHDMINode(): Failed to find HDMI node
D/PowerManagerService( 1017): Excessive delay in !@display_state: ON: 119ms
D/MISC PowerHAL( 1017): sysfs_write +: /sys/class/input/event1/device/enabled: 1
D/KnoxNotification( 1180): ----- inflateViews : modified publicViewLocal -----
,D/MISC PowerHAL( 1017): sysfs_write +: /sys/class/input/event3/device/enabled: 1
,D/LightsService( 1017): [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 1017) 
,D/LightsService( 1017): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off,
E/lights  ( 1017): write_led_info failed to open -1
D/BatteryService( 1017): turn off LED
E/lights  ( 1017): write_led_info failed to open -1
D/LightsService( 1017): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
E/lights  ( 1017): write_led_info failed to open -1
,D/LightsService( 1017): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
E/lights  ( 1017): write_led_info failed to open -1
E/lights  ( 1017): write_led_info failed to open -1
E/lights  ( 1017): write_led_info failed to open -1
E/lights  ( 1017): write_led_info failed to open -1
E/lights  ( 1017): write_led_info failed to open -1
E/lights  ( 1017): write_led_info failed to open -1
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
D/KnoxNotification( 1180): ----- inflateViews : modified KnoxViewLocal -----,
D/PersonaManager( 1180): PersonaID is invalid or persona doesn't exists. : -1
,E/SmartFaceService( 1017): onReceive: android.intent.action.SCREEN_ON
,W/System.err( 1017): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
W/System.err( 1017): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1017): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1017): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1017): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1017): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
,E/SmartFaceService( 1017): fail to set sysfs 1
W/System.err( 1017): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:468)
W/System.err( 1017): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1017): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1017): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1017): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1017): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1017): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory),
W/System.err( 1017): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1017): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1017): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1017): 	... 10 more
V/UserPresentBroadcastReceiver( 1714): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
D/PersonaManager( 1180): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1180): Icon Only
,I/StatusBar( 1180): Icon Only
D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1180): Icon Only
I/StatusBar( 1180): Icon Only
D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,D/StatusBar.NetworkController( 1180): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1180): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/MenuAppsGridFragment( 1493): onResume
,D/StatusBar.NetworkController( 1180): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBarKeyguardViewManager( 1180): callback.onShown()
V/KeyguardServiceDelegate( 1017): **** SHOWN CALLED ****
D/DisplayPowerController( 1017): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
,I/DisplayPowerController( 1017): Unblocked screen on after 171 ms
I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
D/DisplayPowerState( 1017): !@ ColorFade exit
I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1202857848) wakelock released: 1, error no: 0
I/rmt_storage(  271): 
,I/rmt_storage(  271): rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb84dd7c8
,D/StatusBar.NetworkController( 1180): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1180): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1180): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,I/SurfaceFlinger(  256): id=10 Removed DolorFade (8/8)
D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/DisplayPowerController( 1017): getFinalBrightness : Summary is 5 -> 5
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/DisplayPowerController( 1017): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
I/SurfaceFlinger(  256): id=10 Removed DolorFade (-2/8)
,D/PanelView( 1180): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
E/libEGL  ( 1017): call to OpenGL ES API with no current context (logged once per thread)
D/BatteryMeterView( 1180): onDraw batteryColor : -1
,D/lights  ( 1017): lcd : 5 +
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): handle home activity for 0
I/WallpaperManagerService( 1017): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1017): post home show event for user 0
D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
,D/SecKeyguardClockView( 1180): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/lights  ( 1017): lcd : 5 -
D/SecKeyguardClockView( 1180): HomeTimezone(): 1
D/DisplayPowerController( 1017): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1017): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 1017): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1017): SecHardwareInterface.setBatteryADC : true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,I/Timeline( 1493): Timeline: Activity_idle id: android.os.BinderProxy@12f3f57e time:1042187,
D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/SensorService( 1017): [SO] currT = 1042201047000, prevT = 51051075000, diff = 991149972000, [0.153 0.134 10.209]
D/SensorService( 1017): [SO] Reset Rotation Old [100], Init [1]
,D/WallpaperManagerService( 1017):  force update = false; persona id = 0; current user =0; current persona = 0
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1017): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
,D/InputMethodManagerService( 1017): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,I/splitIntent( 1017): Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=5, mSplitNum[2]=7, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=9
I/splitIntent( 1017): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
D/MISC PowerHAL( 1017): sysfs_write -: /sys/class/input/event3/device/enabled: 1
,D/GalleryCacheReady( 4510): Receive : home resume
,D/MotionRecognitionService( 1017):   mReceiver.onReceive : ACTION_SCREEN_ON
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
I/StatusBar( 1180): Icon Only
D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/MotionRecognitionService( 1017):  handler : SCREEN_ON end
D/Recents_RecreateReceiver( 2293): onReceive by home
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,V/TaskCloserActivity( 5638): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,I/WifiNative-HAL( 1017): startHal
,E/wifi    ( 1017): getStaticLongField sWifiHalHandle 0x9caff7fc
,I/WifiNative-HAL( 1017): Could not start hal
,D/NotificationService( 1017): ACTION_SCREEN_ON
D/LightsService( 1017): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1017) 
,D/LightsService( 1017): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
,D/LightsService( 1017): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1017): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/audio_hw_primary(  285): adev_set_parameters: enter: screen_state=on
V/voice   (  285): voice_set_parameters: enter: screen_state=on
V/voice   (  285): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  285): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  285): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  285): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  285): adev_set_parameters: exit
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,D/Mms/UIEventReceiver( 5150): ui event
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,D/MISC PowerHAL( 1017): sysfs_write -: /sys/class/input/event1/device/enabled: 1
,D/MISC PowerHAL( 1017): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
D/PowerManagerService( 1017): Excessive delay in nativeSetInteractive(true): 153ms
D/MISC PowerHAL( 1017): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
D/PowerManagerService( 1017): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 272ms
D/PowerManagerService-JNI( 1017): Excessive delay in MISC setInteractive(true) while turning screen on: 152ms
I/QCOM PowerHAL( 1017): Got set_interactive hint
,D/lights  ( 1017): button : 1 +
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
W/BroadcastQueue( 1017): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1493, uid=10007) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
,D/IpRemoteDisplayController( 1017): intent received android.intent.action.SCREEN_ON
,D/IpRemoteDisplayController( 1017): Bridge Server is not available
,D/lights  ( 1017): button : 1 -
,I/splitIntent( 1017): Queue : backgroundsplit_2 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SensorService( 1017): [SO] currT = 1042401068000, prevT = 51051075000, diff = 991349993000, [0.153 0.077 10.094]
,D/SensorService( 1017): [SO] 0.153 0.077 10.094
D/SensorService( 1017): [SO] [100 -> 255]
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  290): DCD OFF
,E/SQLiteLog( 1656): (10) POSIX Error : 11 SQLite Error : 3850
,D/SSRM:n  ( 1017): SIOP:: AP = 270
,D/lights  ( 1017): button : 0 +
,D/GpsLocationProvider( 1017): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/PersonaManagerService( 1017): ACTION_SCREEN_ON onReceive
D/PersonaManagerServiceHandler( 1017): MSG_ACTION_SCREEN_ON called
,D/CoverManagerWhiteLists( 1017): isAllowedToUse : SIGNATURE_MATCH
,I/NfcService( 1447): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
D/lights  ( 1017): button : 0 -
,D/accuweather( 1591): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
D/accuweather( 1591): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/NfcService( 1447): call the applyRouting
D/accuweather( 1591): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/accuweather( 1591): [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
D/accuweather( 1591): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1591): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1591): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1591): [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 2
,D/accuweather( 1591): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1591): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,E/accuweather( 1591): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 19 11
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,I/SamsungIME( 1749): getNextShiftState() cursorCapsMode : 0
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/OpenGLRenderer( 1493): SFEffectCache::get: create texture(0xa3d53724): name, size, mSize = 36, 135420, 458160
,D/PowerManagerService( 1017): [PWL] sb release: PowerManagerService.Broadcasts
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,D/daemonapp( 1287): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1287): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1287): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1287): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1287): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1287): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1287): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1287): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1287): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1287): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1287): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1287): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1287): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1287): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1287): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1453852500000
D/daemonapp( 1287): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1453831918194
,D/daemonapp( 1287): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1287): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/daemonapp( 1287): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1287): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1287): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1287): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 1287): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/SSRM:a  ( 1017): DeviceInfo:: 000000000000
,D/SSRM:a  ( 1017): SettingsAirViewInfo:: 000000000
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/SecKeyguardClockView( 1180): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1180): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/accuweather( 1591): [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionTIME_TICK,
D/accuweather( 1591): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/accuweather( 1591): [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,D/accuweather( 1591): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1591): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1591): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
D/accuweather( 1591): [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 2
,D/accuweather( 1591): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
D/accuweather( 1591): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,E/accuweather( 1591): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 19 12
,W/OpenGLRenderer( 1493): SFEffectCache::get: create texture(0xa3d53724): name, size, mSize = 37, 143856, 602016
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4285, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/PersonaManager( 1180): isKioskContainerExistOnDevice
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1180): Icon Only
I/StatusBar( 1180): Icon Only
D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,D/PanelView( 1180): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,D/SensorService( 1017): [SO] 0.153 0.077 10.094
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/PowerManagerService( 1017): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1180 (0x0)
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4288, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,D/PowerManagerService( 1017): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 1017): getFinalBrightness : Summary is 1 -> 1
D/DisplayPowerController( 1017): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 1017): [s] DisplayPowerCallbacks : onStateChanged()
,D/DisplayPowerController( 1017): getFinalBrightness : Summary is 1 -> 1
,D/lights  ( 1017): lcd : 1 +
D/DisplayPowerController( 1017): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255))),
,D/lights  ( 1017): lcd : 1 -
,D/DisplayPowerController( 1017): getFinalBrightness : Summary is 1 -> 1
D/DisplayPowerController( 1017): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1017): !@Sync 35,
,E/SMD     (  290): DCD OFF,
,D/PowerManagerService( 1017): [s] UserActivityState : 2 -> 4
,I/PowerManagerService( 1017): Nap time (uid 1000)...
D/PowerManagerService( 1017): handleSandman : startDreaming: false  (canDreamLocked: false  canDozeLocked: false)
I/PowerManagerService( 1017): !@[ps] Screen__Off - 1 :  dream(timeout) (2)
I/PowerManagerService( 1017): Going to sleep due to screen timeout (uid 1000)...
,D/PowerManagerService( 1017): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 1017): SecHardwareInterface.setBatteryADC : false
,D/PowerManagerService( 1017): handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
D/PowerManagerService( 1017): handleSandman : startDream(true)
E/PowerManagerService( 1017): handleSandman : startDreaming, but isDreaming false
,I/PowerManagerService( 1017): Sleeping (uid 1000)...
D/PowerManagerService( 1017): [s] UserActivityState : 4 -> 0
,I/SurfaceFlinger(  256): id=14 createSurf (720x1280),-1 flag=20004, DolorFade
,V/WindowOrientationListener( 1017): WindowOrientationListener disabled
,D/SensorService( 1017): [SO] activate (ident=0xb7bfb638, enabled=0)
,I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/SensorManager( 1017): unregisterListener ::   
,D/KeyguardViewMediator( 1180): onScreenTurnedOff(3)
,I/KeyguardEffectViewController( 1180): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1180): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1180): notifyScreenOffLocked
,D/Launcher.HomeView( 1493): onPause
,D/KeyguardViewMediator( 1180): timeout : 5000
,D/Launcher( 1493): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/PowerManagerService( 1017): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 32ms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,D/DisplayPowerController( 1017): ColorFade: onAnimationStart
D/DisplayPowerController( 1017): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1017): performScreenOffTransition : no brightness animation
,V/TaskCloserActivity( 5638): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,D/KeyguardViewMediator( 1180): setting alarm to turn off keyguard, seq = 2
D/KeyguardViewMediator( 1180): handleNotifyScreenOff
,D/VolumePanel( 1180): onScreenTurnedOff()
D/VolumePanel( 1180): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1180): mCoverBroadcastReceiver: Screen OFF end
,D/SecKeyguardClockSingleView( 1180): onScreenTurnedOff
,V/ActivityThread( 1493): updateVisibility : ActivityRecord{3ee2f877 token=android.os.BinderProxy@12f3f57e {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/Launcher.HomeView( 1493): onStop
,D/LightsService( 1017): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1017) 
,D/LightsService( 1017): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/BatteryService( 1017): turn on LED for fully charged
D/LightsService( 1017): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
E/lights  ( 1017): write_int failed to open -1
D/LightsService( 1017): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SmartFaceService( 1017): onReceive: android.intent.action.SCREEN_OFF
,W/System.err( 1017): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
W/System.err( 1017): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1017): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1017): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1017): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1017): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1017): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:474)
W/System.err( 1017): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1017): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1017): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1017): 	at android.os.Looper.loop(Looper.java:145)
E/SmartFaceService( 1017): fail to set sysfs 0
W/System.err( 1017): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1017): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1017): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1017): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1017): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1017): 	... 10 more
,I/StatusBar( 1180): Icon Only
,D/PanelView( 1180): There is/are notification(s) 
D/MotionRecognitionService( 1017):   mReceiver.onReceive : ACTION_SCREEN_OFF
,D/SamsungIME( 1749): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,E/MotionRecognitionService( 1017):  handler : SCREEN_OFF end 
,I/WifiNative-HAL( 1017): startHal
,E/wifi    ( 1017): getStaticLongField sWifiHalHandle 0x9caff7fc
D/NotificationService( 1017): ACTION_SCREEN_OFF
I/WifiNative-HAL( 1017): Could not start hal
D/LightsService( 1017): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1017) 
D/LightsService( 1017): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/LightsService( 1017): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1017): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/audio_hw_primary(  285): adev_set_parameters: enter: screen_state=off,
V/voice   (  285): voice_set_parameters: enter: screen_state=off
V/voice   (  285): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  285): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  285): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  285): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  285): adev_set_parameters: exit
,D/IpRemoteDisplayController( 1017): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 1017): Bridge Server is not available
,D/PanelView( 1180): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/DisplayPowerState( 1017): !@ ColorFade entry
,D/DisplayPowerController( 1017): ColorFade: onAnimationEnd
,D/lights  ( 1017): lcd : 0 +
D/DisplayPowerController( 1017): getFinalBrightness : Summary is 0 -> 0
D/DisplayPowerController( 1017): performScreenOffTransition : no brightness animation
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4278, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/lights  ( 1017): lcd : 0 -
D/DisplayPowerController( 1017): getFinalBrightness : Summary is 0 -> 0
D/DisplayPowerController( 1017): performScreenOffTransition : no brightness animation
D/PowerManagerService( 1017): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1017): [PWL] sb release: PowerManagerService.Display
,D/MISC PowerHAL( 1017): sysfs_write +: /sys/class/input/event3/device/enabled: 0
,D/MISC PowerHAL( 1017): sysfs_write +: /sys/class/input/event1/device/enabled: 0
D/MISC PowerHAL( 1017): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/MISC PowerHAL( 1017): sysfs_write -: /sys/class/input/event3/device/enabled: 0
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/MISC PowerHAL( 1017): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/DisplayManagerService( 1017): !@display_state: ON -> OFF
,D/MISC PowerHAL( 1017): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
I/DisplayManagerService( 1017): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
I/QCOM PowerHAL( 1017): Got set_interactive hint
V/ActivityManager( 1017): Display changed displayId=0
D/SurfaceFlinger(  256): Set power mode=0, type=0 flinger=0xb7115690
D/qdhwcomposer(  256): hwc_setPowerMode: Setting mode 0 on display: 0
,E/qdutils (  256): int qdutils::getHDMINode(): Failed to open fb node 2
,E/qdutils (  256): int qdutils::getHDMINode(): Failed to find HDMI node
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/StatusBar.NetworkController( 1180): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
,D/StatusBar.NetworkController( 1180): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1180): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/qdhwcomposer(  256): handle_blank_event: dpy:0 panel power state: 0
,E/qdutils (  256): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  256): int qdutils::getHDMINode(): Failed to find HDMI node
D/qdhwcomposer(  256): hwc_setPowerMode: Done setting mode 0 on display 0
D/SurfaceControl( 1017): Excessive delay in setPowerMode(): 269ms
,D/PowerManagerService( 1017): Excessive delay in !@display_state: OFF: 270ms
I/libsuspend( 1017): !@autosuspend_wakeup_count_enable
I/libsuspend( 1017): !@autosuspend_wakeup_count_enable done
D/PowerManagerService( 1017): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 276ms
I/PowerManagerService( 1017): [PWL] Off : 0s ago
I/PowerManagerService( 1017): [PWL]   PowerManagerService.Broadcasts: ref count=1
,E/SMD     (  290): DCD OFF
,D/GpsLocationProvider( 1017): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.SCREEN_OFF
,V/EmergencyMode( 1407): [EmergencyStateReceiver] binteractive [false] why[3]
,D/PersonaManagerService( 1017): ACTION_SCREEN_OFF onReceive
D/PersonaManagerServiceHandler( 1017): MSG_ACTION_SCREEN_OFF called
,D/accuweather( 1591): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF,
D/NfcService( 1447): call the applyRouting
D/accuweather( 1591): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1591): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/daemonapp( 1287): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,D/accuweather( 1591): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1591): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1591): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1591): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/daemonapp( 1287): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,E/LibSecureUISvc( 1851): svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
,D/PowerManagerService( 1017): [PWL] sb release: PowerManagerService.Broadcasts
,D/daemonapp( 1287): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/SSRM:n  ( 1017): SIOP:: AP = 270
,D/accuweather( 1591): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1591): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1591): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
D/accuweather( 1591): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1591): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
,D/accuweather( 1591): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/accuweather( 1591): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4
,D/KeyguardViewMediator( 1180): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/KeyguardViewMediator( 1180): doKeyguard: not showing because lockscreen is off
,V/KeyguardEffectViewController( 1180): *** Keyguard wallpaper service already unbounded
,I/PowerManagerService( 1017): [PWL] Off : 5s ago,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4300, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1017): SIOP:: AP = 270,
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 15s ago,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4293, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1017): !@Sync 36
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4303, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 1017): [PWL] Off : 30s ago,
,E/SMD     (  290): DCD OFF,
,V/AlarmManager( 1017): waitForAlarm result :4
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :8
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 50s ago,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4302, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged,
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1017): !@Sync 37,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4303, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1017): Plugged
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate,
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4306, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1017): stay LED for fully charged
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 75s ago,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1017): !@Sync 38
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4305, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate,
V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4306, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED,
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 105s ago,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4305, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1017): !@Sync 39
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4306, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 1017): stay LED for fully charged
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,I/PowerManagerService( 1017): [PWL] Off : 140s ago,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4307, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/TimaService( 1017): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1017): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1017): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 1017): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 1017): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 1017): Updating Usage Statistics in DB @ 1453832089997
,I/ApplicationUsage( 1017): Done Updating Usage Statistics in DB @ 1453832090000
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1017): !@Sync 40,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1017): !@Sync 41
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1656): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1656): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1656): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1656): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1656): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/GLSActivity( 1656): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1656): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1656): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1656): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1656): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1656): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1656): 	at android.os.Binder.execTransact(Binder.java:461)
,E/SMD     (  290): DCD OFF
D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
D/PersonaManager( 1180): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1180): Icon Only
I/StatusBar( 1180): Icon Only
D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,E/PlayEventLogger( 4876): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4876): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4876): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 4876): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4876): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 4876): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4876): 	at android.os.Binder.execTransact(Binder.java:461)
,W/System  ( 4876): Ignoring header User-Agent because its value was null.
I/System.out( 4876): (HTTPLog)-Static: isSBSettingEnabled false
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1180): Icon Only
I/StatusBar( 1180): Icon Only
D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,D/EnterpriseController(  277): uids 10028
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 10028
,D/PanelView( 1180): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/PowerManagerService( 1017): [PWL] Off : 180s ago,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4305, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4307, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1017): Plugged,
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1407): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1407): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1017): !@Sync 42,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :8
,V/AlarmManager( 1017): No more alarm at this time.nowELAPSED=1285756 batch.start=1518205
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/SecKeyguardClockView( 1180): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1180): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 6233): 
D/AndroidRuntime( 6233): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6233): CheckJNI is OFF
D/AndroidRuntime( 6233): readGMSProperty: start
D/AndroidRuntime( 6233): readGMSProperty: already setted!!
D/AndroidRuntime( 6233): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6233): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6233): readGMSProperty: end
D/AndroidRuntime( 6233): addProductProperty: start
E/AffinityControl( 6233): AffinityControl: registerfunction enter
D/AndroidRuntime( 6233): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1017): START PACKAGE DELETE: observer{819405443}
D/PackageManager( 1017): pkg{<packageName>}
D/PackageManager( 1017): user{0}
D/PackageManager( 1017): caller{2000}
D/PackageManager( 1017): flags{3}
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1017): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1017): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1017): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1017): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1017): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/PackageManager( 1017): !@killApplicatoin: 10174, uninstall pkg
D/ApplicationPolicy( 1017): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1017): getApplicationUninstallationEnabled :  enabled true
I/ActivityManager( 1017): Force stopping com.test.thalitest appid=10174 user=-1: uninstall pkg
I/ActivityManager( 1017): Killing 5542:com.test.thalitest/u0a174 (adj 15): stop com.test.thalitest cause uninstall pkg
I/ActivityManager( 1017): Force stopping com.test.thalitest appid=10174 user=0: pkg removed
W/ActivityManager( 1017): CustomStartingWindow se packge removed so remove capture also
I/art     ( 3733): Explicit concurrent mark sweep GC freed 17587(1018KB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 6MB/11MB, paused 1.454ms total 61.319ms
I/art     ( 5524): Explicit concurrent mark sweep GC freed 382(26KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 8MB/11MB, paused 954us total 61.760ms
I/InputReader( 1017): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 1749): mOCRHelper is null
W/GeofencerStateMachine( 1714): Ignoring removeGeofence because network location is disabled.
I/KLMS-2.5.183: ( 3536): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Jan 26 19:16:01 GMT+01:00 2016
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
D/RegisteredComponentCache( 1447): Collect Tech packages for Knox
D/PersonaManager( 1447): isKioskContainerExistOnDevice
I/KLMS-2.5.183: ( 3536): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 1017): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=28
I/splitIntent( 1017): base  index=28, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1017): other index=31, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1017): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6246): MountEmulatedStorage()
E/Zygote  ( 6246): v2
I/libpersona( 6246): KNOX_SDCARD checking this for 10094
I/libpersona( 6246): KNOX_SDCARD not a persona
I/SELinux ( 6246): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6246): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6246): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6246 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
I/KLMS-2.5.183: ( 3536): KLMSIntentService(): onCreate()
I/KLMS-2.5.183: ( 3536): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/TimaKeyStoreProvider( 6246): TimaSignature is unavailable
D/ActivityThread( 6246): Added TimaKeyStore provider
I/KLMS-2.5.183: ( 3536): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/KLMS-2.5.183: ( 3536): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1017): mCursor = null
I/KLMS-2.5.183: ( 3536): KLMSIntentService(): PACKAGE_REMOVED
I/KLMS-2.5.183: ( 3536): KLMSIntentService(): listeningToPackageRemoved().START
I/KLMS-2.5.183: ( 3536): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
D/EnterpriseDeviceManagerService( 1017): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1017): Admin package name: com.google.android.gms
I/art     ( 1017): Explicit concurrent mark sweep GC freed 39410(3MB) AllocSpace objects, 107(1733KB) LOS objects, 33% free, 26MB/40MB, paused 3.905ms total 237.806ms
I/art     ( 1017): WaitForGcToComplete blocked for 138.693ms for cause Explicit
W/TextServicesManagerService( 1017): no available spell checker services found
D/PersonaManager( 1447): isKioskContainerExistOnDevice
D/RegisteredServicesCache( 1447): empty dynamic service
D/elm:15183( 6246): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15183( 6246): ELMEngine.ELMEngine( context ).
D/elm:15183( 6246): MDMBridge.setEnterpriseBridge()
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:15183( 6246): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:15183( 6246): ElmAgentService : onCreate()
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:15183( 6246): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15183( 6246): MainReceiver.listeningToPackageRemoved()
D/elm:15183( 6246): MDMBridge.getInstance()
D/elm:15183( 6246): MDMBridge.getAllLicenseInfoFromSDK()
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:15183( 6246): MDMBridge.getAllLicenseInfoFromSDK()
I/KLMS-2.5.183: ( 3536): KLMSIntentService(): listeningToPackageRemoved().END
I/KLMS-2.5.183: ( 3536): KLMSIntentService(): onDestroy()
D/elm:15183( 6246): ElmAgentService : onDestroy().
I/art     ( 1017): Explicit concurrent mark sweep GC freed 12417(638KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 26MB/40MB, paused 3.014ms total 172.763ms
W/ResourceType( 1017): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/PackageManager( 1017): delete codoeFile: 
D/AASAuninstall( 1017): userId = 0, info.removedAppID = -1, info.uid = 10174, packageName = com.test.thalitest
I/AASA_removePackage( 1017): UID=10174 Target=com.test.thalitest
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/PackageManager( 1017): result of delete: 1{819405443}
D/AndroidRuntime( 6233): Shutting down VM
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ResourcesManager( 1017): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/RCPManagerService( 1017): PackageReceiver onReceive()
I/HarmonyEASService( 1017): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy( 1017): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1017): PackageRemovalReceiver::onReceive Enter
D/OTPFW   ( 1017): OtpDbHelper::getInstance New instance created
D/OTPFW   ( 1017): DBIntegrity::getInstance - New instance created
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/OTPFW   ( 1017): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10174 container id = 0
I/OTPFW   ( 1017): ProvisionData::getAllEntries Enter
E/OTPFW   ( 1017): ProvisionData::getAllEntries Table is empty
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/BackupManagerService( 1017): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/JobSchedulerService( 1017): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1017): uID is 10174
V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0
I/CrashAnrDetector( 1017): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager( 1017): clearDefaults: com.test.thalitest
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/TaskPersister( 1017): removeObsoleteFile: deleting file=233_task.xml
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1017): uID is 10174
V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
D/SSRM:aZ ( 1017): MSG_TYPE_APP_REMOVED::
I/PCWCLIENTTRACE_PushUtil( 5198): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5198): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5198): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5198): [onReceive] - android.intent.action.PACKAGE_REMOVED
I/SA      ( 5488): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
I/SA      ( 5488): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10174 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
I/PackagesMonitor( 4510): PackagesMonitor onReceive :com.test.thalitest
D/Mms/FreeMessageStatusReceiver( 5150): onReceive, action : android.intent.action.PACKAGE_REMOVED
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
I/TactileAssist( 1017): enable value -1
I/TactileAssist( 1017): internal enable value -1
I/TactileAssist( 1017): intensity value -1
I/TactileAssist( 1017): saveAppList value true
D/Mms/FreeMessageReceiverService( 5150): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
I/TactileAssist( 1017): List of disabled apps :
D/Mms/FreeMessageReceiverService( 5150): onHandleIntent: ACTION_PACKAGE_REMOVED
D/Compatibility( 5383): onReceive() it will make start service
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/Compatibility( 5383): onHandleIntent()
D/Compatibility( 5383): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10174, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/Compatibility( 5383): found: 2
D/Compatibility( 5383): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5383): skipping ResolveInfo{3e59c045 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5383): considering ResolveInfo{1f2a139a com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5383): default: com.sec.android.app.soundalive.SAControlPanelActivity
E/Zygote  ( 6268): MountEmulatedStorage()
I/libpersona( 6268): KNOX_SDCARD checking this for 10003
E/Zygote  ( 6268): v2
I/libpersona( 6268): KNOX_SDCARD not a persona
I/SELinux ( 6268): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6268 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
D/Compatibility( 5383): enabling receiver ResolveInfo{19ff74cb com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
I/SELinux ( 6268): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6268): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Compatibility( 5383): enabling receiver ResolveInfo{75cc4a8 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
W/art     ( 6233): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
D/Compatibility( 5383): enabling receiver ResolveInfo{285b1bc1 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 5383): enabling receiver ResolveInfo{2985cf66 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 5383): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
D/TimaKeyStoreProvider( 6268): TimaSignature is unavailable
D/ActivityThread( 6268): Added TimaKeyStore provider
D/UserAnalysis.PlaceProvider( 6268): PlaceProvider onCreate()
D/UserAnalysis.SecureDbManager( 6268): Key for secure DB is newly created
D/UserAnalysis.SecurePlaceDbHelper( 6268): SecurePlaceDbHelper() 
D/UserAnalysis( 6268): Create SecureDbHelper
D/IntelligenceServiceApplication( 6268): onCreate()
D/UserAnalysis.UserAnalysisBroadcastReceiver( 6268): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
E/SQLiteLog( 6268): (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 6268): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 6268): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6268): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6268): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6268): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6268): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6268): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6268): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6268): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6268): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6268): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6268): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6268): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6268): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6268): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 6268): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:69)
E/SQLiteDatabase( 6268): 	at com.samsung.android.intelligenceservice.IntelligenceServiceApplication$1.run(IntelligenceServiceApplication.java:46)
E/SQLiteDatabase( 6268): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 6268): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 6268): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6268): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6268): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6268): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6268): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6268): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper( 6268): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper( 6268): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 6268): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 6268): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 6268): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 6268): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 6268): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 6268): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 6268): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteOpenHelper( 6268): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteOpenHelper( 6268): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 6268): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteOpenHelper( 6268): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 6268): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 6268): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 6268): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:69)
E/SQLiteOpenHelper( 6268): 	at com.samsung.android.intelligenceservice.IntelligenceServiceApplication$1.run(IntelligenceServiceApplication.java:46)
E/SQLiteOpenHelper( 6268): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteOpenHelper( 6268): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteOpenHelper( 6268): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 6268): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteOpenHelper( 6268): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 6268): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 6268): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 6268): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper( 6268): Opened privacy in read-only mode
D/IntelligenceServiceApplication( 6268): no applications having user consent for prediction
W/ContextImpl( 5400): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
V/PlaceDetection v1.0.19 ( 6268): [PlaceDetection::stopService] Service stopped.
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
V/PlaceDetection v1.0.19 ( 6268): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
E/SQLiteLog( 6268): (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 6268): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 6268): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6268): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6268): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6268): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6268): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6268): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6268): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6268): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6268): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6268): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6268): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6268): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6268): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6268): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6268): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:204)
E/SQLiteDatabase( 6268): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:78)
E/SQLiteDatabase( 6268): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 6268): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 6268): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6268): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6268): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6268): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6268): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6268): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime( 6268): Shutting down VM
E/AndroidRuntime( 6268): FATAL EXCEPTION: main
E/AndroidRuntime( 6268): Process: com.samsung.android.intelligenceservice, PID: 6268
E/AndroidRuntime( 6268): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6268): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6268): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime( 6268): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime( 6268): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 6268): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 6268): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 6268): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/AndroidRuntime( 6268): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/AndroidRuntime( 6268): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime( 6268): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/AndroidRuntime( 6268): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime( 6268): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6268): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6268): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:204)
E/AndroidRuntime( 6268): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:78)
E/AndroidRuntime( 6268): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime( 6268): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 6268): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6268): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/AndroidRuntime( 6268): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6268): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6268): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 6268): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.samsung.android.intelligenceservice
D/RCPManager( 5440):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1017):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1017): queryAllProviders():  providerCallBack is not register for 0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6287): MountEmulatedStorage()
E/Zygote  ( 6287): v2
I/libpersona( 6287): KNOX_SDCARD checking this for 10100
I/libpersona( 6287): KNOX_SDCARD not a persona
I/SELinux ( 6287): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=6287 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/SELinux ( 6287): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6287): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/Process ( 6268): Sending signal. PID: 6268 SIG: 9
E/SQLiteLog( 5400): (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 5400): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 5400): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5400): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5400): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5400): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5400): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5400): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5400): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5400): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 5400): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 5400): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5400): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 5400): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5400): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5400): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5400): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
E/SQLiteDatabase( 5400): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
E/SQLiteDatabase( 5400): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5400): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5400): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5400): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 5400): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 5400): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 5400): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
W/System.err( 5400): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
W/System.err( 5400): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 5400): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 5400): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 5400): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
W/System.err( 5400): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
W/System.err( 5400): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
W/System.err( 5400): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
W/System.err( 5400): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err( 5400): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err( 5400): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err( 5400): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
W/System.err( 5400): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
W/System.err( 5400): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 5400): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5400): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5400): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/lowmemorykiller(  253): Error writing /proc/6268/oom_score_adj; errno=22
I/ActivityManager( 1017): Killing 5120:com.google.android.partnersetup/u0a15 (adj 15): empty #31
E/DropBoxManagerService( 1017): Can't write: system_app_crash
E/DropBoxManagerService( 1017): java.io.FileNotFoundException: /data/system/dropbox/drop167.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1017): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 1017): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 1017): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 1017): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1017): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 1017): 	at com.android.server.am.ActivityManagerService$25.run(ActivityManagerService.java:15884)
E/DropBoxManagerService( 1017): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1017): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1017): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 1017): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 1017): 	... 5 more
D/TimaKeyStoreProvider( 6287): TimaSignature is unavailable
D/ActivityThread( 6287): Added TimaKeyStore provider

```
