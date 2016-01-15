#### Test 56151093f3290d6_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
D/ComposerPerformance( 5717): 1452862875733 ms / [DONE] Composer constructor
E/CII     ( 5717): CommonIMSInterface: VoLTE CSC feature disabled.
I/Mms/ReservationManager( 5717): ReservationManager()
I/Mms/ReservationManager( 5717): resetAfterConnected()
D/TP/MmsSmsProvider( 1450): query,matched:7, calling pid = 5717
W/art     ( 2012): Verification of void com.google.android.gms.common.app.GmsApplicationContext.<init>(android.content.Context, com.google.android.gms.common.app.BaseApplicationContext) took 111.570ms
D/TP/MmsSmsProvider( 1450): match 7:Elapsed time : 1.198 ms
I/Mms/ReservationManager( 5717): getReservedSendMessageCount(): retMessageCount=0
D/Mms/MmsApp( 5717): [end]    onCreate() consume time = 51.356927
D/Mms/Conversation( 5717): [start]    init() consume time = 0.00698
D/TP/MmsSmsProvider( 1450): deleteConversation threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1450): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1450): updateThread(), thread_id = 9223372036854775807
V/TP/MmsSmsDatabaseHelper( 1450): sUpgradeVersion = 0, db.getVersion() = 81
D/TP/MmsSmsProvider( 1450): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1450): need read changed broadcast:false
D/Mms/Conversation( 5717): [end]    init consume time = 10.406718
D/Mms/MessagingNotification( 5717): [start]    init() consume time = 2.772605
D/Mms/MessagingNotification( 5717): [end]    init consume time = 1.835416
D/TP/MmsSmsProvider( 1450): query,matched:0, calling pid = 5717
V/TP/MmsSmsProvider( 1450): getSimpleConversations entered.
D/TP/MmsSmsProvider( 1450): match 0:Elapsed time : 1.404 ms
I/DBG_POLICYDM( 5783): [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
D/Mms/DownloadManager( 5717): Service state changed: Bundle[mParcelledData.dataSize=744]
D/Mms/DownloadManager( 5717): roaming ------> false, mSimSlot = 0
D/Mms/Synchronizer( 5717): [start]    doSync consume time = 17.543646
D/TP/MmsSmsProvider( 1450): update, matched:300, calling pid = 5717
V/TP/MmsSmsProvider( 1450): syncDBData start
D/Mms/SpamFilter( 5717): [start]    SpamFilter fill() begin consume time = 2.871875
V/TP/MmsSmsProvider( 1450): syncDBData sms end
V/TP/MmsSmsProvider( 1450): syncDBData mms end
V/TP/MmsSmsProvider( 1450): syncDBData end
D/Mms/MethodReflector( 5717): getSubId is called
D/Mms/TelephonyUtils( 5717): getLongSubId from simSlot 0, return Value = -1
--------- beginning of system
D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/Mms/MethodReflector( 5717): getTelephonyProperty is called
D/Mms/DownloadManager( 5717): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5717): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5717): auto download without roaming -> true
D/Mms/DownloadManager( 5717): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5717): mAutoDownload ------> true
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5897): MountEmulatedStorage()
I/libpersona( 5897): KNOX_SDCARD checking this for 10072
E/Zygote  ( 5897): v2
I/libpersona( 5897): KNOX_SDCARD not a persona
I/SELinux ( 5897): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5897): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5897): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5897 uid=10072 gids={50072, 9997} abi=armeabi-v7a
D/Mms/Synchronizer( 5717): [end]    doSync consume time = 28.058802
D/TP/MmsSmsProvider( 1450): query,matched:400, calling pid = 5717
I/DBG_POLICYDM( 5783): [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
D/Mms/SpamFilter( 5717): [end]    SpamFilter fill() finished consume time = 9.084792
D/Mms/FreeMessageStatusReceiver( 5717): onReceive, action : android.intent.action.PACKAGE_ADDED
D/ActivityManager( 1016): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
D/TimaKeyStoreProvider( 5897): TimaSignature is unavailable
W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/ActivityThread( 5897): Added TimaKeyStore provider
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/Mms/FreeMessageReceiverService( 5717): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 5717): onHandleIntent: ACTION_PACKAGE_ADDED
E/Zygote  ( 5913): MountEmulatedStorage()
E/Zygote  ( 5913): v2
I/libpersona( 5913): KNOX_SDCARD checking this for 10047
I/SELinux ( 5913): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 5913): KNOX_SDCARD not a persona
D/Mms/ArtClassLoader( 5717): init [DONE] art
I/SELinux ( 5913): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5913): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5913 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
D/BadgeProvider( 5897): onCreate
I/ActivityManager( 1016): Killing 5333:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
I/ActivityManager( 1016): Killing 5210:com.google.android.talk/u0a104 (adj 15): empty #32
D/BadgeProvider( 5897): DatabaseHelper
D/TimaKeyStoreProvider( 5913): TimaSignature is unavailable
D/ActivityThread( 5913): Added TimaKeyStore provider
I/DBG_POLICYDM( 5783): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
D/Mms/MessagingNotification( 5717): checkBadgeCount unreadCount=0 badgeCount=0
I/DBG_POLICYDM( 5783): [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
D/TP/SmsProvider( 1450): query,matched:26, calling pid = 5717
D/TP/SmsProvider( 1450): match 26:Elapsed time : 1.166 ms
W/ResourcesManager( 5913): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/TP/MmsSmsProvider( 1450): query,matched:6, calling pid = 5717
W/ResourcesManager( 5913): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5913): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/TP/MmsSmsProvider( 1450): match 6:Elapsed time : 1.627 ms
D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5929): MountEmulatedStorage()
I/libpersona( 5929): KNOX_SDCARD checking this for 10025
E/Zygote  ( 5929): v2
I/libpersona( 5929): KNOX_SDCARD not a persona
I/SELinux ( 5929): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5929 uid=10025 gids={50025, 9997} abi=armeabi-v7a
I/SELinux ( 5929): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5929): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5929): TimaSignature is unavailable
D/ActivityThread( 5929): Added TimaKeyStore provider
I/ActivityManager( 1016): Killing 5395:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
W/libprocessgroup( 1016): failed to open /acct/uid_10057/pid_5333/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10104/pid_5210/cgroup.procs: No such file or directory
W/ResourcesManager( 5929): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/MyFiles ( 5913): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
W/art     ( 2012): Verification of void com.google.android.gms.games.service.PlayGamesAsyncService.launchGameForRecording(com.google.android.gms.games.broker.GamesClientContext, com.google.android.gms.games.service.WrappedGamesCallbacks, java.lang.String, com.google.android.gms.games.video.VideoConfiguration) took 125.523ms
D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
I/OMACP   ( 5929): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
E/installd(  284): system dir 0 : /system/app/
E/installd(  284): system dir 1 : /system/priv-app/
E/installd(  284): system dir 2 : /vendor/app/
E/installd(  284): system dir 3 : /oem/app/
W/libprocessgroup( 1016): failed to open /acct/uid_10069/pid_5395/cgroup.procs: No such file or directory
D/Mms/Omacp( 5717): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
I/TactileAssist( 1016): enable value -1
I/TactileAssist( 1016): internal enable value -1
I/TactileAssist( 1016): intensity value -1
I/TactileAssist( 1016): saveAppList value true
I/TactileAssist( 1016): List of disabled apps :
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/OMACP   ( 5929): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
I/OMACP   ( 5929): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
I/OMACP   ( 5929): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
I/OMACP   ( 5929): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
I/OMACP   ( 5929): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
D/PackageManager( 1016): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
E/Zygote  ( 5950): MountEmulatedStorage()
E/Zygote  ( 5950): v2
I/libpersona( 5950): KNOX_SDCARD checking this for 10053
I/libpersona( 5950): KNOX_SDCARD not a persona
I/SELinux ( 5950): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/OMACP   ( 5929): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
I/ActivityManager( 1016): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=5950 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
I/OMACP   ( 5929): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
I/OMACP   ( 5929): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
I/SELinux ( 5950): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/OMACP   ( 5929): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
E/SELinux ( 5950): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/OMACP   ( 5929): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
I/OMACP   ( 5929): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
I/OMACP   ( 5929): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
I/OMACP   ( 5929): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
D/TimaKeyStoreProvider( 5950): TimaSignature is unavailable
D/ActivityThread( 5950): Added TimaKeyStore provider
I/DBG_POLICYDM( 5783): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
W/ResourcesManager( 5950): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/DBG_POLICYDM( 5783): [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
D/Compatibility( 5950): onReceive() it will make start service
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/Compatibility( 5950): onHandleIntent()
D/Compatibility( 5950): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10155, android.intent.extra.user_handle=0}]
E/Zygote  ( 5972): MountEmulatedStorage()
I/libpersona( 5972): KNOX_SDCARD checking this for 10057
E/Zygote  ( 5972): v2
I/libpersona( 5972): KNOX_SDCARD not a persona
I/SELinux ( 5972): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5972): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5972): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/Compatibility( 5950): found: 2
I/ActivityManager( 1016): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5972 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
D/ChimeraCfgMgr( 2012): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2012): Module APK com.google.android.play.games already loaded
I/SL_DEBUG( 5871): isLoggable:: isProductShip = 1
I/SL_DEBUG( 5871): isLoggable:: SL_DEBUG_EXIST = false
D/Compatibility( 5950): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5950): skipping ResolveInfo{2abf82aa com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
D/Compatibility( 5950): considering ResolveInfo{6d69e9b com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5950): default: com.sec.android.app.soundalive.SAControlPanelActivity
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Compatibility( 5950): enabling receiver ResolveInfo{1496f238 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 5950): enabling receiver ResolveInfo{11626211 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/ChimeraCfgMgr( 2012): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/Compatibility( 5950): enabling receiver ResolveInfo{aeb1f76 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Compatibility( 5950): enabling receiver ResolveInfo{14f68977 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/AsyncTaskServiceImpl( 2012): Submit a task: k
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/Compatibility( 5950): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 5972): TimaSignature is unavailable
D/ActivityThread( 5972): Added TimaKeyStore provider
D/ChimeraCfgMgr( 2012): Loading module com.google.android.gms.gass from APK com.google.android.gms
I/ActivityManager( 1016): Killing 5426:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
D/ChimeraCfgMgr( 2012): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/k       ( 2012): Processing package: com.test.thalitest
D/GassUtils( 2012): Found app info for package com.test.thalitest:18. Hash: 82ccbc74df315987b7be206c22ec4eaa3ab0d49235c4895536307c8f71b675fe
D/k       ( 2012): Found info for package com.test.thalitest in db.
D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.internal.SharedPreferencesService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ContextImpl( 5871): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/BaseAppContext( 2012): Using Auth Proxy for data requests.
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5426/cgroup.procs: No such file or directory
W/BaseAppContext( 2012): Using Auth Proxy for data requests.
D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
I/UpdateIcingCorporaServi( 5972): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5871): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
I/PeopleDatabaseHelper( 2012): cleanUpNonGplusAccounts done.
W/BaseAppContext( 2012): Using Auth Proxy for data requests.
D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
W/BaseAppContext( 2012): Using Auth Proxy for data requests.
W/BaseAppContext( 2012): Using Auth Proxy for data requests.
W/BaseAppContext( 2012): Using Auth Proxy for data requests.
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6002): MountEmulatedStorage()
I/ActivityManager( 1016): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=6002 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 6002): v2
I/libpersona( 6002): KNOX_SDCARD checking this for 10041
I/SELinux ( 6002): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 6002): KNOX_SDCARD not a persona
I/SELinux ( 6002): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6002): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
W/BaseAppContext( 2012): Using Auth Proxy for data requests.
D/TimaKeyStoreProvider( 6002): TimaSignature is unavailable
D/ActivityThread( 6002): Added TimaKeyStore provider
,D/LocationManagerService( 1016): getProviders()=[passive]
I/SA      ( 6002): [SSP] onCreated
W/art     ( 5802): Suspending all threads took: 5.032ms
I/SA      ( 6002): [TPM] There is no property file
I/SA      ( 6002): [SCU] isHaveSA() - false
I/SA      ( 6002): [TPM] getModelProperty : null
I/SA      ( 6002): [TPM] getCSCProperty : null
I/SA      ( 6002): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 6002): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 6002): [DM] TFT FEATURE: false
I/SA      ( 6002): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/ActivityManager( 1016): Killing 5443:com.google.android.apps.plus/u0a120 (adj 15): empty #31
I/SA      ( 6002): [DM] init START
I/SA      ( 6002): [DM] This device is not a Vodafone
W/ResourceType( 6002): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 6002): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 6002): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 6002): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 6002): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 6002): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 6002): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 6002): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 6002): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 6002): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 6002): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 6002): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 6002): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 6002): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 6002): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 6002): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 6002): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
W/ResourceType( 6002): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 6002): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 6002): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 6002): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 6002): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 6002): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 6002): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 6002): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
I/SA      ( 6002): [SCU] isHaveSA() - false
I/SA      ( 6002): support phone number id : false
I/SA      ( 6002): [DM] Supports Ref Jpn : true
I/SA      ( 6002): [DM] init END
I/SA      ( 6002): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
I/SA      ( 6002): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10155 extra.user_handle.:0 ]
I/ActivityManager( 1016): Killing 5080:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
I/UpdateIcingCorporaServi( 5972): UpdateCorporaTask done [took 117 ms] updated apps [took 116 ms] 
I/ActivityManager( 1016): Killing 4926:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
W/libprocessgroup( 1016): failed to open /acct/uid_10120/pid_5443/cgroup.procs: No such file or directory
W/GAV2    ( 5802): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/AndroidRuntime( 6023): 
D/AndroidRuntime( 6023): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6023): CheckJNI is OFF
D/AndroidRuntime( 6023): readGMSProperty: start
D/AndroidRuntime( 6023): readGMSProperty: already setted!!
D/AndroidRuntime( 6023): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6023): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6023): readGMSProperty: end
D/AndroidRuntime( 6023): addProductProperty: start
W/libprocessgroup( 1016): failed to open /acct/uid_10150/pid_5080/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10040/pid_4926/cgroup.procs: No such file or directory
D/ActivityManager( 1016): startService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.apps.docs
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.ContentSyncService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
W/GAV2    ( 5802): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/art     ( 1016): Explicit concurrent mark sweep GC freed 233510(15MB) AllocSpace objects, 4(4MB) LOS objects, 33% free, 27MB/41MB, paused 2.638ms total 190.579ms
E/Zygote  ( 6051): MountEmulatedStorage()
E/Zygote  ( 6051): v2
I/libpersona( 6051): KNOX_SDCARD checking this for 10100
I/libpersona( 6051): KNOX_SDCARD not a persona
I/SELinux ( 6051): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6051): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6051): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=6051 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
D/TimaKeyStoreProvider( 6051): TimaSignature is unavailable
D/ActivityThread( 6051): Added TimaKeyStore provider
D/PackageIntentReceiver( 6051): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 6051): Not GearManger package! 
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6068): MountEmulatedStorage()
E/Zygote  ( 6068): v2
I/libpersona( 6068): KNOX_SDCARD checking this for 1000
I/libpersona( 6068): KNOX_SDCARD not a persona
I/SELinux ( 6068): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=6068 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 6068): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6068): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Killing 4420:com.google.android.music:main/u0a111 (adj 15): empty #31
I/art     (  307): Explicit concurrent mark sweep GC freed 8692(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 628us total 21.058ms
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 643us total 17.633ms
D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1834): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/TimaKeyStoreProvider( 6068): TimaSignature is unavailable
D/ActivityThread( 6068): Added TimaKeyStore provider
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 625us total 21.140ms
W/libprocessgroup( 1016): failed to open /acct/uid_10111/pid_4420/cgroup.procs: No such file or directory
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
W/AccountFeatureHelper( 5802): Write apps_features disabled false
E/Zygote  ( 6085): MountEmulatedStorage()
E/Zygote  ( 6085): v2
I/libpersona( 6085): KNOX_SDCARD checking this for 1000
I/libpersona( 6085): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6085 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 4777:com.sec.android.widgetapp.SPlannerAppWidget/u0a134 (adj 15): empty #31
I/SELinux ( 6085): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6085): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6085): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6085): TimaSignature is unavailable
D/ActivityThread( 6085): Added TimaKeyStore provider
E/AffinityControl( 6023): AffinityControl: registerfunction enter
W/libprocessgroup( 1016): failed to open /acct/uid_10134/pid_4777/cgroup.procs: No such file or directory
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
D/AndroidRuntime( 6023): Calling main entry com.android.commands.am.Am
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/AcmsPackageEventListener( 6085): Received: android.intent.action.PACKAGE_ADDED
W/ContextImpl( 6085): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
E/Zygote  ( 6103): MountEmulatedStorage()
E/Zygote  ( 6103): v2
I/libpersona( 6103): KNOX_SDCARD checking this for 10120
I/libpersona( 6103): KNOX_SDCARD not a persona
I/SELinux ( 6103): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6103): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6103): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
E/PersonaManagerService( 1016): inState():  stateMachine is null !!
I/ActivityManager( 1016): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6103 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/PersonaManagerService( 1016): PersonaId don't exist
I/ActivityManager( 1016): Killing 5251:com.android.calendar/u0a135 (adj 15): empty #31
I/ActivityManager( 1016): do not start freezing screen for locked container getKeyguardshowstate = false
D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/AcmsService( 6085): Enter Oncreate
D/AcmsServiceMonitor( 6085): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 6085): creating AcmsCore
D/AcmsCore( 6085): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 6085): AcmsCore
W/GAV2    ( 5802): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
D/AcmsCore( 6085): init
D/AcmsCore( 6085): Looper handler is not null
D/AcmsCore( 6085): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6085): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6085): Incrementing - Counter value: 1
D/AcmsCore( 6085): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsService( 6085): onStartCommand
D/AcmsService( 6085): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 6085): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 6085): Incrementing - Counter value: 2
D/AcmsService( 6085): Incremented Counter Value : onStartCommand
D/AcmsCertificateMngr( 6085): AcmsCertificateMngr
D/TimaKeyStoreProvider( 6103): TimaSignature is unavailable
D/ActivityThread( 6103): Added TimaKeyStore provider
D/AcmsRevocationMngr( 6085): AcmsRevocationMngr
W/ActivityManager( 1016): mDVFSHelper.acquire()
I/Icing   ( 2012): Indexing 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28 from com.google.android.gms
D/FocusedStackFrame( 1016): Set to : 0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1016): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1016): *FMB* installDecor flags : 25362712
E/Zygote  ( 6121): MountEmulatedStorage()
E/Zygote  ( 6121): v2
I/libpersona( 6121): KNOX_SDCARD checking this for 10155
I/libpersona( 6121): KNOX_SDCARD not a persona
I/SELinux ( 6121): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6121 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1016): Focused application set to: xxxx
D/InputDispatcher( 1016): Focus left window: 1478
I/SELinux ( 6121): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6121): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
D/PhoneWindow( 1016): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/ActivityThread( 6085): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
D/PhoneWindow( 1016): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=12 createSurf (1x1),1 flag=404, uhalitest
D/AndroidRuntime( 6023): Shutting down VM
W/ResourcesManager( 6103): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 6121): TimaSignature is unavailable
D/ActivityThread( 6121): Added TimaKeyStore provider
V/WindowManager( 1016): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/ActivityManager( 1016): Display changed displayId=0
W/libprocessgroup( 1016): failed to open /acct/uid_10135/pid_5251/cgroup.procs: No such file or directory
D/StatusBarManagerService( 1016): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/PersonaManager( 1016): isKioskContainerExistOnDevice
V/AlarmManager( 1016): waitForAlarm result :8
I/SurfaceFlinger(  258): id=8 Removed Mauncher (5/9)
I/SurfaceFlinger(  258): id=8 Removed Mauncher (-2/9)
D/WindowOrientationListener( 1016):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
D/AcmsService( 6085): Inside handle Intent
D/AcmsService( 6085): App added - package name: com.test.thalitest
D/AcmsCore( 6085): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6085): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6085): Incrementing - Counter value: 3
D/AcmsCore( 6085): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 6085): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 6085): Decrementing - Counter value: 2
D/Launcher( 1478): onTrimMemory. Level: 20
V/ActivityThread( 1478): updateVisibility : ActivityRecord{225cdee0 token=android.os.BinderProxy@1ae2d143 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
I/Icing   ( 2012): Indexing done 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28
W/art     ( 6023): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/WebViewFactory( 6121): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,I/LibraryLoader( 6121): Time to load native libraries: 1 ms (timestamps 1270-1271)
,I/LibraryLoader( 6121): Expected native library version number "",actual native library version number ""
,I/Mms/MmsApp( 5717):  start initViewCache mms
D/Mms/ComposeMessageFragment( 5717): [start]    fillCache consume time = 1936.663697
D/Mms/ComposeMessageFragment( 5717): fillCache, easy = false
,V/WebViewChromiumFactoryProvider( 6121): Binding Chromium to main looper Looper (main, tid 1) {1496f238}
,I/LibraryLoader( 6121): Expected native library version number "",actual native library version number ""
I/chromium( 6121): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6121): Initializing chromium process, singleProcess=true
,W/art     ( 6121): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6121): ApplicationContext is null in ApplicationStatus
,D/ChimeraCfgMgr( 2012): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2012): Module APK com.google.android.play.games already loaded
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,W/chromium( 6121): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 6121): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,I/chromium( 6121): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,I/Adreno-EGL( 6121): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6121): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6121): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6121): Local Branch: 
I/Adreno-EGL( 6121): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6121): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6121):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/AbsListView( 5717): Get MotionRecognitionManager
,D/MotionRecognitionService( 1016):  ssp status : false
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/Mms/ComposeMessageFragment( 5717): [end]    fillCache consume time = 113.043281
,I/splitIntent( 1016): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,W/chromium( 6121): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,D/Mms/BubbleViewCache( 5717): fillCache bubble = 1
,W/art     ( 6121): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6121): onDetachedFromWindow called when already detached. Ignoring
,W/ActivityManager( 1016): Activity pause timeout for ActivityRecord{8aa95d3 u0 com.test.thalitest/.MainActivity t7}
,D/PhoneWindow( 6121): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 6121): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 6121): CordovaWebView is running on device made by: samsung
,W/art     ( 6121): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6121): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6121): Render dirty regions requested: true
,D/ActivityManager( 1016): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1016): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1016): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1016): handleActiveUserChange for user 0
,D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
,I/ActivityManager( 1016): Killing 5097:com.google.android.gm/u0a101 (adj 15): empty #31
,V/ActivityThread( 6121): updateVisibility : ActivityRecord{106ca414 token=android.os.BinderProxy@1c385226 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PhoneWindow( 6121): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 6121): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  258): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1016): Focus entered window: 6121
,D/SRIB_DCS( 6121): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 6121): Initialized EGL, version 1.4
D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,D/OpenGLRenderer( 6121): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096,
D/OpenGLRenderer( 6121): Enabling debug mode 0
,E/SMD     (  291): DCD OFF
,D/InputMethodManagerService( 1016): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/StatusBar( 1179): Icon Only
,D/PanelView( 1179): There is/are notification(s) 
,I/SamsungIME( 1767): getCurrentCandidateView
,W/libprocessgroup( 1016): failed to open /acct/uid_10101/pid_5097/cgroup.procs: No such file or directory
,I/ActivityManager( 1016): Displayed Component not be shown by security: +698ms (total +818ms)
,I/Timeline( 1016): Timeline: Activity_windows_visible id: ActivityRecord{8aa95d3 u0 com.test.thalitest/.MainActivity t7} time:91782
W/ActivityManager( 1016): mDVFSHelper.release(),
,W/IInputConnectionWrapper( 6121): showStatusIcon on inactive InputConnection
,I/Timeline( 6121): Timeline: Activity_idle id: android.os.BinderProxy@1c385226 time:91787,
,I/SurfaceFlinger(  258): id=12 Removed uhalitest (7/9)
I/SurfaceFlinger(  258): id=12 Removed uhalitest (-2/9)
,D/SamsungIME( 1767): Dismiss ExpandCandiate
W/BindingManager( 6121): Cannot call determinedVisibility() - never saw a connection for the pid: 6121
,I/ActivityManager( 1016): Killing 5593:com.google.android.gms:car/u0a12 (adj 15): empty #31
,D/JsMessageQueue( 6121): Set native->JS mode to OnlineEventsBridgeMode
,I/SamsungIME( 1767): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1767): getDebugLevel  : 0x4f4c
,W/libprocessgroup( 1016): failed to open /acct/uid_10012/pid_5593/cgroup.procs: No such file or directory
,I/SamsungIME( 1767): KeybaordView init() : load resources
,I/SamsungIME( 1767): getCurrentKeyboard
,I/SamsungIME( 1767): getTextKeyboard
,D/SamsungIME( 1767): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/jxcore_app_log( 6121): JniHelper::setJavaVM(0xb7130450), pthread_self() = -1217917672,
D/JX-Cordova( 6121): jxcore cordova android initializing
,I/DBG_POLICYDM( 5783): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5783): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5783): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5783): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5783): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5783): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5783): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,D/SamsungIME( 1767): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/AcmsKeyStoreHelper( 6085):  getKeyStoreForApplication Enter
,I/AcmsKeyStoreHelper( 6085): Key Store exist
I/AcmsKeyStoreHelper( 6085): Hence loading the keystore file
,D/AcmsKeyStoreHelper( 6085):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 6085): getKeyStoreForApplication success 
D/AcmsCore( 6085): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 6085): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6085): Decrementing - Counter value: 1
D/AcmsCore( 6085): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 6085): This is NOT a valid MirrorLink app
D/AcmsCore( 6085): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 6085): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6085): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 6085): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 6085): getSvcCounter - Counter value: 0
,D/AcmsService( 6085): Enter onDestroy
I/AcmsService( 6085): cleanUp(): inside service clean up
D/AcmsCore( 6085): AcmsCore: inside DeInit
,D/AcmsCore( 6085): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 6085): AcmsCertificateMngr: inside cleanup
,D/AcmsRevocationMngr( 6085): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 6085): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 6085): AppEntryInterface: Inside CleanUp
,D/AcmsServiceMonitor( 6085): getSvcCounter - Counter value: 0
,D/AcmsService( 6085): killing acms process
I/Process ( 6085): Sending signal. PID: 6085 SIG: 9
,I/ActivityManager( 1016): Process ACMS.Process (pid 6085)(adj 0) has died(36,1175)
,I/PowerManagerService( 1016): [PWL] Off : 15s ago
,W/jxcore-log( 6121): Initializing JXcore engine
W/jxcore-log( 6121): JXcore engine is ready
,W/jxcore-log( 6121): Starting JXcore engine
,E/audit   ( 1915): type=1400 msg=audit(1452862880.055:205): avc:  denied  { ioctl } for  pid=6121 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1915):  SEPF_SM-A500FU_5.0.2-1_0038
E/audit   ( 1915): type=1300 msg=audit(1452862880.055:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=bef80d58 items=0 ppid=307 ppcomm=main pid=6121 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1915): type=1320 msg=audit(1452862880.055:205): 
,W/jxcore-log( 6121): Platform android
W/jxcore-log( 6121): 
,W/jxcore-log( 6121): Process ARCH arm
W/jxcore-log( 6121): 
,I/jxcore-log( 6121): JXcore Cordova bridge is ready!
I/jxcore-log( 6121): 
,W/jxcore-log( 6121): JXcore engine is started
,I/Choreographer( 6121): Skipped 147 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6121): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6121): Toggling radios to true
I/jxcore-log( 6121): 
,D/BluetoothAdapter( 6121): enable()
,D/BluetoothAdapter( 6121): enable(): BT is already enabled..!
,D/SecContentProvider( 1016): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1016): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2( 1016): mCursor = null
,D/WifiService( 1016): setWifiEnabled: true pid=6121, uid=10155
,W/ActivityManager( 1016): Permission Denial: getCurrentUser() from pid=6121, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 1016): Failed getting userId using ActivityManagerNative
W/WifiService( 1016): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6121, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1016): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24778)
W/WifiService( 1016): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1016): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1016): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1016): 	at android.os.Binder.execTransact(Binder.java:461)
,D/SettingsProvider( 1016): name = wifi_on
,I/WifiService( 1016): disconnect: pid=6121, uid=10155
,I/wpa_supplicant( 2076): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 6121): Radios toggled
I/jxcore-log( 6121): 
,I/jxcore-log( 6121): My device name is: samsung-SM-A500FU
I/jxcore-log( 6121): 
,E/SMD     (  291): DCD OFF
,I/wpa_supplicant( 2076): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
D/Tethering( 1016): interfaceStatusChanged wlan0, false
,I/wpa_supplicant( 2076): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 2076): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 2076): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 2076): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/wpa_supplicant( 2076): Cmd 35605 not handled,
,I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1016): InitialState.processMessage what=4
E/WifiStateMachine( 1016): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 2076): reset timer : RESET_TIMER 0
I/wpa_supplicant( 2076): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 2076): P2P: Current p2p state = IDLE
I/wpa_supplicant( 2076): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 2076): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 2076): First Scan Start
,I/wpa_supplicant( 2076): Scan requested (ret=0) - scan timeout 30 seconds
,E/Tethering( 1016): No numeric data
,D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1016): interfaceStatusChanged wlan0, false
D/Tethering( 1016): sendTetherStateChangedBroadcast 0, 0, 0
I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
D/Tethering( 1016): clearTetheredNotification()
E/WifiConfigStore( 1016): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
V/NetworkStats( 1016): performPollLocked(flags=0x1)
D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
D/HotspotTile( 1179): onReceive : android.net.conn.TETHER_STATE_CHANGED
,D/Tethering( 1016): interfaceStatusChanged wlan0, false
D/HotspotTile( 1179): updateTetherState():false, false
D/NetworkStatsFactory( 1016): UpdateStatsForKnox updated
I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
,D/NetworkStatsFactory( 1016): UpdateStatsForKnox main else ---
,V/NetworkStats( 1016): performPollLocked() took 4ms
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,E/WifiNative-wlan0( 1016): do suspend true
,D/WifiP2pService( 1016): InactiveState{ what=143375 }
,D/WifiP2pService( 1016): P2pEnabledState{ what=143375 }
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/CommandListener(  278): Clearing all IP addresses on wlan0
V/NativeCrypto( 1834): Read error: ssl=0xb76e37b0: I/O error during system call, Connection timed out
,V/NativeCrypto( 1834): SSL shutdown failed: ssl=0xb76e37b0: I/O error during system call, Broken pipe
,E/WifiStateMachine( 1016): Start Disconnecting Watchdog 1
E/ConnectivityService( 1016): updateNetworkInfo()
D/ConnectivityService( 1016): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1016): updateNetworkInfo()
D/ConnectivityService( 1016): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,I/wpa_supplicant( 2076): wlan0: Setting scan request: 0 sec 0 usec
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14952 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 ,
,E/WifiNative-wlan0( 1016): do suspend true
,D/ConnectivityService( 1016): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): ValidatedState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): DefaultState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,I/System.out( 1016): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1016): Tagging socket 360 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1016, getuid(): 1000
,D/WifiP2pService( 1016): InactiveState{ what=143375 }
D/WifiP2pService( 1016): P2pEnabledState{ what=143375 }
,I/qtaguid ( 1016): Untagging socket 360
I/System.out( 1016): (HTTPLog)-Static: isSBSettingEnabled false
,I/WifiTrafficPoller( 1016): evaluateTrafficStatsPolling
,D/EnterpriseController(  278): uids 1000
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 1000
D/CommandListener(  278): Clearing all IP addresses on wlan0
,D/TelephonyNetworkFactory( 1450): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/ConnectivityService( 1016): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/WIFI_P2P( 1016): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/ConnectivityService( 1016): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/TelephonyNetworkFactory( 1450): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1016): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 2012): CM callback handler got msg 524292
D/CSLegacyTypeTracker( 1016): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/CSLegacyTypeTracker( 1016): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 1016): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/EntConnectivity( 1016): Not allowed due to - mEnabled false - primarySimSlot false
,D/ConnectivityManager.CallbackHandler( 1179): CM callback handler got msg 524292
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Validated
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): ValidatedState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/StatusBar.NetworkController( 1179): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/EntConnectivity( 1016): Not allowed due to - mEnabled false - primarySimSlot false
,D/ConnectivityService( 1016): nai.networkMonitor.doQuit()
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): doQuit - quitNow()
,I/WifiTrafficPoller( 1016): evaluateTrafficStatsPolling
,D/WifiNetworkAgent( 1016): NetworkAgent: NetworkAgent channel lost
,D/Tethering( 1016): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,V/NetworkStats( 1016): updateIfacesLocked()
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
V/NetworkStats( 1016): performPollLocked(flags=0x1)
,D/Tethering( 1016): MasterInitialState.processMessage what=3
,D/NetworkStatsFactory( 1016): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1016): UpdateStatsForKnox main else ---
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
V/NetworkStats( 1016): performPollLocked() took 4ms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,I/Hs20UtilService( 3472): Starting #8
,I/Hs20UtilService( 3472): Message received 5007
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
V/NetworkStats( 1016): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/StatusBar.NetworkController( 1179): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WIFI    ( 1016): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/StatusBar.NetworkController( 1179): EthernetConnected: false
,D/StatusBar.NetworkController( 1179): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1179): getUpdateDataNetType(): mDataTypeBrand = LTE
,D/StatusBar.NetworkController( 1179): updateDataNetType()
D/StatusBar.NetworkController( 1179): NoService, mRoamingIconId = 0
,D/NearbySettings( 1371): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
V/NearbySettings( 1371): DMSUtil.isNetworkConnected - flag-null, state-null
,E/StatusBar.NetworkController( 1179): updateLTEICONDataNetType:0
,I/NearbySettings( 1371): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1371): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1371): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1371): MountReceiver.onReceive - Set preference state off
,D/SecContentProvider2( 1016): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1016): mCursor = null
,V/NearbySettings( 1371): MountReceiver.mPrefHandler - 7002
,D/StatusBar.NetworkController( 1179): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1179): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1179): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1179): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/SecContentProvider2( 1016): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1016): mCursor = null
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6190): MountEmulatedStorage(),
I/ActivityManager( 1016): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6190 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
E/Zygote  ( 6190): v2
I/libpersona( 6190): KNOX_SDCARD checking this for 10104
,I/libpersona( 6190): KNOX_SDCARD not a persona
,I/SELinux ( 6190): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6190): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6190): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6190): TimaSignature is unavailable
,D/ActivityThread( 6190): Added TimaKeyStore provider
,D/PhoneApp( 1450): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1450): FileWriteThread : threadType = 3
,D/PhoneApp( 1450): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1450): FileWriteThread : threadType = 3
,D/PhoneApp( 1450): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1450): FileWriteThread : threadType = 3
,W/ResourcesManager( 6190): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/PhoneApp( 1450): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1450): FileWriteThread : threadType = 3
,D/PhoneApp( 1450): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1450): FileWriteThread : threadType = 3
,D/PhoneApp( 1450): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1450): FileWriteThread : threadType = 3
,D/PhoneApp( 1450): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1450): FileWriteThread : threadType = 3
,D/PhoneApp( 1450): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1450): FileWriteThread : threadType = 3
,D/PhoneApp( 1450): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1450): FileWriteThread : threadType = 3
,D/PhoneApp( 1450): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1450): FileWriteThread : threadType = 3
,D/PhoneApp( 1450): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1450): FileWriteThread : threadType = 3
,D/PhoneApp( 1450): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1450): FileWriteThread : threadType = 3
,D/PhoneApp( 1450): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1450): FileWriteThread : threadType = 3
,D/PhoneApp( 1450): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1450): FileWriteThread : threadType = 3
,D/PhoneApp( 1450): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1450): FileWriteThread : threadType = 3
,I/Babel   ( 6190): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 6190): MmsConfig.loadMmsSettings
I/Babel   ( 6190): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,I/Babel   ( 6190): MmsConfig.loadFromDatabase
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/Babel   ( 6190): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 6190): MmsConfig.loadFromResources
,E/Babel   ( 6190): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 6190): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,W/Settings( 6190): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_StickerModule( 6190): App launched.
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3472): Starting #9
I/Hs20UtilService( 3472): Message received 5007
,D/NearbySettings( 1371): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1371): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1371): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1371): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1371): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1371): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1371): MountReceiver.mPrefHandler - 7002
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 0
W/QCamera2Factory(  283): getCameraInfo: X
,W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 1
,W/QCamera2Factory(  283): getCameraInfo: X
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/VideoCapabilities( 6190): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6190): Unsupported mime audio/evrc
,W/AudioCapabilities( 6190): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6190): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 6190): Unsupported mime audio/mpeg-L2
,D/ConnectivityService( 1016): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 1016): updateDataUsageMap
,W/AudioCapabilities( 6190): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6190): Unsupported mime audio/x-ima
,D/GpsLocationProvider( 1016): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/AudioCapabilities( 6190): Unsupported mime audio/qcelp
,I/DBG_DM  ( 3095): [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,W/AudioCapabilities( 6190): Unsupported mime audio/evrc
,I/PCWCLIENTTRACE_PushUtil( 5736): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5736): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5736): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5736): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1016): Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
I/splitIntent( 1016): finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5736): noConnectivity : true,
,E/Zygote  ( 6232): MountEmulatedStorage(),
E/Zygote  ( 6232): v2,
I/libpersona( 6232): KNOX_SDCARD checking this for 10111,
I/libpersona( 6232): KNOX_SDCARD not a persona,
,I/ActivityManager( 1016): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6232 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/DBG_DM  ( 3095): [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false,
,I/SELinux ( 6232): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 6232): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast,
,E/SELinux ( 6232): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6249): MountEmulatedStorage(),
I/ActivityManager( 1016): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6249 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/TimaKeyStoreProvider( 6232): TimaSignature is unavailable,
D/ActivityThread( 6232): Added TimaKeyStore provider
E/Zygote  ( 6249): v2,
I/libpersona( 6249): KNOX_SDCARD checking this for 10009,
I/libpersona( 6249): KNOX_SDCARD not a persona
,I/SELinux ( 6249): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 6249): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6249): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,D/accuweather( 1728): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/VideoCapabilities( 6190): Unsupported mime video/wvc1
,W/VideoCapabilities( 6190): Unsupported mime video/x-ms-wmv
,D/TimaKeyStoreProvider( 6249): TimaSignature is unavailable
,I/ActivityManager( 1016): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6264 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
D/ActivityThread( 6249): Added TimaKeyStore provider
I/libpersona( 6264): KNOX_SDCARD checking this for 10145
E/Zygote  ( 6264): MountEmulatedStorage()
I/libpersona( 6264): KNOX_SDCARD not a persona
E/Zygote  ( 6264): v2
,I/SELinux ( 6264): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6264): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6264): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START,
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,D/daemonapp( 1303): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,W/VideoCapabilities( 6190): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 6190): Unsupported mime video/wvc1
,D/accuweather( 1728): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1728): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1728): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1728): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/TimaKeyStoreProvider( 6264): TimaSignature is unavailable
,D/ActivityThread( 6264): Added TimaKeyStore provider
,W/VideoCapabilities( 6190): Unsupported mime video/x-ms-wmv
,D/accuweather( 1728): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1728): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/VideoCapabilities( 6190): Unsupported mime video/x-ms-wmv7
W/VideoCapabilities( 6190): Unsupported mime video/x-ms-wmv8
W/VideoCapabilities( 6190): Unsupported mime video/mp43
,E/Zygote  ( 6280): MountEmulatedStorage(),
E/Zygote  ( 6280): v2
I/libpersona( 6280): KNOX_SDCARD checking this for 10081
I/libpersona( 6280): KNOX_SDCARD not a persona
,I/SELinux ( 6280): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6280): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6280): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1016): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6280 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 6280): TimaSignature is unavailable
,D/ActivityThread( 6280): Added TimaKeyStore provider
,W/VideoCapabilities( 6190): Unsupported mime video/sorenson
,W/ResourcesManager( 6264): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6264): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6264): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6264): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6264): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/VideoCapabilities( 6190): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6190): Unsupported profile 4 for video/mp4v-es
,I/MusicStore( 6232): Database version: 108
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,I/ActivityManager( 1016): Killing 5662:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
,I/KLMS-2.5.183: ( 3515): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jan 15 14:01:22 GMT+01:00 2016
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/KLMS-2.5.183: ( 3515): KLMSAbstractReciever(): onReceive().END.
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,I/KLMS-2.5.183: ( 3515): KLMSIntentService(): onCreate()
I/KLMS-2.5.183: ( 3515): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.5.183: ( 3515): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,E/Zygote  ( 6303): MountEmulatedStorage()
,E/Zygote  ( 6303): v2
I/libpersona( 6303): KNOX_SDCARD checking this for 10034
I/libpersona( 6303): KNOX_SDCARD not a persona
,I/SELinux ( 6303): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 6303): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1016): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6303 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
,E/SELinux ( 6303): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.5.183: ( 3515): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/wpa_supplicant( 2076): nl80211: Received scan results (7 BSSes)
I/wpa_supplicant( 2076): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 2076): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 2076): Trying to associate with  'G700'
I/wpa_supplicant( 2076): Re-associate with C0.AA.48
D/WifiMonitor( 1016): didn't find BSSID Trying to associate with SSID 'NG700'
I/wpa_supplicant( 2076): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 2076): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,D/SecContentProvider2( 1016): uri = 20 selection = getPromptCredentialsEnabled,
D/SecContentProvider2( 1016): mCursor = null
,I/KLMS-2.5.183: ( 3515): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.183: ( 3515): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false,
,I/KLMS-2.5.183: ( 3515): StateImplV2(): networkChangeListener().END
,I/ActivityManager( 1016): Killing 5313:com.samsung.aasaservice/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6303): TimaSignature is unavailable
,D/ActivityThread( 6303): Added TimaKeyStore provider
,I/KLMS-2.5.183: ( 3515): KLMSIntentService(): onDestroy()
,W/libprocessgroup( 1016): failed to open /acct/uid_10142/pid_5662/cgroup.procs: No such file or directory
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,E/Zygote  ( 6325): MountEmulatedStorage(),
,E/wpa_supplicant( 2076): Cmd 35605 not handled,
I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 2076): wlan0: State: ASSOCIATING -> ASSOCIATED
I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 2076): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/ActivityManager( 1016): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6325 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/wpa_supplicant( 2076): Associated with C0.AA.48
,I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 2076): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, true
,I/wpa_supplicant( 2076): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 2076): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1016): interfaceStatusChanged wlan0, false
D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
D/Tethering( 1016): interfaceStatusChanged wlan0, false
D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
D/Tethering( 1016): interfaceStatusChanged wlan0, false
,D/Tethering( 1016): interfaceLinkStateChanged wlan0, true
,D/Tethering( 1016): interfaceStatusChanged wlan0, true
E/Tethering( 1016): No numeric data
,I/wpa_supplicant( 2076): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 2076): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 2076): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE,
I/wpa_supplicant( 2076): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 2076): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 2076): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2076): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 2076): Blacklist: Clear (temp) 
I/wpa_supplicant( 2076): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 1016): sendTetherStateChangedBroadcast 1, 0, 0
,D/Tethering( 1016): clearTetheredNotification()
D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,E/Zygote  ( 6325): v2,
I/libpersona( 6325): KNOX_SDCARD checking this for 10113,
I/SELinux ( 6325): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 6325): KNOX_SDCARD not a persona
,D/SecContentProvider2( 1016): uri = 20 selection = getPromptCredentialsEnabled
I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, true
D/SecContentProvider2( 1016): mCursor = null
V/NetworkStats( 1016): performPollLocked(flags=0x1)
D/Tethering( 1016): interfaceLinkStateChanged wlan0, true
,D/HotspotTile( 1179): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/Tethering( 1016): interfaceStatusChanged wlan0, true
,D/HotspotTile( 1179): updateTetherState():false, false,
,I/SO_AGENT( 6303): [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
V/NetworkStats( 1016): performPollLocked() took 4ms
D/NetworkStatsFactory( 1016): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1016): UpdateStatsForKnox main else ---
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
I/SELinux ( 6325): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6325): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 6232): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
D/WifiNative-wlan0( 1016): callSECApiVoid - ID [50]
W/ResourcesManager( 6232): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/WifiConfigStore( 1016): setLastSelectedConfiguration -1
D/ConnectivityService( 1016): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1016): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 1016): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1016): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 1016): updateNetworkInfo()
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1179): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiConfigStore( 1016): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/TimaKeyStoreProvider( 6325): TimaSignature is unavailable
,D/ActivityThread( 6325): Added TimaKeyStore provider
,E/SPPClientService( 5844): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 6002): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,I/SA      ( 6002): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 6002): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6002): [SLFUCHKMGR] constructor called
,I/DBG_POLICYDM( 5783): [com.policydm.XDMApplication(503/xdmProtoIsWIFIConnected)] WiFi network Connected : false
V/JNIHelp ( 6232): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/ActivityManager( 1016): startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,I/DBG_POLICYDM( 5783): [com.policydm.XDMApplication(513/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,E/DBG_POLICYDM( 5783): [com.policydm.XDMBroadcastReceiver$2(109/run)] network is unserviceable
,W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
E/DBG_POLICYDM( 5783): [com.policydm.XDMApplication(477/isNetworkChanged)] network not changed.... 
,I/SA      ( 6002): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 6002): [OR] == isSIMCardReady false ==
,I/SA      ( 6002): [SCU] == networkStateCheck == false
I/SA      ( 6002): [OR] onReceive END
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5313/cgroup.procs: No such file or directory
,V/DownloadManager( 1228): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/BadgeProvider( 5897): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,W/ActivityThread( 6232): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6232): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1919de5b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6232): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6232): GMSCore installation verified
,E/SPPClientService( 5844): [[SystemStateMonitorService]] No Active Internet
,D/BadgeProvider( 5897): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5897): sendNotify, [notify] : null
D/BadgeProvider( 5897): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5897): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5897): update, [UpdateCount] : 1
,D/CommandListener(  278): Setting iface cfg
,E/WifiStateMachine( 1016): Start Dhcp Watchdog 2
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SecContentProvider2( 1016): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1016): mCursor = null
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/SecContentProvider2( 1016): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1016): mCursor = null
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/WifiNative-wlan0( 1016): do suspend false
D/WifiP2pService( 1016): InactiveState{ what=143375 }
D/SecContentProvider2( 1016): uri = 20 selection = getPromptCredentialsEnabled
D/WifiP2pService( 1016): P2pEnabledState{ what=143375 }
D/SecContentProvider2( 1016): mCursor = null
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,I/ConfigStore( 6232): Config Database version: 1
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/Launcher.Model( 1478): reloadBadges entered.
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/Zygote  ( 6351): MountEmulatedStorage(),
E/Zygote  ( 6351): v2
I/libpersona( 6351): KNOX_SDCARD checking this for 1000
I/SELinux ( 6351): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 6351): KNOX_SDCARD not a persona,
,I/SELinux ( 6351): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6351 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 5702:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
I/ActivityManager( 1016): Killing 4945:com.sec.android.gallery3d/u0a44 (adj 15): empty #32
E/SELinux ( 6351): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  307): Explicit concurrent mark sweep GC freed 8729(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 2.743ms total 24.538ms
,D/TimaKeyStoreProvider( 6351): TimaSignature is unavailable
,D/ActivityThread( 6351): Added TimaKeyStore provider
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 638us total 17.207ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 710us total 17.079ms
,D/SecurityLogAgent( 6351): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6351): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 6351): StateMachine : Current State = 1
,D/SecurityLogAgent( 6351): StateMachine : Changed Current State = 1
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6368): MountEmulatedStorage(),
I/ActivityManager( 1016): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6368 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 6368): v2
I/libpersona( 6368): KNOX_SDCARD checking this for 10159
,I/libpersona( 6368): KNOX_SDCARD not a persona
,I/SELinux ( 6368): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 6368): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6368): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL,
,E/dhcpcd  ( 6374): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,I/dhcpcd  ( 6374): version 5.5.6 starting,
,E/dhcpcd  ( 6374): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,I/dhcpcd  ( 6374): wlan0: sending IPv6 Router Solicitation,
E/dhcpcd  ( 6374): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 6374): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 6374): bssid match
,I/dhcpcd  ( 6374): wlan0: rebinding lease of 192.168.1.129
,D/TimaKeyStoreProvider( 6368): TimaSignature is unavailable
,D/ActivityThread( 6368): Added TimaKeyStore provider
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 54354(2MB) AllocSpace objects, 3(96KB) LOS objects, 33% free, 27MB/41MB, paused 3.502ms total 213.988ms
,W/libprocessgroup( 1016): failed to open /acct/uid_10152/pid_5702/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10044/pid_4945/cgroup.procs: No such file or directory
,I/ActivityManager( 1016): Killing 4694:com.samsung.android.sm/1000 (adj 15): empty #31
,I/iu.Environment( 2012): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/ActivityManager( 1016): Killing 5356:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/iu.UploadsManager( 2012): num queued entries: 0
,I/iu.UploadsManager( 2012): num updated entries: 0
,I/iu.SyncManager( 2012): NEXT; no task
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6232): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6232): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6232): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1016): getStreamVolume 3 index 0
,I/MediaRouter( 6232): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6232): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_4694/cgroup.procs: No such file or directory
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,W/libprocessgroup( 1016): failed to open /acct/uid_10015/pid_5356/cgroup.procs: No such file or directory
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,I/ActivityManager( 1016): Killing 5065:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6325): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6325): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Zygote  ( 6400): MountEmulatedStorage()
E/Zygote  ( 6400): v2
I/libpersona( 6400): KNOX_SDCARD checking this for 10002
I/libpersona( 6400): KNOX_SDCARD not a persona
,I/SELinux ( 6400): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6400): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1016): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6400 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 6400): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5065/cgroup.procs: No such file or directory
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 6400): TimaSignature is unavailable
,D/ActivityThread( 6400): Added TimaKeyStore provider
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6325): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,W/ResourcesManager( 6232): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6232): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,I/GHttpClientFactory( 6232): Using the GMSCore's GoogleHttpClient
,W/ContextImpl( 6325): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/dhcpcd  ( 6374): wlan0: acknowledged 192.168.1.129 from 192.168.1.1
,I/ActivityManager( 1016): Killing 5753:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,I/ActivityManager( 1016): Killing 5768:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6421): MountEmulatedStorage(),
E/Zygote  ( 6421): v2
I/libpersona( 6421): KNOX_SDCARD checking this for 1000
I/libpersona( 6421): KNOX_SDCARD not a persona
I/SELinux ( 6421): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1016): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6421 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 6421): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6421): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/dhcpcd  ( 6374): wlan0: leased 192.168.1.129 for 86400 seconds
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1016): failed to open /acct/uid_10156/pid_5753/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5768/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6421): TimaSignature is unavailable
,D/ActivityThread( 6421): Added TimaKeyStore provider
,I/WebViewFactory( 6325): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,I/LibraryLoader( 6325): Time to load native libraries: 2 ms (timestamps 6971-6973),
I/LibraryLoader( 6325): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6325): Binding Chromium to main looper Looper (main, tid 1) {33904d10},
I/LibraryLoader( 6325): Expected native library version number "",actual native library version number ""
I/chromium( 6325): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6325): Initializing chromium process, singleProcess=true
,W/art     ( 6325): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6325): ApplicationContext is null in ApplicationStatus
,I/DIAGMON_AGENT( 6421): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,W/chromium( 6325): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 6325): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
I/chromium( 6325): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,I/Adreno-EGL( 6325): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6325): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6325): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6325): Local Branch: 
I/Adreno-EGL( 6325): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6325): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6325):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/AudioManagerAndroid( 6325): Requires BLUETOOTH permission
,I/NSApplication( 6325): Starting up...
,E/WifiNative-wlan0( 1016): do suspend true
,D/WifiP2pService( 1016): InactiveState{ what=143375 }
,D/WifiP2pService( 1016): P2pEnabledState{ what=143375 }
,I/DIAGMON_AGENT( 6421): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,D/StatusBar.NetworkController( 1179): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 1016): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
E/WifiStateMachine( 1016): VerifyingLinkState enter
,D/WifiNative-wlan0( 1016): callSECApiInt - ID [210]
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/ConnectivityService( 1016): updateNetworkInfo()
,D/ConnectivityService( 1016): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,D/ConnectivityService( 1016): Adding iface wlan0 to network 503
,I/DIAGMON_AGENT( 6421): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 6421): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6421): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:,
I/DIAGMON_AGENT( 6421): ./extraInfo: <unknown ssid>
W/DIAGMON_AGENT( 6421): [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,D/WifiWatchdogStateMachine( 1016): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 1016): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.DnsResolver( 1016): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker( 1016): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1016): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1016): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService( 1016): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/StatusBar.NetworkController( 1179): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/ActivityManager( 1016): Killing 5375:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
D/ConnectivityService( 1016): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,E/ConnectivityService( 1016): Unexpected mtu value: 0, wlan0
,D/ConnectivityService( 1016): Setting Dns servers for network 503 to [/192.168.1.1]
,D/ConnectivityService( 1016): LTETest block dns file not exists
E/WifiStateMachine( 1016): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/ConnectivityService( 1016): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503],
,I/WifiTrafficPoller( 1016): evaluateTrafficStatsPolling
,E/ConnectivityService( 1016): updateNetworkInfo()
,E/ConnectivityService( 1016): updateNetworkInfo()
D/ConnectivityService( 1016): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService( 1016): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,I/System.out( 1016): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): uids 1000
D/ConnectivityService( 1016): rematching NetworkAgentInfo [WIFI () - 503]
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 1000
,D/StatusBar.NetworkController( 1179): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1016):    accepting network in place of null
,D/WIFI_P2P( 1016): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1450): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/TelephonyNetworkFactory( 1450): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker( 1016): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
E/CSLegacyTypeTracker( 1016): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/ConnectivityService( 1016): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/WIFI    ( 1016): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/ConnectivityService( 1016): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService( 1016): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,I/WifiTrafficPoller( 1016): evaluateTrafficStatsPolling
I/WifiTrafficPoller( 1016): mBoosterFLAG : 0
I/WifiTrafficPoller( 1016): current booster mode : FullMode
,D/EntConnectivity( 1016): Not allowed due to - mEnabled false - primarySimSlot false
,D/ConnectivityManager.CallbackHandler( 1179): CM callback handler got msg 524290
,D/WifiNative-wlan0( 1016): callSECApiVoid - ID [212]
,D/ConnectivityManager.CallbackHandler( 2012): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/Tethering( 1016): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,D/Tethering( 1016): MasterInitialState.processMessage what=3
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,V/NetworkStats( 1016): updateIfacesLocked()
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,V/NetworkStats( 1016): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1016): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1016): UpdateStatsForKnox main else ---
,V/NetworkStats( 1016): performPollLocked() took 4ms
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
V/NetworkStats( 1016): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,W/libprocessgroup( 1016): failed to open /acct/uid_10032/pid_5375/cgroup.procs: No such file or directory
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1179): EthernetConnected: false
,D/StatusBar.NetworkController( 1179): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1179): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1179): updateDataNetType()
D/StatusBar.NetworkController( 1179): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1179): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1179): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1179): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1179): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6494): MountEmulatedStorage(),
,E/Zygote  ( 6494): v2,
I/libpersona( 6494): KNOX_SDCARD checking this for 10125
I/libpersona( 6494): KNOX_SDCARD not a persona
,I/ActivityManager( 1016): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6494 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 5411:com.sec.knox.bridge/1000 (adj 15): empty #31
I/SELinux ( 6494): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6494): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6494): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/System.out( 1016): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/TimaKeyStoreProvider( 6494): TimaSignature is unavailable
,D/ActivityThread( 6494): Added TimaKeyStore provider
,W/ResourcesManager( 6494): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6494): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6494): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 6494): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6494): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 6494): PeriphStartReceiver.onReceive - no need to start
,I/splitIntent( 1016): Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1016): Killing 5466:com.android.vending/u0a28 (adj 15): empty #31
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 15 Jan 2016 13:01:23 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452862883835], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452862883807]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Validated
D/ConnectivityService( 1016): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1016): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1016): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 1016): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1179): CM callback handler got msg 524290
,D/ConnectivityService( 1016): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 2012): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1179): EthernetConnected: false
,D/StatusBar.NetworkController( 1179): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1179): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1179): updateDataNetType()
D/StatusBar.NetworkController( 1179): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1179): updateLTEICONDataNetType:0
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
D/StatusBar.NetworkController( 1179): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1179): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/StatusBar.NetworkController( 1179): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/Hs20UtilService( 3472): Starting #10
I/Hs20UtilService( 3472): Message received 5007
,D/NearbySettings( 1371): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1371): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1371): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1371): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1371): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1371): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3472): Starting #11
,I/Hs20UtilService( 3472): Message received 5007
,D/NearbySettings( 1371): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1371): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3472): Starting #12
,I/Hs20UtilService( 3472): Message received 5007
,D/NearbySettings( 1371): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1371): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1371): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1371): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1371): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1371): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/NearbySettings( 1371): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1371): MountReceiver.onReceive - Keep current state
I/Hs20UtilService( 3472): Starting #13
,D/WifiStateMachine( 1016): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/Hs20UtilService( 3472): Message received 5007
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravity
,D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravityXOffset
,D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravityYOffset
D/SecContentProvider2( 1016): mCursor = null,
,D/SecContentProvider2( 1016): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1016): mCursor = null
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5411/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10028/pid_5466/cgroup.procs: No such file or directory
,I/SurfaceFlinger(  258): id=14 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 1016): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1016
,D/SRIB_DCS( 1179): log_dcs ThreadedRenderer::initialize entered! 
,E/SMD     (  291): DCD OFF
,D/ConnectivityService( 1016): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1016): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1179): CM callback handler got msg 524295
,D/ConnectivityService( 1016): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1179): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 2012): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 2012): CM callback handler got msg 524295
,D/ConnectivityService( 1016): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,I/NetworkMonitor( 6232): type=WIFI subType= reason=null isConnected=true
,I/PCWCLIENTTRACE_PushUtil( 5736): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5736): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5736): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5736): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 3095): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/splitIntent( 1016): Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
I/splitIntent( 1016): finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,V/MusicLeanback( 6232): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/GpsLocationProvider( 1016): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/accuweather( 1728): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/FOTA_Client( 6249): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/daemonapp( 1303): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1016): mCursor = null
,I/FOTA_Client( 6249): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,D/accuweather( 1728): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,I/FOTA_Client( 6249): [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
D/accuweather( 1728): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1728): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1728): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,W/FOTA_Client( 6249): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,D/SecurityLogAgent( 6351): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6351): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6351): StateMachine : Current State = 1
,D/SecurityLogAgent( 6351): StateMachine : Changed Current State = 1
,D/accuweather( 1728): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/KLMS-2.5.183: ( 3515): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jan 15 14:01:24 GMT+01:00 2016
,D/accuweather( 1728): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.183: ( 3515): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.183: ( 3515): KLMSIntentService(): onCreate()
,I/DIAGMON_AGENT( 6421): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6421): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6421): ./extraInfo: "NG700"
,I/KLMS-2.5.183: ( 3515): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/DIAGMON_AGENT( 6421): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/KLMS-2.5.183: ( 3515): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,I/KLMS-2.5.183: ( 3515): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,D/WaitQueueForNetworkActivate( 5820): notifyNetworkActivated
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.183: ( 3515): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.183: ( 3515): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.183: ( 3515): StateImplV2(): networkChangeListener().START
,I/KLMS-2.5.183: ( 3515): NetworkChangeOperations(): uploadRequestLog().START 
,D/QuickConnect( 6494): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6494): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 6494): PeriphStartReceiver.onReceive - no need to start
,W/ContextImpl( 5820): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/KLMS-2.5.183: ( 3515): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.5.183: ( 3515): StateImplV2(): networkChangeListener().END
,I/KLMS-2.5.183: ( 3515): KLMSIntentService(): onDestroy()
,E/SPPClientService( 5844): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/DBG_POLICYDM( 5783): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5783): [com.policydm.XDMApplication(469/isNetworkChanged)] a previous network is 0, current network is 2
,E/DBG_POLICYDM( 5783): [com.policydm.XDMApplication(471/isNetworkChanged)] network changed.... 
,I/SA      ( 6002): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,I/SA      ( 6002): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 6002): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6002): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 6002): [OR] == isSIMCardReady false ==
,I/SA      ( 6002): [SCU] == networkStateCheck == true
,I/SA      ( 6002): [DM] getCountryCodeFromCSC : PL
I/SA      ( 6002): isChinaCountryCode : false
I/SA      ( 6002): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6002): [OR] == networkStateCheck true ==
,I/SA      ( 6002): [OR] GetMyCountryZoneTask
,I/SA      ( 6002): [OR] onReceive END
,I/SA      ( 6002): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 1228): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/ActivityManager( 1016): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/DBG_POLICYDM( 5783): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5783): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,D/SecContentProvider2( 1016): uri = 15 selection = getAppBlockDownloadState
,D/SecContentProvider2( 1016): mCursor = null
,I/DBG_POLICYDM( 5783): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/SA      ( 6002): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 6002): [SSP] query invoked
,I/DBG_POLICYDM( 5783): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5783): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5783): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5783): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_POLICYDM( 5783): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,I/SA      ( 6002): [TPMU] GetMccFromDB : null
,I/SA      ( 6002): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6002): [TPM] isNoProxy(default) : true
,E/DBG_POLICYDM( 5783): [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,E/File    ( 6002): fail readDirectory() errno=2
,I/DBG_POLICYDM( 5783): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,D/ActivityManager( 1016): startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 5820): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5820): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 5820): exit::IDLE
D/InitializeManagerStateMachine( 5820): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5820): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5820): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5820): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5820): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5820): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5820): entry::SUCCESS
D/hcjo    ( 5820): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5820): AutoUpdateTriggerManager:IDLE:notifyNextTime
,I/iu.Environment( 2012): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
D/hcjo    ( 5820): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,I/iu.UploadsManager( 2012): num queued entries: 0
,I/iu.UploadsManager( 2012): num updated entries: 0
,I/iu.SyncManager( 2012): NEXT; no task
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1016): Queue : backgroundsplit_2 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,D/InitializeManagerStateMachine( 5820): exit::SUCCESS
D/InitializeManagerStateMachine( 5820): entry::IDLE
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 10012
,D/ConnectivityService( 1016): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/SSRM:n  ( 1016): SIOP:: AP = 340
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,I/SA      ( 6002): [RC New] Execute method=[GET] start
,I/SA      ( 6002): [RC New] Security=[true]
,I/System.out( 6002): Thread-1045(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6002): Thread-1045(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 6002): Thread-1045(ApacheHTTPLog):isShipBuild true
I/System.out( 6002): Thread-1045(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6002): Thread-1045(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  278): uids 10041
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 10041
,I/SA      ( 6002): [RC New] [v2liruge] api execute + 631
,I/SA      ( 6002): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out( 6002): AsyncTask #1 calls detatch()
,I/SA      ( 6002): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 6002): [OCP] update openData : PL
,I/SA      ( 6002): [TPMU] getNetworkMcc : 
,I/SA      ( 6002): [SCU] saveMccToPreferece Start
,I/SA      ( 6002): [SCU] RegionMCC : 260
I/SA      ( 6002): [SSP] query invoked
,I/SA      ( 6002): [TPMU] GetMccFromDB : null
,I/SA      ( 6002): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6002): [SCU] saveMccToPreferece End
,I/SA      ( 6002): [RC New] executeRequest [v2liruge] end. 692
I/SA      ( 6002): [RC New] Execute end
,I/SA      ( 6002): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 6002): [OR] GetMyCountryZoneTask Success
,D/PackageManager( 1016): [MSG] MCS_UNBIND
,I/ActivityManager( 1016): Killing 5717:com.android.mms/u0a46 (adj 15): empty #31
,I/Choreographer( 6121): Skipped 312 frames!  The application may be doing too much work on its main thread.
,D/CountryDetector( 1016): No listener is left
,I/chromium( 6121): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/libprocessgroup( 1016): failed to open /acct/uid_10046/pid_5717/cgroup.procs: No such file or directory
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,I/dhcpcd  ( 6374): wlan0: sending IPv6 Router Solicitation
,E/SMD     (  291): DCD OFF
,D/ActivityManager( 1016): startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,I/SurfaceFlinger(  258): id=14 Removed Uoast (8/9)
,I/SurfaceFlinger(  258): id=14 Removed Uoast (-2/9)
,D/PowerManagerService( 1016): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1016) eventTime = 100975
,D/PowerManagerService( 1016): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1016 (0x0)
,D/PowerManagerService( 1016): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1016, ws=WorkSource{10054}) (elapsedTime=3483)
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1834): callingUid 10012, callindPid: 1834
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/GAV4    ( 6325): Thread[GAThread,5,main]: No campaign data found.
,I/MusicLeanback( 6232): Conditions not met for autocaching.
,I/MusicLeanback( 6232): Stop autocaching.
,E/GmsUtils( 6232): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,E/GmsUtils( 6232): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5736): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5736): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5736): [GetString-S]
,I/ReactiveServiceManager( 5736): Supported : 1
,D/QSEECOMAPI: ( 1016): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1016): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1016): Loaded image: APP id = 11
,D/QSEECOMAPI: ( 1016): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 1016): QSEECom_shutdown_app, app_id = 11
,E/terrier ( 1016): handleString: Failed to handle string(-4)
E/terrier ( 1016): Java_com_android_server_ReactiveService_GetString: error code = [-4]
,D/PCWCLIENTTRACE_SecurePreferencesJNI( 5736): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5736): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5736): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5736): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5736): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 5736): [ensureRegistration] - No Samsung account
,V/AlarmManager( 1016): waitForAlarm result :4
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6546): MountEmulatedStorage(),
,I/libpersona( 6546): KNOX_SDCARD checking this for 10028
E/Zygote  ( 6546): v2
I/libpersona( 6546): KNOX_SDCARD not a persona
I/SELinux ( 6546): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6546 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6546): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6546): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
E/SMD     (  291): DCD OFF
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: android, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
,I/BackgroundCompactionService( 1016): onStart. jobID=801
,I/BackgroundCompactionService( 1016): onStart done. jobID=801
,I/BackgroundCompactionService( 1016): Execute BGCompaction (type1). (0 times)
,I/BackgroundCompactionService( 1016): compact_memory command done
,D/TimaKeyStoreProvider( 6546): TimaSignature is unavailable
,D/ActivityThread( 6546): Added TimaKeyStore provider
,D/Finsky  ( 6546): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/ActivityManager( 1016): Waited long enough for: ServiceRecord{3c92769b u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,D/Finsky  ( 6546): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6546): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6546): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Ads     ( 6546): Skipping gmscore version check
,D/Finsky  ( 6546): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6546): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 6546): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/Finsky  ( 6546): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/Finsky  ( 6546): [1150] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6546): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ActivityManager( 1016): Killing 5913:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,W/libprocessgroup( 1016): failed to open /acct/uid_10047/pid_5913/cgroup.procs: No such file or directory
,I/dhcpcd  ( 6374): wlan0: sending IPv6 Router Solicitation
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4347, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1016): !@Sync 3
,D/ActivityManager( 1016): startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.preloadupdate.PreloadUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 5820): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5820): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5820): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5820): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 5820): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5820): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5820): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5820): entry::IDLE
,V/AlarmManager( 1016): waitForAlarm result :4
,D/SSRM:n  ( 1016): SIOP:: AP = 310
,I/PowerManagerService( 1016): [PWL] Off : 30s ago
,I/dhcpcd  ( 6374): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 6374): wlan0: no IPv6 Routers available
,I/Atfwd_Sendcmd(  317): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  317): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,I/ActivityManager( 1016): Waited long enough for: ServiceRecord{2f1aea69 u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,V/AlarmManager( 1016): waitForAlarm result :4
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1834): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1834): Vacuum at: now=1452862899788 tag=VacuumService
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 47435(2MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 27MB/41MB, paused 2.487ms total 148.840ms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.games.chimera.GamesSyncServiceMainProxy; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 2012): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2012): Module APK com.google.android.play.games already loaded
,I/GamesSyncServiceMain( 2012): Found unexpected GCM tag when scheduling; aborting
,W/GamesSyncServiceMain( 2012): Failed to execute periodic sync, missing client context - aborting
,D/FactoryTest( 5293): Not factory mode
,D/FactoryTest( 5293): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 5293): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 5293): still no open session command from host, so toast
,I/Timeline( 5293): Timeline: Activity_launch_request id:com.android.settings time:114152
,W/ContextImpl( 5293): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
E/PersonaManagerService( 1016): inState():  stateMachine is null !!
W/ContextImpl( 5293): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
I/PersonaManagerService( 1016): PersonaId don't exist
I/ActivityManager( 1016): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.android.settings
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): mDVFSHelper.acquire()
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,D/PersonaManager( 1016): isKioskContainerExistOnDevice
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/InputDispatcher( 1016): Focused application set to: xxxx
D/InputDispatcher( 1016): Focus left window: 6121
,E/MTPRx   ( 5293): started activity for popup,
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,W/ResourcesManager( 5293): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 5293): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5293): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5293): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5293): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5293): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 5293): PREF_DONT_ASK_AGAIN : true
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.android.settings
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1016): Focused application set to: xxxx
,D/InputDispatcher( 1016): Focus entered window: 6121
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/InputMethodManagerService( 1016): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService( 1016): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@10f6d75 attribute=null, token = android.os.BinderProxy@12bf79b3
,D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,D/SettingsReceiverActivity( 5293): dev.kiessupport is : TRUE
,D/PhoneWindow( 5293): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 5293): *FMB* installDecor flags : 8388610
,D/ActivityManager( 1016): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1016): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1016): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1016): handleActiveUserChange for user 0
D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
,V/ActivityThread( 6121): updateVisibility : ActivityRecord{106ca414 token=android.os.BinderProxy@1c385226 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/Timeline( 6121): Timeline: Activity_idle id: android.os.BinderProxy@1c385226 time:114311
,D/PersonaManager( 1016): isKioskContainerExistOnDevice
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate,
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ActivityManager( 1016): mDVFSHelper.release(),
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1016): SIOP:: AP = 300
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 1
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1016): [PWL] Off : 50s ago
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  291): DCD OFF
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/AlarmManager( 1016): waitForAlarm result :8
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1016): !@Sync 4
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,I/PowerManagerService( 1016): [PWL] Off : 75s ago
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 4
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1016): !@Sync 5,
,I/ClearcutLoggerApiImpl( 1834): disconnect managed GoogleApiClient
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.,
,E/SMD     (  291): DCD OFF,
,I/PowerManagerService( 1016): [PWL] Off : 105s ago
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1016): !@Sync 6
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,V/AlarmManager( 1016): waitForAlarm result :4
,V/AlarmManager( 1016): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManagerEXT( 1016): <AppSync3 Whitelist>
,V/AlarmManagerEXT( 1016): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1179): handleTimeUpdate
,D/SecKeyguardClockView( 1179): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1179): HomeTimezone(): 1
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.EventLogService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/KeyguardEffectViewController( 1179): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1179): *** don't update sliding image ***
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 2012): Aggregate from 1452861124726 (log), 1452861124726 (data)
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6646): MountEmulatedStorage(),
E/Zygote  ( 6646): v2
I/libpersona( 6646): KNOX_SDCARD checking this for 1000
I/libpersona( 6646): KNOX_SDCARD not a persona
,I/SELinux ( 6646): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=6646 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 6646): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6646): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 6646): TimaSignature is unavailable
,D/ActivityThread( 6646): Added TimaKeyStore provider
,W/ResourcesManager( 6646): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/ActivityManager( 1016): Killing 5929:com.wsomacp/u0a25 (adj 15): empty #31
,W/libprocessgroup( 1016): failed to open /acct/uid_10025/pid_5929/cgroup.procs: No such file or directory
,E/SMD     (  291): DCD OFF,
,I/Atfwd_Sendcmd(  317): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  317): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate,
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 140s ago
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/Watchdog( 1016): !@Sync 7
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 2
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,V/AlarmManager( 1016): waitForAlarm result :8
,E/SMD     (  291): DCD OFF
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1016): !@Sync 8
,I/PowerManagerService( 1016): [PWL] Off : 180s ago,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1016): !@Sync 9
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1016): Plugged
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 5
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF,
,I/PowerManagerService( 1016): [PWL] Off : 225s ago,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,E/SMD     (  291): DCD OFF
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/TimaService( 1016): TIMA: TimaService scheduler is intialized. 
D/TimaService( 1016): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1016): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1016): initializing...,
I/TLC_TIMA_PKM_initialize( 1016): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1016): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1016): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1016): process = tima_pkm, process_strlen = 8,
,I/TZ: qc_tlc_communication( 1016): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1016): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1016): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1016): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1016): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1016): Loaded image: APP id = 12
,I/TZ: qc_tlc_communication( 1016): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1016): Trustlet response is completed
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF,
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
D/TimaService( 1016): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1016): !@Sync 10
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF
,I/Atfwd_Sendcmd(  317): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  317): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1016): !@Sync 11,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 1016): stay LED for fully charged
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,I/PowerManagerService( 1016): [PWL] Off : 275s ago
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 2,
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1016): !@Sync 12,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1179): handleTimeUpdate
,D/SecKeyguardClockView( 1179): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1179): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1179): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1179): *** don't update sliding image ***
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1016): !@Sync 13,
,I/PowerManagerService( 1016): [PWL] Off : 330s ago
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1016): stay LED for fully charged
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :8,
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1016): !@Sync 14
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,I/Atfwd_Sendcmd(  317): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  317): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.,
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1016): !@Sync 15,
,I/PowerManagerService( 1016): [PWL] Off : 390s ago,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,I/MotionRecognitionService( 1016): Plugged,
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,I/bootchecker(  312): bootchecker wake up!!,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1016): !@Sync 16,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1016): !@Sync 17,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1016): Plugged
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
I/MotionRecognitionService( 1016): mGripSensorEnabled= false,
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1016): [PWL] Off : 455s ago
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1016): !@Sync 18,
,I/Atfwd_Sendcmd(  317): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  317): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,I/Atfwd_Daemon(  317): Stop the daemon....
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1016): !@Sync 19,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.,
,E/SMD     (  291): DCD OFF,
,I/PowerManagerService( 1016): [PWL] Off : 525s ago
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/TimaService( 1016): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1016): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1016): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1016): !@Sync 20,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1016): !@Sync 21,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1016): !@Sync 22,
,I/PowerManagerService( 1016): [PWL] Off : 600s ago,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1016): !@Sync 23
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1016): !@Sync 24,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,I/PowerManagerService( 1016): [PWL] Off : 680s ago,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate,
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1016): !@Sync 25,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1016): Plugged
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,V/AlarmManager( 1016): waitForAlarm result :8,
,E/Watchdog( 1016): !@Sync 26,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1016): !@Sync 27,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,I/PowerManagerService( 1016): [PWL] Off : 765s ago
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1016): !@Sync 28,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1016): !@Sync 29,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1016): stay LED for fully charged
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,D/TimaService( 1016): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1016): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1016): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1016): !@Sync 30,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1016): [PWL] Off : 855s ago,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1016): !@Sync 31,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
I/MotionRecognitionService( 1016): Plugged
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1016): !@Sync 32,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :4,
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1179): handleTimeUpdate
,D/SecKeyguardClockView( 1179): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1179): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1179): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1179): *** don't update sliding image ***
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms,
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.uploader.UploaderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeConfigurator( 1834): Scheduling Phenotype for one-off execution 7654 seconds from now (1452863785347)
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GetConfigurationSnapshotOperation( 1834): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeFlagCommitter( 1834): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1834): Using platform SSLCertificateSocketFactory
,D/LocationManagerService( 1016): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1834): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1834): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1834): (HTTPLog)-Static: isShipBuild true
I/System.out( 1834): (HTTPLog)-Thread-262-791611016: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1834): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 10012
,I/System.out( 1834): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1834): Tagging socket 83 with tag 1000120100000000{268440065,0} for uid -1, pid: 1834, getuid(): 10012
,I/qtaguid ( 1834): Tagging socket 87 with tag 1000120100000000{268440065,0} for uid -1, pid: 1834, getuid(): 10012
,D/LocationManagerService( 1016): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1834): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1834): Tagging socket 83 with tag 1000120100000000{268440065,0} for uid -1, pid: 1834, getuid(): 10012
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1016): userId = 0, bbcId = -10000,
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1016): !@Sync 33
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,I/PowerManagerService( 1016): [PWL] Off : 950s ago,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,V/AlarmManager( 1016): waitForAlarm result :8
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1016): !@Sync 34
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1016): !@Sync 35,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
D/BatteryService( 1016): stay LED for fully charged,
D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate,
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1016): !@Sync 36
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1016): !@Sync 37,
,I/PowerManagerService( 1016): [PWL] Off : 1050s ago
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false,
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1016): Plugged
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1016): !@Sync 38,
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1016): Plugged
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1016): !@Sync 39,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,D/TimaService( 1016): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1016): TimaServiceHandler.handleMessage what =1
D/TimaService( 1016): TIMA: checkEvent, operation: 50000 subject: 10000
,I/UsageStatsService( 1016): User[0] Flushing usage stats to disk,
,I/ApplicationUsage( 1016): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 1016): Updating Usage Statistics in DB @ 1452864002169
,I/ApplicationPolicy( 1016): updateDataUsageMap
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/NetworkDataUsageDb( 1016): ::getAppControlDB: DB is Created 
,I/NetworkDataUsageDb( 1016): ::isTableExists: Table exists 
,I/ApplicationUsage( 1016): Done Updating Usage Statistics in DB @ 1452864002465
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1016): !@Sync 40,
,E/SMD     (  291): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 1155s ago
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1016): Plugged
D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1016): mGripSensorEnabled= false,
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1016): !@Sync 41,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1016): !@Sync 42,
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1016): !@Sync 43,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1016): !@Sync 44,
,E/SMD     (  291): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,I/PowerManagerService( 1016): [PWL] Off : 1266s ago
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1016): !@Sync 45,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1016): !@Sync 46,
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged,
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1016): mGripSensorEnabled= false,
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1016): !@Sync 47,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1016): !@Sync 48,
,I/PowerManagerService( 1016): [PWL] Off : 1381s ago,
,E/SMD     (  291): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1016): !@Sync 49,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/TimaService( 1016): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 1016): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1016): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1016): !@Sync 50,
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1016): Plugged,
D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1016): !@Sync 51,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1016): !@Sync 52,
,I/PowerManagerService( 1016): [PWL] Off : 1501s ago
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged,
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED,
,I/MotionRecognitionService( 1016): Plugged
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1016): !@Sync 53
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1016): !@Sync 54
,E/SMD     (  291): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1016): !@Sync 55
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1016): !@Sync 56
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1016): Plugged,
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 1626s ago,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged,
D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1016): !@Sync 57
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1016): Plugged
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1016): !@Sync 58
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
I/MotionRecognitionService( 1016): Plugged,
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1016): !@Sync 59
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF
,D/NetworkStatsFactory( 1016): UpdateStatsForKnox updated
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,D/TimaService( 1016): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 1016): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1016): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1016): !@Sync 60
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,I/PowerManagerService( 1016): [PWL] Off : 1756s ago,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1016): !@Sync 61,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate,
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1016): !@Sync 62
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1016): Plugged
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :4
,E/SMD     (  291): DCD OFF
D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1179): handleTimeUpdate
,I/ActivityManager( 1016): Killing 6002:com.osp.app.signin/u0a41 (adj 15): empty for 1800s
,D/SecKeyguardClockView( 1179): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
I/ActivityManager( 1016): Killing 6494:com.samsung.android.sconnect/u0a125 (adj 15): empty for 1800s
,I/ActivityManager( 1016): Killing 6103:com.google.android.apps.plus/u0a120 (adj 15): empty for 1800s
D/SecKeyguardClockView( 1179): HomeTimezone(): 1
I/ActivityManager( 1016): Killing 6325:com.google.android.apps.magazines/u0a113 (adj 15): empty for 1800s
,I/ActivityManager( 1016): Killing 6303:com.sec.android.soagent/u0a34 (adj 15): empty for 1800s
I/ActivityManager( 1016): Killing 6280:com.android.chrome/u0a81 (adj 15): empty for 1800s
I/ActivityManager( 1016): Killing 6421:com.sec.android.diagmonagent/1000 (adj 15): empty for 1800s
,I/ActivityManager( 1016): Killing 6368:com.samsung.android.service.travel/u0a159 (adj 15): empty for 1800s
,I/ActivityManager( 1016): Killing 6351:com.samsung.android.securitylogagent/1000 (adj 15): empty for 1800s
,I/ActivityManager( 1016): Killing 6400:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1800s
I/ActivityManager( 1016): Killing 6264:com.android.email/u0a145 (adj 15): empty for 1800s
,I/ActivityManager( 1016): Killing 5736:com.sec.pcw.device/1000 (adj 15): empty for 1800s
D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
I/ActivityManager( 1016): Killing 5897:com.sec.android.provider.badge/u0a72 (adj 15): empty for 1802s
,I/ActivityManager( 1016): Killing 6068:com.samsung.helphub/1000 (adj 15): empty for 1807s
I/ActivityManager( 1016): Killing 6051:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty for 1807s
I/ActivityManager( 1016): Killing 5802:com.google.android.apps.docs/u0a91 (adj 15): empty for 1808s
I/ActivityManager( 1016): Killing 5871:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty for 1808s
,I/ActivityManager( 1016): Killing 5972:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty for 1808s
,I/ActivityManager( 1016): Killing 5950:com.sec.android.app.soundalive/u0a53 (adj 15): empty for 1808s
,I/ProcessStatsService( 1016): Prepared write state in 9ms
,D/KeyguardEffectViewController( 1179): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1179): *** don't update sliding image ***
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ProcessStatsService( 1016): Pruning old procstats: /data/system/procstats/state-2016-01-14-19-22-06.bin
,W/libprocessgroup( 1016): failed to open /acct/uid_10038/pid_5871/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10125/pid_6494/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10120/pid_6103/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10057/pid_5972/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10002/pid_6400/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10159/pid_6368/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10034/pid_6303/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10081/pid_6280/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_6421/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10100/pid_6051/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10053/pid_5950/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10072/pid_5897/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10041/pid_6002/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5736/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10113/pid_6325/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_6068/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_6351/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10091/pid_5802/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10145/pid_6264/cgroup.procs: No such file or directory
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,TIME-OUT KILL (timeout was 1800000ms),D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
E/SMD     (  291): DCD OFF
D/SSRM:n  ( 1016): SIOP:: AP = 260
D/AndroidRuntime( 7360): 
D/AndroidRuntime( 7360): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7360): CheckJNI is OFF
D/AndroidRuntime( 7360): readGMSProperty: start
D/AndroidRuntime( 7360): readGMSProperty: already setted!!
D/AndroidRuntime( 7360): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 7360): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 7360): readGMSProperty: end
D/AndroidRuntime( 7360): addProductProperty: start
E/AffinityControl( 7360): AffinityControl: registerfunction enter
D/AndroidRuntime( 7360): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 1016): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1016): START PACKAGE DELETE: observer{49704713}
D/PackageManager( 1016): pkg{<packageName>}
D/PackageManager( 1016): user{0}
D/PackageManager( 1016): caller{2000}
D/PackageManager( 1016): flags{3}
D/PersonaManagerService( 1016): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1016): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1016): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1016): !@killApplicatoin: 10155, uninstall pkg
D/PackageManager( 1016): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
I/ActivityManager( 1016): Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
D/PackageManager( 1016): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
I/ActivityManager( 1016): Killing 6121:com.test.thalitest/u0a155 (adj 0): stop com.test.thalitest cause uninstall pkg
D/PackageManagerService( 1016): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1016): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1016): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1016): getApplicationUninstallationEnabled :  enabled true
E/SMD     (  291): DCD OFF
I/WindowState( 1016): WIN DEATH: Window{260d8b70 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  258): id=13 Removed NainActivit (6/8)
I/SurfaceFlinger(  258): id=13 Removed NainActivit (-2/8)
D/InputDispatcher( 1016): Focus left window: 6121
D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
I/ActivityManager( 1016):   Force finishing activity ActivityRecord{8aa95d3 u0 com.test.thalitest/.MainActivity t7}
D/InputDispatcher( 1016): Focused application released
W/ActivityManager( 1016): Spurious death for ProcessRecord{2b8350e 6121:com.test.thalitest/u0a155}, curProc for 6121: null
I/ActivityManager( 1016): Force stopping com.test.thalitest appid=10155 user=0: pkg removed
W/ActivityManager( 1016): CustomStartingWindow se packge removed so remove capture also
I/art     ( 5554): Explicit concurrent mark sweep GC freed 2390(140KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 732us total 33.996ms
I/InputReader( 1016): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 1767): mOCRHelper is null
W/GeofencerStateMachine( 1834): Ignoring removeGeofence because network location is disabled.
I/art     ( 2012): Explicit concurrent mark sweep GC freed 10174(599KB) AllocSpace objects, 5(80KB) LOS objects, 25% free, 14MB/18MB, paused 1.292ms total 75.341ms
D/RegisteredComponentCache( 1439): Collect Tech packages for Knox
I/KLMS-2.5.183: ( 3515): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jan 15 14:31:31 GMT+01:00 2016
D/ActivityManager( 1016): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
D/EnterpriseDeviceManagerService( 1016): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1016): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1016): no available spell checker services found
D/PersonaManager( 1439): isKioskContainerExistOnDevice
I/KLMS-2.5.183: ( 3515): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 1016): Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
I/splitIntent( 1016): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7374): MountEmulatedStorage()
E/Zygote  ( 7374): v2
I/libpersona( 7374): KNOX_SDCARD checking this for 10094
I/libpersona( 7374): KNOX_SDCARD not a persona
I/SELinux ( 7374): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux ( 7374): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7374): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7374 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
I/KLMS-2.5.183: ( 3515): KLMSIntentService(): onCreate()
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7389): MountEmulatedStorage()
E/Zygote  ( 7389): v2
I/KLMS-2.5.183: ( 3515): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/libpersona( 7389): KNOX_SDCARD checking this for 10044
I/libpersona( 7389): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7389 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/SELinux ( 7389): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 7389): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7389): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7374): TimaSignature is unavailable
D/ActivityThread( 7374): Added TimaKeyStore provider
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.183: ( 3515): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
D/TimaKeyStoreProvider( 7389): TimaSignature is unavailable
D/ActivityThread( 7389): Added TimaKeyStore provider
E/Zygote  ( 7405): MountEmulatedStorage()
E/Zygote  ( 7405): v2
I/libpersona( 7405): KNOX_SDCARD checking this for 10149
I/libpersona( 7405): KNOX_SDCARD not a persona
I/SELinux ( 7405): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 7405): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7405 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 7405): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.5.183: ( 3515): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
D/TimaKeyStoreProvider( 7405): TimaSignature is unavailable
D/ActivityThread( 7405): Added TimaKeyStore provider
I/KLMS-2.5.183: ( 3515): KLMSIntentService(): PACKAGE_REMOVED
E/SQLiteLog( 6646): (284) automatic index on crash_info_summary(package_name_touched)
I/KLMS-2.5.183: ( 3515): KLMSIntentService(): listeningToPackageRemoved().START
I/KLMS-2.5.183: ( 3515): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
I/art     ( 6646): Explicit concurrent mark sweep GC freed 482(40KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 6MB/9MB, paused 655us total 29.994ms
D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1016): mCursor = null
W/ResourcesManager( 7389): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7389): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7389): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7389): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7389): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 7389): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7389): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7389): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/elm:15183( 7374): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.samsung.android.sm, calleePkgName: com.sec.android.provider.badge
I/art     ( 1016): Explicit concurrent mark sweep GC freed 68046(8MB) AllocSpace objects, 344(5MB) LOS objects, 33% free, 28MB/42MB, paused 4.101ms total 316.302ms
I/art     ( 1016): WaitForGcToComplete blocked for 309.033ms for cause Explicit
D/elm:15183( 7374): ELMEngine.ELMEngine( context ).
D/elm:15183( 7374): MDMBridge.setEnterpriseBridge()
D/PersonaManager( 1439): isKioskContainerExistOnDevice
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7420): MountEmulatedStorage()
E/Zygote  ( 7420): v2
I/libpersona( 7420): KNOX_SDCARD checking this for 10072
I/SELinux ( 7420): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 7420): KNOX_SDCARD not a persona
I/SELinux ( 7420): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7420): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7420 uid=10072 gids={50072, 9997} abi=armeabi-v7a
D/ActivityManager( 1016): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
D/ThemeInfoUtil( 7405): getCurrentFestivalName is [null]
D/ThemeInfoUtil( 7405): isCurrentFestival = false
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
D/TimaKeyStoreProvider( 7420): TimaSignature is unavailable
D/ActivityThread( 7420): Added TimaKeyStore provider
D/elm:15183( 7374): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/RegisteredServicesCache( 1439): empty dynamic service
D/elm:15183( 7374): ElmAgentService : onCreate()
I/KLMS-2.5.183: ( 3515): KLMSIntentService(): listeningToPackageRemoved().END
D/elm:15183( 7374): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15183( 7374): MainReceiver.listeningToPackageRemoved()
D/elm:15183( 7374): MDMBridge.getInstance()
D/elm:15183( 7374): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:15183( 7374): MDMBridge.getAllLicenseInfoFromSDK()
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7441): MountEmulatedStorage()
E/Zygote  ( 7441): v2
I/libpersona( 7441): KNOX_SDCARD checking this for 10152
I/libpersona( 7441): KNOX_SDCARD not a persona
I/SELinux ( 7441): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 7441): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7441): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7441 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.aasaservice, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/art     (  307): Explicit concurrent mark sweep GC freed 8697(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 625us total 20.554ms
D/TimaKeyStoreProvider( 7441): TimaSignature is unavailable
D/ActivityThread( 7441): Added TimaKeyStore provider
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 613us total 16.836ms
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 603us total 17.223ms
E/Zygote  ( 7456): MountEmulatedStorage()
E/Zygote  ( 7456): v2
I/libpersona( 7456): KNOX_SDCARD checking this for 1000
I/libpersona( 7456): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.samsung.aasaservice for broadcast com.samsung.aasaservice/.AASAUpdateReceiver: pid=7456 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 7456): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
I/SELinux ( 7456): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7456): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7471): MountEmulatedStorage()
E/Zygote  ( 7471): v2
I/libpersona( 7471): KNOX_SDCARD checking this for 1000
D/TimaKeyStoreProvider( 7456): TimaSignature is unavailable
I/libpersona( 7471): KNOX_SDCARD not a persona
D/ActivityThread( 7456): Added TimaKeyStore provider
I/ActivityManager( 1016): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7471 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 5783:com.policydm/1000 (adj 15): empty for 1807s
I/SELinux ( 7471): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 7471): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Killing 6249:com.sec.android.fotaclient/u0a9 (adj 15): empty for 1807s
W/ResourceType( 1016): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
E/SELinux ( 7471): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/elm:15183( 7374): ElmAgentService : onDestroy().
I/KLMS-2.5.183: ( 3515): KLMSIntentService(): onDestroy()
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TimaKeyStoreProvider( 7471): TimaSignature is unavailable
D/ActivityThread( 7471): Added TimaKeyStore provider
I/ActivityManager( 1016): Killing 6190:com.google.android.talk/u0a104 (adj 15): empty for 1806s
I/art     ( 1016): Explicit concurrent mark sweep GC freed 15024(746KB) AllocSpace objects, 1(22KB) LOS objects, 33% free, 27MB/41MB, paused 11.809ms total 334.466ms
D/NearbySource( 7389): Nearby Source Create!
D/NearbyContext( 7389): Nearby Context Create!
D/BadgeProvider( 7420): onCreate
D/BadgeProvider( 7420): DatabaseHelper
D/AASAservice-UpdateReceiver( 7456): AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
W/System.err( 7456): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 7456): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
W/System.err( 7456): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
W/System.err( 7456): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 7456): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 7456): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 7456): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7456): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7456): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 7456): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7456): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7456): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 7456): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
I/ActivityManager( 1016): Killing 5643:com.android.defcontainer/u0a4 (adj 15): empty for 1805s
E/SQLiteLog( 7441): (284) automatic index on shooting_modes(title_id)
W/ContextImpl( 7471): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7488): MountEmulatedStorage()
I/libpersona( 7488): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7488): v2
I/libpersona( 7488): KNOX_SDCARD not a persona
I/SELinux ( 7488): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
D/BadgeProvider( 7420): sendNotify entered. [uri] : content://com.sec.badge/apps
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
D/BadgeProvider( 7420): sendNotify, [notify] : null
D/BadgeProvider( 7420): update, [uri] : content://com.sec.badge/apps
D/BadgeProvider( 7420): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7420): update, [UpdateCount] : 1
W/ContextImpl( 7389): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource( 7389): Samsung link source created
I/ActivityManager( 1016): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7488 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 7488): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7488): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
D/TimaKeyStoreProvider( 7488): TimaSignature is unavailable
D/ActivityThread( 7488): Added TimaKeyStore provider
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ResourcesManager( 1016): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1016): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1016): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/Zygote  ( 7504): MountEmulatedStorage()
I/libpersona( 7504): KNOX_SDCARD checking this for 10156
E/Zygote  ( 7504): v2
I/libpersona( 7504): KNOX_SDCARD not a persona
I/SELinux ( 7504): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 7504): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7504): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7504 uid=10156 gids={50156, 9997} abi=armeabi-v7a
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/ActivityManager( 1016): Killing 5844:com.sec.spp.push/u0a35 (adj 15): empty for 1804s
D/RCPManagerService( 1016): PackageReceiver onReceive()
I/HarmonyEASService( 1016): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/PackageManager( 1016): delete codoeFile: 
D/KnoxMUMContainerPolicy( 1016): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1016): PackageRemovalReceiver::onReceive Enter
D/OTPFW   ( 1016): OtpDbHelper::getInstance New instance created
D/OTPFW   ( 1016): DBIntegrity::getInstance - New instance created
D/AASAuninstall( 1016): userId = 0, info.removedAppID = -1, info.uid = 10155, packageName = com.test.thalitest
I/AASA_removePackage( 1016): UID=10155 Target=com.test.thalitest
D/PackageManager( 1016): result of delete: 1{49704713}
I/ActivityManager( 1016): Killing 6232:com.google.android.music:main/u0a111 (adj 15): empty for 1803s
D/OTPFW   ( 1016): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
I/OTPFW   ( 1016): ProvisionData::getAllEntries Enter
E/OTPFW   ( 1016): ProvisionData::getAllEntries Table is empty
D/BackupManagerService( 1016): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1016): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1016): uID is 10155
V/EnterpriseBillingPolicy( 1016): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - end - null
D/TimaKeyStoreProvider( 7504): TimaSignature is unavailable
D/ActivityThread( 7504): Added TimaKeyStore provider
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1016): uID is 10155
V/EnterpriseBillingPolicy( 1016): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - end - null
D/SSRM:aZ ( 1016): MSG_TYPE_APP_REMOVED::
V/AlarmManagerEXT( 1016): com.test.thalitest(10155) is removed.
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/AndroidRuntime( 7360): Shutting down VM
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ResourcesManager( 7488): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/TaskPersister( 1016): removeObsoleteFile: deleting file=7_task.xml
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7520): MountEmulatedStorage()
I/libpersona( 7520): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7520): v2
I/libpersona( 7520): KNOX_SDCARD not a persona
I/SELinux ( 7520): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7520 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 7520): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7520): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/UsbSettingsManager( 1016): clearDefaults: com.test.thalitest
D/ContactProvider( 7389): getAllContactInfoList Start
I/CrashAnrDetector( 1016): onPackageRemoved : com.test.thalitest
E/SQLiteLog( 6646): (284) automatic index on crash_info_summary(package_name_touched)
I/TapandpayWidget:TapandpayAppWidgetProvider( 7504): onReceive()
D/TapandpayWidget:TapandpayAppWidgetProvider( 7504): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5783/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10009/pid_6249/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10104/pid_6190/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10004/pid_5643/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 7520): TimaSignature is unavailable
I/TapandpayWidget:Utils( 7504): Clear T&P info.
D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/RCPManager( 7488):  in createShortcut() for packageName: com.test.thalitest userId0
D/ActivityThread( 7520): Added TimaKeyStore provider
D/RCPManagerService( 1016):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1016): queryAllProviders():  providerCallBack is not register for 0

```
