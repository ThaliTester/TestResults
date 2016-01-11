#### Test 549702617e2936d_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
D/Mms/DraftCache( 5777): [end]    rebuildCache consume time = 40.814375
E/PhotosPlugin( 5874): Loading PhotosPlugin
--------- beginning of system
W/ResourcesManager( 5931): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5931): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
I/DBG_POLICYDM( 5844): [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
D/ComposerPerformance( 5777): 1452525629414 ms / [DONE] Composer constructor
E/CII     ( 5777): CommonIMSInterface: VoLTE CSC feature disabled.
I/Mms/ReservationManager( 5777): ReservationManager()
I/Mms/ReservationManager( 5777): resetAfterConnected()
D/TP/MmsSmsProvider( 1451): query,matched:7, calling pid = 5777
D/Mms/Conversation( 5777): [start]    init() consume time = 55.622604
D/TP/MmsSmsProvider( 1451): match 7:Elapsed time : 1.876 ms
D/TP/MmsSmsProvider( 1451): deleteConversation threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1451): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1451): updateThread(), thread_id = 9223372036854775807
I/Mms/ReservationManager( 5777): getReservedSendMessageCount(): retMessageCount=0
V/TP/MmsSmsDatabaseHelper( 1451): sUpgradeVersion = 0, db.getVersion() = 81
D/Mms/MmsApp( 5777): [end]    onCreate() consume time = 7.641198
D/TP/MmsSmsProvider( 1451): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1451): need read changed broadcast:false
D/Mms/Conversation( 5777): [end]    init consume time = 5.6825
D/Mms/MessagingNotification( 5777): [start]    init() consume time = 6.463386
D/Mms/MessagingNotification( 5777): [end]    init consume time = 3.080416
D/TP/MmsSmsProvider( 1451): query,matched:0, calling pid = 5777
V/TP/MmsSmsProvider( 1451): getSimpleConversations entered.
D/Mms/SpamFilter( 5777): [start]    SpamFilter fill() begin consume time = 5.846875
D/TP/MmsSmsProvider( 1451): match 0:Elapsed time : 2.313 ms
D/Mms/DownloadManager( 5777): Service state changed: Bundle[mParcelledData.dataSize=744]
D/Mms/DownloadManager( 5777): roaming ------> false, mSimSlot = 0
D/Mms/Synchronizer( 5777): [start]    doSync consume time = 16.165469
D/Mms/MethodReflector( 5777): getSubId is called
D/Mms/TelephonyUtils( 5777): getLongSubId from simSlot 0, return Value = -1
D/TP/MmsSmsProvider( 1451): update, matched:300, calling pid = 5777
V/TP/MmsSmsProvider( 1451): syncDBData start
V/TP/MmsSmsProvider( 1451): syncDBData sms end
V/TP/MmsSmsProvider( 1451): syncDBData mms end
V/TP/MmsSmsProvider( 1451): syncDBData end
D/TP/MmsSmsProvider( 1451): query,matched:400, calling pid = 5777
I/DBG_POLICYDM( 5844): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
D/Mms/MethodReflector( 5777): getTelephonyProperty is called
D/Mms/DownloadManager( 5777): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5777): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5777): auto download without roaming -> true
D/Mms/DownloadManager( 5777): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5777): mAutoDownload ------> true
D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
D/Mms/Synchronizer( 5777): [end]    doSync consume time = 10.647604
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/Mms/FreeMessageStatusReceiver( 5777): onReceive, action : android.intent.action.PACKAGE_ADDED
I/DBG_POLICYDM( 5844): [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
E/Zygote  ( 5955): MountEmulatedStorage()
E/Zygote  ( 5955): v2
I/libpersona( 5955): KNOX_SDCARD checking this for 10072
I/libpersona( 5955): KNOX_SDCARD not a persona
I/SELinux ( 5955): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5955): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5955 uid=10072 gids={50072, 9997} abi=armeabi-v7a
E/SELinux ( 5955): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1015): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
E/SMD     (  286): DCD OFF
D/Mms/SpamFilter( 5777): [end]    SpamFilter fill() finished consume time = 27.740469
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/ServiceManager(  324): Waiting for service AtCmdFwd...
D/TimaKeyStoreProvider( 5955): TimaSignature is unavailable
D/ActivityThread( 5955): Added TimaKeyStore provider
E/Zygote  ( 5970): MountEmulatedStorage()
E/Zygote  ( 5970): v2
I/libpersona( 5970): KNOX_SDCARD checking this for 10047
I/libpersona( 5970): KNOX_SDCARD not a persona
I/SELinux ( 5970): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/DBG_POLICYDM( 5844): [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
I/ActivityManager( 1015): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5970 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
D/Mms/ArtClassLoader( 5777): init [DONE] art
I/SELinux ( 5970): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5970): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
I/wpa_supplicant( 2074): nl80211: Received scan results (4 BSSes)
D/WifiP2pService( 1015): InactiveState{ what=147461 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147461 }
D/WifiP2pService( 1015): DefaultState{ what=147461 }
D/TimaKeyStoreProvider( 5970): TimaSignature is unavailable
D/ActivityThread( 5970): Added TimaKeyStore provider
D/BadgeProvider( 5955): onCreate
D/BadgeProvider( 5955): DatabaseHelper
D/Mms/FreeMessageReceiverService( 5777): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 5777): onHandleIntent: ACTION_PACKAGE_ADDED
W/ResourcesManager( 5970): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5970): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5970): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/ActivityManager( 1015): Killing 5251:com.google.android.talk/u0a104 (adj 15): empty #31
I/ActivityManager( 1015): Killing 5331:com.android.providers.calendar/u0a42 (adj 15): empty #32
D/Mms/MessagingNotification( 5777): checkBadgeCount unreadCount=0 badgeCount=0
D/TP/SmsProvider( 1451): query,matched:26, calling pid = 5777
D/TP/SmsProvider( 1451): match 26:Elapsed time : 1.703 ms
D/TP/MmsSmsProvider( 1451): query,matched:6, calling pid = 5777
D/TP/MmsSmsProvider( 1451): match 6:Elapsed time : 1.640 ms
D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1015): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5986 uid=10025 gids={50025, 9997} abi=armeabi-v7a
E/Zygote  ( 5986): MountEmulatedStorage()
I/libpersona( 5986): KNOX_SDCARD checking this for 10025
E/Zygote  ( 5986): v2
I/libpersona( 5986): KNOX_SDCARD not a persona
I/SELinux ( 5986): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5986): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5986): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5986): TimaSignature is unavailable
D/ActivityThread( 5986): Added TimaKeyStore provider
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1015): Killing 5389:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/libprocessgroup( 1015): failed to open /acct/uid_10104/pid_5251/cgroup.procs: No such file or directory
W/ResourcesManager( 5986): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/ChimeraCfgMgr( 2004): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2004): Module APK com.google.android.play.games already loaded
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/OMACP   ( 5986): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
D/MyFiles ( 5970): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
W/libprocessgroup( 1015): failed to open /acct/uid_10042/pid_5331/cgroup.procs: No such file or directory
D/Mms/Omacp( 5777): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
E/installd(  282): system dir 0 : /system/app/
E/installd(  282): system dir 1 : /system/priv-app/
E/installd(  282): system dir 2 : /vendor/app/
E/installd(  282): system dir 3 : /oem/app/
W/libprocessgroup( 1015): failed to open /acct/uid_10057/pid_5389/cgroup.procs: No such file or directory
I/TactileAssist( 1015): enable value -1
I/TactileAssist( 1015): internal enable value -1
I/TactileAssist( 1015): intensity value -1
I/TactileAssist( 1015): saveAppList value true
I/TactileAssist( 1015): List of disabled apps :
D/ChimeraCfgMgr( 2004): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/AsyncTaskServiceImpl( 2004): Submit a task: k
I/OMACP   ( 5986): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
E/Zygote  ( 6007): MountEmulatedStorage()
I/libpersona( 6007): KNOX_SDCARD checking this for 10053
E/Zygote  ( 6007): v2
I/libpersona( 6007): KNOX_SDCARD not a persona
I/OMACP   ( 5986): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
I/SELinux ( 6007): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/OMACP   ( 5986): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
I/OMACP   ( 5986): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
I/OMACP   ( 5986): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
D/PackageManager( 1015): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
I/OMACP   ( 5986): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
I/SELinux ( 6007): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/OMACP   ( 5986): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
E/SELinux ( 6007): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/OMACP   ( 5986): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
I/OMACP   ( 5986): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
I/OMACP   ( 5986): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
I/ActivityManager( 1015): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=6007 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 6007): TimaSignature is unavailable
D/ActivityThread( 6007): Added TimaKeyStore provider
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ResourcesManager( 6007): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/Compatibility( 6007): onReceive() it will make start service
D/ActivityManager( 1015): startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/Compatibility( 6007): onHandleIntent()
D/Compatibility( 6007): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10175, android.intent.extra.user_handle=0}]
D/Compatibility( 6007): found: 2
D/ChimeraCfgMgr( 2004): Loading module com.google.android.gms.gass from APK com.google.android.gms
I/libpersona( 6026): KNOX_SDCARD checking this for 10057
I/OMACP   ( 5986): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
I/libpersona( 6026): KNOX_SDCARD not a persona
I/OMACP   ( 5986): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
I/OMACP   ( 5986): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
E/Zygote  ( 6026): MountEmulatedStorage()
E/Zygote  ( 6026): v2
I/SELinux ( 6026): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6026): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6026): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/ChimeraCfgMgr( 2004): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Compatibility( 6007): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 6007): skipping ResolveInfo{d4ef056 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 6007): considering ResolveInfo{305ab8d7 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 6007): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/k       ( 2004): Processing package: com.test.thalitest
I/ActivityManager( 1015): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6026 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
D/Compatibility( 6007): enabling receiver ResolveInfo{83c65c4 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Compatibility( 6007): enabling receiver ResolveInfo{22513cad com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/TimaKeyStoreProvider( 6026): TimaSignature is unavailable
D/ActivityThread( 6026): Added TimaKeyStore provider
D/Compatibility( 6007): enabling receiver ResolveInfo{37e1bbe2 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Compatibility( 6007): enabling receiver ResolveInfo{5280b73 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 6007): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
W/BaseAppContext( 2004): Using Auth Proxy for data requests.
W/BaseAppContext( 2004): Using Auth Proxy for data requests.
I/DBG_POLICYDM( 5844): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/GassUtils( 2004): Found app info for package com.test.thalitest:18. Hash: 82ccbc74df315987b7be206c22ec4eaa3ab0d49235c4895536307c8f71b675fe
D/k       ( 2004): Found info for package com.test.thalitest in db.
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1015): Killing 5450:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
I/DBG_POLICYDM( 5844): [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.internal.SharedPreferencesService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/BaseAppContext( 2004): Using Auth Proxy for data requests.
D/ActivityManager( 1015): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
I/SL_DEBUG( 5931): isLoggable:: isProductShip = 1
W/libprocessgroup( 1015): failed to open /acct/uid_10069/pid_5450/cgroup.procs: No such file or directory
I/SL_DEBUG( 5931): isLoggable:: SL_DEBUG_EXIST = false
W/BaseAppContext( 2004): Using Auth Proxy for data requests.
I/art     ( 1866): Explicit concurrent mark sweep GC freed 48850(2MB) AllocSpace objects, 15(480KB) LOS objects, 39% free, 12MB/21MB, paused 1.425ms total 82.188ms
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
I/PeopleDatabaseHelper( 2004): cleanUpNonGplusAccounts done.
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/UpdateIcingCorporaServi( 6026): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/BaseAppContext( 2004): Using Auth Proxy for data requests.
W/BaseAppContext( 2004): Using Auth Proxy for data requests.
W/BaseAppContext( 2004): Using Auth Proxy for data requests.
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5931): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5931): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
D/LocationManagerService( 1015): getProviders()=[passive]
D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6068): MountEmulatedStorage()
I/ActivityManager( 1015): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=6068 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 6068): v2
I/libpersona( 6068): KNOX_SDCARD checking this for 10041
I/libpersona( 6068): KNOX_SDCARD not a persona
I/SELinux ( 6068): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6068): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6068): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6068): TimaSignature is unavailable
D/ActivityThread( 6068): Added TimaKeyStore provider
I/art     (  304): Explicit concurrent mark sweep GC freed 8708(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 677us total 28.860ms
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 610us total 18.407ms
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 619us total 17.711ms
I/UpdateIcingCorporaServi( 6026): UpdateCorporaTask done [took 154 ms] updated apps [took 154 ms] 
I/SA      ( 6068): [SSP] onCreated
I/SA      ( 6068): [TPM] There is no property file
I/SA      ( 6068): [SCU] isHaveSA() - false
I/ServiceManager(  324): Waiting for service AtCmdFwd...
I/SA      ( 6068): [TPM] getModelProperty : null
I/SA      ( 6068): [TPM] getCSCProperty : null
I/SA      ( 6068): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 6068): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 6068): [DM] TFT FEATURE: false
I/SA      ( 6068): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 6068): [DM] init START
I/SA      ( 6068): [DM] This device is not a Vodafone
W/ResourceType( 6068): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 6068): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 6068): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 6068): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 6068): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 6068): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 6068): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 6068): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 6068): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 6068): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 6068): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 6068): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 6068): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 6068): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 6068): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 6068): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 6068): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
W/ResourceType( 6068): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 6068): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 6068): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 6068): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 6068): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 6068): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 6068): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 6068): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
I/ActivityManager( 1015): Killing 5481:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
I/SA      ( 6068): [SCU] isHaveSA() - false
I/SA      ( 6068): support phone number id : false
I/SA      ( 6068): [DM] Supports Ref Jpn : true
I/SA      ( 6068): [DM] init END
I/SA      ( 6068): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
I/SA      ( 6068): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10175 extra.user_handle.:0 ]
I/ActivityManager( 1015): Killing 5497:com.google.android.apps.plus/u0a120 (adj 15): empty #31
W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/art     ( 1015): Explicit concurrent mark sweep GC freed 227220(14MB) AllocSpace objects, 4(4MB) LOS objects, 33% free, 27MB/41MB, paused 3.040ms total 183.853ms
I/ActivityManager( 1015): Killing 5087:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
W/GAV2    ( 5874): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/AndroidRuntime( 6063): 
D/AndroidRuntime( 6063): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6063): CheckJNI is OFF
D/AndroidRuntime( 6063): readGMSProperty: start
D/AndroidRuntime( 6063): readGMSProperty: already setted!!
D/AndroidRuntime( 6063): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6063): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6063): readGMSProperty: end
D/AndroidRuntime( 6063): addProductProperty: start
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5481/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10120/pid_5497/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10150/pid_5087/cgroup.procs: No such file or directory
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6106): MountEmulatedStorage()
E/Zygote  ( 6106): v2
I/libpersona( 6106): KNOX_SDCARD checking this for 10100
I/libpersona( 6106): KNOX_SDCARD not a persona
I/SELinux ( 6106): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6106): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6106): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=6106 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 5630:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
D/ActivityManager( 1015): startService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.apps.docs
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.ContentSyncService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
D/TimaKeyStoreProvider( 6106): TimaSignature is unavailable
D/ActivityThread( 6106): Added TimaKeyStore provider
W/GAV2    ( 5874): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1866): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PackageIntentReceiver( 6106): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 6106): Not GearManger package! 
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6129): MountEmulatedStorage()
E/Zygote  ( 6129): v2
I/libpersona( 6129): KNOX_SDCARD checking this for 1000
I/SELinux ( 6129): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 6129): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=6129 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 6129): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
W/libprocessgroup( 1015): failed to open /acct/uid_10040/pid_5630/cgroup.procs: No such file or directory
E/SELinux ( 6129): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/AccountFeatureHelper( 5874): Write apps_features disabled false
D/TimaKeyStoreProvider( 6129): TimaSignature is unavailable
D/ActivityThread( 6129): Added TimaKeyStore provider
E/AffinityControl( 6063): AffinityControl: registerfunction enter
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/AndroidRuntime( 6063): Calling main entry com.android.commands.am.Am
E/Zygote  ( 6145): MountEmulatedStorage()
E/Zygote  ( 6145): v2
I/libpersona( 6145): KNOX_SDCARD checking this for 1000
I/SELinux ( 6145): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 6145): KNOX_SDCARD not a persona
I/SELinux ( 6145): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6145 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/PersonaManagerService( 1015): inState():  stateMachine is null !!
I/ActivityManager( 1015): Killing 4454:com.google.android.music:main/u0a111 (adj 15): empty #31
I/PersonaManagerService( 1015): PersonaId don't exist
I/ActivityManager( 1015): do not start freezing screen for locked container getKeyguardshowstate = false
E/SELinux ( 6145): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/ActivityManager( 1015): mDVFSHelper.acquire()
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 6145): TimaSignature is unavailable
D/PhoneWindow( 1015): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1015): *FMB* installDecor flags : 25362712
D/ActivityThread( 6145): Added TimaKeyStore provider
I/Icing   ( 2004): Indexing 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28 from com.google.android.gms
E/Zygote  ( 6163): MountEmulatedStorage()
E/Zygote  ( 6163): v2
I/libpersona( 6163): KNOX_SDCARD checking this for 10175
I/libpersona( 6163): KNOX_SDCARD not a persona
I/SELinux ( 6163): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/PhoneWindow( 1015): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1015): *FMB* isFloatingMenuEnabled return false
I/ActivityManager( 1015): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6163 uid=10175 gids={50175, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/SurfaceFlinger(  256): id=13 createSurf (1x1),1 flag=404, uhalitest
I/SELinux ( 6163): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6163): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/InputDispatcher( 1015): Focused application set to: xxxx
D/InputDispatcher( 1015): Focus left window: 3087
D/TimaKeyStoreProvider( 6163): TimaSignature is unavailable
D/AndroidRuntime( 6063): Shutting down VM
D/ActivityThread( 6163): Added TimaKeyStore provider
D/ChimeraCfgMgr( 2004): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2004): Module APK com.google.android.play.games already loaded
D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
V/ActivityManager( 1015): Display changed displayId=0
D/StatusBarManagerService( 1015): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1015): isKioskContainerExistOnDevice
W/libprocessgroup( 1015): failed to open /acct/uid_10111/pid_4454/cgroup.procs: No such file or directory
V/ActivityThread( 3087): updateVisibility : ActivityRecord{2e97a907 token=android.os.BinderProxy@f9cb7aa {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
W/GAV2    ( 5874): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager( 1015): Killing 4824:com.sec.android.widgetapp.SPlannerAppWidget/u0a134 (adj 15): empty #31
I/SurfaceFlinger(  256): id=10 Removed YUIInstallC (5/9)
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
I/SurfaceFlinger(  256): id=10 Removed YUIInstallC (-2/9)
D/AcmsPackageEventListener( 6145): Received: android.intent.action.PACKAGE_ADDED
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
W/ContextImpl( 6145): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
E/Zygote  ( 6185): MountEmulatedStorage()
E/Zygote  ( 6185): v2
I/libpersona( 6185): KNOX_SDCARD checking this for 10120
I/libpersona( 6185): KNOX_SDCARD not a persona
I/SELinux ( 6185): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6185): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6185 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 6185): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Killing 5310:com.android.calendar/u0a135 (adj 15): empty #31
D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
D/AcmsService( 6145): Enter Oncreate
D/TimaKeyStoreProvider( 6185): TimaSignature is unavailable
D/ActivityThread( 6185): Added TimaKeyStore provider
D/AcmsServiceMonitor( 6145): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 6145): creating AcmsCore
D/AcmsCore( 6145): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 6145): AcmsCore
D/AcmsCore( 6145): init
D/AcmsCore( 6145): Looper handler is not null
D/AcmsCore( 6145): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6145): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6145): Incrementing - Counter value: 1
D/AcmsCore( 6145): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsService( 6145): onStartCommand
D/AcmsService( 6145): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 6145): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 6145): Incrementing - Counter value: 2
D/AcmsService( 6145): Incremented Counter Value : onStartCommand
I/Icing   ( 2004): Indexing done 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28
W/ResourcesManager( 6185): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/AcmsCertificateMngr( 6145): AcmsCertificateMngr
D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
D/ActivityThread( 6145): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
D/AcmsRevocationMngr( 6145): AcmsRevocationMngr
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/WebViewFactory( 6163): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
D/AcmsService( 6145): Inside handle Intent
D/AcmsService( 6145): App added - package name: com.test.thalitest
D/AcmsCore( 6145): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6145): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6145): Incrementing - Counter value: 3
D/AcmsCore( 6145): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 6145): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 6145): Decrementing - Counter value: 2
W/art     ( 6063): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
I/LibraryLoader( 6163): Time to load native libraries: 3 ms (timestamps 1311-1314)
I/LibraryLoader( 6163): Expected native library version number "",actual native library version number ""
W/libprocessgroup( 1015): failed to open /acct/uid_10134/pid_4824/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10135/pid_5310/cgroup.procs: No such file or directory
,V/WebViewChromiumFactoryProvider( 6163): Binding Chromium to main looper Looper (main, tid 1) {83c65c4}
,I/LibraryLoader( 6163): Expected native library version number "",actual native library version number ""
,I/chromium( 6163): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/Mms/MmsApp( 5777):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 5777): [start]    fillCache consume time = 1926.357864
,D/Mms/ComposeMessageFragment( 5777): fillCache, easy = false
,I/BrowserStartupController( 6163): Initializing chromium process, singleProcess=true
,W/art     ( 6163): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6163): ApplicationContext is null in ApplicationStatus
,W/chromium( 6163): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
I/chromium( 6163): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
I/chromium( 6163): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
I/Adreno-EGL( 6163): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6163): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6163): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6163): Local Branch: 
I/Adreno-EGL( 6163): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6163): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6163):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/AbsListView( 5777): Get MotionRecognitionManager
,D/MotionRecognitionService( 1015):  ssp status : false
,D/Mms/ComposeMessageFragment( 5777): [end]    fillCache consume time = 125.539948
,W/art     ( 5777): Suspending all threads took: 9.954ms
D/ActivityManager( 1015): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,W/chromium( 6163): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,W/art     ( 6163): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6163): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 6163): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 6163): *FMB* installDecor flags : 8456448
,D/Mms/BubbleViewCache( 5777): fillCache bubble = 1
I/splitIntent( 1015): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
W/ActivityManager( 1015): Activity pause timeout for ActivityRecord{1b20f79e u0 com.test.thalitest/.MainActivity t3}
,D/SystemWebViewEngine( 6163): CordovaWebView is running on device made by: samsung
,W/art     ( 6163): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6163): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6163): Render dirty regions requested: true
,D/ActivityManager( 1015): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1015): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1015): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1015): handleActiveUserChange for user 0
D/PersonaManagerService( 1015): getPersonasForUser(): returning null!
,V/ActivityThread( 6163): updateVisibility : ActivityRecord{2aa26f60 token=android.os.BinderProxy@3734e192 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PhoneWindow( 6163): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 6163): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  256): id=14 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1015): Focus entered window: 6163
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 6163): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 6163): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6163): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 6163): Enabling debug mode 0
,I/ActivityManager( 1015): Killing 5138:com.google.android.gm/u0a101 (adj 15): empty #31
,D/InputMethodManagerService( 1015): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/StatusBar( 1176): Icon Only
I/Timeline( 6163): Timeline: Activity_idle id: android.os.BinderProxy@3734e192 time:81777
,D/PanelView( 1176): There is/are notification(s) 
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 6163): showStatusIcon on inactive InputConnection
,I/SamsungIME( 1813): getCurrentCandidateView
,I/ActivityManager( 1015): Displayed Component not be shown by security: +654ms (total +743ms)
,I/Timeline( 1015): Timeline: Activity_windows_visible id: ActivityRecord{1b20f79e u0 com.test.thalitest/.MainActivity t3} time:81793
W/ActivityManager( 1015): mDVFSHelper.release()
,I/SurfaceFlinger(  256): id=13 Removed uhalitest (7/9)
,I/SurfaceFlinger(  256): id=13 Removed uhalitest (-2/9)
,W/BindingManager( 6163): Cannot call determinedVisibility() - never saw a connection for the pid: 6163
,W/libprocessgroup( 1015): failed to open /acct/uid_10101/pid_5138/cgroup.procs: No such file or directory
,D/SamsungIME( 1813): Dismiss ExpandCandiate
,D/JsMessageQueue( 6163): Set native->JS mode to OnlineEventsBridgeMode
,I/SamsungIME( 1813): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1813): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1813): KeybaordView init() : load resources
,D/jxcore_app_log( 6163): JniHelper::setJavaVM(0xb7f43450), pthread_self() = -1203160368
,D/JX-Cordova( 6163): jxcore cordova android initializing
,I/SamsungIME( 1813): getCurrentKeyboard
I/SamsungIME( 1813): getTextKeyboard
,D/SamsungIME( 1813): [SwiftkeyWrapper] currentLangauge : 1701729619
,V/AlarmManager( 1015): waitForAlarm result :4
,D/KeyguardViewMediator( 1176): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/KeyguardViewMediator( 1176): doKeyguard: not showing because lockscreen is off
V/KeyguardEffectViewController( 1176): *** Keyguard wallpaper service already unbounded
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/DBG_POLICYDM( 5844): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5844): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy,
,I/DBG_POLICYDM( 5844): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5844): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts,
,I/DBG_POLICYDM( 5844): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5844): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5844): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,D/SamsungIME( 1813): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/PowerManagerService( 1015): [PWL] Off : 5s ago
,W/jxcore-log( 6163): Initializing JXcore engine
W/jxcore-log( 6163): JXcore engine is ready
,W/jxcore-log( 6163): Starting JXcore engine
,E/audit   ( 1927): type=1400 msg=audit(1452525633.452:205): avc:  denied  { ioctl } for  pid=6163 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1927):  SEPF_SM-A500FU_5.0.2-1_0038
E/audit   ( 1927): type=1300 msg=audit(1452525633.452:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=beff1d58 items=0 ppid=304 ppcomm=main pid=6163 auid=4294967295 uid=10175 gid=10175 euid=10175 suid=10175 fsuid=10175 egid=10175 sgid=10175 fsgid=10175 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1927): type=1320 msg=audit(1452525633.452:205): 
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 5
,W/jxcore-log( 6163): Platform android
W/jxcore-log( 6163): 
W/jxcore-log( 6163): Process ARCH arm
W/jxcore-log( 6163): 
,I/jxcore-log( 6163): JXcore Cordova bridge is ready!
I/jxcore-log( 6163): 
,W/jxcore-log( 6163): JXcore engine is started
,I/Choreographer( 6163): Skipped 130 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6163): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6163): Toggling radios to true
I/jxcore-log( 6163): 
,D/BluetoothAdapter( 6163): enable()
,D/BluetoothAdapter( 6163): enable(): BT is already enabled..!
,D/SecContentProvider( 1015): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1015): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1015): mCursor = null
,D/WifiService( 1015): setWifiEnabled: true pid=6163, uid=10175
,W/ActivityManager( 1015): Permission Denial: getCurrentUser() from pid=6163, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 1015): Failed getting userId using ActivityManagerNative
W/WifiService( 1015): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6163, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1015): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24778)
W/WifiService( 1015): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1015): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1015): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1015): 	at android.os.Binder.execTransact(Binder.java:461)
,D/SettingsProvider( 1015): name = wifi_on
,I/WifiService( 1015): disconnect: pid=6163, uid=10175,
I/jxcore-log( 6163): Radios toggled
I/jxcore-log( 6163): 
I/wpa_supplicant( 2074): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 6163): My device name is: samsung-SM-A500FU
I/jxcore-log( 6163): 
,I/wpa_supplicant( 2074): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1,
I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 2074): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 2074): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
D/Tethering( 1015): InitialState.processMessage what=4,
I/wpa_supplicant( 2074): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 2074): wlan0: State: DISCONNECTED -> DISCONNECTED
E/wpa_supplicant( 2074): Cmd 35605 not handled,
D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false
E/WifiStateMachine( 1015): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 2074): reset timer : RESET_TIMER 0
,I/wpa_supplicant( 2074): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 2074): P2P: Current p2p state = IDLE
I/wpa_supplicant( 2074): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 2074): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 2074): First Scan Start
,I/wpa_supplicant( 2074): Scan requested (ret=0) - scan timeout 30 seconds
E/Tethering( 1015): No numeric data
,I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1015): clearTetheredNotification()
,E/WifiConfigStore( 1015): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,V/NetworkStats( 1015): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1015): UpdateStatsForKnox main else ---
,D/HotspotTile( 1176): onReceive : android.net.conn.TETHER_STATE_CHANGED
,D/HotspotTile( 1176): updateTetherState():false, false
,D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
,V/NetworkStats( 1015): performPollLocked() took 7ms
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,E/WifiNative-wlan0( 1015): do suspend true
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/WifiP2pService( 1015): InactiveState{ what=143375 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=143375 }
,D/CommandListener(  276): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1866): Read error: ssl=0xb8482c58: I/O error during system call, Connection timed out,
E/ConnectivityService( 1015): updateNetworkInfo()
,D/ConnectivityService( 1015): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps],
,E/ConnectivityService( 1015): updateNetworkInfo()
D/ConnectivityService( 1015): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
V/NativeCrypto( 1866): SSL shutdown failed: ssl=0xb8482c58: I/O error during system call, Broken pipe
E/WifiStateMachine( 1015): Start Disconnecting Watchdog 1
D/StatusBar.NetworkController( 1176): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/wpa_supplicant( 2074): wlan0: Setting scan request: 0 sec 0 usec
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14952 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
,I/WifiTrafficPoller( 1015): evaluateTrafficStatsPolling,
,E/WifiNative-wlan0( 1015): do suspend true,
D/WifiP2pService( 1015): InactiveState{ what=143375 }
D/WifiP2pService( 1015): P2pEnabledState{ what=143375 },
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): ValidatedState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService( 1015): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): DefaultState{ when=-2ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
I/System.out( 1015): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1015): Tagging socket 360 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1015, getuid(): 1000
,I/qtaguid ( 1015): Untagging socket 360
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
,I/System.out( 1015): (HTTPLog)-Static: isSBSettingEnabled false
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/CommandListener(  276): Clearing all IP addresses on wlan0
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ConnectivityService( 1015): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,D/ConnectivityService( 1015): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,D/EntConnectivity( 1015): Not allowed due to - mEnabled false - primarySimSlot false
D/ConnectivityService( 1015): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WIFI_P2P( 1015): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/CSLegacyTypeTracker( 1015): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 1015): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,D/ConnectivityService( 1015): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1176): CM callback handler got msg 524292
,I/WifiTrafficPoller( 1015): evaluateTrafficStatsPolling
,D/EnterpriseController(  276): uids 1000
D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 0 for uid 1000
,D/WifiNetworkAgent( 1015): NetworkAgent: NetworkAgent channel lost
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Validated
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): ValidatedState{ when=-5ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyNetworkFactory( 1451): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/TelephonyNetworkFactory( 1451): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WIFI    ( 1015): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1015): mCursor = null
,D/ConnectivityManager.CallbackHandler( 2004): CM callback handler got msg 524292
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1015): mCursor = null
,D/ConnectivityService( 1015): nai.networkMonitor.doQuit()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): doQuit - quitNow()
,D/EntConnectivity( 1015): Not allowed due to - mEnabled false - primarySimSlot false
,D/Tethering( 1015): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,D/Tethering( 1015): MasterInitialState.processMessage what=3
,V/NetworkStats( 1015): updateIfacesLocked()
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
V/NetworkStats( 1015): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1015): UpdateStatsForKnox main else ---
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
V/NetworkStats( 1015): performPollLocked() took 3ms
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,V/NetworkStats( 1015): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1176): EthernetConnected: false
D/StatusBar.NetworkController( 1176): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1176): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1176): updateDataNetType()
D/StatusBar.NetworkController( 1176): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1176): updateLTEICONDataNetType:0
I/Hs20UtilService( 3536): Starting #8
,D/StatusBar.NetworkController( 1176): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,I/Hs20UtilService( 3536): Message received 5007
,D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/NearbySettings( 1324): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1324): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1324): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1324): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1324): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1324): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1324): MountReceiver.mPrefHandler - 7002
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6249): MountEmulatedStorage(),
,E/Zygote  ( 6249): v2,
I/libpersona( 6249): KNOX_SDCARD checking this for 10104
I/SELinux ( 6249): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 6249): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6249 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a,
,I/SELinux ( 6249): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6249): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/PhoneApp( 1451): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1451): FileWriteThread : threadType = 3
,D/PhoneApp( 1451): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1451): FileWriteThread : threadType = 3
,D/PhoneApp( 1451): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1451): FileWriteThread : threadType = 3
,D/PhoneApp( 1451): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/TimaKeyStoreProvider( 6249): TimaSignature is unavailable
,D/FileWriteThread_Telephony( 1451): FileWriteThread : threadType = 3
D/PhoneApp( 1451): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/ActivityThread( 6249): Added TimaKeyStore provider
D/FileWriteThread_Telephony( 1451): FileWriteThread : threadType = 3
D/PhoneApp( 1451): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1451): FileWriteThread : threadType = 3
D/PhoneApp( 1451): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1451): FileWriteThread : threadType = 3
D/PhoneApp( 1451): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1451): FileWriteThread : threadType = 3
,D/PhoneApp( 1451): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1451): FileWriteThread : threadType = 3
,D/PhoneApp( 1451): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1451): FileWriteThread : threadType = 3
,D/PhoneApp( 1451): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1451): FileWriteThread : threadType = 3
,D/PhoneApp( 1451): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1451): FileWriteThread : threadType = 3
,D/PhoneApp( 1451): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1451): FileWriteThread : threadType = 3
,D/PhoneApp( 1451): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1451): FileWriteThread : threadType = 3
,D/PhoneApp( 1451): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1451): FileWriteThread : threadType = 3
,W/ResourcesManager( 6249): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel   ( 6249): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 6249): MmsConfig.loadMmsSettings
I/Babel   ( 6249): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel   ( 6249): MmsConfig.loadFromDatabase
,E/Babel   ( 6249): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 6249): MmsConfig.loadFromResources
,E/Babel   ( 6249): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 6249): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/Settings( 6249): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,D/ConnectivityService( 1015): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 1015): updateDataUsageMap
,I/DBG_DM  ( 3087): [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,I/DBG_DM  ( 3087): [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,D/GpsLocationProvider( 1015): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/Babel_StickerModule( 6249): App launched.
,W/QCamera2Factory(  281): getCameraInfo: E, camera_id = 0
,W/QCamera2Factory(  281): getCameraInfo: X
,W/QCamera2Factory(  281): getCameraInfo: E, camera_id = 1
,W/QCamera2Factory(  281): getCameraInfo: X
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
I/Hs20UtilService( 3536): Starting #9
,D/NearbySettings( 1324): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1324): DMSUtil.isNetworkConnected - flag-null, state-null
,I/Hs20UtilService( 3536): Message received 5007
,I/NearbySettings( 1324): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1324): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1324): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1324): MountReceiver.onReceive - Set preference state off
,W/VideoCapabilities( 6249): Unrecognized profile 2130706433 for video/avc
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6249): Unsupported mime audio/evrc
,W/AudioCapabilities( 6249): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6249): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 6249): Unsupported mime audio/mpeg-L2
,V/NearbySettings( 1324): MountReceiver.mPrefHandler - 7002
,W/AudioCapabilities( 6249): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6249): Unsupported mime audio/x-ima
,D/AcmsKeyStoreHelper( 6145):  getKeyStoreForApplication Enter
,W/AudioCapabilities( 6249): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6249): Unsupported mime audio/evrc
,W/VideoCapabilities( 6249): Unsupported mime video/wvc1
,W/VideoCapabilities( 6249): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6249): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 6249): Unsupported mime video/wvc1
,W/VideoCapabilities( 6249): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6249): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 6249): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 6249): Unsupported mime video/mp43
,W/VideoCapabilities( 6249): Unsupported mime video/sorenson
,W/VideoCapabilities( 6249): Unsupported mime video/mp4v-esdp
,I/AcmsKeyStoreHelper( 6145): Key Store exist
I/AcmsKeyStoreHelper( 6145): Hence loading the keystore file
,I/VideoCapabilities( 6249): Unsupported profile 4 for video/mp4v-es
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/ActivityManager( 1015): Killing 5699:com.google.android.gms:car/u0a12 (adj 15): empty #31
,D/AcmsKeyStoreHelper( 6145):  getKeyStoreForApplication Exit
,I/AcmsCertificateMngr( 6145): getKeyStoreForApplication success 
D/AcmsCore( 6145): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
,D/AcmsServiceMonitor( 6145): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6145): Decrementing - Counter value: 1
D/AcmsCore( 6145): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 6145): This is NOT a valid MirrorLink app
,D/AcmsCore( 6145): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 6145): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6145): Decrementing - Counter value: 0
,D/AcmsServiceMonitor( 6145): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 6145): getSvcCounter - Counter value: 0
,D/AcmsService( 6145): Enter onDestroy
I/AcmsService( 6145): cleanUp(): inside service clean up
,D/AcmsCore( 6145): AcmsCore: inside DeInit
D/AcmsCore( 6145): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 6145): AcmsCertificateMngr: inside cleanup
,D/AcmsRevocationMngr( 6145): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 6145): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 6145): AppEntryInterface: Inside CleanUp
,D/AcmsServiceMonitor( 6145): getSvcCounter - Counter value: 0
D/AcmsService( 6145): killing acms process
I/Process ( 6145): Sending signal. PID: 6145 SIG: 9
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/wpa_supplicant( 2074): nl80211: Received scan results (7 BSSes)
I/wpa_supplicant( 2074): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 2074): Trying to associate with SSID '4E47373030'
,I/wpa_supplicant( 2074): Trying to associate with  'G700'
I/wpa_supplicant( 2074): Re-associate with C0.AA.48
I/wpa_supplicant( 2074): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 2074): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,D/WifiMonitor( 1015): didn't find BSSID Trying to associate with SSID 'NG700'
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/ActivityManager( 1015): Process ACMS.Process (pid 6145)(adj 0) has died(43,1140)
,D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1015): mCursor = null
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/PCWCLIENTTRACE_PushUtil( 5795): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5795): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5795): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5795): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1015): Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
,I/splitIntent( 1015): finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
I/PCWCLIENTTRACE_SYSTEMReceiver( 5795): noConnectivity : true
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
W/libprocessgroup( 1015): failed to open /acct/uid_10012/pid_5699/cgroup.procs: No such file or directory
,E/Zygote  ( 6292): MountEmulatedStorage()
,E/Zygote  ( 6292): v2
I/libpersona( 6292): KNOX_SDCARD checking this for 10111
I/libpersona( 6292): KNOX_SDCARD not a persona
,I/SELinux ( 6292): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6292 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,I/SELinux ( 6292): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/SELinux ( 6292): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6300): MountEmulatedStorage()
E/Zygote  ( 6300): v2
I/libpersona( 6300): KNOX_SDCARD checking this for 10009
I/libpersona( 6300): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6300 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6300): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6300): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
D/accuweather( 1721): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,E/SELinux ( 6300): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/SMD     (  286): DCD OFF
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 6300): TimaSignature is unavailable
,D/ActivityThread( 6300): Added TimaKeyStore provider
,E/Zygote  ( 6316): MountEmulatedStorage()
E/Zygote  ( 6316): v2
I/libpersona( 6316): KNOX_SDCARD checking this for 10145
I/libpersona( 6316): KNOX_SDCARD not a persona
I/SELinux ( 6316): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 6316): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1015): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6316 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
E/SELinux ( 6316): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/wpa_supplicant( 2074): Cmd 35605 not handled
I/wpa_supplicant( 2074): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 2074): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 2074): Associated with C0.AA.48
I/wpa_supplicant( 2074): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 2074): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 2074): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
D/Tethering( 1015): interfaceLinkStateChanged wlan0, true
D/SecContentProvider2( 1015): mCursor = null
D/Tethering( 1015): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 2074): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 2074): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
I/wpa_supplicant( 2074): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 2074): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 2074): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1015): mCursor = null
I/wpa_supplicant( 2074): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2074): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 2074): Blacklist: Clear (temp) 
,I/wpa_supplicant( 2074): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, true
,D/WifiNative-wlan0( 1015): callSECApiVoid - ID [50]
D/TimaKeyStoreProvider( 6292): TimaSignature is unavailable
E/WifiConfigStore( 1015): setLastSelectedConfiguration -1
,D/Tethering( 1015): interfaceLinkStateChanged wlan0, true
D/Tethering( 1015): interfaceStatusChanged wlan0, true
D/ActivityThread( 6292): Added TimaKeyStore provider
,E/Tethering( 1015): No numeric data
,I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, true
,D/daemonapp( 1296): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 8
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/Tethering( 1015): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1015): clearTetheredNotification()
,D/ConnectivityService( 1015): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1015): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 1015): updateNetworkInfo()
D/ConnectivityService( 1015): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/accuweather( 1721): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
V/NetworkStats( 1015): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/accuweather( 1721): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1721): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1721): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1015): UpdateStatsForKnox main else ---
,V/NetworkStats( 1015): performPollLocked() took 4ms
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/TimaKeyStoreProvider( 6316): TimaSignature is unavailable
,D/ActivityThread( 6316): Added TimaKeyStore provider
,E/WifiConfigStore( 1015): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/HotspotTile( 1176): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1176): updateTetherState():false, false
,E/WifiConfigStore( 1015): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/accuweather( 1721): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1721): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/CommandListener(  276): Setting iface cfg
,E/WifiStateMachine( 1015): Start Dhcp Watchdog 2
W/ResourcesManager( 6316): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6316): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6316): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
W/ResourcesManager( 6316): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/SecContentProvider2( 1015): mCursor = null
W/ResourcesManager( 6316): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.,
I/ActivityManager( 1015): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6338 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Zygote  ( 6338): MountEmulatedStorage(),
E/Zygote  ( 6338): v2
I/libpersona( 6338): KNOX_SDCARD checking this for 10081
I/libpersona( 6338): KNOX_SDCARD not a persona
I/SELinux ( 6338): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 6338): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/WifiNative-wlan0( 1015): do suspend false
,E/SELinux ( 6338): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1015): mCursor = null
D/WifiP2pService( 1015): InactiveState{ what=143375 }
D/WifiP2pService( 1015): P2pEnabledState{ what=143375 }
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 6338): TimaSignature is unavailable
,D/ActivityThread( 6338): Added TimaKeyStore provider
,I/ActivityManager( 1015): Killing 5368:com.samsung.aasaservice/1000 (adj 15): empty #31
,I/KLMS-2.5.183: ( 3556): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 11 16:20:35 GMT+01:00 2016
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.183: ( 3556): KLMSAbstractReciever(): onReceive().END.
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6359 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
,I/KLMS-2.5.183: ( 3556): KLMSIntentService(): onCreate()
,E/Zygote  ( 6359): MountEmulatedStorage()
I/libpersona( 6359): KNOX_SDCARD checking this for 10034
E/Zygote  ( 6359): v2
I/libpersona( 6359): KNOX_SDCARD not a persona
I/SELinux ( 6359): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/MusicStore( 6292): Database version: 108
I/SELinux ( 6359): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6359): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.183: ( 3556): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,I/KLMS-2.5.183: ( 3556): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/art     (  304): Explicit concurrent mark sweep GC freed 8728(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 631us total 31.069ms
,I/KLMS-2.5.183: ( 3556): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.183: ( 3556): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 626us total 18.132ms
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,I/KLMS-2.5.183: ( 3556): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.183: ( 3556): StateImplV2(): networkChangeListener().END
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/TimaKeyStoreProvider( 6359): TimaSignature is unavailable
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 709us total 20.409ms
,D/ActivityThread( 6359): Added TimaKeyStore provider
,I/KLMS-2.5.183: ( 3556): KLMSIntentService(): onDestroy()
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5368/cgroup.procs: No such file or directory
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6384): MountEmulatedStorage()
,E/Zygote  ( 6384): v2
I/libpersona( 6384): KNOX_SDCARD checking this for 10113
I/libpersona( 6384): KNOX_SDCARD not a persona
,I/SELinux ( 6384): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,E/dhcpcd  ( 6380): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
I/SELinux ( 6384): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6384): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/dhcpcd  ( 6380): version 5.5.6 starting
,I/ActivityManager( 1015): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6384 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 4984:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
E/dhcpcd  ( 6380): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider( 6384): TimaSignature is unavailable
,D/ActivityThread( 6384): Added TimaKeyStore provider
,I/SO_AGENT( 6359): [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available,
,I/dhcpcd  ( 6380): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 6380): wlan0: sendmsg: Cannot assign requested address
,I/dhcpcd  ( 6380): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 6380): bssid match
I/dhcpcd  ( 6380): wlan0: rebinding lease of 192.168.1.129
,W/libprocessgroup( 1015): failed to open /acct/uid_10044/pid_4984/cgroup.procs: No such file or directory,
W/ResourcesManager( 6292): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6292): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/SPPClientService( 5902): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/DBG_POLICYDM( 5844): [com.policydm.XDMApplication(503/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/SA      ( 6068): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,I/SA      ( 6068): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 6068): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/DBG_POLICYDM( 5844): [com.policydm.XDMApplication(513/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/DBG_POLICYDM( 5844): [com.policydm.XDMBroadcastReceiver$2(109/run)] network is unserviceable
,I/SA      ( 6068): [SLFUCHKMGR] constructor called
,E/DBG_POLICYDM( 5844): [com.policydm.XDMApplication(477/isNetworkChanged)] network not changed.... 
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/ActivityManager( 1015): startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,D/BadgeProvider( 5955): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/SA      ( 6068): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 6068): [OR] == isSIMCardReady false ==
,I/SA      ( 6068): [SCU] == networkStateCheck == false
,I/SA      ( 6068): [OR] onReceive END
,V/DownloadManager( 1226): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,V/JNIHelp ( 6292): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/Launcher.Model( 1477): reloadBadges entered.
D/BadgeProvider( 5955): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5955): sendNotify, [notify] : null
D/BadgeProvider( 5955): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5955): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5955): update, [UpdateCount] : 1
,E/SPPClientService( 5902): [[SystemStateMonitorService]] No Active Internet
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6414): MountEmulatedStorage(),
,E/Zygote  ( 6414): v2,
I/libpersona( 6414): KNOX_SDCARD checking this for 1000
,I/SELinux ( 6414): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 6414): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6414 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 6414): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6414): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4342, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): Plugged
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
D/BatteryService( 1015): stay LED for fully charged
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaKeyStoreProvider( 6414): TimaSignature is unavailable
D/ActivityThread( 6414): Added TimaKeyStore provider
,W/ActivityThread( 6292): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6292): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@19609497: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6292): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6292): GMSCore installation verified
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 53618(2MB) AllocSpace objects, 3(96KB) LOS objects, 33% free, 27MB/41MB, paused 2.745ms total 200.176ms
,I/ActivityManager( 1015): Killing 5761:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31,
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/art     ( 6316): Verification of void com.android.email.activity.MessageListItemOuterContainer.reverseSwiping() took 123.623ms
,I/ConfigStore( 6292): Config Database version: 1
,D/SecurityLogAgent( 6414): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6414): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 6414): StateMachine : Current State = 1
,D/SecurityLogAgent( 6414): StateMachine : Changed Current State = 1
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6433): MountEmulatedStorage()
E/Zygote  ( 6433): v2
I/libpersona( 6433): KNOX_SDCARD checking this for 10159
I/libpersona( 6433): KNOX_SDCARD not a persona
,I/SELinux ( 6433): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1015): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6433 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6433): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Killing 4745:com.samsung.android.sm/1000 (adj 15): empty #31
E/SELinux ( 6433): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6433): TimaSignature is unavailable
,D/ActivityThread( 6433): Added TimaKeyStore provider
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_4745/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10152/pid_5761/cgroup.procs: No such file or directory
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6292): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6292): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
W/ContextImpl( 6384): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6292): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6384): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6384): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,I/iu.Environment( 2004): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,I/ActivityManager( 1015): Killing 5408:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,W/ContextImpl( 6384): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/iu.UploadsManager( 2004): num queued entries: 0
,I/iu.UploadsManager( 2004): num updated entries: 0
,I/iu.SyncManager( 2004): NEXT; no task
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1015): getStreamVolume 3 index 0
,I/MediaRouter( 6292): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6292): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,W/libprocessgroup( 1015): failed to open /acct/uid_10015/pid_5408/cgroup.procs: No such file or directory
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6470): MountEmulatedStorage(),
I/libpersona( 6470): KNOX_SDCARD checking this for 10002
E/Zygote  ( 6470): v2
I/libpersona( 6470): KNOX_SDCARD not a persona
,I/SELinux ( 6470): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6470): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 6470): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6470 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 6470): TimaSignature is unavailable
,D/ActivityThread( 6470): Added TimaKeyStore provider
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 6292): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6292): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory( 6292): Using the GMSCore's GoogleHttpClient
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/WebViewFactory( 6384): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,I/LibraryLoader( 6384): Time to load native libraries: 1 ms (timestamps 6677-6678)
,I/LibraryLoader( 6384): Expected native library version number "",actual native library version number ""
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/ActivityManager( 1015): Killing 5071:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6492): MountEmulatedStorage()
E/Zygote  ( 6492): v2
I/libpersona( 6492): KNOX_SDCARD checking this for 1000
I/libpersona( 6492): KNOX_SDCARD not a persona
,I/SELinux ( 6492): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6492): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1015): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6492 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 6492): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/WebViewChromiumFactoryProvider( 6384): Binding Chromium to main looper Looper (main, tid 1) {166d121c}
I/LibraryLoader( 6384): Expected native library version number "",actual native library version number ""
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
I/chromium( 6384): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,D/TimaKeyStoreProvider( 6492): TimaSignature is unavailable
,D/ActivityThread( 6492): Added TimaKeyStore provider
,I/BrowserStartupController( 6384): Initializing chromium process, singleProcess=true
,W/art     ( 6384): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6384): ApplicationContext is null in ApplicationStatus
,W/chromium( 6384): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 6384): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
,I/chromium( 6384): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,I/DIAGMON_AGENT( 6492): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,I/Adreno-EGL( 6384): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6384): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6384): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6384): Local Branch: 
I/Adreno-EGL( 6384): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6384): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6384):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5071/cgroup.procs: No such file or directory
,I/NSApplication( 6384): Starting up...
,W/AudioManagerAndroid( 6384): Requires BLUETOOTH permission
,I/ActivityManager( 1015): Killing 5827:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,I/ActivityManager( 1015): Killing 5809:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #32
,I/DIAGMON_AGENT( 6492): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 6492): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 6492): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6492): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6492): ./extraInfo: <unknown ssid>
,W/DIAGMON_AGENT( 6492): [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,I/ActivityManager( 1015): Killing 5431:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
,W/libprocessgroup( 1015): failed to open /acct/uid_10156/pid_5809/cgroup.procs: No such file or directory
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6527): MountEmulatedStorage(),
I/libpersona( 6527): KNOX_SDCARD checking this for 10125
E/Zygote  ( 6527): v2
I/libpersona( 6527): KNOX_SDCARD not a persona,
I/SELinux ( 6527): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6527 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 6527): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Killing 5519:com.android.vending/u0a28 (adj 15): empty #31
,E/SELinux ( 6527): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5827/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6527): TimaSignature is unavailable
,D/ActivityThread( 6527): Added TimaKeyStore provider
,I/dhcpcd  ( 6380): wlan0: acknowledged 192.168.1.129 from 192.168.1.1
,W/ResourcesManager( 6527): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6527): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6527): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 6527): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6527): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 6527): PeriphStartReceiver.onReceive - no need to start
,I/splitIntent( 1015): Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.,
,I/ActivityManager( 1015): Killing 5465:com.sec.knox.bridge/1000 (adj 15): empty #31
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3536): Starting #10
,I/Hs20UtilService( 3536): Message received 5007
,D/NearbySettings( 1324): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1324): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1324): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1324): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1324): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1324): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1324): MountReceiver.mPrefHandler - 7002
,I/dhcpcd  ( 6380): wlan0: leased 192.168.1.129 for 86400 seconds,
,W/libprocessgroup( 1015): failed to open /acct/uid_10032/pid_5431/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10028/pid_5519/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5465/cgroup.procs: No such file or directory
,W/ProcessCpuTracker( 1015): Skipping unknown process pid 6554
,E/WifiNative-wlan0( 1015): do suspend true
,D/WifiP2pService( 1015): InactiveState{ what=143375 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiStateMachine( 1015): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,E/WifiStateMachine( 1015): VerifyingLinkState enter
,D/WifiNative-wlan0( 1015): callSECApiInt - ID [210]
,E/ConnectivityService( 1015): updateNetworkInfo()
,D/ConnectivityService( 1015): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,D/ConnectivityService( 1015): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 1015): updateDnsLinkProperty: enter,
D/WifiWatchdogStateMachine.DnsPinger( 1015): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 1015): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 1015): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1015): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 1015): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService( 1015): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
V/AlarmManager( 1015): waitForAlarm result :8
,D/ConnectivityService( 1015): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,E/ConnectivityService( 1015): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1015): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService( 1015): LTETest block dns file not exists
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1015): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3536): Starting #11
,I/Hs20UtilService( 3536): Message received 5007
,E/WifiStateMachine( 1015): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/NearbySettings( 1324): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1324): MountReceiver.onReceive - Keep current state
,E/ConnectivityService( 1015): updateNetworkInfo()
,I/WifiTrafficPoller( 1015): evaluateTrafficStatsPolling
,E/ConnectivityService( 1015): updateNetworkInfo()
D/ConnectivityService( 1015): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1015): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1015): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,I/System.out( 1015): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  276): uids 1000
D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 503 for uid 1000
,D/WIFI_P2P( 1015): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/ConnectivityService( 1015):    accepting network in place of null
,D/TelephonyNetworkFactory( 1451): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/TelephonyNetworkFactory( 1451): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker( 1015): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1015): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 1015): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WIFI    ( 1015): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/ActivityManager( 1015): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/ConnectivityService( 1015): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/WifiTrafficPoller( 1015): evaluateTrafficStatsPolling
I/WifiTrafficPoller( 1015): mBoosterFLAG : 0
,I/Hs20UtilService( 3536): Starting #12
,I/WifiTrafficPoller( 1015): current booster mode : FullMode
D/WifiNative-wlan0( 1015): callSECApiVoid - ID [212]
,D/ConnectivityService( 1015): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/EntConnectivity( 1015): Not allowed due to - mEnabled false - primarySimSlot false
,D/ConnectivityManager.CallbackHandler( 1176): CM callback handler got msg 524290
,I/Hs20UtilService( 3536): Message received 5007
,D/ConnectivityManager.CallbackHandler( 2004): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1176): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/Tethering( 1015): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,D/Tethering( 1015): MasterInitialState.processMessage what=3
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
V/NetworkStats( 1015): updateIfacesLocked()
V/NetworkStats( 1015): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1015): UpdateStatsForKnox main else ---
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,V/NetworkStats( 1015): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/NearbySettings( 1324): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NetworkStats( 1015): performPollLocked() took 7ms
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,V/NearbySettings( 1324): DMSUtil.isNetworkConnected - flag-null, state-null
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,I/NearbySettings( 1324): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1324): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1324): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1324): MountReceiver.onReceive - Keep current state
,D/StatusBar.NetworkController( 1176): EthernetConnected: false
,D/StatusBar.NetworkController( 1176): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1176): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1176): updateDataNetType()
D/StatusBar.NetworkController( 1176): NoService, mRoamingIconId = 0
,E/StatusBar.NetworkController( 1176): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1176): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1176): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/NearbySettings( 1324): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1324): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 3536): Starting #13
I/Hs20UtilService( 3536): Message received 5007
,D/WifiStateMachine( 1015): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1015): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1015): mCursor = null
,D/SecContentProvider2( 1015): uri = 15 selection = getToastGravity
,D/SecContentProvider2( 1015): mCursor = null
,D/SecContentProvider2( 1015): uri = 15 selection = getToastGravityXOffset
,D/SecContentProvider2( 1015): mCursor = null
,D/SecContentProvider2( 1015): uri = 15 selection = getToastGravityYOffset
,D/SecContentProvider2( 1015): mCursor = null
,D/SecContentProvider2( 1015): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1015): mCursor = null
,D/SecContentProvider2( 1015): uri = 15 selection = getToastShowPackageNameState,
D/SecContentProvider2( 1015): mCursor = null
,I/System.out( 1015): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/SurfaceFlinger(  256): id=15 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 1015): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015
,D/SRIB_DCS( 1176): log_dcs ThreadedRenderer::initialize entered! 
,D/SSRM:n  ( 1015): SIOP:: AP = 340
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 11 Jan 2016 15:20:37 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452525637784], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452525637689]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Validated
D/ConnectivityService( 1015): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1015): rematching NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1015): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 1015): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1176): CM callback handler got msg 524290
,D/ConnectivityService( 1015): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 2004): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1176): EthernetConnected: false
,D/StatusBar.NetworkController( 1176): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1176): getUpdateDataNetType(): mDataTypeBrand = LTE
,D/StatusBar.NetworkController( 1176): updateDataNetType()
D/StatusBar.NetworkController( 1176): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1176): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1176): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1176): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1015): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1015): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 3087): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/NetworkMonitor( 6292): type=WIFI subType= reason=null isConnected=true
,I/PCWCLIENTTRACE_PushUtil( 5795): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5795): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5795): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5795): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1015): Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
,I/splitIntent( 1015): finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,V/MusicLeanback( 6292): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/accuweather( 1721): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/FOTA_Client( 6300): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1015): mCursor = null
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/daemonapp( 1296): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,I/FOTA_Client( 6300): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,D/SecurityLogAgent( 6414): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6414): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6414): StateMachine : Current State = 1
,D/SecurityLogAgent( 6414): StateMachine : Changed Current State = 1
,D/accuweather( 1721): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1721): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1721): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1721): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
I/FOTA_Client( 6300): [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,W/FOTA_Client( 6300): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,D/accuweather( 1721): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1721): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/WaitQueueForNetworkActivate( 5860): notifyNetworkActivated
,I/KLMS-2.5.183: ( 3556): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 11 16:20:38 GMT+01:00 2016
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,I/DIAGMON_AGENT( 6492): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT( 6492): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6492): ./extraInfo: "NG700"
W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
I/DIAGMON_AGENT( 6492): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.183: ( 3556): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.183: ( 3556): KLMSIntentService(): onCreate()
,I/KLMS-2.5.183: ( 3556): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.183: ( 3556): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.183: ( 3556): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.183: ( 3556): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.183: ( 3556): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.183: ( 3556): StateImplV2(): networkChangeListener().START
,W/ContextImpl( 5860): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/KLMS-2.5.183: ( 3556): NetworkChangeOperations(): uploadRequestLog().START 
W/ActivityManager( 1015): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/QuickConnect( 6527): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6527): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 6527): PeriphStartReceiver.onReceive - no need to start
,I/KLMS-2.5.183: ( 3556): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.5.183: ( 3556): StateImplV2(): networkChangeListener().END
,I/KLMS-2.5.183: ( 3556): KLMSIntentService(): onDestroy()
,W/art     ( 6185): Suspending all threads took: 5.511ms
,I/DBG_POLICYDM( 5844): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5844): [com.policydm.XDMApplication(469/isNetworkChanged)] a previous network is 0, current network is 2
,E/SPPClientService( 5902): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,E/DBG_POLICYDM( 5844): [com.policydm.XDMApplication(471/isNetworkChanged)] network changed.... 
,I/SA      ( 6068): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,I/SA      ( 6068): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 6068): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6068): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 6068): [OR] == isSIMCardReady false ==
,I/SA      ( 6068): [SCU] == networkStateCheck == true
,I/SA      ( 6068): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 6068): isChinaCountryCode : false
I/SA      ( 6068): [SCU] is ChinestModel Data Restricted   : false
,I/SA      ( 6068): [OR] == networkStateCheck true ==
,I/SA      ( 6068): [OR] GetMyCountryZoneTask
,I/SA      ( 6068): [OR] onReceive END
,V/DownloadManager( 1226): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/ActivityManager( 1015): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/DBG_POLICYDM( 5844): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5844): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5844): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/SA      ( 6068): [SRS] prepareGetMyCountryZone
,I/DBG_POLICYDM( 5844): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5844): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5844): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5844): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_POLICYDM( 5844): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,D/SecContentProvider2( 1015): uri = 15 selection = getAppBlockDownloadState
,D/SecContentProvider2( 1015): mCursor = null
,E/DBG_POLICYDM( 5844): [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,I/SA      ( 6068): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/DBG_POLICYDM( 5844): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/SA      ( 6068): [SSP] query invoked
,I/SA      ( 6068): [TPMU] GetMccFromDB : null
,I/SA      ( 6068): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6068): [TPM] isNoProxy(default) : true
,E/File    ( 6068): fail readDirectory() errno=2
,D/ActivityManager( 1015): startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 5860): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5860): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 5860): exit::IDLE
D/InitializeManagerStateMachine( 5860): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5860): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5860): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5860): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5860): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5860): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5860): entry::SUCCESS
D/hcjo    ( 5860): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5860): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 5860): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5860): exit::SUCCESS
D/InitializeManagerStateMachine( 5860): entry::IDLE
,I/iu.Environment( 2004): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2004): num queued entries: 0
,I/iu.UploadsManager( 2004): num updated entries: 0
,I/iu.SyncManager( 2004): NEXT; no task
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1015): Queue : backgroundsplit_2 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,E/SMD     (  286): DCD OFF
,D/EnterpriseController(  276): uids 10012
D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 503 for uid 10012
,D/ConnectivityService( 1015): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,I/SA      ( 6068): [RC New] Execute method=[GET] start
,I/SA      ( 6068): [RC New] Security=[true]
,I/System.out( 6068): Thread-1055(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6068): Thread-1055(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 6068): Thread-1055(ApacheHTTPLog):isShipBuild true
I/System.out( 6068): Thread-1055(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6068): Thread-1055(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  276): uids 10041
D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 503 for uid 10041
,D/ConnectivityService( 1015): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1015): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1176): CM callback handler got msg 524295
D/ConnectivityService( 1015): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1176): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 2004): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 2004): CM callback handler got msg 524295
,D/PackageManager( 1015): [MSG] MCS_UNBIND
,I/ActivityManager( 1015): Killing 5777:com.android.mms/u0a46 (adj 15): empty #31
,I/SA      ( 6068): [RC New] [v2liruge] api execute + 1030
,I/SA      ( 6068): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6068): AsyncTask #1 calls detatch()
,I/SA      ( 6068): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 6068): [OCP] update openData : PL
,I/SA      ( 6068): [TPMU] getNetworkMcc : 
,I/SA      ( 6068): [SCU] saveMccToPreferece Start
,I/SA      ( 6068): [SCU] RegionMCC : 260
,I/SA      ( 6068): [SSP] query invoked
,I/SA      ( 6068): [TPMU] GetMccFromDB : null
,I/SA      ( 6068): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6068): [SCU] saveMccToPreferece End
,I/SA      ( 6068): [RC New] executeRequest [v2liruge] end. 1096
I/SA      ( 6068): [RC New] Execute end
,I/SA      ( 6068): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 6068): [OR] GetMyCountryZoneTask Success
,D/CountryDetector( 1015): No listener is left
,W/libprocessgroup( 1015): failed to open /acct/uid_10046/pid_5777/cgroup.procs: No such file or directory
,I/dhcpcd  ( 6380): wlan0: sending IPv6 Router Solicitation
,V/AlarmManager( 1015): waitForAlarm result :8,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/SurfaceFlinger(  256): id=15 Removed Uoast (8/9)
,I/SurfaceFlinger(  256): id=15 Removed Uoast (-2/9)
,D/PowerManagerService( 1015): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1015) eventTime = 91126
,D/PowerManagerService( 1015): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015 (0x0)
,D/PowerManagerService( 1015): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1015, ws=WorkSource{10054}) (elapsedTime=3485)
,D/ActivityManager( 1015): startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/GAV4    ( 6384): Thread[GAThread,5,main]: No campaign data found.
,E/SMD     (  286): DCD OFF
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1866): callingUid 10012, callindPid: 1866
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/MusicLeanback( 6292): Conditions not met for autocaching.
,I/MusicLeanback( 6292): Stop autocaching.
,E/GmsUtils( 6292): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,E/GmsUtils( 6292): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,I/PowerManagerService( 1015): [PWL] Off : 15s ago
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5795): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5795): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5795): [GetString-S]
,I/ReactiveServiceManager( 5795): Supported : 1
,D/QSEECOMAPI: ( 1015): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1015): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1015): Loaded image: APP id = 11
,D/QSEECOMAPI: ( 1015): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 1015): QSEECom_shutdown_app, app_id = 11
,E/terrier ( 1015): handleString: Failed to handle string(-4)
E/terrier ( 1015): Java_com_android_server_ReactiveService_GetString: error code = [-4]
,D/PCWCLIENTTRACE_SecurePreferencesJNI( 5795): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5795): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5795): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5795): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5795): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 5795): [ensureRegistration] - No Samsung account
,V/AlarmManager( 1015): waitForAlarm result :4
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6607 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 6607): MountEmulatedStorage()
E/Zygote  ( 6607): v2
I/libpersona( 6607): KNOX_SDCARD checking this for 10028
I/libpersona( 6607): KNOX_SDCARD not a persona
,I/SELinux ( 6607): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 6607): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 6607): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: android, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
,I/BackgroundCompactionService( 1015): onStart. jobID=801
,I/BackgroundCompactionService( 1015): onStart done. jobID=801
,I/BackgroundCompactionService( 1015): Execute BGCompaction (type1). (0 times)
,I/BackgroundCompactionService( 1015): compact_memory command done
,D/TimaKeyStoreProvider( 6607): TimaSignature is unavailable
,D/ActivityThread( 6607): Added TimaKeyStore provider
,D/Finsky  ( 6607): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 6607): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6607): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6607): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dhcpcd  ( 6380): wlan0: sending IPv6 Router Solicitation
,D/Finsky  ( 6607): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6607): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 6607): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/ActivityManager( 1015): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/Ads     ( 6607): Skipping gmscore version check
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6607): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager( 1015): Waited long enough for: ServiceRecord{29d6c31d u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,D/Finsky  ( 6607): [1161] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6607): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ActivityManager( 1015): Killing 5970:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,W/libprocessgroup( 1015): failed to open /acct/uid_10047/pid_5970/cgroup.procs: No such file or directory
,E/SMD     (  286): DCD OFF
,I/jxcore-log( 6163): Test app app.js loaded
I/jxcore-log( 6163): 
,I/chromium( 6163): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4347, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate,
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 320
,I/dhcpcd  ( 6380): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 6380): wlan0: no IPv6 Routers available
,D/ActivityManager( 1015): startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.preloadupdate.PreloadUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 5860): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5860): exit::IDLE
D/PreloadUpdateManagerStateMachine( 5860): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5860): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 5860): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5860): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5860): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5860): entry::IDLE
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1015): Plugged,
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD OFF
,E/Watchdog( 1015): !@Sync 3
,V/AlarmManager( 1015): waitForAlarm result :4
,D/SSRM:n  ( 1015): SIOP:: AP = 300
,I/PowerManagerService( 1015): [PWL] Off : 30s ago
,I/Atfwd_Sendcmd(  324): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  324): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  286): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :8
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,V/AlarmManager( 1015): waitForAlarm result :4
,V/AlarmManager( 1015): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManagerEXT( 1015): <AppSync3 Whitelist>
V/AlarmManagerEXT( 1015): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1176): handleTimeUpdate
,D/SecKeyguardClockView( 1176): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1176): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1176): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1176): *** don't update sliding image ***
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 45351(2MB) AllocSpace objects, 12(192KB) LOS objects, 33% free, 27MB/41MB, paused 2.626ms total 147.624ms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1866): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1866): Vacuum at: now=1452525662128 tag=VacuumService
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms,
W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.uploader.UploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SMD     (  286): DCD OFF
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeConfigurator( 1866): Scheduling Phenotype for one-off execution 2223 seconds from now (1452525662662)
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GetConfigurationSnapshotOperation( 1866): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeFlagCommitter( 1866): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1866): Using platform SSLCertificateSocketFactory
,D/LocationManagerService( 1015): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1866): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  276): uids 10012
D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 503 for uid 10012
,I/System.out( 1866): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1866): Tagging socket 82 with tag 1000120100000000{268440065,0} for uid -1, pid: 1866, getuid(): 10012
,I/qtaguid ( 1866): Tagging socket 95 with tag 1000120100000000{268440065,0} for uid -1, pid: 1866, getuid(): 10012
,D/FactoryTest( 5349): Not factory mode
,D/FactoryTest( 5349): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 5349): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 5349): still no open session command from host, so toast
W/ContextImpl( 5349): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 5349): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
I/Timeline( 5349): Timeline: Activity_launch_request id:com.android.settings time:113121
E/PersonaManagerService( 1015): inState():  stateMachine is null !!
I/PersonaManagerService( 1015): PersonaId don't exist
I/ActivityManager( 1015): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.android.settings
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1015): mDVFSHelper.acquire(),
,D/PersonaManager( 1015): isKioskContainerExistOnDevice
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.android.settings
D/InputDispatcher( 1015): Focused application set to: xxxx
,D/InputDispatcher( 1015): Focus left window: 6163
,E/MTPRx   ( 5349): started activity for popup
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
,W/ResourcesManager( 5349): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 5349): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5349): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5349): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5349): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5349): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 5349): PREF_DONT_ASK_AGAIN : true
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,D/InputDispatcher( 1015): Focused application set to: xxxx
D/InputDispatcher( 1015): Focus entered window: 6163
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
,D/InputMethodManagerService( 1015): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/InputMethodManagerService( 1015): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@29f7979f attribute=null, token = android.os.BinderProxy@19c06c5f
,D/LocationManagerService( 1015): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1866): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1866): Tagging socket 82 with tag 1000120100000000{268440065,0} for uid -1, pid: 1866, getuid(): 10012
,D/SettingsReceiverActivity( 5349): dev.kiessupport is : TRUE
,D/PhoneWindow( 5349): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 5349): *FMB* installDecor flags : 8388610
,D/ActivityManager( 1015): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1015): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1015): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1015): handleActiveUserChange for user 0
D/PersonaManagerService( 1015): getPersonasForUser(): returning null!
,V/ActivityThread( 6163): updateVisibility : ActivityRecord{2aa26f60 token=android.os.BinderProxy@3734e192 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/Timeline( 6163): Timeline: Activity_idle id: android.os.BinderProxy@3734e192 time:113292
,D/PersonaManager( 1015): isKioskContainerExistOnDevice
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ServiceManager(  324): Waiting for service AtCmdFwd...,
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 1015): mDVFSHelper.release()
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  286): DCD OFF,
,E/SMD     (  286): DCD OFF
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms,
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF,
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 280
,I/PowerManagerService( 1015): [PWL] Off : 50s ago
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  286): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  286): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD OFF
,E/Watchdog( 1015): !@Sync 4,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...,
,E/SMD     (  286): DCD OFF,
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  286): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  286): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 75s ago,
,E/SMD     (  286): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate,
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 1015): !@Sync 5,
,I/ClearcutLoggerApiImpl( 1866): disconnect managed GoogleApiClient
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :8
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 105s ago
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  324): Waiting for service AtCmdFwd...,
,E/SMD     (  286): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  286): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  286): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  286): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1015): !@Sync 6,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1176): handleTimeUpdate
,D/SecKeyguardClockView( 1176): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1176): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1176): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1176): *** don't update sliding image ***
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  286): DCD OFF
,I/Atfwd_Sendcmd(  324): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  324): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  286): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 140s ago
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/Watchdog( 1015): !@Sync 7
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  286): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :8
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  324): Waiting for service AtCmdFwd...,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.,
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  286): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1015): Plugged,
I/MotionRecognitionService( 1015): mGripSensorEnabled= false,
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 1015): !@Sync 8
,I/PowerManagerService( 1015): [PWL] Off : 180s ago
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,I/ServiceManager(  324): Waiting for service AtCmdFwd...,
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  286): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,E/Watchdog( 1015): !@Sync 9
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.,
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  324): Waiting for service AtCmdFwd...,
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 225s ago
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.,
,E/SMD     (  286): DCD OFF
,D/TimaService( 1015): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1015): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1015): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1015): initializing...
,I/TLC_TIMA_PKM_initialize( 1015): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1015): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1015): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1015): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1015): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1015): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1015): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1015): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1015): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1015): Loaded image: APP id = 12
,I/TZ: qc_tlc_communication( 1015): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1015): Trustlet response is completed
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1015): !@Sync 10
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,I/Atfwd_Sendcmd(  324): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  324): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/jxcore-log( 6163): --= Surplus to requirements =--
I/jxcore-log( 6163): 
,I/jxcore-log( 6163): ****TEST TOOK:  ms ****
I/jxcore-log( 6163): 
I/jxcore-log( 6163): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6163): 
,D/AndroidRuntime( 6769): 
D/AndroidRuntime( 6769): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6769): CheckJNI is OFF
,D/AndroidRuntime( 6769): readGMSProperty: start
D/AndroidRuntime( 6769): readGMSProperty: already setted!!
D/AndroidRuntime( 6769): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6769): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6769): readGMSProperty: end
D/AndroidRuntime( 6769): addProductProperty: start
,E/AffinityControl( 6769): AffinityControl: registerfunction enter,
,D/AndroidRuntime( 6769): Calling main entry com.android.commands.pm.Pm,
,D/PackageManager( 1015): START PACKAGE DELETE: observer{336993451}
D/PackageManager( 1015): pkg{<packageName>}
D/PackageManager( 1015): user{0}
D/PackageManager( 1015): caller{2000}
D/PackageManager( 1015): flags{3}
D/PersonaManagerService( 1015): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 1015): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1015): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1015): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1015): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManagerService( 1015): deletePackage- pkg:com.test.thalitest, edmuserId:0,
D/PackageManager( 1015): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1015): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1015): getApplicationUninstallationEnabled
D/PackageManager( 1015): !@killApplicatoin: 10175, uninstall pkg
D/ApplicationPolicy( 1015): getApplicationUninstallationEnabled :  enabled true
,I/ActivityManager( 1015): Force stopping com.test.thalitest appid=10175 user=-1: uninstall pkg
,I/ActivityManager( 1015): Killing 6163:com.test.thalitest/u0a175 (adj 0): stop com.test.thalitest cause uninstall pkg
,W/PackageSettings( 1015): Skipping PackageSetting{2242b340 com.example.hello/10177} due to missing metadata
,I/WindowState( 1015): WIN DEATH: Window{86d46ac u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger(  256): id=14 Removed NainActivit (6/8)
,D/InputDispatcher( 1015): Focus left window: 6163
,I/ActivityManager( 1015):   Force finishing activity ActivityRecord{1b20f79e u0 com.test.thalitest/.MainActivity t3}
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
W/ActivityManager( 1015): mDVFSHelper.acquire()
,W/ActivityManager( 1015): Spurious death for ProcessRecord{21687f08 6163:com.test.thalitest/u0a175}, curProc for 6163: null
,I/ActivityManager( 1015): Force stopping com.test.thalitest appid=10175 user=0: pkg removed
,I/ActivityManager( 1015):   Force finishing activity ActivityRecord{1b20f79e u0 com.test.thalitest/.MainActivity t3 f}
,W/ActivityManager( 1015): Duplicate finish request for ActivityRecord{1b20f79e u0 com.test.thalitest/.MainActivity t3 f}
,E/SMD     (  286): DCD OFF
,W/ActivityManager( 1015): CustomStartingWindow se packge removed so remove capture also
,I/DBG_DM  ( 3087): [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,I/art     ( 5605): Explicit concurrent mark sweep GC freed 2390(140KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 972us total 29.237ms
,D/InputDispatcher( 1015): Focused application released
,I/DBG_DM  ( 3087): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 11
,E/SamsungIME( 1813): mOCRHelper is null
,I/InputReader( 1015): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1866): Ignoring removeGeofence because network location is disabled.
,I/DBG_DM  ( 3087): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,I/DBG_DM  ( 3087): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3087): [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 11
,I/DBG_DM  ( 3087): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,I/DBG_DM  ( 3087): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,D/RegisteredComponentCache( 1441): Collect Tech packages for Knox
,D/PersonaManager( 1441): isKioskContainerExistOnDevice
,I/DBG_DM  ( 3087): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/KLMS-2.5.183: ( 3556): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 11 16:24:35 GMT+01:00 2016
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/DBG_DM  ( 3087): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,I/KLMS-2.5.183: ( 3556): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1015): Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
,I/art     ( 6026): Explicit concurrent mark sweep GC freed 270(21KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 8MB/11MB, paused 726us total 96.894ms
,I/splitIntent( 1015): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,D/ApplicationPolicy( 1015): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3087): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 11
,E/Zygote  ( 6782): MountEmulatedStorage(),
E/Zygote  ( 6782): v2
I/libpersona( 6782): KNOX_SDCARD checking this for 10044,
I/art     ( 2004): Explicit concurrent mark sweep GC freed 7758(404KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 13MB/18MB, paused 3.089ms total 171.240ms
I/libpersona( 6782): KNOX_SDCARD not a persona
,I/DBG_DM  ( 3087): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,I/SELinux ( 6782): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/KLMS-2.5.183: ( 3556): KLMSIntentService(): onCreate()
I/ActivityManager( 1015): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=6782 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/DBG_DM  ( 3087): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
I/SELinux ( 6782): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/DBG_DM  ( 3087): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,E/SELinux ( 6782): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/DBG_DM  ( 3087): [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,I/DBG_DM  ( 3087): [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3556): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3556): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,E/Zygote  ( 6792): MountEmulatedStorage()
E/Zygote  ( 6792): v2
I/libpersona( 6792): KNOX_SDCARD checking this for 10094
I/libpersona( 6792): KNOX_SDCARD not a persona
,I/SELinux ( 6792): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1015): mCursor = null
,I/SELinux ( 6792): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6792): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6792 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,D/ActivityManager( 1015): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1015): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1015): postActiveUserChange, showWhenLocked: false
,I/DBG_DM  ( 3087): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3556): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,D/TimaKeyStoreProvider( 6782): TimaSignature is unavailable
,D/ActivityThread( 6782): Added TimaKeyStore provider
,E/Zygote  ( 6805): MountEmulatedStorage()
,I/libpersona( 6805): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6805): v2
I/libpersona( 6805): KNOX_SDCARD not a persona
I/SELinux ( 6805): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=6805 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
I/SELinux ( 6805): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6805): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
I/KLMS-2.5.183: ( 3556): KLMSIntentService(): PACKAGE_REMOVED
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 42111(3MB) AllocSpace objects, 90(1441KB) LOS objects, 33% free, 27MB/41MB, paused 4.291ms total 241.309ms
,I/art     ( 1015): WaitForGcToComplete blocked for 229.465ms for cause Explicit
,E/Zygote  ( 6823): MountEmulatedStorage()
I/libpersona( 6823): KNOX_SDCARD checking this for 10149
E/Zygote  ( 6823): v2
I/libpersona( 6823): KNOX_SDCARD not a persona
I/SELinux ( 6823): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 6823): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6823): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.5.183: ( 3556): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.5.183: ( 3556): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,D/TimaKeyStoreProvider( 6792): TimaSignature is unavailable
D/ActivityThread( 6792): Added TimaKeyStore provider
,I/ActivityManager( 1015): Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=6823 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  304): Explicit concurrent mark sweep GC freed 8723(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.514ms total 23.075ms
,D/TimaKeyStoreProvider( 6805): TimaSignature is unavailable
D/ActivityThread( 6805): Added TimaKeyStore provider
,D/PersonaManager( 1441): isKioskContainerExistOnDevice
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 617us total 16.734ms
,D/TimaKeyStoreProvider( 6823): TimaSignature is unavailable
D/ActivityThread( 6823): Added TimaKeyStore provider
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 607us total 16.990ms
,W/ResourcesManager( 6782): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6782): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6782): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 6782): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6782): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6782): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6782): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6782): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RegisteredServicesCache( 1441): empty dynamic service
,I/SurfaceFlinger(  256): id=16 createSurf (720x1280),1 flag=404, YUIInstallC
,D/StatusBarManagerService( 1015): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/InputDispatcher( 1015): Focus entered window: 3087
,D/StatusBarManagerService( 1015): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
,W/ResourcesManager( 6805): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/KLMS-2.5.183: ( 3556): KLMSIntentService(): listeningToPackageRemoved().END
,D/SRIB_DCS( 3087): log_dcs ThreadedRenderer::initialize entered! 
,V/ActivityThread( 3087): updateVisibility : ActivityRecord{2e97a907 token=android.os.BinderProxy@f9cb7aa {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,I/KLMS-2.5.183: ( 3556): KLMSIntentService(): onDestroy()
,D/EnterpriseDeviceManagerService( 1015): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1015): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1015): no available spell checker services found
,D/InputMethodManagerService( 1015): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/ThemeInfoUtil( 6823): getCurrentFestivalName is [null]
D/ThemeInfoUtil( 6823): isCurrentFestival = false
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/InputMethodManagerService( 1015): Got RemoteException sending setActive(false) notification to pid 6163 uid 10175
,I/Timeline( 3087): Timeline: Activity_idle id: android.os.BinderProxy@f9cb7aa time:325984
,W/ActivityManager( 1015): mDVFSHelper.release()
,I/Timeline( 1015): Timeline: Activity_windows_visible id: ActivityRecord{191934ef u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t2} time:325993
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,D/RCPManagerService( 1015): PackageReceiver onReceive()
,I/HarmonyEASService( 1015): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1015): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1015): PackageRemovalReceiver::onReceive Enter
,D/OTPFW   ( 1015): OtpDbHelper::getInstance New instance created
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/SamsungIME( 1813): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0,
,D/elm:15183( 6792): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15183( 6792): ELMEngine.ELMEngine( context ).
,D/OTPFW   ( 1015): DBIntegrity::getInstance - New instance created
,D/elm:15183( 6792): MDMBridge.setEnterpriseBridge()
,E/SQLiteLog( 6805): (284) automatic index on crash_info_summary(package_name_touched),
,D/OTPFW   ( 1015): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10175 container id = 0
,I/OTPFW   ( 1015): ProvisionData::getAllEntries Enter
,E/OTPFW   ( 1015): ProvisionData::getAllEntries Table is empty
,E/Zygote  ( 6848): MountEmulatedStorage()
E/Zygote  ( 6848): v2
I/libpersona( 6848): KNOX_SDCARD checking this for 10152
I/libpersona( 6848): KNOX_SDCARD not a persona
D/BackupManagerService( 1015): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1015): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1015): uID is 10175
V/EnterpriseBillingPolicy( 1015): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - enter
I/SELinux ( 6848): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - end - null
,I/SELinux ( 6848): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=6848 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 5986:com.wsomacp/u0a25 (adj 15): empty #31
,E/SELinux ( 6848): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1015): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1015): uID is 10175
V/EnterpriseBillingPolicy( 1015): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - enter
,D/SSRM:aZ ( 1015): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - start - com.test.thalitest
D/elm:15183( 6792): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - end - null
,W/NotificationService( 1015): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
D/KnoxTimeoutHandler( 1015): handleActiveUserChange for user 0
D/PersonaManagerService( 1015): getPersonasForUser(): returning null!
,V/AlarmManagerEXT( 1015): com.test.thalitest(10175) is removed.
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.aasaservice, hostingType: broadcast
,D/elm:15183( 6792): ElmAgentService : onCreate()
D/elm:15183( 6792): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:15183( 6792): MainReceiver.listeningToPackageRemoved()
D/elm:15183( 6792): MDMBridge.getInstance()
D/elm:15183( 6792): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:15183( 6792): MDMBridge.getAllLicenseInfoFromSDK()
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
D/TimaKeyStoreProvider( 6848): TimaSignature is unavailable
,D/ActivityThread( 6848): Added TimaKeyStore provider
,E/Zygote  ( 6863): MountEmulatedStorage()
I/libpersona( 6863): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6863): v2
I/libpersona( 6863): KNOX_SDCARD not a persona
I/SELinux ( 6863): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.samsung.aasaservice for broadcast com.samsung.aasaservice/.AASAUpdateReceiver: pid=6863 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 6863): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6863): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     ( 6805): Explicit concurrent mark sweep GC freed 9696(457KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 1.495ms total 95.284ms
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TaskPersister( 1015): removeObsoleteFile: deleting file=3_task.xml
,D/TaskPersister( 1015): removeObsoleteFile: deleting file=2_task.xml
D/TimaKeyStoreProvider( 6863): TimaSignature is unavailable
D/ActivityThread( 6863): Added TimaKeyStore provider
,D/BadgeProvider( 5955): sendNotify entered. [uri] : content://com.sec.badge/apps
,D/BadgeProvider( 5955): sendNotify, [notify] : null
,D/BadgeProvider( 5955): update, [uri] : content://com.sec.badge/apps
D/BadgeProvider( 5955): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 5955): update, [UpdateCount] : 1
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/elm:15183( 6792): ElmAgentService : onDestroy().
,D/StatusBar( 1176): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1176): Icon Only
,I/StatusBar( 1176): Icon Only
,D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1176): Icon Only
I/StatusBar( 1176): Icon Only
,D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,E/Zygote  ( 6882): MountEmulatedStorage(),
E/Zygote  ( 6882): v2
I/libpersona( 6882): KNOX_SDCARD checking this for 1000
I/libpersona( 6882): KNOX_SDCARD not a persona
I/SELinux ( 6882): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6882 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 6026:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,I/ActivityManager( 1015): Killing 6007:com.sec.android.app.soundalive/u0a53 (adj 15): empty #32
I/SELinux ( 6882): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6882): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/PersonaManager( 1015): isKioskContainerExistOnDevice
,D/TimaKeyStoreProvider( 6882): TimaSignature is unavailable
,E/SQLiteLog( 6848): (284) automatic index on shooting_modes(title_id)
,D/ActivityThread( 6882): Added TimaKeyStore provider
,D/PanelView( 1176): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/AASAservice-UpdateReceiver( 6863): AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,W/System.err( 6863): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 6863): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
W/System.err( 6863): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
W/System.err( 6863): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 6863): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 6863): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 6863): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6863): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 6863): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 6863): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6863): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6863): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 6863): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/ActivityManager( 1015): Killing 5931:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty #31
,D/NearbySource( 6782): Nearby Source Create!
,D/NearbyContext( 6782): Nearby Context Create!
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/PCWCLIENTTRACE_PushUtil( 5795): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5795): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5795): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5795): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,E/Zygote  ( 6898): MountEmulatedStorage()
E/Zygote  ( 6898): v2
,I/libpersona( 6898): KNOX_SDCARD checking this for 10156
I/libpersona( 6898): KNOX_SDCARD not a persona
,I/SELinux ( 6898): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=6898 uid=10156 gids={50156, 9997} abi=armeabi-v7a,
,W/ResourceType( 1015): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
I/SELinux ( 6898): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
W/ContextImpl( 6782): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource( 6782): Samsung link source created
E/SELinux ( 6898): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/art     ( 1015): Explicit concurrent mark sweep GC freed 16083(934KB) AllocSpace objects, 6(102KB) LOS objects, 33% free, 28MB/42MB, paused 6.256ms total 472.402ms
,W/ContextImpl( 6882): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 6898): TimaSignature is unavailable
,D/ActivityThread( 6898): Added TimaKeyStore provider
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6914): MountEmulatedStorage()
E/Zygote  ( 6914): v2
I/libpersona( 6914): KNOX_SDCARD checking this for 10032
I/libpersona( 6914): KNOX_SDCARD not a persona
,I/SELinux ( 6914): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6914 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/SELinux ( 6914): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1015): Killing 5874:com.google.android.apps.docs/u0a91 (adj 15): empty #31
,E/SELinux ( 6914): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 6914): TimaSignature is unavailable
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ActivityThread( 6914): Added TimaKeyStore provider
,E/Zygote  ( 6930): MountEmulatedStorage()
,E/Zygote  ( 6930): v2
I/libpersona( 6930): KNOX_SDCARD checking this for 1000
I/libpersona( 6930): KNOX_SDCARD not a persona
,I/SELinux ( 6930): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6930): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6930 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 6930): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/PackageManager( 1015): delete codoeFile: 
,D/AASAuninstall( 1015): userId = 0, info.removedAppID = -1, info.uid = 10175, packageName = com.test.thalitest
,I/AASA_removePackage( 1015): UID=10175 Target=com.test.thalitest
,I/ActivityManager( 1015): Killing 6106:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,I/TapandpayWidget:TapandpayAppWidgetProvider( 6898): onReceive()
D/TapandpayWidget:TapandpayAppWidgetProvider( 6898): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,D/PackageManager( 1015): result of delete: 1{336993451}
,I/TapandpayWidget:Utils( 6898): Clear T&P info.
,D/TapandpayWidget:TapandpayAppWidgetProvider( 6898): Widget is not attached.
,D/TimaKeyStoreProvider( 6930): TimaSignature is unavailable
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
D/AndroidRuntime( 6769): Shutting down VM
D/ActivityThread( 6930): Added TimaKeyStore provider
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6947): MountEmulatedStorage()
I/libpersona( 6947): KNOX_SDCARD checking this for 10160
E/Zygote  ( 6947): v2
I/libpersona( 6947): KNOX_SDCARD not a persona
,I/SELinux ( 6947): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/SELinux ( 6947): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,W/ResourcesManager( 1015): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1015): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 1015): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/SELinux ( 6947): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager( 1015): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=6947 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 6129:com.samsung.helphub/1000 (adj 15): empty #31
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 6947): TimaSignature is unavailable
,D/ContactProvider( 6782): getAllContactInfoList Start
D/ActivityThread( 6947): Added TimaKeyStore provider
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/PackagesMonitor( 6782): PackagesMonitor onReceive :com.test.thalitest
,I/FeatureConfig( 6914): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,W/ResourcesManager( 6930): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/ResourcesManager( 6947): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/RCPManager( 6930):  in createShortcut() for packageName: com.test.thalitest userId0
,D/RCPManagerService( 1015):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1015): queryAllProviders():  providerCallBack is not register for 0
,E/Zygote  ( 6967): MountEmulatedStorage()
E/Zygote  ( 6967): v2
I/libpersona( 6967): KNOX_SDCARD checking this for 10035
I/libpersona( 6967): KNOX_SDCARD not a persona
,I/SELinux ( 6967): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6967): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1015): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6967 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
E/SELinux ( 6967): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Killing 6316:com.android.email/u0a145 (adj 15): empty #31
D/[0]UMC:UMCContentProvider( 6947): @onCreate
,W/ResourcesManager( 6914): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6914): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6914): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6914): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6914): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6914): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/UsbSettingsManager( 1015): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 1015): onPackageRemoved : com.test.thalitest
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/[0]UMC:Core( 6947): onCreate(): 
W/ResourcesManager( 6914): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 6914): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6914): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6914): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6914): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/[0]UMC:Core( 6947): @isManagedProfileUser
W/ResourcesManager( 6914): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/[0]UMC:Core( 6947): userId: 0
,W/libprocessgroup( 1015): failed to open /acct/uid_10025/pid_5986/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10053/pid_6007/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10057/pid_6026/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10038/pid_5931/cgroup.procs: No such file or directory
D/[0]UMC:Core( 6947): userInfo: UserInfo{0:Thali Test:13}
D/[0]UMC:Core( 6947): userInfo.isManagedProfile() : false
,W/libprocessgroup( 1015): failed to open /acct/uid_10100/pid_6106/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10091/pid_5874/cgroup.procs: No such file or directory
,E/Zygote  ( 6981): MountEmulatedStorage()
I/libpersona( 6981): KNOX_SDCARD checking this for 10046
E/Zygote  ( 6981): v2
I/libpersona( 6981): KNOX_SDCARD not a persona
I/SELinux ( 6981): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6981): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6981): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6967): TimaSignature is unavailable
,D/ActivityThread( 6967): Added TimaKeyStore provider
,I/ActivityManager( 1015): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=6981 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 6414:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,I/ActivityManager( 1015): Killing 6470:com.sec.android.cloudagent/u0a2 (adj 15): empty #31
W/ResourcesManager( 6914): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6914): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6914): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 6981): TimaSignature is unavailable
,D/ActivityThread( 6981): Added TimaKeyStore provider,
,W/ResourcesManager( 6914): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6914): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6914): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/Zygote  ( 6997): MountEmulatedStorage()
E/Zygote  ( 6997): v2
I/libpersona( 6997): KNOX_SDCARD checking this for 10091
I/libpersona( 6997): KNOX_SDCARD not a persona
,I/SELinux ( 6997): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6997 uid=10091 gids={50091, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6997): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6997): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/[0]UMC:DeviceInfo( 6947): USA==US==
,W/ResourcesManager( 6914): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6914): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6914): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6914): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6914): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 6914): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6914): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6914): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/art     ( 6769): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,W/ResourcesManager( 6914): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.,
W/ResourcesManager( 6914): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6914): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6981): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 6981): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6981): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6981): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6981): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6981): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 6997): TimaSignature is unavailable
,D/ActivityThread( 6997): Added TimaKeyStore provider
,D/ContactProvider( 6782): getAllContactInfoList End
,I/syncContacts( 6782): thread: 1148, sync time = 241
,W/ResourcesManager( 6914): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 6914): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6914): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6914): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6914): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/SQLiteLog( 6805): (284) automatic index on crash_info_summary(package_name_touched)
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_6129/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10145/pid_6316/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10002/pid_6470/cgroup.procs: No such file or directory
,W/ResourcesManager( 6914): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6914): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6914): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6914): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_6414/cgroup.procs: No such file or directory
,D/BadgeProvider( 5955): sendNotify entered. [uri] : content://com.sec.badge/apps
,D/BadgeProvider( 5955): sendNotify, [notify] : null
,D/BadgeProvider( 5955): update, [uri] : content://com.sec.badge/apps
,D/BadgeProvider( 5955): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 5955): update, [UpdateCount] : 1
,D/Launcher.Model( 1477): reloadBadges entered.
D/Launcher.Model( 1477): reloadBadges entered.
,E/SPPClientService( 6967): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 6967): [PushClientApplication] Push log off : This is Ship build version
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.sdk.samsunglink, hostingType: broadcast
,D/USER_AGENT( 6947): UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/SPPClientService( 6967): PushLog.txt file is not deleted.
D/SPPClientService( 6967): PushLog.txt file is not deleted.
D/SPPClientService( 6967): ============PushLog. stop!
,D/[0]UMC:AdminManager( 6947): init - start
,W/ResourcesManager( 6914): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.,
W/ResourcesManager( 6914): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6914): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.,
W/ResourcesManager( 6914): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6914): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Zygote  ( 7016): MountEmulatedStorage()
,I/libpersona( 7016): KNOX_SDCARD checking this for 10038,
,E/Zygote  ( 7016): v2,
I/libpersona( 7016): KNOX_SDCARD not a persona,
,W/FileUtils( 6967): Failed to chmod(/data/data/com.sec.spp.push/databases/push_noti_db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
I/SELinux ( 7016): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 7016): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1015): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=7016 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,E/SELinux ( 7016): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/Mms/MmsApp( 6981): [start]    onCreate() consume time = 0.0
,I/art     (  304): Explicit concurrent mark sweep GC freed 8744(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 639us total 21.656ms
,D/[0]UMC:AdminManager( 6947): loadAdmins
,D/TimaKeyStoreProvider( 7016): TimaSignature is unavailable
,D/ActivityThread( 7016): Added TimaKeyStore provider
,I/ActivityManager( 1015): Killing 6433:com.samsung.android.service.travel/u0a159 (adj 15): empty #31
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 702us total 16.984ms
,W/ResourcesManager( 6914): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 6914): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 7016): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7016): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/[0]UMC:AdminManager( 6947): init - end
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 604us total 17.036ms
D/GSLBManager( 6947): migrateStoredUrlFromOldPref,
,W/ResourcesManager( 6914): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6914): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6914): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6914): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6914): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6914): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
E/PhotosPlugin( 6997): Loading PhotosPlugin
,D/GSLBManager( 6947): migrateStoredUrlFromOldPref : Migration Not Needed
,D/[0]UMC:UMCAdmin( 6947): deactivateUMCAdminIfNotRequired : -1
E/[0]UMC:Utils( 6947): Admin not found in package com.samsung.knoxpb.mdm
E/[0]UMC:Utils( 6947): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
,D/[0]UMC:UMCAdmin( 6947): deactivateUMCAdmin : -1
,D/[0]UMC:UMCAdmin( 6947): isContainer : 0
,D/EnterpriseDeviceManagerService( 1015): isManagedProfileUser(): userId = 0
,W/ResourcesManager( 6914): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 6914): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.

```
