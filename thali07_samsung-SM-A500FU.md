#### Test 587523534d3a10e_thali07_samsung-SM-A500FU Logs


```
--------- beginning of main
D/Mms/MessagingNotification( 5119): [end]    init consume time = 11.934792
D/TP/MmsSmsProvider( 1470): query,matched:0, calling pid = 5119
V/TP/MmsSmsProvider( 1470): getSimpleConversations entered.
D/TP/MmsSmsProvider( 1470): match 0:Elapsed time : 2.403 ms
D/Mms/DownloadManager( 5119): Service state changed: Bundle[mParcelledData.dataSize=744]
D/Mms/DownloadManager( 5119): roaming ------> false, mSimSlot = 0
D/Mms/MethodReflector( 5119): getSubId is called
D/Mms/TelephonyUtils( 5119): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 5119): getTelephonyProperty is called
D/Mms/DownloadManager( 5119): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5119): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5119): auto download without roaming -> true
D/Mms/DownloadManager( 5119): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5119): mAutoDownload ------> true
D/Mms/FreeMessageStatusReceiver( 5119): onReceive, action : android.intent.action.PACKAGE_ADDED
--------- beginning of system
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5277): MountEmulatedStorage()
E/Zygote  ( 5277): v2
I/SELinux ( 5277): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5277): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5277): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/Mms/ArtClassLoader( 5119): init [DONE] art
I/libpersona( 5277): KNOX_SDCARD checking this for 10072
I/libpersona( 5277): KNOX_SDCARD not a persona
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
I/ActivityManager( 1018): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5277 uid=10072 gids={50072, 9997} abi=armeabi-v7a
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5294): MountEmulatedStorage()
E/Zygote  ( 5294): v2
D/Mms/SpamFilter( 5119): [start]    SpamFilter fill() begin consume time = 66.964322
I/SELinux ( 5294): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/TimaKeyStoreProvider( 5277): TimaSignature is unavailable
I/SELinux ( 5294): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
D/ActivityThread( 5277): Added TimaKeyStore provider
E/SELinux ( 5294): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
D/Mms/Synchronizer( 5119): [start]    doSync consume time = 6.338125
I/libpersona( 5294): KNOX_SDCARD checking this for 10047
I/libpersona( 5294): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5294 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
D/TP/MmsSmsProvider( 1470): query,matched:400, calling pid = 5119
D/TP/MmsSmsProvider( 1470): update, matched:300, calling pid = 5119
V/TP/MmsSmsProvider( 1470): syncDBData start
V/TP/MmsSmsProvider( 1470): syncDBData sms end
V/TP/MmsSmsProvider( 1470): syncDBData mms end
V/TP/MmsSmsProvider( 1470): syncDBData end
D/Mms/SpamFilter( 5119): [end]    SpamFilter fill() finished consume time = 19.385053
D/TimaKeyStoreProvider( 5294): TimaSignature is unavailable
I/art     (  305): Explicit concurrent mark sweep GC freed 8719(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 645us total 28.567ms
D/ActivityThread( 5294): Added TimaKeyStore provider
D/Mms/Synchronizer( 5119): [end]    doSync consume time = 7.498593
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
E/SMD     (  288): DCD OFF
W/ActivityManager( 1018): userId = 0, bbcId = -10000
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 617us total 16.974ms
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ConfigFetchService( 1849): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
D/BadgeProvider( 5277): onCreate
D/BadgeProvider( 5277): DatabaseHelper
I/ConfigFetchService( 1849): launchTask
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 618us total 16.751ms
D/Mms/FreeMessageReceiverService( 5119): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 5119): onHandleIntent: ACTION_PACKAGE_ADDED
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ChimeraCfgMgr( 1849): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1849): Module APK com.google.android.play.games already loaded
I/ActivityManager( 1018): Killing 3407:com.android.providers.calendar/u0a42 (adj 15): empty #31
I/ActivityManager( 1018): Killing 4543:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #32
I/PeopleContactsSync( 1849): CP2 sync disabled
D/ChimeraCfgMgr( 1849): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 1849): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Mms/MessagingNotification( 5119): checkBadgeCount unreadCount=0 badgeCount=0
D/Vision  ( 1849): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1849): No vision deps
D/TP/SmsProvider( 1470): query,matched:26, calling pid = 5119
W/ResourcesManager( 5294): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5294): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5294): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/TP/SmsProvider( 1470): match 26:Elapsed time : 3.453 ms
D/TP/MmsSmsProvider( 1470): query,matched:6, calling pid = 5119
D/TP/MmsSmsProvider( 1470): match 6:Elapsed time : 1.944 ms
I/DBG_POLICYDM( 5198): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
I/DBG_POLICYDM( 5198): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
I/DBG_POLICYDM( 5198): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
I/DBG_POLICYDM( 5198): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
I/DBG_POLICYDM( 5198): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 5198): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
I/DBG_POLICYDM( 5198): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
I/DBG_POLICYDM( 5198): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/data/com.policydm/cache]
I/ActivityManager( 1018): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5316 uid=10025 gids={50025, 9997} abi=armeabi-v7a
I/DBG_POLICYDM( 5198): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
I/DBG_POLICYDM( 5198): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
E/Zygote  ( 5316): MountEmulatedStorage()
E/Zygote  ( 5316): v2
I/libpersona( 5316): KNOX_SDCARD checking this for 10025
I/libpersona( 5316): KNOX_SDCARD not a persona
I/SELinux ( 5316): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/DBG_POLICYDM( 5198): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
I/DBG_POLICYDM( 5198): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
I/SELinux ( 5316): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5316): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/DBG_POLICYDM( 5198): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 5198): [com.policydm.XSPPReceiver(53/onReceive)] ACTION_PACKAGE_ADDED. mPkgName:com.test.thalitest
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
V/ConfigFetchTask( 1849): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1ValWPmTt8y7kwHjah-UWvGF9RGC7nhEy_tb65-E4wTL8KdxfhuZOjahZV0EfouNmoRIGUXO23HiWZeNUXSsWa_RRIfT0EK_Mvi4Ej1HdpxfKer2cIkaSOGr0BgLbqSZqYscP3e8KktSxMRNCwYaNhX9EH6XR3W57kCm_sPGjKBVoZGUQK48jALHTvyuxJzzuPnqiOH-OLlc3kQWqKHsPNFlv7hrqwTeLnDF1PXO3XcNgClnC0
I/DBG_POLICYDM( 5198): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
E/Zygote  ( 5326): MountEmulatedStorage()
I/libpersona( 5326): KNOX_SDCARD checking this for 10038
E/Zygote  ( 5326): v2
I/libpersona( 5326): KNOX_SDCARD not a persona
I/SELinux ( 5326): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=5326 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
I/SELinux ( 5326): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1018): Killing 4361:com.samsung.android.app.mirrorlink/1000 (adj 15): empty #31
D/TimaKeyStoreProvider( 5316): TimaSignature is unavailable
D/ActivityThread( 5316): Added TimaKeyStore provider
E/SELinux ( 5326): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1018): failed to open /acct/uid_10042/pid_3407/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_4543/cgroup.procs: No such file or directory
I/ActivityManager( 1018): Killing 4806:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/GoogleURLConnFactory( 1849): Using platform SSLCertificateSocketFactory
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ResourcesManager( 5316): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 5326): TimaSignature is unavailable
D/ActivityThread( 5326): Added TimaKeyStore provider
D/MyFiles ( 5294): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
I/OMACP   ( 5316): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
I/System.out( 1849): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1849): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1849): (HTTPLog)-Static: isShipBuild true
I/System.out( 1849): (HTTPLog)-Thread-242-223896000: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1849): (HTTPLog)-Static: isSBSettingEnabled false
D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10012
W/ResourcesManager( 5326): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5326): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_4361/cgroup.procs: No such file or directory
E/installd(  284): system dir 0 : /system/app/
E/installd(  284): system dir 1 : /system/priv-app/
E/installd(  284): system dir 2 : /vendor/app/
E/installd(  284): system dir 3 : /oem/app/
W/art     ( 1849): Verification of void com.google.android.gms.games.broker.DataBroker.<init>(android.content.Context) took 210.277ms
W/libprocessgroup( 1018): failed to open /acct/uid_10069/pid_4806/cgroup.procs: No such file or directory
I/TactileAssist( 1018): enable value -1
I/TactileAssist( 1018): internal enable value -1
I/TactileAssist( 1018): intensity value -1
I/TactileAssist( 1018): saveAppList value true
I/DBG_POLICYDM( 5198): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
I/TactileAssist( 1018): List of disabled apps :
I/DBG_POLICYDM( 5198): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
I/DBG_POLICYDM( 5198): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
W/ConfigFetchTask( 1849): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/ConfigFetchService( 1849): fetch service done; releasing wakelock
I/ConfigFetchService( 1849): stopping self
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/DBG_POLICYDM( 5198): [com.policydm.agent.XDMTask(174/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized
E/Zygote  ( 5351): MountEmulatedStorage()
I/libpersona( 5351): KNOX_SDCARD checking this for 10053
E/Zygote  ( 5351): v2
I/libpersona( 5351): KNOX_SDCARD not a persona
I/SELinux ( 5351): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5351): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=5351 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
E/SELinux ( 5351): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/Mms/Omacp( 5119): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
D/PackageManager( 1018): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
D/TimaKeyStoreProvider( 5351): TimaSignature is unavailable
D/ActivityThread( 5351): Added TimaKeyStore provider
I/OMACP   ( 5316): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
I/OMACP   ( 5316): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
I/OMACP   ( 5316): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
W/ResourcesManager( 5351): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
I/OMACP   ( 5316): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
I/OMACP   ( 5316): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
I/OMACP   ( 5316): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
I/OMACP   ( 5316): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
I/OMACP   ( 5316): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
I/OMACP   ( 5316): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
I/OMACP   ( 5316): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
I/OMACP   ( 5316): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
I/OMACP   ( 5316): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
I/OMACP   ( 5316): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
D/Compatibility( 5351): onReceive() it will make start service
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/Compatibility( 5351): onHandleIntent()
D/Compatibility( 5351): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10174, android.intent.extra.user_handle=0}]
D/Compatibility( 5351): found: 2
E/Zygote  ( 5371): MountEmulatedStorage()
E/Zygote  ( 5371): v2
I/libpersona( 5371): KNOX_SDCARD checking this for 1000
I/libpersona( 5371): KNOX_SDCARD not a persona
I/SELinux ( 5371): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=5371 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 5371): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5371): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Compatibility( 5351): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5351): skipping ResolveInfo{1c13ecfb com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5351): considering ResolveInfo{bd29118 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5351): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5351): enabling receiver ResolveInfo{16d4771 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 5351): enabling receiver ResolveInfo{19b20956 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/TimaKeyStoreProvider( 5371): TimaSignature is unavailable
D/Compatibility( 5351): enabling receiver ResolveInfo{3e2a5dd7 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/ActivityThread( 5371): Added TimaKeyStore provider
D/Compatibility( 5351): enabling receiver ResolveInfo{beba6c4 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 5351): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
I/ActivityManager( 1018): Killing 4821:com.sec.knox.bridge/1000 (adj 15): empty #31
I/GAv4    ( 5135): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5135):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5135):   adb logcat -s GAv4
W/ContextImpl( 5371): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
W/GAv4    ( 5135): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/Zygote  ( 5387): MountEmulatedStorage()
E/Zygote  ( 5387): v2
I/libpersona( 5387): KNOX_SDCARD checking this for 1000
I/SELinux ( 5387): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/libpersona( 5387): KNOX_SDCARD not a persona
I/SELinux ( 5387): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=5387 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 5387): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_4821/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 5387): TimaSignature is unavailable
D/ActivityThread( 5387): Added TimaKeyStore provider
W/GAv4    ( 5135): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
I/ActivityManager( 1018): Killing 4837:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
W/ResourcesManager( 5387): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
W/BaseAppContext( 1849): Using Auth Proxy for data requests.
W/BaseAppContext( 1849): Using Auth Proxy for data requests.
W/AnalyticsTrackerProxyImpl( 5135): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
W/GAv4    ( 5135): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/BaseAppContext( 1849): Using Auth Proxy for data requests.
W/BaseAppContext( 1849): Using Auth Proxy for data requests.
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_4837/cgroup.procs: No such file or directory
E/Zygote  ( 5406): MountEmulatedStorage()
E/Zygote  ( 5406): v2
I/libpersona( 5406): KNOX_SDCARD checking this for 1000
I/libpersona( 5406): KNOX_SDCARD not a persona
I/SELinux ( 5406): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=5406 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 5406): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1018): Killing 4912:com.google.android.apps.plus/u0a120 (adj 15): empty #31
E/SELinux ( 5406): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/BaseAppContext( 1849): Using Auth Proxy for data requests.
D/TimaKeyStoreProvider( 5406): TimaSignature is unavailable
D/ActivityThread( 5406): Added TimaKeyStore provider
W/ResourcesManager( 5406): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/ActivityManager( 1018): Killing 4195:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
W/BaseAppContext( 1849): Using Auth Proxy for data requests.
W/libprocessgroup( 1018): failed to open /acct/uid_10120/pid_4912/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10057/pid_4195/cgroup.procs: No such file or directory
I/SL_DEBUG( 5326): isLoggable:: isProductShip = 1
I/SL_DEBUG( 5326): isLoggable:: SL_DEBUG_EXIST = false
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5135): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.docs/cache
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5432): MountEmulatedStorage()
E/Zygote  ( 5432): v2
I/libpersona( 5432): KNOX_SDCARD checking this for 10120
I/libpersona( 5432): KNOX_SDCARD not a persona
I/SELinux ( 5432): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5432): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5432): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5432 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 4560:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
W/ResourcesManager( 5135): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5135): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 5432): TimaSignature is unavailable
D/ActivityThread( 5432): Added TimaKeyStore provider
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5326): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/ResourcesManager( 5432): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/art     ( 1018): Explicit concurrent mark sweep GC freed 188599(12MB) AllocSpace objects, 3(3MB) LOS objects, 33% free, 27MB/40MB, paused 2.787ms total 175.340ms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
W/libprocessgroup( 1018): failed to open /acct/uid_10150/pid_4560/cgroup.procs: No such file or directory
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5326): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
V/JNIHelp ( 5135): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1018): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=5453 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 5453): MountEmulatedStorage()
E/Zygote  ( 5453): v2
I/libpersona( 5453): KNOX_SDCARD checking this for 10041
I/libpersona( 5453): KNOX_SDCARD not a persona
I/SELinux ( 5453): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5453): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5453): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5453): TimaSignature is unavailable
D/ActivityThread( 5453): Added TimaKeyStore provider
W/ActivityThread( 5135): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5135): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1b750467: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5135): Installed default security provider GmsCore_OpenSSL
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/SA      ( 5453): [SSP] onCreated
,I/ActivityManager( 1018): Killing 4104:com.google.android.gm/u0a101 (adj 15): empty #31
I/SA      ( 5453): [TPM] There is no property file
I/SA      ( 5453): [SCU] isHaveSA() - false
I/SA      ( 5453): [TPM] getModelProperty : null
I/SA      ( 5453): [TPM] getCSCProperty : null
I/SA      ( 5453): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 5453): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 5453): [DM] TFT FEATURE: false
I/SA      ( 5453): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 5453): [DM] init START
I/SA      ( 5453): [DM] This device is not a Vodafone
W/ResourceType( 5453): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 5453): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 5453): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 5453): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 5453): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 5453): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 5453): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 5453): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 5453): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 5453): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 5453): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 5453): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 5453): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 5453): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 5453): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 5453): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 5453): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
W/ResourceType( 5453): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 5453): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 5453): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 5453): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 5453): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 5453): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 5453): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 5453): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
I/SA      ( 5453): [SCU] isHaveSA() - false
I/SA      ( 5453): support phone number id : false
I/SA      ( 5453): [DM] Supports Ref Jpn : true
I/SA      ( 5453): [DM] init END
I/SA      ( 5453): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
I/SA      ( 5453): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10174 extra.user_handle.:0 ]
I/ActivityManager( 1018): Killing 3643:com.google.android.talk/u0a104 (adj 15): empty #31
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
D/ChimeraCfgMgr( 1849): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1849): Module APK com.google.android.play.games already loaded
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
W/libprocessgroup( 1018): failed to open /acct/uid_10101/pid_4104/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10104/pid_3643/cgroup.procs: No such file or directory
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/AndroidRuntime( 5475): 
D/AndroidRuntime( 5475): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5475): CheckJNI is OFF
D/AndroidRuntime( 5475): readGMSProperty: start
D/AndroidRuntime( 5475): readGMSProperty: already setted!!
D/AndroidRuntime( 5475): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5475): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5475): readGMSProperty: end
D/AndroidRuntime( 5475): addProductProperty: start
E/Zygote  ( 5486): MountEmulatedStorage()
E/Zygote  ( 5486): v2
I/libpersona( 5486): KNOX_SDCARD checking this for 10057
I/libpersona( 5486): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5486 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
I/SELinux ( 5486): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5486): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5486): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Killing 4470:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
D/TimaKeyStoreProvider( 5486): TimaSignature is unavailable
D/ActivityThread( 5486): Added TimaKeyStore provider
W/libprocessgroup( 1018): failed to open /acct/uid_10040/pid_4470/cgroup.procs: No such file or directory
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5511): MountEmulatedStorage()
E/Zygote  ( 5511): v2
I/libpersona( 5511): KNOX_SDCARD checking this for 10010
I/libpersona( 5511): KNOX_SDCARD not a persona
I/SELinux ( 5511): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=5511 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/AffinityControl( 5475): AffinityControl: registerfunction enter
I/SELinux ( 5511): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5511): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/AndroidRuntime( 5475): Calling main entry com.android.commands.am.Am
D/TimaKeyStoreProvider( 5511): TimaSignature is unavailable
D/ActivityThread( 5511): Added TimaKeyStore provider
E/PersonaManagerService( 1018): inState():  stateMachine is null !!
I/PersonaManagerService( 1018): PersonaId don't exist
I/ActivityManager( 1018): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/ActivityManager( 1018): mDVFSHelper.acquire()
D/FocusedStackFrame( 1018): Set to : 0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1018): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1018): *FMB* installDecor flags : 25362712
E/Zygote  ( 5532): MountEmulatedStorage()
I/ActivityManager( 1018): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5532 uid=10174 gids={50174, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1018): Focused application set to: xxxx
E/Zygote  ( 5532): v2
I/libpersona( 5532): KNOX_SDCARD checking this for 10174
D/InputDispatcher( 1018): Focus left window: 1493
I/libpersona( 5532): KNOX_SDCARD not a persona
D/AndroidRuntime( 5475): Shutting down VM
I/SELinux ( 5532): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5532): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5532): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/art     (  305): Explicit concurrent mark sweep GC freed 8746(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.140ms total 25.136ms
D/TimaKeyStoreProvider( 5532): TimaSignature is unavailable
D/ActivityThread( 5532): Added TimaKeyStore provider
V/WindowManager( 1018): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 619us total 16.815ms
D/PersonaManager( 1018): isKioskContainerExistOnDevice
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 674us total 17.037ms
D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
D/LocationManagerService( 1018): getProviders()=[passive]
I/SurfaceFlinger(  257): id=8 Removed Mauncher (6/8)
I/SurfaceFlinger(  257): id=8 Removed Mauncher (-2/8)
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
V/ActivityManager( 1018): Display changed displayId=0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
I/Mms/MmsApp( 5119):  start initViewCache mms
D/Mms/ComposeMessageFragment( 5119): [start]    fillCache consume time = 1888.341041
D/Mms/ComposeMessageFragment( 5119): fillCache, easy = false
V/ActivityThread( 1493): updateVisibility : ActivityRecord{390a449f token=android.os.BinderProxy@2be41c46 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1493): onTrimMemory. Level: 20
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  257): id=11 createSurf (1x1),1 flag=404, uhalitest
D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/AbsListView( 5119): Get MotionRecognitionManager
D/MotionRecognitionService( 1018):  ssp status : false
D/Mms/ComposeMessageFragment( 5119): [end]    fillCache consume time = 87.590104
W/art     ( 5475): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,I/UpdateIcingCorporaServi( 5486): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/WebViewFactory( 5532): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,I/LibraryLoader( 5532): Time to load native libraries: 2 ms (timestamps 2295-2297)
,I/LibraryLoader( 5532): Expected native library version number "",actual native library version number ""
,I/splitIntent( 1018): Queue : backgroundsplit_2 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,D/Mms/BubbleViewCache( 5119): fillCache bubble = 1
,I/ActivityManager( 1018): Killing 4989:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,V/WebViewChromiumFactoryProvider( 5532): Binding Chromium to main looper Looper (main, tid 1) {3e2a5dd7}
,I/LibraryLoader( 5532): Expected native library version number "",actual native library version number ""
,I/chromium( 5532): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5532): Initializing chromium process, singleProcess=true
,W/art     ( 5532): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5532): ApplicationContext is null in ApplicationStatus
,W/chromium( 5532): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5532): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,I/UpdateIcingCorporaServi( 5486): UpdateCorporaTask done [took 122 ms] updated apps [took 122 ms] 
,E/libEGL  ( 5532): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5532): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5532): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5532): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5532): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5532): Local Branch: 
I/Adreno-EGL( 5532): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5532): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5532):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/ActivityManager( 1018): Killing 4397:com.google.android.music:main/u0a111 (adj 15): empty #31
,D/BluetoothAdapter( 5532): 165504226: getState() :  mService = null. Returning STATE_OFF
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_4989/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10111/pid_4397/cgroup.procs: No such file or directory
,W/ActivityManager( 1018): Activity pause timeout for ActivityRecord{2db4b9cf u0 com.test.thalitest/.MainActivity t233}
,W/art     ( 5532): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5532): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 5532): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 5532): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 5532): CordovaWebView is running on device made by: samsung
,W/art     ( 5532): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 5532): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5532): Render dirty regions requested: true
,D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
,W/chromium( 5532): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,V/ActivityThread( 5532): updateVisibility : ActivityRecord{2f7c9919 token=android.os.BinderProxy@2476ec63 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PhoneWindow( 5532): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 5532): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  257): id=12 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1018): Focus entered window: 5532,
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 5532): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 5532): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5532): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 5532): Enabling debug mode 0
,D/SSRM:n  ( 1018): SIOP:: AP = 380
,D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/PanelView( 1181): There is/are notification(s) 
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/SamsungIME( 1772): getCurrentCandidateView
,I/ActivityManager( 1018): Displayed Component not be shown by security: +737ms (total +813ms)
,W/ActivityManager( 1018): mDVFSHelper.release()
I/Timeline( 1018): Timeline: Activity_windows_visible id: ActivityRecord{2db4b9cf u0 com.test.thalitest/.MainActivity t233} time:72831
,W/IInputConnectionWrapper( 5532): showStatusIcon on inactive InputConnection
,I/SurfaceFlinger(  257): id=11 Removed uhalitest (7/9)
,I/SurfaceFlinger(  257): id=11 Removed uhalitest (-2/9)
,I/Timeline( 5532): Timeline: Activity_idle id: android.os.BinderProxy@2476ec63 time:72851
,D/SamsungIME( 1772): Dismiss ExpandCandiate
,I/SamsungIME( 1772): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1772): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1772): KeybaordView init() : load resources
,W/BindingManager( 5532): Cannot call determinedVisibility() - never saw a connection for the pid: 5532
,I/SamsungIME( 1772): getCurrentKeyboard
I/SamsungIME( 1772): getTextKeyboard
,D/SamsungIME( 1772): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/JsMessageQueue( 5532): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5532): JniHelper::setJavaVM(0xb6fad450), pthread_self() = -1219463328
,I/chromium( 5532): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/SMD     (  288): DCD OFF
,D/AcmsKeyStoreHelper( 5185):  getKeyStoreForApplication Enter
,I/AcmsKeyStoreHelper( 5185): Key Store exist
,I/AcmsKeyStoreHelper( 5185): Hence loading the keystore file
,D/AcmsKeyStoreHelper( 5185):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 5185): getKeyStoreForApplication success 
D/AcmsCore( 5185): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 5185): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5185): Decrementing - Counter value: 1
D/AcmsCore( 5185): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 5185): This is NOT a valid MirrorLink app
D/AcmsCore( 5185): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 5185): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5185): Decrementing - Counter value: 0
,D/AcmsServiceMonitor( 5185): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 5185): getSvcCounter - Counter value: 0
,D/AcmsService( 5185): Enter onDestroy
I/AcmsService( 5185): cleanUp(): inside service clean up
D/AcmsCore( 5185): AcmsCore: inside DeInit
,D/AcmsCore( 5185): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 5185): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 5185): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 5185): KeyStoreHelper: inside cleanup
,D/AcmsAppEntryInterface( 5185): AppEntryInterface: Inside CleanUp
D/AcmsServiceMonitor( 5185): getSvcCounter - Counter value: 0
,D/AcmsService( 5185): killing acms process
I/Process ( 5185): Sending signal. PID: 5185 SIG: 9
,I/ActivityManager( 1018): Process ACMS.Process (pid 5185)(adj 0) has died(37,1096)
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/jxcore-log( 5532): Initializing JXcore engine
W/jxcore-log( 5532): JXcore engine is ready
,E/audit   ( 1943): type=1400 msg=audit(1455029370.451:203): avc:  denied  { ioctl } for  pid=5585 comm="Thread-961" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1943):  SEPF_SM-A500FU_5.0.2_0027
E/audit   ( 1943): type=1300 msg=audit(1455029370.451:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9dcff8f8 items=0 ppid=305 ppcomm=main pid=5585 auid=4294967295 uid=10174 gid=10174 euid=10174 suid=10174 fsuid=10174 egid=10174 sgid=10174 fsgid=10174 ses=4294967295 tty=(none) comm="Thread-961" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1943): type=1320 msg=audit(1455029370.451:203): 
,W/jxcore-log( 5532): Starting JXcore engine
,W/jxcore-log( 5532): Platform android
W/jxcore-log( 5532): 
W/jxcore-log( 5532): Process ARCH arm
W/jxcore-log( 5532): 
,I/ActivityManager( 1018): Killing 4258:flipboard.app/u0a98 (adj 15): empty #31
,I/jxcore-log( 5532): JXcore Cordova bridge is ready!
I/jxcore-log( 5532): 
,W/jxcore-log( 5532): JXcore engine is started
,E/jxcore  ( 5532): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 5532): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5532): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,D/FocusedStackFrame( 1018): Set to : 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,D/InputDispatcher( 1018): Focused application set to: xxxx
D/InputDispatcher( 1018): Focus left window: 5532
,W/libprocessgroup( 1018): failed to open /acct/uid_10098/pid_4258/cgroup.procs: No such file or directory
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,I/ActivityManager( 1018): Killing 4887:com.google.android.gms:car/u0a12 (adj 15): empty #31
,W/PluginManager( 5532): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 20ms. Plugin should use CordovaInterface.getThreadPool().
,I/SurfaceFlinger(  257): id=12 Removed NainActivit (6/8)
I/SurfaceFlinger(  257): id=12 Removed NainActivit (-2/8)
,W/ActivityManager( 1018): mDVFSHelper.acquire()
,V/WindowManager( 1018): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,D/Launcher( 1493): onRestart, Launcher: 956068777
,D/Launcher( 1493): onStart, Launcher: 956068777
D/Launcher.HomeView( 1493): onStart
D/Launcher( 1493): onResume, Launcher: 956068777
,D/SettingsProvider( 1018): name = kids_home_mode
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10007
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
D/Launcher.HomeView( 1493): onResume
,D/Launcher( 1493): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/MenuAppsGridFragment( 1493): onResume
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
D/WallpaperManager( 1493): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1493): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
I/splitIntent( 1018): Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=5, mSplitNum[2]=7, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=9
I/splitIntent( 1018): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,D/GalleryCacheReady( 4486): Receive : home resume
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,D/Recents_RecreateReceiver( 2443): onReceive by home
,D/Mms/UIEventReceiver( 5119): ui event
,D/ActivityManager( 1018): handle home activity for 0
I/WallpaperManagerService( 1018): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1018): post home show event for user 0
D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
D/WallpaperManagerService( 1018):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1018): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
D/Launcher.HomeView( 1493): onPause
,D/Launcher( 1493): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
W/BroadcastQueue( 1018): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1493, uid=10007) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,V/TaskCloserActivity( 5021): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1018): failed to open /acct/uid_10012/pid_4887/cgroup.procs: No such file or directory
,E/Zygote  ( 5588): MountEmulatedStorage()
E/Zygote  ( 5588): v2
I/libpersona( 5588): KNOX_SDCARD checking this for 10139
I/libpersona( 5588): KNOX_SDCARD not a persona
,I/SELinux ( 5588): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/ActivityManager( 1018): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=5588 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,I/SELinux ( 5588): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 5588): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/SurfaceFlinger(  257): id=13 createSurf (720x1280),1 flag=4, Mauncher
,D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/InputDispatcher( 1018): Focus entered window: 1493
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 1493): log_dcs ThreadedRenderer::initialize entered! ,
,D/TimaKeyStoreProvider( 5588): TimaSignature is unavailable
,D/ActivityThread( 5588): Added TimaKeyStore provider
,D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/IInputConnectionWrapper( 5532): showStatusIcon on inactive InputConnection
W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SamsungIME( 1772): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,W/ResourcesManager( 5588): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 5588): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5588): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 5588): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 5588): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/PanelView( 1181): There is/are notification(s) 
,V/ActivityThread( 1493): updateVisibility : ActivityRecord{390a449f token=android.os.BinderProxy@2be41c46 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,D/Launcher.HomeView( 1493): onStop
,I/Timeline( 1493): Timeline: Activity_idle id: android.os.BinderProxy@2be41c46 time:75179
,W/ActivityManager( 1018): mDVFSHelper.release()
,I/Timeline( 1018): Timeline: Activity_windows_visible id: ActivityRecord{2773a096 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t232} time:75198
,I/splitIntent( 1018): Queue : backgroundsplit_1 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1018): Killing 3984:com.sec.spp.push/u0a35 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,V/TaskCloserActivity( 5021): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,D/PersonaManager( 1018): isKioskContainerExistOnDevice
,W/libprocessgroup( 1018): failed to open /acct/uid_10035/pid_3984/cgroup.procs: No such file or directory
,D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,I/ConfigService( 1697): onDestroy,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4208, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1181): level :100 plugged : 2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8
,E/Watchdog( 1018): !@Sync 2
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,V/AlarmManager( 1018): waitForAlarm result :8
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/PackageManager( 1018): [MSG] MCS_UNBIND
,I/ActivityManager( 1018): Killing 4721:com.sec.spp.push:RemoteNotiProcess/u0a35 (adj 15): empty #31
,W/libprocessgroup( 1018): failed to open /acct/uid_10035/pid_4721/cgroup.procs: No such file or directory
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,V/AlarmManager( 1018): waitForAlarm result :4
,D/NtpTrustedTime( 1018): forceRefresh() from cache miss
,D/EnterpriseController(  278): uids 1000
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 1000
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10012
,D/EnterpriseController(  278): uids 1000
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 1000
,D/NtpTrustedTime( 1018): forceRefresh Fail.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5616): MountEmulatedStorage(),
E/Zygote  ( 5616): v2
I/libpersona( 5616): KNOX_SDCARD checking this for 10104
I/libpersona( 5616): KNOX_SDCARD not a persona,
I/SELinux ( 5616): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/ActivityManager( 1018): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5616 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SELinux ( 5616): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 5616): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5616): TimaSignature is unavailable
,D/ActivityThread( 5616): Added TimaKeyStore provider
,W/ResourcesManager( 5616): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 5616): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 5616): MmsConfig.loadMmsSettings
I/Babel_SMS( 5616): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel_SMS( 5616): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5616): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5616): MmsConfig.loadFromResources
,E/Babel_SMS( 5616): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 5616): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 0
,W/QCamera2Factory(  283): getCameraInfo: X
,W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 1
,W/QCamera2Factory(  283): getCameraInfo: X
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/Settings( 5616): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5616): startup - clean
,I/Babel   ( 5616): deleted: false for 0
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,W/VideoCapabilities( 5616): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5616): Unsupported mime audio/evrc
,W/AudioCapabilities( 5616): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5616): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 5616): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 5616): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 5616): Unsupported mime audio/x-ima
,W/AudioCapabilities( 5616): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5616): Unsupported mime audio/evrc
,W/VideoCapabilities( 5616): Unsupported mime video/wvc1
,W/VideoCapabilities( 5616): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 5616): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 5616): Unsupported mime video/wvc1
,W/VideoCapabilities( 5616): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 5616): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 5616): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 5616): Unsupported mime video/mp43
,W/VideoCapabilities( 5616): Unsupported mime video/sorenson
,W/VideoCapabilities( 5616): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5616): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5616): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5616): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5616): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5616): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager( 1018): Killing 5105:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,I/vclib   ( 5616): onServiceConnected
,W/Babel   ( 5616): Attempted to change video mute state without an active call.
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/libprocessgroup( 1018): failed to open /acct/uid_10100/pid_5105/cgroup.procs: No such file or directory
,I/PowerManagerService( 1018): [PWL] Off : 30s ago
,I/PowerManagerService( 1018): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1018): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1018): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=1849, ws=null) (elapsedTime=48938)
,D/SSRM:n  ( 1018): SIOP:: AP = 350
,E/SQLiteLog( 1697): (10) POSIX Error : 11 SQLite Error : 3850
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 1018): Waited long enough for: ServiceRecord{3931d42b u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4220, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1018): stay LED for charging
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1018): waitForAlarm result :4
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1697): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1697): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1697): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1697): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4853): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4853): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4853): [1] 5.onFinished: Scheduling replication attempt 2.
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 330,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4227, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2,
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 50s ago
,D/SSRM:n  ( 1018): SIOP:: AP = 310
,E/SMD     (  288): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :8
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4230, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1181): level :100 plugged : 2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  288): DCD OFF
,D/FactoryTest( 4757): Not factory mode
,D/FactoryTest( 4757): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 4757): DRIVER_TIME_OUT 60s lapsed,
D/MTPRx   ( 4757): still no open session command from host, so toast
W/ContextImpl( 4757): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 ,
W/ContextImpl( 4757): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,I/Timeline( 4757): Timeline: Activity_launch_request id:com.android.settings time:107853,
E/PersonaManagerService( 1018): inState():  stateMachine is null !!
I/PersonaManagerService( 1018): PersonaId don't exist,
I/ActivityManager( 1018): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.settings,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1018): mDVFSHelper.acquire()
,D/FocusedStackFrame( 1018): Set to : 0
,D/PersonaManager( 1018): isKioskContainerExistOnDevice
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.settings
D/InputDispatcher( 1018): Focused application set to: xxxx
D/InputDispatcher( 1018): Focus left window: 1493,
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
E/MTPRx   ( 4757): started activity for popup
,D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,W/ResourcesManager( 4757): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 4757): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 4757): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4757): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4757): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4757): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 4757): PREF_DONT_ASK_AGAIN : true
,D/FocusedStackFrame( 1018): Set to : 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.settings
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/InputDispatcher( 1018): Focused application set to: xxxx
,D/InputDispatcher( 1018): Focus entered window: 1493
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService( 1018): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@90704c attribute=null, token = android.os.BinderProxy@36a9ad9e
,D/SettingsReceiverActivity( 4757): dev.kiessupport is : TRUE
,D/PhoneWindow( 4757): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 4757): *FMB* installDecor flags : 8388610
,E/Watchdog( 1018): !@Sync 3
,I/Atfwd_Sendcmd(  316): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  316): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4,
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,V/AlarmManager( 1018): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManagerEXT( 1018): <AppSync3 Whitelist>
,V/AlarmManagerEXT( 1018): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/SecKeyguardClockView( 1181): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1181): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1181): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SViewCoverWidget( 1181): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SViewCoverWidget( 1181): Weather changed action :android.intent.action.TIME_TICK
,D/SViewCoverWidget( 1181): isEmergencyModeEnabled = false, isKidsModeEnabled = false, isWeatherWidgetEnabled = true
,D/daemonapp( 1282): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/SViewCoverWidget( 1181): getCheckCurrent: result = 0
,D/daemonapp( 1282): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/SViewCoverWidget( 1181): cityId=
,D/SViewCoverWidget( 1181): cityId=
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1697): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1697): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1697): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1697): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 34188(2016KB) AllocSpace objects, 19(304KB) LOS objects, 33% free, 27MB/40MB, paused 2.309ms total 138.320ms
,D/Finsky  ( 4853): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4853): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4853): [1] 5.onFinished: Scheduling replication attempt 3.
,W/ActivityManager( 1018): mDVFSHelper.release()
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 310
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4225, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 300
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4230, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1018): stay LED for charging
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1181): level :100 plugged : 2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1018): [PWL] Off : 75s ago
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 2,
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1697): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1697): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1697): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1697): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4853): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4853): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4853): [1] 5.onFinished: Scheduling replication attempt 4.
,D/SSRM:n  ( 1018): SIOP:: AP = 300
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4233, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1018): stay LED for charging
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1018): !@Sync 4,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 290,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :4,
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/NtpTrustedTime( 1018): forceRefresh() from cache miss
,D/EnterpriseController(  278): uids 1000
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 1000
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10012
D/EnterpriseController(  278): uids 1000
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 1000
,D/NtpTrustedTime( 1018): forceRefresh Fail.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,E/SMD     (  288): DCD OFF
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1697): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1697): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1697): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1697): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4853): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4853): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4853): [1] 5.onFinished: Scheduling replication attempt 5.
,D/SSRM:n  ( 1018): SIOP:: AP = 290,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4231, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1018): Plugged
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1018): [PWL] Off : 105s ago,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  288): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :8,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4235, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1018): Plugged
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1018): !@Sync 5
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/SecKeyguardClockView( 1181): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1181): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK,
I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1181): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SViewCoverWidget( 1181): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SViewCoverWidget( 1181): Weather changed action :android.intent.action.TIME_TICK
,D/SViewCoverWidget( 1181): isEmergencyModeEnabled = false, isKidsModeEnabled = false, isWeatherWidgetEnabled = true
,D/daemonapp( 1282): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/SViewCoverWidget( 1181): getCheckCurrent: result = 0
,D/daemonapp( 1282): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/SViewCoverWidget( 1181): cityId=
,D/SViewCoverWidget( 1181): cityId=
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1697): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1697): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1697): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1697): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1697): Explicit concurrent mark sweep GC freed 18609(1054KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 10MB/17MB, paused 1.930ms total 61.382ms
,D/Finsky  ( 4853): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4853): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4853): [1] 5.onFinished: Giving up after 6 failures.,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 290,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4232, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4236, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 140s ago
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 6
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4237, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false,
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/NtpTrustedTime( 1018): forceRefresh() from cache miss
,D/EnterpriseController(  278): uids 1000
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 1000
,D/EnterpriseController(  278): uids 1000
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 1000,
D/NtpTrustedTime( 1018): forceRefresh Fail.,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,I/Atfwd_Sendcmd(  316): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  316): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4237, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1181): level :100 plugged : 2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/Watchdog( 1018): !@Sync 7
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1018): [PWL] Off : 180s ago,
,D/SSRM:n  ( 1018): SIOP:: AP = 290,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 2,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 8,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4237, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged,
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 4
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 225s ago
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10012
,D/SecKeyguardClockView( 1181): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1181): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,E/Watchdog( 1018): !@Sync 9
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1181): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167],
,D/SViewCoverWidget( 1181): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SViewCoverWidget( 1181): Weather changed action :android.intent.action.TIME_TICK
,D/SViewCoverWidget( 1181): isEmergencyModeEnabled = false, isKidsModeEnabled = false, isWeatherWidgetEnabled = true
,D/daemonapp( 1282): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/SViewCoverWidget( 1181): getCheckCurrent: result = 0
,D/daemonapp( 1282): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/SViewCoverWidget( 1181): cityId=
,D/SViewCoverWidget( 1181): cityId=
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 290,
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1018): initializing...
,I/TLC_TIMA_PKM_initialize( 1018): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1018): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1018): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1018): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1018): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1018): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1018): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1018): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1018): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1018): Loaded image: APP id = 9
,I/TZ: qc_tlc_communication( 1018): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1018): Trustlet response is completed
,E/SMD     (  288): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4233, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged,
D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate,
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1018): !@Sync 10
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,I/Atfwd_Sendcmd(  316): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  316): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4237, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/PowerManagerService( 1018): [PWL] Off : 275s ago
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 11
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1697): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1697): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1697): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1697): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/GLSActivity( 1697): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1697): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1697): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1697): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1697): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1697): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1697): 	at android.os.Binder.execTransact(Binder.java:461)
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
D/PersonaManager( 1181): isKioskContainerExistOnDevice
,D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,E/PlayEventLogger( 4853): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4853): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4853): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 4853): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4853): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 4853): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4853): 	at android.os.Binder.execTransact(Binder.java:461)
D/PersonaManager( 1181): isKioskContainerExistOnDevice
W/System  ( 4853): Ignoring header User-Agent because its value was null.
I/System.out( 4853): (HTTPLog)-Static: isSBSettingEnabled false
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
D/EnterpriseController(  278): uids 10028
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10028
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 2
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 280,
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4238, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1018): !@Sync 12
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 330s ago
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4237, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4238, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1018): stay LED for charging,
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged,
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1181): level :100 plugged : 2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4237, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1018): stay LED for charging
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1018): !@Sync 13
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 14,
,I/Atfwd_Sendcmd(  316): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  316): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1018): [PWL] Off : 390s ago,
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1018): !@Sync 15,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4237, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 270,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/bootchecker(  310): bootchecker wake up!!
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 3
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 270,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1018): !@Sync 16,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:99, scale:100, status:2, health:2, present:true, voltage: 4237, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/PowerManagerService( 1018): [PSM] lowPowerModeEnabled: false (mLowPowerModeSetting: false, mAutoLowPowerModeConfigured: false, mBatteryLevel: 99, mLowBatteryTriggerLevel: 0)
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 99
D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :99 plugged : 2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1018): [PWL] Off : 455s ago
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,V/AlarmManager( 1018): waitForAlarm result :8
V/AlarmManager( 1018): No more alarm at this time.nowELAPSED=523960 batch.start=561931
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1018): !@Sync 17,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/SSRM:n  ( 1018): SIOP:: AP = 270,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 270,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:99, scale:100, status:2, health:2, present:true, voltage: 4238, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService( 1018): Plugged
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 99
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :99 plugged : 2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1018): !@Sync 18,
,I/Atfwd_Sendcmd(  316): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  316): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:99, scale:100, status:2, health:2, present:true, voltage: 4237, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 99
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:99 status:2 health:2,
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :99 plugged : 2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4,
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10012
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/SecKeyguardClockView( 1181): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1181): HomeTimezone(): 1
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1181): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SViewCoverWidget( 1181): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SViewCoverWidget( 1181): Weather changed action :android.intent.action.TIME_TICK
,D/SViewCoverWidget( 1181): isEmergencyModeEnabled = false, isKidsModeEnabled = false, isWeatherWidgetEnabled = true,
,D/daemonapp( 1282): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/SViewCoverWidget( 1181): getCheckCurrent: result = 0
,D/daemonapp( 1282): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/SViewCoverWidget( 1181): cityId=
,D/SViewCoverWidget( 1181): cityId=
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 280
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 525s ago,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,I/Atfwd_Daemon(  316): Stop the daemon....,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,V/AlarmManager( 1018): waitForAlarm result :8,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1018): !@Sync 19
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 270,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:99, scale:100, status:2, health:2, present:true, voltage: 4238, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 99
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :99 plugged : 2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1018): !@Sync 20
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:99, scale:100, status:2, health:2, present:true, voltage: 4237, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 99
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :99 plugged : 2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1018): !@Sync 21,
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1697): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1697): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1697): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1697): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/GLSActivity( 1697): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1697): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1697): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1697): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1697): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1697): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1697): 	at android.os.Binder.execTransact(Binder.java:461)
D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
E/PlayEventLogger( 4853): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4853): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4853): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 4853): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4853): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 4853): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4853): 	at android.os.Binder.execTransact(Binder.java:461)
W/System  ( 4853): Ignoring header User-Agent because its value was null.
I/System.out( 4853): (HTTPLog)-Static: isSBSettingEnabled false
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,D/EnterpriseController(  278): uids 10028
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10028
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 600s ago
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): !@[BatteryInfo] type : 3, read from efs = 0
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4236, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/LightsService( 1018): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1018) 
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=3) set On
,D/BatteryService( 1018): turn on LED for fully charged
E/lights  ( 1018): write_int failed to open -1
D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/PowerManagerService( 1018): [PSM] lowPowerModeEnabled: false (mLowPowerModeSetting: false, mAutoLowPowerModeConfigured: false, mBatteryLevel: 100, mLowBatteryTriggerLevel: 0)
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/SecContentProvider2( 1018): uri = 14 selection = getSealedState,
,D/SecContentProvider2( 1018): mCursor = null
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = -1
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId -1 pkgname com.android.systemui
,I/ValidateNoPeople( 1018): skipping global notification
D/WindowManager( 1018): showStatusBarByNotification() mOpenByNotification=false
,D/PowerManagerService( 1018): [api] acquire WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1181
,I/PowerManagerService( 1018): !@[ps] Screen__On  - 1 :  wl: PowerUI.Notification (14)
I/PowerManagerService( 1018): Waking up from sleep (uid 10054)...
,D/PowerManagerService( 1018): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 1018): [s] UserActivityState : 0 -> 1
D/PowerManagerService( 1018): [PWL] sb acquire: PowerManagerService.Display
V/KeyguardServiceDelegate( 1018): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@2f60b7f6)
I/DisplayPowerController( 1018): Blocking screen on until initial contents have been drawn.
,D/WindowOrientationListener( 1018): sensor enabled
I/Sensors ( 1018): AccelerometerSensor(0) setDelay : 200000000(ns)
D/DisplayPowerController( 1018): getFinalBrightness : Summary is 5 -> 5
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/KeyguardViewMediator( 1181): onScreenTurnedOn, seq = 2
D/SViewCoverView( 1181): level :100 plugged : 2
,D/DisplayPowerController( 1018): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/KeyguardViewMediator( 1181): notifyScreenOnLocked
D/DisplayPowerController( 1018): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1018): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/libsuspend( 1018): !@autosuspend_wakeup_count_disable
D/KeyguardViewMediator( 1181): handleNotifyScreenOn
,D/StatusBarKeyguardViewManager( 1181): onScreenTurnedOn()
I/libsuspend( 1018): !@autosuspend_wakeup_count_disable done
D/DisplayManagerService( 1018): !@display_state: OFF -> ON
D/SensorService( 1018): [SO] changed settle time [0]
D/SurfaceFlinger(  257): Set power mode=2, type=0 flinger=0xb8f17690
D/qdhwcomposer(  257): hwc_setPowerMode: Setting mode 2 on display: 0
D/SensorService( 1018): [SO] setDelay [200000000]
D/SensorService( 1018): [SO] activate (ident=0xb789c5b0, enabled=1)
,D/Launcher( 1493): onRestart, Launcher: 956068777
E/qdutils (  257): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  257): int qdutils::getHDMINode(): Failed to find HDMI node
D/SensorService( 1018): [SO] AR_init
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,I/DisplayManagerService( 1018): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager( 1018): Display changed displayId=0
,D/SensorManager( 1018): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,D/SecKeyguardClockSingleView( 1181): onScreenTurnedOn
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/StatusBarKeyguardViewManager( 1181): callback.onShown()
,V/KeyguardServiceDelegate( 1018): **** SHOWN CALLED ****
D/DisplayPowerController( 1018): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
,I/DisplayPowerController( 1018): Unblocked screen on after 43 ms
D/DisplayPowerState( 1018): !@ ColorFade exit
,I/SurfaceFlinger(  257): id=10 Removed DolorFade (8/8)
,E/libEGL  ( 1018): call to OpenGL ES API with no current context (logged once per thread)
D/PowerManagerService( 1018): Excessive delay in ColorFade : dismiss: 23ms
D/DisplayPowerController( 1018): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1018): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/lights  ( 1018): lcd : 5 +
D/lights  ( 1018): lcd : 5 -
D/DisplayPowerController( 1018): getFinalBrightness : Summary is 5 -> 5
I/SurfaceFlinger(  257): id=10 Removed DolorFade (-2/8)
D/DisplayPowerController( 1018): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 1018): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1018): SecHardwareInterface.setBatteryADC : true
,D/PersonaManager( 1018): isKioskContainerExistOnDevice
,D/Launcher( 1493): onStart, Launcher: 956068777
D/Launcher.HomeView( 1493): onStart
,D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
,I/PalmMotion( 1018): [PALM] 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
,E/MotionRecognitionService( 1018):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
I/PalmMotion( 1018): [PALM] SURFACE_PALM_SWIPE: 1
D/LightsService( 1018): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1018) 
D/PalmMotion( 1018): [PALM] SETTINGS : [TOUCH: true] [SWEEP: true]
D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/PalmMotion( 1018): [PALM] ACCEPTED : [default] PALM_CNT : 3, M_TOUCH : 1000.0, M_SWEEP : 100.0, E_SWEEP : 2.0, IGNORE_M_SWEEP : false
D/Launcher( 1493): onResume, Launcher: 956068777
,D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/SettingsProvider( 1018): name = kids_home_mode
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10007
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/Launcher.HomeView( 1493): onResume
,D/SamsungIME( 1772): showDlgMsgBox : false true true
,D/NfcService( 1455): call the applyRouting
,D/KnoxNotification( 1181): ----- inflateViews : modified publicViewLocal -----
,D/Launcher( 1493): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/SSRM:a  ( 1018): DeviceInfo:: 000000000000,
D/SSRM:a  ( 1018): SettingsAirViewInfo:: 000000000
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,D/KnoxNotification( 1181): ----- inflateViews : modified KnoxViewLocal -----
,D/MenuAppsGridFragment( 1493): onResume
,D/PersonaManager( 1181): PersonaID is invalid or persona doesn't exists. : -1
,I/rmt_storage(  272): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb86a87c8
I/rmt_storage(  272): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  272): wakelock acquired: 1, error no: 42
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1200978632)
D/ActivityManager( 1018): handle home activity for 0
I/WallpaperManagerService( 1018): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1018): post home show event for user 0
D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
,I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
D/WallpaperManagerService( 1018):  force update = false; persona id = 0; current user =0; current persona = 0
D/LightsService( 1018): [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 1018) 
I/PhoneStatusBar( 1181): Icon Only
D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
D/KnoxTimeoutHandler( 1018): handleHomeShow for 0 and current 0
D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
I/StatusBar( 1181): Icon Only
D/BatteryService( 1018): turn off LED
D/PanelView( 1181): There is/are notification(s) 
E/SmartFaceService( 1018): onReceive: android.intent.action.SCREEN_ON
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
E/lights  ( 1018): write_led_info failed to open -1
E/lights  ( 1018): write_led_info failed to open -1
E/lights  ( 1018): write_led_info failed to open -1
E/lights  ( 1018): write_led_info failed to open -1
E/lights  ( 1018): write_led_info failed to open -1
E/lights  ( 1018): write_led_info failed to open -1
,E/lights  ( 1018): write_led_info failed to open -1
E/lights  ( 1018): write_led_info failed to open -1
E/SmartFaceService( 1018): fail to set sysfs 1
E/lights  ( 1018): write_led_info failed to open -1
W/System.err( 1018): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
W/System.err( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
,W/System.err( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:468)
W/System.err( 1018): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
,W/System.err( 1018): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1018): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1018): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1018): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1018): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1018): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1018): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
,W/System.err( 1018): ,	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1018): 	... 10 more
D/StatusBar.NetworkController( 1181): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
D/StatusBar.NetworkController( 1181): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/BatteryMeterView( 1181): onDraw batteryColor : -1
D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/qdhwcomposer(  257): hwc_setPowerMode: Done setting mode 2 on display 0
I/qdhwcomposer(  257): handle_blank_event: dpy:0 panel power state: 1
,E/qdutils (  257): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  257): int qdutils::getHDMINode(): Failed to find HDMI node
,D/InputMethodManagerService( 1018): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
D/SurfaceControl( 1018): Excessive delay in setPowerMode(): 158ms
D/PowerManagerService( 1018): Excessive delay in !@display_state: ON: 159ms
,I/Timeline( 1493): Timeline: Activity_idle id: android.os.BinderProxy@2be41c46 time:659737
,D/MISC PowerHAL( 1018): sysfs_write +: /sys/class/input/event3/device/enabled: 1,
D/MotionRecognitionService( 1018):   mReceiver.onReceive : ACTION_SCREEN_ON
D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/MISC PowerHAL( 1018): sysfs_write +: /sys/class/input/event1/device/enabled: 1
,E/MotionRecognitionService( 1018):  handler : SCREEN_ON end
,D/SecKeyguardClockView( 1181): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,I/WifiNative-HAL( 1018): startHal
,E/wifi    ( 1018): getStaticLongField sWifiHalHandle 0x9d01f7fc
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1200978632) wakelock released: 1, error no: 0
I/rmt_storage(  272): 
,I/WifiNative-HAL( 1018): Could not start hal
I/rmt_storage(  272): rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb86a87c8
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,D/SecKeyguardClockView( 1181): HomeTimezone(): 1
,V/UserPresentBroadcastReceiver( 1650): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,D/NotificationService( 1018): ACTION_SCREEN_ON
D/LightsService( 1018): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1018) 
D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
,D/audio_hw_primary(  283): adev_set_parameters: enter: screen_state=on
V/voice   (  283): voice_set_parameters: enter: screen_state=on
V/voice   (  283): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  283): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  283): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  283): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  283): adev_set_parameters: exit
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/SensorService( 1018): [SO] currT = 659791073000, prevT = 51881111000, diff = 607909962000, [0.172 0.115 10.190]
D/SensorService( 1018): [SO] Reset Rotation Old [100], Init [1]
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,D/IpRemoteDisplayController( 1018): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController( 1018): Bridge Server is not available
,I/splitIntent( 1018): Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=5, mSplitNum[2]=7, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=9
,I/splitIntent( 1018): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
D/MISC PowerHAL( 1018): sysfs_write -: /sys/class/input/event3/device/enabled: 1
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,D/Recents_RecreateReceiver( 2443): onReceive by home
,V/TaskCloserActivity( 5021): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,D/GalleryCacheReady( 4486): Receive : home resume
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
W/BroadcastQueue( 1018): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1493, uid=10007) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,D/Mms/UIEventReceiver( 5119): ui event
,I/splitIntent( 1018): Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.
,D/MISC PowerHAL( 1018): sysfs_write -: /sys/class/input/event1/device/enabled: 1
,D/MISC PowerHAL( 1018): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
,D/MISC PowerHAL( 1018): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
D/PowerManagerService-JNI( 1018): Excessive delay in MISC setInteractive(true) while turning screen on: 170ms
I/QCOM PowerHAL( 1018): Got set_interactive hint
,D/lights  ( 1018): button : 1 +
,D/PowerManagerService( 1018): Excessive delay in nativeSetInteractive(true): 173ms
,D/PowerManagerService( 1018): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 333ms
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/lights  ( 1018): button : 1 -
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SensorService( 1018): [SO] currT = 659991190000, prevT = 51881111000, diff = 608110079000, [0.172 0.077 10.094]
D/SensorService( 1018): [SO] 0.172 0.077 10.094
D/SensorService( 1018): [SO] [100 -> 255]
,D/SViewCoverWidget( 1181): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SViewCoverWidget( 1181): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SViewCoverWidget( 1181): Weather changed action :android.intent.action.TIME_TICK
,D/SViewCoverWidget( 1181): isEmergencyModeEnabled = false, isKidsModeEnabled = false, isWeatherWidgetEnabled = true
,D/daemonapp( 1282): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/SViewCoverWidget( 1181): getCheckCurrent: result = 0
,D/daemonapp( 1282): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/SViewCoverWidget( 1181): cityId=
,D/SViewCoverWidget( 1181): cityId=
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SQLiteLog( 1697): (10) POSIX Error : 11 SQLite Error : 3850
,D/GpsLocationProvider( 1018): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/PersonaManagerService( 1018): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler( 1018): MSG_ACTION_SCREEN_ON called
,D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
,I/NfcService( 1455): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/NfcService( 1455): call the applyRouting
,D/accuweather( 1588): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
,D/accuweather( 1588): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/accuweather( 1588): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/accuweather( 1588): [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,D/accuweather( 1588): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1588): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1588): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
D/accuweather( 1588): [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 2
,D/accuweather( 1588): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1588): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,E/accuweather( 1588): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 15 59
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.SCREEN_ON
,I/SamsungIME( 1772): getNextShiftState() cursorCapsMode : 0
,W/OpenGLRenderer( 1493): SFEffectCache::get: create texture(0xa34a1724): name, size, mSize = 40, 145188, 467252
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PowerManagerService( 1018): [PWL] sb release: PowerManagerService.Broadcasts
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,D/daemonapp( 1282): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1282): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1282): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1282): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1282): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1282): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1282): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1282): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1282): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1282): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1282): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1282): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
D/daemonapp( 1282): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1282): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1282): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1455050880000
D/daemonapp( 1282): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1455029956838
D/daemonapp( 1282): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1282): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/daemonapp( 1282): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1282): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1282): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1282): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 1282): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/lights  ( 1018): button : 0 +
,D/lights  ( 1018): button : 0 -
,D/SSRM:a  ( 1018): DeviceInfo:: 000000000000
,D/SSRM:a  ( 1018): SettingsAirViewInfo:: 000000000
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
,I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4221, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,D/SensorService( 1018): [SO] 0.172 0.057 10.094
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1018): !@Sync 22
,D/PowerManagerService( 1018): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1181 (0x0)
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 290,
,E/SMD     (  288): DCD OFF
,D/PowerManagerService( 1018): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 1018): getFinalBrightness : Summary is 1 -> 1
D/DisplayPowerController( 1018): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 1018): [s] DisplayPowerCallbacks : onStateChanged()
,D/DisplayPowerController( 1018): getFinalBrightness : Summary is 1 -> 1
,D/DisplayPowerController( 1018): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/lights  ( 1018): lcd : 1 +
,D/lights  ( 1018): lcd : 1 -
,D/DisplayPowerController( 1018): getFinalBrightness : Summary is 1 -> 1
D/DisplayPowerController( 1018): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/PowerManagerService( 1018): [s] UserActivityState : 2 -> 4
,I/PowerManagerService( 1018): Nap time (uid 1000)...
D/PowerManagerService( 1018): handleSandman : startDreaming: false  (canDreamLocked: false  canDozeLocked: false)
I/PowerManagerService( 1018): !@[ps] Screen__Off - 1 :  dream(timeout) (2)
I/PowerManagerService( 1018): Going to sleep due to screen timeout (uid 1000)...
D/PowerManagerService( 1018): [PWL] sb acquire: PowerManagerService.Broadcasts
,V/WindowOrientationListener( 1018): WindowOrientationListener disabled
D/SensorService( 1018): [SO] activate (ident=0xb789c5b0, enabled=0)
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
D/PowerManagerService( 1018): SecHardwareInterface.setBatteryADC : false
D/PowerManagerService( 1018): handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
D/PowerManagerService( 1018): handleSandman : startDream(true)
E/PowerManagerService( 1018): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService( 1018): Sleeping (uid 1000)...
D/PowerManagerService( 1018): [s] UserActivityState : 4 -> 0
,I/SurfaceFlinger(  257): id=14 createSurf (720x1280),-1 flag=20004, DolorFade
,D/SensorManager( 1018): unregisterListener ::   
,D/KeyguardViewMediator( 1181): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 1181): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1181): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1181): notifyScreenOffLocked
,D/Launcher.HomeView( 1493): onPause
,D/Launcher( 1493): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/KeyguardViewMediator( 1181): timeout : 5000
,D/PowerManagerService( 1018): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 33ms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,D/PowerManagerService( 1018): Excessive delay in ColorFade : initGLShaders: 11ms
,D/DisplayPowerController( 1018): ColorFade: onAnimationStart
D/DisplayPowerController( 1018): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1018): performScreenOffTransition : no brightness animation
,V/TaskCloserActivity( 5021): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
D/KeyguardViewMediator( 1181): setting alarm to turn off keyguard, seq = 2
D/KeyguardViewMediator( 1181): handleNotifyScreenOff
D/VolumePanel( 1181): onScreenTurnedOff()
D/VolumePanel( 1181): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
D/VolumePanel( 1181): mCoverBroadcastReceiver: Screen OFF end
,D/LightsService( 1018): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1018) 
,D/SecKeyguardClockSingleView( 1181): onScreenTurnedOff
D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
E/lights  ( 1018): write_int failed to open -1
D/BatteryService( 1018): turn on LED for fully charged
D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,W/System.err( 1018): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
E/SmartFaceService( 1018): onReceive: android.intent.action.SCREEN_OFF
W/System.err( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/SmartFaceService( 1018): fail to set sysfs 0
W/System.err( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:474)
W/System.err( 1018): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1018): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1018): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1018): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1018): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1018): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1018): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1018): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1018): 	... 10 more
,V/ActivityThread( 1493): updateVisibility : ActivityRecord{390a449f token=android.os.BinderProxy@2be41c46 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true,
D/Launcher.HomeView( 1493): onStop
,I/StatusBar( 1181): Icon Only
,D/PanelView( 1181): There is/are notification(s) 
,D/SamsungIME( 1772): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,D/MotionRecognitionService( 1018):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService( 1018):  handler : SCREEN_OFF end 
,I/WifiNative-HAL( 1018): startHal
D/NotificationService( 1018): ACTION_SCREEN_OFF
D/LightsService( 1018): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1018) 
,E/wifi    ( 1018): getStaticLongField sWifiHalHandle 0x9d01f7fc
I/WifiNative-HAL( 1018): Could not start hal
D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/audio_hw_primary(  283): adev_set_parameters: enter: screen_state=off
,V/voice   (  283): voice_set_parameters: enter: screen_state=off
V/voice   (  283): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  283): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  283): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  283): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  283): adev_set_parameters: exit
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/IpRemoteDisplayController( 1018): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 1018): Bridge Server is not available
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4220, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DisplayPowerState( 1018): !@ ColorFade entry
,D/DisplayPowerController( 1018): ColorFade: onAnimationEnd
,D/DisplayPowerController( 1018): getFinalBrightness : Summary is 0 -> 0
,D/lights  ( 1018): lcd : 0 +
,D/DisplayPowerController( 1018): performScreenOffTransition : no brightness animation
,D/lights  ( 1018): lcd : 0 -
,D/DisplayPowerController( 1018): getFinalBrightness : Summary is 0 -> 0
D/DisplayPowerController( 1018): performScreenOffTransition : no brightness animation
D/PowerManagerService( 1018): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1018): [PWL] sb release: PowerManagerService.Display
,D/MISC PowerHAL( 1018): sysfs_write +: /sys/class/input/event1/device/enabled: 0
D/MISC PowerHAL( 1018): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/MISC PowerHAL( 1018): sysfs_write +: /sys/class/input/event3/device/enabled: 0
,D/MISC PowerHAL( 1018): sysfs_write -: /sys/class/input/event3/device/enabled: 0
,D/MISC PowerHAL( 1018): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
,D/MISC PowerHAL( 1018): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
I/QCOM PowerHAL( 1018): Got set_interactive hint
,D/DisplayManagerService( 1018): !@display_state: ON -> OFF
,I/DisplayManagerService( 1018): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager( 1018): Display changed displayId=0
,D/SurfaceFlinger(  257): Set power mode=0, type=0 flinger=0xb8f17690
D/qdhwcomposer(  257): hwc_setPowerMode: Setting mode 0 on display: 0
,E/qdutils (  257): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  257): int qdutils::getHDMINode(): Failed to find HDMI node
,D/StatusBar.NetworkController( 1181): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
,D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/qdhwcomposer(  257): handle_blank_event: dpy:0 panel power state: 0
,E/qdutils (  257): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  257): int qdutils::getHDMINode(): Failed to find HDMI node
D/qdhwcomposer(  257): hwc_setPowerMode: Done setting mode 0 on display 0
D/SurfaceControl( 1018): Excessive delay in setPowerMode(): 253ms
D/PowerManagerService( 1018): Excessive delay in !@display_state: OFF: 258ms
,I/libsuspend( 1018): !@autosuspend_wakeup_count_enable
I/libsuspend( 1018): !@autosuspend_wakeup_count_enable done
D/PowerManagerService( 1018): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 267ms
I/PowerManagerService( 1018): [PWL] Off : 0s ago
I/PowerManagerService( 1018): [PWL]   PowerManagerService.Broadcasts: ref count=1
,D/GpsLocationProvider( 1018): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.SCREEN_OFF
,V/EmergencyMode( 1431): [EmergencyStateReceiver] binteractive [false] why[3]
,D/PersonaManagerService( 1018): ACTION_SCREEN_OFF onReceive
D/PersonaManagerServiceHandler( 1018): MSG_ACTION_SCREEN_OFF called
,D/NfcService( 1455): call the applyRouting
,D/accuweather( 1588): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 1588): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.SCREEN_OFF
,D/SViewCoverView( 1181): Move to page : HomePage
,D/accuweather( 1588): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/daemonapp( 1282): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 6
,D/accuweather( 1588): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1588): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1588): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1588): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,D/daemonapp( 1282): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,E/LibSecureUISvc( 1964): svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
,D/PowerManagerService( 1018): [PWL] sb release: PowerManagerService.Broadcasts
,D/daemonapp( 1282): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,D/accuweather( 1588): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1588): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1588): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
D/accuweather( 1588): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1588): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
,D/accuweather( 1588): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/accuweather( 1588): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardViewMediator( 1181): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/KeyguardViewMediator( 1181): doKeyguard: not showing because lockscreen is off
V/KeyguardEffectViewController( 1181): *** Keyguard wallpaper service already unbounded
,I/PowerManagerService( 1018): [PWL] Off : 5s ago
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4235, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8
,I/PowerManagerService( 1018): [PWL] Off : 15s ago
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1018): !@Sync 23
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4236, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1018): [PWL] Off : 30s ago
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
D/SecKeyguardClockView( 1181): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
D/SecKeyguardClockView( 1181): HomeTimezone(): 1,
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1181): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SViewCoverWidget( 1181): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SViewCoverWidget( 1181): Weather changed action :android.intent.action.TIME_TICK
,D/SViewCoverWidget( 1181): isEmergencyModeEnabled = false, isKidsModeEnabled = false, isWeatherWidgetEnabled = true
D/SSRM:n  ( 1018): SIOP:: AP = 270
,D/daemonapp( 1282): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/SViewCoverWidget( 1181): getCheckCurrent: result = 0
,D/daemonapp( 1282): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo,
,D/SViewCoverWidget( 1181): cityId=
,D/SViewCoverWidget( 1181): cityId=
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4243, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged,
D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate,
V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1018): !@Sync 24
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4236, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 1018): [PWL] Off : 50s ago
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4235, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged,
D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate,
V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1181): level :100 plugged : 2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4235, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged,
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1018): Plugged
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :8
,I/PowerManagerService( 1018): [PWL] Off : 75s ago
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1018): !@Sync 25,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4236, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4241, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4236, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 105s ago,
,E/SMD     (  288): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/SecKeyguardClockView( 1181): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1181): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1181): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SViewCoverWidget( 1181): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SViewCoverWidget( 1181): Weather changed action :android.intent.action.TIME_TICK
,D/SViewCoverWidget( 1181): isEmergencyModeEnabled = false, isKidsModeEnabled = false, isWeatherWidgetEnabled = true
,D/daemonapp( 1282): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/SViewCoverWidget( 1181): getCheckCurrent: result = 0
,D/daemonapp( 1282): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo,
,D/SViewCoverWidget( 1181): cityId=
,D/SViewCoverWidget( 1181): cityId=
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/Watchdog( 1018): !@Sync 26
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4233, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1181): level :100 plugged : 2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4236, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :8,
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1018): !@Sync 27
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 140s ago,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4235, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4236, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate,
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1181): level :100 plugged : 2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1018): !@Sync 28,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4236, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate,
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1181): level :100 plugged : 2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 180s ago
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4235, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4236, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1018): !@Sync 29
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4237, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4236, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,I/PowerManagerService( 1018): [PWL] Off : 225s ago
,I/PowerManagerService( 1018): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1018): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1018): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=1018, ws=null) (elapsedTime=14)
,E/SMD     (  288): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1018): !@Sync 30
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1018): !@Sync 31,
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1697): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1697): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1697): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1697): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/GLSActivity( 1697): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1697): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1697): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1697): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1697): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1697): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1697): 	at android.os.Binder.execTransact(Binder.java:461)
,D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/PlayEventLogger( 4853): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4853): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4853): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 4853): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4853): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 4853): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4853): 	at android.os.Binder.execTransact(Binder.java:461)
W/System  ( 4853): Ignoring header User-Agent because its value was null.
I/System.out( 4853): (HTTPLog)-Static: isSBSettingEnabled false
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,D/EnterpriseController(  278): uids 10028
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10028
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
,I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 275s ago
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1018): !@Sync 32,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4237, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4236, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1181): level :100 plugged : 2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4236, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/BatteryService( 1018): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8,
V/AlarmManager( 1018): No more alarm at this time.nowELAPSED=1003960 batch.start=1193616
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1018): !@Sync 33,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1018): [PWL] Off : 330s ago,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1018): !@Sync 34,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4235, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged,
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4236, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1018): !@Sync 35
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 390s ago
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1018): !@Sync 36,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4235, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4236, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1018): !@Sync 37,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4242, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1018): Plugged
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate,
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1181): level :100 plugged : 2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4235, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged,
D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 455s ago
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4242, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1018): !@Sync 38,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4235, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged,
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1181): level :100 plugged : 2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1018): !@Sync 39,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED,
D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4236, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged,
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged,
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 1018): waitForAlarm result :4
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10012
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.EventLogService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SecKeyguardClockView( 1181): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1181): HomeTimezone(): 1
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/EventLogService( 1849): Aggregate from 1455028689620 (log), 1455028689620 (data)
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1181): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SViewCoverWidget( 1181): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SViewCoverWidget( 1181): Weather changed action :android.intent.action.TIME_TICK
,D/SViewCoverWidget( 1181): isEmergencyModeEnabled = false, isKidsModeEnabled = false, isWeatherWidgetEnabled = true
,D/daemonapp( 1282): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/SViewCoverWidget( 1181): getCheckCurrent: result = 0
,D/daemonapp( 1282): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/SViewCoverWidget( 1181): cityId=
,D/SViewCoverWidget( 1181): cityId=
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4235, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1018): Plugged
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1181): level :100 plugged : 2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4243, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged,
D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF,
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,I/PowerManagerService( 1018): [PWL] Off : 525s ago
,I/PowerManagerService( 1018): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1018): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1018): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=1018, ws=null) (elapsedTime=106)
,I/UsageStatsService( 1018): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 1018): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 1018): Updating Usage Statistics in DB @ 1455030512024
,I/ApplicationUsage( 1018): Done Updating Usage Statistics in DB @ 1455030512027
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1018): !@Sync 40,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4235, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4240, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1181): level :100 plugged : 2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4245, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1181): level :100 plugged : 2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8,
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1018): !@Sync 41,
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1697): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1697): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1697): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1697): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1697): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/GLSActivity( 1697): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1697): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1697): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1697): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1697): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1697): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1697): 	at android.os.Binder.execTransact(Binder.java:461)
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,E/PlayEventLogger( 4853): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4853): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4853): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 4853): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4853): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 4853): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4853): 	at android.os.Binder.execTransact(Binder.java:461)
,W/System  ( 4853): Ignoring header User-Agent because its value was null.
D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/System.out( 4853): (HTTPLog)-Static: isSBSettingEnabled false
I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
D/EnterpriseController(  278): uids 10028
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10028
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4232, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4245, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
I/MotionRecognitionService( 1018): Plugged,
I/MotionRecognitionService( 1018): mGripSensorEnabled= false,
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4235, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1018): Plugged
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1018): !@Sync 42
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,TIME-OUT KILL (timeout was 1200000ms),E/SMD     (  288): DCD OFF
D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/AndroidRuntime( 6178): 
D/AndroidRuntime( 6178): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6178): CheckJNI is OFF
D/AndroidRuntime( 6178): readGMSProperty: start
D/AndroidRuntime( 6178): readGMSProperty: already setted!!
D/AndroidRuntime( 6178): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6178): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6178): readGMSProperty: end
D/AndroidRuntime( 6178): addProductProperty: start
E/AffinityControl( 6178): AffinityControl: registerfunction enter
D/AndroidRuntime( 6178): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1018): START PACKAGE DELETE: observer{567527555}
D/PackageManager( 1018): pkg{<packageName>}
D/PackageManager( 1018): user{0}
D/PackageManager( 1018): caller{2000}
D/PackageManager( 1018): flags{3}
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1018): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1018): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1018): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManager( 1018): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1018): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 1018): !@killApplicatoin: 10174, uninstall pkg
I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10174 user=-1: uninstall pkg
I/ActivityManager( 1018): Killing 5532:com.test.thalitest/u0a174 (adj 15): stop com.test.thalitest cause uninstall pkg
E/SMD     (  288): DCD OFF
I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10174 user=0: pkg removed
W/ActivityManager( 1018): CustomStartingWindow se packge removed so remove capture also
I/art     ( 3787): Explicit concurrent mark sweep GC freed 2487(148KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 6MB/11MB, paused 862us total 46.519ms
I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 1772): mOCRHelper is null
W/GeofencerStateMachine( 1650): Ignoring removeGeofence because network location is disabled.
I/art     ( 5486): Explicit concurrent mark sweep GC freed 377(26KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 8MB/11MB, paused 752us total 61.290ms
I/KLMS-2.5.183: ( 3464): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Feb 09 16:09:42 GMT+01:00 2016
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
D/EnterpriseDeviceManagerService( 1018): Package has changed for user 0
W/TextServicesManagerService( 1018): no available spell checker services found
D/EnterpriseDeviceManagerService( 1018): Admin package name: com.google.android.gms
I/KLMS-2.5.183: ( 3464): KLMSAbstractReciever(): onReceive().END.
D/RegisteredComponentCache( 1455): Collect Tech packages for Knox
D/PersonaManager( 1455): isKioskContainerExistOnDevice
I/splitIntent( 1018): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=28
I/splitIntent( 1018): base  index=28, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1018): other index=31, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6191): MountEmulatedStorage()
E/Zygote  ( 6191): v2
I/libpersona( 6191): KNOX_SDCARD checking this for 10094
I/libpersona( 6191): KNOX_SDCARD not a persona
I/SELinux ( 6191): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/KLMS-2.5.183: ( 3464): KLMSIntentService(): onCreate()
I/SELinux ( 6191): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/KLMS-2.5.183: ( 3464): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/ActivityManager( 1018): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6191 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
E/SELinux ( 6191): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.5.183: ( 3464): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/KLMS-2.5.183: ( 3464): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1018): mCursor = null
I/KLMS-2.5.183: ( 3464): KLMSIntentService(): PACKAGE_REMOVED
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/KLMS-2.5.183: ( 3464): KLMSIntentService(): listeningToPackageRemoved().START
D/TimaKeyStoreProvider( 6191): TimaSignature is unavailable
D/ActivityThread( 6191): Added TimaKeyStore provider
I/KLMS-2.5.183: ( 3464): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/art     ( 1018): Explicit concurrent mark sweep GC freed 42303(4MB) AllocSpace objects, 148(2MB) LOS objects, 33% free, 27MB/40MB, paused 4.400ms total 240.832ms
I/art     ( 1018): WaitForGcToComplete blocked for 157.216ms for cause Explicit
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/PersonaManager( 1455): isKioskContainerExistOnDevice
D/RegisteredServicesCache( 1455): empty dynamic service
D/elm:15183( 6191): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15183( 6191): ELMEngine.ELMEngine( context ).
D/elm:15183( 6191): MDMBridge.setEnterpriseBridge()
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
D/elm:15183( 6191): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:15183( 6191): ElmAgentService : onCreate()
D/elm:15183( 6191): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15183( 6191): MainReceiver.listeningToPackageRemoved()
D/elm:15183( 6191): MDMBridge.getInstance()
D/elm:15183( 6191): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:15183( 6191): MDMBridge.getAllLicenseInfoFromSDK()
I/KLMS-2.5.183: ( 3464): KLMSIntentService(): listeningToPackageRemoved().END
I/KLMS-2.5.183: ( 3464): KLMSIntentService(): onDestroy()
D/elm:15183( 6191): ElmAgentService : onDestroy().
W/ResourceType( 1018): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ResourcesManager( 1018): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/art     ( 1018): Explicit concurrent mark sweep GC freed 12258(597KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/40MB, paused 3.426ms total 182.171ms
D/PackageManager( 1018): delete codoeFile: 
D/AASAuninstall( 1018): userId = 0, info.removedAppID = -1, info.uid = 10174, packageName = com.test.thalitest
I/AASA_removePackage( 1018): UID=10174 Target=com.test.thalitest
D/PackageManager( 1018): result of delete: 1{567527555}
D/AndroidRuntime( 6178): Shutting down VM
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/RCPManagerService( 1018): PackageReceiver onReceive()
I/HarmonyEASService( 1018): onReceive : android.intent.action.PACKAGE_REMOVED for 0
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/KnoxMUMContainerPolicy( 1018): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1018): PackageRemovalReceiver::onReceive Enter
D/OTPFW   ( 1018): OtpDbHelper::getInstance New instance created
D/OTPFW   ( 1018): DBIntegrity::getInstance - New instance created
D/UsbSettingsManager( 1018): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 1018): onPackageRemoved : com.test.thalitest
D/OTPFW   ( 1018): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10174 container id = 0
I/OTPFW   ( 1018): ProvisionData::getAllEntries Enter
E/OTPFW   ( 1018): ProvisionData::getAllEntries Table is empty
D/BackupManagerService( 1018): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1018): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1018): uID is 10174
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
D/TaskPersister( 1018): removeObsoleteFile: deleting file=233_task.xml
V/EnterpriseBillingPolicy( 1018): uID is 10174
D/SSRM:aZ ( 1018): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
I/PCWCLIENTTRACE_PushUtil( 5168): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5168): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5168): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5168): [onReceive] - android.intent.action.PACKAGE_REMOVED
I/SA      ( 5453): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
I/SA      ( 5453): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10174 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
I/PackagesMonitor( 4486): PackagesMonitor onReceive :com.test.thalitest
D/Mms/FreeMessageStatusReceiver( 5119): onReceive, action : android.intent.action.PACKAGE_REMOVED
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
I/TactileAssist( 1018): enable value -1
I/TactileAssist( 1018): internal enable value -1
I/TactileAssist( 1018): intensity value -1
I/TactileAssist( 1018): saveAppList value true
I/TactileAssist( 1018): List of disabled apps :
D/Mms/FreeMessageReceiverService( 5119): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 5119): onHandleIntent: ACTION_PACKAGE_REMOVED
D/Compatibility( 5351): onReceive() it will make start service
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/Compatibility( 5351): onHandleIntent()
D/Compatibility( 5351): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10174, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/Compatibility( 5351): found: 2
D/Compatibility( 5351): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5351): skipping ResolveInfo{10cd0073 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5351): considering ResolveInfo{295e6b30 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5351): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5351): enabling receiver ResolveInfo{38fc73a9 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
E/Zygote  ( 6213): MountEmulatedStorage()
E/Zygote  ( 6213): v2
I/libpersona( 6213): KNOX_SDCARD checking this for 10003
I/libpersona( 6213): KNOX_SDCARD not a persona
I/SELinux ( 6213): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/Compatibility( 5351): enabling receiver ResolveInfo{c70ed2e com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
I/SELinux ( 6213): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6213 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
E/SELinux ( 6213): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Compatibility( 5351): enabling receiver ResolveInfo{13ed30cf com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 5351): enabling receiver ResolveInfo{ff70a5c com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
W/art     ( 6178): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
D/Compatibility( 5351): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
D/TimaKeyStoreProvider( 6213): TimaSignature is unavailable
D/ActivityThread( 6213): Added TimaKeyStore provider
D/UserAnalysis.PlaceProvider( 6213): PlaceProvider onCreate()
D/UserAnalysis.SecureDbManager( 6213): Key for secure DB is newly created
D/UserAnalysis.SecurePlaceDbHelper( 6213): SecurePlaceDbHelper() 
D/UserAnalysis( 6213): Create SecureDbHelper
D/IntelligenceServiceApplication( 6213): onCreate()
D/UserAnalysis.UserAnalysisBroadcastReceiver( 6213): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
E/SQLiteLog( 6213): (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 6213): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 6213): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6213): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6213): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6213): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6213): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6213): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6213): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6213): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6213): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6213): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6213): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6213): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6213): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6213): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 6213): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:69)
E/SQLiteDatabase( 6213): 	at com.samsung.android.intelligenceservice.IntelligenceServiceApplication$1.run(IntelligenceServiceApplication.java:46)
E/SQLiteDatabase( 6213): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 6213): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 6213): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6213): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6213): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6213): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6213): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6213): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper( 6213): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper( 6213): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 6213): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 6213): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 6213): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 6213): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 6213): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 6213): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 6213): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteOpenHelper( 6213): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteOpenHelper( 6213): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 6213): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteOpenHelper( 6213): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 6213): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 6213): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 6213): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:69)
E/SQLiteOpenHelper( 6213): 	at com.samsung.android.intelligenceservice.IntelligenceServiceApplication$1.run(IntelligenceServiceApplication.java:46)
E/SQLiteOpenHelper( 6213): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteOpenHelper( 6213): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteOpenHelper( 6213): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 6213): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteOpenHelper( 6213): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 6213): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 6213): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 6213): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper( 6213): Opened privacy in read-only mode
D/IntelligenceServiceApplication( 6213): no applications having user consent for prediction
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
V/PlaceDetection v1.0.19 ( 6213): [PlaceDetection::stopService] Service stopped.
W/ContextImpl( 5371): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
V/PlaceDetection v1.0.19 ( 6213): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
E/SQLiteLog( 6213): (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 6213): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 6213): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6213): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6213): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6213): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6213): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6213): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6213): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6213): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6213): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6213): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6213): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6213): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6213): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6213): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6213): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:204)
E/SQLiteDatabase( 6213): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:78)
E/SQLiteDatabase( 6213): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 6213): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 6213): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6213): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6213): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6213): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6213): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6213): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime( 6213): Shutting down VM
E/AndroidRuntime( 6213): FATAL EXCEPTION: main
E/AndroidRuntime( 6213): Process: com.samsung.android.intelligenceservice, PID: 6213
E/AndroidRuntime( 6213): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6213): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6213): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime( 6213): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime( 6213): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 6213): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 6213): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 6213): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/AndroidRuntime( 6213): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/AndroidRuntime( 6213): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime( 6213): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/AndroidRuntime( 6213): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime( 6213): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6213): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6213): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:204)
E/AndroidRuntime( 6213): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:78)
E/AndroidRuntime( 6213): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime( 6213): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 6213): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6213): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/AndroidRuntime( 6213): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6213): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6213): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 6213): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.samsung.android.intelligenceservice
D/RCPManager( 5406):  in createShortcut() for packageName: com.test.thalitest userId0
E/SQLiteLog( 5371): (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 5371): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 5371): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5371): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5371): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5371): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5371): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5371): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5371): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5371): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 5371): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 5371): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5371): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 5371): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5371): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5371): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5371): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
E/SQLiteDatabase( 5371): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
E/SQLiteDatabase( 5371): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5371): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5371): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5371): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 5371): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 5371): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 5371): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
W/System.err( 5371): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
W/System.err( 5371): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 5371): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 5371): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 5371): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
W/System.err( 5371): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
W/System.err( 5371): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
W/System.err( 5371): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
W/System.err( 5371): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err( 5371): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err( 5371): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err( 5371): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
W/System.err( 5371): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
W/System.err( 5371): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 5371): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5371): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5371): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/RCPManagerService( 1018):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1018): queryAllProviders():  providerCallBack is not register for 0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/DropBoxManagerService( 1018): Can't write: system_app_crash
E/DropBoxManagerService( 1018): java.io.FileNotFoundException: /data/system/dropbox/drop170.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 1018): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1018): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 1018): 	at com.android.server.am.ActivityManagerService$25.run(ActivityManagerService.java:15884)
E/DropBoxManagerService( 1018): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1018): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1018): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 1018): 	... 5 more
E/Zygote  ( 6233): MountEmulatedStorage()
I/libpersona( 6233): KNOX_SDCARD checking this for 10100
E/Zygote  ( 6233): v2
I/libpersona( 6233): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=6233 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/SELinux ( 6233): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1018): Killing 5090:com.google.android.partnersetup/u0a15 (adj 15): empty #31
I/Process ( 6213): Sending signal. PID: 6213 SIG: 9
I/SELinux ( 6233): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6233): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL

```
