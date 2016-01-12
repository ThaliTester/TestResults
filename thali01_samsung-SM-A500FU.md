#### Test 55613145ac448d4_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
D/Mms/MethodReflector( 5097): getTelephonyProperty is called
D/Mms/DownloadManager( 5097): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5097): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5097): auto download without roaming -> true
D/Mms/DownloadManager( 5097): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/MethodReflector( 5097): getSubId is called
E/DBG_POLICYDM( 5183): [com.policydm.agent.XDMTask(173/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized
D/Mms/DraftCache( 5097): [end]    rebuildCache consume time = 33.414427
D/Mms/MethodReflector( 5097): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 5097): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 5097): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 5097): getTelephonyProperty is called
D/Mms/DownloadManager( 5097): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 5097): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 5097): auto download without roaming -> true
D/Mms/DownloadManager( 5097): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 5097): auto download during roaming secondary -> false
D/Mms/DownloadManager( 5097): mAutoDownload ------> true
--------- beginning of system
W/ResourcesManager( 4831): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4831): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 4831): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4831): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4831): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4831): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4831): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 4831): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/SPPClientService( 5226): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 5226): [PushClientApplication] Push log off : This is Ship build version
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.sdk.samsunglink, hostingType: broadcast
D/SPPClientService( 5226): PushLog.txt file is not deleted.
D/SPPClientService( 5226): PushLog.txt file is not deleted.
D/SPPClientService( 5226): ============PushLog. stop!
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5247): MountEmulatedStorage()
E/Zygote  ( 5247): v2
I/SELinux ( 5247): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5247): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/libpersona( 5247): KNOX_SDCARD checking this for 10038
I/libpersona( 5247): KNOX_SDCARD not a persona
I/ActivityManager( 1013): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=5247 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1013): Killing 4100:com.android.calendar/u0a135 (adj 15): empty #31
E/SELinux ( 5247): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
E/PhotosPlugin( 5164): Loading PhotosPlugin
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
D/ActivityManager( 1013): startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
D/TimaKeyStoreProvider( 5247): TimaSignature is unavailable
D/ActivityThread( 5247): Added TimaKeyStore provider
D/ComposerPerformance( 5097): 1452596463705 ms / [DONE] Composer constructor
E/CII     ( 5097): CommonIMSInterface: VoLTE CSC feature disabled.
I/art     (  305): Explicit concurrent mark sweep GC freed 8743(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 655us total 47.318ms
I/Mms/ReservationManager( 5097): ReservationManager()
I/Mms/ReservationManager( 5097): resetAfterConnected()
D/Mms/Conversation( 5097): [start]    init() consume time = 103.869114
D/TP/MmsSmsProvider( 1437): query,matched:7, calling pid = 5097
D/TP/MmsSmsProvider( 1437): deleteConversation threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1437): match 7:Elapsed time : 2.163 ms
D/TP/MmsSmsProvider( 1437): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1437): updateThread(), thread_id = 9223372036854775807
V/TP/MmsSmsDatabaseHelper( 1437): sUpgradeVersion = 0, db.getVersion() = 81
W/ResourcesManager( 5247): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 621us total 17.419ms
W/ResourcesManager( 5247): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/TP/MmsSmsProvider( 1437): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1437): need read changed broadcast:false
D/Mms/Conversation( 5097): [end]    init consume time = 20.27448
D/Mms/MessagingNotification( 5097): [start]    init() consume time = 3.539114
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 635us total 17.219ms
I/Mms/ReservationManager( 5097): getReservedSendMessageCount(): retMessageCount=0
W/libprocessgroup( 1013): failed to open /acct/uid_10135/pid_4100/cgroup.procs: No such file or directory
D/Mms/MessagingNotification( 5097): [end]    init consume time = 13.472656
D/Mms/MmsApp( 5097): [end]    onCreate() consume time = 5.546979
D/TP/MmsSmsProvider( 1437): query,matched:0, calling pid = 5097
V/TP/MmsSmsProvider( 1437): getSimpleConversations entered.
D/Mms/SpamFilter( 5097): [start]    SpamFilter fill() begin consume time = 5.465782
D/TP/MmsSmsProvider( 1437): match 0:Elapsed time : 1.530 ms
D/Mms/Synchronizer( 5097): [start]    doSync consume time = 6.118177
D/TP/MmsSmsProvider( 1437): query,matched:400, calling pid = 5097
D/ActivityManager( 1013): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
D/TP/MmsSmsProvider( 1437): update, matched:300, calling pid = 5097
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
V/TP/MmsSmsProvider( 1437): syncDBData start
V/TP/MmsSmsProvider( 1437): syncDBData sms end
V/TP/MmsSmsProvider( 1437): syncDBData mms end
V/TP/MmsSmsProvider( 1437): syncDBData end
D/Mms/DownloadManager( 5097): Service state changed: Bundle[mParcelledData.dataSize=744]
D/Mms/DownloadManager( 5097): roaming ------> false, mSimSlot = 0
D/Mms/MethodReflector( 5097): getSubId is called
D/Mms/TelephonyUtils( 5097): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 5097): getTelephonyProperty is called
D/Mms/DownloadManager( 5097): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5097): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5097): auto download without roaming -> true
D/Mms/DownloadManager( 5097): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5097): mAutoDownload ------> true
E/Zygote  ( 5274): MountEmulatedStorage()
E/Zygote  ( 5274): v2
I/libpersona( 5274): KNOX_SDCARD checking this for 10072
I/libpersona( 5274): KNOX_SDCARD not a persona
I/SELinux ( 5274): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/Mms/ArtClassLoader( 5097): init [DONE] art
I/ActivityManager( 1013): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5274 uid=10072 gids={50072, 9997} abi=armeabi-v7a
D/Mms/Synchronizer( 5097): [end]    doSync consume time = 27.581198
I/SELinux ( 5274): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/Mms/SpamFilter( 5097): [end]    SpamFilter fill() finished consume time = 2.857344
E/SELinux ( 5274): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
E/SMD     (  287): DCD OFF
D/TimaKeyStoreProvider( 5274): TimaSignature is unavailable
D/Mms/FreeMessageStatusReceiver( 5097): onReceive, action : android.intent.action.PACKAGE_ADDED
D/ActivityThread( 5274): Added TimaKeyStore provider
D/ActivityManager( 1013): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
D/BadgeProvider( 5274): onCreate
D/BadgeProvider( 5274): DatabaseHelper
E/Zygote  ( 5289): MountEmulatedStorage()
E/Zygote  ( 5289): v2
I/libpersona( 5289): KNOX_SDCARD checking this for 10047
I/libpersona( 5289): KNOX_SDCARD not a persona
I/SELinux ( 5289): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5289): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1013): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5289 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
E/SELinux ( 5289): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
D/Mms/FreeMessageReceiverService( 5097): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 5097): onHandleIntent: ACTION_PACKAGE_ADDED
I/ActivityManager( 1013): Killing 4424:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
D/Mms/MessagingNotification( 5097): checkBadgeCount unreadCount=0 badgeCount=0
D/TimaKeyStoreProvider( 5289): TimaSignature is unavailable
D/ActivityThread( 5289): Added TimaKeyStore provider
D/TP/SmsProvider( 1437): query,matched:26, calling pid = 5097
D/TP/SmsProvider( 1437): match 26:Elapsed time : 1.557 ms
D/TP/MmsSmsProvider( 1437): query,matched:6, calling pid = 5097
D/TP/MmsSmsProvider( 1437): match 6:Elapsed time : 1.582 ms
W/ResourcesManager( 5289): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5289): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5289): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/ActivityManager( 1013): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5305): MountEmulatedStorage()
E/Zygote  ( 5305): v2
I/libpersona( 5305): KNOX_SDCARD checking this for 10025
I/SELinux ( 5305): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 5305): KNOX_SDCARD not a persona
I/ActivityManager( 1013): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5305 uid=10025 gids={50025, 9997} abi=armeabi-v7a
I/SELinux ( 5305): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5305): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1013): failed to open /acct/uid_10150/pid_4424/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 5305): TimaSignature is unavailable
D/ActivityThread( 5305): Added TimaKeyStore provider
I/ActivityManager( 1013): Killing 3990:com.android.providers.calendar/u0a42 (adj 15): empty #31
W/ResourcesManager( 5305): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/MyFiles ( 5289): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
I/OMACP   ( 5305): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
E/installd(  283): system dir 0 : /system/app/
E/installd(  283): system dir 1 : /system/priv-app/
E/installd(  283): system dir 2 : /vendor/app/
E/installd(  283): system dir 3 : /oem/app/
I/TactileAssist( 1013): enable value -1
I/TactileAssist( 1013): internal enable value -1
I/TactileAssist( 1013): intensity value -1
I/TactileAssist( 1013): saveAppList value true
D/Mms/Omacp( 5097): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
I/TactileAssist( 1013): List of disabled apps :
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
I/OMACP   ( 5305): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
I/OMACP   ( 5305): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
I/OMACP   ( 5305): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
I/OMACP   ( 5305): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
I/OMACP   ( 5305): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
I/OMACP   ( 5305): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
E/Zygote  ( 5322): MountEmulatedStorage()
E/Zygote  ( 5322): v2
I/libpersona( 5322): KNOX_SDCARD checking this for 10053
I/libpersona( 5322): KNOX_SDCARD not a persona
I/SELinux ( 5322): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1013): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=5322 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
I/SELinux ( 5322): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5322): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/PackageManager( 1013): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/libprocessgroup( 1013): failed to open /acct/uid_10042/pid_3990/cgroup.procs: No such file or directory
D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 5322): TimaSignature is unavailable
D/ActivityThread( 5322): Added TimaKeyStore provider
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ResourcesManager( 5322): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/Compatibility( 5322): onReceive() it will make start service
D/ActivityManager( 1013): startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
D/ChimeraCfgMgr( 2000): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2000): Module APK com.google.android.play.games already loaded
I/OMACP   ( 5305): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
D/ActivityManager( 1013): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
D/Compatibility( 5322): onHandleIntent()
I/OMACP   ( 5305): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
I/OMACP   ( 5305): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
I/OMACP   ( 5305): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
I/UpdateIcingCorporaServi( 4785): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/OMACP   ( 5305): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
I/OMACP   ( 5305): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
D/Compatibility( 5322): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10175, android.intent.extra.user_handle=0}]
I/OMACP   ( 5305): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
D/Compatibility( 5322): found: 2
D/Compatibility( 5322): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5322): skipping ResolveInfo{138c430e com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5322): considering ResolveInfo{39fb012f com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5322): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5322): enabling receiver ResolveInfo{396033c com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/ChimeraCfgMgr( 2000): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/Compatibility( 5322): enabling receiver ResolveInfo{3843d8c5 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 5322): enabling receiver ResolveInfo{e4d821a com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 5322): enabling receiver ResolveInfo{2ec0814b com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 5322): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
I/SL_DEBUG( 5247): isLoggable:: isProductShip = 1
I/SL_DEBUG( 5247): isLoggable:: SL_DEBUG_EXIST = false
I/UpdateIcingCorporaServi( 4785): UpdateCorporaTask done [took 81 ms] updated apps [took 81 ms] 
D/AsyncTaskServiceImpl( 2000): Submit a task: k
D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1013): Killing 4464:com.google.android.gm/u0a101 (adj 15): empty #31
D/ChimeraCfgMgr( 2000): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ChimeraCfgMgr( 2000): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/k       ( 2000): Processing package: com.test.thalitest
D/ActivityManager( 1013): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.internal.SharedPreferencesService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5247): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
D/GassUtils( 2000): Found app info for package com.test.thalitest:18. Hash: 82ccbc74df315987b7be206c22ec4eaa3ab0d49235c4895536307c8f71b675fe
D/k       ( 2000): Found info for package com.test.thalitest in db.
D/ActivityManager( 1013): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
W/libprocessgroup( 1013): failed to open /acct/uid_10101/pid_4464/cgroup.procs: No such file or directory
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5247): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
D/ActivityManager( 1013): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
W/BaseAppContext( 2000): Using Auth Proxy for data requests.
W/BaseAppContext( 2000): Using Auth Proxy for data requests.
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5362): MountEmulatedStorage()
E/Zygote  ( 5362): v2
I/libpersona( 5362): KNOX_SDCARD checking this for 10041
I/libpersona( 5362): KNOX_SDCARD not a persona
I/SELinux ( 5362): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1013): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=5362 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 5362): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5362): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 5362): TimaSignature is unavailable
D/ActivityThread( 5362): Added TimaKeyStore provider
W/BaseAppContext( 2000): Using Auth Proxy for data requests.
,W/BaseAppContext( 2000): Using Auth Proxy for data requests.
W/BaseAppContext( 2000): Using Auth Proxy for data requests.
W/BaseAppContext( 2000): Using Auth Proxy for data requests.
D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/BaseAppContext( 2000): Using Auth Proxy for data requests.
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
I/SA      ( 5362): [SSP] onCreated
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1013): Killing 4340:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
I/SA      ( 5362): [TPM] There is no property file
I/SA      ( 5362): [SCU] isHaveSA() - false
I/SA      ( 5362): [TPM] getModelProperty : null
I/SA      ( 5362): [TPM] getCSCProperty : null
I/SA      ( 5362): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 5362): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 5362): [DM] TFT FEATURE: false
I/SA      ( 5362): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 5362): [DM] init START
I/SA      ( 5362): [DM] This device is not a Vodafone
W/ResourceType( 5362): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 5362): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 5362): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 5362): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 5362): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 5362): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 5362): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 5362): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 5362): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 5362): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 5362): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 5362): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 5362): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 5362): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 5362): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 5362): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 5362): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
W/ResourceType( 5362): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 5362): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 5362): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 5362): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 5362): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 5362): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 5362): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 5362): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
I/SA      ( 5362): [SCU] isHaveSA() - false
I/SA      ( 5362): support phone number id : false
I/SA      ( 5362): [DM] Supports Ref Jpn : true
I/SA      ( 5362): [DM] init END
I/SA      ( 5362): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
I/SA      ( 5362): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10175 extra.user_handle.:0 ]
W/libprocessgroup( 1013): failed to open /acct/uid_10040/pid_4340/cgroup.procs: No such file or directory
W/GAV2    ( 5164): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/art     ( 1013): Explicit concurrent mark sweep GC freed 224786(14MB) AllocSpace objects, 7(4MB) LOS objects, 33% free, 27MB/41MB, paused 2.629ms total 183.752ms
I/ActivityManager( 1013): Killing 4247:com.google.android.music:main/u0a111 (adj 15): empty #31
I/PeopleDatabaseHelper( 2000): cleanUpNonGplusAccounts done.
D/AndroidRuntime( 5379): 
D/AndroidRuntime( 5379): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5379): CheckJNI is OFF
D/AndroidRuntime( 5379): readGMSProperty: start
D/AndroidRuntime( 5379): readGMSProperty: already setted!!
D/AndroidRuntime( 5379): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5379): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5379): readGMSProperty: end
D/AndroidRuntime( 5379): addProductProperty: start
W/libprocessgroup( 1013): failed to open /acct/uid_10111/pid_4247/cgroup.procs: No such file or directory
D/ActivityManager( 1013): startService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.apps.docs
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.ContentSyncService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
W/GAV2    ( 5164): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
E/Zygote  ( 5402): MountEmulatedStorage()
E/Zygote  ( 5402): v2
I/libpersona( 5402): KNOX_SDCARD checking this for 10100
I/libpersona( 5402): KNOX_SDCARD not a persona
I/SELinux ( 5402): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1013): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=5402 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/SELinux ( 5402): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5402): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/AffinityControl( 5379): AffinityControl: registerfunction enter
D/TimaKeyStoreProvider( 5402): TimaSignature is unavailable
D/ActivityThread( 5402): Added TimaKeyStore provider
D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1856): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 5379): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1013): inState():  stateMachine is null !!
I/PersonaManagerService( 1013): PersonaId don't exist
I/ActivityManager( 1013): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/PackageIntentReceiver( 5402): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 5402): Not GearManger package! 
W/ActivityManager( 1013): mDVFSHelper.acquire()
W/AccountFeatureHelper( 5164): Write apps_features disabled false
I/SurfaceFlinger(  257): id=9 createSurf (16x16),-1 flag=20004, EimLayer(Di
I/SurfaceFlinger(  257): id=10 createSurf (16x16),-1 flag=20004, EimLayer(An
D/FocusedStackFrame( 1013): Set to : 0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1013): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1013): *FMB* installDecor flags : 25362712
E/Zygote  ( 5426): MountEmulatedStorage()
E/Zygote  ( 5426): v2
I/libpersona( 5426): KNOX_SDCARD checking this for 10175
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
I/libpersona( 5426): KNOX_SDCARD not a persona
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 1013): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5426 uid=10175 gids={50175, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/InputDispatcher( 1013): Focused application set to: xxxx
I/SELinux ( 5426): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/InputDispatcher( 1013): Focus left window: 1463
D/AndroidRuntime( 5379): Shutting down VM
I/SELinux ( 5426): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/SELinux ( 5426): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PhoneWindow( 1013): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1013): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  257): id=11 createSurf (720x1280),1 flag=404, uhalitest
D/PointerIcon( 1013): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1013): setMouseCustomIcon IconType is same.101
E/Zygote  ( 5438): MountEmulatedStorage()
E/Zygote  ( 5438): v2
I/libpersona( 5438): KNOX_SDCARD checking this for 1000
I/libpersona( 5438): KNOX_SDCARD not a persona
I/SELinux ( 5438): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1013): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=5438 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 5438): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5438): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Killing 4634:com.google.android.talk/u0a104 (adj 15): empty #31
D/TimaKeyStoreProvider( 5426): TimaSignature is unavailable
D/ActivityThread( 5426): Added TimaKeyStore provider
V/WindowManager( 1013): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/ActivityManager( 1013): Display changed displayId=0
D/StatusBarManagerService( 1013): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/TimaKeyStoreProvider( 5438): TimaSignature is unavailable
D/ActivityThread( 5438): Added TimaKeyStore provider
D/PersonaManager( 1013): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1013):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  257): id=6 Removed Mauncher (5/9)
I/SurfaceFlinger(  257): id=6 Removed Mauncher (-2/9)
V/ActivityThread( 1463): updateVisibility : ActivityRecord{1ef99dcd token=android.os.BinderProxy@35c97a0a {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1463): onTrimMemory. Level: 20
W/libprocessgroup( 1013): failed to open /acct/uid_10104/pid_4634/cgroup.procs: No such file or directory
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5456): MountEmulatedStorage()
I/ActivityManager( 1013): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=5456 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 5456): v2
I/libpersona( 5456): KNOX_SDCARD checking this for 1000
I/libpersona( 5456): KNOX_SDCARD not a persona
I/SELinux ( 5456): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1013): Killing 4849:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
I/SELinux ( 5456): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5456): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5456): TimaSignature is unavailable
D/ActivityThread( 5456): Added TimaKeyStore provider
W/art     ( 5379): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
W/GAV2    ( 5164): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager( 1013): Killing 4880:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
,I/WebViewFactory( 5426): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,I/LibraryLoader( 5426): Time to load native libraries: 2 ms (timestamps 5322-5324)
,I/LibraryLoader( 5426): Expected native library version number "",actual native library version number ""
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/AcmsPackageEventListener( 5456): Received: android.intent.action.PACKAGE_ADDED
,W/libprocessgroup( 1013): failed to open /acct/uid_10069/pid_4849/cgroup.procs: No such file or directory
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_4880/cgroup.procs: No such file or directory
,W/ContextImpl( 5456): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
D/ActivityManager( 1013): startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
D/AcmsService( 5456): Enter Oncreate
D/AcmsServiceMonitor( 5456): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 5456): creating AcmsCore
D/AcmsCore( 5456): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 5456): AcmsCore
D/AcmsCore( 5456): init
D/AcmsCore( 5456): Looper handler is not null
D/AcmsCore( 5456): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 5456): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5456): Incrementing - Counter value: 1
D/AcmsCore( 5456): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsService( 5456): onStartCommand
D/AcmsService( 5456): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 5456): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 5456): Incrementing - Counter value: 2
D/AcmsService( 5456): Incremented Counter Value : onStartCommand
D/AcmsCertificateMngr( 5456): AcmsCertificateMngr
D/ActivityManager( 1013): getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
D/ActivityThread( 5456): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
V/WebViewChromiumFactoryProvider( 5426): Binding Chromium to main looper Looper (main, tid 1) {396033c}
I/LibraryLoader( 5426): Expected native library version number "",actual native library version number ""
I/chromium( 5426): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,D/AcmsRevocationMngr( 5456): AcmsRevocationMngr
,D/AcmsService( 5456): Inside handle Intent
D/AcmsService( 5456): App added - package name: com.test.thalitest
D/AcmsCore( 5456): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 5456): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5456): Incrementing - Counter value: 3
D/AcmsCore( 5456): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 5456): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 5456): Decrementing - Counter value: 2
,I/BrowserStartupController( 5426): Initializing chromium process, singleProcess=true
,W/art     ( 5426): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5426): ApplicationContext is null in ApplicationStatus
,I/splitIntent( 1013): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,W/chromium( 5426): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,W/chromium( 5426): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 5426): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,I/chromium( 5426): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,I/Adreno-EGL( 5426): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5426): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5426): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5426): Local Branch: 
I/Adreno-EGL( 5426): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5426): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5426):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/ChimeraCfgMgr( 2000): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2000): Module APK com.google.android.play.games already loaded
,D/BluetoothAdapter( 5426): 906902593: getState() :  mService = null. Returning STATE_OFF
,I/Icing   ( 2000): Indexing 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28 from com.google.android.gms
,W/chromium( 5426): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,W/art     ( 5426): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5426): onDetachedFromWindow called when already detached. Ignoring
,W/ActivityManager( 1013): Activity pause timeout for ActivityRecord{152535da u0 com.test.thalitest/.MainActivity t2}
,I/Icing   ( 2000): Indexing done 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28
,D/PhoneWindow( 5426): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 5426): *FMB* installDecor flags : 8456448
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SystemWebViewEngine( 5426): CordovaWebView is running on device made by: samsung
,W/art     ( 5426): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 5426): Attempt to remove local handle scope entry from IRT, ignoring
,I/Mms/MmsApp( 5097):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 5097): [start]    fillCache consume time = 1964.533332
D/Mms/ComposeMessageFragment( 5097): fillCache, easy = false
,D/OpenGLRenderer( 5426): Render dirty regions requested: true
,D/ActivityManager( 1013): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1013): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1013): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1013): handleActiveUserChange for user 0
,D/PersonaManagerService( 1013): getPersonasForUser(): returning null!
,V/ActivityThread( 5426): updateVisibility : ActivityRecord{5bdb7b1 token=android.os.BinderProxy@3098533b {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PhoneWindow( 5426): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 5426): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  257): id=12 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1013): Focus entered window: 5426
,D/PointerIcon( 1013): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1013): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 5426): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 5426): Initialized EGL, version 1.4
D/OpenGLRenderer( 5426): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 5426): Enabling debug mode 0
,D/AbsListView( 5097): Get MotionRecognitionManager
,D/MotionRecognitionService( 1013):  ssp status : false
,D/Mms/ComposeMessageFragment( 5097): [end]    fillCache consume time = 95.64224
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:2, health:2, present:true, voltage: 4323, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for charging
,D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1013): Plugged
,I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1400): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1400): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/InputMethodManagerService( 1013): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/SamsungIME( 1798): getCurrentCandidateView
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ActivityManager( 1013): Displayed Component not be shown by security: +727ms (total +836ms)
,W/ActivityManager( 1013): mDVFSHelper.release()
D/PanelView( 1175): There is/are notification(s) 
,I/Timeline( 1013): Timeline: Activity_windows_visible id: ActivityRecord{152535da u0 com.test.thalitest/.MainActivity t2} time:75872
,W/IInputConnectionWrapper( 5426): showStatusIcon on inactive InputConnection
,I/Timeline( 5426): Timeline: Activity_idle id: android.os.BinderProxy@3098533b time:75878
,I/SurfaceFlinger(  257): id=11 Removed uhalitest (7/9)
,I/SurfaceFlinger(  257): id=11 Removed uhalitest (-2/9)
,D/Mms/BubbleViewCache( 5097): fillCache bubble = 1
,W/BindingManager( 5426): Cannot call determinedVisibility() - never saw a connection for the pid: 5426
,D/SamsungIME( 1798): Dismiss ExpandCandiate
,I/ActivityManager( 1013): Killing 4967:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
,D/JsMessageQueue( 5426): Set native->JS mode to OnlineEventsBridgeMode
,I/SamsungIME( 1798): getDebugLevel  : 0x4f4c
,W/libprocessgroup( 1013): failed to open /acct/uid_10142/pid_4967/cgroup.procs: No such file or directory
,I/SamsungIME( 1798): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1798): KeybaordView init() : load resources
,I/SamsungIME( 1798): getCurrentKeyboard
I/SamsungIME( 1798): getTextKeyboard
,D/jxcore_app_log( 5426): JniHelper::setJavaVM(0xb8739450), pthread_self() = -1194809576
D/JX-Cordova( 5426): jxcore cordova android initializing
,D/SamsungIME( 1798): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/AcmsKeyStoreHelper( 5456):  getKeyStoreForApplication Enter
,I/AcmsKeyStoreHelper( 5456): Key Store exist
I/AcmsKeyStoreHelper( 5456): Hence loading the keystore file
,D/AcmsKeyStoreHelper( 5456):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 5456): getKeyStoreForApplication success 
D/AcmsCore( 5456): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 5456): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5456): Decrementing - Counter value: 1
D/AcmsCore( 5456): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 5456): This is NOT a valid MirrorLink app
D/AcmsCore( 5456): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 5456): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5456): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 5456): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 5456): getSvcCounter - Counter value: 0
D/AcmsService( 5456): Enter onDestroy
I/AcmsService( 5456): cleanUp(): inside service clean up
D/AcmsCore( 5456): AcmsCore: inside DeInit
D/AcmsCore( 5456): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 5456): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 5456): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 5456): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 5456): AppEntryInterface: Inside CleanUp
,D/AcmsServiceMonitor( 5456): getSvcCounter - Counter value: 0
,D/AcmsService( 5456): killing acms process
I/Process ( 5456): Sending signal. PID: 5456 SIG: 9
,E/SMD     (  287): DCD OFF
,I/ActivityManager( 1013): Process ACMS.Process (pid 5456)(adj 0) has died(55,1177)
,D/SamsungIME( 1798): [SwiftkeyWrapper] currentLangauge : 1701729619
,W/jxcore-log( 5426): Initializing JXcore engine
W/jxcore-log( 5426): JXcore engine is ready
,W/jxcore-log( 5426): Starting JXcore engine
,E/audit   ( 1911): type=1400 msg=audit(1452596467.404:203): avc:  denied  { ioctl } for  pid=5426 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1911):  SEPF_SM-A500FU_5.0.2-1_0038
E/audit   ( 1911): type=1300 msg=audit(1452596467.404:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=bec92d58 items=0 ppid=305 ppcomm=main pid=5426 auid=4294967295 uid=10175 gid=10175 euid=10175 suid=10175 fsuid=10175 egid=10175 sgid=10175 fsgid=10175 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1911): type=1320 msg=audit(1452596467.404:203): 
,W/jxcore-log( 5426): Platform android
W/jxcore-log( 5426): 
W/jxcore-log( 5426): Process ARCH arm
W/jxcore-log( 5426): 
,V/AlarmManager( 1013): waitForAlarm result :8
,E/Watchdog( 1013): !@Sync 2
,I/jxcore-log( 5426): JXcore Cordova bridge is ready!
I/jxcore-log( 5426): 
,W/jxcore-log( 5426): JXcore engine is started
,I/chromium( 5426): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,V/AlarmManager( 1013): waitForAlarm result :8
,I/jxcore-log( 5426): Toggling radios to true
I/jxcore-log( 5426): 
,D/BluetoothAdapter( 5426): enable()
,W/ActivityManager( 1013): Permission Denial: getCurrentUser() from pid=5426, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
,W/BluetoothManagerService( 1013): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService( 1013): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5426, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService( 1013): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24778)
W/BluetoothManagerService( 1013): 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
W/BluetoothManagerService( 1013): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
W/BluetoothManagerService( 1013): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/BluetoothManagerService( 1013): 	at android.os.Binder.execTransact(Binder.java:461)
,E/DevicePolicyManagerService( 1013): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 1013): getAllowBluetoothMode - value retunrs : 2
,D/SettingsProvider( 1013): name = bluetooth_on
,E/DevicePolicyManagerService( 1013): getAllowBluetoothMode - value retunrs : 2
,E/DevicePolicyManagerService( 1013): getAllowBluetoothMode - value retunrs : 2
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/SecContentProvider( 1013): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1013): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1013): mCursor = null
,E/Zygote  ( 5518): MountEmulatedStorage()
E/Zygote  ( 5518): v2
I/libpersona( 5518): KNOX_SDCARD checking this for 1002
,I/libpersona( 5518): KNOX_SDCARD not a persona
,D/WifiService( 1013): setWifiEnabled: true pid=5426, uid=10175
W/ActivityManager( 1013): Permission Denial: getCurrentUser() from pid=5426, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1013): Failed getting userId using ActivityManagerNative
W/WifiService( 1013): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5426, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1013): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24778)
W/WifiService( 1013): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1013): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1013): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1013): 	at android.os.Binder.execTransact(Binder.java:461)
,D/SettingsProvider( 1013): name = wifi_on
I/ActivityManager( 1013): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=5518 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,I/SELinux ( 5518): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5518): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,I/WifiService( 1013): disconnect: pid=5426, uid=10175
E/SELinux ( 5518): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/jxcore-log( 5426): Radios toggled
I/jxcore-log( 5426): 
,I/jxcore-log( 5426): My device name is: samsung-SM-A500FU
I/jxcore-log( 5426): 
E/WifiHW  ( 1013): ##################### set firmware type 0 #####################
,D/TimaKeyStoreProvider( 5518): TimaSignature is unavailable
,D/ActivityThread( 5518): Added TimaKeyStore provider
,W/ResourcesManager( 5518): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 5518): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/BluetoothA2dpSinkServiceJni( 5518): register_com_android_bluetooth_a2dp_sink
,D/BtSettings.ProfileConfig( 5518): Adding GattService
,D/BtSettings.ProfileConfig( 5518): Adding HeadsetService
D/BtSettings.ProfileConfig( 5518): Adding A2dpService
D/BtSettings.ProfileConfig( 5518): Adding HidService
D/BtSettings.ProfileConfig( 5518): Adding HealthService
D/BtSettings.ProfileConfig( 5518): Adding PanService
D/BtSettings.ProfileConfig( 5518): Adding BluetoothMapService
D/BtSettings.ProfileConfig( 5518): Adding SapService
D/BtSettings.ProfileConfig( 5518): Adding HeadsetClientService
D/BtSettings.ProfileConfig( 5518): Adding A2dpSinkService
D/BtSettings.ProfileConfig( 5518): Adding SapClientService
D/BtSettings.ProfileConfig( 5518): Adding HidDevService
I/BtSettings.ProfileConfig( 5518): *********Initializing Bluetooth Profile Settings*******
,D/SettingsProvider( 1013): name = bt_svcst_com.android.bluetooth.gatt.GattService
,D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 1002
,D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
,W/BackupManagerService( 1013): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SettingsProvider( 1013): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 1002
,D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
,W/BackupManagerService( 1013): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1013): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 1002
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
,W/BackupManagerService( 1013): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1013): name = bt_svcst_com.android.bluetooth.hid.HidService
,D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
,D/SettingsProvider( 1013): selectionArgs: 1002
,D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
,W/BackupManagerService( 1013): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1013): name = bt_svcst_com.android.bluetooth.hdp.HealthService,
D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false,
D/SettingsProvider( 1013): selectionArgs: 1002
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1013): ret = -1
I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,W/BackupManagerService( 1013): dataChanged but no participant pkg='com.android.providers.settings' uid=1002,
,D/SettingsProvider( 1013): name = bt_svcst_com.android.bluetooth.pan.PanService
,D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 1002
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
,W/BackupManagerService( 1013): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1013): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 1002
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
,W/BackupManagerService( 1013): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,D/SettingsProvider( 1013): name = bt_svcst_com.broadcom.bt.service.sap.SapService
,D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 1002
,D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
,W/BackupManagerService( 1013): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,D/SettingsProvider( 1013): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1013): selectionArgs: false
,D/SettingsProvider( 1013): selectionArgs: 1002
I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1013): ret = -1
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,W/BackupManagerService( 1013): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1013): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 1002
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
,W/BackupManagerService( 1013): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1013): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 1002
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,W/BackupManagerService( 1013): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1013): name = bt_svcst_com.android.bluetooth.hid.HidDevService
D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 1002
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
,W/BackupManagerService( 1013): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,D/BluetoothAdapterState( 5518): make
,I/bluedroid( 5518): init
,I/BluetoothAdapterState( 5518): Entering OffState
,I/bte_conf( 5518): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 5518): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,E/bt_osi_config( 5518): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 5518): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,E/bt-btif ( 5518): btif_fetch_local_ble_random_bdaddr
,I/bluedroid( 5518): get_profile_interface socket
I/bluedroid( 5518): get_profile_interface map_client
,D/BluetoothAdapterService( 5518): checkAddrForIOP: Loading from conf
,I/GKI_LINUX( 5518): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties( 5518): Address is:7C:F9:0E:37:96:AB
,E/BluetoothServiceJni( 5518): populateRssiValuesNative
I/bluedroid( 5518): getModelRssiValues
,E/BluetoothServiceJni( 5518): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 5518): modelRssiValuesCallback, low, mid, high = -70,-60,127
,D/SettingsProvider( 1013): name = bluetooth_name
,D/BluetoothAdapterProperties( 5518): Name is: A5-1
,D/BluetoothA2dp( 5518): doBind(): CallingUid(myUserHandle) = 0
,D/ActivityManager( 1013): bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
I/bluedroid( 5518): config_hci_snoop_log
D/BluetoothManagerService( 1013): Broadcasting onBluetoothServiceUp() to 9 receivers.
D/BluetoothManagerService( 1013): Ble is always on enable gatt
I/BluetoothManagerService( 1013): enableGattForLeMode, doBind called
D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,I/BtGatt.JNI( 5518): classInitNative(L900): classInitNative: Success!
,E/DevicePolicyManagerService( 1013): getAllowBluetoothMode - value retunrs : 2
,E/DevicePolicyManagerService( 1013): getAllowBluetoothMode - value retunrs : 2
,D/SecContentProvider( 1013): uri = 3 selection = isBluetoothEnabled
,D/BluetoothManagerService( 1013): Broadcasting onBluetoothServiceUp() to 0 receivers.
,D/BluetoothAdapterState( 5518): CURRENT_STATE=OFF, MSG = USER_TURN_ON
,D/BluetoothAdapterProperties( 5518): Setting state to 11
,I/BluetoothAdapterState( 5518): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 5518): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 5518): updateAdapterState state is 11
,D/BluetoothAdapterService( 5518): Autoconnection is available 
D/BluetoothAdapterService( 5518): updateAdapterState prevState = 10newState = 11
,W/InputMethodManagerService( 1013): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService( 1013): [BT Setting State] State =11
,D/BluetoothSecureManager( 5518): getInstant: null
,D/BluetoothSecureManager( 5518): calling getMethod for getService
D/BluetoothSecureManager( 5518): calling getService
,D/BluetoothSecureManager( 5518): getService return binder: android.os.BinderProxy@3ef2a340
,D/BluetoothSecureManagerService( 1013): isSecureModeEnabled
D/BluetoothSecureManagerService( 1013): getSecureModeSetting, name: secure_mode_enable
,D/BtConfig.SecureMode( 5518): isSecureModeOn:false
D/BtSettings.ProfileConfig( 5518): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
D/BluetoothTile( 1175):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 1175): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1175):  getBluetoothState : 11
,W/BluetoothAdapterService( 5518): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 5518): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,I/SamsungIME( 1798): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
W/BluetoothAdapterService( 5518): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5518): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 5518): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 5518): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 5518): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5518): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 5518): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 5518): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,D/StatusBarManagerService( 1013): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/StatusBarManagerService( 1013): setIconVisibility slot=bluetooth visible=false
D/PhoneStatusBar( 1175): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/PhoneStatusBar( 1175): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,W/BluetoothAdapterService( 5518): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 5518): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,D/BluetoothTile( 1175):  handleUpdatestate:false name:null
D/STATUSBAR-QSTileView( 1175): onStateChanged: Bluetooth
,W/BluetoothAdapterService( 5518): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 5518): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 5518): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 5518): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService( 5518): processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 5518): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 5518): processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 5518): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,W/BluetoothAdapterService( 5518): processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
,D/BtSettings.ProfileConfig( 5518): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,W/BluetoothAdapterService( 5518): processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,D/BluetoothNotiBroadcastReceiver( 1281): onReceive
,D/BluetoothBondStateMachine( 5518): make
,V/BluetoothStatusReceiver( 1175): Received android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothStatusReceiver( 1175): AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,I/BluetoothBondStateMachine( 5518): StableState(): Entering Off State
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
W/BluetoothAdapterService( 5518): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 5518): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 5518): Not skipping com.android.bluetooth.gatt.GattService
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5555): MountEmulatedStorage()
,I/libpersona( 5555): KNOX_SDCARD checking this for 10003,
E/Zygote  ( 5555): v2
I/libpersona( 5555): KNOX_SDCARD not a persona
I/SELinux ( 5555): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/Tethering( 1013): interfaceAdded wlan0
E/Tethering( 1013): No numeric data
I/SELinux ( 5555): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5555): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Tethering( 1013): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1013): interfaceLinkStateChanged wlan0, false
D/Tethering( 1013): interfaceStatusChanged wlan0, false
,I/ActivityManager( 1013): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=5555 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,D/Tethering( 1013): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1013): clearTetheredNotification()
D/Tethering( 1013): InitialState.processMessage what=4
,E/Tethering( 1013): No numeric data
D/Tethering( 1013): interfaceAdded p2p0
D/Tethering( 1013): p2p0 is not a tetherable iface, ignoring
D/NtpTrustedTime( 1013): forceRefresh() from cache miss
D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
,D/HotspotTile( 1175): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1175): updateTetherState():false, false
,I/WifiHW  (  277): wifi_change_fw_path(): fwpath = sta
I/Nat464Xlat( 1013): interfaceLinkStateChanged p2p0, false
D/Tethering( 1013): interfaceLinkStateChanged p2p0, false
D/Tethering( 1013): interfaceStatusChanged p2p0, false
D/SoftapController(  277): Softap fwReload - Ok
D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
,D/Tethering( 1013): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1013): clearTetheredNotification()
,D/CommandListener(  277): Setting iface cfg
D/HotspotTile( 1175): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/CommandListener(  277): Trying to bring down wlan0
D/HotspotTile( 1175): updateTetherState():false, false
,D/CommandListener(  277): Clearing all IP addresses on wlan0
D/ActivityManager( 1013): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
W/ActivityManager( 1013): userId = 0, bbcId = -10000
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 5518): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5518): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 5518): Not skipping com.android.bluetooth.hfp.HeadsetService
D/ActivityManager( 1013): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/NtpTrustedTime( 1013): forceRefresh Fail.
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
D/BtGatt.DebugUtils( 5518): handleDebugAction() action=null
D/NetworkStatsFactory( 1013): UpdateStatsForKnox updated
V/NetworkStats( 1013): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1013): UpdateStatsForKnox main else ---
V/NetworkStats( 1013): performPollLocked() took 4ms
D/BtGatt.GattService( 5518): Received start request. Starting profile...
D/BtGatt.GattService( 5518): start()
D/BtGatt.GattService( 5518): start()
I/bluedroid( 5518): get_profile_interface gatt
D/BluetoothAdapterService( 5518): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ec0814b
D/BtGatt.AdvertiseManager( 5518): advertise manager created
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
I/art     (  305): Explicit concurrent mark sweep GC freed 8731(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 651us total 29.276ms
W/BluetoothAdapterService( 5518): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 5518): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
D/ActivityManager( 1013): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
W/BluetoothAdapterService( 5518): Not skipping com.android.bluetooth.a2dp.A2dpService
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
V/NetworkStats( 1013): performPollLocked(flags=0x1)
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
D/NtpTrustedTime( 1013): forceRefresh() from cache miss
D/NtpTrustedTime( 1013): forceRefresh() from cache miss
D/NtpTrustedTime( 1013): forceRefresh Fail.
D/NtpTrustedTime( 1013): forceRefresh Fail.
D/NetworkStatsFactory( 1013): UpdateStatsForKnox updated
D/ActivityManager( 1013): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/NetworkStatsFactory( 1013): UpdateStatsForKnox main else ---
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
E/WifiHW  ( 1013): supplicant_name : p2p_supplicant
W/BluetoothAdapterService( 5518): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5518): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 5518): Not skipping com.android.bluetooth.hid.HidService
,V/NetworkStats( 1013): performPollLocked() took 11ms
,D/BtGatt.GattService( 5518): mStartError = false
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/BluetoothAdapterService( 5518): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ec0814b
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.289ms total 19.631ms
,D/WifiMonitor( 1013): startMonitoring(wlan0) with mConnected = false
,W/BluetoothAdapterService( 5518): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService,
D/BtSettings.ProfileConfig( 5518): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 5518): Not skipping com.android.bluetooth.hdp.HealthService
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/STATUSBAR-WifiQuickSettingButton( 1175): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-WifiQuickSettingButton( 1175): Wifi onReceive(2)
D/STATUSBAR-QSTileView( 1175): onStateChanged: Wi-Fi
D/TimaKeyStoreProvider( 5555): TimaSignature is unavailable
D/ActivityThread( 5555): Added TimaKeyStore provider
D/HotspotTile( 1175): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/HotspotTile( 1175): onReceive : 2, 0
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 625us total 17.896ms
,D/ActivityManager( 1013): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,D/WifiCredService( 1281): Action received :android.net.wifi.WIFI_STATE_CHANGED
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5518): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 5518): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 5518): Not skipping com.android.bluetooth.pan.PanService
D/ActivityManager( 1013): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,D/HeadsetService( 5518): Received start request. Starting profile...
D/HeadsetService( 5518): start()
,I/BluetoothHeadsetServiceJni( 5518): classInitNative: succeeds
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/HeadsetStateMachine( 5518): make
,W/BluetoothAdapterService( 5518): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 5518): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 5518): Not skipping com.android.bluetooth.map.BluetoothMapService
E/HeadsetStateMachine( 5518): # of Max HF connection is 2
,D/NtpTrustedTime( 1013): forceRefresh() from cache miss
D/NtpTrustedTime( 1013): forceRefresh Fail.
D/ActivityManager( 1013): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
I/wpa_supplicant( 5572): [wpa_supplicant_init]: use SECRIL
I/wpa_supplicant( 5572): Successfully initialized wpa_supplicant
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
I/SecureStorage( 5572): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5518): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 5518): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 5518): Not skipping com.broadcom.bt.service.sap.SapService
,D/ActivityManager( 1013): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
D/ActivityManager( 1013): bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
W/BluetoothAdapterService( 5518): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 5518): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService( 5518): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 5518): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 5518): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,W/BluetoothAdapterService( 5518): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,D/ActivityManager( 1013): bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
I/bluedroid( 5518): get_profile_interface handsfree
W/BluetoothAdapterService( 5518): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 5518): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,W/BluetoothAdapterService( 5518): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 5518): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 5518): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService( 5518): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
I/BluetoothAdapterState( 5518): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/SecureStorage( 5572): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage(  335): [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 5572
,I/SecureStorage(  335): [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
I/SecureStorage( 5572): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 5572): ssSupport state is = 1
I/wpa_supplicant( 5572): >>>>> GET KEY, IV <<<<<
I/SecureStorage( 5572): [INFO]: SPID(0x00000000)Processing data
,I/SecureStorage(  335): [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 5572
,I/SecureStorage(  335): [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,I/DualScoManager( 5518): Instantiating Dual Sco Manager
I/DualScoManager( 5518): Set HeadsetServiceHelper
,D/BluetoothAtMessage( 5518): createCMTIContentObservers
D/SettingsProvider( 1013): name = bluetooth_hfp_allowed_bvra
,D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 1002
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
,W/BackupManagerService( 1013): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/HeadsetStateMachine( 5518): Enter Disconnected: -2
,D/HeadsetService( 5518): mStartError = false
D/BluetoothAdapterService( 5518): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ec0814b
,D/BluetoothA2dp( 1013): Proxy object connected
,D/A2dpService( 5518): Received start request. Starting profile...
D/A2dpService( 5518): start()
D/BluetoothA2dp( 2704): Proxy object connected
D/HeadsetStateMachine( 5518): Clear mHeadsetBrsf
D/HeadsetStateMachine( 5518): map size, before remove : 0
D/HeadsetStateMachine( 5518): map size, after remove: 0
I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
I/BluetoothAvrcpServiceJni( 5518): classInitNative: succeeds
I/bluedroid( 5518): get_profile_interface avrcp
,D/UserAnalysis.PlaceProvider( 5555): PlaceProvider onCreate()
,E/RemoteController( 5518): Cannot set synchronization mode on an unregistered RemoteController
,I/Avrcp   ( 5518):  Updating now playing list upon AVRCP Start
,D/BluetoothMediaBrowser( 5518):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include,
I/BluetoothA2dpServiceJni( 5518): classInitNative: succeeds
,D/A2dpStateMachine( 5518): make
,I/bluedroid( 5518): get_profile_interface a2dp,
I/GKI_LINUX( 5518): gki_task_entry task_id=2 [A2DP-MEDIA] starting
E/bt-btif ( 5518): warning : media task started media_task_refcnt 1 
,D/A2dpService( 5518): mStartError = false
D/BluetoothAdapterService( 5518): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ec0814b
D/A2dpStateMachine( 5518): Enter Disconnected: -2
E/BluetoothAdapterService(784367947)( 5518): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
I/BluetoothHidServiceJni( 5518): classInitNative: succeeds
,D/UserAnalysis.SecureDbManager( 5555): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 5555): SecurePlaceDbHelper() 
D/UserAnalysis( 5555): Create SecureDbHelper
,D/IntelligenceServiceApplication( 5555): onCreate()
,D/BluetoothMediaBrowser( 5518): no now playing list
D/BluetoothMediaBrowser( 5518):  getNowPlayingId now playing id : -1
,D/HidService( 5518): Received start request. Starting profile...
D/HidService( 5518): start()
I/bluedroid( 5518): get_profile_interface hidhost
D/HidService( 5518): setHidService(): set to: null
D/HidService( 5518): mStartError = false
D/BluetoothAdapterService( 5518): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ec0814b
I/BluetoothHealthServiceJni( 5518): classInitNative: succeeds
D/HealthService( 5518): Received start request. Starting profile...
D/HealthService( 5518): start()
I/ActivityManager( 1013): Killing 5033:com.google.android.gms:car/u0a12 (adj 15): empty #31
,I/bluedroid( 5518): get_profile_interface health
D/HealthService( 5518): mStartError = false
D/BluetoothAdapterService( 5518): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ec0814b
D/IntelligenceServiceApplication( 5555): no applications having user consent for prediction
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,I/BluetoothPanServiceJni( 5518): classInitNative(L105): succeeds
,V/PlaceDetection v1.0.19 ( 5555): [PlaceDetection::stopService] Service stopped.
,D/BluetoothPan( 1013): BluetoothPAN Proxy object connected
,D/PanService( 5518): Received start request. Starting profile...
,D/PanService( 5518): start()
,D/BluetoothPanServiceJni( 5518): initializeNative(L110): pan
,I/bluedroid( 5518): get_profile_interface pan
,D/PanService( 5518): mStartError = false
D/BluetoothAdapterService( 5518): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ec0814b
,V/PlaceDetection v1.0.19 ( 5555): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,D/BluetoothMapService( 5518): Received start request. Starting profile...
D/BluetoothMapService( 5518): start()
,D/BluetoothMapService( 5518): mStartError = false
,D/BluetoothAdapterService( 5518): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ec0814b
,I/BluetoothSAPServiceJni( 5518): classInitNative(L204): succeeds
,D/SapService( 5518): Received start request. Starting profile...
,D/SapService( 5518): start()
,D/BluetoothSAPServiceJni( 5518): initializeNative(L209): sap
I/bluedroid( 5518): get_profile_interface sap
D/SapService( 5518): mStartError = false
D/BluetoothAdapterService( 5518): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ec0814b
,D/HeadsetStateMachine( 5518): Try to query the phonestate on bind
,I/Telecom ( 1415): BluetoothPhoneService: queryPhoneState
,I/Telecom ( 1415): BluetoothPhoneService: handleMessage(7) / param 0,
I/Telecom ( 1415): BluetoothPhoneService: updateHeadsetWithCallState
,I/Telecom ( 1415): BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,I/Telecom ( 1415): BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,I/Telecom ( 1415): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,W/BluetoothHeadset( 1415): Proxy not attached to service
,I/Telecom ( 1415): BluetoothPhoneService: Result of Message : true
,D/HeadsetStateMachine( 5518): Proxy object connected
D/HeadsetPhoneState( 5518): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetPhoneState( 5518): sendDeviceDataStateChanged
D/HeadsetStateMachine( 5518): Disconnected process message: 11
D/HeadsetStateMachine( 5518): Disconnected process message: 18
D/HeadsetPhoneState( 5518): Signal level : previous=0 curr=0
E/BluetoothAdapterService(784367947)( 5518): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
V/HeadsetService( 5518): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/BluetoothA2dp( 5518): Proxy object connected
D/BluetoothAdapterService( 5518): Bluetooth A2dp source service connected
,E/BluetoothAdapterService(784367947)( 5518): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
D/HeadsetStateMachine( 5518): Disconnected process message: 10
D/HeadsetPhoneState( 5518): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 5518): Disconnected process message: 11
,E/BluetoothAdapterService(784367947)( 5518): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,E/BluetoothAdapterService(784367947)( 5518): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,E/BluetoothAdapterService(784367947)( 5518): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5587): MountEmulatedStorage()
,I/libpersona( 5587): KNOX_SDCARD checking this for 10107
E/Zygote  ( 5587): v2
I/libpersona( 5587): KNOX_SDCARD not a persona
,I/SELinux ( 5587): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1013): Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=5587 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 5587): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5587): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1013): getContentProviderImpl callerProcessName:com.android.bluetooth, calleePkgName: com.android.email,
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1013): failed to open /acct/uid_10012/pid_5033/cgroup.procs: No such file or directory
,I/SecureStorage(  335): [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,D/TimaKeyStoreProvider( 5587): TimaSignature is unavailable
I/ActivityManager( 1013): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=5601 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
D/ActivityThread( 5587): Added TimaKeyStore provider
,E/Zygote  ( 5601): MountEmulatedStorage()
I/libpersona( 5601): KNOX_SDCARD checking this for 10145
E/Zygote  ( 5601): v2
I/libpersona( 5601): KNOX_SDCARD not a persona
I/SELinux ( 5601): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SecureStorage( 5572): [INFO]: SPID(0x00000002)Processing data has been completed
I/SELinux ( 5601): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5601): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5601): TimaSignature is unavailable
,D/ActivityThread( 5601): Added TimaKeyStore provider
,W/ResourcesManager( 5601): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5601): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5601): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5601): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5601): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/wpa_supplicant( 5572): Ctrl_iface: loading cred from phone,
I/SecureStorage( 5572): [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,D/RCPManagerService( 1013): exchangeData() failure , invalid userId,
,I/SecureStorage( 5572): [INFO]: SPID(0x00000002)This device supports Secure Storage,
I/SecureStorage(  335): [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 5572
I/SecureStorage(  335): [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,I/SecureStorage( 5572): [INFO]: SPID(0x00000002)SS Daemon is running
I/wpa_supplicant( 5572): ssSupport state is = 1
,I/wpa_supplicant( 5572): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5572): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5572): SIM READ ERROR
I/wpa_supplicant( 5572): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5572): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,E/wpa_supplicant( 5572): SIM READ ERROR
I/wpa_supplicant( 5572): Blacklist: Clear (all) 
I/wpa_supplicant( 5572): wpa_default_ap_write_once
I/wpa_supplicant( 5572): There is no /data/misc/wifi/default_ap.check. Start copy default ap
,I/wpa_supplicant( 5572): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5572): getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
I/wpa_supplicant( 5572): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5572): getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
,I/wpa_supplicant( 5572): rfkill: Cannot open RFKILL control device,
,I/Nat464Xlat( 1013): interfaceLinkStateChanged wlan0, false
D/Tethering( 1013): interfaceLinkStateChanged wlan0, false
D/Tethering( 1013): interfaceStatusChanged wlan0, false
,D/RCPManagerService( 1013): exchangeData() failure , invalid userId
,I/wpa_supplicant( 5572): wlan0: Setting scan request: 0 sec 100000 usec
,E/BluetoothAdapterService(784367947)( 5518): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
E/BluetoothAdapterService(784367947)( 5518): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,I/ActivityManager( 1013): Killing 4357:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,D/RCPManagerService( 1013): exchangeData() failure , invalid userId
,D/BluetoothAdapterState( 5518): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 5518): enable
,I/bt_hci_bdroid( 5518): init
,I/bt_vendor( 5518): bt-vendor : init
,I/bt_vendor( 5518): bt-vendor : get_bt_soc_type
E/bt_vendor( 5518): get_bt_soc_type: Failed to get soc type
,I/bt_vendor( 5518): init: Local BD Address : ab:96:37:0e:f9:7c
D/bt_userial_mct( 5518): userial_init
,I/GKI_LINUX( 5518): gki_task_entry task_id=0 [BTU] starting
,I/bt_vendor( 5518): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 5518): Starting hciattach daemon
I/bt_vendor( 5518): try to set false
,I/bt_vendor( 5518): bt-vendor : BT_VND_OP_POWER_CTRL: On
I/bt_vendor( 5518): Starting hciattach daemon
I/bt_vendor( 5518): try to set true
,I/qcom-bluetooth( 5633): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,I/qcom-bluetooth( 5641): /system/etc/init.qcom.bt.sh: Transport : smd ,
,D/RCPManagerService( 1013): exchangeData() failure , invalid userId
,I/qcom-bluetooth( 5642): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,D/BadgeProvider( 5274): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/qcom-bluetooth( 5645): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 5647): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
,I/qcom-bluetooth( 5648): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,I/qcom-bluetooth( 5649): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,D/RCPManagerService( 1013): exchangeData() failure , invalid userId,
,I/wpa_supplicant( 5572): wlan0: State: DISCONNECTED -> DISCONNECTED
,I/SecureStorage( 5572): [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,D/RCPManagerService( 1013): exchangeData() failure , invalid userId
,V/GLSActivity( 1856): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1856): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SecureStorage( 5572): [INFO]: SPID(0x00000002)This device supports Secure Storage
,I/SecureStorage(  335): [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 5572
I/SecureStorage(  335): [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
I/SecureStorage( 5572): [INFO]: SPID(0x00000002)SS Daemon is running
I/wpa_supplicant( 5572): ssSupport state is = 1
,W/libprocessgroup( 1013): failed to open /acct/uid_10044/pid_4357/cgroup.procs: No such file or directory
,D/BadgeProvider( 5274): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5274): sendNotify, [notify] : null
D/BadgeProvider( 5274): update, [uri] : content://com.sec.badge/apps/1
,D/Launcher.Model( 1463): reloadBadges entered.
,D/BadgeProvider( 5274): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5274): update, [UpdateCount] : 1
,I/wpa_supplicant( 5572): Ctrl_iface: loading cred from phone
I/SecureStorage( 5572): [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,I/SecureStorage( 5572): [INFO]: SPID(0x00000002)This device supports Secure Storage,
I/SecureStorage(  335): [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 5572
I/SecureStorage(  335): [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,I/SecureStorage( 5572): [INFO]: SPID(0x00000002)SS Daemon is running
I/wpa_supplicant( 5572): ssSupport state is = 1
I/wpa_supplicant( 5572): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5572): getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
E/wpa_supplicant( 5572): SIM READ ERROR
I/wpa_supplicant( 5572): wpa_default_ap_write_once
I/wpa_supplicant( 5572): There is no /data/misc/wifi/default_ap.check. Start copy default ap
I/wpa_supplicant( 5572): rfkill: Cannot open RFKILL control device
,I/Nat464Xlat( 1013): interfaceLinkStateChanged p2p0, false
,D/Tethering( 1013): interfaceLinkStateChanged p2p0, false
D/Tethering( 1013): interfaceStatusChanged p2p0, false
,I/Nat464Xlat( 1013): interfaceLinkStateChanged p2p0, false
,D/Tethering( 1013): interfaceLinkStateChanged p2p0, false
D/Tethering( 1013): interfaceStatusChanged p2p0, false
,D/StrictMode( 5587): StrictMode policy violation; ~duration=381 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5587): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5587): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 5587): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 5587): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 5587): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 5587): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 5587): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 5587): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
D/StrictMode( 5587): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 5587): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 5587): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 5587): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 5587): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 5587): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5587): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 5587): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 5587): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5587): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5587): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 5587): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/StrictMode( 5587): StrictMode policy violation; ~duration=374 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5587): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5587): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 5587): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 5587): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 5587): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 5587): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 5587): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 5587): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 5587): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 5587): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 5587): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 5587): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5587): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 5587): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 5587): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5587): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5587): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 5587): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/StrictMode( 5587): StrictMode policy violation; ~duration=292 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5587): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5587): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 5587): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 5587): 	at java.io.File.exists(File.java:363)
D/StrictMode( 5587): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 5587): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 5587): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
D/StrictMode( 5587): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 5587): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 5587): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 5587): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 5587): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 5587): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 5587): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5587): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 5587): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 5587): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5587): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5587): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 5587): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 5587): StrictMode policy violation; ~duration=291 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5587): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5587): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 5587): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 5587): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 5587): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 5587): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 5587): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 5587): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 5587): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 5587): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 5587): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 55,87): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5587): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 5587): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 5587): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5587): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5587): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 5587): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 5587): StrictMode policy violation; ~duration=289 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5587): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5587): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 5587): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 5587): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 5587): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 5587): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 5587): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 5587): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 5587): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 5587): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 5587): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 5587): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5587): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 5587): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 5587): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5587): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5587): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 5587): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 5587): StrictMode policy violation; ~duration=284 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5587): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5587): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 5587): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 5587): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 5587): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 5587): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 5587): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 5587): 	at com.google.r.k.a(PG:2107)
D/StrictMode( 5587): 	at com.google.v.a.a.eq.<init>(PG:23)
D/StrictMode( 5587): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 5587): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 5587): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 5587): 	at com.google.r.e.b(PG:170)
D/StrictMode( 5587): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 5587): 	at com.google.b.a.ca.a(PG:125)
D/Strict,Mode( 5587): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 5587): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 5587): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 5587): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 5587): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 5587): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5587): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 5587): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 5587): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5587): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5587): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 5587): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 5587): StrictMode policy violation; ~duration=282 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5587): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5587): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 5587): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 5587): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 5587): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 5587): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 5587): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 5587): 	at com.google.r.k.b(PG:14147)
D/StrictMode( 5587): 	at com.google.r.k.c(PG:583)
D/StrictMode( 5587): 	at com.google.v.a.a.eq.<init>(PG:40)
D/StrictMode( 5587): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 5587): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 5587): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 5587): 	at com.google.r.e.b(PG:170)
D/StrictMode( 5587): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 5587): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 5587): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 5587): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 5587): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 5587): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 5587): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5587): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 5587): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 5587): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5587): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5587): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 5587): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 5587): StrictMode policy violation; ~duration=242 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5587): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5587): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 5587): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 5587): 	at java.io.File.exists(File.java:363)
D/StrictMode( 5587): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 5587): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 5587): 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
D/StrictMode( 5587): 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
D/StrictMode( 5587): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 5587): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 5587): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 5587): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 5587): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 5587): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5587): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 5587): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 5587): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5587): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5587): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 5587): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 5587): StrictMode policy violation; ~duration=241 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5587): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5587): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 5587): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 5587): 	at java.io.File.exists(File.java:363)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.map.l.s.a(PG:7692)
D/StrictMode( 5587): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 5587): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 5587): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 5587): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 5587): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 5587): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 5587): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5587): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 5587): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 5587): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5587): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5587): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 5587): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
I/ServiceManager(  314): Waiting for service AtCmdFwd...
E/SMD     (  287): DCD OFF
,I/wpa_supplicant( 5572): p2p0: State: DISCONNECTED -> INACTIVE
I/wpa_supplicant( 5572): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
W/com.google.a.a.b.d.a( 5587): Application name is not set. Call Builder#setApplicationName.
,I/art     ( 1013): Explicit concurrent mark sweep GC freed 26710(1422KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 2.605ms total 177.318ms
,I/ActivityManager( 1013): Killing 4769:com.samsung.aasaservice/1000 (adj 15): empty #31
,D/AuthorizationBluetoothService( 1856): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/wpa_supplicant( 5572): p2p0: State: INACTIVE -> DISCONNECTED
I/wpa_supplicant( 5572): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
I/wpa_supplicant( 5572): Skip scan - bUseNetwork false
,E/WifiStateMachine( 1013): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,D/ActivityManager( 1013): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
I/Nat464Xlat( 1013): interfaceLinkStateChanged p2p0, false
D/Tethering( 1013): interfaceLinkStateChanged p2p0, false
D/Tethering( 1013): interfaceStatusChanged p2p0, false
,I/Hs20UtilService( 3393): Starting #2
,I/Hs20UtilService( 3393): Message received 5011
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/WifiNative-wlan0( 1013): callSECApiBoolean - ID [21]
,I/wpa_supplicant( 5572): HOTSPOT20_ENABLE called
I/wpa_supplicant( 5572): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5572): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5572): SIM READ ERROR
I/wpa_supplicant( 5572): Blacklist: Clear (all) 
,E/Zygote  ( 5659): MountEmulatedStorage()
E/Zygote  ( 5659): v2
I/libpersona( 5659): KNOX_SDCARD checking this for 1000
I/libpersona( 5659): KNOX_SDCARD not a persona
,I/qcom-bluetooth( 5658): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab 
,I/SELinux ( 5659): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5659): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 5659): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/qcom-bluetooth( 5664): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
I/ActivityManager( 1013): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=5659 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,I/wpa_supplicant( 5572): wlan0: Setting scan request: 0 sec 0 usec,
,I/bt_vendor( 5518): bluetooth satus is on,
D/bt_userial_mct( 5518): userial_open(port:0)
I/bt_vendor( 5518): bt-vendor : BT_VND_OP_USERIAL_OPEN
,I/bt_vendor( 5518): Done intiailizing UART
,I/wpa_supplicant( 5572): Skip scan - bUseNetwork false
,D/WifiNative-wlan0( 1013): callSECApiInt - ID [210]
,I/bt_vendor( 5518): Done intiailizing UART
I/bt_userial_mct( 5518): CMD=65, EVT=65, ACL_Out=66, ACL_In=66
I/bt_vendor( 5518): Bluetooth Firmware and transport layer are initialized
,D/TimaKeyStoreProvider( 5659): TimaSignature is unavailable
,D/ActivityThread( 5659): Added TimaKeyStore provider
,D/WifiConfigStore( 1013): Loading config and enabling all networks 
,I/        ( 5518): BTE_InitTraceLevels -- TRC_HCI
I/        ( 5518): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 5518): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 5518): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 5518): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 5518): BTE_InitTraceLevels -- TRC_A2D
I/        ( 5518): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 5518): BTE_InitTraceLevels -- TRC_BTM
I/        ( 5518): BTE_InitTraceLevels -- TRC_GAP
I/        ( 5518): BTE_InitTraceLevels -- TRC_PAN
I/        ( 5518): BTE_InitTraceLevels -- TRC_SAP
I/        ( 5518): BTE_InitTraceLevels -- TRC_SDP
I/        ( 5518): BTE_InitTraceLevels -- TRC_GATT
I/        ( 5518): BTE_InitTraceLevels -- TRC_SMP
I/        ( 5518): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 5518): BTE_InitTraceLevels -- TRC_BTIF
I/        ( 5518): BTE_InitTraceLevels -- TRC_PROTOCOL
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/STATUSBAR-WifiQuickSettingButton( 1175): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1175): Wifi onReceive(3)
,D/STATUSBAR-QSTileView( 1175): onStateChanged: Wi-Fi
,D/HotspotTile( 1175): onReceive : android.net.wifi.WIFI_STATE_CHANGED
W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/HotspotTile( 1175): onReceive : 3, 0
,D/bt_userial_mct( 5518): Entering userial_read_thread()
,D/WifiCredService( 1281): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,E/WifiConfigStore( 1013): Not a HS20
,E/WifiConfigStore( 1013): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WifiNative-wlan0( 1013): callSECApiInt - ID [65]
,D/WifiNative-wlan0( 1013): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 5572): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant( 5572): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 5572): reset timer : RESET_TIMER 0
I/wpa_supplicant( 5572): P2P: Current p2p state = IDLE
I/wpa_supplicant( 5572): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 5572): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 5572): First Scan Start
I/wpa_supplicant( 5572): Scan requested (ret=0) - scan timeout 30 seconds,
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_4769/cgroup.procs: No such file or directory
,D/WifiNative-wlan0( 1013): Setting external_sim to 1
,D/WifiStateMachine( 1013): Setting OUI to DA-A1-19
,I/WifiNative-HAL( 1013): startHal
E/wifi    ( 1013): getStaticLongField sWifiHalHandle 0x9c8cf88c
I/WifiNative-HAL( 1013): Could not start hal
,E/WifiNative-wlan0( 1013): do suspend true
,E/WifiStateMachine( 1013): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
D/WifiP2pService( 1013): P2pDisabledState{ what=131203 }
,D/CommandListener(  277): Setting iface cfg
D/CommandListener(  277): Trying to bring up p2p0
,D/WifiScanningService( 1013): SCAN_AVAILABLE : 3
,D/WifiMonitor( 1013): startMonitoring(p2p0) with mConnected = true
D/WifiScanningService( 1013): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL( 1013): startHal
,D/WifiP2pService( 1013): P2pEnablingState
E/wifi    ( 1013): getStaticLongField sWifiHalHandle 0x9dd799bc
D/WifiP2pService( 1013): P2pEnablingState{ what=147457 }
,D/WifiP2pService( 1013): P2p socket connection successful
D/WifiP2pService( 1013): P2pEnabledState
D/RttService( 1013): SCAN_AVAILABLE : 3
,D/WifiP2pService( 1013): sending p2p connection changed broadcast: IDLE
,D/RttService( 1013): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL( 1013): Could not start hal
,E/WifiScanningService( 1013): could not start HAL
,E/WifiStateMachine( 1013): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-wlan0( 1013): callSECStringApiVoid - ID [215]
E/WifiNative-wlan0( 1013): invaild command id : 215
,D/WifiP2pService( 1013): create mNetworkAgent
,E/WifiStateMachine( 1013): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,D/WifiDisplayController( 1013): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController( 1013): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 1013): disconnect
D/WifiDisplayController( 1013): updateConnection
D/WifiDisplayController( 1013): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,I/wpa_supplicant( 5572): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,I/wpa_supplicant( 5572): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,I/wpa_supplicant( 5572): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,D/WifiDisplayAdapter( 1013): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/SecContentProvider2( 1013): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1013): mCursor = null
,D/AllShareCastTile( 1175): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
D/SecContentProvider2( 1013): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1013): mCursor = null
,D/WifiDisplayAdapter( 1013): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ConnectivityService( 1013): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 1013): hsengiv:checkWhatTypeOfNetwork and the value is false
,E/ConnectivityService( 1013): updateNetworkInfo()
,D/ConnectivityService( 1013): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from null to UNKNOWN, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,E/CSLegacyTypeTracker( 1013): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} } for legacy network type 13
,D/AllShareCastTile( 1175): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,W/bt-l2cap( 5518): l2c_link_processs_ble_num_bufs 16
,E/bt-btm  ( 5518): BTM_SecRegister:p_cb_info->p_le_callback == 0xa40c66e9 
,E/bt-btm  ( 5518): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa40c66e9 
,D/WifiDisplayController( 1013): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WifiNative-p2p0( 1013): p2pGetDeviceAddress
,D/WifiNative-p2p0( 1013): p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
,D/BluetoothAdapterProperties( 5518): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,E/bt-btif ( 5518): Calling BTA_HhEnable
D/WifiP2pService( 1013): DeviceAddress: 7e:96:ac
,E/bt-btif ( 5518):                : sec: 0x80orig 0, psm 0x0019, proto_id 7
D/BluetoothAdapterProperties( 5518): Address is:7C:F9:0E:37:96:AB
E/BluetoothServiceJni( 5518): populateRssiValuesNative
I/bluedroid( 5518): getModelRssiValues
E/BluetoothServiceJni( 5518): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 5518): modelRssiValuesCallback, low, mid, high = -70,-60,127
,D/WifiDisplayController( 1013): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
D/WifiDisplayController( 1013):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1013):  primary type: 10-0050F204-5
D/WifiDisplayController( 1013):  secondary type: null
D/WifiDisplayController( 1013):  wps: 0
D/WifiDisplayController( 1013):  grpcapab: 0
D/WifiDisplayController( 1013):  devcapab: 0
D/WifiDisplayController( 1013):  status: 3
D/WifiDisplayController( 1013):  wfdInfo: null
D/WifiDisplayController( 1013):  groupownerAddress: null
D/WifiDisplayController( 1013):  GOdeviceName: null
D/WifiDisplayController( 1013):  interfaceAddress: 
D/WifiDisplayController( 1013):  SConnectInfo : null
,D/BluetoothAdapterProperties( 5518): Name is: A5-1
,D/SettingsProvider( 1013): name = bluetooth_name
,D/SecurityLogAgent( 5659): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 5659): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5659): StateMachine : Current State = 1
,D/SecurityLogAgent( 5659): StateMachine : Changed Current State = 1
,I/ActivityManager( 1013): Killing 4659:com.samsung.android.sm/1000 (adj 15): empty #31
,D/BluetoothUtils( 5518): getBtEnabledContainers(): btContainers = []
,D/BluetoothAdapterProperties( 5518): Scan Mode:20
D/BluetoothAdapterProperties( 5518): Discoverable Timeout:120
,D/BluetoothAdapterProperties( 5518): LE Address is:FC:F3:1C:6E:2D:57
E/bt-btif ( 5518): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif ( 5518): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,E/bt-btif ( 5518): btif_sock_init: !radio_req && !rfc_init
,E/bt-btif ( 5518): btif_sock_init: !vhci_init
,D/IOP_DB_BT( 5518): db_open: file /etc/bluetooth/iop_bt.db
,E/bt_mct  ( 5518): hci lib postload completed
,D/ActivityManager( 1013): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/IOP_DB_BT( 5518): db_open: db_open : handle 3023777808l, read 13894 bytes onto local cache
,D/IOP_DB_BT( 5518): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 5518): db_query: result 1
,I/        ( 5518): iop_db_open: iop_db_open status 0
,I/Hs20UtilService( 3393): Starting #3
,I/Hs20UtilService( 3393): Message received 5011
,E/WifiStateMachine( 1013): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-wlan0( 1013): callSECStringApiVoid - ID [215]
E/WifiNative-wlan0( 1013): invaild command id : 215
,D/bte_conf( 5518): Device ID record 1 : primary
D/bte_conf( 5518):   vendorId            = 0075
D/bte_conf( 5518):   vendorIdSource      = 0001
D/bte_conf( 5518):   product             = 0100
D/bte_conf( 5518):   version             = 0200
D/bte_conf( 5518):   clientExecutableURL = 
D/bte_conf( 5518):   serviceDescription  = 
D/bte_conf( 5518):   documentationURL    = 
D/bte_conf( 5518): bte_load_did_conf no section named DID2.
,D/BluetoothPanServiceJni( 5518): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,D/SecurityLogAgent( 5659): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 5659): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5659): StateMachine : Current State = 1
D/SecurityLogAgent( 5659): StateMachine : Changed Current State = 1
,D/BluetoothAdapterState( 5518): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,D/BluetoothAdapterProperties( 5518): ScanMode =  20
,D/BluetoothAdapterProperties( 5518): State =  11
,D/WifiP2pService( 1013): sending p2p persistent groups changed broadcast
,D/SecContentProvider( 1013): uri = 3 selection = isDiscoverableEnabled
,D/NearbySettings( 1281): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/WifiP2pService( 1013): InactiveState
,D/WifiP2pService( 1013): InactiveState{ what=143376 }
D/WifiP2pService( 1013): P2pEnabledState{ what=143376 }
,I/wpa_supplicant( 5572): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,D/BluetoothUtils( 5518): getBtEnabledContainers(): btContainers = []
,D/BluetoothAdapterProperties( 5518): Scan Mode:21
D/BluetoothAdapterProperties( 5518): Setting state to 12
V/NearbySettings( 1281): DMSUtil.isNetworkConnected - flag-null, state-null
D/WifiP2pService( 1013): InactiveState{ what=143376 }
I/BluetoothAdapterState( 5518): Bluetooth adapter state changed: 11-> 12
,D/WifiP2pService( 1013): P2pEnabledState{ what=143376 }
D/BluetoothAdapterProperties( 5518): Discoverable Timeout:120
E/ConnectivityService( 1013): updateNetworkInfo()
,D/SettingsProvider( 1013): name = bluetooth_a2dp_sink_mode
D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 1002
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
I/NearbySettings( 1281): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,W/BackupManagerService( 1013): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/NearbySettings( 1281): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1281): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1281): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1281): MountReceiver.mPrefHandler - 7002
,D/BluetoothAdapterService( 5518): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5518): updateAdapterState state is 12
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,E/Zygote  ( 5688): MountEmulatedStorage()
E/Zygote  ( 5688): v2
I/libpersona( 5688): KNOX_SDCARD checking this for 10068
I/libpersona( 5688): KNOX_SDCARD not a persona
,I/SELinux ( 5688): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5688): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1013): Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=5688 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ActivityManager( 1013): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,E/SELinux ( 5688): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothAdapterService( 5518): Autoconnection is available 
D/BluetoothAdapterService( 5518): updateAdapterState prevState = 11newState = 12
D/BluetoothAdapterService( 5518): starting service from this receiver
D/BluetoothAdapter( 5587): onBluetoothStateChange: up=true
D/BluetoothAdapter( 5587): onBluetoothStateChange: Bluetooth is on
,D/BluetoothAdapter( 1856): onBluetoothStateChange: up=true
D/ActivityManager( 1013): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
I/BluetoothAdapterState( 5518): Entering On State from state = 11
D/BluetoothAdapter( 1856): onBluetoothStateChange: Bluetooth is on
D/BluetoothAdapter( 5426): onBluetoothStateChange: up=true
D/BluetoothAdapter( 5426): onBluetoothStateChange: Bluetooth is on
D/BluetoothAdapter( 2704): onBluetoothStateChange: up=true
D/BluetoothAdapter( 2704): onBluetoothStateChange: Bluetooth is on
,D/BluetoothAdapter( 1013): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1013): onBluetoothStateChange: Bluetooth is on
D/BluetoothAdapter( 1175): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1175): onBluetoothStateChange: Bluetooth is on
D/TimaKeyStoreProvider( 5688): TimaSignature is unavailable
D/ActivityThread( 5688): Added TimaKeyStore provider
D/BluetoothA2dp( 2704): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 1423): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1423): onBluetoothStateChange: Bluetooth is on
I/BluetoothPbapService( 5518): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,D/BluetoothAdapter( 1415): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1415): onBluetoothStateChange: Bluetooth is on
,D/BluetoothA2dp( 5518): onBluetoothStateChange: up=true
,D/BluetoothA2dp( 1013): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 5518): onBluetoothStateChange: up=true
D/BluetoothAdapter( 5518): onBluetoothStateChange: Bluetooth is on
,D/BluetoothAdapter( 1437): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1437): onBluetoothStateChange: Bluetooth is on
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,W/InputMethodManagerService( 1013): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService( 1013): [BT Setting State] State =12
I/InputMethodManagerService( 1013): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/BluetoothTile( 1175):  onBluetoothStateChange:
D/BluetoothHeadset( 1415): registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@26b0c1a0, true
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_4659/cgroup.procs: No such file or directory
,I/SamsungIME( 1798): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/BluetoothHeadset( 1415): registerMessageListener
,I/BluetoothPbapService( 5518): Handler(): got msg=1
,D/SecContentProvider( 1013): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,W/ResourcesManager( 5688): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/HeadsetService( 5518): registerMessageListener
,D/HeadsetService( 5518): registerMessageListener
,D/HeadsetStateMachine( 5518): Disconnected process message: 70
I/Telecom ( 1415): BluetoothPhoneService: handleMessage(7) / param null
I/Telecom ( 1415): BluetoothPhoneService: updateHeadsetWithCallState
,D/HeadsetStateMachine( 5518): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@8afd464
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,V/BluetoothPbapService( 5518): PBAP Service initSocket try: 0
,I/Telecom ( 1415): BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,I/Telecom ( 1415): BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,D/BluetoothMapMasInstance( 5518): set MAP SDP message type : 1
I/Telecom ( 1415): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/HeadsetStateMachine( 5518): Disconnected process message: 9
,D/HeadsetStateMachine( 5518): mNumActive: 0 mNumHeld: 0 mCallState: 6
,D/BluetoothSocket( 5518): bindListen(): myUserId = 0
W/BluetoothAdapter( 5518): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 5518): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
D/BluetoothSocket( 5518): bindListen(), new LocalSocket 
D/BluetoothSocket( 5518): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 5518): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2eec16cd
D/BluetoothSocket( 5518): channel: 19
D/BluetoothPbapService( 5518): PBAP Socket is BluetoothServerSocket
,D/BluetoothSocket( 5518): bindListen(): myUserId = 0
W/BluetoothAdapter( 5518): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 5518): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
D/BluetoothSocket( 5518): bindListen(), new LocalSocket 
D/BluetoothSocket( 5518): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 5518): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@19065b82
,D/BluetoothSocket( 5518): channel: 5
,D/audio_hw_primary(  282): adev_set_parameters: enter: A2dpSuspended=false
,V/voice   (  282): voice_set_parameters: enter: A2dpSuspended=false
,V/voice   (  282): voice_set_parameters: exit with code(-2)
,V/msm8974_platform(  282): platform_set_parameters: enter: A2dpSuspended=false
D/FileShare-Client( 5688): ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/BluetoothTile( 1175):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1175): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothTile( 1175):  getBluetoothState : 12
V/msm8974_platform(  282): platform_set_parameters: exit with code(-2)
D/BluetoothTile( 1175):  handleUpdatestate:false name:null
D/audio_hw_hfp(  282): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  282): adev_set_parameters: exit
E/HeadsetStateMachine( 5518): terminateScoUsingVirtualVoiceCall:No present call to terminate,
,D/BluetoothTile( 1175):  handleUpdatestate:false name:null
,D/StatusBarManagerService( 1013): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/StatusBarManagerService( 1013): setIconVisibility slot=bluetooth visible=true
,D/PhoneStatusBar( 1175): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/BluetoothTile( 1175):  handleUpdatestate:false name:null
,D/FileShare-Client( 5688): ClientBroadcastReceiver.onReceive - disconnected
,D/FileShare-Client( 5688): Outbound.stopDelayTimer - 
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5706): MountEmulatedStorage()
,E/Zygote  ( 5706): v2
I/libpersona( 5706): KNOX_SDCARD checking this for 10069
I/libpersona( 5706): KNOX_SDCARD not a persona
I/SELinux ( 5706): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1013): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=5706 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1013): Killing 5082:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,I/SELinux ( 5706): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5706): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5706): TimaSignature is unavailable
,D/ActivityThread( 5706): Added TimaKeyStore provider
,D/FileShare-Server( 5706): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,I/ActivityManager( 1013): Killing 3687:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,W/ContextImpl( 1281): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/ActivityManager( 1013): startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,D/LocalBluetoothProfileManager( 1281): Adding local A2DP profile
,D/BluetoothA2dp( 1281): doBind(): CallingUid(myUserHandle) = 0
,D/ActivityManager( 1013): bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/LocalBluetoothProfileManager( 1281): Adding local HEADSET profile
,E/BluetoothHeadset( 1281): BTStateChangeCB is registed
,D/BluetoothHeadset( 1281): doBind(): CallingUid(myUserHandle) = 0
,D/ActivityManager( 1013): bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 1281): BluetoothHeadset service is binded
,D/BluetoothMap( 1281): Create BluetoothMap proxy object
,D/ActivityManager( 1013): bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/ActivityManager( 1013): bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,W/ContextImpl( 1281): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,D/ActivityManager( 1013): bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/Bluetoothsap( 1281): bindService called to Bluetooth SAP Service
,D/ActivityManager( 1013): bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,W/libprocessgroup( 1013): failed to open /acct/uid_10152/pid_5082/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_3687/cgroup.procs: No such file or directory
,D/ActivityManager( 1013): bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/LocalBluetoothProfileManager( 1281): PANU : true
,W/LocalBluetoothProfileManager( 1281): Warning: SAP profile was previously added.
D/LocalBluetoothProfileManager( 1281): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 1281): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1281): onReceive
,D/BluetoothA2dp( 1281): Proxy object connected
D/A2dpProfile( 1281): Bluetooth service connected
,V/BluetoothStatusReceiver( 1175): Received android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothStatusReceiver( 1175): AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,D/HeadsetProfile( 1281): Bluetooth service connected
,D/BluetoothMap( 1281): Proxy object connected
D/MapProfile( 1281): Bluetooth service connected
,D/BluetoothMap( 1281): getConnectedDevices()
D/BluetoothAdapterService( 5518): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ec0814b
D/BtConfig.SecureMode( 5518): isSecureModeOn:false
,D/ActivityManager( 1013): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothPbap( 1281): Proxy object connected
D/PbapServerProfile( 1281): Bluetooth service connected
,D/Bluetoothsap( 1281): BluetoothSAP Proxy object connected
D/SapProfile( 1281): Bluetooth service connected
D/Bluetoothsap( 1281): getConnectedDevices()
,D/AuthorizationBluetoothService( 1856): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothInputDevice( 1281): Proxy object connected
D/HidProfile( 1281): Bluetooth service connected
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,D/BluetoothPan( 1281): BluetoothPAN Proxy object connected
,D/PanProfile( 1281): Bluetooth service connected
,D/SecContentProvider( 1013): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/BluetoothSocket( 5518): bindListen(): myUserId = 0
,W/BluetoothAdapter( 5518): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 5518): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
D/BluetoothSocket( 5518): bindListen(), new LocalSocket 
D/BluetoothSocket( 5518): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 5518): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@c1f4bfc
D/BluetoothSocket( 5518): channel: 12
I/BtOppRfcommListener( 5518): Accept thread started.
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/wpa_supplicant( 5572): nl80211: Received scan results (7 BSSes),
I/wpa_supplicant( 5572): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 5572): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 5572): Trying to associate with  'G700'
I/wpa_supplicant( 5572): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 5572): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
D/WifiMonitor( 1013): didn't find BSSID Trying to associate with SSID 'NG700'
I/WifiNative-HAL( 1013): startHal
,E/wifi    ( 1013): getStaticLongField sWifiHalHandle 0x9c8cf8ac
I/WifiNative-HAL( 1013): Could not start hal
,D/SecContentProvider2( 1013): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1013): mCursor = null
,E/wpa_supplicant( 5572): Cmd 35605 not handled
,I/wpa_supplicant( 5572): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 5572): wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,I/wpa_supplicant( 5572): wlan0: State: ASSOCIATING -> ASSOCIATED
I/Nat464Xlat( 1013): interfaceLinkStateChanged wlan0, false
D/Tethering( 1013): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1013): interfaceLinkStateChanged wlan0, false
D/Tethering( 1013): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 5572): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 5572): Associated with C0.AA.48
I/wpa_supplicant( 5572): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 5572): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 5572): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 1013): interfaceLinkStateChanged wlan0, false
D/Tethering( 1013): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1013): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1013): interfaceLinkStateChanged wlan0, false
D/Tethering( 1013): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1013): interfaceLinkStateChanged wlan0, true
,D/Tethering( 1013): interfaceLinkStateChanged wlan0, true
D/Tethering( 1013): interfaceStatusChanged wlan0, true
,D/SecContentProvider2( 1013): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1013): mCursor = null
,I/wpa_supplicant( 5572): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 5572): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/SecContentProvider2( 1013): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1013): mCursor = null
,I/wpa_supplicant( 5572): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 5572): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 5572): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 5572): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 5572): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 5572): Blacklist: Clear (temp) 
I/wpa_supplicant( 5572): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,I/Nat464Xlat( 1013): interfaceLinkStateChanged wlan0, true
D/Tethering( 1013): interfaceLinkStateChanged wlan0, true
D/Tethering( 1013): interfaceStatusChanged wlan0, true
,E/Tethering( 1013): No numeric data
,D/Tethering( 1013): sendTetherStateChangedBroadcast 1, 0, 0
,D/Tethering( 1013): clearTetheredNotification()
,D/NtpTrustedTime( 1013): forceRefresh() from cache miss
,D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
,D/HotspotTile( 1175): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1175): updateTetherState():false, false
,D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
,D/NtpTrustedTime( 1013): forceRefresh Fail.
V/NetworkStats( 1013): performPollLocked(flags=0x1)
,D/WifiNative-wlan0( 1013): callSECApiVoid - ID [50]
,D/NetworkStatsFactory( 1013): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1013): UpdateStatsForKnox main else ---
E/WifiConfigStore( 1013): setLastSelectedConfiguration -1
,V/NetworkStats( 1013): performPollLocked() took 8ms
,D/ConnectivityService( 1013): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1013): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 1013): updateNetworkInfo()
,D/ConnectivityService( 1013): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiConfigStore( 1013): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/NtpTrustedTime( 1013): forceRefresh() from cache miss
D/ActivityManager( 1013): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/NtpTrustedTime( 1013): forceRefresh Fail.
,I/Hs20UtilService( 3393): Starting #4
,I/Hs20UtilService( 3393): Message received 5007
,D/NearbySettings( 1281): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1281): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1281): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1281): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1281): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1281): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1281): MountReceiver.mPrefHandler - 7002
,E/WifiConfigStore( 1013): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  277): Setting iface cfg
,E/WifiStateMachine( 1013): Start Dhcp Watchdog 1,
,D/SecContentProvider2( 1013): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1013): mCursor = null
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/SecContentProvider2( 1013): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1013): mCursor = null
,E/WifiNative-wlan0( 1013): do suspend false
,D/WifiP2pService( 1013): InactiveState{ what=143375 }
D/WifiP2pService( 1013): P2pEnabledState{ what=143375 }
,E/dhcpcd  ( 5734): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,I/dhcpcd  ( 5734): version 5.5.6 starting
,E/dhcpcd  ( 5734): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/dhcpcd  ( 5734): wlan0: sending IPv6 Router Solicitation,
E/dhcpcd  ( 5734): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 5734): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 5734): bssid match
,I/dhcpcd  ( 5734): wlan0: rebinding lease of 192.168.1.129
,I/dhcpcd  ( 5734): wlan0: acknowledged 192.168.1.129 from 192.168.1.1,
,I/dhcpcd  ( 5734): wlan0: leased 192.168.1.129 for 86400 seconds,
,E/WifiNative-wlan0( 1013): do suspend true
,D/WifiP2pService( 1013): InactiveState{ what=143375 }
,D/WifiP2pService( 1013): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 1013): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
E/WifiStateMachine( 1013): VerifyingLinkState enter
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WifiNative-wlan0( 1013): callSECApiInt - ID [210]
,E/ConnectivityService( 1013): updateNetworkInfo()
,D/ConnectivityService( 1013): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,D/ConnectivityService( 1013): Adding iface wlan0 to network 502
,D/WifiWatchdogStateMachine( 1013): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 1013): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.DnsResolver( 1013): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker( 1013): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1013): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiStateMachine( 1013): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check,
,D/ActivityManager( 1013): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/ConnectivityService( 1013): Adding Route [fe80::/64 -> :: wlan0] to network 502
,D/ConnectivityService( 1013): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 502,
,D/ConnectivityService( 1013): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 502
,I/Hs20UtilService( 3393): Starting #5
E/ConnectivityService( 1013): Unexpected mtu value: 0, wlan0
,D/ConnectivityService( 1013): Setting Dns servers for network 502 to [/192.168.1.1]
,D/ConnectivityService( 1013): LTETest block dns file not exists
,I/Hs20UtilService( 3393): Message received 5007
D/NearbySettings( 1281): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1281): MountReceiver.onReceive - Keep current state
,D/ConnectivityService( 1013): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,E/WifiStateMachine( 1013): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService( 1013): updateNetworkInfo()
E/ConnectivityService( 1013): updateNetworkInfo()
E/WifiStateMachine( 1013): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/ConnectivityService( 1013): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1013): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1013): rematching NetworkAgentInfo [WIFI () - 502]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1013): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1013): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1013): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1013): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,I/WifiTrafficPoller( 1013): evaluateTrafficStatsPolling
,D/ConnectivityService( 1013):    accepting network in place of null
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/ConnectivityService( 1013): Setting tx/rx TCP buffers to 524288,1048576,4525824,524288,1048576,4525824
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/TelephonyNetworkFactory( 1437): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/WIFI_P2P( 1013): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1437): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1013): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,I/WifiTrafficPoller( 1013): evaluateTrafficStatsPolling
I/WifiTrafficPoller( 1013): mBoosterFLAG : 0
I/System.out( 1013): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/WifiTrafficPoller( 1013): current booster mode : FullMode
I/System.out( 1013): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1013): (HTTPLog)-Static: isShipBuild true
I/System.out( 1013): (HTTPLog)-Thread-173-511399024: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 1013): (HTTPLog)-Static: isSBSettingEnabled false
D/WifiNative-wlan0( 1013): callSECApiVoid - ID [212]
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/CSLegacyTypeTracker( 1013): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,D/CSLegacyTypeTracker( 1013): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
,D/ConnectivityService( 1013): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 1000
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1013): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1013): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
,D/Tethering( 1013): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,D/Tethering( 1013): MasterInitialState.processMessage what=3
D/EntConnectivity( 1013): Not allowed due to - mEnabled false - primarySimSlot false
,D/ConnectivityManager.CallbackHandler( 1175): CM callback handler got msg 524290
V/NetworkStats( 1013): updateIfacesLocked()
V/NetworkStats( 1013): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1013): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1013): UpdateStatsForKnox main else ---
,D/NtpTrustedTime( 1013): forceRefresh() from cache miss
,D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 1000
,V/NetworkStats( 1013): performPollLocked() took 4ms
,D/StatusBar.NetworkController( 1175): EthernetConnected: false
D/StatusBar.NetworkController( 1175): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1175): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1175): updateDataNetType()
D/StatusBar.NetworkController( 1175): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1175): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1175): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ActivityManager( 1013): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3393): Starting #6
D/NearbySettings( 1281): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1281): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1281): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/Hs20UtilService( 3393): Message received 5007
,I/NearbySettings( 1281): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1281): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1281): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1013): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/NearbySettings( 1281): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1281): MountReceiver.onReceive - Keep current state
I/Hs20UtilService( 3393): Starting #7
,I/Hs20UtilService( 3393): Message received 5007
,D/WifiStateMachine( 1013): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1013): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1013): mCursor = null
,D/SecContentProvider2( 1013): uri = 15 selection = getToastGravity
,D/SecContentProvider2( 1013): mCursor = null
,D/SecContentProvider2( 1013): uri = 15 selection = getToastGravityXOffset
,D/SecContentProvider2( 1013): mCursor = null
,D/SecContentProvider2( 1013): uri = 15 selection = getToastGravityYOffset
,D/SecContentProvider2( 1013): mCursor = null
,D/SecContentProvider2( 1013): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1013): mCursor = null
,D/SecContentProvider2( 1013): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1013): mCursor = null
,I/SurfaceFlinger(  257): id=13 createSurf (1x1),1 flag=4, Uoast
,I/System.out( 1013): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/PowerManagerService( 1013): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1013
,D/SRIB_DCS( 1175): log_dcs ThreadedRenderer::initialize entered! 
,D/NtpTrustedTime( 1013): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1452596473561 mCachedNtpElapsedRealtime : 82511 mCachedNtpCertainty : 21
,D/NtpTrustedTime( 1013): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1013): currentTimeMillis() cache hit
D/NtpTrustedTime( 1013): currentTimeMillis() cache hit
D/NtpTrustedTime( 1013): currentTimeMillis() cache hit
D/NtpTrustedTime( 1013): currentTimeMillis() cache hit
V/NetworkStats( 1013): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1013): currentTimeMillis() cache hit
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1013): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 12 Jan 2016 11:01:13 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452596472616], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452596472598]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1013): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1013): Validated
D/ConnectivityService( 1013): Validated NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1013): rematching NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1013): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
D/ConnectivityService( 1013): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityManager.CallbackHandler( 1175): CM callback handler got msg 524290
D/ConnectivityService( 1013): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/StatusBar.NetworkController( 1175): EthernetConnected: false
D/StatusBar.NetworkController( 1175): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1175): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1175): updateDataNetType()
D/StatusBar.NetworkController( 1175): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1175): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1175): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1013): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1175): handleTimeUpdate
,D/NtpTrustedTime( 1013): currentTimeMillis() cache hit
,D/AlarmManagerService( 1013): Setting time of day to sec=1452596473
,D/AlarmManagerService( 1013): Trying to open a file
,D/SecKeyguardClockView( 1175): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/AlarmManagerService( 1013): File Open Success
,D/AlarmManagerService( 1013): File Close Success
I/AlarmManagerService( 1013): DRM_TIME_PATH CHMOD 666 for resetState done 
,W/AlarmManagerService( 1013): Unable to set rtc to 1452596473: Invalid argument
V/AlarmManager( 1013): waitForAlarm result :65536
,D/SecKeyguardClockView( 1175): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1175): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1175): *** don't update sliding image ***
,V/AlarmManager( 1013): No more alarm at this time.nowELAPSED=82801 batch.start=87090
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.TIME_SET
D/KeyguardUpdateMonitor( 1175): handleTimeUpdate
,D/OTPFW   ( 1013): OTPTimeChangeLogger :: TimeChangeListener$onReceive | Device Time Changed. Current time = 1452596473846
,D/WifiStateMachine( 1013): android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
,I/DowntimeConditions( 1013): android.intent.action.TIME_SET ignored because schedule turned off.
,D/SecKeyguardClockView( 1175): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1175): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1175): onReceive action : android.intent.action.TIME_SET
,W/Settings( 1013): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/SSRM:n  ( 1013): SIOP:: AP = 320
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,D/SettingsProvider( 1013): name = lockscreen_zoom_panning_effect
,D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 10054
,D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
,D/KeyguardEffectViewUtil( 1175): isStrongPowerSavingMode() :false
,D/KeyguardEffectViewController( 1175): isPreloadedWallpaper=true
,I/GeometricMosaic_Keyguard( 1175): update
,D/KeyguardEffectViewUtil( 1175): getCurrentWallpaper() mWallpaperPath :null
W/SEC_DRM_PLUGIN_Playready(  281): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK after: 1452596472 after conversion: 1452596472
W/SEC_DRM_PLUGIN_Playready(  281): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK before: 1452596473 after conversion: 1452596473
,I/splitIntent( 1013): Split this intent : android.intent.action.TIME_SET, mSplitNum[0]=7, mSplitNum[1]=13, mSplitNum[2]=18, mBgSplitQueueNum=3 divideNum= 5 r.nextReceiver= 1 receivers.size=24
,I/splitIntent( 1013): finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5770): MountEmulatedStorage()
E/Zygote  ( 5770): v2
I/libpersona( 5770): KNOX_SDCARD checking this for 10062
I/libpersona( 5770): KNOX_SDCARD not a persona
,I/ActivityManager( 1013): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=5770 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 5770): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
I/PowerManagerService( 1013): [PWL] Off : 30s ago
I/PowerManagerService( 1013): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1013): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1013): [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=5518, ws=null) (elapsedTime=2931)
I/PowerManagerService( 1013): [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=2615)
I/PowerManagerService( 1013): [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=2614)
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/SELinux ( 5770): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5770): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/Zygote  ( 5776): MountEmulatedStorage(),
E/Zygote  ( 5776): v2
I/libpersona( 5776): KNOX_SDCARD checking this for 10135
,I/libpersona( 5776): KNOX_SDCARD not a persona
,I/SELinux ( 5776): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
D/ConnectivityService( 1013): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager( 1013): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=5776 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a,
,I/SELinux ( 5776): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5776): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 5770): TimaSignature is unavailable
,D/ActivityThread( 5770): Added TimaKeyStore provider
,D/GpsLocationProvider( 1013): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 2903): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 2903): [com.wssyncmldm.llllIIIllIlIIIIllllI(230/onReceive)] ----------- XEVENT_DM_INIT WIFI ok
I/DBG_DM  ( 2903): [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT,
I/KeyguardEffectViewUtil( 1175): set current wallpaper info
,D/SettingsProvider( 1013): name = keyguard_current_wallpaper_type
,D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 10054
,D/TimaKeyStoreProvider( 5776): TimaSignature is unavailable,
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
,D/SettingsProvider( 1013): name = keyguard_current_wallpaper_file_path
D/ActivityThread( 5776): Added TimaKeyStore provider
D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 10054
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
D/SettingsProvider( 1013): name = keyguard_current_wallpaper_res_id
D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 10054
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
,E/Zygote  ( 5803): MountEmulatedStorage(),
,E/Zygote  ( 5803): v2
I/libpersona( 5803): KNOX_SDCARD checking this for 10009
I/SELinux ( 5803): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 5803): KNOX_SDCARD not a persona
,I/SELinux ( 5803): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 5803): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=5803 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 5803): TimaSignature is unavailable
I/DBG_DM  ( 2903): [IlIlllIlllllIlIllllI(403/llIIllllIIlllIIIIlll)] Check completed.
,D/ActivityThread( 5803): Added TimaKeyStore provider
,I/DBG_DM  ( 2903): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 2903): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 2903): [IIlIIIlllllIIlIIIlII(91/llllIIIllIlIIIIllllI)] 
,D/TEST    ( 1175): run!!!
,D/daemonapp( 1314): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1314): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1314): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/GeometricMosaic_Renderer( 1175): setBackgroundBitmap
,I/DBG_DM  ( 2903): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.phenotype.service.sync.PhenotypeConfigurator; callingUser = 0; userId(target) = 0
D/daemonapp( 1314): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ResourcesManager( 5776): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5776): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5776): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/daemonapp( 1314): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/DBG_DM  ( 2903): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,I/DBG_DM  ( 2903): [com.wssyncmldm.db.file.XDB(6236/IlIIlIIlIllllIlllIII)] Initiated Type: 2
,D/daemonapp( 1314): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,D/comsamsunglog( 1314): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1314): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1314): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1314): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1314): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,E/GpsLocationProvider( 1013): No APN found to select.
D/daemonapp( 1314): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,D/daemonapp( 1314): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,I/DBG_DM  ( 2903): [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,I/DBG_DM  ( 2903): [IlIlllIlllllIlIllllI(251/lllIlIlIIIllIIlIllIl)] XDL_STATE_READY_TO_UPDATE,
D/daemonapp( 1314): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1314): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1314): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
I/DBG_DM  ( 2903): [IlIIlIIlIllllIlllIII(274/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.games.chimera.GamesSyncServiceMainProxy; callingUser = 0; userId(target) = 0
,D/daemonapp( 1314): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 2903): [llllIIIllIllIlllIIlI(772/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
,E/daemonapp( 1314): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/ChimeraCfgMgr( 2000): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2000): Module APK com.google.android.play.games already loaded
,I/DBG_DM  ( 2903): [IlIIlIIlIllllIlllIII(1901/llllIIIllIlIIIIllllI)] 
,I/DBG_DM  ( 2903): [llllIlllIIIlIlIlIIII(49/llIIIIlllllIIllIIllI)] 
,I/DBG_DM  ( 2903): [com.wssyncmldm.DMSecBroadcastReceiver(572/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,I/DBG_DM  ( 2903): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(503/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,I/ExternalOEMControlProvider( 5770): onCreate
,I/DBG_DM  ( 2903): [IIllIIIIlIlIlIlIllII(49/IIIlIIllIlIIllIlllII)] FirmwareObjectSize:308289685
,I/DBG_DM  ( 2903): [IIllIIIIlIlIlIlIllII(1715/llllllIllIlIlllIIlIl)] 
,I/DBG_DM  ( 2903): [com.wssyncmldm.db.file.XDB(5178/IIIIlIllIlllIlIIIIlI)] Data Margin : 500
,I/GoogleURLConnFactory( 1856): Using platform SSLCertificateSocketFactory
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/comdaemonstockapp( 1314): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
,D/comdaemonstockapp( 1314): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 2903): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Data App Weight : 0.0
,E/Zygote  ( 5826): MountEmulatedStorage(),
E/Zygote  ( 5826): v2
I/libpersona( 5826): KNOX_SDCARD checking this for 1000
I/libpersona( 5826): KNOX_SDCARD not a persona
,I/SELinux ( 5826): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5826): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5826): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.contextagent.ContextAgentReceiver: pid=5826 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/DBG_DM  ( 2903): [com.wssyncmldm.db.file.XDB(5258/llllIIlIlIIIIllIlIIl)] Delta Weight : 0.5
,I/DBG_DM  ( 2903): [com.wssyncmldm.db.file.llllIIIllIlIIIIllllI(194/llIIIIlllllIIllIIllI)] ### Data Margin only: 678432842
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/DBG_DM  ( 2903): [com.wssyncmldm.llIIllllIIlllIIIIlll(1125/handleMessage)] event ->220
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/daemonapp( 1314): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/DBG_DM  ( 2903): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 2903): [com.wssyncmldm.XDMService(712/lllIIIIllIlIlllllllI)] 
,D/TimaKeyStoreProvider( 5826): TimaSignature is unavailable
,D/ActivityThread( 5826): Added TimaKeyStore provider
,I/ Time Manager ( 5770): Time Difference not stored. TIME_DIFFERENCE
,I/DBG_DM  ( 2903): [com.wssyncmldm.db.file.XDB(5018/IIllIIllIIIlllIlIIll)] Get Autoinstall status : false
,I/DBG_DM  ( 2903): [com.wssyncmldm.XDMService(468/lIllIllllIIIlllIlllI)] 
,I/DBG_DM  ( 2903): [llllIIIllIllIlllIIlI(726/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
,E/DBG_DM  ( 2903): [com.wssyncmldm.XDMService(476/lIllIllllIIIlllIlllI)] didn't register
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/DBG_DM  ( 2903): [com.wssyncmldm.XDMService(477/lIllIllllIIIlllIlllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@2ddfd8da
W/ResourcesManager( 5826): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/GamesSyncServiceMain( 2000): Found unexpected GCM tag when scheduling; aborting
,D/ActivityManager( 1013): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/GamesSyncServiceMain( 2000): Failed to execute periodic sync, missing client context - aborting
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,I/FOTA_Client( 5803): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,I/DBG_DM  ( 2903): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,I/FOTA_Client( 5803): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chromesync.sync.SyncService; callingUser = 0; userId(target) = 0
,I/KLMS-2.5.183: ( 3430): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Tue Jan 12 12:01:14 GMT+01:00 2016
,I/DBG_DM  ( 2903): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,I/DBG_DM  ( 2903): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(649/IIIIllIlIIlIIIIlllIl)] nWidgetStatus : 2
,W/ContextImpl( 2903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.wssyncmldm.ui.llllIIIllIlIIIIllllI.IIIIllIlIIlIIIIlllIl:652 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:172 llllIIIllIllIlllIIlI.llIIIIlllllIIllIIllI:732 
,D/ActivityManager( 1013): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1013): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/CheckinService( 2000): Checkin interval check for package: unspecified last checkin: 1452462713190 min interval config: 0 actual interval: 133761227
,I/KLMS-2.5.183: ( 3430): KLMSAbstractReciever(): onReceive().END.
,D/ActivityManager( 1013): getContentProviderImpl callerProcessName:com.android.calendar, calleePkgName: com.android.providers.calendar
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/SecurityLogAgent( 5659): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 5659): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5659): StateMachine : Current State = 1
,E/Zygote  ( 5852): MountEmulatedStorage()
,I/libpersona( 5852): KNOX_SDCARD checking this for 10042
E/Zygote  ( 5852): v2
I/libpersona( 5852): KNOX_SDCARD not a persona
I/SELinux ( 5852): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5852): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 5852): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1013): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5852 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/KLMS-2.5.183: ( 3430): KLMSIntentService(): onCreate()
,D/SettingsProvider( 1013): name = SOFTWARE_UPDATE_NOTIFICATION_STATUS
,I/KLMS-2.5.183: ( 3430): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
,I/SA      ( 5362): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 5852): TimaSignature is unavailable
,D/ActivityThread( 5852): Added TimaKeyStore provider
,I/KLMS-2.5.183: ( 3430): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/DBG_DM  ( 2903): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7,
,E/Zygote  ( 5868): MountEmulatedStorage(),
I/libpersona( 5868): KNOX_SDCARD checking this for 10157
E/Zygote  ( 5868): v2
I/libpersona( 5868): KNOX_SDCARD not a persona
I/SELinux ( 5868): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5868): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5868): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=5868 uid=10157 gids={50157, 9997} abi=armeabi-v7a
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,D/TimaKeyStoreProvider( 5868): TimaSignature is unavailable,
D/ActivityThread( 5868): Added TimaKeyStore provider,
D/accuweather( 1718): [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
I/art     ( 1013): Explicit concurrent mark sweep GC freed 57749(3MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 27MB/41MB, paused 5.283ms total 189.297ms
D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncService; callingUser = 0; userId(target) = 0
,I/art     (  305): Explicit concurrent mark sweep GC freed 8708(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 657us total 44.569ms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 622us total 17.371ms
,D/accuweather( 1718): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 629us total 19.002ms
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
,I/KLMS-2.5.183: ( 3430): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5885): MountEmulatedStorage()
,E/Zygote  ( 5885): v2
I/libpersona( 5885): KNOX_SDCARD checking this for 10085
I/libpersona( 5885): KNOX_SDCARD not a persona
,I/SELinux ( 5885): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5885): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5885): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=5885 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/KLMS-2.5.183: ( 3430): KLMSIntentService(): TIME_CHANGED
,W/ResourcesManager( 5852): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/KLMS-2.5.183: ( 3430): StateImplV2(): dateTimeChanged().START : Tue Jan 12 12:01:14 GMT+01:00 2016
D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.sync.metadata.ContactMetadataSyncService; callingUser = 0; userId(target) = 0
,W/ResourcesManager( 5868): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KLMS-2.5.183: ( 3430): StateImplV2(): dateTimeChanged().END
,D/TimaKeyStoreProvider( 5885): TimaSignature is unavailable
,D/ActivityThread( 5885): Added TimaKeyStore provider
,I/ActivityManager( 1013): Killing 4805:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.metadata.sync.syncadapter.SyncAdapterService; callingUser = 0; userId(target) = 0
,I/KLMS-2.5.183: ( 3430): KLMSIntentService(): onDestroy()
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.qualcomm.timeservice, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 5885): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.,
W/ResourcesManager( 5885): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5885): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5885): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5885): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5885): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,I/ActivityManager( 1013): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=5902 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1013): Killing 5117:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,I/DBG_DM  ( 2903): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0,
E/Zygote  ( 5902): MountEmulatedStorage(),
E/Zygote  ( 5902): v2
I/libpersona( 5902): KNOX_SDCARD checking this for 1000,
I/libpersona( 5902): KNOX_SDCARD not a persona
,I/SELinux ( 5902): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 5902): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5902): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.sec.android.gallery3d, action: android.content.SyncAdapter
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.android.gallery3d/com.sec.android.gallery3d.remote.picasa.PicasaService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5912): MountEmulatedStorage()
,E/Zygote  ( 5912): v2
I/libpersona( 5912): KNOX_SDCARD checking this for 10044
I/CalendarProvider2( 5852): CalendarProvider2.onCreate() called
I/libpersona( 5912): KNOX_SDCARD not a persona,
I/SELinux ( 5912): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1013): Start proc com.sec.android.gallery3d for service com.sec.android.gallery3d/.remote.picasa.PicasaService: pid=5912 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,I/SELinux ( 5912): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5912): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Killing 5129:com.sec.pcw.device/1000 (adj 15): empty #31
,V/GLSActivity( 1856): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ApplicationPolicy( 1013): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/TimaKeyStoreProvider( 5902): TimaSignature is unavailable
D/ActivityThread( 5902): Added TimaKeyStore provider
,I/DBG_DM  ( 2903): [com.wssyncmldm.ui.XUIFotaPostponeActivity(337/llIIIIlllllIIllIIllI)] 
D/WindowManager( 1013): showStatusBarByNotification() mOpenByNotification=false
W/NotificationService( 1013): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ResourcesManager( 1175): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 5912): TimaSignature is unavailable
,D/ActivityThread( 5912): Added TimaKeyStore provider
,I/DBG_DM  ( 2903): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,D/SecContentProvider2( 1013): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1013): mCursor = null
,D/SecContentProvider2( 1013): uri = 15 selection = getToastGravity
,D/SecContentProvider2( 1013): mCursor = null
,D/SecContentProvider2( 1013): uri = 15 selection = getToastGravityXOffset
,D/SecContentProvider2( 1013): mCursor = null
,D/SecContentProvider2( 1013): uri = 15 selection = getToastGravityYOffset
,D/SecContentProvider2( 1013): mCursor = null
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_5117/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_5129/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_10015/pid_4805/cgroup.procs: No such file or directory
,W/ResourcesManager( 5912): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5912): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5912): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5912): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5912): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 5912): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5912): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5912): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/SecContentProvider2( 1013): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1013): mCursor = null
,D/SecContentProvider2( 1013): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1013): mCursor = null
,E/ActivityThread( 2000): Failed to find provider info for com.android.contacts.metadata
,I/DBG_DM  ( 2903): [com.wssyncmldm.db.file.XDB(5457/lllIIIIllIlIlllllllI)] Set Download Postpone status : 8
,I/DBG_DM  ( 2903): [com.wssyncmldm.ui.XUIFotaPostponeActivity(386/llIIIIlllllIIllIIllI)] No idle Postpone
,I/DBG_DM  ( 2903): [com.wssyncmldm.ui.XUIFotaPostponeActivity(474/llIIIIlllllIIllIIllI)] 
,D/TimeService( 5902): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1452596474917
,D/        ( 5902): TimeServiceNative: User Time to be set is 1452596474918
D/QC-time-services( 5902): Lib:time_genoff_operation: pargs->base = 2
,D/QC-time-services( 5902): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 5902): Lib:time_genoff_operation: pargs->ts_val = 1452596474918
,D/QC-time-services(  316): Daemon: Connection accepted:time_genoff
,D/QC-time-services(  316): Daemon:Received base = 2, unit = 1, operation = 0,value = 1452596474918
D/QC-time-services(  316): Daemon:genoff_opr: Base = 2, val = 1452596474918, operation = 0
D/QC-time-services(  316): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS6/13/70 9:7:35
D/QC-time-services(  316): Daemon:Value read from RTC seconds = 16708055000
D/QC-time-services(  316): Daemon:new time 1452596474918 
D/QC-time-services(  316): Daemon: delta 1435888419918 genoff 1435888419918 
,D/QC-time-services(  316): Daemon:genoff_persistent_update: Writing genoff = 1435888419918 to memory
D/QC-time-services(  316): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  316): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services( 5902): Lib:time_genoff_operation: Send to server  passed!!
,D/KnoxNotification( 1175): ----- inflateViews : modified publicViewLocal -----
D/QC-time-services(  316): Updating the TOD offset
D/QC-time-services(  316): Daemon:genoff_persistent_update: Writing genoff = 1435888419918 to memory
D/QC-time-services(  316): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  316): Daemon:time_persistent_memory_opr:Genoff write operation 
,I/PhenotypeConfigurator( 1856): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,D/KnoxNotification( 1175): ----- inflateViews : modified KnoxViewLocal -----
,E/QC-time-services(  316): Daemon:Update to modem bit set
D/QC-time-services(  316): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  316): Daemon: Base = 2, Value being sent to MODEM = 1119923619918
,E/QC-time-services(  316): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,E/QC-time-services(  316): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services( 5902): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,D/PersonaManager( 1175): PersonaID is invalid or persona doesn't exists. : 0
D/PersonaManager( 1175): isKioskContainerExistOnDevice
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
,D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
,D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,D/SyncManager( 1013): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 23440, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager( 1013): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 115607, reason: UserStart
,I/ActivityManager( 1013): Killing 5148:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,D/NearbySource( 5912): Nearby Source Create!
D/NearbyContext( 5912): Nearby Context Create!
,D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/SettingsProvider( 1013): name = next_alarm_formatted
D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 10085
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
,D/ActivityManager( 1013): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,D/PackageManager( 1013): [MSG] MCS_UNBIND
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5912): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource( 5912): Samsung link source created
,D/SecContentProvider2( 1013): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1013): mCursor = null
,D/ContactProvider( 5912): getAllContactInfoList Start
,D/WifiDisplayAdapter( 1013): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1013): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chromesync.sync.SyncService; callingUser = 0; userId(target) = 0
,W/art     ( 5885): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 174.012ms
,W/libprocessgroup( 1013): failed to open /acct/uid_10156/pid_5148/cgroup.procs: No such file or directory
,I/art     ( 1856): Explicit concurrent mark sweep GC freed 47558(2MB) AllocSpace objects, 21(336KB) LOS objects, 40% free, 12MB/21MB, paused 6.513ms total 133.112ms
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1856): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ContactProvider( 5912): getAllContactInfoList End
,I/syncContacts( 5912): thread: 1013, sync time = 137
,I/ActivityManager( 1013): Killing 4864:com.sec.knox.bridge/1000 (adj 15): empty #31
,E/Auth.Api.Credentials( 2000): [CredentialSyncAdapter] Unknown sync event.
,I/ActivityManager( 1013): Killing 4831:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5952): MountEmulatedStorage()
E/Zygote  ( 5952): v2
I/libpersona( 5952): KNOX_SDCARD checking this for 10094
,I/libpersona( 5952): KNOX_SDCARD not a persona
,I/SELinux ( 5952): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5952): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1013): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5952 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
E/SELinux ( 5952): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncService; callingUser = 0; userId(target) = 0
,I/ActivityManager( 1013): Killing 4920:com.android.vending/u0a28 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5952): TimaSignature is unavailable
,D/ActivityThread( 5952): Added TimaKeyStore provider
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_4864/cgroup.procs: No such file or directory
,D/elm:15183( 5952): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:15183( 5952): ELMEngine.ELMEngine( context ).
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,D/elm:15183( 5952): MDMBridge.setEnterpriseBridge()
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15183( 5952): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
,D/elm:15183( 5952): ElmAgentService : onCreate()
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/System.out( 1856): (HTTPLog)-Static: isSBSettingEnabled false
,D/elm:15183( 5952): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,D/elm:15183( 5952): ELMAgentService.listeningToTimeDateChanges( context, intent ).
,D/elm:15183( 5952): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
D/elm:15183( 5952): ModuleBase.ModifySetAlarm()
D/elm:15183( 5952): MDMBridge.getInstance()
D/elm:15183( 5952): MDMBridge.getAllLicenseInfoFromSDK()
,E/Zygote  ( 5970): MountEmulatedStorage(),
E/Zygote  ( 5970): v2
I/libpersona( 5970): KNOX_SDCARD checking this for 10134
I/libpersona( 5970): KNOX_SDCARD not a persona
I/ActivityManager( 1013): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=5970 uid=10134 gids={50134, 9997} abi=armeabi-v7a
I/SELinux ( 5970): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/elm:15183( 5952): ElmAgentService : onDestroy().
,I/ActivityManager( 1013): Killing 5183:com.policydm/1000 (adj 15): empty #31
I/SELinux ( 5970): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5970): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Killing 5198:com.sec.android.app.samsungapps/u0a10 (adj 15): empty #31
,E/ConnectivityChangeReceiver( 2000): Ignoring connectivity change
,D/TimaKeyStoreProvider( 5970): TimaSignature is unavailable
,D/ActivityThread( 5970): Added TimaKeyStore provider
,I/System.out( 1856): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1856): Tagging socket 34 with tag 1000120300000000{268440067,0} for uid -1, pid: 1856, getuid(): 10012
,D/ConnectivityManager( 2000): CallingUid : 10012, CallingPid : 2000
,W/ResourcesManager( 5970): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5970): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/ConnectivityService( 1013): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService( 1013): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1013): apparently satisfied.  currentScore=60
,D/ConnectivityService( 1013): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
D/ConnectivityManager.CallbackHandler( 2000): CM callback handler got msg 524290
,W/libprocessgroup( 1013): failed to open /acct/uid_10032/pid_4831/cgroup.procs: No such file or directory
,I/splitIntent( 1013): Queue : backgroundsplit_0 intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5987): MountEmulatedStorage(),
,I/ActivityManager( 1013): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=5987 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/Zygote  ( 5987): v2
I/libpersona( 5987): KNOX_SDCARD checking this for 1000
,I/libpersona( 5987): KNOX_SDCARD not a persona
,I/SELinux ( 5987): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5987): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5987): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1013): Killing 5226:com.sec.spp.push/u0a35 (adj 15): empty #31
,W/libprocessgroup( 1013): failed to open /acct/uid_10028/pid_4920/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 5987): TimaSignature is unavailable
,D/ActivityThread( 5987): Added TimaKeyStore provider
,I/PCWCLIENTTRACE_LOG( 5987): DEFAULT_LOGON : true
,I/PCWCLIENTTRACE_LOG( 5987): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 5987): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil( 5987): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5987): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5987): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5987): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1013): Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
,I/splitIntent( 1013): finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,D/accuweather( 1718): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/FOTA_Client( 5803): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,I/art     ( 1644): Explicit concurrent mark sweep GC freed 2267(86KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 777us total 35.796ms
E/Zygote  ( 6003): MountEmulatedStorage()
,E/Zygote  ( 6003): v2
I/libpersona( 6003): KNOX_SDCARD checking this for 10111
I/SELinux ( 6003): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 6003): KNOX_SDCARD not a persona
,I/SELinux ( 6003): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6003): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6003 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.sync.FitnessSyncAdapterService; callingUser = 0; userId(target) = 0
,I/FOTA_Client( 5803): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,W/libprocessgroup( 1013): failed to open /acct/uid_10010/pid_5198/cgroup.procs: No such file or directory
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_5183/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_10035/pid_5226/cgroup.procs: No such file or directory
,D/daemonapp( 1314): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 9
,D/TimaKeyStoreProvider( 6003): TimaSignature is unavailable
,D/ActivityThread( 6003): Added TimaKeyStore provider
,D/RCPManagerService( 1013): exchangeData() failure , invalid userId
,D/RCPManagerService( 1013): exchangeData() failure , invalid userId
,I/qtaguid ( 1856): Tagging socket 74 with tag 1000120300000000{268440067,0} for uid -1, pid: 1856, getuid(): 10012
,D/accuweather( 1718): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1718): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1718): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1718): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,I/FOTA_Client( 5803): [IlIlIIllllIllIIIIIll(86/llllIIIllIlIIIIllllI)] Polling time is not vaild
,I/FOTA_Client( 5803): [com.sec.android.fotaclient.FotaUpdaterReceiver(101/onReceive)] Polling time is already passed. Start device init Immediately
,D/accuweather( 1718): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/SecurityLogAgent( 5659): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 5659): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5659): StateMachine : Current State = 1
,D/accuweather( 1718): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/SecurityLogAgent( 5659): StateMachine : Changed Current State = 1
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6020): MountEmulatedStorage(),
E/Zygote  ( 6020): v2
I/libpersona( 6020): KNOX_SDCARD checking this for 10081
I/libpersona( 6020): KNOX_SDCARD not a persona
,I/SELinux ( 6020): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6020): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 6020): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6020 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 6020): TimaSignature is unavailable
,E/Zygote  ( 6032): MountEmulatedStorage(),
E/Zygote  ( 6032): v2
I/libpersona( 6032): KNOX_SDCARD checking this for 10159
I/libpersona( 6032): KNOX_SDCARD not a persona
,I/SELinux ( 6032): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1013): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6032 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6032): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
D/ActivityManager( 1013): startService callerProcessName:com.sec.android.fotaclient, calleePkgName: com.sec.android.fotaclient
W/ActivityManager( 1013): userId = 0, bbcId = -10000
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.android.fotaclient/com.sec.android.fotaclient.FotaUpdateIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.android.fotaclient, destAppInfo.processName = com.sec.android.fotaclient
E/SELinux ( 6032): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/ActivityThread( 6020): Added TimaKeyStore provider
,W/FOTA_Client( 5803): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/FOTA_Client( 5803): [com.sec.android.fotaclient.FotaUpdateIntentService(30/onHandleIntent)] Update State: Start update request
,I/FOTA_Client( 5803): [IIIlIIIIIIlIlllllllI(45/llIIIIlllllIIllIIllI)] Update State: Check condition to decide update type
,I/KLMS-2.5.183: ( 3430): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Jan 12 12:01:15 GMT+01:00 2016
D/ActivityManager( 1013): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/TimaKeyStoreProvider( 6032): TimaSignature is unavailable
,I/FOTA_Client( 5803): [lIllIIIllIIllIIlIllI(143/llIIIIlllllIIllIIllI)] Update State: Checking polling to server
D/ActivityThread( 6032): Added TimaKeyStore provider
,I/KLMS-2.5.183: ( 3430): KLMSAbstractReciever(): onReceive().END.
,I/FOTA_Client( 5803): [lIllIllllIIIlllIlllI(88/llllIIIllIlIIIIllllI)] WiFi Network is connected
,I/KLMS-2.5.183: ( 3430): KLMSIntentService(): onCreate()
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,I/KLMS-2.5.183: ( 3430): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3430): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.183: ( 3430): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.183: ( 3430): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,E/Zygote  ( 6057): MountEmulatedStorage(),
,E/Zygote  ( 6057): v2
I/libpersona( 6057): KNOX_SDCARD checking this for 10034
I/libpersona( 6057): KNOX_SDCARD not a persona
I/SELinux ( 6057): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6057): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1013): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6057 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
E/SELinux ( 6057): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1013): startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
I/FOTA_Client( 5803): [lIIllIIIIIlllIIlllIl(28/llIIIIlllllIIllIIllI)] Request Network Connection
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.183: ( 3430): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/MusicStore( 6003): Database version: 108
,I/FOTA_Client( 5803): [lIllIllllIIIlllIlllI(88/llllIIIllIlIIIIllllI)] WiFi Network is connected
,I/KLMS-2.5.183: ( 3430): StateImplV2(): networkChangeListener().START
,D/TimaKeyStoreProvider( 6057): TimaSignature is unavailable
,D/ActivityThread( 6057): Added TimaKeyStore provider
,I/KLMS-2.5.183: ( 3430): NetworkChangeOperations(): uploadRequestLog().START 
I/FOTA_Client( 5803): [com.sec.android.fota.osp.time.llIIIIlllllIIllIIllI(82/llIIIIlllllIIllIIllI)] Server time is zero
,I/FOTA_Client( 5803): [com.sec.android.fota.osp.time.llIIIIlllllIIllIIllI(111/llllIIIllIlIIIIllllI)] Request ServerTime
,I/FOTA_Client( 5803): [com.sec.android.fota.osp.http.RestClient(264/llIIIIlllllIIllIIllI)] =====================================================================
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.sec.android.gallery3d, action: android.content.SyncAdapter
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.android.gallery3d/com.sec.android.gallery3d.remote.picasa.PicasaService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3430): NetworkChangeOperations(): uploadRequestLog().END 
,I/ActivityManager( 1013): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=6080 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/KLMS-2.5.183: ( 3430): StateImplV2(): networkChangeListener().END
,E/Zygote  ( 6080): MountEmulatedStorage()
E/Zygote  ( 6080): v2
I/libpersona( 6080): KNOX_SDCARD checking this for 10010
I/libpersona( 6080): KNOX_SDCARD not a persona
,I/SELinux ( 6080): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6080): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6080): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.183: ( 3430): KLMSIntentService(): onDestroy()
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/art     (  305): Explicit concurrent mark sweep GC freed 8718(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 732us total 30.581ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 612us total 17.249ms
D/TimaKeyStoreProvider( 6080): TimaSignature is unavailable
D/ActivityThread( 6080): Added TimaKeyStore provider
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 631us total 17.162ms
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/CalendarProvider2( 5852): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,I/FOTA_Client( 5803): [com.sec.android.fota.osp.http.RestClient(276/llIIIIlllllIIllIIllI)] =====================================================================,
,I/art     ( 1013): Explicit concurrent mark sweep GC freed 35340(1590KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/41MB, paused 2.770ms total 180.489ms,
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/PicasaService( 5912): start picasa sync
,D/PicasaService( 5912): end picasa sync
,I/System.out( 5803): Thread-982(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5803): Thread-982(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5803): Thread-982(ApacheHTTPLog):isShipBuild true
I/System.out( 5803): Thread-982(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5803): Thread-982(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  277): uids 10009
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10009
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.policydm, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6101): MountEmulatedStorage(),
,E/Zygote  ( 6101): v2,
I/libpersona( 6101): KNOX_SDCARD checking this for 1000
I/libpersona( 6101): KNOX_SDCARD not a persona
,I/SELinux ( 6101): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1013): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=6101 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1013): Killing 5274:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
I/SELinux ( 6101): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6101): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Killing 5289:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6101): TimaSignature is unavailable
,D/ActivityThread( 6101): Added TimaKeyStore provider
,D/WaitQueueForNetworkActivate( 6080): notifyNetworkActivated,
,W/ResourcesManager( 6003): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6003): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gm, action: android.content.SyncAdapter
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.provider.MailSyncAdapterService; callingUser = 0; userId(target) = 0
,I/System.out( 5803): IntentService[Service[FotaUpdateIntentService]] calls detatch()
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,V/JNIHelp ( 6003): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ContextImpl( 6080): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,E/Zygote  ( 6119): MountEmulatedStorage(),
I/FOTA_Client( 5803): [com.sec.android.fota.osp.time.llIIIIlllllIIllIIllI(139/llllIIIllIlIIIIllllI)] Receive result: success in ServerTime
E/Zygote  ( 6119): v2
I/libpersona( 6119): KNOX_SDCARD checking this for 10101
I/libpersona( 6119): KNOX_SDCARD not a persona
,I/ActivityManager( 1013): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=6119 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6119): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 6119): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6119): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/FOTA_Client( 5803): [com.sec.android.fota.osp.http.RestClient(264/llIIIIlllllIIllIIllI)] =====================================================================
,D/TimaKeyStoreProvider( 6119): TimaSignature is unavailable
,D/ActivityThread( 6119): Added TimaKeyStore provider
,I/DBG_POLICYDM( 6101): [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
,I/DBG_POLICYDM( 6101): [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
I/FOTA_Client( 5803): [com.sec.android.fota.osp.http.RestClient(276/llIIIIlllllIIllIIllI)] =====================================================================
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1013): Do not check CP during LCD off.
,I/System.out( 5803): Thread-982(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5803): Thread-982(ApacheHTTPLog):isShipBuild true
I/System.out( 5803): Thread-982(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5803): Thread-982(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,W/System  ( 6003): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@30acf4ef: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
W/ActivityThread( 6003): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ProviderInstaller( 6003): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6003): GMSCore installation verified
,D/EnterpriseController(  277): uids 10009,
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10009
,I/DBG_POLICYDM( 6101): [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] ,
,E/Zygote  ( 6140): MountEmulatedStorage()
,E/Zygote  ( 6140): v2
I/libpersona( 6140): KNOX_SDCARD checking this for 10104
I/libpersona( 6140): KNOX_SDCARD not a persona
,I/DBG_POLICYDM( 6101): [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,I/SELinux ( 6140): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/DBG_POLICYDM( 6101): [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
,I/SELinux ( 6140): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6140): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/DBG_POLICYDM( 6101): [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
I/ActivityManager( 1013): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6140 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager( 1013): Killing 5305:com.wsomacp/u0a25 (adj 15): empty #31
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/DBG_POLICYDM( 6101): [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,D/TimaKeyStoreProvider( 6140): TimaSignature is unavailable
,D/ActivityThread( 6140): Added TimaKeyStore provider
,W/libprocessgroup( 1013): failed to open /acct/uid_10072/pid_5274/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_10047/pid_5289/cgroup.procs: No such file or directory
,I/ConfigStore( 6003): Config Database version: 1
,W/ResourcesManager( 6140): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/DBG_POLICYDM( 6101): [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,I/DBG_POLICYDM( 6101): [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,I/DBG_POLICYDM( 6101): [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 6101): [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
,W/PhenotypeConfigurator( 1856): Server returned 404
,W/libprocessgroup( 1013): failed to open /acct/uid_10025/pid_5305/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 6101): [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,I/System.out( 5803): IntentService[Service[FotaUpdateIntentService]] calls detatch()
,I/FOTA_Client( 5803): [IIllIIIIlIlIlIlIllII(102/llIIIIlllllIIllIIllI)] result is success
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.cache.DataUpdateListenerCacheService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/SettingsProvider( 1013): name = FOTA_CLIENT_HEARTBEAT_PERIOD,
D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 10009
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
,E/Zygote  ( 6160): MountEmulatedStorage(),
E/Zygote  ( 6160): v2
I/libpersona( 6160): KNOX_SDCARD checking this for 10035,
I/libpersona( 6160): KNOX_SDCARD not a persona
,I/ActivityManager( 1013): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=6160 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6160): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
D/SettingsProvider( 1013): name = FOTA_CLIENT_HEARTBEAT_ADD,
D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 10009
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed,
D/SettingsProvider( 1013): ret = -1
I/ActivityManager( 1013): Killing 5322:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
,I/SELinux ( 6160): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,W/BackupManagerService( 1013): dataChanged but no participant pkg='com.android.providers.settings' uid=10009
,E/SELinux ( 6160): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/DBG_POLICYDM( 6101): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 6101): [com.policydm.XDMApplication(469/isNetworkChanged)] a previous network is 0, current network is 2
,E/DBG_POLICYDM( 6101): [com.policydm.XDMApplication(471/isNetworkChanged)] network changed.... 
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,E/DBG_POLICYDM( 6101): [com.policydm.XDMBroadcastReceiver(240/xdmNotInitSetResume)] DM Not Init
,D/TimaKeyStoreProvider( 6160): TimaSignature is unavailable
,D/ActivityThread( 6160): Added TimaKeyStore provider
,I/FOTA_Client( 5803): [llIllIIlIIIIIIIllllI(191/IllIlIIIIlIIlIIIllIl)] Request NetActionGetPolling
,I/FOTA_Client( 5803): [lIllIIIllIIllIIlIllI(146/llIIIIlllllIIllIIllI)] Receive result: success in NetActionGetPolling
,I/FOTA_Client( 5803): [IIllIIIIlIlIlIlIllII(193/IIIIllIlIIlIIIIlllIl)] Find Firmware version in Version List
,I/FOTA_Client( 5803): [IIIlIIllllllIllIlIII(177/llIIIIlllllIIllIIllI)] Update State: success to check polling
,I/FOTA_Client( 5803): [IlIlIIllllIllIIIIIll(37/llIIIIlllllIIllIIllI)] Calculate next polling time
,D/SettingsProvider( 1013): name = FOTA_CLIENT_POLLING_TIME
,D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
,D/SettingsProvider( 1013): selectionArgs: 10009
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1013): ret = -1
,W/BackupManagerService( 1013): dataChanged but no participant pkg='com.android.providers.settings' uid=10009
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,W/libprocessgroup( 1013): failed to open /acct/uid_10053/pid_5322/cgroup.procs: No such file or directory
,I/FOTA_Client( 5803): [llIllIIIIlllIIlIIllI(238/llIIIIlllllIIllIIllI)] Update State: Initialize polling update
,I/FOTA_Client( 5803): [llIllIIlIIIIIIIllllI(248/IlIlIlIlIlIIlllllIlI)] request Polling
,I/Gmail   ( 6119): getAccountsCursor
,E/SMD     (  287): DCD OFF,
,I/FOTA_Client( 5803): [com.sec.android.fotaclient.FotaUpdateIntentService(36/onHandleIntent)] Update State: Finish update request
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator,
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,W/DriveInitializer( 2000): Awaiting to be initialized
,I/DBG_POLICYDM( 6101): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,W/DriveInitializer( 2000): Background init thread started
,W/GAV2    ( 6119): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6003): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,I/ActivityManager( 1013): Killing 4785:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6003): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 2000): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6003): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,I/DBG_POLICYDM( 6101): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,E/SPPClientService( 6160): ============PushLog. commonIsShipBuild. stop!,
E/SPPClientService( 6160): [PushClientApplication] Push log off : This is Ship build version
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/DBG_POLICYDM( 6101): [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 7
,I/DBG_POLICYDM( 6101): [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 7,
,E/SPPClientService( 6160): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/DBG_POLICYDM( 6101): [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 7
,D/SPPClientService( 6160): PushLog.txt file is not deleted.
D/SPPClientService( 6160): PushLog.txt file is not deleted.
D/SPPClientService( 6160): ============PushLog. stop!
,I/SA      ( 5362): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,I/SA      ( 5362): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 5362): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5362): [SLFUCHKMGR] constructor called
,W/libprocessgroup( 1013): failed to open /acct/uid_10057/pid_4785/cgroup.procs: No such file or directory
,I/dhcpcd  ( 5734): wlan0: sending IPv6 Router Solicitation
,E/dhcpcd  ( 5734): wlan0: sendmsg: Cannot assign requested address
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:2, health:2, present:true, voltage: 4311, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1013): stay LED for charging
D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1013): Plugged
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,W/DriveInitializer( 2000): Background init thread ended
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1400): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1400): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/SA      ( 5362): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 5362): [OR] == isSIMCardReady false ==
,I/SA      ( 5362): [SCU] == networkStateCheck == true
,I/SA      ( 5362): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 5362): isChinaCountryCode : false
I/SA      ( 5362): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 5362): [OR] == networkStateCheck true ==
,V/GLSActivity( 1856): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
,V/HeadsetService( 5518): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5518): Disconnected process message: 10
,W/ActivityManager( 1013): userId = 0, bbcId = -10000,
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
I/SA      ( 5362): [OR] GetMyCountryZoneTask
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
I/SA      ( 5362): [OR] onReceive END
,I/DBG_POLICYDM( 6101): [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
,I/ActivityManager( 1013): Killing 5247:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty #31
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ConnectivityService( 1013): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1013): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,V/DownloadManager( 1225): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityManager.CallbackHandler( 2000): CM callback handler got msg 524295
,D/ConnectivityService( 1013): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityManager.CallbackHandler( 1175): CM callback handler got msg 524295
,I/SurfaceFlinger(  257): id=13 Removed Uoast (8/9)
,I/SurfaceFlinger(  257): id=13 Removed Uoast (-2/9)
,D/ConnectivityManager.CallbackHandler( 1175): CM callback handler got msg 524295
,D/PowerManagerService( 1013): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1013) eventTime = 86024
,D/PowerManagerService( 1013): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1013 (0x0)
D/PowerManagerService( 1013): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1013, ws=WorkSource{10054}) (elapsedTime=3522)
D/ConnectivityManager.CallbackHandler( 2000): CM callback handler got msg 524295
,I/SA      ( 5362): [SRS] prepareGetMyCountryZone
,D/ActivityManager( 1013): startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,D/OpenGLRenderer( 2903): Render dirty regions requested: true
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
E/Gmail   ( 6119): Error finding the version of the Email provider.....
E/Gmail   ( 6119): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6119): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 6119): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1240)
E/Gmail   ( 6119): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 6119): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6119): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6119): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 6119): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6119): We do not support migrating this version of the Email provider.
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/hcjo    ( 6080): AutoUpdateManager:IDLE:execute
,D/ActivityManager( 1013): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,I/DBG_POLICYDM( 6101): [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/WifiDisplayAdapter( 1013): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/DBG_POLICYDM( 6101): [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
,I/DBG_POLICYDM( 6101): [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,I/SurfaceFlinger(  257): id=14 createSurf (1x1),1 flag=4, Uoast
,D/InitializeManagerStateMachine( 6080): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 6080): exit::IDLE
D/InitializeManagerStateMachine( 6080): entry::NETWORK_CHECK
,I/DBG_POLICYDM( 6101): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,D/InitializeManagerStateMachine( 6080): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6080): exit::NETWORK_CHECK
D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/InitializeManagerStateMachine( 6080): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6080): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6080): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6080): entry::SUCCESS
D/hcjo    ( 6080): AutoUpdateManager:INITCHECK:onInitializeSuccess
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,I/DBG_POLICYDM( 6101): [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
,I/DBG_POLICYDM( 6101): [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 6101): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/DBG_POLICYDM( 6101): [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,I/DBG_POLICYDM( 6101): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,I/DBG_POLICYDM( 6101): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,I/DBG_POLICYDM( 6101): [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,D/btif_config_util( 5518): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/DBG_POLICYDM( 6101): [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2016/01/18/12:08:32
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/Babel   ( 6140): MmsConfig: mnc/mcc: 0/0
,I/DBG_POLICYDM( 6101): [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
I/Babel   ( 6140): MmsConfig.loadMmsSettings
I/Babel   ( 6140): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel   ( 6140): MmsConfig.loadFromDatabase
,D/PowerManagerService( 1013): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1013
,D/hcjo    ( 6080): AutoUpdateTriggerManager:IDLE:setInterval:345600000
,I/DBG_POLICYDM( 6101): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2016/01/12/12:01:17
I/DBG_POLICYDM( 6101): [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
,I/DBG_POLICYDM( 6101): [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
,I/DBG_POLICYDM( 6101): [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,I/DBG_POLICYDM( 6101): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
,I/DBG_POLICYDM( 6101): [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
,W/libprocessgroup( 1013): failed to open /acct/uid_10038/pid_5247/cgroup.procs: No such file or directory
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SRIB_DCS( 2903): log_dcs ThreadedRenderer::initialize entered! 
,I/Adreno-EGL( 2903): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 2903): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 2903): Build Date: 04/06/15 Mon
I/Adreno-EGL( 2903): Local Branch: 
I/Adreno-EGL( 2903): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 2903): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 2903):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/OpenGLRenderer( 2903): Initialized EGL, version 1.4
,I/DBG_POLICYDM( 6101): [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
,D/OpenGLRenderer( 2903): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 2903): Enabling debug mode 0
,W/Gmail   ( 6119): Sync started for account: account:61035162
,E/Babel   ( 6140): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 6140): MmsConfig.loadFromResources
,I/Gmail   ( 6119): Observing account changes for notifications
,E/Babel   ( 6140): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 6140): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/SA      ( 5362): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/Gmail   ( 6119): getAccountsCursor
D/hcjo    ( 6080): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 6080): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/InitializeManagerStateMachine( 6080): exit::SUCCESS
D/InitializeManagerStateMachine( 6080): entry::IDLE
,D/SecContentProvider2( 1013): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1013): mCursor = null
,I/SA      ( 5362): [SSP] query invoked
,D/WifiDisplayAdapter( 1013): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.syncadapters.calendar, action: android.content.SyncAdapter
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.syncadapters.calendar/com.google.android.syncadapters.calendar.CalendarSyncAdapterService; callingUser = 0; userId(target) = 0
,I/SA      ( 5362): [TPMU] GetMccFromDB : null
I/SA      ( 5362): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5362): [TPM] isNoProxy(default) : true
,V/GLSActivity( 1856): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/DBG_POLICYDM( 6101): [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
,E/File    ( 5362): fail readDirectory() errno=2
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/AudioService( 1013): getStreamVolume 3 index 0
,E/Zygote  ( 6231): MountEmulatedStorage(),
I/libpersona( 6231): KNOX_SDCARD checking this for 10102
E/Zygote  ( 6231): v2
I/libpersona( 6231): KNOX_SDCARD not a persona,
I/SELinux ( 6231): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/SELinux ( 6231): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6231): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Start proc com.google.android.syncadapters.calendar for service com.google.android.syncadapters.calendar/.CalendarSyncAdapterService: pid=6231 uid=10102 gids={50102, 9997, 3003} abi=armeabi-v7a
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/MediaRouter( 6003): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/DBG_POLICYDM( 6101): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
,I/ActivityManager( 1013): Killing 5164:com.google.android.apps.docs/u0a91 (adj 15): empty #31
,V/MusicLeanback( 6003): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/DBG_POLICYDM( 6101): [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,W/Settings( 6140): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TimaKeyStoreProvider( 6231): TimaSignature is unavailable
,D/ActivityThread( 6231): Added TimaKeyStore provider
,I/iu.SyncManager( 2000): SYNC; picasa accounts
,I/NetworkMonitor( 6003): type=WIFI subType= reason=null isConnected=true
,D/NetworkLogImpl( 2000): Loaded NetworkSpeedPredictor
,I/iu.Environment( 2000): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2000): num queued entries: 0
,I/iu.UploadsManager( 2000): num updated entries: 0
,I/iu.SyncManager( 2000): NEXT; no task
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/SQLiteLog( 6119): (283) recovered 143 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/Babel_StickerModule( 6140): App launched.
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,W/AbstractGoogleClient( 6231): Application name is not set. Call Builder#setApplicationName.
,E/Zygote  ( 6251): MountEmulatedStorage(),
E/Zygote  ( 6251): v2
I/libpersona( 6251): KNOX_SDCARD checking this for 10113
I/libpersona( 6251): KNOX_SDCARD not a persona
,I/SELinux ( 6251): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/SELinux ( 6251): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1013): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6251 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 6251): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.gmsproc.GcmIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 6101): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,D/WifiDisplayAdapter( 1013): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/ActivityManager( 1013): Killing 5402:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
,D/TimaKeyStoreProvider( 6251): TimaSignature is unavailable
,D/ActivityThread( 6251): Added TimaKeyStore provider
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/NetworkMonitor( 6003): type=WIFI subType= reason=null isConnected=true
,V/GLSActivity( 1856): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/QCamera2Factory(  282): getCameraInfo: E, camera_id = 0
,W/QCamera2Factory(  282): getCameraInfo: X
,V/GLSActivity( 1856): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/DBG_POLICYDM( 6101): [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,W/QCamera2Factory(  282): getCameraInfo: E, camera_id = 1
W/QCamera2Factory(  282): getCameraInfo: X
,E/Zygote  ( 6269): MountEmulatedStorage()
E/Zygote  ( 6269): v2
I/libpersona( 6269): KNOX_SDCARD checking this for 10002
I/libpersona( 6269): KNOX_SDCARD not a persona
,I/SELinux ( 6269): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1013): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6269 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6269): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6269): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/VideoCapabilities( 6140): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6140): Unsupported mime audio/evrc
W/AudioCapabilities( 6140): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6140): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 6140): Unsupported mime audio/mpeg-L2
,D/TimaKeyStoreProvider( 6269): TimaSignature is unavailable,
D/ActivityThread( 6269): Added TimaKeyStore provider
,W/AudioCapabilities( 6140): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6140): Unsupported mime audio/x-ima
,W/AudioCapabilities( 6140): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6140): Unsupported mime audio/evrc
,W/libprocessgroup( 1013): failed to open /acct/uid_10091/pid_5164/cgroup.procs: No such file or directory
,W/libprocessgroup( 1013): failed to open /acct/uid_10100/pid_5402/cgroup.procs: No such file or directory
,W/VideoCapabilities( 6140): Unsupported mime video/wvc1
,W/VideoCapabilities( 6140): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6140): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 6140): Unsupported mime video/wvc1
,W/VideoCapabilities( 6140): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6140): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 6140): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 6140): Unsupported mime video/mp43
,W/VideoCapabilities( 6140): Unsupported mime video/sorenson
,I/art     ( 1013): Explicit concurrent mark sweep GC freed 24262(1212KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 2.755ms total 166.755ms
D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GCM     ( 1856): GCM config loaded
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
,W/VideoCapabilities( 6140): Unsupported mime video/mp4v-esdp
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 6003): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6003): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory( 6003): Using the GMSCore's GoogleHttpClient
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/VideoCapabilities( 6140): Unsupported profile 4 for video/mp4v-es
,I/System.out( 1856): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
E/File    ( 6119): fail readDirectory() errno=2
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1856): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1856): Tagging socket 86 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1856, getuid(): 10012
,I/Gmail   ( 6119): notifyAccountChanged
,I/qtaguid ( 1856): Tagging socket 89 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1856, getuid(): 10012
,I/Gmail   ( 6119): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/VacuumService( 1856): Vacuum at: now=1452596478058 tag=VacuumService
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,I/Gmail   ( 6119): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/Gmail   ( 6119): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6119): calculateUnknownSyncRationalesAndPurgeInBackground: running
,E/Zygote  ( 6303): MountEmulatedStorage()
,E/Zygote  ( 6303): v2
I/libpersona( 6303): KNOX_SDCARD checking this for 1000
I/libpersona( 6303): KNOX_SDCARD not a persona,
,I/ActivityManager( 1013): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6303 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 6303): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6303): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6303): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Killing 5438:com.samsung.helphub/1000 (adj 15): empty #31
,V/AlarmManager( 1013): waitForAlarm result :4
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 6303): TimaSignature is unavailable
,D/ActivityThread( 6303): Added TimaKeyStore provider
,E/Zygote  ( 6318): MountEmulatedStorage(),
E/Zygote  ( 6318): v2
I/libpersona( 6318): KNOX_SDCARD checking this for 10028
,I/libpersona( 6318): KNOX_SDCARD not a persona
I/ActivityManager( 1013): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6318 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/SELinux ( 6318): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 6318): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6318): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Killing 4896:com.google.android.apps.plus/u0a120 (adj 15): empty #31
,I/Gmail   ( 6119): notifyAccountChanged
,D/TimaKeyStoreProvider( 6318): TimaSignature is unavailable
,D/ActivityThread( 6318): Added TimaKeyStore provider
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_5438/cgroup.procs: No such file or directory
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6251): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,I/DIAGMON_AGENT( 6303): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,W/ContextImpl( 6251): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6251): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,W/libprocessgroup( 1013): failed to open /acct/uid_10120/pid_4896/cgroup.procs: No such file or directory
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6251): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/Finsky  ( 6318): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.syncadapters.calendar, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
I/DIAGMON_AGENT( 6303): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.syncadapters.calendar, destAppInfo.processName = com.google.android.gms
,I/DIAGMON_AGENT( 6303): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 6303): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6303): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6303): ./extraInfo: "NG700"
,I/DIAGMON_AGENT( 6303): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1856): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 6119): getAccountsCursor
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1856): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1644): Explicit concurrent mark sweep GC freed 2905(114KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/9MB, paused 735us total 50.297ms
,D/Finsky  ( 6318): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/Gmail   ( 6119): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 14343, normalSync: true
,W/Settings( 6318): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6318): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/WebViewFactory( 6251): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,I/LibraryLoader( 6251): Time to load native libraries: 2 ms (timestamps 7684-7686)
,I/LibraryLoader( 6251): Expected native library version number "",actual native library version number ""
,I/System.out( 1856): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1856): Tagging socket 86 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1856, getuid(): 10012
,D/Finsky  ( 6318): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6318): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 6318): Skipping gmscore version check
,V/WebViewChromiumFactoryProvider( 6251): Binding Chromium to main looper Looper (main, tid 1) {2f10a932}
,I/LibraryLoader( 6251): Expected native library version number "",actual native library version number ""
I/chromium( 6251): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,D/Finsky  ( 6318): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/ActivityManager( 1013): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,I/BrowserStartupController( 6251): Initializing chromium process, singleProcess=true
,D/Finsky  ( 6318): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/art     ( 6251): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
E/SysUtils( 6251): ApplicationContext is null in ApplicationStatus
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,W/chromium( 6251): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 6251): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
I/chromium( 6251): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,I/Adreno-EGL( 6251): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6251): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6251): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6251): Local Branch: 
I/Adreno-EGL( 6251): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6251): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6251):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/ResourcesManager( 6119): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6119): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/NSApplication( 6251): Starting up...
,W/AudioManagerAndroid( 6251): Requires BLUETOOTH permission
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6400): MountEmulatedStorage(),
I/ActivityManager( 1013): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6400 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 6400): v2
,I/libpersona( 6400): KNOX_SDCARD checking this for 10120
I/libpersona( 6400): KNOX_SDCARD not a persona
,I/SELinux ( 6400): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 6400): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6400): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,V/JNIHelp ( 6119): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager( 1013): Killing 5706:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,I/ActivityManager( 1013): Killing 5688:com.samsung.android.app.FileShareClient/u0a68 (adj 15): empty #32
,D/TimaKeyStoreProvider( 6400): TimaSignature is unavailable
,D/ActivityThread( 6400): Added TimaKeyStore provider
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityThread( 6119): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6119): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@35c4a892: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6119): Installed default security provider GmsCore_OpenSSL
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,W/libprocessgroup( 1013): failed to open /acct/uid_10069/pid_5706/cgroup.procs: No such file or directory
,W/libprocessgroup( 1013): failed to open /acct/uid_10068/pid_5688/cgroup.procs: No such file or directory
,W/ResourcesManager( 6400): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/GLSActivity( 1856): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SA      ( 5362): [RC New] Execute method=[GET] start
,I/SA      ( 5362): [RC New] Security=[true]
,I/System.out( 5362): Thread-915(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out( 5362): Thread-915(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5362): Thread-915(ApacheHTTPLog):isShipBuild true
I/System.out( 5362): Thread-915(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5362): Thread-915(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  277): uids 10041
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10041
,I/ActivityManager( 1013): Killing 5555:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,I/System.out( 6231): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 6231): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 6231): (HTTPLog)-Static: isShipBuild true
I/System.out( 6231): (HTTPLog)-Thread-1076-731477748: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 6231): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10102
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10102
,D/AndroidHttpClient( 6119): [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Android-GmailProvider/52000999 (sw360dp; 320dpi) (a5ulte LRX22G); gzip
D/AndroidHttpClient( 6119): [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = POST
,I/System.out( 6119): Thread-1075(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6119): Thread-1075(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 6119): Thread-1075(ApacheHTTPLog):isShipBuild true
I/System.out( 6119): Thread-1075(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6119): Thread-1075(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  277): uids 10101
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10101
,I/qtaguid ( 6119): Tagging socket 59 with tag 1010000000000000{269484032,0} for uid -1, pid: 6119, getuid(): 10101
,I/System.out( 6231): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 6231): Tagging socket 28 with tag 1100000000000000{285212672,0} for uid -1, pid: 6231, getuid(): 10102
,I/qtaguid ( 6119): Tagging socket 63 with tag 1010000000000000{269484032,0} for uid -1, pid: 6119, getuid(): 10101
,W/libprocessgroup( 1013): failed to open /acct/uid_10003/pid_5555/cgroup.procs: No such file or directory
,D/Finsky  ( 6318): [1115] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6318): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ActivityManager( 1013): Killing 5587:com.google.android.apps.maps/u0a107 (adj 15): empty #31
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6428): MountEmulatedStorage()
E/Zygote  ( 6428): v2
I/libpersona( 6428): KNOX_SDCARD checking this for 10125
I/libpersona( 6428): KNOX_SDCARD not a persona
,I/SELinux ( 6428): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1013): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6428 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager( 1013): Killing 5770:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
,I/SELinux ( 6428): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6428): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/qtaguid ( 6231): Untagging socket 28
,I/art     (  305): Explicit concurrent mark sweep GC freed 8717(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 638us total 34.692ms
,D/TimaKeyStoreProvider( 6428): TimaSignature is unavailable
,D/ActivityThread( 6428): Added TimaKeyStore provider
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 637us total 25.585ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 602us total 16.913ms
,W/ResourcesManager( 6428): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6428): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6428): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/ActivityManager( 1013): Waited long enough for: ServiceRecord{2ef21027 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,D/QuickConnect( 6428): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6428): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 6428): PeriphStartReceiver.onReceive - no need to start
,I/splitIntent( 1013): Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1013): Killing 5826:com.samsung.android.sm/1000 (adj 15): empty #31
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1013): failed to open /acct/uid_10107/pid_5587/cgroup.procs: No such file or directory
,W/libprocessgroup( 1013): failed to open /acct/uid_10062/pid_5770/cgroup.procs: No such file or directory
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1013): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1013): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/CalendarSyncAdapter( 6231): Found 0 events marked dirty & lastSynced
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
E/SMD     (  287): DCD OFF
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.android.fotaclient, destAppInfo.processName = com.wssyncmldm
,I/ActivityManager( 1013): Killing 5868:com.sec.android.app.taskmanager/u0a157 (adj 15): empty #31
,I/DBG_DM  ( 2903): [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_5826/cgroup.procs: No such file or directory
,I/DBG_DM  ( 2903): [llIIIllllIIIlIIIlIIl(1846/llIlIIIIlIIIIIlIlIII)] flag is : false
,I/SA      ( 5362): [RC New] [v2liruge] api execute + 657
I/SA      ( 5362): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out( 5362): AsyncTask #1 calls detatch()
,I/ActivityManager( 1013): Killing 5097:com.android.mms/u0a46 (adj 15): empty #31
,I/SA      ( 5362): [ODM] saveOpenData( GEO_IP, PL )
,I/DBG_DM  ( 2903): [com.wssyncmldm.DMSecBroadcastReceiver(192/onReceive)] sec.fota.polling.intent.RECEIVE
,I/SA      ( 5362): [OCP] update openData : PL
,I/DBG_DM  ( 2903): [com.wssyncmldm.DMSecBroadcastReceiver(543/llIIIIlllllIIllIIllI)] nMode : 0
,I/SA      ( 5362): [TPMU] getNetworkMcc : 
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.metadata.sync.syncadapter.SyncAdapterService; callingUser = 0; userId(target) = 0
,I/SA      ( 5362): [SCU] saveMccToPreferece Start
I/SA      ( 5362): [SCU] RegionMCC : 260
I/SA      ( 5362): [SSP] query invoked
,I/DBG_DM  ( 2903): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/SA      ( 5362): [TPMU] GetMccFromDB : null
I/SA      ( 5362): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5362): [SCU] saveMccToPreferece End
,I/SA      ( 5362): [RC New] executeRequest [v2liruge] end. 726
I/SA      ( 5362): [RC New] Execute end
,I/SA      ( 5362): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 5362): [OR] GetMyCountryZoneTask Success
,I/DBG_DM  ( 2903): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 8
,I/DBG_DM  ( 2903): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/DBG_DM  ( 2903): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(226/llIIIIlllllIIllIIllI)] 
,I/DBG_DM  ( 2903): [com.wssyncmldm.db.file.XDB(3800/IllIIlllIllIIIIIllII)] Wifi_Only_flag : true
,I/DBG_DM  ( 2903): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 2903): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(251/llIIIIlllllIIllIIllI)] bWifiOnly flag : true
,I/DBG_DM  ( 2903): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/DBG_DM  ( 2903): [llIIIllllIIIlIIIlIIl(1846/llIlIIIIlIIIIIlIlIII)] flag is : false
,I/DBG_DM  ( 2903): [IIllIIIIlIlIlIlIllII(1756/lllllIIlIIIlIlIIIllI)] bUpdateProcessing : false
,I/DBG_DM  ( 2903): [llllIIIllIllIlllIIlI(772/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
,I/DBG_DM  ( 2903): [llllIlllIIIlIlIlIIII(49/llIIIIlllllIIllIIllI)] 
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,I/DBG_DM  ( 2903): [IIllIIIIlIlIlIlIllII(49/IIIlIIllIlIIllIlllII)] FirmwareObjectSize:308289685
,D/ActivityManager( 1013): startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,I/DBG_DM  ( 2903): [IIllIIIIlIlIlIlIllII(1715/llllllIllIlIlllIIlIl)] 
,D/CountryDetector( 1013): No listener is left
,I/DBG_DM  ( 2903): [com.wssyncmldm.db.file.XDB(5178/IIIIlIllIlllIlIIIIlI)] Data Margin : 500
,I/DBG_DM  ( 2903): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Data App Weight : 0.0
,I/DBG_DM  ( 2903): [com.wssyncmldm.db.file.XDB(5258/llllIIlIlIIIIllIlIIl)] Delta Weight : 0.5
,I/DBG_DM  ( 2903): [com.wssyncmldm.db.file.llllIIIllIlIIIIllllI(194/llIIIIlllllIIllIIllI)] ### Data Margin only: 678432842
,I/DBG_DM  ( 2903): [com.wssyncmldm.llIIllllIIlllIIIIlll(1125/handleMessage)] event ->220
,I/DBG_DM  ( 2903): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 2903): [com.wssyncmldm.XDMService(712/lllIIIIllIlIlllllllI)] 
,I/DBG_DM  ( 2903): [com.wssyncmldm.db.file.XDB(5018/IIllIIllIIIlllIlIIll)] Get Autoinstall status : false
,I/DBG_DM  ( 2903): [llllIIIllIllIlllIIlI(726/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
I/DBG_DM  ( 2903): [com.wssyncmldm.XDMService(468/lIllIllllIIIlllIlllI)] 
,E/DBG_DM  ( 2903): [com.wssyncmldm.XDMService(476/lIllIllllIIIlllIlllI)] didn't register
,E/DBG_DM  ( 2903): [com.wssyncmldm.XDMService(477/lIllIllllIIIlllIlllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@2ddfd8da
,I/DBG_DM  ( 2903): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,I/DBG_DM  ( 2903): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,I/DBG_DM  ( 2903): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,D/GCM     ( 1856): GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
,W/libprocessgroup( 1013): failed to open /acct/uid_10157/pid_5868/cgroup.procs: No such file or directory
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/libprocessgroup( 1013): failed to open /acct/uid_10046/pid_5097/cgroup.procs: No such file or directory
,I/DBG_DM  ( 2903): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,D/ApplicationPolicy( 1013): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,I/DBG_DM  ( 2903): [com.wssyncmldm.ui.XUIFotaPostponeActivity(337/llIIIIlllllIIllIIllI)] 
,W/NotificationService( 1013): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/SecContentProvider2( 1013): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1013): mCursor = null
,D/SecContentProvider2( 1013): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1013): mCursor = null
,I/DBG_DM  ( 2903): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,D/StatusBar( 1175): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
,D/PanelView( 1175): There is/are notification(s) 
,D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
,D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.apps.plus, action: android.content.SyncAdapter
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.EsSyncAdapterService; callingUser = 0; userId(target) = 0
,I/DBG_DM  ( 2903): [com.wssyncmldm.db.file.XDB(5457/lllIIIIllIlIlllllllI)] Set Download Postpone status : 8
,I/DBG_DM  ( 2903): [com.wssyncmldm.ui.XUIFotaPostponeActivity(386/llIIIIlllllIIllIIllI)] No idle Postpone
,I/DBG_DM  ( 2903): [com.wssyncmldm.ui.XUIFotaPostponeActivity(474/llIIIIlllllIIllIIllI)] 
,D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,I/art     ( 1013): Explicit concurrent mark sweep GC freed 30193(1424KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 2.771ms total 157.630ms
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,I/System.out( 1856): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1856): Tagging socket 86 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1856, getuid(): 10012
,I/qtaguid ( 6119): Untagging socket 59
,I/System.out( 6119): SyncAdapterThread-1 calls detatch()
,I/DBG_POLICYDM( 6101): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,I/DBG_POLICYDM( 6101): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,V/GLSActivity( 1856): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/DBG_POLICYDM( 6101): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 6101): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 6101): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 6101): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 6101): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_POLICYDM( 6101): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,E/DBG_POLICYDM( 6101): [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,I/DBG_POLICYDM( 6101): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,W/art     ( 6400): Attempt to remove local handle scope entry from IRT, ignoring
,D/EnterpriseController(  277): uids 10120
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10120
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5987): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5987): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5987): [GetString-S]
,I/ReactiveServiceManager( 5987): Supported : 1
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/QSEECOMAPI: ( 1013): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1013): App is not loaded in QSEE
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/QSEECOMAPI: ( 1013): Loaded image: APP id = 10
,D/QSEECOMAPI: ( 1013): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 1013): QSEECom_shutdown_app, app_id = 10
,E/terrier ( 1013): handleString: Failed to handle string(-4)
E/terrier ( 1013): Java_com_android_server_ReactiveService_GetString: error code = [-4]
,D/PCWCLIENTTRACE_SecurePreferencesJNI( 5987): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5987): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5987): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5987): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5987): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 5987): [ensureRegistration] - No Samsung account
,I/art     ( 6119): Explicit concurrent mark sweep GC freed 11248(400KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 10MB/13MB, paused 975us total 62.606ms
,I/Gmail   ( 6119): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 14565, normalSync: true
,I/Gmail   ( 6119): lowestBackward conversation id 0
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/dhcpcd  ( 5734): wlan0: sending IPv6 Router Solicitation
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 2000): Explicit concurrent mark sweep GC freed 15920(1192KB) AllocSpace objects, 27(432KB) LOS objects, 39% free, 14MB/23MB, paused 1.283ms total 67.387ms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Gmail   ( 6119): notifyAccountChanged
,I/Gmail   ( 6119): getAccountsCursor
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,I/Gmail   ( 6119): notifyAccountChanged
,V/GLSActivity( 1856): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Gmail   ( 6119): Sync complete for account: account:61035162
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.subscribedfeeds.SyncService; callingUser = 0; userId(target) = 0
,I/Gmail   ( 6119): getAccountsCursor
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1856): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GoogleURLConnFactory( 2000): Using platform SSLCertificateSocketFactory
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1856): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 2000): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 2000): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 2000): (HTTPLog)-Static: isShipBuild true
,I/System.out( 2000): (HTTPLog)-Thread-307-288417201: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 2000): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
,I/System.out( 2000): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 2000): Tagging socket 108 with tag 1000210100000000{268443905,0} for uid -1, pid: 2000, getuid(): 10012
,I/qtaguid ( 2000): Tagging socket 113 with tag 1000210100000000{268443905,0} for uid -1, pid: 2000, getuid(): 10012
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.ReportingSyncService; callingUser = 0; userId(target) = 0
,I/GCoreUlr( 1856): Uploading GCM registration ID for account#2#
,W/BaseAppContext( 1856): Using Auth Proxy for data requests.
,E/BaseAppContext( 1856): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,I/System.out( 1856): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1856): Tagging socket 86 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1856, getuid(): 10012
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000,
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/GAV2    ( 6119): Thread[GAThread,5,main]: No campaign data found.
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.appcert.AppCertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1856): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
,I/System.out( 1856): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 1856): Tagging socket 91 with tag 1000060200000000{268436994,0} for uid 10012, pid: 1856, getuid(): 10012
,I/qtaguid ( 1856): Tagging socket 94 with tag 1000060200000000{268436994,0} for uid 10012, pid: 1856, getuid(): 10012
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/Icing   ( 2000): Indexing CCCF2610294B0D8C53498F9681259C2D89058ED7 from com.google.android.gm
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1856): callingUid 10012, callindPid: 1856
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/Gmail   ( 6119): Backfilling search sequence table
,E/GmsUtils( 6003): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,E/GmsUtils( 6003): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,W/Icing   ( 2000): Content incarnation mismatch: Expected [8d92969ef99d3d25] found [e6777b1968bf16b9]
,I/Icing   ( 2000): Indexing done CCCF2610294B0D8C53498F9681259C2D89058ED7
E/Icing   ( 2000): Aborting indexing of corpus messages/com.google/thalitester%40gmail.com
,I/Icing   ( 2000): Removing corpus key CCCF2610294B0D8C53498F9681259C2D89058ED7 for package com.google.android.gm
,I/MusicLeanback( 6003): Conditions not met for autocaching.
,I/MusicLeanback( 6003): Stop autocaching.
,I/jxcore-log( 5426): Test app app.js loaded,
I/jxcore-log( 5426): 
,I/qtaguid ( 1856): Untagging socket 91
,I/chromium( 5426): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/GCoreUlr( 1856): GCM ID uploaded for account#2#
I/GCoreUlr( 1856): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.DispatchingService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/GCoreUlr( 1856): DispatchingService.onCreate()
D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chromesync.sync.SyncService; callingUser = 0; userId(target) = 0
,I/qtaguid ( 2000): Untagging socket 108
,I/GCoreUlr( 1856): DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1856): Unbound from all location providers
I/GCoreUlr( 1856): Place inference reporting - stopped
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.apps.magazines, action: android.content.SyncAdapter
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.service.SyncAdapterService; callingUser = 0; userId(target) = 0
,I/GCoreUlr( 1856): DispatchingService.onDestroy()
,I/GCoreUlr( 1856): Stopping handler for UlrDispSvcFast
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.syncadapters.contacts, action: android.content.SyncAdapter
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.syncadapters.contacts/com.google.android.syncadapters.contacts.ContactsSyncAdapterService; callingUser = 0; userId(target) = 0
,I/GCoreUlr( 1856): Unbound from all location providers
,I/GCoreUlr( 1856): Place inference reporting - stopped
,I/SyncAdapterService( 6251): Ignoring sync request for non-current account
,I/Icing   ( 2000): Indexing CCCF2610294B0D8C53498F9681259C2D89058ED7 from com.google.android.gm
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1856): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Icing   ( 2000): Indexing done CCCF2610294B0D8C53498F9681259C2D89058ED7
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.plus.service.OfflineActionSyncAdapterService; callingUser = 0; userId(target) = 0
,D/AndroidHttpClient( 1644): [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Android-GData-Contacts/1.3 (a5ulte LRX22G); gzip
D/AndroidHttpClient( 1644): [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,I/System.out( 1644): Thread-143(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 1644): Thread-143(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 1644): Thread-143(ApacheHTTPLog):isShipBuild true
I/System.out( 1644): Thread-143(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 1644): Thread-143(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
,I/qtaguid ( 1644): Tagging socket 36 with tag 1244000400000000{306446340,0} for uid -1, pid: 1644, getuid(): 10012
,I/qtaguid ( 1644): Tagging socket 41 with tag 1244000400000000{306446340,0} for uid -1, pid: 1644, getuid(): 10012
,W/BaseAppContext( 2000): Using Auth Proxy for data requests.
,W/BaseAppContext( 2000): Using Auth Proxy for data requests.
,W/BaseAppContext( 2000): Using Auth Proxy for data requests.
,W/BaseAppContext( 2000): Using Auth Proxy for data requests.
,W/BaseAppContext( 2000): Using Auth Proxy for data requests.
,W/BaseAppContext( 2000): Using Auth Proxy for data requests.
,W/BaseAppContext( 2000): Using Auth Proxy for data requests.
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.music, action: android.content.SyncAdapter
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.sync.SyncAdapterService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 6003): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6003): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory( 6003): Using the GMSCore's GoogleHttpClient
,I/qtaguid ( 1644): Untagging socket 36
,I/System.out( 1644): GDataFeedFetcher calls detatch()
,I/art     ( 1644): Explicit concurrent mark sweep GC freed 17901(846KB) AllocSpace objects, 2(55KB) LOS objects, 25% free, 7MB/10MB, paused 793us total 28.527ms
,D/ContactProvider( 5912): getAllContactInfoList Start
,D/AndroidHttpClient( 1644): [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Android-GData-Contacts/1.3 (a5ulte LRX22G); gzip
,D/AndroidHttpClient( 1644): [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
I/System.out( 1644): Thread-145(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 1644): Thread-145(ApacheHTTPLog):isShipBuild true
I/System.out( 1644): Thread-145(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 1644): Thread-145(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 1644): Tagging socket 36 with tag 1144000400000000{289669124,0} for uid -1, pid: 1644, getuid(): 10012
,D/ContactProvider( 5912): getAllContactInfoList End
,I/syncContacts( 5912): thread: 1019, onChange
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,E/SMD     (  287): DCD OFF
I/qtaguid ( 1644): Untagging socket 36
I/System.out( 1644): GDataFeedFetcher calls detatch()
,V/GLSActivity( 1856): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ContactProvider( 5912): getAllContactInfoList Start
,I/System.out( 6003): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 6003): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 6003): (HTTPLog)-Static: isShipBuild true
I/System.out( 6003): (HTTPLog)-Thread-1051-52592207: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 6003): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10111
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10111
,E/SQLiteLog( 1682): (284) automatic index on sqlite_sq_B8DB2568(STAT_DATA_ID)
,E/SQLiteLog( 1682): (284) automatic index on sqlite_sq_B8DB4AE8(STAT_DATA_ID)
,I/System.out( 6003): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/ContactProvider( 5912): getAllContactInfoList End
I/syncContacts( 5912): thread: 1020, onChange
,I/art     ( 1013): Explicit concurrent mark sweep GC freed 34448(1556KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/41MB, paused 2.489ms total 150.650ms
,E/SQLiteLog( 1682): (284) automatic index on sqlite_sq_B8DCEBF8(STAT_DATA_ID)
,E/SQLiteLog( 1682): (284) automatic index on sqlite_sq_B8DD0BA8(STAT_DATA_ID)
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1856): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Auth.Api.Credentials( 2000): [CredentialSyncAdapter] Unknown sync event.
,I/System.out( 6003): (HTTPLog)-Static: isSBSettingEnabled false
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.apps.plus, action: android.content.SyncAdapter
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.libraries.social.autobackup.AutoBackupSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/GAV4    ( 6251): Thread[GAThread,5,main]: No campaign data found.
,W/MusicApiClient( 6003): No content in 'data' field in GET sync response for Track
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.android.vending
,I/MusicSyncAdapter( 6003): Will attempt periodic sync for account: Account {name=thalitester@gmail.com, type=com.google}
I/MusicSyncAdapter( 6003): Periodic update
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.KeepOnUpdater$SyncListener; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.apps.plus, action: android.content.SyncAdapter
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.photos.service.GooglePhotoDownsyncService; callingUser = 0; userId(target) = 0
,W/ContextImpl( 6003): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/File    ( 6003): fail readDirectory() errno=2
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6003): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/cache
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.keepon.KeeponSchedulingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.sync.RemindersSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/MusicLeanback( 6003): Conditions not met for autocaching.
,I/MusicLeanback( 6003): Stop autocaching.
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.sync.FitnessSyncAdapterService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6003): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/cache
,E/GmsUtils( 6003): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,E/GmsUtils( 6003): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,I/RemindersSync( 2000): Found sync condition that we don't recognize, aborting. [T SyncAdapterThread-1:id=314:priority=5:group=main]
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.apps.plus, action: android.content.SyncAdapter
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.EsSyncAdapterService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.apps.plus, action: android.content.SyncAdapter
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.libraries.social.autobackup.AutoBackupSyncService; callingUser = 0; userId(target) = 0
,I/SurfaceFlinger(  257): id=14 Removed Uoast (8/9)
,I/SurfaceFlinger(  257): id=14 Removed Uoast (-2/9)
,D/PowerManagerService( 1013): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1013) eventTime = 92532
,D/PowerManagerService( 1013): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1013 (0x0)
D/PowerManagerService( 1013): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1013, ws=WorkSource{1000}) (elapsedTime=6412)
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.syncadapters.calendar, action: android.content.SyncAdapter
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.syncadapters.calendar/com.google.android.syncadapters.calendar.CalendarSyncAdapterService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.syncadapters.calendar, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.syncadapters.calendar, destAppInfo.processName = com.google.android.gms
,I/System.out( 6231): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 6231): Tagging socket 28 with tag 1000000400000000{268435460,0} for uid -1, pid: 6231, getuid(): 10102
,I/qtaguid ( 6231): Tagging socket 32 with tag 1000000400000000{268435460,0} for uid -1, pid: 6231, getuid(): 10102
,V/CalendarSyncAdapter( 6231): Saving inProgress state: {calendarId=thalitester@gmail.com, maxAttendees=50, maxResults=200, timeMax=2017-01-24T00:00:00.000Z, updatedMin=2015-11-18T16:31:02.459Z}
,I/qtaguid ( 6231): Untagging socket 28
,D/SSRM:n  ( 1013): SIOP:: AP = 330
,D/CalendarSyncAdapter( 6231): Found 0 events marked dirty & lastSynced
,I/ActivityManager( 1013): Killing 5885:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
,W/libprocessgroup( 1013): failed to open /acct/uid_10085/pid_5885/cgroup.procs: No such file or directory
,I/dhcpcd  ( 5734): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 5734): wlan0: no IPv6 Routers available
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:2, health:2, present:true, voltage: 4345, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for charging
D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1013): Plugged
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1400): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1400): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5518): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5518): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/ActivityManager( 1013): startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.preloadupdate.PreloadUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 6080): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 6080): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6080): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6080): AutoUpdateTriggerManager:REQUEST2:requestInterval
,I/Volley  ( 6080): RestApi Request Add : 2307
,E/File    ( 6080): fail readDirectory() errno=2
,I/System.out( 6080): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 6080): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 6080): (HTTPLog)-Static: isShipBuild true
I/System.out( 6080): (HTTPLog)-Thread-1056-392960800: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 6080): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10010
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10010
,I/System.out( 6080): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 6080): Tagging socket 26 with tag 79a327ee00000000{2040735726,0} for uid -1, pid: 6080, getuid(): 10010
,I/qtaguid ( 6080): Untagging socket 26
,D/hcjo    ( 6080): AutoUpdateTriggerManager:REQUEST2:setInterval:86400000
,D/hcjo    ( 6080): AutoUpdateTriggerManager:REQUEST2:notifyTimedOutAndWriteUpdateCheckedTime,
,D/PreloadUpdateManagerStateMachine( 6080): execute::CHECK_TIMEOUT_FOR_UPDATE:TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 6080): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6080): entry::REQ_UPDATE_CHECK
,I/Volley  ( 6080): RestApi Request Add : 2315
,I/System.out( 6080): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 6080): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 6080): Tagging socket 28 with tag 79a327ee00000000{2040735726,0} for uid -1, pid: 6080, getuid(): 10010
,I/qtaguid ( 6080): Untagging socket -1
,I/qtaguid ( 6080): Failed write_ctrl(u -1) res=-1 errno=9
I/qtaguid ( 6080): Untagging socket -1 failed errno=-9
W/NetworkManagementSocketTagger( 6080): untagSocket(-1) failed with errno -9
,D/PreloadUpdateManagerStateMachine( 6080): execute::REQ_UPDATE_CHECK:REQUEST_SUCCESS
D/PreloadUpdateManagerStateMachine( 6080): exit::REQ_UPDATE_CHECK
D/PreloadUpdateManagerStateMachine( 6080): entry::NOTIFY_NOTIFICATION
D/PreloadUpdateManagerStateMachine( 6080): exit::NOTIFY_NOTIFICATION
D/PreloadUpdateManagerStateMachine( 6080): entry::FINISH
,D/PreloadUpdateManagerStateMachine( 6080): exit::FINISH
D/PreloadUpdateManagerStateMachine( 6080): entry::IDLE
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 300
,I/PowerManagerService( 1013): [PWL] Off : 50s ago
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1013): Do not check CP during LCD off.
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1013): !@Sync 3
,D/FactoryTest( 4697): Not factory mode
D/FactoryTest( 4697): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 4697): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 4697): still no open session command from host, so toast
,W/ContextImpl( 4697): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 4697): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,I/Timeline( 4697): Timeline: Activity_launch_request id:com.android.settings time:108189
,E/PersonaManagerService( 1013): inState():  stateMachine is null !!
,I/PersonaManagerService( 1013): PersonaId don't exist
I/ActivityManager( 1013): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.android.settings,
,W/ActivityManager( 1013): userId = 0, bbcId = -10000,
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1013): mDVFSHelper.acquire()
,D/PersonaManager( 1013): isKioskContainerExistOnDevice
,V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/InputDispatcher( 1013): Focused application set to: xxxx
D/InputDispatcher( 1013): Focus left window: 5426
,E/MTPRx   ( 4697): started activity for popup
,D/PointerIcon( 1013): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1013): setMouseCustomIcon IconType is same.101
,W/ResourcesManager( 4697): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 4697): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4697): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4697): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4697): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4697): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 4697): PREF_DONT_ASK_AGAIN : true
,V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,D/InputDispatcher( 1013): Focused application set to: xxxx
,D/InputDispatcher( 1013): Focus entered window: 5426
,D/PointerIcon( 1013): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
D/PointerIcon( 1013): setMouseCustomIcon IconType is same.101
,D/InputMethodManagerService( 1013): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/InputMethodManagerService( 1013): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@370469e5 attribute=null, token = android.os.BinderProxy@32ce6348,
,D/SettingsReceiverActivity( 4697): dev.kiessupport is : TRUE
,D/PhoneWindow( 4697): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 4697): *FMB* installDecor flags : 8388610
,D/ActivityManager( 1013): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1013): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1013): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1013): handleActiveUserChange for user 0
D/PersonaManagerService( 1013): getPersonasForUser(): returning null!
,I/Timeline( 5426): Timeline: Activity_idle id: android.os.BinderProxy@3098533b time:108370
,V/ActivityThread( 5426): updateVisibility : ActivityRecord{5bdb7b1 token=android.os.BinderProxy@3098533b {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PersonaManager( 1013): isKioskContainerExistOnDevice
,I/Atfwd_Sendcmd(  314): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  314): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  287): DCD OFF
,W/ActivityManager( 1013): mDVFSHelper.release()
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 290
,V/AlarmManager( 1013): waitForAlarm result :4
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/LightsService( 1013): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1013) 
,E/lights  ( 1013): write_int failed to open -1
,D/LightsService( 1013): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=3) set On
D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1013): turn on LED for fully charged,
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate,
D/LightsService( 1013): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
D/LightsService( 1013): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1013): Plugged
,I/MotionRecognitionService( 1013): mGripSensorEnabled= false,
,V/EmergencyMode( 1400): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1400): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/SecContentProvider2( 1013): uri = 14 selection = getSealedState,
D/SecContentProvider2( 1013): mCursor = null
,V/HeadsetService( 5518): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5518): Disconnected process message: 10
,D/ApplicationPolicy( 1013): isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = -1
,V/ApplicationPolicy( 1013): isApplicationStateBlocked userId -1 pkgname com.android.systemui
,I/ValidateNoPeople( 1013): skipping global notification
D/WindowManager( 1013): showStatusBarByNotification() mOpenByNotification=false
,D/PowerManagerService( 1013): [api] acquire WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1175
I/PowerManagerService( 1013): !@[ps] Screen__On  - 1 :  wl: PowerUI.Notification (14)
,I/PowerManagerService( 1013): Waking up from sleep (uid 10054)...
,D/PowerManagerService( 1013): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService( 1013): [s] UserActivityState : 0 -> 1
,D/PowerManagerService( 1013): [PWL] sb acquire: PowerManagerService.Display
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/KeyguardServiceDelegate( 1013): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@1465caa3)
,D/KeyguardViewMediator( 1175): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1175): notifyScreenOnLocked
I/DisplayPowerController( 1013): Blocking screen on until initial contents have been drawn.
D/WindowOrientationListener( 1013): sensor enabled
D/DisplayPowerController( 1013): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1013): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/DisplayPowerController( 1013): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1013): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/libsuspend( 1013): !@autosuspend_wakeup_count_disable
D/DisplayManagerService( 1013): !@display_state: OFF -> ON,
I/libsuspend( 1013): !@autosuspend_wakeup_count_disable done
D/SurfaceFlinger(  257): Set power mode=2, type=0 flinger=0xb8796690
D/qdhwcomposer(  257): hwc_setPowerMode: Setting mode 2 on display: 0
I/Sensors ( 1013): AccelerometerSensor(0) setDelay : 66000000(ns)
E/qdutils (  257): int qdutils::getHDMINode(): Failed to open fb node 2
,E/qdutils (  257): int qdutils::getHDMINode(): Failed to find HDMI node
,D/SensorService( 1013): [SO] changed settle time [1]
,D/SensorService( 1013): [SO] setDelay [66000000]
D/SensorService( 1013): [SO] activate (ident=0xb8fa27f8, enabled=1)
D/SensorService( 1013): [SO] AR_init
,I/Sensors ( 1013): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,I/DisplayManagerService( 1013): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager( 1013): Display changed displayId=0
,D/SensorManager( 1013): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,D/PersonaManager( 1013): isKioskContainerExistOnDevice
,D/KeyguardViewMediator( 1175): handleNotifyScreenOn
,D/StatusBarKeyguardViewManager( 1175): onScreenTurnedOn(),
,D/SecKeyguardClockSingleView( 1175): onScreenTurnedOn
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/CoverManagerWhiteLists( 1013): isAllowedToUse : SIGNATURE_MATCH
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,D/SamsungIME( 1798): showDlgMsgBox : false true true
,D/NfcService( 1423): call the applyRouting
,I/rmt_storage(  269): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8d107c8
I/rmt_storage(  269): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
,I/rmt_storage(  269): wakelock acquired: 1, error no: 42
I/rmt_storage(  269): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1194260344)
D/SensorService( 1013): [SO] currT = 116240066932, prevT = 52020077947, diff = 64219988985, [0.057 0.134 10.075]
D/SensorService( 1013): [SO] Reset Rotation Old [100], Init [1]
D/KnoxNotification( 1175): ----- inflateViews : modified publicViewLocal -----
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
E/MotionRecognitionService( 1013):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
D/LightsService( 1013): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1013) 
I/PalmMotion( 1013): [PALM] 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
,D/LightsService( 1013): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
I/PalmMotion( 1013): [PALM] SURFACE_PALM_SWIPE: 1
D/PalmMotion( 1013): [PALM] SETTINGS : [TOUCH: true] [SWEEP: true]
D/PalmMotion( 1013): [PALM] ACCEPTED : [default] PALM_CNT : 3, M_TOUCH : 1000.0, M_SWEEP : 100.0, E_SWEEP : 2.0, IGNORE_M_SWEEP : false
,D/LightsService( 1013): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
,D/SSRM:a  ( 1013): DeviceInfo:: 000000000000
D/KnoxNotification( 1175): ----- inflateViews : modified KnoxViewLocal -----
,D/LightsService( 1013): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRM:a  ( 1013): SettingsAirViewInfo:: 000000000
,D/PersonaManager( 1175): PersonaID is invalid or persona doesn't exists. : -1
,D/LightsService( 1013): [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 1013) 
,D/LightsService( 1013): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
D/BatteryService( 1013): turn off LED
D/LightsService( 1013): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
E/lights  ( 1013): write_led_info failed to open -1
,E/lights  ( 1013): write_led_info failed to open -1
I/qdhwcomposer(  257): handle_blank_event: dpy:0 panel power state: 1
,E/lights  ( 1013): write_led_info failed to open -1
D/LightsService( 1013): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
E/lights  ( 1013): write_led_info failed to open -1
E/lights  ( 1013): write_led_info failed to open -1
E/lights  ( 1013): write_led_info failed to open -1
E/lights  ( 1013): write_led_info failed to open -1
E/lights  ( 1013): write_led_info failed to open -1
E/lights  ( 1013): write_led_info failed to open -1
,E/qdutils (  257): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  257): int qdutils::getHDMINode(): Failed to find HDMI node
D/qdhwcomposer(  257): hwc_setPowerMode: Done setting mode 2 on display 0
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
D/PersonaManager( 1175): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1175): Icon Only
D/SurfaceControl( 1013): Excessive delay in setPowerMode(): 119ms
D/PowerManagerService( 1013): Excessive delay in !@display_state: ON: 120ms
,I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,D/MISC PowerHAL( 1013): sysfs_write +: /sys/class/input/event3/device/enabled: 1
,D/ActivityManager( 1013): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1013): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1013): postActiveUserChange, showWhenLocked: false
,E/SmartFaceService( 1013): onReceive: android.intent.action.SCREEN_ON
D/KnoxTimeoutHandler( 1013): handleActiveUserChange for user 0
D/PersonaManagerService( 1013): getPersonasForUser(): returning null!
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
,D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
D/StatusBar.NetworkController( 1175): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBarKeyguardViewManager( 1175): callback.onShown()
V/KeyguardServiceDelegate( 1013): **** SHOWN CALLED ****
D/MISC PowerHAL( 1013): sysfs_write +: /sys/class/input/event1/device/enabled: 1
D/DisplayPowerController( 1013): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
I/DisplayPowerController( 1013): Unblocked screen on after 138 ms
D/DisplayPowerState( 1013): !@ ColorFade exit
,D/StatusBar.NetworkController( 1175): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,W/System.err( 1013): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
W/System.err( 1013): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1013): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1013): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1013): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
E/SmartFaceService( 1013): fail to set sysfs 1
W/System.err( 1013): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1013): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:468)
W/System.err( 1013): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1013): 	at android.os.Handler.handleCallback(Handler.java:739)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
W/System.err( 1013): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1013): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1013): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
W/System.err( 1013): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
W/System.err( 1013): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1013): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1013): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1013): 	... 10 more
,D/BatteryMeterView( 1175): onDraw batteryColor : -1
,I/SurfaceFlinger(  257): id=8 Removed DolorFade (8/8),
D/PowerManagerService( 1013): Excessive delay in ColorFade : dismiss: 12ms
I/SurfaceFlinger(  257): id=8 Removed DolorFade (-2/8)
D/DisplayPowerController( 1013): getFinalBrightness : Summary is 5 -> 5
E/libEGL  ( 1013): call to OpenGL ES API with no current context (logged once per thread)
D/DisplayPowerController( 1013): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/lights  ( 1013): lcd : 5 +
D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/InputMethodManagerService( 1013): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false,
,D/SensorService( 1013): [SO] currT = 116310082297, prevT = 52020077947, diff = 64290004350, [0.038 0.115 10.017]
,D/SensorService( 1013): [SO] 0.038 0.115 10.017
D/SensorService( 1013): [SO] [100 -> 255]
,D/MotionRecognitionService( 1013):   mReceiver.onReceive : ACTION_SCREEN_ON
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.uploader.UploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/lights  ( 1013): lcd : 5 -
,D/DisplayPowerController( 1013): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1013): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 1013): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1013): SecHardwareInterface.setBatteryADC : true
E/MotionRecognitionService( 1013):  handler : SCREEN_ON end
,I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
,I/WifiNative-HAL( 1013): startHal
E/wifi    ( 1013): getStaticLongField sWifiHalHandle 0x9c8cf7fc
I/WifiNative-HAL( 1013): Could not start hal
,D/NotificationService( 1013): ACTION_SCREEN_ON
D/LightsService( 1013): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1013) 
,D/LightsService( 1013): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 1013): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1013): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/audio_hw_primary(  282): adev_set_parameters: enter: screen_state=on
V/voice   (  282): voice_set_parameters: enter: screen_state=on
V/voice   (  282): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  282): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  282): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  282): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  282): adev_set_parameters: exit
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,E/WifiNative-wlan0( 1013): do suspend false
,D/MISC PowerHAL( 1013): sysfs_write -: /sys/class/input/event3/device/enabled: 1
,I/wpa_supplicant( 5572): reset timer : RESET_TIMER 1
I/wpa_supplicant( 5572): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 5572): P2P: Current p2p state = IDLE
,I/wpa_supplicant( 5572): Scan requested (ret=0) - scan timeout 30 seconds
,D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/IpRemoteDisplayController( 1013): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController( 1013): Bridge Server is not available
,I/rmt_storage(  269): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
I/rmt_storage(  269): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  269): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1194260344) wakelock released: 1, error no: 0
I/rmt_storage(  269): 
,I/rmt_storage(  269): rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb8d107c8,
,V/UserPresentBroadcastReceiver( 1856): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Timeline( 5426): Timeline: Activity_idle id: android.os.BinderProxy@3098533b time:116415
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/MISC PowerHAL( 1013): sysfs_write -: /sys/class/input/event1/device/enabled: 1
D/PowerManagerService( 1013): Excessive delay in nativeSetInteractive(true): 171ms
D/MISC PowerHAL( 1013): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
D/PowerManagerService( 1013): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 291ms
D/MISC PowerHAL( 1013): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
D/PowerManagerService-JNI( 1013): Excessive delay in MISC setInteractive(true) while turning screen on: 170ms
I/QCOM PowerHAL( 1013): Got set_interactive hint
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/lights  ( 1013): button : 1 +
,D/lights  ( 1013): button : 1 -
,D/GpsLocationProvider( 1013): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/PersonaManagerService( 1013): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler( 1013): MSG_ACTION_SCREEN_ON called
,D/CoverManagerWhiteLists( 1013): isAllowedToUse : SIGNATURE_MATCH
,I/NfcService( 1423): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/NfcService( 1423): call the applyRouting
,D/accuweather( 1718): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
,D/accuweather( 1718): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/accuweather( 1718): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/accuweather( 1718): [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,D/accuweather( 1718): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1718): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1718): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1718): [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 2
,D/accuweather( 1718): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1718): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,E/accuweather( 1718): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 12 01
,D/ActivityManager( 1013): startService callerProcessName:com.sec.android.widgetapp.ap.hero.accuweather, calleePkgName: com.sec.android.widgetapp.ap.hero.accuweather
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,I/SamsungIME( 1798): getNextShiftState() cursorCapsMode : 0
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/PowerManagerService( 1013): [PWL] sb release: PowerManagerService.Broadcasts
,D/SSRM:n  ( 1013): SIOP:: AP = 290
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/daemonapp( 1314): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1314): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1314): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1314): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1314): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1314): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1314): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1314): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1314): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1314): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1314): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1314): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
D/daemonapp( 1314): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1314): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1314): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1452618000000
D/daemonapp( 1314): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1452596507838
,D/daemonapp( 1314): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1314): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/daemonapp( 1314): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1314): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1314): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1314): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 1314): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,I/BatteryStatsDumper( 1013): In refreshStats isReason Screen ON/OFF: true
,D/NetworkStatsFactory( 1013): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1013): UpdateStatsForKnox updated
,I/art     ( 1856): Explicit concurrent mark sweep GC freed 101118(5MB) AllocSpace objects, 47(1783KB) LOS objects, 40% free, 13MB/22MB, paused 1.380ms total 96.316ms
,I/BatteryStatsDumper( 1013): Screen bin #0: time=30305 power=0.17677916666666665
I/BatteryStatsDumper( 1013): Screen bin #1: time=0 power=0.0
I/BatteryStatsDumper( 1013): Screen bin #2: time=0 power=0.0
I/BatteryStatsDumper( 1013): Screen bin #3: time=0 power=0.0
I/BatteryStatsDumper( 1013): Screen bin #4: time=0 power=0.0
I/BatteryStatsDumper( 1013): Previous Battery Level: 100 Current Level: 100 Delta: 0
,I/art     ( 1013): Explicit concurrent mark sweep GC freed 63601(3MB) AllocSpace objects, 17(272KB) LOS objects, 33% free, 28MB/42MB, paused 2.992ms total 171.980ms
,I/BatteryStatsDumper( 1013): Writing to database completed
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeConfigurator( 1856): Scheduling Phenotype for one-off execution 14123 seconds from now (1452596508145)
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GetConfigurationSnapshotOperation( 1856): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/PhenotypeFlagCommitter( 1856): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1856): Using platform SSLCertificateSocketFactory
,D/LocationManagerService( 1013): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1856): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1856): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1856): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020543/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/SSRM:a  ( 1013): DeviceInfo:: 000000000000
D/SSRM:a  ( 1013): SettingsAirViewInfo:: 000000000
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/lights  ( 1013): button : 0 +
,D/lights  ( 1013): button : 0 -
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/wpa_supplicant( 5572): nl80211: Received scan results (8 BSSes),
,D/WifiP2pService( 1013): InactiveState{ what=147461 },
,D/WifiP2pService( 1013): P2pEnabledState{ what=147461 }
,D/WifiP2pService( 1013): DefaultState{ what=147461 },
,I/System.out( 1856): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1856): Tagging socket 34 with tag 3000040100000000{805307393,0} for uid 10012, pid: 1856, getuid(): 10012
,I/qtaguid ( 1856): Tagging socket 90 with tag 3000040100000000{805307393,0} for uid 10012, pid: 1856, getuid(): 10012
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  287): DCD OFF
,I/System.out( 1856): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
,I/System.out( 1856): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1856): Tagging socket 95 with tag 3000120100000000{805310977,0} for uid -1, pid: 1856, getuid(): 10012
,I/qtaguid ( 1856): Tagging socket 98 with tag 3000120100000000{805310977,0} for uid -1, pid: 1856, getuid(): 10012
,D/LocationManagerService( 1013): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1856): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1856): Tagging socket 95 with tag 3000120100000000{805310977,0} for uid -1, pid: 1856, getuid(): 10012
,D/LocationManagerService( 1013): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1856): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1856): Tagging socket 95 with tag 3000120100000000{805310977,0} for uid -1, pid: 1856, getuid(): 10012
,D/LocationManagerService( 1013): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1856): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1856): Tagging socket 95 with tag 3000120100000000{805310977,0} for uid -1, pid: 1856, getuid(): 10012
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/LocationManagerService( 1013): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1856): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1856): Tagging socket 95 with tag 3000120100000000{805310977,0} for uid -1, pid: 1856, getuid(): 10012
,D/LocationManagerService( 1013): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1856): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1856): Tagging socket 95 with tag 3000120100000000{805310977,0} for uid -1, pid: 1856, getuid(): 10012
,D/LocationManagerService( 1013): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1856): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1856): Tagging socket 95 with tag 3000120100000000{805310977,0} for uid -1, pid: 1856, getuid(): 10012
,D/LocationManagerService( 1013): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1856): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1856): Tagging socket 95 with tag 3000120100000000{805310977,0} for uid -1, pid: 1856, getuid(): 10012
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000,
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/SensorService( 1013): [SO] 0.038 0.115 10.017
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,W/IcingInternalCorpora( 2000): getNumBytesRead when not calculated.
,E/SMD     (  287): DCD OFF
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1013): userId = 0, bbcId = -10000,
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1013): [checkCaptivePortal] - callbackHandler=Handler (com.android.server.wifi.WifiWatchdogStateMachine$CaptivePortalHandler) {2c45017d}
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700",
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1013): start check captive portal 
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1013): result = 0, mCaptivePortalCheckMode = 11, mCouldNotIdentifyCaptivePortalState = true
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
D/PersonaManager( 1175): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1013): Plugged
,I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1400): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1400): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5518): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5518): Disconnected process message: 10
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1013): SIOP:: AP = 290,
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 2
,V/AlarmManager( 1013): waitForAlarm result :8
,V/AlarmManager( 1013): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManagerEXT( 1013): <AppSync3 Whitelist>
,V/AlarmManagerEXT( 1013): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1175): handleTimeUpdate
,D/SecKeyguardClockView( 1175): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1175): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1175): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1175): *** don't update sliding image ***
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/accuweather( 1718): [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionTIME_TICK,
D/accuweather( 1718): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/accuweather( 1718): [KK AccuPhone]>>> UIM:289 [0:0] direct update clock,
D/accuweather( 1718): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
D/accuweather( 1718): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
D/accuweather( 1718): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
D/accuweather( 1718): [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 2
D/accuweather( 1718): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1718): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,E/accuweather( 1718): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 12 02
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  287): DCD OFF
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/SensorService( 1013): [SO] 0.038 0.096 10.017
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  287): DCD OFF
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/PowerManagerService( 1013): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1175 (0x0)
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 290
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/Watchdog( 1013): !@Sync 4
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,D/PowerManagerService( 1013): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 1013): getFinalBrightness : Summary is 1 -> 1
,D/DisplayPowerController( 1013): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 1013): [s] DisplayPowerCallbacks : onStateChanged()
,D/DisplayPowerController( 1013): getFinalBrightness : Summary is 1 -> 1
,D/lights  ( 1013): lcd : 1 +
,D/DisplayPowerController( 1013): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 1013): lcd : 1 -
,D/DisplayPowerController( 1013): getFinalBrightness : Summary is 1 -> 1
,D/DisplayPowerController( 1013): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/SensorService( 1013): [SO] 0.038 0.115 10.017
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1013): waitForAlarm result :4
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 3
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.sync.metadata.ContactMetadataSyncService; callingUser = 0; userId(target) = 0
,E/ActivityThread( 2000): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager( 1013): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 115607, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager( 1013): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 207247, reason: UserStart
,D/SecContentProvider2( 1013): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1013): mCursor = null
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  287): DCD OFF
,D/PowerManagerService( 1013): [s] UserActivityState : 2 -> 4
,I/PowerManagerService( 1013): Nap time (uid 1000)...
D/PowerManagerService( 1013): handleSandman : startDreaming: false  (canDreamLocked: false  canDozeLocked: false)
I/PowerManagerService( 1013): !@[ps] Screen__Off - 1 :  dream(timeout) (2)
I/PowerManagerService( 1013): Going to sleep due to screen timeout (uid 1000)...
D/PowerManagerService( 1013): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 1013): SecHardwareInterface.setBatteryADC : false
D/PowerManagerService( 1013): handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
D/PowerManagerService( 1013): handleSandman : startDream(true)
E/PowerManagerService( 1013): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService( 1013): Sleeping (uid 1000)...
D/PowerManagerService( 1013): [s] UserActivityState : 4 -> 0
,V/WindowOrientationListener( 1013): WindowOrientationListener disabled
D/SensorService( 1013): [SO] activate (ident=0xb8fa27f8, enabled=0)
I/Sensors ( 1013): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,I/SurfaceFlinger(  257): id=15 createSurf (720x1280),-1 flag=20004, DolorFade
,D/SensorManager( 1013): unregisterListener ::   
,D/KeyguardViewMediator( 1175): onScreenTurnedOff(3)
,I/KeyguardEffectViewController( 1175): *** KeyguardEffectView getInstanceIfExists ***
,D/KeyguardEffectViewController( 1175): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1175): notifyScreenOffLocked
,D/KeyguardViewMediator( 1175): timeout : 5000
,D/PowerManagerService( 1013): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 38ms
,V/ActivityThread( 5426): updateVisibility : ActivityRecord{5bdb7b1 token=android.os.BinderProxy@3098533b {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/KeyguardViewMediator( 1175): setting alarm to turn off keyguard, seq = 2
,D/KeyguardViewMediator( 1175): handleNotifyScreenOff
,D/VolumePanel( 1175): onScreenTurnedOff()
D/VolumePanel( 1175): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1175): mCoverBroadcastReceiver: Screen OFF end
,D/SecKeyguardClockSingleView( 1175): onScreenTurnedOff
,D/DisplayPowerController( 1013): ColorFade: onAnimationStart
D/DisplayPowerController( 1013): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1013): performScreenOffTransition : no brightness animation
,D/LightsService( 1013): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1013) 
,D/LightsService( 1013): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/BatteryService( 1013): turn on LED for fully charged
D/LightsService( 1013): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
,E/lights  ( 1013): write_int failed to open -1
D/LightsService( 1013): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SmartFaceService( 1013): onReceive: android.intent.action.SCREEN_OFF
,W/System.err( 1013): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
W/System.err( 1013): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1013): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1013): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1013): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1013): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1013): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:474)
W/System.err( 1013): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1013): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1013): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1013): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1013): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1013): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1013): 	at libcore.io.Posix.open(Native Method)
E/SmartFaceService( 1013): fail to set sysfs 0
W/System.err( 1013): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1013): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1013): 	... 10 more
,I/StatusBar( 1175): Icon Only
,D/PanelView( 1175): There is/are notification(s) 
,D/MotionRecognitionService( 1013):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/WifiNative-wlan0( 1013): do suspend true
,D/NotificationService( 1013): ACTION_SCREEN_OFF
D/LightsService( 1013): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1013) 
,D/LightsService( 1013): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/LightsService( 1013): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
,D/LightsService( 1013): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
E/MotionRecognitionService( 1013):  handler : SCREEN_OFF end 
,D/audio_hw_primary(  282): adev_set_parameters: enter: screen_state=off
,V/voice   (  282): voice_set_parameters: enter: screen_state=off
V/voice   (  282): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  282): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  282): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  282): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  282): adev_set_parameters: exit
,I/BackgroundCompactionService( 1013): Schedule Type1 BGCompaction
,D/IpRemoteDisplayController( 1013): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 1013): Bridge Server is not available
,D/GpsLocationProvider( 1013): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,V/EmergencyMode( 1400): [EmergencyStateReceiver] onReceive : android.intent.action.SCREEN_OFF
,V/EmergencyMode( 1400): [EmergencyStateReceiver] binteractive [false] why[3]
,D/PersonaManagerService( 1013): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 1013): MSG_ACTION_SCREEN_OFF called
,D/NfcService( 1423): call the applyRouting
,D/accuweather( 1718): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF,
D/accuweather( 1718): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1718): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/daemonapp( 1314): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,D/accuweather( 1718): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1718): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1718): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1718): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/daemonapp( 1314): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,E/LibSecureUISvc( 1932): svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
,D/SSRM:n  ( 1013): SIOP:: AP = 290
,D/daemonapp( 1314): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/PowerManagerService( 1013): [PWL] sb release: PowerManagerService.Broadcasts
,D/accuweather( 1718): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1718): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1718): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1718): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1718): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
,D/accuweather( 1718): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/accuweather( 1718): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/DisplayPowerState( 1013): !@ ColorFade entry
,D/DisplayPowerController( 1013): ColorFade: onAnimationEnd
,D/DisplayPowerController( 1013): getFinalBrightness : Summary is 0 -> 0
D/lights  ( 1013): lcd : 0 +
,D/DisplayPowerController( 1013): performScreenOffTransition : no brightness animation
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1013): stay LED for fully charged
D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1013): Plugged
,I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1400): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1400): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/lights  ( 1013): lcd : 0 -
,D/DisplayPowerController( 1013): getFinalBrightness : Summary is 0 -> 0
D/DisplayPowerController( 1013): performScreenOffTransition : no brightness animation
D/PowerManagerService( 1013): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1013): [PWL] sb release: PowerManagerService.Display
,D/MISC PowerHAL( 1013): sysfs_write +: /sys/class/input/event3/device/enabled: 0
,D/MISC PowerHAL( 1013): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,D/MISC PowerHAL( 1013): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/MISC PowerHAL( 1013): sysfs_write -: /sys/class/input/event3/device/enabled: 0
,D/MISC PowerHAL( 1013): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 1013): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
I/QCOM PowerHAL( 1013): Got set_interactive hint
,D/DisplayManagerService( 1013): !@display_state: ON -> OFF
,V/HeadsetService( 5518): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/SurfaceFlinger(  257): Set power mode=0, type=0 flinger=0xb8796690
D/qdhwcomposer(  257): hwc_setPowerMode: Setting mode 0 on display: 0
I/DisplayManagerService( 1013): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/HeadsetStateMachine( 5518): Disconnected process message: 10
E/qdutils (  257): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  257): int qdutils::getHDMINode(): Failed to find HDMI node
,V/ActivityManager( 1013): Display changed displayId=0
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/BatteryStatsDumper( 1013): In refreshStats isReason Screen ON/OFF: true
,D/NetworkStatsFactory( 1013): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1013): UpdateStatsForKnox updated
,D/StatusBar.NetworkController( 1175): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
,D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/BatteryStatsDumper( 1013): Screen bin #0: time=30305 power=0.17677916666666665
I/BatteryStatsDumper( 1013): Screen bin #1: time=0 power=0.0
I/BatteryStatsDumper( 1013): Screen bin #2: time=0 power=0.0
I/BatteryStatsDumper( 1013): Screen bin #3: time=0 power=0.0
I/BatteryStatsDumper( 1013): Screen bin #4: time=0 power=0.0
I/BatteryStatsDumper( 1013): Previous Battery Level: 100 Current Level: 100 Delta: 0
,I/qdhwcomposer(  257): handle_blank_event: dpy:0 panel power state: 0
D/qdhwcomposer(  257): hwc_setPowerMode: Done setting mode 0 on display 0
,E/qdutils (  257): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  257): int qdutils::getHDMINode(): Failed to find HDMI node
,D/SurfaceControl( 1013): Excessive delay in setPowerMode(): 241ms,
D/PowerManagerService( 1013): Excessive delay in !@display_state: OFF: 241ms
I/libsuspend( 1013): !@autosuspend_wakeup_count_enable
D/PowerManagerService( 1013): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 251ms
I/libsuspend( 1013): !@autosuspend_wakeup_count_enable done
,I/PowerManagerService( 1013): [PWL] Off : 0s ago
I/BatteryStatsDumper( 1013): Writing to database completed
I/PowerManagerService( 1013): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService( 1013): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1013): [PWL]       PARTIAL_WAKE_LOCK              'SmartManager Framework Thread' (uid=1000, pid=1013, ws=null) (elapsedTime=231)
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1013): waitForAlarm result :4
,D/KeyguardViewMediator( 1175): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2,
D/KeyguardViewMediator( 1175): doKeyguard: not showing because lockscreen is off
,V/KeyguardEffectViewController( 1175): *** Keyguard wallpaper service already unbounded
,I/PowerManagerService( 1013): [PWL] Off : 5s ago
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1013): waitForAlarm result :8
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:5, health:2, present:true, voltage: 4343, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1013): stay LED for fully charged
D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1013): Plugged,
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1400): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1400): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5518): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5518): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,V/AlarmManager( 1013): waitForAlarm result :8
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1013): [PWL] Off : 15s ago
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1013): !@Sync 5
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1013): waitForAlarm result :4
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: android, action: null
,D/ActivityManager( 1013): retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
,I/BackgroundCompactionService( 1013): onStart. jobID=801
,I/BackgroundCompactionService( 1013): onStart done. jobID=801
,I/BackgroundCompactionService( 1013): Execute BGCompaction (type1). (1 times)
,I/BackgroundCompactionService( 1013): compact_memory command done
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1013): waitForAlarm result :4
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1013): level:100, scale:100, status:5, health:2, present:true, voltage: 4343, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for fully charged
D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1013): Plugged
,I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1400): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1400): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5518): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5518): Disconnected process message: 10
,I/PowerManagerService( 1013): [PWL] Off : 30s ago
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 5
,V/AlarmManager( 1013): waitForAlarm result :8
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,I/PowerManagerService( 1013): [PWL] Off : 50s ago,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1013): !@Sync 6
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,I/Atfwd_Sendcmd(  314): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  314): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1013): [PWL] Off : 75s ago,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/Watchdog( 1013): !@Sync 7
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ClearcutLoggerApiImpl( 1856): disconnect managed GoogleApiClient
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1013): level:100, scale:100, status:5, health:2, present:true, voltage: 4343, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate,
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for fully charged
D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
V/EmergencyMode( 1400): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1400): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
I/MotionRecognitionService( 1013): Plugged
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,V/HeadsetService( 5518): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 5518): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1013): [PWL] Off : 105s ago
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1013): !@Sync 8
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1013): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1175): handleTimeUpdate
,D/SecKeyguardClockView( 1175): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1175): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/KeyguardEffectViewController( 1175): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1175): *** don't update sliding image ***
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1013): [PWL] Off : 140s ago
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1013): !@Sync 9
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1013): SIOP:: AP = 260
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): stay LED for fully charged
,D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1013): Plugged
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
V/EmergencyMode( 1400): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1400): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5518): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5518): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1013): SIOP:: AP = 260,
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1013): waitForAlarm result :8
,I/jxcore-log( 5426): --= Surplus to requirements =--
I/jxcore-log( 5426): 
I/jxcore-log( 5426): ****TEST TOOK:  ms ****
I/jxcore-log( 5426): 
,I/jxcore-log( 5426): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5426): 
,E/SMD     (  287): DCD OFF
,D/AndroidRuntime( 6675): 
D/AndroidRuntime( 6675): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6675): CheckJNI is OFF
D/AndroidRuntime( 6675): readGMSProperty: start
D/AndroidRuntime( 6675): readGMSProperty: already setted!!
D/AndroidRuntime( 6675): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6675): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6675): readGMSProperty: end
D/AndroidRuntime( 6675): addProductProperty: start
,E/AffinityControl( 6675): AffinityControl: registerfunction enter,
,D/AndroidRuntime( 6675): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService( 1013): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1013): START PACKAGE DELETE: observer{968613190}
D/PackageManager( 1013): pkg{<packageName>}
D/PackageManager( 1013): user{0}
D/PackageManager( 1013): caller{2000}
D/PackageManager( 1013): flags{3}
D/PersonaManagerService( 1013): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1013): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1013): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1013): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1013): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1013): deletePackage- pkg:com.test.thalitest, edmuserId:0
,D/PackageManagerService( 1013): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1013): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1013): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1013): !@killApplicatoin: 10175, uninstall pkg
,I/ActivityManager( 1013): Force stopping com.test.thalitest appid=10175 user=-1: uninstall pkg
,I/ActivityManager( 1013): Killing 5426:com.test.thalitest/u0a175 (adj 0): stop com.test.thalitest cause uninstall pkg
,I/ActivityManager( 1013):   Force finishing activity ActivityRecord{152535da u0 com.test.thalitest/.MainActivity t2}
,D/InputDispatcher( 1013): Focus left window: 5426
I/SurfaceFlinger(  257): id=12 Removed NainActivit (6/8)
I/SurfaceFlinger(  257): id=12 Removed NainActivit (-2/8)
,D/InputDispatcher( 1013): Focused application released
,D/PointerIcon( 1013): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1013): setMouseCustomIcon IconType is same.101
,D/FocusedStackFrame( 1013): Set to : 0
,W/ActivityManager( 1013): mDVFSHelper.acquire()
,W/PackageSettings( 1013): Skipping PackageSetting{3513aa38 com.example.hello/10177} due to missing metadata
,V/WindowManager( 1013): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,I/ActivityManager( 1013): Force stopping com.test.thalitest appid=10175 user=0: pkg removed
,W/ActivityManager( 1013): CustomStartingWindow se packge removed so remove capture also
,I/art     ( 3710): Explicit concurrent mark sweep GC freed 2851(177KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 6MB/11MB, paused 771us total 26.486ms
,D/Launcher( 1463): onRestart, Launcher: 856942375,
,I/InputReader( 1013): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 2000): Explicit concurrent mark sweep GC freed 6623(291KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 14MB/19MB, paused 1.266ms total 69.035ms
,D/EnterpriseDeviceManagerService( 1013): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1013): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1013): no available spell checker services found
,E/SamsungIME( 1798): mOCRHelper is null
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/GeofencerStateMachine( 1856): Ignoring removeGeofence because network location is disabled.,
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/Launcher( 1463): onStart, Launcher: 856942375
D/Launcher.HomeView( 1463): onStart
,D/Launcher( 1463): onResume, Launcher: 856942375
,D/SettingsProvider( 1013): name = kids_home_mode
D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 10007
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
D/Launcher.HomeView( 1463): onResume
,D/RegisteredComponentCache( 1423): Collect Tech packages for Knox
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PersonaManager( 1423): isKioskContainerExistOnDevice
,I/KLMS-2.5.183: ( 3430): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Jan 12 12:05:02 GMT+01:00 2016
,D/Launcher( 1463): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/ActivityManager( 1013): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/MenuAppsGridFragment( 1463): onResume
,D/WallpaperManager( 1463): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1463): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1463): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,I/KLMS-2.5.183: ( 3430): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1013): Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
,I/splitIntent( 1013): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,I/PackagesMonitor( 5912): PackagesMonitor onReceive :com.test.thalitest
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3430): KLMSIntentService(): onCreate()
,D/elm:15183( 5952): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,E/Zygote  ( 6691): MountEmulatedStorage(),
E/Zygote  ( 6691): v2
I/libpersona( 6691): KNOX_SDCARD checking this for 1000
I/libpersona( 6691): KNOX_SDCARD not a persona
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager( 1013): Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=6691 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 6691): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 6691): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/KLMS-2.5.183: ( 3430): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/SELinux ( 6691): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3430): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,E/Zygote  ( 6702): MountEmulatedStorage(),
E/Zygote  ( 6702): v2
I/libpersona( 6702): KNOX_SDCARD checking this for 10149
I/libpersona( 6702): KNOX_SDCARD not a persona
,I/SELinux ( 6702): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6702): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,I/ActivityManager( 1013): Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=6702 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ActivityManager( 1013): handle home activity for 0
D/ActivityManager( 1013): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
I/WallpaperManagerService( 1013): switchPersonaWallpaper is called for personaId-0
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
D/KnoxTimeoutHandler( 1013): post home show event for user 0
D/ActivityManager( 1013): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1013): postActiveUserChange for user 0
,I/KnoxTimeoutHandler( 1013): postActiveUserChange, showWhenLocked: false
D/Launcher.HomeView( 1463): onPause
E/SELinux ( 6702): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
D/Launcher( 1463): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/TimaKeyStoreProvider( 6691): TimaSignature is unavailable
,D/ActivityThread( 6691): Added TimaKeyStore provider
,I/KLMS-2.5.183: ( 3430): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,D/elm:15183( 5952): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/TimaKeyStoreProvider( 6702): TimaSignature is unavailable
,D/ActivityThread( 6702): Added TimaKeyStore provider
,D/elm:15183( 5952): ElmAgentService : onCreate()
,D/elm:15183( 5952): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15183( 5952): MainReceiver.listeningToPackageRemoved()
D/elm:15183( 5952): MDMBridge.getInstance()
D/elm:15183( 5952): MDMBridge.getAllLicenseInfoFromSDK()
D/PersonaManager( 1423): isKioskContainerExistOnDevice
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,D/elm:15183( 5952): MDMBridge.getAllLicenseInfoFromSDK()
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3430): KLMSIntentService(): PACKAGE_REMOVED
,I/art     ( 1013): Explicit concurrent mark sweep GC freed 79597(5MB) AllocSpace objects, 87(2MB) LOS objects, 33% free, 27MB/41MB, paused 3.536ms total 287.780ms
,I/art     ( 1013): WaitForGcToComplete blocked for 268.427ms for cause Explicit
I/KLMS-2.5.183: ( 3430): KLMSIntentService(): listeningToPackageRemoved().START
,E/Zygote  ( 6722): MountEmulatedStorage()
E/Zygote  ( 6722): v2
I/libpersona( 6722): KNOX_SDCARD checking this for 10046
I/libpersona( 6722): KNOX_SDCARD not a persona
I/SELinux ( 6722): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1013): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=6722 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,D/RegisteredServicesCache( 1423): empty dynamic service
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.aasaservice, hostingType: broadcast
I/KLMS-2.5.183: ( 3430): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
I/SELinux ( 6722): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6722): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/SecContentProvider2( 1013): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1013): mCursor = null
,E/Zygote  ( 6737): MountEmulatedStorage()
I/libpersona( 6737): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6737): v2
I/libpersona( 6737): KNOX_SDCARD not a persona
I/SELinux ( 6737): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6737): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6737): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Start proc com.samsung.aasaservice for broadcast com.samsung.aasaservice/.AASAUpdateReceiver: pid=6737 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/TimaKeyStoreProvider( 6722): TimaSignature is unavailable
D/ActivityThread( 6722): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 6737): TimaSignature is unavailable
,D/ActivityThread( 6737): Added TimaKeyStore provider
,D/elm:15183( 5952): ElmAgentService : onDestroy().
,W/ActivityManager( 1013): mDVFSHelper.release()
,W/ResourcesManager( 6722): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,I/KLMS-2.5.183: ( 3430): KLMSIntentService(): listeningToPackageRemoved().END
W/ResourcesManager( 6722): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6722): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6722): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6722): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6722): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 6691): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KLMS-2.5.183: ( 3430): KLMSIntentService(): onDestroy()
I/SurfaceFlinger(  257): id=16 createSurf (720x1280),1 flag=4, Mauncher
,D/StatusBarManagerService( 1013): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 1013): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/InputDispatcher( 1013): Focus entered window: 1463
,D/PointerIcon( 1013): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1013): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 1463): log_dcs ThreadedRenderer::initialize entered! 
,D/ThemeInfoUtil( 6702): getCurrentFestivalName is [null]
,D/ThemeInfoUtil( 6702): isCurrentFestival = false
,D/AASAservice-UpdateReceiver( 6737): AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,D/Launcher.HomeView( 1463): onStop
V/ActivityThread( 1463): updateVisibility : ActivityRecord{1ef99dcd token=android.os.BinderProxy@35c97a0a {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,W/System.err( 6737): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 6737): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
W/System.err( 6737): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
W/System.err( 6737): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 6737): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 6737): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 6737): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6737): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 6737): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 6737): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6737): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6737): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 6737): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/ResourceType( 1013): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,D/InputMethodManagerService( 1013): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6754): MountEmulatedStorage(),
I/ActivityManager( 1013): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=6754 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
E/Zygote  ( 6754): v2
I/libpersona( 6754): KNOX_SDCARD checking this for 10152
I/libpersona( 6754): KNOX_SDCARD not a persona
,W/InputMethodManagerService( 1013): Got RemoteException sending setActive(false) notification to pid 5426 uid 10175
,I/ActivityManager( 1013): Killing 5902:com.qualcomm.timeservice/1000 (adj 15): empty #31
,D/SamsungIME( 1798): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
I/SELinux ( 6754): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6754): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6754): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 1013): Killing 5009:com.android.defcontainer/u0a4 (adj 15): empty #31
,W/OpenGLRenderer( 1463): SFEffectCache::get: create texture(0x9f9fb724): name, size, mSize = 39, 143856, 321408
,D/TimaKeyStoreProvider( 6754): TimaSignature is unavailable
,D/ActivityThread( 6754): Added TimaKeyStore provider
,D/Mms/MmsApp( 6722): [start]    onCreate() consume time = 0.0
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/Timeline( 1013): Timeline: Activity_windows_visible id: ActivityRecord{5b67c68 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:311907
,I/art     ( 6691): Explicit concurrent mark sweep GC freed 2328(138KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 776us total 32.958ms
,D/PersonaManager( 1013): isKioskContainerExistOnDevice
,E/SQLiteLog( 6691): (284) automatic index on crash_info_summary(package_name_touched)
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/SQLiteLog( 6754): (284) automatic index on shooting_modes(title_id)
,I/art     ( 1013): Explicit concurrent mark sweep GC freed 10644(524KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 13.817ms total 322.795ms
,E/Zygote  ( 6773): MountEmulatedStorage()
E/Zygote  ( 6773): v2
I/libpersona( 6773): KNOX_SDCARD checking this for 1000
I/libpersona( 6773): KNOX_SDCARD not a persona
I/SELinux ( 6773): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1013): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6773 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 6773): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6773): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1013): Killing 5987:com.sec.pcw.device/1000 (adj 15): empty #31
,D/ActivityManager( 1013): getContentProviderImpl callerProcessName:com.samsung.android.sm, calleePkgName: com.sec.android.provider.badge
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6787): MountEmulatedStorage()
E/Zygote  ( 6787): v2
I/libpersona( 6787): KNOX_SDCARD checking this for 10072
I/libpersona( 6787): KNOX_SDCARD not a persona
,I/SELinux ( 6787): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1013): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6787 uid=10072 gids={50072, 9997} abi=armeabi-v7a
,I/SELinux ( 6787): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6787): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1013): startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,D/TimaKeyStoreProvider( 6773): TimaSignature is unavailable
,D/ActivityThread( 6773): Added TimaKeyStore provider
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 6787): TimaSignature is unavailable
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/ActivityThread( 6787): Added TimaKeyStore provider
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6804): MountEmulatedStorage()
E/Zygote  ( 6804): v2
I/libpersona( 6804): KNOX_SDCARD checking this for 10156
I/libpersona( 6804): KNOX_SDCARD not a persona
I/SELinux ( 6804): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6804): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6804): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=6804 uid=10156 gids={50156, 9997} abi=armeabi-v7a
,I/ActivityManager( 1013): Killing 5601:com.android.email/u0a145 (adj 15): empty #31
,W/art     ( 6722): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 136.077ms
,I/ActivityManager( 1013): Killing 5659:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6804): TimaSignature is unavailable
,D/ActivityThread( 6804): Added TimaKeyStore provider
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/BadgeProvider( 6787): onCreate
,D/BadgeProvider( 6787): DatabaseHelper
,W/ContextImpl( 6773): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1013): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,W/ResourcesManager( 1013): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1013): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1013): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/BadgeProvider( 6787): sendNotify entered. [uri] : content://com.sec.badge/apps
D/BadgeProvider( 6787): sendNotify, [notify] : null
D/BadgeProvider( 6787): update, [uri] : content://com.sec.badge/apps
D/BadgeProvider( 6787): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 6787): update, [UpdateCount] : 1
,I/TapandpayWidget:TapandpayAppWidgetProvider( 6804): onReceive(),
D/TapandpayWidget:TapandpayAppWidgetProvider( 6804): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,I/TapandpayWidget:Utils( 6804): Clear T&P info.
,D/TapandpayWidget:TapandpayAppWidgetProvider( 6804): Widget is not attached.
,E/Zygote  ( 6823): MountEmulatedStorage()
E/Zygote  ( 6823): v2
I/libpersona( 6823): KNOX_SDCARD checking this for 1000
I/libpersona( 6823): KNOX_SDCARD not a persona
,I/SELinux ( 6823): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,W/art     ( 6722): Verification of com.sec.android.touchwiz.animator.TwDndHorizontalListAnimator com.android.mms.ArtClassLoader.createTwDndHorizontalListAnimator(android.content.Context) took 129.556ms
,I/SELinux ( 6823): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 6823): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6823 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/Mms/TelephonyPermission( 6722): start operation mode monitor
,D/Mms/ArtClassLoader( 6722): init before art
,D/PackageManager( 1013): delete codoeFile: 
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 1013): PackageReceiver onReceive()
I/HarmonyEASService( 1013): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,W/ResourcesManager( 6722): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 6823): TimaSignature is unavailable
D/AASAuninstall( 1013): userId = 0, info.removedAppID = -1, info.uid = 10175, packageName = com.test.thalitest
D/ActivityThread( 6823): Added TimaKeyStore provider
D/KnoxMUMContainerPolicy( 1013): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1013): PackageRemovalReceiver::onReceive Enter
D/OTPFW   ( 1013): OtpDbHelper::getInstance New instance created
D/OTPFW   ( 1013): DBIntegrity::getInstance - New instance created
,I/AASA_removePackage( 1013): UID=10175 Target=com.test.thalitest
,D/PackageManager( 1013): result of delete: 1{968613190}
E/Zygote  ( 6839): MountEmulatedStorage()
I/libpersona( 6839): KNOX_SDCARD checking this for 10160
E/Zygote  ( 6839): v2
I/libpersona( 6839): KNOX_SDCARD not a persona
,I/SELinux ( 6839): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6839): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6839): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=6839 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager( 1013): Killing 6020:com.android.chrome/u0a81 (adj 15): empty #31
,I/ActivityManager( 1013): Killing 6032:com.samsung.android.service.travel/u0a159 (adj 15): empty #31
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/AndroidRuntime( 6675): Shutting down VM
,D/OTPFW   ( 1013): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10175 container id = 0
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/Mms/TelephonyPermission( 6722): DefaultSmsApp is com.android.mms
,D/Mms/TelephonyPermission( 6722): isDefault true
,I/OTPFW   ( 1013): ProvisionData::getAllEntries Enter
,D/Mms/MmsApp( 6722): onCreate() com.android.mms
,D/TimaKeyStoreProvider( 6839): TimaSignature is unavailable
,D/ActivityThread( 6839): Added TimaKeyStore provider
,E/OTPFW   ( 1013): ProvisionData::getAllEntries Table is empty
,W/ResourcesManager( 6823): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/BackupManagerService( 1013): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1013): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy( 1013): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1013): uID is 10175
V/EnterpriseBillingPolicy( 1013): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1013): getProfileForApplication - enter
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
V/EnterpriseBillingPolicyStorage( 1013): getProfileForApplication - exit null : containerId = 0
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
V/EnterpriseBillingPolicy( 1013): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1013): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1013): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1013): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,V/EnterpriseBillingPolicy( 1013): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
D/SSRM:aZ ( 1013): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicy( 1013): uID is 10175
V/EnterpriseBillingPolicy( 1013): Removed Packageuid is0
D/TaskPersister( 1013): removeObsoleteFile: deleting file=2_task.xml
,V/EnterpriseBillingPolicyStorage( 1013): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1013): getProfileForApplication - exit null : containerId = 0
,V/EnterpriseBillingPolicy( 1013): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1013): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1013): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1013): getBillingProfileForVpnEngine - end - null
,D/WindowOrientationListener( 1013):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,D/WallpaperManagerService( 1013):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 1013): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler( 1013): handleActiveUserChange for user 0
,D/PersonaManagerService( 1013): getPersonasForUser(): returning null!
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 6839): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,I/StatusBar( 1175): Icon Only
,I/libpersona( 6854): KNOX_SDCARD checking this for 1000
D/PanelView( 1175): There is/are notification(s) 
I/libpersona( 6854): KNOX_SDCARD not a persona
E/Zygote  ( 6854): MountEmulatedStorage()
E/Zygote  ( 6854): v2
I/SELinux ( 6854): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6854): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6854): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6854 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,V/AlarmManagerEXT( 1013): com.test.thalitest(10175) is removed.,
,D/RCPManager( 6823):  in createShortcut() for packageName: com.test.thalitest userId0
,D/[0]UMC:UMCContentProvider( 6839): @onCreate
,D/RCPManagerService( 1013):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1013): queryAllProviders():  providerCallBack is not register for 0
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/art     (  305): Explicit concurrent mark sweep GC freed 8757(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 719us total 35.189ms
,D/TimaKeyStoreProvider( 6854): TimaSignature is unavailable
D/ActivityThread( 6854): Added TimaKeyStore provider
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 678us total 18.612ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 598us total 17.745ms
,E/Zygote  ( 6870): MountEmulatedStorage()
I/libpersona( 6870): KNOX_SDCARD checking this for 10091
E/Zygote  ( 6870): v2,
I/libpersona( 6870): KNOX_SDCARD not a persona
I/SELinux ( 6870): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6870): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1013): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6870 uid=10091 gids={50091, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 6870): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Killing 6057:com.sec.android.soagent/u0a34 (adj 15): empty #31
,D/[0]UMC:Core( 6839): onCreate(): 
D/[0]UMC:Core( 6839): @isManagedProfileUser
D/[0]UMC:Core( 6839): userId: 0
,I/Choreographer( 1463): Skipped 36 frames!  The application may be doing too much work on its main thread.
D/Launcher.Model( 1463): reloadBadges entered.
,I/Timeline( 1463): Timeline: Activity_idle id: android.os.BinderProxy@35c97a0a time:312468
,D/[0]UMC:Core( 6839): userInfo: UserInfo{0:Thali Test:13}
D/[0]UMC:Core( 6839): userInfo.isManagedProfile() : false
,D/UsbSettingsManager( 1013): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 1013): onPackageRemoved : com.test.thalitest
,W/libprocessgroup( 1013): failed to open /acct/uid_10004/pid_5009/cgroup.procs: No such file or directory
E/SQLiteLog( 6691): (284) automatic index on crash_info_summary(package_name_touched)
W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_5902/cgroup.procs: No such file or directory
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_5987/cgroup.procs: No such file or directory
,W/libprocessgroup( 1013): failed to open /acct/uid_10145/pid_5601/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_5659/cgroup.procs: No such file or directory
,W/art     ( 6675): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,W/libprocessgroup( 1013): failed to open /acct/uid_10081/pid_6020/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_10159/pid_6032/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 6870): TimaSignature is unavailable
,D/ActivityThread( 6870): Added TimaKeyStore provider
,I/PCWCLIENTTRACE_LOG( 6854): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 6854): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 6854): new DMDBOpenHelper instance
,D/Launcher.Model( 1463): reloadBadges entered.
,D/BadgeProvider( 6787): sendNotify entered. [uri] : content://com.sec.badge/apps
D/BadgeProvider( 6787): sendNotify, [notify] : null
D/BadgeProvider( 6787): update, [uri] : content://com.sec.badge/apps
D/BadgeProvider( 6787): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 6787): update, [UpdateCount] : 1
,D/[0]UMC:DeviceInfo( 6839): USA==US==
,I/PCWCLIENTTRACE_PushUtil( 6854): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6854): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 6854): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6854): [onReceive] - android.intent.action.PACKAGE_REMOVED
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6885): MountEmulatedStorage()
E/Zygote  ( 6885): v2
I/libpersona( 6885): KNOX_SDCARD checking this for 10032
I/libpersona( 6885): KNOX_SDCARD not a persona
I/SELinux ( 6885): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1013): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6885 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/SELinux ( 6885): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1013): Killing 5362:com.osp.app.signin/u0a41 (adj 15): empty #31
E/SELinux ( 6885): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6885): TimaSignature is unavailable
,D/ActivityThread( 6885): Added TimaKeyStore provider
,D/Mms/MmsApp( 6722): [start]    initCountryIso consume time = 690.362604
,D/CountryDetector( 1013): The first listener is added
,E/PhotosPlugin( 6870): Loading PhotosPlugin
,D/Mms/MmsApp( 6722): [end]    initCountryIso consume time = 12.844271,
D/Mms/MmsConfig( 6722): [start]    MmsConfig.init() consume time = 0.169688
,D/Mms/MmsConfig( 6722): before partial update
,D/Mms/MmsConfig( 6722): Load Resize quality : 80
,D/EasySignUpManager_1.0.1( 6722): serviceId : 1, features : -1
,D/EasySignUpManager_1.0.1( 6722): isAuth is false,
D/Mms/MmsConfig( 6722): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,D/TP/MmsSmsProvider( 1437): query,matched:2117, calling pid = 6722
,D/TP/MmsSmsProvider( 1437): match 2117:Elapsed time : 2.622 ms
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/FeatureConfig( 6885): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,W/libprocessgroup( 1013): failed to open /acct/uid_10034/pid_6057/cgroup.procs: No such file or directory
,E/SQLiteLog( 6160): (28) failed to open "/data/data/com.sec.spp.push/databases/registration_db" with flag (131138) and mode_t (0) due to error (30)
,E/Zygote  ( 6905): MountEmulatedStorage()
E/Zygote  ( 6905): v2
I/libpersona( 6905): KNOX_SDCARD checking this for 10035
I/libpersona( 6905): KNOX_SDCARD not a persona
,I/SELinux ( 6905): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6905): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6905): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,E/SQLiteDatabase( 6160): Failed to open database '/data/data/com.sec.spp.push/databases/registration_db'.
E/SQLiteDatabase( 6160): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6160): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6160): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6160): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6160): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6160): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6160): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6160): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6160): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6160): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6160): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6160): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6160): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6160): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6160): 	at com.sec.spp.push.i.a.a(Unknown Source)
E/SQLiteDatabase( 6160): 	at com.sec.spp.push.i.c.d(Unknown Source)
E/SQLiteDatabase( 6160): 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
E/SQLiteDatabase( 6160): 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
E/SQLiteDatabase( 6160): 	at com.sec.spp.push.receiver.a.handleMessage(Unknown Source)
E/SQLiteDatabase( 6160): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6160): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6160): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6160): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6160): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6160): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6160): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/SPPClientService( 6160): [c] [getAppId()] SQLiteException with message =not an error (code 0): Could not open the database in read/write mode.
I/ActivityManager( 1013): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6905 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1013): Killing 6269:com.sec.android.cloudagent/u0a2 (adj 15): empty #31
,D/EasySignUpManager_1.0.1( 6722): isAuth is false
D/EasySignUpManager_1.0.1( 6722): getServiceStatus : serviceId (1) is OFF
,E/CscParser( 6722): mps_code.dat does not exist
E/CscParser( 6722): customer_path =/system/csc/customer.xml
E/CscParser( 6722): fileName + /system/csc/customer.xml
,W/ResourcesManager( 6885): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6885): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6885): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6885): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6885): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6885): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 6905): TimaSignature is unavailable
,D/ActivityThread( 6905): Added TimaKeyStore provider
,E/CscParser( 6722): mps_code.dat does not exist
E/CscParser( 6722): customer_path =/system/csc/customer.xml
E/CscParser( 6722): fileName + /system/csc/customer.xml

```
